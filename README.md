# Ansible role: tftp
Installs and configures TFTP server.

## Requirements
None.

## Role Variables
None.

## Dependencies
+ [xinetd](https://github.com/shomatan/ansible-xinetd.git)

```yaml
- hosts: all
  roles:
    - { role: tftp }
```
