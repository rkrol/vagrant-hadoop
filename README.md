vagrant-hadoop
==============

To start Hadoop cluster with Vagrant :
- clone this repository
- [install vagrant](http://www.vagrantup.com/) 
- vagrant box add base-hadoop http://files.vagrantup.com/lucid64.box
- vagrant up
- vagrant ssh master
- sudo ssh 192.168.1.11 (to 14) and accept authorization
- cd /opt/hadoop-1.1.1/bin
- sudo ./hadoop namenode -format
- sudo ./start-all.sh
