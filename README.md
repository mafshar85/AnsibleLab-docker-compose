# AnsibleLab
Ansible Lab with docker compose

# Quick start

## Clone repository

Clone this git repository:

`git clone https://github.com/mafshar85/AnsibleLab.git`

## Build images and run containers

Enter **ansible** directory containing [docker-compose.yml](./docker-compose.yml) file.

Build docker images and run containers in the background (details defined in [docker-compose.yml](./docker-compose.yml)):

`docker-compose up -d `

### Connect to **master node**:

`docker exec -it Ansile_Master /bin/zsh`

### check slave nodes from Ansile_Master node

`ping slave1`

`ssh slave1`
