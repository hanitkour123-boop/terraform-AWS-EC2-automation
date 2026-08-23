# Terraform AWS EC2 Automation

## Project Overview

Automated the deployment and configuration of an AWS EC2 instance using Terraform. The project demonstrates infrastructure provisioning, instance initialization, Apache2 installation, and capturing the deployed instance's IP address locally.

## Project Workflow

1. Destroyed the previous Terraform deployment.
2. Created a script to install Apache2.
3. Provisioned a new AWS EC2 instance using Terraform.
4. Executed the Apache2 installation script on the newly created instance.
5. Retrieved the EC2 instance IP address after deployment.
6. Stored the instance IP address in a local file.

## Technologies Used

* Terraform
* Amazon Web Services (AWS)
* Amazon EC2
* Apache2
* Shell scripting

## Key Terraform Concepts Demonstrated

* Infrastructure as Code (IaC)
* Terraform resource provisioning
* Terraform deployment lifecycle
* EC2 instance provisioning
* Instance initialization/provisioning scripts
* Terraform outputs
* Local file generation
* AWS infrastructure automation

## Screenshots

Screenshots demonstrating the Terraform deployment, EC2 instance creation, Apache2 installation, successful execution, and local IP-address output are available in the `screenshots` folder.

## Outcome

Successfully automated the creation of an AWS EC2 instance, installed Apache2 through a script, and recorded the deployed instance's IP address in a local file.
