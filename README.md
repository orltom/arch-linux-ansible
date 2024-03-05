![](https://github.com/orltom/setup-workstation/workflows/check/badge.svg)
![](https://github.com/orltom/setup-workstation/workflows/install/badge.svg)

# Automated Arch Linux Setup
This ansible playbook automates my personal Arch Linux setup. All dotfiles are kept in an independent repository.

## Prerequisites
The following packages need to be installed.
```shell
dhcpd netctl iwctl dnsutils ansible git openssh wpa_supplicant ansible
```

Create SSH Key
```shell
ssh-keygen -C "$(whoami)@$(uname -n)-$(date -I)" -b 4096
```

Enabled dhcpd
```shell
sudo systemctl enable dhcpcd@${NETWORK_NAME}.service
sudo systemctl start dhcpcd@${NETWORK_NAME}.service
```

For more information see https://github.com/id101010/ansible-archlinux/blob/main/doc/INSTALL_EFI.md

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
