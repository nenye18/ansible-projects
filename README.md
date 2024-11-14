## CONFIGURE DYNAMIC INVENTORY 

## Technologies used:
Ansible, Terraform, AWS

## 1. Create an EC2 Instance with Terraform
  - Write a Terraform configuration file to define and create an EC2 instance on AWS.
  - Specify instance details, including instance type, region, AMI, security groups, and key pair.
  - Run Terraform to apply the configuration and provision the EC2 instance.
## 2. Write an Ansible AWS EC2 Plugin for Dynamic Inventory Management
  - Configure Ansible to use the AWS EC2 dynamic inventory plugin.
  - Set up the plugin to retrieve the list of EC2 instances in your AWS account, dynamically updating the inventory based on current EC2 instances.
  - Ensure the plugin filters and selects only the relevant EC2 instances you want Ansible to manage (e.g., using tags or instance criteria).
  - This approach removes the need to hard-code server IP addresses in the Ansible inventory file, allowing Ansible to manage instances flexibly as they are created or terminated.
