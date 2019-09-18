Role Name
=========

This ansible role creates a redis container on target hosts

Requirements
------------

Docker and python's docker module must be present on target hosts

Role Variables
--------------

See [defaults](defaults/main.yml)

Dependencies
------------

No specific dependencies, for installing Docker I highly recommend [geerlingguy.docker](https://github.com/geerlingguy/ansible-role-docker)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- hosts: servers
  become: yes
  roles:
    - role: ussrlongbow.redis_container
```

License
-------

MIT

Author Information
------------------

[Valentin Gostev](https://github.com/ussrlongbow)
