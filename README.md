create docker user
=========

Role for creating a user for executing docker

Requirements
------------

Only tested with the condition below:
- CentOS7 and RHEL7
- Ansible 2.8


Role Variables
--------------
None

Dependencies
------------

Role docker should be called before calling this role

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: create-docker-user }

License
-------

BSD

Author Information
------------------

nm7-jp
