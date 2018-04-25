Java
====

Install OpenJDK Java 8.

Requirements
------------

No requirements.

Role Variables
--------------

* `java`
  * `version` - The Java version to install

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: reform.java, java: { version: "1.8.0"} }

License
-------

MIT

Author Information
------------------

HMCTS Reform Programme
