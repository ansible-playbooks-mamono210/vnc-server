[![](https://github.com/ansible-playbooks-centos7/vnc-server/workflows/ansible-lint/badge.svg)](https://github.com/ansible-playbooks-centos7/vnc-server/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-playbooks-centos7/vnc-server/workflows/molecule/badge.svg)](https://github.com/ansible-playbooks-centos7/vnc-server/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-playbooks-centos7/vnc-server/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-playbooks-centos7/vnc-server/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-playbooks-centos7/vnc-server/workflows/yamllint/badge.svg)](https://github.com/ansible-playbooks-centos7/vnc-server/actions?query=workflow%3Ayamllint)

# Ansible Playbook - vnc-server

## Introduction

This program installs [VNC Server](https://tigervnc.org) on CentOS7.

## How To install

1. Install ansible and git

```
sudo yum -y install epel-release git
sudo yum -y install ansible
```

2. Execute playbook as root

```
git clone https://github.com/ansible-playbooks-centos7/vnc-server.git
cd vnc-server
ansible-playbook -i localhost, -c local install.yml
```
