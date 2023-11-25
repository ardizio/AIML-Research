## About Fuzziness

### Introduction to Query Analytics

ESQL is more than a language. It represents a significant investment in new compute capabilities within Elasticsearch. To achieve both the functional and performance requirements for ESQL, it is necessary to build an entirely new compute architecture. ESQL search, aggregation, and transformation functions are directly executed within Elasticsearch itself. Query expressions are not transpiled to QueryDSL for execution. Rather, we have built native support for ESQL functions within Elasticsearch.

ESQL introduces distributed compute capabilities to users in disparate roles and with varying skill levels. These compute capabilities enable ESQL to simplify user workflows in several key ways.

[Read more](https://www.elastic.co/blog/introduction-to-esql-new-query-language-flexible-iterative-analytics)


### Fuzziness, LED vs DLED

Fuzziness is the heart of Fuzzy Query.

The value that we pass to this parameter is the maximum distance allowed.

There are two types of value that we can pass, an integer for exact maximum distance and "AUTO".

The "AUTO" value allows the fuzziness in the query to be dynamic.

[Read more](https://hackernoon.com/how-to-use-fuzzy-query-matches-in-elasticsearch-dh1h3167)

### Fuzzy Searching using Intervals Query

The fuzzy rule matches terms that are similar to the provided term, within an edit distance defined by Fuzziness. If the fuzzy expansion matches more than 128 terms, Elasticsearch returns an error.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-intervals-query.html#intervals-fuzzy)

### Fuzzy Searching using Match Query

Match Query with fuzziness parameter is more preferable than Fuzzy Query. The analyzer in the query will analyze your query before searching it into the Inverted Index.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-match-query.html)

### Special Parameter for the Search Field

The search_fields parameter restricts a query to search only specific fields.

Restricting fields will result in faster queries, especially for schemas with many text fields.

[Read more](https://www.elastic.co/guide/en/app-search/current/search-fields-weights.html)