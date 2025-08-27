# aws-multi-vpc-terraform
Infrastructure-as-Code project using Terraform to deploy a secure multi-VPC AWS architecture with automated provisioning and network segmentation.

Status: In progress.
Goal: Showcase cloud networking + security + automation skills (VPC design, TGW/peering, SGs/NACLs, IaC workflows).

# 🔎 Overview

**This lab provisions a production-style AWS network:**

Multiple VPCs (e.g., prod, dev, shared-services)

Public/Private subnets across multiple AZs

Routing (route tables, NAT gateways, IGWs)

Inter-VPC connectivity via Transit Gateway or VPC peering

Baseline security (Security Groups, NACLs, IAM roles/policies)

Optional bastion/utility host for testing

CI/CD-ready structure for future GitLab/Terraform Cloud integration

**Use cases**

Portfolio demonstration

Team onboarding reference

Foundation for adding Palo Alto VM-Series, Zero Trust policies, and DevSecOps checks (tfsec/Checkov/OPA)

