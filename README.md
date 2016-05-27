# Ansible Role - Docker

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like:

    - hosts: localhost
      roles:
        - role: elnebuloso.docker
          become: yes

## Example Playbook

    - hosts: localhost
      roles:
        - { role: elnebuloso.server-base }

##  License

MIT

##  Author Information

This role was created in 2014 by [elnebuloso](https://github.com/elnebuloso/)