ansible-mapr-loopbacknfs
=========

Install and configure MapR loopbacknfs (aka POSIX client).

Requirements
------------

MapR 5.0 cluster. This package should be installed not on cluster nodes, but on edge nodes, with the MapR client installed and configured.

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: edge
      roles:
         - { role: mapr-loopbacknfs }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
