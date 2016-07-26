Networking
==========

Fits like LEGO: Building a cloud using Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack Neutron is like a Lego brick box for building, administering and monitoring virtual networks. Beginner users can easily understand Neutron’s basic building bricks, Port, Network and Subnet, to deploy a simple virtual network. However, when building a more complex private or public cloud, specialty bricks (e.g. router, floating-IP, security-groups, firewall) come into play. In my presentation, I will introduce the basic and specialty building bricks & how to use them to build five topologies: from a basic network topology all the way to the core block of multi-tenant self-service cloud. Each topology will be presented by its pros and cons, & how it fits other topologies in order to build an elaborated network structure.


* **Liaz Kamper** *(Liaz has ten years of experience in designing and developing software for embedded systems, networking and SAN technologies. Prior to joining Stratoscale, he led a software team in Broadcom, a world-leading provider of broadband communications. Liaz holds a B.Sc. in Communication Systems Engineering from Ben-Gurion University. He is a big fan of history and aviation.)*

Neutron troubleshooting from the top down
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will help poeple new to openstack understand how neutorn works as well as how to troubleshoot neutron networking problems. The most common problem is "hey I can't ssh to my instance", so where do you start troubleshooting? This presentation offers an in depth look in to the process as well as a live troubleshooting demo. Finally I will give an example of a script to collect and even perform basic neutron troubleshooting tests. Here is the presentation link:  https://docs.google.com/presentation/d/1_6tP6FQNjwz1MALHdUVRpwRVH9uon2U2dnX6vvW2G2o/edit?usp=sharing  


* **Jeremy Melvin** *(Hello, I am an OpenStack Support engineer working at Red Hat.)*

Picking an OpenStack Networking solution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack networking ecosystem is very rich with both open source and proprietarysolutions representing many different architectures to implement Neutron and networking services. What are the high level differences between the various open source solutions? What should you look forwhen picking a solution? Topics include L2/L3 gateways, L3 only networks, monitoring and debugging, containers, hybrid cloud, connecting legacy networks with new networks, NFV and service chaining, scaling, federation, and more.


