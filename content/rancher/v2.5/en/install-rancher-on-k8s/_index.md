---
title: Installing on a Kubernetes Cluster
description: Learn how to install Rancher in development and production environments. Read about single node and high availability installation
weight: 3
---

> This section is under construction.

Rancher is both a platform and a Kubernetes distribution. In this section you'll learn how to set up a Rancher Kubernetes cluster that has the Rancher server Helm chart installed.

There are two main ways that Rancher can be installed:

1. You can use Helm to install the Rancher Helm chart on any Kubernetes cluster.
2. You can use the Rancher CLI to install a Rancher Kubernetes cluster. This cluster comes with the Rancher Helm chart built in.

The installation path that you choose will affect the way that you upgrade Rancher, but not the way that Rancher is backed up and restored.

This section focuses on the installation path in which the Rancher Helm chart is installed on an existing Kubernetes cluster.