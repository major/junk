Case Studies
============

Efficient Business Analysis for an OpenStack-based Multitenant Public Cloud Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We at NTT Communications provide the public/hosted private cloud service Enterprise Cloud 2.0 based on OpenStack in five countries, and planning to expand further globally. Business analysis is crucial to expand business all over the world for a public cloud service provider with OpenStack because each country has different user trends. Questions like what is the most popular flavor or most used OS provides crucial data in resource management and stock monitoring. However, it is not easy to gather and analyze these data using only OpenStack. In order to implement effective business analysis for global service management and expansion, we have designed a service architecture using a system which gathers, stores and analyzes OpenStack usage data in a global scale. In this session, we will show which OpenStack data are crucial for our business analysis, and our approach to utilize these data for effective global management and expansion of our public cloud service.


* **Hirotaka Kojima** *(Hirotaka Kojima is Software Engineer, Cloud Service Development at NTT Communications. He is working to manage OpenStack Nova based Cloud Service (e.g. Enterprise Cloud of NTT Communications). He also has one year experience working for Verio, Inc. as a system administrator for Unix/Linux Hosting Service. He graduated from Nanzan University with a Master's Degree in Information Science.)*

* **Noriko Yokoyama** *(Noriko Yokoyama is a Software Engineer, working at NTT Communications in the cloud service department since 2015. She works with the operation engineering team and develops operation tools for NTT’s enterprise cloud service. Before that, she worked at NTT Service Evolution Laboratories for more than three years. Her research interests include big data analysis and action support systems. She earned her M.S. degree from Waseda University in 2012.)*

T-Systems' Open Telekom Cloud (OTC) powered by OpenStack: lessons learned and future roadmap
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

On March 14, 2016 at CeBIT 2016, Deutsche Telekom announced the launch of Open Telekom Cloud (OTC). The new public cloud platform will provide European enterprises of all sizes with on-demand, pay-as-you-go, secure cloud services to respond to fast changing market conditions. OTC is based on OpenStack.  In this presentation, we will discuss the opportunities and challegnes of OTC, the learnings from OTC/OpenStack deployment, and the future enhancements needed in OpenStack for OTC to trive in the competitive and fast changing European market.


* **Anni lai** *(I am an IT technology professional with a passion for community and partnership building. I'm very fortunate to live in the Silicon Valley area where I obtained my graduate degree in CS, and trainings in engineering, product mgt/marketing, business dev, services, consulting, and enterprise sales from successful companies such as Sun Microsystems/Oracle, Salesforce.com, Savvis/Centurylink, and now Futurewei/Huawei. Yes, I have done them all (except for HR, Legal, and Finance). For the last 10 years, I've chosen technology evangelism, developer enablement and partnership building to be the focus of my career because I truly believe in partner enablement/empowerment, and win-win. Together, we can make our market bigger, and win together. I formally joined OpenStack community in July 2015, however, prior to that, as the Head of Global Business Dev for Huawei, I have traveled to 30+ countries visiting telco and enterprise customers in EMEA, APAC, and Latin America to discuss their ICT and Cloud initiatives, evangelized OpenStack to both enterprise and telco communities, and presented the latest Cloud/OpenStack technologies and business trends at various industry conferences and forums.  In 2015, I've attended multiple Board meetings representing Huawei, participated in Product Team, Marketing, Diversity, Telco, etc. work groups, and presented 2 sessions and hosted a telco panel at the last OpenStack summit in Tokyo. With my engineering and business background and training in Enterprise IT and Telco, I would like to continue contributing to the OpenStack community in the following areas: 1. Generate mindshare and increase telco and service provider adoption in OpenStack 2. Bring enterprise and telco customer requirements/perspectives to OpenStack community 3. Enable the global developer and ISV communities to build interesting apps for OpenStack 4. Help woman developers and engineers to grow using OpenStack as a platform 5. Help OpenStack to embrace diversity and make OpenStack a true global movement  6. Foster more collaboration and partnerships among OpenStack members and various regional communities)*

* **Clemens Hardewig** *(Dr. Clemens Hardewig is currently responsible for the delivery of Open Telekom Cloud platform and services at Deutsche Telekom. After he completed his phd studies in technical computer science and microprocessor architecture, he became employed as responsible head of mobile device software. Since his studies he has been intensively engaged on open source software and Linux. Clemens Hardewig held various management positions in the IT service and IT infrastructure area, after joining Deutsche Telekom in 1997. Since 2010 he has been responsible in a management position for the design, installation and operations of cloud infrastructure platforms. Furthermore, Clemens Hardewig is also currently working on the set up and development of a technical ecosystem and community for OpenStack offerings of Deutsche Telekom. Therefore, the technical development of the platform as well as the product development of PaaS and SaaS solutions and thus their operations are the main focus areas of his work.  )*

I don’t always attach volumes, but when I do its host based and with os-brick
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, people can expect to get a better understanding of what os-brick really is, where it came from, and where it’s going. Initially os-brick was designed to handle host-based volume attaches and detaches, but has since grown to be much more than that. It supports a variety of transport protocols, operating systems, and architectures- it’s more than just iSCSI on Linux x86. With this expansion, os-brick hasn’t been immune to controversy within the community.  It’s faced many challenges with replacing rootwrap with privsep, and is under discussion whether or not the host based attachment approach should be replaced with QEMU direct attaches. By the end of this talk, you will walk away with an understanding of the basics and history of os-brick, how it is continuing to grow and develop, and what areas are being debated.


* **Kendall Nelson** *(Kendall Nelson is a Software Developer working on Cinder since she started in June of 2015.  She has worked on some smaller scheduler changes to Cinder and a larger effort to make the sample configuration file generation a more dynamic process.  She recently had a spec merged for and has begun working on dynamic reconfiguration of services based on changes to the configuration file. Lately she has also been involved in the refactor of much of os-brick. In addition, she is the cross project liaison for Cinder and given many intro to Cinder presentations to IBMers getting into cloud computing. At the Austin Summit, she had the privilege to give two talks- one to the Women of OpenStack about what she's learned in her first year as an upstream developer and the other on the basics of Cinder and setting up multiple backends.)*

* **Walter A. Boring IV** *(Walt is a software engineer at Hewlett-Packard currently working in the Management and Solutions Development Unit focusing on storage systems enablement.   He has been working at Hewlett-Packard since 2007.  Since 2012, he has been working on OpenStack for HP enabling several of HP’s storage systems.  He became a core member of the OpenStack Cinder team in 2013 after co-authoring the Fibre Channel protocol support in OpenStack’s Nova and Cinder projects.    He codeveloped the 3PAR iSCSI and FibreChannel drivers for OpenStack Cinder as well as helped develop the Cinder Fibre Channel Zone Manager. Also created the os-brick shared library that's used by Cinder and Nova to manage discovery and removal of volumes from a host as part of the attach and detach process for OpenStack.)*

Building a Private Cloud for Tripsta.com
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tripsta is building its own private cloud environment targeting to migrate all of their current workload by the end of 2016. For the time being the company IT services are relied upon bare-metal offerings from a third-party provider. The size of the allocated infrastructure resources is approximately 140 physical servers. The company decided to modernize its IT operations with OpenStack, while they are already transitioned into an Infrastructure as Code model with the help of SaltStack. As a consequence of their competent knowledge in configuration management and orchestration, as well as for simplicity matters they have built their OpenStack cloud in their own. In this endeavor Tripsta works closely with Stackmasters, who have undertaken the task to quickly enable the project team into performing comprehensively as part of their OpenStack consulting and support services.


* **Thanassis Parathyras** *(Thanassis Parathyras Thanassis Parathyras is CTO and Co-founder at Stackmasters. He has a long experience on high-performance and high-availability Linux clusters for over 12 years. His expertise is based on delivering specialized solutions for distributed storage, automated process workflows, fault-tolerant Linux services and virtualizing several complex enterprise computing environments. For the last 5 years he is leading the open source cloud team within Virtual Trip and Stackmasters, while at the same time being an authorized instructor for Mirantis OpenStack training program.)*

* **Yiannis Polizois** *(CTO at tripsta.com)*

Using OpenStack Swift to empower Turkcell's public cloud services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Turkcell is the leading mobile network operator in Turkey and also offers additional internet services to its users. One of these services is Akıllı Depo, a service to store and share important documents, photos, videos and other media files in the cloud. In 2015 Turkcell upgraded their offering and therefore needed a storage system that is- easily accessible from apps and web-browsers; - is built with a strong durability, high availability and scalability in mind;- stores data replicated across multiple datacenters;- and can be enhanced using software developed in-house.During this talk, we want to give you an overview and introduction to OpenStack Swift, an open-source object storage system, and how it is used and operated to empower Turkcell's offerings using the Red Hat OpenStack platform.


* **Christian Schwede** *(Christian started working on Swift four years ago and works as a Principal Software Engineer at Red Hat. Most of his Swift related work is related to supporting customers running Swift and working on automation, testing and development tools.)*

* **Orhan Biyiklioglu** *(Orhan has been working as a Linux/UNIX Systems Administrator for 14 years.  He is currently working for Turkcell, the leading mobile network operator of Turkey, where he is responsible for the design, implementation and operation of Turkcell's large scale systems. He has a MSc. in Computer Engineering and a current Red Hat Certified Engineer.  )*

* **Doruk Aksoy** *(Doruk is currently working as a  UNIX/Linux Systems Administrator for Turkcell.  He is also responsible for the operation ofTurkcell's Openstack enviroments.Doruk has 10 years of experience in UNIX / Storage / Virtualization Administration.)*

Oracle RAC real case on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The presentation will show some real cases about China user how to run Oracle RAC on OpenStack 


* **Gibson Chen** *(Gibson is a Director of industry Business Development in EasyStack. He has 15 years work experience in IT. before EasyStack gibson once worked in HP and Oracle.)*

Experiences building a Public Cloud with OpenStack and LinuxONE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The LinuxONE Community Cloud is just under a year old and already supports 1000+ users worldwide. It's open to anyone who wants a free trial of a Linux virtual server, with an interest in touching a real-life LinuxONE machine. How is this possible? With OpenStack, of course! OpenStack, running on the IBM z/VM hypervisor, underpins this growing public cloud. In this session we will discuss the architecture of the LinuxONE Community Cloud, challenges in setting it up and tending it and how it has grown.  We'll also discuss the joys and sorrows of running OpenStack on a non x86 KVM platform and lessons learned from that. We'll include demos of our custom built self-service dashboard based on OpenStack Horizon which allows users to provision a variety of Linux distributions. After you hear about it, you might even want to try it yourself. You too can start playing with all the latest technologies like Blockchain, Apache Spark and all the other buzzwords we can fit into this description!


* **Emily Hugenbruch** *(Emily has been working on IBM mainframe virtualization for 10 years, specializing in functional test, systems management and CPU virtualization.  She contributes to the OpenStack Tempest project and writes the occasional blog on OpenStack.  She has attended the Kilo and Liberty summits and given Brown Bag talks and webcasts on IBM z/VM and OpenStack.  She's also leading the mentoring initiative for the Women of OpenStack group.)*

* **Kershaw Mehta** *(Kershaw works for IBM and his current roles is the Chief Engineer OpenStack Solutions & PaaS. He is part of the z Systems Strategy and Design team and has spent his career in roles in z/OS and Linux for z Systems.  )*

* **John Arwe** *(I've grunged around in the mainframe kernels (z/OS SRM/WLM mostly, recently a bit of z/VM and zKVM) for many years, and took a wide detour doing standards and open source work (W3C SML and LDP, OSLC, OASIS, DMTF, Eclipse, REST APIs, Linked Data) in the middle. Lately I've been schizophrenically focused on both the z/VM nova CI system and architecting/debugging client deployments of the OpenStack and hypervisor back-end components.)*

Let's Oversubscribe the OpenStack environment and try to find the weaknesses and improvements.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Oversubscription of SDI is not a trivial problem.Numerous questions to be answered and tradeoffs to be fine-tuned.Is it worth to stressing the environment to the max?Where are the limits and bottlenecks? Let's find the sweet-point of the performance-SLA pair!As the OpenStack Performance Team we've executed countless tests and gathered gigabytes of data to verify that. During the talk we will present new open testing framework that we have developed.*It's features include running workloads in different conditions,measuring them and visualize.*We will describe the methodology and show the analysis of stack under the businesses line applications stress.According to the Delft University of Technology:"CPU utilization is higher than memory utilization,which is the opposite of the finding of Diet for the Google trace.This is because that business-critical workloads are more in line with grid workloads".You will walk out of this presentation knowing exactly who is right in this dispute.


* **Patryk Wolsza** *(Patryk is a Data Center Architect in the Intel Cloud Platforms Group, with a focus on Software Defined Infrastructure. With more than 12 years of expertise in different virtualization and cloud platforms, Patryk has broad experience in cloud solutions, system designs, influencing data center designs and understanding connections between ordinary Data Centers, virtualization and SDI. He believes that mastering the purpose of existing cloud solutions is the key to deliver and maintain the complete product, hardware and software, for any demand.)*

* **Dina Belova** *(Dina has been working with OpenStack as a cloud platform for more than four years, both taking part in private cloud tuning and upstream contributing. Her experience includes close interaction with all OpenStack projects and their improvement to satisfy the needs of cloud users. Dina leads upstream Performance team initiative and is part of Mirantis scale/performance testing initiatives.)*

Architecture and  optimization on 1000 nodes cluster in China Mobile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the leading mobile services provider in Mainland China, China Mobile Limited and its subsidiaries manage the world’s largest mobile network and the world’s largest mobile customer base.  China Mobile selected a software stack of all open source components.Use OpenStack as cloud solution, has deployed several 1000 nodes cloud cluster powered by OpenStack. In this topic,we will reveal the Architecture of the OpenStack cloud in China Mobile, the desicision debate during the planning&deployment. How to tune the cloud from underlaying Virtualization/storage/network to OpenStack components, from adjust OpenStack parameter to custom OpenStack components to meeting enterprise cloud and NFV requirement. Other operation issue and solution will also be addressed in this topic.  


* **yuntong jin** *(Yuntong Jin received his B.S in mathematics from Harbin University of science and technology, Master’s degrees in computer science from DaLian University of science and technology ,China. He joined SUN microsystem in 2008, work on Opensolaris  and joined IBM after that, work on KVM virtualization, cloud management.   He is currently a senior software engineer in Intel OTC, work on openstack community project, active developer in Nova/Ceilometer/Magnum.)*

* **Hao Li** *(LiHao is a cloud engineer in China Mobile)*

Hybrid Cloud migration and recovery using OpenStack Smaug
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

 The ability to implement a comprehensive DR solution is a critical requirement for enterprise-grade readiness. OpenStack Smaug provides a framework of APIs and services to orchestrate data protection and recovery of all the entities that comprise a production site.  Smaug APIs simplify the process of building a viable Disaster Recovery mechanism between the running site and an independent DRP site, that runs in a completely separate OpenStack instance. In this session, we will share how Huawei uses OpenStack Smaug in its Hybrid Cloud solution to implement a cross-cloud disaster recovery, helping its customers to protect their data in the public cloud, or on another private cloud, while retaining a very short “back to business” time, in case of a service outage.


* **wei yin** *(Wei Yin, over 9 years experiences working in storage area, insterested in distributed storage, data protection algorithms, data recovery soltuions.   Wei used to work for emc distributed storage products like atmos and vipr for years as a fundamental member. Now Wei is working for Huawei's hybrid-cloud project, and is leading a team to research and develop DR solution across clouds.   Wei is also a core member of openstack smaug project, who has contributed several important BPs for smaug design.  )*

Why Insurance company Folksam choose City Network OpenStack Iaas cloud for finance and inscurance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Presenters are Daniel Gustafsson VP-BU-Compliant Cloud at City Network and Roger Ewert IT area architect for Technology and Infrastructure at Folksam Late 2015 City Network launched a initiative to build IaaS clouds based on OpenStack for regulated industries with a heavy focus on Bank and Finance. Insurance company Folksam was one of the first customers that started using the servcice. Folksam wanted to change the way the ran thier applications and services. They wanted be able to have a scaleable platform that could easily be deployed thru automation tools like ansible and function with contionues deployments. In this presentation we will cover how this was acomplished.   .


* **Daniel Gustafsson** *(A veteran of almost 20 years in the IT and telecom industry. Started as a sys admin and worked my way to a management postion. Cloud and mobility evangelist  Career: Sys admin at TietoEnator  Sys admin at VM-data  Cloud and mobility strategy at Logica Cloud and mobility strategy at CGI Mobility strategy, mobile security at moWizor Current: VP- Business Unit- Compliant Cloud at City Network Hosting  )*

* **None None** *(None)*

OpenStack Management at Hyperscale – a Verizon case study
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Verizon Wireless is using OpenStack as the basis for the Verizon Cloud Platform (VCP).  Openstack is helping bring features to customers faster, allowing the business to be more responsive to internal requests for services and to deliver innovative solutions to enterprise customers.  Workloads extend far beyond Infrastructure as a Service to also include networking products, databases, data-stores, hosted applications and more.    VCP services are delivered by a federated group of datacenters distributed globally. Verizon will share lessons learned from deploying and operating early phases of the Verizon Cloud Platform - an OpenStack cloud.


* **Andrew  Hendrickson** *(Distinguished Member of Technical Staff Verizon Wireless January 2015 – Present Greater New York City Area Distinguished Member of Technical Staff for National Network Operations within Verizon Wireless. Solution Architect ESRI November 2008 – December 2014 (6 years 2 months) Since GIS has grown from the back office to the enterprise, many organizations, large and small, need assistance realizing the potential for what geospatial technologies can do for them. Andrew assists in this arena. He helped ESRI clients in the design, development, and deployment of their geo-enabled information systems. Manager, Spatial Data Analysis & Geographic Information Systems Verizon Wireless April 2000 – November 2008 (8 years 8 months) Andrew was responsible for the management, development, and support of Verizon Wireless's web-based Geographic Information System. He designed and built the system from the ground up, with no existing application in place prior. This system is utilized internally to map, model and solve complex spatial analysis issues as they relate to the Verizon Wireless network landscape including EOC operations. He also managed the directional Spatial Data Process which supports the flow of coverage information and other spatial data from Verizon's network RF Engineers to collateral available in a Verizon Wireless retail store. Lastly, Andrew was responsible for the management and scheduling of ad-hoc cartographic requests and complex spatial analysis that support all aspects of the Verizon enterprise.)*

* **Sanjay Mishra** *(Sanjay Mishra is Founder and CTO of Talligent, the leading provider of cost and capacity management solutions for OpenStack and hybrid clouds.  Day to day, his activities include setting company strategy, working on Openbook deployments, creating a customer driven roadmap, and writing code.  Prior to Talligent, Sanjay was involved in a wide variety of IT infrastructure startups and roles, including co-founding a venture-backed network monitoring company and engineering and consulting roles at Tivoli and IBM.)*

* **Billy Felton** *(Work experience: 8 years working military intelligence electronic warfare systems, software development and integration for 2 years with OSI. 16 years with Verizon Wireless. Currently at Verizon Wireless, Billy leads the Tier 3 Engineering team focusing on problem systems and new technologies. These efforts primarily involved architecture and design changes correcting flaws that would limit a systems capabilities to fulfill business requirements.)*

Deutsche Telekom Openstack University – Prepare the Organisation for Disruption
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Latest since the market launch of Deutsche Telekom’s Open Telekom Cloud, the demand for Open Source and OpenStack expertise has risen substantially at Deutsche Telekom. In Europe in depth experts in this field are far below demand and face a very competitive environment. Therefore, the required expertise needs to be fulfilled by internal skill transformation of existing workforce. The presentation outlines how Deutsche Telekom approaches this challenge by providing an internal OpenStack University, which aims to complete external offers for training. Central challenge is the change of mind set and attitude of Mode A Experts towards the new Mode B Model which affects all end2end processes of the IT application lifecycle. It is further outlined how this transformation is triggered. Challenges and pitfalls are described as well as transformation elements are presented. Feedback and first experiences with the program will give insight on how it is adopted and what can be improved.


* **Clemens Hardewig** *(Dr. Clemens Hardewig is currently responsible for the delivery of Open Telekom Cloud platform and services at Deutsche Telekom. After he completed his phd studies in technical computer science and microprocessor architecture, he became employed as responsible head of mobile device software. Since his studies he has been intensively engaged on open source software and Linux. Clemens Hardewig held various management positions in the IT service and IT infrastructure area, after joining Deutsche Telekom in 1997. Since 2010 he has been responsible in a management position for the design, installation and operations of cloud infrastructure platforms. Furthermore, Clemens Hardewig is also currently working on the set up and development of a technical ecosystem and community for OpenStack offerings of Deutsche Telekom. Therefore, the technical development of the platform as well as the product development of PaaS and SaaS solutions and thus their operations are the main focus areas of his work.  )*

People, Process, and Technology: Oh My!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a tool, and tools are meant to do one thing well. Unfortunately, a tool isn't enough to solve business problems. People and processes are more important than the right tool. This talk will address how to work with the people and processes needed to succeed with cloud.  We will: Explain challenges with people (governance) Explain challenges with processes (waterfall to agile) Offer solutions and best practices This session discusses a specific solution that can be used by organizations to increase agility. It is a how to, not a philosophical discussion What can I expect to learn? It will: Organizational best practices to help with people Development changes (waterfall to agile) Process changes to give power to each person/organization


* **Greg Pryzby** *(Greg Pryzby has been using Open Source since the 1980s and working with Linux since 1992. Over the last 2 decades Greg has helped companies use Open Source to solve business needs. Greg is also the benevolent dictator for life of Northern Virgina Linux Users Group (NoVALUG.com))*

Service Function Chaining for vCPE with OpenStack and Software Defined Networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Service providers and the broader vendor community have made progress in virtualizing key vCPE network functions. Concurrently, there is a strong push to bring these functions to the cloud. This session will discuss how Openstack is enabling this transformation and the role played by technologies like SDN and NFV. It will also discuss the latest advances in the networking stack of the Linux kernel which further enable these network functions to run in a fully distributed architecture. Finally, it will tie all these concepts together proposing a model for implementing virtual CPE services.


* **Valentina Alaria** *(Valentina Alaria has been part of the OpenStack community for 5+ years and has worked with 100s of users throughout their journey of learning, designing and deploying OpenStack-based cloud solutions.  A product innovation strategist and technology evangelist, Valentina has 10+ years experience with Cloud and Datacenter Infrastructure and has been involved with SDN since the early days throughout her endeavors at PLUMgrid, Nicira and Cisco. Valentina has held roles across engineering, Product Management and Marketing and currently runs Product and Solutions Marketing & Training for PLUMgrid.)*

* **Rafael Gonzalez** *(Areas of Expertise: Data center infrastructure and virtualization technologies. Server and Desktop Virtualization, Alternative Desktop / Thin Client Computing, Cloud Computing, OpenStack, Cloud management technology. Red Hat Enterprise Linux ; OpenStack Platform ; CloudForms ; Enterprise Virtualization ; OpenShift IBM System x ; Pure Systems)*

Deploying and Operating a Production Application Cloud with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Swisscom has one of the largest in-production industry standard Platform as a Service built on OpenStack. Their offering is focused on providing an enterprise-grade PaaS environment to customers worldwide and with various delivery models based on Cloud Foundry and OpenStack. Swisscom embarked early on the OpenStack journey to deploy their app cloud partnering with Red Hat, Cloud Foundry, and PLUMgrid. With services such as MongoDB, MariaDB, RabbitMQ, ELK, and an object storage, the PaaS cloud offers what developers need to get started right away. Join this panel for take-away lessons on Swisscom’s journey, the technologies, partnerships, and developers who are building apps everyday on Swisscom’s OpenStack cloud.   


* **Pere Monclus** *(Pere is the co-founder and CTO at PLUMgrid where he builds innovative solutions in the areas of SDN and Cloud. Before founding PLUMgrid, Pere was a Distinguished Engineer at Cisco Systems in the Research and Advanced Development team, where he led innovation in the areas of cloud, security and converged infrastructure. Prior to that, he was responsible for the architecture and technology of network services and their integration with switches and routers in data centers. He sponsored some of the early work around SDN, including the SIGCOMM 2008 OF prototype on Cisco’s Flagship Catalyst 6500 platform. During his 12-years tenure at Cisco, Pere led the development and architecture of billion-dollar in the area of firewalls, L4-L7 load balancing, application development and data center switching. He has filed multiple patents in the area of networking, including control plane, data plane, security, load balancing and cloud, and is a frequent speaker at networking technology forums.)*

* **Chris Wright** *(Chris Wright is the Chief Technologist at Red Hat where he is leading engineers who work on cloud computing, distributed storage, network virtualization, containers, and continuous delivery.  During his more than 20 years as a software engineer he has worked in the telecom industry on high availability and distributed systems and in the Linux industry on security, virtualization, and networking.  He has been a Linux developer for over 15 years, most of that time spent deep in the Linux kernel. He is passionate about developing open source software to serve as the foundation for next generation IT systems.  He lives in sunny Portland, OR where he is happliy working on open source projects such as OpenDaylight, Open vSwitch, OPNFV and OpenStack.)*

* **Marcel Haerry** *(Marcel Haerry is leading the architecture of Swisscom's OpenStack based environments. With the goal of providing an elastic environment for modern platforms, such as PaaS based on CloudFoundry. Having both a system and software engineering background and years of participation within devops-minded community (e.g. Puppet), he is seeking for an automated and continuously integrated delivery of operational platforms.)*

* **Sandra O’Boyle** *(Experienced IT and telecom marketing manager and research director with over 15 years of experience. Skills include market positioning and research, brand awareness, value proposition development, content creation and marketing, competitive analysis, customer targeting, lead generation campaigns and sales training and collateral.Provide valuable market insight and product marketing strategies, experience working with senior executives in engineering and product development roles as well as sales and marketing.Excellent understanding of the competitive issues and trends shaping the telecom and IT sectors.Specialties: Mobile networks and network intelligence, Enterprise Mobility, M2M, Mobile data services, Enterprise networks, Collaboration and Communications services, Cloud strategy and services)*

OpenStack Called to Public Service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the OpenStack community and technology grow and mature, we are seeing full-circle adoption within public sector organizations. The public sector is finding that the combination of leading-edge technology and enterprise-grade capabilities makes OpenStack viable technology for meeting the policy and budget demands being handed down from top-level decision makers. In this session, we will take the journey from inception to current day adoption of OpenStack, focused on examples within government, research and scientific communities, and higher education. Attendees of this session will hear about use cases and best practices in the public sector. We’ll also share specific customer implementations of OpenStack and how they are being used.


* **Kevin Jones** *(Kevin Jones is a Cloud Architect for Red Hat. His mission is to bring OpenStack into public service for Government, Research, and Educational entities. Kevin spends his time working with customers to define use cases around cloud and devops. Kevin has significant experience working with research and scientific computing entities to determine best fit for OpenStack and other technologies. Kevin comes to Red Hat from NASA Langley Research Center where he was the Chief Technologist for IT. In his role at NASA, he helped evangelize the use of hybrid cloud computing. Kevin came up in his career as a developer first and via curiosity, migrated to a holistic approach focused on utilizing technology to deliver business results. Kevin has been in the IT industry in Public Sector space since 2001. He came up as a developer and evolved into a full bore cloud solution architect. He carries Red Hat certification in OpenStack and Solution Architect certification in Amazon Web Services.)*

* **David Huff** *(David is a senior solutions architect at Red Hat, and Team Lead for the Public Sector Virtualization and Cloud specialist group focusing on OpenStack. David has been at Red Hat for over 12 years, and has held several different roles including product development on some of Red Hat's earlier Virtualization projects.  Currently David works exclusively with the public sector supporting both federal and local customer as well as higher ED customers. )*

Case Study of an OpenStack Deployment in China
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a widely used cloud management framework driven by a very active technical community. VMware joins OpenStack community effort and provides an enterprise ready OpenStack distribution (VMware Integrated OpenStack). In this session we will talk about VIO status and deliver a real customer case study deployed in China with other VMware products including vSphere, vSAN and NSX.


* **Gavin Lu** *(Gavin Lu is the site lead for VMware OpenStack R&D teams in China. He joined VMware in early 2009 and managed various R&D teams on Hyper-V Manager, VDS, VxLAN, VCNS, vSphere Big Data Extensions, VMware Integrated Containers and a few other internal engineering projects. Before that, he worked in engineering and management positions at Sun Microsystems, Microsoft, AOL for multiple years. He holds Bachelor and Master degree of Electrical Engineering from Tsinghua University.)*

Moving from productivity to profitability: winning clients with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has changed the way the world builds & integrates cloud technologies. For you, it's changed the way you do business by bringing you value through a robust & interoperable foundation for cloud. How do you help your customers realize the value that OpenStack can bring to their business? In this non-technical session targeted to executives & sellers, we will discuss several approaches they can use to introduce, demo, and position OpenStack to three types of hypothetical customers: a customer with no knowledge of cloud or OpenStack, a customer with knowledge of cloud but no knowledge of OpenStack, and finally, a customer with knowledge of cloud and misconceptions of OpenStack. In addition we will provide proven strategies that attendees can use to introduce and discuss OpenStack within their own organizations.


* **Sean McClintock** *(Sean McClintock is a tinkerer, a problem solver, and someone who likes to share complex ideas in simple ways with the world.)*

* **Manuel Silveyra** *(Manuel Silveyra is a Senior Cloud Solutions Architect. Manuel's focus is on OpenStack, Docker, Cloud Foundry, and Node.js.  He was previously a lead architect in the Linux Integration Center at IBM. Manuel received B.S. degrees in Electrical Engineering and M.S. degree in Computer Engineering from the University of Texas at El Paso (Go Miners!).)*

Deep dive into Keystone Tokens   - Which is best for large-scale production environment?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

   Now, we know keystone supports four different types of tokens, UUID, PKI, PKIZ and Fernet. Which is best for large-scale production environment?    In China Mobile public Cloud, We have built two cluster at different region - 1000 nodes in each cluster which contains 6 keystone nodes for high availability. We have done a lot of performance tests with different types of  tokens. Based on these results, we have  made careful analysis and lots of improvements for large-scale production enviroment.  


* **weiwei yang** *(Yang Weiwei is a staff engineer of China Mobile. She is now focusing on cloud computing and has abundant experience on cloud development and operating.)*

* **junwei liu** *(Liu junwei is a technical director of China Mobile. He is now focusing on cloud computing and has abundant experience on cloud development and operating.)*

* **Hao Li** *(LiHao is a cloud engineer in China Mobile)*

China 2016 OpenStack Roadshow - Use Cases you must know
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the rapid development of cloud infrastructure, OpenStack has been the dominated cloud platform in China. As the leading OpenStack service providers in China, 99Cloud & AWcloud are devoted to the OpenStack ecosystem, participate and witness the success of OpenStack. We have successfully helped hundreds of companies adopting OpenStack solution, working closely with our customers to develop OpenStack solutions for their business. We’d love to join together to share typical use cases in key vertical industries, from sales, technical decisions to the lessons learned. We’d love to talk about our experiences on cloud business, how we help enterprises achieve success and how OpenStack brings technical innovation and social benefit, such as our effort on optimizing the infrastructure of Jiangsu Province Taxation Bureau to increase taxing efficiency for millions of local companies, building public cloud infrastructure for Guizhou Province to help local companies reduce, etc.


* **Li Ma** *(Nick is a Linux veteran with over 10 years of experience on Linux development. He is the cloud architect at AWcloud where he works on OpenStack Networking, SDN/NFV, messaging system and large-scale cloud architecture. Prior to joining OpenStack community, he spent 4 years on infosec, virtualization/containerization and distributed system.)*

* **Liu Qing Jing** *(Senlin Core)*

* **Shuquan Huang** *(Shuquan Huang is technical director of 99cloud, one of top 3 OpenStack provider in China. He focuses on helping enterprise land OpenStack cloud and migrate the data & applications to cloud environment. He started his Openstack journey from 2011 and actively involved in the OpenStack community as a contributor and speaker.  )*

Cazando Mitos en OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Todos nos hemos preguntado cosas como: "¿Es OpenStack un competidor de AWS y VMware?", "¿Está OpenStack listo para producción?", o "¿Va a reemplazar OpenStack toda nuestra infraestructura virtual?". Aunque bien es cierto que OpenStack proporciona una solución para mucha gente con diferentes intereses y objetivos, todavía hay algunas particularidades que debemos tener en cuenta antes de ponernos en marcha. Después de haber trabajado con clientes en OpenStack, nos hemos dado cuenta de que en muchos casos la realidad no cumple con las expectativas. Por eso, es importante que los nuevos stakers entiendan la realidad, la separen de los mitos, y sepan cómo sacarle el máximo partido a OpenStack. En esta sesión explicaremos algunos de los mitos más comunes sobre OpenStack recogidos de nuestros propios clientes y enumeraremos las diferentes ideas preconcebidas que los nuevos usuarios tienen cuando comparan OpenStack con otras herramientas, clouds, o servicios.


* **Adrian Moreno Martinez** *(Adrian is a software engineer at EMC. He is part of a team focused on engaging and enabling modern application developers, DevOps teams and next-gen ISVs. He is responsible for leading some OpenStack and DevOps related projects. In the last 5 years he has been mainly working in Cloud computing and distributed systems. Prior to EMC, he had the oportunity to work in an FP7 european project at the University Rovira i Virgili in Tarragona, Spain. There, he was one of the founders of StackSync, a fully-featured personal cloud that integrates with the OpenStack platform.)*

* **Javier Soriano** *(TBD)*

Why you shouldn't fork OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Following upstream is not easy.There are training sessions and mentoring to help but sometimes the problem is not knowing how to do it but not having time to do it properly. As cloud operators we have day to day constraints and we often need to fix and patch as soon as possible which is not really compatible with upstream at first look. After more than one year in production with many internal patches, we learned that we have no other choice than committing upstream our previous and future modifications and that's why we need a smart solution to do what we couldn't do before.We don't want to maintain our fork of OpenStack so we are currently improving this contribution process and we would like to share our mistakes and discoveries on our journey with OpenStack.


* **Adam Kijak** *(DevOps at OVH working on large cloud deployments.)*

Lessons from the trenches - onboarding customers and  workloads  to OpenStack private clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

After a customer is provided a managed private cloud based on OpenStack , we often get a question from the customer around "Now what do we do to get our workload onboarded ?" The typical challenges we have seen include - Level of OpenStack exposure needed for end users - including Horizon vs Custom portals - Migration of existing VMs with minimum disruption - including compatibility of VM formats - Application deployment mechanisms - including  automation considerations and containers - Hybrid scenarios - dealing with workloads that span across hybrid clouds - Tuning the stack based on workload considerations We will share the lessons learnt and real world customer case studies , including some of  the common pitfalls that break workload onboarding to OpenStack  and how to avoid them.


* **Anupriya Ramraj** *(Americas lead - Cloud Automation - HP Enterprise Services    https://www.linkedin.com/in/anupriyaramraj o Evagelist and architect for large lighthouse customers embarking on cloud journey to setup OpenStack private clouds. Provide techical oversight on all  private cloud deployments in Americas executed by HP Enterprise Services. o  Previous role : Engineering manger for teams in HP public Cloud that created automation to operate OpenStack at scale .  Delivered an entire operational toolset and CI/CD tool chain for deploying, administering and supporting OpenStack at a scale of several thousand nodes. o Instrumental in HPE playing a major role in Operator meetups and evangelist of the operator tooling project :  https://wiki.openstack.org/wiki/Osops      )*

* **Rick Mathot** *(Rick Mathot APJ Cloud & Data Centre Services Leader at HP Enterprise Services)*

Amadeus’s journey building a Software Defined Data Center with VMware VIO and NSX
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session you will learn how Amadeus IT Group, a multi-national IT provider for global travel and tourism with over 3 billion euro in revenue, undertook a transformational project to modernize their infrastructure. We will go through some of the drivers for the project and technology choices evaluated for the project. You will learn how and why Amadeus chose OpenStack over AWS, Private Cloud with Chef / Puppet based automation.   After deciding to go with OpenStack, we will go through why Amadeus decided to go with VMware Integrated OpenStack and NSX for this critical project. We will then share the high level design and best practices Amadeus implemented and learnt from this project.  


* **Sai Chaitanya** *(Sai Chaitanya is a Product Manager at VMware and focuses NSX platorm - Network and Security Virtualization Platform. He focusses on NSX integration with OpenStack Neutron and extending NSX to support Cloud Native Aplications using Container technologies such as Docker, Kubernetes and other platforms.   )*

* **Arthur Knopper** *(“Arthur Knopper is an Associate Director with Amadeus and drives the implementation of a multi-region Enterprise Private Cloud based upon VMware products such as VIO and NSX. The Amadeus private cloud is catering for piloting applications provided via an open source container stack and will expand further to take on mission critical workloads.”)*

Moving Large Workloads from a Public Cloud to an OpenStack Private Cloud: Is It Really Worth It?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It can be easy to come up with a TCO analysis that would challenge any public cloud and make you think, "let's go in-house!". What are the challenges and is it really worth it? The TubeMogul Operation team went thru the technical challenges at building a private cloud. In this presentation you will learn how the team went from a R&D to an automated deployment of a bare-metal servers to finally migrate a large workload from a Public Cloud to its own Private Cloud infrastructure. We will detail how the team dealt with unexpected issues and also how we chose the hardware, estimated capacity, stay cost effective, improve overall performance of the system, and bring better control and visibility.


* **Nicolas Brousse** *(Speaker's Bio: Nicolas Brousse is Senior Director of Operations Engineering at TubeMogul (NASDAQ: TUBE). The company's sixth employee and first operations hire, Nicolas has grown TubeMogul's infrastructure over the past seven years from several machines to over two thousand servers that handle billions of requests per day for clients like Allstate, Chrysler, Heineken and Hotels.com. Prior to TubeMogul, Nicolas was an IT leader at companies such as MediaPlazza, Kewego, and Lycos France. Nicolas has recently been working on a public cloud to private cloud migration effort and has spoken to conference such as Velocity, SuiteWorld, SRECon, USENIX LISA, and PuppetCamp.   https://nicolas.brousse.info/ https://www.shell-tips.com/ http://lanyrd.com/profile/nicolasbrousse/)*

Case Study in deploying SAS to OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Abstract


* **Donna DeCapite** *(Bio)*

Orchestrating an OpenStack-based IoT Smart Home
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session presents a reference architecture for building an IoT smart home based upon OpenStack. Our subject matter experts from IoT technology and back-end cloud platform will share their experiences on how to integrate an end-to-end solution from the IoT sensor to scalable cloud-based applications. In this session, we will discuss how various OpenStack components can be used to build scalable applications with back-end analytics for the IoT connected devices. The reference architecture features open-source components such as Zephyr, Ostro, MinnowBoard Max, Cloud Foundry, OpenStack and Open Connectivity Foundation’s IoTivity for interconnectivity.


* **Dr Yih Leong Sun** *(Dr Sun accumulated more than 16 years of experience in software development and infrastructure deployment. He obtained PhD Computer Science (Multi-Cloud Infrastructure) in 2013. He spent the past 7 years on Multi-Cloud infrastructure development. He currently serves as a Senior Software Cloud Architect for Intel Open Source Technology Center. Prior to that, he was a Principal Software Engineer for a Fortune-100 Insurance Group, working for the next-generation Cloud platform project. He also led the engineering team of a few start-up companies in Singapore and Silicon Valley. His expertise is in Multi-Cloud orchestration and with a strong interest in building an Enterprise Multi-Cloud platform.)*

* **Michael Kadera** *(Michael Kadera has over nineteen years experience in Intel leading enterprise software development, Cloud and Infrastructure DevOps teams. Michael lead Intel IT’s Open Cloud Program in the design and implementation of private and Intel’s first hybrid cloud solutions. His team delivered deep technical and IT solutions and shared architecture knowledge across a wide spectrum of data center practices including orchestration, security and compliance, multi-tenancy and scalability in applications and software defined infrastructure.   Michael now part of Intel’s Open Source Technology Center leading the Cloud & Data Center Technical Marketing Engineering team.)*

* **John Geier** *(John has held several roles at Intel over the past 20 years, working with cutting edge Intel Architecture from Alpha to Production stages. He has spent over a decade in architecture, management, and deployment of datacenters. He currently serves as a Technical Marketing Engineer for the Intel Open Source Technology Center, focused on cloud and data center technologies. His expertise in this area is architecture and deployment.)*

300 node large-scale deployment commercial cloud platform in Bailian Group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Bailian group， at the first place of the top 100 chain enterprises in china,  is the largest state-owned commercial and trading company, is also one of the world's top 500 enterprises. Bailian group as offline commercial carrier is called China's "wal-mart". Retail outlets are all over the country 25 provinces and cities, nearly 6000 offline stores. Business covers shopping plaza, supermarkets, convenient stores, etc. Since 2014, the Bailian group had been changing from the traditional entity retail to the Internet all-channels. It will become the biggest O2O platform from domestic largest traditional retail industry, which is based on the OpenStack technology. The platform will cover data exchanging, online-offline payment system, bailian E mall E-co.mmerce platform and big data of Consumption.


* **Jin G** *(More than ten years experience in IT project management, long worked in telecom operators. Senior traditional telecommunications、government and financial industry IT and cloud computing platform construction and project management experience.)*

* **Jian Wang** *(11+ years experience in IT, 7 years experience in Cloud Computing. Worked for Mirantis, Canonical, Nokia and Alcatel, as Senior Architect, Cloud Consultant, SA Manager, Senior System Verification Engineer. Involved in many customers' OpenStack Cloud Project: Shenzhen Stock, NUDT TianHe-2 Super Compute, Yahoo! Japan, NEC, State Power Grid Jiangsu, 1-Net, Capital One and Bailian Group. Leading UMCloud Architect team to provide Professional technical services to customers.)*

* **Zhixuan Li** *(Technical VP Leon has been working for IBM/EMC/UMCloud over 10 years. He is familiar traditional IT architecture, as well as cloud architecture. For OpenStack, he mainly focus on storage and total solution. Currently he is leading service team to deliver project.)*

OpenStack Practice in China Telecom
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the cloud computing leader and practitioner in China, China Telecom group had started the cloud computing as early as 2009 which opened its cloud computing glorious journey. After years of efforts and construction, China Telecom Group has built up a unified management cloud computing framework to adapt cloud computing resource pools in region. By using OpenStack Cloud technology, China Telecom has gained great success in protecting more cloud integration including some cloudstack cloud, large amount of servers in one data center deployment and multi-regional  deployment. At the sametime, China Telecom has also ensured business continuity and high processing capacity in key components of the computing , storage, networking , management. And all the systems run stable in OpenStack cloud without a single fault point.


* **None None** *(None)*

OpenStack Journey in Tieto Elastic Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Tieto is the #1 cloud service provider in Northern Europe with over 150 cloud customers in the region. Turnover is approximately €1.5 billion. Chronicle our journey to a new operational meta for our OpenStack cloud. From humble beginnings, follow our path to operational freedom and the security of knowing that every change is proven and can be deployed safely at any time. See how we’ve built on the OpenStack-salt project along with utilizing CI/CD pipelines to allow upstream bug fixes, security patching, service lifecycle management all off a git commit. The session will feature live demos so come prepared to be blown away.  


* **Jakub Pavlík** *(Jakub Pavlik is CTO and chief architect of tcp cloud (http://opentcpcloud.org). He is focused to virtual private cloud and private cloud solutions based on OpenStack and Kubernetes and vendors derivates. He is responsible for whole infrastructure solution (architecture, implementation, operation). He is member of OpenContrail Advisory Board.)*

* **Lukáš Kubín** *(Cloud infrastructure architect with strong focus in open cloud technologies, storage and cloud native applications. » Leading an OpenStack based, hosted multitenant cloud service development. Responsible for proper choice and integration of technology components and service design. » Passionate in automating infrastructure operations and full-stack performance troubleshooting. Utilizing modern statistical tools and methods supporting infrastructure metrics analysis. » Helped to build Tieto Dynamic SAP Landscape service, mainly by leading storage services and platform automation, including creation of toolset handling automated failover of SAP systems. » For over 13 years has been focused on datacenter infrastructure architecting and providing presales support – consulting storage, server availability and backup services, dealing with clients and supervising implementations.)*

Scaling Science Clouds in Europe with TOSCA and Heat Translator
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Last summit we introduced the work being done by the Indigo DataCloud project, whose members include CERN, UPV and many other institutions in Europe. The goal is to build a sustainable infrastructure for science, spanning multiple computer centers and existing public clouds. We rely on TOSCA as the standard to model the full stack, and have now expanded the infrastructure to include multiple OpenStack and OpenNebula sites and public clouds running proprietary software. As the infrastructure grows and extends to include more countries, so do the use cases both in number and complexity. In this presentation we will summarize the work being done both in the Heat Translator and the TOSCA parser, and how we build on them to model and deploy our infrastructure. We will demo a complex application defined using TOSCA and deployed in multiple heterogeneous sites, along with some of the workflows we apply to running applications.


* **Mathieu Velten** *(Mathieu Velten is a software engineer at CERN. He's currently a member of the CERN OpenStack team, focusing on service and application orchestration and container deployments, and working on the Heat translator for the INDIGO DataCloud eurropean project. Previous work included Technological Research at Atos Toulouse mainly for the French spatial agency regarding container and new Big Data technologies like Mesos and Kubernetes, and several years of Eclipse development for Model Based applications.)*

* **Sahdev Zala** *(Sahdev Zala is an IBM Advisory Software Engineer in the IBM Cloud Architecture and Technology organization. In his current role, Sahdev is Project Technical Lead (PTL) of OpenStack TOSCA-Parser and Heat-Translator projects. Both the projects are part of OpenStack Heat main program. He is a TOSCA Technical Committee member. He has also contributed towards LDAP enhancements in the OpenStack Keystone. Previously, he worked on developing IBM software for small and medium businesses and cross-product serviceability initiatives. He has authored IBM Redbooks, articles for developerWorks and ThoughtsOnCloud, white papers and technical documents on a variety of topics.)*

* **Miguel Caballer** *(I obtained the B.Sc. M.Sc, and PhD degrees in Computer Science from the Universidad Politécnica de Valencia (UPV), Spain, in 2000,  2012 and 2014 respectively. I am part of the Grid and High Performance Computing group of UPV since 2001. I  have participated in different research projects about the application of Grid and Cloud computing techniques to several areas of engineering. Other fields of interest include green computing.)*

Postal Savings Bank of China  with the most of outlets embraces mobile Internet by using OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Postal Savings Bank of China(PSBC) is the world's most outlets, most extensive coverage, the largest number of customers commercial bank. PSBC has more than 40,000 outlets, nearly 490 million customers. Its business covers China's urban and rural areas. From the 2H of 2015, PSBC use OpenStack to build its mobile Internet service platform, providing services include small consumer loans , mobile banking, self-service banking App, and so on. These systems are currently running on OpenStack platform. By OpenStack, PSBC are gradually transferred large number of customers from offline to online, providing Internet banking services.PSBC's OpenStack environment currently has 150 nodes, and is planning a larger platform about 650 nodes.


* **Chongyi Zhou** *(Chongyi Zhou is EasyStack company vice president, responsible for industry solutions and business development. Prior to joining EasyStack, Chongyi worked at Oracle company as Exadata Chief Architect of China. Chongyi has been committed to large-scale government information technology, traditional IT transformation to cloud computing, massive data processing and analysis.)*

How LeoVegas changed the game with OpenStack: a case study
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Why did the Online Casino Operator of the Year 2016 choose OpenStack? How do they make the most of its advantages? And what challenges did they need to overcome? Hear the LeoVegas story with firsthand insights from their head of tech ops and Rackspace’s director of OpenStack International. Our case study will look at LeoVegas’s approach to:·       Development, tech and production environments·       Real-world advantages & problems·       Multi-region setups·       Keeping it running at high availability·       Migrating from public to private OpenStack clouds What can I expect to learn?Discover how an award-winning online business teamed with Rackspace to implement and optimize OpenStack for public and private clouds.  


* **Frank Weyns** *(Frank Weyns is the Director OpenStack International at Rackspace. His mission is to deliver OpenStack private clouds with 99.99% of uptime to enterprises. He has 20 years of experience in enterprise open source, and the last 4 years he is focusing on OpenStack and cloud technologies. He is a trusted advisor to the financial and telecom world. He loves to share his knowledge with lectures at universities and business schools.  Contact Frank at: http://nl.linkedin.com/in/frankweyns/)*

* **Martin Hed** *(Martin HedLeoVegas GamingMartin serves as head of technical operations, IT and security at LeoVegas. He is a senior manager and consultant with extensive experience from e-commerce to web development.https://www.linkedin.com/in/martinhed )*

In depth analysis of deploying OpenStack for the Financial Sector; HENGFENG
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack provides a scalable datacenter solution, but how to deploy it when it concerns the financial sector? In this presentation, a detail will be given about deploying Liberty at the HENGFENG BANK (1987, commercial, headquartered in Yantai) to provide them with a platform to meet the demands of online banking, handling credit and credit card services in a time when commerce faces a year over year increase. You will learn the characteristics and how we have performed the analysis; from question, the PoC phase to the eventual deployment and production phase. To meet the demands of their clients, security, high availability and providing scalable services are key. Following the timeline, you will be informed about the decisions that have been made, and challenges that have been faced and how they have been resolved. Currently, the platform that has been delivered hosts over 5000 virtual instances of different operating systems, hosting key business functionality, in an HA setup.


* **Hui Cheng** *(Hui is the CEO & Founder of UnitedStack Inc., an OpenStack start-up with targeting Greater China and Asia open cloud market. As a new enterprenour who has deep engineering background in open source and cloud technologies, Hui gathered a group of powerful and talented OpenStack developers and top engineers from China and U.S., and founded this cloud company to build an open and commoditized cloud OS based on OpenStack as well as some other open source softwares in February 2013.  Hui’s dream is to build a cloud software company to overthrow the traditional enterprise IT industry, as well as a respectable open source company that could be heaven for technical engineers.Prior to starting his own business, Hui was the technical leader of the OpenStack team in Sina, where he initiated the first OpenStack based on public Iaas cloud in China, while leading his team to become the No.1 corporate contributor in China.)*

Reducing Your Risk in Adopting OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With so many enterprise and service providers looking at OpenStack to reduce OPEX or CAPEX, unseen risk inevitably enters the equation.  This session will focus on lessons learned to help you bake the perfect cloud strategy. With this knowledge, your resulting solutions will provide value to all vectors of your business plan. Translating business stratagem to your technical teams through deep understanding of OpenStack is similar to trying to arrange all the grains of sand in a beach so we share Agile methods of achieving success. Your reduced cost of entry into cloud by avoiding common pitfalls and misconceptions enables you to enter markets faster while staying Agile in both approach and operation.


* **Eric Lajoie** *(Eric Lajoie is a OpenStack & NFV Architecture Consultant for HP Helion Professional Services (PS) – Helion OpenStack, Germany. In his current capacity, Eric is responsible for end to end solution design, be it IPv6, EPC, or virtualization solutions. His key interests and achievements are in design and implementation of carrier grade Helion OpenStack solutions as well as integration with SDN, EPC, LTE, VoLTE, Femto, M2M, VMware, and all flavors of Linux including RHEL, Ubuntu, Debian, CentOS, and Gentoo. He is responsible for solution, design, service implementation and assessments related to service providers environments.)*

* **Glyn Bowden** *(Glyn Bowden is the Chief Technologist for HPE's open source Cloud Consulting organisation in EMEA. He specialises in enterprise cloud, data center transformation, shared infrastructure and using IT services to enable business. He has over 15 years experience designing and implementing cloud solutions both with vendors and multi-national end user organisations.)*

Public Cloud done right: Making of the SysEleven Stack 1.0
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation explains the development of SysEleven's OpenStack-based public cloud. After two years of development, the SysEleven Stack 1.0 went live on July 1, 2016. In this presentation, we'll share our experiences over the last two years, covering all the different aspects of building and running a public cloud based on OpenStack. You'll get a basic idea of the architectural design of our OpenStack platform. You'll learn about the motives behind our design decisions. Highlights include building a network design based on 100G hardware that can scale out properly choosing the right hardware full lifecycle management for the servers doing Software Defined Networking (SDN) and Software Defined Storage (SDS) right getting central aspects of OpenStack operations right from the get-go mastering the many challenges, big and small, that OpenStack has ready for you


* **Felix Hupfeld** *(Felix Hupfeld is one of the creators of XtreemFS, the open-source fault-tolerant distributed file system, spent several years at Google to accompany Google's tape backup system from pre-production to mind-blowing scale, and returned to Berlin to join in founding the software storage company Quobyte. Quobyte's Unified Storage Plane enables everyone to run professional storage infrastructure on standard hardware.)*

* **Martin Loschwitz** *(Martin Loschwitz became a member of the Open Source Community in 2000 and has been a Debian developer since 2003. He had his first contact with OpenStack in late-2011 and currently holds the position of the teamlead of the OpenStack team at SysEleven in Berlin, Germany. His primary technical focus are Software Defined Storage and Software Defined Networking solutions.)*

* **Erez Cohen** *(Erez Cohen acts as Mellanox Vice President for CloudX Program, responsible for all aspects of the program including architecture, implementation and marketing/sales. The CloudX program incorporate Mellanox state of the art network and storage interconnect product lines to form the most efficient and scalable cloud infrastructure. Between 2003 and 2013 Mr. Cohen led the Field Engineering group at Mellanox. In this position Mr. Cohen was responsible for Global pre and post sales technical support for OEMs and end users. As part of this role Mr. Cohen was involved with some of the largest and most complex data centers and High Performance Computing clusters in the world. Between 2000 and 2003 Mr. Cohen lead the Architecture and Design Validation group at Mellanox. Mr. Cohen holds a Bachelor of Science in Computer Engineering from the Technion Israel Institute of Technology.)*

Using RUP, XP and Kanban Programming For OpenStack Development
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Development process is fairly well documented and requirements for specific interactions with Git, Jenkins, Garrit and Zuul are somewhat straightforward. However, when it comes to the specifics on the developer's side, you're largely on your own. This is especially problematic in a world where development is moving from more traditional IT infrastructures to a more cloud-native architecture, so processes are already in flux. This talk will provide a guide to some of the more proven methods and practices that can be applied to achieve positive results, and how they apply to development in OpenStack.


* **Bruce Basil Mathews** *(Bruce has been a Senior Solutions Architect in the computer industry for almost forty years, working at Information International, Inc., Symbolics, Inc. Prime Computers, Inc., Computervision, Sun Microsystems, Hewlett-Packard, and now Mirantis. During his career, Bruce has provided integration services, application development, and large scale deployments for major corporate initiatives at companies such as PayPal, Salesforce.com, Wells Fargo, McKessen, Intel, and Dreamworks, Technicolor, American Express, CitrixOnLine, and Amgen to name a few. Bruce became involved with OpenStack in 2010 as a member of Hewlett-Packard’s Public Cloud team where he successfully on-boarded more than fifty customers, migrating application services from in-house to OpenStack on versions from Diablo+ to Grizzly, living with them through the upgrade process. Bruce was also heavily involved with the initial release of HP’s Helion Openstack based on the Juno release. Bruce has maintained an active role in the OpenStack, Big Data and Open Source communities. He is certified as an Administrator for OpenStack, Cloudera, and MapR.Customer engagements have typically included technical design, build, implementation, customization, integration and ongoing administration of multi-vendor servers, storage, SAN and network elements, hosted on-premises, implemented as a managed service, and/or publically hosted in the cloud.  Successful implementations have generally included multi-vendor Operating Systems (Solaris, HP-UX, AIX, Irix, RedHat, Ubuntu, CentOS, Debian, Fedora, Windows and Mac,) multi-vendor databases (Microsoft SQL Server, Oracle, MySQL, DB2, Sybase, Informix, PostGres, GreenPlum, Vertica, Cache, etc.) and NoSQL offerings such as CouchBase, CouchDB, Cassandra, MongoDB, etc. Applications implemented and supported have included a wide variety of multi-vendor commercial and non-commercial applications such as Microsoft ERP, Data Warehousing and Business Analytics, SAP, Oracle Manufacturing and Financials, PeopleSoft, etc. and Big Data solutions such as Cloudera, MapR, HortonWorks, and the eco-system that supports them based on Six Sigma methodologies. )*

Deploying OpenStack on a PUBLIC ISP in LATAM
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The main idea is to show how an ISP from LATAM deployed OpenStack to create a PUBLIC and PRIVATE cloud on the region  We include dealing with cultural changes, policy changes and procedural changes on the organization.    Gigared is a Telecomunication ISP from LATAM, they mainly sell Internet, Cable TV and VOIP.  We helped Gigred to Open their Public and Private Cloud using OpenStack.      http://cloud.gigared.com.ar/  


* **Rodrigo Benzaquen** *(Rodrigo is the founder and CEO of NubeliU. After spending 14 years in managing infrastructure MercadoLibre and nearly three years in Silicon Valley, he returned to Latin America with a vision:Private clouds should be simple, flexible and nimble no matter what kind of hardware is used.Before founding Nubeliu, Rodrigo joined MercadoLibre in 1999 as the first employee in the area of technology, one of the pillars of the IT team of the company since the early days. It was he who led the project implementation ongoing management of Private Cloud based on OpenStack, formed a dedicated team to support the growth that the company would face in the coming years - See more at: https://www.crunchbase.com/person/rodrigo-benzaquen#sthash.gBLQsZBG.dpuf)*

Deploying OpenStack for an NAVENT  RealEstate and Jobs Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Navent Group was established to provide the highest quality jobs and real estate online listings to people living in Latin America, as a majority of listings in the region are currently only available in print. The company was founded in 2010 with a mission to help its users find work and housing options. It owns five job classifieds websites: Bumeran, Konzerta, Multitrabajos, UniversoBit, and Curriculum, the most popular of which is Bumeran.com.Bumeran has over 5 million individual users per month and lists over 50,000 job postings.   We have been working with them deploying OpenStack, Ceph and Swift to manage DEV teams, Production Sites and gain agility to the business.   The idea is to show how we helped them on this process and discuss why we choose OpenStack instead of others solutions.


* **Rodrigo Benzaquen** *(Rodrigo is the founder and CEO of NubeliU. After spending 14 years in managing infrastructure MercadoLibre and nearly three years in Silicon Valley, he returned to Latin America with a vision:Private clouds should be simple, flexible and nimble no matter what kind of hardware is used.Before founding Nubeliu, Rodrigo joined MercadoLibre in 1999 as the first employee in the area of technology, one of the pillars of the IT team of the company since the early days. It was he who led the project implementation ongoing management of Private Cloud based on OpenStack, formed a dedicated team to support the growth that the company would face in the coming years - See more at: https://www.crunchbase.com/person/rodrigo-benzaquen#sthash.gBLQsZBG.dpuf)*

Balance workloads for optimal performance with Watcher
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Watcher is an open source software package which provides a flexible and scalable resource optimization service for multi-tenant OpenStack-based clouds. Watcher provides a complete optimization loop. This provides a robust framework to realize a wide range of resource optimization goals. The project joined the big tent recently. We tested Watcher on a 50 hosts cluster in September 2016 and this talk will give you the main outputs we learned from this experiment. 


* **Vincent Mahe** *(Vincent Mahé received a degree in computer engineering from ISEP (Paris) in 1995, then joined Orange Labs as a research and development engineer and first worked on several Orange web and mobile portals. He contributed during 2 years to the SVG Tiny working group at W3C. He then specialized in video preparation workflows for the media asset management system of the Orange group. Prior to working for b<>com, Vincent spent 4 years working for Orange on architecturing and deploying a Cloud SaaS solution for audio and video processing and metadata extraction.He is currently one of the lead architects of the Watcher project which focuses on resource optimization service for OpenStack.)*

* **Ananth Narayan Sankaranarayanan** *(I am currently a senior software engineer at Intel investigating usages and features for next generation platforms & processors. I completed my Master's in Computing Science at Simon Fraser University, and researching problems in power management in heterogeneous server clusters and data centers. I have published my research work in peer reviewed conferences. I come a background of power management, having worked on tools for validation of Intel(R) notebook platforms, primarily power management features.)*

* **Jean-Emile DARTOIS** *( )*

Deploying OpenStack Networks for Financial use cases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As IT organizations look to the cloud to reduce costs and provide greater agility to their business units, they’re also responsible for the security, and regulatory compliance of the systems that they build. This can be a daunting task, particularly for Financial Institutions which have the added responsibility of ensuring the security of their customers' financial information. In this presentation, attendees will learn how one large financial institution is solving these seemingly competing priorities through automation, micro-segmentation, and security in depth with Openstack and SDN.


* **Justin Moore** *(Justin Moore is a Principal Solutions Architect at PLUMgrid specializing in developing Cloud and SDN strategy and architecture for the enterprise. Prior to joining PLUMgrid, Justin served as a Sr. Director for Enterprise Growth at American Express, establishing and leading the Cloud and DevOps functions. At American Express, Justin led the creation of the Cloud cost model, Hybrid Cloud strategy, and PCI certification of the card processing environment. The adoption of the Cloud model led to significant cost savings over the legacy environment, as well as significant reduction in time to market for new business features through tight integration with the CI/CD pipeline.)*

Sungard Availability Services: Building a multihypervisor cloud with automated network services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Sungard Availability Services is a global provider of business continuity, information security, IT disaster recovery, and cloud systems.  Serving a diverse and highly demanding customer base, Sungard AS has partnered with Cisco and Red Hat to design an OpenStack cloud solution that supports both the KVM and VMware hypervisors while offering a unified set of managed network services.   In this session, you will learn about the infrastructure considered and chosen, the reference architecture employed, the current state of the deployment, challenges overcome in design and implementation, and key lessons to incorporate in future deployments.


* **Mike Cohen** *(Mike Cohen is Director of Product Management at Cisco Systems.  Mike began his career as an early engineer on VMware's hypervisor team and subsequently worked in infrastructure product management on Google and Big Switch Networks.  Mike holds a BSE in Electrical Engineering from Princeton University and an MBA from Harvard Business School.)*

* **Jason Plank** *(I have been working with cloud providers throughout the world and specialize in building scalable multi-tenant architectures for Service Providers to monetize. Over the last 10+ years I have focused heavily on working with Service Providers to solve complex architectural issues involving scale, monetization, and other business and technical requirements.I have become a trusted advisor to our Development/CTO teams as well as a trusted advisor to some of our more prominent Cloud/Service Providers. In addition, I have had the fortunate experienceof influencing new product(s) with the CTO and CDO orginizations at Cisco.In addition to the Data Center and Cloud experience over the last 7 years, I have worked at some of the largest ISPs (UUNet, MCI, and ETC) and have had a big focus on architecting SP Networks with various traditional / hybrid Service Providers.)*

Optimizing Cloud Resources leveraging OpenStack Watcher
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Watcher is an OpenStack Big Tent project which provides a flexible and scalable resource optimization service for multi-tenant OpenStack-based clouds. Watcher provides a robust framework to realize a wide range of cloud optimization goals, including the reduction of data center operating costs, increased system performance via intelligent virtual machine migration and increased energy efficiency.  In this session we will share some interesting use cases and challenges Walmart has experienced running one of the largest private cloud environments, and how watcher can be used as a resource optimization infrastructure. We will demonstrate how Watcher integrates with other OpenStack subsystems like nova scheduler and host aggregates. We will present how watcher can provide some interesting optimization use cases and capabilities: Workload consolidation and balancing Resource Prioritization, QoS and optimization strategies Datacenter energy conservation


* **Prashanth Hari** *(Prashanth Hari is a Senior Technical Expert (Cloud Engineering) in Walmart Technologies. Leading the cloud optimization efforts in Walmart.  Also, involved in various other projects like telemetry, CI/CD, Openstack Ansible, Fleet management etc. He is been active since Openstack Essex.  )*

* **Susanne Balle** *(Susanne is a senior Principal Engineer at Intel working on SDI and Cloud architecture and pathfinding. She has been involved in OpenStack since the Essex OpenStack summit. Her latest focus is on Watcher a service to optimize the Datacenter TCO via Data-analytics and ML models for OpenStack and non-OpenStack Clouds.)*

* **Sameer Adhikari** *(Sameer Adhikari works on OpenStack IaaS cloud in the @WalamrtLabs organization in Walmart eCommerce.)*

Experience with implementing Openstack & SDN for new pay-per-use business models
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

User Story of one of the leading  Cloud & Managed ICT Service Provider (operational services, a Joint Venture by T-Systems International and Fraport) in Germany. We’ll explain why OpenStack became one of our strategic cloud platforms, why traditional solutions fell short, what we exactly realized and how we proceeded. We’ll furthermore explain our experience with our OpenStack distribution, why we needed a SDN-Controller and what it is precisely doing for us. -OpenStack as business enabler in our private and public cloud offering, new way of production leads to new flexible services with lower cost. -Automated provisioning of bare metal servers via MaaS and automated provisioning of virtualization stack via JuJu -Production grade neutron and Network automation via openContrail and OpenStack Liberty -fully automated install and lifecycle management incl. SDN-controller -Which components of OpenStack & SDN are important to us. -Where do we see room for improvement.


* **Andreas Meisinger** *(Service Provider Solution Architect for SDN & NFV at Juniper Networks with +20year Experience in Networking Industry. Current Focus areas are SDN & NFV for Service Providers, Openstack based Cloud Management, SDN-Controller technologies, DC-IaaS, DCI, etc…)*

* **Florian Hagemann** *(Service Provider Teamleader Linux & OpenStack at operational services.)*

* **Kim-Norman Sahm** *(Service Provider Solution Architect for Linux & OpenStack at operational services.)*

Developing for OpenStack APIs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building a cloud orchestrator is not like building any other cloud application. Not because it is more challenging, they’re all challenging...but because an orchestrator needs to expose the full range of functionality that the underlying cloud exposes. If the orchestrator can't provide the full range of cloud services, what good is it ultimately? That is why integrating with the cloud SDK correctly requires users to have access to the full range of API functions and parameters through the orchestration template. In this talk we’ll describe the techniques we used to expose the full OpenStack SDK to Cloudify blueprints, some of the pitfalls encountered, and how we overcame them.


* **Ran Ziv** *(  Ran Ziv is the Cloudify Team Leader and a Senior Software Engineer at GigaSpaces. He has spoken at various conferences on development and cloud computing. Ran has extensive knowledge in developing and architecting large-scale open source cloud projects. On top of being an awesome guy, Ran is also a Python charmer and Ruby gem. )*

* **Yoram  Weinreb** *(Yoram Weinreb, member of the CTO office at GigaSpaces, is a distributed and cloud computing expert with over twenty years of experience programing, architecting managing and consulting to large scale distributed systems.)*

Deploying Internal Cloud Policies and Procedures
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In building an OpenStack team, policies and procedures are often implemented once the team has been built and deployed.  This session will give users tools to implement policies and procedures that can cover multiple teams and multiple cloud platforms.  Building a solid foundation for an OpenStack team sets them up for success from the beginning.


* **Megan Rossetti** *(Megan Rossetti is part of the OpenStack Operations team at Walmart, working to to set project priorities and meet ever-changing deadlines. She began her OpenStack journey in March of 2014, and is actively involved in several projects and working groups within the community. )*

Sharing resources with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We all know how virtualization solves the problem of unused server resources, but what happens when a your organization is made up of scientists, each of whom needs the resources of a computing behemoth to do his or her job? In this session, we'll look at how Naturalis uses OpenStack to enable administrators to easily share computing resources among scientists while avoiding both wasted resources and the hassles of buying and managing an inordinate number of powerful workstations. We'll also look at how we make use of features such as host aggregates, post-install scripts, and the OpenStack API to provide an environment where scientists can safely test and repeat their calculations.


* **Atze de Vries** *(I have a background in astrophysics and art. I've started operating Openstack 3 years ago. We then did our own deployment using Puppet. Our newer Openstack deployments are deployed with Fuel.  In my free time i like to do some alpine climbing and rock climbing. )*

Multi-location Cloud Health Tracking - Building an Operations Dashboard
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will cover a custom approach to tracking cloud health across many geo-locations. There are multiple OpenStack solutions for monitoring, but these tend to focus on single-location, with an opinionated approach to the data they collect and how they collect it. We have investigated various methods of extracting metrics from all the OpenStack IaaS and PaaS components, and built a custom dashboard to display this data from the 75+ OpenStack clouds deployed inside AT&T. The dashboard allows both users and operators to see the data they need, in order to maintain their applications and services across multiple locations.


* **Marshall Margenau** *(I am a cloud applications architect with over 11 years of software engineering experience.  I have an extensive background in deploying a wide range of full-stack and mobile applications in the cloud.  I evangelize software development topics like agile (as opposed to "Agile"), CI/CD, and DevOps.)*

* **Alexis Rivera De La Torre** *(Bachelor's Computer Science. Worked for a small startup (CrowdSource - now OneSpace) doing QA and Web Development. Started with AT&T in June 2015 and have been working both community work (mainly the Barbican and Horizon projects) and developing an internal cloud application to bring together monitoring, logging, metering, and other cross cloud metrics into a single dashboard.)*

* **Daniel Steven** *(Is currently a Professional Technical Architect at AT&T. Performs full stack developer responsibilites and has been working with Open Stack for about a year as of July, 2016.)*

No team? No problem! (How a single admin manages 70 OpenStack nodes)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One complaint we always hear about OpenStack is that managing an big environment takes a team of people, but we've found that it's simply not true. In this talk, you'll see how switching to OpenStack actually saved us time and money by replacing a few dozen workstations with just two OpenStack clusters that consist of 70 nodes -- all managed by a single admin. More than that, though, we'll talk about issues you're likely to face and how to solve them, as well as what we needed to do to make it possible for one person to manage all of these resources.


* **Atze de Vries** *(I have a background in astrophysics and art. I've started operating Openstack 3 years ago. We then did our own deployment using Puppet. Our newer Openstack deployments are deployed with Fuel.  In my free time i like to do some alpine climbing and rock climbing. )*

5 Years of OpenStack Managed Service at SAP SE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In 2011, B1 Systems began evaluating OpenStack vs. SAP's traditional script-based Xen hosting solution. The projectstarted off as a PoC based on OpenStack Bexar. In 2012, B1 built a fully-fledged OpenStack production environment with +200 hypervisors and 135TB of memory.For more than four years, B1 has been operating and providing support for SAP's OpenStack landscape.Since then, a total redesign of SAP's OpenStack landscape has taken place in order to benefit from OpenStack's fast development pace.The migration of two thousand VMs from Folsom to Icehouse was but one of the major milestones.This environment features OpenStack customizations, a workflow engine and an enduser frontend (B1 Cloud Portal) tailor-made for SAP, thus integrating the new environment with thousands of VMs seamlessly intothe existing SAP infrastructure.SAP and B1 Systems will share their OpenStack journey - includingtheir experiences regarding customizations, operation and upgrades.


* **Christian Wolter** *(Christian Wolter is a Service Manager and Project Lead of B1 Systems Managed Services at SAP SE.   He is responsible for the operation, development and support of multiple cloud environments running with OpenStack and XEN at SAP SE.  )*

* **Boris Wuest** *(Boris Wuest is Technology Consultantat at SAP SE.  In changing roles from technical consultant, cloud architect to IT service owner in the last 8 years he was responsible for development, implementation and operation of various virtualisation and cloud solutions within the SAP SE.)*

Cisco Intercloud migration from Ceph to Swift while in production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This is the story about how Cisco Intercloud migrated from Ceph Rados Gateway (RGW) to OpenStack Swift while in production and without service interruption. To prepare for the migration we collected vital data in the Cisco labs on storage requirements, throughput, latency, etc. A migration plan including all dependencies, such as RGW, Swift, networking, load balancing, SSL termination, Keystone endpoint switch-over and data migration was created. If any of these things weren't planned in detail, a seamless cut-over could not be guaranteed. The SwiftStack data migrator and cluster shunt middleware were key components to the migration. The migrator maintains thresholds to make sure the data movement won't hurt throughput in the Ceph cluster. The SwiftStack shunt middleware allows RGW and Swift to co-exist and ensures service during the cutover period. Throughout the migration, monitoring is watching the status of both Ceph and Swift, providing status reports of the migration progress.


* **Johnny Wang** *(Johnny is currently a Sr. Cloud Storage Engineer in Cisco Inter-Cloud and as the leader of Object Storage architects.  Prior to joining Cisco, he spent four years building a File Sync and Share system base on Object Storage in Hewlett Packard Enterprise after spending over nine years in a variety of design and development engineering and manager roles in Quanta Computer Inc. Johnny holds a BS and MS in Management Information System and is working as Ph.D candidate in Computer Engineering from Santa Clara University in California.)*

* **Martin Lanner** *(Martin Lanner is an Engagement Manager at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Martin has been working as an entrepreneur and specialized IT consultant involved in OpenStack projects. Martin is active in many large Swift deployments with SwiftStack customers worldwide.)*

How Four Superusers Measure the Business Value of their OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Businesses care about outcomes — not so much about the specifics of your technically-beautiful OpenStack cloud implementation. This mismatch of priorities often results in "orphan clouds" — clouds that have no tenants, and no buy-in from business leadership.. How to avoid this impasse? Simple: You need to make sure your cloud is delivering measurably beneficial outcomes. How? we've asked the experts: four OpenStack superusers (each with at least a year's successful experience running OpenStack at scales of 100 to 1,000 physical nodes); we've  extracted concrete business value metrics, and learned what practices made these users' OpenStack implementations wildly successful. You can benchmark your own cloud efforts against these metrics, use them to justify an OpenStack project internally to your CXO and demonstrate value to tenants to grow internal adoption. Our superusers will share lessons learned, so you can copy their best practices and avoid their mistakes.


* **Amar Kapadia** *(Amar Kapadia is senior director of product marketing at Mirantis, the pure-play OpenStack company. Amar is also an OpenStack blogger and published his first book on OpenStack Swift in 2013. Before Mirantis, Amar was at EVault, where he helped build EVault's public cloud storage, called Long-Term Storage Service (LTS2) using OpenStack Swift. He has also worked at Emulex, VLSI, and HP on data center infrastructure technologies. Amar has an  MS in EE from UC Berkeley. Amar has also spoken at conferences such as OpenStack summit and Clouded Leopards Den.)*

* **Kamesh Pemmaraju** *(Kamesh is the Vice President of Product Marketing at Mirantis where he works to define, drive, and deliver comprehensive joint go to market activities and content marketing of Mirantis products and Mirantis Unlocked partners in the OpenStack ecosystem   Kamesh has a deep knowledge of the cloud marketplace and the OpenStack ecosystem along with a rare mix of entrepreneurial/start-up experience, passionate customer focus, and strong technical expertise.  Kamesh held marketing, product management, engineering, consulting and executive roles with a number of key companies throughout his career. As a frequent speaker at OpenStack community and business events, and as an avid blogger focused on cloud, mobile, and big data, Kamesh draws on his strong knowledge of emerging technology markets, broad open source experience, and technical consulting background to ask the right questions and advocate tirelessly for innovation. Follow Kamesh on twitter @kpemmaraju)*

Object-Based Genomics: Building a Distributed, Fault-Tolerant NGS workflow with OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn how Counsyl revamped its NGS (Next Generation Sequencing) analysis pipeline from dependence on expensive, single point of failure centralized block storage to a highly scalable storage cloud that is resilient to failures and able to be run on commodity hardware. We will also discuss key optimizations for running genomics workflows to and from OpenStack Swift, current and future support for object workflows in tooling, and preview Counsyl’s soon-to-be open-sourced tool, stor, which allowed them to transparently rewrite posix-based python code to work with the native Swift and S3 APIs.


* **Jeffrey Tratner** *(Counsyl is a leading health technology company that offers DNA screening with a simple philosophy...focus on diseases where advanced knowledge makes a difference in health outcomes. They integrate sophisticated technology with custom automation in their CLIA-approved, CAP-accredited and NYS CLEP-certified medical laboratory. Jeffrey Tratner is a technical lead in Scientific Computing at Counsyl.)*

* **Martin Lanner** *(Martin Lanner is an Engagement Manager at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Martin has been working as an entrepreneur and specialized IT consultant involved in OpenStack projects. Martin is active in many large Swift deployments with SwiftStack customers worldwide.)*

Running OpenStack on Bare Meta Provider - Case Study - Packet.net
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Renting hardware instead of owning it is increasingly becoming popular -- and providers like Rackspace, Softlayer, OVH & Packet enable the building of Private Clouds with rented hardware.  Using a bare metal provider as the foundation of a private cloud can save you the hassle of owning hardware, allow for highly automated private cloud environments and strong operational models.  This talk consists of a case study of deploying OpenStack on Packet (www.packet.net) and dives into key deployment considerations and technical hurdles. You will learn about security issues, networking models in deploying OpenStack on a public bare metal provider and solution(s) Platform9 (www.platform9.com) employed to overcome some of these challenges.  Using public bare metal providers can be beneficial both in terms of cost and flexibility.


* **Roopak Parikh** *(Roopak Parikh is one of the Co-founder and CTO at Platform9 Systems Inc. Platform9 Systems is one of the OpenStack distribution and service providers. Prior to Platform9 Systems Roopak help technical leadership roles at VMware helping them build various management products including vCloud Director (VCD).)*

* **Zachary Smith** *(Zachary is an entrepreneur and proven manager with a focus on infrastructure services, including cloud platforms, hosting services, automation software and financial transaction clearing.   He has a successful history of managing high growth companies, from operations through finance/fund raising and product development.   Most recently, Zachary was an early member of the management team at Voxel, a NY-based cloud hosting company with a focus on infrastructure automation that sold to Internap (NASDAQ: INAP) in 2011 for 35MM. - See more at: https://www.packet.net/about/team/zachary-smith/#sthash.uIv9fVZt.dpuf)*

OpenStack and the US Army or: How I Learned to Stop Worrying and Love the Bureaucracy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When one thinks of business agility, maximizing productivity, and bleeding-edge technology, one generally doesn't think of the United States Army.  In fact, some people might imagine that an organization with 1.38 million employees would be the exact opposite of agile.  Some people might imagine a crushing bureaucracy that snuffs out innovation in favor of policy and procedure.  Some people might imagine a myriad of internal organizations whose sole purpose is to tell you why you can't do something.  Some people might even imagine that there would be exactly zero internal support for anything that deviates from "normal". These people would be absolutely correct. Yet, a fully functioning (and rapidly growing) OpenStack deployment is at the heart of the training program at the United States Army Cyber School.  Come learn how we navigated this project through one of the most innovation-unfriendly organizations on earth, how we use OpenStack, and where we plan to go from here.


* **Christopher Apsey** *(CPT Christopher Apsey is a 9-year Army veteran who has been involved with technology and computing profesionally for the past 11 years.  He is a Cyber Operations (Information Security) Officer in the United States Army, and has a Bachelor of Science Degree in Computer Science from the United States Military Academy. He has been an evangelist, architect, operator, and administrator of the OpenStack-based Virtual Training Area at the United States Army Cyber School since its inception.)*

* **Julianna Rodriguez** *(MAJ Julianna Rodriguez is the Director of the Cyber Technical College at the United States Army Cyber School. She has a Bachelor of Science in Electrical Engineering from the United States Military Academy and a Master of Science in Computer Engineering from Columbia University.)*

Swift Deployment Automation in Cisco Intercloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Cisco Intercloud Storage team has worked with SwiftStack to build Swift deployment automation using SwiftStack and a variety of open source tools. The automation includes hardware provisioning, deployment of Swift, integration with various systems like Keystone, monitoring, etc, as well as unit-tests at the end. The automated workflow leverages Ansible to wrap Kickstart and Python (SwiftStack python modules) scripts for deployment and configuration, creating a repeatable, auditable and consistent process. The deployment takes into consideration different hardware profiles and cluster designs and will dynamically adjust parameters for various environments. It can be run repeatedly and the same process is leveraged for upgrades. At the end, after a Swift cluster build or upgrade, unit-tests are run against the cluster to verify that the system is working. The entire process of deploying/upgrading can be monitored/reviewed through the build pipeline GUI and/or through system logs.


* **Johnny Wang** *(Johnny is currently a Sr. Cloud Storage Engineer in Cisco Inter-Cloud and as the leader of Object Storage architects.  Prior to joining Cisco, he spent four years building a File Sync and Share system base on Object Storage in Hewlett Packard Enterprise after spending over nine years in a variety of design and development engineering and manager roles in Quanta Computer Inc. Johnny holds a BS and MS in Management Information System and is working as Ph.D candidate in Computer Engineering from Santa Clara University in California.)*

OpenStack Practice in Express industry
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As Chinese logistics industry leader，innovation and diversity、openness and win-win is the core value concept of SF-express. Since 2011, SF cognizant of that cloud computing can help and accelerate achieve the value and definitely leading the direction.  So SF-express more and more focus on open source technology，and try to build the cloud computing platform. so OpenStack became SF preferred technology architecture .  By using OpenStack Cloud technology，SF improve IT service quality and infrastructure , and continuously achieving automatic operations. Currently, SF have realized the whole-process shipment circulation, information monitoring, tracking, inquiry and resource allocation to ensure stable improvement of service quality by using OpenStack.


* **Guopeng Liang** *(EasyStack Senior Technical Consultant，focus on logistics and industry)*

Legacy architectures to an automated, multi-tenant private cloud: EBSCO Case Study
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

I heard that implementing OpenStack is not for the faint of heart. As IT architect at EBSCO, I will draw upon our recent experience with implementing OpenStack at EBSCO to share best practices that I discovered along the way. You will learn both the technology and organizational barriers that need to be overcome to create a robust private cloud implementation with OpenStack.


* **Nate Baechtold** *(Nate Baechtold is an Infrastructure Architect at EBSCO.  He has been a professional software engineer for 7 years writing distributed applications for the enterprise and an architect for 3 years focused on infrastructure design, automation and cloud technologies. He is the primary architect and technical lead for EBSCO’s private cloud rollout to live customer facing environments and the implementation of a software defined load balancing strategy.  Nate has been also heavily involved in EBSCO’s overall cloud strategy.)*

Building large scale private clouds with OpenStack and Ceph
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Case study on how Walmart leverages OpenStack and Ceph to deliver private cloud at scale supporting both Walmart.com and our Retail technology needs


* **Andrew Mitry** *(I am the lead architect for Walmart's OpenStack effort to provide private cloud for the products and services Walmart offers to customers. I coordinate among the OpenStack community, our development, engineering and operations teams and our internal customers to offer best in class cloud services. I have encouraged Walmart's increased participation as an operator in the OpenStack community.)*

* **Anton Thaker** *(With over 19 years in the IT industry Anton Thaker has a wide range of experience in companies large and small. Anton is currently an OpenStack engineer at Walmart. He is focused on tackling the storage strategy for OpenStack at Walmart, spending most of his time working on Ceph.)*

Case Study: Enabling CI/CD for a Future of Connected Cars at one of the World’s Largest Automakers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the world’s largest automakers chose OpenStack to build their cloud in response to the industry shift to a service economy. As part of this project, they needed to stand up a mix of business and consumer-facing applications, that would be used by supplier and dealer networks as well as related brands under their umbrella. They built their cloud platform to deliver digital transformation and enable CI/CD to build a future with connected cars.


* **Adrian Steer** *(Adrian has been working in some form of IT role for his entire career, primarily in the areas of networking and infrastructure, security and software development. Adrian is based in Europe and works at Mirantis as a Solutions Engineer where he helps people and organisations design and implement private clouds based on Openstack.)*

* **Praveen Yalagandula** *(Praveen Yalagandula is the OpenStack Architect at Avi Networks, responsible for designing and developing the integration of Avi Networks’ Avi Vantage Platform with OpenStack infrastructure services. At Avi, Praveen also leads the application performance visibility component of Avi’s solution and has developed a scalable and distributed log analytics system. Prior to Avi, Praveen was a Principal Scientist at HP Labs in Palo Alto, where he spent 8 years exploring several aspects of data center networks, software defined networking, and large-scale distributed systems. Praveen received his Ph.D. in Computer Science from the University of Texas at Austin in 2005. He is currently a senior member of IEEE and ACM.)*

How to embrace hybrid cloud without giving up OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For enterprises running OpenStack based private cloud, adding public cloud resources is an attractive proposition. A hybrid cloud offers pay-as-you-go flexibility of a public cloud combined with security and privacy of a private cloud. However, the complexity poses a barrier to its adoption. In this talk, we show how to use the OpenStack API layer as the unifying interface for hybrid-cloud management. We found that this approach solves a number of use cases for managing workloads on public cloud like AWS. It enables uniform experience, simplicity and portability for cloud tooling and applications. We have extended the OpenStack control pane by building AWS-specific drivers for Nova, Glance, Cinder and Neutron. We added Platform9’s brownfield discovery technology to further ease the ingestion of AWS workloads into an OpenStack-driven cloud. This approach can easily be extended to other clouds as well, making the holy grail of multi-cloud a reality.


* **Sachin Manpathak** *(I lead core openstack projects at Platform9 such as Nova, Cinder and Keystone. In the past, I was an engineer in  VMware Resource Management group responsible for Storage DRS and Storage IO Control. I am passonate about Cloud, Resource Management, Storage and Containers.)*

* **Pushkar Acharya** *(Pushkar Acharya is an early engineer with Platform9 Systems Inc., working on vSphere integration with Platform9 primarily in the nova, cinder and glance. Recently also started working on integrating VMware NSX plugin in neutron with Platform9 OpenStack.)*

* **Pooja Ghumre** *(I work as a backend developer at Platform9 Systems Inc. on the openstack compute project Nova and recently started working on the Keystone project as well. My areas of interest include virtualization and cloud technologies. Prior to joining Platform9, I was working at VMware Inc. on the hybrid cloud project.)*

A DevOps State of Mind with Docker, Kubernetes, and OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Rapid innovation, changing business landscapes, and new IT demands force businesses to make changes quickly.  In the eyes of many, containers are at the brink of becoming a pervasive technology in Enterprise IT to accelerate application delivery.  In this presentation, you'll learn about the              • The transformation of IT to a DevOps, Microservices, and Container on OpenStack based Architecture            • What are containers and how DevOps practices can operate in a container based environment            • A demonstration of how Docker and Kubernetes can reduce software delivery cycle times, drive automation, and increase efficiency of applications on an OpenStack environment            • How other organizations are using DevOps + Microservices + Containers on OpenStack and how to replicate their success    Join Chris Van Tuin, Chief Technologist, West at Red Hat, as he walks through how DevOps with Docker and Kubernetes can accelerate application delivery for the Business.


* **Chris Van Tuin** *(Chris Van Tuin, Chief Technologist for the Western US at Red Hat, has over 20 years of experience in IT and Software.   Since joining Red Hat in 2005, Chris has been architecting solutions for strategic customers and partners with a focus on emerging technologies including IaaS, PaaS, and DevOps.  He started his career at Intel in IT and Managed Hosting followed by leadership roles in services and sales engineering at Loudcloud and Linux startups.  Chris holds a Bachelors of Electrical Engineering from Georgia Institute of Technology and found his passion in technology as a C and Smalltalk developer.  Chris presented at OpenStack Vancouver.         )*

Experiencing World's Biggest Openstack Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AT&T is engaged in a poineer work for deploying world's biggest openstack deployment with AIC (AT&T Integrated Cloud) project. I am Vice President, Program Management from Ericsson managing this program with an executive panel : Executive Director Incharge of IT/Cloud - Ryan Van Vik, Director Business Stretegy - James Smith & Director Development - Andrew Leasick discussing inspirational,knowledagble and interesting aspects of the program. This panel discussion should bring out technical, business & operational experience which can inspire & serve millions of people aspiring to know in- depth practical usage, benefits & case study on this perfect openstack project.


* **Ryan van Wyk** *(Leading a scaled agile development organization of 500+ software engineers and architects, leveraging open source technologies at massive scale, following DevOps principles and delivering via CI/CD. Responsible for executing the following strategic objectives for AT&T;AT&T Integrated Cloud (AIC): one of the worlds largest OpenStack based private clouds, deployed at scale, both domestically and internationally. AIC is enabling SDN network services like Network on Demand and the virtualizing network functions that run our mobile network. AT&T Netbond: software-defined networking (SDN) capabilities and proprietary technology that enable AT&T customers to connect, or “bond,” their virtual private network (VPN) to a cloud provider of their choice.)*

* **Jacob Smith** *(Jacob Smith is a Director - Technology leading a scaled agile development organization of cloud software engineers and architects, leveraging open source technologies including OpenStack, following DevOps principles and delivering via CI/CD. Previous to this, Jacob lead technology application development and deployment teams in both AT&T U-Verse Provisioning applications as well as AT&T Mobility Apps for iOS. Jacob is currently responsible for delivering strategic Cloud offerings and managing deployment acceleration across AT&T’s cloud.)*

* **Andrew Leasck** *(Andrew Leasck is a Director at AT&T responsible for OpenStack development, automation, and community participation. In 2015 his teams delivered cloud automation tooling, known as OpsSimple, that deployed 74 OpenStack clouds globally. Currently he is focused on creating a community engineering program at AT&T staffed for the sole purpose to help advance the OpenStack platform. Previously he co-authored an Interface normalization patent and more recently received an ITO award for driving AT&T’s Agile transformation, adopting Scrum and XP fundamentals. He attended University of Missioiuri graduating from the School of Engineering with a degree in Computer Science.)*

* **Sunil Sood** *(with a 20+ years of IT experience, I have been wowed with openstack's journey and feel pride in managing AT&T AIC as a pioneer openstack project of its kind mapping AT&Ts worldwide infra with many clouds into one integrated cloud. Enabling latest infra technologies in the world with all availaible VNFs & contributions from open community with cultural diversities all coming together to produce something amazing!)*

Case Study: Cisco InterCloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cisco deploys OpenStack for its Cisco InterCloud (CIS) and has been successful in terms of platform stability, uptime and meeting variable application performance needs. In this session, presented by Cisco’s Yuming Ma and Shyam Bollu and NetApp SolidFire's Alex Sorokunov, learn about Cisco’s OpenStack strategy, use cases, architectural choices – including its Provisioned IOPS Block Storage (PIB) offering backed by NetApp SolidFire storage – results, and future plans for CIS. Cisco (NASDAQ: CSCO) is the worldwide technology leader that has been making the Internet work since 1984. Our people, products and partners help society securely connect and seize tomorrow's digital opportunity today. 


* **Yuming Ma** *(Yuming Ma is an architect in Cisco Cloud Services group where he is responsible for the overall solution and technology direction of its cloud storage platform. He is a veteran engineering in the distributed computing, clustering and storage systems and particilating developing, designing and architecture of multiple projects in such areas. Before joining Cisco Cloud Services, Yuming help engineer leader role in Symantec and Alcatel Lucent. )*

* **Shyam Bollu** *(Currently working as storage architect in Cisco Cloud services.)*

* **Alex Sorokunov** *(Alex Sorokunov is a Sr. Systems Engineer at NetApp SolidFire.)*

One cloud. Openstack.  Kubernetes. One hour. A managed OpenStack success story.”
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is hard.  At least it has been for some time.  It requires resources to manage and expert knowledge on-site, and downtime remains a nagging fear. With the proliferation of containers, cloud teams now have to manage two systems, with 4X (2^2) the worry. Indeed, the “OpenStack or containers?” question consumes further resources in unproductive debate. No longer.  Dell, Platform9 and Midokura have teamed to delivered a solution that is easy to deploy, leverages SDN, minimizes resource overhead, reduces TCO, and best of all: unifies OpenStack and Kubernetes workload management within a single interface


* **Michael  Ford** *(Mike manages technical services for Midokura, with technical responsibilities across the sales and support cycle. His depth of experience spans OpenStack, NFV, networking security, and wireless, on a variety of hardware and software platforms.)*

* **Charles Conte** *(Charles runs the open networking group inside Dell, with emphasis on providing unified solutions around Dell OS10, OpenStack and Containers.)*

* **Paavan Shanbhag** *(Paavan works as a software engineer building some of the key cloud services at Platform9 Systems, Inc. Prior to Platform9, he spent close to 6 years working at VMware, where he has contributed to various cloud management products working across the VMware stack, mainly on ESXi and VirtualCenter platforms. )*

HPC on OpenStack - real world deployments and use cases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the first portion of this session we will examine three real world implementations of HPC workloads deployed on OpenStack.  We will take a close look at each environment and discuss both the technical and business drivers behind selecting OpenStack as well as the specifics of the workload types – grid analytics, genomics and computational chemistry.   In the second portion of this session we will cover the specific technology of each of these three deployments including technical architecture, sizing, scale, underlying systems, project selection and other design, configuration and deployment aspects.   Throughout the session we will tie these use cases and technology back to a growing industry trend of “Mode 2 HPC” and what that means for HPC practitioners and organizations that want to leverage OpenStack as HPC continues to adopt private cloud technologies.


* **Jason Grimm** *(I am a husband, father and maker of things. I have lived most of my life in downtown Atlanta, but I now reside on an 11-acre sustainable family farm 1 hour north of the city. My background includes 25 years of IT experience, several certifications, various IT scar tissue and 2 technical degrees.  I am currently a Cloud Solutions Architect at Cisco and am pursuing my MIS degree at Georgia Tech. I have been working with OpenStack since the Essex release, have attended or spoken at the last 8 OpenStack summits. I am a veteran technologist with experience ranging from Naval Intelligence, freelance consulting, start-up co-founder, and a decade of professional services with Dell. My focus has been on cloud technology for the last 5 years beginning with Crowbar at Dell in 2011, Fuel at Mirantis, RPC at Rackspace and now Metacloud at Cisco. I am competent with Ruby, Python, Perl, BASH, and Java, but my greatest strengths are as a cross-discipline infrastructure architect designing and deploying complex OpenStack-based solutions and supporting sales, product and operations teams. Jason Grimm http://www.brothergrimm.com)*

* **Steven Carter** *(Steven Carter is an Architect for Cisco Systems with over 15 years of industry experience working in large universities, government research and development, and the private sector.  He has spent time as a system administrator running some of the largest supercomputers in the world, built out one of the World's first SDN networks for the Department of Energy, and developed code for both network devices and supercomputers in the process.  Steven has a wide range of experience in embedded software development, large system design and build-out, and operations.  He currently works on building solutions for technical- and data-intensive cloud computing based on OpenStack and other software-defined technologies.)*

* **Josh Lothian** *(Josh Lothian is an engineer at Cisco Systems.  He has over 15 years experience working in academic and high performance computing research facilities as a system administrator and developer.  He has supported the fastest HPC systems in the world, and is now leveraging that experience in an OpenStack devops role.)*

Customer Case Study: How TechAccelerator used OpenStack as a better alternative to vCloud Director
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With vCloud Director approaching the end of its life, enterprises are increasingly looking at alternatives to satisfy their cloud goals atop existing VMware infrastructure investments. One such company is TechAccelerator - a solutions provider that empowers enterprises with an easy-to-use, on-demand, hands-on platform to speed up product adoption and solution integration. Given the rate at which these lab environments need to be dynamically spun up and destroyed, it is also important to be able to deploy them with a single-click, and clean them up.    


* **David Hekimian** *(David Hekimian founded TechAccelerator in 2012. Prior to TechAccelerator, he was  the CTO of Trace3, a regional solution provider and Value-Added reseller. David was responsible for developing product vision, marketing strategies, and scalable business models to increase revenue for his customers. As a recognized expert within the Storage, Networking, Virtualization, and Security space, David has been the Keynote Speaker at a number of prominent conferences like SNIA, VMworld, and VMware vSphere road shows. David has served as a member of the VMware Partner Technology Advisory Board, NetApp Partner Technology Advisory Council, and Riverbed Partner Advisory Council. He is also a VMware Certified Professional (VCP, VSP and VTSP) and Riverbed Certified Solutions Associate (RCSA).)*

* **Cody Hill** *(Prior to joining Platform9, Cody was the Lead Cloud Architect at General Electric, where he built an enormous private cloud based on VMware vCloud Director spanning North America, Europe, and Asia. With more than 10 years of IT infrastructure experience across multiple industries, he brings a wealth of knowledge and expertise, particularly as an enterprise IT practitioner and strategist in one of the world’s largest technology shops.cod)*

* **Pushkar Acharya** *(Pushkar Acharya is an early engineer with Platform9 Systems Inc., working on vSphere integration with Platform9 primarily in the nova, cinder and glance. Recently also started working on integrating VMware NSX plugin in neutron with Platform9 OpenStack.)*

How to product manage IoT/IIoT OpenStack Deployment?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How to Manage IoT and IIoT devices using OpenStack?  There are no standard software to manager IoT (Internet of Things) and IIoT (Industrial Internet of Things) devices.  OpenStack is the startling possibility.  However, OpenStack is not built ground up to manage IoT and IIoT.  What are business and technical considerations in managin IoT/IIoT devices?  This presentation provides the outcome of a case study of an Industrial IoT device i.e. water monitoring device for Energy Utilities.


* **Ravi Jagannathan** *(Ravi Jagannathan has 25 years of Computer industry experience. As a MS Cybersecurity graduate of NSA program, currently he is focusing on developing and deploying high performance, secure cloud.   Ravi is a hands on coder and is a project-lead.  His interests are Cryptography, Virtualiation, Cloud, Cloud-security, Secure Boot, protecting assets in private/public/hybrid cloud. He works extensively with developers, customers, partners, and VCs providing mentorship and leadership as a project lead, hands on technical manager, and second-level manager.  He continues to code in various languages. He has worked across various organizations in proposing and successfully defining and delivering products.)*

Why We Chose OpenStack As our Hybrid Cloud Management Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AVG Technologies is a leader in internet security software, providing security software that protects devices for families and businesses worldwide. As part of supporting a high velocity software development model, the AVG team needed to leverage internal infrastructure and public cloud while accelerating CI/CD and automation using a common API. It was clear to them that OpenStack could fully manage their private infrastructure across VMware and KVM, and integrating with Cisco ACI. But what about the need for a single platform across public and private clouds? Other hybrid CMPs were an option but they have a lot of overlap in functionality with OpenStack and the AVG team prefers using OpenStack API due to compatibility with devops tools they use. So they asked themselves: why not consolidate using OpenStack? This talk will highlight how AVG was able to collaborate within the community to build AWS-specific drivers for OpenStack to deliver a fully hybrid implementation at AVG.        


* **Madhura Maskasky** *(Madhura maskasky leads Product Management at Platform9. Before co-founding Platform9, Madhura spent 7 years at VMware Engineering, where she grew to be technical lead for several key products including vCloud Director, Update Manager and ConfigControl. Madhura helped spearhead vSphere's transformation into a policy driven product suite, working broadly across groups to pull together the vision. Madhura holds a M.S. in Computer Science from Stanford University, specializing in databases and distributed systems. When she isn't sweating the details on product, Madhura can be found rock-climbing, swing dancing and exploring San Francisco.)*

* **Blake Parker** *(Blake heads the devops team at AVG that powers the internal private and hybrid infrastructure and enables high velocity software development model at scale for the organization. )*

* **Mike Cohen** *(Mike Cohen is Director of Product Management at Cisco Systems.  Mike began his career as an early engineer on VMware's hypervisor team and subsequently worked in infrastructure product management on Google and Big Switch Networks.  Mike holds a BSE in Electrical Engineering from Princeton University and an MBA from Harvard Business School.)*

Towards to an Intelligent Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Intelligent cloud without human intervention is the ultimate goal of openstack. This presentation shares our story of how to achieve it. We are maintaining a cloud for developer usage for totally different purpose: * build server for CPU intensive workload, like andorid build. * openstack development like devstack environment setup, requires huge network bandwidth The trend of workload and users is not predictable, so need add new servers in peak time and remove them when idle. Furthermore, long time heavy work load usually makes server broken, so that we need identify then remove them in the 1st time. We try to use automation, but some steps still requires human intervention. Then we found Watcher, resource optimization in openstack, and defined our own strategies for workload balance & server consolication. Also developed some algorithm based on power/temperature metrics for intelligent management. Finally, our smart cloud runs well without any human intervention.


* **Gang Zhai** *(Gang joined Intel in 2003 as kernel engineer for driver development. From 2005, Gang switched to open source virtualization, like xen/kvm, with interests in VT enabling, live migration, GPU virtualization. In 2014, joined openstack community and mainly focused on telemetry work.  )*

* **Susanne Balle** *(Susanne is a senior Principal Engineer at Intel working on SDI and Cloud architecture and pathfinding. She has been involved in OpenStack since the Essex OpenStack summit. Her latest focus is on Watcher a service to optimize the Datacenter TCO via Data-analytics and ML models for OpenStack and non-OpenStack Clouds.)*

Case Study: Building a fully automated developer workflow using OpenStack on VMware
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Alert Logic is a leader in security and compliance solutions for the cloud, providing Security-as-a-Service for on-premises, cloud, and hybrid infrastructures powering enterprises worldwide. The IT team inside Alert Logic standardized on VMware as their private infrastructure of choice for it’s stability and performance. However, they had to build a significant amount of automation inhouse (a ruby on rails application) to automate deployment of workloads on a variety of platforms – Vmware, AWS, LXC etc. all their deployment tools interacted directly with VMware vCenter. And the automation still did not fix the need for end-users to have direct access to vCenter for console and other use cases. This conflicted with Alert Logic’s policy of doing everything as-a-service and enabling self-serve model for users. This talk describes Alert Logic’s use case of building a powerful automation using OpenStack with VMware, and ruby on rails with chef to automate their developer workflows.


* **Madhura Maskasky** *(Madhura maskasky leads Product Management at Platform9. Before co-founding Platform9, Madhura spent 7 years at VMware Engineering, where she grew to be technical lead for several key products including vCloud Director, Update Manager and ConfigControl. Madhura helped spearhead vSphere's transformation into a policy driven product suite, working broadly across groups to pull together the vision. Madhura holds a M.S. in Computer Science from Stanford University, specializing in databases and distributed systems. When she isn't sweating the details on product, Madhura can be found rock-climbing, swing dancing and exploring San Francisco.)*

* **Michael Wiggin** *(Michael Wiggin leads the infrastructure automation team at Alert Logic that enables developer productivity and powers their private and hybrid cloud infrastructure. )*

* **James  Poore** *(James is a lead automation engineer in the infrastucture automation team at Alert Logic. The team enables developer productivity by managing their private and hybrid infrastructure and providing self-service and automation tools for the end users. )*

SpringCM's experience delivering document management on Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

SpringCM is a cloud platform that manages documents, contracts and all related collateral. Delivering this SaaS application to users puts great demands on infrastructure, on top of the architectural demands to deliver a great user experience at the right cost for our business. We saw Swift as a great infrastructure fit when building our offering.


* **Antonis Papatsaras** *(Antonis Papatsaras, PhD, CTO, SpringCM Dr. Antonis Papatsaras takes tech to new levels at SpringCM. He can translate his 15 years experience in massive cloud infrastructure, highly available and scalable architectures, and very high volume ingestion knowledge into strategies and projects that put the SpringCM cloud platform in a class by itself. Before he joined SpringCM, Antonis was Director of Software Engineering of Autonomy where he led the re-architecture of numerous products to true SaaS multi-channel, multi-tenant solutions. Antonis was also Director of Software Engineering at Interwoven, and Vice President of Software Engineering at Discovery Mining, a SaaS eDiscovery company. Antonis received his PhD in Formal Specification and Design of Safety Critical/Distributed Systems from Teesside University, UK. In 2003, he was elected a member of the Institute of Learning and Teaching in Higher Education (ILTHE) and in 2007 he achieved the status of Fellow of the Higher Education Academy.)*

How Rockstar games rocks storage with Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

millions of concurrent game users place huge demands on storage


* **Mario Blandini** *(Mario is VP of Marketing at SwiftStack, Inc. Passionate about disruption, Mario has previously lead marketing teams for Storage technology companies including Brocade, Drobo, and HGST. Hand-on backround deploying infrastructure in technical roles at Rhapsody Networks (now Brocade), Sanrise (now EMC), Adaptec, and the United States Marine Corps.)*

Networking Down Under: Proving OpenStack across a large-scale academic research network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NeCTAR is an Australian Government project conducted as part of the Super Science initiative, and led by the University of Melbourne. NeCTAR was an early adopter of OpenStack Essex, using nova-networking. They knew that migration from nova-networking to Neutron would be challenging. NeCTAR knew they wanted an open-source Neutron plugin from a vendor with excellent community credibility. Running OpenStack at scale with over 7000 instances, 1000 hosts, across 10 datacenters, NeCTAR needed a solution that was easy to install and provided both basic networking features and advanced services that can handle such scale. They chose MidoNet.  


* **Ryu Ishimoto** *(Ryu Ishimoto is the technical lead of Midokura Japan, currently leading the effort to integrate MidoNet and OpenStack Neutron.  He is also responsible for designing and implementing the MidoNet API as well as some parts of the MidoNet cluster and agent.  He is a Neutron contributor.   Prior to joining Midokura, he spent 10 years as a developer for various technologies including data mining, ad server, financial systems, and e-commerce applications.  In 2004, he received a Master's Degree in Computer Science from UCLA.)*

* **Sam Morrison** *(Sam Morrison is the Technical lead for the NeCTAR Research Cloud, which spans 9 different datacentres across Australia. In this role he is responsible for coordinating the technical team's activities in each location, in addition to OpenStack customisation work. As happy managing government funding milestone expectations as diving into python code, Sam is a contributor to nova, horizon, cinder, keystone, glance, ceilometer and trove. His latest hobby is migrating nova-network clouds to neutron.)*
