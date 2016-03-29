hosts
=====

This Ansible role adds host records to `/etc/hosts`, including host aliases
Host aliases are optional.

Role Variables
--------------

    save_hosts: [] # hosts to save


Example configuration
---------------------

    save_hosts:
    - name: example.net
      ip:   8.8.8.8
      aliases:
      - dns
      - googledns
    - name: example.com
      ip:   8.8.4.4
          

License
-------

Public Domain


Author Information
------------------

Serhiy Oplakanets <serhiy@oplakanets.com>
