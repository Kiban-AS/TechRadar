---
title:      "AWS CloudFormation"
quadrant:   tool
ring:       hold
tags:       [IAC, AUTOMATION, CLOUD]
featured:   false
---

[AWS CloudFormation](https://aws.amazon.com/cloudformation/) is AWS's native Infrastructure as Code service that allows teams to model and provision AWS resources using JSON or YAML templates. CloudFormation has been used to deploy infrastructure on AWS including EKS clusters, Atlassian Stack deployments, and test environments. However, for new projects teams should prefer Terraform or OpenTofu which offer multi-cloud support, a richer ecosystem of providers, better modularity, and a more developer-friendly workflow. CloudFormation is acceptable to maintain in existing AWS-only projects but should not be chosen for greenfield infrastructure work.
