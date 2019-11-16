# ansible-role-ubuntu-clean

Ansible role for setting up a clean ubuntu desktop installation.

## Supported Platforms

* Ubuntu 16.04, 18.04

## Requirements

Ansible 2.7 or higher is recommended.

## Variables

Variables for this

| variable | default value in defaults/main.yml | description |
| -------- | ---------------------------------- | ----------- |
| role_ubuntu-clean_enabled | False | determine whether role is enabled (True) or not (False) |

## Dependencies

None.

## Example Playbook

```yaml
---
# role: ansible-role-ubuntu-clean
# file: site.yml

- hosts: ubuntu_clean_systems
  become: True
  vars:
    role_ubuntu_clean_enabled: True
  roles:
    - role: ansible-role-ubuntu-clean
```

## License and Author

- Author:: Jonas Mauer (<jam@kabelmail.net>)
- Copyright:: 2019, Jonas Mauer

Licensed under MIT License;
See LICENSE file in repository.

## References

[ArchWiki](https://wiki.archlinux.org/)