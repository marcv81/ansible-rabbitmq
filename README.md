# Intro

This project helps to provision and maintain RabbitMQ clusters. It comes with a 2-nodes VirtualBox/Vagrant test environment.

## Features

- Management plugin
- Administrator and unprivileged user

# Setup

    vagrant up
    ansible-playbook -i environments/vagrant.py playbooks/site.yml
