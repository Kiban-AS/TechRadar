---
title:      "Crossplane"
quadrant:   tool
ring:       adopt
tags:       [IAC, PLATFORM-ENGINEERING, GITOPS]
featured:   true
---

[Crossplane](https://www.crossplane.io/) is an open-source Kubernetes add-on that extends Kubernetes with the ability to provision and manage cloud infrastructure and services using Kubernetes-style declarative APIs and GitOps workflows. Crossplane transforms Kubernetes into a universal control plane, allowing platform teams to define composite resources (XRDs) that abstract cloud provider APIs (Azure, AWS, GCP) behind clean, self-service interfaces for application teams. It enables infrastructure provisioning through standard Kubernetes tooling such as FluxCD and Helm, eliminating the need for separate IaC pipelines. Crossplane is particularly powerful for building internal developer platforms where application teams can provision infrastructure on demand through curated abstractions without requiring cloud provider expertise.
