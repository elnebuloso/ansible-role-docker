# Ansible Role - Docker for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker)

Docker for Linux Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-docker/blob/master/defaults/main.yml)
- [`vars/main.yml`](https://github.com/elnebuloso/ansible-role-docker/blob/master/vars/main.yml)
- [`vars/ubuntu14.yml`](https://github.com/elnebuloso/ansible-role-docker/blob/master/vars/ubuntu14.yml)
- [`vars/ubuntu16.yml`](https://github.com/elnebuloso/ansible-role-docker/blob/master/vars/ubuntu16.yml)
- Variables prefixed with __ (2 Underscores) are Defaults, overwrite them by writing without the Underscores

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.docker
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)