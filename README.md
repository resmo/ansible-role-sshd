# Ansible SSH Daemon Role

## Usage

```
---
# group_vars/all
sshd_permit_root_login: without-password
```

Example playbook:
```
- hosts: all
  remote_user: root
  roles:
  - resmo.sshd
