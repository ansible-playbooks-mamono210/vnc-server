This playbook installs VNC Server and GNOME Desktop on CentOS7.

## Install

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml
```

## Default variables

```
vnc_user: vncuser
vnc_password: vncpassword
```
