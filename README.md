nodejs-role
=========

Installs NodeJS environment.

This role written using [Ansible Codestyle](https://faunusaff.atlassian.net/wiki/spaces/DEVOPS/pages/634683425/Ansible+Codestyle).

How to use
=========

This is how your playbook should look.

```
- hosts: staging
  user: root
  roles:
    - nodejs-role
```


TODO
=========
* tasks and vars depending on OS
