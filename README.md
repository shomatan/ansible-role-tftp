# Ansible role: tftp
Installs and configures TFTP server.

## Requirements
None.

## Role Variables
None.

## Dependencies
+ [xinetd](https://github.com/shomatan/ansible-xinetd.git)

## Example playbook
```yaml
- hosts: all
  roles:
    - { role: tftp }
```
