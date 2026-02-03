# Task-2 
# AWS EC2 Deployment – Manual & Terraform

## Objective
Launch an AWS EC2 instance manually and using Terraform, and document the process.

---

## AWS Core Concepts
- EC2: Virtual server
- AMI: OS image
- Security Group: Firewall
- Key Pair: SSH authentication

---

## Manual EC2 Launch
1. Logged into AWS Console
2. Selected Amazon Linux 2
3. Used t2.micro
4. Configured security group for SSH
5. Successfully connected using SSH
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6d573a66-7c46-44ad-b9e2-21d21f4cd21e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/99ed7065-aa98-4213-9ee0-0bb282d3d27e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b7dc44cf-c0b7-42a7-9e1a-11355283f8c2" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8a6a7e03-0a82-40f2-8ff9-e719946e4a16" />






---

## Terraform Setup
Terraform is used for Infrastructure as Code (IaC).

### Files Used
- provider.tf
- main.tf

### Commands
```bash
terraform init
terraform plan
terraform apply
