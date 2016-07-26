Adding dynamic configuration to Kolla Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kolla and Kolla Kubernetes  are two primary projects that can be used to install OpenStack using containers and Kubernetes orchestration framework respectively.  While Kolla-Kubernetes is great, it does suffer from few drawbacks: Adding new service requires changes to the central kolla-kuberntes repository. Adding the service also means a way to create configuration ansible and password scripts in one location. There is no easy way to upgrade 'configuration' and services. This talk proposes changes to kolla-kubernetes architecture into a more service oriented architecture by introducing: a) A new service Kolla-Config that centralizes the configuration. b) Introducing 'Service-Manager' per component (glance, nova etc) that is responsible for generating and updating configuration. The result is a much more dynamic OpenStack installation and upgrade experience.


* **Roopak Parikh** *(Roopak Parikh is one of the Co-founder and CTO at Platform9 Systems Inc. Platform9 Systems is one of the OpenStack distribution and service providers. Prior to Platform9 Systems Roopak help technical leadership roles at VMware helping them build various management products including vCloud Director (VCD).)*

* **Bich Le** *(Spent most of career innovating in the cloud and virtualization areas. Before co-founding Platform9, spent 14 years as a Principal Engineer at VMware, helping them innovate their way from a small startup to a multi-billion dollar powerhouse. Prior to that, architected the Aries RISC-to-IA64 dynamic translator at Hewlett Packard. Graduate of U.C. Davis Node.js enthusiast and maintainer of the fuse4js github project.)*
