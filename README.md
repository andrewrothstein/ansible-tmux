andrewrothstein.tmux
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-tmux.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-tmux)

Installs [tmux](https://tmux.github.io/).

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
    - andrewrothstein.tmux
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
