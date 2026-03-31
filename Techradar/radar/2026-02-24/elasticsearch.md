---
title:      "Elasticsearch"
quadrant:   service
ring:       trial
tags:       [OBSERVABILITY, MONITORING]
featured:   true
---

[Elasticsearch](https://www.elastic.co/elasticsearch) is a distributed, RESTful search and analytics engine built on Apache Lucene, commonly used as the core of the ELK stack (Elasticsearch, Logstash, Kibana) for centralized log management and full-text search. Elasticsearch provides near real-time indexing, powerful query DSL, and horizontal scalability, making it well suited for large-scale log aggregation and analysis. It has been used as part of observability stacks for monitoring infrastructure and application logs. Teams evaluating log aggregation should compare the ELK stack with the lighter-weight PLG stack (Prometheus, Loki, Grafana), which is more operationally simple and cost-effective for Kubernetes-native deployments, reserving Elasticsearch for use cases requiring full-text search or complex log analytics.
