Role Name
=========

This role configures required SAP content for Satellite.

Requirements
------------

Role Variables
--------------

satellite_username: "admin"
satellite_password: "admin"
satellite_url: "https://localhost"

sap_satellite_configure_rhel_release: "7.6"
sap_satellite_configure_architecture: "x86_64"
satellite_organization: "Default"
sap_satellite_configure_sat_subscription_name: "SKU"

Dependencies
------------

- theforeman.foreman ansible collection

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: sap_content

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
