Ansible - Docker demo
===============

Prerequisites
---------------

If you don't have Docker installed, follow the [instructions here](https://docs.docker.com/engine/installation) to install it.

Install Ansible on Ubuntu

    sudo apt-get install software-properties-common -y
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible -y

Install docker-py (assuming you have pip installed)

    pip install docker-py

Demo
---------------

Get development environment up

    ansible-playbook development.yml

Deploy to production

    ansible-playbook production.yml

(you should edit the production server in hosts for this to work)
