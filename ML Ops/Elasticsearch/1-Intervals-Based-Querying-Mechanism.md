## Intervals Based Querying Mechanism

### Introduction to Elasticsearch

Elasticsearch is a distributed, free and open search and analytics engine for all types of data, including textual, numerical, geospatial, structured, and unstructured. Elasticsearch is built on Apache Lucene and was first released in 2010 by Elasticsearch N.V. (now known as Elastic). Known for its simple REST APIs, distributed nature, speed, and scalability, Elasticsearch is the central component of the Elastic Stack, a set of free and open tools for data ingestion, enrichment, storage, analysis, and visualization. Commonly referred to as the ELK Stack (after Elasticsearch, Logstash, and Kibana), the Elastic Stack now includes a rich collection of lightweight shipping agents known as Beats for sending data to Elasticsearch.

[Read more](https://www.elastic.co/elasticsearch/)

### Elasticsearch architecture

Elasticsearch is a distributed search engine used for full-text search. In this section, you will understand the physical architecture of Elasticsearch. In which we will see how documents are distributed across the physical or virtual machine. Along with it, we will also see how machines work together to form a cluster.

In Elasticsearch architecture, node and cluster play an important role. These are the center of Elasticsearch architecture. Each node in a cluster handles the HTTP request for a client who wants to send the request to the cluster.

[Read more on JavatPoint](https://www.javatpoint.com/elasticsearch-architecture)

### Installing & Configuring Elasticsearch

In the below article, you will learn how to install and configure Elasticsearch on your system.

[Read more on installation and config.](https://www.elastic.co/guide/en/elasticsearch/reference/current/setup.html)

### Full Text Search

The full text queries enable you to search analyzed text fields such as the body of an email. The query string is processed using the same analyzer that was applied to the field during indexing.

[Read more on Fulltext Search](https://www.elastic.co/guide/en/elasticsearch/reference/current/full-text-queries.html#full-text-queries)

### Basic search operations with Elasticsearch API

This API is used to search content in Elasticsearch. A user can search by sending a get request with query string as a parameter or they can post a query in the message body of post request. Mainly all the search APIS are multi-index, multi-type.

[Read more on API](https://www.tutorialspoint.com/elasticsearch/elasticsearch_search_apis.htm)

### Full Text Queries and Intervals Query

The intervals query uses matching rules, constructed from a small set of definitions. These rules are then applied to terms from a specified field.

The definitions produce sequences of minimal intervals that span terms in a body of text. These intervals can be further combined and filtered by parent sources.

[Read more on Full Text Queries and Intervals Query](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-intervals-query.html)