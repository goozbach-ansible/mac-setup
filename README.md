Role Name
=========

Setup a mac computer for my use

Requirements
------------

* 'easy_install'
* 'pip'
* 'homebrew'

Role Variables
--------------

All of the packages each system installs (inside loops) are located in the
vars/main file

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:


    - name: setup mac environment
      hosts: mylaptop
      connection: local
    
      sudo: false
    
      roles:
          - { role: goozbach.mac_setup, is_personal: False } 


License
-------

MIT

Author Information
------------------

Derek Carter <derek@goozbach.com>  
Goozbach Infrastructure Solutions LLC http://goozbach.com
