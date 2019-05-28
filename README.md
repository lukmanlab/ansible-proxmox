# Ansible for Proxmox
Ref: https://www.lukmanlab.com/tutorial-ansible-untuk-proxmox-ve/

- Proxmox 5.3.2 dengan Storage Local dan Local-LVM

## Pre-requirrement
- Install Python-minimal, Python-pip
- Install Proxmoxer

## Hosts
- Sesuaikan IP Address sesuai Proxmox anda.

## Sesuaikan Variable di group_vars
- Sesuaikan value node, api_user, api_password, api_host sesuai proxmox anda.
- Sesuaikan value-value lain sesuai keinginan anda untuk create ct dan vms.

## Menjalankan Ansible (didalam folder ansible-proxmox)

`$ ansible-playbook -i hosts main.yml`
