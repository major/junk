Containers
==========

Kuryr - Here Comes Advanced Services for Container Networking!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kuryr's goal is to make Neutron networking available to containers in their most widespread usages.Kuryr bridges the gap between the container orchestration engines like Kubernetes, Swarm and Mesos and the OpenStack networking. It exposes all of the production grade Neutron capabilities and services to large scale container consumers. In Mitaka we presented our plans for Kubernetes integration and nested containers; for Newton we are enriching these enviorments with OpenStack advanced services such as Security Groups and Load Balancers. We show how a seamless set of advanced networking services and policies for containers, VMs, bare metal and nested containers can be provided by leveraging Kuryr with OpenStack.


* **Gal Sagie** *( I am a software architect, passionate about open source, experienced with networking, virtualization and all areas of SDN/NFV and cloud computing. Contributing to OpenStack Neutron, Containers networking projects and hybrid cloud. Eager to bridge the gaps between OpenStack development and its users and explore new areas to help OpenStack shine Blogging for anything OpenStack related at: Blog - http://galsagie.github.io)*

* **Antoni Segura Puimedon** *(Antoni serves as a core member of Openstack Kuryr and as the Container Team lead at Midokura and works on integrating MidoNet with VM and Container platforms. He has contibuted in the past to the networking stack of oVirt, Libvirt nova-docker and MidoNet. His recent focus has been on Container Software Defined Networking and Container projects like OpenStack Magnum and Mesosphere.)*

* **Mohammad Banikazemi** *(Mohammad is a research staff member at the IBM T.J. Watson Research Center. His research interests include cloud computing and software-defined networking. He is a senior member of the ACM and the IEEE and an active contributior to Neutron. Mohammad lives with his family in NYC.)*

A journey to use Kuryr in Private Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will introduce the journey to use kuryr to improve our docker network in Webex Cisco Private Cloud Environment.  In private cloud, tenant end user needs better performance and advance network feature for Docker.  Kuryr can map docker-libnetwork to neutron. This talk will focus on the problem we meet and how we solve when enable Kuryr in multi-host and multi-tenant environment, what's the dependency and limitation if you want to enable kuryr in your private cloud.


* **Liping Mao** *(Working as devops at Cisco Webex Cloud Service, develop and operate Openstack Private Cloud in Cisco Webex. Participate in Kuryr Upstream work, active developer in Kuryr Project.  )*

* **Ian  Zhang** *(Working at Cisco WebEx for 11 years, cloud platform architect for Cisco WebEx Openstack deployment. observer of data center and infrastructure evolvement. Skillful in distributed file system, cloud platform, high availability, and application/software cloudification. The guy under the philosophy of building best marriage between infrastructure and application...  )*

Converging QEMU and TCMU for Container Storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers storage technologies are changing rapidly. Volume Plugins in Docker and Kubernetes open doors to 3rd party storage provisioning for containers. However, these technologies are all based on bind-mount, volume drivers have to implement storage functionalities on their own. On the other hand, QEMU has a different approach to provide storage for virtual machines. QEMU's block drivers abstracts different backend storage types and thus supports features like multi-tenancy, snapshot, and QoS, which are currently missing in Container storage drivers. This talk presents a new technology that converges QEMU and TCMU. This allows Containers to use rich storage features that are already available to Virtual Machines. This technology integrates QEMU's block layer with tcmu-runner, and enables Containers to access various storage backends and rich storage features.


* **Huamin Chen** *(A passionate system software developer, Huamin Chen contributes to open source projects spanning from A to Z: Apache BigTop, Ceph, fio, Gluster, Kubernetes, Tachyon, and ZFS. Huamin Chen is currently employed by Red Hat. Follow him at http://github.com/rootfs)*

What happens when DC/OS meets OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Mesosphere Open DC/OS treats container as first class citizen, supporting container image for AppC, Docker, Linux container with OCI being planned for the near future.  Until recently, automated deployment for DC/OS is only available on AWS and Azure, but with a new bay driver in Magnum, users can now manage their DC/OS cluster in OpenStack. This brings several benefits: 1) Open DC/OS easily available in a private cloud, allowing full customization of the cluster. 2) Dynamic scaling of the cluster infrastructure 3) Advanced coordination between container auto scaling and cluster infrastructure auto scaling. In this talk, we will show how Magnum deploys and manages the DC/OS cluster in OpenStack.  We will also describe advanced support for DC/OS with storage through Docker volume driver and networking through CNI. 


