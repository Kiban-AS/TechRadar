---
title:      "Traefik"
quadrant:   platform
ring:       adopt
tags:       [PLATFORM-ENGINEERING, ORCHESTRATOR]
featured:   true
---

[Traefik](https://traefik.io/traefik/) is a modern, cloud-native reverse proxy and ingress controller designed specifically for dynamic container environments. Traefik automatically discovers services and configures routing rules by watching container orchestrators (Kubernetes, Docker) for changes, eliminating the need for manual reload cycles. It supports HTTP, HTTPS, TCP, and UDP routing, built-in Let's Encrypt integration, middleware for authentication and rate limiting, and a web dashboard for real-time traffic visibility. Compared to Ingress NGINX, Traefik offers a more dynamic and developer-friendly configuration model with lower operational overhead for environments with frequent service changes. Teams evaluating ingress controllers for new Kubernetes platforms should assess Traefik alongside Ingress NGINX, particularly when looking for a more modern, API-driven approach to traffic management and observability.
