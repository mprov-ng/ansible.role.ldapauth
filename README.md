Role Name
=========

A simple role to configure ldap authentication.

Requirements
------------

None


Role Variables
--------------

see [defaults file](defaults/main.yml)

Dependencies
------------

None

Example Playbook
----------------
```yaml
- hosts: all
  remote_user: root
  roles:
    - ansible.role.ldapauth
```

License
-------

[Apache](LICENSE)

Author Information
------------------
Jason Williams <jasonw@jhu.edu>
