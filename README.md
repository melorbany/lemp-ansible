# LEMP Stack Ansible Playbook
Quickly install and configure the LEMP stack (Linux, Nginx, MySQL, PHP) on Ubuntu servers using this Ansible playbook.

## Prerequisites
Ansible on your control machine
SSH access with sudo privileges on your Ubuntu server

## Setup
Update your inventory in the hosts file with your server's IP.
Configure necessary variables in group_vars/all.

## Usage
Run the playbook with:

`ansible-playbook -i hosts site.yml`

## Roles
update: System update
common: Basic tools
nginx: Nginx server
php: PHP and extensions
mysql: MySQL database
initapps: Application setup
restartsvcs: Service restarts
Customize site.yml to include or exclude specific roles as needed.

## Support
For issues and enhancements, please open a GitHub issue.
