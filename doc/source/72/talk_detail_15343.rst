IP-Multicast in an Openstack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you planning to use applications that use IP multicast in your OpenStack cloud – e.g IPTV? Are you planning to use high volumes of IP multicast? Are you planning to automate also the network resources required to run IP multicast from the viewpoint of an infrastructure provider? There is currently no multicast API available in OpenStack to declare resources needed by an application. As a result IP multicast runs only in L2 networks. But how to manage L3 multicast routing? High volumes of IP multicast can only be handled efficient if offloaded to the physical network infrastructure – but this offloading consumes a part of the hardware resources of the network equipment. This offloading needs to be controlled by the infrastructure provider. To do this, information is needed from tenants via an API. The goal of the talk is to collect enough interested parties to work on a blueprint for an OpenStack Multicast API, which covers L2, L3, cloud local and global network aspects.


* **Ralf Trezeciak** *(As a Senior Network Architect, Ralf working on data center/cloud network virtualization and Software Defined Networking technologies at Deutsche Telekom. He is currently working on the network architecture for a Openstack based NFV cloud at Deutsche Telekom.)*
