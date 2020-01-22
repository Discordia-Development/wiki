---
title: Technology
description: Stuff about Discord's internal systems, with some undocumented situations as well
published: true
date: 2020-01-09T05:39:52.841Z
tags: 
---

# Discord's "stack"

Technologies Discord uses to provide the service as we know it, gathered from [Discord's engineering articles](https://blog.discordapp.com/tagged/engineering) and some other stuff:
 - [Cassandra](http://cassandra.apache.org/) for storage(they used [MongoDB](https://www.mongodb.com/) in the first 2 months of Discord, [source](https://blog.discordapp.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)).
 - [Elixir](https://elixir-lang.org/) for the `sessions`, `presence` and `guild` clusters(Gateway API, [source](https://blog.discordapp.com/scaling-elixir-f9b8e1e7c29b)).
 - [Python](https://www.python.org/) for HTTP/REST API.
 - [Go](https://golang.org/) for the embed servers and one element of their logging(see [Punt](https://github.com/hammerandchisel/punt))
 - [Loqui](https://github.com/hammerandchisel/loqui) for node communication.
 - [Punt](https://github.com/hammerandchisel/punt) In favour of [Logstash](https://github.com/elastic/logstash) for logging.
 - [Elasticsearch](https://github.com/elastic/elasticsearch) that powers the search feature for users and powers logging.
   - Sources about logging: Punt and [this issue](https://github.com/elastic/elasticsearch/issues/20354)
   - [Source about message search](https://blog.discordapp.com/how-discord-indexes-billions-of-messages-e3d5e9be866f)
   - There is an article in the works that describes Discord's logging in detail, Soon:tm:
 - [Google's Cloud Platform](https://cloud.google.com/) for their infrastructure, [source](https://status.discordapp.com/incidents/rhvp2tn7g0zc)
 - [Cloudflare](https://www.cloudflare.com/) as a proxy to their nodes

# Clusters
All the clusters were made to be fault tolerant(read: "not crash") and handle cases where a node of them goes out
or when a cluster goes down and wait a bit before requesting from the cluster again.

## Sources
 - [Description of a full outage where they had to reboot everything](https://status.discordapp.com/incidents/dj3l6lw926kl)
 - [`sessions` and `presence` clusters get rebooted due to a host error in a `guild` node](https://status.discordapp.com/incidents/ywdwttd6b0hg)
 - [Repeating message sends due to errors in the `push` cluster](https://status.discordapp.com/incidents/93kyyctg0wf3)
 - ["furiously" spinning an nginx cluster due to an error in GCP's load balancer](https://status.discordapp.com/incidents/rhvp2tn7g0zc)

## Clusters
 - `sessions` cluster
   - Manages multiple sessions per node in the cluster(as Elixir allows it).
   - Relationships:
     - Requests from the `guild` cluster to gather guild data for your `READY` event.
     - Requests from the `presence` cluster for the same reason.
 - `presence` cluster
   - Manages your "playing status", smaller than `sessions`.
   - Gets a high throughput since users join in and request presence data, and users go out and write presence data.
- `guild` cluster
  - Manages real time state for guilds and guild data.
- `push` cluster
  - Manages push notifications to users.
# Informations about Resuming

There is some stuff regarding the resume logic for clients:
 - Session nodes have a message deque, that gets filled with each event your client receives
   - If you want to resume from a sequence number that isn't in the deque, your session gets invalidated

 - When Discord goes down, you might get a `PRESENCES_REPLACE` event
    - That is sent when your session node notices your client is lagging behind new presence updates.