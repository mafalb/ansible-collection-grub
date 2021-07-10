# Ansible Role mafalb.grub.bootparam

## Basic Usage

```yaml
- name: install mafalb.grub.bootparam
  hosts: localhost
  roles:
  - role: mafalb.grub.bootparam
    bootparam: selinux
    state: absent
```

## Variables

```state: present``` # not implemented

```state: absent``` # remove a boot parameter

```bootparam: selinux``` # what boot parameter to operate on

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
