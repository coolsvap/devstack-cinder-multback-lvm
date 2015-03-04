devstack-cinder-multback-lvm
============================
Devstack with Cinder and multiple LVM backends

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

Clone devstack-cinder-multback-lvm
```
$git clone https://github.com/svashu/devstack-cinder-multback-lvm.git
```

Copy localrc from devstack-cinder-multback-lvm to devstack
```
$ cp devstack-cinder-multback-lvm/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```
