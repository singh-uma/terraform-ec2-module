# Terraform EC2 Module

This project demonstrates how to create and use a reusable **Terraform EC2 module** following Infrastructure as Code (IaC) best practices.

The setup uses a **root module** and a **child EC2 module**, with variables and outputs managed cleanly and the code version-controlled using GitHub.


---

## ⚙️ What This Project Does

- Creates an EC2 instance using Terraform
- Uses a reusable child module (`modules/ec2`)
- Passes variables from the root module
- Exposes outputs from the child module to the root module
- Follows Terraform and Git best practices



