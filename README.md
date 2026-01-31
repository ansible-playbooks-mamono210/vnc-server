[![CircleCI](https://dl.circleci.com/status-badge/img/gh/ansible-playbooks-mamono210/vnc-server/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/ansible-playbooks-mamono210/vnc-server/tree/main)

# Ansible Playbook - vnc-server

## Introduction

This program installs [VNC Server](https://tigervnc.org) on CentOS Stream 9.

## How To install

1. Install ansible and git

```
sudo dnf -y install git
sudo dnf -y install ansible
```

2. Execute playbook as root

```
git clone https://github.com/ansible-playbooks-mamono210/vnc-server.git
cd vnc-server
ansible-playbook -i localhost, -c local install.yml
```
