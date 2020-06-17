# Ansible playbook for Kali Linux
Configurations of my personal Kali setup

## Configuration
Set the ip of your VM in `inventory/inventory.yml` under `[kali]`

Set your username in `host_vars/kali.yml`

## Running
```
ansible-playbook playbook.yml -i inventory/inventory.yml --ask-become-pass
```
