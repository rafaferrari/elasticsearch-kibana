# elasticsearch-kibana 

Use the searching/aggregation capabilities of Elasticseach and the visualization power of Kibana.
This compose will run with the latest version of elasticsearch and kibana images.

Based on the official images:

* [elasticsearch](https://registry.hub.docker.com/_/elasticsearch/)
* [kibana](https://registry.hub.docker.com/_/kibana/)

# Requirements

1. Install [Docker](http://docker.io).
2. Install [Docker-compose](http://docs.docker.com/compose/install/).
3. Clone this repository

# Usage

Start the stack using *docker-compose*:

```bash
$ docker-compose up
```

You can also choose to run it in background (detached mode):

```bash
$ docker-compose up -d
```

Then you can access Kibana UI by hitting http://localhost:5601 with a web browser.

By default, the stack exposes the following ports:
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana

# About

Written by Rafael Lopes Ferrari
