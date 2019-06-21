---
question: "How do I prevent a query from consuming too many resources?"
draft: true
---

A generalization of [ProtectionFromDeepNestedQueriesAttacks](https://github.com/graphql/faq/blob/master/proposals/ProtectionFromDeepNestedQueriesAttacks.md).
Answer is something along the lines:
* Use persisted operations if you can get away with it
* Query complexity limits
* Query depth limits
* Input document size limits
* Input variable size limits
* Timeouts as a last resort
