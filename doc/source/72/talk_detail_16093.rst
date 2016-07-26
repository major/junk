Impact of DVR port-binding on Live Migration and Allowed-Address-Pairs in Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  The Distributed Virtual Router (DVR) implementation in Neutron heavily depends on theNeutron port-binding to identify the DVR service ports to configure routers on hosts, and to route traffic both East-West and North-South. Some advanced features, such as Instance Live Migration and Allowed-Address-Pairs, have adirect impact on the distributed nature of the ports and how they are bound and unboundwith Floating IP addresses. This session will target the design considerations for Live Migration andAllowed-Address-Pairs with respect to DVRs, in order to achieve more flexibleuse cases by changing the relationship between Floating IPs and how they arebound and unbound to Neutron ports.


* **Swaminathan Vasudevan** *(Swaminathan Vasudevan is a Systems Software Engineer at Hewlett Packard Enterprise where he currently works on Cloud Networking Division in OpenStack Neutron. He is an active technical Contributor of OpenStack since 2013 and have contributed code to VPNaaS and Distributed Virtual Router in Neutron. Swaminathan Vasudevan has been developing code for more than 18+ years with expertise in linux, virtualization, networking, mobility, security and convergence.)*

* **Brian Haley** *(Brian Haley is a core contributor to OpenStack Neutron, primarily focused in the L3 and DVR areas, but has particular interests in both IPv6 and cloud security.  He has been working on OpenStack since 2011, first on Nova Networking and later on Neutron.  His background is in kernel networking, both UNIX and Linux, mainly focusing on performance, scalability and IPv6 features over the past 20 years.  Brian currently works in HPE Cloud, developing and supporting HPE Helion OpenStack.)*
