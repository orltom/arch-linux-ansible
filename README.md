[![check](https://github.com/orltom/arch-linux-ansible/actions/workflows/lint.yml/badge.svg?branch=main)](https://github.com/orltom/arch-linux-ansible/actions/workflows/lint.yml)
[![Install](https://github.com/orltom/arch-linux-ansible/actions/workflows/install.yml/badge.svg)](https://github.com/orltom/arch-linux-ansible/actions/workflows/install.yml)
[![License](https://img.shields.io/github/license/orltom/arch-linux-ansible)](/LICENSE)

# Automated Arch Linux Setup
This Ansible playbook automates the setup of my development machine running Arch Linux.

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
* [Mount an encrypted drive](https://necromuralist.github.io/posts/mount-an-encrypted-drive-using-cryptsetup/)

## Contributing
Please use the GitHub issue tracker to submit bugs or request features.

## Disclaimer
This project is licensed under the MIT License. See the LICENSE file for more details.
