---
draft: false 
date: 2024-01-01
categories:
  - Bash
  - Kubernetes
---

# k8s-login

Scripts to create namespaces, permissions, and kubeconfig files to enable multiple separate deployments of ArcGIS Enterprise on Kubernetes to a single cluster. 

:material-bash:
:simple-kubernetes:

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/k8s-login){:target="_blank"}

<!-- more -->

Success usually requires teamwork. This is the rare project where success required going outside the team to forge a solution. In this case, competing priorities among different teams meant that we were not making progress in delivering our desired solution for authenticating namespace admins to a Kubernetes cluster using Azure RBAC. I researched an alternative solution that used the built-in Kubernetes RBAC to create an authentication scheme that met our needs. The scripts in this project were easier to implement than our original solution, which let us move forward on the project faster.