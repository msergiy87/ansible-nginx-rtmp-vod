# ansible-nginx-rtmp-vod

Compile from soucers nginx with rtmp or vod module and install php5-fpm 

In roles/defaults/main.yml you can set nginx version as a variable and other parameters
```
ansible-playbook -i hosts ans-rtmp.yml
ansible-playbook -i hosts ans-vod.yml
```
Test with:
Ubuntu 14.04
