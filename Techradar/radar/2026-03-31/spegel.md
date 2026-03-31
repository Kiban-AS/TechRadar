---
title:      "Spegel"
quadrant:   platform
ring:       adopt
tags:       [PLATFORM-ENGINEERING, DOCKER]
featured:   true
---

[Spegel](https://github.com/spegel-org/spegel) is a stateless cluster-local OCI registry mirror for Kubernetes that allows nodes to share container images with each other without relying on an external registry. By acting as a peer-to-peer registry mirror, Spegel reduces image-pull failures caused by upstream registry unavailability, lowers external bandwidth usage, and improves cluster startup times. Spegel has been deployed as a local registry cache in AKS to improve availability and reduce downtime caused by upstream pulls. It is worth assessing for any team running large-scale Kubernetes clusters with high image-pull frequency or strict reliability requirements.
