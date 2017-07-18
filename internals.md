<!-- TITLE: Internals -->
<!-- SUBTITLE: Stuff about Discord's internal systems -->

# Discord's stack

Discord's stack as we know it, gathered from Discord's engineering articles and some other stuff:
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
