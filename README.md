# Ansible playbook to install Magna for CentOS
## Requirements
Latest ansible version

## Run
With username and password
```
ansible-playbook -u USUARIO --ask-pass PLAYBOOK.yaml
```
With username and private key file
```
 ansible-playbook -u USUARIO --private-key RUTACLAVEPRIVADA PLAYBOOK.yaml   
```