---
title:      "External Secrets Operator"
quadrant:   tool
ring:       adopt
tags:       [SECURITY, PLATFORM-ENGINEERING]
featured:   true
---

[External Secrets Operator (ESO)](https://external-secrets.io/) is a Kubernetes operator that integrates external secret management systems — including Azure Key Vault, HashiCorp Vault, AWS Secrets Manager, and GCP Secret Manager — into Kubernetes as native Secret resources. ESO synchronizes secrets from the external provider into Kubernetes Secrets automatically, keeping them up to date and eliminating the need to store sensitive values in Git or manage manual secret injection. It provides a clean separation between secret storage (in the external provider) and secret consumption (in Kubernetes workloads), following the principle of least privilege. External Secrets Operator is the recommended approach for injecting secrets from Azure Key Vault or HashiCorp Vault into AKS workloads, and is particularly well suited for GitOps workflows where all configuration — including secret references — is stored in version control.
