# Lampstack-Ansible


This is a Ansible Playbook to deploy a LAMP Stack infrastructure on Centos 7 hosts.

# Stack
•	apache
•	mysql
•	php


# Pre-requisites
Stop host key checking

#vim /etc/ansible/ansible.cfg 

#host_key_checking = False

# Setup
•	Add host in /etc/ansible/hosts file. See the given hosts file to add hosts.

•	Run command sudo ansible-playbook lampstack.yml
