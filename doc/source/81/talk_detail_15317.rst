Hypernetes: Secure & Multi-tenant Kubernetes Enabled by OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Hypernetes aims at managing hypervisor-based containers with Kubernetes. Instead of running k8s on OpenStack, Hypernetes directly launch HyperContainer as k8s container runtime, then build a production ready solution with Keystone for multi-tenancy, Neutron for container network, and Cinder for container persistent volume. This is a much easier way integrate k8s with OpenStack, and joins both good parts of VMs and containers so it can provide secure and multi-tenant container cloud without wrapping them inside VMs. This presentation will also demo the Kubernetes official project Frakti which aims at using hypervisor as first class container runtime, how OpenStack core components serve container network and persistent volume. Today, many developers are not comfortable with Linux containers as an effective boundary, and requires for a stronger degree of isolation, particularly for those running in a multi-tenant environment. We believe this solution is one of the best answers.


* **lei zhang** *(Phd candidate. Microsoft MVP of 2016. Feature Maintainer and Member of Kubernetes project. Formerly VMwarer and then Baiduer, now working for HyperHQ, the author team of world's first open-source hypervisor based container. Mainly focusing on maintaining kube-scheduler, kubelet and HyperContainer as container runtime on Kubernetes upstream which is also known as Hypernetes project. An active community advocator, Top Star Speaker of InfoQ Container Conference in 2015, once published the book "Docker and Kubernetes Under The Hood" which is the best seller of container cloud area in China. )*
