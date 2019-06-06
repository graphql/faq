---
author: @leebyron
question: "What is a _GraphQL Query_?"
term: graphql query
draft: true
---

A GraphQL Query is a request for specific data provided by a GraphQL Service
written in the GraphQL language.

Here's a simple example which asks for my name, and the names of 3 of my friends:

```graphql
{
  me {
    name
    friends(first: 3) {
      name
    }
  }
}
```

Once sent to a GraphQL Service, this might return the result:


```json
{
  "data": {
    "me": {
      "name": "Lee Byron",
      "friends": [
        { "name": "Ash Huang" },
        { "name": "Nick Schrock" },
        { "name": "Dan Schafer" },
      ]
    }
  }
}
```

Some important properties of GraphQL Queries this example helps illustrate:

## A GraphQL Query describes the shape of the resulting data

TK

## A GraphQL Query can access data across many "resources"

TK

## Query behavior can change by using field arguments

TK

# Relevant Links

  * [Learn about the GraphQL Query Language](https://graphql.org/learn/queries/)
  * [GraphQL Language Specification](https://graphql.github.io/graphql-spec/June2018/#sec-Language.Document)
