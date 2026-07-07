ansible-role-nagios
===================

This role is used to deploy the Nagios monitoring server. Host status notifications are sent via Postfix, which is configured as an email relay for Gmail.

Supported platfroms:
```
- Debian 12 (Bookworm)
- Debian 13 (Trixie)
- Ubuntu 22.04 (Jammy Jellyfish)
- Ubuntu 24.04 (Noble Numbat)
```

Requirements
------------

This role requires Ansible 2.19 or higher

Role Variables
--------------

The role variables and their descriptions can be found [here](https://github.com/serhii9132/ansible-role-nagios/blob/main/defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - serhii9132.ansible-role-nagios
```

License
-------

MIT
