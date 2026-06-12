# Homelab Infrastructure


## Overview

Infrastructure automated with Ansible.


## Stack

- Ubuntu Server
- Ansible
- Docker
- Nginx
- SSL
- Prometheus
- Grafana


## Architecture


User
 |
Nginx
 |
Docker
 |
Monitoring


## Deployment

Clone repository:

git clone https://github.com/ChistoNeNN/homelab-infrastructure.git


Install dependencies:

ansible-playbook playbook.yml


## Result

After deployment:

Grafana:
http://grafana.domain.com

Prometheus:
http://prometheus.domain.com
