Products & Services
===================

Multi-Site OpenStack Cloud Orchestration With Integrated WAN and Public Cloud Connectivity
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk CPLANE NETWORKS will describe how its Multi-Site Manager (MSM) for OpenStack seamlessly orchestrates compute, storage and networking resources across globally distributed cloud computing sites.CPLANE recently announced the selection of MSM by PCCW Global, a major communications service provider, to orchestrate OpenStack resources for its global cloud service. MSM provides API consolidation and correlation from Horizon and northbound business support systems and then seamlessly orchestrates OpenStack resources (including user authentication via Keystone) across multiple sites. In addition to using CPLANE’s data center networking for its OpenStack cloud center networking, our Overlay Gateway Router (OGR) provides VXLAN virtual overlay connectivity to PCCW Global’s wide area network and public clouds. This talk will present an architectural overview of MSM and a demonstration of multi-site OpenStack service orchestration.


* **Saurabh Mohan** *(Over ten years of experience as networking software engineer and architect. I have been part of companies and product as co-founder, early team member at startups and through acquisitions by large networking product vendors. Helped with product definition, product roadmaps and taken products from concept to successful delivery to customers. Experience in multi-threaded-using Intel dpdk- and ASIC based data-path of network router and switches and supervisor architecture of network routers and switches. Authored new Linux kernel networking module (ip_vti.ko). Filed and issued three patents. I have extensive experience with building security features like IPSec VPN, L2TP. Virtual networking expertise with Openstack (neutron), ovs, overlay networking. Integration with kvm, qemu. Name-space (container) overlay networking.)*

* **John Casey** *(John Casey contributes over 20 years of deep technology leadership. His proven success with a variety of technical leadership roles in Telecom, Enterprise and Government and in software design and development provide the foundation for the system architecture and engineering team. At CPLANE NETWORKS John is responsible for all aspects of technical strategy and innovation, and product engineering.  Previously John led worldwide deployment teams for both IBM’s Software Group and Narus, Inc. His work in large scale, high performance system design at Transarc Labs and Walker Interactive Systems brings leadership to the CPLANE NETWORKS product suite.)*

OpenStack to external network/public cloud integration with x86-based gateways
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk CPLANE NETWORKS will describe how its Overlay Gateway Router (OGR) can be used to provide OpenStack-enabled data center VXLAN virtual overlay connectivity to external network resources such as MPLS networks, legacy infrastructure, or public clouds such as Amazon Web Services. OGR, which runs on any x86-based device as a physical or virtual network function (PNF/VNF) utilizes CPLANE’s SDN Service Orchestration Platform for configuration and management services. The Platform provides a common service framework for all of CPLANE’s data center, wide area, and edge network services. OGR uses the same Open vSwitch (OVS) that provides compute node networking for CPLANE’s Dynamic Virtual Networks – Data Center (DVNd) VXLAN virtual overlay product. The session will include a demonstration of provisioning gateway connections via CPLANE user interface (console) and/or APIs.


* **Saurabh Mohan** *(Over ten years of experience as networking software engineer and architect. I have been part of companies and product as co-founder, early team member at startups and through acquisitions by large networking product vendors. Helped with product definition, product roadmaps and taken products from concept to successful delivery to customers. Experience in multi-threaded-using Intel dpdk- and ASIC based data-path of network router and switches and supervisor architecture of network routers and switches. Authored new Linux kernel networking module (ip_vti.ko). Filed and issued three patents. I have extensive experience with building security features like IPSec VPN, L2TP. Virtual networking expertise with Openstack (neutron), ovs, overlay networking. Integration with kvm, qemu. Name-space (container) overlay networking.)*

* **John Casey** *(John Casey contributes over 20 years of deep technology leadership. His proven success with a variety of technical leadership roles in Telecom, Enterprise and Government and in software design and development provide the foundation for the system architecture and engineering team. At CPLANE NETWORKS John is responsible for all aspects of technical strategy and innovation, and product engineering.  Previously John led worldwide deployment teams for both IBM’s Software Group and Narus, Inc. His work in large scale, high performance system design at Transarc Labs and Walker Interactive Systems brings leadership to the CPLANE NETWORKS product suite.)*

Identity-as-a-Service for Cisco Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Identity management is one of the primary challenges when developing next generation Cloud Native applications and services. These services span across clouds, PaaS layers, and can be entrenched deeply in private Cloud deployments. These disparate platforms can each have unique policy, governance, and identity management systems. Cisco Cloud Services has been developing a next generation Identity as a Service (IDaaS) offering poised to change the way developers can manage identity across disparate platforms while being powerful, open and flexible. In this session you will learn about the architecture, functionality and capabilities of this new IDaaS offering. You will also learn how the IDaaS APIs can be used to incorporate identity management into your Docker Container apps, traditional services, and innovations.


* **Klaas Wierenga** *(Klaas Wierenga is the Identity Architect for Cisco Cloud Services, responsible for designing the identity architecture for the Cisco Intercloud. He has many years of experience in the fields of identity and mobility but is relatively new to the OpenStack scene. In the past he has designed a number of identity management systems and he is the creator of eduroam, the WiFi roaming service in academia. Klaas is active in standards bodies related to identity and mobility and currently serves as chair of the IETF Abfab working group, that works on federated authentication for non-Web applications.)*

* **Krishna Athur** *(Krishna Athur is a Technical Leader at Cisco's Cloud Infrastructure Services group, He has over 10 yrs of experience in  Identity and Security area. Specilized Implementing in complex and challenging environments. Krishna is currently working on enabling Identity and Security over cloud for Cisco's various cloud offerings.)*

* **George Chogovadze** *(Xxx)*

Testing Cloud Forms integration with openstack providers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A talk about the testing process of cloud forms integration with openstack.Make long story short: The Cloud Forms (CFME), and Red Hat Openstack, (RHOS) integration raise many challenges that a simple UI tests did not raise before. how to test the undercloud which is on the control plane network, the networking issues what type of use cases testing the undercloud will be achieved How do we monitor the metrics of RHOS undercloud during RHOS overcloud deployment Automating the tests in local testing environment Panel: manageIQ CFME, testers developers.  web testers/developers


* **Ronnie Rasouli** *(Red Hat employee. A software engineer Computre and technology enthusiastic.)*

SEN - A Modular and Extensible Cloud Scheduler
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

SEN is a general purpose open source cloud scheduler project. It tracks CPU, memory and other resources to determine scheduling policy. It has extensible architecture with two main goals: to support various cloud computing solutions on the market including OpenStack, and to allow addition of new scheduling algorithms and configuring the current ones. SEN comes with 2 virtual machine/volume placement algorithms to be readily used, namely RoundRobin and BestFitDecreasing which particularly aims energy efficiency on the cluster. Machine learning based VM placement algorithms are also being studied by SEN team. SEN takes account of affinity definitions, CPU models, and migration cost of the new VM placement while calculating the algorithm. SEN core and its OpenStack adapters are implemented and ready to be used. It is tested with various CPU, memory loads, flavors and heterogeneous CPU architectures on Mitaka and Liberty. Energy consumption is measured using hardware energy logger device.


