![](https://github.com/orltom/setup-workstation/workflows/check/badge.svg)

# Setup Workstation
Arch linux developer workstation setup with ansible.
```
ansible-playbook site.yml --ask-become-pass -u ${USERN_NAME}
```


## Prerequisite
```
sudo pacman -S python ansible openssh
ansible-galaxy install -r requirements.yml
```

## DOT files
https://github.com/orltom/linux-user-configs

## Installation Hints
* /sys/firmware/efi exists means system uses UEFI
* https://wiki.archlinux.de/title/GRUB

## Disclaimer
This software is provided as source code under an Apache 2.0 license.

## Contributing
If you are missing a feature or see a bug. Please report it.

