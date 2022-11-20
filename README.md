# Introduction

Ansible role to deploy Docker CE

# Usage

```yaml
---
- hosts: docker 
  become: yes
  remote_user: admin
  vars:
    add_docker_users:
      - julien
    remove_docker_users:
      - johndoe 
  roles:
    - docker 
```
