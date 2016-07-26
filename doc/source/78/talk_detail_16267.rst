Enhanced platform awareness in OpenStack for mortals
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has over a number of releases grown a large number of features that grant the compute scheduler enhanced visibility of the capabilities of the OpenStack environment and the hypervisors within it. These features when combined enable fine-grained matching of workloads with the capabilities of the platform that they require, sometimes referred to as Enhanced Platform Awareness (EPA). Currently exposed capabilities include NUMA topologies, dedicated CPU cores, CPU thread policies, huge pages, SR-IOV physical functions, SR-IOV virtual functions, network interface cards, and other PCIe devices like GPUs. While these faciliies are already proving extremely useful for high performance computing (HPC), network function virtualization (NFV), and software defined networking (SDN) networking use cases the steps involved in requesting these capabilities for a virtual machine and the ways the features do and don't work in conjunction with each other are not always obvious.


* **Stephen Gordon** *(Stephen is a product manager focused on OpenStack tenant workloads at Red Hat be they virtualized, containerized, orbaremetal. He is currently a facilitator of the Kubernetes OpenStack SIG, an avid collector of “Internet points” at  the Foundation's Q&A portal, ask.openstack.org, and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/. Previously Stephen was a technical writer producing documentation for Red Hat Enterprise Linux OpenStack Platform, Red Hat Enterprise Virtualization, and related open source projects including the OpenStack documentation project, oVirt, and Fedora.  )*
