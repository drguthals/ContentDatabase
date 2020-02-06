---
layout: single
title: Kubernetes 101
date: 2020-01-28
category: cloud
tags: [cloud, kubernetes, 100]
author: Scott Coulton
header:
  overlay_image: images/header/arm.png
  teaser: images/teaser/cloud-builder.png
excerpt: TBD
sidebar:
  nav: "aks"
featured: true
---
## Introduction
This workshop is the entry level into Azure Kubernetes service. In the workshop we will cover the topics listed above in the kubernetes 101 section. 

## Metadata
Duration: 2 hours  

## Pre-requisites
- A basic understanding of Linux
- Be able to read bash scripts
- Understand what a container is

## Workshop requirements
- Docker installed
- An Azure account with the access to create resources service principals
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [kubectx](https://github.com/ahmetb/kubectx)
- jq (from your package manager)

## Course modules
- [Agenda](slides/intro/code.md) 
- [Introduction into Kubernetes](slides/introduction-into-kubernetes/code.md)
- [Kubernetes components](slides/kubernetes-components/code.md) 
- [Deploying Kubernetes on Azure](deploying-kubernetes-on-azure/code.md)
- [Pods, services and deployments](pods-services-deployments/code.md)
- [Rabc, roles and service accounts](rbac-roles-service-accounts/code.md) 
- [Stateful sets](statefull-sets/code.md)
- Kubernetes networking and service discovery
- [Load balancing and ingress control](ingress-controller/code.md)

## Additional Resources
- [Choosing the right container base image](https://dev.to/scottyc/i-cho-cho-chose-you-container-image-part-1-227p)
- [Pod security 101](https://medium.com/devopslinks/kubernetes-pod-security-101-15fe8cda829e)
- [Understading application routing with istio](https://itnext.io/understanding-application-routing-in-istio-aade30d594f4)

