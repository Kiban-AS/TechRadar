---
title:      "JFrog Artifactory"
quadrant:   service
ring:       adopt
tags:       [SECURITY, CI/CD, PLATFORM-ENGINEERING]
featured:   true
---

[JFrog Artifactory](https://jfrog.com/artifactory/) is a universal artifact repository manager that supports all major package formats including container images, Helm charts, npm, Maven, PyPI, and more. It provides secure artifact storage, dependency management, vulnerability scanning (via JFrog Xray), and fine-grained access control. Artifactory has been used as the primary artifact repository for Helm OCI charts, container images, and CI/CD build artifacts, providing a reliable and policy-compliant distribution layer across GitLab runners, VMs, and AKS clusters. The JFrog Dependency Proxy feature has been used to proxy and cache upstream container images, improving availability and enabling controlled access. Teams running at scale with multiple artifact types should evaluate Artifactory as their unified artifact management platform.
