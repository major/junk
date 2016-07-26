Running Manila at Scale: How SAP Hosts In-memory Databases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will cover the usage of Manila for high-end enterprise application like in-memory databases. It will start the first challenge: the data center deployment, where we used OpenStack Kolla and Kubernetes. Many storage backeds in manila only supporting 4096 (VLAN limit) networks which is one issue we solved with multi-segment hierarchical port binding. Here we will cover in-depths how full network automation in manila works and how also such complex network topologies can be supported. We will discuss in details about the current state of active-active HA and missing features and how we want to address them.


* **Marc Koderer** *(Active contribuiter since 2013 with the focus on storage and QA for enterprise usage. Part of the OpenStack cloud inititive at SAP.)*

* **Bernd Herth** *(Focus on cloud infrastructure architecture for Enterprise applications. )*
