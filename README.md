# Homelab Ansible

Ansible playbooks for automating and managing my homelab infrastructure.

## Inventory
- k3s-node1 — 192.168.1.71
- k3s-node2 — 192.168.1.89

## Playbooks
- `update-nodes.yml` — updates all nodes simultaneously
- `harden-nodes.yml` — hardens nodes with UFW firewall and SSH hardening

## Stack
- Ansible 2.20.6
- Ubuntu Server 24.04
- Proxmox
