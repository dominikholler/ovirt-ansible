oVirt host deploy
================

This role will updates properties of the oVirt hypervisor.

Requirements
------------

 * Ansible version 2.0

Role Variables
--------------

No.

Dependencies
------------

 * ovirt-provider-ovn-driver

Example Playbook
----------------

```yaml
- name: oVirt host update
  hosts: hostname

  roles:
    - ovirt-host-update
```

License
-------

Apache License 2.0
