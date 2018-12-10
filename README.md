# techwave-ansible
A collection of Ansible playbooks used during December 2018's Techwave.

These playbooks are not production ready and should not be used in production.

For full documentation on the Palo Alto Networks Ansible modules, check out the repo [here](https://github.com/PaloAltoNetworks/ansible-pan)

Usage:
```
$ ansible-playbook deploy-servers.yml -i inventory.ini -v
$ ansible-playbook configure-ngfw.yml -i inventory.ini -v
```
