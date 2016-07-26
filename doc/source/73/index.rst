Storage
=======

Running Cinder in Docker
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will give an overview of Cinder architecture with specifics of its implementation in Docker containers environment, highlightes encountered issues and solutions during the development process. It also includes a demonstration of launching an instance in Kolla/Docker environment using LVM2/iSCSI backend for cinder storage.  This session will provide basic diagnostics and troubleshooting tips. 


* **Serguei Bezverkhi** *(Born in Russia, moved to Canada in 1996, living in Montreal since. Working for Cisco for past 10 years supporting major service provider in Canada. Getting involved with OpenStack about 3 years ago and starting operating and developing for OpenStack, specifically for Kolla project.)*

* **John Griffith** *(John Griffith, Senior Software Engineer at SolidFire, helped to create the Cinder project in OpenStack.  His primary responsibility at SolidFire is technical contributor to OpenStack.  He served as Technical Lead for the Block Storage Project since it's beginning through the Juno release, and also holds an elected seat on the OpenStack Technical Committee. John has over fifteen years of engineering experience in both hardware and software engineering.  He’s been an active user and contributor to open source for close to a decade, and has been focused on OpenStack since January of 2011. In addition to his technical contributions, John also spends a lot of his time talking to people who are interested in learning about OpenStack as well as gathering feedback from current users.)*

Manila Share Groups - How, What, and Why
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Manila has developed "share groups", a generic grouping construct that, like individual shared filesystems, is an atomic data type.  Building on our experience with consistency groups in both Manila and Cinder, "share groups" provide a more consistent user experience, simplify management of cloud applications, and can serve a much broader set of use cases such as group-based replication, migration, cloning and backup.


* **Alex Meade** *(Alex has been developing across various projects in OpenStack since the Cactus release in 2011. Alex has a wide breadth of OpenStack experience having been a top commiter in Nova, a core member of Glance, and key operator of the Rackspace Public Cloud. Currently, he focuses on solidifying Cinder and Manila as enterprise ready projects.)*

* **Clinton Knight** *(Clinton has worked in enterprise storage management since 1999 and joined the OpenStack phenomenon in 2014.  He is a core reviewer on Manila and helps maintain the NetApp drivers for Manila and Cinder.)*

Store All The Things: An overview of storage options for your OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Join the PTLs of Swift, Cinder, and Manila for an overview of OpenStack storage. From block, file, and object storage, learn about the various use cases for each and considerations on why and where you would want to use each for different scenarios.


* **Sean McGinnis** *(Sean McGinnis is a software architect and project lead with the Dell Storage group. He focuses on enabling integration of Dell Storage capabilities with external systems to streamline the ease of use and availability of the various Dell storage offerings to meet application needs.)*

* **John Dickinson** *(John Dickinson is Director of Technology at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Object Storage. John serves as the Project Technical Lead for OpenStack Swift and has been involved in the development of Swift since 2009)*

* **Ben Swartzlander** *(Ben Swartzlander is the PTL of the Manila program within OpenStack. He is a member of technical staff at NetApp, where he focuses on OpenStack.)*

Enabling a Policy-Driven, Self-Service storage provisioning control plane for a Service Provider 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Storage self-service is one of the important tenets of modernizing IT. Storage provisioning typically takes days to weeks time due to the complex approval processes and application requirements getting translated into storage capabilities. Service providers aim to achieve agility, operational efficiency and improved service levels by allowing application and server teams to provision their own storage, on-demand. It allows the storage team to free up critical resources and improves operational efficiency, while maintaining IT control via policies to avoid any erroneous self-service errors.In this talk we present how we have used Openstack successfully to enable self servicing and API based automated storage provisioning for one of the largest service provider (IBM Global Technology Services). We will share the lessons learnt from the perspective of IT service provider and many customers across the globe on what has worked well vs what did not work as expected.


* **Rakesh Jain** *(Rakesh Jain is a Research Engineer with IBM Research. He is currently working in implementing automation and self-service capabilities using Openstack in IBM's Global Technology Service division, one of the biggest IT service provider, focused on block storage aspects. He has also been involved in the development of IBM's storage management and monitoring products, as well as storage management for IBM Cloud. He has over fifteen years of experience in software development and architecture with focus on systems management, optimization through analytics and automation.)*

* **Ramani Routray** *(Ramani Routray is a senior researcher and manager of Cloud Systems Analytics group at IBM Research with over 17 years of technical experience. In his role, Ramani continues to invent, design and transform next generation data center solutions ranging from cutting-edge underpinning cloud technology, such as Software Defined Storage, Container, IBM Cloud Managed Services (CMS) API economy, Hybrid Cloud Design, to innovative cloud management platforms using advanced big data analytics technologies, such as Hadoop, Spark, NoSQL, and scalable machine learning platforms. The essence of these solutions lies in the unique integration of data science with domain-specific applications on large scale cloud system analytics paradigm. Ramani has made significant impact by architecting and implementing key components of the IBM Spectrum Control, IBM Cloud platform (CMS) and IBM Services Delivery framework. He leads technical teams, works with architects, strategists across brand (Systems, Software and Services) within IBM and with Strategic Outsourcing clients. Ramani has been awarded one IBM Corporate Award, CEO's Best-of-IBM Award, five Outstanding Technical Achievement Awards , two Research Division Awards, multiple publication awards. He has published over 30 papers in key conferences, IBM Master Inventor - submitted 64 patent applications out of which 28 have been granted by USPTO. Ramani collaborates with universities, standards (DMTF/SNIA/..), OpenStack and works on IBM task forces.)*

Smaug - An ecosystem for Data Protection Providers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Smaug is a new OpenStack Big Tent project, focused on protecting the Data and Metadata that comprises an OpenStack-deployed Application against loss/damage (e.g. backup, replication) by providing a standard framework of APIs and services that allows vendors to provide plugins through a unified interface. In this talk, we will present Smaug's vision of an ecosystem for data protection providers, using Smaug to orchestrate backup and restore providers. We will also show how Smaug can be used inside a Disaster Recovery vendor's stack.


* **Eshed Gal-Or** *(I'm an avid technologist, innovation leader and problem solver, with 20 years of R&D experience in diverse domains, such as networking, virtualization, telecom, BSS, IT infrastructure, cloud and security. As an architect, I'm practiced at setting and realizing technology vision and roadmap in highly complex global organizations, while crossing between business/product management and technical research/development teams. I currently manage a team of open source developers and PTLs in Huawei, focusing mainly on 3 OpenStack Big Tent projects: Dragonflow, Smaug and Kuryr  )*

Protecting File Shares in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data protection is a vital requirement for any enterprise. No one likes to be caught off guard when the power goes out or the storage array goes off-line. Hence, choosing the right backup solution is critical in today's make-or-break economy. This is why Manila's storage backend replication capabilities are of critical importance! Not only do they allow OpenStack clouds to offer Shared File System based replication, but also enable users to achieve fail-over and fail-back. However, there are other potential solutions. We will discuss additional ways to achieve data protection for shared file systems, and explain how they work. We will demonstrate these alternatives, and try to fit them into use-cases that they are most suitable for:  Manila with a 3rd party backend driver Manila with Smaug and storage strategies Manila with Smaug and Swift Manila with Smaug, Swift, and Neutron (protecting both share data and share network) Freezer: The OpenStack Back-up as a Service Platform


* **zhong jun** *(ZhongJun is a senior engineer from Huawei. He has expertise in Linux, storage, data protection related experience, cloud and virtualization technologies. ZhongJun has been an OpenStack contributor since the Kilo release and work in Manila, Cinder.  )*

* **ying chen** *(Ying Chen is a senior engineer from Huawei. He has expertise in Linux kernel, storage, cloud and virtualization technologies. Ying Chen has been an OpenStack contributor since the Kilo release and is a core member in Smaug.)*

* **Sumit  Kumar** *(Sumit earned his bachelor's degree in Computer Engineering from Virginia Tech in May 2015. He then joined NetApp as a Technical Marketing Engineer, and has been involved with OpenStack since. He has been an active participant in various Openstack meetups, and has presented sessions on various topics on Openstack forums. He is very excited about the future and potential of OpenStack, and looks forward to contributing to the OpenStack community.)*

Building reliable Ceph clusters
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph is the most popular Software-Defined-Storage technology used with OpenStack. It enables a multitude of block, object, and file storage use cases, and its flexibility allows it to be configured as required for many different scenarios. The hardware environment can be similarly tailored. This is a sizable decision matrix, but leads to an environment optimally tuned for the required balance between performance, functionality, and cost. Dependability aspects - availability and reliability in particular - are often overlooked. Based on twenty years of development and hands-on experience with designing dependable distributed systems and supporting them in production, the goal of this presentation is to make you confident in your choice of Ceph for your use case, and to build an architecture you can trust. Beginning with choosing the appropriate access method for your workload, we then continue to introduce the algorithms and technologies in Ceph as they relate to resilience and High-Availability. We will discuss the considerations involved in optimizing a distributed storage system for reliability, availability, and durability of data and fault tolerance. We will look at the performance of Ceph in degraded and recovery scenarios, and how to reduce exposure. This affects the choice of hardware, the approach to feature selection, and system architecture. We will also talk about operational procedures to reduce unplanned downtime, speed-up recovery, and improve supportability.


* **Lars Marowsky-Brée** *(Lars serves as architect for Software-Defined-Storage at SUSE, focused on Ceph. He represents SUSE on the Ceph Advisory Board as a founding member, and is a frequent invited speaker. Since joining S.u.S.E. in March 2000, his previous roles include senior consultant, kernel engineer, engineering manager in SUSE Labs, and he is most known for his work on the Linux High-Availability stack and distributed systems engineering. He was named Distinguished Engineer in 2012. He holds an MSc from the University of Liverpool. He moved to Berlin in 2014. He wears black.)*

Doppelgänger - Towards Disaster Recovery Support in Ceph
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph is a highly scalable distributed storage system and the heart of SUSE's software defined storage solution. Ceph clusters are usually deployed in single site. Although a multi-site configuration is also possible, it may hurt the overall performance due to the conjunction of strong consistency and high-latency channels. Disaster recovery (DR) is an imperative feature for maintaining critical data safe. In the newest version of Ceph (codename Jewel), a solution for disaster recovery support was designed and implemented for the block device interface, and named as RBD Mirroring. The approach to support DR is based on the asynchronous propagation of block device operations to a remote (geo-distant) site. By being asynchronous, the operation mirroring does not interfere with the critical path of the primary site functioning, and thus the performance penalty becomes negligible.


* **Ricardo Dias** *(Ricardo Dias is currently a senior software engineer at SUSE Enterprise Storage Team working in the development of Ceph a distributed storage solution. Previously, he was a researcher in the areas of concurrent programming and distributed systems, published several scientific papers, and received a doctoral degree from NOVA University of Lisbon.)*

Troubleshooting Ceph in the Field
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So you have a Ceph cluster that suddenly starts misbehaving, and want to get the cluster back to a healthy state as soon as possible. Sure, Ceph's health details will spit out a bunch of information: "some pgs are degraded", "a few operations are blocked", "oops, an OSD is down!". What can you do when the alarm bells start ringing? During this talk we'll walk you through the steps to be taken in various situations, from understanding some basic error messages, to setting the appropriate debug levels and looking for the right messages to fully understand what is wrong with your cluster.


* **Joao Eduardo Luis** *(Joao has been involved in Ceph since early 2012, mostly working on the monitors. Soon after finishing his MSc in Computer Science, Joao started working remotely for Inktank - a Los Angeles based startup focused on developing and providing enterprise support for Ceph. After a brief stay at Red Hat, Joao joined the SUSE storage team in early 2015, where he has been branching out from his comfort zone on the Ceph monitors to other components of Ceph.)*

OpenStack Swift: Say hello to object storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Swift object storage is designed to scale on commodity or enterprise hardware. Swift enables data to be stored efficiently and cheaply. Accessing the stored data has become a major problem as everyone wants the data to be highly available across platforms and from their devices. Swift answers this need consistently and safely with Representational State Transfer (ReST) APIs.In this session, we’ll show that Swift is a long-term storage system with scalability, redundancy, and permanence. We’ll demonstrate how it stores data in an object form and how object replications work. We’ll also discuss Swift object versioning, which allows object/data archival. Its storage policies enable different storage implementations, like selecting different physical servers or disk as needed. In this presentation, you’ll see object versioning, access control, and storage policies in action.


* **Sachin Patil** *(Sachin works at Red Hat and is passionate about Open source & avid GNU Emacs user. He likes to talk and write about open source, GNU/Linux, Git, and Python. He recently got interested in Swift Object Storage. He can be reached on IRC as psachin@{REDHAT, Freenode, OFTC}. He blogs at http://psachin.github.io)*

Beyond Object Storage - A Unified storage Architecture for IoT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the immense growth of connected devices across multiple industry verticals in recent times, Internet of Things (IoT) platforms gained huge focus across various organisations. As volume, velocity of data generated by the IoT devices are massive, there exists a need for scalable, faster, analytic, internet friendly storage. Even though we are in early stages of IoT wave there exists multiple frameworks (centralized vs. decentalized), prototypes in market today. However with the maturity of IoT workloads, openstack swift architecture as a sole does not meet the growing requirements of IoT data. The proposed presentation discusses in detail various design issues and nuances associated with object storage serving IoT workload and presents different features, approaches to solve them by leveraging a massively scalable, parallel, n unified clustered file and object storage architecture.


* **Sasikanth Eda** *(Sasikanth Eda is a Software Engineer with the IBM Spectrum Scale development team. He works for the integration of OpenStack with Spectrum Scale, focusing on Swift object, Cinder block and Manila file storage components of OpenStack.)*

* **Simon Lorenz** *(Simon Lorenz is an IT Architect in IBM Research and Development Germany. Hejoined IBM Germany in 1993 and worked on productivity and manufacturing qualityimprovements within IBM Disk Drive Manufacturing Management software. Duringinternational assignments, he helped to improve fully automated chip factories in the US andAsia. Simon has held various positions within IBM Research and Development. Since 2009,he has worked on Storage Systems Management software and has been responsible forsubcomponents, such as system health reporting, cluster configuration management, andrecovery. Simon joined the IBM Spectrum Scale (built upon IBM GPFS) development team in 2014 and works on the integration of Openstack with Spectrum Scale.)*

* **Sandeep Patil** *(Sandeep Ramesh Patil works as a storage cloud architect with IBM labs and has over 15 years of extensive product architecture and design experience. Sandeep is IBM Master Inventor with over 150+ US patent filings in the field of storage cloud, security, filesystem, etc and is among the leading inventors in India in the mentioned field. Sandeep has authored numerous articles and paper publications in the filed of computer science with subjects over security, storage clouds, etc and has presented in various international conferences across the world.)*

are we ready for "file service" in public cloud with OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the public cloud, what should we do if we want supply file service. Is that the same thing as what we did in private cloud or there are security solutions we should think about.


* **Tao Bai** *(Over 12 years on IT software design and development. 3 years Cinder development and contribution.  Right now, working in Huawei Company as OpenStack Architect in the private cloud and public cloud domain. Responsible for Cinder, Manila development and an opensource software-defined storage controller , data protection in public cloud and private cloud domain.)*

The Roadmap to Cohesive Data Protection in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data protection solutions differ from each other in many aspects: backup versus replication, on and off premise, hardware or software based, agent or agentless, cost, etc.  Furthermore, different resources in the organization have different requirements for data protection. OpenStack Smaug glues together OpenStack resources and data protection solutions (existing or new), and then provides a homogenous interface for a variety of protection plans, satisfying the most rigorous enterprise requirements.


* **Yuval Brik** *(I’m an avid Open Source software engineer with focus on Cloud, Security, and Storage. I've been contributing independently to Node.js, libuv, and currently a core contributor for Huawei in designing and developing OpenStack Smaug - Application Data Protection as a Service.)*

Why do we like distributed storage backends more
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

More and more company starts to build IT system with virtualization and cloud computing technology, storage system has met more severe challenge. E.g. storage system need undertake more business. It should have higher performance, reliability and expansibility. Meanwhile cutting the cost, it should also keep the QoS level.Distributed storage backends have obvious advantage in performance comparing to ipsan storage backend, thus have attracted lots of attention from both vendors and users. Currently there are serveral distributed storage drivers available in cinder: EMC, VMware, netapp, ceph, hitachi, etc and the newly added FusionStorage. What's their pros and cons? What distinct feature do they have?In this topic, we will have a deepdive into the most common distributed storage backends in Cinder, disuss how downstream driver can help OpenStack become more secussful, moreover, we will share our experience of intergrate OpenStack with some of the distributed storage drivers.


* **Xiyuan Wang** *(Xiyuan Wang joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Zaqar, Glance and Cinder. He is one of the zaqar core members.)*

* **Zhenyu Zheng** *(Zhenyu Zheng joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Nova, Searchlight.)*

* **Duncan Thomas** *(Involved in Openstack since Cactus, and large HPC systems as adeveloper and admin before that. Worked on one of the first large Openstackpublic clouds, and one of the founding members of the Cinder team.)*

Sheepdog: an alternative software-defined storage on your OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Sheepdog is an open-source distributed storage system that can be integrated with OpenStack as Cinder/Glance backends. It is installed into commodity Linux servers to provide a scalable, reliable and manageable storage pool consisting of internal disk drives. It can run on not only dedicated servers but also Nova Compute ones so as to deploy hyper-converged infrastructure. With Sheepdog, you can launch your own cloud storage small then scale it out flexibly to fit your business growth. This talk will present how to use Sheepdog as Cinder/Glance backends, beginning with minimal installation then extending it. It will also cover recent topics in development and use cases. This introduction is good for attendees who find another way to build your own cloud storage.


* **Takashi Menjo** *(Researcher at Nippon Telegraph and Telephone Corporation)*

openATTIC: Managing Ceph and Storage with Linux and Open Source Software
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

openATTIC is a comprehensive open source storage management solution with a clean and intuitive web-based user interface.Under development for more than 5 years, it is based on a modern and extensible architecture built with proven web technologies and frameworks like Django, AngularJS and Bootstrap.It supports a wide range of storage technologies, both file- and block-based, e.g. NFS, CIFS, iSCSI and FibreChannel.In order to provide a scale out storage option, the development of Ceph management and monitoring support was begun in early 2015, now supporting a cluster status dashboard, options to manage and monitor Ceph pools, RBDs and OSDs.More functionality is planned and under development.All functionality is available via a web interface and RESTful APIs through a common backend.The development takes place in the open, with a strong focus on early community involvement.


* **Lars Marowsky-Brée** *(Lars serves as architect for Software-Defined-Storage at SUSE, focused on Ceph. He represents SUSE on the Ceph Advisory Board as a founding member, and is a frequent invited speaker. Since joining S.u.S.E. in March 2000, his previous roles include senior consultant, kernel engineer, engineering manager in SUSE Labs, and he is most known for his work on the Linux High-Availability stack and distributed systems engineering. He was named Distinguished Engineer in 2012. He holds an MSc from the University of Liverpool. He moved to Berlin in 2014. He wears black.)*

* **Kai Wagner** *(Im part of the openATTIC team. We´re building an Open Source Storage Solution for local storage and ceph management. Ceph is the first choice for OpenStack. That's one of the reasons why we're developing the ceph managemnt within openATTIC. Ceph should be trivial to everyone - specially for OpenStack users.)*

Cinder Backup
~~~~~~~~~~~~~

**Abstract:**

Cinder Backup process


* **Sheel Rana** *(Sheel has experience of 6+ years in storage and telecom domain. Currently working as OpenStack developer and added some functionalities to cinder project recently. )*

* **Lisa Li** *(Lisa has about 10 years' experiences in block storage and has proved background on disaster recovery. From Liberty she starts to work on Cinder project, and continues working on improving backup service.   )*

Running Manila at Scale: How SAP Hosts In-memory Databases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will cover the usage of Manila for high-end enterprise application like in-memory databases. It will start the first challenge: the data center deployment, where we used OpenStack Kolla and Kubernetes. Many storage backeds in manila only supporting 4096 (VLAN limit) networks which is one issue we solved with multi-segment hierarchical port binding. Here we will cover in-depths how full network automation in manila works and how also such complex network topologies can be supported. We will discuss in details about the current state of active-active HA and missing features and how we want to address them.


* **Marc Koderer** *(Active contribuiter since 2013 with the focus on storage and QA for enterprise usage. Part of the OpenStack cloud inititive at SAP.)*

* **Bernd Herth** *(Focus on cloud infrastructure architecture for Enterprise applications. )*

Crystal: Open and Extensible Software-Defined Storage for OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Crystal is the first open and extensible Software-Defined Storage architecture for OpenStack Swift. Crystal provides simplified policy-based storage management to system administrators in a "If-This-Then-That" (IFTTT). These policies can change the behavior of  the system by transparently intercepting object requests with storage transformations or filters ("That"). The enforcement of filters may be static or dynamic based on monitoring metrics ("This"). Crystal's dashboard extends Horizon for enabling administrators to write policies and monitor the system. Crystal integrates several storage filters and monitoring metrics that demonstrate its feasibility. For instance, Crystal handles policies that enforce data compression or caching on object requests based on a container's activity, or it can enforce multi-tenant bandwidth differentiation. Moreover, both storage filters and inspection metrics can be plugged-in at runtime to extend the system's capabilities in a transparent manner.


* **Raúl Gracia-Tinedo** *(Raúl Gracia-Tinedo received his M.Sc. in Computer Engineering and Security in 2011 and his Ph.D. in Computer Engineering in 2015 with distinction grade, both at the Universitat Rovira i Virgili (URV). During his PhD, he worked at IBM Research (Haifa) and Tel-Aviv University under the supervision of Dalit Naor and Sivan Toledo, respectively. He is currently a postdoc in the Architectures and Telematic Services research group at URV. His research interests include distributed storage management, cloud computing and performance evaluation of systems, with more than 15 papers. He received the Best Dataset Award at ACM Sigcomm IMC’15. He has actively participated in EU research projects (FP7-CloudSpaces and H2020-IOStack). Contact him at raul.gracia@urv.cat.)*

* **Pedro Garcia Lopez** *(Pedro García-López is a professor in the Computer Engineering and Mathematics Department at URV, where he also leads the Architectures and Telematic Services Research Group. His research interests include distributed systems, peer-to-peer systems, cloud storage, software architectures, and middleware and collaborative environments. García-López has a PhD in computer science from University of Murcia. Contact him at pedro.garcia@urv.cat.)*

* **Yosef Moatti** *(Yosef Moatti is a member of the research staff at IBM Research–Haifa, Israel. His research interests include Big Data analytics and storage frameworks. Moatti has a doctorate in computer science from Télécom ParisTech.)*

Building a Highly Available OpenStack Storage Solutions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data availability is just as important as data reliability.. if you cant get to it then you might as well not have it!  Deploying a storage solution for Cinder, Swift, Manila and even just standard user data with Openstack has to include a level of availability both from a single site perspective as well as a multi-site perspectives.  This session dives into options available for storage in from the block side with scale up options in single and multi-site solutions, scale out options for object storage as well as the backend storage needed for services like Manila.  The types of storage today will be detailed and where each type fits will be shown.


* **Michael Letschin** *(Michael Letschin has more than 15 years of experience in the IT industry, ranging from Systems Engineer to IT Director. Most recently, he has held roles as Sales Engineer and now as Field Chief Technology Officer at Nexenta Systems, a software-defined storage company. He received an MBA from Mount Saint Mary's University and has technical certifications from multiple storage and virtualization vendors. He was awarded the VMware vExpert award for the past four years for his work on his blog (thesolutionsarchitect.net), on social media (@mletschin) and in the IT community as a whole. He has continued this community support through speaking engagements at numerous conferences including VMworld and SNIA shows among others, he has also recently began the Inside Software-Defined Everything blog on ComputerWorld.)*

Forget everything you knew about Swift Rings - here's everything you need to know about Swift Rings
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Swift is designed to make the most durable and available object storage system possible from your commodity hardware. From a few terabytes to dozens of petabytes and beyond Swift uses a consistent hashing ring to ensure data storage locations are dispersed to ensure failure-resistant operations of your clusters running at scale. Swift operators are ring masters. They interact with them constantly to maintain order in their clusters, adding new capacity to power their growing cloud, removing or replacing old and busted disks and nodes, or creating new powerful differentiated storage offerings based on their clusters unique characteristics, geography or features. In this talk we want to give you a deep dive into the rings: low level details how initial placement and rebalance works, best practices when designing cluster topology and ring management, and what you need to know about recent and upcoming changes like overloading, increasing partition power and composite rings.


* **Christian Schwede** *(Christian started working on Swift four years ago and works as a Principal Software Engineer at Red Hat. Most of his Swift related work is related to supporting customers running Swift and working on automation, testing and development tools.)*

* **Clay Gerrard** *(Clay Gerrard is a Sr. Software Engineer at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Clay was part of the original development team at Rackspace that created Rackspace Files, which became the Swift project within OpenStack when it was made open source. Clay has continued to be active in the OpenStack community as a contributor to the Swift project.)*

Openstack swift object storage simulator for scale test using Containers/VMs.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack Swift has ability to scale to a huge object store but to test this with large no of physical nodes can leads to a higher cost constraints. In order to overcome the dependency on the physical nodes and HDD to configure Swift we deployed Swift proxy and object nodes on VMs/containers running on any hypervisor/docker-host. Thus we can have a large number of proxy and object nodes having required no. of virtual disk drives (by adding external storage from any storage array to the hypervisor/host ) to meet a scale of required object storage. We will cover the following:• How to deploy and configure proxy and object node as a VM/container• How to clone that VM to create required number of proxy and object nodes.• How many proxy and object nodes on a single baremetal hardware can be deployed and cost savings• Automation to deploy swift services on cloned VMs – Deploy hundreds of swift nodes within minutes• Test results and comparisons with physical nodes.


* **Ankit Goel** *(I am working as test engineer in Helion openstack on swift scale (Object storage)  )*

* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*

* **Raja Sekhar Reddy Juturu** *(I am a QA in HPE working on Helion openstack career grade and telecomm.solutions.)*

“Hello Smaug!” – An Introduction
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Smaug is a new OpenStack Big Tent project, which provides a set of APIs and an service framework for orchestrating data protection and restore functions.  It allows OpenStack users to use Cinder backup capabilities to meet business use cases, by creating protection plans that cover various resource types, such as volumes, virtual machines, networks, as well as extend to handle custom entities.  Its pluggable architecture enables 3rd party software vendors to integrate proprietary and commercial protection services to offer additional features to the user. In this session we will have an introductory tutorial about Smaug, explore its architecture and inner-workings, how it is deployed, and how it can work with other OpenStack projects, such as Cinder, Nova, Swift, Freezer and Manila.


* **zhonghua li** *(Senior System Engineer - Cloud and Open Source,Huawei Zhonghua has nearly 10 years of R&D and Product experience in multiple fields, such as Big Data Analytics, Storage, NAS, SAN, virtualization, cloud and so on. He is currently in charge of Open Source in Huawei, managing a research team of open source with several engineers, leading members to take part in several projects e.g. Cinder,Manila,Swift,Smaug,Murano and so on, developing in Openstack and leading the open source especially in storage domain. In the community Zhonghua has led the design of Smaug. Prior to Huawei, Zhonghua worked in Big Data Analytics, dealing with Business Intelligence)*

Building  high performance OpenStack storage solution with NVMe SSD and Intel® Optane™ technology
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In order to provide reliable, high-performance, on-demand, cost effective storage for applications hosted on servers, more and more cloud providers and customers are extend their storage to include Solid State drive (SSD).  In this session, you will learn about how to build Ceph based OpenStack storage solutions with today’s SSD as well as future Intel® Optane™ technology, we will Present two reference architects and data of all SSD Ceph cluster that can deliver greater than 1 million IOPS for the performance intensive environment - providing a more cost effective solution than today’s HDD cluster.   Share “good/better/best” system configurations and performance optimization best known methods, and share early Ceph BlueStore performance results with all SSD configuration Discuss future Ceph architectures using next generation Intel® Optane™ technology, including proposals of OpenStack Ceph hyper-converged solutions based on Intel® Optane™ technology


* **Jian Zhang** *(Jian Zhang is a senior software engineer of the Cloud Storage Engineer group from Intel Asia Pacific Research & Development Ltd. The team focus developing and optimizing opensource cloud storage architecture and solutions based on Intel platforms. The team is No.2 code contributor in Ceph, contribued to many core features like Cache tiering, Erasure coding, Rados I/O Hint, and BlueStore. They orgznied and hosted the Beijing and Shanghai Ceph Day together with Redhat. They also work very closely with China customer to build Ceph based Server Based storate POCs solutions.  Jian has 9 years of software development, performance analysis, optimization and tuning experiences in open source software, including in Xen, KVM, Openstack, Ceph, Swift.   Jian has a master's degree in Comuter Science and Engineering.    )*

Ceph Performance on OpenStack Based On Over 25000 Benchmarks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalability is key for most OpenStack users. In particular being able to scale SDS without performance degradation is central part of that discussion. Join this session to learn how to avoid performance bottlenecks while using Ceph as block storage with OpenStack. In this session we will share our results from evaluating Ceph with OpenStack, including design points and the results of over 25,000 separate benchmark tests. Purpose and detail of evaluation Benchmark results (Summary of over 25,000 times benchmark!) Bottleneck analysis (ex. SSD journal sync interval) Design points (including new Ceph backend "BlueStore") This session will be held by Open Standard Cloud Association (OSCA). OSCA was established in February 2012 as a promoter of cloud computing solutions in Japan from both technical and business perspectives.


* **Takehiro Kudou** *(Takehiro is a Lead Engineer at Hitachi Solutions. He has about 10 years experience in finding and evaluating new technologies best for enterprise users. The theme he is currently most interested in is OpenStack related SDN/SDS projects and technology ecosystem.He is also active as following roles.- Organizing committee member in OpenStack Days Tokyo.- Technical leader in Open Standard Cloud Association(OSCA) Technical Review Committee.- OpenStack mentor in Okinawa Open Laboratory specialist training program.)*

* **Takanori Suzuki** *(Takanori Suzuki is a network product technologist at Dell Networking team in APJ. His team is focuses on OpenNetworking, it brings more open ecosystem in the networking industry like a server and software industry. OpenStack based NFV is one of the killer solution for carriers and service providers in Japan, so many of NFV players including carriers, ISPs, Universities and networking vendors has combined to form a consortium for NFV called "Next NSP consortium", he is a board member of this consortium. Other Joined Communities: Japan OpenStack User Group, OpenDaylight Tokyo User Group, Next NSP consortium board member, Interop Tokyo ShowNet NOC member and COnference Network BUilders(CONBU).)*

* **Hirotada Sasaki** *(Hirotada Sasaki is Solution Architect at Red Hat.  He sells Red Hat solutions to customer as pre-sales technical person and presents lectures in marketing events.  Previously, he worked for a network equipment vendor and deeply involved to introduce NFV (vEPC) to the Japanese biggest mobile operator.  He has expertise in OpenStack, especially in network area.)*

Geographically resilient Object Storage with Ceph Radosgw
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Radosgw (RGW from here on) is Ceph's Object Storage frontend providing an Openstack Swift and Amazon S3 like api.It also integrates with Openstack Keystone for identity management, making it a good candidate for object storage in Openstack deployments. DR strategies are essential in ensuring that critical data is never lost. With the latest version of Ceph (Jewel) active-active multisite RGW has been implemented, allowing writes to any of the remote clusters, allowing for data and metadata to be recovered in case of a datacenter loss. Data writes are async, allowing for this to happen without taking a major performance hit.In hopes of clearly representing the place of RGW in Ceph & Openstack ecosystem, we'll look into the current status of  Multisite in Ceph and look into the internals and architecture of RGW, how objects are stored internally, synce'd across a  remote cluster and the various caveats and troubleshooting tips based on our work with RGW.


* **Abhishek  Lekshmanan** *(I'm a Software developer working on Distributed storage and related management tooling. I've been a contributor to the Ceph project for the past 2 years now, primarily on Object Storage, and have also made various fixes to Openstack keystone integration with Ceph's Object Storage. I was also one of the authors of ceilometer plugin for Radosgw. I'm also interested in operations and deployment of distributed systems in general)*

* **Karol Mroz** *(I'm a Software developer working on Distributed storage @SUSE, I've been a contributor  to Ceph for over an year now, primarily focusing on Object Storage. I've previously worked on security architectures, high availability and reliability for systems and networks, networking and protocols (TCP, SCTP, SIP).)*

How to migrate a large Swift cluster to Erasure Coding?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Erasure Coding (EC) is full of promise. Do you want know how you could convert your clusters to EC without wasting months to download/upload your petabytes? Come to see how we did it. We will first quickly explain what is EC and how it works in Swift. We will then spend more time describing the migration process we designed, our choices about the method and how we made it scale to PB of data and billions of objects. We will also talk about the traps we fell into. This talk will also be the occasion to give a feedback on EC at scale, what you should and should not do when deploying EC in your clusters. Finally, we will see that with few improvements, this method can be reused for other needs.


* **Romain Le Disez** *(Romain is a devops, working in the storage team at OVH.)*

2 years of running Ceph storage for OVH Public Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk we will present OVH cloud storage team experiences after running Public Cloud in production for more than 2 years. During this time we have had some surprises which we would to share with you. For example, we will answer questions like: * how much time does it take to do an online upgrade of a 1 PB cluster? * how to deal with PG problems? * how to backup more than 1 PB of data? * how many objects can you store in a single RGW bucket and what happens when you put too much? * how big should your clusters be to reduce blast radius Come and listen to those and other stories!


* **Paweł Sadowski** *(Started as System/Network administrator more than ten years ago. I was part of System Administrators team of biggest social network in Poland. After that worked for Amazon in Dublin, Ireland. Since almost three years I'm a part of OVH Poland, where I'm taking care of Ceph-as-a-Service.)*

Building a solid storage foundation for traditional and new workloads in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Today, it feels like the the IT world is going through changes faster than ever: the emergence of Third Platform, DevOps as a new way of working, or for example containers as a new way of running and deploying applications. However, at the same time, traditional workloads continue to exist and still need to be operated. This poses a challenge for IT departments, since they now have to manage new, as well as existing workloads. Short-term, it may be feasible to operate different platforms for each of these workloads, but mid-term, a consolidated platform based on OpenStack is obviously desired. In this session we will discuss how you can design a solid storage foundation for your OpenStack cloud, while not only accommodating traditional business applications, but also new workloads on the same platform. We will discuss the different types of data in cloud environments and provide recommendations for how to deploy and manage storage in a modern hybrid cloud datacenter.


* **Kapil Arora** *(Kapil Arora is a Cloud Platform Architect at NetApp in the EMEA region. He helps customers with OpenStack proof of concept implementations and production deployments and focusses on innovation, evangelization, and promoting the benefits of NetApp storage and software in cloud computing environments. He has 9 years of IT indsustry experience including 6+ years in the Storage industry. Kapil is also an experienced Java programmer and has a Bachelors degree in Information Technology from Bharati Vidyapeeth College of Engineering, Pune.)*

* **Clemens Siebler** *(Clemens Siebler is a Solutions Architect with strong background in software engineering and test-driven design. He enjoys helping and interacting with customers and partners. Clemens is also a Clean code enthusiast. He has 5+ years of professional experience and overall 12+ years of IT experience with extensive educational background in Computer Science.)*

50PB Multi-site Cloud Object Storage in China Mobile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

    The cloud storage is becoming the most important part of IaaS platform, because internet and mobile internet produced a mass of video, image and some other unstructured data. Therefore, ChinaMobile built 50PB cloud storage service for enterprise and individual customer this year.      There are some challenges in this program: one is the scale of storage service, it contains more than 1000 servers totally, we haven't found too much successfull cases; the other one is the unified namespace that crossed multi-site. We did sufficient investigation and research, including Ceph, Swift and some other options.      Finally, We decided to build and operate 50PB Object Storage service based on Ceph. The object storage service has also been integrated with our OpenStack-powered cloud platform to store the backups of virtual machines and glance images. We use the new multi-site architecture of ceph to meet the needs of scale and erasure code to reduce the total cost.  


* **Zhandong Guo** *( I worked for EMC after got master degrade from Beijing University of Posts and telecommuniations in 2011, and focus on object storage, Hybrid cloud platform and some other fields. In 2014, I become the employee of China mobile. As a team leader, Be responsible for the development of cloud object storage system which is the important part of CMCC cloud platform. From 2015, we focus on the practice of ceph.)*

* **Rongze Zhu** *(Cloud Architect, OpenStack/Ceph contributor. Responsible for financial and large enterprise OpenStack private cloud architecture design. Many years experience in the block storage system. Builded public cloud based OpenStack in 2012. Developed a distributed block storage system for large-scale production environment in 2013.     )*

* **Jiaying Ren** *(UMCloud software engineer,Ceph contributor,Being put in charge of Ceph object storage at UMCloud now .Having being focused on OpenStack/Ceph since 2015,operating dozens of OpenStack/Ceph private cloud,having been responsible for the design & implementation of Ceph admin platform,OpenStack functionality CI platform.)*

Breaking block storage performance limits: Introducing NVMe over fabrics integration with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NVM Express (NVMe) is a storage technology allowing to access Solid State Drives (SSD) directly over PCI. This allows for a much better throughput, latency and IO Operations Per Second (IOPS). NVMe over Fabrics (NVMf) is a new open source Linux project that provides access to NVMe devices over the network. This industry standards based technology enables sharing a pool of high-performance NVMe SSDs among multiple Nova instances running on a compute cluster. This talk presents the integration of NVMf volumes under Cinder framework, and how OpenStack users can benefit from high-performance NVMe SSDs. The session also presents early performance results and future areas of work for community participation.


* **Aviram Bar Haim** *(Aviram Bar-Haim acts as a Cloud Solutions team leader at Mellanox Technologies. Leading the Mellanox integration with OpenStack, in which puts contribution to OpenStack projects, including Openstack distributions and core projects, at the field of RDMA storage support (iSER) and Openstack high performance features. Before his current position at the Cloud solutions team, Mr.Bar-Haim worked at Mellanox storage and SW management teams, with developing large scale networking projects and SDN oriented POCs. Mr. Bar-Haim holds a Bachelor of Science in Computer Engineering from the Hebrew University of Jerusalem.  )*

* **Gunna Marripudi** *(Gunna Marripudi leads storage storage architecture in Memory Solutions Lab at Samsung Semiconductor Inc. Prior to joining Samsung, he was co-founder and CTO at Argil Data, a developer of storage software for Big Data applications. Earlier to Argil, he held engineering and technologist roles at Hewlett-Packard and QLogic in designing and productizing high-performance enterprise storage and networking solutions. He has MS (CS) from NIT, India and MBA from UCLA Anderson School of Management.)*

Cinder Next : Towards "Truly Software Defined Storage” Controller
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder has come a long way and it now supports many storage systems, making it truly a vendor-independent storage controller. In other words no vendor lock-in. However, there is more work to be done for it to qualify as a “truly software defined storage controller”. In this talk, we will give insight into what things the Cinder project community should consider for the upcoming road map so that it can distinguish itself as the best SDS solution available. We will offer a candidate list of new features and capabilities such as storage discovery, performance based port selection, storage migration hardware support, etc. For each feature, we will delve on how they can be implemented, and why they are the features to be considered for Cinder roadmap.


* **Parashuram Hallur** *(  Parash is a software professional having around 12 years of experience in designing and developing software products using Java, J2EE, Python and C# technologies. He has almost decade of experience in storage and virtualization industry. He has been working with OpenStack community from Icehouse release, majorly contributing to the cinder project.  He is currently working with EMC on their software defined storage portfolio.)*

* **Mallari Kulkarni** *(Software Executive specialized in building products that makes customer life simpler and better. Accomplished software professional with experience in building enterprise product leading small and large distributed teams. More details @ https://in.linkedin.com/in/mallarikulkarni  My webinars on Openstack and SOA - REST can be accessed from below links. http://www.techgig.com/expert-speak/Introduction-to-OpenStack-Software-Defined-Storage-CoprHD-763   https://www.youtube.com/watch?v=MvvRUnBMIOQ)*

* **Anil Degwekar** *(Anil is a Senior Consultant Software Engineer in EMC’s Advanced Software Division. Anil has been part of the EMC ViPR development team right from its inception. He joined EMC in 2009 and has 25 years’ experience in the IT industry. His technical interests include cloud computing, storage, graphics and parallel processing. Anil holds B. Tech. and M. Tech. degrees in Electrical Engineering from IIT Bombay.)*

The Efficient Object Store:  Large Scale Geo-Distributed Erasure Coding Swift Deployments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deployments of large-scale geo-distributed Swift using local and distributed erasure coding compared in this talk. Common swift data replication is 3x, assuring that each copy is on a different drive and a different storage node.  However, 3x replication, result in low hardware utilization comparing to RAID solutions.  Erasure coding has been recently become available in Swift, making data replication a more efficient 1.5x in a single location.   Greater data durability can be achieved by replicating the objects across multiple data centers.  With replication across data centers, resiliency can increase from 3x9’s in a single data center to 8x9’s with two data centers and 12x9’s with three data centers.  More recent developments allow for geo-distributed erasure coding which drive higher hardware utilization across data centers.  Instead of keeping full local replication, data can be distributed across 3 or more locations while maintaining a low 2x replication across all sites.


* **Jacob Caspi** *(Jacob Caspi is a Principal Technical at AT&T's Domain 2.0 Architecture team, currently responsible for the architecture of the AT&T Integrated Cloud (AIC), including compute, storage and network underlay.  Jacob joined AT&T in 2011 to manage the design and implementation of OpenStack-based geo-distributed cloud computing services at multiple data centers across the US, with thousands of Compute nodes and Petabytes of Swift Object storage.   Mr. Caspi came to AT&T from Sun Microsystem where he managed engagements in the Financial Services Area, including the introduction of Sun’s $1/CPU/Hour cloud computing offer using Sun Grid Engine for orchestration and Solaris zones/containers virtualization technology.  )*

* **Caleb Tennis** *(Caleb is an engagement manager and consulting engineer at SwiftStack. He helps bridge the gap between sales, support, and engineering, working with customers, partners, and the OpenStack Swift community daily. Caleb technical expert on SwiftStack software and provide guidance and support to customers and prospects in their evaluation and usage of our software defined storage product line. He also provide guidance in integrating SwiftStack into the customer data center. This includes assessments and recommendations around hardware, data center layout, network infrastructure requrements, data security needs and issues, VPN management and configuration, and other technical implementation details.)*

* **James Clark** *(James is a Cloud Architect at Solinea where he helps enterprises and service providers deploy and integrate OpenStack into their organisations. His work with clients spans from strategy and roadmap developemnt, through to architecture, design, and adoption.  He is based in Solinea’s Seoul office, covering the APJ region. Prior to joining Solinea, James was Chief Architect for the kt (the former Korea Telecom) OpenStack platform development program. His background is in service provider networking and software development.)*

The Open Hardware Alternative: Geo-Distributed Swift Deployments at Scale with OpenPOWER
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deployment factors of geo-distributed Swift using OpenPOWER CPU and hardware covered in this talk. As an alternative to Intel x86 CPUs, the POWER8 is a 4GHz, 12 core processor with 8 hardware threads per core for a total of 96 threads of parallel execution. It uses 96 MB of eDRAM L3 cache on chip and 128 MB off-chip L4 cache. POWER CPU hardware is as traditional server as well as OCP form factor. Building on the open edict of OpenStack, the POWER CPU is open source and governed by the OpenPOWER foundation. With certain applications, it has been shown to be a very power-efficient CPU. A stable OpenStack component such as Swift makes it a logical candidate for running on a large scale. Swift has now been ported and is available to run on POWER8-based hardware.


* **Jacob Caspi** *(Jacob Caspi is a Principal Technical at AT&T's Domain 2.0 Architecture team, currently responsible for the architecture of the AT&T Integrated Cloud (AIC), including compute, storage and network underlay.  Jacob joined AT&T in 2011 to manage the design and implementation of OpenStack-based geo-distributed cloud computing services at multiple data centers across the US, with thousands of Compute nodes and Petabytes of Swift Object storage.   Mr. Caspi came to AT&T from Sun Microsystem where he managed engagements in the Financial Services Area, including the introduction of Sun’s $1/CPU/Hour cloud computing offer using Sun Grid Engine for orchestration and Solaris zones/containers virtualization technology.  )*

* **Mark Baker** *(Product Manager at Canonical where I've spent the last 5+ years helping shape Ubuntu server and Ubuntu OpenStack. Previously held positions MySQL and Red Hat helping them disrupt Billion dollar encumbant enterprise software companies. Seem to be on the same path with OpenStack and Ubuntu.)*

* **Tom Mathews** *(Tom is a Distinguished Engineer leading the overall Cloud technical strategy and architecture for the Power Systems software development organization within the IBM Systems Division.  He is currentlyfocusing on OpenStack enablement, enhancement, and optimization of the OpenPower platform.   Tom has extensive technical experienceand background based in OpenStack and has been responsible for the architecture and development of numerous OpenStack-based IBM product offerings, including the SoftLayer-based IBM Cloud OpenStack Services private managed cloud,  IBM Cloud Manager with OpenStack, and IBM's PowerVC virtualization cluster management product.   He has also had responsibility for developing and delivering scalable OpenStack infrastructure clouds that underlie key IBM BlueMix services provided through IBM's public cloud environment.  Tom also has extensive systems andinfrastructure knowledge grounded in years spent designing and developing system software for IBM’s UNIX** business.   He joined IBM in 1985 after receiving a B S degreein computer science from the University of Texas at El Paso in 1984)*

Delivering high performance OpenStack storage solutions with NVMe SSD and Intel® Optane™ technology
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In order to provide reliable, high-performance, on-demand, cost effective storage for applications hosted on servers, more and more cloud providers and customers are extend their storage to include Solid State drive (SSD). In this session, you will learn about how to build Ceph based OpenStack storage solutions with today’s SSD as well as tomorrow's Intel® Optane™ technology (3D Xpoint), we will:  Present two reference architects and data of all SSD Ceph cluster that can deliver greater than 1 million IOPS for the performance intensive environment - providing a more cost effective solution than today’s HDD cluster.   Share “good/better/best” system configurations and performance optimization best known methods, and share early Ceph BlueStore performance results with all SSD configuration Discuss future Ceph architectures using next generation Intel® Optane™ technology, including proposals of OpenStack Ceph hyper-converged solutions based on Intel® Optane™ technology


* **Jack Zhang** *(Jack Zhang currently is a senior SSD Enterprise Architect at Intel’s NVM (non-volatile memory) solution group (NSG), he manages/leads SSD solutions/optimizations and next generation 3D XPoint solutions/enabling across various vertical segments, he also leads SSD solutions/optimizations at various open source storage solutions, SDS, Openstack, Ceph, Big data. Jack held several senior engineering management positions before joined Intel in 2005, he has many years’ design experience in firmware/hardware, software/kernel/driver, system architectures, as well as new technology ecosystem enabling and market developments.)*

* **Jian Zhang** *(Jian Zhang is a senior software engineer of the Cloud Storage Engineer group from Intel Asia Pacific Research & Development Ltd. The team focus developing and optimizing opensource cloud storage architecture and solutions based on Intel platforms. The team is No.2 code contributor in Ceph, contribued to many core features like Cache tiering, Erasure coding, Rados I/O Hint, and BlueStore. They orgznied and hosted the Beijing and Shanghai Ceph Day together with Redhat. They also work very closely with China customer to build Ceph based Server Based storate POCs solutions.  Jian has 9 years of software development, performance analysis, optimization and tuning experiences in open source software, including in Xen, KVM, Openstack, Ceph, Swift.   Jian has a master's degree in Comuter Science and Engineering.    )*

Converge and Conquer: OpenStack Converged Compute with Ceph SDS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deployment factors of orchestrated converged compute with Ceph block storage explored in this talk. The hyper-convergence server is a software-centric architecture that tightly integrates compute, storage, and networking on commodity hardware. Many compute servers in the in data centers have internal storage disks, but block storage is provided by dedicated SANs.  As a result, much of the local storage on compute nodes remains un- or underutilized. Ceph stores data on distributed commodity servers and provides interfaces for object and block storage. While Ceph is often run on dedicated servers, it can make more sense to converge OpenStack compute and Ceph on the same nodes and employ the unused local hard disks as drives for Ceph OSDs. Converged Ceph can significantly reduce storage costs in comparison to proprietary iSCSI arrays.  It allows for a scalable storage infrastructure that grows as compute capacity increases, and eliminates the need for dedicated Block storage system.


* **Jacob Caspi** *(Jacob Caspi is a Principal Technical at AT&T's Domain 2.0 Architecture team, currently responsible for the architecture of the AT&T Integrated Cloud (AIC), including compute, storage and network underlay.  Jacob joined AT&T in 2011 to manage the design and implementation of OpenStack-based geo-distributed cloud computing services at multiple data centers across the US, with thousands of Compute nodes and Petabytes of Swift Object storage.   Mr. Caspi came to AT&T from Sun Microsystem where he managed engagements in the Financial Services Area, including the introduction of Sun’s $1/CPU/Hour cloud computing offer using Sun Grid Engine for orchestration and Solaris zones/containers virtualization technology.  )*

* **Kiko Reis** *(I am a VP at Canonical and a long-time Ubuntu and open source contributor. I'm responsible for Canonical's storage, server enablement & automation products, but also get involved occasionally in other complicated and wonderful areas on the fringes of technology. I have an MSc in Software Engineering from ICMC USP, and live in São Carlos, Brazil, with my amazing wife Mari and two funny little toddlers.  )*

* **Christian Huebner** *(Christian Huebner works at the Mountain View head office of Mirantis, Inc. as Senior OpenStack Storage and Cloud Architect. Coming from a conventional storage architecture background, Christian moved into cloud storage before joining Mirantis and later into general cloud architecture. He currently is spearheading Big Data and Storage architecture projects for Mirantis customers with the focus on providing reference architectures and technical and organizational assistance for a wide range of storage technologies. In addition to the storage focus, Christian is providing architectural guidance and implementation consulting as well as subject matter expertise for a wide variety of customer OpenStack cloud projects. Christian has been a speaker at the five most recent OpenStack Summits, presenting topics from his experience as architect and storage subject matter expert.)*

Our Journey with CEPH (SUSE Enterprise Storage) SUSE Customer Story
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We are a global financial services company and recently went live with a Software Defined Storage solution based on CEPH.  In this session we will share details of our journey, discussing some of our use cases and requirements and how CEPH has helped us respond quickly to a business need. We will disucss the various challenges, both business and technical during the various phases of the project and share some of the lessons learned which ultimately led to a seccessful deployment. The next steps for us will be deploying OpenStack and looking at how we can integrate any future solution with the existing storage solution.  


* **Stephen Mogg** *(  Most of my career has been in Support and Technical Consulting roles over a period of 25 years. For the last two years I have been working as a Pre-Sales Consultant at SUSE. I am a fan of Open Source technology and try to contribute to the community where possible by getting involed and presetning at various meetups.        )*

Adventures in exploring containers : Using, Cloudfuse to get Swift as Docker volume
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During one of our explorations into containerized infrastructure challenges, we found that we needed a cheap solution to store terabytes of artifact. As an Openstack-certified provider, we're very keen on using Swift as the storage back-end for Artifactory, our artefact management system, but weren't satisfied with buying a $30k/ year driver for it. So we experimented with ways to configure and scale Cloudfuse, a Linux OS level driver for Swift. In this presentation, Sébastien Delisle and Corentin Ardeois will share their journey into containers, artifact management, kernel security with docker, and a concrete Cloudfuse use-case.


* **Sebastien Delisle** *(Bio to come)*

* **Corentin Ardeois** *(Born with a sense of adventure, that made him plunged right into the arm of Rick Dangerous, Corentin discovered the world of computers. Fast forward 25 years later, he's now a Javascript explorer, a pythonista and an OpenStack advocate. Currently involved with the OpenStack Javascript efforts and one of the technical lead of Internap, he is working on finding ways to make the OpenStack's and Internap's experience seamless.)*

How do I move my elephants? Uncovering the mystery of Cinder and Manila Replication
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder and Manila have proven to be effective providers of Block and File storage in OpenStack. Both projects have come a long way in providing a self service abstraction to a wide variety of storage systems and technologies that may exist in your data centers. Through the Newton release, there has been a great deal of focus in solving other important use cases such as high availability, data protection and disaster recovery which are critical in production environments. Through this session we will help you compare and navigate through the design and internals of the solutions that are available today. We will demonstrate how you can leverage the host level disaster recovery in cinder and tenant driven data replication in manila. We’ll discuss standard configuration best practices to benefit the use case/s you are trying to solve. We’ll take a sneak-peek at what’s in the works for the evolution of these features in the Ocata release and beyond.


* **Kapil Arora** *(Kapil Arora is a Cloud Platform Architect at NetApp in the EMEA region. He helps customers with OpenStack proof of concept implementations and production deployments and focusses on innovation, evangelization, and promoting the benefits of NetApp storage and software in cloud computing environments. He has 9 years of IT indsustry experience including 6+ years in the Storage industry. Kapil is also an experienced Java programmer and has a Bachelors degree in Information Technology from Bharati Vidyapeeth College of Engineering, Pune.)*

OpenStack and Ceph: Block Storage Harmony
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph is a fully open source distributed object store, network block device, and file system designed for reliability, performance, and scalability from terabytes to exabytes. The community has been very active integrating Ceph block storage into OpenStack, with deep support built into Nova, Cinder, and Glance. The most recent OpenStack user survey shows Ceph continues to be used in the majority of Cinder deployments. This session will explore the numerous capabilities integrated between Ceph RADOS block device (RBD) and OpenStack Nova, Cinder, and Glance services in addition to sharing the roadmap for future releases.


* **Jason Dillaman** *(Jason Dillaman is a software engineer at Red Hat and has been an active contributor to the Ceph project for over two years.  Jason currently acts as the project technical lead for the RADOS Block Device (RBD) module within Ceph.)*

Software Defined Storage for MySQL on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Software defined storage (SDS), the abstraction of storage software from underlying hardware, has gained explosive adoption thanks to public clouds such as Amazon Web Services, Azure, and Google. According to the latest user survey, MySQL is the most popular workload on OpenStack. Over the last two months, engineers at NetApp have been deploying OpenStack with a MySQL workload in a SDS platform with commodity hardware. Please join us to gain insights on deployment and validation of MySQL, architecture, and other deployment considerations for OpenStack with SDS. Though the deployment is done with OpenStack Manila (file share services), this presentation will be useful to those interested in using SDS for other workloads or in other ways (blocks, objects) with OpenStack, and taking advantage of enterprise storage features such as efficient snapshots, deduplication, compression, and thin provisioning, among others.


* **Akshai Parthasarathy** *(Akshai Parthasarathy is a Technical Marketing Engineer at NetApp, working on all things OpenStack and cloud computing. He has over 7 years of experience in the technology industry, having previously worked at Amazon Web Services and Dell. Prior to that, Akshai obtained his Bachelors (with Highest Honor) and Masters from the School of Electrical and Computer Engineering at Georgia Institute of Technology. )*

* **Ranga Sankar** *(I work as a Senior engineer in the RTP Netapp facility. Over the past 25 years i have been involved in developing System Level Software with primary focus on Operating Systems and Storage System Software. I have been with Netapp at their RTP facility for the past 17 years. I have been recently looking at integrating Netapp Storage Services with OpenStack.)*

OpenStack and Ceph @ Converged Microservers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

On the Austin Summit the Ceph Community and WDLabs presented about running a 4 Petabyte Ceph on ethernet attached Converged Microserver He8 drives. WDLabs provided access to early production devices for key customers for early adoption and feedback. This talk will provide insight into our experience with running a Ceph cluster on these devices as a storage provider for our OpenStack environment and will address among others topics like: How to deploy and manage a cluster where each drive is a server? Does the setup influence the network architecture of your cloud? What level of performance (native vs Ceph) can be expected? Are there implications on security and data privacy? What could come next?


* **Danny Al-Gaaf** *(Danny Al-Gaaf is a Senior Cloud Technologist working for Deutsche Telekom on building NFV clouds. As an Ceph upstream developer he is also a driver for using Ceph as a distributed open source storage back-end for OpenStack at Deutsche Telekom. For the last 10 years his professional focus has been on Linux and open source software. He works actively in several upstream communities.)*

The Day After Tomorrow - Production Recovery of Multi-site OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack private clouds are moving to production deployments, IT organizations are required to maintain service continuity and address possible resources outages with loss of storage, or extended loss of availability at the primary site.A disaster recovery strategy is required to allow application workloads to rapidly migrate to the secondary site and transition with little or no impact to their availability. This talk will cover key use cases and architectures that are in current use by customers for deploying backup and disaster recovery sites. We’ll review and demonstrate live the latest capabilities for Cinder Volume Replication and Active-Active Object replication with software-defined Ceph storage as the backend solution, as well as cover the OpenStack services enablement progress for building future multi-site configurations based on the Newton release.  


* **Sean Cohen** *(Sean is a seasoned product manager bringing over 15 years of experience in senior engineering, global operations and services management roles in virtualization & cloud companies. He has international experience of storage virtualization products delivery & private clouds design for enterprise customers in various market segments in US, Europe & APAC. Sean is focused on cloud storage product management and strategy for Red Hat OpenStack Platform cloud offering. Sean is a member of the OpenStack Foundation, a frequent speaker at OpenStack summits and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/.)*

* **Sébastien Han** *(Sebastien Han currently works as a Principal Software Engineer, Storage Architect for Red Hat. He has been involved since 2011 with OpenStack and Ceph and has built a strong expertise around these two technologies. Curious and passionate, he loves working on bleeding edge technologies and always hope to find a suitable spot to integrate his two favorite technologies. In 2013, he started to work with containers and ultimately implemented containerised Docker Ceph services. On a daily basis, he loves to rotate between these three areas where he always makes sure to strengthen the integration between all of them. From time to time, he attends various summits and events where he evangelises these technologies and their usage. In addition, he always devotes a third part of his time to blogging. But this... is just the beginning :).)*

* **Federico Lucifredi** *(Product Management Director for Ceph Storage at Red Hat, formerly the Ubuntu Server PM at Canonical, and the Linux "Systems Management Czar" at SUSE.)*

Ceph performance on all-flash storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When SATA disks are fully replaced with NVMe SSDs, Ceph's performance is not what it should be. In this session we will discuss how to get better performance in all-flash scenarios.


* **Jun Liu** *(Architecture and core researcher for distributed Storage.)*

* **Jay Yang** *(cloud architecture.)*

Accelerating Ceph with NVMe
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Solid state storage is increasingly an important technology for significantly increasing IOPS and reducing latency. Unfortunately, legacy industry standard drive interfaces are unable to keep up with this demand for high IOPS and low latency. NVM Express (NVMe) technology helps eliminate those barriers and deliver end-to-end performance gains. This session will present an architecture using NVMe devices for Ceph block storage applications. Benchmark results comparing NVMe to traditional storage approaches will be presented. This session will also discuss the upcoming Ceph storage backend BlueStore, and present a conceptual architecture for using NVMe together with BlueStore.


* **Pete Brey** *(As Cloud Solutions Product Manager for HPE Helion Cloud Storage Solutions, Pete Brey is responsible for developing and delivering innovative OpenStack cloud storage solutions for a variety of use cases which build upon Cinder and Swift OpenStack storage API’s, as well as Ceph. Prior to joining the Helion team at HPE, Pete was with HPE Storage for 10 years where he was responsible for research and development, technical marketing, and product marketing for Scale Out Network Attached Storage. In his tenure in HPE Storage, Pete was also instrumental in developing storage solutions for desktop client virtualization and mobility, as well as vertical market storage solutions for Healthcare, Life Sciences, and Media and Entertainment. Pete holds Bachelor of Science degrees in Electrical and Computer Engineering and Computer Science from the University of Wisconsin, as well as a Master of Business Administration from the University of Denver. Pete is an avid runner and cyclist, having completed numerous marathons and triathlons worldwide and raced many bike races in his home state of Colorado. You can catch Pete’s latest whereabouts and thoughts on cloud storage on his Twitter account @cloudstorageguy.  )*

Swift3: The Use Cases and Features of Amazon S3 compatibility layer built on Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

 Highly dependable object storage is one of the key components to develop cloud application. Cloud application developers need to store any data for their application like media (picture/movie), their application logs, documents, and it could be also used as static HTTP content providers.  Amazon S3 is definitely an instance of de-fact standard object storage and OpenStack Swift is also used all over the world as the most common OSS object storage software.  In this talk, we would like to introduce Swift3 which is open source software to provide S3 compatibility built on top of OpenStack Swift and the customer success stories it has enabled.  This session covers with the topics:   - Overview of the Swift/S3/Swift3 protocol   - The similarities and fundamental differences between the Swift and S3 APIs   - Current compatibility with Swift3 & S3   - Customer feedback - what features are most important for customer?   - Community activities and future plans/priorities


* **Kota Tsuyuzaki** *(Kota is a Software Engineer at Nippon Telegraph and Telephone Corporation (NTT). NTT is one of the biggest telecommunication companies which provide cloud services in Japan. Kota has worked on OpenStack Swift for approximately 4 years. Recently, he has worked on global distributed cluster efficiency and the area of erasure code stuff in the Swift community and he has joined Swift core team since Jun 2015. Since before joining Swift core team, he is working on Swift3 as an upstream contributer and now take a role of PTL on the Swift3 project.)*

* **Bill Owen** *(Bill Owen is Senior Software Engineer with IBM's Spectrum Scale team.  He is responsible for the integration of OpenStack with Spectrum Scale.  He has worked in various development roles within IBM for the past 15 years.  Prior to joining IBM, Bill developed and deployed grid management software for electric utilities.)*

* **Tim Burke** *(Tim Burke is a software developer at SwiftStack and core reviewer for swift and swift3.)*

CephFS & OpenStack Update
~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Austin, we discussed the release of a stable CephFS in Jewel, with several caveats around missing features and security in cloud environments. The CephFS team has been hard at work (and growing!) in the six months since. This talk will present an overview of CephFS, a POSIX filesystem built on top of the stable storage you already love and can manage from using RBD; and move on to the new work present in the latest “Kraken” release, especially as it relates to OpenStack and Manila users. Hear about how we’ve improved the security model and what our roadmap is for coveted features like arbitrary-subtree snapshots and horizontally-scalable metadata servers.


* **Gregory Farnum** *(Greg Farnum is a long-standing member of the core Ceph development group, having joined the project as the third full-time engineer after graduating from Harvey Mudd College in 2009. Now a Red Hat employee, Greg has done major work on all components of the Ceph ecosystem and currently focuses on the filesystem.)*

OpenStack’s Storage Performance:  Can you handle the truth?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Choosing the right storage for OpenStack is not a simple task.  Deciding what storage to use is a big problem in and of itself, but understanding how that storage performs, what its operational complexity really is, and what real workloads actually look like running on it are questions that anyone running OpenStack in production is faced with.  


* **Paul Roberts** *(An extremely technical and seasoned technologist who has spent the last decade engineering and implementing large scale infrastructure and security architectures for organizations of all sizes - ranging from startup to Fortune 500.  Today, Paul is managing the pre-sales engineering team that is helping customers design and architect various OpenStack powered cloud initiatives.  Prior to Mirantis, Paul managed the Coraid Technology Group team who were responsible for developing custom solutions for customers and helping build reliable and scalable storage infrastructures leveraging enterprise-class Ethernet SAN technology.  Prior to Coraid, Paul was the the lead architect for Carpathia's cloud solution, deploying numerous multi–petabyte cloud storage solutions that deliver hundreds of gigabits of Internet traffic.  Paul was also instrumental in architecting Carpathia's federal and commercial cloud platforms, while playing a key role in the on–boarding of customer's applications into the Carpathia cloud platform.)*

* **Ryan Day** *(Versatile, pragmatic technologist with more than 10 years of experience working in information systems and technologies. At Mirantis, Ryan works as a pre-sales engineer, helping companies design and develop strategies for OpenStack powered cloud computing. Prior to Mirantis, Ryan worked as a systems architect for a system integrator, collecting a breadth of expertise and experience in a wide range of datacenter technologies, with a focus on emerging technologies in the areas of Big Data, Cloud and NFV.)*

Intelligent Archival Systems for Cognitive and Analytics Workloads
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session discusses how the Ennovar Lab at Wichita State and IBM are combining emerging technology based on metadata search with OpenStack Swift object storage to create a next generation, cognitive and analytics enabled Intelligent Archival System.  The intelligent archival system integrates with custom metadata tag and search technology and Swift High Latency Media (SwiftHLM) middleware. It allows users to tag objects with application specific custom metadata and enables content aware migration of the objects to and from low cost storage pools such as tape or SMR drives based on the custom metadata. By placing the custom metadata on flash / SSD and making it readily accessible via REST API, cognitive applications as well as emerging analytics frameworks such as Spark can efficiently gain insight from the metadata while still achieving low cost due to the use of higher latency storage such as tape. A live demo of this capability will be included.


* **Joseph Dain** *(None)*

* **Nilesh Bhosale** *(Nilesh Bhosale is a working as a member of IBM Storage & SDS CTO office, closely working with IBM's Spectrum Scale (a.k.a. General Parallel File System) team.  He is responsible for the integration of OpenStack with GPFS and has been actively contributing to OpenStack Cinder, Manila projects.  He is also working on integrating and enhancing OpenStack Swift object store with IBM Spectrum Scale object offering.He has been working in IBM India Storage Lab, developing IBM NAS storage systems, for the past 5 years. Nilesh has 13 years of industry experience and prior to joining IBM, has worked in system's software development role at multiple organizations.)*

Increasing Cloud's storage capacity to meet the dynamic growth demands of your tenants
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The unceasing addition of new tenants and their growth's demands for storage requires frequent capacity expansion activities on the Cloud's storage infrastructure.  Meticulous efforts by a savvy staff with the precise expansion strategies are keys to successful deliveries of new storage in production environments.  My intention is to disseminate the practical experiences that were acquired through the deployments of new storage to production environments.  Adding storage capacity to the production sites without the tenants experiencing the service interruptions ensures a healthy tenant base.    A CEPH storage cluster is designed with the ability to increase the storage capacity dynamically.  CEPH gives us the ability to dynamically add the needed storage to an existing storage cluster to serve the new demands.


* **Al Lau** *(My background is in storage and my prior professional experiences, before joining Cisco, vary from file system development to writing Linux/Solaris/HPUX/AIX Kernel Device Drivers. My current role at Cisco is a storage technical lead within the Cisco's Cloud Infrastructure team.  Since joining Cisco, I have been focusing exclusively on CEPH, ext4 and xfs file systems, and OpenStack components (cinder, glance, nova, neutron, keystone).)*

Ceph, containers and performance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers and the world of microservices have been getting a lot of traction recently as companies are investing in containerizing their applications. Storage is an integral part of the solution and forms a key component of the architecture, as the entire platform must be deployed, managed and orchestrated in containers. The Ceph cluster will be entirely containerized, all daemons will live inside Docker containers. After explaining why we are doing this, we will go through several use cases for containerizing Ceph and orchestrating it with Kubernetes. We will start from the deployment phase, and continue on to upgrades and the entire management life cycle of the solution. We will characterize the storage performance of applications running in containers that are using the Ceph kernel block driver (krbd) to provide persistent storage. We will close with a reference architecture of how to optimize krbd for the lowest latency, catering to RDBMS hosting environments.


* **Kyle Bader** *(Kyle Bader is a Senior Solution Architect working in the Storage Solutions Team at Red Hat, lending his design and operational skills with Ceph to help develop tested solutions that ensure repeatable success when deploying distributed, fault-tolerent, multi-petabyte storage systems. Prior to Red Hat, Kyle had architectural roles at both Inktank and DreamHost. Kyle was part of the team that brought the first production Ceph clusters to the world, supporting DreamHost's DreamObjects and DreamCompute services.)*

* **Tushar Gohad** *(Tushar is part of Intel's Data Center Group where his primary area of focus is Software Defined/Scale-out Storage Architecture. Tushar has been working in the open-source networking and storage-related technologies for over a decade now – his recent contributions were to Erasure Code data path in OpenStack Swift, Intel’s Storage Performance Dev Kit (SPDK) and networking in the Linux kernel. Prior to joining Intel, Tushar was a lead open-source/Linux kernel developer at Cavium Networks/MontaVista Software where his focus was data-plane packet processing acceleration in all-Linux environments involving UIO, IPv6 enabling in the Linux ecosystem, Linux namespaces/containers and Linux IPsec scalability improvements. Tushar holds a Masters degree in Computer Science.)*

* **Sébastien Han** *(Sebastien Han currently works as a Principal Software Engineer, Storage Architect for Red Hat. He has been involved since 2011 with OpenStack and Ceph and has built a strong expertise around these two technologies. Curious and passionate, he loves working on bleeding edge technologies and always hope to find a suitable spot to integrate his two favorite technologies. In 2013, he started to work with containers and ultimately implemented containerised Docker Ceph services. On a daily basis, he loves to rotate between these three areas where he always makes sure to strengthen the integration between all of them. From time to time, he attends various summits and events where he evangelises these technologies and their usage. In addition, he always devotes a third part of his time to blogging. But this... is just the beginning :).)*

Second-level recovery of volume in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

     The topic involves the field of data protection in OpenStack. In order to meet the needs of recovery to the closest point after the disaster, we introduce the continuous data protection (CDP) technology in OpenStack. CDP is a technology which can continuously capture and save the changes of data to another independent location. Theoretically, it can recover to any specified point in the past. We apply the technology in OpenStack to provide second-level recovery of the disk in the virtual machine based on KVM. When a fault occurs, the disk can be recovered to the nearest time or any second.      In addition to describing the technology of second-level recovery of volume in OpenStack, this topic will provide a demo, demonstrating how to use and manage it.


* **junli li** *(None)*

Sharing - what's true since childhood is true for clouds! Using Shared Filesystem in OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Efficient data storage is critical for large scale OpenStack cloud deployments. There are several shared file systems that can be used in an OpenStack cloud. These can be used to efficiently share data between Nova, Glance and Cinder, as well as provide storage for object and file based protocols with Swift and Manila. Enterprise features like copy on write file clones and file system snapshots, policy based tiering of data between storage classes, and intelligent backup schemes are important benefits that the filesystem backend can provide. In this presentation we describe these benefits that a shared file system can bring to your cloud architecture, as well as demonstrate an implementation based on Spectrum Scale.


* **Gaurang Tapase** *(Gaurang Tapase is a software developer with IBM Spectrum Scale team. He mainly works on integration of Openstack storage components (Cinder/Manila/Swift) with Spectrum Scale. Previously, he has worked on development projects centered around object stores.)*

* **Bill Owen** *(Bill Owen is Senior Software Engineer with IBM's Spectrum Scale team.  He is responsible for the integration of OpenStack with Spectrum Scale.  He has worked in various development roles within IBM for the past 15 years.  Prior to joining IBM, Bill developed and deployed grid management software for electric utilities.)*

* **Smita Raut** *(Smita has been working with IBM for the last five years in storage area. She has been working on Network Attached Storage products on features related to disk and filesystem management, Active Cloud Engine (wan-caching across geos), Information Lifecycle Management and Object protocol for cloud storage. Her current focus is on Object storage protocol for cloud enablement.)*

Keep your Data Lake Healthy
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A growing and aging data lake might fast become a polluted dump, plug up your pipes or might even overflow if not maintained. There is a growing demand for further object store management functions to keep the lake clean and healthy. For example to automatically compress and expire object data, as well as place data using an optimal storage tier, to allow access from file interface (SwiftOnfile), or save private data in an encrypted format. The session begins with a short overview of the swift storage policy mechanism and how it can be used to separate the object data stored in the underlying storage system. Further we will explain how combining the features of storage back ends with swift storage policies creates new functionality for your object store. This presentation includes examples and demonstrations. Keep your data lake clean and healthy. Add important data management functions to your object store, by (easily) attaching the needed storage policy and storage back end to it!


* **Simon Lorenz** *(Simon Lorenz is an IT Architect in IBM Research and Development Germany. Hejoined IBM Germany in 1993 and worked on productivity and manufacturing qualityimprovements within IBM Disk Drive Manufacturing Management software. Duringinternational assignments, he helped to improve fully automated chip factories in the US andAsia. Simon has held various positions within IBM Research and Development. Since 2009,he has worked on Storage Systems Management software and has been responsible forsubcomponents, such as system health reporting, cluster configuration management, andrecovery. Simon joined the IBM Spectrum Scale (built upon IBM GPFS) development team in 2014 and works on the integration of Openstack with Spectrum Scale.)*

* **Gaurang Tapase** *(Gaurang Tapase is a software developer with IBM Spectrum Scale team. He mainly works on integration of Openstack storage components (Cinder/Manila/Swift) with Spectrum Scale. Previously, he has worked on development projects centered around object stores.)*

* **Sasikanth Eda** *(Sasikanth Eda is a Software Engineer with the IBM Spectrum Scale development team. He works for the integration of OpenStack with Spectrum Scale, focusing on Swift object, Cinder block and Manila file storage components of OpenStack.)*

Applying Flash to a Parallel Fileystem in support of Openstack Environments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Whilst a scalable parallel filesystem brings some interesting benefits in building a storage layer for Openstack environments, architecting Openstack on parallel filesystems is performed today largely in the absence of quality data. A single, highly scalable namespace for object, cinder, glance and mounted, shared filesystems is possible today with Spectrum Scale (previously GPFS) and can reduce the complexity of openstack environments and provide a useful path from traditional research environments into virtualised ones. However, today it is difficult, a-priori for an architect to understand the implications of running production services at scale on the IO loads placed upon the underlying filesystem and storage - in particular when using a parallel filesystem. Further to this, whether or not to deploy higher–cost flash tiers, and if so, how, and at what capacity complicates the architect's task. We provide benchmark data at scale to improve the current state of understanding.  


* **James Coomer** *(Dr James Coomer has held a career in High Performance Computing starting with a PhD in Theoretical Physics at Exeter University (UK), modelling material structures using high-performance computing techniques. James then spent over 10 years at Sun Microsystems and Dell in a wide range of High Performance Computing and Cloud roles from L3 support through consultancy, training, installation and pre-sales. James has specialised in the past in HPC schedulers, parallel programming and high-performance interconnects and filesystems before turning to focus on IO and storage in a move to DDN Storage in 2011. James now leads a team of technical staff in Europe.)*

* **Simon Thompson** *(Simon is the Research Computing Infrastructure Architect at the University of Birmingham. Working designing and building research data and computation systems. Recently much of Simon's time has been taken up designing and building OpenStack based private cloud systems including the pilot for the CLIMB project. CLIMB is an ambitious multi-University, multi-site deployment aimed at supporting microbial bioinformaticians and was built with Tom Connor (Cardiff University) and Nick Loman (University of Birmingham) and supported by the Medical Research Council. Simon enjoys challenging projects, and challenging the traditional approaches used which has led to the development of a private research cloud being deployed at University of Birmingham which includes being the first UK site to deploy Lenovo warm water cooling technology and even getting parts created to support the systems. He is also chair of the independent Spectrum Scale user group.)*

New in Swift: Object Encryption
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the Newton cycle, Swift released an exciting new feature which enables encryption of object data at rest. OpenStack Swift provides reliable and scalable object storage that has been deployed in many successful production environments. With the Newton release Swift has added an exciting new feature to enable encryption of object data on disks. This feature is intended to protect data at rest from an attacker that gains physical access to disks. We will demonstrate this new feature, show how it is deployed, and discuss performance implications.


* **Tim Burke** *(Tim Burke is a software developer at SwiftStack and core reviewer for swift and swift3.)*

* **Alistair Coles** *(Alistair Coles is a core reviewer for the OpenStack Swift project and a principal engineer in the Hewlett Packard Enterprise Helion Cloud engineering organisation. Prior to this, Alistair spent over 25 years with HP Labs, where most recently he worked on virtualised infrastructure management technologies, including scalable virtualised block storage solutions that were deployed in public cloud services.)*

Block, Object, NFS, SMB in a single region storage cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You are asked to design and deploy an OpenStack private cloud. The requirements are straightforward: roughly 20-30 compute nodes, 100 cores and flat DHCP networking in a single region. However, you are expected to support a variety of storage protocols: block for database, object for images and videos, NFS and SMB for file shares. On top of that, service availability and reliability are critical. There are several architectural approaches to in designing a storage cluster, using Ceph, Swift, or unified block storage, but what are the pros and cons and what are the trade off's between performance, complexity, and costs between different between each of them?  In this session, we will explore multiple approaches and analyze the benefits, pitfalls and performance characteristics of each.


* **Narayan Kumar** *(Narayan Kumar has over 17 years of progressive experience across multiple industries and disciplines in product management and enterprise server solutions, currently working for Nimble Storage and focusses on virtualization, integrating storage with VMware features like vSphere plugin for vCenter, Virtual Volumes, Storage Policy-Based Management and VASA along with other open source cloud integrations like Openstack and Docker.)*

* **Greg Loughmiller** *(Greg Loughmiller is curently a Sr. Tech Marketing Engineer with a focus on Openstack Architecture and Solutions using Nimble Storage systems. His primary focus is to work with members of the field to identify, develop and provide solutions needed in the OpenStack space using Nimble storage arrays. Greg has over 20+ years of storage expericence and in the past has worked as Global Solution lead with focus on Database Buniess Applciation solutions and Architecture.)*

Tips and Tricks for building an iSCSI deployment for Cinder
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying the first few hosts is easy, but scaling your iSCSI Network for Cinder backends requires careful thought and planning. What are the considerations for deploying Cinder Backends using iSCSI drivers? How could this scale? What are the deployment considerations? What about the infamous Neutron network?  This talk will cover a host of issues when it comes to designing and deploying iSCSI backends with Cinder at scale for OpenStack Clouds.


* **Greg Loughmiller** *(Greg Loughmiller is curently a Sr. Tech Marketing Engineer with a focus on Openstack Architecture and Solutions using Nimble Storage systems. His primary focus is to work with members of the field to identify, develop and provide solutions needed in the OpenStack space using Nimble storage arrays. Greg has over 20+ years of storage expericence and in the past has worked as Global Solution lead with focus on Database Buniess Applciation solutions and Architecture.)*

* **Narayan Kumar** *(TBD)*

Why you should consider using a cluster file system for OpenStack storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cluster file systems (shared-disk) provide concurrent access control for multiple clients. They can serve as an abstraction layer between compute and storage nodes. By using block based access protocol, cluster file systems provide high performance storage access compared to a network based distributed file systems. In this session, we will examine use cases for Docker containers, Nova instances, Manila file shared service and data migration. We will explain a best practice for deploying shared-disk file systems on OpenStack storage covering how the cluster file systems can provide concurrency, failover and access transparency. In addition an analysis of their performance characteristics will be presented.


* **Narayan Kumar** *(Narayan Kumar has over 17 years of progressive experience across multiple industries and disciplines in product management and enterprise server solutions, currently working for Nimble Storage and focusses on virtualization, integrating storage with VMware features like vSphere plugin for vCenter, Virtual Volumes, Storage Policy-Based Management and VASA along with other open source cloud integrations like Openstack and Docker.)*

* **Greg Loughmiller** *(Greg Loughmiller is curently a Sr. Tech Marketing Engineer with a focus on Openstack Architecture and Solutions using Nimble Storage systems. His primary focus is to work with members of the field to identify, develop and provide solutions needed in the OpenStack space using Nimble storage arrays. Greg has over 20+ years of storage expericence and in the past has worked as Global Solution lead with focus on Database Buniess Applciation solutions and Architecture.)*

'Stacked Storage with Ceph at CERN: Glance, Cinder, ... Manila?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CERN IT has been operating Cinder and Glance services, backed by Ceph, for close to three years. The technologies involved have demonstrated their flexibility when building higher-level IT applications (we now host more than 2200 Cinder volumes). So the obvious question is... what's next? On the one hand, both the growth and age of these services has required us to refresh the hardware behind our largest Ceph cluster. We'll present how we transparently doubled of largest Ceph cluster to six petabytes. On the other hand, we have recently started evaluating CephFS for HPC use-cases. Though it's still early days, the initial feedback from users has been positive, and we've therefore wondered: if our CephFS/HPC tests are successful and we decide to open it as a wider service, then could OpenStack Manila help use manage a large, multi-user CephFS system?


* **Dan van der Ster** *(Dan is a Storage Engineer and Ceph Manager in CERN IT's Storage Group. Prior to working on storage, Dan worked in Grid Computing for the ATLAS experiment at CERN. Dan earned a PhD in Computer Engineering at the University of Victoria in 2008.)*

Sharing Volume in a Multi-Node Cluster Applications Using Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

oThis presentation will walk you through the new shared volume feature. It will touch base on some real life examples of High availability applications like Oracle which make use of shared storage. Session will help the new developers how one can leverage Openstack shared volume ( multiattach) feature to manage the workload in a Cluster application.


* **Chhavi Agarwal** *(Chhavi Agarwal is a Advisory Software Engineer at IBM, having over 11 years of experience. Over the last 5 years actively involved in systems related to Cloud, Virtualization and Systems Management.  She has been actively involved in the community for the nova-powervm drivers and cinder community. )*

* **Shyama Venugopal** *(Shyama is a Software Engineer with 9 years of experience in product development. Currently working on storage virtualization in IBM's Power Virtualization Center built on top of Openstack. Openstack specialization include Cinder and Nova.)*

* **Gerald McBrearty** *(Gerald McBrearty has contributing fixes to OpenStack Cinder since Liberty. He has worked at IBM in a number of different capacities that include storage management, file systems, kernel extensions, OS install and update. Currently he is working on Openstack on Power as a software architect.)*

Tesora  and VMware present – A Complete Guide to Running Your Own DBaaS using OpenStack Trove
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Databases are at the heart of every application. They come in multiple shapes and forms, and rest assured all of them pose a significant operational challenge. DBaaS presents a powerful approach to mask the operational challenges and present databases as a easily consumable service.  In this session, Tesora - market leading DBaaS provider and VMware – provider of easiest OpenStack solution,  will deliver a complete step–by–step guide on how to get your own DBaaS going by leveraging OpenStack Trove.


* **Arvind Soni** *(Arvind leads OpenStack efforts at VMware. Arvind manages product strategy and execution for integrating OpenStack with VMware products. Arvind is also the lead PM on development of VMware’s OpenStack Distribution, VMware Integrated OpenStack.  Arvind has over 10years of technology industry experience. Arvind holds an MBA from University of Chicago, Booth School of Business. He also has Masters in Computer Sc from North Carolina State along with Bachelors in Computer Sc from IIT Bombay.)*

* **Doug Shelley** *(VP, Product Development at Tesora. )*

Living on the Edge: Scalable Edge Caching and Disaster Recovery with OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As industry shifts towards building their own private and public storage clouds, OpenStack Swift has become an invaluable storage platform with numerous tools in the toolbox.  Once objects are distributed across multiple geographies though, the toolbox becomes lighter and lighter.  Currently OpenStack Swift assumes a mostly homogenous set of data centers over which to distribute data, which does not take into account that not every data center is created equally.  We are building an object storage solution, which builds upon unmodified OpenStack Swift, that supports on-disk caching of objects at edge data centers while always being stored at an organizations primary data centers that contain the DR, backup and archive facilities.  In our solution, applications can continue to failover and failback between data centers in the case of a disaster, but are no longer required to store a piece of the object store at every site. 


* **Dean Hildebrand** *(Dean Hildebrand is a senior researcher at the IBM Almaden Research Center and a recognized expert in the field of object storage as well as distributed and parallel file systems. Dr. Hildebrand pioneered pNFS, demonstrating the feasibility of providing standard and scalable access to any file system. He received a B.Sc. degree in computer science from the University of British Columbia in 1998 and M.S. and PhD. degrees in computer science from the University of Michigan in 2003 and 2007, respectively.)*

* **Gaurang Tapase** *(Gaurang Tapase is a software developer with IBM Spectrum Scale team. He mainly works on integration of Openstack storage components (Cinder/Manila/Swift) with Spectrum Scale. Previously, he has worked on development projects centered around object stores.)*

Towards Zero ETL: Unifying data management across PaaS,CaaS and IaaS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Recent trends in application deployment point to hybrid deployment models cutting across PaaS, CaaS and IaaS runtimes.  A single deployment model cannot cater to all application types. Often enterprises need to deal with a mix of easily decomposable applications (12 factor micro services) and monolithic legacy applications. Common amongst them is need for data sharing and persistence. In this talk we will highlight the challenges in managing and enabling shared data access from across different runtimes such as Cloudfoundry, Docker and Openstack to common shared data.  We will share our experiences building data centric storage services for seamless data sharing using storage plugins for Docker, Cloudfoundry and Nova and highlight performance, resiliency and security implications of each of the alternatives and conclude with a common set of best practices.  


* **Nagapramod Mandagere** *(Nagapramod Mandagere received his PhD from University of Minnesota in Enterprise data management. He has been a researcher at IBM Almaden Research center since 2008 working on various systems technologies. He has coauthored several conference papers and has several patents in domain of systems management. Recent work revolves around container runtimes and is a contributer to cloudfoundry. )*

* **Dean Hildebrand** *(Dean Hildebrand is a senior researcher at the IBM Almaden Research Center and a recognized expert in the field of object storage as well as distributed and parallel file systems. Dr. Hildebrand pioneered pNFS, demonstrating the feasibility of providing standard and scalable access to any file system. He received a B.Sc. degree in computer science from the University of British Columbia in 1998 and M.S. and PhD. degrees in computer science from the University of Michigan in 2003 and 2007, respectively.)*

* **Amit Warke** *(Working as an Advisory Software Engineer at IBM Research in the Cloud Storage Group.)*

“3-2-1, Action” - Running OpenStack Shared File System Service in Production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack’s Shared File System Service is getting more and more adoption as one of top leading emerging projects in OpenStack deployments (according to the last OpenStack foundation user survey), we would like to share some of the key customers use cases such as DevOps, Containers and Enterprise Applications as well review the latest Newton release project updates towards delivering a production-grade deployments.


* **Anika Suri** *(Anika Suri is a Technical Alliance Manager with NetApp's Global Alliances team, managing the OpenStack Ecosystem. She has over 6 years of experience in the technology industry, having previously worked at Brocade. Prior to that, Anika obtained her Masters from San Jose State University in Computer Engineering (specializing in Networking).)*

Give me Cinder volume for containerized apps on top of baremetal node!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Storage is an essential part of any computing systems. In OpenStack, Cinder provides persistent storage, but currently, Ironic only supports integrated storage and is not available Cinder volume as an external storage. By utilizing external storage at Ironic, user can run enterprise workloads on bare metal servers to ensure stable and predictable performance, and better data consistency etc. Also this can be applied to containerized apps on top of baremetal node. Enterprise workloads such as Database, fail over with state-full application on container need persistent and stable storage. There are two ongoing effort and one lacking feature to enable volume support for containerized apps on baremetal. - [Ironic] Cinder volume support- [Magnum] Ironic support- [Magnum] Volume support on baremetal node(not started) In this session, we explain recent updates of Ironic and Cinder integration effort and then discuss Ironic support for Magnum and volume support for container.


* **Mitsuhiro Tanino** *(Mitsuhiro Tanino is a software engineer who has been working for Hitachi since 2004 and a principal software engineer Hitachi Data systems since 2014. He has experience about development of virtual machine manager for heterogeneous cloud systems and RAS features for KVM virtual environments. His current working area is Cinder and Nova, he is enhancing reliability and stability features to achive Mission Critical systems requirements.)*

* **Satoru Moriya** *(Satoru is Researcher of Cloud management at Hitachi. Satoru has 10 years experience in software industory from hypervisor, linux kernel to OpenStack. Satoru currently focuses on improving bare metal server management in OpenStack, in particular, Ironic and Cinder integration to support boot from volume in Ironic.  )*

Architecting and Automating a Bcache Ceph Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Block storage is an integral part of any OpenStack deployment, and Ceph is one of the most popular options. However, Ceph can be expensive because of the number of disks required, especially when SSDs are chosen. Using Ceph with Bcache allows you to save money without sacrificing performance. In this talk we'll show you how we designed a Bcache Ceph cluster and automated its deployment with Ansible. 


* **Michael Sambol** *(Michael Sambol is a Software Engineer at IBM Cloud where he automates and deploys monitoring frameworks for enterprise OpenStack clients. Prior to IBM, Michael graduated from Georgia Tech with a BS and MS in Computer Science. When he's not coding, you'll find Mike in the gym. )*

* **Krishna Nandyala** *(Krishna Nandyala is a Software Engineer at IBM Cloud where he designs and automates block storage solutions.)*

Unleashing the power of Oracle Database with shared filesystems and OpenStack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Oracle Database can give superior performance when used with ZFS storage Appliance over dNFS. ZFS Storage appliance(ZFSSA) has hooks to listen to cues from the database over dNFS. This reduces the tuning effort required when provisioning shares from Manila when integrating with a database. The compression ratios are also improved drastically when integrating Oracle database with Manila on ZFSSA. dNFS enables fibre-channel like performance but with reduced operational and capital cost of file based storage. With DTrace based analytics in the ZFSSA, it is easy to identify individual database's performance which can help with storage optimization and identification of performance issues. There will be a demo in which the database will be hosted on a VM on Nova and the shares on ZFSSA will be provisioned by Manila.


* **Kedar Vidvans** *(Kedar is a senior software developer working for Oracle. Kedar works with the Oracle ZFS Storage appliance(ZFSSA) team and is responsible for developing and maintaining ZFSSA storage drivers in OpenStack. Kedar has been associated with OpenStack since the kilo release.)*

* **Juan Zuluaga** *(Juan is a principal software engineer with Oracle and has 15+ years of experience in the industry. Juan is responsible for developing and maintaining on the ZFS Storage appliance drivers in OpenStack. Juan has been associated with OpenStack since the juno release.)*

* **Alka Deshpande** *(Alka is a senior software manager with Oracle having 20+ years of experience in the storage industry. Alka manages the team that is responsible for developing and maintaining Oracle ZFS Storage Appliance OpenStack drivers.)*

Ceph: The Next Generation at Comcast
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Comcast’s journey with Ceph started 3 years ago with the release of Dumpling.  Since then, we have continued to evolve our ever-expanding Ceph footprint and, as a result, have many lessons learned and tips to share.  This presentation will discuss our next generation design from both a software and hardware point of view.  Topics Include: General hardware recommendations Ceph configuration tips, tricks, and advice Using cached block devices to improve performance Asynchronous active-active geo-replication using Rados Gateways    


* **James Saint-Rossy** *(Principal Engineer for the Ceph storage infrastructure at Comcast.  Over 15 years of Linux and UNIX experience doing operations and systems engineering for major government and commercial organizations.)*

DRBD SDS in action at PROZETA
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The DRBD SDS was put into production by the Czech company PROZETA and DRBD's creators at LINBIT. Learn about the motivation to use the DRBD stack for all block storage needs. Get an overview of the deployed technologies DRBD SDS and dockerized OpenStack. Be among the first to pick up the experiences from the course of the project, the shortcomings and the highlights. Explore with us performance numbers of the created block storage system.  


* **Philipp Reisner** *(Philipp Reisner is CTO of LINBIT Information Technologies GmbH inVienna. During his studies of computer sciences at the Technical University in Vienna (TU Wien), hestarted to work on the DRBD® replication software that is in themeantime successfully used around the globe. DRBD got accepted intomainline Linux with the 2.6.33 release. Philipp is an internationallyrenowned OSS specialist, kernel programmer and eminent lecturer on highavailability at international Linux events.)*

* **David Cermak** *(David Čermák has been operating for 10 years as technical director at PRO-ZETA and significantly contributed to the success of company expansion to more than 20 countries worldwide.David is an expert in Ethernet networking infrastructure, data centers and their security. In his more than 20 years of experience he is likely to be met with most of existing technology in the field of networks, data centers and running applications - from NetBIOS, IPX and Novell Netware to MPLS, NGN and construction of large-scale cloud services. He was co-founder of community networks CZFree.NET. David is a consultant for several operators and service providers in Europe and, if needed he is able to give even a module into the Linux kernel.)*

Persistent resilient storage for containers in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The next phase in migration of workloads from virtualized environments to containers is when mission critical workloads start moving to containers. These workloads will have requirements like persistent storage, live migration, storage resiliency.In this session you will be introduced to an implementation of an OpenStack storage provider which delivers persistent resilient storage for container based workloads.


* **Ketan Nilangekar** *(Ketan Nilangekar is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

* **Gaurav Makin** *(Gaurav Makin is a technical lead in the CTO group at Veritas Technologies LLC)*

* **Abhijit Dey** *(Abhijit Dey is a Sr. director of engineering in Information Availability at Veritas. He leads Cloud and Embedded Solutions within Storage Engineering team and is responsible for cloud, NAS and storage deliverables. Abhijit has worked in the storage industry for more than 18 years and is a technologist at heart. His key focus areas are Virtualization, OpenStack, Storage and Cloud. Abhijit is interested in participating in the OpenStack community and new-age storage innovations in the cloud ecosystem.)*

Residual IOPs based provisioning in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

M placement mechanism in OpenStack is easily extensible using nova filters. In this session you will be introduced to a new storage IOPs based filter which augments the nova filters to place VMs based on the available storage IOPs on the compute plane.


* **Ketan Nilangekar** *(Ketan Nilangekar is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

* **Rakesh Ranjan** *(Rakesh Ranjan is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

* **Abhijit Dey** *(Abhijit Dey is a Sr. director of engineering in Information Availability at Veritas. He leads Cloud and Embedded Solutions within Storage Engineering team and is responsible for cloud, NAS and storage deliverables. Abhijit has worked in the storage industry for more than 18 years and is a technologist at heart. His key focus areas are Virtualization, OpenStack, Storage and Cloud. Abhijit is interested in participating in the OpenStack community and new-age storage innovations in the cloud ecosystem.)*

Oracle ZFS Storage Appliance: Ideal for the cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Oracle ZFS Storage Appliance (ZFSSA) has features that make it ideal for the cloud environment. Some of the features are: hybrid storage pools where most sought after blocks of data are stored in the cache making it ideal of the virtualized workloads where multiple VMs of with the same base image are run, data encryption, copy of write snapshots and clones, performance and health analytics which can be used to identify utilization of individual VMs, RESTful interface for programatic management and provisioning for storage.


* **Kedar Vidvans** *(Kedar is a senior software developer working for Oracle. Kedar works with the Oracle ZFS Storage appliance(ZFSSA) team and is responsible for developing and maintaining ZFSSA storage drivers in OpenStack. Kedar has been associated with OpenStack since the kilo release.)*

* **Alka Deshpande** *(Alka is a senior software manager with Oracle having 20+ years of experience in the storage industry. Alka manages the team that is responsible for developing and maintaining Oracle ZFS Storage Appliance OpenStack drivers.)*

* **Juan Zuluaga** *(Juan is a principal software engineer with Oracle and has 15+ years of experience in the industry. Juan is responsible for developing and maintaining on the ZFS Storage appliance drivers in OpenStack. Juan has been associated with OpenStack since the juno release.)*

Ceph, now and later: our plan for open unified cloud storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph is a highly scalable open source distributed storage system that provides object, block, and file interfaces on a single platform.  Although Ceph RBD block storage has dominated OpenStack deployments for several years, maturing object (S3, Swift, and librados) interfaces and stable CephFS (file) interfaces now make Ceph the only fully open source unified storage platform. This talk will cover Ceph's architectural vision and project mission and how our approach differs from alternative approaches to storage in the OpenStack ecosystem.  In particular, we will look at how our open development model dovetails well with OpenStack, how major contributors are advancing Ceph capabilities and performance at a rapid pace to adapt to new hardware types and deployment models, and what major features we are priotizing for the next few years to meet the needs of expanding cloud workloads.


* **Sage Weil** *(Sage originally designed Ceph as part of his PhD research in Storage Systems at the University of California, Santa Cruz. Since graduating, he has continued to refine the system with the goal of providing a stable next generation distributed storage system for Linux.)*

Simplify your backup strategy using cloud storage with the Swift API
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn why OpenStack Swift cloud storage presents new architectures for protecting your vital business data. Instead of backing up to storage silos, using 3rd-party replication tools, or even hauling tapes to the mountain and back, cloud storage enables near-unlimited scalability without reducing performance, automatic disaster recovery protection by geo-replicating data to other locations, and a cost-effective hardware infrastructure based on standard servers and high-capacity SATA disk drives.


* **Paul Mayer** *(Over the past few decades, Veritas has been, and remains to be, a leading provider of data protection solutions. The Veritas NetBackup team is working on Swift API support to allow their customers to best leverage cloud storage. Paul Mayer is a senior member of the NetBackup product team at Veritas, focused on storage.)*

* **Doug Soltesz** *(Doug is currently a Director of Product Solutions at SwiftStack and has over 15 years of experience working in Information Technology. Prior to joining SwiftStack, Doug was VP of IT at Budd Van Lines. Doug has been recognized and received innovation awards in the areas of green initiatives, virtualization, disaster readiness, and workflow consolidation. Prior to Budd Van Lines, Doug was President of NetTech Solutions, a Systems Integrator servicing the NYC Metro Area.)*

Ready for Production - Swift3 - AWS S3 API on Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As more applications adopt Object Storage, it's important to cover all the bases. OpenStack Swift has a sister project, Swift3, that unlocks the S3 API on a Swift cluster. The Swift3 project has garnered much developer attention in the last year and is ready for production use cases. This session will detail the S3 features supported by the Swift3 project, recent improvements, benchmarks and upcoming enhancements, in addition to getting started with Swift3 on OpenStack Swift.


* **Doug Soltesz** *(Doug is currently a Director of Product Solutions at SwiftStack and has over 15 years of experience working in Information Technology. Prior to joining SwiftStack, Doug was VP of IT at Budd Van Lines. Doug has been recognized and received innovation awards in the areas of green initiatives, virtualization, disaster readiness, and workflow consolidation. Prior to Budd Van Lines, Doug was President of NetTech Solutions, a Systems Integrator servicing the NYC Metro Area.)*

* **Tim Burke** *(Tim Burke is a software developer at SwiftStack and core reviewer for swift and swift3.)*

Distributed file access in OpenStack Swift - development update and live demo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack developers have had all they need in the Swift API to build new applications and store unstructured data in Swift. But what about classic apps that are not yet refactored? And maybe there are requirements to read from or move data between Swift and NAS storage. At OpenStack Summit Austin, we introduced an architecture for adding distributed files capabilities to OpenStack Swift, which will be developed in a open project called ProxyFS. In this session, we will provide an update on development progress and demonstrate the current functionality.


* **Joe Arnold** *(Joe founded SwiftStack to deploy high-scale, cloud storage systems using OpenStack.Joe managed the first public OpenStack launch of Swift independent of Rackspace deploying multiple large-scale cloud storage systems. He went on to co-found SwiftStack and serves as CEO. SwiftStack powers enterprises with a software defined storage platform, built on the OpenStack Swift object storage engine, to build a massively scalable private cloud.Prior to working with OpenStack, Joe was the Director of engineering at Cloudscaling, where he managed OpenStack deployments at KT and Internap. Joe also headed up engineering for Engine Yard, overseeing the development of their Ruby on Rails deployment platform, AppCloud and managing the open source efforts of Rails 3, JRuby and Rubinius.Joe is the author of OpenStack Swift, published by O'Reilly.)*

* **Ed McClanahan** *(Ed McClanahan is a storage architect at SwiftStack and is a lead contributor to the ProxyFS project.)*

Dueling Demos: Petabytes of Ceph and Gluster in Under and Hour
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud workloads increasingly demand persistent data, accessible across distributed stateless application instances. Software-defined storage systems built on commodity hardware and operating environments are a natural fit to address this growing need. Join us in this session for a live demonstration standing up the two most popular software-defined storage systems, Ceph and Gluster, from bare systems to petabytes of protected storage in under an hour. We will provide a primer of the basics for each system and an introduction to common use cases, and then dive immediately into at-scale deployments using the most current techniques and toolsets. Attendees will gain core knowledge for the implementation of both Ceph and Gluster in enterprise environments and the confidence to begin building their own distributed persistent storage systems.


* **Dustin Black** *(Openness and transparency are keys to organizational success in the modern world. Innovation and progress are crowd-driven, and leadership today means being a steward of the community. I have been a proud disruptor of traditional and antiquated business practices and ideologies since the beginning of my career. And it continues as my mission to champion community over hierarchy and meritocracy over authority. With Red Hat, I've found an opportunity where disruption is the norm and my voice is always heard. I believe adamantly that this type of organization is the future of business success and human progress.   My career focus is on enabling enterprises to succeed with open systems and processes, and in fostering a sense of community that is agnostic of the norms of business boundaries. I have a passion for the customer experience, and I believe that each individual shares in the responsibility of positive brand impression. Among my technical expertise are:   • Linux   • Software-defined storage   • Cloud infrastructure   • Network engineering   • Security and risk   • Data center architecture   I am a proven successful mentor, taking far more pride in the success of those I've advised over my own personal triumphs. I am an experienced public speaker, presenting on technical topics at major industry conferences around the world.)*

Manila share data does not simply move and protect itself, oh wait, it does!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Typical datacenters comprise of products from multiple storage vendors, and usually no two products behave the same. Thus, operators often rely on complex scripts and tools to move data, provide high availability and protect it from disasters. As a multi-storage abstraction, OpenStack Manila is invested in addressing such requirements through a consistent API to avoid vendor lock-in. We have made tremendous progress with features such as Migration and Replication, and a new service that can handle data plane operations and assist in moving data between shared file systems. We enhanced the design of storage availability zones as failure domains and allowed for them to be consistent with Nova and Neutron availability zones. We will discuss use cases and demonstrate the use of these features while indicating best practices and troubleshooting tips that might come in handy when using both these features in your data center. We’ll also discuss the roadmap for these features.


* **Rodrigo Barbieri** *(Rodrigo is a core reviewer in Manila since Mitaka release, driver developer for Hitachi since Juno release, and a researcher in the field of Fault Tolerance. He is focused on Manila upstream development and has contributed with several new major features, notably Share Migration and Data Service. He started working with OpenStack in Juno release by deploying OpenStack distributions and developing Hitachi storage device drivers for Cinder and Manila projects.    )*

* **Goutham Pacha Ravi** *(Goutham is an active contributor to OpenStack Block Storage and Shared File Systems projects. Prior to OpenStack, he has worked on several projects involving data protection across storage systems. Aside from his code contributions, Goutham spends a lot of his time building cross project synchronization and advocating for user experience and API stability. He is the API working group liaison for the Shared File Systems project.)*

Ceph Storage in PayPal Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation with focus on how Ceph is used to provide a low cost block storage alternative in PayPal Cloud. Existing block storage in PayPal Cloud was expensive and not applicable for several use cases. Hence, we decided to onboard Ceph block storage and integrate it with the existing OpenStack deployment in PayPal. Ceph block storage is integrated with cinder as a separate backend so that users/customers could continue to use block storage but have Ceph as an option in addition to the existing backend. This presentation will focus on the challenges encountered to enable Ceph in PayPal Cloud and the solutions adopted to overcome them. We will cover the following topics: 1) Ceph Deployment and Configuration 2) Ceph RBD and OpenStack Integration 3) Enabling Ceph as Cinder backend 4) Ceph Performance Evaluation 5) Monitoring Ceph Cluster


* **Bharath Venkatakrishnan** *(Bharath is a member of PayPal Cloud team and focusses mostly on LBaaS component within it. His main focus has been on adopting/enhancing LBaaS within PayPal cloud. Prior to that, Bharath worked in Oracle with specific focus on Database Manageability, performance tuning etc.)*

Go - Why and what of Swift is moving to Go
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Swift is large-scale storage, and it has been successfully deployed in thousands of places all over the world. We're constantly looking for ways to improve performance and efficiency in the system. At its most basic level, Swift brokers network requests and disk access. Since networks and hard drives work very differently, managing each of these so they are both used efficiently is a difficult technical problem. This talk will cover the various strategies the Swift community has used over the years to provide better performance for end users. We'll examine each in detail, including their strengths and weaknesses. Finally, we'll conclude with a discussion on the current work that's being done to reimplement some parts of Swift in the Go programming language.


* **John Dickinson** *(John Dickinson is Director of Technology at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Object Storage. John serves as the Project Technical Lead for OpenStack Swift and has been involved in the development of Swift since 2009.)*

* **Clay Gerrard** *(Clay Gerrard is a Sr. Software Engineer at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Clay was part of the original development team at Rackspace that created Rackspace Files, which became the Swift project within OpenStack when it was made open source. Clay has continued to be active in the OpenStack community as a contributor to the Swift project.)*

Realizing the dream:  Openstack + Ceph for low-latency block storage workloads
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph continues to be the leading block-storage-of-choice for Openstack VM deployments. Latency-sensitive workloads such as databases remain an emerging Ceph use case - latency guarantee typically a challenge in shared VM storage environments as compute/networked-storage resources cease to scale as VM density increases. With growing flash footprint on clients, flash-based read/write caching has the potential to improve storage latency by reducing IO path dependency on network/cluster. We'll introduce an ordered, crash-consistent read/write-back cache native to the Ceph block layer. Blocks will be cached on client-side SSD/NVMe/3DXPoint/NVRAM device. A shared cache mode will be supported which is an ideal fit for VM master image cache. A big feature-up from current object-based, DRAM-based cacher - flash increases cache size on packed hypervisor and improves cache warmup on restart. We'll delve into the high-level design and demonstrate performance gains with this new Ceph-RBD cache.


* **Tushar Gohad** *(Tushar is part of Intel's Data Center Group where his primary area of focus is Software Defined/Scale-out Storage Architecture. Tushar has been working in the open-source networking and storage-related technologies for over a decade now – his recent contributions were to Erasure Code data path in OpenStack Swift, Intel’s Storage Performance Dev Kit (SPDK) and networking in the Linux kernel. Prior to joining Intel, Tushar was a lead open-source/Linux kernel developer at Cavium Networks/MontaVista Software where his focus was data-plane packet processing acceleration in all-Linux environments involving UIO, IPv6 enabling in the Linux ecosystem, Linux namespaces/containers and Linux IPsec scalability improvements. Tushar holds a Masters degree in Computer Science.)*

* **Jason Dillaman** *(Jason Dillaman is a software engineer at Red Hat and has been an active contributor to the Ceph project for over two years.  Jason currently acts as the project technical lead for the RADOS Block Device (RBD) module within Ceph.)*

Ceph BOF
~~~~~~~~

**Abstract:**

A lot has been happening in the Ceph world, from the inclusion of CephFS with Jewel to ongoing work around the new Bluestore backend. This Ceph Birds of a Feather session will update Ceph users on the recent work in both Ceph development and the community while giving them the opportunity to ask questions of some of the core developers.  Prior to the session users will be able to populate an etherpad with questions and topics they would like addressed [http://pad.ceph.com/p/cephbofbarcelona] and other Ceph experts will be on hand to share their recent work and experiences as well.


* **Patrick McGarry** *(Patrick is currently incarnated as a Director of Community at Red Hat working to spread the Ceph gospel.  An experienced community manager, gamer, mischief maker, and all around geek, Patrick spent five years writing and managing Slashdot under the nomme du keyboard 'scuttlemonkey.'  Patrick enthusiastically helps companies to understand and adopt Open Source ideals and continues to be a strong advocate of FOSS on the desktop and in the enterprise.  He has strong feelings about tomatoes, longs for his deep, dark cave, and still hates writing these bios. )*

* **Sage Weil** *(Sage originally designed Ceph as part of his PhD research in Storage Systems at the University of California, Santa Cruz. Since graduating, he has continued to refine the system with the goal of providing a stable next generation distributed storage system for Linux.)*

CephFS - The Good, the bad and the ugly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Is CephFS ready for real world workloads after it's first 'production-ready' release?  We'd like to share eBay's experience on building file sharing service with OpenStack and Ceph: how we evaluate the performance of CephFS,  what CephFS's performance looks like comparing to alternative solutions and how we may productionize file sharing serivce with OpenStack.  We'd also dig into CephFS's caveats/limitations and share our thoughts on possible workarounds.


* **xiaoxi chen** *(Xiaoxi Chen is a software engineer in eBay.  His interests is storage technology and distributed storage.  He's active contributor to Ceph.)*

The consequences of Infinite Storage Bandwith
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Overall increases in CPU and DRAM processing power are falling behind the massive acceleration in available storage and network bandwidth.  Storage management services are emerging as a serious bottleneck.  What does this imply for the datacenter of the future?  How will it affect the physical network and storage topologies?  And how will storage software need to change to meet these new realities?


* **Allen Samuels** *(Allen joined SanDisk in 2013 as an Engineering Fellow, he is responsible for directing software development for SanDisk’s system level products. He has previously served as Chief Architect at Weitek Corp. and Citrix, and founded several companies including AMKAR Consulting, Orbital Data Corporation, and Cirtas Systems. Allen has a Bachelor of Science in Electrical Engineering from Rice University. Allen is a member of the Ceph Advisory Board and is heavily involved in the evolution of this critical open source technology.)*

Understanding Cinder Performance in an OpenStack environment.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We will present our findings around storage performance for QEMU/KVM.  We look at hypervisor and VM storage tuning variables.  The number of VMs per host and different methods to connect storage to an instance and their impact on storage performance. We will also look at Cinder API performance for a large number of provisioning requests and other operations.


* **Ed Balduf** *(Ed Balduf is a Cloud Solutions Architect at SolidFire/NetApp, focusing on OpenStack, Containers and Agile Infrastructure. Ed wrote the SolidFire Puppet module, contributes to Cinder and container storage drivers. Ed has been working over 20+ years in technology, consulting and sales.  Ed is highly technical but has always chosen to work in roles involving interaction with customers and partners as he excels at solving new problems and knowledge sharing. Ed was most recently Sr. Staff Storage Architect with Fusion-io/SanDisk working with Hyperscale customers on scale out storage deployments. Ed lead Fusion-io’s technical efforts around OpenStack.     Ed has extensive history and experience in Fibre Channel, Real-time processing, NAND Flash, Training development and packet routing.)*

* **David Black** *(David works as an architect in NetApp's Central Field Labs, designing and demonstrating a wide variety of proof-of-concept environments for customers.  His areas of expertise are in virtualization and automation including OpenStack, storage performance, networking and security.  He holds the CISSP certification and is a frequent speaker at NetApp's Insight annual technical conferences.)*

* **John Griffith** *(John Griffith, Principal Software Engineer at SolidFire, helped to create the Cinder project in OpenStack.  His primary responsibility at SolidFire is technical contributor to OpenStack and Open Source technologies.  He served as Technical Lead for the Block Storage Project since it's beginning through the Juno release, and also has held an elected seat on the OpenStack Technical Committee on and off over the past four years. John has over fifteen years of engineering experience in both hardware and software engineering.  He’s been an active user and contributor to open source for close to a decade, and has been focused on OpenStack since January of 2011. In addition to his technical contributions, John also spends a lot of his time talking to people who are interested in learning about OpenStack as well as gathering feedback from current users.)*

Highly available, DR ready Storage platform for Multi-data center OpenStack private cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprises looking to deploy OpenStack based private clouds are looking to deploy multi-site data centers which are not only A/A but also are fully DR capable. For this OpenStack needs the underlying storage platform to be Highly available, DR ready providing high performance at low cost. In this session, we will showcase a 3 Data center A/A-A OpenStack private cloud deployment which is backed by highly available, fully DR ready and high performt software defined storage solution built completely on commodity x86 hardware using Direct Attached Storage and existing SAN


* **Sachin Lakhanpal** *(Highly Collaborative Engineering leader with 16 years mix of hands-on and leadership experience inmanaging Product Development, Quality (SW & HW) & Performance Engineering for Storage Managementfor On-prem and hybrid cloud Products. Leading Openstack communities of practice within Veritas Led Veritas engineers to make contributions to upstream projects. Leading development of Software defined storage platform and plugins for OpenStack. Led Veritas sponsorship and technical content submissions at the Austin summit. Co-presented Storage Multitenancy for OpenStack Brownbag session at the Austin summit with Abhijit Dey)*

* **sarat inuguri** *(Sarat is a principle software engineer working on Symantec storage NAS appliance product. He was part of Veritas File System development team prior to this. He has been working lately to integrate Symantec's NAS appliance with OpenStack Cinder and Manila.)*

Cinder storage benchmarking using vdbench and Heat orchestration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, I will describe using Heat orchestration to build a parameterized and scalable VdBench based system to run IO tests on cinder storage backends.  VdBench is a flexible Java-based IO generator written by Henk Vandenbergh of SUN microsystems and now Oracle.  VdBench can be configured to run in a master/slave configuration with all reporting through a central web repository.  This process can be used to compare drivers, configurations, resilience and performance of different storage platforms.


* **Daniel Rooke** *(I am working on deploying redhat's Liberty release and I support several icehouse clouds.  I've been working with Unix/Linux since the 90s and got into OpenStack in 2014 when I had to come up with a storage platform for the cloud team.)*

Bring your own backup vendor!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We are proposing a backup service with RESTful interface to discover instances, create guest quiesced, CG snapshots of Openstack instances that can be read out for backup, archiving, DR. The APIs would allow any backup vendor to read vdisk snapshots, block map, changed blocks (since previous backup) from outside of Openstack over HTTP(S) by a backup vendor or from within a service running in Openstack (for existing backup drivers). The proposed backup service would internally communicate with nova for discovery and taking instance level (image) snapshots. The service would mount cinder snapshots as block devices over different protocols, e.g. Iscsi, SAN, librados etc. to local system as it does today and would expose them over RESTful APIs. Eg. A snapshot read interface would look like : “https://<IP>:<PORT>/backup/v1/read/<vdisk snap id>” along with POST data containing a list of offset,length pairs for vdisk blocks to be read.


* **Ketan Mahajan** *(A software professional with 9 years of experiance on storage technologies. Currently working with Veritas on OpenStack storage technologies.)*

* **Ravindra Teli** *(A software professional with 17 years of experiance on storage technologies. Currently working with Veritas on OpenStack storage technologies.)*

GlusterFS as Storage for OpenStack: Pros and Cons and how to get started
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Pros and Cons and how to get started GlusterFS has been overlooked when it comes to a backend storage solution for OpenStack.Yet, it's the obvious choice over many others for KVM deployments.How can this be? In this discussion I'd like to touch on: What use-cases is GlusterFS great for? What use-cases is GlusterFS just OK for? What use-cases is GlusterFS a bad choice for? Performace metrics for: Epemeral, Block, & Objcet Storage What are the architecture decisions that need to be made when deploying GlusterFS? How do you monitor it to ensure GlusterFS is healthy. How do you get started?  


* **Cody Hill** *(Prior to joining Platform9, Cody was the Lead Cloud Architect at General Electric, where he built an enormous private cloud based on VMware vCloud Director spanning North America, Europe, and Asia. With more than 10 years of IT infrastructure experience across multiple industries, he brings a wealth of knowledge and expertise, particularly as an enterprise IT practitioner and strategist in one of the world’s largest technology shops.cod)*

Data migration solution from on-premise or public cloud to OpenStack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprises wanting to use OpenStack in their private cloud environments face the challenge of migrating their current data to OpenStack. The current data may reside on premise or some of it in another public cloud. In this session we will showcase the scalable Veritas NAS solution that can migrate the data from on premise or other public cloud to OpenStack using intuitive policy based framework.


* **sarat inuguri** *(Sarat is a principle software engineer working on Symantec storage NAS appliance product. He was part of Veritas File System development team prior to this. He has been working lately to integrate Symantec's NAS appliance with OpenStack Cinder and Manila.)*

* **Sachin Lakhanpal** *(Highly Collaborative Engineering leader with 16 years mix of hands-on and leadership experience inmanaging Product Development, Quality (SW & HW) & Performance Engineering for Storage Managementfor On-prem and hybrid cloud Products. Leading Openstack communities of practice within Veritas Led Veritas engineers to make contributions to upstream projects. Leading development of Software defined storage platform and plugins for OpenStack. Led Veritas sponsorship and technical content submissions at the Austin summit. Co-presented Storage Multitenancy for OpenStack Brownbag session at the Austin summit with Abhijit Dey)*

Eliminating bottlenecks by rethinking storage design
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The traditional design of Distributed FS binds storage control nodes and storage media within a storage server, and connects storage servers by Ethernet networking. All of major DFS such as Ceph, HDFS and Gluster FS use the same design. Nowadays, this old design already constitutes the bottleneck of storage system. It is the time to rethink this old design, and make a change. SurFS introduces a new architecture. It separates storage control nodes from storage media but rather converges storage control nodes and compute nodes resulting in extremely short I/O path. SurFS also leverages SAS-3 networking which has very large bandwidth (up to 96Gb) and very low latency (a few microseconds) to constitute an ultra-fast storage system at low cost. Furthermore, this new architecture has a unique feature of globally shared storage pool. This feature enables RAID for DFS (instead of RAIN) to reduce 50%+ disks at same data durability, which is ideal for HA and enabling re-balancing in seconds.


* **Alex Wang** *(Alex is an excellent innovator. He was nominated as one of the Top 10 Youth Scientist by the Chinese central government in 2010. He was also recognized as one of the distinguished engineers (the only one coming from software and Internet industry) in China in 2014. Alex began to innovate on cloud storage systems in 2011. His first project SurDoc won the “Cloud Storage Excellence Award” by US Cloud Computing magazine in 2013, got 10M+ users worldwide within 2 years upon its service launched. Alex is founder of a Silicon Valley company SurCloud. He is also 1st inventor of 100+ patents worldwide.    )*

Swift at Scale: The IBM SoftLayer Story
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Come hear IBM SoftLayer's OpenStack Swift story and lessons from operating public object storage.IBM's SoftLayer began its OpenStack journey in early 2012 when it launched public OpenStack Swift clusters in three of its global datacenters. Over the last 4.5 years, it has added Swift clusters into 22 additional datacenters at break-neck pace, launched several multi-facility Swift clusters, and expanded global storage capacity by several orders of magnitude. Join us for this session as we share the story of our journey running Swift at scale over the years.


* **Brian Cline** *(Brian Cline is the development team lead for IBM SoftLayer's Object Storage product, which is built on OpenStack Swift. At SoftLayer, he and his team help to enhance the product's feature set, improve release management, testing, and deployment through automation and continuous integration, as well as operational efforts to keep things running smoothly. Since joining SoftLayer in 2012 he has been deeply involved in research, backend services development, OpenStack, Swift, cloud storage, and automation.  )*
