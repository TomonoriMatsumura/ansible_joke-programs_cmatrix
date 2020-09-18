[![](https://github.com/ansible-joke-programs/cmatrix/workflows/build/badge.svg)](https://github.com/ansible-joke-programs/cmatrix/actions?query=workflow%3Abuild)

# Ansible Playbook - CMatrix

## Description

Installs [CMatrix](https://github.com/abishekvashok/cmatrix) for CentOS7/CentOS8.

## How To install

1. Install ansible

```
sudo yum -y install epel-release
sudo yum -y install ansible
```

2. Execute playbook as root

```
git clone https://github.com/ansible-joke-programs/cmatrix.git
cd cmatrix
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml
```
