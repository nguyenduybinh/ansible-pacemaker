Role Name
=========

Pacemaker role

Requirements
------------

This role is written for installing and cofiguring pacemaker+corosync on Ubuntu 14.04

Role Variables
--------------

All of the variables use in this role are stored in defaults/main.yml YAML file.

Dependencies
------------

No Dependencies

Example Playbook
----------------

An example of how to use this role (for instance, with variables passed in as parameters):

Use custom inventory: 
>hosts: all
>   
>remote_user: vagrant
> 
>sudo: yes
>
>roles:
>
- pacemaker


License
-------

BSD

Author Information
------------------

BinhND

Email: binhnd.ask@gmail.com

