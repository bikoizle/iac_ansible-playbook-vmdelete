VMdelete Playbook
=================

This Ansible playbook removes a virtual machine
from OpenStack.

Requirements
------------

The below python library requirements are needed on the host that executes this playbook.

openstacksdk
openstacksdk >= 0.12.0
python >= 2.7

Variables
--------------

vault: Ansible Vault path to be imported
os_user: Openstack user (included in vault)
os_passwd: Openstack user password (included in vault)
url: OpenStack URL
project: OpenStack project
project_domain: OpenStack project domain
user_domain: OpenStack user domain
vm_name: Virtual machine name

License
-------

GPL3

Author Information
------------------
