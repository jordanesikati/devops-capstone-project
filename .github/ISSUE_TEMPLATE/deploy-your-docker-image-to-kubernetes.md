---
name: Deploy your Docker image to Kubernetes
about: Product Backlog
title: ''
labels: ''
assignees: ''

---

Title: Deploy your Docker image to Kubernetes
**As a** service provider
**I need** my service to run on Kubernetes
**So that** I can easily scale and manage the service
### Assumptions
* Kubernetes manifests will be created in yaml format
* These manifests could be useful to create a CD pipeline
* The actual deployment will be to OpenShift
### Acceptance Criteria
Given the Kubernetes manifests have been created
When I use the oc command to apply the manifests
Then the service should be deployed and run in Kubernetes
Copied!
