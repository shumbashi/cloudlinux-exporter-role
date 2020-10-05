Cloudlinux Exporter
=========

An Ansible role to install Prometheus Cloudlinux Exporter on Cloudlinux servers.

Requirements
------------

None

Role Variables
--------------

- cloudlinux_exporter_port: Port for the cloudlinux exporter to listen on

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cloudlinux_exporter_role, cloudlinux_exporter_port: 9100 }

License
-------

BSD

Author Information
------------------

Ahmed Shibani <sheipani@gmail.com>