coffeesprout.setup
=================

Sets up the following:

* Hostname (persistently)
* Network interfaces if configured
* Disable insecure modules

Supports:

* CentOS/RHEL 7-8
* FreeBSD

This role can be used in a ansible-pull style playbook to ensure base system state.

Dependencies
------------


Example Playbook
----------------

This and dependant roles have many settings. I default to settings that make sense for me.
Your defaults will likely be different

    - hosts: servers
      roles:
      - name: coffeesprout.setup
           

License
-------

BSD

Author Information
------------------

Reach out on Github
