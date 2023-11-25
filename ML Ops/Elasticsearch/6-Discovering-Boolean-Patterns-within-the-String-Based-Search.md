## String Based Search

### Introduction to String Based Search

The search API allows you to execute a search query and get back search hits that match the query. The query can either be provided using a simple query string as a parameter, or using a request body.

[Read more](https://mindmajix.com/elasticsearch/searching-data)

### Custom Attributes for Query Based Search

The query string is parsed into a series of terms and operators. A term can be a single word — quick or brown — or a phrase, surrounded by double quotes — "quick brown" — which searches for all the words in the phrase, in the same order.

Operators allow you to customize the search.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html#query-string-syntax)

### Implementation of Query String

You can use the query_string query to create a complex search that includes wildcard characters, searches across multiple fields, and more. While versatile, the query is strict and returns an error if the query string includes any invalid syntax.

[Read more](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html)