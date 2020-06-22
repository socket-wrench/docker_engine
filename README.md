# Docker Engine setup Ansible Playbook

Ansible playbook to setup a docker engine using docker-ce and docker-compose on centos 8

## Prerequisites

  * ansible (tested on 2.9.9)
  * ability to connect to github.com and docker.com
  * centos >=8

## Usage

Either call the file with the ansible playbook command like so:
   # sudo ansible-playbook docker_engine.yml

Or run the playbook as an executable.
   # chmod +x docker_engine.yml
   # ./docker_engine.yml
