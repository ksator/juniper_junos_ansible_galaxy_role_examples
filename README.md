## About this repo
This repository provides an Ansible playbook that render the Junos configuration files without commiting changes on Junos devices

## Repository structure
- [ansible inventory file](hosts)
- [junos template](template.j2)
- [host specific variables](host_vars)
- [group specific variables](group_vars)
- [ansible playbook](playbook.yml)
- [directory with rendered template](rendered_template)
- [directory with candidate configuration files](candidate_config)

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
pip list
```
Clone the repository: 
```
git clone https://github.com/ksator/juniper_junos_ansible_role_examples.git
cd juniper_junos_ansible_role_examples/
```

