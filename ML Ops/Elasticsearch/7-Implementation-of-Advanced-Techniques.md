## Implementation of Advanced Techniques

### Nested Queries in Elasticsearch: Searching Inside Nested Objects

The nested query searches nested field objects as if they were indexed as separate documents. If an object matches the search, the nested query returns the root parent document.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-nested-query.html)

### Script Queries in Elasticsearch: Customizing Query Behavior with Scripts

Filters documents based on a provided script. The script query is typically used in a filter context.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-script-query.html)

### Join Queries in Elasticsearch: Searching Across Related Documents

Performing full SQL-style joins in a distributed system like Elasticsearch is prohibitively expensive. Instead, Elasticsearch offers two forms of join which are designed to scale horizontally.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/7.17/joining-queries.html)