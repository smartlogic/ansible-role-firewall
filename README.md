Firewall
=========

Open ports based on a variable.

Requirements
------------

None

Role Variables
--------------

* `firewall_ports` : list of ports that should be opened

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: smartlogic.firewall }

License
-------

MIT

Author Information
------------------

SmartLogic. https://smartlogic.io
