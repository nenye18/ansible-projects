
## PROVISION ANSIBLE WITH DOCKER

## Technologies Used
Ansible, AWS, Docker, Terraform, Linux

## 1. Create an AWS EC2 Instance with Terraform
  - Write a Terraform configuration file to define and provision an EC2 instance on AWS.
  - Specify instance details such as instance type, region, AMI, security groups, and key pair for SSH access.
  - Run Terraform commands to apply the configuration and create the EC2 instance.
## 2. Write an Ansible Playbook

  ## Install Necessary Technologies
  - Use Ansible to install Docker and Docker Compose on the EC2 instance.
  - Ensure any dependencies required by Docker and Docker Compose are also installed.
  
  ## Copy Docker Compose File to the Server
  - Transfer the docker-compose.yml file from the local environment to the EC2 instance.
  - Place the file in a specified directory on the server where Docker will execute it.

  ## Start Docker Containers
  -Use Ansible to start the Docker containers as defined in the docker-compose.yml file.
  -Verify that each container is running successfully according to the configuration.
