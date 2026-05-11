# Azure Terraform Architecture

This section demonstrates Azure resources commonly provisioned using Terraform.

## Services Included

- Virtual Machines
- Azure Kubernetes Service (AKS)
- App Services
- Azure Functions
- VNets/Subnets
- NSGs
- Azure Monitor
- Application Gateway
- Key Vault

## Terraform Provider

```hcl
provider "azurerm" {
  features {}
}
```
