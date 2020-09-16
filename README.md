Ansible role: Terraform
=========

This role helps you to install terraform on your linux machine.


|Travis|CircleCI|GitHub|Quality|Downloads|Version|
|------|--------|------|-------|---------|-------|
|[![travis](https://travis-ci.com/amine7777/ansible-role-terraform.svg?branch=master)](https://travis-ci.com/amine7777/ansible-role-terraform)|![circleci](https://circleci.com/gh/amine7777/ansible-role-terraform.svg?style=svg)|[![github](https://github.com/amine7777/ansible-role-terraform/workflows/CI/badge.svg)](https://github.com/amine7777/ansible-role-terraform/actions)|[![quality](https://img.shields.io/ansible/quality/50498)](https://galaxy.ansible.com/amine7777/terraform)|[![downloads](https://img.shields.io/ansible/role/d/50348)](https://galaxy.ansible.com/amine7777/terraform)|[![Version](https://img.shields.io/github/release/amine7777/ansible-role-terraform.svg)](https://github.com/amine7777/ansible-role-terraform/releases/)|

![](terraform.jpg)

Requirements
------------
- Linux machine
- Ansible 2.9

Role Variables
--------------
These variables helps to manage terraform installation.

You can specify your terraform version in this variable.
```yaml
terraform_version: 0.13.1
terraform_arch: amd64
terraform_directory_path: /usr/local/bin
```
This is the url where terraform will be downloaded.
```ỳaml
terraform_download_url: 'https://releases.hashicorp.com/terraform/{{ terraform_version }}/terraform_{{ terraform_version }}_linux_{{ terraform_arch }}.zip'
```
This is the path where packer binary will be stored.
```yaml
terraform_directory_path: /usr/local/bin
```

Example Playbook
----------------

```yaml
- hosts: all
  roles:
     - amine7777.terraform
```


Author Information
------------------

- [Amine Kahlaoui](https://github.com/amine7777), DevOps engineer.
