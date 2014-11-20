mesos-zeroconf
==============

Hacked up proof of concept that discovers mesos clusters on the local network

Just install mesos on your system and run mesos-zeroconf.

The first instance on the network will start a master all subsequent
instances will start slaves that connect to the master.
