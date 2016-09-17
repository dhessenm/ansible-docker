Ansible role: docker
=========

Role installs Docker engine on Ubuntu trusty

Requirements
------------
none

Role Variables
--------------
Available variables are listed below, along with default values:

* use_proxy: false
* http_proxy
* no_proxy


Dependencies
------------

* common
* proxyconf


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: docker, tags ["docker"]  }

License
-------

BSD

Author Information
------------------
it's me
