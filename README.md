# Ansible Role: Desktop
An Ansible Role that installs tools on Linux Workstations.

## Software packages
* gnome tweak tool
* libreoffice
* teams
* teamviewer
* mailspring
* chromium
* visual studio code
* virtualbox 
* vagrant
* packer
* gitkraken
* vimwiki
* qemu
* remmina
* gimp
* nextcloud client
* keepassxc


## Dependencies
None.

## Example Playbook
- hosts: localhost
  gather_facts: yes
  connection: local
  roles:
  - ansible-role-desktop