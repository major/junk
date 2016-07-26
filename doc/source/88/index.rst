Developer Tools
===============

Continuous Delivery at Scale: Scaling Jenkins with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will cover how we run Jenkins at scale on top of OpenStack, and how the product is continuously built, tested and deployed using OpenStack. The Jenkins platform can be dynamically scaled to run jobs across hundreds of Jenkins masters, on Docker containers distributed across the OpenStack cluster or full virtual machines. Jenkins build agents are dynamically created based on load, isolating job execution and allowing a better allocation of resources. This presentation will show the challenges of continuous delivering distributed applications built on OpenStack, particularly JVM ones, by sharing a real world use case.


* **Carlos Sanchez** *(Carlos Sanchez specializes in software automation, from build tools to Continuous Delivery, integrating technologies at multiple levels: Docker, micro services, Infrastructure-As-Code and even IoT.He has spoken at several conferences around the world, including ApacheCON, JavaOne, Fosdem,... Involved in Open Source for more than ten years, he is a member of the ASF amongst other open source groups, contributing to several projects, such as Jenkins, Apache Maven, or Puppet. He works at CloudBees scaling the Jenkins platform.)*

User Messages - Async Error Reporting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For quite some time, OpenStack services have wanted to be able to send messages to API end users. In Newton, both the Cinder and Manila projects have implemented the concept of User Messages as a way to inform users of the status of asynchronous operations. This presentation will demonstrate the use of this feature via the Horizon UI, project CLIs, and the API.


* **Alex Meade** *(Alex has been developing across various projects in OpenStack since the Cactus release in 2011. Alex has a wide breadth of OpenStack experience having been a top commiter in Nova, a core member of Glance, and key operator of the Rackspace Public Cloud. Currently, he focuses on solidifying Cinder and Manila as enterprise ready projects.)*

AIOrchestra. AsyncIO-based open source TOSCA orchestration framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OASIS TOSCA gains more and more involvement into cloud orchestration no matter what it is. OpenStack is not an exception: Murano accepts TOSCA through its plugins Tacker uses to describe NFV deployment topology Heat-translator (TOSCA to HOT) toscaparses library lived under OpenStack "Big Tent" So, as it can be seen, TOSCA is more than just yet another way to describe deployments, it is future for orchestration itself. But TOSCA is just a DSL to describe topology. AIOrchestra is an engine to process TOSCA DSL to real deployment process. By use of modern python 3.5 technologies like coroutines with async/await syntax AIOrchestra allows DevOps/Developers to write TOSCA templates to describe how they want to see their apps in clouds and the way how it would get into cloud. AIOrchestra is not a just a product driven by specific organisation, it is the way to reconsider the way we develop and deploy. The idea that stands behind it - open platform, open capabilities, open TOSCA.    


* **Denys Makogon** *(Developer and starting software architect in cloud environments, founder of Project Invader open source organization, mainly focused on developing and designing platform and software as a service applications for OpenStack. He’s lead software developer in EPAM, concentrating on product development along with bringing well-designed and production ready integration with clouds environments, including vCloud Air and vSphere for Cloudify. He is a contributor to AIOrchestra, Aria TOSCA, toscaparser.)*

Pratai, Event-Driven Compute for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In a cloud computing era, change is the norm. And whether you are a developer, an administrator or the owner of the cloud you want to provide the right tools to help your customers migrate to the cloud more easily and quickly. Pratai provides an incredible flexibility on how to migrate workloads to the cloud that respond to events without having to manage any server or network, this allows your systems to be more flexible, loosely-coupled, scalable and easier to develop while offering a more tolerant to failure environments. Pratai offers an event driven platform that works with OpenStack to provide server-less applications and services, No infrastructure management, no VM spawning, no network provisioning, just run your code in OpenStack. Let’s discuss the infrastructure to provide an event driven platform for OpenStack  


* **Guillermo Ramirez Garcia** *(Mexican software and systems engineer at HPE, I'm currently living in Galway Ireland where I'm working with the Profressional Services team, my main role is to develop Freezer, a backup and restore tool for OpenStack and Pratai an event driven compute platform for OpenStack)*

¿Por qué no los dos? Container and VM Images with Packer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Packer is a tool from Hashicorp that automates the creation of machine images and containers. In this session, you’ll learn what Packer is and an overview of what it does, key terminology, and how to use Packer to build a container image for your developers to use, while using the same tool to build virtual machine images for production deployments in an OpenStack cloud.


* **Hart Hoover** *(Hart Hoover is an OpenStack User Advocate at Cisco. Hoover started his career at Rackspace in 2007 as a Linux Systems Administrator, moving to the cloud to help create their Managed Cloud offering in 2009. He has been an advocate for the open source community, contributing to multiple open source projects. He is also the founder of the San Antonio DevOps meetup and loves tacos and coffee. You can follow him on Twitter at @hhoover.)*

* **Jason Smith** *(Linux Engineer, turned Architect. I Design, Build, and Automate stuff. )*

The Shell in the Cloud
~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Iridium is a test shell, which will help manage the one component most testing and development organizations have been needing: a low-level automated exploratory test shell for engineers to perform micro-bench test for ad-hoc testing and reproduction of existing defects. This focus differentiates Iridium from Tempest and Rally, as those two frameworks / testbeds are aimed at testing a completed solution. This is better known as an end-to-end scenarios test, which is also known as black box testing. This approach is needed to insure that the customer experience is free of external API service fouls, but it does not address issues where code path may not be executed due to varying configurations or the fact that most commands are canned or preformatted. The ability to perform white box testing in a controlled shell will allow quality engineers to have a closer working relationship and will enable the faster production of quality software.


