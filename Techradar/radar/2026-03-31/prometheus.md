---
title:      "Prometheus"
quadrant:   service
ring:       adopt
tags:       [OBSERVABILITY, MONITORING, PLATFORM-ENGINEERING]
featured:   true
---

[Prometheus](https://prometheus.io/) is an open-source systems monitoring and alerting toolkit originally built at SoundCloud and now a CNCF graduated project. It collects and stores time-series metrics, supports a powerful query language (PromQL), and integrates natively with Kubernetes workloads through service discovery and pod annotations. Prometheus is the de facto standard for metrics collection in the Kubernetes ecosystem and is used as the primary metrics backend in the observability stack, feeding data to Grafana dashboards and alert managers. It has been deployed to provide platform-wide visibility across namespaces and clusters, supporting both infrastructure and application-level metrics. Prometheus is strongly recommended for any team operating Kubernetes in production.
