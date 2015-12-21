Role Name
=========

Ansible Galaxy Role for installing Docker Compose

Role Variables
--------------

    docker_compose_version
    Docker compose version to be installed

Dependencies
------------

    - sparkfabrik.docker

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sparkfabrik.docker-compose, docker_compose_version: 1.5.2 }

License
-------

BSD
