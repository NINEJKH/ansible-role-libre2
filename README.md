[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-libre2.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-libre2)

# lifeofguenter.libre2

An Ansible role that installs google/re2 (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
libre2_version: 2017-11-01
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: libre2
  roles:
    - { role: lifeofguenter.libre2 }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[Gunter Grodotzki](https://lifeofguenter.de)
