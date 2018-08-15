# LinuxTricks

This is for repairing problem at boot
* systemctl reboot
* systemctl default
* fsck /dev/sda9

## Installing Netbeans

Convert to installer -first navigate to location of file-

chmod +x netbeans-8.2-linux.sh

Install

./netbeans-8.2-linux.sh

## Free memory

```sudo sysctl -w vm.drop_caches=3```


## Install Postman

[Instructions here](https://www.getpostman.com/docs/postman/launching_postman/installation_and_updates)

## Install woeusb
```sudo add-apt-repository ppa:nilarimogard/webupd8
sudo apt update
sudo apt install woeusb
```
#Check ports in use

```
sudo lsof -i
sudo netstat -lptu
sudo netstat -tulpn
```
