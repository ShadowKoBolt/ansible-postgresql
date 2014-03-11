PostgreSQL
========

Installs PostgreSQL 9.1 from ubuntu repos while passing in locale for default template setup

Requirements
------------

None

Role Variables
--------------

postgresql_locale: en_GB.UTF-8

Dependencies
------------

None

Example Playbook
-------------------------

    - hosts: default
      vars:
        - postgresql_localeL en_GB.UTF-8
      roles:
         - shadowkobolt.postgresql 

License
-------

BSD

Author Information
------------------

None
