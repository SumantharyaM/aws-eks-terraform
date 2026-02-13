# 🚀 AWS EKS Infrastructure Provisioning using Terraform

## 📌 Project Overview

This repository contains Terraform configuration files used to provision AWS infrastructure for the DevOps end-to-end project.

The infrastructure includes:

- VPC
- Subnets
- Internet Gateway
- IAM Roles
- Security Groups
- EKS Cluster
- Worker Nodes

Terraform is used to automate infrastructure creation following Infrastructure as Code (IaC) principles.

---

## 🏗️ Architecture Components Provisioned

### 🌐 Networking
- Custom VPC
- Public and Private Subnets
- Internet Gateway
- Route Tables

### 🔐 IAM Configuration
- IAM Roles for EKS Cluster
- IAM Roles for Worker Nodes
- Required AWS managed policies attached

### ☸️ Amazon EKS Cluster
- Managed control plane
- Worker node group
- Auto-scaling configuration

---

## ⚙️ Terraform Files Description

- `main.tf` – Core resource definitions
- `variables.tf` – Input variable definitions
- `output.tf` – Output values (cluster endpoint, etc.)
- `providers.tf` – AWS provider configuration (if included)
- `rbac/` – Kubernetes RBAC related configurations (if applicable)

---

## 🚀 Deployment Steps

### 1️⃣ Initialize Terraform
