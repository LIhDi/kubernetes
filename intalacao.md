# Instalação
------------


- [Virtual Box](#virtual-box)
- [Vagrant](#viagrant)


## Virtual Box

```sh
sudo add-apt-repository multiverse && sudo apt-get update
sudo apt install virtualbox
sudo dpkg-reconfigure virtualbox-dkms
sudo modprobe vboxdrv
sudo apt install virtualbox-dkms
virtualbox

```

## Vagrant

1. Baixar - [Vagrant](https://www.vagrantup.com/downloads.html)

```sh
sudo dpkg -i vagrant_2.2.6_x86_64.deb
```