hoplacloud.skeleton
=========

Hopla.cloud role for awx to add ip address to security group WL-infogerance-hopla.


Requirements
------------

None.

Role Variables
--------------

- ip_hopla_v4
- ip_hopla_v6


Dependencies
------------

User API for customer project


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.add_ip

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
