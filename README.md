# 🚀 Roboshop Terraform EKS CI/CD

## 📌 Project Overview

This repository contains production-style Terraform code to provision complete AWS infrastructure for deploying Roboshop microservices on Amazon EKS.

It automates networking, security, container registry, load balancing, SSL, and Kubernetes cluster creation for scalable CI/CD deployments.

---

## 🛠️ Tools & Technologies

- Terraform
- AWS
- Amazon EKS
- Amazon ECR
- VPC
- EC2 Bastion Host
- Security Groups
- Application Load Balancer
- ACM
- Kubernetes
- Linux
- Docker

---

## 🏗️ Infrastructure Components

- Custom VPC
- Public / Private Subnets
- Internet Gateway
- NAT Gateway
- Security Groups
- Bastion Host
- Amazon ECR
- Amazon EKS Cluster
- Worker Nodes
- Frontend ALB
- ACM SSL Certificate

---

## 📂 Repository Structure

```bash
00-vpc
10-sg
20-bastion
30-sg-rules
40-ecr
70-acm
80-frontend-alb
90-eks
```

---

## 🚀 Deployment Steps

```bash
git clone <repo-url>
cd roboshop-terraform-eks-cicd

terraform init
terraform plan
terraform apply -auto-approve
```
---

## 🔐 Key Features

- Modular Terraform Architecture
- EKS Cluster Automation
- ECR Repository Provisioning
- Secure VPC Networking
- SSL Enabled ALB
- CI/CD Platform Ready
- Reusable Infrastructure Code

---

## 📸 Architecture Flow

Developer → CI/CD Pipeline → ECR → EKS Cluster → ALB → Users

📈 Real-Time Use Cases
- Automated Kubernetes platform creation for Dev/Test/Prod
- Containerized microservices deployment on EKS
- Secure and scalable infrastructure provisioning
- Faster environment setup using Terraform automation
- Standardized CI/CD platform deployment

---

## 👨‍💻 Author

Surendra 
DevOps Engineer
---

⭐ If you like this project, give it a star
