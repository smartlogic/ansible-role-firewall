Firewall
=========

Open ports based on a variable.

## Install to requirements.yml

```
- src: git+git@github.com:smartlogic/ansible-role-firewall
  name: firewall
  version: 0.1.1
```

Requirements
------------

None

Role Variables
--------------

* `firewall_ports` : list of ports that should be opened

Dependencies
------------

None

Example Configuration
----------------


```yaml
firewall_ports:
  - rule: allow
    port: http
  - rule: allow
    port: https
  - rule: allow
    port: 8080
    src: 127.0.0.1
```

License
-------

MIT

Author Information
------------------

SmartLogic. https://smartlogic.io