* **Toure Dunnon** *(With more than a decade involved in the open source community, Toure has had the pleasure of being exposed to various technologies which have shaped the current state of the community. These roles involved a start as a linux systems administrator which launch the initial interest into engineering that lead to getting involved from an early start in his career as a test engineer for various large corporations. Once he gained enough experience he persued a career at Red Hat where he worked his way up the engineering ranks to get involved with Linux internals from a maintaince engineering standpoint and later moving back into his first love of testing (breaking products). Now Toure spends his time writing software to shake bugs out of the cloud.)*

* **Dustin Schoenbrun** *(Dustin Schoenbrun is an OpenStack Quality Engineer at Red Hat and focuses on Manila. He has spent the last ten years working in several aspects of the technology industry including writing test plans for FCoE, contributing to reference architectures, developing software plugins, QA'ing software, to now working on OpenStack. When he's not working on OpenStack, Dustin is an avid musician who plays bass guitar and electric guitar.)*

Technical primer to Atomic and ostree; creating custom Host images
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This is not a talk about atoms and trees, but about a new way to deploy Operating Systems. It might still change the way you think about nat^H^H^Htrees. Think of something between image-based and package-based deployments. Ostree delivers a tree management and delivery in which system updates can be performed atomically. This has profound impact on how we can think of running instances in the cloud and even as the host for the OpenStack environment itself. In this presentation I will detail the history of the ostree project and how this lead to Project Atomic. I will show how a customized version can be delivered, and how this can be used as a base for either your instances in the cloud. As part of the research, I will also detail how this might affect the delivery of an OpenStack environment based on an atomic host.


* **Gerard Braad** *(Gerard is primarily responsible for the Open Source strategy and has been key in setting up the course and training program for OpenStack and Linux at UnitedStack. As an engineer, he is considered to be a full-stack engineer by his peers, although he will never introduce himself as such. He has done development in a wide variety of languages to implement Domain Driven Design and microservices. Due to his background in IT management, he has a good grasp of infrastructure, deployment, and the needs of the actual users. As part of his involvement in Open Source communities, particularly in APAC and China he has a good understanding how communities work. He has been on the Fedora Ambassador Steering Committee for two successive years representing APAC. Currently, he consults companies and projects about community engagement and participation. Has presentation and teaching experience is more than comfortable in front of large audiences, from beginners to advanced level.      )*

The benefits of E2E Integration Between Open Source Communities Using 3rd Party CI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OPNFV is in the process of setting up 3rd party CI to synchronize the development process between the two communities. This will allow us to faster work on common requirements and patches. OPNFV developers will be able to submit patches to OpenStack and test them in OPNFV environment. OpenStack developers will benefit from the early testing of their patches together with other OPNFV components using OPNFV test frameworks and CI pipeline running against distributed bare metal labs We share experience from setting up the 3rd party CI, explain how the CI systems are connected and discuss benefits for developers and users from both communities We explain the difference between OPNFV’s 3rd party CI and typical company 3rd party CI. In OPNFV we do two different things: Besides Helping OPNFV projects to access OpenStack patches using the combined CI pipeline we also establish a service to OpenStack by reusing OpenStack Infra utilities to create OPNFV scenarios like HA and bare metal testing


* **Ulrich Kleber** *(Ulrich Kleber is a Chief Architect Cloud Platform in Huawei’s European Research Center. During his 30 years of work experience he gained extensive experience as system architect in all areas of telecommunication systems developing technology and architecture strategies according to customer requirements and business goals.He has a track record in open standards and open source development, including own code contributions. He contributed to ETSI ISG NFV to working groups and ISG level documents from its beginning. With the founding of OPNFV he started representing Huawei in the technical steering committee and started one of the first projects in the new organization.He also represents Huawei in the Scope Alliance as a board member and was chairman of the board in 2013. Before joining Huawei, he represented Siemens and NSN in the Service Availability Forum as chair of the technical working group and OpenSAF as a TSC member.)*

