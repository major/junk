Unikernels on OpenStack: Toward Secure and Lightweight Software Appliances in the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Unikernels are sealed, specialized machine images and are emerging as efficient and secure alternative for deploying applications. An application built as a unikernel is compiled and linked with only the OS components necessary for its operation.  By design, unikernels boot extrememly fast, have small footprints and small attack surfaces. These characteristics make unikernel a perfect fit for deploying software appliances (e.g. NFV, Security appliance) in a cloud environment.  Because unikernels are specialized per application, new lifecycle management methodology and tools need to be developed to compile, build, and deploy unikernels efficiently in the cloud. In this talk, we demonstrate and discuss: 1) extensions to OpenStack (Glance, Nova, and Solum) to enable unikernel as a first-class resource like VM and container, 2) impact of using unikernels to deploy software appliances in the cloud, and 3) lessons and challenges from operationalizing unikernels using OpenStack.


* **Michael Le** *(Michael Le is currently a research staff member at the IBM T. J. Watson Research Center. His current research focus is on cloud infrastructure and cloud platform management. Michael has previously worked on automating deployment of secure and compliant data analytics platform using OpenStack Sahara and is currently working on how to better secure and isolate applications deployed on the cloud.)*

* **Hui Kang** *(Hui is a research staff member at IBM T.J. Watson Research Center. He is currentlywith the cloud infrastructure team, focusing on OpenStack, Docker, Linux kernel, etc. Hui has contributed to several open source projects, including openstack/kolla, Docker, CRIU, and ovn-scale-test. He also enjoys hacking OS kernel and learning hardware techniques.)*

* **Shu Tao** *(Shu Tao is manager of cloud infrastructure and data services department at IBM T J Watson Research Center.  He has been working on various OpenStack-related projects since 2012.  His current interests about OpenStack include control plane performance and scalability, Neutron plugins, and support for data intensive applications on OpenStack cloud.)*
