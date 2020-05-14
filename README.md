**wh** - webhost (or WordPress Host) with automatic HTTPS, built
with docker
=========

Deploy a webhost on a new server, including:

  * Reverse proxy with automaic HTTPS certificates enrollment
  * Database server shared to all the websites on the host
  * A list of websites

Requirements
------------

Any docker-capable system will do fine.

2+ GB RAM is recommended

Role Variables
--------------

All settable variables are listed in defaults/main.yml with comments on their usage.

Example Playbook
----------------

    - hosts: servers
      roles:
      - 123unix.wh

License
-------

GPL v.3

Author Information
------------------

Created by [Alexander Shcheblikin](https://www.123unix.com)
