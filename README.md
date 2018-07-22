Ansible Role: OracleJDK8
=========

Install OracleJDK8 for CentOS and Ubuntu linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
site_url: http://download.oracle.com/otn-pub/java/jdk/8u181-b13/96a7b8442fe848ef90c96a2fad6ed6d1
jdk_version: 8u181
```

Dependencies
------------

None.

Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.oraclejdk8 }

License
-------

MIT
