[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-tmux.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-tmux)
andrewrothstein.tmux
=========

Installs [tmux](https://tmux.github.io/)

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
