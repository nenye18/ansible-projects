## AUTOMATE NODE.JS APPLICATION DEPLOYMENT

## Technologies Used
Ansible, Node.js, DigitalOcean, Linux

## Project Description
## 1. Create a Server on DigitalOcean ##
   - Set up a new server instance on DigitalOcean.
   - Configure basic server settings (e.g., OS, region, and specs based on project requirements).
## 2. Write an Ansible Playbook
  ## Create a Linux User for the Application
      - Add a new Linux user dedicated to running the Node.js application.
      - Set appropriate permissions for security and application isolation.
   ## Configure the Server
      - Set up necessary configurations, such as firewall settings, network configurations, and environment variables.
      - Prepare the server for Nexus installation by updating packages and ensuring prerequisites are installed.
  ## Install and Deploy Nexus
      - Download and install Nexus Repository Manager.
      - Configure Nexus settings as needed, such as storage and ports.
      - Deploy Nexus under the newly created user to ensure it runs with the correct permissions.
  ## Verify Nexus is Running Successfully
     - Check that the Nexus service is running.
     - Test the Nexus application by accessing it through its designated URL or IP to confirm it’s functioning as expected.
