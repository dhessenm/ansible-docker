Role Name
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

* dbs_common
* dbs_proxyconf


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dbs_docker, tags ["docker"]  }

License
-------

BSD

Author Information
------------------
it's me
