golang
=========

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
