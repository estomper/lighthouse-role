lighthouse-role
=========

This role can install LightHouse on EL

Role Variables
--------------

|vars|description|
|:-:|:-:|
| lighthouse_git | Git repository LightHouse |
| lighthouse_dir | Installation directory for LightHouse |
| lighthouse_port | Port for LightHouse |
| nginx_user_name | Nginx User for LightHouse |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lighthouse-role }

License
-------

MIT

Author Information
------------------

Alexander Boboshin
