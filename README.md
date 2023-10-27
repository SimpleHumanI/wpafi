## description
cli script for easy to use wpa_supplicant

## requirements
```bash
Archlinux
$ sudo pacman -S wireless_tools wpa_supplicant dhclient procps-ng coreutils

Debian
$ sudo apt install wireless-tools wpasupplicant isc-dhcp-client procps coreutils
```

## Quick start
```bash
in this example we add new configurarion then run script
 
$ git clone https://github.com/SimpleHumanI/wpafi.git
$ cd wpafi
$ sudo ./wpafi -n tplink=12345678 -i eth0
$ sudo ./wpafi
```
