# Ansible role to create a self signed SSL/TLS certificate

Creates a local certificate authority (CA) and self signed certificate
for testing or local services

# Variables

see `defaults\main.yaml`

`cert_dir` - certificates directory
`key_dir` - private key directory
`common_name` - CN for certificate to be assigned to
`cert_length_days` - duration of certificate (days)