ansible-role-letsencrypt
=================

Ansible role for generate ssl certificate with letsencrypt

Ansible role
------------

These variables could be configured:


- **domain_name:**:
- **csr_subj**:
- **acme_directory_prod:**: The ACME directory to use for production environment
- **acme_directory_test:**: The ACME directory to use for test environment
- **cert_days:**: 10 before the certificate will be renewed
