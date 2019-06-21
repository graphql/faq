---
question: "REST APIs have HTTP verbs, urls and statuses which are very convenient for monitoring. How do I monitor 
GraphQL APIs if there's a single HTTP endpoint?"
draft: true
---

The answer is highly dependent on the monitoring framework but hopefully we can provide some high level guidance 
such as using operation names (which works well if you control the clients) and client identifiers in metrics.
