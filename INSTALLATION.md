```
sudo pacman -S python ansible openssh vi

ssh-keygen -C "$(whoami)@$(uname -n)-$(date -I)" -b 4096 

sudo systemctl enable dhcpcd@${NETWORK_NAME}.service
sudo systemctl start dhcpcd@${NETWORK_NAME}.service



```
