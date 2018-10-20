tcthien.ansible_docker_registry
===============================

Configures and runs Docker Registry. Supporting storage: Amazon S3, Filesystem & Azure

Requirements
------------
See [meta/main.yml](meta/main.yml)


Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - tcthien.ansible_docker_registry
```

License
-------

MIT

Author Information
------------------
Original author: Andrew Rothstein <thientran1986@gmail.com>
Add support for filesystem & azure: Thien Tran <thientran1986@gmail.com>