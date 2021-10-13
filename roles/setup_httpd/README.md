Role Name
=========

This role sets up Apache Web Server and creates index.html.

Requirements
------------

None!

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None!

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: setup_httpd, greeting_reply: "Valar Dohaeris" }

License
-------

Do whatever you want

Author Information
------------------

Vladislav Y.
