# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective
Provision and manage a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Nginx

## Project Description
This project uses Terraform to provision an Nginx Docker container. The Docker provider manages the Docker image and container through infrastructure-as-code configuration.

## Implementation Steps
1. Created `main.tf` with the Terraform Docker provider.
2. Initialized Terraform using `terraform init`.
3. Validated the configuration using `terraform validate`.
4. Reviewed the proposed changes using `terraform plan`.
5. Created the Nginx container using `terraform apply`.
6. Verified the application at `http://localhost:8085`.
7. Inspected managed resources using `terraform state list` and `terraform state show`.
8. Saved execution evidence in `execution-logs.txt`.
9. Removed the infrastructure using `terraform destroy`.

## Files
- `main.tf` — Terraform configuration.
- `execution-logs.txt` — State listing and plan output.
- `README.md` — Project documentation.

## Result
Successfully created and tested the Nginx Docker container using Terraform, inspected Terraform state, and destroyed the managed resources after verification.

## Verification
The Nginx welcome page was accessible at `http://localhost:8085` while the container was running.

# terraform-docker-iac-task3
Task 3 - Infrastructure as Code using Terraform and Docker
 0d5a76b83071017cc4474436a4c2b585dddfa6f3
