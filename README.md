# Ansible playbook to install Magna for CentOS
## Requirements
Latest ansible version http://docs.ansible.com/ansible/latest/intro_installation.html

Create host inventory and variables --> hosts.ini <-- 

Create "project" folder and put frontend project (Without .git folder)
### Before run this script edit project config files!

## Run
With username and password
```
ansible-playbook -u USER --ask-pass PLAYBOOK.yaml -i hosts.ini
```
With username and private key file
```
 ansible-playbook -u USER --private-key RUTACLAVEPRIVADA PLAYBOOK.yaml -i hosts.ini
```