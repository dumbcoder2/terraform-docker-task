# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools Used
- AWS EC2 Ubuntu
- Docker
- Terraform
- Nginx

## Project Description
Used Terraform to automate the creation of an Nginx Docker container.

## Implementation Steps
1. Installed Docker and Terraform on Ubuntu.
2. Configured the Docker provider in `main.tf`.
3. Downloaded the Nginx Docker image.
4. Initialized Terraform using `terraform init`.
5. Validated configuration using `terraform validate`.
6. Previewed infrastructure using `terraform plan`.
7. Created infrastructure using `terraform apply`.
8. Verified the container using `docker ps` and `curl`.
9. Inspected resources using `terraform state list`.
10. Removed infrastructure using `terraform destroy`.

## Docker Configuration
- Container name: terraform-nginx
- Image: nginx:latest
- Container port: 80
- Host port: 8080

## Expected Result
Nginx welcome page successfully served through the Docker container.

## Key Learning
- Infrastructure as Code
- Terraform providers and resources
- Terraform state management
- Plan, Apply and Destroy
- Docker container provisioning
