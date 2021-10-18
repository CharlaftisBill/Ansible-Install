# Ansible-Install

## Install Ansible using the following commands (Ubuntu) :

Follow the above commands:

```bash
sudo -i
apt update
apt upgrade
apt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
exit
```

Test that installation was fine using the command:

```bash
ansible --version
```

If everything worked as expected then the result should be similar to:

```bash
ansible 2.9.6
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/ubuntu/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.8.10 (default, Jun  2 2021, 10:49:15) [GCC 9.4.0]
```
