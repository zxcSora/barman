Role Name
=========

barman-server - Installs and configures barman to connect to DB. Make schedule rule.

Requirements
------------

unique connection for every DB. (be mindfully with defaults/main.yml)
unique replication slot for every DB. (be mindfully with defaults/main.yml)

Role Variables
--------------

defaults/main.yml

Dependencies
------------

You must use the role "barman-client" first (../roles/barman-client)

Example Playbook
----------------

../playbooks/example.yml

License
-------

GPLv3

Author Information
------------------

Derevyashkin Alexander
