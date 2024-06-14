Role Name
=========

Role that installs [Hector J. Smith's](https://gitlab.com/hectorjsmith) Grafana-Matrix-Forwarder. Compiled with go from source and started with Systemd.

Requirements
------------

Your host needs systemd.

Role Variables
--------------

Most variables are self-explaining, or meanings can be found in the [repo](https://gitlab.com/hectorjsmith/grafana-matrix-forwarder/-/tree/main/).
Please make sure that your `grafana_matrix_forwarder_password` goes to an ansible-vault.  
`grafana_matrix_forwarder_systemd_user` is the system-user, wheras `grafana_matrix_forwarder_username` is the matrix username.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - name: usegalaxy_eu.grafana_matrix_forwarder
           vars:
             - grafana_matrix_forwarder_systemd_user: galaxy
             - grafana_matrix_forwarder_systemd_group: galaxy

License
-------

MIT

Author Information
------------------

[Mira Kuntz](github.com/mira-miracoli)
