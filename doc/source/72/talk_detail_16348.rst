War Story: How we built a scalable and reliable Neutron driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron’s northbound API can be integrated with networking backends such as SDN controllers via either monolithic core plugins or ML2 drivers. Each option provides a well defined interface, but how these integrations interact with their respective backends varies, sometimes significantly, trying to solve a common set of well known challenges: Reliability Scalability Availability State synchronization and consistency For several releases, Cisco has provided an ML2 mechanism driver integrating Neutron with our ACI SDN controller. After many successful customer deployments and lessons learned regarding its limitations, we decided to revisit our driver’s architecture. We want to share with the developer and operator communities our story of how we designed a Neutron driver that tackles the above problems through the use of asynchronous calls and eventual consistency. We will describe the options considered, the choices made, the results achieved, and some potential Neutron enhancements.


* **Ivar Lazzaro** *(I am a software engineer driven by genuine passion and curiosity for computer science. I have mostly been focusing on building fast and scalable distributed systems, in particular for network centric environments. Dived into Openstack as part of my Master thesis, my interest in it kept growing over time. I'm designer, developer, and maintainer of multiple Neutron's plugins, ML2 drivers and CI systems. I've also recently started my contribution as a core developer of the Group Bases Policy project in Openstack.)*

* **Robert Kukura** *(I am a Principal Engineer in Cisco's Noiro Networks group, working on OpenStack Neutron and other open source projects. My current focuses are Neutron's ML2 core plugin and Group Based Policy. I've contributed to OpenStack since joining Red Hat in late 2011, and have served as a core reviewer in the Neutron project. Throughout my career developing distributed systems, ranging from digitial audio processors to large defense systems, I've been a strong advocate of and contibutor to open standards and open source.)*

* **Amit Bose** *(Amit is a Techinical Leader at Cisco Systems and contributes primarily to the Group Based Policy project and Neutron.)*
