# GCP Terraform Architecture

This section demonstrates Google Cloud Platform resources commonly provisioned using Terraform.

## Services Included

- GKE
- Cloud Run
- Cloud SQL
- VPC Networks
- IAM
- Cloud Monitoring
- Cloud Storage

## Terraform Provider

```hcl
provider "google" {
  project = "my-project-id"
  region  = "us-central1"
}
```
