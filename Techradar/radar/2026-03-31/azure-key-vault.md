---
title:      "Azure Key Vault"
quadrant:   service
ring:       adopt
tags:       [SECURITY, AZURE, PLATFORM-ENGINEERING]
featured:   true
---

[Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault) is a cloud service for securely storing and managing secrets, encryption keys, and certificates used by cloud applications and services. It provides hardware security module (HSM)-backed storage, fine-grained access policies via Azure AD and RBAC, and audit logging of all key vault operations. Azure Key Vault is the primary secrets backend for AKS workloads on Azure, integrated via the Secrets Store CSI Driver to mount secrets directly into pods without exposing them in Kubernetes Secrets. It is the recommended secrets management solution for any team running workloads on the Azure platform and a native complement to HashiCorp Vault for Azure-specific credential management.
