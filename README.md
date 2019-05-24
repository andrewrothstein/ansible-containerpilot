andrewrothstein.container-pilot
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-container-pilot.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-container-pilot)

Installs [Container Pilot](https://www.joyent.com/containerpilot)

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
    - andrewrothstein.container-pilot
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
