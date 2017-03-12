# [whale-es]

Installs Docker and Elasticsearch containers (2.4.4-alpine or 5.2.2-alpine) as a service on a Ubuntu Desktop 16.04 (Xenial Xerus). 

### Usage
```
~$ sudo visudo
ubuntu  ALL=(ALL) NOPASSWD: ALL

~$ sudo apt install -y git
~$ git clone https://github.com/jorisdevrede/whale-es.git
~$ cd whale-es
~/whale-es$ chmod +x setup.sh
~/whale-es$ ./setup.sh
~/whale-es$ ansible-playbook -i hosts setup.yml
```
