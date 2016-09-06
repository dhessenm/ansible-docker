Ansible role: docker
=========

Role installs docker engine

Requirements
------------


Role Variables
--------------

Available variables are listed below, along with default values:

* use_proxy: false


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
