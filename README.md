# Ubuntu Ansible

## Description

So this is the project where i write ansible scripts for the automated setup of my home server.

## Usage

### some common commands:

ansible all -m ping -i inventory.yaml

ansible-inventory -i inventory.yaml --list

ansible-playbook -i inventory.yaml playbook.yaml

## Roadmap

- server security
- ssh keygen and setup