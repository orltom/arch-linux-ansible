![](https://github.com/orltom/setup-workstation/workflows/check/badge.svg)
![](https://github.com/orltom/setup-workstation/workflows/install/badge.svg)


This is my personal Ansible playbook to set up my developer workstation.

## Prerequisites
The following packages need to be installed.
* Install [python](https://wiki.archlinux.org/title/python)
* Install [ansible](https://wiki.archlinux.org/title/Ansible)
* Install [openssh](https://wiki.archlinux.org/title/OpenSSH)

Create SSH Key
```shell
ssh-keygen -C "$(whoami)@$(uname -n)-$(date -I)" -b 4096
```

Enabled dhcpd
```shell
sudo systemctl enable dhcpcd@${NETWORK_NAME}.service
sudo systemctl start dhcpcd@${NETWORK_NAME}.service
```

## Usage
```shell
./install
```

## Additional Information
* [Arch Linux Installation Guide](https://wiki.archlinux.org/title/installation_guide)

## Contributing
Please use the GitHub issue tracker to submit bugs or request features.

## Disclaimer
Copyright Orlando Tomás.

Distributed under the terms of the MIT license, tool is free and open source software.
