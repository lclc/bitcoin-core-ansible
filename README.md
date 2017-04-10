Bitcoin Core
=========

Ansible Rule for installing the latest Bitcoin Core release using the Ubuntu PPA.
Only works on Ubuntu. Installs a systemd service to auto-restart Bitcoin Core.

Requirements
------------

There are no requirements.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------
There are no dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: nodes
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache

Author Information
------------------

Lucas Betschart (lucas@blockchainsource.ch)
www.blockchainsource.ch
