Role Name

hoplacloud.linux_base

=========

Hopla.cloud role for ansible to install a simple Wordpress.

Requirements
------------

None.

Role Variables
--------------

username: "user"


Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd



Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.linux_base

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
