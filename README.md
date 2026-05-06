# Terraform Basic Assignment

## Objective
Create an AWS EC2 instance using Terraform.

## Resources Created
- **AMI:** Amazon Linux (ami-0f58b397bc5c1f2e8)
- **Instance Type:** t2.micro
- **Tags:** Name = Terraform-Student-Instance

## Commands Used
1. `terraform init` - Initializes the Terraform working directory and downloads necessary provider plugins.
2. `terraform plan` - Creates an execution plan showing what resources will be created.
3. `terraform apply` - Executes the actions proposed in the plan to create the resources in AWS.