ansible-role-docker
=========

[![Build Status](https://travis-ci.org/rgroten/ansible-role-docker.svg?branch=master)](https://travis-ci.org/rgroten/ansible-role-docker)

This role will install/configure Docker on a CentOS7/RH7 server

Requirements
------------

Target server(s) must have access to https://yum.dockerproject.org to download Docker

Example Playbook
----------------

    - hosts: docker-servers
      become: yes
      roles:
         - { role: rgroten.docker }

License
-------

MIT

Author Information
------------------

Ryan Groten  <rgroten@gmail.com>
