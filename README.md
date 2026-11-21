# Ansible Configuration

Configuration management and host automation for the food platform.

## Planned scope

- Host bootstrap and security hardening
- Runtime and deployment dependencies
- Jenkins agent configuration
- Monitoring and logging agents

## Repository conventions

- Inventory is separated by environment.
- Reusable automation belongs in `roles/`.
- Playbooks must be idempotent and linted before use.
- Passwords, private keys, and vault credentials must never be committed.

Provisioning remains in `terraform-infrastructure`; operational guidance belongs in `devops-engineering-docs`.
