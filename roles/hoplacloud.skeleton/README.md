hoplacloud.skeleton
=========

Hopla.cloud role for awx to prepare a project.


Requirements
------------

Linux server Ubuntu 18.04

Role Variables
--------------

- username : customer ID
- public_key : Public key to add in project
- lan1(bool) : create lan1 if true
- lan2(bool) : create lan2 if true
- router(routeros|vr|false) : deploy a router



Dependencies
------------

User API for customer project


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.skeleton

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
