Role Name
=========

This role will set the basic configuration of a host. This includes setting the hostname and timezone.

Requirements
------------

/

Role Variables
--------------

timezone: The timezone to set on the host. Default is "Europe/Brussels".
hostname: The hostname to set on the host. Default is the hostname defined in the inventory file.

Dependencies
------------

/

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: base_server_setup, timezone: UTC }

License
-------

/
