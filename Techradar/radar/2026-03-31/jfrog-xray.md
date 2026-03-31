---
title:      "JFrog Xray"
quadrant:   service
ring:       adopt
tags:       [SECURITY, CI/CD, PLATFORM-ENGINEERING]
featured:   true
---

[JFrog Xray](https://jfrog.com/xray/) is a universal software composition analysis (SCA) and security tool that integrates with JFrog Artifactory to scan artifacts, container images, and dependencies for known vulnerabilities (CVEs), license compliance issues, and malware. Xray automatically scans all artifacts stored in Artifactory and can block promotion or deployment of artifacts with critical vulnerabilities based on configurable policies. JFrog Xray is used alongside Artifactory to enforce security gates on container images and Helm charts before they reach production environments. It is recommended for teams already using JFrog Artifactory who want integrated artifact scanning without adding a separate toolchain component.
