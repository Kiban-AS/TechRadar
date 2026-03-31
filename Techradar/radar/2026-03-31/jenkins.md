---
title:      "Jenkins"
quadrant:   tool
ring:       hold
tags:       [CI/CD, AUTOMATION]
featured:   false
---

[Jenkins](https://www.jenkins.io/) is an open-source automation server widely used for building CI/CD pipelines. Jenkins has a large plugin ecosystem and has historically been the de facto CI/CD tool across the industry. However, Jenkins comes with significant operational complexity — managing the Jenkins controller, agents, plugins, and upgrades requires considerable effort. Modern alternatives such as GitLab CI/CD and GitHub Actions offer better developer experience, native VCS integration, more secure secrets management, and lower operational overhead. Jenkins should not be adopted for new CI/CD workloads. Existing Jenkins pipelines should be migrated to GitLab CI/CD or GitHub Actions as part of any platform modernization effort.
