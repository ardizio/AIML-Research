## Multi-match Querying Mechanism

### Match Phrase & Match Phrase Prefix

Returns documents that contain the words of a provided text, in the same order as provided. The last term of the provided text is treated as a prefix, matching any words that begin with that term.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-match-query-phrase-prefix.html)

### Introduction to Multi-Match Query

The multi_match query builds on the match query to allow multi-field queries

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-multi-match-query.html)

### Relevance Score

The relevance score is a positive floating point number, returned in the _score metadata field of the search API. The higher the _score, the more relevant the document. While each query type can calculate relevance scores differently, score calculation also depends on whether the query clause is run in a query or filter context.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-filter-context.html#scoring)

### Implementation of Multi-match Query Patterns

The multi-match (multi_match) query, as the name suggests, searches the query across multiple fields. For example, if we want to search for the word Java across the three fields title, synopsis, and tags, then the multi_matchquery is the answer. The following listing shows a query that searches for Java across these three fields.

[Read more](https://mkonda007.medium.com/elasticsearch-in-action-multi-match-multi-match-queries-5a29ad7efe0)