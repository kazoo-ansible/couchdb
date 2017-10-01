CouchDB
=======

CouchDB Role for Kazoo Ansible

Requirements
------------

None

Role Variables
--------------

User Variables
erlang_cookie - The Erlang cookie used by all Kazoo components
couch_user - The CouchDB username
couch_password - The CouchDB password

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible, couch_user: user, couch_password: password }

License
-------

MIT

