# Ansible Role - Docker for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker)

Docker for Linux Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu16

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-docker/blob/master/defaults/main.yml)

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.docker
      docker_version: "1.12"
      docker_compose_install: "yes"
      docker_compose_version: "1.16.1"
      docker_install_docker_python: "yes"
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)