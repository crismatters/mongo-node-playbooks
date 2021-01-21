The playbook ```orch.yml``` will install and configure the NodeJS and MongoDB packages.
## Requisites.
Install Ansible. [Installation 
Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) 

Establish a root password and run using the BECOME authentication method.
 
``` ansible-playbook orch.yml -K ```
#### Note: Be sure that a password has been provided for the root user.

