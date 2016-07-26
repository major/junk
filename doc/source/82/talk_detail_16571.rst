A generic network driver mechanism for Neutron -- One driver to bind them all
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron provides an extension mechanism by which network vendors can register their drivers to support the functionality of Switching, Routing and Security on their devices instead of on LB/OVS and Namespaces. Even though this works, a service provider or enterprise customer still has take care of installing the appropriate drivers and maintaining them across versions. In a mixed network vendor environment this problem gets more accentuated. The current proposal solves this issue by introducing a genric driver mechanism in the Neutron plugin flow  for L2, L3, FwaaS, LB and VPN services. This will result in day zero support of network vendor devices adhering to standards.


* **Sarath Chandra Mekala** *(Sarath is a hardcore Java progarammer and has over 13 years of industry experience in building scalable and distributed Network Management Systems. He is currently working on integrating Juniper's Switching and Security devices with Openstack Neutron. The following are his areas of interest: - Neutron (ML2 and L3) - Neutron-FwaaS - Ceilometer  He blogs @ http://sarathblogs.blogspot.in/)*

* **Chandan Dutta Chowdhury** *(Tech Lead - Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ)*

* **Sriram Subramanian** *(Director - Software Engineering, Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ Blogger - http://www.innervoice.in/blogs Speaker - https://goo.gl/JYGcFo)*
