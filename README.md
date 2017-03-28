# Ansible Role - Docker for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker)

Docker for Linux Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
docker_compose_version: "latest"

# values can be: yes, no
docker_install_docker_py: "no"
```

## Example Playbook

```
- hosts: localhost
  roles:
    - { role: elnebuloso.docker }
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)