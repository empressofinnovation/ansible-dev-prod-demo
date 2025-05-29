# ansible-dev-prod-demo

# Ansible Dev & Prod Demo

This project simulates a real-world setup for managing Ansible playbooks in `dev` and `prod` environments.

## Structure

- `inventory/dev/hosts`: DEV inventory
- `inventory/prod/hosts`: PROD inventory
- `site.yaml`: Main playbook
- `roles/`: Custom roles (optional)

## Usage

Run on dev:
```bash
ansible-playbook -i inventory/dev/hosts site.yaml
