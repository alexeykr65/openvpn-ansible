# Ansible playbook for configure Openvpn on Ubuntu 18.04

### Prerequisite
- Add user 'adminvpn' on ubuntu 18.04  
- Enable sudo for adminvpn
- Install python (exist /usr/bin/python)

### How to use
After run playbook, create users for openvpn:
- login to ubuntu as `adminvpn`
- change directory `cd easyrsa`
- run script  `sudo ./create-users.sh name_user`
- copy file *name_user.ovpn*  from directory *~/client-configs/files/* to local and import to openvpn


