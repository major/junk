Credential and switch management CLI’s for bringing physical switches in the cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation talks about managing the switch credentials of the physical switches as part of Baremetal Network provisioning. Currently there is no way to represent the physical switches in Neutron space. After Ironic Neutron integration, for Baremetal enrollment there is a need to keep the switch credential information to plumb the networks in the Neutron upon receiving the Ironic notifications.We have written a generic client framework that can support credential management for any vendor switch and their management protocol .All the credentials information are encrypted in the DB using Barbican Client library. Administrator can create the credentials using CLI and associate the physical switch for network provisioning. Administrator can see the physical switches in the Neutron. Later Baremetal servers can be provisioned using the Ironic.  


* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **MANJUNATH PATIL** *(Working as a software engineer at HP India. Major code contributor to networking-l2gw. Active code contributor to openstack neutron.)*

* **Nalina Maraiah** *(Currently working in Openstack ironic project with 2.5 years of experience in networking. Previously had worked in software defined network application Hpconverged control which is l2gateway discover and management project which provides communication for NSX hosted VXLAN booted Virtual machines attached to Logical switches with vlan configured unmanaged Baremetals. This projects brings an idea of extending ironic provisioned baremetals in VLAN network communicate with VXLAN booted virtual machines hosted on openstack compute nodes. Aspire to expertise my career in Openstack and bring in lot more inventions to provide best solutions to customers and own the success.)*
