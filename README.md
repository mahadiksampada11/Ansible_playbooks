# Ansible Study and Hands-On

This repository contains commands and screenshots demonstrating how to use **Ansible** for automation tasks.

## Table of Contents
- [Introduction](#introduction)
- [Basic Commands](#basic-commands)
- [Common Ansible Modules](#common-ansible-modules)
- [Screenshots of Hands-On Practice](#screenshots-of-hands-on-practice)

## Introduction
Ansible is a powerful automation tool for configuration management and deployment. In this repository, I share my commands and hands-on experiences with Ansible.

## Basic Commands
- `ansible --version`: Check Ansible version
- `ansible all -m ping`: Ping all hosts

- Ansible Galaxy:
Install a role: ansible-galaxy install <role_name>
Search for roles: ansible-galaxy search <role_name>
Create a new role: ansible-galaxy init <role_name>

- Ansible Inventory:
Specify an inventory file for a playbook: ansible-playbook -i inventory.ini playbook.yml
Ping all hosts in an inventory: ansible all -i inventory.ini -m ping

- Ansible Playbooks:
Run a playbook: ansible-playbook playbook.yml
Run a playbook with tags: ansible-playbook playbook.yml --tags <tag_name>
Check playbook syntax: ansible-playbook --syntax-check playbook.yml

## Common Ansible Modules
- `ping`: Tests connectivity.
- `command`: Runs commands on remote machines.

## Screenshots of Hands-On Practice
- Add your images in the `images/` folder.
1.First we SSH in tnto our EC2 server.
- ![Ansible Setup](images/1.png)
- ![Ansible Setup](images/2.png)
- ![Ansible Setup](images/3.png)
- ![Ansible Setup](images/4.png)
- ![Ansible Setup](images/5.png)
- ![Ansible Setup](images/6.png)
- ![Ansible Setup](images/7.png)
- ![Ansible Setup](images/8.png)
- ![Ansible Setup](images/9.png)
- ![Ansible Setup](images/10.png)
- ![Ansible Setup](images/11.png)
- ![Ansible Setup](images/12.png)
- ![Ansible Setup](images/13.png)
- ![Ansible Setup](images/14.png)
- ![Ansible Setup](images/15.png)
