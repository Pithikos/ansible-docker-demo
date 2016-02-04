Ansible - Docker demo
===============

Prerequisites
---------------

Install Ansible on Ubuntu

    sudo apt-get install software-properties-common -y
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible -y

Install docker-py

    pip install docker-py

Demo
---------------

Get development environment up

    ansible-playbook development.yml

Deploy to production

    ansible-playbook production.yml

(you should edit the production server in hosts for this to work)
