# Summary

Post terraform step to setup software packages on VMs.

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
