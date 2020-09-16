Ansible role: Terraform
=========

This role helps you to install ansible on your linux machine.


|Travis|CircleCI|GitHub|Quality|Downloads|Version|
|------|--------|------|-------|---------|-------|
|[![travis](https://travis-ci.com/amine7777/ansible-role-ansible.svg?branch=master)](https://travis-ci.com/amine7777/ansible-role-ansible)|![circleci](https://circleci.com/gh/amine7777/ansible-role-ansible.svg?style=svg)|[![github](https://github.com/amine7777/ansible-role-ansible/workflows/CI/badge.svg)](https://github.com/amine7777/ansible-role-ansible/actions)|[![quality](https://img.shields.io/ansible/quality/50498)](https://galaxy.ansible.com/amine7777/ansible)|[![downloads](https://img.shields.io/ansible/role/d/50348)](https://galaxy.ansible.com/amine7777/ansible)|[![Version](https://img.shields.io/github/release/amine7777/ansible-role-ansible.svg)](https://github.com/amine7777/ansible-role-ansible/releases/)|

![](ansible.jpg)

Requirements
------------
- Linux machine
- Ansible 2.9

Role Variables
--------------
These variables helps to manage ansible installation.

You can specify your ansible version in this variable.
```yaml
ansible_version: 0.13.1
ansible_arch: amd64
ansible_directory_path: /usr/local/bin
```
This is the url where ansible will be downloaded.
```ỳaml
ansible_download_url: 'https://releases.hashicorp.com/ansible/{{ ansible_version }}/ansible_{{ ansible_version }}_linux_{{ ansible_arch }}.zip'
```
This is the path where packer binary will be stored.
```yaml
ansible_directory_path: /usr/local/bin
```

Example Playbook
----------------

```yaml
- hosts: all
  roles:
     - amine7777.ansible
```


Author Information
------------------

- [Amine Kahlaoui](https://github.com/amine7777), DevOps engineer.
