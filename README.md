zabbix
=========

Automate zabbix tasks.

Requirements
------------

This requires the openshift_tools rpm be installed for the zbxapi.py library.  It can be found here: https://github.com/openshift/openshift-tools under openshift_tools/monitoring/zbxapi.py for now.

Role Variables
--------------

None

Dependencies
------------

This depends on the zbxapi.py library located here: https://github.com/openshift/openshift-tools under openshift_tools/monitoring/zbxapi.py for now.

Example Playbook
----------------

  - zbx_host:
      server: zab_server
      user: zab_user
      password: zab_password
      name: 'myhost'

License
-------

ASL 2.0

Author Information
------------------

This role and its set of modules was created by the OpenShift Operations team at Red Hat, Inc.  It solves a significantly awesome problem and so I'm moving it to a consumable role with the hopes of pushing it towards upstream ansible.

Original author information:

OpenShift operations, Red Hat, Inc
