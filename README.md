andrewrothstein.openssl
=========
![Build Status](https://github.com/andrewrothstein/ansible-openssl/actions/workflows/build.yml/badge.svg)

Installs openssl and optionally openssl-dev operating system packages.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.openssl
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
