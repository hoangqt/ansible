# Summary

Terraform configuration to spin up VMs for testing.

## Setup

### Prerequisites

```bash
brew install ansible
```

### Playbook

Run playbook to install packages.

```bash
ansible-playbook -i inventories/dev/hosts base.yml
```
