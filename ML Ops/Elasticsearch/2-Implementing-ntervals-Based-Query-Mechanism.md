## Further reading on implementation

### Match Query and its implementation

Returns documents that match a provided text, number, date or boolean value. The provided text is analyzed before matching.

The match query is the standard query for performing a full-text search, including options for fuzzy matching.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-match-query.html#query-dsl-match-query)

### Intervals query rules

The intervals query uses matching rules, constructed from a small set of definitions. These rules are then applied to terms from a specified field.

The definitions produce sequences of minimal intervals that span terms in a body of text. These intervals can be further combined and filtered by parent sources.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-intervals-query.html)

### Implementing Intervals Query Using Filters

A filter in Elasticsearch is all about applying some conditions inside the query that are used to narrow down the matching result set.

[Read more](https://opster.com/guides/elasticsearch/glossary/elasticsearch-filter/)