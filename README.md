Nginx
=========

Ansible role for installing nginx. Tested platforms are:
* Debian 8

Requirements
------------

Debian 8 (jessie)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

debian_codename: jessie

Latest debian codename

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
