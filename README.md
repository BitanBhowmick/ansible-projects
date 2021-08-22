# Ansible scripts
Ansible Scripts for automation

1. Launch an EC2 instance with Ubuntu in it.
2. Follow the below steps to install Ansible in the server.

```sh
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
ansible --version
```
3. Create the inventory file and update the details.

