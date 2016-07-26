Telecom / NFV Operations
========================

Adapt or die: Architecting and deploying OpenStack NFV clouds in the Telecommunications Industry
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The telecommunications industry is rapidly changing with the adoption of emerging technologies. Network Function Virtualization (NFV) is a key driver of this change, providing efficiency, agility, and cost reduction. OpenStack has positioned itself in the telecommunications industry as the platform in which NFV workloads could be deployed in a secure, efficient, and reliable way. In this panel, we will discuss our experience architecting and deploying NFV clouds on OpenStack, including challenges that we found in the process, best practices, and architecture advice based on real-life deployments.


* **Chris Paquin** *(Senior Infrastructure and Cloud Consultant with over 15 years experience working with Unix, Linux, Virtualization, and Cloud. )*

* **Stuart McLean** *(None)*

* **Rob Fisher** *(Robert Fisher brings almost 20 years of Linux and UNIX experience to his team. He has built his experience working on teams such as Operations, to Information Security, and HPUX engineering.  For 7 years Rob worked on Linux Engineering and Enterprise Architecture teams.  During this time he automated the OS installation, reducing the amount of time it takes to build a Linux server.  He then worked to standardize all Linux systems in the enterprise.  Within 6 years the team that Rob was on, went from 600 installations of Linux to over 8000 physical and virtual servers.  During this period, Rob and 2 other Verizon employees were awarded a patent for the software that they had created for automating and standardizing the Linux build (Patent #20130262845).  In 2012 Rob was promoted to the lead over the Linux Architecture team where he was in charge of coordinating activities between multiple Verizon IT teams.  One of the large requirements that was given to Rob was training.  A bi-weekly and sometimes weekly training call was run by Rob or he coordinated to bring in Vendors for special training sessions.  Other topics that Rob and his team continued to tackle were: automation of virtual builds in vCenter APIs, automated multipath configuration, automated configuration and standardization of Oracle RAC/GRID database and building a RedHat Satellite/Proxy network to improve the patch update process.  Rob and his team were also tasked with reviewing, testing and certifying new hardware and software to be used within the Verizon enterprise.  These reviews also included new application implementations that Verizon developers were looking at.  The new applications needed to be reviewed to determine what type of hardware or software configuration was required so that they were allowed to work inside the Verizon enterprise.  Some of the software that Rob and his team tested, certified and implemented are:   -       RedHat Gluster   -       RedHat Satellite 5   -       RedHat OpenStack Icehouse release   -       CISCO UCS hardware   -       Several generations of HP and Dell hardware   -       RedHat Enterprise Linux 7   -       Oracle RAC/GRID using ASM running on RedHat Enterprise Linux   -       RedHat clustering using rgmanager   -       HP Moonshot and CloudLine hardware   -       MongoDB and Jive running on RHEL on virtual servers   This is just a short list of all of the software and hardware that Rob has been an integral part of certifying inside of Verizon IT.   For the last year Rob has been working on a new team, who’s mandate is to certify and architect a NFV OpenStack deployment.  The team is currently using RedHat OSP with a Director deployment method.  Rob’s focus has been largely on integrating security standards into the undercloud and overcloud deployments.   Rob received an undergraduate bachelor’s degree of science in Chemical Engineering from the University of Toledo and a master’s degree of science in Computer Information Systems from the University of Phoenix satellite campus in Temple Terrace Florida. For the last five years Rob has also been one of the professors in the Information Systems and Technology college at the University of Phoenix satellite campus in Temple Terrace, where he teaches at least 2 classes each year.       )*

* **Jay Cromer** *(Jay is a Distinguished Member of Technical Staff at Verizon. )*

* **Julio Villarreal Pelegrino** *(Julio Villarreal Pelegrino is an RHCA with over 15 years of experience in Enterprise IT. Currently, he is a Sr. Cloud Architect in the Red Hat's Cloud Infrastructure Practice. In his role, Julio helps customers to architect and implement OpenSource cloud and virtualization solutions (e.g: OpenStack, Red Hat Enterprise Virtualization).Before joining Red Hat he worked for Oracle and Dell where he held different roles within the IT and Services organizations.)*

Requirements for Building a Virtualized Central Office
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The central office (CO) is ripe for virtualization. And there are many projects, both open source and commercial, that virtualize network functions, eliminating the need to install physical devices for such devices as access or edge routers, optical line termination equipment, and broadband gateways. But what is the role of the controller in a virtualized central office, and what are the necessary orchestration components to make it all work together? This session will discuss everything from the NFV underlay to the SDN controller and the VNF managers/orchestrators needed to build a next generation, virtualized CO. 


* **Azhar Sayeed** *(Azhar is currently at Red Hat Inc., as a Chief Architect driving their Service Provider Architectures and solutions with Openstack, SDN, NFV and DC orchestration. Azhar has more than 25 years of experience in the networking and communications industry that includes development, design, installation and management of complex networks involving multiple technologies and products. Prior to Red Hat, Azhar is a 17 year veteran of Cisco Systems Inc. His last responsibility there was a Sr. Director of Solutions Engineering. Azhar was responsible for developing System Architectures, developing and delivering Cloud based solutions. Azhar has also actively contributed to the industry adoption cutting edge technologies. He is an active participant and a contributor to industry forums and standards bodies. His interests are in the area of Cloud Architectures, Openstack, SDN, virtualization, Data Center Networking and Mobile Networks.  Azhar is the co-author of a book “MPLS and Next-Generation Networks: Foundations for NGN and Enterprise Virtualization” with Monique Morrow. Azhar has 9 patents in the space of Network protocols and several published papers.)*

* **Alan Sardella** *(None)*

AIOrchestra. NFV VIM through TOSCA
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AIOrchestra is an engine to process TOSCA DSL to real deployment process. AIOrchestra allows DevOps/Developers to write TOSCA templates to describe how they want to see their apps in clouds and the way how it would get into cloud. AIOrchestra is aimed to be more than just yet another orchestration solution on over-polluted market. This framework designed to be a ground for more complex solutions. So, why AIOrchestra and NFV mentioned in the same context? NFV in the nutshell is just a cloud infrastructure and software, so why do we treat it as totally different beast? Because NFV was a huge new open initiative and it allows to reconsider the way we use clouds and its networking operations on the regular bases. From its initial design AIOrchestra allows developers to build their platforms for further app delivery by using TOSCA and AIOrchestra engine capabilities, in this case NFV VIMs.  


* **Denys Makogon** *(Developer and starting software architect in cloud environments, founder of Project Invader open source organization, mainly focused on developing and designing platform and software as a service applications for OpenStack. He’s lead software developer in EPAM, concentrating on product development along with bringing well-designed and production ready integration with clouds environments, including vCloud Air and vSphere for Cloudify. He is a contributor to AIOrchestra, Aria TOSCA, toscaparser.)*

Characterizing Migration of Telco Services to Openstack NFVI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Telco services such as voice, messaging, data etc. are running on physical infrastructures serving millions of end user. Many provider are doing POC and planning migrations to NFVI using Openstack but there is no silver bullet. We have worked out migration steps by monitoring at least ten KPI’s (QoS, resiliency, availability, scalability, capacity, performance, automating Apps onboarding, Operationalization, legal and regulatory compliance, cost) whihc we discuss how to use them effectively; before, in-flight and after migration. In this session we will share our hands on experience, tools and methodology for hitless migration to virtual infrastructures environments.


* **Prakash suthar** *(Currently working with Cisco Systmes, Inc and based in Chicago, USA. SME for virtualized mobility solutions such as virtual packet core, policy, service chaining (IETF Network Services Header) using ETSI MANO NFVI framework. Currently designing solutions with hands on system integration work by using following technologies•    Hypervisor such VMware ESXi, Openstack KVM, Virtualbox etc.•    Open stack experience on all releases Havana to Kilos•    Open Network Operating System (ONOS) and SDN controller (OpenFlow and Open Daylight)•    Openstack installers such Mercury (Cisco), Packstack (Redhat) etc.•    Virtual Switch – OpenVswitch, VMware standard and distributed, NSX, Cisco Nexus 1000v•    Netsim and auto configuration tools - Mininet,  OpenConfig, Tail-F NCS (YANG, CONFD)I have expert level knowledge on IPv4/IPv6 routing protocols (RIP, EIGRP, OSPF, IS-IS, BGP), VPLS, Inter-AS MP-BGP, L3VPN, L2VPN, multicast technologies, internet peering, datacenter technologies (L4-L7), security and Datacenter interconnect technologies. I have very good knowledge in SDN and virtualized network configuration, troubleshooting etc. Hands-on experience in over 10 mobile networks - AT&T US and Mexico (SAEGW, virtual packet core and policy for connected car, GiLAN, Monetization Orchestration Gateway, mobile datacenters design, IPv6), Verizon Wireless (PGW, HSGW, Mobile Datacenter, IPv6), Sprint (SAEGW and IPv6 design for LTE deployment),  RIL (LTE design, IP/MPLS transport, VoWiFi and ePDG), MetroPCS (LTE, IPv6), KDDI Japan (VoLTE design and deployments) etc. I am also engaged for transformation of fixed Telco infrastructure to cloud based solution for optimizing cost and performance for many providers. I am leading 5G Packet Core Architecture and solution development at various industry forums such as ITU IMT-2020 focus group (http://www.itu.int/en/ITU-T/focusgroups/imt-2020/Pages/default.aspx), 3GPP and IEEE. Involved with POC for Information Centric Networking (ICN), network slicing, edge computing, control and user plane separations.)*

How to make OpenStack relevant for Mobile Networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has been the choice of virtualized infrastructure for hosting Virtualized Network Functions (VNFs). Networking abstractions supported in OpenStack Neutron (i.e., port, sub-net, net) and services such as Load Balancing as a Service (LBaaS), Firewall as a Service (FWaaS), etc. cover a broad range of enterprise use cases. Yet, these services and networking abstractions also fall short of addressing the needs of next generation mobile network architectures particularly in the context of providing different mobile network stacks and verticals to different tenants. Our talk will cover some of the 5G use cases such as connectionless services, edge cloud, context aware networking and provide a discussion around new networking abstractions such as programmable buffers, mobility management as a service, and measurement as a service.  


* **Ulas Kozat** *(Ulas Kozat is a senior member of technical staff at Huawei R&D in Santa Clara, CA. At Huawei, he leads several R&D and open source projects in the areas of Software Defined Mobile Networks and Network Function Virtualization. He is also the PTL of OPNFV Domino Project. Previously, he has worked as principal research scientist at Argela USA in Sunnyvale, CA and as principal research engineer at DOCOMO Innovations (formerly DOCOMO USA Labs) in Palo Alto, CA.  Ulas Kozat received his Ph.D. from the University of Maryland, College Park, USA; M.Sc. from the George Washington University, Washington DC, USA; and B.Sc. from the Bilkent University, Ankara, Turkey all in Electrical & Electronics/Computer Engineering.   Dr. Kozat has published extensively (https://sites.google.com/site/ulaskozat/home/publications) and holds several patents (https://sites.google.com/site/ulaskozat/home/patents) in the areas of network modeling; cross-layer optimization; and architecture, protocol, algorithm design. He is a co-receipient of the best paper awards in IEEE ICC-2011 and ACM VISA-2010 conferences. He has served in the organization and technical programming committees of various prestegious venues including IEEE NFV-SDN, IEEE Infocom, IEEE ICC, IEEE Globecom, IEEE PIMRC, ACM Mobicom, ACM Mobisys, ACM ATC. He is a senior member of IEEE.)*

* **Subramaniyam Pooni** *(As a principal Architect, Center for Software Excellance, working in the area of Software Defined Mobile Networking (SDMN) , spear heading R&D efforts and bringing thought leadership for building next generation mobile software architectures for mobility platforms (5G and beyond)  with focus on microservices, containers, IOT platforms, Mobile edge services etc.)*

* **Prakash Ramchandran** *(Prakash has 30+ years of Telco/IT experience with MSEE from IIT Bombay. He is an active OpenStack participant, and has been a veteran consultant on NFV/SDN in the areas of data center and network operators. The companies he has served for include before Futurewei Technologies, seven.com, coverity.com, AT&T Labs, AT&T Mobility, He was also part of Valley start-ups including Tekmobile and other IT /Internet Data Center ventures in late 90's and early 2000. He brought to table the experience building NFV PoCs using OpenStack eco system .Has been a regular attendee as wel speaker at OpenStack and OPNFV over last several years in Bay area as well globally in US, China & India.)*

NFV use case. Software-defined vRouter with AIOrchestra
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AIOrchestra is an engine to process TOSCA DSL to real deployment process. By use of modern python 3.5 technologies like coroutines with async/await syntax AIOrchestra allows DevOps/Developers to write TOSCA templates to describe how they want to see their apps in clouds and the way how it would get into cloud. AIOrchestra is aimed to be more than just yet another orchestration solution on over-polluted market. This framework designed to be a base ground for more complex solutions.   In NFV, the most widely spread use case is - virtual router. So, it does really matter how you get router into OpenStack, would it be Neutron plugin or would it be a NFV on top of OpenStack. The most flexible way to get vRouter into OpenStack is to use TOSCA as modelling language and AIOrchestra as tool to convert TOSCA into executable graph.


* **Denys Makogon** *(Developer and starting software architect in cloud environments, founder of Project Invader open source organization, mainly focused on developing and designing platform and software as a service applications for OpenStack. He’s lead software developer in EPAM, concentrating on product development along with bringing well-designed and production ready integration with clouds environments, including vCloud Air and vSphere for Cloudify. He is a contributor to AIOrchestra, Aria TOSCA, toscaparser.)*

Domino: Distributed Template-based Orchestration Service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Template based orchestration is used by multiple OpenStack projects including Heat, Tacker, & Senlin. Model based network programming and configuration are also heavily adopted by SDN controllers (e.g., ODL, ONOS). To be able to consume orchestration services in another domain, specific drivers need to be written with explicit knowledge about the north bound API as well as the template formats and domain specific features.  OPNFV project Domino is responsible for creating, translating, and distributing orchestration templates for Virtual Network Functions (VNFs) from a common network service descriptor. It is a critical indirection layer to solve the pain points of automatic capability and policy discovery as well as VNF placement. Our talk will cover the use cases and architectural design of Domino. We will also provide a demo to show Domino in action with distributed OpenStack sites running different orchestration engines such as Heat and Tacker.  


* **Ulas Kozat** *(Ulas Kozat is a senior member of technical staff at Huawei R&D in Santa Clara, CA. At Huawei, he leads several R&D and open source projects in the areas of Software Defined Mobile Networks and Network Function Virtualization. He is also the PTL of OPNFV Domino Project. Previously, he has worked as principal research scientist at Argela USA in Sunnyvale, CA and as principal research engineer at DOCOMO Innovations (formerly DOCOMO USA Labs) in Palo Alto, CA.  Ulas Kozat received his Ph.D. from the University of Maryland, College Park, USA; M.Sc. from the George Washington University, Washington DC, USA; and B.Sc. from the Bilkent University, Ankara, Turkey all in Electrical & Electronics/Computer Engineering.   Dr. Kozat has published extensively (https://sites.google.com/site/ulaskozat/home/publications) and holds several patents (https://sites.google.com/site/ulaskozat/home/patents) in the areas of network modeling; cross-layer optimization; and architecture, protocol, algorithm design. He is a co-receipient of the best paper awards in IEEE ICC-2011 and ACM VISA-2010 conferences. He has served in the organization and technical programming committees of various prestegious venues including IEEE NFV-SDN, IEEE Infocom, IEEE ICC, IEEE Globecom, IEEE PIMRC, ACM Mobicom, ACM Mobisys, ACM ATC. He is a senior member of IEEE.)*

* **Prakash Ramchandran** *(Prakash has 30+ years of Telco/IT experience with MSEE from IIT Bombay. He is an active OpenStack participant, and has been a veteran consultant on NFV/SDN in the areas of data center and network operators. The companies he has served for include before Futurewei Technologies, seven.com, coverity.com, AT&T Labs, AT&T Mobility, He was also part of Valley start-ups including Tekmobile and other IT /Internet Data Center ventures in late 90's and early 2000. He brought to table the experience building NFV PoCs using OpenStack eco system .Has been a regular attendee as wel speaker at OpenStack and OPNFV over last several years in Bay area as well globally in US, China & India.)*

Using OpenStack to enable VNFs in Wide Area Networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The MEF, with its 125+ service provider member community, is focused on enabling dynamic Third Network services for the digital economy and the hyper-connected world, providing businesses an on-demand, cloud-connected, secure, and assured experience. The MEF provides a practical evolution toward interconnected, orchestrated, and automated networks powered by LSO (Lifecycle Service Orchestration), SDN, and NFV implementations. The MEF has established a technical framework that includes architecture, information models, services, operational processes, LSO, open source implementations, and certification programs. This presentation will highlight how service providers can use OpenStack based solutions originally focused for use in data centers to rapidly deliver Network Functions as a Service (NFaaS) and service function chaining not only into their own Wide Area Networks but into the networks of their wholesale service connectivity suppliers using Lifecycle Service Orchestration (LSO).  


* **Pascal Menezes** *(Pascal serves as CTO and Advisory Director for MEF and is a former Principal at Microsoft Skype for Business Global Carrier Group.  Pascal is a proven technology thought leader, sales evangelist, product manager and seasoned IP architect with close to 30 years of experience in internetworking, next-generation information systems, and communication architectures.    As the founder of TSCM Technology he is focused on the building of cloud scale architectures and real-time media networks using Software Defined Networks (SDN), Network Function Virtualization (NFV) and Lifecycle Service Orchestration (LSO).   As one of the leading industry experts in Unified Communication (UC) and SDN he is a UCStrategies Expert, pioneer of Unified Communications (UC) and Software Defined Networks (SDN), Chair of UC SDN Task Group at International Multimedia Telecommunication Consortium (IMTC),  Vice-Chair of Open Network Foundation (ONF) NBI Working Group  and Co-Founder and former Vice-Chair of Wi-Fi Alliance Task Group Mobile Multimedia Over Wi-Fi.  Pascal has done five startups with multiple successes, has received numerous industry awards and has presented extensively in numerous events globally.  Pascal holds 4 patents with 25 additional patents pending and has co-authored many standards in the IETF, MEF, IMTC and Broadband Forum (MPLS).)*

Telco Accelerating Automated Maintenance Enhancements
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OPNFV Doctor and Promise projects requires enhancements to compute host maintenance. This, together with operators using OpenStack provided requirements on achieving better handling of the maintenance control feature in OpenStack. This presentation will give an overview on the use cases and requirements from the operators, what is already ongoing and what might be coming later on. While telecom is the initiator for this, required changes are highly useful to enterprise users also.


* **Tomi Juvonen** *(Highly experienced Telco world specialist since 1998. Designed and implemented tons of code, lead specific SW areas, kept trainings and communicated between different people how the wheel is or should be implemented. Currently working in OPNFV Doctor project and Openstack to have Telco industry a solid ground in cloud.)*

* **Ashiq Khan** *(Ashiq Khan is an Asst. Manager in NTT DOCOMO. He is an NFV Architect and presently involed in designing mobile core network for 5G and beyond. He is a TSC member in OPNFV, and the originator of the Doctor and Promise Projects. He received his PhD in Computer Sciences from the University of Tsukuba in 2015.)*

Real-Time KVM
~~~~~~~~~~~~~

**Abstract:**

Getting near real-time performance for VNF applications requires designing the application with timing requirements in mind and profiling its performance under realistic conditions. OpenStack has developed many functionalities that helps in this, such as CPU and PCI topology awareness and pinning the virtual machines to dedicated cores. The host networking stack, in turn, has been optimized with features, such as accelerated virtual switches and DPDK. One crucial piece of the NFV infrastructure that deserves attention is the performance of the hypervisor layer itself. In the case of the open source, standard kvm hypervisor, the OPNFV project kvm4nfv has been optimizing its latencies to meet carrier-grade requirements. This presentation gives an update of the kvm4nfv project and its recent achievements.  


* **Jiming Sun** *(Jiming Sun is currently an engineering manager in Intel's Open Source Technology Center. His team is currently involved in OPNFV, Docker, and Container projects. Jiming has 19 granted patents in US, and has published a book, "Embedded Firmware Solutions" in 2015. Throughout his career, he worked on power management firmware and software for CPU, Graphics, and different IOT devices, and grandfathered several firmware solutions to help silicon vendors to wrap their silicon initialization code to shorten the time-to-market cycles for customers. He spent a lot of non-working hours in coaching junior basketball teams, chaperoning school activities, and teaching youth Sunday School in his church. Jiming currently lives in the Bay Area of sunny California.)*

* **Tapio Tallgren** *(will be added)*

* **Yunhong Jiang** *(Yunhong has been working on virtualization and cloud computing for a long time. He began working on virtualization since 2004. On 2012~2015, he worked on openstack Nova project. Now he is focus on OPNFV KVM4NFV project.)*

The Implementation Synopsis of Gluon Core
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV brings new networking use cases in the L3 domain, for example, MPLS and L3VPN. Those new use cases need new networking APIs that are increasingly unlike Neutron, and need to be quickly developed and deployed in order to accelerate time-to-market and improve business agility. In addition, NFV requires the flexibility to use multiple networking back-ends in OpenStack, and to use multiple APIs and back-ends simultaneously. Gluon is a Model-Driven, Extensible Framework of NFV Networking Services that enable Telecom Service Providers to provide its customers with new NFV use cases on-demand. Gluon uses a model-driven approach to generate APIs from a YAML file which models the NFV Networking Service. Applications use those APIs to provide the new service. Thus, Gluon helps Telecom Service Providers accelerate the time-to-market and achieve business agility in NFV domain. This presentation gives an overview of the design and implementation of Gluon.


* **Bin Hu** *(Bin Hu is an innovation thought-leader and instrumental in diverse technology domains ranging from mobile Internet and web platform to network virtualization, SDN and cloud computing. He currently focuses on implementing AT&T's open source strategy in network virtualization, primarily through active participation in OPNFV. Bin is the convener of OPNFV's technical community, driving the cross-project collaboration of OPNFV community, including the cross-project topics such as Intent and common CI tooling, consensus of OPNFV projects from ideation and initiation (e.g. project proposals) to execution and deliverables (e.g. Blueprints) through weekly technical discussion. In addition, Bin Hu is the Project Lead of IPv6-enabled OPNFV project, and committer of some other projects such as ARM Band targeting to deploy OPNFV platform on ARM environment. He was the Winner of OPNFV 2015 Annual Award, and the recipient of OPNFV 2015 Q3 Collaboration Award. In addition, Bin was a recipient of OMA Contributor and Achievement Award for Outstanding Contribution in Content Delivery and Cloud Computing. Bin was also the Chairman of IEEE ComSoc SCV Chapter (2007 and 2009). Under his leadership, SCV Chapter won IEEE ComSoc Chapter Achievement Award of North America Region in 2009. Bin Hu’s previous speaking experience includes OPNFV Summit (2015), Open Networking Summit (2015), NFV World Congress (2015), OPNFV Session in OpenStack Summit (2015), OPNFV Hackfest (2015), OMA Messaging Workshop (2012), AppNation Conference (2011), SVIEF Conference (2011), SVC Wireless Conference (2011), SVC Wireless Mobile Apps Workshop (2011), RichComm (2010), and many others before 2010. Bin is the member of Program Committee of ONS 2016, ICSR 2016, OPNFV Summit 2015, and OPNFV Hackfest 2015.)*

* **Nikolas Hermanns** *(-)*

* **Thomas Hambleton** *(N/A)*

Modeling Edge Cloud Services using OpenStack "Meghdwar"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenSource efforts to bring Edge Cloud Services have run into archietecural issues as how to serve from Edge while the Smart Phones continue to be registered through Provider portal at the Core or IMS in 3GPP terms. The case in point is Cloudlet efforts through Nova and Advanced Neutron srevices through Service VM. The spekers here will share their experience as how all this will change in new proposed Module "Meghdwar" and how new architecture will help Model Cluster of VM, Application management from Core or Central cloud to serve via edge yet maintain low latency for end users.


* **Subramaniyam Pooni** *(As a principal Architect, Center for Software Excellance, working in the area of Software Defined Mobile Networking (SDMN) , spear heading R&D efforts and bringing thought leadership for building next generation mobile software architectures for mobility platforms (5G and beyond)  with focus on microservices, containers, IOT platforms, Mobile edge services etc.)*

* **Syed Moneeb Javed** *(Been in Telecommunications Industry for about 8 years. Was involved in Telecom network integration, design and managed services.   Currently working in Ericsson Cloud Design Team and helping with putting together Demo’s and PoC for various global engagements. Experience in CDN and Media Sreaming has got me into Edge Cloud Services and have started working with OpenStack community in Meghdwar and lokking to present the lessons learned as a joint comunity efrorts with colleagues from competing venodors.)*

Building a highly scalable fast forwarding application stack using Openstack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV and virtualized high performance applications, such as video processing, require a “fast data stack” solution that provides both carrier grade forwarding performance, scalability and open extensibility, along with functionality for realizing application policies and controlling a complex network topology. This session discusses how different components in OpenStack and OpenDaylight are being evolved to integrate with the new open source Vector Packet Processor (VPP) forwarder provided by the FD.io Linux Foundation project to build such a solution stack. Being an OPNFV project, FastDataStacks heavily leverages OPNFV’s continuous integration, deployment and test pipeline as well as the automated component install and test infrastructure.


* **Wojciech Dec** *(Wojciech Dec is Technical Leader in Cisco's Cloud Virtualization Group. His recent focus is on OpenDaylight and OpenStack. Wojciech holds the degrees of Master of Science in Data Communication Systems, an Bachelor (Hons.) in Electrical Engineering and is a Cisco Certified Internetworking Expert (CCIE). Frank)*

* **Frank Brockners** *(Frank Brockners is Distinguished Engineer in Cisco's Chief Technology and Architecture Office, driving software and architecture development for software defined devices. Frank holds a diploma degree in Electrical Engineering (Aachen University) and a PhD/Dr degree in Information Science (University of Cologne).)*

How to Lower TCO for Network Modernization
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the Key Challenges of Service Providers (SP) is Total Cost of Ownership for a new tech site/lab. Especially for PoC/Staging Labs where SP tests & integrates new products/solutions before buying/rolling out in production, they are costly (building, maintaining and operating) and they are mostly under utilized across the calendar year. In order to address temporary site/lab needs via Global Cloud SP offer amazingly low cost compute, storage solutions and they provide secure private channels for Operating, Administrating and Mainatining (OAM) of it. In this presentation we will show how easily be Openstack IaaS to be deployed over AWS and also real time show of cost of resources over AWS Billing System. This approach can be used as reference and improved for low funded Tier3s for network modernization and allows VNF vendors to offer true "pay as much as you use" model by using AWS statistics and Analytics Tools.


* **Fatih E. Nar** *(Hard Working, Passionate Technologist with Telco Services & Networking Background. Current Study & Working areas include: Cloud Computing (Openstack) , Virtualization (QEMU/KVM) & Containerization (LXD). Virtualized Enterprise Applications Deployment within Tier1/Tier2 IaaS Platforms, Handling IaaS inter-working issues with Blueprint Designs and Implementations. Past Experiences & Background: C & Java Development for Enterprise Applications, IP Unified Communication Services Design, OTT IP Streaming Multimedia Services Build, Smart Home Application Development and Delivery.)*

* **Michael Iatrou** *(TBD)*

* **Rogerio Rocha Santos** *(Telecom Cloud Solution Architect responsible for Telco VNF delivery.)*

Place your VNFs smartly with a smart network monitoring tool
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Orange is using Openstack in several contexts, from public cloud with Cloudwatt to private cloud distributed all around the world for NFV use cases. Thanks to those experiences, devops teams at Orange agree that better tools to troubleshoot networking are needed. From one deployment to another, we may not use the same SDN controller hence operation team can't rely on dedicated SDN analysers tools. With the emergence of container based VNF, having a unified tool that NFV operations teams can use in mixed environments to monitor, troubleshoot NFV deployments makes a lot of sense. For those purposes, a tool such as Skydive providing live network metrics looks appropriated. This could be helpful to orchestrator tools or even used by the Openstack scheduler to smartly run network constrained applications in geo distributed cloud environments. This kind of feature will soon be needed since ETSI NFV will allow VNF to specify network constraints on virtual links between VNF components.


* **Sylvain Afchain** *(Sylvain Afchain is a Principal Software Engineer at Redhat. He has 15 years of software development experience. He has been involved on Openstack since the Havana release. He worked mainly on Neutron and on Network projects.)*

* **mathieu rohon** *(Mathieu has been working in Orange Labs for 5 Years on Innovation for Business Services. He's working on Openstack Neutron since the Folsom release, and he leads the networking-bgpvpn project. He is also working close to Openstack deployment teams at Orange, for public, private or NFV oriented Clouds.)*

A Tour of the Open Source NFV Eco-System: Create, Integrate, Deploy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are a lot of open-source projects which deliver components of the NFV eco-system. The puzzle has many pieces like fd.io, IOvisor, OpenO, OSM, OpenDaylight, CNCF, CNI, Cloudfoundry, etc. – though they all center around OpenStack and OPNFV. This session is putting the different open source projects in perspective and shows how they all organize into a "big picture" – with a special spotlights on OpenStack as the cornerstone project as well as OPNFV as the system-level integration project which equally drives NFV-focused feature evolution and continuous system level composition and testing.


* **Frank Brockners** *(Frank Brockners is Distinguished Engineer in Cisco's Chief Technology and Architecture Office, driving software and architecture development for software defined devices. Frank holds a diploma degree in Electrical Engineering (Aachen University) and a PhD/Dr degree in Information Science (University of Cologne).)*

Empower your NFV Services through Service Function Chaining and SFC graphs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The first release of networking-sfc can already fulfill multiple use cases. For the second phase, the project team has been working on supporting more features and more use cases. One of them is the support for the NSH SFC Encapsulation mechanism as defined by the IETF SFC working group. This talk will go through: the changes that are needed in order to support NSH Encapsulation; the advanced features that NSH encapsulation enables; the challenges on chaining legacy non-NSH-aware Service Functions; how you can deploy OpenStack SFC with the NSH encapsulated data path with Open vSwitch; and how to achieve advanced use cases that SFC Encapsulation in general allows.


* **Cathy Zhang** *(Cathy is currently a principal architect/engineer working on Network Virtualization, Cloud service, and SDN technologies at Huawei Technology USA. Her expertise includes L2/L3 Networking, HA Infrastructure, Network Virtualization, SDN, and Cloud Computing. She is the author of the OpenStack Neutron Service Chain API and Data Model Specification and is currently leading the service chain project development in the OpenStack community. Besides OpenStack, Cathy is also an active contributor to the service chain work in IETF, Openflow, ETSI NFV, OPNFV organizations. She won the "Outstanding Technical Contributor" award from Open Network Foundation and is one of the authors of the Openflow L4-L7 Service Chaining Architecture and API specification. She is a contributor to the IETF Service Chain Data Plane Working Specification. She is also the project lead of the VNF Forwarding Graph project in the OPNFV community. Cathy has a Ph.D. degree in Computing Engineering and has multiple patents.)*

* **Igor Duarte Cardoso** *(As a Software Engineer at Intel, Igor is mostly focused on upstream OpenStack enablement of Service Function Chaining. As a former NFV researcher, he has experience with comparing solutions and proposing new and potentially better ways of doing technology, while keeping his work as standards-compliant as possible. Previous development experience under OpenStack essentially spans DevStack, Neutron and Group-Based Policy.)*

VPP: the ultimate NFV vSwitch (and more!)?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV support in OpenStack started in Kilo release with Enhanced Platform Awareness (EPA) support, optimizing OpenStack orchestration and use of modern server’s software and hardware. (e.g. Huge Pages, CPU pinning, NUMA Topology awareness, etc.). However, with limited performance vSwitch options, SR-IOV was used in many cases. So, the Telco VMs (VNFs) could have reached high packet processing performances / core, at the cost of hardware dependency and features flexibility and challenges to software control plane. Nowadays, Vector Packet Processing (VPP) technology, offers an interesting high performance I/O processing alternative for NFV. VPP also offers network features richness (yes, e.g. SFC with NSH is also included), flexibility, hardware independence and a 100% Open Source software vSwitch with open governance model, with an OpenStack,  OpenDayLight and containers integration in progress.


* **Franck Baudin** *(Franck Baudin is in responsible for the NFV technical strategy of  within Red Hat’s OpenStack product management team. He  currently focuses on providing high performance network connectivity to VNFs: SR-IOV, OVS-DPDK, VPP.   In his previous role within the Qosmos CTO team, Franck was responsible for technical Proof of Concepts (PoCs) and prototyping of emerging products, such as Service Function Chaining PoC in Telekom Malaysia lab and Qosmos L7 classification plugin. He also designed and led the implementation of DPI integration within DPDK based VNFs.   Previously, Franck was managing the engineering team at 6WIND, where he defined the outsourcing strategy and resource allocation between France and China. On the technical side, his responsibilities included the development of strategic projects in the areas of SDN, Open vSwitch, and Intel DPDK. Included in his responsibilities, he was also driving development of the 6WINDGate packet processing software, focusing on performance improvements and support for different types of CPU architectures: x86, Cavium, Broadcom, and Freescale. He also led the porting of 6WIND portfolio from FreeBSD to Linux.   Franck started his career as a Software Development Engineer at Thales Aerospace, working on projects such as the Dassault Rafale aircraft radar software. He holds a Master's degree in Engineering from French engineering school ENSEA.  )*

* **Uri Elzur** *(Uri Elzur is a director of SDN System Architecture with Intel’s Network Platforms Group. In this role, Uri is responsible for creating SDN and SDI long term vision, technical strategy, architectures and products for server platforms.Prior to joining Intel, Uri has held a position of a Sr. Director at Broadcom, managing an architecture team with responsibilities over the company’s NIC architecture and strategy.)*

Solving Distributed NFV Puzzle with OpenStack and SDN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many NFV use cases call for deployment of service elements at the provider network edge.  5G nodes, PGW, CPE, caches, all need to be placed near the end user to ensure efficient and cost-effective performance of the corresponding services.  With NFV, elements previously implemented as proprietary hardware appliances, can be virtualized, deployed on COTS servers and centrally managed.  In this presentation we'd like to share an approach to deploying distributed OpenStack-based NFV in a carrier network with an ultra-light edge composed of optimized Nova Compute Nodes and a centralized control plane placed in a provider DC with integrated SDN solution.  We'll discuss different deployment options, their advantages and disadvantages as well as present the learnings derived from a PoC deployment with a demo of the resulting solution.  In addition to addressing architectural challenges inherent to the distributed deployment model, we'll explore performance and distance related implications.


* **Rimma Iontel** *(Rimma Iontel, Senior Architect at Red Hat working on building NFV solutions for service providers as part of Red Hat Cloud Practice team.  After fourteen years with one of the major North American Service Providers, jointed Red Hat, working with service providers to make NFV platform a production reality with the help of Red Hat NFV solution, creating high performance and easy to manage future-proof networks that will enable new and exciting services for service provider customers.)*

* **Fernando  Oliveira** *(Fred Oliveira joined Verizon through the acquisition of CloudSwitch Corporation (http://web.archive.org/web/20130823173303/http://www.cloudswitch.com/), where as Chief Architect , he led the technology architecture and direction, and brought a wealth of experience in envisioning, designing and developing cutting-edge products. Prior to joining CloudSwitch, Fred was Chief Architect of the Cloud Infrastructure Group at EMC where he led the development of the Atmos next generation, multi-petabyte, policy-based storage system. He took this product from conception to initial customer delivery in an unprecedented two years time, building a new development team to over 100 people distributed across multiple continents. During his 10 year tenure at EMC, Fred was named a Distinguished Engineer and was a Senior Technologist in the Office of the CTO, where he led the technical due diligence of several potential partners (including VMware, Documentum and Smarts)  and technologies, and also managed the architecture teams for the Invista and PowerVolume products. He joined EMC through the acquisition of Conley Corporation, where he was Director of the PowerPath product. Before EMC, Fred held leadership roles at Stratus Computer, Apple Computer and Kendall Square Research. Fred has a BS in Electrical Engineering and Computer Science from the University of Connecticut and has been granted more than 20 patents in the virtualization, system software and storage areas.)*

* **Rajneesh Bajpai** *(TBD)*

TOSCA & Mistral: Orchestrating end-to-end Telco Grade NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Now you can orchestrate a full NFV service, with TOSCA templates & Mistral workflows on single/multiple geographies! There’s no doubt that workflows are a key ingredient for cloud automation, and automation is a key element in orchestration. However, when looking at an end-to-end, Telco grade, full NFV deployment over multiple distributed sites, orchestration starts becoming trickier. Using TOSCA as the main DSL for the Network Service Descriptor provides a hierarchical view of services, components and their relationships, which is decoupled from the underlying VIM/NFVI. When combining TOSCA interfaces and a mistral workflow, a full network service lifecycle can be achieved. The CloudBand Network Director, an NFV Orchestrater uses TOSCA based Network Service level description and modeling. In this session we will describe and demonstrate using TOSCA templates and a Mistral workflow engine to achieve Telco grade NFV orchestration with the CloudBand Network Director.


* **Tomer Shtilman** *(Tomer is a Senior Software Engineer at Alcatel-Lucent's CloudBand Business unit, working for the the last couple of years in the VNF life cycle group. Tomer has vast experience in software engineering, mainly in the cloud and telco industries and holds a B.Sc in Computer Science with over 10 years of active software development.)*

* **Renat Akhmerov** *(Senior Software Engineer at Nokia. His primary expertise is distributed computing and HPC, Concurrent Programming, Java, Spring and In-Memory Data Grids (GridGain, GemFire, Coherence) as well as significant experience in framework development. For the last two and a half year he's been mostly working on Mistral Workflow Service for OpenStack. Since the very beginning of the project he’s been actively contributing in both architecture design and implementation. He’s also been working as a community lead and presenting the project publicly.)*

SuperHEATed Orchestration: doing more with HEAT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Use the powerful heat engine to do more than just application life cycle management. https://github.com/ckravi/super-heat Taking a real life production example of Telco NFV cloud delivering vCPE solution, we show that apart from  application lifecycle mangement and orchestration, there are other needs like  admission control, service class/SLA aware oversubscription, intelligent placement, VNF license management etc. Currently these aspects are built as management applications on top of heat.In this example we show how to create custom heat resources that can be used to efficiently solve business aspects of cloud application life cycle including priority based oversubscription, admission control, licensing etcEnabling this via the heat engine allows:- Uniform declarative business policies- Version controlled business policiesIn short, superHEATing for fun and profit.


* **Ravindranath C K** *(Technical Lead at Juniper Networks. Over 14 years of experience in Networking and distributed systems. Currently productizing Openstack/OpenContrail based NFV solutions with focus on Virtual CPE and Distributed NFV Orchestration. Extensive experience in real world Service Provider Networks and QoS. Published works on standards based Network and Enterprise Management in:   2005 9th IFIP/IEEE International Symposium on Integrated Network Management, 2005. IM 2005. Moving from data modeling to process modeling in CIM  http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1440839&isnumber=31017 CIMOM is a service composition engine and a precursor to current Heat based orchestration. We embedded active decision making entities into CIMOM which helped move functionality of custom-built management applications into the middleware.  )*

* **None None** *(None)*

Orchestrating VNF Forwarding Graphs and SFC using OpenDayLight, Neutron and Tacker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Successful deployments of complex Network Services needs dynamic control of traffic flows through VNFs.Even when using SDN, adding new services and changing the related networking in the underlying networks can still be a challenge. Service Function Chaining (SFC) addresses these complexities, making even the most complex scenarios quite simple. SFC implemented in an SDN Controller, like OpenDaylight (ODL), must interact with additional components to automate the entire Service Chaining scenario. A VNF Manager, like Tacker, is necessary to manage the life cycle of VNFs.  Multiple layers need to work in cohesion to make this a reality. This ability to support dynamic VNF Forwarding Graphs using Service Function Chaining differentiates various NFV Orchestration stacks out there in the market. In this talk, you will hear how three opensource projects - Tacker, Neutron and OpenDayLight SDN Controller - coming together to achieve this holy grail of the NFV promise.


* **Sridhar Ramaswamy** *(Sridhar Ramaswamy works as a Principal Engineer in Brocade’s Software Networking division. Sridhar is the PTL for OpenStack Tacker project building NFV Orchestrator solutions within OpenStack tent. Previously Sridhar contributed to OpenStack Neutron projects. Sridhar is also a Container enthusiast and tinkers solutions in the Container Orchestration space. Previously Sridhar worked as Sr. Technical Leader in Cisco Systems in wide variety of areas including LXC Container based application management and CSR1000V Virtual Router.)*

* **Brady Johnson** *(Brady leads OPNFV and OpenDayLight SFC teams.)*

* **Louis Fourie** *(Louis is currently a senior staff engineer working on network virtualization, cloud services, and SDN technologies at Huawei Technology USA. Louis is an active contributor to the service chaining work in several organizations including ONF, ETSI NFV, IETF, and OPNFV.)*

How to test OpenStack for large NfV deployments (POPs) without miles of cables ?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Based on answering RFI/RFP for Service providers and equipment manufacturers a recurring question appears: How far apart can control and compute/storage be spread in a large real service provider network ?   This talk aim at providing metrics, tools and how to induce latency and errors (WAN simulation) for developers without a large network to test (miles of cables) in order to help the community make OpenStack thriving in those environments. Agenda for the talk (explanations AND live demonstration) :- Setting the problem, Point of presence, exchange, central office- How are going to simulate a Tier 1 network ?- Getting metrics, what to measure ?- Validating latency ism induced- impact on metrics.- Architecture considerations (stretch, multi-region) - Lesson for cells   Methods and code will be made available for the OpenStack community to simulate/test/measure and then enhance the OpenStack code for those use cases. 


* **Nicolas Thomas** *(Among the "founder" of the NfV realm, working on 2 of the initial use cases used to create ETSI NfV IG which defines and promote NfV. Member of ETSI NfV IG group before creation. 18 years of experience helping Telco use open platforms and ride the wave of IT innovation adapted to the telco space. Public speaker and hands-ons engineering. Former participant in Telco and platform standards : SAForum, Scope-Alliance, PICMG,  TC commite for OpenSAF and founder of CP-TA alliance. Currently NfV Solution Architect at Canonical, active participant to osm.etsi.org, ETSI NfV IG, OPNFV, Open-O https://fr.linkedin.com/in/nicolasthomasfr for details.)*

Create VNFs on the fly - VNF Components in Tacker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tacker is OpenStack based generic NFV Orchestrator and VNF Manager that instantiates and manages Virtual Network Functions(VNF). Virtualisation Deployment Unit(VDU) is the granular part of VNF which hosts the network functionality in the nova instance.  Currently, Tacker requires glance images or image location which has preinstalled network function like firewall etc., One of key requirements of operators is to have loose coupling software component and the underlying image.  As per ETSI MANO standard, VNF Component(VNFC) is the object which creates network function in the underlying nova instance. In this talk, we are going to walk through the following points. How Tacker adopts VNFC to instantiate the network function in VDUs. Onboarding of VNF Descriptor which embeds VNFC and deployment of VNFs. Various drivers in Tacker which supports communication with VDUs and how to introduce a new VNFC driver. Kanagaraj M<mkr1481@gmail.com>will also join the presentation.


* **Bharath Thiruveedula** *(Bharath Thriuveedula is software engineer in Imaginea Technologies Inc, Core reviewer and key contributor to the OpenStack Tacker, Heat translator projects. A contended individual who is passionate about open source technologies and an evangelist who is focussed to make his mark in the Cloud/NFV domains. He had worked on the custom solutions on the NFV Orchestration and his other interests are Containers and Distributed systems.)*

* **Manikanta Srinivas** *(Manikanta is a senior software developer in Imaginea Technologies Inc, A networking enthusiast and focussed engineer who is passionate about cloud and NFV domains, He has 5+ years of experience into development of switching and routing solutions. Currently focusing on scaling of  PaaS solution using containers and contributing to the Openstack Tacker Project.)*

NFV Orchestration with OpenStack - An Open Source MANO Perspective on Status and Extensions Needed
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV Orchestration with OpenStack - An Open Source MANO Perspective on Status and Extensions Needed. This talk will focus on NFV Orchestration challenges and the impacts on OpenStack from the perspective of the telecommunication service providers through the lens of the Open Source MANO community.  A number of scenarios will be described to clarify the types of deployments that telecoms service providers are looking to leverage OpenStack for. Open Source MANO is an ETSI-hosted project to develop an Open Source NFV Management and Orchestration (MANO) software stack aligned with ETSI NFV. It will be reviewed to provide some context on the architectural choices that are being made at this layer of the stack which impact the Virtual Infrastructure Manager (VIM) requirements. A review of some of the things that are considered to be working well and the areas that need immediate development.


* **Adrian Hoban** *(Adrian Hoban is a Principal Engineer in Intel's Data Center Solutions Group and the Technical Steering Committee chair for the Open Source MANO project. In Intel he is the system architect responsible for orchestration of Software Defined Networking and Network Function Virtualisation and leads the Intel team on OpenStack contributions in this area. He specialises in open source software such as OpenStack, Linux, Open vSwitch, KVM, QEMU and libvirt. Adrian is also active in standards initiatives such as ETSI-NFV.  In OpenStack Adrian set the architectural direction for the Intel contributors on areas such as PCIe passthrough, SR-IOV, Enhanced Platform Awareness for NUMA, Huge Pages, CPU pinning, and thread policy, OVS with DPDK enablement, and Security Groups. He has a particular interest in extensions that relate to using OpenStack to facilitate high performance application deployments and infrastructure utilisation. )*

* **Francisco-Javier Ramón Salguero** *(Head of Network Virtualisation Initiative and NFV Reference Lab, Telefónica GCTO Unit | TI+DChairman of Open Source MANO Community Project | ETSI OSG OSM Since 2000 Francisco-Javier has worked in Telefónica. Former head of the IP Network Technologies group in Telefónica I+D, since 2008 he is head of the Network Virtualisation Initiative and the NFV Reference Lab in Telefónica GCTO Unit. Additionally, he has been chair of the Performance and Portability Expert Group and the Working Group of Testing, Experimentation and Open Source in ETSI NFV ISG  In April 2016, he was elected Chairman of Open Source MANO (ETSI OSG OSM) project on Management and Orchestration for NFV. His expertise areas are network virtualisation, IP network architecture, traffic capture and analysis, QoE modelling, network planning and dimensioning, routing and network performance. He is author of several patents and technical papers in these fields.   Francisco-Javier has achieved a Master Telecommunications Engineer qualification at the Technical School of Telecommunications Engineering of Málaga (Spain), 2000, and a Master's Degree in Economics at UNED (Spain), 2006.)*

Infrastructure and service modeling strategies to deploy NFV in production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This panel brings together operators, tool and platform vendors, and telecom system integrators to discuss the challenges of obtaining meaningful and actionable insights when designing and deploying modern carrier-grade services in real world scenarios.  NFV and OpenStack provides vendors and network operators with transformational capabilities for service innovation and architectural flexibility. However, this flexibility introduces significant complexity in VNF service modeling, performance testing, verification and ongoing maintenance. The panel will explore how network operators can successfully manage OpenStack-based NFVI and VNF selection and onboarding. Including how automation frameworks together with comprehensive and integrated verification procedures are being used to accelerate service delivery, verify interoperability, performance, reliability and security.  


* **Diego Lopez** *(Since October 2011 I am in charge of Technology Exploration at the Global CTO Unit, within Telefónica I+D. My responsibilities are related to the definition and coordination of research projects in the areas of new networking technologies and network infrastructures. I am directly involved in activities related to network virtualization, core optimization, AAA, traffic analysis, and infrastructure security. I am actively participating in the ETSI ISG on Network Function Virtualisation (NFV), chairing its Technical Steering Committee.I am acting as representative of Telefónica in bodies related to network technologies, like the ONF and the BBF, and contributing to several working groups inside IETF. I have been appointed by the European Commission as member of the High Level Expert Group on Scientific Data e-Infrastructures (HLEG-SDI). I received my MS from the University of Granada in 1985, and my PhD degree from the University of Seville in 2001. Since 1985 I have worked for several private and public organisations, developing and deploying communication services.)*

* **Pierre Lynch** *(Pierre Lynch has been working in the wireless testing industry for 20 years, and is now a Lead Technologist, responsible for representing Ixia at various SDOs, forums and open source communities. He is currently the vice chair of the ETSI NFV ISG TST Working Group. He has been with Ixia since 2006, when he helped start and then guided the development of the wireless core network testing product line.)*

* **Artur Tyloch** *(Artur Tyloch is Canonical’s Global Telco Program Lead focusing on SDN and NFV requirements for Ubuntu customers and partners, as well as Telco ISV applications enabled through Canonical’s cloud ecosystem. Prior to Canonical, Artur ran software innovation projects and solutions at Nokia Networks Silicon Valley innovation center. He was also the architecture team lead, where he worked on various IoT, and BSS products and the core platforms. Artur specializes in NFV aspects of OpenStack enabled cloud architecture and is active in OPNFV, ETSI and other telco community and standards initiatives.)*

* **Michael Lazar** *(Michael Lazar is a veteran of the telecom industry, and has held C-level positions in system design, custom engineering and software development for the last two decades. He joined DataArt in 2016 to lead the company's telecom practice, focusing on the most demanding areas of the marketplace - systems performance, NFV, SDN & telecom security. Prior to joining DataArt, Mr. Lazar was Chief Technology Officer of Veloxum/Ambicom Holdings where he was responsible for developing system optimization software, and before that CTO of Network Physics, where he led the design and development of Voice over IP (VoIP) and Financial Information exchange (FIX) monitoring software. Prior to the CTO role, Michael was VP of Customer Advocacy at Network Physics, in charge of worldwide pre-sales engineering, post sales support, and custom engineering. Prior to Network Physics, Michael held senior technical roles at Datatec Systems and Spirian Technologies, Inc. Mr. Lazar holds a Bachelor of Science Degree in Physics from New York’s Queens College and holds a patent for Systems and Methods of Tuning an Operating System, Application or Network Component.)*

* **Morgan Richomme** *(Morgan works as Network architect for innovative services in Orange. He is Orange Network open source evangelist and OPNFV representative. Primarily involved in IMS deployment for Orange affiliates, he managed the project Emerginov (OW2), an open source PHP PaaS that has been deployed in Africa. He has 10 years' experience in managing open source solutions. He is engaged in OPNFV testing group, as Functest Project Leader.)*

Heterogeneous Cloud MANO deployment experiences and levaraging enterprise IT for NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We will present a PoC model for implementing a MANO deployment service offering distributed across an OpenStack Cloud,  a public cloud and an OpenShift (Kubernetes/Docker).  The service consists of multiple CloudRouter VNFs providing routing and VPN functionality across multiple clouds with the service terminating at a Container-based IMS.     The Open Source ManageIQ CMP, provides top-level orchestration including configuration of individual components through Ansible / Ansible Tower integration.  Tacker provides VNFM functionality within OpenStack while ManageIQ provides VNFM functionality in the public cloud.   TOSCA is used for service description. While OpenStack and NFV are at the heart of the POC,  we will show that a more practical way to accelerate the creation of an open source MANO is to start with a CMP product that already has most of the attributes for managing cloud-native applications and is already proven, by being widely deployed.


* **Pasi Vaananen** *(Pasi Vaananen is a NFV systems architect within the Red Hat Office of Technology, where he is responsible for advancing the Red Hat NFV system solution capabilities.  Currently, he is involved with many different initiatives such as, NFV MANO, system resiliency improvements and related community and standardization efforts. Mr. Vaananen has over 20 years of experience working on mission critical communications systems from companies such as Nokia, Motorola and Stratus. Previously, he held a systems architect role focused on SW & HW communication platforms, along with focus on other products in the broadband IP access and mobile network space. Vaananen is also currently participating in ETSI, OPNFV, OSM and Open-O activities, and has been previously active in efforts in e.g.  SCOPE alliance, IETF (MPLS and QoS), IEEE and  Broadband Forum. He holds over 10 US and international patents.)*

* **Aaron Smith** *( Aaron attended Swarthmore College as an undergrad and received his Masters and Ph.D. From Brown University in Electrical Engineering.  After a brief stay at Lincoln Laboratories, Aaron joined as an early member of a telecom startup and spent the next several years in either involved with system design or asic verification for telco.  After the telecom downturn, Aaron joined another early stage startup in an area now known as the "Internet of Things" helping to build one of the first cloud based HVAC control systems eventually reaching CTO of the company.  Aaron embraced early cloud efforts over the next few years at EMC and Stratus Technologies.  Aaron worked on an early CMP for OpenStack while at Stratus.  Aaron recently joined Red Hat in the NFV Partner Engineering group and has been able to continue working in the MANO and HA space.    "Cloud computing bears a striking resemblance to the work I was doing for my dissertation.  Cloud computing is very similar to massively parallel computing that was a research topic in the 80's and 90's.  It is rare to be able to work on what you studied in school"        )*

* **Andrew Toth** *(Andrew Toth has been developing software for over 20 years starting in the defense industry.  More recently, Andrew has been working in cloud computing and High Availablity at Stratus Technologies.  Andrew has concentrated on deploying VNFs into NFV environments focusings on HA and MANO.)*

Migration from "Carrier-Grade" to "Service Provider Cloud"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For many years, the Telcos adopted the term “Carrier Grade” for a system, hardware or software component that is extremely reliable, well tested and proven. Carrier grade systems are tested and engineered to meet or exceed "five nines" high availability standards.  However, in today’s exploding volume of bandwidth demands, networks have become increasingly complex and need to efficiently and reliably handle diverse traffic types and patterns requiring different types of resources for Compute (CPU and Memory), Storage and Network (I/O). Today, Service Providers need to deliver service with high Reliability, Availability, Manageability, Performance and Security (RAMPS) across the entire end-to-end ‘Service Provider Cloud’ system, with the objective of minimizing the business impact of of service outages in order to meet their Service Level Agreement (SLA). This talk is about why Telcos need “Service Provider Cloud ” solutions rather than just “Carrier Grade”  


* **Pasi Vaananen** *(Pasi Vaananen is a NFV systems architect within the Red Hat Office of Technology, where he is responsible for advancing the Red Hat NFV system solution capabilities.  Currently, he is involved with many different initiatives such as, NFV MANO, system resiliency improvements and related community and standardization efforts. Mr. Vaananen has over 20 years of experience working on mission critical communications systems from companies such as Nokia, Motorola and Stratus. Previously, he held a systems architect role focused on SW & HW communication platforms, along with focus on other products in the broadband IP access and mobile network space. Vaananen is also currently participating in ETSI, OPNFV, OSM and Open-O activities, and has been previously active in efforts in e.g.  SCOPE alliance, IETF (MPLS and QoS), IEEE and  Broadband Forum. He holds over 10 US and international patents.)*

* **Aaron Smith** *( Aaron attended Swarthmore College as an undergrad and received his Masters and Ph.D. From Brown University in Electrical Engineering.  After a brief stay at Lincoln Laboratories, Aaron joined as an early member of a telecom startup and spent the next several years in either involved with system design or asic verification for telco.  After the telecom downturn, Aaron joined another early stage startup in an area now known as the "Internet of Things" helping to build one of the first cloud based HVAC control systems eventually reaching CTO of the company.  Aaron embraced early cloud efforts over the next few years at EMC and Stratus Technologies.  Aaron worked on an early CMP for OpenStack while at Stratus.  Aaron recently joined Red Hat in the NFV Partner Engineering group and has been able to continue working in the MANO and HA space.    "Cloud computing bears a striking resemblance to the work I was doing for my dissertation.  Cloud computing is very similar to massively parallel computing that was a research topic in the 80's and 90's.  It is rare to be able to work on what you studied in school"        )*

* **Ali Kafel** *(Ali Kafel is the Technical Product Marketing lead for Red Hat’s Service Provider solutions, responsible for technical thought leadership, industry insights, technical content creation and field enablement. Prior to Red Hat, Ali held leadership roles in various technical and business roles for several high-tech start-ups and multinational companies, including Stratus Technologies, Extreme Networks, Sonus Networks and Lucent Technologies (now Nokia). He brings over 20 years of experience in Telecom and Networking, including Carrier/packet Telephony, Mobility, Data Networks, Cloud Computing and NFV/SDN. He has written several industry articles and spoken at multiple industry events on NFV and other telecom & networking initiatives. He holds an MBA and a bachelor’s degree in physics from Suffolk University in Boston, MA)*

NFV Service Assurance
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the overwhelming adoption of Openstack, tools such as Ceilometer can be leveraged to build a service assurance platform that performs autonomous event correlation from different network sources. Ceilometer, along with other open source monitoring tools, can provide an NFV Service Assurance Platform. This platform receives data from tools such as nagios for hardware, sflow for network information, ceilometer for VM and VNF's performance & fault through VNFManager/Orchestrator and  many more.  Service assurance in NFV can truly help to extend services such as self-optimization and self-healing within networks where Correlation engines correlate collected data and perform root-cause analysis, service impact analysis and inter-op with policy management and VNFs. Assurance helps user to predict any stoppage in service and perform the corrective action. The actions may include evacuation, live migration, scale out/in based on the policy defined by the network service.


* **Srinivas Tadepalli** *(Srinivas is the Solution Architect in Technology Business Unit’ NextGen initiatives to identify new offerings and use cases to drive adoption of NFV & DevOps. His focus is on developing and demonstrating NFV solution enablers and opensource contributions in OpenStack & OPNFV. He is a core contributor to tosca-parser and heat-translator openstack projects.)*

* **Meena Ventrapati** *(Meena is a Designer in Technology Business Unit’ NextGen. She is working on developing NFV and Service assurance use cases. She is also a contributor to openstack projects, heat-translator and tosca-parser.)*

Kazakhstan's First Commercial OpenStack Cloud: KazTransCom's Deployment and Operations Experience
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

KazTransCom  (one of the leading Telecom operators in Kazakhstan & Central Asia) has successfully deployed and operationalized the first commercial OpenStack cloud in Kazakhstan and Central Asia. This has become a cost-effective foundation for a number of important workloads, including e-learning and content filtering systems for schools in the region, cloud services for corporate clients, public WiFi services and various NFV VNF's. KazTransCom continues to add innovations to this OpenStack cloud, such as anti-DDoS solutions and Video Surveillance systems. This session provides detail on: - Benefits to the region from this deployment and workloads running on it - The deployed architecture and best practices on deploying Red Hat OpenStack Platform and Ceph Storage on Cisco UCS - Lessons learned from deployment and operationalization - Agile methodologies to deploy quickly and iterate rapidly instead of a complex cloud rollout - Growth plans, dependencies on OpenStack features.


* **Maxim Popov** *(Will Be Provided)*

* **Karthik Prabhakar** *(Karthik works with Red Hat's top Cloud Provider, Telco/NFV and Enterprise customers and partners in the development of open source cloud solutions, leveraging experience from over a decade of Chief Architect and Lead Technologist roles. Karthik specializes in the design and operational management of Microservices/Container and Cloud Infrastructure with innovative compute, storage and networking technologies. Karthik has been involved with OpenStack since the Essex release.)*

Neutron software-defined interconnects with WAN BGP VPNs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The networking-bgpvpn Neutron project allows to create connectivity between Openstack VMs and BGP/MPLS VPNs. These VPNs are a cornerstone of operators' backbones and interconnect datacenters, businesses or NFV POPs. Interconnecting them on-demand with Openstack is a critical piece of the NFV and hybrid cloud puzzles. This needs to be done in a controller-agnostic fashion to let automation and orchestration code be free of ties to a specific solution. The networking-bgpvpn project has been kickstarted in the Neutron stadium in 2015 to address this need, and its OPNFV counterpart SDNVPN project focusing on deployment and testing.  


* **Thomas Morin** *(Thomas has been for a bit more than 10 years at Orange Labs, mainly involved on IP and MPLS networking for backbones and datacenters, with activities ranging from architecture/ engineering studies, to lab and software development. Thomas is also active in the IETF, where he contributes to RFCs and co-chairs BESS, the working group defining evolutions of BGP VPN specifications. He has been focusing on network virtualization for IaaS since 2012 and contributes to related opensource projects, in particular in Openstack, where he co-leads the Neutron stadium BGP VPN project (networking-bgpvpn) and in OPNFV.)*

* **Paul Carver** *(Paul Carver is a Principal Member of Technical Staff at AT&T working on Software Defined Networking and Network Function Virtualization. His background includes traditional hardware networking with a wide variety of vendors in WAN and datacenter environments as well as software development in C, Perl and Python. He is currently focused on AT&T's "Domain 2.0" initiative to virtualize large portions of the mobile/cellular and wireline data and VoIP infrastructure on top of a common OpenStack based cloud.)*

* **Tim Irnich** *(Tim holds a Diploma and PhD in Telecommunications from RWTH Aachen University, Germany. Since 2007 he works at Ericsson. After holding various positions as standardization delegate and project lead at Wireless Access Networks Research, he joined the SDN Systems and Technology team in 2014, where he is today managing the SDN Open Source & Ecosystem program, which coordinates Ericsson's SDN-related open source activities in OPNFV, OpenStack, ODL, OVS and fd.io. He is PTL of the OPNFV SDN VPN project and a contributor in OPNFV Fuel as well as OpenStack networking-bgpvpn. )*

Juju modeling of DPDK based NFVi in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Juju is a universal service modeling system that models services and their relationships. This service-orientation makes Juju particularly well suited to support the deployment of OpenStack NFVi services, enabling high performance DPDK based interconnection between the VMs. Using Juju, 6WIND has developed some Charms to quickly and easily deploy some NFVi DPDK packages and some applications that provide that fastest interconnection with a full-service and full-SDN support of Neutron’s networking models.


* **Vincent JARDIN** *(Vincent Jardin is 6WIND's CTO. He is responsible to lead the architectures and developments for high performance packet processing. He co-founded the Quagga project, the open source project for routing, and remains one of its main contributors. He also helped found DPDK.org, an open source community that enables high performance network applications such as Network Functions Virtualization (NFV). Vincent has a strong knowledge on the packet processing technologies.)*

* **Nicolas Thomas** *(Among the "founder" of the NfV realm, working on 2 of the initial use cases used to create ETSI NfV IG which defines and promote NfV. Member of ETSI NfV IG group before creation. 18 years of experience helping Telco use open platforms and ride the wave of IT innovation adapted to the telco space. Public speaker and hands-ons engineering. Former participant in Telco and platform standards : SAForum, Scope-Alliance, PICMG,  TC commite for OpenSAF and founder of CP-TA alliance. Currently NfV Solution Architect at Canonical, active participant to osm.etsi.org, ETSI NfV IG, OPNFV, Open-O https://fr.linkedin.com/in/nicolasthomasfr for details.)*

NFV Gets Real / lessons learned with Telcos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network Function Virtualization (NFV), Cloud in the core network of telecom operators, is one of the latest developments of Cloud. Join this session to learn about the challenges and requirements specific to Telcos, discover key Telco use-cases for NFV and the different approaches used to address these challenges. Hear about the experience of large telecom operators and network equipment providers (NEPs) implementing NFV use-cases. We will describe how some of the largest EMEA Telcos currently using VMware as the VIM platform for their vIMS VNF, are now in a journey toward Openstack as their VIM platform.  We will present the HPE NFV ecosystem (working with our open source VNF partners) and the different capabilities that we can demonstrate in our openNFV Labs.


* **Christian SCHUTZ** *(Christian Schutz work as an EMEA Cloud Pre Sales for HPE Cloud Business unit.I am supporting both PaaS/DevOPS and NFV/Openstack projects with large enterprise (including Tier 1 EMEA telecom operators).Helping key EMEA customers define their cloud strategy and helping them adopt and implement this new style of IT based on Cloud, NFV and PaaS solutions. Work around Public, Private and Hybrid solutions.I work closely with HP field to pursue cloud opportunities across EMEA and assist them to answers to customer RFx, produce solution designs and deliver solution presentations to customers.Representing HP at key industry events (HP Discover, Openstack Summit and Mobile World Congress).)*

* **sUdhindra Subbarao** *(Sudhindra Subbarao is the EMEA Region lead for the NFV POC COE works out of Grenoble, France. 11 years of experience in various roles – Development, Program management, Presales, Solutioning and Consulting. Recognized expert in Openstack, Cloud & Automation and Licensing domain.  Responsible for solution designing, deploying and demonstratng Carrier Grade POCs for various Telcos in EMEA and APJ.  Also responsible for solutioning Cloud brokerage solutions through a market palce portal (HP CSA /OO) to consume hetergoenous clouds spanning across private and public cloud providers. Be it AWS, Azure, HPE Helion or IBM Softlayer. And providing Technical Leadership in the area of Openstack, Cloud and Automation for Enterprise, Financial isntitution and Telcos.)*

* **christine Perrin** *(Christine Perrin is part of the Hewlett Packard Enterprise (HPE) Enterprise Group – EMEA Hybrid IT / Cloud Presales team, working as a Solution Architect. Christine is expert in solution offerings articulating end to end solutions, with hardware, software and services portfolio to address business needs in the cloud & NFV domains. Christine supports complex pursuits and accounts teams.)*

50 Shades of OpenStack Orchestration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation wants to give a overview over different DSLs and Engines that are available for Orchestration.


* **Martin Oemke** *(since Feb. 2015 Deutsche Telekom, Germany)*

OpenStack Adoption in Telcos for NFV: drivers and blocking factors
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We’ve been hearing a lot about the use of Network Function Virtualization (NFV) for delivering virtual network functions in a cloud. In this area, OpenStack has quickly gained a lot of attention from Telco Providers and Application Vendors. The evolution of OpenStack itself is strongly influenced by NFV requirements and use cases, and this is proven by the great amount of Blueprints and initiatives which are NFV-related (e.g. OpNFV). This nevertheless, the adoption of OpenStack in production is quite low, and most Telcos are still in evaluation mode, performing PoCs in their test labs. This session will present to attendees drivers and blocking factors for OpenStack adoption in the Telcos: why is OpenStack so appealing with respect to other platforms? What are the requirements that are driving its development and evolution? What are the blocking factors that are slowing down its adoption in production environments? And what are the community and vendors doing to address them?


* **Pierangelo Magli** *(Pierangelo holds a master's degree in Computer Engineering from Politecnico di Milano (Italy) and a Master of Science in Computer Science from the University of Illinois at Chicago (USA). He joined HPE in 2006 as part of the Italy Innovation Center, where he worked as Solution Architect, developing strong skills on Software Design, Agile Methodologies and Cloud Computing. Currently his main focus and area of interest is Network Functions Virtualization (NFV). His experience as NFV Solution Architect dates back to 2012 with the very first HPE NFV PoCs, followed by delivery projects in IMS and VoLTE domain.)*

* **Luca Galluppi** *(Luca holds a Bachelor degree in Software Engineering and joined HPE in 2007. As an Information Systems Architect, Luca led the development of custom CTI and VOIP solutions for Telco and FSI Customers. He is competent with Networking, SDN and Cloud. Luca has participated in NFV PoCs and Custom projects of Common NFV Infrastructure for Telco services since 2013. He is actively involved in EU sponsored innovation projects in the Telco and NFV solution space.)*

End to End Architecture Design for NFV workloads: from Hardware up to the Cloud layer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Communication Technology industry with the help of Telco Application Vendor and IT industry are guiding a transformation phase that will move network functions from disperse, dedicated silos to a shared common infrastructure. Network Function Virtualization (NFV) workloads running of a cloud platform, with respect to IT applications, should rely on an End to End Carrier Grade (CG) architecture meeting at least "five nines" high availability standards and guaranteeing very intensive performance KPIs. This session will guide the attendees on the key requirements and design principles of a CG platform starting from the physical layer, moving to the virtualization layer and concluding with the Cloud platform. For each of these architectural layers, key aspects of compute, network and storage domains will be discussed. After watching this session, you should be able to understand the key principles to take care in the design of a CG infrastructure suitable to host NFV workloads.  


* **Luca Galluppi** *(Luca holds a Bachelor degree in Software Engineering and joined HPE in 2007. As an Information Systems Architect, Luca led the development of custom CTI and VOIP solutions for Telco and FSI Customers. He is competent with Networking, SDN and Cloud. Luca has participated in NFV PoCs and Custom projects of Common NFV Infrastructure for Telco services since 2013. He is actively involved in EU sponsored innovation projects in the Telco and NFV solution space.)*

* **Pierangelo Magli** *(Pierangelo holds a master's degree in Computer Engineering from Politecnico di Milano (Italy) and a Master of Science in Computer Science from the University of Illinois at Chicago (USA). He joined HPE in 2006 as part of the Italy Innovation Center, where he worked as Solution Architect, developing strong skills on Software Design, Agile Methodologies and Cloud Computing. Currently his main focus and area of interest is Network Functions Virtualization (NFV). His experience as NFV Solution Architect dates back to 2012 with the very first HPE NFV PoCs, followed by delivery projects in IMS and VoLTE domain.)*

The role of Neutron in OPNFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OPNFV is gaining more traction every day. Concepts are not always easy to understand, there are lots of new acronyms, moving pieces and questions still open regarding its relationship with OpenStack and specifically with Neutron. In this talk we are going to give answers to those doubts and questions. We will start with an introduction of OPNFV, what's its scope, what are the differences with OpenStack and what value it provides. Then we will move on describing the role of Neutron and associated projects in OPNFV, the most common use cases and configurations. We will illustrate how the OPNFV and the Neutron community interact: we will focus on some key feature (e.g. vlan-aware-vms) and explain how they built towards future capability that will be needed by OPNFV.  To conclude we will highlight current gaps in Neutron from the NFV point of view and we will share our thoughts about future work and directions.


* **Rossella Sblendido** *(Rossella is a Software Engineer at SUSE. She's a core reviewer for Neutron and has been involved in SDN since 2010 . She's also a mentor for the OpenStack Outreach Program for Women.)*

* **Christopher Price** *(Chris leads open source industry collaboration for Ericsson in the areas of NFV, Cloud & SDN from the CTO’s office in Sweden and is an active member of the technical steering comitee’s of the OpenDaylight and OPNFV Projects. Chris’ experiences include leading Ericssons' IP&Broadband network architecture and standardization teams with a rich history in development of systems and technology in the areas of network management, policy control and user service management, user session control plane solutions, and DPI technologies.)*

* **Armando Migliaccio** *(Armando Migliaccio is the PTL for the Mitaka and Newton releases of the OpenStack Neutron Project. He has been involved in the OpenStack community since its early days, and has dealt with a number of OpenStack projects, and solutions in various capacities. Most recently he has been working in various open source projects, like OpenDaylight and Open vSwitch to help the industry usher in a new era of networking.  When he is away from his desk, Armando enjoys sunny California between one travel and another. )*

OPNFV SFC with OpenStack and OpenDaylight
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data centers today are becoming more and more complicated to manage. Adding new services and changing the related networking usually requires involving system and networking admins and can take weeks to complete. Software Defined Networking (SDN) promises to improve this situation, and Service Function Chaining (SFC) will make it even easier. We will show how integrating OpenDaylight (ODL) SFC with OpenStack and a VNF Manager, all in an OPNFV deployed environment, can greatly increase the manageability of data center networks. We will show how the VNF Manager creates Service Function VNF VMs on-demand, based on the needs of different Service Chaining configurations. Once multiple service chains have been created with their respective VNFs, we will show end-to-end traffic through the different service chains, and show how the tenant traffic behavior transparently changes depending on the service chain being used. Demos will be Vagrant-based VMs, enabling participants to dig in at home.


* **Brady Johnson** *(Brady leads OPNFV and OpenDayLight SFC teams.)*

* **Daniel Farrell** *(Daniel Farrell is a Software Engineer on Red Hat’s SDN Team, where he contributes to upstream OpenDaylight and OPNFV. He has been involved in SDN’s development since it emerged from Stanford, including early OpenFlow and OpenStack work. During ODL’s Helium release cycle he bootstrapped ODL’s performance efforts. In Lithium, he focused on building ODL’s upstream delivery pipeline, including RPMs, Vagrant base boxes, containers, an Ansible role and a Puppet module. He’s now the PTL of ODL Integration/Packaging and OPNFV CPerf, as well as a committer to ODL Integration/Test and an ODL TSC member. Daniel has given talks at LinuxCon North America 2014+15, LinuxCon Europe 2015, LinuxCon Japan 2016, Open Networking Summit 2015+16, OpenDaylight Summit 2015+16, OPNFV Summit 2015+16, All Things Open 2015 and numerous small FOSS conferences.)*

Automated Cloud Infrastructure Deployment for Telco
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Telco operators have a special set of requirements when it comes to cloud environments. A single cloud must support different functional use-cases (hosting, service function chaining) applications requiring different performance requirements fully integrated and automated end-to-end lifecycle management In this session we will talk about how Deutsche Telekom achieved that goals by creating an OpenStack environment, which is distributed across multiple DCs in several regions. The network foundation for the overlay network and the service function chaining as well as the interconnection between the different DCs is provided by the OpenContrail SDN solution. Canonicals MaaS and Juju provide the lifecycle management, including the fully automated deployment of OpenStack, OpenContrail and Ceph elements into a highly complex and secured network setup. Telco requirements, current status, time used, lessons learned and solution gaps will be explained. Join the presentation and you will know.


* **Ralf Trezeciak** *(As a Senior Network Architect, Ralf working on data center/cloud network virtualization and Software Defined Networking technologies at Deutsche Telekom. He is currently working on the network architecture for a Openstack based NFV cloud at Deutsche Telekom.)*

* **Paolo de Rosa** *(Paolo De Rosa , Services Engineer @ Canonical I work for Canonical as Support Engineer, I'm an Network and Cloud specialist with programming skills and strong telco background. In the past I have been working to design, configure, troubleshoot and install large computer networks in campus and carrier scenarios. I spend my time to model and build beneficial IT infrastructures to be cultivated, scaled up and maintained over time. Loving network and system automation I have always been inspired by large IT infrastructures, because unlike computing systems which typically concern independent or stand alone systems, is a concept being developed to describe large scale, complex, and networked technologies.)*

* **Michael Henkel** *(Prior to joining Juniper in 2014 Michael worked 16 years for HP. In HP he spent his last 2 years on doing research on SDN and writing applications unleashing the power of SDN. Michael is passionate about SDN and virtualization. As part of Junipers Contrail team he takes care for integrating OpenContrail into whatever kind of new and exciting technology comes along. Lately he started to enjoy the brave new world of Containers and their need for a robust networking infrastructure.)*

Asking the right questions for Storage in NFV deployments, so that you can forget about it !
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Architects designing NFV deployments are currently focusing most of their time on providing solid network, compute and automation layers. This is due to the fact, that solving especially network on scale is a challenging task. Nevertheless, most Virtual Network Functions (VNFs) require persistent storage to provide their services.


* **Yves Weisser** *(I have been working around Telco & Service Providers for about 15 years, focusing on storage, and more recently NFV & SDN architectures in EMEA)*

Optimizing, Configuring and Deploying NFV VNF's on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A deep technical discussion on how to best leverage Nova scheduler to configure and deploy applications for NFV.  Virtual Network Functions (VNF’s) typically have critical performance targets and need to predictability get the performance they expect every time they are launched.  The scheduler is a complex beast and knowing how to best leverage its wonderful capabilities to maximize performance will be demonstrated.  We will compare performance with and without leveraging the scheduler parameters that are available and highlight the delta. Providing predictable access to resources for VNFs is a critical part of a successful NFV deployment and we will show you how to accomplish this important goal.


* **Ian Jolliffe** *(Ian has over 20 years experience in Telecom and has been working with Openstack since 2013.  He guides upstream work in Nova, and Neutron and participates in the community on the Telco Working Group.  He is a frequent presenter on Cloud and NFV at customer events, internal conferences and webinars.  Ian is a committer on the OPNFV high availability project.  )*

* **Chris Friesen** *(Chris Friesen is a software developer at Wind River, and is one of the inaugural developers of the Titanium Server product. He works at various levels of the stack from kernel device drivers up to guest userspace, with a focus on nova.)*

* **Ludovic Beliveau** *(Ludovic is an active contributor to Nova with a focus on SRIOV.  Ludovic is a networking industry expert and has been working on Openstack for 3 years.)*

Tapping in NFV cloud : A real world showcase by Swisscom, Ericsson and IXIA.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this tech talk, Sébastien Grognuz from Swisscom, Vinay Yadhav from Ericsson, and Anirban Majumder from Ixia will explain how Swisscom collaborated with Ericsson and Ixia to solve their major challenge of monitoring their new NFV based wireless infrastructure. Swisscom network leverages the Ericsson CEE architecture, which runs on OpenStack, and needed a solid solution to monitor the virtual traffic. The three entities collaborated to implement the opensource Tap as a Service added to Ixia CloudLens virtual visibility solutions, bringing traffic filtering capabilities to allow for more efficient usage of resources when monitoring traffic.


* **Vinay Yadhav** *(Vinay obtained his Masters in Communication Systems from The Royal Institute of Technology (KTH) Sweden in 2012. Vinay has been hacking in Openstack since 2011 predominantly in Networking for Layer 3 Services developing cutting edge Research and proof of concepts for VPN Access and inter cloud connectivity. Vinay currently work as an Experienced Researcher in Ericsson Research Unit where he is actively engaged in other projects such as SAIL where he has worked on Federated Cloud Research and distributed service deployments across heterogeneous cloud platforms. Vinay is currently working on developing services around Neutron for better NFV support within Openstack such as adding port mirroring (Tapping) feature in OpenStack Neutron.)*

* **Sébastien Grognuz** *(After several years of experience in wireless core architecture, Sébastien Grognuz switches to the cloud world following the natural evolution of the telco industry. As principal solution architect for the telco cloud program at Swisscom, he leads the deployment of the Ericsson NFV cloud and coordinates the technical aspects among the different projects.)*

* **Anirban Majumder** *(Anirban Majumder is a Software Architect working at IXIA leading cloud monitoring solutions. He has been involved in leading and managing multiple network solution on Openstack and other virtual platforms for more than 4years. Anirban has more than decade long experience leading and working with linux and windows based network, security and monitoring solutions.)*

Meeting SLA: NFV Notification and Remediation using Tacker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The advent of NFV has changed the way TELCOs are beginning to deploy network functions. NFV has brought benefits in terms of deployment agility and cost reduction while also introducing virtualization layers that add complexity and operational challenges. One of the critical requirement for TELCO to maintain SLA is that identifying the abnormal situations of running VNFs and address them to bring it to normal operational state,  automatically or manually. This requires monitoring, async event notifications, remediation such as scaling which has been addressed collectively by OpenStack services tacker, ceilometer, heat, etc. In this session, we will discuss in detail about these features and how OSS can use them automatically to handle the abnormal situations.


* **Vishwanath Jayaraman** *(tacker upstream contributor)*

* **Kanagaraj Manickam** *(  Huawei Senior System Architect @ Huawei Technology India Pvt. Ltd. OpenStack Core-reviewer @ OpenStack Orchestration Service (Heat) Core-reviewer @ OpenStack NFV Orchestration Service (Tacker) Establishing OpenStack Manager (Namos) Open-O Active participant and contributor in Open-O community)*

Telco Cloud and Container-Based VNFs Architecture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Today most of Telco Cloud VNFs are hypervisor-based and using KVM in OpenStack, the next evolution of VNFs in Telco cloud will be containerization of Telco applications & functions (vMME, vSGW, vPGW, vFW, vLB) and how current Telco Cloud Data Center Design will support those changes. This session will provide an evolution of Telco Cloud Data Center Architecture for containerized VNFs. Current Telco Cloud Data Center Architecture (OpenStack + SDN) VNFs Overlay design principles and use cases Future Telco Cloud Data Center Architecture (OpenStack + Docker +Kubernetes ) Container-based VNFs High availability Container-based VNFs Networking (Overlay/Underlay) requirements Container-based VNFs & Orchestration (Available Options) Container-based VNFs Overlay design with constrainers and use cases End to End Telco Cloud Architecture with Containerization support  


* **Qasim Arham** *(An innovative leader, Consultant, and strategist, possessing over 15 years of Packet Core (EPC/vEPC), Cloud SDN/NFV solutions architecture and design experience, in the rapidly advancing world of Telecommunication, Packet Backbone and Next Generation Cloud Networks Architecture. Passionate about OpenStack cloud computing, future Data Center IP Networks and teamwork for the success.)*

* **Maria Napierala** *(Maria Napierala is a technology and services architect in Mobile Packet Core organization at AT&T Laboratories. She is currently working on Mobility Data Center architecture based on network function virtualization and SDN. Previously, Maria worked on WAN architecture and service, including MPLS/BGP VPNs, VoPacket, QoS, Multicast, MPLS traffic engineering. Prior to joining AT&T worked as a senior software engineer in Network Routing Systems group at IBM. Maria holds a Ph.D. degree in Computer Science and Engineering from Oregon Graduate Institute, Oregon (1992). Her Ph. D. thesis is in the area of automated program generation and computational logic.)*

"REST API driven Compute Node configuration for enabling EPA based placement of VNFs by MANO"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

VNFD templates allow for specifying requirements for VNF workloads that leverage features of a compute node such as NUMA topology, SR-IOV, PCI-Passthrough, Huge pages and CPU pinning. This allows for Enhanced Platform Awareness(EPA) driven placement of VNF workloads to achieve better performance. However the cloud administrator is required to pre-configure computes to enable for EPA usage. The manual steps involved here are not scalable considering size of typical Telco clouds and can be error prone.  This talk introduces a REST-API driven ability to configure/modify compute nodes to enable for EPA usage. OpenStack Tacker (or other ETSI MANO clients) will be able to query which compute nodes are configured for EPA usage and the respective resource allocations. In addition this talk will highlight the need for enhancing/extending OpenStack (e.g. Nova) APIs for retreiving detailed EPA relavant resource usage information from compute nodes.


* **Chegu Vinod** *(Chegu Vinod (Vinod) is an Architect in the NFV Business Unit at Hewlett Packard Enterprise. His interests include EPA, NFVi, VIM, Performance and scaling.)*

* **Naziya Khan** *(Naziya Khan is a Senior Software Engineer/Technical Lead working on implementing various Telco Cloud related solutions in the NFV business unit at Hewlett Packard Enterprise.)*

* **Vishwanath Jayaraman** *(tacker upstream contributor)*

High Availability automation test suite for 5 9’s reliability of VNF workloads in NFV clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV cloud environment requires 99.999% availability and is built at all levels of the ETSI architecture. Testing the HA high availability of the cloud end to end and deriving the 5 9’s availability is always a challenge. We would like to present this automated test suite build on the Rally framework that runs end to end HA scenarios with fault injections on the compute and VM in the NFVI. It also measures the fault detection times and recovery times of the compute and the VM, thereby enabling validating the derivation of 5 9’s availability for the VNF workloadsOur presentation covers the following,Reliability test cases and their work flow.Automation of the test casesDemo of sample test case executionDiscuss the derivation of 5 9’s availability.


* **Thalabathy Venkatesan** *(Working in HPE as a QA Specialist.)*

* **Maheshkumar Pandurangan** *(Cloud test architect working at HPE)*

* **Ashraf Vazeer** *(working at HPE as a QA specialist.)*

Data Performance testing on NFV clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Normally vlan traffic is generated from a traffic generator to the VNF under test and looped back to the traffic generator to measure the throughput and latency of the VNF on N/S and E/W topologies. However, there are much more metrics like the VNF boot time, VNF processing performance and  vSwitch processing performance with variable CPU/Mem/Other resource allocations and bandwidth allocations, that can be done across multiple different topologies for both vlan and vxlan with different acceleration techniques like DPDK, SRIOV and PCIPT used in the VNF.In our presentation we cover the following,-Different L2/L3 topologies for both vlan and vxlan, with and without DVR-vlan/vxlan Traffic generation tool used-Comparing data performance results across different acceleration techniques to identify performance bottlenecks-Brief demo showcasing variable VNF/Vswitch resources allocations and its impact on data performance


* **Thalabathy Venkatesan** *(Working in HPE as a QA Specialist.)*

* **Maheshkumar Pandurangan** *(Cloud test architect working at HPE)*

* **Ashraf Vazeer** *(working at HPE as a QA specialist.)*

Deploying network latency sensitive workload for NFV in Helion Operating System (HOS)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Virtual bridges are used in OpenStack to offer flexibility to create segmented tenant networks for East-West and North-South traffic. Use of bridges limits the network throughput generated by Virtual Machines, and hence not suitable for NFV workloads. An alternative approach to ensure network throughput for such latency sensitive workloads is to use PCI-SRIOV and PCI techniques.  In this presentation, we will talk about: our experience of enabling PCI on Intel and Mellanox network controllers. how in HPE, we have managed to automate and simplify the deployment of PCI devices to work with OpenStack how easy it is made for a cloud provider to stand-up a cloud supporting deployment of network latency sensitive tenant workloads using PCI-PT and SRIOV techniques. The session will end with a demo of how a tenant VM with PCI-SRIOV/PT would communicate to other normal VMs on the virtual bridge, thus retaining the East-West and North-South traffic untouched, but with greater throughput. 


* **Maruti Kamat** *(An active contributor in OpenStack Neutron (especially in networking-l2gw) . Have been working in OpenStack Neutron for past 3 years. Being with the networking business of Hewlett Packard Enterprise (cloud development) and earlier in BYOD and campus edge networking, played a major role in design and development of solutions delivered to valuable customers. Published several papers and patents in these areas.  )*

* **Sonu Sudhakaran** *(Active Neutron/Nova and Monasca contributor)*

* **Prashant Naik** *(Active Neutron contributor)*

Streamlining VNF Management: Requirements for a Generic VNFM
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  The NFV promise is a “standard” and “commoditized” VNF deployment environment phasing out proprietary hardware network appliances, which are configured and managed by vendor-specific EMSs. Management of the virtual infrastructure is being simplified by VIMs, i.e. OpenStack, but as vendors virtualize their VNFs and make them cloud ready, existing EMSs are augmented to provide the VNFM function.  While this coupling might allow vendors to utilize their knowledge of the application to enhance the VNFM capability it also continues the outdated practice of application-specific VNFMs. Generic VNFM would streamline the overall solution.   This talk presents work underway at Verizon to develop Generic VNFM requirements, which depend on the VIM capabilities, type and complexity of the VNFs, and a robust set of VNFDs. An analysis of the possible pros and cons of open source approach with projects such as Tacker, OpenBaton, Juju vs. vendor specific approaches, i.e. Nokia’s CBAM is also presented  


* **Nabeel Cocker** *(Network and Cloud architect with over 16 yrs of experience in architecting, designing and depolying large scale service provider networks and data centers. Avid soccer fan.  )*

* **Fred Oliveira** *(None)*

Tacker 102: Beyond VNF life cycle management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tacker project is an extendable NFV orchestration software that follows a plugin driver model approach for ease of customization and adaptability by network operators. Operators wanting to deploy Tacker in their infrastructure typically write custom drivers based on their VNF requirements and implement end to end service workflows.  In this session, first, you will learn about Tacker internals on how different components such as VNFM, NFVO, and VIM interact with each other. New features such as alarm based monitoring, manual and autoscaling, events notification and VNF forwarding graphs introduced in the Newton release will be discussed. Then, you will learn how to extend Tacker's capability by writing custom drivers. A step-by-step procedure of writing a new driver for VNF monitoring, configuration and supporting custom VIMs will be presented. Lastly, the audience will learn how to configure the new drivers in Tacker and invoke them through TOSCA VNFD template specification.


* **Sripriya Seetharam** *(Works as a Senior Software Engineer at Brocade. Tacker project committer. Open source enthusiast. Interested in SDN and NFV related projects.)*

* **Bob Haddleton** *(Bob Haddleton is the Innovation Team Lead and a Cloud Solutions Architect in the Applications & Analytics business unit at Nokia, where he works to develop cloud-based solutions. Bob has over 28 years of experience in telecommunications software, 3G/4G wireless, and networking.  He joined the Cloud Innovation Center in 2013 and set to work using his extensive telecommunications software/networking and wireless knowledge to demonstrate how network functions can be virtualized and provide higher levels of reliability at lower costs.  He is a core reviewer for the Tacker, TOSCA Parser and Heat Translator projects, and is interested in the issues that surround deploying/configuring/monitoring/maintaining complex VNFs and Network Services.)*

* **Sridhar Ramaswamy** *(Sridhar Ramaswamy works as a Principal Engineer in Brocade’s Software Networking division. Sridhar is the PTL for OpenStack Tacker project building NFV Orchestrator solutions within OpenStack tent. Previously Sridhar contributed to OpenStack Neutron projects. Sridhar is also a Container enthusiast and tinkers solutions in the Container Orchestration space. Previously Sridhar worked as Sr. Technical Leader in Cisco Systems in wide variety of areas including LXC Container based application management and CSR1000V Virtual Router.)*

Root Cause Analysis for NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Fault Management is a critical component of the NFV effort. OpenStack Vitrage, with its RCA  support, brings OpenStack one step closer to giving NFV the tools it needs to become a reality. Fault management in NFV is complex. Problems at physical layers impact the virtual layers, resulting in service disruptions. Due to the high performance required in Telecom systems, fast fault analysis and response is critical in this domain.  NFV Services are comprised of virtual resources that may be distributed across separate (OpenStack) clusters, so failures in one cluster can impact performance in the other. Tracking this impact chain across layers in a production-grade system is challenging. In this talk we present how Vitrage uses its latest Heat data source to give insights into VNF-related faults, and how Vitrage provides a clear and holistic view of the system, from physical infrastructure to the VNF, which can then be used to drive application management policy.


* **Ifat Afek** *(Ifat Afek is a System Architect in Nokia CloudBand, and the PTL of Vitrage project - OpenStack RCA service for organizing, analyzing and visualizing OpenStack Alarms and Events. In her role, she has lead the Vitrage effort from day one towards its acceptance into the Big Tent six months later. She now focuses on Vitrage productization and new features for Newton, as well as the design and roadmap for Ocata. She is also involved in OPNFV projects which have relevance to Vitrage (Doctor, PinPoint, VES).)*

* **Dan Offek** *(Dan has over 30 years of experience in development. He began programming from a young age, and following his hobby, continued developing as part of his military service and after that, on Network management systems, and Cloud orchestration. Today Dan is a member of Analytics Insight team in Nokia's CloudBand. On his free time, when not spending time with his family, Dan likes cliff climbing, wall climbing and bouldering. He also enjoys bike riding.)*

VITAL: A framework for Benchmarking and Characterization of Telco grade Virtual Network Functions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As we observe a proliferation of Virtual Network Function offerings from various vendors, benchmarking and performance characterization of these VNFs on an Openstack environment is of utmost importance. In our talk, we present a framework that has been designed and implemented at HPE, which uses a two pronged approach to the problem. In the first approach, we address the issue of determining an optimal output set achievable, for given a set of input virtualization knobs such as the sizing, VIF model, pinning etc.,. The output set is a list that can span across parameters such as throughput, latency, jitter or other VNF/solution specific attributes. The second approach of the framework is to start with a least-common-denominator input set of virtualization parameters and try to achieve an optimal output set by automatically varying the inputs. The framework also implements monitoring vital characteristics such as CPU/Memory/Disk/Network I/O and correlates this with the input sets.


* **Badri Natarajan** *(Badri Natarajan is currently a Solutions Architect with the Network Functions Virtualization Business Unit at HPE. His responsibilities include working with CSPs in accelerating their adoption of NFV , and integrating partners and ISVs  into a common ecosystem through the HPE OpenNFV Partner program. His prior Telecom experience includes working in various technology roles with Network Equipment Manufacturers, in optical and packet switching domains.)*

End to End Network Service Deployment in Tacker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tacker is a generic VNF Manager and NFV Orchestrator that performs Virtual Network Functions (VNFs) life cycle management and configuration. In this talk, we will present the Network Service Descriptors (NSDs) support within Tacker that enables dynamic composition of network services, allowing users to orchestrate a collection of VNFs and forwarding graphs.     NSD templates mainly describe network elements as a relationship between different network element and their links to be instantiated in the NFV infrastructure.  An NFV Orchestrator can use NSD to instantiate a network service which may have one or more VNFs,  Virtual Links (VLs) and VNF Forwarding Graphs (VNFFGs). In this talk we will discuss:     * Aspect of NSD in NFV MANO     * NSDs walkthrough     * Network Service Fault Management and case study     * NSD workflow in Tacker     * How to leverage NSD templates for VNFFG


* **dharmendra kushwaha** *(Software engineer at NEC Technologies India. He has worked in various domain like Storage, FS, Cloud computing etc. Worked on OSD project which integrated Swift with secondary backend storage. Also having good knowledge in NFV area. Currently working in OpenStack Tacker and activly contributing in Tacker project.  )*

* **Sripriya Seetharam** *(Works as a Senior Software Engineer at Brocade. Tacker project committer. Open source enthusiast. Interested in SDN and NFV related projects.)*

* **Bharath Thiruveedula** *(Bharath Thriuveedula is software engineer in Imaginea Technologies Inc, Core reviewer and key contributor to the OpenStack Tacker, Heat translator projects. A contended individual who is passionate about open source technologies and an evangelist who is focussed to make his mark in the Cloud/NFV domains. He had worked on the custom solutions on the NFV Orchestration and his other interests are Containers and Distributed systems.)*

OpenStack and the Orchestration Options for Telecom / NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many open source orchestrator projects which are attempting to accelerate SDN/NFV deployment in operator networks, Open Source MANO is targeting how to deploy NFV based on the ETSI MANO specification; OpenStack Tacker starts from a VNF manager and is evolving from there with the help of other projects; Open-O (Orchestrator) explores areas beyond the MANO specification by including SDN orchestrator, legacy networks, and OSS; ManageIQ and others could evolve from cloud/IT managers into an NFV orchestrator; and at the same time, AT&T published the ECOMP whitepaper which augments the ETSI MANO story with policy, closed loop control, VNF onboarding, SDN configuration. This panel will address how we plan to harmonize multiple orchestrator projects to better align on modular code within each project. There are many common new modules like Parser, VNF onboarding, EPA, Generic VNF managers, event streaming, which could benefit from the cooperation among multiple open source projects.


* **Hui Deng** *(Hui Deng is Principal Staff and is leading SDN/NFV technical strategy at China Mobile. He is the current chairman of OPEN O project; He is also the treasurer and BoD member of OPNFV. He also serves as the chair of Platform & Ecosystem WG in SDN/NFV Industry Alliance (China). Hui Deng has organized and chaired the NFV workshop 2015 (Beijing), NFV Workshop (Shanghai) 2015, SDN/NFV Open Source Workshop 2016 (Beijing). And he also made speeches in MWC 2015 OPNFV Panel, China DPDK Summit, China SDN/NFV Conference, Intel Network Summit, and Huawei Cloud Conference in 2015.)*

* **Chris Wright** *(Chris Wright is the Chief Technologist at Red Hat where he is leading engineers who work on cloud computing, distributed storage, network virtualization, containers, and continuous delivery.  During his more than 20 years as a software engineer he has worked in the telecom industry on high availability and distributed systems and in the Linux industry on security, virtualization, and networking.  He has been a Linux developer for over 15 years, most of that time spent deep in the Linux kernel. He is passionate about developing open source software to serve as the foundation for next generation IT systems.  He lives in sunny Portland, OR where he is happliy working on open source projects such as OpenDaylight, Open vSwitch, OPNFV and OpenStack.)*

* **Diego Lopez Garcia** *(Since October 2011 I am in charge of Technology Exploration at the Global CTO Unit, within Telefónica I+D. My responsibilities are related to the definition and coordination of research projects in the areas of new networking technologies and network infrastructures. I am directly involved in activities related to network virtualization, core optimization, AAA, traffic analysis, and infrastructure security. I am actively participating in the ETSI ISG on Network Function Virtualisation (NFV), chairing its Technical Steering Committee.I am acting as representative of Telefónica in bodies related to network technologies, like the ONF and the BBF, and contributing to several working groups inside IETF. I have been appointed by the European Commission as member of the High Level Expert Group on Scientific Data e-Infrastructures (HLEG-SDI).)*

* **Tobias Ford** *(As the AVP of Cloud Infrastructure and Platform Architecture & Strategy for AT&T, Toby Ford leads technology efforts around AT&T's cloud offerings both internally and externally focused. Currently, Mr. Ford is responsible for shepherding SDN and NFV projects on to AT&T’s Common Cloud platform. Toby served as CTO for USi, which was acquired by AT&T in 2006. Previously, Mr. Ford held positions at Cornell University, ARINC, TeleCommunication Systems, and his own company in the Netherlands. Toby is also a member of the OpenStack Board of Directors.    )*

Red Hat and Juniper Networks collaborate to develop converged carrier grade cloud software stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Red Hat and Juniper Networks have collaborated and co-developed a validated and integrated software stack for Telco clouds. We have subsequently tested these stacks for carrier-gradeness. Subsequent to these efforts, we have found some joint customers who have deployed these validated carrier grade software stacks.  We will discuss the process behind arriving at these joint stacks, the stack components, the end-to-end provisioning of the stack components, and some customer use cases.  We will potentially invite some of our joint customers to provide their perspective at using, deploying and operating Telco clouds that leverage such joint stacks. 


* **Marc Rapoport** *(Sr. Product Manager for OpenContrail at Juniper Networks, Inc. Past - Product Manager for HPE Helion OpenStack Product Manager at Ericsson (Redback))*

* **Nick Barcet** *(Nick is the Director of Product Management for OpenStack at Red Hat.  Nick joined Red Hat in June 2014, as part of the acquisition of eNovance, where he was VP of Products. Prior to that role, Nick was Ubuntu Server and Cloud Product manager at Canonical, where he participated in the definition and success of Ubuntu as a platform above and under the cloud. Nick joined the OpenStack project since its first summit in Austin and founded the Ceilometer project, now known as OpenStack Telemetry, at the Folsom summit in April 2012, to handle centralised metering on OpenStack. He has been project leading it for its first year and until it was integrated by OpenStack's technical committee. Nick was also a Director of the Board of the OpenStack Foundation in 2013. Nick has been involved in Free Software since 2000 working with Novell and Intel in various technical and management roles. Nick is a french citizen residing in the Boston area, MA and is 48 years old.)*

* **Aniket Daptari** *(Sr. Product Manager (Cloud Network Automation, Contrail) @ Juniper Networks Inc. Started as a Software Engineer writing protocol code, CLI, device drivers and online diagnostic software for various networking equipment at different network equipment vendors - Allied Telesyn, Force10 Networks, Cisco Systems. Then began a journey into network programmability, APIs and SDK at Juniper Networks. Evolved from programmability into platforms for NFV and SDN. In this journey evolved from being a Software Engineer to a Technical Marketing Engineer to a Solutions Engineer to a Product Manager. On the education front have a Bachelors degree in Computer Science from Mumbai, India. A Masters degree in Computer Science from University of Southern California. And a graduate certificate in Management Science and Engineering from Stanford University.)*

Service Assurance, a challenge for Network Functions Virtualization(NFV) -- What can OpenStack do?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Service Assurance and FCAPS are funtions of Telco operational support systems(OSS). Monotoring fault/performance and autoprovisioning are extremely important for Operationalizing the Network services. While Virtualization and Cloudification of the Network Services is the obvious path forward for Telecommunications, it has presented with the new challenges in handling the Service Assurance aspect. What can OpenStack do? 1. Is Telmetry ready for the task? 2. Is OpenStack keeping up with the ETSI MANO requirements with respect to Service Assurance? 3. How are the various modeling specifications and tools helping with closed loop Service Assurance?  As the Telco Solution Architects at Red Hat working with a major Telecom Operator, we will talk about our first hand experience with the challenges and present some potential solutions.    


* **Sudhir Kethamakka** *(Sudhir is a Senior Architect at Red Hat focused on Telco Solutions, working with Tier1 operators in North America. Prior to joining Red Hat, Sudhir was a Product Development Director at Ericsson, heading one of the core development units for Ericsson Cloud Manager solution. He has more than 15 years of experience in Telecom industry working in different roles related to Software Development and Architecture. He holds a Masters degree in Computer Science.)*

* **Gordon Keegan** *(Experienced Telco Solution Architect at Red Hat Inc.)*

Containerized workloads challenges with NFV solutions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Containers are considered as a potential alternative to Virtual Machine-based implementations. Their popularity among developers incredibly grows with standardization and portability and have led to new microarchitectures providing opportunities to solve large-distributed computing tasks. On the other hand, SDN and NFV are changing the networking landscape providing huge flexibility and functionality to the cloud-based solutions. This presentation will describe cases of using virtual machines for NFV workloads and how containers can address these competitions. This session covers: Cases with NFV and Virtual Machine Implementations NFV with Containers and potential solutions Architecture A hybrid deployment of containers with virtual machines Technical details Attendees will leave this session with a firm picture of existing solutions for using NFV with containerized workloads, their common features, and differences.


* **Ihor Dvoretskyi** *(Ihor is an experienced engineer at Mirantis, responsible the for projects tightly bound to Cloud computing, containerized workloads and Linux systems. He is deeply interested in OpenStack cloud platform, other cloud technologies, especially the Open Source projects. Also, Ihor acts as the Kubernetes upstream contributor and OpenStack Special Interest group lead (SIG-OpenStack) at Kubernetes Community, working intensely on the questions and abilities, related to OpenStack and Kubernetes collaboration and integration.)*

* **Andrian Noga** *(Andrian is a Project manager in the Partner Integration Team, with 11+ years in Project management and networking.)*

* **Dmitriy Novakovskiy** *(Dmitriy has been doing OpenStack clouds with Mirantis for 3 years. Transitioning from Professional Services through Solution Architecture into Product Management, Dmitriy is now busy developing new features for Mirantis OpenStack and Fuel project that make consumption of Private Cloud as joyful experience as it can reasonably be.)*

Successful rapid NFVi deployment - take 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During 2015 and 2016, many of the leading providers, such as Orange, AT&T or Telefonica have experienced some NFV lab trials, proof of concepts and some early NFV deployments. Based on these early deployments, NFV is perceived as a complex solution to be deployed with OpenStack. From 6WIND’s experiences, we have seen some lab trials which require many weeks before having an environment that is high performance ready. Most of the engineering efforts are spent in setting up the nodes because of the constraints related to the DPDK powering the NFVi virtual switching: setting up the proper DPDK PCI NICs, configuring the vswitch VLAN or VXLAN, trying to debug with tools like tcpdump, getting a SDN controller into the game, provisionning the security groups. Beyond 2016, getting rapidly a running NFVi will become critical for the maturity of deploying NFV. Fuel can be used to solve such rapid deployments of DPDK based NFVi.


* **Vincent JARDIN** *(Vincent Jardin is 6WIND's CTO. He is responsible to lead the architectures and developments for high performance packet processing. He co-founded the Quagga project, the open source project for routing, and remains one of its main contributors. He also helped found DPDK.org, an open source community that enables high performance network applications such as Network Functions Virtualization (NFV). Vincent has a strong knowledge on the packet processing technologies.)*

* **Irina Povolotskaya** *(Maintainer of Fuel Plugins SDK. Currently, drive different integration types like Fuel Plugins and OpenStack Drivers/Plugins validations. Constantly support dialog with Community to make the workflow clear, transparent and easy-to-go for contributors.)*

SFQM & Doctor: Keeping my (telco) cloud afloat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Additional statistics facilitate more resilient and performant telco/NFV clouds. It is vital to monitor systems for malfunctions that could lead to users' application service disruption and promptly react to these fault events to facilitate improving overall system performance. By providing OpenStack with system statistics from collectd, more data is available, which can be used for monitoring, performance analysis, fault detection, etc. using OPNFV Doctor-prescribed enhancements to OpenStack, action can then be taken to negate the effects of any faults in the deployment. Gaps have been identified and work to improve OpenStack to enable a more fault tolerant cloud environment is well underway. A key part of this work includes expanding the amount of data available about the system (e.g. DPDK and Open vSwitch statistics) and improving alarming functionality in OpenStack Aodh. This presentation is a follow-up of the last OpenStack summit in Austin.


* **Emma Foley** *(Emma is a Software Engineer in the Network Platforms Group in Intel. She joined Intel after graduating from the University of Limerick where she studied Electronic and Computer Engineering with a major in Robotics. She has worked mainly in the area of telementry for telco, working on making more statistics available for the OpenStack cloud, by enabling collectd stats to be used in Ceilometer.)*

* **Maryam Tahhan** *(Maryam Tahhan has been a Software Engineer at Intel Corporation for the last 6 years. Her work focus for the last two years has been on virtual switch , virtual switch performance and enabling Software Assurance features in DPDK. She is one of the engineers that enabled DPDK in Open vSwitch. Maryam also enabled user-space vhost (vhost-cuse) to help with the effort of accelerating guest network access. She leads two OPNFV projects, Software Fastpath service Quality Metrics (SFQM) and Characterize vSwitch Performance for Telco NFV Use Cases, a.k.a VSPERF.)*

* **Carlos Goncalves** *(Carlos Goncalves is a Software Specialist on the 5G Networks team at NEC Laboratories Europe in Heidelberg, Germany. He works in the areas of Network Functions Virtualization and Carrier-Cloud Operation & Management, developing novel technologies and tools for the design, deployment, operation and management of cloud-native virtualized network functions. He has been participating in open-source projects including OpenStack and OPNFV where he plays a committer role in OPNFV Doctor project. Carlos received his Master of Science degree in Computers and Telematics Engineering from the University of Aveiro, and prior to joining NEC he was a Researcher in the Institute of Telecommunications, Portugal.)*

NFV and Cloud Application Orchestration with TOSCA in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OASIS TOSCA is an industry standard for defining the orchestration of a cloud infrastructure and its application. It is supported by a large number of cloud service and tooling providers to model cloud applications and Network Functions Virtualization (NFV) workloads. During the OpenStack Newton release cycle, the version 1.0 of TOSCA simple profile in YAML is officially approved. This work serves as a foundation that has enabled us to extend TOSCA to support NFV orchestration modeling. In this presentation we describe how TOSCA is used across several facets of OpenStack with both general purpose and NFV based use cases. It is targeted for the OpenStack audience that is new to TOSCA and it's usage within OpenStack. We will briefly cover basic of TOSCA and NFV followed by up to date coverage of TOSCA integration in OpenStack. We will also show how a web application can modeled in TOSCA with demonstration of deploying it into an OpenStack cloud with OpenStack Heat and Tacker.


* **Sahdev Zala** *(Sahdev Zala is an IBM Advisory Software Engineer in the IBM Cloud Architecture and Technology organization. In his current role, Sahdev is Project Technical Lead (PTL) of OpenStack TOSCA-Parser and Heat-Translator projects. Both the projects are part of OpenStack Heat main program. He is a TOSCA Technical Committee member. He has also contributed towards LDAP enhancements in the OpenStack Keystone. Previously, he worked on developing IBM software for small and medium businesses and cross-product serviceability initiatives. He has authored IBM Redbooks, articles for developerWorks and ThoughtsOnCloud, white papers and technical documents on a variety of topics.)*

* **Bob Haddleton** *(Bob Haddleton is the Innovation Team Lead and a Cloud Solutions Architect in the Applications & Analytics business unit at Nokia, where he works to develop cloud-based solutions. Bob has over 28 years of experience in telecommunications software, 3G/4G wireless, and networking.  He joined the Cloud Innovation Center in 2013 and set to work using his extensive telecommunications software/networking and wireless knowledge to demonstrate how network functions can be virtualized and provide higher levels of reliability at lower costs.  He is a core reviewer for the Tacker, TOSCA Parser and Heat Translator projects, and is interested in the issues that surround deploying/configuring/monitoring/maintaining complex VNFs and Network Services.)*

* **Bharath Thiruveedula** *(Bharath Thriuveedula is software engineer in Imaginea Technologies Inc, Core reviewer and key contributor to the OpenStack Tacker, Heat translator projects. A contended individual who is passionate about open source technologies and an evangelist who is focussed to make his mark in the Cloud/NFV domains. He had worked on the custom solutions on the NFV Orchestration and his other interests are Containers and Distributed systems.)*

OPNFV: Architectural Planning & Deployment Deep Dive
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OPNFV Community has created architectural requirements defining an base NFV Platform deployment. In this session attendees will be introduced to the architecture established by the OPNFV community and the architectural prerequisites needed to deploy an NFV Platform according to OPNFV standards. Once a base architecture is discussed attendees will be introduced to the OPNFV Apex installer and walk through the required configuration files necessary to successfully execute a deployment using the Apex installer.


* **Dan Radez** *(Dan Radez has worked for Red Hat for 8 years from the company's headquarters office in Raleigh, NC. With Red Hat he's worked in systems release engineering, product engineering and development operations. Dan has been extended invitations internationally to present and participate in OpenSource communities. He has presented introductory / getting started sessions as well as architectural design sessions on OpenStack and OPNFV to international audiences. He's published the book OpenStack Essentials on getting started with OpenStack and is currently focused on involvement in the OPNFV project. Dan enjoys racing triathlons and tinkering with electronics projects.)*

* **Michael Chapman** *(I have been involved in the OpenStack community in various capacities since the Cactus release. I spent some time as a core reviewer of the puppet-openstack modules and have also spent time working as part of operations teams running OpenStack at scale. Currently, I work for RedHat on the upstream project Opnfv making the Apex installer better.  )*

STEER: An Implementation of Service Function Chains using Network Service Header (NSH) Encapsulation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Modern networks due to the explosion of connected devices obligates the need to support different levels of quality of experience whether it is for web browsing, online games, messaging etc. This level of experience is expected to be provisioned by the way the traffic is steered across the network by a set of network service functions (SFs) called service function chains (SFCs). The SFs need not reside on the direct data path and can reside on the cloud or data centers. In this talk and demo, we introduce a simplified solution for Dynamic SFC orchestration (STEER) which implements Network Service Header (NSH) encapsulation inside OpenStack as per IETF recommendation. The solution consists of a control plane (SFC Controller) with REST based APIs to configure the data plane (Traffic Classifier, Service Function Forwarder and Service Function Proxy). The STEER APIs makes SFC implementation and prototyping simple and fast. The solution supports both NSH-Aware and NSH-Un-aware SFs.


* **Shamik Mishra** *(Shamik Mishra is currently a Technology Director with the Cloud Innovation Team at Aricent. He has extensive experience in software development in cloud, wireless technologies and platform software. His research interests are Network Function Virtualization, Cloud Computing and Machine Learning. Shamik has a bachelor’s and a master’s degree from Indian Institute of Technology (IIT) Kharagpur.)*

NFVO / Enterprise CMP convergence
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV has embraced OpenStack as the preferred platform for NFV Infrastructure.  ETSI and other organizations have proposed models for the management layer above the NFVI/VIM while ignoring a lot of the early work done for Cloud Computing in the Enterprise.   We propose that the ETSI MANO functionality above VIM layer closely resembles current Cloud Management Platforms (CMPs) developed for the enterprise.  While Cloud Computing is new, enterprise CMPs have a had a head start on developing frameworks for managing cloud infrastructures.  Enterprise CMPs have already addressed many of the issues related to managing complex applications such as inventory, chargeback, and monitoring.  While the usual justification for embarking on a new development effort for NFV is that NFV has much greater performance requirements for the infrastructure, we propose that adapting current, mature enterprise CMPs to address NFV management requirements is a much faster approach than starting from scratch.


* **Pasi Vaananen** *(Pasi Vaananen is a NFV systems architect within the Red Hat Office of Technology, where he is responsible for advancing the Red Hat NFV system solution capabilities.  Currently, he is involved with many different initiatives such as, NFV MANO, system resiliency improvements and related community and standardization efforts. Mr. Vaananen has over 20 years of experience working on mission critical communications systems from companies such as Nokia, Motorola and Stratus. Previously, he held a systems architect role focused on SW & HW communication platforms, along with focus on other products in the broadband IP access and mobile network space. Vaananen is also currently participating in ETSI, OPNFV, OSM and Open-O activities, and has been previously active in efforts in e.g.  SCOPE alliance, IETF (MPLS and QoS), IEEE and  Broadband Forum. He holds over 10 US and international patents.)*

* **Aaron Smith** *( Aaron attended Swarthmore College as an undergrad and received his Masters and Ph.D. From Brown University in Electrical Engineering.  After a brief stay at Lincoln Laboratories, Aaron joined as an early member of a telecom startup and spent the next several years in either involved with system design or asic verification for telco.  After the telecom downturn, Aaron joined another early stage startup in an area now known as the "Internet of Things" helping to build one of the first cloud based HVAC control systems eventually reaching CTO of the company.  Aaron embraced early cloud efforts over the next few years at EMC and Stratus Technologies.  Aaron worked on an early CMP for OpenStack while at Stratus.  Aaron recently joined Red Hat in the NFV Partner Engineering group and has been able to continue working in the MANO and HA space.    "Cloud computing bears a striking resemblance to the work I was doing for my dissertation.  Cloud computing is very similar to massively parallel computing that was a research topic in the 80's and 90's.  It is rare to be able to work on what you studied in school"        )*

* **Ali Kafel** *(Ali Kafel is the Technical Product Marketing lead for Red Hat’s Service Provider solutions, responsible for technical thought leadership, industry insights, technical content creation and field enablement. Prior to Red Hat, Ali held leadership roles in various technical and business roles for several high-tech start-ups and multinational companies, including Stratus Technologies, Extreme Networks, Sonus Networks and Lucent Technologies (now Nokia). He brings over 20 years of experience in Telecom and Networking, including Carrier/packet Telephony, Mobility, Data Networks, Cloud Computing and NFV/SDN. He has written several industry articles and spoken at multiple industry events on NFV and other telecom & networking initiatives. He holds an MBA and a bachelor’s degree in physics from Suffolk University in Boston, MA)*

Dynamic Network Fabric for NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NFV deployments are moving away from POCs in labs to building a multi-site, NFV-compliant OpenStack solution. Many NFV use cases, such as vCPE, vBRAS and vBNG, all require dynamic scaling, agile resource balancing, and geo redundancy across multiple PoPs (Point of Presence).  We argue that the current OpenStack does not handle network dynamics well because the lack of network-aware resource allocation. In this talk, we present an OpenStack enhanced dynamic network fabric that offers high availability, manageability, and performance required for carrier-grade. To react to network dynamics, e.g., traffic spike, or resource failure, we provide underlay network aware PoP level rerouting. Within the PoP, we find the best resource reallocation via bandwidth-guaranteed VM placement. In addition, we use SLA verification to check if the reactions satisfy the SLAs. Our framework can free function-developers from attending to carrier class requirements.


* **Ying Zhang** *(Ying Zhang is a Senior Research Scientist in the Networking and Mobility Lab in Hewlett Packard Labs. Before joining Hewlett Packard Enterprise, Ying was a Senior Researcher in the IP and Transport Research group, Ericsson Research Silicon Valley, San Jose, CA. She was a member of the Yong Advisory Board to the CEO of Ericsson. She have 30+ patents and 50+ publications. She received the Ph.D. degree from the Electrical Engineering and Computer Science Department, University of Michigan, Ann Arbor, in 2009. Her research interests are in networking and systems, including Software-Defined Networking, Cloud, Internet and Cellular network management, Internet routing and network security.  )*

* **Mario Sanchez** *(Mario is a Research Scientist at Hewlett Packard Labs in Palo Alto, CA.  He received a Computer Science Ph.D. degree from Northwestern University in the Electrical Engineering and Computer Science Department and a Master’s degree in Telecommunications from the University of Maryland, College Park under the sponsorship of the Fulbright scholarship. He did his undergraduate studies at Pontificia Universidad Católica Madre y Maestra (PUCMM) in the Dominican Republic where he received his B.Eng. in Telecommunications.)*

* **Arun Thulasi** *(Arun Thulasi is the Chief Technologist for Platform Solutions in the Network Functions Virtualization Business Unit at HP. His responsibilities include defining, building and delivering NFV solutions bringing together technologies that form building blocks of a Next-Gen network (Cloud Operating Systems, SDN, Orchestration etc) into consumable, production-ready solutions. From an early career in kernel networking and performance analysis, his current focus areas have moved him into Software-Defined-X, Data Analytics and Cloud-native application & service development.)*

Virtual Network Functions (VNF) : From Machine to Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open Source and Network Function Virtualization (NFV) are forcing Telecommunication Companies to transform how they consume traditional network (and enterprise) functionality. For NFV, existing applications need to evolve in order to leverage the flexibility and elasticity of a distributed cloud platform like OpenStack. Virtual Network Function (VNF) vendors need to adapt their applications and make a “cloudification” process that will embrace OpenStack as the NFVi reference platform. One example of a “cloudification” transformation is Virtual Device Role Tagging. Traditionally, Network Functions (NFs) have ordered/named network interface card (NIC) devices in a consistent way based on either MAC addresses or PCI addresses. While the former still works,  it does not scale well in the cloud, and the latter is simply no longer possible. This talk will explain and demonstrate how to transform a traditional NF into a proper VNF using OpenStack specifications in terms of NIC ordering.


* **Ricardo Noriega** *(Ricardo is a Software Engineer in the Office of Technology working as NFV Partner Engineer at Red Hat. He's been doing R&D related to OpenStack for the past three years. He is passionate about new technologies (NFV/SDN) and everthing related to the Open Source world. Ricardo holds a MSc Degree in Telecomunications from Technical University of Madrid (UPM). He loves music, photography and outdoor sports.)*

* **Jean-Philippe Jung** *(Jean-Philippe (JP) Jung joined Red Hat in 2014 as part of the eNovance acquisition. JP is currently working as Engineering Partner Manager, interacting with partners in the OpenStack/NFV space to define, track and coordinate the development of upstream features. JP worked before as Technical Project Manager overseeing Openstack project deliveries in North America in agile mode, working on cloud migrations and feature development coordination. Driven by the love of technology, he previously mixed former infrastructure design and virtualization experiences with SAP skills to design and run extensive virtual SAP environments starting as early as 2006.)*

Scaling OpenStack to support large scale Compute – 500 Computes and beyond
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has known scalability limitations and scaling beyond 100-200 compute nodes per single OpenStack instance (Region) is a challenge. Scaling out to support 500 + nodes in a single datacenter is possible by deploying multiple OpenStack instances in that location but that adds extra overhead, cost and management complexity for tenants.   In this case study, we will share our performance and scale test results, fine tuning that ‘worked’ versus ‘did not work’ to support the scale and the architecture changes made to OpenStack deployment to support 500+ compute nodes per OpenStack region.   We have addressed bottlenecks in the messaging bus, Nova scheduler, and other key components, with a combination of: Control plane flexibility (moving services to different hosts) Configuration changes particularly with RabbitMQ and Nova Tuning the use of Ceilometer


* **Randall DeFauw** *(Randy DeFauw is Director of Cloud Solutions at Mirantis.  He has 15 years of experience in technology, ranging from software development to consulting to marketing and product management.  He spent several years working on DevOps and CI/CD process and automation, and most recently worked on replication infrastructure for large-scale Hadoop deployments.)*

* **Gnanavelkandan Kathirvel** *(Gnanavelkandan Kathirvel is a Lead Principal-Technical Architect at AT&T working on Cloud Strategy, Cloud Architecture and Network function Virtualization (NFV). Previously, Kandan led the architecture work to support Cloud convergence, building external cloud and Content Delivery network (CDN) for AT&T. He is currently focused on AT&T’s “Domain 2.0” initiative to virtualize large portions of AT&T Network services infrastructure on top of a common OpenStack based Cloud. )*

* **Haseeb Akhtar** *(20+ years of experience spanned across various roles within the research and product development of telecommunication systems, with a special concentration on wireless and packet based networks. In depth knowledge of IETF (TCP/UDP, IP, LDAP, SIP, SNMP, RTP/RTCP, IPSec, Mobile IP, Radius/Diameter etc.), wireless (TDMA, CDPD, CDMA, 1XRTT, GPRS, UMTS, WiMAX, LTE, 802.11x based WLAN etc.) and wireline (ANSI-41, ATM, ISUP, MEGACO/MGCP, PRI, SS7, TDM etc.) protocols. Always held key positions and led highly competent technical teams to come up with state-of-the art solution. Filed over 60 patents (to date, 36 of them have been granted by US, Australia and European patent authorities), authored several IETF documents (co-authored RFC 4283, contributed in RFCs 3344, 3588 and 3846 and co-authored other IETF drafts). Also authored conference papers and chapters in books on 3G/4G wireless networks.Specialties: Application driven End-to-End Solution Architecture, Performance of Applications and Services, Translation of Business Drivers into Technical Requirements, Technical Validation and Development of Business Cases.)*

Maturing OpenStack together to solve telco needs - A track by Nokia and Red Hat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For over three years, Nokia CloudBand and Red Hat have been partnering to address Telecom Service Providers’ (SP) specific needs in the network functions virtualization (NFV) space. As a community, we need to join forces to accelerate OpenStack maturity for carriers. In this track, we will discuss the performance challenges Telco SPs face and how we are working collaboratively to help solve them. Carriers have high expectations with NFV; they are looking for scalability, flexibility, extensibility, high asset utilization, integration of services, open competitive landscape, innovative ecosystem, and continuous deployments and upgrades. And they’re looking to open source innovations as a solution. However, the use of OpenStack for NFV poses some challenges. OpenStack needs to be enhanced to enable availability and scalability. In this presentation, we will jointly present our work solving some of the challenges described and explore the ones that still need to be solved as a community.  


* **Marcos Garcia** *(Marcos Garcia is Red Hat's OpenStack and NFV Technical Marketing manager. He has 12 years of international experience in IT, with studies in Telecommunications and Software Engineering, currently pursuing an MBA. Being a certified ITIL Service Manager, he has a broad understanding of service design and delivery, and a deep expertise operating cloud and virtualization systems using a DevOps approach. He is a co-founder of the Montreal Openstack community where he is a frequent speaker.)*

* **Ian Hood** *(High impact, results oriented professional with excellent technical and communications skills, business acumen, and team leadership. Experience in product and business strategy, global product launches, economic analysis, solutions marketing, and systems engineering.  Led the development and delivery of multiple software and hardware solutions, each of them generating market share growth and hundreds of millions to billions in revenue. Deep technical and business knowledge of Video, Mobile Internet, Carrier Ethernet, and Cloud-based networking architectures that span both Service Provider and Enterprise markets. Led many global product launches driving billions in incremental revenues.Comprehensive hardware and software technology depth across many domains including Carrier Ethernet, Mobile / Wireless, Security, Video, Software Defined Networks (SDN), Virtualization, Cloud-Based / Managed Services, Routing, and Optical Transport.)*

* **Iris Finkelstein-Sagi** *(Iris Finkelstein-Sagi brings over 20 years of experience and vision from her work in telecommunications, consumer tech, SaaS and more. Iris' expertise runs the gamut from product and communications marketing to strategy, PR, copywriting, events & campaign management, social media marketing, website design and lead generation.  As a super mom to three beautiful bandits Iris tries to squeeze baking, kick-boxing, swimming and obsessive reading into her spare time. She also used to be a professional designer.  Iris holds an MBA from INSEAD in Fontainebleau, France and a BS in Industrial Design from Tel-Aviv University.)*

osm.etsi.org identified gaps in OpenStack for high performance network applications.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Open Source Mano identified gaps and proposed solution from osm.etsi.org high perf networking use cases Use case is  virtual routers (vPE)  which interconnect from different regions, must reach the bandwidth of the physical lines (over 40 Gbps with small frame sizes), and be capable of managing directly ethernet framing, so that subinterfaces can be dynamically created and destroyed by the VNF based on in-band signaling. We achieved the goal with a combination of pci-passthrough and DPDK applications to achieve a scenario where 3 vPE could be automatically configured thanks to modeling and reach 99% usage of the 10G lines. We will deep dive into that issue and how we overcome them and directions we experiment. The examples being part of http://osm.etsi.org Release 0  can be reproduced.It is a call to the OpenStack community for providing the best solution for solving this use case.


* **Nicolas Thomas** *(Among the "founder" of the NfV realm, working on 2 of the initial use cases used to create ETSI NfV IG which defines and promote NfV. Member of ETSI NfV IG group before creation. 18 years of experience helping Telco use open platforms and ride the wave of IT innovation adapted to the telco space. Public speaker and hands-ons engineering. Former participant in Telco and platform standards : SAForum, Scope-Alliance, PICMG,  TC commite for OpenSAF and founder of CP-TA alliance. Currently NfV Solution Architect at Canonical, active participant to osm.etsi.org, ETSI NfV IG, OPNFV, Open-O https://fr.linkedin.com/in/nicolasthomasfr for details.)*

* **Francisco-Javier Ramón Salguero** *(Head of Network Virtualisation Initiative and NFV Reference Lab, Telefónica GCTO Unit | TI+DChairman of Open Source MANO Community Project | ETSI OSG OSM Since 2000 Francisco-Javier has worked in Telefónica. Former head of the IP Network Technologies group in Telefónica I+D, since 2008 he is head of the Network Virtualisation Initiative and the NFV Reference Lab in Telefónica GCTO Unit. Additionally, he has been chair of the Performance and Portability Expert Group and the Working Group of Testing, Experimentation and Open Source in ETSI NFV ISG  In April 2016, he was elected Chairman of Open Source MANO (ETSI OSG OSM) project on Management and Orchestration for NFV. His expertise areas are network virtualisation, IP network architecture, traffic capture and analysis, QoE modelling, network planning and dimensioning, routing and network performance. He is author of several patents and technical papers in these fields.   Francisco-Javier has achieved a Master Telecommunications Engineer qualification at the Technical School of Telecommunications Engineering of Málaga (Spain), 2000, and a Master's Degree in Economics at UNED (Spain), 2006.)*

* **Yann Rapaport** *(As Product Manager for 6WIND, Yann works closely with sales, marketing and R&D to define and implement the 6WINDGate and Speed Series roadmaps in coordination with 6WIND’s ecosystem of partners and customers. Yann has held diverse positions at 6WIND, starting as a QA engineer in 2001 to managing the software outsourcing team in Vietnam in 2004, then serving as a pre-sales engineer in the US in 2008 and managing the customer support team back in Paris in 2009. Yann holds a MSc in Computer Science, with a major in Systems and Networking, from ENSIMAG in France, which specializes in Computer Science and Applied Mathematics.)*

Building NFV Cloud for IT & Telco
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With VMs & VNFs needing faster and more reliable throughput in OpenStack environments, high performance technologies like DPDK, NUMA, Hugepages, Real Time Kernel, Transparent VLANs (802.1q via vNIC), and SR-IOV are becoming more and more relevant. IoT & HPC are also presenting themselves as high density workload use cases with a need for low latency throughput. We take you through all the lessons learned in choosing the right open software, hardware layout, and OpenStack features related to performance and stability. We’ll talk through the advantages of DPDK, Non Uniform Memory Access (NUMA), and Hugepages, some of the lessons learned and the next steps leveraging Mitaka+ for your needs. We will also touch upon Tacker (VNFM & VNFO) and ODL (SDN or NVP) as example case study of expanding upon NFVI out into MANO integration.  


* **Eric Lajoie** *(Eric Lajoie is a OpenStack & NFV Architecture Consultant for HP Helion Professional Services (PS) – Helion OpenStack, Germany. In his current capacity, Eric is responsible for end to end solution design, be it IPv6, EPC, or virtualization solutions. His key interests and achievements are in design and implementation of carrier grade Helion OpenStack solutions as well as integration with SDN, EPC, LTE, VoLTE, Femto, M2M, VMware, and all flavors of Linux including RHEL, Ubuntu, Debian, CentOS, and Gentoo. He is responsible for solution, design, service implementation and assessments related to service providers environments.)*

Automating the VNF on-boarding process using OPNFV Functest and OpenStack Heat templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The NFV story is built around virtualizing network functions. To achieve inter-operability, VNF setup and fulfillment must be based on a common information model, which today is specified by ETSI. For acceptance by CSPs, the VNF should be validated using a universally accepted testing method.  This presentation and demo will define an end-to-end VNF validation process,  from VNF descriptor definition to testing the VNF, using the OPNFV Parser and Functest projects with an on-boarding wizard tool built on standards. The web-based wizard guides the user in defining the VNF Description details and to define the VNF setup metadata in an implementation agnostic, ETSI standards based format (ETSI NFV Yang format). The wizard then converts this format into the implementation format consumed by the VIM layer. In this case format is converted to OpenStack Heat Orchestration templates using the Parser project in OPNFV. We will also talk about ongoing work for conversion to TOSCA NFV profile.


* **Madhu Kashyap** *(Over three years of OpenStack community engagement, now focused on all things NFV. Blogged on OpenStack site - http://superuser.openstack.org/articles/bringing-nfv-into-openstack-with-tacker Expertise in cloud networking, virtualization, OpenStack, data center with broad product management responsibilities. )*

* **Vinayak Ram** *(Architect at HPE)*

* **Vasu Sankhavaram** *(Vasu Sankhavaram is Chief Technologist/Strategist within Hewlett Packard Enterprise’s NFV business unit, focused on strategy and execution of the OpenNFV partner program. Prior to this, he was Chief Strategist of DevOps and Cross Portfolio Architecture Alignment within HP Software. Earlier, he provided product management leadership and strategy within HP's Cloud Automation portfolio, with a focus on application release and deployment, and hybrid cloud automation. Vasu has been with HPE since 1995 and has worked in all phases of the software lifecycle – Innovation, R&D, Testing, Support, Consulting, Product and Solution Management and Strategy. During that time, he led several ground breaking projects in the areas of telecommunications and enterprise software management solutions for leading Fortune 500 Telecom and Media companies. Vasu is passionate and driven about product and solution development, ideation, evangelization and being a student for life. He holds an MBA degree from U.C. Berkeley and a B.E in Electronics & Communications Engineering from University of Mysore, India.   Vasu and his wife have their hands full with a 13-year old son and 3-year old twin daughters)*

OPEN O (Orchestrator)
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In early June, the industry's first end-to-end open source community focused on SDN/NFV Orchestration, OPEN-O was launched.The primary goal for OPEN-O is to accelerate the commercialization of SDN and NFV, and ultimately, the transformation of carrier operations.OPEN O has approved 5 projects in order to have 1st release by the end of 2016, GSO project will provide end to end service orchestration across multiple SDN and NFV domains. NFVO project is doing almost same as MANO architecture which is specified by ETSI NFV ISG. SDNO will work with two types of open source controller: ODL and ONOS to coordinate the telecomm access and metro network. Common tosca project is mostly cover parser, catalogue, model design and workflow engine. Common services project is mostly dealing with micro service, API gateway for pub/sub, et al. This speech will dive into the detail of the implementation of OPEN O, and introduce each project how they implement and detail design of the modules.


* **Hui Deng** *(Hui Deng is Principal Staff and is leading SDN/NFV technical strategy at China Mobile. He is the current chairman of OPEN O project; He is also the treasurer and BoD member of OPNFV. He also serves as the chair of Platform & Ecosystem WG in SDN/NFV Industry Alliance (China). Hui Deng has organized and chaired the NFV workshop 2015 (Beijing), NFV Workshop (Shanghai) 2015, SDN/NFV Open Source Workshop 2016 (Beijing). And he also made speeches in MWC 2015 OPNFV Panel, China DPDK Summit, China SDN/NFV Conference, Intel Network Summit, and Huawei Cloud Conference in 2015.)*

Running CI on a DIstributed OPNFV Infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OPNFV is an open source community focusing on accelerating the evolution of NFV products and services through creating an integrated platform which includes components like OpenStack, OpenDaylight, KVM, etc. In order to build a system that fulfills the requirements of VNFs, it also collaborates with the underlying upstream projects to fill any gaps. In addition to addressing the telecom needs, our activities cover an E2E flow of integrating, deploying, validating and verifying the platform. This provides many challenges as we deal with a diverse and complex project. This presentation provides an inside view of the challenges we were facing from the early days to the latest release as well as goals for the future. You will be part of our journey as we will show how the different deployment tools, test frameworks and lab infrastructures distributed across 3 continents work as collective whole. Particularly outlining how we managed to establish OPNFV CI within this diverse environment.


* **Fatih Degirmenci** *(Fatih is Principal Software Developer working at Ericsson. He is specialized in CI/CD, Software Development Infrastructure, and automation. He has more than 10 years experience and involved in several large scale CI/infrastructure projects during his career. He is Project Technical Lead for the OPNFV Release Engineering Project and core committer for several other OPNFV projects. Before Ericsson, Fatih worked for Havelsan and provided expertise to Havelsan's customers such as BOEING and BAE Systems.)*

* **Jack Morgan** *(Jack Morgan is a Network Software Engineer working for Intel.)*

Enhanced Platform Awareness (EPA): boosting dataplane performance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network Function Virtualization (NFV) is all about deterministic, maximal network packet processing performance. The Openstack community has implemented various technologies towards this goal, but those need carefully configured and combined to be effective. This talk will show how to configure Openstack to provide this performance for NFV workloads using Enhance Platform Aware (EPA) features already available, such as CPU pinning, Huge Pages, PCI pass-through and Single Root I/O Virtualization (SR-IOV), showing best practices applied in Telefonica NFV Reference Lab with Red Hat OpenStack Platform. NFV workloads require to assign dataplane interfaces to guests in order to maximize Virtual Network Function (VNF) performance. This is usually accomplished by allowing the VNF to rely on DPDK technologies, alone or in conjunction with the pass-through of physical and virtual functions (the latter commonly denominated SR-IOV) from the host to the VNF guests.


* **Ricardo Noriega** *(Ricardo is a Software Engineer in the Office of Technology working as NFV Partner Engineer at Red Hat. He's been doing R&D related to OpenStack for the past three years. He is passionate about new technologies (NFV/SDN) and everthing related to the Open Source world. Ricardo holds a MSc Degree in Telecomunications from Technical University of Madrid (UPM). He loves music, photography and outdoor sports.)*

* **Jean-Philippe Jung** *(Jean-Philippe (JP) Jung joined Red Hat in 2014 as part of the eNovance acquisition. JP is currently working as Engineering Partner Manager, interacting with partners in the OpenStack/NFV space to define, track and coordinate the development of upstream features. JP worked before as Technical Project Manager overseeing Openstack project deliveries in North America in agile mode, working on cloud migrations and feature development coordination. Driven by the love of technology, he previously mixed former infrastructure design and virtualization experiences with SAP skills to design and run extensive virtual SAP environments starting as early as 2006.)*

* **Antonio López Gracia** *(-)*

VMWare Integrated Openstack with Gigaspaces Cloudify Orchestration for NFV - technical deep dive
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session we will do a technical deep dive on  Cloudify  orchestration of  VMware Integrated Openstack resources through its Openstack plugin, and how to set up an configure this environment to make it Carrier-Grade and produciton ready.  In addition, we will explain how to orchestrate applications on multi-vim openstack environment where some resources are provisioned by VMware Integrated Openstack endpoints while others are provisioned via 3rd party Openstack distributions. We will discuss the entire service life cycle, from blueprinting, onboarding, scaling and deommissioning in this integrated platform.  In addition, we will explore how VMWare supplements the solution with its vRealize OPS product integration for unified and consolidated logging across Openstack, VMWare and Cloudify to present a unified FCAPS view of the entire infrastrcture. 


* **Vanessa Little** *(With over 25 years experience in various roles in network and system architecture, mobile video system architecture and governance in both telco and  retail sectors, Van has developed a diverse toolset.  Van spent much of her career as a contractor, working for every telco as well as major retailers in Canada over the years.  Having worked as everything from unix sysadmin to Chief Technical Officer with a number of leadership roles in between, Van has contributed to technologies from mobile, enterprise data centre, multi-national networks and beyond.  Now at VMware as the Sr Manager - Global NFV Ecosystem Architecutre Van is focused on leading integrated architectures that integrate all of the NFV partners across the globe in useful NFV solutions that solve for specific problems.  This role has her speaking at conferences around the world, and spreading the word about the strength of the NFV Ecosystem. Van attended the University of Toronto where she majored in Computer Science and Astro-Physics.  Van currently makes her home in Toronto Canada, where she enjoys spending her free time playing hockey, tennis and fishing.)*

Design Case Study - IMS Core deployment with Metaswitch and Cloudify on VMware Integrated Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Design Case Study - IMS Core deployment with Metaswitch and Cloudify on VMware Integrated Openstack Metaswitch ClearWater is a popular open source vIMS reference implementation with multiple VMs, networks and cross dependencies. In this talk we will discuss how Cloudify can Orchestrate Metaswitch ClearWater on VMware Integrated Openstack and manage its operational aspects and life cycle. This is a technical session that will discuss the entire service life cycle of this deployment from blueprinting, deployment, scaling and decommission. 


* **Vanessa Little** *(With over 25 years experience in various roles in network and system architecture, mobile video system architecture and governance in both telco and  retail sectors, Van has developed a diverse toolset.  Van spent much of her career as a contractor, working for every telco as well as major retailers in Canada over the years.  Having worked as everything from unix sysadmin to Chief Technical Officer with a number of leadership roles in between, Van has contributed to technologies from mobile, enterprise data centre, multi-national networks and beyond.  Now at VMware as the Sr Manager - Global NFV Ecosystem Architecutre Van is focused on leading integrated architectures that integrate all of the NFV partners across the globe in useful NFV solutions that solve for specific problems.  This role has her speaking at conferences around the world, and spreading the word about the strength of the NFV Ecosystem. Van attended the University of Toronto where she majored in Computer Science and Astro-Physics.  Van currently makes her home in Toronto Canada, where she enjoys spending her free time playing hockey, tennis and fishing.)*

How to help your networking peers roll out NFV solutions and be a hero while at it.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You must have heard your colleagues in the carrier/service provider group talk about OpenStack extensively.  If you're attending OpenStack summit you know why, but how could you help your colleagues? What is it that they are looking for?  In this session we will answer these questions and will explain how your existing VMware infrastructure and the expertise could be turned into an OpenStack-compliant Infrastructure as a Service (IaaS) in which your networking colleagues could deploy their virtual network functions.  By no mean is this a product pitch, but rather a deep dive into the requirements NFV puts on your infrastructure and one experience-based approach to its solution.


* **Jambi Ganbar** *(Jambi leads the solution team responsible for design and validation of VMware's vCloud NFV solution. With 18 years of background in telecommunications Jambi has a great perspective on the transformation that is pushing telcos towards virtualization.  Jambi has contributed to the IETF and ETSI NFV ISG and have been escorting various vendors and service providers in their transition to NFV.)*

* **Arvind Soni** *(Arvind leads OpenStack efforts at VMware. Arvind manages product strategy and execution for integrating OpenStack with VMware products. Arvind is also the lead PM on development of VMware’s OpenStack Distribution, VMware Integrated OpenStack.  Arvind has over 10years of technology industry experience. Arvind holds an MBA from University of Chicago, Booth School of Business. He also has Masters in Computer Sc from North Carolina State along with Bachelors in Computer Sc from IIT Bombay.)*

Achieving multi site VNF network readiness with less OPEX
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Two of the primary cornerstones for NFV have been the reduction of OPEX, and the optimization of COTS resources. However, automating provisioning tasks across multiple, and possibly even heterogeneous, sites is proving to be quite challenging. For this reason, numerous use cases and requirements have been created around the matters. This presentation will show how to use the OpenStack Tricircle project to automate the network provisioning across multiple sites, as a precursor to very fast VNF networking via FD.io's VPP (Vector Packet Processing) project. 


* **Ash Young** *(I've been working in open source since 1993, primarily in RAID, file systems, iSCSI, and various other kernel/storage areas. I designed the first Linux and open source-based NAS appliance in 1997 at NetAttach, which was acquired by VA Linux Systems. I also developed the industry's first unified block/file stack back in 2003. I'm  a developer in OPNFV, FD.io, OCI, and in varios IoT communities.  I do also run an open source non-profit, Yunify, that is focused on creating software to help spark the NFV ecosystem. With the standards community deciding on OpenStack as the Virtual Infrastructure Manager (VIM) of choice, I am also very interested in building out the necessary infrastructure components to make this more optimal. This requires me to be fairly impartial as I look at all the various efforts, which might help bootstrap that ecosystem.  As the PTL for ONOSFW, I lead and develop a lightweight framework to instrument the NFVI (NFV Infrastructure). Currently, the first release of ONOSFW can be found in the Brahmaputra release of OPNFV and is still building out the network framework. The next release will add a unified Intent interface to the NFVI Networking.  Lastly, I am also one of only a few developers working in the area of NVMoE. NVMe (Non Volatile Memory express) is a storage protocol that was designed to remove the CPU as the storage bottleneck. However, due to the architectural constraints of PCIe, the only way to share NVMe storage, in a disaggregated fashion, places the bottleneck back in the CPU used to share access to the protocol. NVMoE places this technology onto an Ethernet fabric and allows the client to talk the NVMe protocol over Ethernet, in a fashion that eliminates the CPU bottleneck. I currently work on kernel, FTL, flash, drivers, and management software to help support this important ecosystem building block. )*

A  generalization of the OpenStack networking model for L2 VPN MEF compliant SD-VPN service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A strong analogy between the network models of Neutron and SD-VPN is presented. Using this analogy, a MEF compliant SD-VPN service was implemented while leveraging the generic network virtualization infrastructure of NetVirt in ODL. The resulting VPN service offers L2 and L3 connectivity between geographically remote locations each based on a local OpenFlow switch. A mapping service is used in order to allow information exchange between these locations for the purpose of MAC address, IP address and route distribution. The sites are interconnected by an overlay network carried on top of an arbitrary IP network. The presented solution allows for a MEF compliant SD-VPN service without dependency on technologies such as MPLS, strongly simplifying this process.


* **Gal Mainzer** *(In his role as Engineering Director at Hewlett Packard Enterprise, Gal is responsible for leading the architecture, design and implementation of all layers of HPE CSB’s ODL based SDN solution for the telco vEPC, vCPE & SFC usecases. Prior to his current role, Gal served as the senior software engineer of ConteXtream where he managed the J2EE engineering team of distributed systems and the company’s first tier 1 service provider SDN deployment. Gal brings more than 15 years of experience in leading, building, architecting and deploying small, medium and large scale products, including more than ten years focused on large scale, tier 1 carrier grade and enterprise products. Gal has held senior-level positions with Cisco and GOI and holds both a M.Sc and B.A. in Computer Science from Ha'Universita Ha'Petuha in Israel.)*

* **Ariel Noy** *(Ariel Noy, CTO, HPE ConteXtream Ariel Noy is responsible for setting the technical direction and architecture for HPE ConteXtream, a business unit of Communications Solution Business. Ariel co-founded ConteXtream and served as CTO for 9 years. Prior to ConteXtream, he was a technical leader at Cisco Systems, which he joined as a result of its acquisition of Sheer Networks, where he was a co-founder CTO and VP Engineering for 6 years. Prior to this, he led the architecture and design of a large-scale network management project at 3Com. Ariel holds a B.S. in Math and Computer Science from Tel Aviv University.    )*

* **David Goldberg** *(David is responsible for leading the architecture , design and implementation of Hewlett Packard Enterprise's OpenDaylight-based telco SD-WAN solution. David led HPE’s contribution to the LispFlowMapping project, and is now acting as the PTL of the UNI Manager project. Prior to HPE,  David was responsible for the development of network analysis tools during his army service in an elite technological group in the IDF Intelligence Corps. David holds a BA in Computer Science and Management (cum laude).)*

Design Case Study - VoLTE core solution with Cloudify and Athonet on VMware Integrated Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Design Case Study - VoLTE core solution with Cloudify and Athonet on VMware Integrated Openstack In this case study we will detail the NFV VoLTE core solution by Athonet and Cloudify on top of VMWare Integrated Openstack cloud environment. The solution is comprised of  vEPC, vIMS VNFs. The case study showcase how one can rapidly deploy this entire solution from scratch and go from zero to functional infrastructure in a mere 15 minutes.  We will demonstrate how Cloudify can orchestrate these VNFs and service chain them together, as well as scale the capacity in runtime. The demo will include actual handset establishing a VOIP call and how the call continues uninterrupted during scaling out of the infrastructure. This session will conclude with us doing a live call with members of the audience that will use the virtual infrastructure we just built in the session!


* **Vanessa Little** *(With over 25 years experience in various roles in network and system architecture, mobile video system architecture and governance in both telco and  retail sectors, Van has developed a diverse toolset.  Van spent much of her career as a contractor, working for every telco as well as major retailers in Canada over the years.  Having worked as everything from unix sysadmin to Chief Technical Officer with a number of leadership roles in between, Van has contributed to technologies from mobile, enterprise data centre, multi-national networks and beyond.  Now at VMware as the Sr Manager - Global NFV Ecosystem Architecutre Van is focused on leading integrated architectures that integrate all of the NFV partners across the globe in useful NFV solutions that solve for specific problems.  This role has her speaking at conferences around the world, and spreading the word about the strength of the NFV Ecosystem. Van attended the University of Toronto where she majored in Computer Science and Astro-Physics.  Van currently makes her home in Toronto Canada, where she enjoys spending her free time playing hockey, tennis and fishing.)*

The Open Source Disruption in NFV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There is a massive shift in the NFV world to open source tooling and technologies, from companies like AT&T with their ECOMP project to other players such as OPNFV, ONOS, and OPEN-O, not to mention ETSI and MEF. However, this transformation, although positive for end users, means certain large corporations now have an inherent conflict of interest due to their business models being mostly driven by proprietary hardware. Some names include Cisco, Ericsson, Nokia, and Amdocs. In this talk, we will discuss the open source NFV vs. proprietary vendor struggle, where the NFV world is headed, and ways proprietary vendors can work to join the open source disruption without having a disastrous effect on their bottom lines.


* **Sivan Barzily** *(Sivan is Director of Product for Cloudify at GigaSpaces, working on an open source and open standard cloud orchestration platform that automates and manages complex services throughout their entire lifecycle for telcos and enterprises. Prior to GigaSpaces Sivan was a Product Line Manager at Alcatel Lucent, building an NFV MANO solution. Sivan is an active contributor to the TOSCA standard, and is an expert at the areas of networking, cloud, and service management. Read her posts at the Cloudify blog.)*

* **Arthur Berezin** *(Arthur Berezin is an active member of the OpenStack community and a hands-on OpenStacker since the early Essex release of OpenStack in 2012. During this time Arthur has built multiple production data centers based on OpenStack, helped dozens of organizations in planning their OpenStack environments, and in executing their software defined data center strategy. Prior to OpenStack, Arthur worked on KVM virtualization management project oVirt/RHEV and open source virtualization management technologies for mission critical environments. Arthur is the Director of Product for *Cloudify* at GigaSpaces working on an open-source and open-standard cloud application orchestration platform with cloud aware applications in mind that run natively on OpenStack and other private and public clouds. Prior to Cloudify, Arthur was a Senior Technical Product Manager for OpenStack at Red Hat and Product Owner of Keystone, Heat, Horizon, RHEL OpenStack Platform Installer (Foreman/Puppet based Project Staypuft), Packstack, and OpenStack High Availability. In the past 14 years, Arthur has served in various management and technical positions in the high-tech industry, including working as a founder and technical lead of a start up, a product line lead, Linux consultant, technical pre/post sales, and as a Linux Instructor for Red Hat Certified Engineer (RHCE) exams. You can find Arthur on Twitter as @ArthurBerezin or on his blog at www.Berezins.com.)*

Data Intensive Virtual Network Functions on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The successful adoption of NFV depends on the ability of cloud infrastructure to deliver sufficient performance compared to today's proprietary network appliances. Generic hardware isn't equipped, nor configured, to handle this kind of load, and as a result, can't run with the necessary performance large carriers & Telcos require. To achieve such performance, you need advanced processor & networking technologies embedded in silicon and in PCIe devices, but even so, you need to ensure your VNFs are ultimately able to leverage these capabilities. In this talk, we'll show how NFV throughput performance varies depending on proper VNF workload placement configuration, by declaring what the VNF requires from the hardware (SR-IOV, DPDK, etc) and ensuring proper matching & configuration with the OpenStack NFVI. We'll also see how Enhanced Platform Awareness & smart orchestration are enablers for such extreme performance.


* **Sivan Barzily** *(Sivan is Director of Product for Cloudify at GigaSpaces, working on an open source and open standard cloud orchestration platform that automates and manages complex services throughout their entire lifecycle for telcos and enterprises. Prior to GigaSpaces Sivan was a Product Line Manager at Alcatel Lucent, building an NFV MANO solution. Sivan is an active contributor to the TOSCA standard, and is an expert at the areas of networking, cloud, and service management. Read her posts at the Cloudify blog.)*

On the Journey to Cloud Native VNFs on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Explore a platform that can bring VNF development closer to becoming fully cloud native.   Network functions have advanced significantly from their original dedicated hardware. Virtualized Network Functions (VNFs) based on Service Oriented Architecture (SOA) provides the underpinnings of much of the recent work around Network Function Virtualization. While there are containerized VNFs, running in a container does not necessarily mean it is cloud native. In general, VNFs are not cloud native yet.   In the Use Case section, several questions will be considered to determine whether your service may or may not be cloud native. While some VNFs have challenging requirements and are difficult, the majority can be made cloud native.   We will review what it means to be cloud native and explore a platform that can help bring VNF development closer to being truly cloud native on an OpenStack cloud.


* **Bryan Murray** *(Bryan has been working with OpenStack since Essex, initially in creating an easy to use distro, and later in developing NFV applications that use OpenStack.)*

* **Jay Beltur** *(Jay has worked with OpenStack since Essex.)*

* **Jeff Walls** *(Jeff has worked with OpenStack since Essex, primarily working in the Horizon dashboard. He now works for the NFV business unit within Hewlett Packard Enterprise where he is a member of the architecture team currently working on VNF microservice architectures. He has a passion for programming and is currently excited about Go. In his spare time, Jeff coaches competitive youth baseball, runs half and full marathons and hopes to run ultramarathons one day.)*

Project: OPNFV - Base system functionality testing (Functest) of a vIMS on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network Functions Virtualization (NFV) based on OpenStack as the VIM (virtual infrastructure manager) is a growing use case among leading Telcos around the globe. Orange Labs have been leading the “OPNFV - base system functionality testing” project that provides a comprehensive testing methodology, test suites and test cases to test and verify OPNFV Platform functionality that covers the VIM and NFVI components. This project uses a "top-down" approach based on ETSI NFV use-cases and open source VNFs for the functional testing. This session will dive into the functional testing of a vIMS system based on Metaswitch's Clearwater, coupled with the open source tools Cloudify and Jenkins, for the full lifecycle orchestration and management including the monitoring, healing, scaling and software upgrade of such a complex system.


* **Sivan Barzily** *(Sivan is Director of Product for Cloudify at GigaSpaces, working on an open source and open standard cloud orchestration platform that automates and manages complex services throughout their entire lifecycle for telcos and enterprises. Prior to GigaSpaces Sivan was a Product Line Manager at Alcatel Lucent, building an NFV MANO solution. Sivan is an active contributor to the TOSCA standard, and is an expert at the areas of networking, cloud, and service management. Read her posts at the Cloudify blog.)*

* **Morgan Richomme** *(Morgan works as Network architect for innovative services in Orange. He is Orange Network open source evangelist and OPNFV representative. Primarily involved in IMS deployment for Orange affiliates, he managed the project Emerginov (OW2), an open source PHP PaaS that has been deployed in Africa. He has 10 years' experience in managing open source solutions. He is engaged in OPNFV testing group, as Functest Project Leader.)*

* **Valentin Boucher** *(Valentin has been an apprentice Network Architect within Orange Labs since 2014. He is studying at ENSSAT, Lannion. His apprenticeship has primarily focused on NFV; deploying an OPNFV cluster and testing orchestration solutions. Indeed, Valentin has even contributed to the OPNFV standard, through the integration of a fully functional vIMS deployment using continuous integration. Additionally, Valentin is a passionate member of the Fablab group at Lannion and is also working on a LoRa based tracking system.)*

Infrastructure and service modeling strategies to deploy NFV in production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will review the findings of operators, tool and platform vendors, and telecom system integrators to when dealing with the challenges of obtaining meaningful and actionable information when designing and deploying modern carrier-grade services in real world scenarios.  NFV and OpenStack provides vendors and network operators with transformational capabilities for service innovation and architectural flexibility. However, this flexibility introduces significant complexity in VNF service modeling, performance testing, verification and ongoing maintenance.   The presenttion will explore how network operators can successfully manage OpenStack-based NFVI and VNF selection and onboarding. Including how automation frameworks together with comprehensive and integrated verification procedures are being used to accelerate service delivery, verify interoperability, performance, reliability and security.  


* **Michael Lazar** *(Michael Lazar is a veteran of the telecom industry, and has held C-level positions in system design, custom engineering and software development for the last two decades. He joined DataArt in 2016 to lead the company's telecom practice, focusing on the most demanding areas of the marketplace - systems performance, NFV, SDN & telecom security. Prior to joining DataArt, Mr. Lazar was Chief Technology Officer of Veloxum/Ambicom Holdings where he was responsible for developing system optimization software, and before that CTO of Network Physics, where he led the design and development of Voice over IP (VoIP) and Financial Information exchange (FIX) monitoring software. Prior to the CTO role, Michael was VP of Customer Advocacy at Network Physics, in charge of worldwide pre-sales engineering, post sales support, and custom engineering. Prior to Network Physics, Michael held senior technical roles at Datatec Systems and Spirian Technologies, Inc. Mr. Lazar holds a Bachelor of Science Degree in Physics from New York’s Queens College and holds a patent for Systems and Methods of Tuning an Operating System, Application or Network Component.)*

* **Pierre Lynch** *(Pierre Lynch has been working in the wireless testing industry for 20 years, and is now a Lead Technologist, responsible for representing Ixia at various SDOs, forums and open source communities. He is currently the vice chair of the ETSI NFV ISG TST Working Group. He has been with Ixia since 2006, when he helped start and then guided the development of the wireless core network testing product line.)*

* **Artur Tyloch** *(Artur Tyloch is Canonical’s Global Telco Program Lead focusing on SDN and NFV requirements for Ubuntu customers and partners, as well as Telco ISV applications enabled through Canonical’s cloud ecosystem. Prior to Canonical, Artur ran software innovation projects and solutions at Nokia Networks Silicon Valley innovation center. He was also the architecture team lead, where he worked on various IoT, and BSS products and the core platforms. Artur specializes in NFV aspects of OpenStack enabled cloud architecture and is active in OPNFV, ETSI and other telco community and standards initiatives.)*

Out of the Box Resiliency for Network Function Virtualization
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many virtual network functions available today are software representations of hardware and can consume large quantities of dedicated resources, which often sit idle, to meet capacity requirements. By developing a framework that shifts the burden of providing resiliency away from the NFV vendor towards the operator, we believe many of the obstacles impeding the ability to create cloud solutions which meet capacity needs and optimize resources can be removed. AT&T has devised a framework for NFV that provides resiliency features as services that can be leveraged by the NFV vendors. This allows vendors to focus on function versus cloud resiliency and helps eliminate legacy dependencies from the NFV as resiliency breakpoints. Another aim is to help encourage vendor participation by facilitating resiliency that can be customized to an operator’s specification. Vendors can then avoid having to create vendor specific resiliency implementations for each target operator.  


* **Dave Senestraro** *(30+ year experience in the wireless /telco industry. Experience in both operator space and NFV space having worked for multiple carrers and network element suppliers)*

* **Geetha Sankuratri** *(Geetha is a Director with the Software Resiliency Engineering group at AT&T. She has been with the company since 2002. Prior to this role Geetha has worked on a wide range of roles with leading operations and production support teams as well as application and technology portfolio teams.)*

* **Bryan Spencer** *(Active in Open Source community)*

Benchmarking hardware accelerated OVS with VSPERF
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network Functions Virtualization involves using cloud management technology like OpenStack and deploying the network functions on COTS servers (scaling out) to achieve high aggregate throughput. For NFV deployments to work properly, it is very important to ensure that the virtual switching function in the NFVi does not become a data bottleneck, starving VNF applications.  To address this problem, an emerging trend has been to accelerate the virtual switching function in hardware.   For this reason,  precisely understanding the performance characteristics of the virtual switching function, with comparison to accelerated and non-accelerated implementations, is critical.  In addition, the testing of the virtual switching function must be done under conditions that closely approximate the real-world traffic load on the target VNF applications.  This is often difficult with existing test methodologies, but can be improved as we will discuss in this presentation.


* **Pervaze Akhtar** *(Pervaze Akhtar has extensive and varied background in the the computer industry. He has been a (Unix) kernel developer and managed development of software for Fore Systems ATM switches. He has also managed and developed file systems and NAS systems. Most recently he is VP of software engineering at Netronome and is also involved in performance testing of their hardware accelerated OVS and vRouter products.)*

Telemetery for NFV; A tale of  Meters, Samples and Unicorns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

SevOne’s service provider customers leverage OpenStack as to virtualize the infrastructure that drives their wireless business.    For this use-case, SevOne has focused on the Ceilometer metering, as a common point of VNF integration, to collect performance data.  Ceilometer holds the promise to deliver on a normalized method to collect key performance samples regardless of vendor, function or network reachability -- a long-standing customer unicorn. However, when developing an actual performance management solution that combines OpenStack Ceilometer metrics with Key performance indicators from virtual network functions, SevOne ran into several data collection challenges. This customer then partnered SevOne with RedHat, who architected the customer's Kilo based cloud, to drive new solutions to improve the experience in future versions of OS.  Through enhancements to Ceilometer, with the Gnocchi blueprints, this can now be realized.


* **Franck Baudin** *(Franck Baudin is in responsible for the NFV technical strategy of  within Red Hat’s OpenStack product management team. He  currently focuses on providing high performance network connectivity to VNFs: SR-IOV, OVS-DPDK, VPP.   In his previous role within the Qosmos CTO team, Franck was responsible for technical Proof of Concepts (PoCs) and prototyping of emerging products, such as Service Function Chaining PoC in Telekom Malaysia lab and Qosmos L7 classification plugin. He also designed and led the implementation of DPI integration within DPDK based VNFs.   Previously, Franck was managing the engineering team at 6WIND, where he defined the outsourcing strategy and resource allocation between France and China. On the technical side, his responsibilities included the development of strategic projects in the areas of SDN, Open vSwitch, and Intel DPDK. Included in his responsibilities, he was also driving development of the 6WINDGate packet processing software, focusing on performance improvements and support for different types of CPU architectures: x86, Cavium, Broadcom, and Freescale. He also led the porting of 6WIND portfolio from FreeBSD to Linux.   Franck started his career as a Software Development Engineer at Thales Aerospace, working on projects such as the Dassault Rafale aircraft radar software. He holds a Master's degree in Engineering from French engineering school ENSEA.  )*

* **Pradeep Kilambi** *(Software/Systems Engineer with experience,* Overseeing all phases of software/systems development lifecycle including systems research, design, and Development.* Working with open source projects and community; major contributions to various projects part of OpenStack, puppet, RHEL, fedora etc. * Working in agile, fast paced and highly demanding environments.* Interacting with internal and external customers with outstanding technical and communication skills.* Various US patent applications in the area of Cloud & Systems Management* Enthusiasm to quickly learn new concepts and technologies and to coach others in their use.Areas of Interest/expertise:Cloud Computing, DevOps, Systems Management, Virtualization, Storage Management, Linux System Administration.)*

* **Brandon Hale** *(Brandon is responsible for all Cloud and Container monitoring initiatives for SevOne. He has built products for some of the largest service providers in North America to assure performance and availability of OpenStack, especially for SDN/NFV use cases.     )*

Resource Assurance for NFV Workloads
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Availability and Performance are key attributes for NFV workloads. On the other end of the spectrum, service rollbacks are becoming increasingly expensive to address and an impediment to NFV adoption. Resource assurance for network services would ensure that no service deployment would fail due to resource requirements. It would also ensure that network services continue to provide the expected quality of service since their resource requirements would always be met.  


* **Arun Thulasi** *(Arun Thulasi is the Chief Technologist for Platform Solutions in the Network Functions Virtualization Business Unit at HP. His responsibilities include defining, building and delivering NFV solutions bringing together technologies that form building blocks of a Next-Gen network (Cloud Operating Systems, SDN, Orchestration etc) into consumable, production-ready solutions. From an early career in kernel networking and performance analysis, his current focus areas have moved him into Software-Defined-X, Data Analytics and Cloud-native application & service development.)*

* **Tariq Khan** *(As a long-time technologist and architect with extensive solution selling & development experience around Data Centers and Cloud infrastructures. Tariq has had the opportunity to create meaningful impact on clients through thought leadership by evangelizing next generation solutions, selling consultatively, and driving client-facing strategy.  In his current role, Tariq is responsible for shaping HPE’s NFV technology architecture related to the Virtual Infrastructure Layer that include compute and network virtualization technologies and driving the evolution of open source efforts like OpenStack & OpenDayLight to meet the demands of current and next generation of telco applications. As the design and technical authority for the role of OpenStack within HP’s OpenNFV architecture, Tariq drives the development of features needed by telco applications within HP’s Carrier Grade OpenStack distribution (HPE Helion OpenStack Carrier Grade) and upstream OpenStack. He regularly participates and represents HPE at meetings for various open source and standards efforts like OpenStack, OPNFV, Open Cloud Connect and OpenDayLight to drive Carrier Grade features.)*

* **Gerald Kunzmann** *(Gerald studied electrical and information engineering at the Technische Universität München (TUM) in Munich, Germany, with a concentration in information and communication technology. For his PhD he researched distributed, self-organizing routing protocols and network architectures for the Next Generation Internet and developed novel concepts and algorithms for their optimized operation. In 2010 Gerald started as researcher for the next generation mobile core network in DOCOMO Euro-Labs in Munich, working on improving the Quality of Experience (QoE) and efficiency of mobile networks. He represented DOCOMO Euro-Labs in the European research projects MEDIEVAL and SAIL, where partners from academia and industry worked to optimize mobile networks for multimedia services and scalable/adaptive solutions for a next generation transport network respectively. Since 2014, he has been leading DOCOMO Euro-Labs' standardization team which is active in the areas of Machine-Type-Communications (MTC), Software-defined Networking (SDN), 5th Generation Mobile Networks (5G), and Network Function Virtualization (NFV). In the latter topic, Gerald is participating in OPNFV project with a concentration on the topics Doctor (Fault Management) and Promise (Resource Reservation).)*

OpenStack controlled IoT  Gateway to manage a Smart Home
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Interaction between proprietary Internet of Things Devices along with their data management and security presents a lot of complexity presently. UC Berkeley’s Swarm Lab have come out with a secure, open, distributed data logs called the Global Data Plane, with a communication platform to solve this problem. In this talk we show IoT platform framework or a Universal Software Plane for Smart Homes. Our IoT Gateway platform is based on GDP, which we have containerized and use OpenStack based Flotilla’s framework on the cloud side to establish a dynamic vpn tunnel from the openstack gateway to the Swarm Box and deploy containerized apps on it remotely using a single pane network function portal based on Horizon & Murano. The apps deployed on the swarm box would be having the capability to read/write logs either on the openstack based cloud or on the local distributed data store along with big-data kind of closed loop analytics, making the swarm box a personal cloud for Smart Homes. 


* **Sumanth Sathyanarayana** *(Sumanth M. Sathyanarayana is a Research Engineer working at Deutsche Telekom Innovation Laboratories (T-Labs) in MountainView, CA. He is working on Openstack, SDN and Containerized Networking at T-Labs. Prior to joining T-Labs, he was working as a SDN Software Design Engineer at Hewlett Packard where he was developing HP’s Core SDN Controller focusing on the HA, Persistence and Backup & Restore aspects of the Controller. Sumanth worked at ON.Lab developing Flowvisor, the open-sourced network hypervisor tool and was responsible for the development and release of FlowVisor 1.2 and 1.4. He has also worked at Nokia Siemens Networks, Bangalore developing the Integrity Checking components of Home Location Register in Telecommunication Networks. His research mainly focuses on the design and implementation of SDN and Advanced Networking Systems. He received his Masters Degree from the University of Pennsylvania.)*

* **None None** *(None)*

* **None None** *(None)*

Juniper Cloud CPE Demo
~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will provide demo and overview of Juniper Cloud CPE for Service Provider managed enterprise solution. Juniper solution is an open, modular and fully integrated solution for service creation, service provisioning and monitoring of managed enterprise network services. Juniper solution is simple to install and operation and it supports both distributed and centralized VNF lifecycle management for on premise and data center use case.


* **Vinay Hegde** *(Vinay Hegde is the Product Manager in Juniper Networks. He is responsible for Cloud CPE solution.)*

Overview of AT&T’s Cloud Workloads: Before, and After OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you ever wondered about the different types of cloud workloads, and service integration use-cases a typical large operator manages on daily basis? Join us for this session as we walk through a diverse set of workloads, application and service delivery patterns that are powered by our OpenStack cloud platform. Running all your workloads on a common unifying platform is a great vision to pursue. However, in a complex multi-vendor multi-solution landscape that a large operator deals with regularly, the key to executing this vision becomes technology integration. We'll cover: The process to deploy new services going from 2-3 weeks of time line, down to minutes with the help of cloud platform and other tools. For a telco provider, a legacy way of launching a new service would have involved commandeering multiple disjoint technology blocks with significant lead time. Whereas now, with the help of Gluon, Yardstick and OPNFV platform this becomes simple, predictable agile process.


* **Tobias Ford** *(As the AVP of Cloud Infrastructure and Platform Architecture & Strategy for AT&T, Toby Ford leads technology efforts around AT&T's cloud offerings both internally and externally focused. Currently, Mr. Ford is responsible for shepherding SDN and NFV projects on to AT&T’s Common Cloud platform. Toby served as CTO for USi, which was acquired by AT&T in 2006. Previously, Mr. Ford held positions at Cornell University, ARINC, TeleCommunication Systems, and his own company in the Netherlands. Toby is also a member of the OpenStack Board of Directors.    )*

* **Amit Tank** *(Amit Tank is a Sr. Principal Cloud Architect with AT&T. He spends his time designing and building large scale cloud infrastructure, and leading projects and teams of technologists working towards putting OpenStack in production - while contributing the learnings back to the community. He enjoys helping enterprises, businesses and customers become fluent with OpenStack, Open Source, and Cloud skills and technologies within their organizations. Prior professional associations include several startups, DirecTV, Cisco, EMC, Hitachi, and Schindler among others.)*

Driving NFV High-throughput performance using user space fast data processor
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack Clouds are gearing towards the next generation NFV application which demands high data-rate performace from the cloud. On the otherhand opensource technologies like VPP (Vector Packet Processing) are rapidly growing to cater high performing network application needs. VPP natively runs as a Linux user-space process and creates a vector of packet indices and processes them using a directed graph of nodes resulting in a high performance. If a controller supports OpenStack Neutron (as OpenDaylight does), this provides a easy mechanism for VPP to integrate with Openstack. In this session, join Velmurugan Kumar and Vinay Rao to get an overview on how technologies like VPP can help to deliver high performance resilient networks for Enterprise and Service provider applications. Also the session will go over some scale and performance tools/measurements that can be used to measure the Openstack cloud performance.


* **Velmurugan Kumar** *(Velmurugan Kumar is a Technical Leader in Cloud and Virualization group at Cisco Systems. Vel is actively working in Openstack Systems Engineering team on deploying openstack cloud using Cisco openstack installer and performing Scale, Performance and HA testing using industry standard benchmark tools for openstack. Vel has extensively worked on routing/switching technologies across Cisco core and edge routers such as CSR and ASR9K. Vel is also actively involved with customers deploying openstack using Cisco openstack installer and running Cisco NFV applications on top of openstack.)*

* **Vinay Rao** *(Vinay is currently working on building NFV clouds at Cisco Systems. Vinay has extensively worked on service provider high performance technologies (Like SDH, DWDM and Mobility) and is currently interested in next generation NFV application  )*

Clearwater vIMS VNF onboarding on Carrier Grade OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

IMS is the standard architecture adopted for voice, video & messaging services in IP only environment. During the current NFV revolution, IMS has become a leading NFV use case. Telcos expect IMS [IP Multimedia Subsystem] and all their network functions from layer2 and above in NFV environment. As a case study, we experimented with Clearwater IMS, which provides SIP based call control for voice and video communications and SIP-based messaging applications. It has built-in calling features and standalone subscriber database. Experiences learned during this process and how they are applicable to other Telco VNF's will be shared. Session is good for cloud admins, Telco network engineers & OpenStack NFV users. It will cover: Clearwater IMS components (Bono, Sprout, Ellis, Homestead, Homer & Ralf) Component configuration, blue print yaml & Tosca document Deployment of Clearwater on Carrier Grade OpenStack Operational workflow using 2 SIP clients Demo of voice & video using Jitsi call


* **Nayana Dawalbhakta** *(Nayana Dawalbhakta works at Hewlett-Packard Enterprise on Helion OpenStack Carrier Grade as an Architect in R&D engineering. She has several years of experience working with OpenStack. Currently, she is leading SDN integration with OpenStack to offer a Carrier Grade NFV Solution. This is a multi-hypervisor and multi-site solution offered to Cloud Service Providers for Telco market. She has 15+ years of experience as a Software Developer, QA, Project Lead and an Architect in the technology industry.)*

* **Devapraba Muthumani** *(Devapraba Muthumani works as a Systems Software Engineer on Helion OpenStack Carrier Grade, NFV BU Headquarters at Hewlett Packard Enterprise, USA.   She has few years’ experience in cloud technologies like OpenStack, virtual storage, SDN controllers that includes multi-NIC, Multi Data center, security policy, HA testing, KVM/ESX hypervisors. Currently involved in test strategic planning in qualifying Carrier Grade functionality and features offered to Cloud Service Providers for Telco market. Also involved in design, deployment, administering and troubleshooting enterprise telco grade configurations. This also includes Validation of deployment topologies, servers, storage and networks.   Outside cloud her other experiences include product testing, I/O Storage Certification, VMA Storage Device Qualification, Protocol Compliance testing in storage area networking technologies such as Fibre channel, scsi etc, managing HP-UX servers which includes superdome used for SAP HANA, Storage Devices, Switches, Virtual Connect, Virtual machines (VM), Virtual Partitions (vPars), Fibre Channel Over Ethernet(FCOE), Mission Critical feature and so on.    )*

MeghDVR - An Intelligent Video Delivery Platform for the Era of the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you frustrated by the slowness of your video streaming? Are you annoyed with rebuffering when all you wanted was to catch the last word of the joke that was last streaming?  Wouldn't it be great if you could seamlessly continue to watch a program on your phone that you were just watching at home?We will introduce the current state of video delivery technologies, present some of the complex interactions between the content, the network and the subscribers, while discussing some of the key trends, economic drivers and critical mass that prompted the need for this prototype. We will also consider the technical aspects of existing content delivery platforms and their shortfalls with regard to scale, elasticity and constrained service offerings.We will also explore the components of our proposed solution and demonstrate improved personalization in consumer interactive video services.


* **Narendra Narang** *(Narendra N. Narang has accumulated a wealth of experience, while working in various Information Technology roles at financial institutions in New York. Most recently, he spent 11 years at Bloomberg in various roles and comes to Red Hat with deep knowledge of enterprise systems and storage infrastructure, emerging technologies and data analytics platforms. His areas of specialization include analyses of comparative storage architectures, performance and optimization studies, developing best practices and planning for disaster recovery, and in-depth knowledge of distributed and elastic cloud storage platforms.)*

* **Laurent Domb** *(Laurent Domb is a Senior Cloud Solutions Architect working for Red Hat. He is a Red Hat Certified Architect Level III, a puppet certified professional 2013/2014 and ITILv2 certified. Next to his technical certifications he also holds an eMBA degree in general management as well as a BSc in applied computer sciences. His IT career started in 2002 by studying applied computer sciences at the University of Northwestern Switzerland and founding the VIBB Unix User Group (VUUG). During university he started teaching Linux and Norman data defense and worked as a Linux admin at Wagner Kunz aktuare. After graduating, he was hired by Trivadis AG, a Swiss consultancy as a Linux / Open source consultant where he worked for different banks, insurances, and automotive industries in Switzerland, Germany, Norway and Sweden. Laurent also lead the Trivadis IT department where he was responsible for transforming the traditional way of IT thinking  into a new, modern agile IT department. Later in his career Laurent took over the Service Engineering Department at OPITZ CONSULTING Switzerland where he was responsible for building up the Consulting Services. In 2010 he moved to America where he worked as a Linux System Engineer at OnSIp. In 2013 Laurent was hired by Red Hat as a Senior Linux consultant where he transformed multiple financial firms from traditional IT environments into agile IT environments. Today, as a Sr.Cloud Solutions Architect Laurent helps customers  to understand, envision and build successful cloud environments.)*

* **Sanjay Aiyagari** *(Sanjay is a Sr. Solutions Architect working on NFV strategies within Redhat.)*

Network traffic telemetry with OVS DPDK in Monasca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Handling the ever increasing network traffic requires NFV to design and build networks that have scalability, flexibility and elasticity to it. One of the widely used tool for this purpose is the Data Path Development Kit (DPDK) libraries. Heavy traffic seeds the need to perform efficient network analytics over DPDK which involves monitoring network metrics such as Tx/Rx throughputs. Currently in Monasca, when ports are DPDK enabled, the libvirt plugin does not store and query metrics measurement/stats for the ports and hence is unable to collect the network metrics.We address this problem by collecting the metric for DPDK port using ovs plugin integration with the monasca-agent. Ovs plugin fetches the port stats from ovsdb using ovs-vsctl commands and store the queried metrics in a cache and from there we calculate the rate for the tx/rx packets for the dpdk enabled ports.


* **Ashish Gupta** *(I'm working with Openstack more than 4 years. Now I'm Senior Software developer at Hewlett Packard. My main interest is in Cloud computing especially OpenStack .Contributed my work in neutron related project such as vpnaas,lbaas,fwaas , networking-l2gw ,automation (tempest), ironic baremetal networking provisioning mech driver implementaion,monasca-agent ovs/libvirt plugin  implementation and testing.Currently involve in automating monasca-agent ovs/libvirt plugin.)*

* **Alok Maurya** *(Working as  Sr. Software engineer at  HPE . I and  responsible  for  performing scalability  testing of  HPE Helion  products . I have  been actively involved  in  contributing in upstream  in  different  projects networking-l2gw , monsaca , tempest .)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*

Operations Dashboard: Looking past the Horizon at Telco Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Large telcos like AT&T have begun to realize that a hybrid “shared nothing” architecture for a cloud is the only true way to provide the level of reliability and resiliency we need. Doing this , however, adds challenges around how to provide a single pane of glass view for your entire cloud platform without bogging it down and expending limited datacenter resources. Beyond Horizon, operators at telco scale also have a need to use and view intelligent logging/monitoring/alerting solutions that look beyond OpenStack. Big data provides intelligent frameworks for logging/monitoring/alerting and opportunities to leverage this data to improve the reliability and resiliency of our cloud platform. We will go into some strategies that we think would benefit other operators in their environments.


* **Randeep Jalli** *(Lead Openstack/Devops/Networking Engineer at AT&T Integrated Cloud, worked on/been a part of multiple cloud projects and building/tweaking/deploying/maintaining the AIC platform for various applications around AT&T including but not limited to AT&T Business VOIP, Wireline, Uverse and Mobility. Helped setup/refine the contrail CI/CD pipeline at AIC (AT&T Integrated Cloud).)*

* **Marshall Margenau** *(I am a cloud applications architect with over 11 years of software engineering experience.  I have an extensive background in deploying a wide range of full-stack and mobile applications in the cloud.  I evangelize software development topics like agile (as opposed to "Agile"), CI/CD, and DevOps.)*

* **Kayla Fromme** *(I am managing development of OpenStack core components (upstream and internal customizations) at AT&T and deployment of OpenStack using Fuel in enterprise data centers.  My first summit was Vancouver 2015.  I enjoy learning about OpenStack and how other companies are using & deploying OpenStack.  I joined the  Women of OpenStack shortly before the Austin Summit and I am looking forward to becoming more involved. In my spare time I like to snowboard, cheer on the St. Louis Cardinals, and play soccer. )*

Automation Testing: Leveraging the right open framework for VNF Performance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Yardstick is an open-source tool to verify compliance of the VNF environment. The use cases are taken into consideration from ETSI GS NFV 001 which suites the need for the highly complex environments. The use cases is considered in Yardstick in form of test cases. Yardstick needs access to the Openstack to create and ssh to VMs, connection to external network of the environment. The project's scope is to develop a test framework, test cases. The VNF Workload Characterisation Framework supports the automated testing of VNF platform configurations and the capture of associated data in an OpenStack Cloud Environment. The framework provides orchestration of the full test lifecycle including deployment of the VNF, starting/stopping packet generation, collection of test data, creation experiment metadata and termination of the test case  


* **Venkat Gadwal** *(Principal System Engineer @ AT&T Lead Automated Openstack testing, Performance and Openframce work testing.)*

Problem prediction/detection assisted by AI running on Distributed Analytics & Monitoring framework.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Robustness against unexpected problems such as silent failures caused by software bugs and failures of server components is important for operators of telecom and cloud services. Fast detection of problems, and predicting them is crucial for us to avoid serious situations. We propose Distributed Analytics & Monitoring (DAM) framework to achieve real-time failure management in OpenStack. For fast detection, DAM deploys an analytics/monitoring agent into each compute node, and each agent can collect statistics from the local environment and analyze them very rapidly. A typical application of DAM for prediction is running AI to learn huge statistics locally, so that we recognize problems 30 minutes in advance of actual failure with 94% precision. Optionally, an orchestrator reacts to invoke auto-healing. DAM greatly helps improve the scalability and real-timeness of cloud and NFV infrastructure. DAM also helps us detect micro-bursts of demand, fast change of configuration, etc.


* **yuki kasuya** *(Yuki Kasuya work for KDDI Laboratories as a research engineer. He investigates how to build NFVI using OpenStack effectively and to solve performance and operation problem in NFV.)*

* **Hyde Sugiyama** *(Driving NFV/SDN technology partnership at Red Hat APAC as a member of Red Hat NFV Initiative Leading team 28 years experience in the Information Communications Technology industry.)*

* **Ryota Mibu** *(Ryota Mibu has been working on integrating cloud technologies to telecommunication platform form 2012 in NEC. He has been contributing OpenStack projects, including Neutron, Ironic and Ceilometer. He is the Project Lead of "Doctor" which is one of the OPNFV projects and focusing on building a framework for fault management for high availability of Network Services on top of virtualized infrastructure.)*

Accelerating Enterprise Cloud Adoption with Murano: AT&T Telco Use Cases and Lessons Learned
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AT&T is one of the world's largest-scale users of OpenStack, and an aggressive proponent of Network Functions Virtualization (NFV) on the OpenStack platform. As they've explored the performance-critical NFV use case and confronted the challenges of building out a viable, 'carrier-scale' business around these technologies AT&T has had to discover new ways of enabling and automating operations for speed and repeatability. One of AT&T's key tools is Murano — which offers a framework for packaging components, apps, and complex stacks, along with configuration details, providing these in an informative catalog for rapid selection, dialog-driven configuration, and automated deployment at scale. It's an example of an advanced tool that serves AT&T's need to describe and package complexity, and to distribute components, apps, VNFs and stacks across organizational boundaries while also simplifying Ops procedures — maintaining control, accelerating ops and working efficiently at telco scales.


* **Gnanavelkandan Kathirvel** *(Gnanavelkandan Kathirvel is a Lead Principal-Technical Architect at AT&T working on Cloud Strategy, Cloud Architecture and Network function Virtualization (NFV). Previously, Kandan led the architecture work to support Cloud convergence, building external cloud and Content Delivery network (CDN) for AT&T. He is currently focused on AT&T’s “Domain 2.0” initiative to virtualize large portions of AT&T Network services infrastructure on top of a common OpenStack based Cloud. )*

* **Craig Peters** *(Craig, a product manager at Mirantis, has spent his career making complex systems easier to consume in a variety of industries. His mission to improve the developer experience in distributed systems has developed through work on Documentum, Hadoop, and even Lotus Notes. His experience has been forged through experience at EMC, Yahoo!, Strava, and HGST. His current responsibilities include enabling PaaSes, containers, and analytic workloads on OpenStack.)*

Can we use OPNFV Doctor framework in OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In telecom operation, fault management is essential to achieve high service availability. This is typically realized by a monitoring system which is specific to hardware and application as they are tightly coupled before introduction of NFV. To realize the same network service availability in NFV, we have to make sure to have the same level of monitoring functionality in a cloud type platform. The OPNFV Doctor project focuses on this requirement and has proposed missing features to the OpenStack community. We present our implementation of a fault management framework for NFV realized by different OpenStack services and comprising various exemplary use cases of compute/network/storage resource faults. This talk also provides insights on how to adopt this framework to various types of deployment models and operational policies utilizing Congress and Vitrage. The results of multiple PoCs will be shared to show the performance of this framework in particular w.r.t immediate notification.


* **Ryota Mibu** *(Ryota Mibu has been working on integrating cloud technologies to telecommunication platform form 2012 in NEC. He has been contributing OpenStack projects, including Neutron, Ironic and Ceilometer. He is the Project Lead of "Doctor" which is one of the OPNFV projects and focusing on building a framework for fault management for high availability of Network Services on top of virtualized infrastructure.)*

* **masahito muroi** *(Masahito Muroi is a software enginer in NTT. He is now working as a cloud architect for NTT's public/private cloud, and also working as a core developer of OpenStack Congress Project and Masakari. He's started to join OpenStack Community and develop NTT's cloud with OpenStack since Diablo release.)*

* **Ohad Shamir** *(Ohad is a product manager in CloudBand, Nokia. In his role, Ohad is leading Analytics and monitoring for the CloudBand NFV product line and he is also responsible for open source activity in CloudBand. Ohad is driving Vitrage, an official OpenStack project, initiated by CloudBand, for root cause analysis, deduced alarms and states.)*

Managed Router Services: chronicling Cox's journey and rationale behind choice of the lego blocks.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cox Communications has embarked on a projec to enhance their MPLS IP-VPN with new services that include managing customer premise equipment and providing security within customer premises. In order to do so, Cox set out to select a bunch of carrier grade building blocks that include OpenStack and solutions to address robust, scalable and malleable networking. Supporting multiple tenants in shared infrastructure environments was a dominant concern and securely isolating the different customers was vital. In this session we will have Cox partner with Juniper Networks to describe the project, the considerations, the challenges, some of their choices and the rationale behind those choices.  


* **Aniket Daptari** *(Sr. Product Manager (Cloud Network Automation, Contrail) @ Juniper Networks Inc. Started as a Software Engineer writing protocol code, CLI, device drivers and online diagnostic software for various networking equipment at different network equipment vendors - Allied Telesyn, Force10 Networks, Cisco Systems. Then began a journey into network programmability, APIs and SDK at Juniper Networks. Evolved from programmability into platforms for NFV and SDN. In this journey evolved from being a Software Engineer to a Technical Marketing Engineer to a Solutions Engineer to a Product Manager. On the education front have a Bachelors degree in Computer Science from Mumbai, India. A Masters degree in Computer Science from University of Southern California. And a graduate certificate in Management Science and Engineering from Stanford University.)*

* **Steve Hartt** *(Steve has worked in various software engineering and network consulting roles at Cisco Systems. For the past more than 3 years he has been working at Cox Communications helping them design, architect, build Differentiated and value added services to Cox's existing offerings to their customers. These include managed customer premise equipment, managed on-premise security offerings among others. Steve is also helping evaluate various alternatives for the building blocks required to implement such services.  )*

Lessons learnt from Customer Deployments using Fuel, Mirantis OpenStack, and OpenContrail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Leading Telecom operators and Enterprise customers have chosen Mirantis OpenStack (MOS) and along with it, an SDN product like OpenContrail, to enable Telco Cloud, Enterprise private cloud, SaaS Cloud use-cases. In such customer environments, it is crucial to have an integrated and seamless deployment of all software components that constitute the cloud software stack. Mirantis OpenStack provisioning is done via Mirantis’ Fuel, an open source tool for deployment and management of OpenStack. Fuel also has a plugin model that allows other components’ deployment to be integrated with Fuel.  In this session we will discuss how the Fuel plugin model was leveraged to provide a seamless and integrated deployment and provisioning of Mirantis OpenStack and OpenContrail Neutron plugin. We will also cover the best practices and lessons learnt in such customer deployments.


* **Pratik Roychowdhury** *(Pratik has been with Juniper Networks for the last 5 years, leading product management activities for Juniper’s Network Virtualization Platform and Network Programmability products and taking some of these products from concept to release. Overall he has spent 15 yrs in the hi-tech industry assuming various roles including product development at Citrix, strategy & marketing at early stage start-ups and technology investment banking at UBS. Pratik has a B.Tech in Electrical Engineering from Indian Institute of Technology and an MBA from Univ of Michigan, Ann Arbor (Ross School of Business))*

* **Durgaprasad Ayyadevara** *(DP Ayyadevara is a Sr. Product Manager at Mirantis responsible for Networking aspects of the Mirantis OpenStack distribution including SDN, NFV and native OpenStack networking. DP has been in the Networking industry for the past 15 years managing products ranging from Core Routing Platforms to DataCenter Switches to SDN/NFV platforms deployed at Top Tier Service Providers and Large Enterprises.)*

VNF Service Modeling and Chaining on VMware Integrated OpenStack using TOSCA/YANG
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the world of NFV, YANG is basically the data modeling language of choice for networking devices, where TOSCA has been selected by ETSI, MEF, Open-O, Open MANO, & many telecom carriers as the de facto modeling language for service orchestration. TOSCA, in the context of NFV, is a language that enables data modeling with a focus on topology and workflows, processes, and policies. Therefore, when you want to manage the full lifecycle of orchestration in an NFV use case, it is important for TOSCA and YANG to communicate seamlessly.  With the powerful integration of TOSCA & YANG it's possible to provision VIM resources, deploy software components & VNFs, wire them in and push configurations, & then chain them to other services. Here we will dive into the different service modeling options for virtual & physical network devices these days, how they communicate, and how to seamlessly deploy them on VMware and OpenStack using a TOSCA/YANG translator and open source MANO solutions


* **Ran Ziv** *(  Ran Ziv is the Cloudify Team Leader and a Senior Software Engineer at GigaSpaces. He has spoken at various conferences on development and cloud computing. Ran has extensive knowledge in developing and architecting large-scale open source cloud projects. On top of being an awesome guy, Ran is also a Python charmer and Ruby gem. )*

NFV Considerations for OpenStack on VMware Infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Large set of Telco companies use VMware for running their enterprise workloads today. The next big movement is on Network Function Virtualization (NFV) which would help them to reduce capEx, OpEx and improve agility. The demands of NFV is significantly different from traditional enterprise workloads especially when it comes to reliability and performance. Even though virtualization helps in high degree of automation and resource utilization, NFV still needs to be dependent on physical hardware (passthrough, physical switch configuration etc.) to meet the SLA. OpenStack is being considered as one of the main components in NFV layout primarily for standardized APIs and ability to work with wider ecosystem. This talk will cover details on how OpenStack on VMware provides a path towards addressing carrier grade requirements by better capacity planning, guaranteed resource allocation, improved performance with SR-IOV/direct passthrough, and configurable latency sensitivity options.


* **Giridhar Jayavelu** *(Giridhar Jayavelu is a Staff Engineer from the NFV group at VMware. Giridhar workson VMware Integrated OpenStack (VIO) enabling features to meet the carrier grade requirementsfrom customers in Telco space. He has been involved in various automation initiatives within VMware.Prior to joining OpenStack team, Giridhar worked on vSphere networking and NSX team for about 8 years.Giridhar holds a Master's degree in Computer Engineering from the University of Arizona, Tucson.If OpenStack and NFV don't keep him busy, you can find him involved in short film productions.)*

NFV Multi-VIM Management and Orchestration (MANO) with a VMware/OpenStack Demo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Telcos have been waiting for the world of open & interoperable collaborative software to replace existing & costly proprietary black-box hardware.  The promise of NFV on OpenStack makes all this possible, however many existing network functions have been written to run on existing VMware environments, & achieving the true benefit of multi-VIM NFV interoperability & portability has been a challenge.   Many of these organizations are looking to leverage existing investments & reliability of VMware architecture, coupled with the new open & futureproof world of OpenStack-based infrastructure. To enable the seamless portability between existing architecture to cloud environments, multi-cloud orchestration is key.  This live deme will show how to compose services on top of hybrid cloud environments, transition legacy apps & VNFs between VMware & OpenStack, with some components running on VMware and others on OpenStack, all through a single pane of glass, to leverage the best of both worlds.


* **Shay Naeh** *(Shay Naeh is a seasoned technology professional with over 20 years of experience in the areas of internet ventures, cloud services and enterprise software who helps lead technical innovation on the Cloudify team at GigaSpaces. He has driven the directions of several successful start-ups and ventures.  Some of Shay’s expertise includes deep coverage of networking, DPI and protocols, and specifically NFV, network automation and orchestration, virtualization, security, web acceleration, large-scale applications, application performance management, cloud multi-tenant models, SaaS, agile prototyping and more.  Shay is an avid blogger and technology writer.  )*