* **Gal Sagie** *( I am a software architect, passionate about open source, experienced with networking, virtualization and all areas of SDN/NFV and cloud computing. Contributing to OpenStack Neutron, Containers networking projects and hybrid cloud. Eager to bridge the gaps between OpenStack development and its users and explore new areas to help OpenStack shine Blogging for anything OpenStack related at: Blog - http://galsagie.github.io)*

* **Russell Bryant** *(Russell is the Technical Director for OpenStack at Red Hat, Inc.  He is on the OpenStack Technical Committee (since Fall 2012) and served on the OpenStack Foundation Board of Directors from January 2015 to June 2016.  Russell has been contributing to the development of OpenStack since the Fall of 2011.  His most significant contributions around OpenStack have been to Nova and most recently Neutron and OVN. Prior to working for Red Hat, Russell spent 7 years (2004 - 2011) working for Digium on the Asterisk project. In the later years, Russell was the leader of the Asterisk project as well as the Engineering Manager for Asterisk development at Digium. Russell is also a published author.  Russell co-authored "Asterisk: The Definitive Guide" and "Asterisk Cookbook", published by O'Reilly Media.  He also contributed a chapter on Asterisk to the book "Architecture of Open Source Applications". Russell graduated from Clemson University with a Bachelor's degree in Computer Engineering in the Fall of 2006.  He currently resides in Charleston, South Carolina.)*

* **Kyle Mestery** *(Kyle is a Distinguished Engineer and Director of Open Source Networking at IBM. He leads a team focused on Open Source networking at scale. Kyle is also a member of the OpenStack Technical Committee, and the former PTL of OpenStack Neutron for the Juno, Kilo, and Liberty cycles. Kyle lives with his wife and kids in Minnesota.)*

Co-existing and Integrating Open vSwitch with OpenFlow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The mainly idea of this talk is cover how to take advantages with SDN(Open vSwitch) using OpenFlow that enables networks to evolve, by giving a remote controller the power to modify the behavior of network devices, through a well-defined "forwarding instruction set".


* **Alberto Santos** *(Dedicated, skilled Network Consultant with a broad range of experience with 10+ years leading large network projects, acting in planning, design and implementation for enterprise, mobile & fixed and internet service provider. Ability to work in a multi-vendor environment and focused in learning new technologies. Academic background includes a Master's degree in network & telecommunication and programming degree. Focus on (not limited to): MPLS, MPLS-VPN, CsC, I-AS, MPLS-TE, VPLS, GMPLS, MPLS-TP, IPv6, 6PE, 6VPE, IPTV, Multicast, GPRS, LTE/EPC, SACC.)*

Extending MPLS VPN network to Openstack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a powerful cloud computing platform used to build public and private clouds. Enterprise and service provider operators are taking advantage of OpenStack to drive new business models. While most access to OpenStack workloads relies on the public Internet – there are times when private connections are needed. MPLS is a mature, well-understood transport technology in use today. Service providers who offer MPLS services may be interested in offering their own OpenStack platforms or connecting to other Openstack cloud providers. This type of inter-connectivity brings up questions. How do I connect MPLS VPNs to OpenStack projects? Can this connectivity be completely automated? What factors should I consider? This session will provide an example of how to develop automation to connect Openstack projects to service provider MPLS networks using REST APIs and NCS (Tail-F). The goal is to share an example and lessons learned so that participants may have a reference for future use.


* **Tim Petrisko** *(Tim Petrisko first joined Cisco in 1999 to work for Cisco Advanced Services. Tim   is Currently Technical Lead Software Engineer for Cisco Cloud Services for over 2 Years. Tim is one of the lead developers for a wan automation system, which brings OpenStack and MPLS routing together. In 2001 he was assigned to large service provider to lead multiple projects deploying CRS, ASR, IRS, 6500 and Nexus platforms, solutions consisting of MPLS, Routing, LAN and Wan switching Technologies. Tim was also the Primary engineer responsible for the designing of a large service provider, to migrate their data centers, call centers, and retail outlets from their ATM Network to their CRS MPLS core network. Tim has also provided technical and design assistance at CiscoLive2010 - Technical Solutions Clinic Booths for both Switching and BGP. In his spare time, Tim enjoys spending time with his wife and daughter. Tim also enjoys going on cruises with his friends and family.)*

* **Aundra Browning** *(Andre Browning, CCIE No. 21901, is currently an Architect in Cisco’s Cloud Infrastructure Services group, focusing on designing edge connectivity for Cisco Cloud. He holds a BS in Computer Science with over 18 years of experience in the field of networking – working with clients such as stock exchanges, service providers, and several large global investment banks. His area of work centers on creating innovative ways to connect people to emerging cloud technologies such as OpenStack & Kubernetes. Prior to Cisco, Andre spent time working at large service providers & universities – he currently resides in the Raleigh, NC area where he enjoys spending time with family.)*

* **Faisal Azizullah** *(Faisal Azizullah is a Technical Leader Engineering in the Cloud Infrastructure Services (CIS) group at Cisco Systems and a frequent contributor to opensource projects. He has been in the cloud solutions industry for the past 7 years and specializes in SDN and Cloud orchestration. Faisal has filed 50+ patents and is involved in innovating new solutions for Cloud connectivity. He is currently involved in a WAN automation solution at Cisco. In his spare time, Faisal enjoys spending time with his family and is an enthusiastic beekeeper.)*

* **Omar Ansari** *(Omer is a seasoned Cloud Services leader at Cisco. He is responsible for Engineering at Cisco Cloud Services in support of the large-scale production of SaaS assets across key federation partners worldwide. He has overseen SDN solutions built by integrating the best of breed Cisco technologies with Opensource platforms including Openstack, next-gen XaaS revenue-generating features such as MPLS Private Link (WAN Automation), Analytics-based Load Balancer as-a-Service, VPN as-a-Service and ACI integration into Openstack, provisioned IOPS based storage to name a few. In his spare time, Omer loves to swim.)*

Deployment of OpenStack Group Based Policy with Cisco ACI/APIC/ASA FW, and F5 LB in FSI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This use-case illustrates the integration of the GBP of OpenStack integrated with ACI/APIC, ASA FW, and F5 LB and demonstrates the benefits of ACI with OpenStack GBP and L4-7 Network services offloaded to ASA FW and F5 LB. The major enhancements implemented in this use-case include, but not limited to: Implemented an improved UI for automating networks provision in OpenStack. The conventional network structure are replaced with Network Containers, Network Security Domains, Application Profile Rules and Rule Sets, and L2/L3 Networks. Extended L4-7 external connectivity with integrating ASA FW and F5 LB. Implemented firewall service based on ASA FW, achieving FW rules management and external network and network group management. Implemented LBaaS based on F5 LB, achieving LBaaS policy configuration on F5 LB. This user-case demonstrated OpenStack integrated with a closed-loop network solution based on Cisco ACI/APIC/N9K, ASA FW and F5 LB is ready for FSI production environment.


* **Larry Jiang** *(Larry Jiang is the Founder and CEO of KeyTone Cloud, a leading OpenStack-based cloud computing technology provider and a hosted hybrid cloud service provider. In early 2014, KeyTone Cloud completed Series-A funding co-led by Gobi Partners and CBC, and followed by a strategic investment from Cisco Investments. Prior to founding KeyTone Cloud in early 2014, Dr. Jiang was the Vice President of Shanda Grand Cloud from Jan, 2012 to April, 2014, responsible for all aspects of technical operations, including network & datacenter operations, infrastructure engineering, and cloud operation management systems/tools development. Before his tenure at Shanda Grand Cloud, Dr. Jiang spent 16 years at various high-tech companies in Silicon Valley in US, and held software development, cloud service infrastructure design and deployment, and executive management positions at Siemens-Pyramid, BroadVision, Lucent, WebEx, and Cisco. Dr. Jiang has extensive experiences in scalable, reliable and highly-available Cloud Computing infrastructure and SaaS application design, development, deployment and operations. Dr. Jiang holds B. Eng. and M. Eng. degrees from Tianjin University, China and a PhD degree from the University of British Columbia, Vancouver, Canada.)*

Connect all the things: span multiple clouds and networks securely in 30 seconds or less
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Getting VMs connected across different regions in the same cloud can be challenging.  Getting VMs connected between two different clouds is harder.  Migrating an active workload from one cloud provider to another is tougher still, and borders on impossible without deep networking expertise.  Much of the same connectivity concerns exist just getting connected to VMs in a cloud without giving them all public IPs or using a bastion host. There's a simple open source VPN designed to solve these problems (and more), with minimal experience required to make full use of it.This presentation will cover the background and technology enabling this VPN, showcase some real-world use cases (like moving your app from AWS to an Openstack cloud, or controlling a beer brewing system from your phone), and will include a LIVE DEMO deploying zerotier and using it on VMs distributed across multiple providers.


* **Christopher Aedo** *(  Christopher Aedo, Cloud Architect at IBM, is an IT veteran for consulting, design and technology companies. He is also an outspoken public advocate for OpenStack, cloud computing, software defined networking, and software defined storage. He's recognized as a community thought leader and has spoken at numerous OpenStack conferences in addition to speaking or participating on panels in multiple international conferences, including OSCon, CloudOpen, PuppetConf, and Okinawa OpenStack Days as well as numerous regional developer groups.)*

* **matthew wagoner** *(A long time computing enthusiast, the majority of Olaph's OpenStack experience has been in supporting public clouds, first at HP and now at IBM.  He currently serves as the cross-spek liasion for the Infrastructure team, and enjoys pushing the boundaries of the definition of 'at scale'.)*

Deploying IPv6 in OpenStack Environments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

More and more enterprise and service provider environments are deploying IPv6 due to extreme IPv4 address exhaustion.  IPv6 support in OpenStack has come a long way but has had serious gaps until the recent releases.  Now, production quality IPv6 deployment within the tenant domain can be fully realized. This session will discuss: IPv6 deployment options for the cloud provider IPv6 address assignment options within the tenant space to include: SLAAC, Stateless DHCPv6 and Stateful DHCPv6 Using IPv6 Prefix Delegation to reduce the burden of IPv6 address management for tenants IPv6 with L3 HA Dealing with limitations in IPv6-only tenant environments Detailed slides as well as lively demos will be used throughout the session.   This session differentiates itself from other competing sessions because it focuses on proven designs and deployment guidance. It supports the growing need to operationalize OpenStack to support emerging use cases and it is presented in a lively way. :-)


* **Shannon McFarland** *(Shannon McFarland, CCIE #5245, is a Distinguished Engineer and help leads OpenStack Architecture at Cisco. Shannon is currently focused on OpenStack architecture, design and deployment. He has been responsible for the Enterprise IPv6 design, large scale data center design and emerging technology areas such as container networking. He has authored many technical papers, Cisco Validated Design guides, a contributor to Cisco Press books and is a frequent speaker at Cisco Live and other industry conferences. He co-authored a Cisco Press book titled IPv6 in Enterprise Networks . Shannon has been at Cisco for 16+ years.)*

Firewall as a Service: Never Say Never Again
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Firewall as a Service (FWaaS) has experienced some rapid and extensive evolution in the Newton cycle.  A complete refactoring of the code joining FWaaS to the L3 agent, integration with the L2 agent, and the evolution of Neutron community standards have been significant challenges for the FWaaS team as implementation of the FWaaS v2 API spec has proceeded.  Hear from the FWaaS team about the challenges they have overcome, the current state of affairs, and the roadmap looking forward for Firewall as a Service.


* **Nate Johnston** *(I have been working alternately as a developer, a system administrator, and a system architect since 1997.  I have been working on Openstack since September, 2014, with a focus on the Quality of Servce ("QoS") functionality within Neutron.  I have been with Comcast for 6 years and worked as a system administrator, system architect, and automation developer prior to focusing on Openstack.  I have previous positions at MCI, Cable & Wireless, Broadwing, and AOL.   I am very excited to be a part of the Openstack community.  I believe strongly that the open source paradigm not only enables the enterprise, but that it enriches the entire technology community, and indeed all mankind.  )*

* **Sridar Kandaswamy** *(Sridar Kandaswamy is a Technical Leader in the Openstack team at Cisco Systems Inc. In his past life, he used to work on Switching & L4 - L7 services (the physical kind). He has primarily been working with FWaaS in OpenStack from its inception in Havana.  )*

* **Yushiro FURUKAWA** *(Yushiro FURUKAWA Software Engineer, Fujitsu Limited. He has been working in Neutron and Neutron-FWaaS since Kilo development cycle. Currently, he focuses on development of neutron plugin(ML2), Neutron, Neutron-FWaaS and Ironic.)*

Survey of Security Group Implementations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we'll examine the behavior of four different Neutron security group configurations, so we can better understand their common behavior and where they differ. We'll examine the existing IPTables firewall driver in the Open vSwitch (OVS) and LinuxBridge contexts. We'll also look at the new OVS Firewall Driver and the firewall functionality in Open Virtual Network (OVN). All firewall drivers are responsible for anti-spoofing protection, so we also look at the behavior of the allowed-address pairs extension in each of these contexts.


* **Dustin Lundquist** *(Dustin Lundquist is a Senior Network Software Engineer on the IBM Cloud Open Source Networking Team. He joined IBM through the Blue Box acquisition, where he had worked since that company’s early days. Dustin's unique perspective evolved because he has worked as a network engineer, cloud operator, and software developer--on all sides of the house! He holds a B.S. degree in Computer Science from the University of Washington.)*

How Did Our Private Cloud Realize Better Application SLA Using Open vSwitch with DPDK
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In recent years, our OpenStack private cloud resources (65k+ VM, 25k vCPU, 350TB memory) that support Yahoo! JAPAN web services require 6x network performance per server compared with traditional server farm as a result of VM aggregation and higher density.Additionally, huge and/or burst network traffic (5~10x than ordinary) we have often received from internet. More internal backend traffic (DNS, RDB, MQ, etc.) happend accordingly.In such situations, we faced a network performance issue in our cloud.To overcome this, we have adopted Open vSwitch with DPDK as a software L2 switch on HyperVisor instead of LinuxBridge, built new mitaka cluster (serving 8000+ VM scale) on OCP (Open Compute Project) servers, and started operation phase now.As we found many problems through our activities from OvS/DPDK PoC phase to operation phase, we will present about combination limitation related OvS/DPDK/NIC driver, network architecture/performance, L7 SLA, operation perspective, and future works.


* **Yusuke Tatsumi** *(Yusuke Tatsumi is a network infrastructure engineer at Yahoo! JAPAN. He belongs Site Operation Division, Infrastructure Engineering Department, support our own production web services by providing several resources(Servers, networking, Storages, Datacenter facilities).For 6 years, He had buit/maintein/managed "physical" production network. From last year, He started work about "virtual" networking such as DPDK, Open vSwitch, HyperVisor IP fabric especially in OpenStack environment.  )*

* **Hiroaki Morikawa** *(Hiroaki Morikawa has been working on OpenStack development project in Yahoo! JAPAN since 2012.Currently, he's been involved in projects related to network virtualization and most recently focused on Neutron DPDK plugin.)*

* **Naoyuki Mori** *(Naoyuki Mori is Application Engineer at Developer Relations Division, Software & Services Group at Intel. He has been working closely with software eco system partner to help optimizing for Intel Architecture. Recent years, he has focus on networking optimization such as DPDK, Open vSwitch, as well as storage ceph and OpenStack.)*

Understanding the network workflow in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

What is the flow that the network packet follows from my instance to the outside world? In this presentation we will do a high level review on what's the flow that a network packet follows starting from the virtual machine and to the outside world, including network namespaces and how to monitor that traffic, including linux bridges, namespaces and Open vSwitch.


* **Jose Casimiro** *(Jose 'Kaz' Casimiro started using linux since 1994 and has been working at opensource enterprises such as Rackspace and Red Hat doing a wide variety of IT roles including: instructor, developer, sysadmin and support engineer. He currently works at Rackspace as an OpenStack Engineer.)*

* **Kent Wolfe** *(Kent Wolfe is a Red Hat Certified Architect who currently works for Rackspace Hosting Inc. as an OpenStack Engineer. His professional interests include troubleshooting a wide range of technologies surrounding Linux and OpenStack. In his previous role, Kent enjoyed mentoring new administrators and serving as an escalation point.)*

* **Carlos Martinez** *(Carlos Martinez is a Openstack Engineer who has done a lot of troubleshooting on Production Openstack Environments, with 8 years of experience as a Linux Engineer)*

Delivering Openstack NFV Service Chaining at Scale with Networking-SFC and Networking-OVN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The ability to dynamically create and modify service chains of multiple virtual network functions (VNF) is a critical component enabling the deployment of NFV. Until recently this ability has required add-on SDN controllers with third party neutron plugins, resulting in a patchwork of solutions. The Openstack networking-sfc has created a standard service chaining interface and an extensible driver model to enable different networking technologies to provide service chaining and flow classification. The networking-ovn project, which everages the OVN enhancements in OpenVSwitch, has introduced a new highly scalable networking infrastructure for Openstack. The combination of these Openstack projects will enable the delivery of advanced service chaining use cases.This presentation will show how advanced service chaining use cases can be delivered at scale by using these new Openstack components.   


* **Cathy Zhang** *(Cathy is currently a principal architect/engineer working on Network Virtualization, Cloud service, and SDN technologies at Huawei Technology USA. Her expertise includes L2/L3 Networking, HA Infrastructure, Network Virtualization, SDN, and Cloud Computing. She is the author of the OpenStack Neutron Service Chain API and Data Model Specification and is currently leading the service chain project development in the OpenStack community. Besides OpenStack, Cathy is also an active contributor to the service chain work in IETF, Openflow, ETSI NFV, OPNFV organizations. She won the "Outstanding Technical Contributor" award from Open Network Foundation and is one of the authors of the Openflow L4-L7 Service Chaining Architecture and API specification. She is a contributor to the IETF Service Chain Data Plane Working Specification. She is also the project lead of the VNF Forwarding Graph project in the OPNFV community. Cathy has a Ph.D. degree in Computing Engineering and has multiple patents.)*

* **John McDowall** *(John McDowall is SDN/Virtualization Architect at Palo Alto Networks where he is working on the dynamic insertion of security policy into virtual environments and clouds. Currently he has been actively contributing to Openstack Service Function Chaining, Openstack Neutron-OVN and OVS/OVN to enable service function chaining. Previously he was at Cisco where he developed the programmable network architecture that played a key role in Cisco’s SDN strategy, which he presented to large customers and internally. He has presented to industry forums on web services, security, and SAAS. John has an MSc from UC Berkeley and a BSc from University of Glasgow.BD)*

* **Na Zhu** *(Na Zhu is a senior cloud networking services developer in IBM China Software Development Lab, she has rich experience in networking design and develop including tranditional network, network virtualization, SDN/NFV and cloud computing network.  )*

How software defined networking promises simplifying your life
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The demand for and consumption of Internet services and resources is growing. These are times in which software running on connected intelligent devices is replacing stand alone, single purpose hardware. Traditional networking is under the pressure from a new technology evolution: hardware can run faster but software can adapt faster. The networking data plane can be separated from the forwarding data plane and move to centralized, software-orientated configuration and datacenter management without relying on proprietary technologies. We know OpenStack is a popular cloud solution, but it is not the only solution out there and not all applications are prepared for running on an OpenStack infrastructure. To be able to offer integrated solutions, we need to use smart network technologies to interconnect those solutions. In large and hybrid data centers we need to be able to control and respond as fast as possible, with the minimum error percentage or exposition to the human factor.


* **Federico Ressi** *(I am born in 1979 near Parma (Italy) where I studied as Software Engineer and where I worked for a small company as C++ software developer writing applications for video streaming over TCP/IP and video rentering in real-time. I then moved to Spain where I got most of my working experiences in the aerospace industry. Most notable projects was related to fluid dynamic simulation (Python), geo-localization using signals relaied from Galileo and GPS satellites (C) and supervision software for civil airports (Java). I also lived for short periods in France, the Netherlands and Englad as Python software consultant working on militar and scientific sofware. In the year 2015 I joined Intel in Ireland and I joined OpenStack community as opens source developer. My focus areas are mostly OpenStack networking-odl plugin and DevStack (some bug fixing). You can have a look at most of my open source contributions on my GitHub page: https://github.com/FedericoRessi  )*

* **Alvaro Soto** *(I was born in Chile in a little town call Linares in 1983, but living in Mexico City since 2003. I'am a system engineer with a complete knowledge designing and implementing secure, high availability architectures thinking in availability, scalability, reliability as a primary focus. Also enjoy writing code to integrate closed API (vmware, netapp, etc) with OpenSource frameworks, and to develop helper scripts from Ceph rbd and librados mainly in Python and perl sometimes. Nowadays fully focused in cloud solutions (healthy disengagement between non cloud to cloud solutions) and architectures using OpenStack and Ceph. https://github.com/alsotoes http://headup.ws)*

* **Erick Maqueda** *(Netwoking Professional and SDx enthusiast, with wide experience on several networking technologies and vendors like Cisco, Arista, Juniper and Brocade.)*

Distributing OpenStack Networking Across Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scaling OpenStack in many cases involves operating multiple OpenStack regions or using Nova cells. One of the significant network challenges faced by operators is how to connect workloads in this distributed environment. This is also a challenge encountered when attempting to operate a hybrid cloud with a mix of on-premise and offsite resources. Deploying multiple OpenStack instances and connecting them together presents unique networking challenges. Floating IP's are a common and workable solution for connecting workloads in these environments. However, floating IP's can also be an inefficient way to connect workloads.In this session we will introduce a solution for connecting multiple OpenStack deployments using BGP EVPN. We will discuss how it integrates with features already available in neutron such as address scopes, DVR, and BGP dynamic routing. We will also discuss the current state of development of this solution and what functionality to expect in future releases.


* **Steve Ruan** *(I am senior software engineer of IBM cloud networking service, focus on the OpenStack based hybrid cloud solution. I used to develop routing appliance in IBM SDN-VE since 2014, then developed in the OpenStack Neutron community especially on neutron-dynamic-routing project and developed in the OVN community. Before that I have more than 8 years in development of hardware switch and router.)*

* **Ryan Tidwell** *(Ryan Tidwell is a contributor to the OpenStack Neutron project and has been deploying and tinkering with OpenStack in various roles since the Diablo release of OpenStack.  Ryan has been working at HP (now Hewlett packard Enterprise) since 2008.  He is well-versed in developing manageability tools for systems administrators and OpenStack operators, building SDN controllers and applications, and currently contributes to OpenStack's Neutron project.  Raised in Northern Colorado, Ryan has a B.S. and M.S. in computer science from Colorado State University and the University of Colorado respectively.  He currently resides with his family in Roseville, CA.)*

* **Vikram Choudhary** *(Working with Huawei Technolgies India Pvt Ltd. Have around 7.5 years of experience in routing domain (protocols like RIP, OSPF and BGP). Have around 1.5 years of experience in openstack. Mainly contributing for neutron in openstack)*

Scaling Up OpenStack Networking with Routed Networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, we will introduce Neutron's Routed Networks functionality which was added during the Newton cycle. Routed Networks rely on a layer 3 architecture that routes traffic to small segments of the network to achieve scale. This approach serves well deployments where large scale is a paramount requirement and users just need a set of VMs with IP addresses. Routed Networks showcases how technology can be simplified and scaled, two goals that are often difficult to meet together. We hope to inspire architectural decisions that eliminate unnecessary complexity and complicated user experiences. This presentation will include a live demo.


* **Miguel Lavalle** *(Miguel Lavalle is a regular contributor to Openstack's Neutron project. Over the past 4 years, he has made contributions to the L3 agent, Tempest testing of Neutron, integration of Neutron, Nova and Designate and more recently, during the Newton cycle, participated in the development and testing of Routed Networks . He is a member of the Neutron L3 sub-team, where he performs duties as "bugs czar". At IBM, he is a member of the Linux Technology Center development team, focused on contributing code to the Neutron project. Miguel lives in San Antonio, TX, with his wife Beatriz and their Beagle Toto. He is an avid gliders pilot, having accumulated more than 700 hours of flight time, most of them in cross country tasks in his Jantar Standard 3. When not coding or flying, he enjoys swimming and yoga.)*

* **Carl Baldwin** *(Carl Baldwin is a regular contributor Openstack's Neutron project and has been a core reviewer since 2014. He is the Neutron L3 Lieutenant. He started his career developing electronic design automation software with HP’s microprocessor design projects: PA-RISC and Itanium. Years later, he spent a short time on a few of HP's network attached storage products. He was drawn to computer networking. He consistently stepped outside his purview to weigh in on office networking issues as well as to provide expertise to the network design in the products. In January, 2013, he got the opportunity to meet HP's new Neutron team in Fort Collins. He soon hired on to the team and has been enjoying it ever since. He is fascinated by network virtualization in the cloud. Carl lives in Fort Collins, Colorado with his wife Emily, two daughters, and a son. He loves to run, hike, swim, mountain bike, and plays disc golf and volleyball. Otherwise, his hobbies look a lot like his work: writing software and tinkering with networking.)*

Physical bug fix in a logical world: an approach to network root cause analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud computing introduces a host of new troubleshooting challenges for the operator:Poor performance might stem from one of many unrelated issues, from CPU utilization to network congestion to physical network errors.Problems can be intermittent - there for your users, but not by the time you lookTracking problems from the virtual network env. to the physical network is very tricky.Whether private or public cloud, the need for rapid network fix is the same - get it done now! Yet the added complexity, moving parts and layers of an SDN greatly complicate the root cause analysis and bug fix. In this session we first outline the existing challenges faced by network operators in a cloud env. We then elaborate on the abilities built into MidoNet for solving some of the challenges. These new capabilities are supported by the Cumulus Linux platform and Broadcom Broadview, although in principle MidoNet tools work on any platform that provides the necessary information and interfaces  


* **Alon Harel** *(Before Midokura, I have hold architecture positions at Marvell Semiconductors and Mellanox Technologies dealing with Ethernet switching, cloud virtualization and SDN technologies. I have spent the first half of my career as a software engineer and a software team leader developping software for embedded systems in the communication industry.)*

* **Bhaskar Chinni** *(Bhaskar is driving Broadcom's SDN & NFV solutions for the Data center, Enterprise & Service Provider market segments. He is responsible for BroadView Instrumentation software suite and ecosystem. Before joining Broadcom, Bhaskar has worked at Ericsson for 14 years in various roles, most recently, leading Ericsson's Cloud & SDN solutions for the service provider market segment.     )*

* **JR Rivers** *(JR is the co-founder and CTO of Cumulus Networks where he is deeply involved in the company, product, and technology direction.  JR has been involved with networking since Ethernet only ran on coaxial cables.  He's worked on some of the most foundational networking products of their time, from early Network Interface Cards at 3Com through switching and routing products at Cisco. JR's early involvement in home-grown networking at Google and as the VP of System Architecture for Cisco's Unified Computing System both helped fine tune his perspective on networking for the modern datacenter.)*

The evolution of OpenDaylight with OpenStack: big changes for production environment in future
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenDaylight is an open source SDN(Software Defined Networking) platform which provides various features. One of the biggest use-case is OpenStack integration as network virtualization. So the OpenDaylight community has spent much effort on this use case along side with neutron community. In OpenStack netwon cycle and OpenDaylight Boron cycle, we've made big progress and changes. In OpenStack side migration to new driver framework for HA, in OpenDaylight side migration to new code base, VPNService from the old netvirt. Those are the essential and big change necessary for production  environment. Those changes come with new features, L2Gateway, ACL for security groups, SNAT, QoS, SFC and etc.Since they are all internal changes, it shouldn't affect user facing features ideally, but the real world is not perfect. The implementation changes, pitfalls and things to be aware of will be discussed. This session will be concluded with the future plan.


* **Isaku Yamahata** *(Isaku Yamahata is a Software architect in the Open Source Technology Center, Intel. His main focus is Network virtualization as Software Defined Networking and Network Function Virtualization. Isaku is an active OpenStack Neutron (networking) developer and has in the past contributed significantly to qemu, kvm, Xen, and Ryu SDN frameworks.)*

* **Sam Hague** *(Sam Hague is the Project Technical Lead for the OpenDaylight OVSDB project and Senior Principal Engineer in the Office of Technology at Red Hat, Inc. Sam's most significant contributions to OpenDaylight concern the network virtualization provider and OVSDB MD-SAL southbound plugin as well as service function chaining and the neutron northbound. Previous experience includes leading the software development at Extreme Networks adding OpenFlow to their line of switches and a variety of technologies at Cisco Systems from creating the first SIP IP phones to adding Bluetooth and VPN capabilities to mobile routers to implementing H.264/AVC video conferencing on Android-based tablets. (https://www.linkedin.com/in/samhague))*

* **John Joyce** *(John is an active contributor to Openstack. He has been involved with Neutron since the essex timeframe where he added Horizon integration for Neutron/quantum. In addition to that he authored the first Cisco plugin for intelligent parallel orchestration of Cisco devices with Neutron. He has also driven key features in Neutron like dynamic segmentation. He's currently active in the Neutron ML2 community)*

Under the Trenchcoat: Neutron Agent Extensions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron agents are a critical part of the Openstack networking infrastructure. The Quality of Service (QoS) effort leading up to Liberty prompted the creation of an L2 agent extension mechanism in order to provide a defined ability for agent extensions to be added to the neutron-openvswitch-agent. Other Neutron L2 agents, such as neutron-linuxbridge-agent and neutron-sriov-agent, have since been modified to utilize this extension mechanism. In the Newton cycle, this framework was generalized and implemented in Neutron's L3 base agent, with FWaaS' v2 implementation as the initial subscriber. This talk will discuss: The history of agent extensions in Neutron. A deep dive into how they function. Various use cases that take advantage of them. We will review a selection of the current use cases for agent extensions. Finally we will examine future use cases and development trends for Neutron agent extensions.


* **Nate Johnston** *(I have been working alternately as a developer, a system administrator, and a system architect since 1997.  I have been working on Openstack since September, 2014, with a focus on the Quality of Servce ("QoS") functionality within Neutron.  I have been with Comcast for 6 years and worked as a system administrator, system architect, and automation developer prior to focusing on Openstack.  I have previous positions at MCI, Cable & Wireless, Broadwing, and AOL.   I am very excited to be a part of the Openstack community.  I believe strongly that the open source paradigm not only enables the enterprise, but that it enriches the entire technology community, and indeed all mankind.  )*

* **Margaret Frances** *(I have worked on OpenStack development, almost exclusively in Neutron, since August of 2015. Prior to that, I worked as a web application developer for the networking and telecommunications group at University of Pennsylvania's Information Systems & Computing.)*

* **David Shaughnessy** *(I'm a Network Software Engineer in Intel's Networks Platform Group. I recently graduated and I'm currently working on OpenStack, specifically in Neutron with an interest in QoS. My contributions are limited at the moment but I'm hoping to learn as much as I can and contribute to OpenStack.)*

Enabling Network Intents for OpenStack using Labels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As Neutron features evolve and become more complex, network intents can be specified by multiple stakeholders (e.g., tenants, operators), either directly via Neutron APIs or indirectly via HEAT templates. These individually specified intents may overlap/conflict, resulting in unexpected runtime behaviors. We demonstrate how to enable high-level network intents for managing diverse OpenStack services.  We present a system that defines a group of endpoints (EPG) using logical labels, with each label representing diverse endpoint attributes: e.g., application components they host, their locations, and tenants. We extract such labels and relationships using Congress and automatically construct a label namespace from metadata and database. This enables users to correctly define EPGs using the labels and allows our system to proactively/automatically compose these intents. Users can express complex intents as graphs to represent security/QoS. We also demonstrate our prototype on Newton.


* **Joon-Myung Kang** *(Joon-Myung Kang is a Researcher at Hewlett Packard Labs, Palo Alto, CA. His research interests include cloud computing, software-defined networking, and network management. He has been working on OpenStack networking, computing, identity & access and monitoring since 2011 (diablo release). Before joining in Hewlett Packard Labs, he was a core architect and developer for Canadian SAVI (Smart Applications on Virtual Infrastructure) testbed based on OpenStack which has been deployed across much of Canada. Currently, Joon-Myung is working on Policy Graph Abstraction for OpenStack networking and label management for OpenStack services. Talk expereince in OpenStack Summit: OpenStack summit Austin 2016: Policy Canvas: Draw your policies for OpenStack services https://www.openstack.org/videos/video/policy-canvas-draw-your-policies-for-openstack-services OpenStack summit Vancouver 2015: Supporting network bandwidth guarantees with OpenStack: an implementation perspective https://www.openstack.org/summit/vancouver-2015/summit-videos/presentation/supporting-network-bandwidth-guarantees-with-openstack-an-implementation-perspective)*

* **Mario Sanchez** *(Mario is a Research Scientist at HP Labs in Palo Alto, CA. He received a Computer Science Ph.D. degree from Northwestern University in the Electrical Engineering and Computer Science Department. His research interests include distributed systems, cloud computing and Internet measurements.  )*

* **Anu Mercian** *(Anu Mercian is a Sr. Systems Engineer, in SDN R&D at Hewlett Packard Enterprise, Networking, Palo Alto, CA. She earned a PhD and MS in Electrical Engineering from Arizona State Univeristy and Bachelors in Electronics Engineering from CET, India. She is currently working on OpenDayLight Network Intent Composition (NIC) and her interests include Intent-based Networking, Policy Management and Service Chaining. She is also a Research Affiliate with Lawrence Berkeley Labs (LBL) where she collaborates in SDN challenges. She serves as a reviewer for various Publications including Elseiver, Optical Communications, Journal of Networks etc. Prior to HPE, she has worked with Energy Sciences Network (ESnet) and Huawei towards different SDN application services. )*

Service Function Chaining (SFC) with Neutron, CNI and CNM based VNFs using OpenContrail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Based on the type of virtualization different networking frameworks are used.OpenStack networking is based on Neutron, Docker uses the Container Networking Model (CNM)and Kubernetes, OpenShift and Mesos can use the Container Network Interface (CNI).The common denominator of the three frameworks is a plugin system for externalSoftware Defined Networking (SDN) drivers.In this session we will talk about the OpenContrail SDN controller providing drivers forall three frameworks. As part of the session we will demonstrate how the orchestration toolsand command line interfaces of the frameworks can be used to create Virtual Networks (VNs) andto interconnect Virtual Machines and Containers. We will show that VNs created with oneframework can be consumed by another framework. To show the full potential of the solutionwe will setup a Service Function Chain (SFC) with three Virtual Network Functions, each based on oneof the three frameworks and distributed across multiple hosts.


* **Michael Henkel** *(Prior to joining Juniper in 2014 Michael worked 16 years for HP. In HP he spent his last 2 years on doing research on SDN and writing applications unleashing the power of SDN. Michael is passionate about SDN and virtualization. As part of Junipers Contrail team he takes care for integrating OpenContrail into whatever kind of new and exciting technology comes along. Lately he started to enjoy the brave new world of Containers and their need for a robust networking infrastructure.)*

* **Rudra Rugge** *(Rudra joined Juniper networks through the acquisition of Contrail Systems. He leads the service infrastructure, container networking team for Opencontrail. Rudra managed the virtual edge networking team at VMware prior to Contrail Systems. He has led engineering teams at F5 networks for LB, DPI, Firewall products and at Juniper Networks for Switching products.  Prior to that he worked at Foundry Networks and Cisco Systems where he developed various switching, MPLS and multicast routing software. Rudra holds a Masters in Computer Science from Ohio State University.)*

* **Sanju Abraham** *(Sanju is a software engineer at Juniper Networks working on Opencontrail. He works with customers and prospects on developing and optimizing solutions for virtual network implementations for private and publicclouds.  )*

Stateful Service Meets Stateless Gateway: Resolve Bottlenecks to Horizontally Scale L3 Gateways
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Stateless layer 3 gateways appear to be a simple way to increase scalability and on-ramp traffic to your virtual network. Growing throughput requirements can easily be met with additional gateway nodes. However, the apparent simplicity of L3 gateways scaling breaks down with the addition of stateful L4 functionality, such as NAT or load balancing, when the gateways quickly become a bottleneck. In this session, we present how we identified, debugged and ultimately solved this problem. To this end, we borrowed from the design of Google Maglev and built on top of the high performance foundation offered by Cisco's Vector Packet Processing (VPP) for DPDK. During the session, we demonstrate this functionality built on top of open-source MidoNet, although the same solution can be transposed to alternative SDNs.


* **Ivan Kelly** *(I've been active in virtual networking with Midokura since early 2015, previous having worked on the networking stack of SymbianOS for Nokia. I also spent a large part of my career at Yahoo, building distributed systems and databases, most notably Apache BookKeeper and Apache Omid.)*

* **Alex Bikfalvi** *(I am a developer at the networking virtualization software company Midokura. There, I contribute to the MidoNet project, with a focus on the control plane. Previously, I worked both in the industry as a software engineer as well as in academia as a networking researcher on networking and distributed systems, having earned a PhD from the Carlos III University in Madrid.)*

Sharing Your Driveway With Neighbours The OpenStack Way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack provides many technologies to ensure your applications are protected from noisy neighbours using all their CPU.  We explore how to achieve the same thing for networking. This talk will explore partitioning network resources with OpenStack and how it complements the significant progress that is being made on partitioning compute resources with Enhanced Platform Awareness. The following will be covered: How to run applications to get dedicated compute resources The current state-of-art on network scheduling and bandwidth management from a tenant perspective Where this needs to go to provide dedicated network resources How both the compute and network infrastructure contribute to the solution space How fabric management is a necessary component of a cohesive solution We will report on our experiments to date, and identify areas where we can extend OpenStack to better address network isolation.


* **Adrian Hoban** *(Adrian Hoban is a Principal Engineer in Intel's Data Center Solutions Group and the Technical Steering Committee chair for the Open Source MANO project. In Intel he is the system architect responsible for orchestration of Software Defined Networking and Network Function Virtualisation and leads the Intel team on OpenStack contributions in this area. He specialises in open source software such as OpenStack, Linux, Open vSwitch, KVM, QEMU and libvirt. Adrian is also active in standards initiatives such as ETSI-NFV.  In OpenStack Adrian set the architectural direction for the Intel contributors on areas such as PCIe passthrough, SR-IOV, Enhanced Platform Awareness for NUMA, Huge Pages, CPU pinning, and thread policy, OVS with DPDK enablement, and Security Groups. He has a particular interest in extensions that relate to using OpenStack to facilitate high performance application deployments and infrastructure utilisation. )*

* **Ian Wells** *(An OpenStack developer and user since the Essex release, Ian works on the internals of Openstack, on applications to run on top of Openstack, and on making Openstack easy for people to use.  His current focus is in NFV, the work to use Openstack to provide virtual network functions in an OpenStack cloud for use in telco networks - a balancing act to get maximum performance from a cloud infrastructure while running mission critical network intensive workloads.)*

Load Balancing as a Service and Octavia, Newton and Beyond
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Load balancing as a Service (LBaaS) has been one of the critical features asked for by cloud tenants. For the Newton release cloud providers such as Rackspace, Hewlett Packard Enterprise, IBM, etc. have partnered with the community and load balancer vendors such as Radware and A10 to enhance the new LBaaS v2 and Octavia services with improved reliability, security, and functionality.  We will be giving an update on the Active/Active work on Octavia as well as discussing the merge of LBaaSv2 and Octavia into a new proposed project called OpenStack LBaaS.


* **Michael Johnson** *(Michael is the PTL for OpenStack Octavia and a core reviewer in the OpenStack Neutron-LBaaS and Kosmos (GSLB) projects. Over his fifteen year career at HP he has worked on data center automation, distributed network systems, embedded system design, and big data. Recently Michael join the cloud load balancing team at Rackspace.  Michael lives in Corvallis, Oregon.)*

* **Stephen Balukoff** *(Stephen Balukoff is a Principal Software Developer at Blue Box, an IBM Company. He graduated Summa Cum Laude with a Bachelor's degree in General Studies from the University of Idaho. This means he is very well qualified for nothing in particular. He has spent the last 18 years working in the IT industry. Starting in customer support positions, he worked his way through roles involving systems administration, systems architecture, software engineering, and finally principal technologist. His work always has involved finding practical solutions, mostly for practical problems, and for occasionally practical clients. This work is no exception to that rule. Nowadays you can find him annoying members of the OpenStack, specifically in the Octavia load balancer project, which he named.)*

How Scalable is OVN-powered OpenStack:  A Cloud Operator’s Perspective
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open Virtual Network (OVN) adds native support for virtual network abstractions. OVN is designed to be more scalable than the Neutron OVS implementation. As it reaches it's first release, work is underway to prove it's scalability in a large scale deployment. We present our methodology of building a CI/CD pipeline that helps OpenStack cloud operator to quickly identify performance and scalability bottlenecks in OVN, and to decide on the adoption of latest patches based on experimental results. Our solution deploys emulated compute nodes and real control plane setups, by containerization of OVN components, fake OVN chassis, and the rally-ovs extension. We will share the latest results from our experiments, as well as how these results help improve the overall scalability of OVN and OpenStack network functions powered by it. We also talk about how these results are enabling us to verify commits by integrating the work into the OVS/OVN continuous integration setup using travis-ci.


* **Hui Kang** *(Hui is a research staff member at IBM T.J. Watson Research Center. He is currentlywith the cloud infrastructure team, focusing on OpenStack, Docker, Linux kernel, etc. Hui has contributed to several open source projects, including openstack/kolla, Docker, CRIU, and ovn-scale-test. He also enjoys hacking OS kernel and learning hardware techniques.)*

* **Kyle Mestery** *(Kyle is a Distinguished Engineer and Director of Open Source Networking at IBM. He leads a team focused on Open Source networking at scale. Kyle is also a member of the OpenStack Technical Committee, and the former PTL of OpenStack Neutron for the Juno, Kilo, and Liberty cycles. Kyle lives with his wife and kids in Minnesota.)*

* **Lei Huang** *(Lei huang is currently an MTS 1 Software Engineer in ebay's Cloud IAAS Team, focusing on SDN for ebay private cloud. He created an ovs scalability test framework based on OpenStack/Rally. He is currently involved in a routed network solution at ebay.)*

OpenStack in Reference Implementation for Next Generation Network Services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open source and open standards are coming together to maximize the pace and relevance of both. The MEF, with its 125+ service provider member community, is defining Lifecycle Service Orchestration (LSO) with APIs enabling dynamic network services for the digital economy and hyper-connected world, providing an on-demand, cloud-connected, secure, and assured experience. The MEF provides a practical evolution toward interconnected, orchestrated, and automated networks powered by LSO, SDN, and NFV. This talk briefly describes the Third Network vision, the LSO architecture, and how it dynamically delivers high value Carrier Ethernet (CE 2.0) services enhanced with L4-L7 VNF-based services. It also explains how open source projects, including OpenStack, OpenDaylight, and OPNFV are being enhanced and applied to create a reference implementation of this architecture.  


* **Charles Eckel** *(Charles is a developer evangelist in Cisco DevNet with a passion for open source software and open standards. His journey with open source began in 1999 as a founding member of Vovida Networks where he developed some of the industry's first open source Voice over IP (VoIP) protocol stacks and applications. Now at Cisco, Charles has become a recognized champion of open standards, open source, and interoperability. He runs the Open Source Dev Center, which focuses on Cisco’s major open source contributions, use, and community engagements, including OpenStack, OpenDaylight, and OPNFV. Last year, he successfully introduced open source hackathons into IETF and MEF, revolutionizing the way these SDOs operate and uniting open source software with open standards to maximize the pace and relevance of both. Charles speaks regularly at CiscoLive and has also been a speaker at previous OpenStack, RedHat, LinuxCon, and MPLS SDN NFV World Congress events.)*

Neutron Quality of Service, What's new in Newton and what will be in future.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Newton is the third release of Neutron with Quality of Service framework available and it's being developed quickly. In this release a couple of new features was added: Improved mechanism to validate QoS rules in mixed environments (SR-IOV, OVS, LB, ...). Maximum bandwidth limit for ingress traffic: supported by Linuxbridge and Openvswitch L2 agents. Minimum bandwidth rules for egress traffic: it provides a best effort guarantee of available egress bandwidth for ports. DSCP markings: supported by Openvswitch L2 agent.


* **Sławek Kapłoński** *(Devop at OVH working on large cloud infrastructures. Software Defined Networking geek and programming enthusiast, I work in R&D team to solve networking chalenges and integration requirements on large scale public cloud solution. Developer of Openstack Neutron in my free time. You can catch me on #openstack-dev or #openstack-neutron channels at FreeNode)*

* **Miguel Angel Ajo** *(Neutron developer, and package maintainer. Passionate about engineering and programming in general (high level to low level). Networking issues scalation ninja. Find me around #openstack-neutron @ FreeNode)*

* **Rodolfo Alonso** *(OpenStack rookie, but truly enthusiastic. Focus on networking and metering projects.)*

IP-Multicast in an Openstack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you planning to use applications that use IP multicast in your OpenStack cloud – e.g IPTV? Are you planning to use high volumes of IP multicast? Are you planning to automate also the network resources required to run IP multicast from the viewpoint of an infrastructure provider? There is currently no multicast API available in OpenStack to declare resources needed by an application. As a result IP multicast runs only in L2 networks. But how to manage L3 multicast routing? High volumes of IP multicast can only be handled efficient if offloaded to the physical network infrastructure – but this offloading consumes a part of the hardware resources of the network equipment. This offloading needs to be controlled by the infrastructure provider. To do this, information is needed from tenants via an API. The goal of the talk is to collect enough interested parties to work on a blueprint for an OpenStack Multicast API, which covers L2, L3, cloud local and global network aspects.


* **Ralf Trezeciak** *(As a Senior Network Architect, Ralf working on data center/cloud network virtualization and Software Defined Networking technologies at Deutsche Telekom. He is currently working on the network architecture for a Openstack based NFV cloud at Deutsche Telekom.)*

Unified networking for VMs and containers for Openstack and k8s using Calico and OVS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Mixing containers and VMs in one environment is difficult. Ongoing progress in containerization of services should be confronted with legacy use-case of enterprise workloads. It should be possible to stay opened to 'old-style' solutions and in the same time support latest trends in microservicing. The talk will present possible future of datacenter networking platform based on containerized Openstack environment run on Kubernetes cluster. The presentation will show architecture of co-located containers and VMs joined in common networking framework. To enable this, Neutron, Calico and OVS technologies will be explored. We will show how they can be configured to support unified networking. The evaluation of solutions existing on market will lead to assessment of current value and will show needed improvements to achieve common use-cases in both containers and VMs worlds. The requirements to fulfill are HA, multitenancy and exposing services to the Internet access.


* **Artur Korzeniewski** *(Artur Korzeniewski is a software engineer at Intel, currently working in Neutron community on subjects related to upgradability and HA of services. He is Neutron Upgrades team member, dedicated to improve the process of upgrade. Before joining the Neutron team, he was closely coupled with OpenStack since Diablo release, working on resource scheduling and compute assurance. Artur likes new challenges, path-finding and designing solutions from scratch. He is the Python language and networking fan. Artur has master degree in IT from Gdańsk University of Technology in Poland.      )*

* **Vladimir Eremin** *(Site Reliability Engineer in high-loaded and cloud business applications.)*

OVN - Moving into Production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OVN is a network virtualization project that brings virtual networking to the Open vSwitch user community and is the latest iteration of Open vSwitch integration for OpenStack.  It is an open source project being developed by the core OVS development community, which includes large-scale network operators.  In this talk, we will cover the state of OVN with a focus on the newest features and improvements that help make OVN ready for production usage.  Topics include performance and scale improvements, L3 gateways, and more.


* **Russell Bryant** *(Russell is the Technical Director for OpenStack at Red Hat, Inc.  He is on the OpenStack Technical Committee (since Fall 2012) and served on the OpenStack Foundation Board of Directors from January 2015 to June 2016.  Russell has been contributing to the development of OpenStack since the Fall of 2011.  His most significant contributions around OpenStack have been to Nova and most recently Neutron and OVN. Prior to working for Red Hat, Russell spent 7 years (2004 - 2011) working for Digium on the Asterisk project. In the later years, Russell was the leader of the Asterisk project as well as the Engineering Manager for Asterisk development at Digium. Russell is also a published author.  Russell co-authored "Asterisk: The Definitive Guide" and "Asterisk Cookbook", published by O'Reilly Media.  He also contributed a chapter on Asterisk to the book "Architecture of Open Source Applications". Russell graduated from Clemson University with a Bachelor's degree in Computer Engineering in the Fall of 2006.  He currently resides in Charleston, South Carolina.)*

* **Ben Pfaff** *(Ben Pfaff is a lead developer of the Open vSwitch project and led the development effort of the OpenFlow reference implementation. He was a founding employee at Nicira and is currently at VMware. He received his PhD from Stanford University in 2007. Ben has worked in free and open source software projects, including Debian and GNU, for over 20 years. Ben is a Senior Member of ACM and a Fellow of the Open Networking Foundation.)*

* **Justin Pettit** *(Justin Pettit is an engineer at VMware's Networking & Security BU. Justin joined VMware through Nicira acquisition and was a founding employee at Nicira Networks. He was one of the original authors of the OpenFlow Standard, working on both the specification and reference implementation. Justin was an early developer of the NOX OpenFlow controller platform. He is one of the lead developers of Open vSwitch and involved in the development of VMware's other products. Prior to Nicira, Justin worked at three successful startups focused on network security. While completing his Master’s degree in Computer Science at Stanford, he worked on research that became the basis for the OpenFlow Standard and software-defined networking.)*

Give your compute nodes superpowers with layer 3 open networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack networking with multiple tenants can cause a complicated infrastructure. This presentation contains two parts: 1) Implementing an all layer 3 VXLAN network topology all the way to the compute nodes, and 2) Using this concept to design a network where traffic flows are clear to understand, debug, and troubleshoot. Combining these concept with standard Linux DevOps tools (like Ansible and Git) and other open protocols, one can create a more agile and easy to debug network with better automation.


* **Attilla de Groot** *(Over the past few years I've worked at ISPs and Enterprises. Currently I'm working for Cumulus Networks as the Systems Engineer for EMEA. I'm working on scalable networking using standard protocols and technologies based on the open networking concept with Cumulus Linux.)*

Tenant Networks vs. Provider Networks in the Private Cloud Context
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Neutron defines two major types of networks- tenant networks and provider networks. OpenStack administrators must decide what their Neutron network deployment strategy will leverage- tenant networks, provider networks or some combination of the two. This session will describe the unique challenges presented by tenant networks in the private cloud context and will build an argument for why shared provider networks may provide the best Neutron network deployment strategy for enterprise private clouds. This session will also discuss the rationale behind the assertion that network security is now orthogonal to network topology (which if true, is a significant factor leading to the viability of shared provider networks).


* **Marcos Hernandez** *(Marcos Hernandez is a Staff Systems Engineer in the Network and Security Business Unit (NSBU). He is responsible for supporting large Global Enterprise accounts and providing technical guidance around VMware's suite of networking products, including NSX. Marcos has a background in datacenter networking design and expert knowledge in routing and switching technologies. Marcos holds CCIE certification #8283, VCIX and a Masters Degree in Telecommunications from Universidad Politécnica de Madrid.)*

Deploying Policy-based vTap on Virtual Ports, Service Function Chains, and VNFs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As virtual networks grow with complex VNFs and service function chains, monitoring and troubleshooting can become unwieldy without analyzing packet flows and traffic patterns to diagnose network issues. While first generation vTap offered port mirroring type functionality, policy-based vTap is extending the capability to perform more intelligent data gathering that are defined by classification and action rules on flows and reverse flows.  These rules can be applied at any point in a virtual network on virtual ports or any part of a service function chain including in between VNFs. Join this session for a deep dive on: Using vTap in a virtual network vTap policy classification and action rules vTap policy chain definitions Applying vTap in a service function chain


* **Jamal Arif** *(I am currently involved in building SDN based OpenStack Private/Public Cloud infrastructures for various range of customers including enterprises, telcos, & service providers etc. Working with Dev-Ops and Network Operations teams to design and implement highly available, scalable and secure multi-tenant cloud systems for different cloud computing models (IaaS, PaaS, SaaS), and using virtualization techniques for networks functions virtualization. Have earlier experiences in core IP and telecommunication networks (CS/PS Core networks and IP/MPLS Networks) working in a multi-vendor environment (NSN Rel4, Huawei R4, Cisco, Juniper). In addition have hands-on knowledge of NGN networks (3G, 4G LTE), and legacy 2G GSM TDM networks, and Core & IP signaling protocols.)*

SDN Scale-out Testing at OpenStack Innovation Center (OSIC)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Innovation Center (OSIC), established by Intel and Rackspace, is created to accelerate adoption of open source cloud operating system while supporting open source principles. OSIC provides ready-to-use data center facilities to the OpenStack community for development and test.  This case study presentation highlights a scale-out test performed within a 3 week period using OpenStack Ansible Community based on Liberty with an SDN overlay network connecting 131 nodes running over 1,000 VMs. Tempest and Rally tests were conducted to validate functions including high availability failure scenarios. Join this session to find out more about OSIC and the SDN scale-out test configuration, scenarios, and results.


* **Jamal Arif** *(I am currently involved in building SDN based OpenStack Private/Public Cloud infrastructures for various range of customers including enterprises, telcos, & service providers etc. Working with Dev-Ops and Network Operations teams to design and implement highly available, scalable and secure multi-tenant cloud systems for different cloud computing models (IaaS, PaaS, SaaS), and using virtualization techniques for networks functions virtualization. Have earlier experiences in core IP and telecommunication networks (CS/PS Core networks and IP/MPLS Networks) working in a multi-vendor environment (NSN Rel4, Huawei R4, Cisco, Juniper). In addition have hands-on knowledge of NGN networks (3G, 4G LTE), and legacy 2G GSM TDM networks, and Core & IP signaling protocols.)*

* **Travis Broughton** *(Travis is a Product Marketing Engineer in Intel's Open Source Technology Center, focusing on Intel's upstream contributions to cloud and data center software.  He previously spent 15 years in Intel IT, where he was an architect working on OpenStack deployment, PaaS, and cloud-native application development practices.)*

* **Melvin Hillsman** *(Currently working as Ops Team Tech Lead at OpenStack Innovation Center | Rackspace. I live in the great city of Houston, TX with my awesome family. I enjoy spending most of my time learning more about all kinds of aspects of the technology field from innovations in microprocessing, changes in DataCenter infrastructure, to the latest trends in Cloud Computing. Working with the OpenStack community is a great experience as I assist in leading a monthly OpenStack User Group.)*

VLAN Transparency support using the Neutron Open vSwitch ML2 mechanism driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV service VMs often need to communicate over many tagged VLAN channels.   Support for transmitting VLAN tagged traffic across Neutron networks is only provided by certain Neutron plugins and ML2 mechanism drivers.   This talk will discuss the work being done to support “VLAN transparency” using the Neutron Open vSwitch ML2 mechanism driver and the support for QinQ in Open vSwitch.


* **Ed Bak** *(Ed Bak is a Senior Networking Engineer at Hewlett-Packard Enterprise.  He is currently working on HPE Helion Openstack as the lead for the HPE Neutron engineering team.   He has been an upstream contributor for Neutron and Nova and has been working with Openstack since the Diablo release.   )*

* **Dermot Tynan** *(TBD)*

Calico in the wild: Letting the cat out of the bag
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Networking is interesting again. With a plethora of SDN solutions in the market, it can be intimidating to choose the right solution for your data center. Project Calico is the newest kid in the block with a simple premise of making your data center look and function like the internet. But can it deliver on the promise? Is it the right solution for you? Join us to find out. In this talk, we will give an introduction to Calico and discuss how it integrates with OpenStack and OpenShift (Kubernetes). We will also compare its approach with Openvswitch, discuss its gotchas and talk about its performance in the private and public clouds. At the end of this talk, an operator will be able to find out if Project Calico is ready for production for their use cases.


* **Rudrajit Tapadar** *(Rudrajit specializes in virtual networking and is excited to be a part of Symantec's Cloud Platform Engineering SDN team. He has deep interest in open source technologies and has also been a contributor to OpenStack Neutron and OpenStack Designate. At Symantec, he is responsible for designing, developing and operating an enterprise grade secure multi-tenant cloud network.)*

* **Karthik Ramasubramanian** *(Karthik is a Principal Software Engineer in the Cloud Platform Engineering team at Symantec. Karthik has been working on SDN since the buzz for the space began. He's now working at Symantec, building and operating their Opentack based cloud's and SDN solution.)*

* **Jasmeet Sidhu** *(Jasmeet is a senior devops engineer at Symantec, focusing on the overlay network.)*

Best practice of ChinaMobile in deploying SDN and NFV with 1000+ compute node OpenStack environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

- Overview of China Mobile Public Cloud - Introduction of the 1000+ compute node deployment environment- Why China Mobile did not use stock Neutron - Why China Mobile finally deployed commercial SDN and NFV nodes in the Cloud - How China Mobile deployed 1000+ compute nodes with Nuage SDN and NFV in the field


* **wu jiangtao** *(Jiangtao wu is Virtualization Network Manager of China Mobile(Suzhou) Software Technology Co.,Ltd. He has been involved with Cloud Computing, Virtualization Network, OpenStack Neutron,SDN,NFV for over four years. His work is to resolve network problems of Cloud Computing of China Mobile  With Neutron SDN and NFV. He He has been involved in the construction of China Mobile's public cloud and private cloud.)*

* **Scott Drennan** *(Scott Drennan is a Principal Product Manager for Nuage Networks. He is involved with OpenStack Neutron with a primary focus on exposing sophisticated and scalable network policy within OpenStack. As an avid Open Source proponent since the early days of Linux, Scott is delighted to combine his passions for FOSS and scalable network architecture to enhance OpenStack networking. When not in front of monitor, he is somewhere on his bicycle.)*

* **sharko cheng** *( Sharko cheng is a senior software development engineer  for China Mobile Suzhou Research Center. He is involved with OpenStack Neutron with a primary focus on exposing sophisticated and scalable network policy within OpenStack. )*

Neutron scalability test with 500+ compute nodes by China Mobile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are there any problems with large scale deployment of OpenStack neutron? With scale of 500 compute nodes deployment using OpenStack neutron in China Mobile public cloud project,  we always have doubt about the issues such as: 1. Can neutron support such large scale? 2. Will Message Queue become a bottleneck? 3. How about the concurrent performance of neutron? 4. How to configure and deploy Message Queue and Database services? 5. If a node is down, how fast the agents can be recovered? With these questions in head, we did lots of scalability tests in order to find out the answers. In this session, we will share some test methods and how to optimize the performance in China Mobile public cloud project.


* **Yi Zhao** *(Yi Zhao is a software development engineer working in neutron, open-vswitch and system applications at China Mobile. He has 2 years experiences in developing neutron and its plugins; 5 years experiences in developing open vswitch and hardware SDN switch/application. Before joining China Mobile, he worked as software developer at Centec Networks in Suzhou, China.)*

* **wu jiangtao** *(Jiangtao wu is Virtualization Network Manager of China Mobile(Suzhou) Software Technology Co.,Ltd. He has been involved with Cloud Computing, Virtualization Network, OpenStack Neutron,SDN,NFV for over four years. His work is to resolve network problems of Cloud Computing of China Mobile  With Neutron SDN and NFV. He He has been involved in the construction of China Mobile's public cloud and private cloud.)*

* **sharko cheng** *( Sharko cheng is a senior software development engineer  for China Mobile Suzhou Research Center. He is involved with OpenStack Neutron with a primary focus on exposing sophisticated and scalable network policy within OpenStack. )*

No more Network Node : "OpenSON" Fully SDN-based OpenStack Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk, we present OpenSON (Open Softwarized Networking Platform), a fully SDN-based networking solution, which implements OpenStack networking on virtual switches in compute nodes without a network node. Network functions such as DHCP, SNAT, DNAT and L3 routing are typically executed on a network node in a traditional OpenStack environment. OpenSON, however, eliminates the dependency on the network node by implementing those functions as distributed flow rules on virtual switches in the compute nodes hosting relevant virtual machines. As a result, this approach supports better L3 scalability and high availability.Moreover, the SDN-based networking approach enables to integrate the control of both overlay networks for virtual networking and underlying physical networks, which enhances the network visibility and facilitates the introduction of network applications such as network monitoring.


* **Chunglae Cho** *(Chunglae Cho received his B.S. and M.S. degrees in computer science from Pusan National University, Korea, in 1994 and 1996, respectively. He worked as a research engineer at Electronics and Telecommunications Research Institute(ETRI), Korea, between 2000 and 2005. He received his Ph.D. in computer engineering from the University of Florida in the fall of 2011. He has been working for ETRI as a principal researcher since 2011. His research interests are in resource allocation, load balancing, congestion control and optimization for communication networks, peer-to-peer networks, content distribution networks, wireless networks, software-defined networks and cloud computing.)*

* **SAEHOON KANG** *(Senior Researcher, Ph.d Electronics and Telecommunications Research InstituteProgrammable Infra Research SectionSmart Network Research Department., ETRI)*

* **YongYoon SHIN** *(YongYoon SHIN He worked as a research engineer at ETRI(https://etri.re.kr/eng/main/main.etri), KOREA, between 2010 and NOW.He has been working for ETRI as a Senior Researcher since 2011.He is member of OpenStack Community Korea and member of ONOS project.His research interests are in OpenStack, Neutron, Cloud Networking with SDN. blog: http://uni2u.tistory.comslideshare: http://www.slideshare.net/uni2u)*

Neutron at scale with ML-2
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Paypal is one of the largest OpenStack user with 1000s of physical servers with compliance requirements at Network layer for its private cloud. This presentation will give insights and challenges that we learnt during our journey in deploying and operating Neutron at Scale. 


* **Aihua Li** *(Aihua Li is currently with Paypal taking the role as the cloud networking Project Team Lead. He is overseeing the effort of adopting openstack solution to Paypal large scale deployment, extending openstack with customization requirement and automating deployment process. Prior to Payapal, Aihua has taken principal leadership positions in different companies including Huawei Technologies, Motorola Solutions, Symbol Technologies. Aihua's expertise includes wireless networking, kernel and user-space based virtual switching, service-chaining, distributed switching systems. Aihua has earned a total of nine patents in these areas. )*

* **Zhenhua Feng** *(Zhenhua is a staff software engineer with Paypals' cloud engineering team. He works on OpenStack and SDN to bring availability, scaliblility and security to one of the largest online payment systems in the world. Before that, he was with Cisco's Enterprise Networking Group building switches while drinking beer. He has significant contributions to L2/L3 multicast, Mobility for the catalyst series. Zhenhua holds a PH.D in computer engineering from Virginia Tech and a BE in information engineering from Beijing Institute of Technology.)*

networking-vpp: a simple open source networking driver for Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Vector Packet Processing (VPP) is a standalone open source user space stack designed to move packets around lightning fast. We have written a lightweight mechanism driver for Neutron to bring the advantages of VPP to OpenStack. This project complements the OPNFV FDS project with VPP and ODL/Honeycomb - networking-vpp targets simplicity, and ODL provides a fully extensible control plane for adding more complex network control.


* **Vincent JARDIN** *(Vincent Jardin is 6WIND's CTO. He is responsible to lead the architectures and developments for high performance packet processing. He co-founded the Quagga project, the open source project for routing, and remains one of its main contributors. He also helped found DPDK.org, an open source community that enables high performance network applications such as Network Functions Virtualization (NFV). Vincent has a strong knowledge on the packet processing technologies.)*

* **Ian Wells** *(An OpenStack developer and user since the Essex release, Ian works on the internals of Openstack, on applications to run on top of Openstack, and on making Openstack easy for people to use.  His current focus is in NFV, the work to use Openstack to provide virtual network functions in an OpenStack cloud for use in telco networks - a balancing act to get maximum performance from a cloud infrastructure while running mission critical network intensive workloads.)*

* **Jérôme Tollet** *(Jerome is Distinguished Engineer working in the Cisco Chief Technical and Architecture Office (CTAO) with a specific focus on Datacenter / Container Networking, Policy and Security. Jerome has extensive experience of computer systems and network architectures, and strong technical expertise gained from more than 16 years designing and implementing networking solutions. Before being at CTAO, during the last 5 years, Jerome was driving SDN & NFV initiatives for a company he founded 16 years ago, and was CTO of. He has been participating and contributing to the Open Networking Foundation (ONF), ETSI Industry Specification Group on NFV, IETF Service Function Chaining (SFC) Working Group and various open source initiatives including OpenDayLight, OpenStack and OpenVirtualSwitch. He holds several patents and obtained his Master’s degree in Computer Science from a joint degree program at Pierre and Marie Curie - Paris 6 University, and ENST Paris. Jerome is a frequent speaker at international conferences.)*

Interconnecting Neutron and network operators' BGP VPNs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The networking-bgpvpn Neutron stadium project allows to create connectivity between Neutron Ports, via their Networks and Routers, to BGP/MPLS VPNs. These VPNs are a cornerstone of telecom operators' backbones and interconnect datacenters, businesses or NFV POPs. Interconnecting them on-demand with Openstack is a critical piece of the NFV and hybrid cloud puzzles. This needs to be done in a controller-agnostic fashion to let automation and orchestration code be free of ties to a specific solution. The networking-bgpvpn project has been kickstarted in the Neutron stadium in 2015 to address this need.  


* **Thomas Morin** *(Thomas has been for a bit more than 10 years at Orange Labs, mainly involved on IP and MPLS networking for backbones and datacenters, with activities ranging from architecture/ engineering studies, to lab and software development. Thomas is also active in the IETF, where he contributes to RFCs and co-chairs BESS, the working group defining evolutions of BGP VPN specifications. He has been focusing on network virtualization for IaaS since 2012 and contributes to related opensource projects, in particular in Openstack, where he co-leads the Neutron stadium BGP VPN project (networking-bgpvpn) and in OPNFV.)*

* **Paul Carver** *(Paul Carver is a Principal Member of Technical Staff at AT&T working on Software Defined Networking and Network Function Virtualization. His background includes traditional hardware networking with a wide variety of vendors in WAN and datacenter environments as well as software development in C, Perl and Python. He is currently focused on AT&T's "Domain 2.0" initiative to virtualize large portions of the mobile/cellular and wireline data and VoIP infrastructure on top of a common OpenStack based cloud.)*

* **Tim Irnich** *(Tim holds a Diploma and PhD in Telecommunications from RWTH Aachen University, Germany. Since 2007 he works at Ericsson. After holding various positions as standardization delegate and project lead at Wireless Access Networks Research, he joined the SDN Systems and Technology team in 2014, where he is today managing the SDN Open Source & Ecosystem program, which coordinates Ericsson's SDN-related open source activities in OPNFV, OpenStack, ODL, OVS and fd.io. He is PTL of the OPNFV SDN VPN project and a contributor in OPNFV Fuel as well as OpenStack networking-bgpvpn. )*

DPDK accelerated OVS in OpenStack: How We Got Here
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Recent versions of Open vSwitch (OVS) provide an accelerated datapath based on the Data Plane Development Kit (DPDK) libraries. The acceleration that DPDK provided is vital for meeting the high performance, high determinism requirements of NFV workloads. As the most widely deployed virtual switching in OpenStack, Open vSwitch (OVS) is a key vector in the race to enable real-time applications within OpenStack. Intel has been working with its partners since 2013 to bring the benefits of OVS with DPDK to OpenStack, and this work is finally bearing fruit. In this talk, we explore the work that has been done and the work that is still ongoing to bring the benefits of OVS-DPDK to OpenStack. We detail how users can benefit from these changes, and the impact they can expect to see. Finally, we detail how users can get started exploring these changes themselves, and how they can configure these solutions to deliver the maximum possible performance for their workloads.


* **Stephen Finucane** *(I'm a software developer working in the OpenStack team in Intel Shannon. I predominantly work with Nova, though I've also been known to tinker with Neutron. I previously worked in the Open vSwitch team, also in Shannon, where I led internal testing and validation efforts.)*

* **Seán Mooney** *(Seán Mooney is a network software engineer in Intel's Network Platforms Group. He's passionate about high performance networking and open source software with a particular interest in virtual switching and orchestration technologies. His latest contribution to the OpenStack project is the ML2 Mechanism Driver for OVS+DPDK-netdev.)*

BaGPipe: BGP VPNs to implement Neutron virtual networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

BaGPipe is a proposition to implement Neutron virtual networking by leveraging the BGP VPN toolbox to distribute virtual networking states.BGP VPNs have been proven as a robust, scalable and flexible solution to create isolated virtual networks over IP/MPLS backbones, and have been extended to support various encapsulations (VXLAN, MPLS/UDP, ...), and support both IP and Ethernet virtual networks. The later becoming a mature solution for datacenter fabrics.We propose to reuse Neutron's existing framework for DB persistency and messaging, and reuse AMQP messaging to push to agent the more static configuration changes, thereby offloading the more chatty virtual network state updates from the message bus to the BGP control plane.This is an alternative way of delivering a rich feature set (e.g. BGPVPN interconnections, service-chaining), avoiding the addition of a full-blown SDN controllers and avoid the complexity of synchronising data between different persistency models.


* **Thomas Morin** *(Thomas has been for a bit more than 10 years at Orange Labs, mainly involved on IP and MPLS networking for backbones and datacenters, with activities ranging from architecture/ engineering studies, to lab and software development. Thomas is also active in the IETF, where he contributes to RFCs and co-chairs BESS, the working group defining evolutions of BGP VPN specifications. He has been focusing on network virtualization for IaaS since 2012 and contributes to related opensource projects, in particular in Openstack, where he co-leads the Neutron stadium BGP VPN project (networking-bgpvpn) and in OPNFV.)*

OSIC Enables the SDN Sale: Testing MidoNet with Neutron at Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We know that adoption of OpenStack and SDN has lagged expectations. This is in part due to the lack of SLAs and performance benchmarks demanded by large customers. Developing these benchmarks requires access to large-scale clusters - not easily available to the community or to startups.   The OpenStack Innovation Center (OSIC) solves this problem by providing OpenStack vendors with access to large datacenters to stimulate the generation of performance, scalability and reliability results necessary for SDN selling.   We present our experience testing open-source MidoNet networking virtualization with OpenStack Neutron at scale (132 servers) in the OSIC lab. We discuss: Implementation details of the physical deployment and virtual topology The rationale behind our choice of tests Benchmarks obtained Finally, we summarize the results for network performance and the strengths of MidoNet as a network virtualization solution, especially its resilience against failovers.


* **Lucas Eznarriaga** *(I'm currently working as QA Engineer at Midokura in the Software Acceptance team. Previously, I worked as a Consultant Engineer at Altran Spain and as a Research Assistant at Institute IMDEA Networks investigating in the field of wireless networks. I hold a degree in Telecommunications Engineering and an MSc in Telematics Engineering from Universidad Carlos III de Madrid. In the year of 2010, I took on an internship funded by the European Erasmus Placement Program at the Deutsche Telekom Laboratories in Berlin.)*

* **Antonio Ojea** *(Antonio Ojea is the QA team leader for Midokura. He was graduated Telecommunications Engineer by Vigo University (Spain) in 2002. He worked as a engineer specialist in networks, security and Linux systems in a Regional Telecommunications Company for more than 10 years. He participated in his spare time with several security reseach groups to fight malware and other network threats. He took advantage of the opportunity offered by Midokura to join the company in 2015 to apply his real-life, in-the-trenches bussiness experience to help to make midonet more robust, performant and scalable.)*

MidoNet Scalability Testing with Neutron in AWS to 1000 nodes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The flexibility of SDNs in contrast to traditional networks that are bounded to hardware restrictions is increasing the need to provide SDN scalability benchmarks such as the maximum number of hosts, routers, networks or virtual machines; what is the supported workload or the maximum flow setup rate. Although SDN is revolutionizing data center networks, its testing, benchmarking and monitoring at scale remains a major challenge which requires the tools capable of handling thousands of resources, such as ports or instances as well as the traffic between them. This talk presents the scalability tests done for MidoNet with OpenStack Neutron using open source tools in AWS. Using AWS and fleet spots instance we are able to launch more than 1K compute hosts for less that 100$ / hours. OpenStack Rally runs tasks for addressing scalability benchmark tests while monitoring different metrics such as virtual topology objects count with InfluxDB, Telegraf and Grafana.


* **Antonio Ojea** *(Antonio Ojea is the QA team leader for Midokura. He was graduated Telecommunications Engineer by Vigo University (Spain) in 2002. He worked as a engineer specialist in networks, security and Linux systems in a Regional Telecommunications Company for more than 10 years. He participated in his spare time with several security reseach groups to fight malware and other network threats. He took advantage of the opportunity offered by Midokura to join the company in 2015 to apply his real-life, in-the-trenches bussiness experience to help to make midonet more robust, performant and scalable.)*

* **Lucas Eznarriaga** *(I'm currently working as QA Engineer at Midokura in the Software Acceptance team. Previously, I worked as a Consultant Engineer at Altran Spain and as a Research Assistant at Institute IMDEA Networks investigating in the field of wireless networks. I hold a degree in Telecommunications Engineering and an MSc in Telematics Engineering from Universidad Carlos III de Madrid. In the year of 2010, I took on an internship funded by the European Erasmus Placement Program at the Deutsche Telekom Laboratories in Berlin.)*

Octavia Load Balancer as the last line of your cloud application defense
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk is about turning on HTTPs handling in Octavia, the Open-Stack Load-Balancing as a Service. Octavia's Load-Balancer nodes can terminate the HTTPs connections at the Load-Balancer tier. It can improve your service performance by off-loading the TLS work from your back-end servers. It is required if you want to apply Octavia's L7 Load-balancing rules while using HTTPs. Cool!, so WHAT ARE THE ISSUES? (Q1) How much load is cause by TLS stuff? Answer: It depends.... but it may be significant (Q2) Can the Load-Balancer handle it? Answer: Usually not! -- you need ACTIVE-ACTIVE (Q3) Is it secure? Answer: Yes, but read the fine print... Follow-up questions: With Active-Active turned on several Load-Balancer nodes can handle the TLS load, but there is a new piece to the puzzle -- the Distributor. (Q4) Can the Distributor handle the load? Answer: Yes! (Q5) Is the Distributor secure? Answer: Yes, but read the fine print...


* **Dean Lorenz** *(Dr. Dean H. Lorenz is Research Scientist at IBM Research HaifaLab, a technical leader at the Cloud Networking group of the Cloud Platforms department. Dr. Lorenz received his B.Sc. in Computer Engineering (Summa Cum Laude) and Ph.D. in Electrical Engineering, both from the Technion – Israel Institute of Technology. He has more than 15 years of experience in research, hands-on development, and innovation in Networking, Virtualization, Storage, and Mobile Technologies. Dr. Lorenz has held technical positions at leading companies in these industries, including IBM Research, Akamai, Adobe Omniture, and Qualcomm. He has re-joined IBM Research in 2014, and is currently researching Cloud technologies, with focus on Cloud networking, elasticity, and operation efficiency.)*

* **Banashankar  Kalebelagund** *(...)*

Network Dataplane Acceleration Techniques
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Increasing load on the network often comes at a high cost: having kernel process a lot of packets in a unit of time leads to significant increase in CPU utilization and performance degradation. Using  overlay networks (eg. VxLAN) where encapsulation/decapsulation takes place makes the situation even worse.   Modern hardware allows to take some load from CPU and distribute part of the network processing to the NIC. There are also software techniques that can be used in conjunction with hardware ones to improve throughput greatly.   In this talk we will demonstrate the effect various acceleration techniques  have on performance. We examine differences in throughput as well as the effect on CPU utilization when these techniques are used. In particular, we will touch the following technology areas: Usage of hardware offloads SR-IOV acceleration techniques Software-based acceleration with DPDK


* **Elena Ezhova** *(Elena has been working on OpenStack since Grizzly release and has contributed to such projects as Neutron and its advanced services, especially Octavia, LBaaS, as well as VPNaaS, Oslo, Tempest and Keystone. She was responsible for graduating the oslo.service library and currently is a member of its core team.)*

* **Sergey Matov** *(In Mirantis Sergey has been working on several Networking projects, such as Vyatta vRouter. Authored several features to vRouter, Sergey moved to OpenStack department. He took part in adapting NVF technologies for Mirantis OpenStack 9.0.)*

* **Dmitry Klenov** *(Dmitry has been involved into Mirantis services activities since OpenStack Folsom release adapting OpenStack technologies for customer needs. In Mitaka release Dmitry was driving the productization of NFV technologies for Mirantis OpenStack 9.0.)*

Reshaping Network Services for the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the increase in number and scale of cloud deployments, more and more users find that existing network solutions fall short of meeting their demands.  This is true in many aspects: usability, customizability, application-orientation, and more.In this session we will cover aspects of software defined cloud networking that enable a new architecture for virtual network functions, which is suitable for the needs of large enterprise and telecom. We will focus on concrete implementations using the OpenStack Dragonflow project:* Service Chaining and Dynamic Topology Service Injection* Network Function as a Service (like Lambda functions)* Deployment Framework for VNFs* SDN-based design for VNFs with examples:- DHCP- Metadata service- IGMP


* **Omer Anson** *(Omer is currently a software developer for Huawei, and a core contributor for Dragonflow in OpenStack. He has 9 years of professional programming experience, with over 5 years expertise in Linux systems and networking. Omer has a B.Sc in physics, and is working towards his M.Sc. in Computer Science.)*

Next Generation Virtual Switch Technologies
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the increasing prevalence of cloud computing, there are proliferated east-west traffic in clouds, and also many emerging demands for virtualizing network I/O intensive workload, e.g. telco and big data. All those put huge amount of challenges on existing virtual switches. In this presentation, we want to have a deep dive technical discussion with OpenStack community on technologies which can significantly boost virtual vswitch performance and efficiency, on techniques for implementing a rich feature set to satisfy both public and private cloud use cases, and also easy of integration with Neutron/OVN.


* **Jun Xiao** *(Jun Xiao is the founder & CTO of CloudNetEngine which is focused on  innovating next generation "engine" for cloud virtual networking. He has 15+ years experience in IT/Telco industries within companies: VMware, Huawei, Lucent and Sun Microsystem etc, and he has very solid system design experience ranging from low level device drivers, network stacks, to middleware software and distributed systems. Jun Xiao holds 10+ US/China issued/pending patents and is one of key inventor of VXLAN.)*

Enabling AWS/Azure's VPN and DirectConnect/ExpressRoute in OpenStack - The missing pieces
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Connecting openStack with your VPC in AWS or Microsoft Azure seems to become a common use case and a basic requirement. Other cloud platforms make it easy to do this end-to-end setup by just entering basic information and doing the setup themselves. What would it take for OpenStack to do that? Should OpenStack be doing more to help manage those integration points? Or maybe this should live in higher layers that abstract the cloud API and let one provision cloud resources in a platform-agnostic way using other tools. This talk will show Neutron’s BGP, VPNaaS and L2GW APIs can be used to automate private cloud connections in Hybrid clouds. We will then propose next steps to make these setups truly self-service and hassle-free.


* **Ryu Ishimoto** *(Ryu Ishimoto is the technical lead of Midokura Japan, currently leading the effort to integrate MidoNet and OpenStack Neutron.  He is also responsible for designing and implementing the MidoNet API as well as some parts of the MidoNet cluster and agent.  He is a Neutron contributor.   Prior to joining Midokura, he spent 10 years as a developer for various technologies including data mining, ad server, financial systems, and e-commerce applications.  In 2004, he received a Master's Degree in Computer Science from UCLA.)*

* **Alon Harel** *(Before Midokura, I have hold architecture positions at Marvell Semiconductors and Mellanox Technologies dealing with Ethernet switching, cloud virtualization and SDN technologies. I have spent the first half of my career as a software engineer and a software team leader developping software for embedded systems in the communication industry.)*

From Neutron to Neutron: SDN-driven backbone traffic engineering
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Several models for providing end-to-end traffic engineering between data-centers in carrier backbone networks through the interworking of Data-center(DC) and WAN SDN Controller will be presented. The model will enable seamless end-to-end service and traffic engineering from host to host and/or ToR to ToR across large National Service Provider backbones. A number of use-cases including the dynamic provisioning of virtual resources in Data Center as well as logical resources in transport network will be covered.  Options such as DC SDN Controller to WAN SDN Controller coupling with abstract Interface definition or extension of an unified control plane which spans the Datacenter and Backbone Networks will be discussed along with advantages and disadvantages of the options. The direct sharing of information, via standardized information models, between SDN Controllers will result in improvements in efficiency, flexibility and improved elasticity of resources for modern Carrier Networks.  


* **Yuriy Babenko** *(Yuriy works as a network architect for Deutsche Telekom focusing on data center design, networking and automation. )*

* **Colby Barth** *(Colby Barth is a Distinguished Engineer at Juniper Networks)*

Advanced Topics in OpenStack Networking: OpenFlow, OVS and Dragonflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack networking is in a constant state of change, innovation and improvement.  We see a proliferation of vendor implementations, each trying to solve performance, scale and features in a differentiating way.In this talk, we want to explore some advanced networking topics involving OVS and the OpenFlow protocol.  We will demonstrate some of the ideas using the OpenStack Dragonflow implementation, which utilizes OVS and OpenFlow:* Distributed Security Functions (Port Security, SG, FWaaS, VPNaaS, packet inspection)* Making the OpenFlow pipeline flexible* QoS* Applicative packet generation* Local controller reliability* HA* Load Balancing* NAT with Learning


* **Omer Anson** *(Omer is currently a software developer for Huawei, and a core contributor for Dragonflow in OpenStack. He has 9 years of professional programming experience, with over 5 years expertise in Linux systems and networking. Omer has a B.Sc in physics, and is working towards his M.Sc. in Computer Science.)*

Networking approaches in a container world
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Networking has always been a complicated and delicate topic. It is even more complicated in the world of containers, where huge numbers of containers are continuously created and respawned across entire data centers. There are several container networking choices available, each one with a different implementation and its own peculiarities. The different approaches taken by the different vendors to solve the container networking question can make it daunting to picking the right one for your environment. This talk reviews how the major Linux Container networking solutions work: their implementation details, their strengths and weaknesses, and how they influence the deployment of distributed applications in both container only environments and mixed VM - Container environments.


* **Antoni Segura Puimedon** *(Antoni serves as a core member of Openstack Kuryr and as the Container Team lead at Midokura and works on integrating MidoNet with VM and Container platforms. He has contibuted in the past to the networking stack of oVirt, Libvirt nova-docker and MidoNet. His recent focus has been on Container Software Defined Networking and Container projects like OpenStack Magnum and Mesosphere.)*

* **Flavio Castelli** *(Flavio Castelli is the engineering manager for the Containers team at SUSE. Flavio has been following Docker since its early days and focused on its integration within the openSUSE and SUSE ecosystems.Flavio developed experience in creating and managing systems while working on products such as SUSE Studio and SUSE Manager. Flavio is also a contributor to various open source projects.)*

* **Neil Jerram** *(Neil has been hacking on free software since the early 1990s, with contributions including to Emacs, Guile, Lilypond, QtMoko, the GTA04 phone project, oFono, FSO, OpenStack, Dnsmasq, Linux and Dasher. He's also worked for 20 years for Metaswitch (previously Data Connection) in the world of networking protocols, and happily those two strands of experience are now converged in Project Calico, an open source implementation of simple and massively scalable data center networking.)*

Network Trunking in OpenStack Neutron: Architecture and Design Challenges
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Typically a Neutron port maps to a virtual interface as presented by hypervisors to a virtual instance, or bare metal instance in physical infrastructures. This clearly limits the amount of Neutron networks that an instance can access at any given time. The Neutron trunk feature overcomes this limitation by allowing OpenStack instances to access hundreds or thousands of Neutron networks from a single Neutron port. In this session you will learn about the proposed API, the architecture and challenges faced during the development of this feature in relation to the Open vSwitch and the Linux Bridge implementations available in Neutron.


* **Rawlin Peters** *(Rawlin started as a software engineering intern on the (formerly known as) HP Cloud Neutron team during his junior year at Colorado State University - go Rams! Since graduating with his B.S. in Computer Science, he's been working as a full-time Openstack Neutron Engineer on the (now) HPE Cloud Neutron team for the Helion OpenStack (HOS) product. Most of his time on the Neutron team thus far has been spent downstream on Helion OpenStack, but he's recently been given the opportunity during the Newton cycle to work upstream on the new Trunk Port (vlan-aware VMs) feature. This has helped him learn a lot more about Neutron and allowed him to dive deeper into upstream. He hopes to continue this trend in the future. Outside of working on Neutron and HOS, Rawlin enjoys snowboarding, driving through the mountains, and riding motorcycles.)*

* **Ryan Tidwell** *(Ryan Tidwell is a contributor to the OpenStack Neutron project and has been deploying and tinkering with OpenStack in various roles since the Diablo release of OpenStack.  Ryan has been working at HP (now Hewlett packard Enterprise) since 2008.  He is well-versed in developing manageability tools for systems administrators and OpenStack operators, building SDN controllers and applications, and currently contributes to OpenStack's Neutron project.  Raised in Northern Colorado, Ryan has a B.S. and M.S. in computer science from Colorado State University and the University of Colorado respectively.  He currently resides with his family in Roseville, CA.)*

* **Bence Romsics** *(Bence Romsics has spent the last decade in the technology industry, first operating then engineering and developing software. He has a keen interest in distributed systems, software architecture and scaling. He has worked two years on tooling for a large-scale virtualization platform, another three working with OpenStack networking. Today he is working on finding ways to match the needs of the telecommunications sector with the ever developing offerings of cloud systems.)*

OpenStack Networking Adopted and Extended to support the Next Generation Optical DCN Research
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk shows how OpenStack extensibility helps advancing DCN research. EU project COSIGN introduces Optical Circuit Switching to the data plane and a dual pair of SDN controllers to the control plane. We describe how we support both the optical data plane devices and the control plane duality by extending OpenStack Networking. For the virtual layer, we adopt Neutron API with a customized OVN plugin. For the physical layer, we extend Neutron and employ OpenDaylight to command both the Electrical Packet Switches and the Optical Circuit Switches through extended OF. We give implementation details and show a demo of the working adaptable OpenStack Networking integrated with the rest of services – Nova, Heat, and Horizon. Additionally, we give a brief overview of the COSIGN Data Plane and present the SW architecture whereby the dual-controller dynamic feedback loop allows implementing advanced circuit scheduling and traffic steering to support diverse and unpredictable traffic matrices.


* **Yaniv Ben-Itzhak** *(Yaniv Ben-Itzhak is a research staff member in Haifa IBM Research Lab. His research interests include Data-Center networks, Software Defined Networks (SDN), optical networks, network virtualization, and Network Function Virtualization (NFV). Dr. Yaniv Ben-Itzhak received his B.Sc (magna cum laude), M.Sc., and Ph.D. degrees in Electrical Engineering from the Technion – Israel Institute of Technology.)*

* **Katherine Barabash** *(Kathy is a manager and a technical leader of the Cloud Networking Group in IBM Haifa Research Lab and one of the inventors of the IBM's overlay network virtualization solution. Kathy is with IBM Research since 1997, contributing to different system research areas. Since 2007, Kathy is actively involved in cloud and data centre network virtualization research, basing on OpenStack Neutron since about 2011.)*

* **Jose Aznar** *(TBD)*

Extending OVS on Hyper-V with your own neutron plugin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Discover in this session how OpenvSwitch on Hyper-V can be extended with the Neutron plugin from Nuage Networks.  We will review how the Hyper-V OVS drivers are implemented, what progress has been made during the Newton release cycle, and what performance you can expect. Neutron's default networking implementation can be extended with other plugins, and so we will also discuss how Nuage Networks has taken up this challenge. The session will conclude with a demonstration of what such integration looks like and how distributed routing is done across Hyper-V, KVM and Bare Metals.    


* **Jonas Vermeulen** *(Jonas Vermeulen is Product Manager of Nuage Networks for the EMEA Region. In this position, he works with cloud service providers and large enterprises discussing network virtualization and overlay technologies for their datacenters. He covers the topic at various levels, ranging from business propositions to deep technical solution specifics, and enables a healthy feedback loop between customers and engineering.Prior to joining Nuage Networks, Jonas Vermeulen was an IPTV Senior Network Architect in Singapore and Technical Project Manager in New Zealand. In his free time he enjoys cycling, running, hiking and all kinds of other outdoor sports.    )*

* **Octavian Ciuhandu** *(Octavian Ciuhandu is the COO of Cloudbase Solutions, a company focused on cloud computing interoperability, based in Timisoara, Romania.Octavian is a young entrepreneur that started his own business in 2004, right after graduating a research M.Sc. in DCU, Dublin, Ireland. He has over 20 years of experience with Microsoft and Linux platforms, network management and security. Proficiency in designing applications for scalability and availability is ensured following his research masters area of expertise. Since 2012, focusing on Openstack, integrating Openstack and Windows, and especially on deploying and running Openstack CIs for Microsoft Windows. In his free time, Octavian enjoys off-road driving and skiing. Cloudbase Solutions provides integration between OpenStack and Windows, including the Hyper-V Nova Compute driver and Cloudbase-Init (Cloud-Init for Windows).)*

* **Arnaud Lheureux** *(Arnaud Lheureux is a regional Architect for Cloud Networking at Nuage Networks. After 10 years at Microsoft as datacenter architect and evangelist supporting Microsoft top account in EMEA, Arnaud joined Nuage Networks to help big organization as they adopt SDN in their infrastructure. Regular speaker and trainer at Microsoft and other industry events, Arnaud has been speaking about OpenStack and evangelizing interoperability of datacenter solutions for years.)*

Open vSwitch versus Linux bonding - the battle ends here
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many ways to configure OpenStack networking. With the mix of underlying hardware infrastructure, it is hard to determine and tune-up to achieve the best performance. The right networking configuration can provide a significant performance boost in many aspects of the infrastructure. It’s not just connectivity between two virtual machines, but speed of your software defined storage, access to upstream content, and management of the infrastructure.This session describes how to benchmark and tune-up many aspects of networking, including link aggregation, bridging, selection of hardware, and its accelerations. The use cases are host-to-host, software defined storage, infrastructure, and OpenStack.


* **Krzysztof Janiszewski** *((Chris) Krzysztof Janiszewski is a memeber OpenStack Solution Architects Team at Red Hat. His main background is in designing, developing, and administering multiplatform, clustered, software-defined, and cloud environments. Chris previously worked as an OpenStack and HPC Architect for Lenovo Professional Services and also led System Test efforts for the IBM OpenStack cloud-based solution for x86, IBM System z, and IBM Power platforms.)*

* **Ken Holden** *(Ken Holden is a Senior OpenStack Solution Architect on Red Hat's OpenStack Tiger team. Prior to joining Red Hat in 2014, Ken worked as a System Engineer with World Wide Technology focusing on OpenStack design, Ceph storage, and Hadoop clusters.  He also spent 4 years at Apple as a principle consulting engineer specializing in large scale production deployments of software defined storage clusters using Apple Xsan and ADIC StorNext.  Over his 19 year career in IT, Ken has achieved certifications in Red Hat, MapR, CheckPoint, Cisco, and Microsoft.)*

The IoT Wave is coming, Can your network handle it?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Presenters: David Levin, Midokura and Devdatta Kulkarni, PTL Solum, Rackspace Abstract:Industrial organizations facing fierce global competition are turning to cloud-based custom app development for their digital transformation. The technology enabler for the increasingly connected world is the network and custom software. Everything has to be built from the ground up in IOT because in the bleeding edge, there’s no commercial off the shelf solution. While Platform-as-Service helps abstract away much of the infrastructure, Devs still have to deal with network connectivity, in particular connecting VPCs between clouds, load balancing their applications and security policies.  


* **David Levin** *(Enterprise Sales & Business Development Executive who generates new customers and multi-million dollar engagements for leading edge technical solutions organizations.  Experienced consultative sales executive who maximizes opportunities involving new technology, new markets, and new operations in start up to large, global organizations.  Recognized by accounts and prospects as a strategic partner who creates solutions for Cloud technologies (PaaS, IaaS, SaaS), IoT, Commerical & Residential Automation,  business intelligence, web technologies, mobile strategy, , convergence and security.  Open Source Evangelist and Co-Host of Tech React Radio Show & Home Automation Podcasts. Currently employed by Midokura running sales for America, East focused on promoting Openstack and MidoNet, MEM SDN adoption in the enterprise. ti)*

In-kernel Analytics and Tracing with eBPF for OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the movement of applications from bare metal to the cloud continues, considerations around analytics and tracing are becoming more prevalent for security, monitoring, and accounting. As an open source project under the Linux Foundation, the IO Visor Project is working with the kernel community on extending BPF (eBPF) and is being used by many companies for security, tracing, and analytics. This talk will describe how an OpenStack micro-segmentation framework using eBPF can be utilized for analytics and tracing to secure application workloads. Use cases around application security, intrusion detection using service insertion, identity will be described. While networking is one piece of the solution, sandboxing applications to avoid attacks is also important. We will also touch upon how eBPF technology and a unified policy framework can secure application workloads in areas beyond networking.


* **Brenden Blanco** *(Brenden is part of PLUMgrid's tecnical team. He is involved in several open source products including IO Visor, he works on various areas of cloud networking assocaited with security, multi-tenancy and high avalability.)*

Next generation security and service chaining with NSX and Fortinet
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network and security architects are looking to operationalize OpenStack Neutron with more advanced service integration and manageability options. In general, service chaining has remained a challenge in Neutron, making it harder for security architects to deliver rich and secure topologies in an OpenStack-based private cloud. In this session we will discuss the integration options developed by VMware OpenStack Engineering in order to deliver next generation security and protection using the NSX platform and Fortinet’s FortiGate-VMX solution.


* **Marcos Hernandez** *(Marcos Hernandez is a Staff Systems Engineer in the Network and Security Business Unit (NSBU). He is responsible for supporting large Global Enterprise accounts and providing technical guidance around VMware's suite of networking products, including NSX. Marcos has a background in datacenter networking design and expert knowledge in routing and switching technologies. Marcos holds CCIE certification #8283, VCIX and a Masters Degree in Telecommunications from Universidad Politécnica de Madrid.)*

* **Elie Bitton** *(Fortinet)*

Monitoring Network Underlays with BroadView Instrumentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

BroadView is an open source software suite that enables advanced analytics in next-generation networks. Troubleshooting network problems and ensuring application SLAs are very complex tasks. In cloud networks, overlay technologies reduce visibility into packet flows, thereby making it even more difficult to analyze issues and ensure SLAs. OpenStack projects such as Ceilometer and Monasca provide monitoring-as-a-service to deliver usage metrics from applications and tenant networks; however, underlay monitoring is not supported. Ensuring application SLAs requires overlay mapping to the underlay, and optimal performance of underlay infrastructure is essential. BroadView-based solutions enable programmable access to underlay monitoring, facilitating applications to gather advanced analytics in a highly scalable manner. This session explains how BroadView with Monasca provides network administrators a single pane of glass to monitor all aspects of the network.


* **Syd Logan** *(Syd is the technical project leader for BroadView integration with OpenStack at Broadcom.  Syd has been a software engineer for over 30 years. Prior to Broadcom, Syd has held technical and management positions at a wide variety of companies, including VMware, Netscape Communications, and America Online. He is the author of 3 books, "Developing Imaging Applications with XIELIb" (Prentice Hall), "GTK+ Programming in C" (Prentice Hall), and "Cross-platform Development in C++" (Addison-Wesley) Syd volunteers his time as a Django/Python and Android developer and serves as a member of the board of directors for Thousand Smiles Foundation, a San Diego charity that provides maxillofacial surgery and dental care to children in Ensenada, Mexico.  )*

* **Roland Hochmuth** *(Roland Hochmuth is a software architect, developer and evangelist at Hewlett Packard Enterprise and the Project Technical Lead (PTL) for the open-source OpenStack Monitoring-as-a-Service Monasca project. His current focus is on architecture, development and helping to lead the team that develops a highly performant, scalable and reliable turn-key monitoring and logging solution that leverages the industries newest trends and innovations around near real-time stream processing systems, analytics and big data, such as Apache Kafka, Apache Storm, Apache Spark, HPE Vertica and others. Prior to working on Monasca, he was an architect, developer and tech lead on the metrics processing pipeline for HP's Public Cloud. From roughly 2009-2012, he was an architect and tech lead on WebOS on the PC. From 2002-2009 he was a founder, architect, developer and tech lead on the highly successful remote desktop visualization product Remote Graphics Software (RGS), which served as the foundation for launching two products within HP, HP Workstation Blades and HP Halo Videoconferencing. In the early 2000's he worked on HP's e-utilica solution, which was a predecessor for cloud computing. From 1990-2000, he worked on 3-D graphics geometry processing, rasterization, and NURBS surface tessellation algorithms. Roland has experience in a number of software disciplines and domains ranging from 3-D computer graphics, remote desktop visualization, cloud computing and monitoring. He has a history of innovation and leading successful products and teams. He has around sixty to seventy patents and patent applications and frequently presents at conferences. In his free time he studies statistics and Deep Learning.)*

Scale-out virtual machine bandwidth using Neutron DVR and OSPF deployed using Docker containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Current neutron DVR implementation depends on L2 connected public networks which will cause scalability and performance issues when you want to support multiple racks. In this talk, we will dive into a L3 based DVR implementation. We will see how using pure L3 DVR implementation helps achieve higher scalability and programmability Neutron DVR. By using this scale-out L3 implementation, bandwidth is now on the order of the number of hypervisor nodes and only bound by the limitations of the physical network itself.


* **Hao Chen** *(Hao Chen, a Senior Software Engineer at EMC, currently works on VxRack Neutrino project. The project is a turnkey cloud-native IaaS solution based on OpenStack and Docker. Hao started his career in Cloudscaling as a developer for Open Cloud System, an OpenStack based cloud solution. During his stay in EMC, he focused on distributed system design and networking optimization. In particular, he implemented the L3 DVR solution and the glance scaleio backend solution for neutrino. Hao has deep knowledge in various OpenStack projects such as Keystone, Glance, Nova, Neutron, Ceilometer and Heat.)*

OpenStack Neutron: Deep dive into practical cloud networking with BigSwitch BCF and OpenVswitch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The talk takes a deep dive into two SDN solutions for OpenStack: BigSwitch BCF P+V Edition and native Neutron with DVR. For each of the solutions, it uncovers the internals of the implementation of the virtualized networking. It explains in great detail the flow of packets between virtual instance and between virtual instances and devices on external provider networks. It demonstrates practical approaches and methodology for tracing flows in virtualized networks. Even though the examples are based on Native Neutron and BigSwitch BCF P+V, the approaches are applicable to any other SDN solitions. Understanding the ins outs of the implementation of virtualized networks is the only way to effectively analyze, evaluate and troubleshoot SDN solutions. This presentation has been given multiple times to internal teams within in my organization and has often been refered to as an "eye openner".


* **Dimitar Ivanov** *(You can find my “formal” professional bio further down but for most of you, this probably is all you really want to know: What’s been keeping me busy for the last two years is automation for infrastructure provisioning, OpenStack, architecting, designing and deploying clouds, NFV, SDN. I’m a unix/linux guy, always been, always will be! These days I happen to run yum/dnf more often than apt-get but both are cool. My love for C is forever but I managed to find place in my heart for Python and Perl. Awk and bash are cool too. My idols are Ken Thompson, Dennis Ritchie and Brian Kernighan – on their shoulders we all stand today! Thank you! Loving OpenStack, after all it is for the stack what linux is for the server. My favorite OpenStack project is Neutron. I like systems that scale, anticipate failures and self-heal. I love the West Coast! And this is the official part… Dimitar Ivanov is an IT professional with over twenty five years of experience in the architecture, design and, implementation of large scale, complex, mission critical datacenter  infrastructure environments in a variety of senior technical and leadership roles.  Dimitar started his professional career as a systems programmer at the Institute for Microprocessor Technologies in Sofia, Bulgaria where for three years he designed and developed control systems for industrial automation.  During the mid and late 1990s he worked for some of the leading systems integrators in Bulgaria as well as leading government and commercial organizations with focus on systems and networking administration and integration.  In 1998, Dimitar moved to Vancouver, Canada and for the next seven years took multiple senior technical roles and leadership roles at the head office of leading electronics retailer Best Buy Canada. He was responsible for the architecture, design, deployment and operations of large scale, nationwide compute and networking infrastructure supporting Best Buy Canada’s “bricks and mortar” as well as on-line retail operations. His responsibilities also included the technology support for the core business systems for finance, human resources and retail.  In 2005, Dimitar joined TELUS, a leading telecommunication provider in Canada and for the last ten years has been in variety of leadership roles in IT Operations, Infrastructure Design and Integration and most recently, Cloud Infrastructure and Architecture, part of the CTO organization.  Dimitar and his team are responsible for the architecture of the compute and storage infrastructure for BSS and OSS applications and services nationwide. His team is also responsible for setting up technology standards and new technology introduction.  For the last two years, his main focus areas have been automated provisioning, Network Function Virtualization (NFV), SDN and OpenStack based cloud services. Currently he and his team are developing the architecture of highly resilient, flexible, scalable and elastic multi-tenant private cloud. Dimitar lives in Port Coquitlam, BC with his wife and son, his eldest daughter lives in Mountain View, CA.)*

Practical Neutron: A Hands-On Lab
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this lab, participants will use the Neutron APIs to create a secure, production-quality network stack, and then automate the entire process with Heat.  They will learn of common issues and error, what they mean, and how to resolve them.  By the end of this lab, participants will be able to: Leverage the Neutron APIs to instantiate routers and networks Associate VMs with the appropriate networks Secure VMs using security groups Verify proper routing and security Use Heat to automate the provisioning of an entire stack including networks, routers, security groups, and VM instantiation. Resolve common issues and errors.


* **Jonathan Kelly** *(Jonathan's first exposure to OpenStack was as an attendee at the Bexar summit.  He was one of the initial engineers on Rackspace's Openstack Private Cloud team, and has been working on OpenStack in one capacity or another since then.  He has experience within the OpenStack private cloud space as a System Engineer, Systems Architect, Product Manager, and most recently as a Solutions Architect.  He currently works for the MetaCloud organization within Cisco.)*

* **Chris Riviere** *(Chris Riviere is a Cloud Solutions Architect on the Cisco Metapod team. He joined Cisco via its acquisition of Piston Cloud Computing. Previous to Piston, Chris had Professional Services and Sales Engineering roles at OPNET Technologies (acquired by Riverbed). There he was passionate about application and network performance helping customers around the world optimize the reliability and performance of their mission critical applications. He enjoys traveling, hiking, biking, and scuba diving.)*

* **Vallard Benincosa** *(Vallard: blogs at http://benincosa.com tweets at http://twitter.com/vallard, codes at http://github.com/vallard lives in Portland, OR. works as an engineer at Cisco with what used to be called Metacloud. street skates and drop in on half pipes whenever he can find them.   Was a core developer of IBM's xCAT project for managing large HPC clusters takes long walks on the beach enjoys watching gladiators wrestle Some older articles he wrote in 2008 are still in style, though hard to find: https://web.archive.org/web/20081209062905/http://www.ibm.com/developerworks/linux/library/l-11sysadtips/index.html?ca=dgr-lnxw07LazyLinux11 https://web.archive.org/web/20130913131309/http://www.ibm.com/developerworks/linux/library/l-10sysadtips/  )*

Building an efficient fast path for DVR routed networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In its current state DVR provides an efficient, distributed data path when used in conjunction with floating IP's. To enable that same fast path when directly routing tenant networks, we need to build on features such as address scopes, subnet service types, and BGP dynamic routing. In this session we will discuss how these features combined with DVR work together to enable a more complete distributed routing solution for both IPv4 and IPv6 traffic.


* **Ryan Tidwell** *(Ryan Tidwell is a contributor to the OpenStack Neutron project and has been deploying and tinkering with OpenStack in various roles since the Diablo release of OpenStack.  Ryan has been working at HP (now Hewlett packard Enterprise) since 2008.  He is well-versed in developing manageability tools for systems administrators and OpenStack operators, building SDN controllers and applications, and currently contributes to OpenStack's Neutron project.  Raised in Northern Colorado, Ryan has a B.S. and M.S. in computer science from Colorado State University and the University of Colorado respectively.  He currently resides with his family in Roseville, CA.)*

* **Swaminathan Vasudevan** *(Swaminathan Vasudevan is a Systems Software Engineer at Hewlett Packard Enterprise where he currently works on Cloud Networking Division in OpenStack Neutron. He is an active technical Contributor of OpenStack since 2013 and have contributed code to VPNaaS and Distributed Virtual Router in Neutron. Swaminathan Vasudevan has been developing code for more than 18+ years with expertise in linux, virtualization, networking, mobility, security and convergence.)*

OpenStack in production:  the challenge of SDN and lifecycle management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running a production OpenStack cloud starts with a successful deployment, but the real challenges begin after you go live.  Integrating third party SDN solutions and software into an OpenStack cloud adds another layer of complexity to the environment.  One of the most vexing issues is ensuring that configurations are maintained across upgrades and updates of individual components.  Lifecycle management is a key requirement for a robust OpenStack deployment, enabling an operator to customize and maintain highly tailored environments.  During this session we will go through a few real-life examples of the approach we’ve taken with some of our most complex SDN use cases, including lessons learned and best practices.


* **David Hawley** *(Dave is a product manager for HPE Helion OpenStack, responsible for supporting the development and delivery of Neutron and SDN-based cloud networking solutions for customers.  Dave has more than 20 years of experience in networking as both hardware design manager and PLM.  Prior to joining HP, he helped create the Ethernet switching portfolios at Juniper Networks and Extreme Networks.  Dave holds dual master's degrees in business from UC Berkeley and Columbia, and a bachelor's degree in EECS from Caltech.  He loves the expertise, energy, commitment of the OpenStack community, and is happy to contribute to its success.)*

* **Fabrizio Fresco** *(Freezer core Architect, a seasoned Systems / Software Engineer with an extensive background on Information Security, Infrastructure Automation and development in many different environmnets/languages.)*

Integration between openstack SFC and ODL SFC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The presentation shows how to integrate between Openstack SFC and ODL SFC. Openstack SFC is neutron port based SFC. ODL SFC is based on IETF and support NSH based SFC. ODL SFC YANG model can be augmented to support neurton port based SFC. Openstack SFC can be southbound of ODL SFC by RESTful API. In this presentation, augumented SFC YANG model for neutron port is elaborated. Inegration between ODL SFC southbound and Openstack SFC by RESTful API is also covered.


* **Ruijing Guo** *(Ruijing has 15 years of develop experience in network, storage and big data. Currently, he is actively developing ODL SFC and fuel@opnfv.)*

IPv6 is Easy
~~~~~~~~~~~~

**Abstract:**

Despite enjoying its 20th birthday in January, many engineers still find themselves intimidated by the apparent complexity of IPv6. Those that have tried often grew equally frustrated with vendor support leaving many deployments and business cases out in the cold. The good news is that light glimmers in the distance with worldwide user access to IPv6 climbing through 10% earlier this year. Services are attainable, applications (might) work and real users are connected. For the newly exposed, we will first cover the basics of IPv6, it's history, comparison to IPv4 and how it works. Those that are already familiar will enjoy a review of the changes made over the last decade. Does an RFC really require an entire /48 for each user and just how do you configure a DNS resolver anyway? Finally we will review the state of IPv6 support in major OpenStack components, what is coming in the future and ensure you are left with renewed energy to tackle your own IPv6 deployments with enthusiasm.


* **Trent Lloyd** *(Trent Lloyd has enjoyed educating audiences about IPv6 since 2003 when he naively predicted 2010 as a "more likely" target for IPv4 deprecation. An OpenStack Support Engineer at Canonical, he has over 10 years Linux systems administration & networking experience supporting enterprise customers including roles at MySQL, Sun Microsystems, Oracle.  With a special interest in all kinds of networking, he is also upstream author of the Avahi Multicast DNS Service Discovery stack.)*

Is the classic infrastructure policy approach future-ready for networking?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The classic approach to infrastructure policy is imperative associating a specific feature to a HW/SW component. This talk deabtes the viability of the classic approach and describes a declarative, capability-driven approach independent of a specific HW/SW component. The implementation of this approach is in progress in the OpenStack Nova scheduler [1]. The key benefits of this novel approach to the Nova administrator are simplified Nova Flavor policies and a future-proof path to managing a multi-vendor heterogeneous infrastructure [2] while preserving backward compatibility to the current imperative approach. Use cases discussed for this novel approach involve networking features like mirroring, overlays, service chaining etc. which are available through vSwitch, NIC or ToR. Ref: [1] “Capability Standardization,” https://review.openstack.org/#/c/341341/  [2] “IETF Infrastrcuture Policy,” https://datatracker.ietf.org/doc/draft-irtf-nfvrg-policy-based-resource-management/


* **Ramki Krishnan** *(Ramki has over 20 years of proven industry experience in the areas of Networking, High Performance Switching and System Management. He has over 10 years of experience in Standards Development and Leadership, Research Leadership and Managerial role. He has previous startup experience.  He combines deep technology understanding with strategic thinking to bring customer-winning products and solutions to reality with a direct impact on revenue generation. His expertise includes a wide range of technologies and market trends, including: Networking Protocols (BGP etc.), SDN, NFV, SDS, SDI, Cloud, Security, Open source (OpenStack, OpenDaylight, OSM, and OPNFV etc.), Intel Processors, Servers, Storage, Agile and DevOps, REST, YAML, IPMI, Redfish etc. He is a recognized innovator with 19 US patents and 8 IEEE conference papers including a best paper award. He is a thought leadership speaker in key conferences such as ONS, OpenStack, OpenDaylight, NFV World Congress etc. He is a leader and active participant in several research and standards organizations such as IRTF, IETF and ETSI NFV etc. )*

* **Joseph Gasparakis** *(Joseph is a software architect working for Intel. He was born in Athens, Greece but he left in 1996 and lived for many years in United Kingdom where he studied and worked in the telecoms and enterprise industry. In 2008 he got hired by Intel, his current employer where he focused on packet processing performance with multicore systems and other software optimizations including VXLAN offloads in the Linux kernel for network interfaces. In 2011 he moved to Portland, Oregon and focused on Software Defined Networking (SDN) and Network Functions Virtualization (NFV). He played a key role in shaping Intel's Open Networking Platform and he also got involved in OPNFV, both of which are Reference Architectures that integrate open source components including OpenStack. Joseph has a strong interest on data plane performance and how orchestration is affecting it. He is married with two kids, Nicolas and Kallie, who happily take most of his time when he is not working on networking optimizations or writing patents or practicing Shotokan karate. LinkedIn: https://www.linkedin.com/in/joseph-gasparakis-5618985  )*

* **Arun Yerra** *(Part of Dell Advanced Engineering Team building NFV solutions with openstack as NFVI.)*

L2 gateway in a production environment - highly scaled, secured, seamless data and control path .
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It is heard that most of the cloud provider administrators find it difficult to configure openstack/networking-l2gw to bring legacy bare metal servers into cloud. This is because for the complete solution to work seamlessly, the administrator has to set the right configurations on the networking-l2gw side as well as on the switch side. It was also assumed that this solution is still experimental and was not made for the production quality.    


* **Gowri Manickavasagam** *(Gowri Manickavasagam, Senior R&D Test Engineer at HPE, is responsible for quality deliverables of HPE Cloud system and Helion Openstack L2 gateway modules. She is also involved in neutron-ironic integration activities to provide the automatic deployment and network connectivity of bare metals to the cloud,)*

* **Maruti Kamat** *(An active contributor in OpenStack Neutron (especially in networking-l2gw) . Have been working in OpenStack Neutron for past 3 years. Being with the networking business of Hewlett Packard Enterprise (cloud development) and earlier in BYOD and campus edge networking, played a major role in design and development of solutions delivered to valuable customers. Published several papers and patents in these areas.  )*

Trunked 40G Interfaces with QoS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Usually, OpenStack network architecture is complex and costly. Using multiple 10GbE NICs and Switches for management, storage, internal and public… will be a headache for the operators.   In the past, our private openstack deployment used many 10GbE interfaces with 2-link bonding. As a result, we had to manage 8 links!   This year, we introduced 40GbE NIC to simplify the situation, and we found this can reduce initial costs and everyday maintenance costs.   In this presentation, we will show: How to reduce many 10GbE links to trunked and 2-link bonded 40GbE NIC How to use Quality of Services (QoS) features to ensure bandwidth of each logical links when introducing 40GbE NIC.


* **Masaki Matsushita** *(Masaki Matsushita is a software enginner at NTT Communications.Masaki started contributing to OpenStack from Kilo release.He also contributes to Ruby as a committer mainly for performance improvement.He says, "I like Python too.")*

* **Mahito Ogura** *(Mahito Ogura is a Engineer at NTT Communications, working on Cloud technology R&D team.  He joined the team in late 2014 and since has been focused on to improve OpenStack in his company's cloud, to R&D OpenStack and to educate the cloud engineer.  Mahito has experience in distributed system development.  In the past 5.5 years he has been working for NTT Comware, defining and developing IaaS, NoSQL, configuration tools, KVS as a service, DBaaS(similar to Trove) and Hadoop as a Service (similar to Sahara) . He started contributing to OpenStack from Kilo release. He is actively contributing to DevStack.)*

* **Takeaki Matsumoto** *(Takeaki is software engineer at NTT Communications, working on Cloud technology R&D team.He joined the team in 2015 and since has been focused on to R&D OpenStack.)*

Using Neutron BGP to Dynamically Route IPv6 Tenant Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron provides floating IPv4 address to allow access to instances within it's private IPv4 tenant network from the internet, but Neutron does not provide floating IPv6 address to access IPv6 tenant network because IPv6 network doesn't need to be NATed. Address Scopes will allow to define L3 routed domains instead of forcing NAT on tenant routers, while BGP will automatically advertise new created subnets. This presentation will mainly explore how to use them to dynamically route IPv6 per-tenant network. With just a little bit of routing help from Neutron BGP, we can actually ping directly in to IPv6 tenant network which is in the same address scope as IPv6 external network. In this session we can have a better understanding of Neutron IPv6 feature, Neutron BGP feature, Neutron Address Scope feature etc.


* **Hua Zhang** *(Zhang Hua is a software engineer at canonical, he joined the OpenStack community in Feb 2012 as a contributor, since then he has been focus on the network domain. He loves coding and digging into the details of various computer technologies. Now he is also increasing other domain knowledge in area's of linux kernel, HA, performance, and storage etc.)*

* **Liang Chen** *(Liang is a software engineer at Canonical and has been working on OpenStack since Grizzly Release across various components of OpenStack. Over the last 3 years, he implemented many features both contributed back upstream and company proprietary and fixed a lots of bugs primarily from the community. He was very active in the community for Heat during Havana and Icehouse cycle. Now his primary focus in on Nova and underlying virtualization technology.)*

Deep Dive into VXLAN in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the development of the networking in OpenStack, more and more cloud architecutors are choosing VXLAN as overlay network. And, why VXLAN? VXLAN provides 16M tenant networks, better scalability and flexibility, failover with an L3 ECMP fabic, etc. In this summit, you will learn the history of VXLAN, how does it work, VXLAN network with MP-BGP EVPN Control Plane ,etc.


* **Zhi Chang** *(Zhi has worked as a sdn engineer for years at UnitedStsack, he started his contribution to OpenStack from 2013 and spends most of his time hacking on network (Neutron, Horizon, dnsmasq, Linux networking, etc.).He now currently based in Beijing where works for UnitedStack.)*

* **Wei Wang** *(Wei has worked as a sdn architect and networking team lead for 2 years at UnitedStsack, he started his contribution to OpenStack from 2013 and spends most of his time hacking on network (Neutron, network of Manila, dnsmasq, Linux networking, networkrking-bgp, etc.).He now currently based in Beijing where works for UnitedStack. Wei is also an actively open-source contributor, made contributions to buildbot and midonet. His blog is http://mytrix.me, where he wrote many articles about network, OpenStack Neutron, python, prolog and matlab. He lead a column which written by UnitedStack networking team, talk about openstack networking, neutron progress, ovn, dragonflow, fd.io, ovs, opendaylight and any other opensource networking project. http://bit.ly/29TIKIj)*

The Fuel VMware DVS plugin in comparison to other networking VMware backends
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many OpenStack users want to build hybrid clouds with both KVM and EXSi hypervisors -- and they must communicate with each other. The abundance of solutions for networking VMware backends can be confusing, so we will compare the Networking vSphere (VMware DVS) driver with others to provide enough information to make the right choice. This session covers: An overview of existing solutions, including: Nova-network Networking vSphere (OVSvApp) NSXv The Fuel plugin for VMware DVS The Networking vSphere (VMware DVS) driver A Demo of a deployed VMware DVS environment  Limitations, known issues and areas for future work The low latency, higher performing Networking vSphere (VMware DVS) solution, deployable with Fuel, is interesting for mid- and large size enterprises and telcos who are looking for an appropriate solution for their networking requests in vSphere-based or hybrid clouds as well as developers who are working on such solutions.


* **Igor Gajsin** *(Igor has been a Team Lead in Partner Integration Team for 3+ years working in DevOps, Puppet automation, and networking.)*

* **Alexander Arzhanov** *(Alexander has been a Team Lead in Partner Integration Team for 2+ years working in DevOps, Puppet automation, and networking.)*

Hybrid Clouds?  Open vSwitch to the rescue!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Because in most organization there is not one single virtualization platform and not one single cloud, we need to make multiple worlds communicate together and integrate. During this session, we will discuss how Open vSwitch can be used on KVM, VMware, Hyper-V and Docker containers in a combined solution within and outside of OpenStack. We will then show how using to link in your existing envrionment and how this can all be extended out to AWS or Azure. All of that managed with Nuage Networks SDN and API, because you deserve DevOps now!  


* **Arnaud Lheureux** *(Arnaud Lheureux is a regional Architect for Cloud Networking at Nuage Networks. After 10 years at Microsoft as datacenter architect and evangelist supporting Microsoft top account in EMEA, Arnaud joined Nuage Networks to help big organization as they adopt SDN in their infrastructure. Regular speaker and trainer at Microsoft and other industry events, Arnaud has been speaking about OpenStack and evangelizing interoperability of datacenter solutions for years.)*

* **Jonas Vermeulen** *(Jonas Vermeulen is Product Manager of Nuage Networks for the EMEA Region. In this position, he works with cloud service providers and large enterprises discussing network virtualization and overlay technologies for their datacenters. He covers the topic at various levels, ranging from business propositions to deep technical solution specifics, and enables a healthy feedback loop between customers and engineering.Prior to joining Nuage Networks, Jonas Vermeulen was an IPTV Senior Network Architect in Singapore and Technical Project Manager in New Zealand. In his free time he enjoys cycling, running, hiking and all kinds of other outdoor sports.    )*

* **Philippe Jeurissen** *(Philippe Jeurissen is a Cloud Design Consultant for Nuage Networks. Nuage Networks is venture of Nokia Networks. He helps service providers and large enterprises in the EMEA region with the virtualization of their data center networks. He is a strong believer of the OpenStack Project for next gen datacenters and application deployments and a defender of open source projects!)*

L2 adjacency of KVM and Hyper-V cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are native applications (such as office 360) that needs to run on Microsoft supported Hypervisor platform for better efficiency. A windows shop will have majority of their production servers  running on Hyper-V platform, and their DevOps workload running on KVM cloud. Licensing and supportability implications of running Windows application servers on KVM hypervisor forces customer to deploy Hyper-V cloud along with the KVM cloud for their non- windows specific (such as Oracle database servers) application. Under such scenario, the VMs on KVM cloud cannot communicate to VMs on Hyper-V cloud over the secure VxLAN network.


* **Sonu Sudhakaran** *(Active Neutron/Nova and Monasca contributor)*

* **Shiva Kumar** *(Working as a software developer at HP India. Filed blue print  "DHCP Service LoadBalancing Scheduler" and implemented it. Active code contributor in Openstack neutron.)*

* **Claudiu Belu** *(Neutron, Nova, Hyper-V cloud developer.)*

* **KRISHNA KANTH MALLELA** *(Neutron, Hyper-V developer)*

* **Vinod Kumar** *(Openstack Developer. Working on Neutron and Hyperv.)*

Neutron at CERN: moving thousands of production nodes from Nova Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CERN has been running a production OpenStack Cloud for several years. It was based on Nova Network from the start, with a few changes on the upstream code to adapt to the specifics of our internal networking infrastructure. With more than 6000 hypervisors split in tens of cells, 20000 virtual machines and an heterogeneous setup (KVM and HyperV) moving to Neutron with minimal disruption to users posed a significant challenge. In this talk we'll describe the Neutron plugin we wrote to integrate with our infrastructure, and additional extensions added to take into account network partitions (now covered with the upcoming segments feature being added upstream). We'll cover how we deployed Neutron and how we first enabled it in new cells, and later migrated existing cells once we were confident with the setup and sure it would scale. Finally we'll cover the new features we're looking into or have already enabled, such as Floating IPs, LBaaS and others.


* **Ricardo Rocha** *(Ricardo Rocha is a software engineer at CERN. He's currently a member of the CERN OpenStack team, focusing on service and application orchestration and container deployments. Previous work included development of data storage, bookkeeping and monitoring services for the LHC Computing Grid (LCG).)*

Network-diagnoser: A Distributed Health Monitor For Multi-tenant Network in DVR
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nowadays, Distributed Virtual Router (DVR) becomes more and more popular in overlay network deployment. With DVR, we can isolate the failure domain of network node and optimize network traffic by eliminating the centralized L3 agents. However, as its complicated implementation,  it is literally difficult to identify the root causes of faults on failure. Though there are various network monitoring frameworks for OpenStack, most of them don't work well with DVR mode. Network-diagnoser is a project for automatic network monitoring, troubleshooting and visualization, which makes it easy and efficient to resolve multi-tenant network issues, especially for DVR mode. It conisits of a centralized controller and several distributed agents. Network-diagnoser has been deployed in Qihoo production cloud and working steadily. It really makes our lives easiser.      


* **Kailang Deng** *(Taking charge of network development and deployment of private/public cloud as system engineer in Qihoo 360. Experienced with network troubleshooting and be familiared with OpenStack Neutron development.)*

Almost everything you need to know about provider networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Though the primary use case of OpenStack cloud is to create instances to tenant private networks and access them using floating IPs from external networks, there have been a lot of use cases to create instances directly to an external network to connect it to an existing network, especially for NFV. In this talk, you’ll get answers to the following questions and more: What are provider networks? What are the different types of provider networks (like flat and vlan) and what are their use cases? How do you configure provider networks to create instances directly to it and satisfy floating IP use cases? How do you enable access to Nova metadata service for cloud-init while instances are added to provider networks? How do instances communicate directly to external networks using provider networks? How do you troubleshoot problems related with provider networks?


* **Sadique Puthen** *(I am passionate about building, designing and supporting Infrastructure for workloads, especially Cloud IaaS, using open source technologies, primarily concentrating on Openstack and Virtualization with good knowledge of core Red Hat Enterprise Linux, clustering, storage and networking. Experienced in designing and building Infrastructure (Network, Storage, Operating Systems, etc) for complex applications and workloads for their entire life cycle from development, test cycles, production deployment, and post production monitoring and support of the infrastructure. Area of Expertise, - Cloud IaaS implementation, design and support using Openstack.- Virtualization RHEV, VMware and etc- Skilled in Virtualization and cloud with continuous working experience starting with RHEL/CentOS + Xen/UML back in 2003, RHEL+ KVM, RHEV, VMware, HyperV and Openstack.- Designing and supporting Networking, storage and High Availability solutions.- Expert level knowledge on Linux, especially Red Hat Enterprise Linux.)*

Scaling Neutron Networks to Ten Thousand Ports
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the increasing adoption of Neutron networking in production environments, cloud operators have greater expectations for the number of ports supported by a Neutron network. This problem is further compounded by projects such as Magnum and Kuryr that bring container orchestration and networking to Neutron users. Supporting this scale is challenging and puts significant pressure on the SDN controllers and their southbound database. The difficulty lies not only the actual number of ports but also the expected churn from short-lived containers. While a distributed controller mitigates some this pressure, the southbound DB is still a bottleneck in most cases. With the goal of making a ten thousand port network a reality, in this session we address the scalability problem from two dimensions. First is scalability in the virtual plane, by designing southbound models that allow loading the ports based on demand. Second, we tackle the physical plane by scaling across many physical hosts.


* **Alex Bikfalvi** *(I am a developer at the networking virtualization software company Midokura. There, I contribute to the MidoNet project, with a focus on the control plane. Previously, I worked both in the industry as a software engineer as well as in academia as a networking researcher on networking and distributed systems, having earned a PhD from the Carlos III University in Madrid.)*

* **Adrian Serrano** *(Software Engineer by the Autonomous University of Barcelona, has expertise in network traffic analysis products for desktop and cloud platforms. Currently part of Midokura's core team, developing MidoNet, the open-source network virtualization software for IaaS clouds.)*

A General Network Virtualization Solution for Hybrid Virtualization Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In order to manage diverse workloads running on cloud infrastructure, it is very common to deploy hybrid virtualization platform in cloud resiliant data center and a typical scenario is to deploy VMware for traditional enterprise applications and KVM for cloud native applications. As a result, the capability of managing hybrid virtualization is necessary in OpenStack to meet the requirements, not only the management of computing resources but also the connectivity of heterogeneous network architectures. In China Telecom, we formed a joint research group with Pica8 and AWcloud in China to tackle this problem by open technologies, like SDN controller, whitebox switch and software-based virtual router, etc. The platform is deployed in our national cloud computing laboratory. This integrated solution provides Layer 2 connectivity, tunnel optimization, high performance routing, visibility and reliability. Finally, we would love to share the architecture and details to the community.


* **Li Ma** *(Nick is a Linux veteran with over 10 years of experience on Linux development. He is the cloud architect at AWcloud where he works on OpenStack Networking, SDN/NFV, messaging system and large-scale cloud architecture. Prior to joining OpenStack community, he spent 4 years on infosec, virtualization/containerization and distributed system.)*

* **Zhilan Huang** *(Zhilan is the architect and reseacher in Guangzhou Research Institute of China Telecom. Her research concentration are SDN, IPv6 and cloud computing. Zhilan has a master degree of Zhongshan University in China.)*

Challenges of DVR in a Large Scale Production Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Distributed Virtual Router (DVR) implementation provides the ability of each compute node to handle east-west / north-south traffic locally. For last couple of cycles, openstack community has spent a lot of effort on DVR to make it more robust and meet the industry needs. However, there are too few use cases of DVR in large-scale production cloud today. Since last year, Qihoo has introduced DVR into production cloud. In this session, we will talk about challenges we met and how we deal with it.  


* **Yong Zhang** *(Working on NAT/LVS in Qihoo 360 for 3 years, interest in network technology and introduce neutron into Qihoo's cloud since 2015.)*

* **Yufang Zhang** *(Yufang Zhang leads a team at Qihoo 360, who work on building one of the largest infrastructure based on OpenStack in China. His interest includes virtualization, SDN and system administration. Currently, he is also contributing to OpenStack in the form of patches and bug report. Before joining Qihoo 360, Yufang worked at Redhat as an engineer on virtualization. )*

* **Jie Li** *(Working on network architecture and development of network management system for more than two years ,  and now  become a developer  of project neutron in our own public cloud. Interested in SDN/NFV.)*

Traffic Visibility with Virtual TAP and physical Devices
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As core businesses moving to cloud continually, flow visibility is becoming more and more important. It is the foundation for network traffic monitor, trouble-shooting and security analytics. Now, there are some tools to steer traffic in community such as mirror, sflow/netflow, tap-as-a-service. However, these tools have some limitation (e.g, performance, deployment restriction).   Elastic Tap is a distributed, multi-tenant traffic probe that is deployed in vSwitch. It steers virtual traffic to off-the-shelf devices, where analytics is done. Elastic Tap has less negative performance impact on the switch because it is based on configurable policy. This presentation will discuss this Elastic Tap in detail.


* **Guangming zhang** *(Guangming Zhang is a Software Engineer, working at Qihoo 360 Technology Co. Ltd. in the cloud platform since 2014. Guangming is currently focused on SDN/NFV architecture, design and deployment. He has over 10 years of experience in network/security development and design.)*

The race conditions of Neutron L3 HA's scheduler under scale performace
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron's Router presents a L3 interface that connects VMs to an external network. In its legacy mode, a router can be scheduled only to one agent at a time, presenting a single point of failure - if that node fails, all communications are halted. L3 HA mitigates this issue by presenting an Active/Passive configuration where a router can be scheduled to multiple agents which recover the datapath automatically during failures using a dedicated network that hosts keepalived processes. Using L3 HA presents an orchestration problem: since a router now appears in more than one agent and another dedicated network is required for the keepalived processes, there are a lot more resources involved. We performed L3 HA scale testing for Liberty and Mitaka, which showed benefits of L3 HA and uncovered a number of race conditions in Neutron code both on L3 agent and on server side. We'll present results of this scale testing and showcase some of these race conditions.


* **John Schwarz** *(Working for Red Hat and on Neutron for the past two years, soldier at the IDF beforhand. Coding enthusiast, review fanatic and speaking hobbiest.)*

* **Ann Taraday** *(Ann is a Software engineer, Neutron core-reviewer with a focus on databases, contributing to Neutron since Havana.)*

* **Kevin Benton** *(Kevin Benton is currently a Software Engineer at Mirantis. He has been contributing to Neutron since Havana while he was working at Big Switch Networks and has been a core reviewer since 2014. He is the Lieutenant of the reference implementation and also serves on the Neutron drivers team, helping the PTL define the direction of the project by selecting features to work on. He prefers to spend time improving the stability and performance of Neutron and its reference implementation to give deployers reliable OpenStack networking without immediately turning to a vendor.)*

Automatic network efficiency adjustment to optimize power saving
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Energy - We all depend on it. But when it comes to your data center's scalability and operational expenses, we all try to reduce power consumption as much as possible. One of the biggest power consumers are the network elements. Network is a critical part of any cloud, but is it really working as efficient as possible? Especially when it comes to power efficiency?   In this talk we’ll describe a solution based on Watcher - a new OpenStack project that provides a flexible and scalable resource optimization service for multi-tenant OpenStack-based clouds, and NEO: Mellanox Fabric orchestration and management tool. This solution enables to optimize network elements power consumption based on actual, real time cloud usage.


* **David Slama** *(Leading developments of Mellanox network management products and integration with cloud solutions and SDN controllers.)*

* **Tal  Anker ** *(Tal Anker, PhD, is leading the Cloud architecture in Mellanox. Prior to joining Mellanox, Dr. Anker served in various positions in the IT industry, among which are CTO and director of system and software architecture for Marvell Software Solutions, and Co-Founder and Chief Technology Officer at Sensogo. Dr Anker has over 20 years of experience in Data Networking and Distributed Systems. He has an extensive research background and has patented numerous technology solutions in network security, distributed systems/algorithms, and real-time operating systems. Dr. Anker holds a Bachelor, Masters, and Doctorate degree in Computer Science From the Hebrew University of Jerusalem. )*

* **Joe Cropper** *(Joe is a Senior Software Engineer within the IBM Systems Group, working on advanced virtualization management and cloud computing solutions--solutions that leverage OpenStack at their core.  While interested in a variety of areas, Joe is especially interested in virtual machine placement and optimization within the cloud--building solutions that provide policy-based placement decisions to meet a wide variety of business objectives.  Joe also enjoys working closely with enterprise customers to better understand how technology and OpenStack can help them both within their day-to-day operations and long-term strategy.  He has been working with OpenStack since the Grizzly release and feels extremely honored to be apart of such a transformational era of technology!)*

Flexible SR-IOV Passthrough and VirtIO-relay Based Acceleration on an Open vSwitch Compute Node
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will demonstrate a setup merging SR-IOV passthrough, a virtio relay system and Open vSwitch offloading rules to an intelligent server adapter, or SmartNIC. This combines two separate technologies into one solution, providing performance and power savings not possible using a pure software Open vSwitch. Standard Open vSwitch requires extra processing on the hypervisor. SR-IOV passthrough on most NICs allow only simple flat networks and prevents VM live migration. Flow rules can be offloaded to a SmartNIC, saving processing cycles on the hypervisor and supporting complex network types. A virtio relay provides an efficient interface between an SR-IOV device using vhost-user, allowing VM live migration. OpenStack Nova and Neutron make a number of assumptions about SR-IOV and Open vSwitch based networking solutions. This session will demonstrate how, with a slight change in perspective, multiple networking solutions can be presented in a unified interface.


* **Jan Gutter** *(Jan Gutter has been an Embedded Networking Software Engineer at Netronome for the last two years and has been working with networking and Linux since 2000. He's an incredibly curious person and enjoys figuring out how things operate. He loves figuring out how to make something new work together with something old.)*

* **Jan Scheurich** *(Jan has been working with Ericsson for most of his professional career with various networking products, such as Mobile Soft-switch and Packet Core. Since 2011 Jan is part of Ericsson's System and Technology organization working with Software-defined Networking in general and in the context of Network Function Virtualization infrastructure (NFV-I) and Cloud in particular. In this role Jan has been developing in-house SDN Controller and high-performance OpenFlow vSwitch before moving on to building SDN solutions based on the open-source projects OpenStack, OpenDaylight and Open vSwitch. Jan's focus areas are scalable system architectures and their characteristics such as performance and resiliency.)*

Speed and Reliability: How to Achieve both for OpenStack Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Single Root IO Virtualization (SR-IOV) enables cloud applications direct access to the server’s I/O hardware to achieve maximum network performance and efficiency. It does so through PCIe extension to virtualize a Physical Function (PF) into multiple Virtual Functions (VF). While OpenStack does support SR-IOV ports, there is no easy way to support VF high availability because it gives no control to user on how VFs will be distributed across PFs. In this presentation, we will introduce a way to achieve network high availability by exposing multiple VFs inside a guest, and utilizing them in various ways to achieve VF protection and failure recovery. For example, one way is bonding the VFs. Having multiple VFs/PFs does not protect the guest from switch failure. Two PFs can be connected to the same switch. Thus, we introduce a way to indicate the need to allocate VFs from PFs that are connected to different switches (thus partially circumventing the Shared Risk Link Group phenomenon).


* **Moshe Levi** *(Moshe Levi acts as a Cloud Solutions Engineer at Mellanox Technologies. Leading the Mellanox integration with OpenStack, in which puts contribution to OpenStack projects, including Neutron and Nova, at the field of Single Root I/O Virtualization (SR-IOV) and Openstack high performance features deployments. Before his current position at the Cloud solutions team, Mr. Levi worked at Mellanox SW management teams, with developing large scale networking projects and SDN oriented POCs.)*

* **Tal  Anker ** *(Tal Anker, PhD, is leading the Cloud architecture in Mellanox. Prior to joining Mellanox, Dr. Anker served in various positions in the IT industry, among which are CTO and director of system and software architecture for Marvell Software Solutions, and Co-Founder and Chief Technology Officer at Sensogo. Dr Anker has over 20 years of experience in Data Networking and Distributed Systems. He has an extensive research background and has patented numerous technology solutions in network security, distributed systems/algorithms, and real-time operating systems. Dr. Anker holds a Bachelor, Masters, and Doctorate degree in Computer Science From the Hebrew University of Jerusalem. )*

NTT West challenges in IPv4-v6 DualStack world with OpenStack and Software Defined Networks.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As one of the largest telecom operators in Japan with a broad service offering of cloud, mobile, and Internet services, NTT West is leveraging OpenStack to migrate to elastic, scale-out environment to accelerate service delivery for applications and infrastructure. NTT West requires a comprehensive solution that works with their current infrastructure which is built on IPv4 and IPv6, provides the elasticity of cloud for application development, and enables their operations team to monitor and troubleshoot their OpenStack cloud. In this session, NTT West will discuss their OpenStack journey and how they were able to build a solution to meet their criteria. Topics will include the following: Why OpenStack was chosen for NTT West’s cloud initiative Support for legacy and new applications and infrastructure Stability, multi-tenancy, scale, features/functions Operational needs to manage both virtual and physical resources Engaging the OpenStack community for future needs


* **Shigeaki Kimura** *(Shigeaki Kimura is an assistant manager at R&D Center, NTT-West.He is engaged in the development of a server platform for providing telecommunication services.He is challenging the OpenStack to evolve NTT-West's server infrastructure every day.)*

* **Sharad Ahlawat** *(Sharad Ahlawat is the senior director of engineering at PLUMGrid. He has 20 years of data networking, security, deep packet inspection, classification, and SDN technology experience.)*

* **Yuji Nakamura** *(Yuji Nakamura is responsible for Business Development at NEC Networks & System Integration Corporation (NESIC) which focuses on system integration and distribution business in Japan. Yuji began his career as a network engineer running production networks and has experience in operational aspects of networking.  In his current role, Yuji is  NESIC's representative in Japan to scope new technologies and products to solve challenges faced by Japanese enterprises.  Yuji enjoys technology and working with Silicon Valley and Japanese companies to put groundbreaking innovations in production.   )*

Scheduled to be the Fittest: Network-aware Scheduling in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

More and more cloud applications, especially virtualized network functions for NFV, or HPC applications, depend on the network features and capabilities that servers can provide to run optimally. For example, certain applications may need the underlying servers to have a high link speed (40GbE), network HA (MLAG) support, or a server where the switch uplink is not congested. In this session, we are going to present a way to schedule the VM based on network awareness, so that the VM can be the fittest to applications’ networking needs. Specifically, the proposal is to add a “Network-Aware Filter” to Nova scheduler, i.e. an External agent (“Network Aware Cloud Scheduler Agent”), that exposes REST APIs for the management of resource pools/Inventory. In this manner, a user can then choose to filter or grade hypervisors according to these attributes (similar to CPU. Memory, etc.). This work was motivated by the resource providers specs driven by the NOVA core community.


* **Moshe Levi** *(Moshe Levi acts as a Cloud Solutions Engineer at Mellanox Technologies. Leading the Mellanox integration with OpenStack, in which puts contribution to OpenStack projects, including Neutron and Nova, at the field of Single Root I/O Virtualization (SR-IOV) and Openstack high performance features deployments. Before his current position at the Cloud solutions team, Mr. Levi worked at Mellanox SW management teams, with developing large scale networking projects and SDN oriented POCs.)*

* **Tal  Anker ** *(Tal Anker, PhD, is leading the Cloud architecture in Mellanox. Prior to joining Mellanox, Dr. Anker served in various positions in the IT industry, among which are CTO and director of system and software architecture for Marvell Software Solutions, and Co-Founder and Chief Technology Officer at Sensogo. Dr Anker has over 20 years of experience in Data Networking and Distributed Systems. He has an extensive research background and has patented numerous technology solutions in network security, distributed systems/algorithms, and real-time operating systems. Dr. Anker holds a Bachelor, Masters, and Doctorate degree in Computer Science From the Hebrew University of Jerusalem. )*

A Newbie's Guide to Add Your Network Solution to OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This is a guide by a newbie for newbies on how to add your networking solution to OpenStack. There are a massive number of current networking options in OpenStack. This session will provide an overview of where what happens in a number of diverse scenarios: libvirt, Nova, Neutron and the various plugins and controllers for different historical releases. A step-by-step guide will be presented on the pitfalls of adding a new network solution to OpenStack. There are hardcoded assumptions in core Nova/Neutron, workarounds will be presented. Topics covered include resource reservation, order of operations and minimizing change footprint. An example scenario with a new VIF and VNICs will be presented.


* **Jan Gutter** *(Jan Gutter has been an Embedded Networking Software Engineer at Netronome for the last two years and has been working with networking and Linux since 2000. He's an incredibly curious person and enjoys figuring out how things operate. He loves figuring out how to make something new work together with something old.)*

Multi-site Neutron federation using OpenDaylight with direct host to host cross site connectivity
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Multi-site OpenStack proposals to-date require network gateways to connect the sites weather L2 Gateway or VPN. In the presented solution for multi-site neutron federation inter site connectivity is achieved by allowing direct tunneled connectivity between compute hosts on different sites eliminating the Gateway bottleneck.This solution is based on federated OpenDaylight (ODL) controllers acting as the Neutron driver in all sites. Each site has an independent local ODL cluster and the clusters communicate with each other using a distributed mapping service. By leveraging OpenFlow and OVS-DPDK 100Gb L2 and L3 networking performance is achieved even across sites. Sites may be geographically remote or partitions on a single data center.Cross site network models are defined by a cross site manager which communicates over standard Neutron API with the Neutron service instances in different sites.The entire solution demonstrated is an open source implementation upstreamed in the ODL project


* **Ariel Noy** *(Ariel Noy, CTO, HPE ConteXtream Ariel Noy is responsible for setting the technical direction and architecture for HPE ConteXtream, a business unit of Communications Solution Business. Ariel co-founded ConteXtream and served as CTO for 9 years. Prior to ConteXtream, he was a technical leader at Cisco Systems, which he joined as a result of its acquisition of Sheer Networks, where he was a co-founder CTO and VP Engineering for 6 years. Prior to this, he led the architecture and design of a large-scale network management project at 3Com. Ariel holds a B.S. in Math and Computer Science from Tel Aviv University.    )*

* **Sam Hague** *(Sam Hague is the Project Technical Lead for the OpenDaylight OVSDB project and Senior Principal Engineer in the Office of Technology at Red Hat, Inc. Sam's most significant contributions to OpenDaylight concern the network virtualization provider and OVSDB MD-SAL southbound plugin as well as service function chaining and the neutron northbound. Previous experience includes leading the software development at Extreme Networks adding OpenFlow to their line of switches and a variety of technologies at Cisco Systems from creating the first SIP IP phones to adding Bluetooth and VPN capabilities to mobile routers to implementing H.264/AVC video conferencing on Android-based tablets. (https://www.linkedin.com/in/samhague))*

* **Gideon Kaempfer** *(Gideon is a serial entrepreneur bringing with him 25 years of experience in Telecom networking, routing, hardware and software system design and development. Before joining HPE, Gideon held senior architect or CTO positions at Contextream, Xring Technologies, Axxana, Expand Networks, FlowInspect, SilverKite and Charlotte’s Web Networks. Gideon is a member of the OpenDaylight Technical Steering Committee (TSC). He has an MSc in Computer Science from the Technion - Israeli Institute of Technology.)*

Integrating Containers with OpenStack Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This  talk examines how containers use the OpenStack networking in order to  be able to provide the containers with netwoking capabilities, and how  containers are different from VMs from a networking vantage point.  We  look at what the needs of container networks are, how those needs can be  achieved, and what trade-offs have to be made.  We will dive into some  specific container networking solutions, but the talk is primarily intended  to introduce people to the higher level techologies that container  networking uses, and what the future for container networking might  hold.  Only beginner-level  knowledge of networking will be assumed, and by the end of the talk you  should have a far better understanding of how OpenStack and container  networking works together.


* **Benjamin Bennett** *(I am the Red Hat OpenShift networking team lead.  More to follow.)*

* **Marc Curry** *(Marc has been working with OpenStack and container infrastructure in data centers for the past 14 years at both Cisco and Red Hat.)*

Contrail as networking soultion for OpenStack and Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Providing secure, high-performance, SLA-compliant cloud services to multiple tenants in multiple locations with hybrid cloud topologies is nearly impossible to do with OpenStack’s and Kubernetes default networking back-ends.Contrail can provide network micro-segmentation to kubernetes, with both network isolation as well as the ability to connect a pod to external networks interoperating existing network devices. Contrail SDN utilizes logical leaf-spine layout for added performance and resilience and BGP-based federation at the network edges for facilitating hybrid cloud connectivity. Bare-metal or VM-based deployments of Contrail lack the flexibility, portability and ease of scalability for hosts running SDN control plane components. On the other hand, containerized solutions provide huge benefits in cases of performance, scalability, portability and building microarchitectures.


* **Oleksandr Martsyniuk** *(Oleksandr is a Mirantis Team Lead in the Partner Integration Team with 3+ years working in DevOps, Puppet automation, and networking.)*

* **Oleksiy Molchanov** *(Deployment Engineer at Mirantis with 3+ years experience in clouds.)*

Adapting your Networking Appliance to a world of Network Function Virtualization
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With service providers demanding scalable network infrastructure and much of the workloads moving to the cloud based virtual infrastructure, the network equipment providers has to cope with a new world of virtualized network function. To integrate with a virtual infrastructure just converting your network device to a virtual appliance is not enough. In this talk we will discuss the challenges of hosting a network appliance on OpenStack. Our discussion will involve the following parameters: Hardware requirements of a NFV (performance factors) Integration with cloud configuration system to provide a seamless movement of customer in to a virtual configuration interface. Deploying Multi-node VNF Scaling of virtual infrastructure Hooking up the network ports Network Ports configuration and trunking Clustering and HA in a virtual world.


* **Chandan Dutta Chowdhury** *(Tech Lead - Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ)*

* **Sarath Chandra Mekala** *(Sarath is a hardcore Java progarammer and has over 13 years of industry experience in building scalable and distributed Network Management Systems. He is currently working on integrating Juniper's Switching and Security devices with Openstack Neutron. The following are his areas of interest: - Neutron (ML2 and L3) - Neutron-FwaaS - Ceilometer  He blogs @ http://sarathblogs.blogspot.in/)*

* **Sriram Subramanian** *(Director - Software Engineering, Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ Blogger - http://www.innervoice.in/blogs Speaker - https://goo.gl/JYGcFo)*

Boosting OpenStack performance with OVS DPDK and OpenDayLight – performance benchmarking review
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Networking Virtualization enhancements are required to meet CSP performance requirements. The introduction of a DPDK accelerated version of OVS and an OpenDaylight SDN Controller to OpenStack yields optimized packet processing and hence higher networking performance. A benchmarking lab we built was used to test the throughput gains contributed by the introduction of ODL and OVS DPDK.In this session we review the OpenStack Network Virtualization reference architecture, the benchmarking tests and the tested performance results.


* **Ariel Noy** *(Ariel Noy, CTO, HPE ConteXtream Ariel Noy is responsible for setting the technical direction and architecture for HPE ConteXtream, a business unit of Communications Solution Business. Ariel co-founded ConteXtream and served as CTO for 9 years. Prior to ConteXtream, he was a technical leader at Cisco Systems, which he joined as a result of its acquisition of Sheer Networks, where he was a co-founder CTO and VP Engineering for 6 years. Prior to this, he led the architecture and design of a large-scale network management project at 3Com. Ariel holds a B.S. in Math and Computer Science from Tel Aviv University.    )*

* **Gideon Kaempfer** *(Gideon is a serial entrepreneur bringing with him 25 years of experience in Telecom networking, routing, hardware and software system design and development. Before joining HPE, Gideon held senior architect or CTO positions at Contextream, Xring Technologies, Axxana, Expand Networks, FlowInspect, SilverKite and Charlotte’s Web Networks. Gideon is a member of the OpenDaylight Technical Steering Committee (TSC). He has an MSc in Computer Science from the Technion - Israeli Institute of Technology.)*

* **Mark Gray** *(Mark is a software engineer and the lead engineer on the vSwitch enabling team at Intel.)*

Subnet Service Types - Addressing the Public IP Address consumption problem with Neutron routers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Neutron, each router with an interface on the external network consumesan IP address from the subnet configured on it. These IP addresses aretypically Internet-routable, and in most deployments are a scarceresource. When running with Distributed Virtual Routing (DVR) enabled,additional IP allocations are done for each compute node, which canquickly increase the number of addresses required into the thousands. A new concept is being introduced in Neutron to allow a subnet to belabelled with a "service type", such that IP allocations for routerports can use subnets that do not contain Internet-routable addresses,leading to a substantial decrease in usage. In this session we will describe what a Subnet Service Type is, howthey can be used in a large-scale deployment to reduce Public IP Addressconsumption, and do a short demo on the new commands and usage.


* **Brian Haley** *(Brian Haley is a core contributor to OpenStack Neutron, primarily focused in the L3 and DVR areas, but has particular interests in both IPv6 and cloud security.  He has been working on OpenStack since 2011, first on Nova Networking and later on Neutron.  His background is in kernel networking, both UNIX and Linux, mainly focusing on performance, scalability and IPv6 features over the past 20 years.  Brian currently works in HPE Cloud, developing and supporting HPE Helion OpenStack.)*

* **Carl Baldwin** *(Carl Baldwin is a regular contributor Openstack's Neutron project and has been a core reviewer since 2014. He is the Neutron L3 Lieutenant. He started his career developing electronic design automation software with HP’s microprocessor design projects: PA-RISC and Itanium. Years later, he spent a short time on a few of HP's network attached storage products. He was drawn to computer networking. He consistently stepped outside his purview to weigh in on office networking issues as well as to provide expertise to the network design in the products. In January, 2013, he got the opportunity to meet HP's new Neutron team in Fort Collins. He soon hired on to the team and has been enjoying it ever since. He is fascinated by network virtualization in the cloud. Carl lives in Fort Collins, Colorado with his wife Emily, two daughters, and a son. He loves to run, hike, swim, mountain bike, and plays disc golf and volleyball. Otherwise, his hobbies look a lot like his work: writing software and tinkering with networking.)*

* **John Davidge** *(John is a Program Specialist at Rackspace, and has been working with the OpenStack community since 2012. Starting with network visualization tools - Curvature & Donabe - he now works on IPv6 networking functionality in Neutron.)*

OpenStack At Hyperscale: Deploying On a Full-Mesh Routed Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will cover Clos networking architecture, also known as "Spine and Leaf", and presents an overview of deploying OpenStack in a fully routed network architecture. By utilizing the routing features present in most top-of-rack datacenter Ethernet switches, spine-and-leaf isolates broadcast domains and allows for horizontal scalability. Deploying OpenStack in a routed network environment requires knowledge of how OpenStack interacts with the network, and careful planning to ensure interoperability of components across routed subnets. Hyperscale architecture expands spine-and-leaf with a multi-dimensional spine. Facebook, Google, and LinkedIn use hyperscale architecture to maximize their capacity and throughput. While Hyperscale architecture is new to most Enterprise networks, the concepts behind spine-and-leaf networking are well established, and the technologies used are the same that you will find in any carrier-grade Internet service provider network.


* **Dan Sneddon** *(Dan Sneddon is a Principal OpenStack Engineer with Red Hat, and the Network Architect of RDO and Red Hat OpenStack Platform. Dan has over 20 years of experience in large-scale networking and datacenter operations. Prior to joining Red Hat, he designed the OpenStack HA and NFV architecture for Cloudscaling, and has been developing for OpenStack since the Diablo release. Past positions include Lead Network Engineer for Apple and Network Security Architect for SLAC National Accelerator Lab.)*

Is OpenStack Neutron production ready for large scale deployments?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Neutron with ML2 OVS has always been a challenging component in terms of performance and scalability. However, in recent releases, several enhancements and bug-fixes have resulted in significant improvements in overall reliability, performance and scalability of Neutron. In this talk, we will share the results of our testing (both control-plane and data-plane) at large scale and provide a detailed data-driven analysis that explores the true scale limits and bottlenecks of Neutron. We also discuss better ways to tune Neutron configuration parameters for large scale. Moving forward, we expect further improvements based on planned optimizations. With these changes, is Neutron ready for large-scale production deployments? If customers are planning to deploy vanilla Neutron in their production deployments, what can they expect? How does the reference implementation stack up against other commercial alternatives? These are some of the questions the presentation tries to address.


* **Oleg Bondarev** *(Oleg Bondarev is a Senior Software Engineer at Mirantis working on OpenStack Neutron both in upstream and in Mirantis OpenStack (MOS). He started contributing to OpenStack in Havana release where he took an active part in development of LBaaS v1.0. In Icehouse he became a Neutron Core Team member and now his main focus of contribution is Neutron stability, scalability and performance.)*

* **Satish Salagame** *(Satish Salagame is the Director of Engineering, Networking at Mirantis focused on OpenStack networking, Container networking, SDN and NFV solutions. Satish is a seasoned technology professional in the Networking industry with strong experience in Software Design/Development, Solutions integration, Network Architecture, Product Management, and Engineering Management. Prior professional associations include several startups, StrataCom, Cisco Systems, Calient Networks and Infinera among others.  )*

* **Elena Ezhova** *(Elena has been working on OpenStack since Grizzly release and has contributed to such projects as Neutron and its advanced services, especially Octavia, LBaaS, as well as VPNaaS, Oslo, Tempest and Keystone. She was responsible for graduating the oslo.service library and currently is a member of its core team.)*

Deploying ODL Containers as a Network Controller In OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenDaylight (ODL) is an open source network controller. It is a popular choice in its use as a layer 2 plugin for the Neutron network project and has been included in the big tent of Neutron plugins. In this presentation we will demonstate how to deploy an OpenDaylight Docker container that can be used in large deployments. This containered deployment solution for OpenDayLight and OpenStack can be used as a reference for other networking backend deployments as well. 


* **Manjeet Bhatia** *(Manjeet is a Software Engineer at Intel Corporation working on neutron. He facilitated the container management in context of proxies, developed IP capacity tracking for neutronclient. He also has some bug fixes in neutron and magnum modules of openstack. He lives in Green Portland who loves nature and opensource development. )*

* **Ankur  Gupta** *(I am a Portland native and still believe the Pacific Northwest is the best place in the world. Recently graduated and joined Intel as a Software developer. While at Intel have worked with the OpenDaylight project and OpenStack. Recently, relocated to San Antonio to join the OpenStack Innovation Center, a joint venture between Intel and Rackspace. As a part of OSIC have worked in a large team of new upstream developers. Although still learning, have contributed largely to the Horizon and Neutron projects.)*

LBaaS with Highly scalable muti VPC and muti LB device plugin support
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

LBaaS with Highly scalable muti VPC and muti LB device plugin support.


* **Maharajan Nachiappan** *(Part of one of the largest openstack private cloud development team, I am part of LBaaS development and have played a role in enabling LBaaS services againts external loadbalancers by replacing the propritery loadbalancer management service and enabled LBaaS handling multiple loadbalancer with multiple Virtual Private Cloud, leaveraging LBaaS scheduler to pick external loadbalancers based on the Virtual Private Cloud and availability.)*

* **Anant Kumar** *(Anant is currently responsible for managing the Paypal Cloud, the world's largest Openstack deployment. Spent over a decade working in Cisco Engineering, another 2 running a technology driven Fashion eCommerce business and then Indoor Location at Aruba Networks. Currently responsible for managing the Paypal Cloud. PayPal runs the world's largest OpenStack cloud with ~10000 servers. All of paypal.com and applications run on this cloud. An OpenStack newbie 2 years ago, am still learning the intricacies of deploying and managing a cloud using Openstack.  The complexity of running the cloud is in managing the underlying infrastructure and automation around that. )*

Troubleshooting Cloud Networking Like a Pro 2.0
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Room got filled quickly and there was a big lineup outside our presentation room in Austin. That’s when we realized the need for continuation of our Cloud Networking Troubleshooting. This is phase 2 of our Presentation + Demo. Here we will share our best practices for troubleshooting, with practical examples from real world scenarios: DPDK SR-IOV OVS – Deep Dive First we’ll go over the challenges in troubleshooting DPDK/SR-IOV/OVS (Integrated with DPDK). Then we’ll show how to find your troubleshooting rhythm in the chaotic world of cloud networking. Lastly, as we did in Austin, we’ll show you how do Pros, fix their cloud networks. Embrace yourself for a bumpy ride with a promise of a happy ending.    Whether you are beginner or advanced, if you are struggling much with networking in your cloud, join us to learn new solutions or just to bring home a good troubleshooting guide


* **Sohail Arham** *(As a member of the Cloud Platform, CSI EP team, I’m currently focused on design and integration of Cloud solutions based on Ericsson Cloud System (ECM, CEE), OpenStack and VMware to enable private/public clouds. I am responsible to performs different VNF virtualization and on boarding of VNFs on cloud environments. Working with Tier-1 operator to orchestrate and instantiation of different VNF function on their cloud.   Design, Implementation, Testing and Deployment of VMware/Openstack Infrastructure for Internal Development team. Supporting number of pre-sales/post-sales as an SME on Cloud technologies like VNF/Network Orchestration, VNF deployments on 3PP Cloud, VNF certification and characterization for customers in North America.)*

* **Syed Moneeb Javed** *(Been in Telecommunications Industry for about 8 years. Was involved in Telecom network integration, design and managed services.   Currently working in Ericsson Cloud Design Team and helping with putting together Demo’s and PoC for various global engagements. Experience in CDN and Media Sreaming has got me into Edge Cloud Services and have started working with OpenStack community in Meghdwar and lokking to present the lessons learned as a joint comunity efrorts with colleagues from competing venodors.)*

* **Konstantin Komaristy** *(Telecommunications Industry veteran. Been with Ericsson for 18 years in various roles touching different aspects of development, maintenance and life cycle of Telecom Technologies. Currently working as System Integrator in Ericsson Cloud Design Team and involved in multiple projects around Cloud Networking, Compute and Storage. Is a technology enthusiast and an advocate of Open Source Technologies.)*

Impact of DVR port-binding on Live Migration and Allowed-Address-Pairs in Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  The Distributed Virtual Router (DVR) implementation in Neutron heavily depends on theNeutron port-binding to identify the DVR service ports to configure routers on hosts, and to route traffic both East-West and North-South. Some advanced features, such as Instance Live Migration and Allowed-Address-Pairs, have adirect impact on the distributed nature of the ports and how they are bound and unboundwith Floating IP addresses. This session will target the design considerations for Live Migration andAllowed-Address-Pairs with respect to DVRs, in order to achieve more flexibleuse cases by changing the relationship between Floating IPs and how they arebound and unbound to Neutron ports.


* **Swaminathan Vasudevan** *(Swaminathan Vasudevan is a Systems Software Engineer at Hewlett Packard Enterprise where he currently works on Cloud Networking Division in OpenStack Neutron. He is an active technical Contributor of OpenStack since 2013 and have contributed code to VPNaaS and Distributed Virtual Router in Neutron. Swaminathan Vasudevan has been developing code for more than 18+ years with expertise in linux, virtualization, networking, mobility, security and convergence.)*

* **Brian Haley** *(Brian Haley is a core contributor to OpenStack Neutron, primarily focused in the L3 and DVR areas, but has particular interests in both IPv6 and cloud security.  He has been working on OpenStack since 2011, first on Nova Networking and later on Neutron.  His background is in kernel networking, both UNIX and Linux, mainly focusing on performance, scalability and IPv6 features over the past 20 years.  Brian currently works in HPE Cloud, developing and supporting HPE Helion OpenStack.)*

ODL/OpenContrail Integration with OpenStack, the Pain the Gain and the lessons learnt
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack without SDN Controller is like life without Tapas (You would understand if you’ve been to Barcelona). In the dreamland everything works seamlessly. You want ODL to sing with your OpenStack or you would like to see OpenContrail dance with it, your choice, it will just work. But, you have to take up the daunting journey of “integration”, which is not as pleasant and straight forward as one might think. In this presentation, we’ll detail steps to integrate SDN Controller with your OpenStack, what are challenges and how we solved them. Join us to learn how and what to do and more importantly, what not to do. Ask us your questions, share your comments and let us help share the story of our journey with those who are undertaking it now to make it easier for them what was a rather an “interesting” experience. Leave the session on a high note of believing that we’ll make your OpenStack sing and dance with your choice of SDN Controller (ODL or OpenContrail). 


* **Sohail Arham** *(As a member of the Cloud Platform, CSI EP team, I’m currently focused on design and integration of Cloud solutions based on Ericsson Cloud System (ECM, CEE), OpenStack and VMware to enable private/public clouds. I am responsible to performs different VNF virtualization and on boarding of VNFs on cloud environments. Working with Tier-1 operator to orchestrate and instantiation of different VNF function on their cloud.   Design, Implementation, Testing and Deployment of VMware/Openstack Infrastructure for Internal Development team. Supporting number of pre-sales/post-sales as an SME on Cloud technologies like VNF/Network Orchestration, VNF deployments on 3PP Cloud, VNF certification and characterization for customers in North America.)*

* **Syed Moneeb Javed** *(Been in Telecommunications Industry for about 8 years. Was involved in Telecom network integration, design and managed services.   Currently working in Ericsson Cloud Design Team and helping with putting together Demo’s and PoC for various global engagements. Experience in CDN and Media Sreaming has got me into Edge Cloud Services and have started working with OpenStack community in Meghdwar and lokking to present the lessons learned as a joint comunity efrorts with colleagues from competing venodors.)*

* **Konstantin Komaristy** *(Telecommunications Industry veteran. Been with Ericsson for 18 years in various roles touching different aspects of development, maintenance and life cycle of Telecom Technologies. Currently working as System Integrator in Ericsson Cloud Design Team and involved in multiple projects around Cloud Networking, Compute and Storage. Is a technology enthusiast and an advocate of Open Source Technologies.)*

Network abuse prevention using dynamic QoS enforcement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network abuse and "noisy neighbor" is an issue that every public cloud provider faces. In this presentation, we will demonstrate how can we apply QoS to each Neutron  to limit the network bandwidth per VM. We will further demonstrate how we can dynamically update the QoS policy for a running work load. We will also describe how our solution can be used to apply QoS policy with different rules to different tenants.


* **Shaival Chokshi** *(As Senior Software Engineer in IBM Cloud group, I have been involved in developing and architecting network solutions for IBM cloud offering, both in private managed hosting and in public domain. My prior experience include working on virtualized networking on IBM Power systems.)*

* **Daniel Levy** *(After completing his masters in 'anomoly detection in climate data', Daniel has been working at IBM, first with a project called Watson Analytics, that parses large data sets, and gathers crucial insights; and from on networking and cloud scalability. Today he focused on integrating OVN (Open Virtual Networking) into IBM's public cloud offering.)*

* **Bhalachandra Banavalikar** *(Networking professional)*

Network Orchestration for the Enterprise
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network virtualization is now becoming a standard practice in many data centers. The reality though is that many organization still rely on manual processes to manage their network infrastructure, since achieving reliable and scalable network automation, while ensuring carrier-grade considerations such as security, standards, and robustness is no simple feat. In this session, we will discuss how we can automate network operations through Openstack Neutron together with the rest of the application stack. We will also discuss how we can use network automation to actually increase network security, all while ensuring enterprise-grade standards are maintained.


* **Shay Naeh** *(Shay Naeh is a seasoned technology professional with over 20 years of experience in the areas of internet ventures, cloud services and enterprise software who helps lead technical innovation on the Cloudify team at GigaSpaces. He has driven the directions of several successful start-ups and ventures.  Some of Shay’s expertise includes deep coverage of networking, DPI and protocols, and specifically NFV, network automation and orchestration, virtualization, security, web acceleration, large-scale applications, application performance management, cloud multi-tenant models, SaaS, agile prototyping and more.  Shay is an avid blogger and technology writer.  )*

* **Yoram  Weinreb** *(Yoram Weinreb, member of the CTO office at GigaSpaces, is a distributed and cloud computing expert with over twenty years of experience programing, architecting managing and consulting to large scale distributed systems.)*

Distributed Hardware routing, along with neutron routers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Routing has always been challenge in OpenStack. One solution does not fit all situations, hence, many routing choices - such as Neutron HA router, DVR, Astara, and HW routing.  How does one decide which is the optimal for their deployment?  Many factors play in such as - complexity of deployment (and debugability) as in DVR, or scale issues as in Neutron router.  So, what is critical? - Scale or ease of deployment? What if you can have both?  Well, come in and listen to our presentation, where we will discuss how we take hardware based distributed routing, along with neturon routers to make the deployment simpler and highly scalable.   


* **Shashank Hegde** *(TBA)*

Enabling advanced L7 Load Balancing in Kubernetes with OpenStack Kuryr
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Load balancing is not the same in Kubernetes as in OpenStack. Kubernetes LB focuses on L4, especially for E-W traffic, with automatic backend management and affinity guarantees. OpenStack LB is comparatively more focused on N-S traffic, elasticity, and choice of different vendors for advanced capabilities. OpenStack LB also plays nice with L4 and L7 security, port mirroring, and QoS. Avi Networks and Midokura have combined the best of both approaches, leveraging OpenStack Kuryr and Neutron to implement overlay networking for Kubernetes This allows Midokura to automatically deploy and configure Avi Networks’ load-balancer Pods via LBaaS APIs, triggered by creation of Kubernetes Service templates and Pods. Avi Networks’ load balancer is a drop-in replacement for KubeProxy, preserving its advantages (affinity, no traffic trombones) while delivering high-performance SSL and real-time application monitoring. Kuryr programs security policies in Neutron based on Kubernetes templates.


* **Shashi Sastry** *(Shashi heads Product Management and Strategy for Midokura, a company that focuses on Overay networking and microsegmentation at scale. Shashi has 17+ years of experience in the networking industry and has held a wide range of roles starting as a software developer at Cisco (embedded systems, IKE/IPSEC, GETVPN), Customer Advocacy Engineer, and Technical Marketing Engineer (both at Cisco and Aruba Networks). The few years she spent in Cisco's Customer Advocacy group in Europe makes her a strong advocate for the customer. She has experience working in several startups including Vyatta (acquired by Brocade), Nuage Networks, and now Midokura. Shashi's main areas of focus are Virtualization, Cloud technologies, performance, virtualized data center architectures, and Network Function Virtualization, and scalability. )*

* **Praveen Yalagandula** *(Praveen Yalagandula is the OpenStack Architect at Avi Networks, responsible for designing and developing the integration of Avi Networks’ Cloud Application Delivery Platform with OpenStack infrastructure services. At Avi, Praveen also leads the application performance visibility component of the Avi’s solution and has developed a scalable and distributed log analytics system. Prior to Avi, Praveen was a Principal Scientist at HP Labs in Palo Alto, where he spent 8 years exploring several aspects of data center networks, software defined networking, and large-scale distributed systems. Praveen received his Ph.D. in Computer Science from the University of Texas at Austin in 2005. He is currently a senior member of IEEE and ACM.)*

Deploying IPv6 in OpenStack TripleO
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

IPv6 is the latest version of the Internet Protocol standard. Internet Engineering Task Force (IETF) developed IPv6 primarily as a means to combat the exhaustion of IP address from the current common IPv4 standard. But IPv6 has lots of new features and advantages compared to the older protocol. In the context of OpenStack, IPv6 features let users choose to spawn instances on IPv6 only or via dual-stack, and it lets architects decide if underlying services should run via legacy IPv4 or via the new IPv6. Not all features are currently implemented for IPv6, and users and administrators alike will face challenges in IPv6 enabled clouds. Throughout this session, administrators will learn how to deploy overcloud services and Neutron tenant networks in OpenStack.


* **Andreas Karis** *(I am passionate about all things related to networking, to Linux and to the cloud. Currently, I am  specializing in all aspects of OpenStack and particularly Neutron.)*

* **Jeremy Melvin** *(Hello, I am an OpenStack Support engineer working at Red Hat.)*

Accelerating Data Delivery to Containers via OpenStack and SmartNICs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Docker provides management of Linux containers with a high level API providing a lightweight solution that runs processes in isolation. It provides a way to automate software deployment in a secure and repeatable environment. When used with OpenStack it becomes much more powerful since it’s then possible to manage several hosts, which in turn manage hundreds or thousands of containers. NAT is often used in conjunction with Linux bridging and firewalling to securely connect containers to public networks. Offloading Linux bridging, iptables, and NAT to SmartNICs can increase the throughput and reduce the CPU utilization associated with network connectivity for containers. In order to support a large number of containers, demultiplexing to a commensurate number of host endpoints is required. This presentation explores these requirements in detail while describing options for high performance and accelerated implementations and the implications on OpenStack, specifically Nova and Neutron.


* **Daniel Proch** *(Daniel Proch is responsible for Solutions Architecture at Netronome.  His role includes technology strategy, network architecture, and hardware and software planning.  Previously he was Vice President of Product Management responsible for their line of Intelligent Server Adapters and software.  He has engineering and telecommunications degrees from Carnegie Mellon University and the University of Pittsburgh.)*

Fast and Faster: OpenStack Security Groups using SmartNIC-Accelerated Connection Tracking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack's security groups facilitate micro-segmentation of cloud infrastructure. Historically they have been implemented using the Linux bridging and firewalling facilities. The latest Open vSwitch release (2.5) can interface to the Linux kernel connection tracking (conntrack) module to improve the performance and granularity of security group implementations.  This presentation describes the OVS conntrack architecture and the expressiveness it offers. It covers the integration of OVS conntrack with OpenStack via an OVN driver or a ML2 plugin. It furthermore describes how OVS conntrack can be accelerated by employing SmartNICs, yielding improved throughput and reduced CPU utilization.


* **John Hurley** *(John has been working with Netronome for 4 years looking at the acceleration of SDN and virtual switching using multiple generations of Netronome’s Flow Processors and Intelligent Server Adapters. Prior to this he has been involved in academic research into network analytic and security systems at the Centre for Secure Information Technology (CSIT), Belfast, and product development through startup company TitanIC. He completed a MEng in Computer Science in 2006 and a PhD in 2009, both at the Queen’s University of Belfast.)*

OpenStack Network Performance Tuning and Design at Paypal
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will be discussing the data plane architecture options and performance tuning in Paypals's private cloud environment and the technical challenges that we are facing while making these changes. Topics will be covered include: Network Performance profiling of ML2 based OpenStack at Scale in production deployment Network tuning options (Linux Bridge, Security Groups, LACP, OVS versions) in ML2 based OpenStack production deployment Technical challenges and operational challenges on network tuning in a large scale and multi-tenant production environments


* **Zhenhua Feng** *(Zhenhua is a staff software engineer with Paypals' cloud engineering team. He works on OpenStack and SDN to bring availability, scaliblility and security to one of the largest online payment systems in the world. Before that, he was with Cisco's Enterprise Networking Group building switches while drinking beer. He has significant contributions to L2/L3 multicast, Mobility for the catalyst series. Zhenhua holds a PH.D in computer engineering from Virginia Tech and a BE in information engineering from Beijing Institute of Technology.)*

* **Aihua Li** *(Aihua Li is currently with Paypal taking the role as the cloud networking Project Team Lead. He is overseeing the effort of adopting openstack solution to Paypal large scale deployment, extending openstack with customization requirement and automating deployment process. Prior to Payapal, Aihua has taken principal leadership positions in different companies including Huawei Technologies, Motorola Solutions, Symbol Technologies. Aihua's expertise includes wireless networking, kernel and user-space based virtual switching, service-chaining, distributed switching systems. Aihua has earned a total of nine patents in these areas. )*

What does it take to integrate Octavia with a Container Orchestration Engine. What is it good for?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Elastic containerized services rely on Load Balancing (LB) functionality to be implicitly provided by the platform. In k8s, kube-proxy acts an implicit distributed LB but its capabilities are limited to L2-L3 and cannot be easily extended beyond this. At the same time, OpenStack Octavia allows deploying multiple function-rich LB nodes in several different topology configurations and to expose it as a service through industry standard LBaaSv2 API. In this talk, we explore the possibilities whereby Octavia and k8s can be mutually beneficial and demonstrate several integration scenarios: Octavia as a service in k8s clouds interconnected by Neutron networks through the Kuryr integration layer; Octavia LB between a service tier implemented by VMs and a service tier implemented by k8s containers; Openstack with lightweight containerized Octavia service deployed over k8s. We demonstrate how the proposed solution is enabled by several SDN-based Neutron backends, namely Midonet and OVN.


* **Katherine Barabash** *(Kathy is a manager and a technical leader of the Cloud Networking Group in IBM Haifa Research Lab and one of the inventors of the IBM's overlay network virtualization solution. Kathy is with IBM Research since 1997, contributing to different system research areas. Since 2007, Kathy is actively involved in cloud and data centre network virtualization research, basing on OpenStack Neutron since about 2011.)*

* **Irena Berezovsky** *(Irena Berezovsky is a Senior Architect for Midokura. She is responsible for driving open source MidoNet compatibility across all the OpenStack projects.  An active contributor to Neutron and Nova for several releases, her noteworthy contributions to the open source community include introducing SR-IOV support into Openstack and related OSS projects like SFC, Kuryr, tricircle. Her specialties include distributed systems, open source, embedded and network management software design and architecture. Before her current position at the Midokura CTO team, Irena worked at Mellanox Data Center Solutions group, leading Mellanox product strategy and innovative technology SDN oriented integrations as well as leading Mellanox strategy for integration with OpenStack. In the past, Mrs. Irena Berezovsky led architecture and product strategy for Voltaire and Nokia Siemens Network. Mrs. Irena Berezovsky holds a Bachelor of Science in Computer Engineering and Economics from the Tel Aviv University)*

Network of the Future: Accelerated OpenStack Networking with Contrail vRouter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenContrail system enables OpenStack to support virtual networks that span across datacenters, using a vRouter software dataplane component. However, running the dataplane purely within the hypervisor can have a significant CPU and memory bandwidth cost. We describe how a programmable NIC (SmartNIC) can accelerate the dataplane by offloading the routing function and directly delivering traffic into and out of VMs. With the concept of “representative interfaces” and a vendor-neutral offload API, the presence of hardware acceleration can be almost transparent to the orchestration and management layers.This new approach requires OpenStack to treat VM and hardware interfaces differently from those of traditional NICs. We examine the tradeoffs of various acceleration architectures, and the implications of SmartNICs to OpenStack architecture. The resulting system offers the flexibility of software while improving on the resource usage and performance of traditional hardware.


* **Ted Drapas** *(Ted Drapas is a director of software engineering at Netronome leading the vRouter acceleration effort.  Ted has 10 years of experience at Netronome working on security appliance and SDN software.)*

* **Chris Telfer** *(Chris Telfer is a distinguished software engineer at Netronome System where he has worked for the past 8 years. Among other endeavors, he works on the vRouter acceleration project at Netronome.)*

* **Raja Sivaramakrishnan** *(Raja Sivaramakrishnan is a distinguished software engineer at Juniper Networks. He is currently working on the vRouter forwarding component in the Contrail network virtualization solution. Previously, he worked on forwarding infrastructure in Junos for multiple router/switch platforms at Juniper.)*

Design and Performance Characteristics of Tap-as-a-Service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tap-as-a-Service is an OpenStack project designed to give tenants and service providers a safe and reliable means of monitoring the traffic flowing in their Neutron provisioned virtual networks, via the attachment of virtual taps that do not require any modifications to their instances. Following a short overview of the project, this presentation will explain the TaaS service-plugin and TaaS agent/driver designs and show how they facilitate the implementation of vendor and platform specific extensions. Recent enhancements to the API for supporting asynchronous behavior will also be covered. A discussion on the need for isolating production and mirrored traffic in the physical (underlay) network will follow, during which we will outline the techniques we are pursuing to realize this. Next, an in-depth performance analysis of TaaS will be provided using different operating modes, platforms and workloads. We will conclude by mentioning some of the planned enhancements for the future.


* **Anil Rao** *(Anil Rao is a Distinguished Engineer at Gigamon, leading research and development activities related to virtual machine traffic monitoring. Previously, he worked at Hewlett Packard, VMware and Ericsson. Some of his past accomplishments include implementing Memory Resource Groups in the HP-UX kernel and developing the memory scheduler for the ESX hypervisor. More recently, he was responsible for the inception of the router virtualization effort at Ericsson and served as the principal architect for the project. Anil’s research interests include operating systems, distributed computing, virtual machine technology and software defined networking. He holds a BTech in Computer Engineering from National Institute of Technology, Karnataka and an MS in Computer Science and Engineering from the University of Connecticut.)*

* **Kazuhiro Suzuki** *(Kazuhiro Suzuki is a researcher at Fujitsu Laboratories Ltd. He is interested in the areas of parallel and distributed systems, software defined network, and virtual machine technology. Previously, he contributed to Xen hypervisor community for 4 years. Currently, he is contributing to Tap-as-a-Service project that is a subproject of Neutron.)*

* **Reedip  Banerjee** *(  - Developer with primary contributions in : a) Python-NeutronClient b) Tap-as-a-service c) Neutron Advanced services( LBaaS, FWaaS, VPNaaS) d) Neutron e) Network related issues in Horizon  - Total Experience in software domain of 7 years. - Working with NEC Technologies India for the past 4 years. - Working in Openstack for the past 7 months.)*

NetArbiter: Multi-site Network Stitching and Emulation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the AT&T Integrated Cloud (AIC), distributed storage systems such as Ceph can be deployed over multiple sites to improve reliability and latency.  In order to deploy and test distributed storage systems in a geographically-dispersed cloud environment, we have built a framework for multi-site network stitching and emulation called NetArbiter. NetArbiter is able to bind different OpenStack clusters such that Virtual Machines (VMs) communicate with each other within a single private network domain. In addition, NetArbiter can emulate network delay and bandwidth between geographically distributed sites.  NetArbiter uses a DevOps tool named Ansible for ease of implementation and deployment.


* **Hee Won Lee** *(Hee Won Lee received a Ph.D. degree in Computer Science from North Carolina State University in May 2015. He received a B.E. in Electrical Engineering from Korea University in 2002, and a Master of Software Engineering from Carnegie Mellon University in 2005. During 2002-2009, he worked for KT Corporation as a Technical Member of Staff. He is currently employed as a Principal Member of Technical Staff at AT&T Labs Research. His primary research interest is in networking and storage systems.)*

Containers networking acceleration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The use of Containers in OpenStack is growing, mostly around high performance work load such as NFV. While virtual machines networking stack evolved over time and offer many accelerations, Containers networking is significantly behind.  In this talk we'd like to present a proposal to enable network adapters stateless offloads such as: Receive Side Scaling (RSS) and Transmit Side Scaling (TSS) Accelerated Receive Flow Steering (RFS Dedicated HW descriptor ring and buffers for receive and transmit with containers. During the talk we'll show how we allow the above offloads to apply for Container networking through exposing them for vEth devices. This includes RSS/TSS and aRFS for steering packet processing to each Container associated cores and as well as assigning dedicated HW receive and send queue and buffers for each Container, resulting with enhanced network performance for Containers through standard existing administration tools


* **Erez Cohen** *(Erez Cohen acts as Mellanox Vice President for CloudX Program, responsible for all aspects of the program including architecture, implementation and marketing/sales. The CloudX program incorporate Mellanox state of the art network and storage interconnect product lines to form the most efficient and scalable cloud infrastructure. Between 2003 and 2013 Mr. Cohen led the Field Engineering group at Mellanox. In this position Mr. Cohen was responsible for Global pre and post sales technical support for OEMs and end users. As part of this role Mr. Cohen was involved with some of the largest and most complex data centers and High Performance Computing clusters in the world. Between 2000 and 2003 Mr. Cohen lead the Architecture and Design Validation group at Mellanox. Mr. Cohen holds a Bachelor of Science in Computer Engineering from the Technion Israel Institute of Technology.)*

Container Networking Strategies in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For cloud architects looking to build secure networks that span several docker hosts in their OpenStack cloud, there are a bunch of different options available. One approach is to use the Kubernetes pod model. This involves creating pod CIDRs and privately accessible services that front-end the pods. You can then selectively expose some parts of your application to the external network by opening up the required ports to serve traffic. In this model, you are presented with a variety of networking options such as neutron overlay, flannel, calico, contiv etc. Another option is to use docker swarm with isolated docker networks created using the built-in overlay network driver. You could use a custom docker network driver plugin implemented as a remote-driver for LibNetwork, providing several additional features. Another approach is to use the capabilities provided by the OpenStack Magnum project. This talk will explore the variety of networking models available and demystify them.


* **Naveen Joy** *(Naveen Joy is a cloud computing architect at Cisco Systems with several years of OpenStack solutions development, integration and deployment experience. He has been a speaker at the past OpenStack conferences and his current focus is in the area of microservices, kubernetes, automation and networking. He has contributed code to the development and integration of OpenStack based cloud services for large customers. Naveen holds a master’s degree in Computer Science from the University of Southern California.)*

* **Rohit Agarwalla** *(Rohit Agarwalla currently works in Cisco's OpenStack team. He was one of the first OpenStack contributors from Cisco and has been involved in the OpenStack project since the Bexar release. He is currently active in a wide range of product development, customer and community efforts around OpenStack. Prior to this, Rohit developed and contributed to a variety of cloud computing related projects as part of Cisco's CTO office. Rohit holds a Masters degree in Computer Science from Cornell University.)*

Layer 3 Tunnel Support for Open vSwitch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Advanced OpenStack cloud networking use cases such as L3-VPN overlays or Service Function Chaining and the corresponding interwork with standard network equipment require SDN vSwitches to support an increasing number of tunneling encapsulations such as MPLS over GRE, VXLAN-GPE, Geneve, NSH, and others to carry any type of payload. Traditionally, the Open vSwitch (OVS) is the de-facto standard SDN vSwitch for OpenStack only supported L2 tunnels. Together with the OVS community we are enhancing OVS to support tunnels that can handle arbitrary payload types, including MPLS, IP or NSH.


* **Simon Horman** *(Simon has been working on free and open source software for most of his professional career, initially in operations and then as a developer.He enjoys working on network-related projects, and is interested in the way that they bring people together. He also has a keen interest in the pervasive power of embedded systems.Simon works as an independent consultant and is engaged by Netronome for the work covered by this presentation.)*

Routed (Calico) networking with ECMP, dual fabric planes and data/management separation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will present how the Calico networking driver for Neutron was used in a recent OpenStack deployment with interesting requirements for ECMP through dual fabric planes, and for separate management and project data access into VMs, with Neutron security groups controlling the data access and an independent policy for the management access.  


* **Neil Jerram** *(Neil has been hacking on free software since the early 1990s, with contributions including to Emacs, Guile, Lilypond, QtMoko, the GTA04 phone project, oFono, FSO, OpenStack, Dnsmasq, Linux and Dasher. He's also worked for 20 years for Metaswitch (previously Data Connection) in the world of networking protocols, and happily those two strands of experience are now converged in Project Calico, an open source implementation of simple and massively scalable data center networking.)*

* **Matt Rae** *(Matt Rae is a Cloud Consultant for Canonical)*

DVR:  Ready for Prime Time
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Neutron DVR feature was first introduced in Juno to address the performance bottleneck created by the centralized L3 service, identified in early public cloud deployments of OpenStack. Since then, the Neutron community has steadily increased its functionality, scalability, and performance. DVR is now widely deployed in production customer cloud environments. This session will provide an overview of DVR's current production use cases, high availability characteristics, and network performance benefits. Experiences from real customer deployments will be highlighted. In addition, we will be providing a status update on the latest upstream developments surrounding L3 and DVR. This includes optimizations to enable NS routing for fixed or dynamically routed IP traffic, support for multi-hypervisor deployments, and hardware L2 Gateway and bare metal support. We'll leave plenty of time for audience questions, so come prepared!


* **David Hawley** *(Dave is a product manager for HPE Helion OpenStack, responsible for supporting the development and delivery of Neutron and SDN-based cloud networking solutions for customers.  Dave has more than 20 years of experience in networking as both hardware design manager and PLM.  Prior to joining HP, he helped create the Ethernet switching portfolios at Juniper Networks and Extreme Networks.  Dave holds dual master's degrees in business from UC Berkeley and Columbia, and a bachelor's degree in EECS from Caltech.  He loves the expertise, energy, commitment of the OpenStack community, and is happy to contribute to its success.)*

* **Brian Haley** *(Brian Haley is a core contributor to OpenStack Neutron, primarily focused in the L3 and DVR areas, but has particular interests in both IPv6 and cloud security.  He has been working on OpenStack since 2011, first on Nova Networking and later on Neutron.  His background is in kernel networking, both UNIX and Linux, mainly focusing on performance, scalability and IPv6 features over the past 20 years.  Brian currently works in HPE Cloud, developing and supporting HPE Helion OpenStack.)*

Make Network Great Again: Third Party SDN for Everyone and OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Networking has been rather dull since the 1980s, it has been limited by old technological decisions that have made it difficult to scale in terms of addressing fundamental changes in Cloud Computing models. Layer 2 and lack of Progammability along with semi automated, and manual configuration simply cannot make the Network perform the tasks that we require in 2016. OpenStack is now mainstream, and many Availability Zones sit along with new emerging deployments of Containers, Public Cloud Services and Progammable Restful APIs that abstract much of the Network in code. This session will detail how the Network can be made great again by leveraging a single API and framework to cater to everyones needs, across Silos and beyond the OpenStack Neutron services - making the network great agaiin for everyone.


* **Andreas Roeder** *(Andreas is a technical business developer in Europe, and is experienced in Networking, CCIE, and also SDN and OpenStack deployments and all around Integration with OpenStack Neutron. Also keen  into Software Development.)*

* **Christoph Torlinsky** *(Interested in all things OpenStack, Learning, Brainstorming, Contributing, all the usual...based in London, originally from Berlin, and lived and worked in San Francisco for a bit. I'm engaged across Europe for Nuage Networks, Presenting, Developing and generally spreading the word about Software Definition, all around Cloud Computing and also OpenStack itself. I travel alot, and also do Meetups locally in London and Germany, we probably have bumped into each other one or an OpenStack Day. Please see my LinkedIN for more details, been working on and using OpenStack in the field since 2013, before it became 'commercially' available from Linux vendors.   c)*

Leveraging eXpress Data Path (XDP) for Programmable, High Performance Data Path in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

eXpress Data Path, or XDP is an open source initiative driving high performance, programmable network data path in the kernel as part of the IO Visor Project. XDP is CPU and hardware agnostic with support for any higher layer applications that OpenStack operators may deploy.  Use cases include pre-stack processing such as filtering for mitigating DDoS attacks, packet forwarding and load balancing, flow sampling, monitoring and analytics just to name a few examples. XDP follows the principle of "write once, run anywhere", which enables XDP programs to run in Linux and other OS, with or without hardware offload, and support user space applications. Join this session to learn about this new initiative with contributions from companies such as Facebook, Huawei, PLUMgrid, Cisco, and more.


* **Brenden Blanco** *(Brenden is part of PLUMgrid's tecnical team. He is involved in several open source products including IO Visor, he works on various areas of cloud networking assocaited with security, multi-tenancy and high avalability.)*

* **Yunsong Lu** *(As the Chief Architect of Networking & Virtualization Group, I'm responsible for technical direction of virtual networking and I have been driving corporate-level projects by leading a seasoned cross-culture engineering team I built from scratch. Since 2011, my team has designed and delivered crucial virtual networking technologies, for instance Elastic Virtual Switch(EVS) and S-DNA(Software-Defined Network Acceleration) framework, which have been the fundamental and differentiating building blocks of Huawei's Cloud, SDN, and NFV products and solutions. One of recent projects is Container-based Application Networking which will deliver high performance, application-to-application network monitoring, and network SLA.)*

Advanced Network Services in OpenStack: Load-Balancing as a Service (LBaaS)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This beginner session is about advanced network services in OpenStack, particularly focusing on Load Balancing as a Service (LBaaS). In physical world of enterprise data centers, load balancers have evolved over time to do more than simple spraying of connections to a set of backend servers. We will delve into some of the core requirements including session persistence, SSL termination, and rule based switching. We will present the evolution of OpenStack LBaaS APIs as they incorporated these requirements. On the implementation side, we compare and contrast the most common architectures of LBaaS deployments: (i) process-based (reference architecture), (ii) appliance-based, and (iii) service-VM-based (Octavia's architecture). We will focus on service-VM architecture's elastic scalability and high availability. We will also share learnings from production deployments of elastic LBaaS in large-scale private and public OpenStack clouds.


* **Praveen Yalagandula** *(Praveen Yalagandula is the OpenStack Architect at Avi Networks, responsible for designing and developing the integration of Avi Networks’ Cloud Application Delivery Platform with OpenStack infrastructure services. At Avi, Praveen also leads the application performance visibility component of the Avi’s solution and has developed a scalable and distributed log analytics system. Prior to Avi, Praveen was a Principal Scientist at HP Labs in Palo Alto, where he spent 8 years exploring several aspects of data center networks, software defined networking, and large-scale distributed systems. Praveen received his Ph.D. in Computer Science from the University of Texas at Austin in 2005. He is currently a senior member of IEEE and ACM.)*

Performance Analysis of Openstack Infrastructure using Collectd and Grafana
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Understanding the performance of a cloud is a challenging task. That too with complex clouds like openstack, running myriad number of processes across a cluster of systems, is more complicated. In such situation, understanding the performance of each system, storage and network of openstack while optimizing them together would be a great option. A single user friendly customizable dashboard showing all the metrics would be very enticing for a cloud architect/operator. Extracting every bit of performance from the openstack cloud makes a lot of sense before any system upgrades are initiated. In this presentation and demo we focus on evaluating the performance of OpenStack infrastructure using open source tools like collectd and Grafana on a Dell cloud test-bed. Collectd and Grafana can be considered as the Swiss army knives of monitoring tools. Session aims to interactively explore the dashboard and the performance metrics produced by the openstack infrastructure using these tools.


* **Surya Prabhakar Naredla** *(Surya Prabhakar Naredla is a Principal software Engineer in Dell Enterprise solutions group, Ireland. He has over 16 years of experience in the IT industry working on Opensource. The first 9 years of his experience was spent as a developer on the Linux operating system and since 2011 he was working on Openstack (Bexar). He has done numerous presentations on openstack and evangelized it. His current work involves in performance and bottleneck analysis of openstack.)*

OpenStack Operators - Compute and OVS Debugging: Finding the right tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack in Production is now mainstream, with 60%+ adoption of OVS (openvswitch) as the de rigueur solution for Clouds running Neutron and Network services (Provider Networks), we have now a higher demand for actually mantaining the virtual switch and Linux stack in proper fashion. It's clear that Operators need the right tooling to isolate and troubleshoot issues, such as flows between Nova Compute Nodes and VMs, finding tap interfaces and virutal etherports and also simply being able to debug information and find relevant material in the community. The challenge is that the Linux Networking stack is complicated and tooling varies from simple command line (tcpdump)to more sophisticated projects such as SkyDive / PlotNetCfg and a myriad of third party SDN tooling. This session will be a refresher on what is out there and what can make life easier for operators and sharing the tool with the #openstack-operators and sharing on https://github.com/osops. 


* **Christoph Torlinsky** *(Interested in all things OpenStack, Learning, Brainstorming, Contributing, all the usual...based in London, originally from Berlin, and lived and worked in San Francisco for a bit. I'm engaged across Europe for Nuage Networks, Presenting, Developing and generally spreading the word about Software Definition, all around Cloud Computing and also OpenStack itself. I travel alot, and also do Meetups locally in London and Germany, we probably have bumped into each other one or an OpenStack Day. Please see my LinkedIN for more details, been working on and using OpenStack in the field since 2013, before it became 'commercially' available from Linux vendors.   c)*

War Story: How we built a scalable and reliable Neutron driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron’s northbound API can be integrated with networking backends such as SDN controllers via either monolithic core plugins or ML2 drivers. Each option provides a well defined interface, but how these integrations interact with their respective backends varies, sometimes significantly, trying to solve a common set of well known challenges: Reliability Scalability Availability State synchronization and consistency For several releases, Cisco has provided an ML2 mechanism driver integrating Neutron with our ACI SDN controller. After many successful customer deployments and lessons learned regarding its limitations, we decided to revisit our driver’s architecture. We want to share with the developer and operator communities our story of how we designed a Neutron driver that tackles the above problems through the use of asynchronous calls and eventual consistency. We will describe the options considered, the choices made, the results achieved, and some potential Neutron enhancements.


* **Ivar Lazzaro** *(I am a software engineer driven by genuine passion and curiosity for computer science. I have mostly been focusing on building fast and scalable distributed systems, in particular for network centric environments. Dived into Openstack as part of my Master thesis, my interest in it kept growing over time. I'm designer, developer, and maintainer of multiple Neutron's plugins, ML2 drivers and CI systems. I've also recently started my contribution as a core developer of the Group Bases Policy project in Openstack.)*

* **Robert Kukura** *(I am a Principal Engineer in Cisco's Noiro Networks group, working on OpenStack Neutron and other open source projects. My current focuses are Neutron's ML2 core plugin and Group Based Policy. I've contributed to OpenStack since joining Red Hat in late 2011, and have served as a core reviewer in the Neutron project. Throughout my career developing distributed systems, ranging from digitial audio processors to large defense systems, I've been a strong advocate of and contibutor to open standards and open source.)*

* **Amit Bose** *(Amit is a Techinical Leader at Cisco Systems and contributes primarily to the Group Based Policy project and Neutron.)*

Resolving the SR-IOV conundrum for NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

If you deploy an openstack based NFV solution, you have to make a fundamental trade-off right off the bat -- you can either use a hypervisor/virtual switch based networking for VMs or you can use SR-IOV. A virtual switch based solution gives us all the “SDx goodness” that openstack promises (like self service, network virtualization, advanced traffic steering, distributed firewall/security, policy enforcement, etc) at the cost of additional processing on the hypervisor, OR you can use an SR-IOV based VM network that can achieve faster network function performance by doing a direct DMA to/from the NIC to the VM at the cost of sacrificing that “SDx goodness”. In this talk, we will show how this issue can be resolved cleanly by a modern SDN fabric. By moving the user intent to a policy framework that can be enforced directly in hardware, we can allow the hypervisors to give direct DMA access for network traffic without losing any flexibility provided by the SDx APIs/interfaces.  


* **Mandeep Dhami** *(Mandeep Dhami is a Principal Software Engineer @ Cisco where he currently works on open source projects like Openstack, Opendaylight and Openvswitch. He has dabbled in building networking and security solutions for service provider and datacenters for most of his career. An early pioneer in network virtualization, he led the team that developed the first network services virtualization platform while at Inkra networks. And most recently, before joining Cisco, he was leading the team that built BVS (Big Virtual Switch) at Big Switch Networks.)*

* **Mike Cohen** *(Mike Cohen is Director of Product Management at Cisco Systems.  Mike began his career as an early engineer on VMware's hypervisor team and subsequently worked in infrastructure product management on Google and Big Switch Networks.  Mike holds a BSE in Electrical Engineering from Princeton University and an MBA from Harvard Business School.)*

* **Amit Bose** *(Amit is a Techinical Leader at Cisco Systems and contributes primarily to the Group Based Policy project and Neutron.)*

Openstack Networking with Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The intention of the presentation is to give a birds-eye view of networking in Openstackbased on the "default" setup with Neutron/Openvswitch. It's mostly aimed at peoplefamiliar with network concepts, but not necessarily with deep Openstack experience.Concepts that will be talked about include: General Neutron design ML2 Openvswitch Overlay technologies like VXLAN and GRE Provider networks and Tenant networks Openstack routers, networks and subnets Security Groups Network Partitioning Network namespaces Floating IPs / NAT / PAT Address scopes and Subnet pools Neutron as a BGP speaker Distributed Virtual Routers HA routers L2 and L3 agents Plugins like for example VPNaaS and LBaaS DHCP and Metadata services


* **Magnus Bergman** *(Magnus Bergman has been working with Unix, Networking and Security for around 20 years. Currently he is a tech geek at City Network Hosting designing and implementing new stuff mostly related to Openstack and core networking.)*

Cliff's Notes for adding flavor support to L3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud operators deploying OpenStack today can only select a single monolithic L3 plugin. This presents a problem when attempting to virtualize infrastructure across multiple networking platforms: the cloud operator must either choose a plugin that supports a reference implementation (e.g. namespace routers, DVR, etc), or one that supports a vendor's implementation. A proposal to use the flavor-db framework to allow multiple drivers for L3 is a step towards addressing this limitation. This talk describes a framework in use for several releases with some of the same concepts proposed by the flavor-db L3 framework. It explains how the architecture enables multiple driver implementations, highlights some of the challenges and solutions for maintaining the L3 abstraction across a heterogeneous infrastructure, and demonstrates how benefits such as improved support and scaling can be realized by such a framework.


* **Thomas Bachman** *(Thomas Bachman is a Technical Lead at Cisco Systems, Inc., and works in their Noiro Networks group implementing Policy in the Open Source domain. He is currently working on supporting policy in OpenStack across multi-hypervisor environments, and is a also committer on the OpenDaylight Group Based Policy project. Thomas has over 20 years of experience developing software, 15 of it specifically in networking and communications. He has worked for Juniper Networks and several startups in the Wireless and Cable access markets, and previously architected and developed high speed communications solutions for COTS FPGA boards and systems. Thomas holds a B.S.E.E. from the University of Washington.)*

* **Kent Wu** *(Kent Wu is a Technical Lead at Cisco Systems, Inc., and works in their Noiro Networks group implementing Policy in the Open Source domain. He is currently working on supporting policy in OpenStack across multi-hypervisor environments. Kent has over 15 years of experience developing software, mainly in security and networking area. He has worked for Symantec, TrendMicro, BlueCoat and a startup in the security field. Kent holds a Master degree of Computer Science from National Taiwan University.)*

* **Robert Kukura** *(I am a Principal Engineer in Cisco's Noiro Networks group, working on OpenStack Neutron and other open source projects. My current focuses are Neutron's ML2 core plugin and Group Based Policy. I've contributed to OpenStack since joining Red Hat in late 2011, and have served as a core reviewer in the Neutron project. Throughout my career developing distributed systems, ranging from digitial audio processors to large defense systems, I've been a strong advocate of and contibutor to open standards and open source.)*

Security group performance improvement with ipset for multi-region environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation explains security group in multi-region environment: why it is needed, what is a problem, and how resolve it.'Region' is one of methods to separate OpenStack environment for redundancy. Each region is independent OpenStack environment except keystone. To use multi-region environment for backup or disaster recovery, VM instances in each region need to communicate each other to share their data. Therefore security group to allow the communication between regions have to be set up.However there is a critical performance problem when setting up security group across region, because to allow connection between regions, we have to add rules using remote_ip_prefix and specify IP address of each instances one by one. The number of iptable rules are increased and it causes performance degradation of network.To resolve this problem, I propose to optimize iptable rules using ipset in L2 agent so that a bunch of iptable rules can coalesce into one group.


* **Takao Indoh** *(Takao Indoh has been working for support service of Linux system in Fujitsu since 2001, especially working for crash dump for mission critical server, and has also committed several open source communities relevant to crash dump framework, LKCD(Linux Kernel Crash Dump), diskdump, kdump, and so on. Also working for improving network feature like Open vSwitch, DPDK, etc.  )*

Verizon Cloud and Contrail Networking - Connecting OpenStack Clouds to legacy networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How do you natively connect your OpenStack cloud virtual-networks to the various legacy networks and services quickly, easily and at scale?


* **Christopher Young** *(Christopher Young is a Sr Consulting Engineer with Juniper Networks currently working with Service Provider customers to build OpenStack virtualized Data Centers. Primarily focused on levaraging IP Fabrics and Network Virtualization Overlays in order to internetwork high performance VNFs with legacy physical external service provider networks.)*

Fast and Flexible: Accelerated P4/C and Open vSwitch Datapaths for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Virtual switches are typically deployed in OpenStack managed cloud datacenter servers to act as overlay on/off-ramps, implement micro-segmentation (security groups) or otherwise process and forward packets. These virtual switches can implement the behavior required by an existing standard (for example Open vSwitch implements OpenFlow compliant switching), or implement the semantics directly expressed using a program (potentially written in a domain specific language like P4). A hybrid approach is also possible, whereby portions of the behavior conform to a standard, and other portions are implemented in modules expressed in P4 or C. This presentation compares these approaches, considering aspects like the expressiveness and performance of the resulting datapath as well how these datapath variants can be integrated into OpenStack. It furthermore considers the additional implications of accelerating the datapaths using SmartNICs, again considering the implications for OpenStack.


* **Johann Tönsing** *(Johann is a recognized industry expert in SDN, Linux-based networking technologies, network virtualization, security, and NFV. Johann has been an active contributing member and has been nominated to leadership roles in multiple standards bodies related to SDN and NFV. As Netronome’s Chief Architect, Johann leads all aspects of Netronome’s product design and development, with an emphasis on advanced and open server-based networking technologies. He has a Masters of Engineering degree in Electronics and holds several patents in the networking, security and virtualization fields.)*

* **Ben Mack-Crane** *(Ben Mack-Crane is a Principal Architect at Corsa Technology focusing on high performance applications of pure SDN using open protocols. Ben has experience with automated control across a broad spectrum of network technologies, from optical to packet and L0 through L7. He has been involved in behavioral specification and modeling of a wide variety of network elements over his career including packet switches and routers, transport systems, cable telephony, flexible multiplexers, and telephone switches. His current focus is on SDN and virtualization. Ben has been instrumental in numerous standards development efforts, including work in the ONF, MEF, IEEE, ITU, IETF, OIF, and ATIS.)*

Enterprise Cloud Networking By Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Neutron provides multiple drivers and architectures to meet all Operators requirements. The presentation is to give explanation of best practice of Neutron ML2, OpenvSwitch and DVR for private cloud．


* **Wilence Yao** *(Upstream Developer in OpenStack community, focus on Cloud Networking)*

Configure, Deploy and Troubleshoot DPDK Port in a devstack environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Come to this session to learn how to install & configure Data Plane Development Kit (DPDK), a powerfull set of highly optimized user space libraries and drivers that enable users to consolidate control and data plane platforms and execute efficient data path packet processing.


* **Ashish Gupta** *(I'm working with Openstack more than 4 years. Now I'm Senior Software developer at Hewlett Packard. My main interest is in Cloud computing especially OpenStack .Contributed my work in neutron related project such as vpnaas,lbaas,fwaas , networking-l2gw ,automation (tempest), ironic baremetal networking provisioning mech driver implementaion,monasca-agent ovs/libvirt plugin  implementation and testing.Currently involve in automating monasca-agent ovs/libvirt plugin.)*

* **Alok Maurya** *(Working as  Sr. Software engineer at  HPE . I and  responsible  for  performing scalability  testing of  HPE Helion  products . I have  been actively involved  in  contributing in upstream  in  different  projects networking-l2gw , monsaca , tempest .)*

* **Chandrasekaran Natarajan** *(Working  HPE .  I am  responsible  for  testing  HPE  Helion  openstack  products .Actively involved  in  contributing in upstream  in  different  projects ovsvapp , hyper-V .)*

The battle of the switches: Neutron with Open vSwitch versus Linux Bridge
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open vSwitch and Linux Bridge are two competing open source backends for OpenStack Neutron. While OVS is popular among both developers and users as shown in the latest OpenStack User Survey report, some operators have prior knowledge of Linux Bridge and are looking for a simple solution. In this session we would like to explore the two backends and try to address the key question: Which one’s for you? We will try to make it as objective as possible and stick to the facts - Which use cases are covered, where do features end up, who performs better, how big are the Neutron and Linux communities behind them, how does CI and test coverage look like, does the community push for a default via documentation and more. Objective facts aside, after years of direct contact with Red Hat’s customers and the OpenStack Neutron development community, we’ve formed a strong opinion and we won’t be afraid to share it.


* **Assaf Muller** *(Assaf is managing the OpenStack Network engineering team at Red Hat. Neutron core team member, driver and responsible for the project’s testing. Assaf works out of Brooklyn, New York. Formally and formerly Cisco certified CCNA, CCNP instructor at the Israeli Institute of Technology and Communications. Graduated with a BA in Computer Science on a Business Entrepreneurship scholarship from the Interdisciplinary Center in 2013. assafmuller.com)*

* **Nir Yechiel** *(Nir Yechiel is a Product Manager at Red Hat concentrating on OpenStack Neutron and related networking technologies for Red Hat OpenStack Platform.  )*

The good, bad, and ugly about Neutron Distributed Virtual Routers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron networking has traditionally offered limited scalability by routing all network requests through a dedicated network node.  With the arrival of DVR capability as part of Neutron, the ability to scale Openstack has now changed.  Out of the box, Neutron offers DVR as another option to scale Neutron networking while deploying Open vSwitch.   In our presentation, we discuss the change in architectural designs, how people can benefit from the change in Neutron, and a walk-through on how we can enable components in your OpenStack cloud to utilize these features without buying additional hardware.  


* **Richard Wong** *(Senior systems engineer with 20 years technology experience on VMware, OpenStack, Amazon AWS, Rackspace Cloud, MS Azure, Cisco LANs, SAN engineering, MS Office365, MS Exchange365, RHEL, CentOS, Ubuntu, Oracle, MySQL, MS SQL Server, shell scripting)*

Building Multi-Cluster LBaaS in Yahoo! JAPAN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our private cloud came to be composed of a number of OpenStack cluster, It is also often one of the web service is distributed across multiple OpenStack. LBaaS is strongly associated with its own OpenStack, can not manage the instance of other OpenStack cluster in LBaaS. You can add a member in OpenStack in the IP address, but the data of LBaaS had become apart. Therefore, we built dedicated OpenStack for LBaaS and aggregated all the LBaaS data for the OpenStack clusters. And transparently requests to Neutron of LBaaS OpenStack from Compute OpenStack. By this configuration, each of the Compute OpenStack will request to the dedicated LBaaS as if it's own Neutron. As a result, it is possible to aggregate the data for LBaaS to one OpenStack, it became easier operation.In this session, we will talk about the design and configuration of the new LBaaS used in Yahoo! JAPAN.


* **Akira KAMIO** *(Akira Kamio is a OpenStack Engineer in Yahoo! JAPAN's Infrastructure team. Yahoo! JAPAN provides largest portal site in Japan. He mainly development of openstack-based private cloud in Yahoo! JAPAN.He likes server optimization, such as tuning the kernel and qemu/kvm. He has a particular interest in high performance hypervisor architectures.)*

* **YUUTA KINOSHITA** *(YUUTA KINOSHITA is Engineer in Yahoo! JAPAN's Infrastructure team.)*

Real-World Experiences with Virtual Edge Routers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Participants attending this session will engage in discussion with industry experts who have real-world experience evaluating, deploying and maintaining virtual routers.  These experts will proivide real world insight into market requirment driving adoption, common use cases, interoperability findings, challenges, technical evolution and business benefits associated with virtual routing in service provider networks. 


* **Carsten Rossenhövel ** *(Carsten Rossenhoevel is Managing Director of EANTC AG (European Advanced Networking Test Center), an independent test lab in Berlin, Germany. EANTC offers vendor-neutral network testservices for network equipment manufacturers,service providers, and enterprises. In this role, Carsten is responsible for EANTC's business development and marketing. Carsten has over 20 years of experience in telecommunication networks and testing. His technical areas of expertise include Multi Protocol Label Switching (MPLS), Carrier Ethernet, Triple Play, and Mobile Backhaul. Carsten is one of the co-founders of EANTC AG. Before joining EANTC, he studied computer science at the Technical University of Berlin and worked as a software engineer, as well as consultant in the financial services and media sector.)*

* **Paul Obsitnik** *(Paul Obsitnik is Vice President of Service Provider and Enterprise Marketing for Juniper Networks, responsible for the marketing of Juniper’s portfolio of high performance routing, switching, and data center fabric products to Service Providers globally. Paul's team is responsible for marketing strategy, product marketing, go-to-market planning, and competitive analysis worldwide for the Service Provider segment. Obsitnik has extensive experience in marketing, sales and business development positions with a proven track record in creating technology markets. He has served in senior marketing and sales management positions at several companies including BridgeWave Communications, ONI Systems, NorthPoint Communications and 3Com. Paul holds a Bachelor of Science with Honors in Electrical Engineering from the United States Naval Academy and a Master of Business Administration from the Harvard Graduate School of Business. Obsitnik is based in Sunnyvale, California.)*

Neutron Power Vacuum
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalability issues and a lack of features such as NFV support in Neutron has opened the field to many alternative Neutron plugin solutions. Many of these plugin alternatives are SDN solutions, and unlike many Openstack components, there are no clear favorites. Knowing which solutions best fit your environment can be difficult. This talk will give an generalized discussion of the SDN options and then provide some details on a representative set of solutions.


* **Todd Bowman** *(Todd Bowman is currently a Openstack Trainer at Mirantis specializing in Neutron and SDN solutions. In the recent past he has worked on SDN Ethernet solutions in High Performance Computing and worked with other centralized control plane technologies. He has spent 20+ years in the networking and HPC field and was a Network Engineering Team Leader for a large enterprise.)*

VXLAN and BGP EVOLVE IN OPENSTACK
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Why people curious and community take time in bgp? How to implement a high efficiency networking in OpenStack? How to achieve high availability and reduce MTTR & MTBR? You will get all these thing from presentation. Agenda: OVS VXLAN: Flood&Learn; BaGPipe: EVPN implemented by software; DVR: Neutron as the control plane; MP BGP EVPN: Industry VXLAN control plane; Networking-bgpvpn: DVR with BGP, Routed Network; BGP-EVPN-Advertisement: Bring DirectConnect to OpenStack?  


* **Wei Wang** *(Wei has worked as a sdn architect and networking team lead for 2 years at UnitedStsack, he started his contribution to OpenStack from 2013 and spends most of his time hacking on network (Neutron, network of Manila, dnsmasq, Linux networking, networkrking-bgp, etc.).He now currently based in Beijing where works for UnitedStack. Wei is also an actively open-source contributor, made contributions to buildbot and midonet. His blog is http://mytrix.me, where he wrote many articles about network, OpenStack Neutron, python, prolog and matlab. He lead a column which written by UnitedStack networking team, talk about openstack networking, neutron progress, ovn, dragonflow, fd.io, ovs, opendaylight and any other opensource networking project. http://bit.ly/29TIKIj)*

* **Zhi Chang** *(Zhi has worked as a sdn engineer for years at UnitedStsack, he started his contribution to OpenStack from 2013 and spends most of his time hacking on network (Neutron, Horizon, dnsmasq, Linux networking, etc.).He now currently based in Beijing where works for UnitedStack.)*

Using Horizon & ML2 to Simplify TOR Switch Configuration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The usual reason for writing an ML2 driver is to automate configuration of physical switches. But for Lenovo’s typical OpenStack customers, improving ease-of-use is more important. Smaller-scale deployments with inexperienced operators are commonplace in our market. We will explain how we implemented two functions with big ease-of-use benefits: Mapping TOR switch ports to VMs inside Horizon; and automatic VLAN to VxLAN remapping


* **Yuan Li** *(7+ years experience in Networking product - Master the design and development of networking functionality- Solid experience with ASIC/SDK.- Familiar with Embedded System design and development)*

* **None None** *(None)*

Providing Network Gateway Services in L2 VPN based Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our network for development purpose provides L2 VPN among branch offices. Each division/team connects the Internet through their own routers, NAT and firewall devices. Costs of network hardware devices are expensive especially for small teams and usually, it takes a long time to purchasing hardware in corporations. To provide internet connectivity and NAT/FW functions in a fast and cost-effective way, we chose OpenStack to host virtual network instances. In this session, we will present the architecture of our deployment and lessons learned.      


* **Masaki Matsushita** *(Masaki Matsushita is a software enginner at NTT Communications.Masaki started contributing to OpenStack from Kilo release.He also contributes to Ruby as a committer mainly for performance improvement.He says, "I like Python too.")*

* **Chihiro Yokoyama** *(Chihiro Yokoyama is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*

* **Xiaojing Zhang** *(Xiaojing Zhang is a software engineer at NTT Communications.Xiaojing joined OpenStack community recently.)*

Network Policy Enforcement Based on Cloud Identifiers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session we will introduce current segmentation technologies, highlight their limitations and show what would be required to tackle these. Current segmentation technologies have not been designed to be used in highly scalable, dynamic and on-demand environments such as cloud deployments. Also, current segmentation technologies do not provide the means to classify and isolate traffic based on cloud entities. Networks rely on identification approaches (IPs, port numbers, etc.) to apply policies, define forwarding decision, etc. Without cloud provider, service and tenant visbility on the network layer it is impossible to enforce fine-grained policies. In this session we will highlight a novel approach that takles current limitations, introduces Cloud specific identifiers and enables a multitude of critical use-cases and applications. 


* **Sebastian Jeuk** *(Cloud Solution Test Architect at Cisco Systems, part-time PhD student at the University College in London, passionate about Networking, Cloud Computing, Photography and Judo. Black Belt in Judo. )*

Lessons learned enabling DPDK for an overlay-based SDN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

DPDK can offer many performance benefits, but inserting DPDK into an overlay-based SDN is non-trivial.Different SDN solutions have different constraints on integrations: design complexity, time, and cost restrictions are all part of the tradeoff matrix.Choices include selecting a proper adapting interface, and potentially using 3rd-party vendors, to address use cases where the open source DPDK integration is not sufficiently mature.We describe our experience integrating MidoNet with 6WIND, and show choices, tradeoffs, and final results obtained.Our goal is to extract and present generally applicable and useful lessons, for anyone planning a DPDK integration.


* **Miguel Ángel Herranz Trillo** *(Miguel Ángel Herranz is a software developer working at Midokura's as part of the core team that develop new features of their overlay-SDN solution, Midonet. He has collaborated in several integrations of the product with other technologies, like vSphere and DPDK. Previouly entering Midokura, he worked for several years at Ericsson R&D Madrid developing telco grade software for 3G mobile network nodes.  )*

Troubleshooting Network Issues in Docker Networking Environments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Advanced Session on troubleshooting network issues in containerized cloud deployments. Focusing on issues such as a borken DHCP service, packet drops and other relevant network issues. Highlighting the required steps to troubleshoot neutron and related networking services. The session is based around several examples to show how troubleshooting can be done within a Neutron Environment (containerized or not). For example, we plan to show how to troubleshoot a DHCP issue by going through the compute host OVS architecture showing the expected flow, what key points to look at and how to find (and resolve) the issue.  


* **Sebastian Jeuk** *(Cloud Solution Test Architect at Cisco Systems, part-time PhD student at the University College in London, passionate about Networking, Cloud Computing, Photography and Judo. Black Belt in Judo. )*

Deploying Group Based Policy to Secure Microservices Running in OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As microservices grow, traditional firewall rules based on network ACLs are no longer scalable and fall short of providing fine-grained enforcement. Group Based Policy (GBP) is a  flexible policy language that allows users to specify policy enforcement based on intent, independent of network infrastructure and IP addressing. Using micro-segmented virtual domains, administrators can define policies at a centralized location and use IO Visor technology for distributed enforcement. This provides infrastructure independent rules, template-based policy definitions, and scale-out policy enforcement for a solution that secures and scales with microservices.   The discussion will also cover using GBP for Cloud Foundry application spaces where microservices are deployed and need scalable, efficient security policies. 


* **Marcel Haerry** *(Marcel Haerry is leading the architecture of Swisscom's OpenStack based environments. With the goal of providing an elastic environment for modern platforms, such as PaaS based on CloudFoundry. Having both a system and software engineering background and years of participation within devops-minded community (e.g. Puppet), he is seeking for an automated and continuously integrated delivery of operational platforms.)*

OpenStack Networking SFC and L2GW service through OpenDaylight
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session speakers will mainly talk about the following OpenStack Services and how they are being implemented using the OpenDaylight Controller: OpenStack Service Function Chaining (networking-sfc) OpenStack L2 Gateway Service Speakers will talk about the architecture and high level design of the solution implemented in OpenDaylight to support the OpenStack SFC API and L2 Gateway APIs. Speakers will go through the details of all the component developed across the OpenStack (networking-odl) and OpenDaylight projects (neutron northbound, netvirt and OpenDaylight SFC project) to realize these services. They will talk about the NFV usecase of OpenStack SFC and dive into details of architecture of how OpenStack Tacker project is consuming OpenStack SFC APIs to realize Tacker VNF-FG API's. Speakers will also go through the details of L2 GW Usecase and discuss the architectural details of the service implementation using OpenStack networking-ODL and OpenDaylight.


* **Anil Vishnoi** *(Anil Vishnoi is a Principle Software Engineer at Brocade R&D, US. His research & development focus includes SDN, network virtualization, cloud and data center networks. Anil has been an active participant in OpenDaylight since inception and contributed to a number of projects and technologies including the OpenDaylight Controller, OpenFlow Plugin Project, OpenDaylight OVSDB project, load balancer sample applications,the MD-SAL based Statistics Manager module. For more details about his prior research in these domains please refer https://scholar.google.co.in/citations?user=Y0iwRTYAAAAJ&hl=en)*

* **Vishal Thapar** *(Vishal Thapar works as Tech Lead with Ericsson SDN Conroller project and currently contributing to VPNService and OVSDB HWTEP Projects in OpenDaylight. Vishal has over four years of experience in SDN/OpenFlow. Earlier, apart from designing high availability in the solutions developed for private clouds using OpenStack Neutron, he contributed in the OVS based firewall design. He was also involved in the development of switch software and high availability of an OpenFlow controller.)*

* **Vivekanandan Narasimhan** *(Vivek is working with OpenStack community from Havana and is an Active Contributor to Openstack Neutron He also spends his time on architecting solutions for Private and Public Clouds for HP Cloud customers.  Before involved in Openstack community, Vivek was involved in developing BYOD (Bring Your Own Device) solutions for Converged Network Infrastructures (Wired and Wireless). )*

Automatic Underlay Management in Rack scale Design
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Often, you need to create networks like VLANs while the cloud is deployed and functional. Instead of logging on to the switch CLI, manually creating them and adding to Openstack Neutron for allocation, you would like an automated SDI solution. In a Rack Scale Design pooled infrastructure management infrastructure, automated network creation via newly published network service APIs in Redfish, from the central controller, effectively showcases composition of networks and network services. With a programmable switch and management APIs to discover neighbors, we present a scalable framework to manage underlay networks.


* **Mrittika Ganguli** *(Mrittika is a Principal Engineer and Platform Software Architect in Cloud Platform Group, DCG – India and has 19 years of experience.  At Intel, Mrittika has worked on software systems design, development and architecture. Her work includes building the server system management software architecture for cloud and server hardware deployment for cloud in datacenters. She has been involved in Openstack projects within Intel since 2010. She was a co-creator and architect for a Openstack based product for SLO management Intel(R) SAA. She has 5 patents granted and 5 filed and multiple published papers. Workload charetcerization, orchestration in clouds and disaggregated Rack architectures are her current areas of work.)*

* **Alaa Yousif** *(Architect at DELL)*

* **Jeff Maynard** *(Cloud and Network engineer)*

Microservices vs Monoliths: How to make them communicate
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A lot of enterprises are now managing multiple stacks of VMs and Containers in their Datacenters. Openstack is typically used as the orchestration tool for the VMs, but on the Container side multiple orchestration tools now exist: Docker Swarm, Kubernetes, Mesos, and new ones every other day! The painful question is how do you provide a common networking framework for your containers and your VMs ? This talk is going to explore real deployment use-cases in which both VMs and Containers are involved, and how Networking was solved seamlessly as one single stack.


* **Bernard Van De Walle** *(q)*
