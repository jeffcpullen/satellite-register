# satellite-register

Ansible 2.8 required if PURGE is set to true

In order to use this role you should define the following variables. 


KATELLO_PACKAGE: katello-ca-consumer-latest.noarch.rpm
SATELLITE_FQDN: sat6.homelab.work
SATELLITE_KEY: rhel-7-server-minimal
SATELLITE_ORG: homelab_infra
REPOSITORIES:
  - rhel-7-server-rpms
  - rhel-7-server-extras-rpms
  - rhel-server-rhscl-7-rpms

# This will remove any repos not listed above
PURGE: yes

