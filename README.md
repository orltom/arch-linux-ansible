![](https://github.com/orltom/setup-workstation/workflows/check/badge.svg)

An Ansible playbook to install Arch Linux


## Prerequisites
The following packages need to be installed.
* Install [python](https://wiki.archlinux.org/title/python)
* Install [ansible](https://wiki.archlinux.org/title/Ansible)
* Install [openssh](https://wiki.archlinux.org/title/OpenSSH)

Create SSH Key
```
ssh-keygen -C "$(whoami)@$(uname -n)-$(date -I)" -b 4096
```

Enabled dhcpd
```
sudo systemctl enable dhcpcd@${NETWORK_NAME}.service
sudo systemctl start dhcpcd@${NETWORK_NAME}.service
```

## Usage
```
./install
```

## Installation Hints
* /sys/firmware/efi exists means system uses UEFI


## Contributing
Please use the GitHub issue tracker to submit bugs or request features.

## Disclaimer
Copyright Orlando Tomás.

Distributed under the terms of the MIT license, tool is free and open source software.