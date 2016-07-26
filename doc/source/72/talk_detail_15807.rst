Using Neutron BGP to Dynamically Route IPv6 Tenant Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron provides floating IPv4 address to allow access to instances within it's private IPv4 tenant network from the internet, but Neutron does not provide floating IPv6 address to access IPv6 tenant network because IPv6 network doesn't need to be NATed. Address Scopes will allow to define L3 routed domains instead of forcing NAT on tenant routers, while BGP will automatically advertise new created subnets. This presentation will mainly explore how to use them to dynamically route IPv6 per-tenant network. With just a little bit of routing help from Neutron BGP, we can actually ping directly in to IPv6 tenant network which is in the same address scope as IPv6 external network. In this session we can have a better understanding of Neutron IPv6 feature, Neutron BGP feature, Neutron Address Scope feature etc.


* **Hua Zhang** *(Zhang Hua is a software engineer at canonical, he joined the OpenStack community in Feb 2012 as a contributor, since then he has been focus on the network domain. He loves coding and digging into the details of various computer technologies. Now he is also increasing other domain knowledge in area's of linux kernel, HA, performance, and storage etc.)*

* **Liang Chen** *(Liang is a software engineer at Canonical and has been working on OpenStack since Grizzly Release across various components of OpenStack. Over the last 3 years, he implemented many features both contributed back upstream and company proprietary and fixed a lots of bugs primarily from the community. He was very active in the community for Heat during Havana and Icehouse cycle. Now his primary focus in on Nova and underlying virtualization technology.)*
