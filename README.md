# Ansible playbook for Kali Linux
Configuration for personal Kali setup

## Configuration
Set the ip of your VM in `inventory/inventory.yml` under `[kali]`

## Running
```
ansible-playbook playbook.yml -i inventory/inventory.yml --ask-become-pass
```
