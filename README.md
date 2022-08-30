Lighthouse-role
=========

устанавливает nginx и git, скачивает lighthouse  в заданную папку, создает простейший файл настроек вебсервера и меняет в nginx.conf пользователя на root.

Requirements
------------

Centos 7.


Role Variables
--------------


lighthouse_location:

lighthouse_src:


Example Playbook
----------------
```
    - hosts: servers
      roles:
         - { role: lighthouse, when: ansible_system == 'Linux' }
```
License
-------

XYZ

Author Information
------------------

XYZ
