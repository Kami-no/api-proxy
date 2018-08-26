# api-proxy
Ansible role with alternative API-proxy for kubespray.

Envoy has metrics for Prometheus.

## Playbook sample:
```
---
- hosts: all
  become: true
  gather_facts: false

  roles:
    - api-proxy
```
