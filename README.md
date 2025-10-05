# HomeLab Ansible

Infrastructure automation for my HomeLab (Proxmox, Docker, Pi-hole, WireGuard, Zeek, Splunk, etc.) managed through AWX.

## Structure
- `playbooks/` – All automation scripts.
- `inventory/` – Git-managed inventory (YAML).
- `group_vars/`, `host_vars/` – Variables per group/host.
- `roles/` – Reusable modules.
- `collections/` – External Ansible dependencies.

## Workflow
This repo syncs automatically to AWX (`HomeLab-Playbooks` project).
