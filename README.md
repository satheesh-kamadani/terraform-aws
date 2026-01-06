# Terraform AWS Project

This repository contains Terraform configurations to provision AWS infrastructure resources.

## AWS Resources Included

- **VPC** – Networking setup for AWS resources  
- **EKS** – Amazon Elastic Kubernetes Service cluster  
- **S3 Bucket** – Object storage(used for terraform state file storage)
- **DynamoDB** – NoSQL database (used for state locking)

## Prerequisites

- Terraform installed
- AWS CLI configured with appropriate permissions
- An AWS account

## Usage

```bash
terraform init
terraform plan
terraform apply
```