# Prerequisites
- A Linux workstation (I am using Ubuntu 20.04) with At least 8 GB of RAM and 15 GB of free hard disk space for the virtual machines.

- Vagrant 2.2.6
```
wget https://releases.hashicorp.com/vagrant/2.2.9/vagrant_2.2.9_x86_64.deb
sudo apt install ./vagrant_2.2.9_x86_64.deb
```
- VirtualBox 6.1.6 or above
```
sudo apt install virtualbox
```
- Ansible 2.9.6
```
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

# Schema of the network
- vboxnet0: 192.168.50.1
- K8S-M-1: 192.168.50.11
- K8S-N-1: 192.168.50.12
- K8S-N-2: 192.168.50.13

# Quick Start
For a quick start with all the prerequisites on your machine and **you want to use default settings**, execute this commands on your machine:
```
vagrant up
```
