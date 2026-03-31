---
title:      "Loki"
quadrant:   service
ring:       adopt
tags:       [OBSERVABILITY, MONITORING, PLATFORM-ENGINEERING]
featured:   true
---

[Loki](https://grafana.com/oss/loki/) is a horizontally scalable, highly available log aggregation system developed by Grafana Labs. Unlike traditional log management systems, Loki does not index the contents of the log entries but only the metadata (labels), making it cost-effective and simple to operate. Loki integrates natively with Grafana for log visualization and with Prometheus for alerting, forming part of the PLG (Prometheus, Loki, Grafana) observability stack deployed in Kubernetes clusters. It has been used to aggregate and query logs from Kubernetes workloads across namespaces, providing centralized log visibility alongside Grafana dashboards. Teams already using Grafana and Prometheus should evaluate Loki as their primary log aggregation solution.
