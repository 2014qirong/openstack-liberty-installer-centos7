# openstack-liberty-installer-centos7
the docs for openstack installation

This installer was made to automate the tasks of creating a virtualization infrastructure based on OpenStack. So far, There are two "flavors" for this installer: One for Centos 7 and one for Ubuntu 14.04 LTS.

All two versions produce a fully production-usable OpenStack. You can use this installer to make a single-node all-in-one OpenStack server, or a more complex design with controller and compute nodes.

In summary, this installer can produce an OpenStack virtualization service completely usable in production environments, however, remember that the "bugs" factor don't depend solely on us. From time to time OpenStack packages can bring us some bugs too. We are using rpm/deb packages from Ubuntu and Redhat repositories and they can have their own bugs.
