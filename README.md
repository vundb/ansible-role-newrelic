Ansible Role Newrelic
=======================================

Ansible role to install and configure newrelic on gentoo instances.

Supported Distributions
-----------------------

- Gentoo

Role Variables
--------------

`newrelic_license`: License string used for configuration. Variable is
mandatory.

Dependencies
------------

[vundb/ansible-role-portage](https://github.com/vundb/ansible-role-portage)

Example Playbook
----------------
```
- hosts: all
  roles:
    - role: vundb-newrelic
```

License
-------

MIT

Author Information
------------------

- You can find more roles in my GitHub channel [vundb](https://github.com/vundb)
- Follow me on Twitter [@vundb](https://twitter.com/vundb)
