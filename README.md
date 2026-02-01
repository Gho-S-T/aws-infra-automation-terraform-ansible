# aws-infra-automation-terraform-ansible
End-to-end automated AWS 3-tier infrastructure using Terraform, Ansible, and GitHub Actions CI/CD.
This project provisions a production-grade 3-tier architecture on AWS using reusable Terraform modules.
It includes VPC, public/private subnets, NAT, ALB, EC2, and RDS setup with remote state locking.
Instance configuration and application deployment are automated using Ansible, and CI/CD is implemented with GitHub Actions for automated validation, planning, and deployments using OIDC roles.
CloudWatch dashboards and alarms provide full observability of deployed workloads.
