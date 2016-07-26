"REST API driven Compute Node configuration for enabling EPA based placement of VNFs by MANO"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

VNFD templates allow for specifying requirements for VNF workloads that leverage features of a compute node such as NUMA topology, SR-IOV, PCI-Passthrough, Huge pages and CPU pinning. This allows for Enhanced Platform Awareness(EPA) driven placement of VNF workloads to achieve better performance. However the cloud administrator is required to pre-configure computes to enable for EPA usage. The manual steps involved here are not scalable considering size of typical Telco clouds and can be error prone.  This talk introduces a REST-API driven ability to configure/modify compute nodes to enable for EPA usage. OpenStack Tacker (or other ETSI MANO clients) will be able to query which compute nodes are configured for EPA usage and the respective resource allocations. In addition this talk will highlight the need for enhancing/extending OpenStack (e.g. Nova) APIs for retreiving detailed EPA relavant resource usage information from compute nodes.


* **Chegu Vinod** *(Chegu Vinod (Vinod) is an Architect in the NFV Business Unit at Hewlett Packard Enterprise. His interests include EPA, NFVi, VIM, Performance and scaling.)*

* **Naziya Khan** *(Naziya Khan is a Senior Software Engineer/Technical Lead working on implementing various Telco Cloud related solutions in the NFV business unit at Hewlett Packard Enterprise.)*

* **Vishwanath Jayaraman** *(tacker upstream contributor)*