* **Fatih Degirmenci** *(Fatih is Principal Software Developer working at Ericsson. He is specialized in CI/CD, Software Development Infrastructure, and automation. He has more than 10 years experience and involved in several large scale CI/infrastructure projects during his career. He is Project Technical Lead for the OPNFV Release Engineering Project and core committer for several other OPNFV projects. Before Ericsson, Fatih worked for Havelsan and provided expertise to Havelsan's customers such as BOEING and BAE Systems.)*

Automating your manual test suite using a Tempest plugin, Scenario tests and Rally
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Testing an OpenStack deployment by running 100s of detailed manual test scripts is a very time consuming effort.  Luckily, the Tempest test framework has a plugin interface and scenario test framework that can be leveraged for automating detailed test scenarios. In addition to standard scenario test, that drive the OpenStack REST APIs, it is also possible to create scenario tests utilizing the WebDriver API for simulating browser interaction with Horizon, for full end-to-end UI test scenarios. Furthermore, a Tempest plugin can be installed into a Rally deployment, so you can leverage the power of Rally for persisting your test runs , as well as create reports and compare test runs etc. This presentation will outline and demonstrate the entire process for automating a single detailed test scenario.


* **David Paterson** *(Senior software engineer with over 15 years of experience designing and building software. I am working with the Dell Cloud Solutions team where I originally worked on building the OpenStack deployment tool Crowbar. Currently, I am working with Dell partners delivering OpenStack solutions and I am an active upstream contributor to the OpenStack QA and Rally projects.)*

* **Gael Rehault** *(Passionate about all things automation, coming with experience in software going from working with ISP to l18n, online gaming to public cloud platforms; architecting & engineering tooling solutions to drive automation into everything.)*

In Search of Immortality: Mastering the OpenStack Tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Work Smarter, not Harder. We've heard this, but often don't have time to take a step back and figure out how to do it. This talk will explain many of the Developer tools that OpenStack has to offer, both within the OpenStack Infrastructure and using other Open Source technologies. We'll demo some tools, provide some tips, and share some community secrets with the goal of learning how to get more work done and tame complexity.OpenStack Developers and Operators might use tools like Git, Gerrit, and Tempest every day without maximizing the productivity from these technologies. Many engineers get into workflow habits and don't have time to re-tool or delve deeper. But there are always new features to explore and new ideas to implement in order to get more out of our precious time. Join Scott and Andrea as they explore and explain some of the ways to be more efficient in the OpenStack Developement environment.


* **Scott DAngelo** *(Scott DAngelo is a Senior Software engineer at Hewlett-Packard Enterprise who works as a developer on Helion OpenStack Cinder. He is a member of the Cinder core team and works on the core Cinder code, Cinder testing, and Cinder-Nova API interactions. He has been with HP since 2007 and has worked on OpenStack since 2012.)*

* **Andrea Rosa** *(Andrea Rosa is a software engineer working at Hewlett Packard in Bristol U.K. where he is part of the Nova team.Andrea has been involved in the adoption of OpenStack for HP public cloud more than 4 years ago (Diablo release) then his focus moved to HP OpenStack Helion project.Andrea at the moment is intrested in understanding if it is possible to improve the integration between nova and cinder.Andrea passes his spare time with family and always is learning something new.)*

Fresh, free hardware for testing: How we used OSIC to test OpenStack on  66 nodes for no charge.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A session on OpenStack provisioning and deployment starting from scratch across 66 nodes. This presentation will walk through the experience of using a 66 node bare-metal cluster from the OSIC (OpenStack Innovation Center) cloud through the lens of two developers. It will cover the initial request for experimental nodes from OSIC, the provisioning of these nodes, the deployment of OpenStack, and the testing done once the deployment was complete. Test results include behavior of the rabbit message queue at a 66 node scale as well as comparisons between the Linux Bridge and Open vSwitch ML2 plugins in neutron.


* **Manjeet Bhatia** *(Manjeet is a Software Engineer at Intel Corporation working on neutron. He facilitated the container management in context of proxies, developed IP capacity tracking for neutronclient. He also has some bug fixes in neutron and magnum modules of openstack. He lives in Green Portland who loves nature and opensource development. )*

Speeding up Developer Productivity with OpenStack and Open Source Tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack’s orchestration service and APIs enable developers to easily deploy application infrastructure themselves…but what if developers want to use the popular open source tools with which they're already familiar? This talk covers how developers can use tools from HashiCorp (Vagrant, Terraform, Packer), Docker, Ansible, Puppet, and others to quickly provision workloads on OpenStack clouds. The presenters will share practical examples that attendees can follow along with at the talk and/or take back home to try in their own labs.


* **Trevor Roberts Jr** *(Trevor Roberts, Jr. is the Senior Technical Marketing Manager for OpenStack at VMware and the lead author of DevOps for VMware Administrators (available from VMware Press). He enjoys speaking to customers and partners about the benefits of using OpenStack with VMware technologies.   In his spare time, Trevor shares his insights on data center technologies at http://www.VMTrooper.com, via the vBrownBag Professional OpenStack and Professional VMware podcasts, and on Twitter (@VMTrooper). His contributions to the IT community have garnered recognition by his designation as a VMware vExpert, Cisco Data Center Champion, and EMC Elect.)*

* **Scott Lowe** *(Scott Lowe is a 20-year veteran of the IT industry and a focused technologist that embraces and encourages change, growth, and evolution within the ranks of the IT professionals in the world. Through his books, video training series, blog posts, presentations, and other efforts Scott seeks to help others expand their knowledge and understanding of topics such as cloud computing, networking, virtualization, storage, servers, and other enterprise technologies. Scott's recent books include the OpenStack Architecture Design Guide and the upcoming title Network Programmability and Automation.)*

Using OpenStack to Test Baremetal Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many OpenStack (and other) deployment frameworks have a way to do bare metal provisioning as part of the deployment. However, due to cost and security reasons, it’s extremely difficult to use actual hardware for continuous integration (CI) testing of this functionality. A number of solutions exist, but they all have drawbacks, such as poor security, flexibility, scalability, or performance. Wouldn't it be nice to take advantage of OpenStack to solve all those problems at once? It would allow testing infrastructure to be deployed on-demand, potentially eliminating much of the need for dedicated bare metal CI hardware. This session will explain how to use OpenStack instances to test bare metal-style deployments, including deployment of OpenStack itself.


* **Ben Nemec** *( Ben has been a believer in open source since before he knew open source was a thing.  He previously spent 7 years at IBM in various roles, and now is at Red Hat working on TripleO (using OpenStack to deploy OpenStack).  When not traveling to exotic locales for OpenStack events, he can be found in Rochester, MN.)*

CIAO OpenStack Compatibility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

API compatibility is a key factor to OpenStack components and tools integration. OpenStack services relies on APIs to perform its operations. In today's continuous deployment world, it's fundamental that we design and architect our solutions with compatibility in mind. Transparently interacting with other existing components APIs, even across updates, is a key feature to modern cloud architectures. CIAO provides compute, bare metal and networking services. In order to align with OpenStack specifications and provide a transparent set of OpenStack compatible services that we are developing a full OpenStack API. CIAO is being designed to be fully compatible with OpenStack services, in order for existing OpenStack tools, libraries or applications to transparently work on top of it. CIAO OpenStack compatibility APIs key features are: Fully compatible with several OpenStack service specifications Support one of the two latest versions. Reliability Error Handling Performance


* **Leoswaldo Macias Mancilla** *(Leoswaldo is a Cloud Engineer with a passion for Linux Infrastructure and Automation, he has over three years working on Linux Infrastructure, Automation and Cloud at Intel.  Right now Leoswaldo  works as Cloud Engineer at Intel working in ClearLinux and CIAO projects. Leoswaldo has a role as Cloud Integrator at ClearLinux distro and Cloud Developer at CIAO where he is working on API Compatibility with OpenStack. In his previous experience Leoswaldo worked as Software Engineer of Linux Infrastructure at Intel providing 3rd level of support for Web & DB services. Responsable for two years of Apache HTTPd. One of his greatest accomplisments was the automation for the support of Apache.)*

* **Obed Munoz** *(Obed is a Cloud Software Engineer in the OpenSource Technology Center at Intel and has 6 years of extensive experience in Software Design and Development for Open Source projects that involves from backend to front-end technologies. He has been mainly focused on automation projects for Linux Systems Administration. Obed is also an active contributor to the OpenStack and Clear Linux* Projects.  He's leading the Cloud team for the Clear Linux* Project. Obed did his Bachelor in Computer Science at the University of Guadalajara and actually is finishing his Master’s Degree in Computer Science at the Monterrey Institute of Technology and Higher Education. He’s an ArchLinux and Python language fan.)*

OpenStack Tempest and REST API Testing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tempest— OpenStack’s integrated test suite— used to verify various components of OpenStack cloud. In this talk, we will explain how this test suite can be used to qualify various components of OpenStack. We will use Cinder (Block storage) as the case study for verifying with Tempest. By using Tempest, we are going to verify a Cinder Rest API. This verification infers how many tests are executed, which test cases passed, and how many of them failed. From a Performance perspective, this result will show the amount of time needed to execute individual test cases and overall test coverage. Also, we will explain the configuration changes required in various releases to execute the Tempest test. We will explain how additional customer or feature specific test cases can be incorporated in the Tempest test suite.


* **Ranjith Kumar** *(Name : Ranjith Kumar N SUMMARY: Staff Software Engineer in EMC2 (I) Pvt. Ltd with 15+ years of experience in the IT industry with extensive working knowledge on SDN, SDS, OpenStack, Network fault manager, TCP based application and discovery monitoring, managing virtual infrastructure like Virtual host and ESX servers,  Lucent Ethernet Routers, Intel Network Processor, embedded OS, Assembly Language, Integrated Stack manager, Network Management Software, SNMP agent Implementation, Educational Qualification: Master of Technology in Computer Science & Engg. From Karnataka Regional Engg. College (K.R.E.C./ NITK) Surathkal under Mangalore University completed in the year 2000 April with Bachelor of Engineering in Computer Science & Engg. From N.M.A.M. Institute of Technology under Mangalore University Completed in the year 1996 with First Class. MBA (Correspondence) from Indira Gandhi National Open University (Specialisation in Operation Management).   Experience: Working as Staff Software Engineer in EMC2 (I) Pvt. Ltd. Bangalore from March 2007 to till date Worked as Lead Engineer in Lucent Technologies, Bangalore from February 2006 to March 2007. Worked as Tech Lead in Network Processor Division of INTEL Corporation. Bangalore from July 2001 to till January 2006. Worked as Member Technical Staff in Accelerated Networks (I) Pvt. Ltd. Bangalore (A California based Telecom software company) from October 1999 to June 2001.   Patents: Patent on IPv4 header verification technique called “GENERALIZED AND FAST HEADER VERIFICATION TECHNIQUE FOR DATA PACKET PROCESSING IN NETWORK PROCESSOR APPLICATIONS”. Filed for US Patent on “UNIQUE VLAN NAMING – A GENERIC SOLUTION TO SOLVE THE OVERLAPPING VLAN ISSUES”.)*

* **Parashuram Hallur** *(  Parash is a software professional having around 12 years of experience in designing and developing software products using Java, J2EE, Python and C# technologies. He has almost decade of experience in storage and virtualization industry. He has been working with OpenStack community from Icehouse release, majorly contributing to the cinder project.  He is currently working with EMC on their software defined storage portfolio.)*

AT&T’s Agile Journey: OpenStack Platform Delivery
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In early 2014, AT&T had a multiple teams working on OpenStack development. As a result there were inconsistent and unaligned delivery processes. Since then AT&T Integrated Cloud (AIC) has iteratively implemented advanced Continuous Integration/Continuous Delivery (CI/CD) practices enabling Agile development teams to actively develop features, integrate new technologies, fail fast, and frequently deliver releases. Our journey has included rapid adoption of community build and coding standards. Behind the scenes implementation of Continuous Delivery using Fuel to provide AIC Verification Testing (AVT). Deep dark tales of early integration of Fuel 9.0 with OpenStack Kilo in order to accomplish a massive upgrade from a heavily customized Fuel 6.1.


* **Jared Stein** *(AT&T Senior-System Engineer with primary responsibility in delivering a successful Continuous Integration/Continuous Delivery Framework for the AT&T Integrated Cloud (AIC) Development teams. I am a problem solver with over 10 years of industry experience as a developer, tester, and ScrumMaster.)*

* **Andrew Leasck** *(Andrew Leasck is a Director at AT&T responsible for OpenStack development, automation, and community participation. In 2015 his teams delivered cloud automation tooling, known as OpsSimple, that deployed 74 OpenStack clouds globally. Currently he is focused on creating a community engineering program at AT&T staffed for the sole purpose to help advance the OpenStack platform. Previously he co-authored an Interface normalization patent and more recently received an ITO award for driving AT&T’s Agile transformation, adopting Scrum and XP fundamentals. He attended University of Missioiuri graduating from the School of Engineering with a degree in Computer Science.)*

* **Salim Baig** *(Accomplished Technical Architect / Lead with 12+ years of combined experience in retail, government, telecommunications and wireless billing industries. Strong background in complex wireless billing systems (GSM, 3G) in vendor roles. Recently joining the AT&T Contiuous Integration/Continuous Delivery scrum team to further advance incremental feature delivery.)*

The Gentle Breeze - Functional Testing in Neutron with Zephyr
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack provides the Tempest testing framework to test OpenStack feature functionality.  However, it can be too high-level to test and debug Neutron as a standalone service. Zephyr is an open source framework for developers to test neutron as a standalone entity. Zephyr makes it easy for Neutron developers to test against the Neutron API.  Zephyr is also designed to allow extensible support for Neutron plugins, streamlining Neutron API compatibility testing for third-party Neutron plugin developers. This session will introduce the Zephyr project and design principles, and then we will show a Zephyr running on example test cases, and finally we will create a simple test in Zephyr and show the test results during the session.


* **Michael Micucci** *(I am a Software Engineer living in Tokyo Japan.  My history is primarily in C/C++, especially writing code for networking stacks and multithreading applications.  My education background is in Computer Science at the University of Colorado, and I also hold a Master of Telecommunications degree, also from the University of Colorado.   I have background in technical support and QA, which help me see software engineering as a blend of many disciplines besides raw coding: design, architecture, testing, and support.  My current assignment is at Midokura as a core software developer, focused on Python and Neutron test development.)*

* **Ryu Ishimoto** *(Ryu Ishimoto is the technical lead of Midokura Japan, currently leading the effort to integrate MidoNet and OpenStack Neutron.  He is also responsible for designing and implementing the MidoNet API as well as some parts of the MidoNet cluster and agent.  He is a Neutron contributor.   Prior to joining Midokura, he spent 10 years as a developer for various technologies including data mining, ad server, financial systems, and e-commerce applications.  In 2004, he received a Master's Degree in Computer Science from UCLA.)*

DevOps on Openstack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

DevOps frame work creates the infratructure for Development,testing,deployment and monitoring the application on openstack cloud. The main goal of DevOps is to deploy features into production quickly and to detect and report the problems immediatly, without disrupting other services. This framework can be build with opensource tools for all the SDLC phases such as redmine for requirements management, Zabbix for monitoring, jenkins to build job, Gerrit for code review, Gitlab for source code management , Openstack or docker for deployment.


* **madhavi latha ** *(Madhavi is working as technical lead  in Nextgen business unit ,she is a core member in development of the DevOps framework on openstack cloud.)*

* **Bala Murali Krishna Bokkisam** *(Murali krishna is working as a Development engineer for DevOPs frame work on openstack cloud.)*

Storlets deep dive
~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack storlets is an emerging Openstack project that enables to execute user defined code in an isolated and secured manner within the storage nodes of Openstack Swift.In this talk we first introduce the architecture of the project and overview its functionality. We also describe how to write, deploy and invoke a storlet which is the actual code running near the data. Then, we give the latest status of the project, describing selected features and improvements done since the project was opened as an Openstack project by IBM. Finally, we describe the planned roadmap for the next release.


* **Eran Rom** *(Eran is an open source enthusiatic, who leads the Openstack storlets project and contributor to Openstack Swift. After 10 years in IBM research in the area of storage and systems, and with substantial experiance in leading research and development projects, many of them in the field of cloud storage, Eran has left the company to devote more time to the real thing: open source development.)*

* **Takashi Kajinami** *(Takashi Kajinami is a platform engineer at NTT DATA since 2012. He is working on the private cloud storage construction, with OpenStack Swift and Sheepdog. Recently we deals with IoT system and engaged in the software deployment of IoT services. He is now interested in OpenStack Storlets to realize an effective IoT system, and working as a contributor to that project. He also joined to Docker project to realize auto operation of IT system using Docker.)*

* **Kota Tsuyuzaki** *(Kota is a Software Engineer at Nippon Telegraph and Telephone Corporation (NTT). NTT is one of the biggest telecommunication companies which provide cloud services in Japan. Kota has worked on OpenStack Swift for approximately 4 years. Recently, he has worked on global distributed cluster efficiency and the area of erasure code stuff in the Swift community and he has joined Swift core team since Jun 2015. Since before joining Swift core team, he is working on Swift3 as an upstream contributer and now take a role of PTL on the Swift3 project.)*

How Symantec enhanced OpenStack LBaaS to support legacy LB features via open source Neutron plugin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

SYMC's Cloud P'form Engg team built their pvt OpenStack cloud to host a suite of security/storage-aaS apps. Initially, migrated legacy apps from non-cloud environment to this OpenStack cloud.Legacy apps relied on many LB features implemented on physical LBs.In OpenStack clouds, functionality available thru LBaaS APIs was very limited.Example: HTTP Redirect, backup 404 page, rate limiting to front end VIP, multi SSL Cert, custom health checks, etc could not be exercised via LBaaS APIs.So, to enhance LBaaS offering:- discuss how SYMC leveraged an open source Neutron plugin, implemented a generic mechanism that would allow a user to invoke any arbitrary functionality of LBs outside LBaaS APIs.- explain details of that generic mechanism and how can be used even outside of LBaaS to extend other projects.- explain how OpenContrail Neutron plugin was leveraged in this exercise.- emphasize on how this was done in spirit of community collaboration.


* **Aniket Daptari** *(Sr. Product Manager (Cloud Network Automation, Contrail) @ Juniper Networks Inc. Started as a Software Engineer writing protocol code, CLI, device drivers and online diagnostic software for various networking equipment at different network equipment vendors - Allied Telesyn, Force10 Networks, Cisco Systems. Then began a journey into network programmability, APIs and SDK at Juniper Networks. Evolved from programmability into platforms for NFV and SDN. In this journey evolved from being a Software Engineer to a Technical Marketing Engineer to a Solutions Engineer to a Product Manager. On the education front have a Bachelors degree in Computer Science from Mumbai, India. A Masters degree in Computer Science from University of Southern California. And a graduate certificate in Management Science and Engineering from Stanford University.)*

* **Lodaya Varun Mukesh** *(Varun Lodaya is a Cloud DevOps engineer at Symantec. His work evolves around SDN, analytics/monitoring, docker/kubernetes and other cloud related technologies. His previous experiences include working on Cisco load balancers and core switching gears. Varun has a Master's of Science in Computer Networking from North Carolina State University.)*

Drag and drop tool of Heat to help simplify creating stacks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently use heat to create stacks you have to manually write template files which have limited rules on syntax and format. Users spent much time on learning heat templates and tried to debug times to generate valid templates. This drag and drop tool is integrated into stacks panel page in Horizon. With the tool to create stack, what you need are: drag resource images, input required properties of resources and indicate relationships among resources. The tool will validate your inputs on each step and finally generate valid templates that you could use to create stacks. It greatly simplify creating heat stacks.


* **Bo Wang** *(Bo Wang has been working on OpenStack from 2013. Focusing on Horizon, Heat, DevOps)*

Creating a virtual data center with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When we decided to provide an OpenStack-based public cloud in multiple locations worldwide while maintaining some of our current infrastructure, we knew we would have a big problem to solve: how to alleviate data center hardware complexity. Buying a set of expensive core routers and $100K switches for each developer was not an option. Our solution was to write a complete set of mocking software for all the different types of hardware present in our data centers. Martin Roy and Jonathan Provost will explain how this virtual approach allowed us to quickly iterate through our OpenStack implementation while maintaining a completely automated software process. We will show how the system works and how it can be extended to fit a variety of developer needs.


* **Jonathan Provost** *(Jonathan is a lead developer for Internap.  Mainly focused on the architecture and development of the Baremetal public cloud solution based on OpenStack. He is also the team’s Scrum Master, involved in managing server delivery, backup and network automation. On top of internal responsibilities, Jonathan has also modestly contributed to the upstream Ironic project.)*

* **Martin Roy** *(Powered by Pepsi and classic Jazz, Martin is a coding ninja that is so versatile, he puts swiss army knives to shame.  Just after saying he's not good at something you know that he's gonna show you something about it that you don't know the next day. He's the man behind Netman, a network equipment abstraction layer used at Internap to configure the network layer for Internap's Baremetal public cloud solution.)*

OpenStack CI/CD for Everyone Else
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As a company that develops software on OpenStack, wouldn’t it be amazing if you could use the same robust continuous integration/continuous deployment (CI/CD) process that enables thousands of distributed developers to create reliable software at a blazing pace?  What if setting up this kind of system had an “Easy” button?  Well, the OpenStack Innovation Center (OSIC) QA/CI team is here to help. We’ll walk through a series of best practices and lessons learned from setting up a CI/CD system using open-sourced tools. Your team will be able to leverage the same proven development process used by OpenStack developers upstream.  After this talk you’ll be able to increase your development team’s time-to-market,  efficiency and reliability, and you don't have to be a sysadmin or an IT manager to do it!


* **Joshua White ** *(NA)*

* **Victor  Morales** *(Avid reader who enjoys learning new software technologies and methodologies.  Masters in Information Technology, Co-founder of the OpenStack community at Guadalajara, Mexico and an active OpenStack Contributor, Victor Morales is a passionate developer with over 11 years of software industry experience, expert in programming languages like Java, C #, Visual Basic, Python and SQL. Lately, Fulltime OpenStack developer, helping to accelerate the adoption of OpenStack in Enterprise Environments.)*

* **Luis Daniel Castellanos Barba** *(Work as a developer for the OpenStack Innovation Center in San Antonio primarily working on the OpenStack Horizon project. )*

First App with Terraform
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Do you know that the components of Terraform allows to run a single application on your cloud provider?  Do you want to see how declarative programing can leverage your deployments.  Come to this presentation. We will discuss what are the benefits that Terraform brings Compare functional with declarative programing. Create and destroy cloud resources. Scale available resources up and down. Generates an execution plan describing what it will do to reach the desired state.


* **Victor  Morales** *(Avid reader who enjoys learning new software technologies and methodologies.  Masters in Information Technology, Co-founder of the OpenStack community at Guadalajara, Mexico and an active OpenStack Contributor, Victor Morales is a passionate developer with over 11 years of software industry experience, expert in programming languages like Java, C #, Visual Basic, Python and SQL. Lately, Fulltime OpenStack developer, helping to accelerate the adoption of OpenStack in Enterprise Environments.)*

Master to Metal with OpenStack Charms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How do specific OpenStack commit levels stack up in the metal rack?  In this talk we will discuss the use of OpenStack Charms to deploy OpenStack from source to bare metal, and why that is useful.  Developers and users alike can use the same set of OpenStack Charms to deploy and manage long-running production-grade clouds from stable cloud archive packages as well as dev, test and staging clouds directly from upstream project source code. Packaging can be tricky.  Repackaging from master can be a significant hurdle for a dev or operator to overcome in order to deploy trunk/master onto metal.  The OpenStack Charms enable devs and operators to leap that hurdle without having to repackage from trunk, as a valuable tool for evaluation and development.


* **Corey Bryant** *(Corey Bryant is an Ubuntu core developer and software engineer for the OpenStack Engineering team at Canonical.  He is focused primarily on OpenStack packaging for Ubuntu and Juju OpenStack charm development.  Prior to joining Canonical, Corey was a software engineer for the Linux Technology Center at IBM.)*

* **Ryan Beisner** *(Ryan is QA Engineer on the Ubuntu OpenStack Engineering Team, a global open source software development team at Canonical, the company behind Ubuntu Linux.  He focuses on test automation and application modeling.  His team's CI/CD systems deploy and test hundreds of OpenStack clouds per month, in multiple combinations of topology, architecture and release/build version. Other areas of focus include bare metal cluster management, private cloud administration, service orchestration, modeling language development, general distribution work and consulting support for customer-facing teams. Ryan joined Canonical in 2014.  His background is in network engineering and open source system integration.  Previously, as Operations Director for a US ISP/telecom, he lead the private cloud engineering and deployment efforts for that carrier and its clients.)*

Paas on Openstack – an efficient foundation for CI/CD pipelines.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Continuous Integration is typically about creating numerous application instances repeatedly. These instances are transient in nature. They are brought to life only to undergo a certain set of tests or validation and to be discarded. To support the deployment of these application instances, organizations maintain dedicated environments, which leads to unnecessary operational overhead. PaaS on Openstack provides new automation opportunities and a more efficient CI process. The presentation explains a single PaaS instance deployed on Openstack securely serves all CI phases and ensures consistency across them. It demonstrates dynamic orchestration of containers on PaaS, which in turn drives the underlying Openstack to create additional compute and storage capacity within the security constraints to support transient application instances. The containers and compute resources are later removed or vacated to give room to other apps going through the pipeline.


* **Sasha Jeltuhin** *(Sasha Jeltuhin offers 20 years of experience in software architecture, development and technology management of scalable, high transaction applications, and SaaS platforms. Sasha served in multiple technology roles in a variety of industries including inventory management, tax processing, content management, e-commerce and digital marketing. Applications developed under Sasha’s guidance have been helping organizations, like National Geographic, Smithsonian Institution, hundreds of media companies like CBS, Clear Channel and Tribune as well as major national providers of video and internet service like At&t, Comcast and DirecTV.  During his career Sasha was entrusted with leading several technology organizations of various sizes in the capacity of EVP of Technology and CTO.  Sasha was featured as an invited speaker at various technology events, including Gartner Conferences. Currently Sasha serves as Technology Director of Business Development at Apprenda and is responsible for  PaaS product integration strategy.  )*

Using Kibana & ElasticSearch with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation will provide an overview of Kibana and ElasticSearch. We will cover how they can be used in a distributed system and integrated with OpenStack. We will go into detail on how ElasticSearch shards logs and applies algorithm for search. We will demonstrate the capabilities of the Kibana user interface - searching logs, trending issues, exporting log files and more. Finally, we will provide examples of cases where Kibana was used to analyze and solve real world issues in OpenStack.  


* **Lida He** *(Lida He is a cloud solution architect at EMC Corporation. He has been developing OpenStack based cloud solutions including VxRack Neutrino, a hyper-converged multi-service cloud native solution, and has been helping customers to design IaaS and PaaS to support third platform applications in a wide variety of environments. He also worked on OpenStack monitoring solution for availability, performance and chargeback, and was involved with developing cinder drivers for some industry leading storage products. In addition, he has been actively involved with deploying Cloud Foundry on OpenStack and developing applications on top of it. He is inspired to become an active contributor to the OpenStack projects and community.)*

* **Nebu Mathews** *(I have expertise in Solution Architecture and design of Fault and Performance management solution. I am fully conversant in the process of designing a solution, including study of network design and identifying software components that shape a performance management solution. I have extensive hands on experience & customisation knowledge of EMC M&R (Formerly APG Watch4net), EMC SRM Suite, EMC SAS Suite, EMC VxRacks Neutrino, Openstack Platform, Mycom NIMS-PrOptima, HPOV TeMIP, HPOV TSM.)*

* **Todd Robbins** *(Hi, I am Principal Software Engineer working at EMC Corporation with 10+ years experience. I provide escalation engineering for VxRack Neutrino. Neutrino is OpenStack deployment that allows for turnkey IaaS.)*

HOT for Heat: Validating your Stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Need a way to test your actual stack deployment? Test networking, user permissions, storage access, security and more using HOT. HOT - Heat Orchestration Test is a framework that automates the validation of a deployment. HOT supports template yaml syntax checking, stack build success verification and a highly-flexible fabric-based testing to test the resulting servers. HOT has the ability to run tests from inside your resources and also from outside your environment. Fabric based tests use envassert and any other methods possible in a python script, this ssh’s onto your resource and runs tests. You can check firewall rules, running processes, ensure ports are open, files exist, etc. Script tests are used for testing from outside the environment. Examples include running selenium tests from your CI server, verifying service availability from outside the environment, or calling third party services to run tests such as vulnerability assessment or performance testing.


* **Sabeen Syed** *(Sabeen has been in the QE world for almost 10 years and using OpenStack for the past 3 years. Sabeen likes coding with a QA mindset and taking products & processes from ideas to execution.)*

* **Christopher Hultin** *(I've been with Rackspace since October 2014, and have been working with and on Openstack since October 2015.)*

* **David Fecker** *(I am a professional QA Engineer. I have a history in software development, test and management in multiple environments. From embedded to web services to shrink wrapped software. I am a process champion, working with CMM, ISO, and agile methodologies.)*

Helping OpenStack adoption with an OCCI API Playground (and other OCCIware goodness)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

API adoption is a challenge for OpenStack's rich and complex APIs - a challenge that the OpenStack API Working Group has taken on in strides. In this talk, we will look at a way of helping API adoption, but we'll go beyond API documentation and technical playgrounds such as Swagger. We want to make the case for an interactive online tooling that takes advantage of REST discoverability. In a word, we introduce a REPL shell for REST APIs. We'll showcase a generic playground developed (as part of the OCCIware open source platform) for the OGF's Open Cloud Computing Interface (OCCI), a generic API supported by OpenStack. We'll demonstrate how a beginner OpenStack OCCI API user can execute live examples in seconds, browse through REST resources (such as VMs), and easily generate and derive all kind of queries or changes. We'll finally show how this playground, as well as OCCI standard and OCCIware platform, is a solution to manage other layers and domains in the overall cloud stack.


* **Marc  Dutoo** *(Marc Dutoo is R&D Dept. Head at Open Wide, where he drives innovation in Data, Cloud, SOA and BPM fields. He currently leads the OCCIware project. A FOSS advocate, he belongs to Eclipse SOA and OW2 technical committees, is a regular speaker at conferences (EclipseCon, CloudExpo, Paris Open Source Summit) and has recently opened up the Ozwillo Datacore collaborative Linked, Open Data Cloud.)*

An Interoperable Image Service Powered By OpenStack Glance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Glance supports uploading images for many formats (qcow2, docker, etc.) and purposes (VMs, volumes, containers, etc.). Being able to use an image, however, requires some specific knowledge, for example, what disk and container formats are supported in that cloud, the largest system disk available, etc.  Since Liberty, the Glance team has been working on a more refined API that will help users discover both the platform they can use to upload image data to and the particular formats, sizes, etc. supported in that cloud. This discovery mechanism helps build clients deterministically to build a seamless call for the image import process. This single workflow which lets operators define and users choose a way they want to upload image data makes uploads more performant and flexible.  And did we mentions that it's fully interoperable?  We want to tell you all about it.


* **Nikhil Komawar** *(Nikhil Komawar is the PTL for Glance in Newton release and a Glance subject matter expert at IBM. He's a Open Source and Open Community enthusiast.  He's a former Project Technical lead for the OpenStack Searchlight project and core there. He is also a mentor for the Outreachy program for technical development of the under-represented groups. He loves technical and process evolution.)*

* **Brian Rosmaita** *(Brian Rosmaita is a Senior Software Developer at Rackspace.  He's been an active technical contributor to OpenStack since the Folsom release and was a software developer on the Rackspace first generation cloud.  He's a core contributor to the Glance and Searchlight projects, and is the Glance technical lead for the OpenStack Innovation Center.  In his spare time, he's the host of Radio Ethiopia, a reggae and African music show that's broadcast on K-RACK, Rackspace's internal internet radio station.)*

Beyond Refstack:  The Interop Challenge
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is really big on interoperability.  It has a board chartered committee to drive ever more encompassing interop tests and a project to help run those (and soon other) interop test sets.  But, these efforts are painfully limited due to the youthfulness of OpenStack, the software collection.  So, what can we do to aid interop without stepping on toes?  A consortium of companies have agreed to collaborate on (drum roll, please) The Interop Challenge! The Interop Challenge is using the OpenStack community to create a collection of applications that use the most attainable OpenStack tools (heat and murano) to demonstrate specific workloads for the cloud.  And the challenge is for these community created applications to run successfully across all and any participating vendor's products and/or services. Come join in the fun!


* **Rochelle Grober** *(Rocky is an industry veteran, with experience spanning computer bring up to AI, networks and embedded. But her attention always seems to return to close to the metal, large infrastructure. Starting out in EE, she migrated to SW development then on to QA and SW Process, which is why she is a champion for operations, interoperability and usability. She has been aware and peripherally involved in Open Source since the original creation of Copy Left, but is finally fully emersed in it now, as an OpenStack resource within Huawei. She brings many years of experience in large scale systems and operations, SOA, SAAS, mobile (oh, wait, that's not a TLA!) to the table, along with experience in multiple verticals and other business jargon. But most importantly, she melds a passion for quality performance with a pragmatism gained in the real world.)*

* **Catherine C. Diep** *(Catherine C. Diep is a Solutions Architect and Performance Engineer with IBM Cloud Business Unit at the Silicon Valley Lab. Her responsibilities include providing technical leadership for proof-of-concept, scalability design & testing. Catherine is the PTL of the Refstack project for the Mitaka cycle.)*

Got bored of doing code documentation? Try Sphinx
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

-    Sphinx is a tool that makes it easy to create intelligent and structured documentation. -         We will be covering various aspects like using extensions, generating different output formats and many more interesting things to do with it.


* **Jaivish Kothari** *(Python Developer. Experienced with python programming concepts, building parallel processing systems. Contributor in Openstack projects.I’m a software engineer passionate about working on Distributed system projects. Being interested in various technologies, I have worked on different aspects of Cloud based technologies and other container technologies.As part of my job, I work on Cloud Storage System using python, Linux and couple of other things falling in between. Currently spending my free time in exploring Openstack.)*

* **MD NADEEM** *(I have start my career around 3 years back with Fibre Optics technology, Over the time develope automation framework for Storage Data Centre in python language, Sometime worked in Data analysis using hadoop and then start contributing openstack from last year, Majorly worked in openstack queueing and messeging service zaqar, in parallel start contributing in other openstack project like nova, kolla etc.  )*
