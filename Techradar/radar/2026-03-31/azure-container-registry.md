---
title:      "Azure Container Registry"
quadrant:   platform
ring:       adopt
tags:       [PLATFORM-ENGINEERING, DOCKER, AZURE]
featured:   true
---

[Azure Container Registry (ACR)](https://azure.microsoft.com/en-us/products/container-registry) is a managed, private Docker registry service on Azure for storing and managing container images and other OCI artifacts. ACR integrates natively with AKS, Azure DevOps, and GitLab for seamless image pull authentication, supports geo-replication for high availability, and provides built-in vulnerability scanning via Microsoft Defender for Containers. ACR is used as the primary container registry for AKS-hosted workloads, providing a secure and policy-compliant distribution layer for container images across environments. Teams running workloads on Azure should use ACR as their primary container image registry.
