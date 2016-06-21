Okmeter Ansible
========

Install Okmeter agent.


Variables
--------------

- `okmeter_api_key` - Your Okmeter API key.


Example Playbook
--------------

```
- hosts: servers
  sudo: yes
  vars:
    okmeter_api_key: 'XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX'

  tasks:
  - include: tasks/okmeter.yaml

  handlers:
  - include: handlers/okmeter.yaml
```
