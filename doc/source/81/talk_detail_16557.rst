Unified application model for VMs and containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As containers become as popular for enterprise workloads as VM instances, there is an emergent need to provide a unified application development paradigm across both domains. In this talk, we describe how we achieved this by creating a new kubernetes driver for Nova. This driver is provided with the kubeconfig for the given Kubernetes cluster during initialization. During instance provisioning, it automatically converts the given Glance image into a docker image. The cloud-init customization scripts are injected into the docker image to be run on startup. The driver deploys a single service targeting a single pod when creating an instance, with a replication controller of just 1 replica. Heat was also modified by adding another parameter to the AutoScalingGroup - the kubeconfig. When this parameter is present, Heat creates an appropriate ReplicationController for the instances instead. Finally,we demonstrate the use of the same Heat template to deploy a VM or container based workload.


* **Amrish Kapoor** *(Amrish Kapoor is an early engineer with Platform9 Systems, and leads the vSphere integration effort with Platform9's SaaS-Managed OpenStack offering. Amrish is formerly from Microsoft, where he held technical and management leadership roles, helping ship components of the Microsoft Desktop Optimization Pack (MDOP) suite of virtualization products. He is passionate about his family, work, and sports.)*

* **Bich Le** *(Spent most of career innovating in the cloud and virtualization areas. Before co-founding Platform9, spent 14 years as a Principal Engineer at VMware, helping them innovate their way from a small startup to a multi-billion dollar powerhouse. Prior to that, architected the Aries RISC-to-IA64 dynamic translator at Hewlett Packard. Graduate of U.C. Davis Node.js enthusiast and maintainer of the fuse4js github project.)*
