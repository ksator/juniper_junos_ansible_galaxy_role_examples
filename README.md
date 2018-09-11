## About this repo
This repository provides Ansible playbooks examples using the Juniper.junos role from galaxy.

## Usage 

From ubuntu 16.04  

Install requirements: 
```
sudo apt-get update
sudo apt-get upgrade
sudo pip install ansible==2.5.2.0 junos-eznc jxmlease jsnapy
ansible-galaxy install Juniper.junos,2.1.0
```
Verify:
```
ansible --version
ansible-galaxy Juniper.junos list
pip list | grep 'eznc\|jsnapy\|jxmlease'
```
Clone the repository: 
```
git clone https://github.com/ksator/juniper_junos_ansible_role_examples.git
cd juniper_junos_ansible_role_examples/
ls
```
Each directory has it's own README.md file with instructions.  

## Network topology

3 EX devices connected in a triangle topology
