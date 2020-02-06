---
layout: single
title: Advanced Kubernete Topics
date: 2020-01-28
category: cloud
tags: [cloud, helm, 200]
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
This four hour workshop covers advanced Kubernete topics.

## Metadata
Duration: 4 hours  

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
* [Virtual kubelet](virtual-node-with-virtual-kubelet/code.md)
* [Pod security context](pod-security-policy/code.md) 
* Introduction to istio
* Advanced application routing with istio(advanced-application-routing-with-istio/code.md)
* [Setting mTLS between application services with istio](mTLS-with-istio/code.md)

## Additional Resources
- [Choosing the right container base image](https://dev.to/scottyc/i-cho-cho-chose-you-container-image-part-1-227p)
- [Pod security 101](https://medium.com/devopslinks/kubernetes-pod-security-101-15fe8cda829e)
- [Understading application routing with istio](https://itnext.io/understanding-application-routing-in-istio-aade30d594f4)

