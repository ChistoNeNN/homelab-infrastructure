# Homelab Infrastructure


## Overview

Infrastructure automated with Ansible.


## Stack

- Ubuntu Server
- Ansible
- Docker
- Nginx
- SSL
- Prometheus (WIP!)
- Grafana (WIP!)


## Architecture


User
 |
Nginx
 |
Docker
 |
Monitoring (WIP!)


## Deployment

Clone repository:

git clone https://github.com/ChistoNeNN/homelab-infrastructure.git


Install dependencies:

ansible-playbook playbook.yml


## Result

After deployment:

Grafana:
http://server-ip:3000

Prometheus:
http://server-ip:9090
