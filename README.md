# Ansible Role - Docker for Linux Server

![abandoned](https://img.shields.io/badge/project-abandoned-red)

Docker for Linux Server.

## Installation of docker Releases

- https://download.docker.com/linux/ubuntu/dists/trusty/pool/stable/amd64/
- https://download.docker.com/linux/ubuntu/dists/xenial/pool/stable/amd64/
- https://download.docker.com/linux/ubuntu/dists/bionic/pool/stable/amd64/

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
      docker_release: https://download.docker.com/linux/ubuntu/dists/bionic/pool/stable/amd64/docker-ce_18.06.3~ce~3-0~ubuntu_amd64.deb
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)