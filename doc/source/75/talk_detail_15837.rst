Security Group for Baremetal - How to ensure more safety and performance for baremetal servers?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session explains security group feature without performance degradation for baremetal servers. Currently Ironic and Neutron are working on implementation of multi-tenant network for baremetal servers. Having implemented the feature, tenant network for baremetals can be isolated each other in the same way as VMs. However there is a critical gap between baremetals and VMs in terms of security area in production environment. Baremetals does not have L2 layer security feature same as security group for VMs, that is to say baremetal cannot filter packets which sent from same subnet. Therefore, we propose security group implementation without performance degradation for baremetal servers.


* **Takanori Miyagishi** *(Software Engineer, Fujitsu Limited  )*
