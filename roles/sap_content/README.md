Role Name
=========

This role configures required SAP content for Satellite.

Requirements
------------

Role Variables
--------------

sap_content_rhel_release: "7.6"
sap_content_architecture: "x86_64"
sap_content_sat_username: "admin"
sap_content_sat_password: ""
sap_content_sat_url: "https://localhost"
sap_content_sat_organization: "Default"

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
