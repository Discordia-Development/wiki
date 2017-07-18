<!-- TITLE: Internals -->
<!-- SUBTITLE: Stuff about Discord's internal systems -->

# Discord Internals

Discord's stack as we know it, gathered from Discord's engineering articles and some other stuff:
 - [Cassandra](http://cassandra.apache.org/) for storage(they used [MongoDB](https://www.mongodb.com/) in the first 2 months of Discord).
 - [Elixir](https://elixir-lang.org/) for the `sessions`, `presence` and `guild` clusters.
 - [Python](https://www.python.org/) for HTTP/REST API.
 - [Go](https://golang.org/) for the embed servers and logging
 - [Loqui](https://github.com/hammerandchisel/loqui) for node communication.
 - [Punt](https://github.com/hammerandchisel/punt) In favour of [Logstash](https://github.com/elastic/logstash) for Discord logging.
 - [Elasticsearch](https://github.com/elastic/elasticsearch) that powers the search feature for users and powers Discord logging.
   - Sources about logging: Punt and [this issue](https://github.com/elastic/elasticsearch/issues/20354)
   - There is an article in the works that describes Discord's logging in detail, Soon:tm:

