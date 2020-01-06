Packer
=========

Install packer on a host

Requirements
------------

Linux host

Role Variables
--------------


Dependencies
------------

* `unzip` or `tar`
  Unarchiving the packer zip file


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-packer, version: 1.4.9 }

License
-------

BSD

Author Information
------------------

Trav at Catalyst

