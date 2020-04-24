# Ansible Playbooks

[![Build Status](https://github.com/bala146/ansible)]

Before proceeding make sure ansible is instsalled on the control node.
ansible.cfg and inventory are already created, just change the hostname and remote user

Before running any playbook make sure syntax check and dry run are tested.

# Syntax Check
ansible-playbook <filename.yml> --syntax-check
# Dry Run
ansible-playbook <filename.yml> -C

# First Installation
ansible-playbook fi_install.yml
# Web Server Installation
ansible-playbook web_install.yml
# DB Server Installation
ansible-playbook mysql_install.yml
# Docker Installation
ansible-playbook docker_install.yml
# FI/DB/Web Installation
ansible-playbook all.yml
# Jenkins Installation
ansible-playbook jenkins.yml
# Portainer Installation for Docker
ansible-playbook docker.yml

