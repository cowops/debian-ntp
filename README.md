Debian-NTP
==========

Network Time Protocol

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

ntp:
    server: fr.pool.ntp.org

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-ntp, ntp.server: fr.pool.ntp.org }

Tasks
-----

  - Install [ntp](http://www.ntp.org/)
  - Setup with [french ntp pool](http://www.pool.ntp.org/fr/)

License
-------

BSD