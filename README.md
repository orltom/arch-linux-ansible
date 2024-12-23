[![check](https://github.com/orltom/arch-linux-ansible/actions/workflows/lint.yml/badge.svg?branch=main)](https://github.com/orltom/arch-linux-ansible/actions/workflows/lint.yml)
[![Install](https://github.com/orltom/arch-linux-ansible/actions/workflows/install.yml/badge.svg)](https://github.com/orltom/arch-linux-ansible/actions/workflows/install.yml)

# Automated Arch Linux Setup
This ansible playbook automates my personal Arch Linux setup. All dotfiles are kept in an independent repository.

## Prerequisites
The following packages need to be installed.
* Install [python](https://wiki.archlinux.org/title/python)
* Install [ansible](https://wiki.archlinux.org/title/Ansible)
* Install [openssh](https://wiki.archlinux.org/title/OpenSSH)
* Create SSH keys via `ssh-keygen`

## Usage
```shell
./install
```

## Additional Information
* [Arch Linux Installation Guide](https://wiki.archlinux.org/title/installation_guide)
* [Disk encryption](https://github.com/id101010/ansible-archlinux/blob/main/doc/INSTALL_EFI.md)

## Contributing
Please use the GitHub issue tracker to submit bugs or request features.

## Disclaimer
Copyright Orlando Tomás.

Distributed under the terms of the MIT license, tool is free and open source software.