* **Brad Topol** *(Dr. Brad Topol is an IBM Distinguished Engineer in the IBM Cloud Architecture and Technology organization. In his current role, Brad leads a development team focused on contributing to and improving OpenStack and he has cross-IBM responsibility for coordinating its contributions to OpenStack. Brad is an OpenStack core contributor to Keystone-Specs, Pycadf, and Heat-Translator and has personally contributed to multiple OpenStack projects including Keystone, Pycadf, Heat-Translator, and DevStack. He is a co-author of Identity, Authentication & Access Management in OpenStack, a book published by O'Reilly Media in 2015.    )*

* **Guang Ya Liu** *(Guang Ya Liu is a Senior Software Engineer in IBM CHDL (China Hardware Development Lab) and now focusing on cloud computing, data center operating system and container technology. Starting from 2013, Guang Ya act as an OpenStack Active Contributor and contribute to many projects in OpenStack including Nova, Cinder, Heat, Ceilometer, Magnum etc and he is now the Core Member of OpenStack Magnum. Starting from 2015, Guang Ya act as a Mesos Active Contributor and mainly focusing on allocator and container part for Mesos. Guang Ya is also the organizer for both Mesos and OpenStack Xi'an Meetup and successfully held several meetups for both Mesos and OpenStack in China. Visit his github here https://github.com/jay-lau  )*

* **Ton Ngo** *(Ton Ngo is a senior developer at the IBM Silicon Valley Lab and has been a core contributor to OpenStack for 3 years.  Currently he is working on Magnum, focusing on advanced networking for container, storage support, user guide, troubleshooting guide.  He also developed the Heat translator and helped improved Heat template troubleshooting.  Previously, he was with the IBM Research Lab for 16 years and has published papers on a wide range of subjects.  He spent 10 years building cloud solution for customers using IBM cloud orchestration products.Ton Ngo received his PhD in Computer Science from the University of Washington, Seattle.  He has given several talks at previous OpenStack Summits.)*

Docker Container overview
~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker Engine: The Docker engine is for enabling the realization of purpose-specific as well as generic Docker containers Docker engine is analogus to a KVM in the virtual machine world. It allows the container virtualization at the OS level Docker container: the read-write layer is the container layer, Docker pulls the required image and its parent image. It continues to pull all the parent images until it reaches the base image. Docker Registry: A service responsible for hosting and distributing images. The default registry is the Docker Hub. Docker Repository: A collection of related images (usually providing different versions of the same application or service).


* **Arun Srinivasan** *(I am currently working as a Cloud Reliability Engineer at eBay. Supporting the eBay cloud connect commerce (c3) cloud. eBay cloud is one of the largest implementor of Openstack running about 100000 virtual machines across three availability zone. My role involves remmediate customer issues, build new clouds, add capacity, work on the open stack control services and data plane services such as networking and access to guest virtual machines Formerly worked as a cloud Engineer supporting the IBM smart cloud enterprise(SCE).IBM’s enterprise-class public cloud infrastructure-as-a-service (IaaS)—delivers secure and scalable hosted IT infrastructure with on-demand access to virtual server and storage resources. Well suited for development and test activities, as well as other dynamic workloads.)*

Live Container Migration on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Think VM migration is cool?  Wait until you see container migration in action!In this session we will first discuss runC (https://runc.io/) - the Open Container Initiative's (OCI) reference container runtime, and its relationship to the Docker runtime. Secondly we'll look at some of its features and capabilities, including features like checkpoint/restore which have not been exposed (yet) in the Docker runtime. Finally, we'll demonstrate live migration of container workloads between OpenStack Nova hosts.


* **Phil Estes** *(Phil is a Senior Technical Staff Member with IBM's Cloud Open Technologies team. The Open Technology team leads IBM's strategy and involvement in key cloud open source technologies, including Docker, Cloud Foundry, and Openstack. Phil is a core contributor and maintainer on the Docker engine project and is a leader and expert within IBM on container and cloud open source technologies. He regularly helps both IBM product teams and IBM's customers to apply container technology and concepts to their cloud strategy and implementation. Phil speaks regularly at industry conferences and meetups and enjoys helping customers and developers alike understand this fast growing ecosystem.)*

* **Shaun Murakami** *(Shaun Murakami is a Senior Cloud Architect and Technical Lead for the IBM Cloud Performance team located in Silicon Valley, California. As part of the Cloud Performance team, Shaun has worked with many customers, helping them transform their business using Cloud Computing technologies and IBM integrated solutions. Shaun has helped influence the evolution of IBM Cloud technologies including the IBM SmartCloud Enterprise, IBM CloudBurst, IBM Workload Deployer, and IBM PureApplication System. He is currently working with various open source technologies such as OpenStack, Docker, and Cloud Foundry to transform some of IBM's next-gen cloud offerings. Shaun received B.S. degrees in Electrical Engineering and Computer Science from the University of Hawaii at Manoa and a M.S. degree in Computer Engineering from San Jose State University.)*

Multi-tenancy and advanced networking for containers in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In our previous OpenStack Summit talk, we showed how Kubernetes and Swarm containers can be hosted efficiently on the same OpenStack infrastructure through Mesos.  Even better efficiency can be achieved with multi-tenancy on the same cluster, allowing resources to be shared among containers from multiple tenants in a flexible manner.  Multi-tenancy does introduce new requirements on the infrastructure and management software, such as name space and advanced networking to isolate containers from different tenants. In this talk, we will explore the issues in providing multi-tenancy for containers and show how this can be achieved on OpenStack. The end result is an environment on OpenStack that can host Kubernetes and Swarm containers from multiple tenants.


* **Ton Ngo** *(Ton Ngo is a senior developer at the IBM Silicon Valley Lab and has been a core contributor to OpenStack for 3 years.  Currently he is working on Magnum, focusing on advanced networking for container, storage support, user guide, troubleshooting guide.  He also developed the Heat translator and helped improved Heat template troubleshooting.  Previously, he was with the IBM Research Lab for 16 years and has published papers on a wide range of subjects.  He spent 10 years building cloud solution for customers using IBM cloud orchestration products.Ton Ngo received his PhD in Computer Science from the University of Washington, Seattle.  He has given several talks at previous OpenStack Summits.)*

* **Brad Topol** *(Dr. Brad Topol is an IBM Distinguished Engineer in the IBM Cloud Architecture and Technology organization. In his current role, Brad leads a development team focused on contributing to and improving OpenStack and he has cross-IBM responsibility for coordinating its contributions to OpenStack. Brad is an OpenStack core contributor to Keystone-Specs, Pycadf, and Heat-Translator and has personally contributed to multiple OpenStack projects including Keystone, Pycadf, Heat-Translator, and DevStack. He is a co-author of Identity, Authentication & Access Management in OpenStack, a book published by O'Reilly Media in 2015.    )*

* **Paolo Dettori** *(Paolo Dettori is a Senior Technical Staff Member at the IBM Watson Research Lab. His research interests are in distributed systems, cloud and open source technologies. He received his M.S. in 1991 in electrical engineering from the Polytechnic University of Turin, Italy, and joined IBM in 1992. Since then he has worked as lead architect on a number of projects focused on cloud technologies. Currently, he is a lead architect for the IBM Containers Service. Mr. Dettori authored and co-authored several journal and conference papers and holds 12 patents issued in the U.S. on multimedia technologies, Business Process Management and distributed systems.)*

Networking considered the Achilles heel of container clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the popularity of containers increases, several alternatives for supporting these in OpenStack clouds are emerging. However, given the much higher instance (per hypervisor) density found in real-world production clouds for containers, the usual virtual networking implementations - successfully applied to VMs in the past - have become an Achilles heel. In this talk we present several relevant alternatives, focusing on the networking aspects of each solution. In particular, we present the networking models used with multiple instance management options, such as Nova (nova-docker), Magnum, and Kuryr  (and possibly Zun) projects. We consider all existing container networking solutions from the Docker Container Network Model to the AppC Container Network Interface, and their interaction with OpenStack Neutron. We evaluate and quantify the performance and scalability of the networking alternatives. 


* **Mohammad Banikazemi** *(Mohammad is a research staff member at the IBM T.J. Watson Research Center. His research interests include cloud computing and software-defined networking. He is a senior member of the ACM and the IEEE and an active contributior to Neutron. Mohammad lives with his family in NYC.)*

* **Marcio Silva** *(Software Engineer at IBM Research)*

* **George Almasi** *(Dr. Almasi is a Research Staff Member in the Software DefinedInfrastructure Department at the IBM TJ Watson Research Center. Heholds a PhD in Computer Science from the University of Illinois andhas been employed by IBM since his graduation. He has worked onseveral supercomputer projects like Blue Gene and PERCS, and hasauthored and co-authored several papers on the design of messagingsystems and programming models in High Performance Computing. He isnow an expert on various aspects of OpenStack installation.)*

OpenStack is an Application! Deploy and Manage Your Stack with Kolla-Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack consists of interrelated software components that control hardware pools of processing, storage, and networking resources throughout a datacenter that are difficult to install, manage, and upgrade. With Kubernetes, each of the services can be viewed as applications.  Combined, they form a complex application that Kubernetes is capable of managing. Kubernetes provides high-level abstractions built around the needs of complex production systems like OpenStack. This provides an alternative approach to operations enabling clusters to be more easily operated, managed, and automated. In addition, Kubernetes has native tooling which simplifies otherwise hard problems like HA or upgrades. In this talk, the kolla-k8s team will demonstrate how Kubernetes solves the "Day 1" problem of deployment as well as "Day 2" operations like configuration, reconfiguration, failure recovery, and upgrades.  We will also demonstrate a production ready, highly available OpenStack based on kolla-k8s.


* **Ryan Hallisey** *(Ryan is a software engineer at Red Hat.  He has been working on Kolla since the start of the project two years ago.  Since then, he has been heavily involved in both Kolla and kolla-kubernetes projects.)*

* **Ken Wronkiewicz** *(Ken is a Technical Leader at Cisco working with cloud infrastructure. Previously, Ken managed the Rackspace Cloud AutoScale product. Before that he worked on monitoring and high-performance stock market data feeds.)*

* **Michał Jastrzębski** *(Michal is a senior cloud software engineer at Intel Corporation and one of tech leads of Openstack Innovation Center. Michal is making Openstack better since Grizzly. Michal is a Kolla core reviewer since the Liberty cycle with a focus on diagnostics and upgrades.)*

Open, Scalable, & Integrated Networking for Containers & VMs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How can you easily make VMs, bare metal and container all talk to each other seamlessly? By implementing integrated networking between containers, VMs and baremetal. In this talk, we will discuss the work being done in Project Kuryr to integrate OpenStack Neutron with container networking. We will also discuss Open Virtual Networking (OVN), a new network virtualization project being developed to scale to the needs of VMs, containers and bare metal. All of this allows for the integration of containers, VMs and bare metal. Come to this talk to hear an update on current activity in these critical infrastructure open source projects. We will share how each of these pieces fits together. We will also present a demo showing all of these technologies working together to build a common networking layer to support your compute needs in an OpenStack cloud.


* **Kyle Mestery** *(Kyle is a Distinguished Engineer and Director of Open Source Networking at IBM. He leads a team focused on Open Source networking at scale. Kyle is also a member of the OpenStack Technical Committee, and the former PTL of OpenStack Neutron for the Juno, Kilo, and Liberty cycles. Kyle lives with his wife and kids in Minnesota.)*

* **Phil Estes** *(Phil is a Senior Technical Staff Member with IBM's Cloud Open Technologies team. The Open Technology team leads IBM's strategy and involvement in key cloud open source technologies, including Docker, Cloud Foundry, and Openstack. Phil is a core contributor and maintainer on the Docker engine project and is a leader and expert within IBM on container and cloud open source technologies. He regularly helps both IBM product teams and IBM's customers to apply container technology and concepts to their cloud strategy and implementation. Phil speaks regularly at industry conferences and meetups and enjoys helping customers and developers alike understand this fast growing ecosystem.)*

* **Flavio Fernandes** *(Flavio is a senior software network developer at IBM cloud. Lately, he has been deeply involved with Open Virtual Network for the Open vSwitch project. Prior to IBM, Flavio also worked with SDN technologies at Red Hat and Plexxi. At Red Hat, he was a core contributor to the OpenDaylight Netvirt+OVSDB project. At Plexxi, he worked as a lead engineer of the optical switch. With over 19 years in the networking  industry, Flavio has also worked extensively on routing protocols and high availability at Juniper Networks.  )*

Providing Container Storage Service with Fuxi and Magnum
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Fuxi is an ancient Chinese God who taught people skills for living such as fishing, knitting. In choosing Fuxi as the name of our new OpenStack project, we aim to let containers fully utilize all of OpenStack storage services such as Cinder, Swift, Manilla.In this talk we will introduce the key concepts and and the architecture of Fuxi.  We will examine how Fuxi can be integrated with Container Orchestration Engines deployed by Magnum.  We will share our vision on future storage support for containers in OpenStack and our potential relationship with project Kuryr.


* **Zhipeng Huang** *(Zhipeng Huang is currently a standard manager and open source community operator for Huawei. His activities mainly involves open source projects like OPNFV, OpenStack, Open Container Project, OpenDaylight and so forth.)*

* **Ton Ngo** *(Ton Ngo is a senior developer at the IBM Silicon Valley Lab and has been a core contributor to OpenStack for 3 years.  Currently he is working on Magnum, focusing on advanced networking for container, storage support, user guide, troubleshooting guide.  He also developed the Heat translator and helped improved Heat template troubleshooting.  Previously, he was with the IBM Research Lab for 16 years and has published papers on a wide range of subjects.  He spent 10 years building cloud solution for customers using IBM cloud orchestration products.Ton Ngo received his PhD in Computer Science from the University of Washington, Seattle.  He has given several talks at previous OpenStack Summits.)*

* **ni zhang** *(Ni Zhang is a senior developer in Huawei and the PTL of Fuxi projects)*

Container as first class citizens of OpenStack and across multiple OpenStacks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud-native applications, (Applications or Services that are container-packaged, dynamically scheduled and micro-services oriented), currently is a phrase that sums up where a lot of enterprise developers and operations staff think they are headed. To close the gap between OpenStack and "cloud-native applications", we make efforts on Networking, Storage, and Authorization/Authentication to make containers "first-class citizen". We use Kuryr to connect containers network with Neutron; we use Fuxi to allow containers use Cinder volumes. For the popular container platform Kubernetes, we make use of Keystone to be Authorization/Authentication provider for container clusters integrated with OpenStack IaaS, to support Multi-tenant scenarios. In this presentation, we will also show how Tricircle project, which aims to provide an OpenStack API gateway and networking automation, can help build container network and provision container storages across mutiple OpenStack instances.


* **Chaoyi Huang** *(Principal architect of Huawei FusionSphere (OpenStack based Cloud OS).  The initial and current PTL of the Tricircle project ( https://github.com/openstack/tricircle ) for distributed multi-site cloud and  large scale cloud. The initial and current PTL and key committer of OPNFV multisite project: https://wiki.opnfv.org/multisite The initiator, founder and core reviewer of OpenStack Kingbird project ( https://launchpad.net/kingbird, https://github.com/openstack/kingbird ) The key system architect for one tier 1 Europe operator's cloud, which is OpenStack based, covers up to multiple geographically distributed data centers, and can also integrate AWS into the cloud. He has worked in software area over 10 years from in-memory customized database to cloud computing.)*

* **Zhiyuan Cai** *(Join Huawei in April 2014. Mainly focus on Huawei public cloud maintenance and operations, and OpenStack community contribution, used to work in project like Neutron, Keystone and OpenStack Client. Now pay more effort on Tricircle, which is the project for cascading solution, and Kingbird, a newly started project for multi-site management. Recently working with engineers from NEC together to run a demo which utilizes the cascading solution to deploy web services with a database cluster backend across China and Japan.)*

* **Yin Ding** *(Dr. Yin Ding is the new generation Virtualization Technologist at Huawei IT product line. Yin is responsible for creating and communicating technical vision and strategy for Cloud Infrastructure and Container Technology business. He works closely with IT Product line R&D teams to bring the new generation cloud technology into Huawei IT products. Before joining Huawei, Yin spent over ten years at Microsoft and VMware working on platform and cloud computing. Yin holds Ph.D in Computer Science from Arizona State University, bachelor’s and master’s degrees in Computer Science from Tsinghua University.)*

Toward 10,000's containers on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kubernetes, Swarm and Mesos have been shown to scale to hundreds orthousands of nodes and tens of thousands of containers, handlingmillions of requests per second. On OpenStack, they can be easilydeployed and managed by Magnum, but how do they scale? Building thecorrect infrastructure plays a critical role in the performance andscalability for the containers, and this needs to be implemented in Magnum.Working toward this goal, we have built a collection of Rally plugins totrack the performance and scalability of both Magnum and the ContainerOrchestration Engines (Kubernetes, Swarms, Mesos). We have been runningthe benchmarks on large OpenStack environments to collect measurementsand study the behavior of the system. In this talk, we will present ourfindings along with some of the best practices we found for operatinglarge container environments.


* **Winnie Tsang** *(Normal 0 false false false EN-US X-NONE X-NONE /* Style Definitions */ table.MsoNormalTable {mso-style-name:"Table Normal"; mso-tstyle-rowband-size:0; mso-tstyle-colband-size:0; mso-style-noshow:yes; mso-style-priority:99; mso-style-parent:""; mso-padding-alt:0in 5.4pt 0in 5.4pt; mso-para-margin:0in; mso-para-margin-bottom:.0001pt; mso-pagination:widow-orphan; font-size:10.0pt; font-family:"Calibri","sans-serif";} Winnie Tsang is a software engineer in IBM working on cloud performance. She work on OpenStack Heat on some debugging features in Juno cycle. In this current cycle she is working on a Rally plugin for Magnum. It will allow users to test the performance and scalability of Magnum for Kubernetes, Swarm and Mesos.)*

* **Ricardo Rocha** *(Ricardo Rocha is a software engineer at CERN. He's currently a member of the CERN OpenStack team, focusing on service and application orchestration and container deployments. Previous work included development of data storage, bookkeeping and monitoring services for the LHC Computing Grid (LCG).)*

* **Spyros Trigazis** *(Spyros Trigazis work at CERN.)*

Beyond Neutron: all you wanted to know about container networking but were too afraid to ask
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack users, we are all familiar with Neutron and how it handles networking for our virtual machines. But in a world where an important part of our workloads are being moved to microservices running on containers, how can we efficiently handle secure and high-performance networking for these containers? And how do those containers communicate with the rest of the OpenStack cloud and the outside world? Is there a way to connect both worlds, and does it make sense at all to connect them? This session will address how the currently available solutions for container networking intersect with the OpenStack Neutron networking model. It will also present several open-source and commercial networking solutions for containers and discuss how they work in OpenStack, and inside Container Orchestration environments such as Mesos, DC/OS, Docker Swarm, and Kubernetes. Finally, we will show a demo of how networking works both in an OpenStack and a Container environment.


* **Fernando Sanchez** *(Fernando is a cloud architect specialized in software networking and distributed systems. He's a frequent speaker at Openstack meetups, and has more than four years experience in implementing all sorts of private clouds, ranging from small enterprise to Fortune 100 companies and Service Providers. He works at Mesosphere, where he’s passionate about building cloud solutions to help his customers achieve their business goals.)*

* **Fawad Khaliq** *(Fawad has been a member of the OpenStack community for over four years and a core developer in the Networking ecosystem. He has contributions in several OpenStack projects including Neutron, Nova, Kuryr, Magnum, DevStack. He is also the author and maintainer of networking-plumgrid subproject under Neutron umbrella and has over four years experience in implementing software defined networking, containers, high availability, distributed system and APIs. Fawad is a Senior Software Engineer at PLUMgrid, where he is involved in design and development of cloud computing software components, solving networking problem for new technologies and representing PLUMgrid in various open source forums. Currently, he is working on improving the area of container networking in the OpenStack, Docker and Mesos communities. In future, he plans to solve the problem of application service discovery inside the OpenStack ecosystem. )*

The Combinations between Containers and Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Container technologies have gained significant popularity in the last a few years, and several projects attempt to combine container technologies with OpenStack to address different problems such as multi-tenancy, resource management, monitoring, network, storage, and more. In this session, we will talk about the trend of Containers and OpanStack, such as containers on OpenStack and OpenStack in Containers. We will give a brief introduction to various container-focused projects/sub-projects such as Magnum, Kolla, Kuryr, Murano, nova-docker, nova-lxc, nova-lxd. Then, we will highlight the new container project, called Zun. We will explain the rationales to create this project, and emphasize the use cases this project aims to address. Finally, we will do a comparison of the projects above and explain how these projects will help users run containerized workloads on OpenStack.


* **Hongbin Lu** *(Hongbin is currently a Senior Software Engineer in Huawei Technologies. He is serving as the Project Team Lead (PTL) for OpenStack Magnum project in Newton release cycle. He is also the founder/core reviewer of the Zun project (a new container service for OpenStack). His expertise including container related technologies, application deployment and management, and cloud computing.)*

* **Eli Qiao** *(Qiao, LiYong(Eli)is an OpenStack engineer. He was an virtulazition(KVM/libvirt)  Engineer before, and worked for IBM, now is working for Intel Corp. He Joined OpenStack community since Juno release and continue contributing to Nova project till now. He helped to doing nova-api enhancement, v3 api, micro-version, and other features, and lots of bug fix in nova. Besides he is also a core reviewer for Magnum project also has some contributions for other related projects, like zun, project-config etc.)*

* **Madhuri Kumari** *(Madhuri is a Cloud Software Engineer at Intel Technology India Pvtt. Ltd. having an experience of 4 years in the storage and cloud domain. She is core reviewer in Openstack Magnum Project and also one of the founder/core reviewer for Zun project. She has also contributed to Openstack Object Storage Project, Swift.)*

Setting up Your First Microservice Application on Shipped with Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This will be an introduction/tutorial on Cisco Shipped (ciscoshipped.io), and how it can be used to easily build, deploy and run your first microservice application. It will be a deep dive on how to use docker containers and Shipped to create a simple shopping site using 4 microservice. This will be great introduction course for those new to containers and microservice, it will also make it simple for people to deploy onto openstack.  The shopping site will cover 2 languages, golang and bootstrap js. Shipped is not limited to any langauge and supports a multiple language stack, including postgress and other backend databases.  


* **Nick Hayward** *(Nick is a Software Engineer for Cisco and is currently working on Shipped, an end-to-end tool for deploying micro service containers. Shipped has been in development for the past two years and is currently in beta, and free to use. His main contribution has been to the monitoring tools, that have helped with development of Shipped. During his free time he enjoys craft coffee and beer as well as working out at the gym and yoga. )*

Hypernetes: Secure & Multi-tenant Kubernetes Enabled by OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Hypernetes aims at managing hypervisor-based containers with Kubernetes. Instead of running k8s on OpenStack, Hypernetes directly launch HyperContainer as k8s container runtime, then build a production ready solution with Keystone for multi-tenancy, Neutron for container network, and Cinder for container persistent volume. This is a much easier way integrate k8s with OpenStack, and joins both good parts of VMs and containers so it can provide secure and multi-tenant container cloud without wrapping them inside VMs. This presentation will also demo the Kubernetes official project Frakti which aims at using hypervisor as first class container runtime, how OpenStack core components serve container network and persistent volume. Today, many developers are not comfortable with Linux containers as an effective boundary, and requires for a stronger degree of isolation, particularly for those running in a multi-tenant environment. We believe this solution is one of the best answers.


* **lei zhang** *(Phd candidate. Microsoft MVP of 2016. Feature Maintainer and Member of Kubernetes project. Formerly VMwarer and then Baiduer, now working for HyperHQ, the author team of world's first open-source hypervisor based container. Mainly focusing on maintaining kube-scheduler, kubelet and HyperContainer as container runtime on Kubernetes upstream which is also known as Hypernetes project. An active community advocator, Top Star Speaker of InfoQ Container Conference in 2015, once published the book "Docker and Kubernetes Under The Hood" which is the best seller of container cloud area in China. )*

Deploy container clusters on baremetal with tenants isolated
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker and Containers are taking the application development world by storm, but with all of their benefits there are some limitations and challenges. One key challenge is security between containers, especially when those containers are in different security zones. In areas like Financial Services and Medical Records, companies have widely different security requirements. Today there are no solutions within the Docker ecosystem to fulfill those security requirements while maintaining performance and scale. We will demonstrate a solution to this problem using OpenStack Magnum, Ironic integration, and Neutron Networking with networking-generic-switch plugin. This solution uses: – A Neutron extension to provision ports on generic switch – An Ironic extension to coordinate the port provisioning – Magnum to deploy the container clusters This allows deployment of secure, flexible, scalable bare-metal clusters.


* **wang hua** *(As an OpenStack contributor from Huawei, Hua Wang is responsible for upstream development. Now he is focused on Magnum and the integration of Container and OpenStack. Previously he participated in Huawei FusionSphere OpenStack and has experience in Nova and Glance.)*

* **Hongbin Lu** *(Hongbin is currently a Senior Software Engineer in Huawei Technologies. He is serving as the Project Team Lead (PTL) for OpenStack Magnum project in Newton release cycle. He is also the founder/core reviewer of the Zun project (a new container service for OpenStack). His expertise including container related technologies, application deployment and management, and cloud computing.)*

* **Zhenguo Niu** *(Software Engineer, working on the OpenStack Bare Metal and Dashboard services, contributing to openstack as Horizon core member, involving in Ironic, Nova, etc. As an OpenStack contributor for Huawei, Zhenguo is responsible for developing projects and features from inception to conclusion in OpenStack, driving contributions on behalf of the internal development team, acting as an interface toward OpenStack, promoting needed architectual changes required for our projects.)*

Open Container technologies and OpenStack - Sorting through Magnum, Kuryr, the OCI & CNCF
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers along with next generation topics such as orchestration and serverless computing continue to draw interest across the application developer and data center operator communities because of the enormous potential of the technology and the rapid pace of change.  As the potential of Docker continues to evolve, Kubernetes emerges as the leading orchestration technology, and the OpenStack Magnum project has matured, many want to see shared governance over the baseline container specification and associated runtime and format/image to protect investments and enable confident adoption of this emerging technology. Join this session to learn the latest about the Open Container Initiative (www.opencontainers.org) and the Cloud Native Computing Foundation (cncf.io) - both collaborative projects of the Linux Foundation - that drive the latest cloud native techologies and projects and see how they relate to Magnum and Kuryr.


* **Jeffrey Borek** *(Jeff Borek is a senior technology and communications executive with over twenty years of leadership and technical experience in the Software, Telecommunications, and Information Technology/Consulting industries. He is currently the business development lead for the Open Technologies and Partnerships team - working with clients, business partners, leading industry analysts, and various open source community initiatives including; the OpenStack cloud software project, the Cloud Foundry Foundation, and the Linux Foundation. He also represents IBM as the current Chairman on the Docker Governance Advisory Board.)*

* **Daniel Krook** *(Daniel Krook is a New York area Senior Software Engineer, Distinguished IT Specialist, Master Inventor, and Member of the IBM Academy of Technology. He works with customers to create cloud solutions based on the OpenStack, Cloud Foundry, and Docker open source projects. Daniel has previously spoken on Cloud Foundry and Docker integration with OpenStack at the Juno (Atlanta), Kilo (Paris), Liberty (Vancouver), Mitaka (Tokyo), and Newton (Austin) Summits. He is also a co-organizer of the OpenStack New York and OpenStack Connecticut user groups. )*

* **Sarah Novotny** *(Sarah Novotny leads the Kubernetes Community Program for Google.  She has long been an Open Source community champion in communities such as NGINX and MySQL and ran large scale technology infrastructures before web-scale had a name.  In 2001, she co-founded Blue Gecko, which was sold to DatAvail in 2012.  She has curated teams, been a leader in customer communities focused on high availability web application and platform delivery and is a program chair emeritus for O’Reilly Media’s OSCON. Novotny talks obsessively about people, technology infrastructure and geek lifestyle.  )*

A Survey of Container Security in 2016: A Security Update on Container Platforms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the use of containers continues unabated, including in OpenStack projects like Kolla, Magnum, Kuryr, and others, it's important for developers and operators alike to understand where we stand in 2016 on container security. We had reviewed Docker engine security in a public cloud context at the OpenStack Tokyo Summit in 2015. A year has passed, and we want to look more broadly across the container ecosystem at recent security improvements and remaining open items. We'll bring attendees up to speed on the core aspects of container security, and talk about ongoing work occurring in upstream open source communities since the Tokyo Summit. We'll also look at reports like the NCC Group report covering LXC, rkt, and Docker, noting valuable recommendations and topics along the way. We will also discuss our own open source work to improve container security and to provide tools for improving application security for operators and developers alike.


* **Phil Estes** *(Phil is a Senior Technical Staff Member with IBM's Cloud Open Technologies team. The Open Technology team leads IBM's strategy and involvement in key cloud open source technologies, including Docker, Cloud Foundry, and Openstack. Phil is a core contributor and maintainer on the Docker engine project and is a leader and expert within IBM on container and cloud open source technologies. He regularly helps both IBM product teams and IBM's customers to apply container technology and concepts to their cloud strategy and implementation. Phil speaks regularly at industry conferences and meetups and enjoys helping customers and developers alike understand this fast growing ecosystem.)*

* **Salman Baset** *(Salman Baset is working as a Research Staff Member at IBM T. J. Watson Research Center. He received a PhD in Computer Science from Columbia University. His recent work at IBM has been focused on Docker security and designing, building, and securing IBM Containers. He led the design and implementation of SPEC IaaS Cloud 2016, the first industry standard cloud benchmark. He is a recipient of SPEC Presidential Award in 2016, and Young Scholars Award by Marconi Society in 2008. He is also a coauthor of RELOAD protocol (published by IETF) for building peer-to-peer communication systems.)*

rkt, runC, LXC: How are we running containers?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers have become the new hot topic in the last few years. This is not the least reason why we now have multiple container runtimes. A container runtime is simply the low-level engine hiding behind all of the fancy commands we use to run a container. Usually the runtimes job is done silently in the background. A few years ago there were only very few feature-rich container runtime implementations. Now we have multiple and all promise to be both easy to use, feature-rich and secure by default. In this talk we will try to bridge the gap between a higher-level and a low-level view on what different container runtimes do. We will try to answer what they have in common and where they differ.


* **Christian Brauner** *(Christian Brauner is a Software Engineer currently working at SUSE. His main focus are containers.)*

Enable server-less applications – with Docker ready infrastructure and DevOps
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How to allow non Openstack experts to transform applications to open cloud environments (Public or Private), while keeping control on their applications deployment whatever the underlying infrastructure. During this session, you will learn how this is possible thanks to containers : - Enable an efficient and secure infrastructure management - Migrate smoothly to cloud native applications DevOps and application lifecycle management - Manage dynamically your applications capacities (independently of the underlying supply layer (VM, Bare Metal, private / public Cloud).   During our session, we will illustrate this with a OpenStack cloud platform as an example of underlying platform. Design your infrastructure for optimized DevOps – and forget about it with your infra-agnostic applications : this is the path to fully leverage cloud promises !


* **Patrick Masse** *(Patrick Masse is part of the Hewlett Packard Enterprise (HPE) Enterprise Group – EMEA Hybrid IT / Cloud Presales team, working as Solution Architect. Patrick is expert in solution offerings articulating end to end solutions, with hardware, software and services portfolio to address business needs in the cloud & NFV domains, as expressed in particular by Service Providers. Based on more than 11 years in both presales & delivery, Patrick supports complex pursuits and accounts teams.)*

* **Christian SCHUTZ** *(Christian Schutz work as an EMEA Cloud Pre Sales for HPE Cloud Business unit.I am supporting both PaaS/DevOPS and NFV/Openstack projects with large enterprise (including Tier 1 EMEA telecom operators).Helping key EMEA customers define their cloud strategy and helping them adopt and implement this new style of IT based on Cloud, NFV and PaaS solutions. Work around Public, Private and Hybrid solutions.I work closely with HP field to pursue cloud opportunities across EMEA and assist them to answers to customer RFx, produce solution designs and deliver solution presentations to customers.Representing HP at key industry events (HP Discover, Openstack Summit and Mobile World Congress).)*

Policy-based Kubernetes Scheduling driven by Congress, OPA, Magnum, and the rest of the BigTent
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

 In this talk we describe how OpenStack Congress, the recent open-source project Open Policy Agent (OPA), and Magnum work together to give an OpenStack operator the ability dynamically control the container placement logic of Kubernetes by writing rich, declarative policy statements.  As a first use case, we demonstrate policies where Kubernetes pods need to be scheduled so they have local access to Cinder-backed storage.  Importantly, this integration is accomplished with NO changes to Magnum or Cinder; the exact same integration works to implement policies that draw on data from any (combination) of the BigTent projects.


* **Tim Hinrichs** *(Tim Hinrichs is the PTL of OpenStack Congress and the CTO and co-founder of Styra, Inc.  Before that he spent 2 years as a software engineer at VMware, and in 2008 he received his Ph.D. in declarative programming languages from Stanford University.  He spent the last 15 years designing and implementing policy-aware systems in different domains, such as networking, (what at the time was called) utility computing, configuration management, web security, game-playing, and access-control.)*

* **Ramki Krishnan** *(Ramki has over 20 years of proven industry experience in the areas of Networking, High Performance Switching and System Management. He has over 10 years of experience in Standards Development and Leadership, Research Leadership and Managerial role. He has previous startup experience.  He combines deep technology understanding with strategic thinking to bring customer-winning products and solutions to reality with a direct impact on revenue generation. His expertise includes a wide range of technologies and market trends, including: Networking Protocols (BGP etc.), SDN, NFV, SDS, SDI, Cloud, Security, Open source (OpenStack, OpenDaylight, OSM, and OPNFV etc.), Intel Processors, Servers, Storage, Agile and DevOps, REST, YAML, IPMI, Redfish etc. He is a recognized innovator with 19 US patents and 8 IEEE conference papers including a best paper award. He is a thought leadership speaker in key conferences such as ONS, OpenStack, OpenDaylight, NFV World Congress etc. He is a leader and active participant in several research and standards organizations such as IRTF, IETF and ETSI NFV etc. )*

* **Eric Kao** *(Software engineer at VMware and core reviewer on Congress.)*

Enabling Application Delivery with Kubernetes and OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kubernetes is an open-source platform for automating deployment, scaling, and operation of application containers across clusters of hosts, providing a container-centric approach to infrastructure. It offers developers a way to deploy applications quickly and predictably be it locally, in a public or private cloud, or even across multiple clouds. Kubernetes is in the process of evolving to take better advantage of the facilities provided by OpenStack clouds to provide an ideal platform for modern containerized applications while the applications  themselves remain infrastructure agnostic. 


* **Stephen Gordon** *(Stephen is a product manager focused on OpenStack tenant workloads at Red Hat be they virtualized, containerized, orbaremetal. He is currently a facilitator of the Kubernetes OpenStack SIG, an avid collector of “Internet points” at  the Foundation's Q&A portal, ask.openstack.org, and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/. Previously Stephen was a technical writer producing documentation for Red Hat Enterprise Linux OpenStack Platform, Red Hat Enterprise Virtualization, and related open source projects including the OpenStack documentation project, oVirt, and Fedora.  )*

* **Ihor Dvoretskyi** *(Ihor is an experienced engineer at Mirantis, responsible the for projects tightly bound to Cloud computing, containerized workloads and Linux systems. He is deeply interested in OpenStack cloud platform, other cloud technologies, especially the Open Source projects. Also, Ihor acts as the Kubernetes upstream contributor and OpenStack Special Interest group lead (SIG-OpenStack) at Kubernetes Community, working intensely on the questions and abilities, related to OpenStack and Kubernetes collaboration and integration.)*

Curbing Container Confusion: what you need to know to use the term Containers responsibly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Everyone can agree that Containers is a hot topic.  Unfortunately, when most people talk about "Containers", they are actually talking about different things.  In OpenStack this leads to misleading statements like "Nova can't orchestrate containers" and "Magnum is our container orchestration system" (meaning what is this Zun thing?).  The truth is that OpenStack has no generic container component because anything that makes use of the Linux Containers API is a container.  This means that when most people talk about "containers" they actually mean a particular way their container is built and most likely they mean the container platform (like Docker, Rkt, LXC etc).  The talk will explain what the differences between all these platforms are, and why they need to be different (and why OpenStack actually doesn't need a generic container component).  We will also address the prevailing impression that this is all just a format problem and OCI will sort it all out (it isn't and it won't).


* **James Bottomley** *(James Bottomley is a Distinguished Engineer at IBM Research where heworks on Cloud and Container technology.  He is also Linux Kernelmaintainer of the SCSI subsystem. He has been a Director on the Boardof the Linux Foundation and Chair of its Technical Advisory Board. Hewent to university at Cambridge for both his undergraduate anddoctoral degrees after which he joined AT&T Bell labs to work onDistributed Lock Manager technology for clustering. In 2000 he helpedfound SteelEye Technology, a High availability company for Linux andWindows, becoming Vice President and CTO.  He joined Novell in 2008 asa Distinguished Engineer at Novell's SUSE Labs, Parallels (later Odin)in 2011 as CTO of Server Virtualization and IBM Research in 2016.)*

Magnum and Ironic Integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running containers on bare metal hosts is of interest to some use cases and workloads.   We have integrated Magnum with Ironic for our internal project.   During this integration, we encountered Nova scheduling race condition that slowed down the provisioning.  We also found limitation on current Magnum bay model which restricts our choices for hardware.   In this talk, we will share how we integrated Magnum with Ironic, what Ironic features such as node inspection and secure boot that we used to automate configuration and provisioning of Magnum bay for Kubernetes cluster, what issues and what Magnum bay model limitation we have encountered, and the enhancement blueprints that we have submitted.  We will also talk about Ironic features which are still work in progress that will enhance Magnum and Ironic integration.  Lastly, we will give a demo of this work.


* **Wan-yen Hsu** *(I am a distinguished technolgist at HP Enterprise.  I am working on Ironic, Magnum and container orchestration engines.)*

* **Ligong Duan** *(I am a project manager at HP Enterprise. I work on Magnum and Ironic integration.)*

Monitoring Kubernetes with Monasca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Considering the constantly increasing amount of applications running in containers, providing a reliable and efficiently operable container infrastructure is crucial – in particular at scale. Running Kubernetes, an opensource-system for automatic deployment, scaling and management of containerized applications, on-top of OpenStack have been proven a popular option for container management. The draw-back of this approach was the missing operational link between OpenStack and Kubernetes.In this session we show how Kuberntes run on OpenStack can be comfortably monitored with Monasca (OpenStack Monitoring as a Service). Furthermore we explain how the gained insights can be utilized for operations like alerting, log management and node auto-scaling.In our scenario Monasca is used as the Storage Backend for metrics coming from Heapster and for pod logs. We levarege Monasca alerting functionality to trigger the auto-scaling with Heat. Finally, we will give a demo of our solution.


* **Christoph Held** *(As a cloud architect at Fujitsu, Christoph is passionate about OpenSource in the area of datacenter management. He was working in the OpenStack Monasca project and defined its logging-as-a-service component. Since late 2014, Christoph has been focusing on the usage of Kubernetes in large scale enterprise environments and is now deeply engaged in the Dashboard project.)*

* **Witek Bedyk** *(Witek Bedyk is senior software developer at Fujitsu EST for cloud management software. His current focus is on OpenStack Monitoring Service (Monasca).)*

* **Kamil Choroba** *(I am a senior software developer at Fujitsu Enabling Software Technology in Munich for cloud management software. My current focus is on OpenStack Monitoring Service (Monasca).)*

Kubernetes SDN Performance and Architecture Evaluation at Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Over last year Kubernetes has become similar platform for containers as OpenStack in virtual machines. We spent last 6 month of running Kubernetes for microservices applications as well as for OpenStack itself. We containerazed whole OpenStack including libvirt for more than 100 compute nodes. We discover that networking is one of the most challenging aspects to running Kubernetes. Therefore over the last month, tcp cloud has run extensive performance and diagnostics tests across multiple overlay providers (OpenContrail, Calico, Romana, etc.) as well as against the base Kubernetes Flannel configurations and have come to several insights into CPU penalties. Network design issues at scale as well as performance comparisons use different encapsulation techniques. We deployed Kubernetes cluster on 300 physical servers!  


* **Jakub Pavlík** *(Jakub Pavlik is CTO and chief architect of tcp cloud (http://opentcpcloud.org). He is focused to virtual private cloud and private cloud solutions based on OpenStack and Kubernetes and vendors derivates. He is responsible for whole infrastructure solution (architecture, implementation, operation). He is member of OpenContrail Advisory Board.)*

* **Marek Celoud** *(Responsibility of legacy networking including Data Center Network as well as SDN which includes desing, monitoring, configuration and automation. Focus on OpenContrail, Calico (for Kubernetes) and Cisco Networking solution. Expercience with orchestration of infrastructure services through OpenStack Salt, development and testing OpenStack environment and Kubernetes. Focus on Openstack/SDN based NFV orchestrator platforms. Responsible for Networking Support of enterprise customers and providing professional consulting in the field of NFV/SDN. Experience with architecture, implementation, security and upgrades of networking solution in tcp cloud environment. Hands-on experience with deployment of OpenStack (Juno, Kilo, Liberty and Mitaka) with OpenContrail 3.0 and 3.0.2 using OpenStack Salt.  )*

Openstack-Kubernetes: Using and Deploying Kubernetes with Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications. Kubernetes has the concept of a Cloud Provider, which is a module which provides an interface for managing Load Balancers, Nodes and Networking .  Openstack could be used in a variety of ways with kubernetes :          Kubernetes on top of openstack i.e using openstack as a cloud provider . Containerized deployment of Openstack using kubernetes.  


* **Jaivish Kothari** *(Python Developer. Experienced with python programming concepts, building parallel processing systems. Contributor in Openstack projects.I’m a software engineer passionate about working on Distributed system projects. Being interested in various technologies, I have worked on different aspects of Cloud based technologies and other container technologies.As part of my job, I work on Cloud Storage System using python, Linux and couple of other things falling in between. Currently spending my free time in exploring Openstack.)*

* **MD NADEEM** *(I have start my career around 3 years back with Fibre Optics technology, Over the time develope automation framework for Storage Data Centre in python language, Sometime worked in Data analysis using hadoop and then start contributing openstack from last year, Majorly worked in openstack queueing and messeging service zaqar, in parallel start contributing in other openstack project like nova, kolla etc.  )*

* **Motohiro Otsuka** *(Motohiro is software engineer from NEC. He has been working on projects related to Openstack and Cloud Foundry. He is interested in cloud application deployment. He is Magnum core reviewer since 12/24/14.)*

NFV Solution Using Containers as VNFs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker, with its rich Open Source ecosystem, has gained lot of popularity these days. This talk explores the opportunities of using docker containers as VNFs for the NFV. Docker has always been referred to as stateless and volatile. There has been much debate on the adequacy of replacing VMs with containers. This talk focuses on: Characteristics of VNFs NFV Management & Orchestration and how containers could fit in that space Advantages, potential risks and downsides of using containers in termsl of architecture, stability and cost when used as a VNF Using Docker, Neutron and Kuryr, a demonstration of OpenStack based Service Function Chaining.


* **Prithiv Mohan** *(Currently working as a Network Software Engineer with Intel Shannon. I work with Telco and I am keen on addressing the challenges in OpenStack deployment in real-time Telco production environment and coming up with potential solution. I focus on building potential NFV solututions to address the challenges in OpenStack deployment in Telco. I currently work with Service function chaining and OpenStack Magnum, Containers.   I used to work for @WalmartLabs (e-commerce domain). I have experience in deploying OpenStack for a huge production environment. I have also worked on implementing Storage as Service using Cinder and Ceph for Walmart Production cloud.)*

* **Antoni Segura Puimedon** *(Antoni serves as a core member of Openstack Kuryr and as the Container Team lead at Midokura and works on integrating MidoNet with VM and Container platforms. He has contibuted in the past to the networking stack of oVirt, Libvirt nova-docker and MidoNet. His recent focus has been on Container Software Defined Networking and Container projects like OpenStack Magnum and Mesosphere.)*

Self Healing Cloud: Predictive Analysis before it cost you time and money
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data center is far more complex today than it was a decade ago. The traditional “set and forget” approach to backup and recovery is no longer relevant. New challenges demand new approaches, one of which is the use of analytics to increase the value that backup and recovery provides your business. Self-Healing: for automatic repair or re-provisioning of new resources when a stack becomes unhealthy or a resource is not performing as expected. Integration of OpenStack with Kubernetes has built in self-healing mechanisms, such as auto-restarting, re-scheduling, and replicating containers. As a user, you just define the state and Kubernetes ensures that the state is met at all times on the cluster. We’ve all had issues troubleshooting OpenStack services, whether it’s in the pre-build architecture or post build service failure.    


* **Himanshu Dwivedi** *(Nearly 10 Years of experience in Cloud consulting and Infrastructure Design (Primarily IaaS and Paas ), PreSales, Client PoC, Virtualization (vmware/HyperV/KVM), UseCase Design and Execution , Data Center Consolidation and OpenStack Evangelism.   Founder member of OpenStack india user group and  focus has been customers, technologies and products and how do they interact with each other. Wealth of experience in datacenter technologies ranging from compute, networking to storage.  )*

* **Vaidyanath Manogaran** *(A technically astute professional with 10+ years of experience in quality assurance, project management, solution architecting, develops & puppets, cloud computing and openstack on the cloud and storage technology)*

* **Soumit Mishra** *(7 Years of experience in design and implemention of Automation frameworks, covering UI , CLI, REST API,  across various domains like Virtulization, NMS, Public cloud, SDN, NFV.)*

Kolla and Kubernetes and labs, oh my!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As community developers at AT&T, we desired a tool that allowed us to deploy scalable clouds to our development labs with ease.  In order to embrace community best practices and to allow our development lab to scale, we decided to evaluate kolla and determine whether it would be a great choice for our team.  With the emergence of kolla-kubernetes, we found a tool that could allow us to better manage our development labs, and also allowed us to evaluate kolla-kubernetes as a proof of concept for future production deployments.


* **Steven Wilkerson** *(I'm currently involved in helping evolve AT&T's involvement in open source projects, particularly with OpenStack.  My technical interests include:  infrastructure, various deployment methodologies, and aligning my skills and the skills of my peers with the DevOps lifestyle.  Before AT&T, I interned with Emerson Electric in Saint Louis, and I also interned with The Genome Institute at Washington University School of Medicine in Saint Louis.    )*

* **Tin Lam** *(Worked as a software engineer / architect for the past 12 years and started cloud development/deployment about three years ago.)*

* **Larry Rensing** *(Larry Rensing, AT&T is a Software Engineer with the OpenStack Community Team at AT&T.  His interests include containerization, deployments, and scalability.  Prior to AT&T, he worked as an engineer at Emerson Electric. He has a BSc in Computer Science from Southern Illinois University Edwardsville.  )*

Magnum is not the OpenStack Containers service? How about Zun?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers are hot. Everyone love them. OpenStack is undergoing a continuous evolution toward full-edged container support. Currently there are various projects which try to enable containers on Openstack like Nova-docker, Murano, Heat etc., but none of them have been proven to be the perfect solution. Magnum aimed to make containers available as first class resource in Openstack but went in a different direction recently. In the Austin summit, the Magnum community decided to limit the scope to the management of Container Orchestration Engines and leave the management of containers to a new project which is now called Zun. In this session, we will brief the recent change of Magnum mission statement. Then, we will introduce the Zun project, its targeted use cases, and the rationales to create this project. We will also welcome use cases, ideas from attendees if any.


* **Hongbin Lu** *(Hongbin is currently a Senior Software Engineer in Huawei Technologies. He is serving as the Project Team Lead (PTL) for OpenStack Magnum project in Newton release cycle. He is also the founder/core reviewer of the Zun project (a new container service for OpenStack). His expertise including container related technologies, application deployment and management, and cloud computing.)*

* **Madhuri Kumari** *(Madhuri is a Cloud Software Engineer at Intel Technology India Pvtt. Ltd. having an experience of 4 years in the storage and cloud domain. She is core reviewer in Openstack Magnum Project and also one of the founder/core reviewer for Zun project. She has also contributed to Openstack Object Storage Project, Swift.)*

* **Eli Qiao** *(Qiao, LiYong(Eli)is an OpenStack engineer. He was an virtulazition(KVM/libvirt)  Engineer before, and worked for IBM, now is working for Intel Corp. He Joined OpenStack community since Juno release and continue contributing to Nova project till now. He helped to doing nova-api enhancement, v3 api, micro-version, and other features, and lots of bug fix in nova. Besides he is also a core reviewer for Magnum project also has some contributions for other related projects, like zun, project-config etc.)*

Container Wars: The Persistence Awakens
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One size does not fit all needs for container data persistence and each approach/storage provider has its own unique advantages/disadvantages.  Join us as we discuss solutions such as Cinder, libstorage, Ceph, and even the newly announced Torus and provide an overview for each one.  Finally, we will wrap-up the session with a demo of leveraging Cinder for container volumes.   Attendees will: Learn about different approaches to container data persistence  Get an overview of a few different options Understand how Cinder can be used in this use-case and see a demo


* **Shamail Tahir** *(I am an Offering Manager for OpenStack Initiatives at IBM Cloud and enthusiastic about technology.  In my current role, I am focused on open-source and product strategy.  I have been in the OpenStack community since 2013 and I am currently participating in the Product, Enterprise, Operator Tags, and AUC Recognition working groups along with Superuser.TV.   I am a core member of the openstack-user-stories (product WG) and OpenStack UX teams.  My background includes server/network operations, pre and post-sales engineering, as well as being a technologist focused on cloud and cloud-related eco-systems (Containers, CloudFoundry, Mesos, K8s, etc.) I am passionate about OpenStack, emerging technologies, implications of technology shifts on datacenter architectures, and driving technology adoption. You can follow me on twitter: @ShamailXD  )*

* **John Griffith** *(John Griffith, Principal Software Engineer at SolidFire, helped to create the Cinder project in OpenStack.  His primary responsibility at SolidFire is technical contributor to OpenStack and Open Source technologies.  He served as Technical Lead for the Block Storage Project since it's beginning through the Juno release, and also has held an elected seat on the OpenStack Technical Committee on and off over the past four years. John has over fifteen years of engineering experience in both hardware and software engineering.  He’s been an active user and contributor to open source for close to a decade, and has been focused on OpenStack since January of 2011. In addition to his technical contributions, John also spends a lot of his time talking to people who are interested in learning about OpenStack as well as gathering feedback from current users.)*

Container Orchestration Tapas: Kubernetes, Murano, Magnum and Swarm on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many organizations looking to adopt containers to increase speed for their developers have found OpenStack to be their path to production because OpenStack provides a single platform and set of APIs for virtual machines, bare metal, and containers. Containers are a hot commodity for developers these days but orchestration is where containerized application can reach production grade.  On the other hand, developers have always been told to ignore the underlying infrastructure when moving to the cloud, so the question here is, why should they care about the container orchestrator? The answer is that developers still need to be able to deploy at least a basic architecture to build and test, so it's important to make things as simple as possible.  Fortunately, OpenStack provides multiple easy-to-use options such as Murano and Magnum, and we're going to look at -- and demo! -- them in this session.


* **Ayrat KHAYRETDINOV** *(Ayrat Khayretdinov is Openstack Deployment and Migration Engineer at CloudOps. Was part of large scale Openstack deployment AIC and migration project in ATT. Currently involved in Live Swift cluster Migration for public cloud provider Cloud.ca. In his free time Ayrat is organizing and presenting on OpenStack, Docker and Kubernetes meetups in Montreal. In the past Ayrat worked with OSS and BSS solution integration, migration and monitoring at Ericsson. Ayrat graduated with Master degree in Electrical Engineering from Concordia University, Montreal, Canada )*

* **Stacy Véronneau** *(Cloud Evangelist, Technical Lead with a business know-how, avid GTD methodology user, Open Source advocate and crowd-funding believer. Specialized in global solutions delivery and management in areas as diverse as publishing, finance the mobile and telecom world. I excel in implementing and managing solutions that enables companies to develop and transform their IT infrastructures while maximizing their return on investment.  For OpenStack, this means Day 1 validation but mostly Day2 discussion with customers. <<OpenStack Cloud builder since Grizzly>> "Any sufficiently advanced technology is indistinguishable from magic." -- Arthur C. Clarke)*

* **Ihor Dvoretskyi** *(Ihor is an experienced engineer at Mirantis, responsible the for projects tightly bound to Cloud computing, containerized workloads and Linux systems. He is deeply interested in OpenStack cloud platform, other cloud technologies, especially the Open Source projects. Also, Ihor acts as the Kubernetes upstream contributor and OpenStack Special Interest group lead (SIG-OpenStack) at Kubernetes Community, working intensely on the questions and abilities, related to OpenStack and Kubernetes collaboration and integration.)*

High performance ephemeral storage backend for Containers in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As more and more workloads shift from running in virtualized environments to containers, there is a need for high performance ephemeral storage backend in OpenStack. In this session, you will be introduced to a OpenStack storage provider which can be used with Magnum or Kuryr which combines memory (RAM) and commodity SSD to form a high performance ephemeral storage backend optimized for container based workloads.  


* **Ketan Nilangekar** *(Ketan Nilangekar is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

* **Rakesh Ranjan** *(Rakesh Ranjan is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

* **Abhijit Dey** *(Abhijit Dey is a Sr. director of engineering in Information Availability at Veritas. He leads Cloud and Embedded Solutions within Storage Engineering team and is responsible for cloud, NAS and storage deliverables. Abhijit has worked in the storage industry for more than 18 years and is a technologist at heart. His key focus areas are Virtualization, OpenStack, Storage and Cloud. Abhijit is interested in participating in the OpenStack community and new-age storage innovations in the cloud ecosystem.)*

Cross-Cloud Migration of Container Persistent Data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As Container technology gains more popularity and more people use it, advanced usage issues arise like the ability to migrate a container between clouds, along with its persistent data volume. In this session we will share our experience of using Smaug, Cinder, Nova and Magnum to migrate containers  persistent data between different infrastructures.


* **xinyong xiang** *(Xiang Xinyong is a Senior Technical Engineer in Huawei. My research interests are in cloud and open source technologies. I received his double bachelor's degree in 2008 from the ChongQing University. I have 7 years of data protection and migration related experience, and joined Huawei in 2015. Focused on cloud technologies, he has contributed in lots of the project, including Smaug, Murano, Magnum etc in the OpenStack Community.)*

* **rong zhu** *(3 years openstack development experience, Now works for 99cloud. Murano project core member.)*

Free speed! It's not even illegal!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many users who are interested in the bare-metal speed of containers, even those who may not even know it. In this talk, I'll cover how to use nova-LXD with your OpenStack, and what that experience will feel like for end users. In particular, I'll discuss what sorts of things users can't be allowed to do safely in containers today and what sort of work is happening in the kernel to allow this. I'll also discuss what things may *never* be safe for users, and what OpenStack could do to potentially make using containers easier for users.


* **Tycho Andersen** *(Tycho is a software engineer at Canonical actively working on several cloud-related projects, most recently as one of the core developers of LXD, an open source Linux Container based hypervisor. He holds degrees from the University of Wisconsin--Madison and Iowa State University, and has co-authored several peer-reviewed papers. In his spare time he rides bikes and does improv comedy.)*

Converting a traditional app to containers: how CrowdStar built an effective ecosystem on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk, mobile game developer CrowdStar will explain how and why they moved toward containers after switching to an OpenStack infrastructure provider, how refactoring a monolithic application to micro-services can be a challenge and the benefits that they hope to achieve by leveraging containers. They will also outline how they chose the best tools for the job (i.e. Kubernetes, Rancher, Prometheus) and how they stitched them together to orchestrate this containerized environment. This talk is full of practical, actionable information based on almost two years of experimentation, and solutions found to the most common challenges (including CI / CD) currently faced by DevOps departments seeking to refactor apps. Finally, Internap will lift the hood on adapting an existing OpenStack cloud to facilitate customer application containerization and operation.


* **Stephane Antoine** *(Stephane is Internap’s Senior Manager Cloud & Platform Engineering and Operations. He is in charge of the team responsible for architecting, deploying and managing the OpenStack-based IaaS platform and related services.   Stephane has been with the company since 2014 and has seen it through the adoption of OpenStack as the orchestration platform for Bare Metal servers (through Ironic) in 6 regions worldwide as well as ongoing OpenStack upgrades. His primary concerns are the deployment of Public Cloud with Baremetal support, the rollout of new features and functionality in these Openstack-based services. He works very closely with customers to make sure that their engineering / technical requirements are incorporated into future releases of our IaaS platform.)*

* **Jose Avila** *(Jose (known to all as Tachu) started out at CrowdStar 7 years ago as Director of Operations. In this role, he oversaw the architecture and operations of a portfolio of Facebook apps that reached 12 million daily active users. He was responsible for scaling these apps on a homogeneous infrastructure architecture. Now, as VP of Engineering, Tachu leads both development and operations for Covet Fashion, one of the top grossing apps in both iTunes and Google Play. His team is focused on deploying infrastructure capable of handling a high amount of users and of rendering 1 million “looks” in the app daily. Once again, his challenge is to adapt the current infrastructure so that it is scalable, portable and resilient for the future.   Tachu held engineering positions at Kickapps Corporation/Yuku, Cisco and Ezboard before joining CrowdStar. Tachu studied finance at Universidad Francisco Marroquin in Guatemala and is an avid football (as in soccer) fan.)*

* **Mark Sullivan** *(Mark has been with CrowdStar for over 7 years, starting out as a system administrator and quickly growing through the ranks. Today, Mark manages CrowdStar’s applications and ensuring that they are running optimally.  More recently, Mark has started looking at adopting container technologies to make his apps more resilient, portable and scalable.)*

Multi-tenancy Kubernetes Container Cluster with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In order to make Kubernetes containter cluster work in Multi-tenancy cases, we make use of Keystone to be Authorization/Authentication provider for container clusters integrated with OpenStack IaaS, to support Multi-tenant scenarios. In this presentation, we will show a deep dive how Kubernetes containter clusters use Keystone as the Authorization/Authentication provider, and pass the same role to Neutron, Cinder etc. other OpenStack components, make container clusters part of OpenStack.  


* **Yin Ding** *(Dr. Yin Ding is the new generation Virtualization Technologist at Huawei IT product line. Yin is responsible for creating and communicating technical vision and strategy for Cloud Infrastructure and Container Technology business. He works closely with IT Product line R&D teams to bring the new generation cloud technology into Huawei IT products. Before joining Huawei, Yin spent over ten years at Microsoft and VMware working on platform and cloud computing. Yin holds Ph.D in Computer Science from Arizona State University, bachelor’s and master’s degrees in Computer Science from Tsinghua University.)*

* **feiran hu** *(Hu, Feiran.)*

Load Balancing Containers in Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Container orchestration platforms such as Kubernetes simplify deployment and management of containerized applications across a cluster of machines. The OpenStack community has embraced Kubernetes with projects like Magnum. One key part of any high-performance web application is load balancing. Kubernetes provides built-in support for TCP/UDP load balancing and provides the Ingress resource to configure HTTP load balancers. This resource, however, covers only simple use cases, which leaves users on their own when applications need to support advanced use cases such as WebSocket, extended content-based routing, session persistence, etc. NGINX is a high-performance open source load balancer as well as a content cache and web server. The fact that it is lightweight and highly scalable makes it a great load balancing solution for Kubernetes, and explains why community members are embracing this solution for their containerized applications. 


* **Owen Garrett** *(Owen Garrett leads the product and go-to-market strategy for NGINX’s web acceleration and delivery technologies. Owen has over 15 years of experience in software engineering and product leadership at companies such as Riverbed. Today, Owen uses his technical and management expertise to optimize NGINX products and customer satisfaction.)*

Containers in the Enterprise: Are We There Yet?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn how containers can empower software developers to unlock new value for your enterprise. For enterprises, implementing containers and container cluster management is all about giving application developers a more agile, responsive and efficient cloud infrastructure. For cloud operators, however, delivering that infrastructure is a big departure from the days of VMs. This presentation will give the audience greater insights into: what the adoption curve looks like for containers in the enterprise benefits CIOs can realize—versus the risks—from jumping in now rather than waiting how VMs and containers might—or might not—work in tandem to achieve agile infrastructure goals how OpenStack and Kubernetes can deliver VMs and containers via one control plane how terms like “enterprise ready” can be loaded and unhelpful what new tools are emerging to help agile infra operators deliver the service levels and security that app devs need


* **Sumeet Singh** *(Sumeet Singh is the Founder & CEO of AppFormix. AppFormix optimizes enterprise clouds by providing sophisticated analytics and control of how virtualized infrastructure interacts with applications. Previously, Sumeet was the Principal lead for Hybrid Cloud Networking at Microsoft Azure.   Sumeet’s PhD. thesis at UCSD directly led to him co-founding NetSift, which was subsequently acquired by Cisco, where he led the integration of the NetSift distributed network analytics technology into Cisco products. Sumeet, has over 15 years of experience in the field of distributed systems, he holds 20 patents, has authored 15 research papers and is a recipient of the prestigious MIT Technology Review TR35 award.)*

Building Immutable LXD Container Images from Scratch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Linux container images traditionally include system services and utilities that are not always needed or desired by application developers.  Ideally, containers should only have the files and executables actually needed by the application.  This apporach reduces the size of the container images significantly, as well as reducing the need to patch unused software for bug and security fixes.  LXD is a system level container that provides features not typically found in other application-oriented containers.  The nova-lxd compute driver enables organizations to run LXD system containers on bare metal in an OpenStack cloud, instead of using nested virtualization inside of instances.In this presentation, I plan to present how to build a minimal LXD container image from scratch that can execute an application in an OpenStack cloud.  This minimal application image will be built from distribution-provided packages and automated with Ansible, allowing for ease of use and repeatability.


* **Michael Gugino** *(Michael Gugino works for Walmart on their Cloud Operations team at in Reston, Virginia, USA. He has knowledge and experience with Python, Ansible, Puppet, C, MySQL, RabbitMQ, NoSQL, and of course, Linux. Michael contributes regularly to OpenStack-Ansible.)*

Dev and Ops - Separate Islands No More!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Bringing the power of infrastructure to applications by bridging the gaps between Developers and Operations. Application intent can be communicated to infrastructure for better reliability and performance. The key is to make infrastructure, and application intent policies available for developers to consume in an easy and seamless way. In this session we will share how we are leveraging OpenStack and other completely open source and vendor neutral technologies, that enable developers to attach application intent for infrastructure to provide optimized treatment.  Using OpenStack Magnum, we will deploy Docker containerized applications on kubernetes scheduler with application intent and other operational policies enforcement via project Contiv.


* **None None** *(None)*

Containers without Chaos
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Container technology is gaining traction within the OpenStack community. While one of the goals is to make developers’ lives easier, containers alone won’t solve development and deployment issues. Having a strong and automated tool set for service discovery, networking, and load balancing are critical when your applications need to scale. In this presentation, we will share best practices for service discovery and registration in your OpenStack environment – a complex task. We’ll demonstrate how to implement these practices with NGINX, the top software-based application delivery platform available today, and the most downloaded application on Docker Hub. We’ll also cover multiple methods of automating load balancing and service discovery to take advantage of available open source solutions.


* **Owen Garrett** *(Owen Garrett leads the product and go-to-market strategy for NGINX’s web acceleration and delivery technologies. Owen has over 15 years of experience in software engineering and product leadership at companies such as Riverbed. Today, Owen uses his technical and management expertise to optimize NGINX products and customer satisfaction.)*

Cinder, Manila, Kolla, Docker: The challenges and opportunities of deploying OpenStack on Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a highly distributed platform consisting of multiple services, each with their own software dependency stack. Managing the lifecycle (from deployment through update and upgrade) of these services along with their dependencies poses interesting challenges - even more so when you need to ensure desired availability for these services. One way to deal with these challenges is by containerizing OpenStack services. This can not only simplify deployment, scaling, and updates, but also allow the operator to deal with each service as a discrete unit. The Kolla Project provides the necessary tools to simplify deployment and orchestration of OpenStack services on containers. Manila's new container driver also enables us to exploit a Docker container as a share server instead of a virtual machine.  In this session, we'll discuss the advantages and challenges of deploying OpenStack on containers and how the approach impacts OpenStack Cinder and Manila.


* **Sumit  Kumar** *(Sumit earned his bachelor's degree in Computer Engineering from Virginia Tech in May 2015. He then joined NetApp as a Technical Marketing Engineer, and has been involved with OpenStack since. He has been an active participant in various Openstack meetups, and has presented sessions on various topics on Openstack forums. He is very excited about the future and potential of OpenStack, and looks forward to contributing to the OpenStack community.)*

* **Andrew Sullivan** *(Andrew has worked in the information technology industry for over 10 years, with a rich history of database development, DevOps experience, and virtualization. He is currently focused on storage and virtualization automation, and driving simplicity into everyday workflows.)*

Elevating Magnum to Production with Cinder and Manila Persistence
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Modern applications are using more and more data, which makes doing rapid development and testing with those data sets difficult and expensive.  For organizations which want to transition to using containers for dev, test, or even production, the prospect of migrating data from Cinder or Manila volumes into something perceived to be more container friendly is daunting.  However, the container orchestrators managed by Magnum, Swarm, Kubernetes, and Mesos, can all take advantage of those volumes directly using the Docker Volume Plugin paradigm. This session will explore how to clone Cinder and Manila volumes, introduce them to the orchestration platforms, and integrate them using the native persistent storage mechanisms for each orchestrator.  This drastically simplifies the process of dev and test for large data sets when the application is run in containers, and further removes barriers to transitioning to Docker for cloud native applications.


* **Andrew Sullivan** *(Andrew has worked in the information technology industry for over 10 years, with a rich history of database development, DevOps experience, and virtualization. He is currently focused on storage and virtualization automation, and driving simplicity into everyday workflows.)*

Containers at Walmart - Kubernetes, delivered by OneOps on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn how Walmart uses OneOps to deliver production grade Kubernetes running on Openstack for our application teams.


* **Vitaliy Zinchenko** *(Vitaliy Zinchenko is one of the 3 original co-founders of OneOps, aquired by Walmart in 2013. He has more then 20 years experience designing and implementing large, scalable systems with high availability. Prior to OneOps, he was a Principal Engineer at eBay, where he was responsible for the design and implementation of eBay operations automation systems. He has a Master's degree in Applied Mathematics from National Technical University of Ukraine.)*

* **Michael Schwankl** *(Creater of the Kubernetes pack in OneOps )*

Best practices for using containers to simulate Computes for scalability testing  of Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalability testing of OpenStack require huge number of baremetal computes.Addition of more bare metal computes for meeting increased simulation demands is redundant in the long run.A cheap alternative required to do control path testing and data path testing . Docker containers can help in simulating computes : 1. Using a single baremetal server , user can create 100+ containers2. Each of these containers is used to simulate compute nodes by installing required openstack components/services on it.3. On simulated computes lightweight VMs are spawned4. Effectively we can create 100+ computes using a single baremetal server. This session will present following: 1. How one can use Docker containers to simulate computes.2. Using this environment, test the scalability limit of cloud infrastructure 3. Using this environment, perform VM lifecycle operations.4. Test datapath of simulated VMs    


* **Alok Maurya** *(Working as  Sr. Software engineer at  HPE . I and  responsible  for  performing scalability  testing of  HPE Helion  products . I have  been actively involved  in  contributing in upstream  in  different  projects networking-l2gw , monsaca , tempest .)*

* **Ashish Gupta** *(I'm working with Openstack more than 4 years. Now I'm Senior Software developer at Hewlett Packard. My main interest is in Cloud computing especially OpenStack .Contributed my work in neutron related project such as vpnaas,lbaas,fwaas , networking-l2gw ,automation (tempest), ironic baremetal networking provisioning mech driver implementaion,monasca-agent ovs/libvirt plugin  implementation and testing.Currently involve in automating monasca-agent ovs/libvirt plugin.)*

* **Rajkumar Thiyagarajan** *(I am  working as  Sr. Software engineer at HPE , I  work  on  scalability testing of  products.)*

Use Magnum To Deploy Kubernetes on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we will explain to you the business driver to position Mitaka version of Magnum on OpenStack Liberty environmet to orchestrate the deployment of Kubernetes v1.3 cluster; You will hear from the speakers about the technical challenges we ran into and how we solved them in order to provide Kubernetes as a value-adding service to different organizations. For example, security enhancement of Magnum client and API, support of HA at Magnum level and at Kubernetes cluster level, access to Cinder storage as persistent volume; In addition, we will also share with audience several use cases we can run application inside containers in Kubernetes cluster.


* **Shixiong Shang** *(Shixiong Shang started his career back in 1999 at Nortel Networks. In 2005, he joined Cisco Systems and has been working in Cisco Advanced Services organization for many years on Service Provider Video solution in datacenter and cloud environments.  Shixiong put his arms around OpenStack since Folsom release to virtualize software-based video encoder applications on OpenStack. In 2013, Shixiong and his coworker, Randy Tuttle, successfully enabled OpenStack Grizzly, and then Havana releases over IPv6. The whitepapers were published and received warm acceptance from the community. Afterwards, Shixiong became active contributor to Neutron IPv6 subteam. Shixiong is a frequent speaker to local OpenStack community during meetups on various topics. He also delivered two sessions in Vancouver Summit. Right now Shixiong is CEO of CloudPerceptions, a cloud service-assurance startup company based in Raleigh, NC, USA.)*

* **Randy Tuttle** *(Randy began his career in software development for Nortel Network / Bell Northern Research in telephony-based VoIP systems. Following Nortel / BNR, Randy joined Cisco Systems Advanced Services SP Video, where he broadened his knowledge in data center and cloud eco-systems. This is where Randy was first exposed to OpenStack. Since that time, Randy has been working with OpenStack since the Havana release across various components of OpenStack, primarily in Neutron. His principle focus has been on IPv6 and its implementation in OpenStack. In the Havana release, Randy along with his colleague, Shixiong Shang, developed a PoC of IPv6 in Neutron, and then became involved with the IPv6 sub team when it formed in the Icehouse release. Randy currently works for CloudPerceptions, a cloud service-assurance startup company based in Raleigh, NC, USA. In his role at CloudPerceptions, he is responsible for defining the product evolution strategy, requirements, and architecture.)*

Why Openstack is the platform of choice for hosting your Container Orchestration Engine.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every company starting to look at a platform for their new agile project face the same questions, should i buy a PaaS or should i build a CaaS. If they chose to build, then they must chose the right Orchestration engine and once again choices made so far often makes reversibility harder. Fortunately Openstack is already a plateform of choice for PaaS and CaaS. Let's demonstrate how Openstack Magnum will help you to adress your CaaS requirements from POC to production.   


* **Christophe LE DORZE** *(11 years in IT, from Network to Systems, from Operator to Architect and Security Officer. Today works at SUSE, a Linux Company.)*

Put a Lid on It! Secure Kubernetes Container Workloads with Production-Grade Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Container orchestration engines like Swarm, Kubernetes and Mesos highlight the importance of network security that scales with growing deployments. With Cloud Native applications built by composing microservices, the ability to control traffic as it flows among these services becomes critical.  The Kubernetes Network SIG worked over last year to define Network Policy with the ability to control traffic among containerized services. At the same time, open source projects Kuryr and MidoNet have been advancing to achieve network security for containers in a simplified, distributed architecture. Removing architectural bottlenecks, Kuryr + MidoNet efficiently implement security policies through the hardened Neutron framework for use by containers in large scale environments. In this talk, we will discuss the latest updates of the Kubernetes Network SIG group, insert Neutron as a networking framework, and explore Kuryr and MidoNet networking solutions with advanced use cases.


* **Tim Hockin** *(Tim Hockin is a Senior Staff Engineer at Google. He was the co-founder for the Kubernetes project, an technical lead for Kubernetes, a container cluster management system (open-source). He is an advisor and co-maintainer of the appc spec. https://speakerdeck.com/thockin)*

* **Irena Berezovsky** *(Irena Berezovsky is a Senior Architect for Midokura. She is responsible for driving open source MidoNet compatibility across all the OpenStack projects.  An active contributor to Neutron and Nova for several releases, her noteworthy contributions to the open source community include introducing SR-IOV support into Openstack and related OSS projects like SFC, Kuryr, tricircle. Her specialties include distributed systems, open source, embedded and network management software design and architecture. Before her current position at the Midokura CTO team, Irena worked at Mellanox Data Center Solutions group, leading Mellanox product strategy and innovative technology SDN oriented integrations as well as leading Mellanox strategy for integration with OpenStack. In the past, Mrs. Irena Berezovsky led architecture and product strategy for Voltaire and Nokia Siemens Network. Mrs. Irena Berezovsky holds a Bachelor of Science in Computer Engineering and Economics from the Tel Aviv University)*

* **Cynthia Thomas** *(Cynthia is a Systems Engineer at Midokura. Her background in networking spans Data Center, Telecommunications, and Campus/Enterprise solutions. She is a frequent speaker at cloud conferences such as OpenStack Summits, OpenStack meetups and the IT Cloud Computing Conference (IC3). Cynthia has earned a number of professional certifications, including: Alcatel-Lucent Network Routing Specialist II (NRS II) written certification exams, Brocade Certified Ethernet Fabric Professional (BCEFP), Brocade Certified IP Network Professional (BCNP), and VMware Technical Sales Professional (VTSP) 5 certifications. Cynthia received her B.Sc.(Eng) and M.Sc.(Eng) from Queen’s University in Kingston, Canada.)*

Unified application model for VMs and containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As containers become as popular for enterprise workloads as VM instances, there is an emergent need to provide a unified application development paradigm across both domains. In this talk, we describe how we achieved this by creating a new kubernetes driver for Nova. This driver is provided with the kubeconfig for the given Kubernetes cluster during initialization. During instance provisioning, it automatically converts the given Glance image into a docker image. The cloud-init customization scripts are injected into the docker image to be run on startup. The driver deploys a single service targeting a single pod when creating an instance, with a replication controller of just 1 replica. Heat was also modified by adding another parameter to the AutoScalingGroup - the kubeconfig. When this parameter is present, Heat creates an appropriate ReplicationController for the instances instead. Finally,we demonstrate the use of the same Heat template to deploy a VM or container based workload.


* **Amrish Kapoor** *(Amrish Kapoor is an early engineer with Platform9 Systems, and leads the vSphere integration effort with Platform9's SaaS-Managed OpenStack offering. Amrish is formerly from Microsoft, where he held technical and management leadership roles, helping ship components of the Microsoft Desktop Optimization Pack (MDOP) suite of virtualization products. He is passionate about his family, work, and sports.)*

* **Bich Le** *(Spent most of career innovating in the cloud and virtualization areas. Before co-founding Platform9, spent 14 years as a Principal Engineer at VMware, helping them innovate their way from a small startup to a multi-billion dollar powerhouse. Prior to that, architected the Aries RISC-to-IA64 dynamic translator at Hewlett Packard. Graduate of U.C. Davis Node.js enthusiast and maintainer of the fuse4js github project.)*

Adaptive Monitoring and Auto-recovery of Openstack services in kolla
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kolla is helping to make each service running independently.when some container killed, currently there is a difficulty in getting the status of the service and container and manual intervention required to start the container which creates a downtime in the whole clusterThere is 3 ways we can monitor the kolla services1. Reactive:This kind of monitoring can be achived by the orchestration engine updates the monitoring system2. Proactive:This kind of monitoring can be achived by adding precautionary measures for the known issues, where, if the issue occurs it immidiately starts the precaution to eradicate the fault.3. Adaptive:This is better suited for monitoring a frequently changing system like docker containers, as it can adapt itself to the micro services that get intorduced into the containers. Now the question is “Is the adaptive montoring a full solution to the abovementioned challenges?"- We need solutions at different levels of openstack services and containers and hypervisor


* **Satya Routray** *(Open-source enthusiast who loves new technologies and lookout for areas to innovate. Been working in virtualization and cloud based technologies for the past several years. Previously worked on various components of Openstack such as Compute, Neutron, Cinder, Swift, Docker. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Presented on Monitoring Docker and Dockerised applications in 2015 OpenStack Tokyo summit. Presented on Optimising NFV service chains on openstack using docker in 2016 Openstack Austin summit Presented on Multenancy for docker container with keystone in 2016 Openstack Austin summit)*

* **Don Nalezyty** *(None)*

Monitoring Engine for Linked Containers and Application stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Based on interest received after the last presentation, http://www.slideshare.net/AnanthCB/monitoring-docker-container-and-dockerized-applications we would like to demo a running instance of the monitoring engine integrated with Elastic Search, Logstash, Kibana and Pandas. 1. Demo the traffic and utilization among linked containers 2. Aggregated metrics for apps spread across containers - monitoring applications across docker instances & application classification (DB, Webserver, etc.,) 3. Proactive log based errors, alerts and suggestions to take corrective measures - Ex:Alerts to suggest that the drive is about to be full when a threshold is reached. 4. Custom queries and ability to extrapolate metrics - Ex: The number of times a particular error was seen or SLA was not met  5. Intelligent suggestions to help effective resource planning - Ex: Depending on load / usage trend, application stack can be scaled out


* **CB Anantha Padmanabhan** *(I am an OpenStack engineer, who loves new technologies and is always on the lookout for areas to innovate. I have been working in virtualization and cloud based technologies for the past several years. Previously worked on various components of Openstack such as Compute, Neutron, Scheduler, Cinder and Ceph. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Have contributed to http://ilearnstack.com, an initiative to help newbies ramp up with the technology. Presented a talk on Optimizing NFV service chains using docker, in the OpenStack summit held at Austin in 2016. Link to the presentation : http://www.slideshare.net/AnanthCB/optimising-nfv-service-chains-on-open-stack-using-docker Presented a talk on Providing Multitenancy for Docker using keystone, in the OpenStack summit held at Austin in 2016. Link to the presentation : http://www.slideshare.net/AnanthCB/multi-tenancy-for-docker Presented a talk on Monitoring Docker and Containerised applications in the OpenStack summit held at Tokyo in 2015. Link to the presentation : http://www.slideshare.net/AnanthCB/monitoring-docker-container-and-dockerized-applications The session provided on OpenStack Rally in one of the OpenStack Meetups in India is mentioned in the Rally wikipedia page, https://wiki.openstack.org/wiki/Rally Link to the presentation on Rally : http://www.slideshare.net/AnanthCB/rally-baa-s-os-meetup Linkedin profile : https://in.linkedin.com/in/cbananth  )*

* **Rahul Upadhyaya** *(Has have been working in virtualization and cloud based technologies for the past four years. Previously worked on various components of Openstack such as Compute, Neutron, Scheduler, Cinder and Ceph. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Founder of http://ilearnstack.com, an initiative to help newbies ramp up with the technology. Presented the talk Monitoring Docker and dockerised applications in the OpenStack Tokyo Summit in 2015.)*

* **Meenakshi Sundaram Lakshmanan** *(Been in the openstack and virtualization business for several years, enthusiastic to understand and learn new technologies. Have managed and delivered several projects around Openstack and cloud technologies. Presented on Monitoring Docker and Dockerised applications in the OpenStack Tokyo Summit in 2015. Leading engineering efforts in India for Cloud and Network Solutions group at Cisco.)*

WAN Optimization using Docker Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

WAN optimization solutions such as Cisco® Wide Area Application Services (WAAS) have increasingly emerged as primary IT tools that organizations use to provide application acceleration, WAN bandwidth compression, and local hosting of branch-office IT services. Benefits of WAN optimization include 1. Increased user productivity while accessing centralized applications 2. Consolidation of branch servers & storage 3. Deferral of WAN bandwidth upgrade costs, and a reduced branch-office hardware footprint. Network latency over the WAN is the fundamental reason why applications perform poorly when delivered from the data center to the branch office. We attempt to negate the extra hops between VNFs in a service chain by localizing the operations, running them in containers.  


* **CB Anantha Padmanabhan** *(I am an OpenStack engineer, who loves new technologies and is always on the lookout for areas to innovate. I have been working in virtualization and cloud based technologies for the past several years. Previously worked on various components of Openstack such as Compute, Neutron, Scheduler, Cinder and Ceph. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Have contributed to http://ilearnstack.com, an initiative to help newbies ramp up with the technology. Presented a talk on Optimizing NFV service chains using docker, in the OpenStack summit held at Austin in 2016. Link to the presentation : http://www.slideshare.net/AnanthCB/optimising-nfv-service-chains-on-open-stack-using-docker Presented a talk on Providing Multitenancy for Docker using keystone, in the OpenStack summit held at Austin in 2016. Link to the presentation : http://www.slideshare.net/AnanthCB/multi-tenancy-for-docker Presented a talk on Monitoring Docker and Containerised applications in the OpenStack summit held at Tokyo in 2015. Link to the presentation : http://www.slideshare.net/AnanthCB/monitoring-docker-container-and-dockerized-applications The session provided on OpenStack Rally in one of the OpenStack Meetups in India is mentioned in the Rally wikipedia page, https://wiki.openstack.org/wiki/Rally Link to the presentation on Rally : http://www.slideshare.net/AnanthCB/rally-baa-s-os-meetup Linkedin profile : https://in.linkedin.com/in/cbananth  )*

* **Rahul Upadhyaya** *(Has have been working in virtualization and cloud based technologies for the past four years. Previously worked on various components of Openstack such as Compute, Neutron, Scheduler, Cinder and Ceph. Currently working on cloud and network solutions for Cisco Systems. Have been an active participant in Openstack meetups and have presented sessions on various topics on Openstack forums. Founder of http://ilearnstack.com, an initiative to help newbies ramp up with the technology. Presented the talk Monitoring Docker and dockerised applications in the OpenStack Tokyo Summit in 2015.)*

* **Meenakshi Sundaram Lakshmanan** *(Been in the openstack and virtualization business for several years, enthusiastic to understand and learn new technologies. Have managed and delivered several projects around Openstack and cloud technologies. Presented on Monitoring Docker and Dockerised applications in the OpenStack Tokyo Summit in 2015. Leading engineering efforts in India for Cloud and Network Solutions group at Cisco.)*
