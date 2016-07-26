Create VNFs on the fly - VNF Components in Tacker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tacker is OpenStack based generic NFV Orchestrator and VNF Manager that instantiates and manages Virtual Network Functions(VNF). Virtualisation Deployment Unit(VDU) is the granular part of VNF which hosts the network functionality in the nova instance.  Currently, Tacker requires glance images or image location which has preinstalled network function like firewall etc., One of key requirements of operators is to have loose coupling software component and the underlying image.  As per ETSI MANO standard, VNF Component(VNFC) is the object which creates network function in the underlying nova instance. In this talk, we are going to walk through the following points. How Tacker adopts VNFC to instantiate the network function in VDUs. Onboarding of VNF Descriptor which embeds VNFC and deployment of VNFs. Various drivers in Tacker which supports communication with VDUs and how to introduce a new VNFC driver. Kanagaraj M<mkr1481@gmail.com>will also join the presentation.


* **Bharath Thiruveedula** *(Bharath Thriuveedula is software engineer in Imaginea Technologies Inc, Core reviewer and key contributor to the OpenStack Tacker, Heat translator projects. A contended individual who is passionate about open source technologies and an evangelist who is focussed to make his mark in the Cloud/NFV domains. He had worked on the custom solutions on the NFV Orchestration and his other interests are Containers and Distributed systems.)*

* **Manikanta Srinivas** *(Manikanta is a senior software developer in Imaginea Technologies Inc, A networking enthusiast and focussed engineer who is passionate about cloud and NFV domains, He has 5+ years of experience into development of switching and routing solutions. Currently focusing on scaling of  PaaS solution using containers and contributing to the Openstack Tacker Project.)*
