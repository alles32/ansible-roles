DD SSS D Ansible Roasdasdasdle: Apache 2.x
==========================

[![Build Status](https://travis-ci.org/Aplyca/ansible-role-apache.svg?branch=master)](https://travis-ci.org/Aplyca/ansible-role-apache)
[![Circle CI](https://circleci.com/gh/Aplyca/ansible-role-apache.png?style=badge)](https://circleci.com/gh/Aplyca/ansible-role-apache)

Ansible Role that installs an configure Apache 2.x on Debian/Ubuntu.

Requirements
------------

Use hash behavior for variables in ansible.cfg
See example: https://github.com/Aplyca/ansible-role-apache/blob/master/tests/ansible.cfg
See official docs: http://docs.ansible.com/intro_configuration.html#hash-behaviour

Installation
------------

Using ansible galaxy:
```bash
ansible-galaxy install Aplyca.Apache
```
You can add this role as a dependency for other roles, add the role to the meta/main.yml file of your own role:
```yaml
dependencies:
  - { role: Aplyca.Apache }
```

Role Variables
--------------

See default variables: https://github.com/Aplyca/ansible-role-apache/blob/master/defaults/main.yml

Dependencies
------------

None.

Testing
-------
Using Vagrant:

```bash
tests/vagrant.sh
```
Using Docker:

```bash
tests/docker.sh
```

You should see an Apache server on http://localhost:8080

License
-------

MIT / BSD

Author Information
------------------

Mauricio Sánchez from Aplyca SAS (http://www.aplyca.com)
