---
title:      "Docker Swarm"
quadrant:   platform
ring:       hold
tags:       [ORCHESTRATOR, DOCKER]
featured:   false
---

[Docker Swarm](https://docs.docker.com/engine/swarm/) is Docker's native container orchestration mode that enables clustering and scheduling of Docker containers across multiple hosts. While Docker Swarm was a popular early orchestration solution due to its simplicity, it has been largely superseded by Kubernetes, which provides far superior scalability, ecosystem support, and cloud-native integrations. Docker Swarm should not be used for new projects. Teams still running Docker Swarm workloads should plan migration to Kubernetes (AKS or EKS) to benefit from the rich ecosystem of platform tooling, observability, and policy enforcement available in the Kubernetes landscape.
