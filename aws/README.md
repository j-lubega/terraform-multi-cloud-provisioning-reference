# AWS Terraform Architecture

This section demonstrates AWS resources commonly provisioned using Terraform.

## Services Included

- EC2
- ECS
- VPC
- Load Balancer
- IAM
- RDS
- S3
- CloudWatch

## Terraform Provider

```hcl
provider "aws" {
  region = "us-east-1"
}
```
