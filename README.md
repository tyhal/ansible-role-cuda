# ansible-role-cuda

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftyhal%2Fcuda.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftyhal%2Fcuda?ref=badge_shield)

An Ansible role to install the minimum needed to *run* a cuda application.

You will be able to install additional NVIDIA packages after this playbook E.G ( cublas, cufft, cusparse )

## Install

``` bash
	ansible-galaxy install tyhal.cuda
```

## Usage

Then you can use this with:

```yaml
- hosts: all
  become: yes
  roles:
    - { role: tyhal.cuda }
```
