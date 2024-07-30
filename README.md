# System health monitoring with Prometheus, Node exporter and Grafana

## Requirements
Ensure the managed nodes have the following requirements met
- Docker 
- Docker compose
- Python 3
Ensure the Control node have the following requirements met
- Python 3
- Ansible > 2.16

## Install
1. Install [docker](https://docs.docker.com/engine/install/) on your Managed Nodes 
2. Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on your Control Node  


## Usage
```
ansible-playbook -i hosts.ini playbook/system-monitoring.yml -K
```
**NOTE:** The user will be prompted to enter the password of the control node to proceed with the provisioning.


### Happy Monitoring