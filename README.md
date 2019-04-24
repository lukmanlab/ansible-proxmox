# Ansible for Proxmox
- Proxmox 5.3.2 dengan Storage Local dan Local-LVM
- IP Address 192.168.56.199

## Pre-requirrement
- Install Python-minimal, Python-pip
- Install Proxmoxer

## Hosts
- Sesuaikan IP Address Proxmox

## Sesuaikan Variable di group_vars
- Sesuaikan value node, api_user, api_password, api_host proxmox anda.
- Sesuaikan value-value lain sesuai keinginan anda untuk create ct dan vms.

## Menjalankan Ansible (didalam folder ansible-proxmox)

`$ ansible-playbook -i hosts main.yml`
