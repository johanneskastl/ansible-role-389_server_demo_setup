![Ansible Lint](https://github.com/johanneskastl/ansible-role-389_server_demo_setup/workflows/Ansible%20Lint/badge.svg)

389_server_demo_setup
=========

Setting up a 389 directory server for demo usage

Requirements
------------

None.

Role Variables
--------------

`slapd_root_password`: (Required) Server administration password for the 389 directory server.
`ldap_base`: Suffix to be used for the demo content (Default: `dc=training,dc=b1-systems,dc=de`).
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.389_server_demo_setup' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
