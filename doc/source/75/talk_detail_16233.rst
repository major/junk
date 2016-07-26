OpenStack PKI is basically magic. Here’s some spells to get you started.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack clouds tend not to fit into traditional security architectures.  After all, the primary purpose of a cloud is to take external workloads and data and position them deep within your data center.   Any OpenStack cloud will be a composition of many interacting and optional services. These services often bridge security domains and networks. Over the last few releases, developers have worked hard to ensure that deployers have the option to secure individual connections between services with Transport Layer Security (TLS).  However,  this has left how to manage PKI, the fundamental system of certificates underpinning TLS as an exercise for the cloud operator.   In this presentation we guide the audience through a number of considerations and approaches to securing a cloud with PKI before exploring some specific reference architectures that we have created to make secure deployment easier for everyone.


* **Ade Lee** *(Ade works for Red Hat, and has been involved in Dogtag development (and its integration into FreeIPA) for a number of years now. He has worked to integrate Dogtag and FreeIPA with Openstack, and is a core contributor to the Barbican project. Most recently, he has worked on puppet modules to deploy Barbican in Triple-O and RDO.)*

* **Robert Clark** *(Robert is an IBM Distinguished Engineer, he helps drive security strategy across IBM's cloud portfolio and is the current PTL of the OpenStack Security team. His career has its roots in threat modelling, vulnerability analysis and virtualization security. He is passionate about security and driving up standards in OpenStack which he has been working on for the last four years.)*

* **Juan Osorio Robles** *(Juan Antonio (Ozz) is a member of Red Hat's OpenStack Identity team and a core developer onBarbican, the secret storage as a service solution for OpenStack; and TripleO (OpenStack overOpenStack), a cloud installer. In Red Hat, he has been actively working in TripleO to enable TLS in boththe public and internal services of the deployment.)*
