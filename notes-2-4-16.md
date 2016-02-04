
Subnets
=======

Provision - vlan 145 - 192.168.145.0/24
-----

Management - vlan 150 - 192.168.150.0/24
------

1. Edit /etc/rhsm.conf -> add proxy
2. Subscription-manager register --username _username_ --password _password_ --auto-attach
3. sudo subscription-manager repos --enable=rhel-7-server-rpms --enable=rhel-7-server-optional-rpms --enable=rhel-7-server-extras-rpms --enable=rhel-7-server-openstack-7.0-rpms --enable=rhel-7-server-openstack-7.0-director-rpms

