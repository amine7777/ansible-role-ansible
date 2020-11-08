Ansible role: Ansible
=========

This role helps you to install ansible on your linux machine.


<<<<<<< HEAD
|Travis|GitHubActions|Quality|Downloads|Version|
|------|-------------|-------|---------|-------|
|[![travis](https://travis-ci.com/amine7777/ansible-role-ansible.svg?branch=master)](https://travis-ci.com/amine7777/ansible-role-ansible)|[![github](https://github.com/amine7777/ansible-role-ansible/workflows/CI/badge.svg)](https://github.com/amine7777/ansible-role-ansible/actions)|[![quality](https://img.shields.io/ansible/quality/50498)](https://galaxy.ansible.com/amine7777/ansible)|[![downloads](https://img.shields.io/ansible/role/d/50348)](https://galaxy.ansible.com/amine7777/ansible)|[![Version](https://img.shields.io/github/release/amine7777/ansible-role-ansible.svg)](https://github.com/amine7777/ansible-role-ansible/releases/)|
=======
|Travis|CircleCI|GitHub|Quality|Downloads|Version|
|------|--------|------|-------|---------|-------|
|[![travis](https://travis-ci.com/amine7777/ansible-role-ansible.svg?branch=master)](https://travis-ci.com/amine7777/ansible-role-ansible)|![circleci](https://circleci.com/gh/amine7777/ansible-role-ansible.svg?style=svg)|[![github](https://github.com/amine7777/ansible-role-ansible/workflows/CI/badge.svg)](https://github.com/amine7777/ansible-role-ansible/actions)|[![quality](https://img.shields.io/ansible/quality/50498)](https://galaxy.ansible.com/amine7777/ansible)|[![downloads](https://img.shields.io/ansible/role/d/50782)](https://galaxy.ansible.com/amine7777/ansible)|[![Version](https://img.shields.io/github/release/amine7777/ansible-role-ansible.svg)](https://github.com/amine7777/ansible-role-ansible/releases/)|
>>>>>>> 333114491981ddede64ebc1541d642fe39f7f070

![](ansible.jpg)

Requirements
------------
- Linux machine
- Ansible 2.9

Role Variables
--------------

You can specify your ansible version in this variable.
```yaml
ansible_version: 2.9.6
```

Example Playbook
----------------

```yaml
- hosts: all
  vars:
    ansible_version: 2.9.13
  roles:
     - amine7777.ansible
```

Author Information
------------------

- [Amine Kahlaoui](https://github.com/amine7777), DevOps engineer.
