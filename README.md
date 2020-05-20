# ansible-satellite

This repository includes playbook and roles for configuring a Red Hat satellite system.
Currently it's mainly used to configure satellite for supporting SAP on RHEL workflows

## Variables shared between all roles

- satellite_username
- satellite_password
- satellite_url
- satellite_organization
- satellite_ccv_name: the composite content view to create for SAP
