[![Build Status](https://travis-ci.org/NINEJKH/ansible-role-libre2.svg?branch=master)](https://travis-ci.org/NINEJKH/ansible-role-libre2)

# NINEJKH.libre2

An Ansible role that installs google/re2 (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
libre2_version: 2018-02-01
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: libre2
  roles:
    - { role: NINEJKH.libre2 }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[9JKH (Pty) Ltd.](https://9jkh.co.za)
