# Infrastructure (Terraform)

This directory contains Terraform code for provisioning AWS infrastructure.

## Components
- **VPC**: Multi-AZ with public/private subnets, NAT, and routing
- **EKS**: Kubernetes cluster with managed node groups
- **ECR**: Container registry for app images

## Usage
```bash
terraform init
terraform plan
terraform apply

