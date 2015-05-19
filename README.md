golang
=========

[![Build Status](https://travis-ci.org/gotansible/golang.svg?branch=master)](https://travis-ci.org/gotansible/golang)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-golang-blue.svg?style=flat)](https://galaxy.ansible.com/list#/roles/3837)

Installs go. Either a user specific install or a system wide install.

Requirements
------------

* Ubuntu (Debian)
* CentOS (RedHat)

Role Variables
--------------

# which version of go to install
golang_version: 1.4.2

# per user install of go ~/.gimme/...
golang_per_user: false


Dependencies
------------

None.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gotansible.golang, golang_version: 1.4.2 }

License
-------

MIT

Author Information
------------------

Created by Franklin Wise in Santa Monica, CA.
