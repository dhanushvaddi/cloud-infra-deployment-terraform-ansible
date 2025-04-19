# cloud-infra-deployment-terraform-ansible
Infrastructure-as-Code using Terraform &amp; Ansible to deploy AWS EC2 &amp; RDS
# Automated Cloud Infrastructure Deployment 🚀

This project uses Terraform and Ansible to automate cloud infrastructure provisioning on AWS.

Technologies:
- AWS (EC2, VPC, IAM, RDS)
- Terraform (Modular Design)
- Ansible (Server Configuration)
- IAM for secure role-based access

Modules:
- Terraform provisions VPC, Subnet, EC2 instance
- Ansible installs and configures Nginx on EC2
- IAM Role created for secure access control

Folder Structure:
- terraform/ → Contains all .tf files
- ansible/ → Hosts and playbooks

How to Use:
1. Clone this repo
2. Update your variables in terraform/main.tf
3. terraform init && terraform apply
4. Use Ansible to provision your instance

Screenshots, diagrams, and usage examples coming soon.
