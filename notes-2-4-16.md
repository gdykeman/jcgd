
Subnets
=======

Provision - vlan 145 - 192.168.145.0/24
-----

Management - vlan 150 - 192.168.150.0/24
------

1. Edit /etc/rhsm.conf -> add proxy
2. Subscription-manager register --username <username> --password <password> --auto-attach
3.
subscription-manager repos --disable=*
subscription-manager repos --enable=rhel-7-server-rpms
subscription-manager repos --enable=rhel-7-server-rh-common-rpms
subscription-manager repos --enable=rhel-7-server-openstack-7.0-rpms
