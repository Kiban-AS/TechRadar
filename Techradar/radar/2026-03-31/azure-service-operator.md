---
title:      "Azure Service Operator"
quadrant:   tool
ring:       trial
tags:       [IAC, PLATFORM-ENGINEERING, AZURE, GITOPS]
featured:   true
---

[Azure Service Operator (ASO v2)](https://azure.github.io/azure-service-operator/) is a Kubernetes operator that allows teams to provision and manage Azure resources directly from Kubernetes using custom resource definitions (CRDs). ASO v2 is the successor to the original ASO and provides a more complete and production-ready implementation, with support for a wide range of Azure services including AKS, storage accounts, databases, networking, and more. By representing Azure resources as Kubernetes objects, ASO enables GitOps-driven Azure infrastructure management using the same tooling (FluxCD, Helm) used for application delivery. It is a strong complement or alternative to Bicep and Terraform for teams that want to consolidate their entire platform management — both application and infrastructure — within Kubernetes. Worth assessing for teams already running AKS who want to reduce the number of IaC toolchains.
