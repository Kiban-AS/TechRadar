---
title:      "Cert Manager"
quadrant:   service
ring:       adopt
tags:       [SECURITY, PLATFORM-ENGINEERING]
featured:   true
---

[cert-manager](https://cert-manager.io/) is a native Kubernetes certificate management controller that automates the provisioning, renewal, and management of TLS certificates from a variety of issuers including Let's Encrypt, HashiCorp Vault, AWS ACM, and self-signed CAs. cert-manager eliminates the operational burden of manual certificate rotation by handling the full lifecycle of certificates as Kubernetes resources, ensuring services always have valid, up-to-date certificates. It is used as the standard certificate management solution in Kubernetes clusters, ensuring zero-downtime certificate rotation and compliance with internal PKI requirements. cert-manager is strongly recommended for any team running TLS-secured services on Kubernetes.
