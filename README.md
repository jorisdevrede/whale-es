# [whale-es]
Installs Docker and Elasticsearch containers (2.4.4-alpine or 5.2.2-alpine) as a service on a Ubuntu Desktop 16.04 (Xenial Xerus). This setup can be used inside a virtual machine. 

### Installation
This installation asumes a clean Ubuntu install, which can be found here: http://releases.ubuntu.com/16.04/ubuntu-16.04.2-desktop-amd64.iso. It also asumes an 'ubuntu' default account. When Ansible is already installed, make sure it is at version 2.1 or higher.
```
~$ sudo visudo
ubuntu  ALL=(ALL) NOPASSWD: ALL

~$ sudo apt install -y git
~$ git clone https://github.com/jorisdevrede/whale-es.git
~$ cd whale-es
~/whale-es$ ./setup.sh
~/whale-es$ ansible-playbook -i hosts setup.yml
```
