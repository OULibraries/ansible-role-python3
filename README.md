OULibraries.python3
=========

Role to standardize install and config of Python 3 packages

Requirements
------------
TBD

Role Variables
--------------

See `defaults/main.yml`.  

The most useful variables will generally be `python3_pkgs` and `python3_pip_pkgs`. 

Dependencies
------------
TBD

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: all
      vars:
        python3_pip_pkgs: 
          - docker-compose
      roles:
         - OULibraries.python3

License
-------

BSD

Author Information
------------------

Written for OU Libraries
