devstack-trove
==============
Devstack and Trove localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-trove
```
$git clone https://github.com/svashu/devstack-trove.git
```

Copy localrc from devstack-trove to devstack
```
$ cp devstack-trove/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```
