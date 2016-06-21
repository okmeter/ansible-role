Okmeter Ansible Role
========

Install Okmeter agent.


Example Playbook
--------------

```
- hosts: servers
  roles:
  - { role: okmeter, sudo: yes, okmeter_api_token: "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX" }
```
