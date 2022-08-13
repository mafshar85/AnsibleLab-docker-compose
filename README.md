# AnsibleLab
Ansible Lab with docker compose

# Quick start

## Clone repository

Clone this git repository:

`git clone https://github.com/mafshar85/AnsibleLab.git`

## Build images and run containers

`docker-compose up -d `

### Connect to **master node**:

`docker exec -it Ansile_Master /bin/zsh`

### check slave nodes from Ansile_Master node

`ping slave1`

`ssh slave1`
