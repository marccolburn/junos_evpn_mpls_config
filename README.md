EVPN MPLS Configuration
=========

Configure EVPN MPLS for Junos.

Requirements
------------


Role Variables
--------------
evpn_remove: bool, remove EVPN MPLS config instead of configure

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_evpn_mpls_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
