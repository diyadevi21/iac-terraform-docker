# Terraform with Docker - Nginx Container Deployment

This project uses *Terraform* to deploy an *Nginx Docker container*.

## Prerequisites
- Docker installed and running
- Terraform installed
- Git Bash or any terminal

## Commands

```bash
# Initialize Terraform
terraform init

# Create Docker image & container using Terraform
terraform apply

# Check running containers
docker ps

# Check Terraform state
terraform state list

# Destroy all created resources
terraform destroy
