Architectural Decisions
=======================

Deploying and optimizing for cloud storage systems using Swift simulator
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the rise of cloud systems, IT spending on the storage system is increasing. In order to minimize costs, architects must optimize system capacities and characteristics. Current capacity planning is mostly based on trial and errors as well as rough resource estimations. With increasing hardware diversity and software stack complexity this approach is not efficient enough. This session presents a novel simulation approach, which can be used before system provisioning for cluster capacity planning, performance evaluation, and optimization. Questions such as how to size the cluster, how to configure the software parameters and how to choose the best hardware components can be answered even before software and hardware components are made available.


* **Gen Xu** *(Gen Xu is a performance engineer at Intel’s Software and Service Group. Gen has been working in the area of distributed storage cluster modeling and simulation, especially object storage Swift. He has rich experience in performance optimization of storage systems. Gen holds an M.S. in Computer Science from East China Normal University in China.)*

Modularity in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack cloud is usually provided by a single vendor that ensures the interoperability and compatibility of the cloud services. As a result, cloud users (or even vendors of parts of the cloud) need to rely on the cloud provider to include services, OpenStack updates and extensions whenever those are needed. If the functionality of an OpenStack service that is not part of the cloud is crucial for the user, they can try to run the given service in a standalone mode and deliver it with their product. This setup involves all the operability, security and other aspects of delivering an OpenStack service. In this presentation, we argue for a more fine grained service provision setup and we show practical architectural patterns that make the extension of existing OpenStack services easier and practical.


* **Denes Nemeth** *(Nokia)*

The glory and fallacies of abstraction APIs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The usage of abstraction APIs significantly reduces the effort of integrating one application with the cloud or services of the cloud. The talk will cover several abstraction APIs used to access the cloud or the NFV ecosystem. Several examples will be provided that show the limitations of using abstraction APIs in real world scenarios. The talk will aim to collect the main aspects that an architect should consider before choosing the "right" API.


* **Denes Nemeth** *(Nokia)*

OpenStack For VMware Technologists
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Is OpenStack just a free alternative to VMware technologies or are there substantive differences? Is there a way to integrate VMware technologies like vSphere with OpenStack? As OpenStack continues to gain momentum and grow in user adoptoon, VMware admins and architects are being asked to evaluate, deploy and manage new OpenStack clouds. This presentation will walk through the OpenStack architecture and it's various components and explain them to VMware technologists using concepts familiar to them. We will walk through what uses cases are best for OpenStack and what use cases are best on VMware infrastructure. We will also drill down on how OpenStack is able to integrate with vSphere using the vCenter nova driver, neutron, and cinder. Although we will be briefly evaluate various OpenStack offerings that integrate with vSphere, this will NOT be a product pitch or product presentation. All technical detail presented will be based on the upstream code.  


