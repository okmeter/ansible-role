Okmeter Ansible role
========

Install [Okmeter.io](https://Okmeter.io) agent.


Playbook example
--------------

```
- hosts: ...
  roles:
  - { role: okmeter, sudo: yes, okmeter_api_token: "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX" } 
  # you can find api token for your project @ Docs on okmeter.io/your_project_name/
```