* **Hayati Gonultas** *(Hayati GONULTAS had his bachelor degree from Istanbul University Computer Engineering Department, and masters degree from Gebze Technical University. He's been working at TUBITAK BILGEM since 2006. He has experience on linux system programming, network programming, big data technologies, and Openstack administration and development. He is currently working on cloud and big data projects in Cloud Computing and Big Data Research Laboratory (B3Lab) at Information Technologies Institute, TUBITAK-BILGEM Openstackdaysistanbul 2016 - Speaker Mirantis Certified Administrator for OpenStack - Professional Level Certified Scrum Master PSM I B3LAB Big Data Summer School - Instructor (2013, 2014, 2015) Projects: SEN - Scheduler Enhanced: http://b3lab.org/sen-scheduler-enhanced Damla Search Engine: https://goo.gl/H0wrr9 SKAAS (Digital Storage Archive and Analysis System): http://goo.gl/ofuVY7 BETASIS (Document Tracking System): http://goo.gl/ieXek0  )*

Operations as a Service: Lessons learnt operating multiple Cloud Foundry on OpenStack deployments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

According to OpenStack users survey, Cloud Foundry is the 2nd most popular workload on OpenStack. You want to deploy Cloud Foundry on OpenStack or already have. What's next? Cloud Foundry continues to evolve with revolutionary changes, e.g move from bosh-micro to bosh-init, using the new eCPI, move to Diego etc. Same with OpenStack, e.g changes from Keystone v2 to v3, from Liberty to Mitaka, network plugins changes etc. Both IaaS and PaaS layers are changing frequently. How do you do in-place updates/upgrades/operational tasks without impacting user experience at both the layers? In this talk will discuss our lessons learnt operating hybrid Cloud Foundry deployments on top of OpenStack over the last two years and how we used underlying technologies to seamlessly operate them 1. BOSH2. Razor3. Ansible playbooks via Ursula4. Jenkins 5. Graphite-ELK6. Rally We will also detail community tools to validate if Cloud Foundry deployment will work on your OpenStack etc.


* **Animesh Singh** *(Animesh Singh is an STSM and Lead for IBM Cloud Platform and Infrastructure. He has been with IBM for more than 10 years and currently works with customers in designing cloud computing solutions on OpenStack and Cloud Foundry. He has been leading cutting edge projects for IBM enterprise customers in Telco, Banking, and Healthcare Industries, around cloud and virtualization technologies. He has a proven track record of driving design and implementation of private and public cloud solutions from concept to production. He also led the design and development first IBM public cloud offering, and is currently leading initiatives in IBM around OpenStack, CloudFoundry and Bluemix)*

* **Jesse Proudman** *(In 2003, technology entrepreneur Jesse Proudman parlayed his passion for the “plumbing” of the Internet into the creation of Blue Box Group, a Seattle-based private cloud hosting company. As Founder and CTO, Proudman has guided the company’s rapid growth and multiple successful funding rounds. He received GeekWire’s 2014 Young Entrepreneur of the Year honor,  and is a member of the 2013 class of Puget Sound Business Journal’s 40 Under 40. A regional semifinalist for the Ernst & Young Entrepreneur of the Year award, Jesse is a well-regarded speaker, writer and contributes as a leader and coder in various open source projects. In mid-2015, Blue Box was acquired by IBM to become a cloud innovation hub in Seattle.)*

How to support both public cloud and heterogeneous "backend resources" based on a newframework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Now openstack has the ability of managing private and other public cloud resources simultaneously with the help of the new framework we created. The framework offers the same interfaces with the core component of openstack, so the dashboard/CLI can do the same thing with private and public cloud, and even backup resources between clouds. Currently, one of our customers TCL is using the framework to manage his private resources and aws resources effectively, and another customer,the BGI, also used the framework to manage his private resources and aws,ali resources.


* **Yang Li** *(Have worked for 7 years in software development, worked in Fujitsu before and joined in EasyStack in 2015. Now force on OpenStack Neutron, NFV and hybridcloud development.)*

Billing for OpenStack Solution and Cloud Storage Solution based OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Abstract: OpenStack is a one of the large opensource. And It has various projects and eco systems. Best point of Openstack is RESTful API, anybody can connect. Many companies is adopting for building public, private, hybrid cloud environment.  Also company developing some application they need is a lot. Currently We are working about building and consulting  cloud environment using OpenStack. And we are deveploping billing system for OpenStack and Cloud Storage system based OpenStack Swift. We have built OpenStack to many companies. so we have variety use-case and expriences about solving problem knowhow and their requirements. So we would like to talk about our OpenStack exprience and technologies of our products for OpenStack. We love to share our open source expriences such as architecture of products, process, knowhow about solving problem and how to integrate OpenStack.


* **Nalee Jang** *(It was 5 years ago when I met Openstack. That time, I was a java programmer. so I was difficult about linux, system, network, openstack, opensource and etc. but I was happy because I could know new technologies. and I have worked hardly. After few years, I became a OpenStack Korea user group leader. and I colud publish a book about openstack. so I have sharing my experience to young people and OpenStack beginners. Now I am working with Openstack at ASD Korea.)*

* **Dmitry Malin** *(Over 10 years of experience in IT-business management. Worked for top Russian search engine Rambler, previously founded succesfull BI-analytics start-up.)*

Testing IBM Blue Box Cloud the OpenStack way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ursula is a collection of open source Ansible scripts that IBM uses to deploy its IBM Blue Box OpenStack clouds.  It comes with some basic multi-node OpenStack regression and integration tests that we have setup to run against every proposed change to the codebase.  The infrastructure services we use to accomplish this differ from upstream in almost every way, though. Where upstream uses Gerrit, we use GitHub.  Where upstream uses Zuul, we use Jenkins.  Where upstream uses Nodepool for multi-node provisioning, we use Heat.  So, what would it take to get these tests running the "OpenStack Way" (e.g. with nodepool and zuul) and what would the preceived benefits, drawbacks, and challenges be with this solution? This talk will attempt to answer these questions by walking through our evaluation with the hope it will prove educational both to prospective users of these infrastructure services and the people developing them.


* **Tim Chavez** *(Tim has spent the better part of eight years developing continuous integration solutions with open source technologies.  Currently, Tim is the CI squad lead for IBM Blue Box, where he works with a team of engineers to build, deploy and support the foundational services used to develop and test our private managed cloud product offering.  Prior to IBM, Tim worked at Hewlett Packard Enterprise as a developer on Gozer which was an internal deployment of OpenStack infra services that ran thousands of tests per month for a diverse set of customers.)*

Crowd sourcing OpenStack Operations - A walk through OpenStack Charms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Capturing and re-using OpenStack Operations best practises: introducing the OpenStack Charms project. Sadly operating an OpenStack cloud is still a challenge for many organisations. with basic tasks such as upgrading, expanding and enhancing requiring knowledge and experience. If we are able to capture operations best parctises in code and build community around it then we can help accelerate the proliferation of OpenStack. The OpenStack Charms project aims to do exactly this by providing operators and developers with a means of sharing operations best practises in code so that individual organisations are not having to learn as they go.


* **Mark Baker** *(Product Manager at Canonical where I've spent the last 5+ years helping shape Ubuntu server and Ubuntu OpenStack. Previously held positions MySQL and Red Hat helping them disrupt Billion dollar encumbant enterprise software companies. Seem to be on the same path with OpenStack and Ubuntu.)*

HPE Helion Openstack and VMware NSX Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enabling enterprise grade networking and security.  The talk will discuss how we achieved this, taking into account issues, challenges and problems that we had along the way.  This is from collaborating upstream to providing a packaged solution to customers.


* **Gary Kotton** *(Gary is an active contributor to OpenStack upstream. He is a Neutron core team member and a core member for the stable branch. In addition to this he is contributing to OSLO and Nova. Prior to joining VMware Gary worked at Red Hat and Radware working on various networking technologies and virtualization.Between balancing work and family Gary runs for fun.)*

* **Ed Bak** *(Ed Bak is a Senior Networking Engineer at Hewlett-Packard Enterprise.  He is currently working on HPE Helion Openstack as the lead for the HPE Neutron engineering team.   He has been an upstream contributor for Neutron and Nova and has been working with Openstack since the Diablo release.   )*

Bright OpenStack
~~~~~~~~~~~~~~~~

**Abstract:**

Integrated with Ceph, Kubernetes, Puppet, Hadoop and Spark deployment/management? Check. Single pane of glass between physical and virtual layers? Check. Extensible? Check. (Multi-threaded) OpenStack Deployment in under 10 min? Check. Can provision and configure 3000 nodes from scratch in under 30 min? Check. Monitor everything from physical hardware, through operating system, Ceph, hypervisors, virtual hardware, up to virtualized os/processes? Check. OVS/LB plus VLAN/VxLANs? Check. Virtualize OpenStack controller nodes? Check. Cluster-as-a-service? Check. OpenStack/Hadoop/Ceph/Anything-as-Service? Check HPC jobs across physical nodes and VMs? Check. Bright? Triple Check.


* **Piotr Wachowicz** *(Piotr Wachowicz is a Cloud Integration Lead for Bright Computing. He's passionate about clouds, networking, and all things software defined. He's been working with OpenStack for several years, and his daily focus is looking after the deployment process, and management/monitoring of Bright OpenStack.)*

How to build an OpenStack offering with out-of-tree drivers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many technical challenges and triumphs of building OpenStack with a non-x86 hypervisor.  This session will compare and contrast building an OpenStack solution on x86 vs on IBM z systems. We will focus our comparison on server deployment in Nova, network deployment in Neutron and performance monitoring in Ceilometer.  The session will answer the question if it is possible for SUSE and IBM to create an OpenStack solution for z/VM that allows the hypervisor to keep its unique value statements and whether the same architectural assumptions as on x86 are still valid.


* **Dirk Müller** *(Dirk Mueller is a Senior Software Engineer working at SUSE currently focusing on Cloud, OpenStack, SUSE's deployment and OpenStack distribution. He's being developing for and using Linux for more than 15 years and is doing Software packaging, distribution and software development for more than 10 years. Dirk is currently involved in the RPM Packaging for OpenStack project as a PTL and core contributor and has spent recently effort in extending SUSE OpenStack Cloud to other architectures than x86_64.  )*

* **Emily Hugenbruch** *(Emily has been working on IBM mainframe virtualization for 10 years, specializing in functional test, systems management and CPU virtualization.  She contributes to the OpenStack Tempest project and writes the occasional blog on OpenStack.  She has attended the Kilo and Liberty summits and given Brown Bag talks and webcasts on IBM z/VM and OpenStack.  She's also leading the mentoring initiative for the Women of OpenStack group.)*

LBaaS through the Looking Glass
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we zoom in and take a closer look at LBaaS. What were some of the problems we faced in our customer deployments? Learn how we overcame some of the unique challenges in the real world. Take a deep dive into out our enterprise grade LBaaS solution, showcasing high reliability, scale-out and flexible automated licensing. Let us collaborate, think big and leap forward together in the LBaaS journey ahead.


* **Dhanashri Patil** *(Dhanashri works as a Staff Engineer at Brocade. She is very passionate about Computer Networking and very excited to be working on Cloud and SDN projects that solve real world challenges.)*

* **Ajay Bharadwaj** *(Ajay works as a Senior Product Manager with the Software Networking Business at Brocade. Brocade’s software networking strategy is to invest in an open, vendor-agnostic platform for SDN and NFV technologies. His role within the Product Management team has been to lead several key inititiaves for the vADC portfolio. He is passionate about bringing things to market in a manner that best serves the needs of customers and the technical community at large. Working with the team and partners to develop and build an Openstack offering is a key step forward.     )*

* **Matthew Geldert** *(Matthew works as a Staff Engineer at Brocade. He is an expert on Cloud and OpenStack technologies.)*

Hyper-Converged Red Hat OpenStack Platform and Red Hat Ceph Storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation describes how to deploy Red Hat OpenStack Platform and Red Hat Ceph Storage in a way that both the OpenStack Nova Compute services and the Ceph Object Storage Daemon (OSD) services reside on the same node. A server which runs both compute and storage processes is also known as a hyper-converged node. There is increasing interest in the field for hyper-convergence for cloud (NFVi and Enterprise) deployments. The reasons include smaller initial deployment foot prints, a lower cost of entry, and maximized capacity utilization. The presentations covers the customization of TripleO and Ceph-Ansible to produce a completely automated hyper-converged deployment which supports adding new nova/osd servers, configuration updates and software upgrades. It also covers tunings made to the system in order to improve performance and isolate resources with NUMA. These tunings are then applied in an automated fashion using the same techniques covered in the configuration section.


* **John Fulton** *(John Fulton works in Systems Engineering at Red Hat and focuses on OpenStack and Ceph integration with TripleO and Ansible. He has spent the past six months focused on hyper-converged OpenStack/Ceph deployment; i.e. running Nova Compute and Ceph OSD services on the same servers. Prior to joining Systems Engineering John worked with customers in the highly competitive Financial Services Industry as a technical resource to build private clouds based on Open Stack. He blogs at johnlikesopenstack.com.)*

Getting to Scalable Networking with Red Hat OpenStack and Juniper Contrail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With multiple complex networking options out there, Red Hat and Juniper have partnered to simplify the deployment of software-defined networking (SDN) for OpenStack. Join us to hear about our efforts deploying Contrail, what the future holds for Red Hat’s OpenStack Platform director-based SDN deployments, and current successes in the field. We will talk about: Current SDN deployment challenges in OpenStack What Red Hat and Juniper have done to improve this today The future of composability and what that means for director deployments Lessons learned from deployments in the field Benefits of a combined continuous integration infrastructure


* **Guil Barros** *(Guil is an OpenStack Product Manager at RedHat focused on partner enablement. He works with internal and external engineering groups to leverage our partner value-add towards making OpenStack easier to consume. His personal mission is to remove barriers to entry in the OpenStack space.)*

* **Michael Henkel** *(Prior to joining Juniper in 2014 Michael worked 16 years for HP. In HP he spent his last 2 years on doing research on SDN and writing applications unleashing the power of SDN. Michael is passionate about SDN and virtualization. As part of Junipers Contrail team he takes care for integrating OpenContrail into whatever kind of new and exciting technology comes along. Lately he started to enjoy the brave new world of Containers and their need for a robust networking infrastructure.)*

* **Nagendra Prasath Maynattamai** *(Taking care of Integrating contrail with other platforms, provisioning and packaging.)*

What did we learn: The road of productize OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

More vendors starts to build commercial products based on OpenStack community releases, which is very good for OpenStack society. But it is not as easy as it sounds, in order to build commercial products on top of OpenStack, considering continues evolution, one should got involved deeply to the community, and thinking carefully about the product planning strategy, R&D process, HR structure and product release pace. Nevertheless, how to effectively synchronize OpenStack upstream and downstream product development, how to overcome the gap for QoS and sercurity standards between upstream and commercial products and how to fulfil customers requests that are ahead of OpenStack community's ability are also what vendors should care about. In this session, we will ilustrate the problems we meet in our way of building products based on OpenStack, share the lesson we learned and what we did to overcome them. Moreover, we will share the ideas and thinkings during our R&D process evolution.


* **Zhenyu Zheng** *(Zhenyu Zheng joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Nova, Searchlight.)*

* **Rui Chen** *(RuiChen is a OpenStack upstream developer team leader at Huawei, he has joined into OpenStack community since the Icehouse release. RuiChen is active contributor in OpenStack development mainly in OpenStackClient, Nova and Congress. Follow RuiChen on his blog, http://kiwik.github.io)*

* **Sheng Liu** *(Devoting to OpenStack community contribution, especially in Ceilometer(renamed to "Telemetry" now) project, Sheng Liu have done well in code commit, code review, community involvement to improve Ceilometer capability, stability, usability, etc. In 2015.9, Sheng Liu has been proposed as a core contributor of Ceilometer project. In the last 2+ years working for Huawei, Sheng Liu have also participate development works of Huawei's FusionShpere OpenStack product, and mainly involved NFV scoped features in Nova, such as Numa instance, SRIOV support.)*

ATSDS – API Tracking and Selective Debugging System
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operations biggest challenge is to quickly find the cause of the API failure without disruption. Openstack consists a mesh of services running on various nodes. If, an api fails, one has to find the error and then figure out the real cause. Since there are many services involved, it is challenging to pin point the cause of the issue. Typically, a person raises the logging level of services to DEBUG and then re-issue the API in question. This brings forth following challenges: User need to do this on each node where the service is active or shutdown the service on all nodes but one. Since logging level is increased to debugging at the service level there would be lot of logging data being pushed to log files. This proposal presents an architecture where users can track the API request flow through various services and enable logging for specific API requests, without modifying the configuration files and without restarting any services.


* **Prateek Goel** *(Passionate about techology and innovation. Currently working(1 year) with Tata Communications for Openstack based cloud development. Worked with Nova, Cinder, Neutron, Ironic, Ceilometer projects. Have done various enhancements in nova, cinder for datastore selection. Have enabled CAS in keystone as a plugin. Currently working on platform reliability, availability and serviceability. Prior to this, I have 8 years of experience with IBM Software Labs on AIX kernel and user space development. Primary area of work was dynamic tracing tool ( ProbeVue), Virtual Memory Manager, Procee Management, user and Kernel space debugging using languages C and Assembly language. In user space experienced with perl, shell scripting.   )*

OpenStack Director using Opendaylight to manage underlay and overlay networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we’ll demonstrate how to use OpenStack Director (OSP-D) along with Opendaylight (ODL) controller to exploit a full-fledged stack. OSP-D is an OpenStack installer introduced with Kilo-based RH-OSP-7. ODL is a software-defined network (SDN) controller and is used here to manage both underlay and overlay networks, enabling different OpenStack components to function in harmony with each other. Open vSwitch Database (OVSDB) clustering in ODL can be used to achieve highly available infrastructure. You’ll also see OpenFlow rule modifications that allow the underlying Kernal-based Virtual Machines (KVMs) to communicate with each other. We’ll show how the east-west and the north-south traffic flows in such an implementation on the overlay network, and how the transition happens from L2->L3 from the overlay-underlay network using openflow table transitions. An add-on to this demo will be learning to use Ansible Tower to job-schedule various steps of OSP-D installation.


* **Anand Nande** *(Senior Technical Support Engineer at Red Hat and a Cloudophelic who loves to learn and experiment with various upcoming technologies to develop better solutions to migrate the physical workloads to cloud.)*

* **Janki Chhatbar** *(Janki Chhatbar currently works as software engineer in RedHat. She has experience of working with different SDN controllers, OVS switches and OpenStack. She is contributor to OpenStack Tacker. She writes about different technologies including Docker at simplyexplainedblog.wordpress.com.  )*

Automated path to Red Hat OpenStack Platform Certification? Yes, please.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A successful Openstack deployment is only possible if all layers of the system play well together, from the hardware all the way up to the cloud applications.All the components that make up OpenStack are thoroughly tested independently, but it is hard to know how they would end up behaving once put together.Red Hat provides a unique way for its partners to continuously test their setups with the latest snapshot of the Red Hat OpenStack Distribution.This approach has several benefits:  * Catch bugs as early as possible with a battery of tests.  * Extend the testing ecosystem beyond the Red Hat walls and into partner's environments.  * Make partners an integral part of the Red Hat OpenStack Distribution development cycle.  * Speed up the Red Hat OpenStack Certification process for partners.As a result of being part of this effort, if a partner has a passing CI when the engineering team decides to make the cut for the new release, their platform can be certified from day 1


* **Yanis Guenane** *(Yanis works as an Infrastructure Automation Engineer for RedHat. Passionate about automation, he wishes he can automate everything - OpenStack included. His favorite configuration management tool is Puppet which he has been working with for the past 3 years.)*

* **Yassine Lamgarchal** *(Yassine is a Software Enginner at Red Hat. His main interest is the distributed systems. During his free time, he plays balisong and maintains tropical fishes.)*

Managing Containers and Clouds with ManageIQ
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers are becoming the standard delivery method for modern applications. Managing them next or on top of existing Infrastructure as a Service or traditional Virtual Environments require new tools which provide automatic relationship discovery, insight into Virtual Machines or Containerized Applications, and powerful reporting features, from one unified web interface. ManageIQ (www.manageiq.org) allows operators, developers and decision makers to retrieve the information they need, and also provide the management capabilities to support their daily tasks. This presentation will give an overview of ManageIQ, how it can manage multiple Container, Cloud and VIrtualization Providers and some examples how it can be integrated into small to large enterprise organizations.


* **Christian Jung** *(Christian Jung is an EMEA Technical Specialist for CloudForms, the supported product based on ManageIQ, and has been with Red Hat since 2006. Members of this team are supporting customers, Red Hat Consultants and Architects in designing and implementing cloud solutions based on CloudForms, OpenStack and other emerging technologies. In the past he was working as an Infrastructure Consultant at many European customers and partners.)*

Rackspace and Dell partner with Red Hat to Continuously Improve OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Dell and Rackspace partner with Red Hat to offer OpenStack as the platform of choice for Enterprise and Midmarket customers alike. Building a better solution together takes more than just certifying the platform once, it requires continuous improvement and testing across multiple platforms. Red Hat’s unique approach to Distributed Continuous Integration makes this possible by extending the testing ecosystem out to the partner’s environment.  


* **Gonéri Le Bouder** *( Gonéri is a Senior Software Engineer at Red Hat. He works in the IT industry for a bit more than 12 years. He is also an OpenStack contributor and uses to contribute to various Free Software projects like Debian or FusionInventory.)*

* **Gael Rehault** *(Passionate about all things automation, coming with experience in software going from working with ISP to l18n, online gaming to public cloud platforms; architecting & engineering tooling solutions to drive automation into everything.)*

* **Daniel Sheppard** *(Daniel Sheppard is a seasoned product manager with  15 years of experience in technology and product development. Daniel holds multiple certifications in project management and has his MBA from W.P. Carey School of Business.    Daniel has worked with companies ranging from Fortune 500 to early stage startup and is aware of the unique challenges these environments phase with adoption and operation of technology.    Currently, Daniel is the product manager for Rackspace's Private Cloud Powered by Red Hat product and is using his obsession with customer experience to bring fanatical support to enterprise private clouds.)*

* **Maria Angelica Bracho** *(Experienced professional directing strategy, execution, and delivery of innovative solutions for leading companies across multiple industries. Visionary strategist with proven ability to leverage cutting-edge technology to expand service and capability, holding advanced knowledge of Cloud computing. Trusted partner who engages both technical and business officers to define needs and align technology initiatives with broader organizational goals. Holds an Electronics Engineering from University Simon Bolivar in Caracas, Venezuela and a Masters in Electrical and Computer Engineering from University of Maryland.)*

Policy Driven Red Hat OpenStack Platform with Cisco ACI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cisco Application Centric Infrastructure (ACI) is a comprehensive policy-based architecture that provides an intelligent, controller-based network switching fabric. ACI fabric is designed to be programmatically managed through an API interface that can be directly integrated into multiple orchestration, automation, and management tools, including OpenStack. In this session, audience will learn how integrating ACI with OpenStack allows dynamic creation of networking constructs to be driven directly from OpenStack requirements, while providing additional visibility within the ACI Application Policy Infrastructure Controller (APIC) down to the level of the individual VM instance.


* **Muhammad  Afzal** *(Muhammad Afzal is an Engineering Architect at Cisco Systems in Cisco UCS Data center solution engineering. He is currently responsible for producing and designing Cisco validated converged datacenter and cloud architectures while working collaboratively with product partners. Furthermore, he is a lead architect of FlexPod datacenter solution with Red Hat Enterprise Linux OpenStack Platform. Previously, Afzal had been a lead architect for various cloud and data center solutions including UCSO in Solution Development Unit at Cisco. Prior to this, Afzal has been a Solutions Architect in Cisco’s Advanced Services group, where he worked closely with Cisco's large enterprise and service provider customers delivering data center and cloud solutions. Afzal holds an MBA in finance and a BS in computer engineering.)*

* **Iftikhar Rathore** *(.)*

Showback & Chargeback!! OpenStack Gnocchi + Cloudkitty as a Whole Billing System
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack gnocchi and cloudkitty are the two shining projects for "Metric aggregation as a service" and "rating and chargeback component for openstack" .They are pretty new to the openstack universe, but are amazing projects that came to stay and bring a whole new possibilities to extract priceless information of cloud usage and togheter, they create what we can call, the first time "Rating and Billing system for openstack".How cloud managers can measure the usage and consumption of different cloud resource from Domains, projects, and users, "clients". And transform that values into an invoice to start the payment collection.


* **Leandro Reox** *(Leandro has over 10 years of experience in technologies focused on networking, security, scalability and performance tuning. Leandro is a lover of free software. He has worked at large companies such as Global Crossing/Level3, AT&T and IBM as a senior network engineer. When he joined Mercadolibre, his role was to design the SDN architecture and the network hardware integration and design for the massive environment. At NubeliU, Leandro is the networking expert.)*

* **Stéphane Albert** *(Hi, my name is Stéphane Albert, a french guy living in Toulouse. I work at Objectif Libre mainly around OpenStack and IT automation. My main task is to bring CloudKitty to life to add reporting and pricing with Ceilometer metrics in OpenStack. My main interests are Python, OpenStack (how surprising ;)), networking and Open Source software. When I'm not at my computer I repair arcade systems and hack on electronics.)*

* **Alejandro Comisario** *(Alejandro has been on IT for over 11 years, Debian Linux and Python fan, Alejandro has been around OpenSource for quite long, born as a C++ developer on his early years, passed over Infrastructure and learned to love performance, scaling & automation on linux.Passing thru companies like Techint (A leading global manufacturer and supplier of steel tubes) and Sony as a Linux Senior Sysadmin, Alejandro was Cloud Services  head technical leader being one of the founders of the Mercadolibre's private cloud, the biggest Latin America's openstack private cloud. Investigate cutting edge technology to constantly implement to orchestrate the Openstack private cloud, to make sure the high availability and performance of the platform. Alejandro is now CTO at nubeliu.com, the first Latin American company to bring openstack to the region, making sure that all the biggest till the smallest companies know that openstack its the best that )*

Capacity Planning!! Saving money and maximizing efficiency in Openstack using Gnocchi and ceilometer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud computing offers incredible flexibility for the resource management as well as new and complex challenges. Proper cloud planning can save money from your budget, streamline your IT operations and maximize efficiency.Using ceilometer and Gnocchi, the new project for "Metric aggregation as a service" in openstack, cloud users can achieve the best practices to address the cloud Capacity Management issue.


* **Leandro Reox** *(Leandro has over 10 years of experience in technologies focused on networking, security, scalability and performance tuning. Leandro is a lover of free software. He has worked at large companies such as Global Crossing/Level3, AT&T and IBM as a senior network engineer. When he joined Mercadolibre, his role was to design the SDN architecture and the network hardware integration and design for the massive environment. At NubeliU, Leandro is the networking expert.)*

* **Alejandro Comisario** *(Alejandro has been on IT for over 11 years, Debian Linux and Python fan, Alejandro has been around OpenSource for quite long, born as a C++ developer on his early years, passed over Infrastructure and learned to love performance, scaling & automation on linux.Passing thru companies like Techint (A leading global manufacturer and supplier of steel tubes) and Sony as a Linux Senior Sysadmin, Alejandro was Cloud Services  head technical leader being one of the founders of the Mercadolibre's private cloud, the biggest Latin America's openstack private cloud. Investigate cutting edge technology to constantly implement to orchestrate the Openstack private cloud, to make sure the high availability and performance of the platform. Alejandro is now CTO at nubeliu.com, the first Latin American company to bring openstack to the region, making sure that all the biggest till the smallest companies know that openstack its the best that )*

* **Sergio Colinas** *(Sergio Colinas is a Software Engineer with more than eight years working in the software industry as a developer and architect. During the last two years Sergio has been developing with the NubeliU team different products for Openstack like Nubeliu Rocket Dashboard, NubeliU Showback and Chargeback, NubeliU Monitoring and Alarming. Sergio also collaborate with some official Openstack projects like Ceilometer, Gnocchi, Aodh and Cloudkitty.)*

Co-Engineering an Enterprise Grade OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprise grade products require a reliable infrastructure, be able to scale quickly and most importantly meet special Service Level Agreements. Usually deployment and support tents to be complex and time consuming. Using Redhat Openstack Platform allows to integrate all the components for an Enterprise Cloud environment and also to reduce deployment times. Rackspace support teams have integrated OSP having best practices in mind, such as: high availability infrastructures, validation of the entire deployment, and testing to assure environments comply with the requirements of Enterprise customers, besides in collaboration with Redhat Technical teams and Fanatical Support it will reduce the complexity to manage a fully functional Openstack cloud.   


* **Jeff Ekstrom** *(Jeff Ekstrom is a cloud evangelist for Red Hat’s Certified Cloud and Service Provider program. He has extensive experience with cloud strategy and architecture, with industry experience in Telecommunications, Federal Government, and Insurance. His cloud strategy focus includes both open source technologies and hybrid cloud enablement. Jeff joined Red Hat in late 2015, where he has been promoting and designing Red Hat solutions within Red Hat's partner ecosystem. Prior to that, Jeff's experience includes companies such as Accenture, The Coca-Cola Corporation, and SAIC. )*

* **None None** *(None)*

* **None None** *(None)*

OpenStack Keystone and Cloud Foundry UAA Integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud Foundry (leading PaaS software) manages identity and access management with its User Account and Authentication (UAA) service; OpenStack has its identity service Keystone. The challenge is that integrating the two independent services to work together. Keystone has concepts such as projects (tenants) and domains; Cloud Foundry has concepts such as organizations and spaces. IBM Bluemix is based on Cloud Foundry. It’s a natural requirement for OpenStack Keystone to support UAA authentication. During the talk we will discuss how IBM’s Bluemix integrates both Cloud Foundry and OpenStack for a single user experience. We will present our current solution, its limitations, and our new solution that will be rolled out at a later date.The code for this will be almost completed before the summit and will be verified in our team project. The code will be also open sourced later and maintained by us.


* **Huan Zhang** *(Working in IBM 4 years since graduated. Have experience on both private and public cloud. Now is working around OpenStack Keystone to integrate it with IBM Bluemix.)*

* **Zhu Zhu** *(Zhu Zhu is a Advisory Software Engineer in IBM Cloud and Open Technologies, focusing on OpenStack development and cloud solutions. He started openstack community development since 2013 mainly focus on nova. Currently he is focused on IBM public cloud solution based on openstack.)*

* **Qun Wang** *(Wangqun is a software developer in IBM. She worked on openstack magnum community for one years, and mainly active on kubernetes, swarm and mesos storage. She works on IBM distribution team and is responsible for openstack keystone.)*

How to Integrate Aspera, F5 with Openstack as an High-Speed data transfer Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In order to let OpenStack Cloud be more out-of-box matching industry requirement, more useful feature to OpenStack Cloud as OpenStack Industry Solution is necessary. High-Speed data transfer is a common painpoint in cloud era, especially for media industries' new trend of 4K video,  TB/PB data from customer to cloud for big data analysis, etc. Aspera is an IBM software with high-speed data transfer patent FASP, which speed up 10x, 100x, 1000x in WAN under different network conditions. F5 is a famous load balance software, which have been integrated with Neutron LBaaS. In our solution,  Aspera as a cluster service is deployed in OpenStack VMs with autoscaling feature, and F5 as Neutron LBaaS provider, which provide an OpenStack Cloud with elastic high-speed data transfer capability. Our practice of how to realize this solution will be covered in this session.


* **minmin ren** *(Minmin Ren is a software engineer in IBM Cloud Iaas Lab and Openstack commmunity active contributor. She works on IBM cloud BU and focus on openstack computing, storage and HA development. She has experience in openstack core projects development and tuning. )*

* **Xiao Hua Shen** *(She is one of the IBM Cloud Openstack Service(ICOS) architect and tech lead. Having 10 years of data management and consultant experience and 5 years IaaS solution development experience. Current Focus Area is Openstack related Big Data Analysis platform infrastructure and monitoring data insight in Openstack Operation.  )*

Choosing the right self paced OpenStack online training
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It is becoming harder and harder to keep up with solid competence in fast evolving areas like OpenStack. At the same time it is in many cases hard to send administrators to a classroom course for weeks at a time. The solution can be self paced online trainings.  How do you choose the right one? I will share with my personal key findings from different self paces OpenStack Administration alternatives.  The alternatives we have tested: Red Hat OpenStack Administration online course CL210 OpenStack Administration Fundamentals (LFS252) Linux Academy OpenStack MCA100 - Associates Certification Following the Install guide on docs.openstack.org We will share our key findings and notable differences.  


* **Kim Hindart** *(Huge Open Source fan boy and developer. With a background in mobility and especially Symbian and Android. I am a really geeky dude that was forced to handle security and compliance so the only coding I do is on my spare time. Luckily that's also what I like to do in my spre time, work. But real work and not just a lot of complinace and regulations but something that is acctually for the betterment of mankind.  Unfortunately I happen to bee good at security, especially social engineering, and now I am stuck. But I am happy to share my knowledge and experience in making thins both secure and compliant. And no they are not alwas the same thing.  Compliance is solved through the cloud. Epecially smarter clouds. OpenStack is the key to this. OpenStack is 42 to compliance. One stack to forever in the darkness bind them.  )*

vRack - Hybrid cloud service interconnect L2 network made by OVH
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OVH is one of the biggest dedicated server provider on the world. Since few years we are also active on OpenStack cloud market as  Public Cloud provider. From the begining of Public Cloud project we wanted to make bare metal world complementary with cloud technology. We know that the base backbone for our plans is our widespread network. Discover how we integrated vRack network technology with OpenStack Neutron service to help you link your VMs located in several OVH datacenters across all OVH services like dedicated servers, dedicated cloud and more!


* **Sławek Kapłoński** *(Devop at OVH working on large cloud infrastructures. Software Defined Networking geek and programming enthusiast, I work in R&D team to solve networking chalenges and integration requirements on large scale public cloud solution. Developer of Openstack Neutron in my free time. You can catch me on #openstack-dev or #openstack-neutron channels at FreeNode)*

* **Krzysztof Tomaszewski** *(Devop at OVH working on large cloud infrastructures.)*

Interoperability: The Promises vs. Reality
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While there’s no promise of everything working perfectly, interoperability is a key component of the OpenStack ecosystem. Trove, the OpenStack Database as a Service (DBaaS) offering, runs on several different versions of OpenStack all while supporting relational and non-relational databases.  These databases, like Cassandra, Couchbase, and MySQL, for example, are all supported while the Tesora DBaaS Platform runs on Mitaka, Liberty, and Kilo. In this talk, we will address: Expectations for cross-operability when running the Tesora DBaaS platform. Lessoned learned when deploying Tesora DBaaS platform in a mixed-version OpenStack environment. Challenges associated with qualifying an increasingly complex test matrix. Attendees will take away practical, realistic advice for addressing obstacles when working in an environment with cross-operability. 


* **Emily Wilson** *(Emily is a QA Engineer at Tesora. She currently lives in Cambridge, Massacchusetts. )*

GUTS: Not an OpenStack distro. Making the move to an OpenStack cloud easier.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

GUTS is a workload migration engine designed to automatically move existing workloads and virtual machines from various previous generation virtualisation platforms on to OpenStack. GUTS also provides an alternative to upgrading old versions of OpenStack to newer versions OpenStack clouds by migrating and then cutting over resources between them.   An Open Source project that aims to make the move to an OpenStack cloud easier, GUTS addresses the various difficulties operators and administrators face when migrating workloads from existing clouds into OpenStack.


* **Kavit Munshi** *(Kavit is the CTO of Aptira, heads Aptira's Indian operations and has 15 years of experience in designing and deploying Enterprise and Telco solutions.   He is also the founder of the Indian OpenStack User Group and the OpenStack Ambassador for the region. Kavit is also an Individual Director member of the OpenStack Board of Directors.   Kavit has been a driving force behind the Indian OpenStack community and has interwoven  this into Aptira's deep involvement with OpenStack. He has helped organise numerous OpenStack events in India and loves to work with students driving their involvement with OpenStack. As an active OpenStack Ambassador his priorities are to help the OpenStack Community grow in South Asia by increasing the engagement of the burgeoning OpenSource community in academia with the OpenStack project. Kavit also realises the importance of startups to innovation and always looks to promote OpenStack in that space. Kavit has a vision for India as a Centre of Innovation to develop and commercialise intellectual property rather than an offshoring destination. Kavit has been mentoring students and young entrepreneurs to that end.)*

* **Alok Kumar** *(My name is Alok Kumar and I am a full-stack web application developer currently based in Bangalore, India with over 6 years of extensive experience in python and django in designing, developing and maintaining web solutions. Over the past year, I have been exploring OpenStack internals, and maintains a major focus on Dashboard & Networking components of OpenStack. I have shared my OpenStack learning journey with beginners wishing to learn more about Neutron and how to contribute to OpenStack in numerous articles which have been shared on Superuser. I have also conducted Neutron workshops as part OpenStack Days to large ops & dev audiences, assisting them in a wider range of OpenStack projects including storage and automation. You will find me highly enthusiastic and passionate about a range of topics, from learning new technologies and automation tricks to sharing knowledge within the community and discussing football strategies.)*

* **Bharat Kumar Kobagana** *(I have been an OpenStack developer since 2011. I have extended my contributions to Glance, Nova, Cinder, GlusterFS (Cinder volume driver), devstack, and other projects. I was part of the core team for cinder-glusterfs driver. Currently, I am part of the OpenStack development team for Aptira Pty Ltd. My current role as OpenStack specialist is developing a new project in OpenStack called GUTS, which provides Workload Migration as a Service.)*

Lessons Learned from a Large-Scale Telco OSP+SDN Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk we will discuss lessons learned from a Red Hat OpenStack deployment with a software-defined networking (SDN) provider in the telecommunications market in EMEA. We’ll share our initial level of experience with the specific product integrations and how we overcame the unique requirements of the environment, including: Going from fully manual deployment to fully integrated Unique requirements of the architecture and how we resolved them The future of SDN and other service deployments in OpenStack Platform director


* **Guil Barros** *(Guil is an OpenStack Product Manager at RedHat focused on partner enablement. He works with internal and external engineering groups to leverage our partner value-add towards making OpenStack easier to consume. His personal mission is to remove barriers to entry in the OpenStack space.)*

* **Cyril Lopez** *(Technical Cloud Consultant at RedHat focused on OpenStack in  Red Hat Cloud Innovation Practice team (Coming from eNovance acquisition). Start from manages services on web hosting migrate to become DevOps on cloud solution and now OpenStack integrator. OpenStack contributor as far he can.)*

* **Vicken Krissian** *(My role is to lead and contribute to the delivery of cloud projects based on Red Hat solutions and products using Agile methodology.    The Red Hat Cloud Innovation Practice is a global team of experts that will assist companies with more quickly on-ramping to the cloud. We're doing this by providing solutions and services such as validated designs with reference architectures and agile methodology consulting, training, and support.)*

Plethora of use cases with Openstack Storlets
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack Storlets enables to securely execute user-defined code near data residing in Openstack Swift. In this talk we introduce the project and demonstrate some real life use cases. Amongst the demonstrated use cases are: 1. Smart energy consumption services. Services, such as those offered by Gridpocket [1], rely on analytics over data collected from smart meters. Being highly sensitive data, storlets are used to preserve privacy by transforming the raw meters' data so that it can be made available to the energy analysis applications. 2.Efficient analytics over data in secondary storage. The amount of data (especially IoT data) being gathered for analytics is exponentially growing. Object storage is the typical choice for keeping such data sets. A critical question is whether these data sets, once there, can still be queried efficiently.With storlets we demonstrate up to X4 improvement when running SQL queries over CSV data kept in Openstack Swift. [1] http://www.gridpocket.com


* **Eran Rom** *(Eran is an open source enthusiatic, who leads the Openstack storlets project and contributor to Openstack Swift. After 10 years in IBM research in the area of storage and systems, and with substantial experiance in leading research and development projects, many of them in the field of cloud storage, Eran has left the company to devote more time to the real thing: open source development.)*

* **Filip Gluszak** *(To be filled later)*

* **Yosef Moatti** *(Yosef Moatti is a member of the research staff at IBM Research–Haifa, Israel. His research interests include Big Data analytics and storage frameworks. Moatti has a doctorate in computer science from Télécom ParisTech.)*

Shift from Naive to Cloud Native: Integrating OpenShift and Kubernetes with OpenStack Resources
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenShift, Red Hat’s Kubernetes-based Container Platform, can be deployed easily and ‘naively’ on top of OpenStack. You can simply run the OpenShift Ansible playbooks & have OpenShift up and running on OpenStack. However you will not be taking full advantage of ‘native’ OpenStack Resources such as Heat, Cinder, Swift, LBaaS, Designate, Neutron & more. If you are going to run OpenShift in production at scale, you’ll want to integrate more tightly with native OpenStack resources. In this deep dive technical session, we’ll demonstrate how to move from a simple overlay installation to a dynamic fully integrated deployment which makes the best possible use of OpenStack services. After this session, you will have learned practical deployment patterns based on Red Hat’s reference architecture for OpenShift on OpenStack. This will enable you to configure OpenShift on your OpenStack production infrastructure to meet and scale all your organization’s container-based needs.


* **Mark Lamourine** *(System Admin, Software Developer and QA developer wrapped in one. I'm interested in making the parts work together and I'm especially focused on the operations and sysadmin aspects: Installation, management and maintenance. I'm currently working with the developers of the OpenShift on OpenStack Heat templates for installing and managing OpenShift.    )*

* **Scott Collier** *(None)*

* **Diane  Mueller** *(Diane is the Community Lead for OpenShift Origin (http://openshift.org), the leading Open Source Paas that upstreams Kubernetes, supports Docker natively and runs on OpenStack (as well as AWS, GCP, Vmware, and bare metal). She also runs the OpenShift Commons (http://commons.openshift.org) and manages the cross-community collaboration with all the upstream projects and across the diverse and ever-expanding OpenShift eco-system. She has been coding and tinkering for over 30 years; and founded @GetMakered Labs to help connect underserved and remote communties to new technology in the Pacfic Northwest. She serves on the board of the SC Maker Faire.  She was named one of the top 10 Women in Cloud in 2015.)*

OpenStack and NFVi Real-World Use Case
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How to leverage latest OpenStack for ‘Virtual Ethernet Service Assurance and vCPE/vPE VNFs’ over converged infrastructure platforms. Network Functions Virtualization (NFV) – and Software Defined Networking (SDN), for that matter – is all the rage but most CSPs are still slow to get it from proof of concept to an actual ubiquitous presence on the market. At the crux of NFV infrastructure is OpenStack, which brings all the capabilities and flexibility to achieve the various requirements expected by telcos and cloud service providers. This breakout session will cover how Kontron has worked with ISV partners – including one in particular for virtual Ethernet Service Assurance – to develop the NFVi solutions that help meet these particular CSP requirements with an eye on how OpenStack is an instrumental open source component.


* **Eric Sarault** *(Eric Sarault, B. Eng. is the product manager for Kontron’s (KCI) software portfolio including the development of a software platform powered by OpenStack and Canonical MAAS & Juju to deliver a fully supported OpenStack solution suitable for customers looking to adopt OpenStack as their on-premise cloud platform. Before Kontron, Eric was the lead product manager for Internap's AgileSERVER and AgileCLOUD product offering which has brought to market the first multi-region OpenStack bare metal service with a wide variety of compute options allowing customers to leverage the flexibility of the cloud with a true bare metal catalog closer to traditionnal dedicated server lineups from legacy operators. Prior to his role at Kontron, Eric played multiples roles in product management, engineering, software development, sales and operations at Internap and iWeb Technologies Inc.)*

* **Luc-Yves Pagal Vinette** *(Luc-Yves is a technology expert in many domains (Access & Core Networking, Carrier-Ethernet, LTE EPC & VoLTE, VC & TelePresence, UC&C, MPLS-TE & TP, SDN & NFV...). His role is mostly to provide technology positioning and assessment as a mean for business/marketing structured response and positioning. His previous roles have included technology leadership position such as Chief Technology Officer (CTO) and influential roles towards executive teams in Product Management, Product Marketing, Consulting & Strategic roles. Global Knowledge: Carrier Infrastructure Services : MPLS versions , Carrier Ethernet (802.1, 802.3, ITU), MPLS & Ethernet Protection Mechanisms, OTN & P-OTN, Copper, Cable & Wireless, Clock Sync services (Sync-E & 1588v2), OpenFlow & Virtualization services (SDN/NFV, VMWARE, HyperV...) ; LTE Mobile infrastructure (RAN & LTE EPC) ; Voice & UC Services: VoiceH.323, SIP, Legacy Voice, IMS, VoLTE and IMS UC: Polycom infrastructure/Video Conferencing/Tele-Presence ; Cisco Infrastructure/Video Conference/Tele-Presence/Collaboration ; Microsoft OCS/LYNC Unified Communications & Collaboration solutions, eSBC and Broadsoft PacketSmart.)*

Simplifying Hybrid Cloud with Heat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprises are embracing hybrid cloud, and leveraging the power of OpenStack and the flexibility of Heat orchestration to automate the provisioning of their workloads. In this session, learn how IBM customers are solving this problem and bridging the gap between diverse cloud platforms with Heat orchestration and the IBM UrbanCode Deploy Blueprint Designer, featuring: - rich graphical editor to easily create a full stack HOT template (blueprint) comprised of both IaaS resources (compute, network, storage), and associated software deployments - seamless configuration of blueprints for portability across different cloud providers, including OpenStack, Microsoft Azure, VMware vRealize Automation (vRA), AWS, and others. - provision via Heat and leverage real-time results of deployments via a composite environment view 


* **Chad Holliday** *(Chad is the development lead for the IBM UrbanCode Deploy Blueprint Designer, with many years of experience providing cloud solutions for IBM customers.)*

* **Brad Blancett** *(Brad is a lead developer on the IBM UrbanCode Deploy Blueprint Designer.)*

Hitachi private cloud infrastructure built on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Unified Compute Platform(UCP) from Hitachi Data Systems is a leading converged infrastructure supporting broad range of enterprise workloads and use cases. With the growing interest, and popular acceptance of OpenStack there has been an increased customer demand to have OpenStack platform validated on UCP, and be made available for Enterprise private cloud, as well as other OpenStack based IaaS cloud deployments. Hitachi Data Systems, Brocade, and Red Hat have developed a validated solution, (UCP)2000 with Red Hat Enterprise Linux OpenStack Platform 7.0. This solution enables customers to quickly and reliably deploy OpenStack based private and hybrid cloud on converged infrastructure. The solution architecture is built on HDS 2u4n Server for Solution, Brocade 6740 NOS switches, and HDS G400 storage arrays. In addition to that, it includes Red Hat Enterprise Linux 7.3, Red Hat Enterprise Linux OpenStack Platform 7.2, and the Red Hat Enterprise Linux OpenStack platform installer.


* **Manju Ramanathpura** *(I am a member of Hitachi Data Systems’ Office of Technology & Planning team, working as a Sr. Director & CTO for Intelligent Platforms. In my role, I work closely with strategic clients, research communities, open source communities and various Hitachi’s internal organizations to drive continuous innovation.  I am also a member of OpenStack board of directors, representing Hitachi.    )*

* **Henry  Chu** *(Henry is working as lead Architect for Openstack Solution for Hitachi Data System with many years of experience in Designing Converge and Hyper Converge architecture. He has extensive experience in designing complex architecture with wide variety of technologies, including Openstack , AWS, Puppet, Docker, Cisco, VMware, Microsoft and Linux. His design strengths are in cloud computing, automation and the security space.)*

* **gaurav singh** *(Gaurav Singh is working as a Product manager for Openstack Solution for Hitachi Data System with 7 years of experience in Designing Converge and Hyper Converge architecture. He has extensive experience in designing complex architecture with wide variety of technologies, including Openstack , AWS, Puppet, Docker, Cisco, VMware, Microsoft and Linux. His design strengths are in cloud computing, automation and the security space.)*

OpenStack is Better with Rackspace and Red Hat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is the open source choice cloud for companies everywhere. However, OpenStack still remains challenging with deployment, upgrades, and operations. Red Hat's expertise in the management and distribution of open source combines with Rackspace's industry leading Fanatical Support to provide a world class enterprise grade managed OpenStack private cloud.


* **Daniel Sheppard** *(Daniel Sheppard is a seasoned product manager with  15 years of experience in technology and product development. Daniel holds multiple certifications in project management and has his MBA from W.P. Carey School of Business.    Daniel has worked with companies ranging from Fortune 500 to early stage startup and is aware of the unique challenges these environments phase with adoption and operation of technology.    Currently, Daniel is the product manager for Rackspace's Private Cloud Powered by Red Hat product and is using his obsession with customer experience to bring fanatical support to enterprise private clouds.)*

Continuous delivery to Open Telekom Cloud (OTC)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How to implement a image bakery, ephemeral servers and rolling updates on a IaaS like the Open Telekom Cloud. This shows in a live demo and with architectural sketches how continuous delivery was implemented for a customer project related to large scale web publishing.  


* **Boris Folgmann** *(Boris has more than 20 years experience in Software Development and worked as a freelancer for different start-ups in leading positions. His own company develops and operates services for European MNOs. He substantially enhanced the functionality of the Business Marketplace for the SaaS offering of Deutsche Telekom. For nearly two years he was the Technical Lead for building the Swisscom Cloud which included hands-on work for Continuous Integration, Continuous Delivery, Code Security and QA automation. After this time he was Head of back-end development at Consorsbank and finally joined T-Systems International in March 2016 as a Senior Multi-Cloud Architect. His current focus of work is Cloud Native Development which relies on a proper DevOps methodology.  )*

* **Bernd Rederlechner** *(Bernd Rederlechner works for T-Systems International as Executive Cloud Architect. He has been responsible for the architecture and the rollout of small innovation projects as well as for strategical, large scale pograms. Now, he uses this experience combined with Enterprise Architecture pragmatism and digital concepts like "Lean Startup" to guide customers with theis business ideas to the new Public Open Telekom Cloud - based upon OpenStack.)*

CI/CD with OpenShift and OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack becomes famous in Enterprise, but with cloud platform, what can we do next?  Use it as Virtualization? Or use it as automatic tools. With OpenStack, DevOps practice become reality. You can choose Docker running on OpenStack, also you can choose a production ready, developers friendly tools AKA OpenShift Origin. OpenShift is an open source PaaS implementation which created by Red Hat, in this topic, I will show you how to use OpenShift and OpenStack that make DevOps easier in Enterprise. 


* **Bo Liang** *(Liangbo is a Product Manager at the 99cloud OpenStack Infrastructure group, He has been working with OpenStack as a cloud platform for more than three years,.)*

VMware NSX and Mirantis OpenStack integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will present Mirantis Fuel and its new Neutron plugin: VMware NSX. Is this a match made in heaven? Come to this session to see the integrations between MOS and NSX and see a live demo of the two in action.   Mirantis Fuel offers a robust OpenStack with ease of installation as well as ease of operation. It also offers a large number of validated plugins to enhance OpenStack on all areas (compute, operation, networking, storage, etc). VMware NSX provides advanced, rock-solid network virtualization for multi-hypervisor environments (obviously vCenter but also KVM!). It also offers unmatched network and security operation tools allowing OpenStack cloud admins to operate and troubleshoot OpenStack network and security services.


* **Igor Zinovik** *(Deployment engineer in Partner Integration Team. 3+ years working in DevOps, puppet automation, networking.)*

* **Desmidt Desmidt** *(After (so) many years in networking / high-availability / performance, Dimitri started 4 years ago a great journey in Network Virtualization with Nicira and now VMware NSX. His expertise remains in the Network and Security space and so within OpenStack realm it's within the best OpenStack project: Neutron!)*

* **Andrian Noga** *(Andrian is a Project manager in the Partner Integration Team, with 11+ years in Project management and networking.)*

ManageIQ - Cloud Management Platform & Roadmap
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

ManageIQ is the open source project that powers Red Hat® CloudForms. Drive your complete virtual infrastructure with ManageIQ. Manage the lifecycle of your applications, place virtual workloads according to your business priorities, and — automatically through policies you set — balance your costs, performance, security, and reliability across cloud platforms. ManageIQ lets you control everything, completely, from one end of a virtual machine lifecycle to the other. The ManageIQ community is growing quickly, Red Hat, Google, Nuage, Chef, BBVA, VM Turbo are just a few of the members who contribute to the project. The velocity of ManageIQ is quite astounding; the recent release saw more than 100 new capabilities and features from its previous release. Constantly adding more providers for Compute, Storage, Networking and others giving you more visibility to your environments.  


* **John Hardy** *(Works at Red Hat as the Product Manager for CloudForms. I am easily excited about Cloud, Virt and Containers. I have been working with high-end technologies since birth, and have been involved in a number of successful startups to be sold on to the largest tech companies.   I have been fortunate to work in both vendor and customer environments gaining experience many vendors lack.   I am super happy to be involved in the CloudForms product line, and have a lot of exposure to the upstream ManageIQ community that drives the technology.   We are truly changing the perception of Open Source Management solutions with ManageIQ and CloudForms, which is pretty much how my collogues and my past has always been, bringing to the industry “Desired State” and more recent “Smart State” technologies.   Outside of work, I am a keen RC Heli flyer, and whilst my job involves a lot of travel, one of my heli’s travels with me most of the time. I also ride very rarely now, Felicity. My Repsol FireBlade RR, enjoy skiing, run a 5k most days and entertain my 4 children family.          )*

Hybrid hypervisors under VMware VIO and NSX
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

VMware Integrated OpenStack (VIO), which was launched in 2015, provides an easy and fast path to build OpenStack cloud on top of vSphere, NSX and Virtual SAN. VIO has been adopted by many customers like Nike. And most of existing and potential VIO users hope it can support both VMware and KVM hypervisors. In the past, it could not, because Neutron NSXv/DVS driver was tightly tied with vSphere. After VMware NSX Transformer, the next generation of NSX, comes into the world, VIO will be able to manage hybrid hypervisors (VMware+KVM) ! In this session we will introduce technical details of VIO managed hybrid hypervisors with NSX Transformer. This session covers: - The concept of VIO managed hybrid hypervisors (VMware+KVM). - The NSXv3 SDN for hybrid hypervisors - Technical details about VIO configuration of Nova, Neutron and Cinder. - Demo Attendees will learn the concept and detail of VIO managed hybrid hypervisors, NSX Transformer, including common features and differentiations.  


* **Qin Zhao** *(Qin Zhao is the architect for IBM Cloud Manager. He is OpenStack Nova subjec matter expert, focus on x86 hypervisor enablement. His primary job is to work with OpenStack community and ICM product team for feature design and development, bug fixing and product technical support. He also works with technical sales to design and implement cloud solution for IBM enterprise customers.)*

* **Zhen Mei Ma** *(Zhen Mei Ma is VMware Integrated OpenStack developer. Her primary job is VIO networking development, including Neutron driver and NSX driver. She also works on VIO provisioing and DevOps.)*

Application/Intent Defined Storage in the Modern Storage World
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Datera's "Application/Intent-centric" storage model brings operationalflexibility to the realm of storage administration. Volume-centric modelscan have difficulty scaling to the needs of the modern operator. In thispresentation we discuss the way Datera has fundamentally changed the way thatstorage is controlled. * Current state of Volume-centric storage* Intent defined storage* API First approach* Infrastructure awareness (Infrastructure as Code)* Economic Elasticity* Ease of Use


* **Matt Smith** *(I like Python, hacking on Vim, messing with my toolchain and generally being a bit rambunctious.)*

Next Generation Mgmt for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A prototype for a next generation config management tool, and the specific problems this design solves. Three of the main design features of the tool include:* Parallel execution* Event driven mechanism* Distributed architectureThis talk will demo a prototype I've built that implements these ideas. It is written in golang, and is completely free software. It will feature working code and a number of live demos!We will discuss how this tool will make it much easier to solve the OpenStack management problem, and how it can be elegantly integrated in an existing software project like OpenStack.An introductory blog post on the subject is available. https://ttboj.wordpress.com/2016/01/18/next-generation-configuration-mgmt/ Attendees are encouraged to read it before the talk if they are interested!


* **James Shubin** *(James is a DevOps/Config mgmt. hacker and physiologist from Montreal, Canada. He often goes by @purpleidea on the internet, and writes "The Technical Blog of James".He currently works for Red Hat doing research and prototyping within systems engineering.He started a Next Generation Config Management prototype called mgmt.He studied Physiology at university and sometimes likes to talk about cardiology.)*

Application Aware Root Cause Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Is application-aware RCA attainable? With the holistic system view of Vitrage you can drive application management using insights into application level faults.  Fault management in cloud systems is complex. With a mix of virtual & physical resources interacting, problems at one layer can have ripple effects throughout the system. One situation where this is most apparent is that of fault management in the context of app involvement.  Applications are comprised of virtual resources that may be distributed across separate OpenStack clusters, allowing for failures in one cluster to impact the performance of the other. This impact can be challenging to track in large production deployments. In this talk we present how Vitrage uses its latest Heat data source to give insights into application-level faults, and how Vitrage provides a clear and holistic view of the system, from physical infrastructure to virtual application, which can then be used to drive application management policy.


* **Ohad Shamir** *(Ohad is a product manager in CloudBand, Nokia. In his role, Ohad is leading Analytics and monitoring for the CloudBand NFV product line and he is also responsible for open source activity in CloudBand. Ohad is driving Vitrage, an official OpenStack project, initiated by CloudBand, for root cause analysis, deduced alarms and states.)*

* **Dan Offek** *(Dan has over 30 years of experience in development. He began programming from a young age, and following his hobby, continued developing as part of his military service and after that, on Network management systems, and Cloud orchestration. Today Dan is a member of Analytics Insight team in Nokia's CloudBand. On his free time, when not spending time with his family, Dan likes cliff climbing, wall climbing and bouldering. He also enjoys bike riding.)*

Deploy OpenStack and DevOps environments for multiple distributions on any cloud VM.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  We have created the ability to run OpenStack Mitaka on top of a Host OS (openSUSE Leap / SUSE SLE with the libvirt, QEMU and KVM) on all nodes of a local Server Cluster (100+ x86 CPUs, 300+ GB RAM, 4+ TB Disk Space) with a few clicks of the mouse. We can put our complete server cluster into the OpenStack deployment as compute nodes. We will then demonstrate how we can access the images from the CCPB (OLM) image repository server in the OpenStack deployment and also access them via the OpenStack Image service.  With the ability to setup VLAN routers with OpenStack, the nodes can access each other, and you can login to them via ssh, the Internet, our Software Factory/Application Marketplace and access the OpenStack VMs. We will also show you how we use the OpenStack Dashboard and OpenStack command line tool to perform operations on the OpenStack deployment  


* **Michael van Buren** *(None)*

Zero Admin OpenStack
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Setting and operating OpenStack is hard and there are a few experts available on the market. With SolidFire and Platform9 it is possible to have a zero admin OpenStack. SolidFire is a storage which was built for OpenStack. It can be setup in Minutes without any expert skills and is fully managed by OpenStack. Platform9 introduces OpenStack as a SaaS offering. The entire OpenStack Control Plane is running in the cloud and is operated by Platform9. In the local datacenter a hostagent is installed on a plain Linux server. That hostagent talks to the Control plane and installs and runs all required modules like Nove, Cinder, Neutron, Glance locally on the servers in the onprem datacenter. With this approach it is possible to implement an entire OpenStack solution in the own datacenter without having Openstack skills. The Openstack environment is operated by Platform9 who are doing updates and support which eliminates the typical operational pain.


* **Bengt Lassen** *(Bengt is a Senior Systems Engineer at NetApp and has a lot of experience working with multiple Enterprise Customers in Germany and designing and architecting Storage solutions. Bengt also works on helping enterprise customers move to the cloud and understands the challenges of new and traditional IT.)*

Sentinel: A Platform for Fine-grained Application Security on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Sentinel provides a robust declarative model to express policies between applications, security zones, etc. The highly-scalable policy engine evaluates the policies and automatically enforces the rules on multiple types of endpoints, including OpenStack VMs, containers, legacy systems and vendor Firewall devices. The system continuously reacts to topology changes and seamlessly applies the rules on end-devices. The system also supports near real-time monitoring & visualization of the deployed policies. Sentinel is currently being used at web-scale within eBay to secure applications running across multiple OpenStack clusters and on legacy environments. The talk will be organized as follows. Brief overview of the cloud architecture at eBay Existing policy systems Sentinel Architecture & Policy Language Policy Evaluation & Enforcement Use of Kubernetes API & controller framework for declarative programming Monitoring & real-time visualization of policy violations Challenges


* **Dr. Sudheendra Murthy** *(Software professional with extensive experience ranging from Software Defined Networking, OpenStack, Open vSwitch, Enterprise Software development, designing highly scalable and performant web-services at Internet scale. Currently involved in managing SDN solution and design, architecture of next-generation scalable SDN solution to support large OpenStack deployments. LinkedIn: https://linkedin.com/in/sudhimurthy)*

Implementing Hands-free Orchestration for Deployment, Provisioning and Billing in a Hybrid Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack matures and is deployed in larger and more mission critical environments, administrators and business managers face new challenges. CloudController® was built from the ground-up to allow easy set-up, deployment and management of hybrid Cloud services from a Single-Pane-of-Glass with no proprietary interfaces. CloudController® provides no-nonsense cloud automation for OpenStack resources along with other virtualized on-premise resources and public cloud services with a single workflow engine and a unified Service Catalog Manager. CloudController® also facilitates the integration of technical and business operations with the ability to create unlimited multi-tier service supply chains, customization of financial back office, contract lifecycle management, white-labeling, language and localization options at each level. CloudController® is a single complete Cloud Management Platform (CMP) providing hybrid cloud management from a true Single-Pane-of-Glass


* **Lee Razo** *(Lee Razo joined InContinuum in February of 2016. Prior to InContinuum Lee was an early employee of NetApp where he was Senior Manager of Competitive Field Strategy and most recently Co-Founder and CEO of RafikiSoft which developed cloud-based business services for organizations in developing markets around the world.)*

Remove job execution with Arc
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Arc is a secure, multi-tenant job execution service for managing instances in an OpenStack environment. The service provides an API for scheduling jobs on remote instances and is designed to work in NATed network scenarios where targets are not accessible directly. Arc features an auto-updating remote agent that is easy to bootstrap and ships as a self-contained static binary for Windows and Linux. The remote agent contains an extensible fact discovery system that is used to build up a searchable inventory of instance metadata.   In this talk we will introduce Arc and show how it is used in SAP’s self-service cloud to build a higher level automation system for orchestrating application deployments. All components of the service will be released as open source.


* **Fabian Ruff** *(None)*

Unifying OpenStack and Public Clouds with Scalr
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

User experience is a top priority, and embracing the Hybrid Cloud paradigm brings its own set of unique problems. Offering multiple backends is not a positive if it dumps the burden of relearning and recoding onto the same users that we’re trying to empower. At Symantec, we are leveraging Scalr to provide a uniform experience to our customers, regardless if they wish to use OpenStack, AWS, or any other cloud platform they feel would suit their needs best. Our solution provides : * Cross-region DNS Management – using a single Designate installation to manage all zones and records * Server Farm Management – assigning roles to VMs and managing a group as one * Integration with Keystone – Mapping Scalr accounts to Keystone tenants


* **Ved Lad** *(Ved Lad is a Principal Software Engineer in the Cloud Platform Engineering team at Symantec.)*

* **Rudrajit Tapadar** *(Rudrajit specializes in virtual networking and is excited to be a part of Symantec's Cloud Platform Engineering SDN team. He has deep interest in open source technologies and has also been a contributor to OpenStack Neutron and OpenStack Designate. At Symantec, he is responsible for designing, developing and operating an enterprise grade secure multi-tenant cloud network.)*

* **Miguel Zuniga** *(Experience technical lead, who during his past 10 years in the field has worked with physical, virtual and cloud technologies. He is a supporter of all open source projects and evangelist of using open source tools. Now is a member of the Symantec's Cloud Platform Engineering leading the Platform as a Service.  During his free time he enjoys reverse engineering how technologies work just for the fun of it. Some of his favorite past and ongoing projects include:   Virtual HA Cluster using CentOS/RedHat Cluster Suite and VMware Server 1 (2006) Automated datacenter provisioning and deployment using open source tools (2010)   Open source in-house S3 (2012) OpenEscalar cloud management framework (ongoing) Canister container management and provisioning (ongoing)     His past work experience includes:   Sr Cloud Lead at Paypal Tech Lead at Electronic Arts Digital Platorm  Sr. Cloud Engineer at Rackspace Cloud Sites Sr. Linux Engineer at GlaxoSmithKline Sr. Linux Engineer at GE Corporate International Contracts)*

Cisco Cloud Center Architecture with Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack has demonstrated to be a solid platform to deploy cloud services, in public or private environments. By talking with SP or Cloud Providers, we have realized that their end users' workloads still require heterogeneous environments, MSFT, VMWare, Linux. Also, they need to interface to legacy systems: payment or OSS/BSS systems that are needed for ongoing operations. So, they need to have an upper layer of management and control that interfaces with theses systems but also is able to use Openstack to orchestrate underneath cloud-native applications.Cisco Cloud Center is an Application-driven policy orchestration engine that allows customers to deploy their applications in any public or private cloud. When Cloud Center is connected to Openstack, it provides a powerful solution for customers to transparently manage their applications from a service broker portal and use the power of Openstack underneath to automate these applications on the data center.


* **Hector Morales** *(Hector Morales is a Senior Cloud Lead Architect in Cloud and Business Services Group for Global Service Provider Organization responsible of Cisco Cloud Collaboration and IoT Architectures. He supports sales engineering and business development on Next-Gen Collaboration and IoT, Cisco Cloud Architectures, Virtual Managed Services and NFV Opportunities. He is also a Technical Speaker on Openstack Architecture and Operations and Cloud Collaboration Architecture, member of Openstack Community and Technical Advisor. He also supports the development of SP Cloud Solutions, New Consumption Models and Cloud Architectures.With a successful 21 year professional career in the Technology Industry and broad experience on technical sales and strategic complex opportunities, he has served as Trusted Advisor in Customer Boards and Business Units. Currently is chairman in Appllications for Future Internet Organization in the European Alliance for Innovation. BS on Electrical Engineering from Monterrey Institute of Technology and MBA from Thunderbird School of Managament, Phoenix University.  )*

* **Faustino Aranda** *(Faustino is a Systems Engineer, based in México City. Faustino's experience  includes the architecture design, development, coding, setup and operation of VoIP, Orchestration/automation and Cloud solutions. He joined Cisco in june 2012 as the Consulting Systems Engineer responsible of supporting Cisco Cloud automation and orchestration solutions across LATAM; he is currently the Data Center and Cloud Systems Engineer for Service Providers in Mexico.)*

Accenture Intelligent Orchestration Platform - Holistic approach to Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will deep dive into what does it mean to have an intelligent orchestration platform and how we built the Accenture Intelligent Orchestration Platform. We will show how you can align your orchestration workflows with the needs of the business processes and policies while ensuring the workload is not starved or challenged in anyway for IT resources. We will take you to the front line on how the business views the Orchestration platform components and how it helps define, track and show areas of performance optimization, compliance and auditability and security. The session will assist first-timers and seasoned developers in how to prepare your business and IT for this new way of operating your orchestration layer with data analytics which provides real-time and historic information you can you to deploy now or in the future. We will use use cases and real world experiences to help show what it means to operate intelligent systems in the cloud.


* **Denise Glasscock** *(Global OpenStack Lead and Community of Practice lead for OpenStack.  I am responsible for the Strategic direction for OpenStack and lead the Red Hat Cloud Offering.  I provide the enablement, act as the technology SME for OpenSource Cloud solutions, and help drive client pipeline and Sales enablement.  I have almost 10 years of Cloud experience across all of the large cloud platforms and I have 20 years of experience in Datacenter and systems integration.  I am certified as a TOGAF and IBM Architect in infrastructure and Integrator knowledge domains.  I hold certifications in OpenStack and have an instructor rating within VMware and Red Hat.  I also provide workshops at all levels to help Accenture and our clients grow their knowledge and understanding of market and technology.)*

The OpenStack Innovation Center - Working for You
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Since the inception of the OpenStack Innovation Center (OSIC) a year ago, we’ve been working to make OpenStack easier for enterprise users. Learn about the progress we’ve made by training the next generation of OpenStack core developers who are helping alleviate some key bottlenecks to OpenStack’s rapid innovation. Hear about the community members who’ve taken advantage of our thousand node developer cloud. See the upstream work we’ve been doing to rectify the pain points and barriers we’ve heard from the OpenStack Foundation’s User Survey and beyond. After hearing all of that, we’ll dive into how you can participate, influence and learn directly from our work.


* **Kenny Johnston** *(Kenny Johnston is the Rackspace Alliance Manager for the OpenStack Innovation Center (OSIC). Prior to joining OSIC Kenny was a Senior Product Manager on the Rackspace Private Cloud powered by OpenStack product team. He brings more than four years of experience with OpenStack, having joined Rackspace from HP’s Helion OpenStack Distribution. Kenny is passionate about the importance of and challenges in open-sourced projects and is a member of the OpenStack Product Working Group. Kenny lives in Leawood, Kansas with his wife and two children.  )*

* **David Brown** *(TBD)*

Horizon UI Modifications in the Context of Short-lived, Complex, Interactive, Network centric Stacks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Riverbed is an enterprise networking company using OpenStack to replace a 6,000 physical machine lab. Our primary users are several hundred QA engineers who are often unfamiliar with OpenStack. This talk covers some relatively minor but high value changes made to Horizon in order to consistently display detailed network information, rapidly prototype network topologies, and lower the barrier of entry to writing HEAT Templates. Changes include deterministic display of the Curvature plugin, an interactive visual orchestration tool for applications on OpenStack, with drag and lock, a simplified VM launch bar, custom icons, multi level label information, and a button to dump hand-built topology to a rough Heat template.


* **Jeff Johnson** *(Jeff is part of an ops R&D team which has been working with OpenStack for about 1 year in an effort to build a new testing platform. Prior to this he was a QA Engineer who focused on L2/L3 product testing)*

Achieving Hybrid/Multi-Cloud through Automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hybrid cloud: as many definitions as there are solutions - and more hype than both combined. In the first part of this session we'll cut through the noise to understand the state of the market. Enterprise organizations have come to recognize that a hybrid cloud strategy is the likely answer and have begun the process of seeking out and implementing solutions. But what do these strategies consist of, and what are the solutions? We'll look at common definitions, objectives, and strategies for implementing hybrid cloud. In the second half of the session we'll present a technical architecture for one such solution, followed by a live demonstration. WAN automation allows for real-time provisioning of inter-cloud connectivity, and OpenStack provides a framework for integration and provisioning with public cloud service providers. The solution presented will bring together private and public clouds with the oft-requested single management interface.


* **Grant Kirkwood** *(Grant Kirkwood is the founder and CTO of Unitas Global, a provider of custom Enterprise Cloud solutions for organizations around the world. The company offers its solutions to mid- and large-size enterprise, operating from 35 datacenter deployments worldwide.  A serial entrepreneur and technologist at heart, Grant has always been at the forefront of open source technologies. His first company began offering web application development and hosting based on open source technologies in 1997. At Unitas, he serves as an advocate for adoption of OpenStack, leading its development efforts but Grant also spends much of his time talking with customers to help them formulate a cloud adoption strategy.  Before founding Unitas Global, Mr. Kirkwood served as CTO of PacketExchange, a London-based global network service provider. Prior to PacketExchange, he founded Mzima Networks, a performance-optimized bandwidth operator for web and online video applications. Grant is a frequent presenter and industry analyst at events around the world. Most recently he spoke about open source and specifically OpenStack at the Datacloud Europe event in Monaco held June 8-10.)*

* **Sig Luft** *(None)*

SurCloud: Killer Product to Win in OpenStack Ecosystem
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Compared with VMware, OpenStack is open, low-priced, but still not easy to use from the point of view of end user. SurCloud OpenStack all-in-one appliance pre-loads, pre-tests and pre-configures all software and hardware in a half rack. Zero deployment, plug & play without worrying about the complexity of OpenStack. SurCloud developed an unique technology called SurFS that significantly improves the traditional design of Distributed FS such as Ceph & Gluster FS, resulting extremely short I/O path, high bandwidth, low latency, high density and very low cost. SurCloud optimizes hardware and software together resulting in a perfect appliance which offers extreme performance, high availablity, highest data duarability, highest density, good user experience and good scalability at very low total costs of ownership.


* **Peter Junge** *(Peter is involved in free and open source communities for more than 15 years. Originally he started to work as an QA engineer on OpenOffice but transitioned over the years from document technology to secure document technology to secure document cloud and now landed at OpenStack. Today, Peter works for SurCloud on product management, the intersection of technology and legal compliance, licensing, and also on community and partnerships.)*

SurCloud OpenStack Appliance: the zero-deployment & optimized cloud data center
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The SurCloud OpenStack Appliance is an all-in-one, ready-for-production cloud data center in a half rack designed for extreme performance, HA, highest data durability, good scalability and inexpensive price. SurCloud Appliance leverages latest hardware technology (such as dual-port NVMe SSD), optimized architecture (e.g. an extremely short I/O path) and optimized software to enable the best performance of hardware (2M+ IOPS, few microseconds latency). SurCloud Appliance totally eliminates single points of failure by 100% redundancy design. This design plus automatically fail-over for all modules & services guarantees high availability. SurCloud Appliance leverages ZFS RAID-Z3 to reach 99.999999999% data durability at lowest cost. SurCloud Appliance optimizes configuration of both hardware and software to ensure no single dollar is wasted. The standard configuration which is good for a couple of thousands VMs is less than $300K. It also reserves enough space for future scale-out.


* **Alex Wang** *(Alex is an excellent innovator. He was nominated as one of the Top 10 Youth Scientist by the Chinese central government in 2010. He was also recognized as one of the distinguished engineers (the only one coming from software and Internet industry) in China in 2014. Alex began to innovate on cloud storage systems in 2011. His first project SurDoc won the “Cloud Storage Excellence Award” by US Cloud Computing magazine in 2013, got 10M+ users worldwide within 2 years upon its service launched. Alex is founder of a Silicon Valley company SurCloud. He is also 1st inventor of 100+ patents worldwide.    )*