* **Kenneth Hui** *(Kenneth Hui is a Senior Technical Marketing Manager and a Cloud Evangelist at Rackspace. Ken is passionate about helping customers with their Cloud Computing journey and is an official OpenStack Ambassador. Ken blogs about cloud computing, distributed systems, and OpenStack at http://cloudarchitectmusings.com. He lives in New York City where he can indulge in his love of great food from all around the world. You can follow Ken on Twitter @kenhuiny.)*

* **Eric Wright** *(Eric Wright is a Principal Solutions Engineer and Technology Evangelist at VMTurbo, VMware vExpert, and Cisco Champion with a background in virtualization, VMware, OpenStack, Business Continuity, PowerShell scripting and systems automation in many industries including financial services, health services and engineering firms. As the author behind DiscoPosse.com, a technology and virtualization blog, Eric is also a regular contributor to community driven technology groups such as the VMUG organization in Toronto, Canada.When Eric is not working in technology, you may find him with a guitar in his hand or riding a local bike race or climbing over the obstacles on a Tough Mudder course. Eric also commits time regularly to charity bike rides and running events to help raise awareness and funding for cancer research through a number of organizations.)*

On Building an Auto-healing Resource Cluster using Senlin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building auto-healing cluster is always not an easy job in cloud environment. How to accurately detect failures happen in different layers; how to promptly make fencing to prevent further damage; how to make recovery progress automatically and efficiently, all these headaches need to be addressed before we can announce our systems/applications as auto-healing. In this presentation, we will deep dive into Senlin's health management design to introduce how we address all these issues and fill in the gap.


* **Qiming Teng** *(Qiming Teng is a researcher working at the Cloud Infrastructure and Service department, IBM China Research Lab (CRL). His research interests include system software, virtualization, cloud, Java resource management, performance profiling tools. Starting from early 2013, Qiming has been researching topics related to high availability, auto-scaling of virtual machines, applications in a cloud environment. His focus is on the Heat and the Senlin project in the OpenStack community. Before Joining IBM, Qiming Teng received a Ph.D. in computer science from Peking University in 2006.)*

* **Xinhui Li** *(Xinhui Li is a Staff Engineer, development lead at VMware and a core of Senlin project. Her work focuses on design and optimization of distributed systems, mostly in the Cloud computing and big data fields. She has 13 international patents, published 3 technical documents, and 5 papers on international PIC top/target academy journal and conferences.  )*

* **Ethan Lynn** *(Ethan Lynn is a software engineer in IBM, and he starts working on openstack projects at 2013. During his school time, he focus on IPv6 and IPv4 translation technicals, and help to build experimental IPv6/IPv4 translation router on BUPT CERNET2 node. During his work in IBM, he helps to build up IBM cloud production based on openstack, and help design and deliver HighAvailability solution for openstack services. He contributes lots of codes and reviews to openstack projects, especially heat and senlin project, and receive open source recognition award from IBM.)*

Taking OpenStack towards a hyperconverged future.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There has been a few very popular reference architectures of OpenStack that have changed throughout the different releases of OpenStack, but remained very much closely tied to the original formula.  At VEXXHOST, we've worked on building out a far more efficent and faster reference architecture which we've deployed many times for our customers successfully. This architecture is a hyper-converged setup where you can combine both storage and compute on the same node.  It's always been a big no-no to do this, but times have changed and this new architecture works and it's been proven in production.   This starts the discussion of perhaps moving to a new reference architecture for OpenStack.


* **Mohammed Naser** *(Mohammed has been involved in OpenStack since early 2011 in many different ways.  With code contributions in OpenStack since that time as well as operational experience in deploying, running and managing OpenStack clouds for that same period of time.  With a long history in hosting infrastructure, he had lead VEXXHOST to building out one of the first OpenStack Public Cloud's which continues to run today as well as many private cloud deployments for industries that have strong compliance requirements such as financial and insurance industries.)*

OpenStack Local Cloud Architecture Considerations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Sharing of key principles and best practices on OpenStack based Local Cloud architecture design, implementation and operations. This session will go into detail in areas that include Architecture (pros / cons, CAPEX vs OPEX, site survey, BoM decisions), Deployment (supporting infrastructure, automation, QA), Operations (monitoring, upgrades) and Decommissioning.  


* **Fan He** *(Fan is a Cloud Architect at IBM, working on design, implemenation and operation of cloud infrastructure services based OpenStack. Before that he worked as Continuous Delivery and test architect for IBM Cloud Manager with OpenStack and IBM Systems Director, with focus on automation and continuous test initiative. He has rich experience in system management, networking and embedded systems.)*

* **Ken Weinreich** *(Ken is an experienced I.T. professional, working in the industry for over 15 years, in support, operations, development and architecture roles. Ken is currently a Cloud Deployment Architect at IBM focusing on On-premises local deployments of Openstack. Prior to working with Openstack at IBM, Ken encougaged cloud adoption to customers and internal groups as a Cloud Champion at CenturyLink)*

* **Joshua Guan** *(Joshua Guan is an OpenStack Operations Lead and Engineer of Blue Box. Prior to his current assignment, he has been worked as a tester, DevOps developer and Continuous Delivery tech lead on various IBM products and services. )*

How is Ceilometer/Gnocchi scale out?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The utilization data of the virtual or physical resources are very important in data center operations. Once stored persistently, these data could be retrieved for later analysis, such as metering and billing, and could be used to trigger actions when certain criteria are met, such as alarming, etc.  Ceilometer is the service designed to collect those data, and was complained for not scaling very well in its own data store. Gnocchi is the time-series database designed to solve the scale out issues, by working as the data store backend for Ceilometer. In this presentation, we’ll introduce the evaluation work we’ve done for Ceilometer/Gnocchi on how it scales out in typical configurations.  We’ll also give suggestions on how to configure Ceilometer/Gnocchi to make them perform well.


* **Lianhao Lu** *(Lianhao Lu works in Intel OpenSource Technology Center for Openstack. He's currently a core developer for Ceilometer.)*

* **Steve Lewis** *(OpenStack-ansible core developer)*

* **Sumant Murke** *(s/w engineer)*

OpenShift on OpenStack: Delivering Applications Better Together
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many organizations have had success in dabbling with Linux Containers, and once they see a small project have success, the epiphany happens. This leads to additional questions, including:  1. Can we put everything in containers?  2. How do we get our traditional applications into containers?  3. Can we use containers in combination with virtual machines? In this session, we’ll address these the best approach for organizations to make the transition to containers for both new greenfield, and existing traditional applications. Attendees will learn how OpenStack is evolving to integrate with the Linux, Docker, Kubernetes stack to provide the ideal infrastructure platform for modern containerized applications. We’ll also cover an integrated approach to modern applications made up of containers and virtual machines, made possible with an OpenStack infrastructure.    


* **Scott McCarty** *(At Red Hat, Scott McCarty helps to educate IT professionals, customers, and partners on all aspects of Linux containers, from organizational transformation to technical implementation, and works to advance Red Hat's go-to-market strategy around containers and related technologies. He also liaises with engineering teams, both at the product and upstream project level, to help drive innovation by using feedback from Red Hat customers and partners as drivers to enhance and tailor container features and capabilities for the real world of enterprise IT.Scott is a social media start-up veteran, an e-commerce old timer, and a weathered government research technologist, with experience across a variety of companies and organizations, from seven person start-ups to 8,000 employee technology companies. This has culminated in a unique perspective on open source software development, delivery, and maintenance.)*

Application and storage redundancy and availability - What are my options?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Architects are increasingly being asked to investigate the deployment ofmultiple, geographically dispersed OpenStack deployments to support applicationand storage availability and redundancy requirements. This session will present someof the common use cases represented by these requirements and the currently available, supporting OpenStack multi-site deployment options.


* **Tim Cuddy** *(Sr. Product Manager, Hewlett Packard Enterprise Cloud Business Unit Sr. Product Manager, Cisco Systems, Inc. Sales and Sales Support, Apple Computer IT Network Planning, Sprint)*

Globally Dispersed Active-Active Cloud Regions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So the concept and capability of running multiple OpenStack cloud regions is not a new one.  With that said have you actually seen it done?  Is there way to centrally manage all those cloud regions?  How can this strategy be used to replace a disaster recovery design?  What are the components you need to accomplish this design model and have it scale if needed? During this talk we will walk thru a few use cases of setting up an Active-Active cloud region and then physically demonstrate how to accomplish this design in a short demo.  Audience takaways: Review the native capabilities part of OpenStack to run multiple cloud regions Detail out the components needed to architectually setup this design Explore how simple it is to centrally manage those regions Discuss some known areas of caution and how to circumvent them Talk thru how to scale the active-active region design when needed  


* **Walter Bentley** *(I am a Rackspace Private Cloud Technical Marketing Engineer with a diverse background in Production Systems Administration and Solutions Architecture.  I have over 15 years of experience across numerous industries such as Online Marketing, Financial, Insurance, Aviation, Food Industry, Education and now in the technology product space.  In the past, I was typically the requestor, consumer and advisor to companies to use technologies such as OpenStack, now promoter of OpenStack technology and Cloud educator.)*

Architecting An Enterprise-Grade Cloud Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most enterprises don't plan for Multi-Cloud, Multi-Cloud organically happens as one departement deploys OpenStack and another adopts a public cloud. Finding a balance between the needs of multiple enterprise consituencies while leveraging the benefits of a Multi-Cloud environment is proving to be a challege. This talk will explore the "Enterprise-Grade Cloud Stack" and will provide an overview on how today's enterprises approach a Multi-Cloud strategy, what role does OpenStack play, and what are the types of tools that are available to tackle some of the common challenges.     


* **Ron Harnik** *(After graduating from my mandatory military service I worked as a Network Engineer while also teaching technical certification classes. After I realized my passion lies with technical evangalisim I started doing techical training full time. My training position led me to other opprotunities such as QA testing and Product Design, while always finding way to talk about the product, platforms and technologies I was passionate about. I currently run Product Marketing for Scalr, the enterprise-grade cloud management platform. As an active user of multiple cloud platforms, this position allows me to remain hands-on and technical with operations work and have discussions and tell stories about technology at the same time.  Also, I have a YouTube channel where I talk about TV shows :))*

Scaling your cluster with more flexibility, efficiency and reliability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scaling is an important capability of cloud platform. Either auto or manual, users usually need to adjust their resource pool capacity to adapt to the change of workload. However, scaling is not just simply increasing or decreasing the size of cluster. Lots of issues need to be thought over to ensure the scaling progress is efficient, reliable and flexible enough to fulfill the demand of patical usage. In this presentation, we will deep dive into the (auto)scaling design of Senlin project and use real case to demonstrate how to reduce the overhead caused by nodes creating/deleting, how to make scaling flexible, and how to hanlde exception to make the scaling progress recovable and rollbackable.


* **Ethan Lynn** *(Ethan Lynn is a software engineer in IBM, and he starts working on openstack projects at 2013. During his school time, he focus on IPv6 and IPv4 translation technicals, and help to build experimental IPv6/IPv4 translation router on BUPT CERNET2 node. During his work in IBM, he helps to build up IBM cloud production based on openstack, and help design and deliver HighAvailability solution for openstack services. He contributes lots of codes and reviews to openstack projects, especially heat and senlin project, and receive open source recognition award from IBM.)*

* **Yanyan Hu** *(Yanyan Hu is a researcher from IBM China Research Lab. His research field is mainly about Cloud computing and virtualization. He is now contributing to several Openstack projects, including Senlin, Zun/Higgins, Heat, Ceilometer and also working on business solutions that related to private cloud. Currently, he is focusing on continuous service deployment and management cross multiple region/cloud and hybrid cloud environment, especially autoscaling related topics.)*

* **Haiwei Xu** *(Haiwei is a software engineer from NEC. He has been working in the OpenStackcommunity for more than 3 years. His main contributions include Nova, Tempest andhe is also investigating OpenStack deployment using TripleO. Now he is a corecontributor of Senlin project which provides clustering service. Before moving to OpenStack,he has two yearsexperiences of smartphone's security enforcement.)*

ITaaS to Cloud Service Provider - Planning OpenStack for the Enterprise
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Planning a new Private Cloud for your Organisation? Well selecting OpenStack as the Cloud Services Platform of choice is just the begining. The presentation describes aspects of planning & implementation of Internal OpenStack Clouds based on deployment experiences in a large Indian conglomerate.


* **Alok Jani** *(Alok currently works at India's Largest Private Sector Enterprise for the enablement of an internal Cloud Platform for the Organisation. His areas of execution include Technology & Operations Management of OpenStack Deployments, Systems Integration, Tooling & overseeing implementation. He has a backgroud in Systems Engineering, Enterprise IT and Scientific Computing. He has earned his Masters Degree in Computer Sciences and has interests in Operations Management, Business Strategy and Solutions Architectures.)*

Have a bite of 1K+ nodes with a handful of servers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One big reason of the challenges brought by deploying OpenStack at large scale (beyond 1K nodes) is that the code is not developed and tested on a deployment at such large scale.  Intel together with SVMSoft China (a joint venture of Sugon and VMware in China) have been seeking a way to provision a large scale cloud with fairly little hardware mainly for product quality assurance purpose. What has been achieved is an agile, lightweight, scalable system which provisions cloud at large scale in containers. This system has been used for ensuring that our products scale well and provides good performance at large scale. This presentation will reveal data in aspects such as container intensity, footprint, optimization and networking. It also has a performance comparison between vanilla neutron and neutron with OpenDaylight as the backend. This system can be used as a CI (Contiguous Integration) system for community.


* **Rui Zang** *(Rui is a software engineer in INTEL currently working on Cloud development. He has background from virtualization to kernel and storage. Now he is actively involved in OpenStack adoption in P.R. China.)*

* **Isaku Yamahata** *(Isaku Yamahata is a Software architect in the Open Source Technology Center, Intel. His main focus is Network virtualization as Software Defined Networking and Network Function Virtualization. Isaku is an active OpenStack Neutron (networking) developer and has in the past contributed significantly to qemu, kvm, Xen, and Ryu SDN frameworks.)*

* **Jianjie Wang** *(Main points of interests are NFV and cloud security. Architect for Sugon Cloudview 2.0 networking virtualization. Participated in the design of development of Sugon CloudFirm1.0 and 2.0. Participated in the desgin and development of the networking virtulization of Sugon Cloudview1.8.  )*

Best Practices for Database as a Service with Trove: Changing the Paradigm for OpenStack Databases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprises large and small find that the success of their cloud depends on bringing applications to the cloud. It is generally easier to migrate stateless workloads to the cloud, and it is often the case that working with database workloads is a major stumbling point to cloud adoption. This is also compounded by the wide variety of databases that enterprises employ. Even in the cloud, a number of users still deploy database software into virtual machines and containers using some home-grown orchestration but this increasingly has become a pain point. This talk describes how DBaaS using OpenStack Trove can fundamentally change the paradigm for databases in the cloud, and how it can considerably ease the pain in database consumption in the enterprise. Looking ahead, we see an evolution of DBaaS to encompass not just the existing SQL and NoSQL databases but also big-data solutions, and a data pipeline that will provide users with a unified data management platform for the enterprise.  


* **Amrith Kumar** *(Amrith Kumar is an active technical contributor to the OpenStack project, and a member of the Trove core review team. He is also a member of the OpenStack Foundation Job Analysis Task Force and an author of the book on OpenStack Trove. He is the author of the book on OpenStack Trove (published by Apress, http://www.apress.com/9781484212226). He brings more than two decades of experience delivering industry-leading products for companies specializing in enterprise storage applications, fault tolerant high performance systems and massively parallel databases to Tesora, which he co-founded. Earlier, he served as vice president of technology and product management at Dataupia, maker of the Satori Data Warehousing platform , and Sepaton’s director and general manager where he was responsible for the development of the core virtual tape library product. As a director of product development at Netezza, he managed end-to-end product delivery for all customers and prospects. Amrith studied mathematics at the University of Madras (India) and management at the Indian Institute of Management. )*

OpenStack on Raspberry Pi: One Byte at a Time
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying an OpenStack cloud across multiple Raspberry Pi computers.  The idea that using multiple credit card sized computers that cost about $35 each to run an OpenStack cloud seemed like an intriguing idea.  The actual feasibility of it needed to be tested.  There are a few blog posts that describe the general idea; however, most of them were outdated and did not include the latest version of the Raspberry Pi, the Pi 3.  Using a cluster of these devices, we set out to see how feasible it would be to deploy OpenStack using only Raspberry Pi devices.  In total, between two of us, we had a Raspberry Pi 1, two Pi 2s, and several Pi 3s. Our goal: To set up OpenStack on these minimal devices, across the internet in two physical locations.


* **Gage Hugo** *(Applications developer currently at AT&T, primarily focused in Keystone.)*

* **Jeffrey Augustine** *(Working in the upstream community team under AT&T's Intigrated Cloud (AIC) I have just started my OpenStack journey at the beginning of this year, and trying to learn as much as I can!  This project helped to gain an understanding of how components interact and debugging required by our Ops counterparts.)*

Service Discovery and Registration in a Microservices Architecture: what, why and how?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Microservices, Service Discovery and Registration have been heading towards the peak of inflated expectations on the Gartner Hype cycle for over the last year or so, but there has often been a lack of clarity as to what these are, why are they needed or how to implement them well. Service discovery and registration are key components of most distributed systems and service oriented architectures. In this session we will talk about what, why and how of service registration and discovery in distributed systems in general and OpenStack in particular. We will talk about some of the technologies that address this challenge like Zookeeper, Etcd, Consul, Mesos-DNS, Minuteman, SkyDNS, SmartStack or Eureka. We will also address how these technologies as well as existing OpenStack projects can be used to solve this problem inside OpenStack environments.


* **Fernando Sanchez** *(Fernando is a cloud architect specialized in software networking and distributed systems. He's a frequent speaker at Openstack meetups, and has more than four years experience in implementing all sorts of private clouds, ranging from small enterprise to Fortune 100 companies and Service Providers. He works at Mesosphere, where he’s passionate about building cloud solutions to help his customers achieve their business goals.)*

* **Fawad Khaliq** *(Fawad has been a member of the OpenStack community for over four years and a core developer in the Networking ecosystem. He has contributions in several OpenStack projects including Neutron, Nova, Kuryr, Magnum, DevStack. He is also the author and maintainer of networking-plumgrid subproject under Neutron umbrella and has over four years experience in implementing software defined networking, containers, high availability, distributed system and APIs. Fawad is a Senior Software Engineer at PLUMgrid, where he is involved in design and development of cloud computing software components, solving networking problem for new technologies and representing PLUMgrid in various open source forums. Currently, he is working on improving the area of container networking in the OpenStack, Docker and Mesos communities. In future, he plans to solve the problem of application service discovery inside the OpenStack ecosystem. )*

Building Data Centers of the Future with OpenStack and Composable Infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The datacenters of the future will leverage disaggregated hardware with software that enables dynamic programmatic composition, control, and management. The cloud infrastructure can expand and shrink to meet transient demands from workloads, in addition to the hosts themselves being repurposed to closely match the workload requirements. Intel Rack Scale Design (RSD) takes us closer to that vision, implementing the DMTF Redfish API and extending upon it. The Plasma project in OpenStack has been created to integrate Rack Scale Design with Nova and Ironic to dynamically add and release resources as necessary to meet workload demands. Lenovo is developing new hardware management capabilities and pluggable interfaces to support RSD and Plasma. We will present the architecture of RSD and the design of Lenovo’s systems management software layer and APIs for OpenStack RSD plug-ins. 


* **Srihari Angaluri** *(Srihari Angaluri works at Lenovo Group, Ltd., as a technical architect in the Data Center Group. He leads development of solutions targeted at simplifying infrastructure deployment and management, plus implementing Cloud technologies leveraging open source tools.)*

* **ChaoFeng Zhang** *(ChaoFeng is responsible for enabling Rack Scale Design hardware in OpenStack and bare metal provisioning. He has expertise in OpenStack, open source engagement, and system management technologies. ChaoFeng joined Lenovo in 2014 from IBM with Lenovo’s purchase of the IBM x86 server business. He had been with the IBM Shanghai Lab since 2011.)*

* **Mrittika Ganguli** *(Mrittika is a Principal Engineer and Platform Software Architect in Cloud Platform Group, DCG – India and has 19 years of experience.  At Intel, Mrittika has worked on software systems design, development and architecture. Her work includes building the server system management software architecture for cloud and server hardware deployment for cloud in datacenters. She has been involved in Openstack projects within Intel since 2010. She was a co-creator and architect for a Openstack based product for SLO management Intel(R) SAA. She has 5 patents granted and 5 filed and multiple published papers. Workload charetcerization, orchestration in clouds and disaggregated Rack architectures are her current areas of work.)*

Building a media transcoding pipeline on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session presents an architecture on how to build a media transcoding pipeline on OpenStack.  The explosion of end-user devices (laptop, phone, set-top boxes, etc) is changing the media presentation landscape and requiring content providers to transcode a media to various formats, resolution, bitrate, etc. Media transcoding demands high CPU and large storage resources in general, but those themselves don’t necessarily provide effective solutions. In this session, we will share the reference architecture of deploying such workload and show how to utilize various OpenStack components to fulfil the media transcoding requirements. We will share our experiences, knowledge and best practices including how to configure OpenStack settings, such as nova (CPU, flavor, ephemeral disk), glance and swift. We will also present a performance benchmark results of running the transcoding tasks on different settings.


* **Dr Yih Leong Sun** *(Dr Sun accumulated more than 16 years of experience in software development and infrastructure deployment. He obtained PhD Computer Science (Multi-Cloud Infrastructure) in 2013. He spent the past 7 years on Multi-Cloud infrastructure development. He currently serves as a Senior Software Cloud Architect for Intel Open Source Technology Center. Prior to that, he was a Principal Software Engineer for a Fortune-100 Insurance Group, working for the next-generation Cloud platform project. He also led the engineering team of a few start-up companies in Singapore and Silicon Valley. His expertise is in Multi-Cloud orchestration and with a strong interest in building an Enterprise Multi-Cloud platform.)*

* **Jun Nakajima** *(Jun Nakajima is a Senior Principal Engineer leading open source virtualization and cloud projects, such as, KVM, Xen, and OpenStack at the Intel Open Source Technology Center. Jun has been working on various virtualization projects for almost a decade, and NFV is one of his ongoing projects. Jun presented a number of times at technical conferences, including KVM Forum, Xen Summit, LinuxCon and USENIX. He has over 20 years of experience with operating system internals and virtualization.)*

How to build high availability solution with OpenStack for your critical business.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

If you want to run critical bussness on OpenStack, what should you prepare before it ? The session will introduce the solution how to key the bussness high availibilty in openstack management datacenter to defend, flood, storm,fire,etc to keep bussness continuable.


* **Tao Bai** *(Over 12 years on IT software design and development. 3 years Cinder development and contribution.  Right now, working in Huawei Company as OpenStack Architect in the private cloud and public cloud domain. Responsible for Cinder, Manila development and an opensource software-defined storage controller , data protection in public cloud and private cloud domain.)*

Analyzing and Managing Performance Issues on Real-Time OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As we presented at the last OpenStack Summit in Austin, we shared how to build real-time cloud using OpenStack, proposing a reference architecture. And now it seems that more users and operators need to run low-latency or real-time applications (such as audio/video streaming, highly interactive systems, IoT, HPC, etc.) to meet their requirements in clouds.   This time we we share how to analyze and manage performance issues that users or operators can encounter, showing a framework on performance monitoring.  Since we are working on Real-time KVM as one of the projects of KVM enhancements for NFV at OPNFV, we share our know-how and experiences to root-cause performance or real-time issues on OpenStack. We use more common cases to make the presentation comprehensive and generic. Typical NFV workloads push the limits in all of the system resource areas: CPU, I/O, and memory, and our our know-how and experiences should be applicable to common cases.


* **Jun Nakajima** *(Jun Nakajima is a Senior Principal Engineer leading open source virtualization and cloud projects, such as, KVM, Xen, and OpenStack at the Intel Open Source Technology Center. Jun has been working on various virtualization projects for almost a decade, and NFV is one of his ongoing projects. Jun presented a number of times at technical conferences, including KVM Forum, Xen Summit, LinuxCon and USENIX. He has over 20 years of experience with operating system internals and virtualization.)*

* **Yunhong Jiang** *(Yunhong has been working on virtualization and cloud computing for a long time. He began working on virtualization since 2004. On 2012~2015, he worked on openstack Nova project. Now he is focus on OPNFV KVM4NFV project.)*

What's new for Windows in OpenStack Newton
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Windows support in OpenStack continues to improve with each release, with lots of new feature in Nova (Hyper-V), Neutron (including Open vSwitch and the new Windows Server 2016 network stack), Cinder, Manila, Designate, Cloudbase-Init and much more.   The new Windows Server 2016 offers also a lot of new features that set Hyper-V as a front runner for enterprise workloads with OpenStack as its perfect match. During the session we will talk about the best strategies to include Windows as a first class citizen in an OpenStack cloud. We will also demo a lot of new features, from Shielded VMs to RDS/VDI to Nano Server, including both Windows guest and Windows host scenarios.  


* **Alessandro Pilotti** *(Alessandro Pilotti is the CEO of Cloudbase Solutions, a company focused on cloud computing interoperability and the main contributor of all the OpenStack Windows and Hyper-V components in Nova, Neutron, Cinder, Ceilometer and Heat since the Folsom release. Alessandro lives in Timisoara, Romania. When not hacking or travelling, he is flying with his paraglider into old fashioned clouds.  )*

* **Peter Pouliot** *(I help to maintain OpenStack integration with Microsoft's Virtualization platform Hyper-V. My tenure at Microsoft began in March 2012 with a task of organizing community members to restore and maintain Hyper-V intgration within OpenStack.  Our team was successful in restoring the Hyper-V functionality to OpenStack in time for the Folsom release and the Continouous Integration Infrastructure running for the Juno release. I currently act as the OpenStack subject matter expert within Microsoft as well as the evangelist for OpenStack awareness and adoption of OpenStack Windows platforms. Prior to Microsoft I worked for Novell in the Joint Interoperabilty Lab with Microsoft.  There our team focused on testing and validating Linux workloads on Hyper-V and Windows workloads on Xen and KVM.  In April 2011 I successfully deployed the first OpenStack Cloud using Hyper-V and began my evangelism for Hyper-V within the OpenStack community. Additional experiance includes linux high avialability, network and datacenter infrastructure and security.    )*

What not to do with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It has been 6 years since the first OpenStack release and it is now widely known what use cases it fits and what potential it brings to your organization. Less known and talked about is what not to do with it.  Considering the complexity that OpenStack has gained, sometimes it’s not clear if adopting it in your own workflow is the best call. In fact, it’s not as simple as determining if OpenStack can work or not for you, but you also have to consider how you should deploy OpenStack to fulfill your needs. We will leverage real world use cases to explain when the effort required to migrate to OpenStack is worth it and when it is best to stick with a more traditional architecture. More often than not critical points may not be visible at first and, since these are the ones that define success or failure in a deployment, we will give a few tips on how to recognize them in the future.


* **Juan Manuel Santos** *(I am both an avid developer and a sysadmin, eternally not able to decide between the two. Whenever I've been hacking too much at the OS level, I yearn to code a bit, and viceversa. My OS of choice is Gentoo Linux, and my programming language is, of course, Python. I am always looking for ways to use the latter to ease my daily work with the former. From time to time, I also teach Red Hat OpenStack courses.)*

* **Victoria Martinez de la Cruz** *(Software engineer at Red Hat, FOSS passionate and tech in general enthusiast. Zaqar and Trove core member. Outreachy and Google Summer of Code coordinator. Eager to learn about new technologies. to contribute to different open-source projects and to get new people involved with open-source philosophy.)*

Keep up with the pace: How to smoothly adapt API changes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack have been evoluted for 14 releases, the API of each services have been changed more or less, some of them bumped from v1 to v2, some of them adopted the microversion mechanism, some of them deprecated or planning to deprecate extension machanisms; What can we learn from the changes? How can we quickly keep up with the changes as cloud users and downstream vendors? This topic will discuss the API change history of Nova, Cinder and Neutron, ilustrate and compare the way APIs evoluted in these projects, what kind of problem did our customers meet and what did we try to quickly adapt to the changes in our downstream development, this session will also try to compare the pros and cons for each kind of changes in the cloud users' and downstream vendors' point of view;


* **Zhenyu Zheng** *(Zhenyu Zheng joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Nova, Searchlight.)*

* **Xiyuan Wang** *(Xiyuan Wang joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Zaqar, Glance and Cinder. He is one of the zaqar core members.)*

* **zhao bo** *(Work in Huawei for OpenStack community in 2015. Focus on Neutron and its subprojects.)*

OpenStack Enablement on AArch64
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As ARM advances in server field and hardware is widely available, software ismore important than ever for success. To ensure adoption, all workloads must beprofiled and improved for ARM servers.OpenStack as the state of art cloud solution is, in our view, essential for thedata center. The Linaro SDI team is focusing on OpenStack enablement, profilingand upstreaming patches for AArch64, trying to make OpenStack as architectureindependent as possible. This presentation is about the current status and planfor making the OpenStack experience on AArch64 awesome, with emphasis on thechanges required for computing, networking and storage. We will also describein detail the ARM server development environment and related upstream patches.Please, let us know if you want to help!


* **Yibo Cai** *(I joined ARM workload team at March-2016. My major job is to enable and profile OpenStack on AArch64. Though new to OpenStack, I'm finding it's an interesting and challenging field. My first task is to enable Ironic on AArch64. Now I'm working on Neutron and OpenDaylight. Before join ARM, I worked in four companies of Telecom, consumer electronics, industrial instrumentation and automotive electronics fields.)*

* **Jack He** *(I work for ARM. I am also an Linaro member engineer. I am mostly focused on making OpenStack work smoothly for AArch64.)*

Building a Production Grade Cloud from Scratch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Do you have a bunch of hardware laying around and want to transform that into a cloud?  Not just a prototype cloud, but one where you can deliver a reliable SLA, high quality components, and top tier performance?This session will outline our experiences building production grade clouds using just the open-source projects within the OpenStack ecosystem.  We'll share our challenges and successes of building these high grade, heterogenous clouds.  We will also distribute our cloud reference architecture built using the OpenPOWER which documents this repeatable pattern for setting up cloud infrastructures.


* **Chhavi Agarwal** *(Chhavi Agarwal is a Advisory Software Engineer at IBM, having over 11 years of experience. Over the last 5 years actively involved in systems related to Cloud, Virtualization and Systems Management.  She has been actively involved in the community for the nova-powervm drivers and cinder community. )*

* **Kyle Henderson** *(Kyle Henderson is a Senior Software Engineer at IBM with over 25 years of software development experience.  He has led and contributed to many development projects including POSIX compliant file systems, an LDAP server / client, web services and grid computing toolkits. For about the last ten years he's been involved in projects related to virtualization.  They include building tools to simplify virtualization, constructing Linux based appliances to manage virtualization and most recently focusing on Nova compute drivers for Power systems. When not working, he enjoys flying adventures and currently holds a commercial pilot license.)*

* **Drew Thorstensen** *(Drew has been working on OpenStack related projects for multiple years, working on deploying, managing and developing cloud technologies for POWER systems.  Recently he has actively been developing the PowerVM Hypervisor drivers with enablement spanning across Nova, Neutron and Ceilometer.)*

OpenStack: Shifting from Hardware to Software Reliability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Gartner analyzed data centers for a period of 10 years and found that 47% of all problems were caused by cloud services outages, with a duration ranging between 40 minutes and five days. Ponemon Institute found that on average outages cost US$ 690.204.The increasing use of commodity hardware to build data centers will negatively contribute to the reliability of existing cloud computing platforms.Thus, the development of new techniques and methods to evaluate and increase the reliability of cloud platforms from a software perspective is fundamental.The first part of this presentation will present the mechanisms that pioneers, such as Amazon, Google, and Netflix, have already developed to increase the reliability of their cloud platforms.The second part of the presentation will describe how T-Systems and Huawei are exploring the use of fault-injection mechanisms to effectively increase the reliability of the Open Telekom Cloud platform from Deutsche Telekom, an OpenStack-based platform.


* **Jorge Cardoso** *(Jorge Cardoso is currently Chief Architect for Cloud Operations and Analytics at Huawei Technologies. He is responsible to define the strategy for cloud management for the next 5 years. A core of this work consists in proposing key technical solutions (e.g., IT Operations Analytics, Cloud/Client Computing, Business Process as a Service, Cloud Migration Tools, IT Operations Analytics, Heuristic Automation, and IT Service Orchestration) for the effective and advanced management of the Deutsche Telekom Public Cloud in Germany and the Huawei Enterprise Cloud in China.)*

* **Goetz Reinhaeckel** *(Since 2015 Heading Open Telekom Cloud product development, T-Systems 2012-2015 Heading TSI Cloud engineering & Systems Management, T-Systems 2010 -2012 Vice President Service Delivery Management, T-Systems 2006-2010 Head of Service Delivery Management, T-Systems 2001-2005 Head of Middleware Operations, T-Systems 2000 Trainee debis Systemshaus 1999 PostDoc, CSIRO, Perth, Australia 1997-1999 PhD, (Dr. rer. nat.) University of Munich and Deutsches Zentrum für Luft- und Raumfahrt e.V. (DLR), Munich 1991–1997 Studies of Geology, University of Munich)*

* **Kurt Garloff** *(I grew up in Germany where I graduated in Physics at University of Dortmund. I moved to Eindhoven (The Netherlands) to do postgrad research on plasma physics.I had developed an interest in computers and in particular in the Open Source and Linux movements in parallel and had contributed some code successfully to the Linux kernel when the community was still small. I also succeeded contributing little pieces to a number of other projects (amongst which glibc and gcc).In the end the computer side won over physics and I ended up working for SUSE Linux AG (later part of Novell Inc) as a freelancer and quickly as employee.  I worked as kernel engineer but also took some responsibility in security projects. I ended up running SUSE Labs, the research department hosting the prominent open source kernel, toolchain (compiler ...) and X11 engineers that we managed to hire.Subsequently, I had a number of technical, people and business leadership roles (Head Architect, acting VP Engineering, VP Product Management, VP Business Development, VP Partner Engineering) and I'm grateful to Novell for sending me to the HBS Program for Leadship Development to enhance my business skills before taking over business management functions.The acquisition of Novell by Attachmate ended my career with SUSE and the next step was being part of the BU Cloud Services in Deutsche Telekom's P&I which was had a lot of the startup spirit I was looking for.. In my VP Cloud Technology function I headed the unit that developed the Consumer Cloud Storage platform (DLS/Mediencenter) and the OpenStack based hosting infrastructure for hosting the software partners apps in DT's TelekomCloud BusinessMarketplace. The Telekom project has been cmpleted and I currently work as freelancer, helping IT companies to build technology and business strategy strategy and to build great engineering capabilities.I last supported Huawei's European IT R&D department to be successful with OpenStack.When I don't work on computers, I spend my time with my great wife and two wonderful kids.)*

Dockerizing the Hard Services: Neutron & Nova
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We'll talk about the benefits and pitfalls involved in successfully running complex services like Neutron and Nova inside of Docker containers. Topics will include: What magic incantations are needed to run these services at all? How to prevent HA router failover on service restarts. How to prevent network namespaces from breaking everything. Lessons learned in how to manage configuration changes and deployments. Bonus: If time allows, we'll also discuss what is needed in order to run Cinder in Docker containers.


* **Clayton O'Neill** *(Clayton is a principal software engineer at Time Warner Cable, where he's working on a team developing, configuring and deploying a large private OpenStack cloud. He is primarily responsible for CI/CD, automation and MySQL/Galera on the team, but has deep background on both operations and development teams.)*

A Nova Scheduler for Public Cloud Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the advent of Nova Cells v2, the need for high throughput VM scheduling is becoming increasingly critical to the operation of OpenStack at public cloud scale.  For Cells v2, in particular, the requirement to use a global scheduler means that the scheduler must be able to manage more hypervisors and, potentially, many more VMs.  As with all things cloud, horizontal scaling seems like a natural solution.  However, in the case of the Caching Scheduler, for instance, more schedulers means more resource contention which often results in the infamous "No Valid Host" error.We present performance results for multiple scheduler implementations in an attempt to identify the best one to resolve the resource contention problems, and subsequent throughput deficiencies, encountered in distributed scheduling. One such implementation makes novel use of Redis as a remote, in-memory DB in place of the usual Nova DB.


* **Ryan Rossiter** *(Ryan Rossiter has been with IBM for 2 years, joining after graduating from South Dakota State University. He started working on automation and testing for IBM Cloud Manager with OpenStack. From there, he went on to work upstream in Nova and Magnum. Ryan is now working on IBM's public cloud, specifically on the development and deployment of Nova and the VM service within IBM BlueMix.)*

* **Chris Kirkland** *(I'm an Engineer on the Cloud Foundation Services Performance Team at IBM.  I spend most of my time working on Nova/Heat but have worked on IBM BlueMix web services as well.  In addition to performance, I'm very interested in Development and Automation.  I am primarily a Python developer but working on becoming more proficient in Golang. Before joining IBM, I received an MS in Applied Mathematics (conc. Computation Mathematics) from North Carolina State University.  In my spare time, I assistant direct a Barbershop chorus in Austin, TX.)*

Building secure-networks across cloud boundaries
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You want agility, flexibility, and security for your cloud. That means utilizing all the cloud environments in your disposal to run applications, designing your IT at ANY SCALE while securing your network end-to-end.      With this secure elastic cloud, your workloads move between private and public clouds dynamically while utilizing the best compute vehicle available to run a particular workload, requiring Cloud Connect technology to connect any compute environments anywhere.    Not to mention you must isolate tenants running on your shared IT infrastructure and protect workloads across cloud boundaries.     Juniper has the answer.  With this demo, we will showcase: 1: Secure: Tenant isolation & protect workloads 2: Hybrid Cloud: Build your IT as service at any scale   3: Freedom of Choice: Run applications on different compute environments.


* **Mani Subramanian** *(Subramanian, Manikandan (Mani))*

* **Adam Wayne** *(Adam Wayne)*

The Private Cloud Service Provider Blueprint
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building a Private Cloud business is hard! Don't be fooled. OpenStack is only one piece of the cloud provider puzzle. There are business considerations and technical components required such orchestrators, billing systems, and application catalogs that must all be considered to do it right. If you are faced with the daunting challenge of planning your business this is the session for you. Canonical has created a blueprint for private cloud service providers that can be followed which describes what it takes to move forward with your business plans. Attendees will follow along as we build out a fictional private cloud service provider using our service provider blueprint developed by the Consulting Architecture team. You will gain an understanding of not only the technical aspects of the service provider blueprint but also gain an understanding of the challenges that cloud providers need to solve before realizing their full potential.     


* **Brent Clements** *(Been working with OpenStack since Diablo and absolutely love building solutions using the OpenStack Framework.  I've done a little bit of everything with OpenStack from deploying, architecting, & developing code all the way to selling OpenStack Solutions to Service Providers and Enterprises. Currently working as the Practice Lead for the Consulting Architect team at Canonical. We help customers focus on their business rather than the technical complexities of software. We do this by providing open source software that allows for model-driven operations of "big software".   )*

Rolling Upgrades - Performance between OpenStack Deployed in VMs and Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation compares and evaluates the numerical rolling upgrades performance between OpenStack deployed in VMs and containers. Many operators are considering moving from VM-deployed OpenStack to container-deployed OpenStack partially because of better rolling upgrade performance provided by containers. However, no numerical test results are ever presented to show this performance improvements gained by containers during rolling upgrades. Thus, we want cover it in this presentation.


* **Lujin Luo** *(Lujin joined OpenStack development in 2015. Now she is working on developing rolling upgrade features across many projects. )*

Why should I consider a converged architecture for my OpenStack cloud?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The typical approach to architecting an OpenStack cloud deployment separates the deployment of the control plane of the cloud onto dedicated server infrastructure, providing physical separation from storage and compute services providing resources to tenants of the cloud. This approach has some limitations in terms of flexibility, fault tolerance and scalability. The Ubuntu OpenStack converged cloud architecture treats the control plane of the cloud as a discrete set of services. By spreading those services as far and wide as possible (including on storage and compute servers), we can achieve an high level of resilience, improve fault tolerance and increase the scalability of the individual components of the control plane an OpenStack cloud with no ‘special place’ for control plane services.


* **James Page** *(James as been involved in Open Source software since 2000, evangelising and delivering the use of Free and Open Source technologies in a major UK bank. In 2010, James discovered Ubuntu and became involved in both the development of Ubuntu and shortly afterwards OpenStack. James is part of the team responsible for delivering and supporting OpenStack as part of every Ubuntu release and for the Juju Charms for OpenStack, the best way for deploying and managing OpenStack deployments on Ubuntu at any scale.)*

Deploying and Operating Trove in Production: Reference Architectures and considerations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Trove allows users to provision and manage the lifecycle of over a dozen relational and NoSQL databases. This talk provides a detailed description of the OpenStack Trove architecture, and common reference architectures for deploying Trove. Trove's architecture is very similar to other OpenStack services in that it has a number of control plane components (API, Task Manager, Conductor), but is different from other services in that it has a guest agent that runs in the guest instance; an instance that runs in tenant context. Proper configuration is therefore crucial to stable and secure operation of Trove. This talk begins with a detailed description of the architecture of Trove, the control plane components and the components that run in the guest instances. It describes the various steps that typically must be performed in installing Trove, and how the various components interact with each other.


* **Amrith Kumar** *(Amrith Kumar is an active technical contributor to the OpenStack project, and a member of the Trove core review team. He is also a member of the OpenStack Foundation Job Analysis Task Force and an author of the book on OpenStack Trove. He is the author of the book on OpenStack Trove (published by Apress, http://www.apress.com/9781484212226). He brings more than two decades of experience delivering industry-leading products for companies specializing in enterprise storage applications, fault tolerant high performance systems and massively parallel databases to Tesora, which he co-founded. Earlier, he served as vice president of technology and product management at Dataupia, maker of the Satori Data Warehousing platform , and Sepaton’s director and general manager where he was responsible for the development of the core virtual tape library product. As a director of product development at Netezza, he managed end-to-end product delivery for all customers and prospects. Amrith studied mathematics at the University of Madras (India) and management at the Indian Institute of Management. )*

* **Thanukrishnamurthy Madhusudhanan** *(Thanu works on OpenStack on Oracle Solaris focussing mainly on Trove and Operating System features for OpenStack based cloud infrastructure. Thanu has a MS in Computer science, from Northwestern Polytechnic University, Fremont CA. Post Graduate Diploma in Software Technology (PGDST) from National Center for Software Technology (NCST). BS in Physics from University of Madras, India.15 years of experience in Unix, concentrating mostly on HP-UX, Linux and Solaris. Most of the work are on Networking, Filesystems (NFS, OGFS) Storage domains (HP-UX Mass Storage Stack), and Data Center Automation.)*

A Telco's perspective: interconnect multi-DC Clouds using OpenStack and SDN Über-controller
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation describes a Telecommunication Service Provider solution approach for Multi-Data Center and Multi-Region-OpenStack setup by using the concept of an SDN Uber-controller. Telco cloud is characterized by a number of distributed Data Centers operated as independent OpenStack installations. Aspects of distributed workloads and high availability, management of distributed networking Neutron resources, multi-DC service and multi-DC service chaining will be explained. Also, Multi-Region setup in the context of multi-region keystone support and the possible mechanism like MySQL replication or LDAP over multiple Data Centers will be described.  The Presentation includes a real live demo where a concept of SDN Uber-controller will be shown. Monitoring of distributed Neutron networking resources via the SDN-Uber-controller will be demonstrated.


* **Nachi Ueno** *(None)*

* **Yuriy Babenko** *(Yuriy works as a network architect for Deutsche Telekom focusing on data center design, networking and automation. )*

Will it Blend? The Joint OpenStack Kubernetes Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Will they blend? There's only one way to find out! Join experience DevOps mix-master, Rob Hirschfeld, in this fun and informative exploration. Since the OpenStack on Kubernetes keynote in Austin, there are been many discussions about if and how to deliver a Joint OpenStack Kubernetes Environment. Specifically, using Kubernetes as an underlay. In this presentation, we'll explore the potential benefits and downsides of this configuration. Then, assuming it's a good idea, we'll give into the real architectural and operational work needed to implement a robust OpenStack cloud using Kubernetes. We'll discuss the pros and cons of including the Nova compute nodes in K8s management. Finally, we'll outline upstream work that's needed to turn OpenStack into a cloud native application.


* **Rob Hirschfeld** *(Rob Hirschfeld has been involved in OpenStack since the earliest days with a focus on ops and building the infrastructure that powers cloud and storage.  He's also co-Chair of the Kubernetes Cluster Ops SIG and a four term OpenStack board member. The RackN team has deep knowledge of Kubernetes (we've been deploying it on clouds and metal), OpenStack (we created the Crowbar project) and cloud native architecture (we migrated Digital Rebar to be micro-services). Basically, Rob has deep ops knowledge of both platforms AND experience with cloud native migrations. He's also a regular speaker at OpenStack Summits about items including SDN, interop and running Kubernetes. You can read more about my thoughts and positions regarding OpenStack and Cloud on my blog: http://RobHirschfeld.com.)*

What are you waiting for? Using SDX + OpenStack for your private cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It would be a waste to use OpenStack only for managing resources because OpenStack can serve as the heart of whole your system management. Both SDN and SDS provide incredibly powerful architecture, especially when combined. You can completely integrate your network, storage and computing resources by using SDN/SDS with OpenStack. Now is the time to start using what will certainly be new standard. More specifically, we are using Big Cloud Fabric and Ceph as SDN/SDS in our production environment. Big Cloud Fabric is an especially unique SDN controller with its flexibility to support underlay networks. All combined, this setup allows us to manage our private cloud more efficiently than ever before. This session will explain how we integrate SDX with OpenStack and the potential benefits. It will hopefully provide some valuable hints for increasing the efficiency of your own private cloud.


* **atsushi ono** *(Atsushi Ono is an IT infrastructure strategic leader with extensive experience working on optimizing computing at DeNA, one of the largest internet companies in Japan. He is currently tackling the significant task of making the company’s huge on-site datacenter more flexible and efficient, focusing particularly on the use of network virtualization.)*

* **Wataru Nakamae** *(Currently located in Tokyo as Systems Engineer at Big Switch Networks, responsible for the Japanese market. Having worked previously at a large Japanese systems integrator as a subject matter expert in data center networks and software defined networking, I have been focusing on technologies to integrate the network with Openstack and other orchestration systems since joining Big Switch Networks.  )*

Service Continuity with OpenStack Smaug
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the main concerns of online businesses is ensuring service continuity in case of a major outage.  Most of the protections provided today deal with data replication from one site to the other, but is it enough? Most production environments have considerable amount of configuration, scripts, security settings and metadata, which accumulates. This metadata is not protected in case of a site disaster. OpenStack Smaug protects all the data which comprises a working environment.  It orchestrates protection plans and calls protection providers for each of the various protectable items in your environment, such as images, VMs, network topology, shared folders, and, yes, also volumes. Smaug APIs enable DR tools to focus on the orchestration of the DRP, instead of integrating with the many possible backup and protection tools and solutions. In this session, we will give a short introduction to Smaug project and dive into the Service Continuity use case in more details.


* **Ayal Baron** *(Ayal Baron is Cloud computing CTO in Huawei's ITPL and brings nearly 20 years of software development experience in the fields of virtualization, storage and networking to his role.Prior to joining Huawei, he was Senior Engineering manager in Redhat leading cloud storage and before that Co-Founder and CTO of RockeTier. Ayal lives in Isreal with his wife and two sons and studied Cognitive Sciences Life Sciences at The Hebrew University.)*

Autoscale your PaaS with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Container management platforms like OpenShift bring a new level of scalability and flexibility to application development teams. OpenShift provides auto-scaling and elasticity to the containerized applications running on the platform by leveraging Docker and Kubernetes natively. However, what happens when the application demand exceeds the capacity of the platform itself? OpenShift does not currently auto-scale the underlying platform. But OpenStack offers a flexible, capable Infrastructure-as-a-Service (IaaS) offering to complement your Platform-as-a-Service (PaaS). Attendees will see a demonstration of the use of OpenStack as an IaaS to automatically scale OpenShift nodes based on application demand running on top of OpenShift PaaS. They should walk away with a fundamental understanding of how to use this type of solution in their own environments.


* **Kevin Jones** *(Kevin Jones is a Cloud Architect for Red Hat. His mission is to bring OpenStack into public service for Government, Research, and Educational entities. Kevin spends his time working with customers to define use cases around cloud and devops. Kevin has significant experience working with research and scientific computing entities to determine best fit for OpenStack and other technologies. Kevin comes to Red Hat from NASA Langley Research Center where he was the Chief Technologist for IT. In his role at NASA, he helped evangelize the use of hybrid cloud computing. Kevin came up in his career as a developer first and via curiosity, migrated to a holistic approach focused on utilizing technology to deliver business results. Kevin has been in the IT industry in Public Sector space since 2001. He came up as a developer and evolved into a full bore cloud solution architect. He carries Red Hat certification in OpenStack and Solution Architect certification in Amazon Web Services.)*

* **Jamie Duncan** *(Jamie has been at Red Hat for about 5 years, focusing on the problems unique to Public Sector customers. Prior to Red Hat, Jamie worked in the ‘big web’ world and spent some time at a bioinformatics startup.   At Red Hat, Jamie focuses on cloud-enabling technologies like OpenStack, docker, kubernetes and OpenShift among others. With most of these technologies, he has been involved with them since their infancy.   In his spare time, Jamie lives on a small farm west of Richmond, VA with dogs, cats, frogs, chickens, deer and a very understanding wife.)*

The Road to Production Grade (lessons learned from our experience with Dragonflow)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Dragonflow is a young project, barely two years old.  We have been working hard at making it a good candidate for users that need a networking implementation that can scale to 10,000 hosts, and allow hosts with 10Gbps NICs to be fully utilized, even when running an overlay network with encap/decap.In this session we will share some of our experience and lessons learned while getting Dragonflow ready to handle such loads in Huawei's Enterprise Cloud:* Database Consistency in OpenStack Components* Publish Subscribe: Broker vs. ad-hoc vs. mesh (Peer-2-Peer)* Performance Maximisation and Testing Results


* **Omer Anson** *(Omer is currently a software developer for Huawei, and a core contributor for Dragonflow in OpenStack. He has 9 years of professional programming experience, with over 5 years expertise in Linux systems and networking. Omer has a B.Sc in physics, and is working towards his M.Sc. in Computer Science.)*

How to Configure a Running OpenStack Trove Environment to Ensure High Availability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack users are starting to explore how to configure a running Trove environment to ensure high availability.  It is important to configure OpenStack and Trove in such a way that if a component fails there are enough alternatives to continue supporting the function. This talk will explore: Strategies for deploying OpenStack Trove in a highly available manner Approaches for configuring different monitoring agents when running databases Example user stories detailing a high-availability, production Trove environment You will learn how to quickly deploy Trove and offer a self-service database provisioning system for a dozen commonly used databases and configure a running Trove environment that will ensure high availability.  


* **Sriram Kalyanasundaram** *(Director of Implementation @ Tesora. )*

The Key Components of Adopting CI The OpenStack Way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack’s Continuous Integration (CI) structure is an invaluable tool for stabilizing builds and code repositories. Yet, some may feel that this implementation of CI is too cumbersome to adopt. This session will prove how easy it can be to adopt, configure and migrate existing projects. We will also discuss how a software team can benefit from a CI infrastructure that fits with the OpenStack way, how to stabilize it and which tools we use to do so: Ansible, Jenkins Job Builder, and our internally-developed tool, PrivateStack.


* **Wajdi Al-Hawari** *(Wajdi is a Full Stack Developer for Internap working out of Montreal. Passionate about test driven development and continuous integration, he is mainly responsible for the architecture and development of server and network automation solutions for Internap's Baremetal public cloud solution. When Wajdi isn't developing solutions for the cloud, he is usually a human jungle gym for his two children, enjoys running and dabbling with his guitar. )*

* **Mathieu Mitchell** *(Mathieu is a Lead developer for Internap based in Montreal, Quebec Canad and an active member of Ironic and IPA projects.  He started is career at Internap as a System Administrator and joined the engineering departement a few yers ago where he became a and key member of the developpement departement of Internap.   Involved in low level networking up to high level micro architecture services, Mathieu is passionate about open source and collaborative development.)*

Ceilometer to Almanach: Scalability, accuracy and efficiency in measuring and billing resources
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceilometer is the "all you-can-eat buffet" of event notifications in OpenStack; so, it naturally comes with its own set of challenges. However, many businesses need the ability to pinpoint to a specific subset of those events and to retrieve them in an efficient and scalable manner. Enter Almanach, our solution to this very problem. In this presentation, its main contributors will explain how it leverages the specialized nature of both cloud and bare-metal event workloads to filter only those events who are relevant to a specific process (e.g. billing, platform health checks etc.)


* **Marc Aubry** *(When Marc isn’t climbing walls (literally), he can be found designing and developing Almanach for Internap’s Montreal office. Almanach is an event-based system used as a data source for OpenStack billing. He solved race conditions within a multiple cell deployment, despite the headaches. This coding monkey and caffeine junkie speaks Python fluently, and flawlessly supports the OpenStack deployment at Internap. During his spare time he can be found impressing the crowd at bouldering gyms, swing dance events or near any PokeStops. This attaching individual can be easily identified by his crocodile dundee hat.)*

* **Frederic Guillot** *(Frederic works on the OpenStack billing platform of Internap. During his spare time, he maintains his own open source projects and try to travel everywhere around the world.)*

Message Routing: a next-generation alternative to RabbitMQ
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A broker can only scale so far.  The limitations of a broker-based messaging service are becoming apparent as Openstack deployments are pushed to ever higher scales and wider distributions.  An alternative to the broker-based message bus is needed. This presentation will introduce that alternative.  With the Newton release, the Oslo.Messaging library now includes support for a highly scalable, distributed, and fault tolerant brokerless message bus based on message routing rather than queueing. With this new technology one can achieve high availability through redundancy rather than clustering.  This message bus is optimized for operation across geographically distant sites, allowing for cloud distribution not possible with the single or federated broker approach.


* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*

* **Andrew Smith** *(Principal Software Engineer at Red Hat, Inc. - Enterprise Messaging)*

"Do I need a Cloud Management Platform to manage OpenStack? "
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We often find that day two operations in OpenStack can be very painful, and a Cloud Management Platform (CMP) can help with this. A CMP can easily manage monitoring, insights, security or compliance, as well as basic chargeback. During this session we will do a live demonstration to illustrate the benefits of a CMP.


* **Victor Estival** *(Victor joined Open Source communities a long time ago, and he has been working several years on traditional Unix systems as a Consultant and as an Architect, working with IBM Power Servers and AIX for a long long time. In 2010 he changed his area to Cloud environments and he has been collaborating in the design and architecture on several Private and Public clouds working with a System Integrator, and got involved in different projects, one of them was OpenStack. Since then, he tried to integrate OpenStack with the existing technologies as well to understand how OpenStack fits in the current Customer's ecosystem as an Architect In 2014 he joined Canonical to expand the architecture of their products and add his expertise to the business, as well as complex architecture's integration experiences By the end of 2015 he left Canonical but he is still interested on OpenStack and following the community very closely)*

When not to share - a Global Cloud Model
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk, we take a fundamental approach (with diagrams/pictures) to designing a Global Cloud for a customer. We discuss how to use a ‘shared-nothing’ approach, coupled with an orchestration layer that ties it all together. We discuss the reasons why this approach is best and why this discussion should happen before anything else in the move to Cloud. Our intent is to allow listeners to learn from our mistakes and successes, and start the Cloud journey out on the right foot. This is a 101-level talk, geared toward the IT business decicion makers (CxO, VP, Director, Manager), who need to the best way to approach Cloud before they spend resources on the effort.


* **Ernest de Leon** *(Ernest de Leon is Director of Services Engineering - North America for Mirantis, and a recovering Cloud Solutions Architect. Ernest is also an Amazon AWS Certified Solutions Architect, with 8 years of experience in the Cloud space (building and operating private clouds as well as designing distributed and highly available applications in the cloud). Ernest primarily focuses on large scale cloud deployments in F500 and Telco spaces as well as the applications that span these clouds. Prior to Mirantis Ernest was at Eucalyptus, and before that, did VMware Professional Services.)*

* **Craig Anderson** *(Craig Anderson (canderson@mirantis.com) works at Mirantis, Inc. as an OpenStack solutions architect, where he has lead the design of large scale, distributed, highly customized OpenStack private clouds for fortune 20 customers.)*

Vanilla or distributions: How do they differentiate?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

If it comes to OpenStack there is always the question: vanilla or a distribution. You have the agony of choice, it will highly depend on your usecase and organization. This presentation will not only highlight differences and similarities between these choices but also between the major OpenStack distributions. We will take a look behind the curtain of the OpenStack products. What should you know about the offerings? Is there anything you may should evaluate before you choose a solution? There is more to take a look at than only the OpenStack product itself if you include also e.g. KVM and Ceph. What about the base distributions and support? This talk will cover besides Vanilla also RedHat, SUSE, Ubuntu/Canonical, and Mirantis OpenStack.


* **Danny Al-Gaaf** *(Danny Al-Gaaf is a Senior Cloud Technologist working for Deutsche Telekom on building NFV clouds. As an Ceph upstream developer he is also a driver for using Ceph as a distributed open source storage back-end for OpenStack at Deutsche Telekom. For the last 10 years his professional focus has been on Linux and open source software. He works actively in several upstream communities.)*

Kubernetes vs Docker Swarm Mode for OpenStack Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The container and container orchestration are some of the most attracting technologies for software delivery, maintenance, and upgrade. The technologies can get rid of some pain points that operators hit in their operations (e.g. deploy, upgrade and failover) and make it simple to manage systems. OpenStack is also one of the software products, so cloud operators would like to get the benefit using containers to deploy OpenStack. However, there are several options for container technology and also for container orchestration technology. That makes the operators harder to choose which they should use. This talk presents a comparison between two major container orchestration technologies, Kubernetes and Docker Swarm Mode, for OpenStack deployment. This shows you Pros/Cons of both orchestrators for the deploying purpose, as well as what are new pain points of operations on containerized OpenStack.


* **Mahito Ogura** *(Mahito Ogura is a Engineer at NTT Communications, working on Cloud technology R&D team.  He joined the team in late 2014 and since has been focused on to improve OpenStack in his company's cloud, to R&D OpenStack and to educate the cloud engineer.  Mahito has experience in distributed system development.  In the past 5.5 years he has been working for NTT Comware, defining and developing IaaS, NoSQL, configuration tools, KVS as a service, DBaaS(similar to Trove) and Hadoop as a Service (similar to Sahara) . He started contributing to OpenStack from Kilo release. He is actively contributing to DevStack.)*

* **Hiroki Ito** *(Hiroki Ito is a software enginer in NTT. He is now working as a operator of private cloud for development environment in NTT.)*

* **Takeaki Matsumoto** *(Takeaki is software engineer at NTT Communications, working on Cloud technology R&D team.He joined the team in 2015 and since has been focused on to R&D OpenStack.)*

Lots of VMware Deployed? Integrate with OpenStack Cinder, Nova, Glance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There's a lot of VMware out there and getting it to work with OpenStack isn't all that much of a heavy lifting project. There seems to be quite a few who would like to do this and either don't know how to or don't know where to look to find answers. There are quite a few things to learn about the drivers that help enable VMware to work with Cinder, Nova, and Glance. Lets go through a deep dive on each and show how you can easily get OpenStack working with VMware in your enterprise. You will learn the requirements for each driver and the configuration options that go along with it. We will then show demonstrations of each driver so you can see it in action. Come and see for yourself and start utilizing your vmware infrastructure with OpenStack.


* **Cameron Seader** *(Cameron is currently a Sr. Data Center Strategist with an emphasis on Enterprise Cloud Computing environments; has a diverse background that includes technical sales, solutions architecture, consulting, and engineering. With over a decade of experience at companies such as Hewlett Packard, Micron, Interland (now Web.com) and Idaho Power, he excels in specific areas of data center design, specializing in system solutions on mainframes to high performance clusters. Cameron has also authored and published documentation and guides for several leading products and emerging technology concepts. As a Certified Linux Engineer he is a trusted adviser to SUSE's most strategic customers.)*

* **Simon Briggs** *(Having nearly 20 years experience in the IT industry after starting out as a junior Unix system admin's and then into software support. Initially focused on Windows and Unix/Linux systems management and ITSM. Though, as I enjoy presenting and meeting people the lions share of my career has been in Pre-Sales roles, this background then affording me the opportunity to join SUSE over 5 years ago.  Working as UK SUSE Solutions Architect and since January 1st, I have now happily become the full time EMEA Lead Solutions Architect for SUSE OpenStack Cloud (which I have been doing part time for nearly two years). I am a keen advocate of Open Source and standards for what this offers to society as a whole and I am frequently involved in Meetups on related subjects, having presented at the London, Netherlands and Oslo OpenStack Meetup's and more general Linux sessions.  I was also able to speak at the Openstack Benilux and Paris conferences in 2014. As a family man I also feel passionate that we need to help educate our next generations and have spoken on these topics at some UK universities, hoping to keep the momentum Open Source has achieved going. Away from technology I am a keen on sport, I still play (and coach a little) the wonderfully eccentric sport of Cricket for a local team and though my football playing days are long gone I content myself by being a long suffering Hull City FC fan and helping out for my sons under 7's side at the weekend. I try to stay fit to allow me to Snowboard as much as I can (though the family means this isn't as often as I would like) and have competed at a reasonable level in Swimming and Triathlons in the past.  Which has combined with my interest in charity support, where I arranged an international bike ride by my cricket team in 2014 to raise money for the Poppy Appeal in the UK. I have also volunteered to help larger events, being lucky enough to have been part of the "Games Makers" at the fantastic London 2012 Olympiad and a "Tour Maker" for the Grand Depart of La Tour when it was in Yorkshire, UK in 2014. When I'm not doing all that I love live music, attending festivals when I can.  I read often, particularly enjoying history having even been a voluntary archaeologist in Cypress when I was (much) younger.)*

Yo dawg I herd you like Containers, so we put OpenStack and Ceph in Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, you'll learn how OpenStack is evolving to integrate with the Linux, Docker, Kubernetes stack to provide the ideal infrastructure platform for modern containerized applications. You'll learn how you can modernize application delivery using container infrastructure while seamlessly using the authentication, network, and storage services provided by the underlying OpenStack cloud. We'll also discuss the ways that the Linux, Docker, Kubernetes stack is improving the deployment and management of the life cycle of the underlying infrastructure platforms themselves, focusing on OpenStack and Ceph.


* **Sean Cohen** *(Sean is a seasoned product manager bringing over 15 years of experience in senior engineering, global operations and services management roles in virtualization & cloud companies. He has international experience of storage virtualization products delivery & private clouds design for enterprise customers in various market segments in US, Europe & APAC. Sean is focused on cloud storage product management and strategy for Red Hat OpenStack Platform cloud offering. Sean is a member of the OpenStack Foundation, a frequent speaker at OpenStack summits and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/.)*

* **Federico   Lucifredi** *(The Ceph Storage PM at Red Hat, formerly the Ubuntu Server PM at Canonical, and the Linux "Systems Management Czar" at SUSE.)*

* **Sébastien Han** *(Sebastien Han currently works as a Principal Software Engineer, Storage Architect for Red Hat. He has been involved since 2011 with OpenStack and Ceph and has built a strong expertise around these two technologies. Curious and passionate, he loves working on bleeding edge technologies and always hope to find a suitable spot to integrate his two favorite technologies. In 2013, he started to work with containers and ultimately implemented containerised Docker Ceph services. On a daily basis, he loves to rotate between these three areas where he always makes sure to strengthen the integration between all of them. From time to time, he attends various summits and events where he evangelises these technologies and their usage. In addition, he always devotes a third part of his time to blogging. But this... is just the beginning :).)*

Improving Postgresql Concurrency with VCPU Overcommit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nowadays web-based Information System (WBIS) is commonly used in Indonesian Universities. The most important component for WBIS is Database. Relational database systems such as PostgreSQL is widely used by University with large student body, where high concurrency is likely to happen when all student access the information system at the same time. Comparison between bare metal server versus virtual machine performance will be presented, further discussion will focus on the improvement of Postgresql concurrency access  which have been achieved by overcommitting CPU within Openstack deployment at The University of Jember (UNEJ) Private Datacenter.


* **Sudarko Sudarko** *(I was born in Blitar, Indonesia in March 12 1969. I spent my early primary, secondary dan under graduate education in Indonesia, then I went to Sydney and Newcastle Australia to do my PhD in the area of Computational Chemistry. In 2003 I spent 6 months in Heidelberg Germany for short research on Molecular Dynamics. I spent most of my time now working as a chemistry lecturer at University of Jember, I am also IT manager at my University where I implement Openstack for managing my University computing resources.)*

Expanding and Deepening NTT DOCOMO's private cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the OpenStack Summit Tokyo, we've reported how DevOps works in our project ( http://bit.ly/2a8atnJ ) and what kind of operations are performed behind our private cloud system ( http://bit.ly/29Dw8FW ). Over the first stage of launching private cloud system, now we are aiming to migrate various systems included NTT DOCOMO's basic operation systems to our private cloud. To gather various systems into the one private cloud system enable us to reduce total cost of ownership. Today, We talk our strategy and technical knowledge to expand and deepen our private cloud for the migration. 


* **Jun Ishii** *(Jun Ishii is currently working as an operator and developer of a private cloud system based on OpenStack. He accumulates practical knowledge of the cloud architechture.)*

* **Hiromichi Ito** *(Hiromichi Ito co-founded Virtualtech Japan Inc. in 2006, and he is currently working on providing consultation service for the public and private cloud. He is one of the first members of proposing OpenStack Bare Metal Provisioning.)*

* **Kojiro Amano** *(Kojiro Amano is currently working as a security consultant of a private cloud system based on OpenStack. He accumulates practical knowledge about security, which is necessary for not only cloud operation, but also system architecture on the private cloud.)*

Deploy OpenStack Service Chaining using HOT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will give, - Overview about Service chaining and Heat (template-based orchestration mechanism) , - Brief introduction about Heat orchestration engine , Heat resource plugin , Heat orchestrate Templates(HOT), template parameters . - Examples of how you can deploy collections of resources -- networks, servers, storage, and more -- all from a single, parameterized template and demo to setup SFC network and compute node infrastructure using HOT templates


* **Mohankumar Navaneethan** *(Mohankumar has been working as Openstack Developer at Huawei Technologies and a member of the OpenStack community for the past 1 year . Actively working in Neutron , Networking-SFC , Horizon and Heat Openstack modules. Been in Software Domain for about 4 years. He holds a MTech in Information Technology from Anna University, Chennai.                                                                     )*

Direct Message Routing for Oslo.Messaging  -  Topology and Deployment Considerations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Direct messaging for RPC traffic patterns has emerged as a key requirement for very large scale and highly resilient OpenStack deployments. The use of message brokers for the RPC messaging pattern can be operationally complex due to the state management and clustering techniques required to realize a scalable and resilient control plane. With the OpenStack Newton release, the Oslo.Messaging library now includes support for an easy to setup, highly scalable, distributed and resilient brokerless message bus based on message routing rather than messaging queuing. This direct messaging support for RPC traffic patterns introduces an alternative architecture and with it new  topology and deployment considerations.


* **Andrew Smith** *(Principal Software Engineer at Red Hat, Inc. - Enterprise Messaging)*

* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*

‘Hyperconwhat?!’ - Hyper-Converged OpenStack and Ceph Demystified
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Efficiency in IT has never really been just a nice-to-have. But as increasingly sophisticated compute and data storage needs to be spread further throughout your business's operational landscape, efficiency in gear acquisition, system deployment, ops, and IT resource management becomes a decidedly firm requirement for success. Popular use cases come from the Telecommunications sector, particularly for NFV workloads-operators looking for single-rack deployments of OpenStack generally will want to consider hyper-converged configurations In this session, you will learn how hyperconverged infrastructures can help you make your business and your platform more efficient by simplifying operations. We will dive into hyperconverged basics, analyse the challenges that come with OpenStack in this model, and finally give you the complete recipe for a perfect start with hyperconverged compute and storage in OpenStack.


* **Sean Cohen** *(Sean is a seasoned product manager bringing over 15 years of experience in senior engineering, global operations and services management roles in virtualization & cloud companies. He has international experience of storage virtualization products delivery & private clouds design for enterprise customers in various market segments in US, Europe & APAC. Sean is focused on cloud storage product management and strategy for Red Hat OpenStack Platform cloud offering. Sean is a member of the OpenStack Foundation, a frequent speaker at OpenStack summits and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/.)*

* **Federico Lucifredi** *(Product Management Director for Ceph Storage at Red Hat, formerly the Ubuntu Server PM at Canonical, and the Linux "Systems Management Czar" at SUSE.)*

* **John Fulton** *(John Fulton works in Systems Engineering at Red Hat and focuses on OpenStack and Ceph integration with TripleO and Ansible. He has spent the past six months focused on hyper-converged OpenStack/Ceph deployment; i.e. running Nova Compute and Ceph OSD services on the same servers. Prior to joining Systems Engineering John worked with customers in the highly competitive Financial Services Industry as a technical resource to build private clouds based on Open Stack. He blogs at johnlikesopenstack.com.)*

Intelligent Model-driven Cloud Infrastructre Operations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our presentation is about infrastructure modeling and how it affects continuous operations of Openstack deployments. We will explain how to use models to govern all aspects of day-to-day operations. How to continuously deliver new features and bugfixes into production environment. Setup the ongoing monitoring of log messages and metrics coming from resources that gives operators overview of the current infrastructure health. We will show you how modern orchestrators like openstack-salt, Fuel or Cloudify solve the issues of continuously maintaining the service level of OpenStack deployment within given SLAs and how the service model definitions differ. At the end the service model ontology will give you the ability to track and solve any critical situation and define automated response or learning mechanism to react to events. The presentation will be accompanied by a live demonstration.


* **Ales Komarek** *(Aleš Komárek is a Solutions Architect at tcp cloud a.s. He is responsible for integrating various software and hardware components into working systems. His work includes custom Python development and advanced system automation, orchestration and complete life-cycle management of complex systems with SaltStack and TOSCA. Ales is PTL of openstack-salt project.)*

* **Filip Pytloun** *(Working for tcpcloud as Cloud Architect with main focus on CI/CD systems,automated testing, Debian packaging, security and identity management. Being core developer and co-founder of openstack-salt project. PassionateLinux and Python enthusiast.)*

Challenges and Points of consideration for setting up Hadoop Cluster over Openstack Infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation I would like to discuss about various Challenges and Points of Consideration for setting up Hadoop Cluster over Openstack Infrastructure -  - Baremetal vs Compute (Performance considerations) - Storage backend selection - Scalability - Deployment Choices and so on.   


* **Abhinav Agrawal** *(Working at capacity of Solutions Architect (Storage and Cloud Technologies) with NEC Technologies India Pvt. Ltd having overall more than 10 years of experience, primarily into storage and virtualization domain. Member of NEC's HS Series seondary storage development group (HYDRAstor). Have been leading product team which developed several key features in disk based distributed storage (secondary). Recently started leading team having many openstack community contributors including couple of core community members.)*

The Cloud Can
~~~~~~~~~~~~~

**Abstract:**

A typical cloud deployment focuses on technical requirements and day one implementation. However, after implementation, day two operations kick in. Your team needs to be ready to manage, monitor, and maintain the cloud environment to the expectations of your users. This session focuses on experience from successful production deployments and the use of various strategies and technologies to handle operation of a successful cloud environment. We’ll cover architecture, deployment, networking, storage, monitoring, and management. The attendees will see working examples to demonstrate best practices and management strategies for operational cloud deployments. Attendees will leave with an understanding of the infrastructure components and various technologies used together for an enterprise-grade, manageable OpenStack cloud.


* **Ruchika Kharwar** *(Ruchika Kharwar am a Cloud Success Architect at Redhat. She spends her time working with customers helping them take their POCs to production by enabling integration of various features and components to given them the cloud they want. She helps them with phasing their adoption of the cloud and working across the spectrum with engineerings, sales and process. Ruchika comes with several years of embedded system development at Texas Instruments and she gradually transitioned to the server industry working on ceph storage solutions and then expanding her skills to openstack.   )*

* **Kevin Jones** *(Kevin Jones is a Cloud Architect for Red Hat. His mission is to bring OpenStack into public service for Government, Research, and Educational entities. Kevin spends his time working with customers to define use cases around cloud and devops. Kevin has significant experience working with research and scientific computing entities to determine best fit for OpenStack and other technologies. Kevin comes to Red Hat from NASA Langley Research Center where he was the Chief Technologist for IT. In his role at NASA, he helped evangelize the use of hybrid cloud computing. Kevin came up in his career as a developer first and via curiosity, migrated to a holistic approach focused on utilizing technology to deliver business results. Kevin has been in the IT industry in Public Sector space since 2001. He came up as a developer and evolved into a full bore cloud solution architect. He carries Red Hat certification in OpenStack and Solution Architect certification in Amazon Web Services.)*

Openstack cloud sizing made easy: A simple openstack sizing tool
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this topic we will discuss the issues of translating typical customer cloud requirements into factors to be considered for designing an enterprise grade cloud. This helps cloud architects to understand the key considerations to taken into account while sizing. The session introduces a potential sizing tool to come up with the amount of hardware needed for the control and compute planes of the target openstack cloud. The sizing tool is built based on collective experiences gained in several sizing exercises. The tool takes in customers’ requirements as input and has the flexibility of letting the user configure values of the design parameters. The output would be approximate amount of hardware needed for the control and compute plane as well as block and object storage if needed.


* **Arun Nalpet** *(A Cloud Solution Architect, part of WW Presales. Mainly responsible for designing and architecting cloud solutions for customers and demonstrating the cloud capabilities through a POC.)*

* **Subhrangshu Sarkar** *(Subhrangshu Kumar Sarkar is the world wide lead for the NFV POC COE in HPE and is based out of Bangalore. He has over 15 years of experience and has started his career working on C/Unix and is now focussed around building solutions for Telcos throughout the world. His bios are often written by others. )*

OpenStack: you can take it to the bank!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Being the largest bank in Central and Eastern Europe and the only Russian bank featuring in the World's Top 50 Biggest Banks, Sberbank operates a diverse set of business critical applications hosted on heterogeneous x86 / RISC infrastructure and needs to update them much faster than ever to keep ahead of the game. On its journey towards becoming a true Agile Enterprise, Sberbank has chosen OpenStack and Murano to speed up provisioning of complex multi-tier applications spread across KVM, VMware vSphere, MS Hyper-V, IBM PowerVM and Oracle SPARC virtual machines as well as bare-metal servers for 6500+ in-house developers and QA engineers. This session will provide some details on architectural decisions, trade-offs and lessons learned while designing and building such a complex OpenStack environment.


* **Ivan Krovyakov** *(Ivan Krovyakov is a Cloud Solutions Architect at Mirantis Professional Services. Ivan has more than 8 years of experience in enterprise IT infrastructure architecture and design, and more than 5 years in cloud solutions architecture.)*

* **Vsevolod Pluzhnikov** *(Vsevolod has been working for Savings Bank of Russian Federation since 2012. Since 2013 he participated in planning and design for private cloud concepts and architecture activities for Bank. Now he is one of architects in a team of Openstack deployment project. Vsevolod lives in Moscow.)*

A Simple Way to Backup and Restore OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Backup and Restore is important for OpenStack users to keep their data safe. It is an essential function for most of the enterprises using OpenStack. But most users don’t know that backup and restore is easy to achieve in OpenStack. This session presents how to simply backup and restore the cloud and shows some experiences with a use case. OpenStack is friendly to backup and restore operations. Databases and configurations are two main parts to be backed up and restored. We have designed a simple way to backup and restore the controller plane of Openstack. Nova, Glance, Keystone, Horizon, Cinder, Neutron, Heat and Ceilometer are included in the scope. The method was implemented in IBM Cloud Manager, which is a cloud solution based on Openstack and released to clients.  


* **Haojun Wang** *(Haojun Wang has worked for IBM since 2015 on cloud platform. He focused on the practice of Openstack in enterprise products IBM Cloud Manager. He lives in China. In his spare time, he loves sports, watching films and travelling. )*

* **Chen Xi** *(Xi Chen is working for IBM as Software Developer. He has worked on Cloud Platform for several years. He has rich experience on high availability and backup/restore of Openstack. He lives in the capital of China, Beijing. He loves running and runs several times a week.)*

Building a private cloud with Openstack and Nuage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In 2013 Santander committed to embrace private cloud in an effort to improve IT delivery lead times and consolidate infrastructure resources in line with the company's devops adoption strategy. Being a worldwide financial institution with datacenters in 5 different location across different continents posed no small challenges on infrastructure and network design. We will share with the community the challenges we faced, how they were overcome and the reasons we opted for Openstack and Nuage VSP as key enablers to achieve success.


* **Jorge Garcia** *(Having 15+ years of experience in nework design and implementation I've been involved in all sort of projects (MPLS, VoIP, DWDM) and seen all kinds of technology breakthroughs. In 2013 I was lucky enough to be part of the team which architected the Openstack based Santander Bank private cloud.)*

* **Miguel Angel Perez** *(Network consultant impassioned of technology that takes more than 10 years working with enthusiasm in the market for IT, networking and telecommunications. Now, using all the knowledge adquired in these years to help in the digital transformation of new cloud computing age.)*

Clustered File Systems in Your Application Stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has mature and powerful support for block storage devices. Allowing solutions architects to easily house traditional local file systems for data storage. A busy cloud application at scale needs horizontal scalability and High Availability for all of the layers in the stack. This means Catalyst has been deploying a range of clustered file system solutions inside cloud platforms since 2012. Catalyst have had exposture with NFS, OCFS2, DRBD, CEPH and GlusterFS. We will talk about our experiences here, especially with GlusterFS usage in anger. In this presentation we will talk about the journey we are still on in finding the best fit for a file system inside a large fully-orchestrated cloud application stack. We'll also socialising some mistakes that we think people making when choosing a file storage solution and remind everyone why clustered/networked file systems are a bit of a pain and why it makes sense to start thinking about object storage for more and more use cases.


* **Andrew Boag** *(After completing a Computer Science degree at Otago University in New Zealand, Andrew has been working in various roles from software developer, solutions architect to project manager in the IT industry since 1998. Featuring time in the Media, Banking, Education and bespoke software enginneering sectors. While technical and operational by background, Andrew understands technical leadership and pushing forward with pragmatic solutions to real world problems. Andrew is the Managing Director of the Australian wing of the Catalyst Group, arriving in 2008 as the initial staff member and building up the business to 30 staff over Sydney, Melbourne and Brisbane offices. Having presented at Linux Conference Australia and the Open Source Developers conferences on cloud and open source technologies, Andrew is passionate about OpenStack and the rise of open source cloud technologies and platforms. Giving us all new toolsets to apply to the needs of our clients.)*

Real-time KVM as OpenStack NFV hypervisor
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For network functions virtualization (NFV) workloads, telecommunications companies demand an extremely low-latency, real-time platform. Real-time makes sure there is a defined time limit for worst case latency. This is to process hard deadlines of workloads to avoid any disruption or failure. In this session, we will talk about: - Changes/configurations done in low level kernel-based virtual machine (KVM)/kernel level and how OpenStack is taking advantage of these changes. - Features we are using with real-time KVM like DPDK, vhost-user and OpenvSwitch to solve the latency and throughput needs of telecommunications companies. - Also, we will give a snapshot of performance numbers from our testing with OpenStack Platform and real-time KVM.


* **Pankaj Gupta** *(I am a Software Engineer working with Red Hat on real-time KVM. I have keen interest in fields of low latency user and kernel space networking. My interest lies in how changes in low level networking infrastructure with realtime kernel and KVM fulfil needs of telecom companies for NFV workloads. Also, how this infrastructure is leveraged by Open Stack. I used OpenStack to replicate the latency and throughput numbers which we get with real-time.)*

Containerization and Micro-Services: Technology in Transition
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containerization is gaining much attention in the OpenStack environment.  This presentation explores how and where containers are being used, the merits of containerization, and in particular technology trends and how the IT industry is responding to them.  Those who can see big-picture shifts and changes and the forces that are shaping them are in the best position to capture the greatest befits from the winds of change.  This presentation will most help software engineers to understand key steps in the transition from legacy systems to those that will faciliate cloud-based deployment with containerized services.


* **JOHN TERPSTRA** *(John H Terpstra manages a software enginerring team as part of Dell's Open Source OpenStack solutions team. He helps to define Dell's roadmap for customer-centric OpenStack private cloud solutions. John has a long history of working in the open source community.  He co-founded the Samba Team in 1995, and he led development of Linux platforms at TurboLinux and Caldera.  John has worked with OpenStack since 2013.)*

Embracing Openstack, the right way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is usually one of the first steps of a company’s IT transformation. This transformation forces the IT departments to move out of their comfort zone and embrace new concepts, new processes, and new technologies. That’s why users don’t simply deploy OpenStack in production and hope that everything will be ok. Using our field experience, Red Hat has developed a consulting model to cover the gaps so we don’t limit ourselves to putting an OpenStack platform in the customer’s premises. Instead, we make sure that the customer can achieve their goal of moving to cloud technologies using OpenStack. In this session we will share our consulting model, along with real examples of bad habits that could make an OpenStack project fail.


* **Alberto Garcia** *(Alberto works as Cloud Architect at Red Hat in EMEA. He also leads the EMEA Cloud Infrastucture practice, where he works on the mentoring of consultants and on the development of consulting solution offerings. During his more than ten years of carreer, Alberto has worked in the Telecom industry as a network engineer and in the IT Consulting industry working on the delivery of infrastructure solutions.)*

* **Bart van den Heuvel** *(I manage the EMEA Infrastructure Practice at Red Hat where we deliver high quality, high value Cloud solutions based on emerging technology products. Quality not only in terms of technical ability but also in how the project is positioned and delivered. Using methodologies as SEMAT Essence and Agile we make sure that the right people are involved and we deliver, together with the customer, a realistic and valued result. My role is to help hire new recruits, take responsibility in resource planning and manage a team of around 20 highly skilled, highly motivated IT Architects who work throughout the EMEA region.Develop talent by creating personal development plans, providing guidance and manage the daily operation of the infrastructure practice.)*

Tuning and Optimization of OpenStack Shared Services RabbitMQ and DBs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In setting up OpenStack in Production, there are a number of services like RabbitMQ and Databases that are shared between each of the OpenStack services. Each of these services need to adhere to tuning and optimizations so that each OpenStack service that rely on them can be performant in a Production environment.


* **Ivo Vasev** *(Ivo has been working on and contributing to Open Source software for most of his career and has been primarily contributing to OpenStack since 2012. Projects that Ivo contributed include Nova, Tempest, CloudCAFE. Currently Ivo is responsible for shared services and customer supportability tools development projects in IBM.)*

Get more juice out of your Cloud - Dynamic Over Provisioning techniques
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In a multi-tenanted Enterprise Cloud deployment, every now and then, we face a situation where we wished we had more compute resource to service new requirements. Since capacity planning is not a fool-proof prediction of your growth, facing a resource crunch situation is inevitable. To mitigate this challenge, in this presentation, we will showcase techniques which you can use to run your cloud at maximum efficiency. We will showcase how to make the entire deployment elastic by innovatively expanding and contracting memory / CPU overcommits without penalising performance.


* **Pramod Bhandiwad ** *(Pramod has done his Bachelors in Computer Science Engineering. He brings with him  14 years of experience in the networking and systems domain. He currently heads the Technology Development team at Tata Communications Ltd, a global leader in network and cloud service providers. He is responsible for Openstack based Cloud development and deployment. He has deep understanding of all openstack components and in particular neutron, cinder, murano and sahara. He also has expertise in SDN/NFV technologies. Prior to joining Tata Communications, he was with IBM for 9+ years as Advisory Software Engineer. Between that period, he also had a stint with an ecommerce startup as a Co-Founder and CTO.   Invention Portfolio Invention Plateau holder at IBM Some of Patents Issued held by Pramod : Title: SHARING A TRANSMISSION CONTROL PROTOCOL PORT BY A PLURALITY OF APPLICATIONS Issued as Patent 8619801  in US Issued as Patent 8625626  in US Title: EFFICIENT DATA TRANSFER ON LOCAL NETWORK CONNECTIONS USING A PSUEDO SOCKET LAYER Issued as Patent 8544025  in US Title: HYPERVISOR-BASED DATA TRANSFER Issued as Patent 8468551 Title: METHOD TO EFFICIENTLY USE THE DISK SPACE WHILE UNARCHIVING. Issued as Patent 8275750  in US Issued as Patent 7  in CN Paper Publications (in ip.com) : Title: METHOD FOR FILTERED KERNEL TRACING CAPABILITY FOR NETWORK COMMUNICATION Title: METHOD TO ACCELERATE LARGESEND FEATURE ON TSO (TCP SEGMENT OFFLOAD) ENABLED ADAPTERS Title: FIREWALL RULE PROPAGATION SYSTEM Title: SOCKET LAYER OPTIMIZATION FOR LOCAL HOST CONNECTIONS. Title: METHOD TO EFFICIENTLY PROVISION NETWORK BANDWITH ACROSS WORKLOAD PARTITIONS Title: TCP SEGMENTATION OFFLOAD ASSISTED TCP LARGE RECEIVE OFFLOAD Title: METHOD TO ENHANCE HIGH-AVAILABILITY IN VIPA SETUP  )*

* **Saurabh Gupta** *(Saurabh has over 10 years of experience in PowerPC Architecture, AIX Kernel and TCP network stack components and Cloud development. He has contributed to 1) Performance improvements of Pthread POSIX library and loader/linker subsystem. 2) Power System Software support for various data centers solutions. Currently he is involved with solving our image management platform using Packer as a building block. He holds a patent in AIX Power system quick shutdown/reboot performance enhancement and also has paper publications in AIX Power system Security domain. He has done Master of Science in Software Systems from BITS Pillani and has B.Tech in Computer Science.)*

Multi-site, without the explosions!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

To reach automatic high-availability and disaster-recovery, an OpenStack cloud should not be limited to a single datacenter; a true cloud environment should be stretched across multiple sites. A common theme we encounter when designing OpenStack clouds in enterprise settings is high-availability and disaster-recovery across sites. The rationale is that even if a complete datacenter fails, the cloud needs to continue to work. Multiple individual clouds with disaster-recovery between them fall short; they require an out-of-band backup and restore procedure, which needs to be manually implemented and does not guarantee latest data available on the failover cloud. In this session we will discuss the design of a stretched multi-site OpenStack cloud and provide a proven architecture, validated in real-world implementations. We will share the detailed requirements from the datacenter network interconnect down to OpenStack and storage configurations - without the explosions!


* **Alberto Garcia** *(Alberto works as Cloud Architect at Red Hat in EMEA. He also leads the EMEA Cloud Infrastucture practice, where he works on the mentoring of consultants and on the development of consulting solution offerings. During his more than ten years of carreer, Alberto has worked in the Telecom industry as a network engineer and in the IT Consulting industry working on the delivery of infrastructure solutions.)*

* **Bart van den Heuvel** *(I manage the EMEA Infrastructure Practice at Red Hat where we deliver high quality, high value Cloud solutions based on emerging technology products. Quality not only in terms of technical ability but also in how the project is positioned and delivered. Using methodologies as SEMAT Essence and Agile we make sure that the right people are involved and we deliver, together with the customer, a realistic and valued result. My role is to help hire new recruits, take responsibility in resource planning and manage a team of around 20 highly skilled, highly motivated IT Architects who work throughout the EMEA region.Develop talent by creating personal development plans, providing guidance and manage the daily operation of the infrastructure practice.)*

Innovation BBVA: Next generation Overlay for Kubernetes and Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During this session, BBVA’s innovation department will give an update on how it is transforming its OpenStack infrastructure to become fully containerized. They selected Kubernetes as a platform for dynamic lifecycle management, to quickly stop/start openstack services and place them where desired.  From a networking perspective they are leveraging the overlay technology of Nuage Networks, that has intimately worked with them to  model both OpenStack’s infrastructure networks as the VM networks as overlay networks into a homogenous networking space.


* **Alberto  Morgante Medina** *(I'm currently working at BBVA Bank as a Cloud Computing & Innovation Engineer. I'm developing cloud services in order to apply new technologies to the traditional Bank services. Currently, I'm involved in the deployment of a public cloud based on Openstack and SDN in the BBVA bank for continious delivery purposes. The most important key in the project is the automation of everything)*

* **Fernando Alvarez Gomez** *(I am a licensed MoS engineer, specialized in private and public cloud IT environments. I am trully passionate about building best in class architectural solutions for the most challenging needs. Currently I am working as cloud computing engineer/architect, with emphasis in security architectures. As part of the innovation team in BBVA bank, I am helping with the digital transformation, providing new cloud services based on OpenStack and transmitting this new paradigm to as most IT groups as possible. Our goal is the complete devops adoption inside BBVA, automating everything. )*

Architecting your Private Cloud using Red Hat OpenStack Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Designing and Implementing an enterprise private cloud environment can be very challenging when you consider the complexity of OpenStack and delivering a service level agreement (SLA) to your customers and internal teams. In this talk, you will learn how Rackspace and Red Hat have teamed together to deliver a 99.99% API SLA to our customers. The talk will cover architectural decisions, customization’s, and review the lessons learned to quickly and reliably start your journey of building a enterprise ready private cloud.


* **Manuel Rodriguez** *(Currently working at Rackspace as OpenStack Engineer, Previously working as a System Administrator and Network Security Adminitrator using Free Software. - Undergraduate studies from: Université Nancy 2 - Administrateur de Systèmes et Réseaux Avec du Logiciel Libre - Graduate studies from: Universitat Oberta de Catalunya - Software Libre)*

How OpenStack googlifies the data center
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is today’s most widely used and fastest-growing cloud infrastructure technology. It helps build and manage private, public, and hybrid clouds that ensure reliable, scalable, and flexible services – all while reducing operational overhead. But in order to truly succeed, basing all the data center parts in software is essential or at least highly beneficial. Behind this thought is the googlification of the data center: running software on commodity hardware allows for massive increases in utilization and leads to a significant drop in operations overhead. Based on the Google and Amazon role model, Felix will give an outline of said evolution and claim that OpenStack is a major driving force in the process but is only complete when making good on the ”software-defined“ promise.


* **Felix Hupfeld** *(Felix Hupfeld is one of the creators of XtreemFS, the open-source fault-tolerant distributed file system, spent several years at Google to accompany Google's tape backup system from pre-production to mind-blowing scale, and returned to Berlin to join in founding the software storage company Quobyte. Quobyte's Unified Storage Plane enables everyone to run professional storage infrastructure on standard hardware.)*

The final word on Availability Zones
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Availability zones are one of the most frequently misunderstood and misused constructs in OpenStack. And why not? Each OpenStack service implements them differently -- if it even implements them at all. And yet they are also one of the most important, providing a robust HA option for tenant applications.This session will definitively answer, once and for all, questions such as what availability zones are (and are not), which OpenStack services support AZs and how they relate to one another, the limitations of AZs and best practices and industry standards for using availability zones, including gotchas and lessons learned.


* **Ernest de Leon** *(Ernest de Leon is Director of Services Engineering - North America for Mirantis, and a recovering Cloud Solutions Architect. Ernest is also an Amazon AWS Certified Solutions Architect, with 8 years of experience in the Cloud space (building and operating private clouds as well as designing distributed and highly available applications in the cloud). Ernest primarily focuses on large scale cloud deployments in F500 and Telco spaces as well as the applications that span these clouds. Prior to Mirantis Ernest was at Eucalyptus, and before that, did VMware Professional Services.)*

Instance HA and it impact on SLAs.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we'll cover the meaning of Instance HA, why it is necessary, at a high-level what it takes to configure a cluster to support instance HA and how to setup filters for evacuable and non-evacuable node types


* **John Williams** *(  John Williams, Software Developer/ Principal Engineer with Dell working on Enterprise Cloud Solutions for the last 5+ years. Having worked for several fortune 100 companies over 30+ years, I have experience with itegration of many emerging technologies, engineering practices and software development experiences that lend themselves to developing solutions for the latest business issues.)*

* **Andrew Beekhof** *(Andrew is best known for his work on Pacemaker which he created inMunich while working for SuSE. Since then he as moved back toMelbourne and is currently employed by Red Hat as a Principal SoftwareEngineer, consulting on Pacemaker and creating architectures to meethigh availabilty requirements.)*

Highly available OpenStack. Making sure OpenStack is always there to dispense cloudy goodness.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many components to OpenStack and many have different HA requirements and HA strategies. In this session we will look though which components need to be highly available and the choices you have around configuring those services. The journey will take us from database replication, to instance migration and stopping off at API endpoint HA with VIPs and DNS records on the way.


* **Liam Young** *(Liam works at Canonical on deploying OpenStack with Juju and charms. Before that he worked as a System Administrator supporting a number of private OpenStack clouds among many other things.)*

* **David Ames** *(OpenStack Charm Developer working for Canonical. Interested in deploying OpenStack and managing the entire life cycle, modeling and deploying workloads on Openstack, and participating in the OpenStack community.  )*

Architecting OpenShift on top of OpenStack at Produban
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation Produban will describe the architecture for its Global PaaS solution. The session will start with an overview of the desired business and technical outcomes Produban (IT group behind Grupo Santander) wanted to achieve to setup its PaaS environment. Quickly the session will dive into the architectural details of the chosen OpenStack and Network Architecture that underpin Produban's OpenShift V3.X docker cluster. It will be shown how Nuage Networks SDN features are used for advanced networking configuration across OpenStack and OpenShift, and how the PaaS solution can be scaled out in a big and complex production environment.


* **Cristian Roldan** *(Technical architect with comprehensive experience of designing, developing and deploying architectures and infrastructure for Platform as a Service (PaaS) and Java Application Servers.)*

* **Pablo Alonso Rodriguez** *(Pablo is a Devops Engineer since 2015 at Produban and supports in the build out of the global paas platform. Prior to that he was Research Engineer at Open Middleware. He graduated at the Universidad Politécnica de Madrid.)*

Ironic as a data center appliance & equipment manager
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A project just now ripening to maturity, Ironic is your best bet not only to manage bare-metal instances but also to manage non-OpenStack equipment and their networks. Ahmed Rahal and Philippe Godin will explain how to manage bare metal inventory using the Ironic dashboard, how to push network models and configurations, and how to deliver a publicly exposed—yet secure—server.


* **Ahmed Rahal** *(Planning, building and operating OpenStack deployments since 2013. Planning, building, integrating and operating OpenSource software since much, much longer.)*

* **Philippe Godin** *(After years of trying to make radar systems detect Pokemons, Philippe decided that doing pings with real things was not for him. Being the developer he is, he knew he had to work for a company that would take ping seriously. Currently one of the lead of Internap's Ironic effort, and heavily involved in its open-source effort, Philippe is proud to have helped his team release one of the first public Bare Metal product based on OpenStack)*

* **None None** *(None)*

Identity Management at Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the Openstack community continues to innovate its architecture at a large enterprise scale, Keystone as an Identity Manager is lagging behind.  Multi-cloud and multi-region architectures often have a need for synchronizing both full or partial identities and assignments across sites. This session aims to highlight various identity architectures based on the typical integration requirements of an enterprise environment. Such architectures include integrating with Active Directory, integrating with an Identity Provider, and synchronizing multi-site Keystone identities. Keystone also suffers from the lack of auditing and reporting capabilities, a requirement highly important at large scale. The second portion of this talk aims to introduce Midpoint (OSS covered under the apache 2.0 open source license) as an alternative identity manager behind the scenes, and showcase how a comprehensive identity management solution can address the challenges that Keystone currently fails to address.


* **Florin Stingaciu** *(I have been part of the Openstack community since the Essex release. I've architected, deployed and managed a cloud for one of the top hospitals in Toronto, Canada after which I took more architectural orientated role with Mirantis. I'm currently working towards a more formal solution for Identity Managment and RBAC within Openstack. )*

* **Katarína Valaliková** *(I have been working for the Evolveum company since it was established. I’ve started as a Java Developer implementing midPoint, an open source identity management solution. After some time I  also started with deployments for customers connected with midPoint and single sign-on solutions. Currently I work mostly on designing and implementing midPoint.)*

Swift and Hummingbird: As seen in the wild
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hummingbird is the golang reimplementation of the OpenStack Swift object layer that is currently being reviewed by the upstream Swift community.  At Rackspace, we have deployed Hummingbird to our largest clusters. In this presentation we will go over how we deployed hummingbird and share the performance gains we made.  But beyond the customer API we have done a major redesign to the object replication engine. While not as obvious or apparent as the gains in the API this is a major improvement in cluster health and efficiency.


* **David Goetz** *(David is a software developer at Rackspace and has been on the CloudFiles team working on Openstack Swift since 2010.  A Core contributor since 2011, David is an active member of the Openstack Swift Community.  )*

Application-Aware Data Protection … Virtualization is not Enough
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack environments need robust data protection—something more than just cobbling together scripts or relying on virtualization. This presentation will cover how OpenStack environments benefit from intelligent data protection, such as:   Scaling as the application grows   Efficient Storage   Point-in-time Recovery/Orchestration   Tech Refresh (Use Cases: Upgrades, Disaster Recovery or Data Mobility)   Application Consistent backup   Covering compliance requirement needs


* **Murali Balcha** *(Murali Balcha, co-founder and CTO of Trilio Data, is one of the co-authors of the first specification for OpenStack Backup-as-a-Service, called Raksha. For over 15 plus years Murali Balcha has served in key technical and leadership roles, delivering breakthrough technologies to market. Most recently, he served as an Engineering Leader at EMC, where he led the development of numerous storage, virtualization and cloud computing innovations and established EMC’s leadership in Disaster Recovery, and VMware Integration. An occasional blogger, Murali has been actively involved with OpenStack Community for the past 4 years, particularly in the areas of Storage and Data Protection. He has a Masters in Computer Science from Indian Institute of Technology, Kanpur and a Bachelors from Andhra University, Hyderabad.)*

KVM and QEMU Internals: Understanding the IO Subsystem
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will break down the plethora of options available for delivering storage to a virtual machine in KVM/QEMU. It will detail the mechanics and performance trade offs inherent in the different AIO modes, caching options, paravirtualization drivers, and thread settings. We will outline which OpenStack configuration options lead to the most desireable KVM/QEMU configuration settings, and what could be done to further enhance OpenStack's ability to take advantage of everything KVM/QEMU has to offer. Highlights of performance data will be shared that characterize how these settings affect real world MySQL workloads.  


* **Kyle Bader** *(Kyle Bader is a Senior Solution Architect working in the Storage Solutions Team at Red Hat, lending his design and operational skills with Ceph to help develop tested solutions that ensure repeatable success when deploying distributed, fault-tolerent, multi-petabyte storage systems. Prior to Red Hat, Kyle had architectural roles at both Inktank and DreamHost. Kyle was part of the team that brought the first production Ceph clusters to the world, supporting DreamHost's DreamObjects and DreamCompute services.)*

Providing a Geo-Redundant Application Cloud with OpenStack and Cloud Foundry
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

An examination of the architecture and implementation of Swisscom’s Geo-Redundant Application Cloud (‘MultiCloud’).  A common request from customers migrating legacy applications to cloud native workloads is for a transparent solution which provides effective 100% application availability through geo-redundancy (Geo-Redundancy as a Service).  Swisscom solves this problem with a combination of networking, OpenStack and Cloud Foundry.  The architecture and implementations of our solution will be discussed, along with problems and solutions encountered along the way. 


* **Douglas Copas** *(Swisscom Elastic Cloud Engineer, SDN lead.  Software developer, technology enthusiast, aspiring writer.)*

Multi-Region OpenStack for Mortals
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A discussion of use case specific issues that we run into when architecting custom private clouds for multi-region scenarios. This overview will pertain to general issues but not go into great detail for anyone service. 


* **Christopher Woodard** *(Openstack Architect with Rackspace and avid BBQ fan. Also known to enjoy a bit of whiskey.)*

* **Chris Mecca** *(20 year systems and infrastructure veteran working as an OpenStack Architect for Rackspace, US.)*

Telco NFV Growing Pains – Real World Problems and Solutions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many of the world's leading service providers are accelerating their movement towards wide-scale OpenStack deployments for Telco NFV applications. After several years of laying the preliminary groundwork in terms of architecture, standardization, and more recently proof of concept trials, operators across the globe are now solidifying deployment plans for NFV infrastructure and transitioning away from purpose-built hardware. But in the process of moving from the proof-of-concept phase to a deployable solution, operators have encountered many roadblocks such as performance, scaling, and interoperability issues. We will identify and focus on some of the most critical implementation issues facing NFV end users and service providers today, as they move towards large-scale deployments. Targeted use of NFVi acceleration in the form of SmartNICs will be discussed as a possible solution to address performance and scaling issues.


* **Nick Tausanovitch** *(Nick is the VP of Solutions Architecture at Netronome, where he has been instrumental in driving the company’s SmartNIC acceleration and offload strategy for Cloud IaaS and Telco NFV. In that capacity, Nick has been closely involved with Telco and Cloud Service Providers as they navigate their way towards the optimization and deployment of their cloud data center solutions.   Nick's role includes hardware, software, and network architecture responsibilities. Nick and his organization have been at the forefront of NFV acceleration and offload efforts, working closely with partners and the open source communities over the past several years. In this period, Netronome has developed and delivered to production ground-breaking solutions that greatly accelerate virtual switching, and are tightly integrated with OpenStack and OpenDaylight. Nick’s close interactions with OEMs and end users through multiple PoCs and deployments have given him very practical insight into real-world problems and solutions that he likes to share whenever possible at conferences and webinars.)*

Openstack and Kubernetes: One on Top of the Other, Vice-versa, or Sideways?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack and Kubernetes are leading management platforms in their respective areas: the former for general infrastructure and virtualization, the latter for containers orchestration. For the growing number of organizations that have decided to take advantage of both, a question arises: what is the best way to architect and integrate the two stacks? Historically, the safe answer seemed to be to deploy Kubernetes clusters "on top" of Openstack, using solutions such as Heat, Murano, or Magnum. Recently though, an alternate pattern is emerging: use Kubernetes as a base layer, and deploy Openstack as an "application" on it. What are the advantages of such an approach? Furthermore, a company may have deployed independent Openstack and Kubernetes stacks due to historical or organizational reasons. How can the company integrate the two to leverage their respective strengths? Finally, is it possible to use Murano as a unified catalog for both both Openstack and Kubernetes-based applications?


* **Bich Le** *(Spent most of career innovating in the cloud and virtualization areas. Before co-founding Platform9, spent 14 years as a Principal Engineer at VMware, helping them innovate their way from a small startup to a multi-billion dollar powerhouse. Prior to that, architected the Aries RISC-to-IA64 dynamic translator at Hewlett Packard. Graduate of U.C. Davis Node.js enthusiast and maintainer of the fuse4js github project.)*

* **Daniel Lipovetsky** *(Software Engineer at Platform9, Inc.)*

Controlling access to OpenStack in the Enterprise, this is not a public cloud!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Addressing access control in the enterprise is a hugh challange, as a cloud architect and cloud operator we need to take into account the complexities of exisiting enterprise authentication standards and requirements. The maturity of Openstack authentication mechanisms allows for limited controls and auditing that often dont meet the percieved needs of the enterprise.  We will discussion the short falls and challenges that exisit in Openstack today and what is being done to through blueprints and proposed patches to remedy the situation  Finally we will present a possible solution to the problem, and include a demo of a working RBAC solution for the enterprise.


* **Shaun O’Meara** *(Shaun O’Meara, Senior Sysems Architect at Miranits, has been designing and building Enterprise IT Infrastructure Solutions for 15 years. His work with customers, advising on the journey to cloud and assisting in the development of cloud solutions, has given him a wide scope to learn and try new and diverse technologies.)*

* **Florin Stingaciu** *(I have been part of the Openstack community since the Essex release. I've architected, deployed and managed a cloud for one of the top hospitals in Toronto, Canada after which I took more architectural orientated role with Mirantis. I'm currently working towards a more formal solution for Identity Managment and RBAC within Openstack. )*

Empowering Ironic with Redfish support
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Redfish is an IPMI replacement standardized by the DMTF. It provides a RESTful API for server out of band management and a lightweight data model specification that is scalable, discoverable and extensible. We will start by detailing its role and the features it provides with examples We will then cover the current status around a python library offering Redfish abstractions useful to provide Redfish support for python based solutions such as Ironic in OpenStack. In particular we will detail how this is beneficial for Ironic through power management, information inventory, and how we intend to adapt Ironic to add support for the Redfish specification with new drivers These developments are made to support the deployment of HPE Moonshot cartridges hosting a customer video transcoding application Finally, we'll disclose the Alexandria project to add CMDB support (iTop e.g.) into a Software Defined Infrastructure using Ironic and Redfish based machines Recorded demos will be available


* **Bruno Cornec** *(Bruno Cornec is Engineer of the French Ecole Centrale de Lyon. (1987)He has been managing various Unix systems since 1987 and Linux since 1993 (0.99pl14).Bruno first worked 8 years around Software Engineering and Configuration Management Systems (Build systems, Quality tools) in Unix environments.Since 1995, he is Open Source and Linux (OSL) Technology Strategist and Evangelist, initially for an HPE reseller and since 2000 for Hewlett Packard Enterprise directly in the EMEA Customer Innovation Center. Bruno is also HP WW Linux Community Lead, OSL Advocate, Helion MVP and RHCE. Bruno is a contributor in various OSL projects: MondoRescue (2001), Mageia (2003), LinuxCOE (2006), Pause (2007), Tellico (2008), FOSSology (2008), collectl (2009), Ironic (2015), python-redfish (2015). He is also project leader for MondoRescue (GPL disaster recovery solution, 2005), dploy.org (GPL deployment server, 2006), project-builder.org (GPL build service, 2007), UUWL (LGPL/MIT Unix to Unix Wrapper Library, 2011), PUSK (GPL ProLiant USB Setup Key, 2012), python-redfish (2015). He is a member of the Solution Linux/OWF/POSS Conference Board since 2006.He is also a board member of the AFUL and OpenStack-fr associations. As part of his work he has made numerous presentations for Solution Linux in France, Libre Software Meeting, NordU, Linux World UK, Linux Expo Milano, Linux.Conf.au, OSCON, Linux Symposium, Fosdem around various topics (High Availability, Deployment solutions, System management, Disaster Recovery, Package building, Cloud...) Outside computers, Bruno also likes early and baroque music, singing and playing the recorder. He's married and father of 3 kids.)*

Neutron Mechanism Drivers: What to Ask Your Vendor​
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Do you use OpenStack deployment with a networking solution that is notthe reference implementation? Do you care for a stable and robustsolution?  If you do, you should ask your vendor how it handlesA-Synchronous invocation of networking backend, how does it handle outof sync resources and how does it report back errors to Neutron.In this session we’ll discuss why you care about these questions, whatstands behind them and why they are so important. We would also coverthe way these challenges are handled in OpenDaylight, in OVN and inDragonFlow, all open source solutions.


* **Livnat Peer** *(Livnat Peer is a Senior Engineering manager at Red Hat. Livnat has been part of the on­going innovation in the cloud and virtualization domain, in the last years she was focused around the Networking aspects of this field which is revolutionized by SDN and NFV.Livnat holds MSC in Computer Science from the Hebrew University in Jerusalem with expertise in distributed algorithms.)*

* **Russell Bryant** *(Russell is the Technical Director for OpenStack at Red Hat, Inc.  He is on the OpenStack Technical Committee (since Fall 2012) and served on the OpenStack Foundation Board of Directors from January 2015 to June 2016.  Russell has been contributing to the development of OpenStack since the Fall of 2011.  His most significant contributions around OpenStack have been to Nova and most recently Neutron and OVN. Prior to working for Red Hat, Russell spent 7 years (2004 - 2011) working for Digium on the Asterisk project. In the later years, Russell was the leader of the Asterisk project as well as the Engineering Manager for Asterisk development at Digium. Russell is also a published author.  Russell co-authored "Asterisk: The Definitive Guide" and "Asterisk Cookbook", published by O'Reilly Media.  He also contributed a chapter on Asterisk to the book "Architecture of Open Source Applications". Russell graduated from Clemson University with a Bachelor's degree in Computer Engineering in the Fall of 2006.  He currently resides in Charleston, South Carolina.)*

Stateful Applications in OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Paypal moved stateless workloads to Openstack cloud a few years ago. At PayPal, 100% of front and mid-ier applications run on Openstack. The next logical step is to start moving stateful applications into cloud.   This presents a new set of challenges. In a multi-tenant environment, how do you guarantee that data access is restricted. Recovery is not as simple as spinning up a new compute instance. Data needs to be presented to this new instance ASAP. Load balancers do not solve the problem. Network block storage means you might choke other applications transacting over the network. Solutions range from onboarding these applications on bare metal computes in the cloud (buying some advantage by way of agility) to containerized solutions with a managed storage layer, engineered for fast recovery from failure.  We will present an introductory version of this talk at OpenStack East. This follow-up presentation tracks progress and provides more color to conclusions reached so far.


* **Anant Kumar** *(Anant is currently responsible for managing the Paypal Cloud, the world's largest Openstack deployment. Spent over a decade working in Cisco Engineering, another 2 running a technology driven Fashion eCommerce business and then Indoor Location at Aruba Networks. Currently responsible for managing the Paypal Cloud. PayPal runs the world's largest OpenStack cloud with ~10000 servers. All of paypal.com and applications run on this cloud. An OpenStack newbie 2 years ago, am still learning the intricacies of deploying and managing a cloud using Openstack.  The complexity of running the cloud is in managing the underlying infrastructure and automation around that. )*

* **Jasdeep Sahni** *(Services architect at PayPal)*

History and future of TripleO
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A brief history of TripleO with a focus on how the project has evolved over the years to better accomidate operators and developers.


* **Dan Prince** *(Dan has been involved with OpenStack since Bexar and been involved with many OpenStack projects over the years including Nova, Glance, TripleO and others.)*

Baremetal to Openstack on Kubernetes from 0 to 100
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Imagine you have 13 data centers. Each with a rack of completely blank servers. You have a small but strong, cross-functional team. Your misson, if you choose to accept it, is to deploy and operate an Openstack installation in each data center. What would you do? We chose to drink the kool aid and use Kubernetes and Kolla to manage the Openstack deployments. CoreOS as the underlying operating system promises to minimise operational burden. Bootstrapping this setup in an automated fashion revealed a unique set of challenges that we would like to share. This talk showcases SAP's approach to combine Kolla, Kubernetes and CoreOS into a control plane for an Openstack based private cloud. We will explore how to automatically bootstrap a multi-regional, containerised Openstack from bare metal. A demonstration of our continuous delivery workflow and tools will give you deep hands-on insight. In closing we will discuss pain points and problems we encountered in using a containerised Openstack.


* **Michael Schmidt** *(Michael is a software engineer at SAP in Berlin, Germany working on large-scale enterprise cloud systems. He has a keen interest in tools and technology that allow to release faster and more often. His expectation is that each commit automatically goes to production and it shouldn't be surprising that he is excited about containers, automation, orchestration and the cloud. Michael holds a degree in computer sciences from the Technical University of Berlin, specializing in computer security and artificial intelligence. He's on Twitter and Github as @BugRoger.)*

OpenStack and DC/OS, worlds colliding or merging?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the common questions around OpenStack is “What’s the best way to run cloud native workloads on, or with, OpenStack”. Though OpenStack is the leading open source cloud platform, it’s mostly targeted for more traditional workloads running on bare metal or in VMs.Based on Mesos, DC/OS  is an open source data center OS, designed for running those cloud native and big data workloads at massive scale, efficiently solving the hard problems around cloud native scheduling and clustering.If squarely on one side or the other, your life is pretty easy. For those of us that have a wide variety of workloads, figuring out how to get the best of both worlds can be somewhat challenging.In this session we’ll explore the benefits from running OpenStack and DC/OS together and the use cases and scenarios where this bring the most value.We’ll take a look at the integration work we’ve done in this area and how it can be applied to maximize the benefit in heterogeneous environments.


* **henrik blixt** *(Henrik is a Sr Product Manager for compute in Helion OpenStack, focusing on virtualization, bare metal and containers. He has almost 20 years of experience split between professional services as a developer, DBA and sysadmin and lately as a product manager, working on how to make life easier, and provide tools, for people in those roles. A native of Sweden, where he earned his B.Sc in information systems from the University of Gothenburg, he now lives in California with his family.)*

* **Amina Abdulla** *(.)*

Big Data - big deal?
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Big Data and Cloud: two of the main overarching topics in enterprise IT this summer. Both have one thing in common - there are a few ways to get it right and more ways to get it wrong. Put both together and you can do amazing things - or fall of a very tall cliff. We are currently working on a number of concurrent Big Data projects, both with Big Data as a service in form of Sahara, and with other Big Data deployment approaches. In this session we will discuss our experiences with these projects and the architectural work we've done around the various Hadoop distributions, which we have carefully distilled into a delicious blend of applicable information with hints of theory and stories from the trenches. As a team we are going to present the current state of affairs of Big Data in the cloud, approaches to get a Big Data project right and caveats to avoid falling into common traps.


* **Christian Huebner** *(Christian Huebner works at the Mountain View head office of Mirantis, Inc. as Senior OpenStack Storage and Cloud Architect. Coming from a conventional storage architecture background, Christian moved into cloud storage before joining Mirantis and later into general cloud architecture. He currently is spearheading Big Data and Storage architecture projects for Mirantis customers with the focus on providing reference architectures and technical and organizational assistance for a wide range of storage technologies. In addition to the storage focus, Christian is providing architectural guidance and implementation consulting as well as subject matter expertise for a wide variety of customer OpenStack cloud projects. Christian has been a speaker at the five most recent OpenStack Summits, presenting topics from his experience as architect and storage subject matter expert.)*

* **Thomas Lichtenstein** *(Thomas Lichtenstein is a Solutions Engineer with Mirantis. He focusses on delivering OpenStack solutions to large scale enterprises. He has a strong background in software engineering, graduated with a Master in Computer Science from Karlsruhe Institute of Technology, and studied abroad at Carnegie Mellon University Pittsburgh as well as Budapest University of Technology and Economics. Thomas has presented at several OpenStack events on various cloud storage topics.)*

Evaluating OpenStack Network Architectures at Scale (Armchair Not Included)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

On an average day, AT&T is transiting 114 petabytes of data across its network.  This has required that we carefully evaluate how we build and operate our networks especially within our OpenStack environments where NFV deployments are growing rapidly.  Choosing a particular approach has lasting consequences and today there are more OpenStack network architectures and plugins than at any time in the past.   How do you choose an architecture, plugin, and set each of the many tunable parameters correctly for your organization? You’ll learn how we approached systematically comparing, benchmarking, ranking, and stress testing network plugins and architectures available in OpenStack including options such as OpenContrail, DragonFlow, OVS+SFC, and more.  We’ll review the tools we leveraged, and finally discuss our criteria for ultimately selecting the correct strategy for our organization and our complex NFV needs.  


* **Alan Meadows** *(Alan Meadows works as an OpenStack Architect, responsible for designing, maintaining, and scaling OpenStack infrastructure that spans hundreds of datacenters with mission critical telecom requirements.)*

* **Lee Riviere** *(Lee has been in the IT industry for over 20 years the majority of which as a consultant.  Four years ago AT&T gave him a pitcher of OpenStack cool-aid and he has been drinking it ever since.  )*

Big Brother is watching you! Or how to audit the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operating big public clouds opens a wide stack of challenges and security requirements to architects, cloud operators and all members of public cloud vendor team. Each user step should be verified and tracked to avoid intrusions or/and to have a chance to identify actions sequence that may have caused some issue or led to an unpredictable situation. A cloud audit enables you to monitor who, when, where, why and how actions were taken in the cloud environment. In this presentation we will describe our experience of implementing a CADF based audit, and overview cloud performance measurements, the decisions we made and which solutions we had to reject and why.


* **Oleksii Kolodiazhnyi** *(Oleksii is a Team/Tech Lead in Services department in Mirantis. He is engaged in different Mirantis migration and deployment projects (partially, full time or as an expert).)*

Virtual Machine HA on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many workloads in today’s datacenters are like pets. Their lifespan is in years; they run mission critical service that must be up 24x7. Modern, cloud native applications are designed to tolerate failures. The cloud methodology encourages Cattle approach which treats VMs as commodity. In the near future Pet workloads will coexist with Cattle due to many reasons - (1) During the transition from a datacenter environment to the cloud, a mix of workloads prevail. (2) Legacy applications cannot be easily converted to cloud paradigm. Given the state of enterprise workloads, Virtual Machine High Availability (VM HA) is a must have capability.In the OpenStack community, HA solutions typically deploy Pacemaker with Corosync. At Platform9, we chose Consul to implement a VM HA solution. We found it is easy to adopt and scalable. In this talk we present this feature, experience of running Pet VMs with HA in production and the metrics used to measure effectiveness of VM HA.


* **Sachin Manpathak** *(I lead core openstack projects at Platform9 such as Nova, Cinder and Keystone. In the past, I was an engineer in  VMware Resource Management group responsible for Storage DRS and Storage IO Control. I am passonate about Cloud, Resource Management, Storage and Containers.)*

Boosting OpenStack Performance by using PyPy JIT as the default Python interpreter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk, we will demonstrate how to improve OpenStack performance by making PyPy JIT (Just-In-Time) as the default Python interpreter with no application code changes. We conducted a proof-of-concept study using PyPy JIT on five core components, Keystone, Nova, Neutron, Glance and Cinder.  Our result indicates performance gain by up to 35%, and often non-interpreter related bottlenecks are exposed after PyPy JIT is used, painting a bright picture for a wider adoption of PyPy JIT in all OpenStack components.  In addition, we will also explain how to experiment with PyPy JIT and share some of the issues and experience we have gained in the adoption process.  This talk is a continuation of a previous talk by Dave Stewart/John Dickson titled “Doubling Performance in Swift with No Code Changes” and presented in the OpenStack Summit Austin 2016, in which up to 111% gain was demonstrated on OpenStack Swift   .  .  


* **Peter Wang** *(Peter Wang is a software performance engineer in the Server Language Optimization Team in the Data Center Software Technology group at Intel. Peter has been working on various SW projects at Intel for over 20 years. In the last 12 years, he has been focusing on enterprise application benchmarking, performance analysis and tuning on x86 microarchiecture.  He is currently leading a team of engineers on improving the performance of the open sourced Python interpreters including CPython and PyPy)*

Wizard – Generalized Execution Service in Cloud Computing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Wizard is high-performance dynamic execution service for multi-purpose computing. It has been developed on the context of consistent and scalable computing requirements on the machine learning model calculation, and is extending to the external areas step by step. Wizard provides simple, flexible primitives for managing and operating the executions. These primitives allow various approaches to dynamic program execution to support for various computing environments and performance requirements. Flexible and easy usability have been provisioned by the pluggable transport layer support, so that users can operate their executions via REST API, RPC, web socket… and so forth. Scalable distributed computing have typically supported by using either OpenStack or Docker Swarm cluster as a common execution environment.


* **Debojyoti Dutta** *(Debo~ is a principal engineer in the Office of the Cloud CTO at Cisco Systems where he is involved in several efforts on Openstack including building out large scale big data systems. He is passionate about different aspects of large scale streaming data. He has years of data science experience, both as a postdoctoral research associate in Computational Biology at the University of Southern Califonia and later as a visiting researcher at Stanford (http://widescope.stanford.edu/about.html). He has made several presentations in previous OpenStack summits, most recently in Vancouver. One of them was a recursive container architecture that was implemented and demo-ed at Portland by his team. Parts of it got incorporated into Horizon and the overall project has been opensourced (https://github.com/CiscoSystems/donabe). More recently in the Vancouver summit, he presented work done on Demystifying Logs in OpenStack Clouds (https://www.openstack.org/summit/vancouver-2015/summit-videos/presentation/demystifying-logs-in-openstack-clouds).)*

Tenancy Data Backup Beyond Freezer & Raksha
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Will the real OpenStack Backup Solution please stand up?  How does the cloud owner provide the cloud tenancy with backup?  EMC has been in the business of backing up & protecting data for more than 30 years across multiple platforms & products.  Learn how you can backup all of your domains, projects/tenants and instance metadata through our Horizon GUI or API workflow.  In this session, Mark West discusses some of the limitations of OpenStack backup, explores some of the whitespace within this rapidly growing area, and identifies key architecture & operational considerations when selecting a backup and recovery solution.  Learn about EMC’s Data Protection Extension for OpenStack and how it works with EMC partner reference architectures for Mirantis, Red Hat & Ubuntu and the performance improvements to Backup & Recovery coming down the pipeline.  Learn about how we used Ansible to automate our Continuous Delivery pipeline reducing our cycle time while making better software faster.


* **Mark West** *(Mark West has been a software professional for over 15 years. He is currently a Principal Software Engineer and Architect leading OpenStack Data Protection design and development project at EMC.  Mark’s experience spans from IT Operation to Engineering Development specializing in cloud computing on Microsoft, VMware, and OpenStack platforms.  As an architect for OpenStack Data Protection, Mark has involved in various design discussions with large enterprises and service providers and has a deep understanding of many OpenStack deployments and their data protection needs.)*

Leveraging Hybrid, SDDC & Multi-Cloud Best Practices to attain portability of your Cloud Workloads
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Three leads in multi-infrastructure Ops. discuss real life examples of deploying applications that span multiple clouds and infrastructures as one contiguous platform. We’ll share best practices and architectures to ensure that workloads and applications are portable. Do you prefer not to become too over-reliant on one cloud? We’ll talk about common pitfalls that limit portability and how to avoid them. With few standards between public providers it is common to fall into the pit of vendor locked technology. The only standard that exists is the standard you make. Are you looking at containers because they enable your application portability? Please join us as we discuss how containers help improve your portability.  We will present data on various approaches to increase density, cover pros and cons of using containers on VMs, and talk about options like MAAS and Ironic.


* **Rob Hirschfeld** *(Rob Hirschfeld has been involved in OpenStack since the earliest days with a focus on ops and building the infrastructure that powers cloud and storage.  He's also co-Chair of the Kubernetes Cluster Ops SIG and a four term OpenStack board member. The RackN team has deep knowledge of Kubernetes (we've been deploying it on clouds and metal), OpenStack (we created the Crowbar project) and cloud native architecture (we migrated Digital Rebar to be micro-services). Basically, Rob has deep ops knowledge of both platforms AND experience with cloud native migrations. He's also a regular speaker at OpenStack Summits about items including SDN, interop and running Kubernetes. You can read more about my thoughts and positions regarding OpenStack and Cloud on my blog: http://RobHirschfeld.com.)*

* **Amit Tank** *(Amit Tank is a Sr. Principal Cloud Architect with AT&T. He spends his time designing and building large scale cloud infrastructure, and leading projects and teams of technologists working towards putting OpenStack in production - while contributing the learnings back to the community. He enjoys helping enterprises, businesses and customers become fluent with OpenStack, Open Source, and Cloud skills and technologies within their organizations. Prior professional associations include several startups, DirecTV, Cisco, EMC, Hitachi, and Schindler among others.)*

* **Peter Lopez** *(Peter is the principle architect for Technicolor focusing on Software Defined Data Center and overall IT strategy pertaining to modernization of process and technology. As an advised to larger global corporation and government entities for last the 20 years he has gain tremendous insight into trends in technology which have proven exceptionally valuable to the industry. Working with companies such as Disney, Raytheon, Northrop Grumman, IBM, Microsoft and the OpenStack Foundation has resulted designs and innovation which meet strict security and compliance needs but maintains the flexibility to drive todays agile innovation in public and private clouds.)*

Highly Available Platform as a Service - Powered by Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building a platform as a service involves multiple architectural decisions and you have to fill tons of user expectations... from making it high available to provide plethora of services. On this talk we will see the technical details on how to create a highly available platform as a service which will provide 99.99% of SLA on all your customers applications, all of them sitting on our openstack private cloud. On this presentation you we will take you through   Architectural diagrams (Network diagrams, Infrastructure diagrams) Components of the platform as a service (Storage, Network, Automation, Images, Schedulers, Loadbalancers) Automation Workflow (One button deployment for all your platforma as a service) Creating platform services (Templates, database as a service, message bus as a service, batch processing as a service and more). Demo of user experience  


* **Miguel Zuniga** *(Experience technical lead, who during his past 10 years in the field has worked with physical, virtual and cloud technologies. He is a supporter of all open source projects and evangelist of using open source tools. Now is a member of the Symantec's Cloud Platform Engineering leading the Platform as a Service.  During his free time he enjoys reverse engineering how technologies work just for the fun of it. Some of his favorite past and ongoing projects include:   Virtual HA Cluster using CentOS/RedHat Cluster Suite and VMware Server 1 (2006) Automated datacenter provisioning and deployment using open source tools (2010)   Open source in-house S3 (2012) OpenEscalar cloud management framework (ongoing) Canister container management and provisioning (ongoing)     His past work experience includes:   Sr Cloud Lead at Paypal Tech Lead at Electronic Arts Digital Platorm  Sr. Cloud Engineer at Rackspace Cloud Sites Sr. Linux Engineer at GlaxoSmithKline Sr. Linux Engineer at GE Corporate International Contracts)*

Decomposing a monolithic architecture through common frameworks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack provides a monolithic canvas to build the cloud of your dreams.  Building the "Art of the Possible" can disable even the best architect. Development of rapid, modular and fluid IT demands more from infrastructure through the application layer. Decomposing the architecture and align it with common frameworks built in small appliance-like blocks requires enterprise architectures need to be more flexible and liquid, forcing architects and engineers to think on designs that are more appliance driven. This session is designed to be a deep dive into containerization of the entire cloud infrastructure and application layer. We will look at the technical considerations, review tradeoffs and look at an example environment that has various levels of simplified blocks to enable snap-on like Lego Blocks.   


* **Denise Glasscock** *(Global OpenStack Lead and Community of Practice lead for OpenStack.  I am responsible for the Strategic direction for OpenStack and lead the Red Hat Cloud Offering.  I provide the enablement, act as the technology SME for OpenSource Cloud solutions, and help drive client pipeline and Sales enablement.  I have almost 10 years of Cloud experience across all of the large cloud platforms and I have 20 years of experience in Datacenter and systems integration.  I am certified as a TOGAF and IBM Architect in infrastructure and Integrator knowledge domains.  I hold certifications in OpenStack and have an instructor rating within VMware and Red Hat.  I also provide workshops at all levels to help Accenture and our clients grow their knowledge and understanding of market and technology.)*

Building an Open Source, On-Prem, Provisioned IOPS Service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation examines the performance characteristics of MySQL on Amazon EBS Provisioned IOPS and details how to achieve similar levels of performance with Ceph, the dominant reference driver for Cinder block storage.  It will also examine the ability of AWS to mitigate “noisy-neighbor” challenges through deterministic performance, and discuss how this could be done with upcoming enhancements to Cinder drivers for configuring QEMU IO throttling. Details from the published reference architecture will be discussed, including MySQL performance highlights from 30+ different Ceph and AWS EBS permutations measured. MySQL, and its close relative MariaDB, are consistently in the top workloads running on OpenStack clouds.  This session helps operators understand various hardware selection and MySQL/OpenStack tuning strategies to obtain target IOPS performance.


* **Brent Compton** *(Brent Compton is Director Storage Solution Architectures at Red Hat, leading the team responsible for building Ceph and Gluster storage reference architectures with Red Hat Storage partners.  Before Red Hat, Brent was responsible for emerging non-volatile memory software technologies at Fusion-io.  Previous enterprise software leadership roles include VP Product Management at Micromuse (now IBM Tivoli Netcool) and Product Marketing Director within HP’s OpenView software division.  Within enterprise IT, Brent also served as Director Middleware Development Platforms at the LDS Church and as CIO at Joint Commission International. Clips from a recent conference presentation: https://www.youtube.com/watch?v=ngsxyn2dfus&feature=youtu.be)*

* **Kyle Bader** *(Kyle Bader is a Senior Solution Architect working in the Storage Solutions Team at Red Hat, lending his design and operational skills with Ceph to help develop tested solutions that ensure repeatable success when deploying distributed, fault-tolerent, multi-petabyte storage systems. Prior to Red Hat, Kyle had architectural roles at both Inktank and DreamHost. Kyle was part of the team that brought the first production Ceph clusters to the world, supporting DreamHost's DreamObjects and DreamCompute services.)*

* **Yves Trudeau** *(Yves is a Principal Consultant at Percona, specializing in MySQL High-Availability and distributed systems. Prior to joining Percona in 2009, he worked as a senior consultant for MySQL AB and Sun Microsystems, assisting customers across North America with NDB Cluster and Heartbeat/DRBD technologies. Yves holds a Ph.D. in Experimental Physics from Université de Sherbrooke. He lives in Québec, Canada with his wife and three daughters.)*

OpenStack Hardware Selection Panel: Ceph perf on Dell, QCT, Supermicro, Samsung, SanDisk
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This panel of Dell, Supermicro, QCT, Samsung, and SanDisk architects will discuss performance results from recently published Ceph benchmark studies.  Contrast results from flash-sleds and flash arrays, to standard, dense, and ultra-dense HDD-based servers. Ceph is the most commonly-deployed storage with OpenStack.  OpenStack Ceph clusters can support a wide range of IO workloads.  But which hardware can provide desired performance optimized for target workload IO patterns?  Attend this panel for a lively discussion on this question as well as emerging hardware trends.


* **JOHN TERPSTRA** *(John H Terpstra manages a software enginerring team as part of Dell's Open Source OpenStack solutions team. He helps to define Dell's roadmap for customer-centric OpenStack private cloud solutions. John has a long history of working in the open source community.  He co-founded the Samba Team in 1995, and he led development of Linux platforms at TurboLinux and Caldera.  John has worked with OpenStack since 2013.)*

* **Alan Johnson** *(Alan Johnson is the Storage Applications Manager for Super Micro Computer Inc. He has been involved in storage for the last 35 years and during this time has seen individual hard drive capacities grow from 5 MB to 8TB. More recently he has been navigating the many facets of Software Defined Storage including Openstack and Ceph. Alan has been a long time contributor to the industry; involved in many storage related forums such as the Storage Networking Industry Asscociation (SNIA)  and the Scsi Trade Association (SCSITA). In the past he has also served as a director within The Fibre Channel Industry Accociation (Europe). He holds Bsc and MSc degrees from Dublin City University in Ireland.)*

* **Bob Napaa** *(Placeholder)*

* **Veda Shankar** *(Placeholder)*

* **Brent Compton** *(Brent Compton is Director Storage Solution Architectures at Red Hat, leading the team responsible for building Ceph and Gluster storage reference architectures with Red Hat Storage partners.  Before Red Hat, Brent was responsible for emerging non-volatile memory software technologies at Fusion-io.  Previous enterprise software leadership roles include VP Product Management at Micromuse (now IBM Tivoli Netcool) and Product Marketing Director within HP’s OpenView software division.  Within enterprise IT, Brent also served as Director Middleware Development Platforms at the LDS Church and as CIO at Joint Commission International. Clips from a recent conference presentation: https://www.youtube.com/watch?v=ngsxyn2dfus&feature=youtu.be)*

The Many Personas of Interoperability: Why Operators, Vendors, End Users, & OpenStack Devs Care
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack has matured as a project over the past six years, it has created a vibrant ecosystem of users, products, developers, and operators.  As OpenStack has proliferated across the world, interoperability between OpenStack-powered clouds has become an increasing concern.  The DefCore Committee was created with a mandate to tackle the interoperability issue. As DefCore and the OpenStack Powered program have matured, we’ve come to recognize that there are distinct personas in the OpenStack community that care about interoperability for different reasons, are impacted in different ways, and can take different actions to help ensure an interoperable future for OpenStack.  In this talk, we’ll discuss some of the many personas who have a stake in the interoperability game, why they care, what actions they can take, and how DefCore’s work will impact them.


* **Mark Voelker** *(Mark Voelker is currently the OpenStack Architect with VMware, but generally prefers to think of himself as a breadth-first technologist. In past lives he has worked as a software engineer, engineering manager, and architect designing web applications, automation systems, mobile apps, traffic generators, and more weasely hacks than he can shake a stick at. He also helped design and support the infrastructure supporting his software, including LANs, award-winning SANs, load balancing, and servers. Mark currently works on enterprise cloud architecture, software defined networking, and distributed systems. He's been enamoured of Open Source approximately since his first exposure to the Internet, helped found Cisco's Open Source Conference and was part of the OpenStack@Cisco team before joining VMware in 2014 where he leads architecture for the VMware Integrated OpenStack R&D team. Mark has been active in the OpenStack community since 2011 when he attended the Diablo Design Summit and has been an attendee and/or speaker at every Summit since.  He is OpenStack Foundation member #54 and owns enough OpenStack t-shirts that he can go long stretches without doing laundry.  Mark co-founded the Triangle OpenStack Meetup in Research Triangle Park, NC in 2013 and currently leads the group's 830+ members.  As an application developer and infrastructure afficionado, Mark is concerned with interoperability of cloud platforms and is the co-chair of the DefCore Committee.  He is also a former core reviewer on the Puppet OpenStack project.  He has a habit of including vacation photos and Douglas Adams quotes in his presentations and his time can generally be bought with a sufficient quantity of doughnuts. When not holed up within the trail-photo covered walls of his workspace at home near Research Triangle Park, North Carolina, Mark can be found hiking, camping, backpacking, or making sawdust with extreme prejudice. Mark is a proud alumni of the Park Scholarships at NC State University and currently serves as a Regional Selection Leader for the scholarship. You can also find him on Twitter, LinkedIn, SlideShare, or at his occasional blog.)*

Orchestrate, Secure, Recover SRIOV Virtual Network Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You might have heard about SRIOV and its benefits to Customers requesting high speed and bandwidth to support the Virtual Network Function Needs, but still you might be missing an end to end picture on how to orchestrate, enforce security and how to recover a failed SRIOV VM. At AT&T we designed and made it simple for our VNF customers to create SRIOV networks via HEAT and Neutron and extension to NOVA Compute. And to better things, we have imposed security rules by using DPDK APIs to configure the Virtual functions and at the same time our design didn’t deviate much from Openstack APIs and governance. This will be a great opportunity for anyone looking to learn about how SRIOV and DPDK APIs work in tandem to provide fast data path networks for Virtual Network Functions in your private cloud and enterprise needs.


* **Ganeshkumar Natarajan** *(Ganeshkumar Natarajan (ganeshkumar.natarajan@att.com) works at AT&T Inc. USA, as Principal Technical Architect. He is one of the lead Cloud solution architect currently working on ATT Integrated Cloud (AIC). AIC is AT&T's largest enterprise cloud built on Openstack that serves all AT&T traffic for mobility, IT workloads and Network Functions. His broad experience includes solution architecture, design, and development of the product all the way to production deployment.  Before AIC work, he was lead developer for ATT CDN Cache and Streaming platforms and has also successfully developed and deployed many Enterprise Android Mobile Cloud based application products for AT&T.)*

* **Rodolfo Pacheco** *(Rodolfo Pacheco (rp2723@att.com) works at AT&T as the Leader of the AIC Design TEam , and as a   Cloud Architect helping build the AT&T AIC OpenStack Cloud. The foundational platform for AT&T’s Network On Demand platform.  Prior to that, he was the code Developer and Architect for the AT&T Netbond service.)*

* **Munish Mehan** *(Munish Mehan (munish.mehan@att.com) works at AT&T as Prinicipal Technical Architect and has been working on AT&Ts Openstack Cloud platform. This platform is used by various AT&T applications and host NFVs for various business units. Prior to that, he was developer fot A&T Netbond service and worked on CDN Streaming.)*

OpenContrail, Openstack and building a hardware and SDN integrated CICD Pipeline
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operators at telco scale have large OpenStack setups beyond the typical neutron L3 gateway case. They typically have to integrate with more than one SDN vendor that will be different from who their physical networking infrastructure comes from. We faced challenges building, maintaining, and operating clouds at this scale and rolling out complex and new software releases. In this talk we explore the strategies large telco’s like AT&T employ and use when building their CI/testing chains and beyond how they plan to use off the shelf open source tools when testing them and how OpenStack helps make that easier.


* **Randeep Jalli** *(Lead Openstack/Devops/Networking Engineer at AT&T Integrated Cloud, worked on/been a part of multiple cloud projects and building/tweaking/deploying/maintaining the AIC platform for various applications around AT&T including but not limited to AT&T Business VOIP, Wireline, Uverse and Mobility. Helped setup/refine the contrail CI/CD pipeline at AIC (AT&T Integrated Cloud).)*

* **Elise Eiden** *(Developer at AT&T working to expand the company's Community presence.)*

* **Buddy Yaussy** *(As a Principal Member of Technical Staff at AT&T (AT&T Foundry), Buddy is focused on the company's publicly stated goal of moving their networks towards a software-defined, virtualized infrastructure. How can AT&T migrate their highly specialized "monster" wired and wireless networks? Relying on his background in networking, high-speed communications and multimedia content creation, management and delivery, Buddy is actively in the process of figuring it out! Buddy graduated from West Point, USMA, and has spent a long career developing various communications devices and technologies with Hayes, Broadcom, Scientific Atlanta and AT&T. Buddy is currently a member of the AT&T Foundry, where he and his team are focused on NFV-ifying various mobility and wireline consumer services, re-engineering and deploying new and legacy applications to our Openstack/Contrail integrated cloud, and evolving the U-verse/DirecTV media platforms for 2020 and beyond.)*

* **Tobias Ford** *(As the AVP of Cloud Infrastructure and Platform Architecture & Strategy for AT&T, Toby Ford leads technology efforts around AT&T's cloud offerings both internally and externally focused. Currently, Mr. Ford is responsible for shepherding SDN and NFV projects on to AT&T’s Common Cloud platform. Toby served as CTO for USi, which was acquired by AT&T in 2006. Previously, Mr. Ford held positions at Cornell University, ARINC, TeleCommunication Systems, and his own company in the Netherlands. Toby is also a member of the OpenStack Board of Directors.    )*

Control Plane Architectures: Design Solutions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building an OpenStack private cloud can be very complex.  Underpinning the entire operational capabilities of your cloud is the Control Plane.  It's common knowledge you should treat your cloud resources "like cattle" and not "pets", yet most clouds treat the control plane like a favored pet. How should the modern cloud architect choose to design the control plane aspect of your private cloud? 


* **Shane Gibson** *(Shane Gibson serves as the Cloud Infrastructure Architect for ZeroStack, Inc., which is a private cloud solutions company.  There he is responsible for the architecture, implementation, and management of the internal cloud platform that drives the SaaS and Cloud Portal that power the ZeroStack solution.  Previously, he served as Sr. Principal Infrastructure Architect at Symantec for the Cloud Platform Engineering (CPE) team. He was responsible for the infrastructure design of the underlying platforms, operating systems, tools, and application stack that enables the OpenStack clusters within the CPE group. In previous roles, Shane has served as a Systems Architect, Network Architect, Security Architect, Unix Systems Administrator, Mainframe Operator, Mainframe Hardware Specialist, and has also served in the United States Marine Corps.)*

Openstack Flavor series, an AWS Parity for Private Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack defines Flavors which is synonymous to instance Types in AWS, but what the opensource community lacks is clear categorization of flavors depicting various Tenant offerings and capabilities, something AWS and other public cloud providers have an edge. This session aims to introduce the concept of “flavor series” to draw the parity of flavor categorization in Openstack cloud. We will share process, flows and design on how to go about defining flavors series and creating, distributing and managing flavors and host aggregates over multiple independent cloud zones. You will learn how we leveraged HEAT Templates as a standard resource definition interface to perform our complete platform resource life cycle management. We will show recorded demo on how to use Openstack Resource Manager Framework we introduced at Austin Summit to accomplish this distribution.


* **Ganeshkumar Natarajan** *(Ganeshkumar Natarajan (ganeshkumar.natarajan@att.com) works at AT&T Inc. USA, as Principal Technical Architect. He is one of the lead Cloud solution architect currently working on ATT Integrated Cloud (AIC). AIC is AT&T's largest enterprise cloud built on Openstack that serves all AT&T traffic for mobility, IT workloads and Network Functions. His broad experience includes solution architecture, design, and development of the product all the way to production deployment.  Before AIC work, he was lead developer for ATT CDN Cache and Streaming platforms and has also successfully developed and deployed many Enterprise Android Mobile Cloud based application products for AT&T.)*

* **Rodolfo Pacheco** *(Rodolfo Pacheco (rp2723@att.com) works at AT&T as the Leader of the AIC Design TEam , and as a   Cloud Architect helping build the AT&T AIC OpenStack Cloud. The foundational platform for AT&T’s Network On Demand platform.  Prior to that, he was the code Developer and Architect for the AT&T Netbond service.)*

Building the Perfect OpenStack Appliance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Selecting a hardware platform to create a hardened OpenStack appliance is a daunting task.  In this presentation, we'll cover real world examples of hardware configurations designed to help you accelerate your initiative to build an appliance (or appliance-like) device for your OpenStack initiative.  We will cover: base hardware platform format the nuts and bolts of the hardware the hardware parts and their drivers as they relate to Linux considerations for OpenStack networking  hardware lifecycle management going to market - customization of the platform Real world hardware configurations and examples will be provided of various platform configurations.   


* **Shane Gibson** *(Shane Gibson serves as the Cloud Infrastructure Architect for ZeroStack, Inc., which is a private cloud solutions company.  There he is responsible for the architecture, implementation, and management of the internal cloud platform that drives the SaaS and Cloud Portal that power the ZeroStack solution.  Previously, he served as Sr. Principal Infrastructure Architect at Symantec for the Cloud Platform Engineering (CPE) team. He was responsible for the infrastructure design of the underlying platforms, operating systems, tools, and application stack that enables the OpenStack clusters within the CPE group. In previous roles, Shane has served as a Systems Architect, Network Architect, Security Architect, Unix Systems Administrator, Mainframe Operator, Mainframe Hardware Specialist, and has also served in the United States Marine Corps.)*

Are Reference Implementations Fashionable?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The problem for new adopters / seekers of OpenStack is that they are not sure where to start and how to start, leave alone appreciating where OpenStack can help them.  In this session we share our findings from user surveys on typical deployment sizes and their usages and the reference implementations born from them. The fact that telcos / enterprises range from ~$100 M to $ 100 B and beyond, the appetite for OpenStack adoption falls across huge spectrum. So are the use cases, users, and preferences of projects / tools based on more sensitive business parameters and not necessarily on the basis of technical appropriateness. The reference implementations are a step in this direction to enable enterprises to jump start on OpenStack, in a fast, reliable, effective, and efficient manner. We next present our work on one such “packaged” implementation, a wizard driven cloud deployment that installs reference implementations on enterprise-grade servers and developer NUCs, alike.


* **Malini Bhandaru** *(Malini Bhandaru, Ph.D., Intel, is an Senior Software Architect  with the Open source Technology Center at Intel.  She has been involved with OpenStack for over three years.  Her interests span security, key management, access control, dynamic resource scheduling, network function virtualization, and scalability. She co-authored the “OpenStack Security Guide”. Prior to her open source cloud endeavors she worked on power and performance aspects on Intel’s Xeon server product line.  Before joining Intel, she worked at Nuance, Verizon, and several start-ups in Massachusetts. She has two patents granted and nine more filed. She has a Ph.D. in Artificial Intelligence from the University of Massachusetts, Amherst. She volunteers for science education activities and computer literacy. Through Intel she had the unique opportunity to develop and field trial in Bangladesh and India an Android application to assist farmers with their fertilizer needs. Malini lives in the Bay Area with her husband and sons, and enjoys gardening and hiking.)*

* **Sonu Sreenivasan** *(Sonu Sreenivasan is a Program Manager in the Cloud and Network Engineering team, part of the OpenSource Techonology center at Intel. He oversees the engineering execution for the OpenStack Innovation Center partnership. He brings with him about 19 years of industry experience spread across, software design & development, IT Operations, program management, and cross-geo software delivery management across various business verticals. He has been with Intel for about 16 years and was based across multiple geographies. Sonu has a Masters in Computer Science. He is currently based in the United States at Portland, Oregon.)*

Global Load Balancing for VNF’s and PaaS in a Largely Distributed Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AT&T is delivering its Network on Demand, by embracing Network functions virtualization (NFV) and software-defined networking (SDN).  As we learn to incorporate geographic redundancy across the VNF traffic, we quickly run into the lack of GSLB functionality inherently within OpenStack. The Kosmos project approach to GSLB , although promising doesn’t; seem to properly encapsulate the ability to incorporate existing solutions in the market. Organizations might  already be utilizing  an existing GSLB vendor. We need an approach that integrates GSLB seamlessly into the OpenStack ecosystem, and provide a simple mechanisms to integrate with existing solutions. We’ll review the proposed Kosmos architecture, how we leverage it, how we plan to implement the architecture at a regional or local level, and finally discuss our implementation and how it is been utilized to help improve the reliability of  our VNF’s and largely distributed PaaS applications.


* **Rodolfo Pacheco** *(Rodolfo Pacheco (rp2723@att.com) works at AT&T as the Leader of the AIC Design TEam , and as a   Cloud Architect helping build the AT&T AIC OpenStack Cloud. The foundational platform for AT&T’s Network On Demand platform.  Prior to that, he was the code Developer and Architect for the AT&T Netbond service.)*

* **Ganeshkumar Natarajan** *(Ganeshkumar Natarajan (ganeshkumar.natarajan@att.com) works at AT&T Inc. USA, as Principal Technical Architect. He is one of the lead Cloud solution architect currently working on ATT Integrated Cloud (AIC). AIC is AT&T's largest enterprise cloud built on Openstack that serves all AT&T traffic for mobility, IT workloads and Network Functions. His broad experience includes solution architecture, design, and development of the product all the way to production deployment.  Before AIC work, he was lead developer for ATT CDN Cache and Streaming platforms and has also successfully developed and deployed many Enterprise Android Mobile Cloud based application products for AT&T.)*

* **Ram Sateesh Talari** *(Works with AT&T as Development Lead for AIC DNSaaS and GSLBaaS Teams.  Is currently working on creating and implementing blueprints with openstack designate.  Previously worked with AIC DBaaS and was Developer for the AT&T CaaS platform.)*

Cockpit and OpenStack
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Some organizations need server admin interfaces for diverse reasons, currently there are lots of options but they all need some level of configuration, are too complex and/or use a considerable amount of resources. Cockpit is an interactive server admin interface. It comes “out of the box” ready for the admin to interact with the system immediately. It can manage multiple servers from a central interface with very little effort. Cockpit is a good choice for managing OpenStack nodes since it has nearly zero footprint, it starts on demand via socket activation and exits when not in use, leaving more system resources available for the OpenStack services. In this talk we'll address a proof of concept OpenStack multinode installation using Cockpit as the bare metal admin interface and compare its resource use with a TripleO installation.


* **Ivan Chavero** *(Iván Chavero wrote his first programs in BASIC at the age of 10, promoter and developer of free software since 1997, he is a systems engineer from the Autonomous University of Chihuahua where he spent over 15 years developing software and managing high availability systems, currently, he's a Senior software engineer at Red Hat working on the Cloud Engineering group. Iván, actively contributes to several open source projects mostly related to OpenStack and cloud computing. He is a founding member of the Chihuhaua's Linux user group and professor of the Masters in free software and mobile networks of the accounting and engineering faculties of the University of Chihuahua. When not taming computers or programming you can find him riding his skateboard in skateparks of his hometown Chihuahua or playing in bars of México or the US with his band Seis Pistos.)*

Adventures with Kolla
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

I've been using container technologies for 10 years so i'm always looking for ways to encapsulate applications, services or VPS, Kolla caught my eye because it provides production-ready containers and deployment tools for operating OpenStack clouds that are scalable, fast, reliable, and upgradable using community best practices. This talk is about the experience i had using Kolla in my personal server infrastructure, okay, okay, in the headless desktop systems i have inside my closet which i use to test and deploy OpenStack development and other stuff.


* **Ivan Chavero** *(Iván Chavero wrote his first programs in BASIC at the age of 10, promoter and developer of free software since 1997, he is a systems engineer from the Autonomous University of Chihuahua where he spent over 15 years developing software and managing high availability systems, currently, he's a Senior software engineer at Red Hat working on the Cloud Engineering group. Iván, actively contributes to several open source projects mostly related to OpenStack and cloud computing. He is a founding member of the Chihuhaua's Linux user group and professor of the Masters in free software and mobile networks of the accounting and engineering faculties of the University of Chihuahua. When not taming computers or programming you can find him riding his skateboard in skateparks of his hometown Chihuahua or playing in bars of México or the US with his band Seis Pistos.)*

Building better autoscaling applications
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While autoscaling is one of the most desired features for cloud native applications,the utilization of Cloudwatch or Ceilometer proved it underperforming, with longtimeouts that don't meet the user requirements and a metering architecture difficultto run efficiently on a large scale.Using the new features from Mitaka and the combination of projects like Monascafor instance monitoring, Heat for automation and Octavia for an elastic load balancerL7 Switching features, we can automate and scale our applications using real timealarm processing and proper load balancer integration. We can go further and once available, we will be able to provide self-healingbased on the Monasca-log-api alarms.In this session we will see how to build a production cloud application thatautoscales using Monasca alarms, Heat integration, Octavia load balancing andBarbican TLS support.


* **Damia Pastor** *(Damia started as a sysadmin for a project related to Swift (late 2011) to then switch to StackOps, one of the first OpenStack distributions to deliver and operate projects from Brussels to Manila. After being in Mirantis for both EMEA and APJ, moved to HPE professional services working in production projects and helping create new solutions.)*

* **Alejandro Tesch** *(Alex Tesch Alex has been working with Open Source enterprise technologies for the better part of his 15 years IT career in companies like Hewlett-Packard Enterprise, Red Hat, IBM and Sun Microsystems. He started his OpenStack journey with Grizzly, delivering the first HPC cloud in APAC for a Singapore University making use of SRIOV technologies combined with big data.  He has extensive deployment experience on configuration management and automation of private cloud based on OpenStack. Alex is currently an APJ Cloud Consultant in the Helion Cloud team at Hewlett-Packard Enterprise, where he evangelizes the OpenSource side of the Helion portfolio (OpenStack / Cloud Foundry / Ceph). He enjoys running automation workshops and seminars in the APJ region for cloud adopters. )*

Using Monitoring to Guide Migration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most cloud platform (and workload) migration stories start with expert knowledge (and surmise): about how apps work, how workloads are assembled, their dependencies, requirements and characteristics. But as cloud environments become more dynamic, apps and instances more numerous, and patterns of utilization more diverse, it makes sense to back up this technical understanding with empirical performance data and dependency analytics — to highlight candidates for migration, assist in migration planning, and provide performance baselines for predicting migration impacts. This is made possible by analytical monitoring tools that work across multiple cloud platforms, enabling parallel examination of multiple clusters, perhaps some remote and others local/on-premise — all through a single operator pane of glass. In this session, we'll present and demonstrate best-practice for using such tools to accelerate migration to OpenStack from other infrastructures.


* **John Jainschigg** *(John Jainschigg works with Mirantis broad partner ecosystem, promoting validation of new solutions with Mirantis OpenStack, and tracking emerging use-case and technology trends in areas like containers, PaaS, and hybrid cloud orchestration. He is a former software developer, virtual reality experience architect, Editor in Chief of Computer Telephony, Communications Convergence, and Online EIC of Dr. Dobb’s Journal.)*

* **Franz Karlsberger** *(Franz Karlsberger is Technical Director Alliances at Dynatrace. Franz combines deep expertise in cloud, data and information management solutions with significant knowledge of product strategy, professional services and alliances. Beside shaping new alliances he recently spends most of his time to define the right "Journey to the cloud" strategy for partners, customers and prospects. Before joining Dynatrace, Franz was working more than 10 years for Accenture a Global Management-, Technology- and Outsourcing Consulting company. He describes himself as Cosmopolitan – tech, history and sports enthusiast.)*

Designing  scalable and resilient  OpenStack deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalable OpenStack cloud deployment isn’t trivial and the unpredictable nature of public cloud workloads adds an extra layer of uncertainty. Enterprise OpenStack cloud deployments are expected to have qualities like high availability, scalability, performance gurantees and security inherent in their architecture.  If you are planning on deploying an OpenStack public cloud, how exactly can you architect your OpenStack components on the underlying infrastructure while maintaining zero down-time, performance guarantees, and tenant isolation at the same time? In this session, we take a peek into some of the specific requirements for OpenStack cloud architecture from our customers leading to some of the architecture design choices. We also discuss how converged infrastructure architecture can meet the above challenges.  


* **Amit Borulkar** *(Amit is a Technical Marketing Engineer with Converged Infrastructure Solutions at NetApp. He has a Masters degree in Computer Science from North Carolina State Univeristy. While at NC State, his research interests included distributed systems and cloud computing. At NetApp, he focusses on infrastructure automation and OpenStack reference architectures on FlexPod. In his spare time he enjoys cooking and hiking in the beautiful NC nature trails.)*

How best to deliver micro-services and Apps. using Kubernetes and Docker, as an OpenStack operator
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you and your Organization been evaluating OpenStack to help solve your business use-cases and application needs?  Somewhere along the way Docker and Kubernetes popped up on your horizon, and that got you pondering if you should be leveraging all or some of those options to deliver your apps effectively. If yes - then join us as we walk thru some viable options to enable Kubernetes and Docker to deliver apps. and services for your developers, users and tenants. Engage in a preemptive self-disruption exercise to better understand your OpenStack path going forward, as containers gain prominence. We’ll cover: Should you consider providing K8S clusters as an IaaS feature? Or is letting your cloud tenants  operate their own container layer a better architectural strategy? We’ll also discuss two architectural options:   Option(a) Delivering apps. and services w/ docker on bare metal versus option(b) Leveraging “Container ---> VM --> docker” for running your containerized workloads.


* **Amit Tank** *(Amit Tank is a Sr. Principal Cloud Architect with AT&T. He spends his time designing and building large scale cloud infrastructure, and leading projects and teams of technologists working towards putting OpenStack in production - while contributing the learnings back to the community. He enjoys helping enterprises, businesses and customers become fluent with OpenStack, Open Source, and Cloud skills and technologies within their organizations. Prior professional associations include several startups, DirecTV, Cisco, EMC, Hitachi, and Schindler among others.)*

* **Joseph Sandoval** *(Currently my role is Director, Cloud Engineering at Lithium Technologies (lithium.com) with 20 years experience with architecting, deploying and orchestrating in the datacenter and public cloud.   I've been involved with Openstack since 2012 and a operator since 2013. My current team has succesfully deployed Openstack to production to power Lithium Technologies SaaS. From my perspective I can help the community understand the challenges of running it at scale and guide other users who are undertaking this journey and the transformation learnings that it brings.    I'm also an organizer of the SF CloudOps meetup in San Franciso which is focused on helping other operators use devop tools and frameworks. Also as a under represented minority I'm very passionate supporting programs like code2040.org and the Telegraph Academy to increase the diversity in tech. )*

The Elephant in the Database: Keystone’s schema can’t scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The current Keystone database schema may suffice for 50 users across 10 projects, but it will break for any significantly large scale deployment. In this session, we will discuss the problems with the current schema, and offer a potential roadmap that would permanently solve these issues. * See what happens when we try to utilize 10,000 users, 1,000 projects, and 10 roles. * Hear what occurred in our production environment when table indices could no longer fit in memory. * Experience the significant scalability improvements Keystone could have with a simple schema change that can be implemented with little effort.  


* **Cristian Sava** *(Experienced Python Software Engineer. Currently working as Openstack Developer at Symantec. )*

Architectural Design considerations for Openstack planning
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Design an Openstack Cloud infrastructure is not a trivial task. There are so many variables to be considered that your choices must be cautiously made. Meet workloads/cloud users expectations should be the ultimate goal, while minimally considering high-availability, resiliency, robustness, application response time, latency, and overall performance. According to April's Openstack User Survey, the top 3 workloads for production environment are comprised of Software dev/test/QA and CI (44%), Infrastructure services (35%), and Web Services and e-commerce (29%). We will use a new open testing framework that we have developed to run on top of IaaS Business Critical Applications. We will explain how some choices can impact your Openstack Cloud infrastructure. We will walk you through our latest findings with regards to: * Different processors generations, and impacts on overall infrastructure * CEPH performance (Comparing HDDs and SSDs) * Memory, Network and Application level metrics


* **Marcelo Pinheiro** *(16 years in the IT field working in several initiatives and projects. Experience from Datacenter planning, operations, admin, team management and product and solutions development in these past years. Working relationship with multiple players such as: Intel, HP, IBM, Dell, Cisco, 3Com, Enterasys, Motorola, SonicWall, OS servers platforms: Linux, FreeBSD, Windows, Vmware and monitoring tools Nagios, Zenoss, Zabbix, etc. Openstack planning and deployment experience in private cloud POCs, and deployments different customers/partners. As a part-time job, I have 7+ years of teaching experience including CCNA, CCNA Security and CCNP @Networking Academies, Wireless, Computer Networks, Operating Systems, Security at different Universities (graduation and post graduation courses). Fluent in Portuguese(native), English and Spanish Currently, working at Intel Corporation as a Cloud Solutions Architect as part of Product Collaboration and Systems Division, under Data Center Engineering Group.)*

* **Patryk Wolsza** *(Patryk is a Data Center Architect in the Intel Cloud Platforms Group, with a focus on Software Defined Infrastructure. With more than 12 years of expertise in different virtualization and cloud platforms, Patryk has broad experience in cloud solutions, system designs, influencing data center designs and understanding connections between ordinary Data Centers, virtualization and SDI. He believes that mastering the purpose of existing cloud solutions is the key to deliver and maintain the complete product, hardware and software, for any demand.)*

Reconciling Infrastructure Limitations With Cloud Native & DevOps Challenges
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud-native applications and DevOps methodologies present big stressors for infrastructure designed and operated from a waterfall mindset. How do we change our infrastructure thinking to implement new ways of delivering software? In this panel discussion, we’ll look at what cloud-native (or cloud-first or next-generation) applications are all about, and why they are an important part of a modern enterprise’s transformation journey. Participants will learn about the key areas and challenges of infrastructure architecture, design and operations that must be examined when embracing these new models, including how failure is handled, resilience, API compatibility versus fidelity, etc.


* **Christopher Logan** *(Chris leads the practice for Application Modernization for EMC Global Services, primarily focused on Platform-as-a-Service, helping customers with Cloud Native adoption including infrastructure, app architecture, operations/governance and development processes.     Before joining EMC, Chris was lead app platform architect for The Walt Disney Company Parks and Resorts division, technical lead for the rewrite of the FBI’s NGI system at Lockheed Martin and lead architect for Iron Mountain Digital Archives.  Chris has a BS in Computer Science from the University of Illinois and is the co-inventor of two patents in the area of web application design.)*

* **Bart Driscoll** *(None)*

* **Ashish Nadkarni** *(Ashish Nadkarni is an Analyst and Research Director within IDC's worldwide infrastructure practice, which includes research on servers and operating environments, storage systems and software, and networking infrastructure for enterprise and cloud data centers.  As a part of IDC’s Storage, Ashish oversees research on software-defined storage, storage for Big Data and Analytics, Data Protection and Archiving, and Business Continuity and Disaster Recovery. He also participates in activities related to research on enterprise and cloud storage systems and software, software-defined infrastructure, infrastructure for and in the cloud. Ashish co-leads IDC's Global Overview program on Big Data and Analytics, one of the four pillar programs of IDC 3rd platform research agenda. This program tracks the infrastructure and software technologies associated with Big Data and Analytics. It also covers research on a wide range of related services, integration strategies, use cases, and go-to-market strategies.)*

Openstack in Containers
~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack has already been designed with microservices in mind and now the time has come to start using it as designed. Deploying openstack components within a microservice architecture framework will allow you to scale, recover from disasters, redeploy and upgrade with ease. Containerizing these micro services will allow you to test and even deploy from the latest and greatest code from community, such as new features can be thoroughly checked before being rolled out to your production cloud.


* **Cristian Sava** *(Experienced Python Software Engineer. Currently working as Openstack Developer at Symantec. )*

How to manager IoT/IIoT devices using OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There is no standard management software for IoT and IIoT devices.  OpenStack is the best choice.  However, OpenStack is not ground up built to manager IoT/IIoT devices.  IoT/IIoT devices requirements are different than conventional Virtual/Physical Computing devices.  What are the architectural, technical and business considerations come into play managing IoT/IIoT devices?  This panel discusses such details.


* **Chaitanya Kadiyala** *(Chaitanya Kadiyala is a Product Marketing Manager at Juniper Networks.)*

* **Ravi Jagannathan** *(Ravi Jagannathan has 25 years of Computer industry experience. As a MS Cybersecurity graduate of NSA program, currently he is focusing on developing and deploying high performance, secure cloud.   Ravi is a hands on coder and is a project-lead.  His interests are Cryptography, Virtualiation, Cloud, Cloud-security, Secure Boot, protecting assets in private/public/hybrid cloud. He works extensively with developers, customers, partners, and VCs providing mentorship and leadership as a project lead, hands on technical manager, and second-level manager.  He continues to code in various languages. He has worked across various organizations in proposing and successfully defining and delivering products.)*

Glare - a unified binary repository for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Glare (from GLance Artifact REpository) is a new service in the Glance project that provides a secure and customizable unified binary repository for OpenStack. The idea behind Glare is to allow various OpenStack services to catalog different objects they use to operate. Images used by Nova to run the VMs are just the best known examples of such objects; other examples include Heat templates, Tacker blueprints, Murano packages, and so on. Obviously, this functionality is common for different kinds of objects, and is usually unrelated to the primary mission of respective projects using these objects. That's why we implemented a dedicated service that will take care of managing various data assets in OpenStack clouds. The talk will describe how Glare helps to manage different artifacts across the cloud, how you can build your own private and secure catalog with artifacts for your service, what deployers need to know about the installation process, and what is coming in the future.


* **Mike Fedosin** *(Mike Fedosin is a full-time upstream OpenStack developer with more than 10 years of experience in Software Development in enterprise, scientific and open-source projects. He has the title of Ph.D. in the development of cloud service architectures. Being one of the core developers of Glance, Mike is driving a number of cross-project initiatives there, like adoption of Glance v2 API across OpenStack, and owning several other large features. Also, Mike leads project Glare, which provides secure and customizable unified binary repository for OpenStack.)*

* **Kairat Kushaev** *(Software Engineer in Mirantis)*

Software Defined Infrastructure (SDI) even for the under-cloud – is that even possible?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Think back when you could go online and custom order your Dell server, thus holding little inventory, assembling on the fly. Imagine a pool of disaggregated hardware from which nodes can be dynamically composed and attached to or detached from a cloud, customized to the workload. For instance, a node for storage would be composed with significantly more SSDs than one for compute intensive workloads. Introducing Intel Rack Scale Design Extensions via PodManager that implements the Redfish API. We highlight its abilities to compose, boot, monitor, power on and off and address current limitations such as VLAN creation via APIs without directly programming the TOR Switch. We share Dell’s solution which integrates this with Fuel, to deploy OpenStack. Lastly, we share our motivation to develop Plasma, working with deployment tools such as Fuel, TripleO, Juju, to realize the vision of SDI, dynamically grow and shrink clouds through plugins in Nova, Ironic, Horizon and policies in Congress


* **Mrittika Ganguli** *(Mrittika is a Principal Engineer and Platform Software Architect in Cloud Platform Group, DCG – India and has 19 years of experience.  At Intel, Mrittika has worked on software systems design, development and architecture. Her work includes building the server system management software architecture for cloud and server hardware deployment for cloud in datacenters. She has been involved in Openstack projects within Intel since 2010. She was a co-creator and architect for a Openstack based product for SLO management Intel(R) SAA. She has 5 patents granted and 5 filed and multiple published papers. Workload charetcerization, orchestration in clouds and disaggregated Rack architectures are her current areas of work.)*

* **Malini Bhandaru** *(Malini Bhandaru, Ph.D., Intel, is an Senior Software Architect  with the Open source Technology Center at Intel.  She has been involved with OpenStack for over three years.  Her interests span security, key management, access control, dynamic resource scheduling, network function virtualization, and scalability. She co-authored the “OpenStack Security Guide”. Prior to her open source cloud endeavors she worked on power and performance aspects on Intel’s Xeon server product line.  Before joining Intel, she worked at Nuance, Verizon, and several start-ups in Massachusetts. She has two patents granted and nine more filed. She has a Ph.D. in Artificial Intelligence from the University of Massachusetts, Amherst. She volunteers for science education activities and computer literacy. Through Intel she had the unique opportunity to develop and field trial in Bangladesh and India an Android application to assist farmers with their fertilizer needs. Malini lives in the Bay Area with her husband and sons, and enjoys gardening and hiking.)*

* **Alaa Yousif** *(Architect at DELL)*

Global name space of data between OpenStack, on premise and public cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hybrid cloud environments are real now. Enterprises are no longer sticking to a single cloud, they are opting for a hybrid approach of having a OpenStack private cloud and one or more public clouds. In this session we will showcase the scalable Veritas NAS solution that can manage data present in OpenStack, on premise and other public clouds using a single global namespace.  A single global namespace of OpenStack and on premise data greatly reduces complexities of data management and migration.


* **Sachin Lakhanpal** *(Highly Collaborative Engineering leader with 16 years mix of hands-on and leadership experience inmanaging Product Development, Quality (SW & HW) & Performance Engineering for Storage Managementfor On-prem and hybrid cloud Products. Leading Openstack communities of practice within Veritas Led Veritas engineers to make contributions to upstream projects. Leading development of Software defined storage platform and plugins for OpenStack. Led Veritas sponsorship and technical content submissions at the Austin summit. Co-presented Storage Multitenancy for OpenStack Brownbag session at the Austin summit with Abhijit Dey)*

* **sarat inuguri** *(Sarat is a principle software engineer working on Symantec storage NAS appliance product. He was part of Veritas File System development team prior to this. He has been working lately to integrate Symantec's NAS appliance with OpenStack Cinder and Manila.)*

Will The Real OpenStack Backup Solution Please Stand Up?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Compare & Contrast OpenStack BackUp Solutions: Raksha Freezer Dell EMC Red Hat Mirantis Ubuntu


* **David Lombardi** *(David is a manager within EMC's Global Technology Office.)*

* **Michelle Nguyen** *(Placeholder)*

* **Zach Wiseman** *(TBD)*

* **Thao Pham** *(TBD)*

* **Mark West** *(Mark West has been a software professional for over 15 years. He is currently a Principal Software Engineer and Architect leading OpenStack Data Protection design and development project at EMC.  Mark’s experience spans from IT Operation to Engineering Development specializing in cloud computing on Microsoft, VMware, and OpenStack platforms.  As an architect for OpenStack Data Protection, Mark has involved in various design discussions with large enterprises and service providers and has a deep understanding of many OpenStack deployments and their data protection needs.)*

Architectural considerations for big data workloads on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data intensive big data applications such as Kafka, Hadoop, and NoSQL are increasingly common in the modern data center, and now more than ever are being deployed at scale in OpenStack cloud environments. The performance demands placed on cloud infrastructure can be extreme, and in shared environment can often result in resource contention or outright stravation. This requires cloud infrastructure architected to support the diverse sets of requirements of these applications. In this talk we discuss considerations and approaches for handling the requirements of data intensive big data workloads in OpenStack such as: Defining big data workload applications proflies Architecting for high performance workloads Synthetic workload and full stack application testing


* **Christopher Power** *(Chris is a Principal Engineer at Comcast, where he is responsible for the architecture definition and implementation of scalable big data platforms and cloud infrastructure for Comcast's Elastic Cloud OpenStack environment. Most recently his work has been focused on architecting cloud infrastructure that is application aware by understanding the diverse demands that high performance systems such as Kafka, NoSQL, and Hadoop place on cloud infrastructure, and exploring different architectural and technical solutions to addressing these requirements. His previous work in this space involved deployment of Hadoop clusters at scale on OpenStack using Swift as the primary data store, including optimizations to the Hadoop-SwiftFS driver, and performance testing to evaluate various architectures. With over fifteen years of experience as a technology, product, and services leader in the telecommunications, mobile supply chain, consumer internet, and financial services industries, his previous roles include Director of Product Management where he was responsible for defining and executing product and technical strategy, Director of Professional Services where he was director and technical architect with P&L responsibility, numerous roles in software development, and a former member of the teaching staff for Harvard's CS50 Introduction to Computer Science course.)*

* **Andrew Leamon** *(Drew Leamon started his career at Microsoft while studying Computer Science at Princeton University.   In his studies, he delved into Computer Graphics, Artificial Intelligence and Computational Neurobiology.  At Microsoft, he collaborated with Microsoft Research on one of the first commercial implementations of collaborative filtering for e-commerce.  This was released as Microsoft Site Server: Commerce Edition.  Graduating into the DotCom boom, Drew caught the entrepreneurial spirit of the time and went on to sell cars on the internet through CarOrder.com, a Trilogy Software spin-off.   While there, he created new ways to sell content online through innovative configuration solutions.  Next Drew became one of the charter members of AirClic where he helped to create a platform to support workforce automation using wireless technologies.  Drew’s work and IP in this space became core to the company’s business value.   At Traffic.com / Navteq / Nokia, Drew pioneered the visualization of traffic data collected from highway sensors and digital probe devices.  Moving on to Comcast, Drew has taken his diverse experience and background and now leads part of the Engineering Analysis organization.  His team is developing advanced data visualizations for network data.  They are building elastically scaling Big Data infrastructure to support Analytic workloads.  Simulations of Comcast’s CDNs and platforms, developed by Drew’s team, are leveraging this platform and guiding the business and engineering teams.   His team is identifying high ROI opportunities.  They apply machine learning to datasets and are currently operationalizing the resulting predictive models to help improve customer experience.)*

Liberate your CloudFoundry installation from being constrained to a single cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud Infrastructure components are here to fail, while your service – in our case your cloud foundry installation – is here to stay available and keeps the hosted applications running. How do you stay available, while whole clouds are going down, either for maintenance or due to failure? At Swisscom we think that cloud infrastructure should be kept as simple as possible, meaning that it is here to deliver a platform that enables rapid delivery and deployment of cloud-native workload. Such a simplicity means that we keep a single stack to a single region and a single availability zone and for example do not stretch shared storage over two sites. However, what matters is that in the end users would still like to access their service running on top of Cloud Foundry and also the platform to deploy new applications should stay alive.


* **Marcel Haerry** *(Marcel Haerry is leading the architecture of Swisscom's OpenStack based environments. With the goal of providing an elastic environment for modern platforms, such as PaaS based on CloudFoundry. Having both a system and software engineering background and years of participation within devops-minded community (e.g. Puppet), he is seeking for an automated and continuously integrated delivery of operational platforms.)*
