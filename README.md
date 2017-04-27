ansible-role-letsencrypt
=================

Ansible role for generate ssl certificate with letsencrypt

Ansible role
------------

Tested with Ansible 2.3 Ubuntu 14.04 16.04

These variables could be configured:


- **domain:**: List of domain
- **country**: Default "IT"
- **organization**: Default "Acme Inc"
- **email**: Default admin@{{ domain }}


- **acme_directory:**: The ACME directory
- **cert_days:**: 10 before the certificate will be renewed
