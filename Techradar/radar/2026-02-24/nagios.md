---
title:      "Nagios"
quadrant:   service
ring:       hold
tags:       [MONITORING, OBSERVABILITY]
featured:   false
---

[Nagios](https://www.nagios.org/) is one of the earliest open-source IT infrastructure monitoring tools, capable of monitoring hosts, services, and network devices and sending alerts on failures. While Nagios established many foundational concepts in infrastructure monitoring, it has been superseded by modern observability platforms that support dynamic, cloud-native environments. Nagios lacks native Kubernetes integration, requires significant manual configuration, and does not provide the metrics, tracing, or log aggregation capabilities expected from modern observability stacks. Nagios should not be adopted for new monitoring initiatives. Teams should migrate to Prometheus and Grafana for metrics, Loki for logs, and a modern alerting stack rather than extending Nagios coverage.
