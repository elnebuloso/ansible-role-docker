# Ansible Role - Docker for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-docker.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-docker)

Docker for Linux Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
# values can be: yes, no
# - linux-image-extra-$(uname -r)
# - linux-image-extra-virtual
docker_install_linux_image_extra: "yes"
docker_compose_version: "latest"
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