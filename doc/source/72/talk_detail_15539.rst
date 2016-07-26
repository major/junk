BaGPipe: BGP VPNs to implement Neutron virtual networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

BaGPipe is a proposition to implement Neutron virtual networking by leveraging the BGP VPN toolbox to distribute virtual networking states.BGP VPNs have been proven as a robust, scalable and flexible solution to create isolated virtual networks over IP/MPLS backbones, and have been extended to support various encapsulations (VXLAN, MPLS/UDP, ...), and support both IP and Ethernet virtual networks. The later becoming a mature solution for datacenter fabrics.We propose to reuse Neutron's existing framework for DB persistency and messaging, and reuse AMQP messaging to push to agent the more static configuration changes, thereby offloading the more chatty virtual network state updates from the message bus to the BGP control plane.This is an alternative way of delivering a rich feature set (e.g. BGPVPN interconnections, service-chaining), avoiding the addition of a full-blown SDN controllers and avoid the complexity of synchronising data between different persistency models.


* **Thomas Morin** *(Thomas has been for a bit more than 10 years at Orange Labs, mainly involved on IP and MPLS networking for backbones and datacenters, with activities ranging from architecture/ engineering studies, to lab and software development. Thomas is also active in the IETF, where he contributes to RFCs and co-chairs BESS, the working group defining evolutions of BGP VPN specifications. He has been focusing on network virtualization for IaaS since 2012 and contributes to related opensource projects, in particular in Openstack, where he co-leads the Neutron stadium BGP VPN project (networking-bgpvpn) and in OPNFV.)*
