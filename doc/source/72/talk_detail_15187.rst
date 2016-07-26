Under the Trenchcoat: Neutron Agent Extensions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron agents are a critical part of the Openstack networking infrastructure. The Quality of Service (QoS) effort leading up to Liberty prompted the creation of an L2 agent extension mechanism in order to provide a defined ability for agent extensions to be added to the neutron-openvswitch-agent. Other Neutron L2 agents, such as neutron-linuxbridge-agent and neutron-sriov-agent, have since been modified to utilize this extension mechanism. In the Newton cycle, this framework was generalized and implemented in Neutron's L3 base agent, with FWaaS' v2 implementation as the initial subscriber. This talk will discuss: The history of agent extensions in Neutron. A deep dive into how they function. Various use cases that take advantage of them. We will review a selection of the current use cases for agent extensions. Finally we will examine future use cases and development trends for Neutron agent extensions.


* **Nate Johnston** *(I have been working alternately as a developer, a system administrator, and a system architect since 1997.  I have been working on Openstack since September, 2014, with a focus on the Quality of Servce ("QoS") functionality within Neutron.  I have been with Comcast for 6 years and worked as a system administrator, system architect, and automation developer prior to focusing on Openstack.  I have previous positions at MCI, Cable & Wireless, Broadwing, and AOL.   I am very excited to be a part of the Openstack community.  I believe strongly that the open source paradigm not only enables the enterprise, but that it enriches the entire technology community, and indeed all mankind.  )*

* **Margaret Frances** *(I have worked on OpenStack development, almost exclusively in Neutron, since August of 2015. Prior to that, I worked as a web application developer for the networking and telecommunications group at University of Pennsylvania's Information Systems & Computing.)*

* **David Shaughnessy** *(I'm a Network Software Engineer in Intel's Networks Platform Group. I recently graduated and I'm currently working on OpenStack, specifically in Neutron with an interest in QoS. My contributions are limited at the moment but I'm hoping to learn as much as I can and contribute to OpenStack.)*
