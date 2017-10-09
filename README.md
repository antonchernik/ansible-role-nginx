Nginx
=========

Ansible role for installing nginx. Tested platforms are:
* Debian 8
* Debian 9
* Ubuntu 16

Requirements
------------

Debian 8 (jessie)
Debian 9 (stretch)
Ubuntu 16 (xenial)

Role Variables
--------------

None

Dependencies
------------

None

Example 
----------------
    ---
    - hosts: all
      roles:
         - { role: antonchernik.nginx }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Anton Chernik](https://github.com/antonchernik).
