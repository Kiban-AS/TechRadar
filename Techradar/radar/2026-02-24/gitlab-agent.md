---
title:      "GitLab Agent for Kubernetes"
quadrant:   tool
ring:       adopt
tags:       [GITOPS, CI/CD, PLATFORM-ENGINEERING]
featured:   true
---

[GitLab Agent for Kubernetes (agentk)](https://docs.gitlab.com/ee/user/clusters/agent/) is a GitLab-native solution for connecting Kubernetes clusters to GitLab without requiring network ingress to the cluster. The agent runs inside the cluster and maintains a persistent connection to GitLab, enabling secure GitOps-based deployments, Kubernetes manifest reconciliation, and CI/CD job execution within the cluster network. It supports both push-based deployments via `kubectl` in CI pipelines and pull-based GitOps reconciliation using the built-in GitOps module. The GitLab Agent for Kubernetes is used to enable GitOps workflows and cluster automation via GitLab CI/CD pipelines without exposing cluster API endpoints to the internet. Teams using GitLab as their DevSecOps platform should evaluate the GitLab Agent as a more integrated and secure alternative to managing cluster credentials in CI variables.
