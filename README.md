# Ansible playbook for Kali Linux
Configurations of my personal Kali setup

## Configuration
Set the ip of your VM in `inventory/inventory.yml` under `[kali]`
Set your username in `inventory/inventory.yml` under `[kali:vars]`

## Running
```
ansible-playbook playbook.yml -i inventory/inventory.yml --ask-become-pass
```
