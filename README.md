# [whale-es]

Installs Docker and Elasticsearch 2.4.4 Alpine containers as a service on a Ubuntu Desktop 16.04 (Xenial Xerus). 

### Usage
```
~$ sudo visudo
# ubuntu  ALL=(ALL) NOPASSWD: ALL
~$ echo 'set nocompatible' > ~/.vimrc

~$ sudo apt install -y git
~$ git clone https://github.com/jorisdevrede/whale-es.git
~$ cd whale-es
~/whale-es$ chmod 0755 setup.sh
~/whale-es$ ./setup.sh
~/whale-es$ ansible-playbook -i hosts setup.yml
```
