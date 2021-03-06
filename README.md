[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-The%20Foreman-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-theforeman) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-theforeman.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-theforeman)

---
# IaC: with[Ansible](https://www.ansible.com) role to install and configure [Foreman](https://www.theforeman.org/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.theforeman
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.theforeman/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - theforeman
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
