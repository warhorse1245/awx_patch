Role Name
=========

This role has been created to take advantage of various learnings in our patch practice.

Requirements
------------

A stout heart, a good ship, and 50 brave men to sail her.

Role Variables
--------------

vm_server - VMWare/vSphere instance to interact with
vm_user - VMWare user account
vm_password - VMWare user password
snow_instance - Instance of ServiceNow to interact with
stop_services - Services that will be stopped before patching
yum_disabled_repos - Repos disabled by patching process
yum_exclude: any packages that should be excluded from patching

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

We are Legion.  This playbook is the result of collaboration between Chris Thurman, Dan Swan, Randal Harisch, Wayne Hewitt, and Ryan McGill.
