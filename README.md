[![Build Status](https://travis-ci.org/jnakatsui/ansible-role-s3cmd.svg?branch=master)](https://travis-ci.org/jnakatsui/ansible-role-s3cmd)

s3cmd
=====
Installs s3cmd. Does not create an s3cfg file because IAM roles should be used for access credentials.

Requirements
------------
None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jnakatsui.s3cmd }

License
-------
The source code is licensed under GPL v3
