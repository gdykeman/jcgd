Installation Instructions
-----

[RedHat Openstack Platform Director Installation Guide](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux_OpenStack_Platform/7/html/Director_Installation_and_Usage/chap-Introduction.html)

1. Edit /etc/rhsm.conf -> add proxy
2. Subscription-manager register --username _username_ --password _password_ --auto-attach
3. sudo subscription-manager repos --enable=rhel-7-server-rpms --enable=rhel-7-server-optional-rpms --enable=rhel-7-server-extras-rpms --enable=rhel-7-server-openstack-7.0-rpms --enable=rhel-7-server-openstack-7.0-director-rpms

