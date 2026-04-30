# Ansible CI/CD Automation

## Description
Automated server configuration and deployment on AWS EC2 using Ansible.

## Tools Used
- Ansible
- AWS EC2
- Linux (Ubuntu)

## Files
- inventory.ini → Target hosts
- playbook.yml → Nginx installation
- nginx-setup.yml → Deploy web page

## Features
- Automated Nginx setup
- Idempotent configuration
- Remote provisioning via SSH

## Run
ansible-playbook -i inventory.ini playbook.yml
