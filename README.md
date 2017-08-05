Role Name
=========

A brief description of the role goes here.

Requirements
------------

  - cristian04.ansible-ioncube
  - geerlingguy.php

Role Variables
--------------

Defaults are for PHP 7:
  - ioncube_ini_path: /etc/php/7.0/apache2/conf.d/00-ioncube.ini
  - ioncube_so_path: /usr/lib/php/20151012/ioncube/ioncube_loader_lin_7.0.so

Dependencies
------------

cristian04.ansible-ioncube

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-ioncube-conf }

License
-------

BSD

Author Information
------------------

None