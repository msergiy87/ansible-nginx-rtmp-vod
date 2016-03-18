# ansible-nginx-rtmp-vod

Compile from soucers nginx with rtmp or vod module and install php5-fpm

Distros tested
------------

Currently, this is only tested on Ubuntu 14.04. It should theoretically work on older versions of Ubuntu or Debian based systems.

Usage
------------

In roles/defaults/main.yml you can set nginx version as a variable and other parameters
```
ansible-playbook -i hosts ans-rtmp.yml
ansible-playbook -i hosts ans-vod.yml
```
