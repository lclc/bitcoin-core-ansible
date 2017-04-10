Bitcoin Core
=========

Ansible Rule for installing the latest Bitcoin Core release using the Ubuntu PPA.
Only works on Ubuntu. Installs a systemd service to auto-restart Bitcoin Core.

Requirements
------------

There are no requirements.

Role Variables
--------------

The only variable available is defining your own bitcoin.conf file instead of using the default one from /files/bitcoin.conf.

For more information about the configuration option of Bitcoin Core see https://bitcoin.org/en/full-node and https://jlopp.github.io/bitcoin-core-config-generator/

Dependencies
------------
There are no dependencies.

Example Playbook
----------------

    - hosts: nodes
      roles:
         - { role: lclc.bitcoin-core, bitcoinConfigFile: bitcoin.conf }

License
-------

MIT

Author Information
------------------

Lucas Betschart (lucas@blockchainsource.ch)
www.blockchainsource.ch
