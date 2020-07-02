[![](https://github.com/ansible-joke-programs/cmatrix/workflows/ansible-lint/badge.svg)](https://github.com/ansible-joke-programs/cmatrix/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-joke-programs/cmatrix/workflows/molecule/badge.svg)](https://github.com/ansible-joke-programs/cmatrix/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-joke-programs/cmatrix/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-joke-programs/cmatrix/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-joke-programs/cmatrix/workflows/yamllint/badge.svg)](https://github.com/ansible-joke-programs/cmatrix/actions?query=workflow%3Ayamllint)

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
ansible-galaxy install -r roles/requirements.yml -p /roles/
ansible-playbook -i localhost, -c local install.yml
```
