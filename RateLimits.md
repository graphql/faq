---
question: "How should GraphQL API rate limiting take into account requests with highly variable cost?"
draft: true
---

Add cost based rate limits i.e. aggregate query complexity per unit of time. Request level
rate limits are still useful though e.g. to prevent spamming an API with lots of invalid
GraphQL queries.
