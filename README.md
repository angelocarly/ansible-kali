# Ansible playbook for Kali Linux
Configurations of my personal Kali setup, focused on reverse engineering

## Features
- `oh-my-zsh` with custom config
- `fzf`
- `neovim` with custom config
- [peda](https://github.com/longld/peda) - Python exploit assistance for gdb
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - Software Reverse Engineering Framework

## Configuration
Set the ip of your VM in `inventory/inventory.yml` under `[kali]`  
Set your username in `inventory/inventory.yml` under `[kali:vars]`

## Running
```
ansible-playbook playbook.yml -i inventory/inventory.yml --ask-become-pass
```
