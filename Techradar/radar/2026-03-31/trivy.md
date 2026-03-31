---
title:      "Trivy"
quadrant:   service
ring:       assess
tags:       [SECURITY, CI/CD, PLATFORM-ENGINEERING]
featured:   true
---

[Trivy](https://trivy.dev/) is an open-source, comprehensive security scanner for container images, file systems, Git repositories, Kubernetes clusters, and IaC configurations. It detects vulnerabilities in OS packages and application dependencies, misconfigurations, exposed secrets, and software bill of materials (SBOM) issues. Trivy is used as the primary image vulnerability scanner in CI/CD pipelines, embedded as a pipeline gate to prevent the promotion of images with known critical vulnerabilities. It is lightweight, fast, and integrates natively with GitLab CI, GitHub Actions, and Kubernetes admission controllers. Teams looking for a reliable, open-source vulnerability scanning solution should trial Trivy as part of their DevSecOps pipeline.
