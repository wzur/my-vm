# olek-vm
Provisioning of an Ubuntu 15.10 (Wily) virtual machine using Vagrant and Ansible.

Host are provisioned with [Ansible](http://docs.ansible.com). Main Ansible playbook is located in `provisioning/site.yml`

Virtual machine is created with [VirtualBox](https://www.virtualbox.org/)

## Requirements ##
* VirtualBox >= 4.3.26
* Ansible >= 1.9.0
* Vagrant >= 1.8.1 - this is due to the bug in Vagrant handling `systemctl` services in Ubuntu

############################
## Additional Vagrant Plugins Installation

### Install Vagrant Hostmanager Plugin
`vagrant plugin install vagrant-hostmanager`

### Start virtual machine
`vagrant up`
