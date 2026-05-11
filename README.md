# Terraform Multi-Cloud Reference Architectures

<p align="center">
  <img 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg"
    alt="Terraform"
    width="120"
  />
</p>

<p align="center">
Provisioning Azure, AWS, and Google Cloud infrastructure using Terraform
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure" />
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws" />
  <img src="https://img.shields.io/badge/GCP-Cloud-lightgrey?logo=googlecloud" />
  <img src="https://img.shields.io/badge/Terraform-IaC-623CE4?logo=terraform" />
  <img src="https://img.shields.io/badge/DevOps-Automation-success" />
</p>

---


A professional reference repository demonstrating how Infrastructure as Code (IaC) can provision and manage resources across multiple cloud platforms using Terraform.

This repository contains:
- Azure architecture reference
- AWS architecture reference
- Google Cloud Platform (GCP) architecture reference
- Common Terraform-managed cloud resources
- Multi-cloud infrastructure examples
- DevOps and platform engineering concepts

---

# Cloud Platforms Covered

| Cloud Provider | Technologies |
|---|---|
| Microsoft Azure | Azure DevOps, AKS, App Services, VNets, Monitoring |
| Amazon Web Services (AWS) | EC2, VPC, ECS, RDS, IAM, CloudWatch |
| Google Cloud Platform (GCP) | GKE, Cloud Run, VPC, Cloud SQL, IAM |

---

# Architecture Diagrams

## Microsoft Azure

![Azure Architecture](./azure/azure-terraform-architecture.png)

---

## Amazon Web Services (AWS)

![AWS Architecture](./aws/aws-terraform-architecture.png)

---

## Google Cloud Platform (GCP)

![GCP Architecture](./gcp/gcp-terraform-architecture.png)

---

# Key Terraform Concepts Demonstrated

- Infrastructure as Code (IaC)
- Cloud networking
- Kubernetes platforms
- CI/CD integration
- Cloud security concepts
- Monitoring and observability
- Modular infrastructure design
- Scalable architecture patterns
- Multi-cloud provisioning strategies

---

# Terraform Benefits

- Repeatable deployments
- Version-controlled infrastructure
- Reduced configuration drift
- Environment consistency
- Automated provisioning
- Improved operational reliability

---

# Technologies Referenced

## Azure
- Azure Virtual Machines
- Azure Kubernetes Service (AKS)
- Azure Monitor
- Azure App Gateway
- Azure DevOps

## AWS
- EC2
- ECS
- VPC
- RDS
- CloudWatch
- IAM

## GCP
- GKE
- Cloud Run
- Cloud SQL
- Cloud Monitoring
- IAM

---


# Multi-Cloud Terraform Architecture

```mermaid
flowchart TD

    Terraform[Terraform IaC]

    Terraform --> Azure
    Terraform --> AWS
    Terraform --> GCP

    Azure --> AKS
    Azure --> AppService
    Azure --> AzureSQL

    AWS --> EC2
    AWS --> ECS
    AWS --> RDS

    GCP --> GKE
    GCP --> CloudRun
    GCP --> CloudSQL

    AKS --> Monitoring
    ECS --> Monitoring
    GKE --> Monitoring
```

# Ideal Use Cases

This repository is useful for:
- DevOps Engineers
- Cloud Engineers
- Platform Engineers
- Site Reliability Engineers (SREs)
- Infrastructure Architects
- Students learning Terraform
- Technical interview preparation

---

# Author

Created by Jimmy Lubega 
DevOps | Cloud Infrastructure | Terraform | Automation

