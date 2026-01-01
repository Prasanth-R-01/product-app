# Kubernetes Deployment for a Small .NET Application

This repository contains a simple .NET application deployed using containerisation and Kubernetes on Azure.  
The project focuses on demonstrating **cloud-native delivery practices** rather than application complexity.

## Overview

The application is built and packaged as a Docker image, pushed to Azure Container Registry (ACR), and deployed to Azure Kubernetes Service (AKS) using Azure DevOps pipelines.

This setup highlights how Kubernetes can be used effectively even for small services to achieve consistent, scalable, and production-ready deployments.

## Tech Stack

- .NET
- Docker
- Azure DevOps Pipelines
- Azure Container Registry (ACR)
- Azure Kubernetes Service (AKS)

## CI/CD Flow

1. Build and containerise the application using Azure Pipelines  
2. Push the Docker image to Azure Container Registry  
3. Deploy the image to Azure Kubernetes Service via release pipeline  

## Purpose

This project was created as part of Kubernetes upskilling to gain hands-on experience with:
- Container-based application delivery
- CI/CD integration with Kubernetes
- Azure-native DevOps tooling

The application itself is intentionally minimal to keep the focus on infrastructure and deployment workflows.

---

