Ansible Role: Node.js
=========

Install Node.js and npm on CentOS servers.

Requirements
------------

Written in Ansible 1.9.*

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

### npm_packages

Install npm packages.

Default will install:

```
- gulp
- grunt-cli
```

Feel free to override it.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - juwai.nodejs

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2016 by [Juwai Limited](http://www.juwai.com).
