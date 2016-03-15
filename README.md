# ElasticSearch examples
I've lined up a bunch of examples to showcase the features and the sheer power of [ElasticSearch](https://www.elastic.co/products/elasticsearch). A lot of the information is based on ["ElasticSearch, The Definitive Guide"](https://www.elastic.co/guide/en/elasticsearch/guide/current/index.html)

## Installing
Installing ElasticSearch is quite simple, go to [the installation page of the ElasticSearch guide](https://www.elastic.co/guide/en/elasticsearch/guide/current/running-elasticsearch.html).

* Install both ElasticSearch & the Sense plugin for Kibana.
* Run ElasticSearch `./bin/elasticsearch`
* Run Kibana `./bin/kibana`
* Access Kibana by using [http://localhost:5601](http://localhost:5601)
* Use the Sense plugin by accessing [http://localhost:5601/app/sense](http://localhost:5601/app/sense)
* Use [http://localhost:9200](http://localhost:9200) as the default ElasticSearch server

## Exercise 1: the basics
Exercise 1 is very simple and the goal is to get the hang of the ElasticSearch RESTFul interface.

Topics:

* Navigating to the ElasticSearch landing page
* Searching all documents
* Counting documents
* Adding documents to the index
* Full document updates
* Partial document updates
* Retrieve individual documents
* Searching all documents for a specific index

[Load exercise 1 in Sense](http://localhost:5601/app/sense?load_from=https://raw.githubusercontent.com/ThijsFeryn/elasticsearch_tutorial/master/1_basics.json)

## Exercise 2: load data in bulk
In exercise 2 we will be indexing a lot of data. To improve the performance, we're doing this in bulk.

This data contains information from the [Combell blog](http://blog.combell.com). I've indexed the following information:

* Title
* Author
* Date
* Categories
* Language
* GUID

This data will be used in the other exercises

[Load the blog data in bulk via Sense](http://localhost:5601/app/sense?load_from=https://raw.githubusercontent.com/ThijsFeryn/elasticsearch_tutorial/master/2_blog_data_bulk.json)
