---
title:      "Open Policy Agent"
quadrant:   service
ring:       assess
tags:       [SECURITY, PLATFORM-ENGINEERING]
featured:   true
---

[Open Policy Agent (OPA)](https://www.openpolicyagent.org/) is a general-purpose, open-source policy engine that enables unified policy enforcement across the stack — from microservices and APIs to Kubernetes admission control. OPA uses a declarative policy language called Rego and integrates with Kubernetes via Gatekeeper as an admission controller. OPA has been used for policy-as-code enforcement in Kubernetes environments as part of security and compliance workflows. While OPA/Gatekeeper offers powerful and flexible policy capabilities, teams currently using Kyverno may find it sufficient for Kubernetes-specific use cases due to its simpler YAML-based policy authoring model. OPA remains worth assessing for organizations needing cross-stack policy enforcement beyond Kubernetes.
