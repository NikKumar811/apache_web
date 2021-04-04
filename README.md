Role Name
=========

A role is used to configure apache web server on linux OS

Requirements
------------

You must need to configure yum before running this role.

Role Variables
--------------

pkgs:
  - httpd
  - firewalld

rule:        # allowing ports 
  - http    
  - https

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - myapache

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
