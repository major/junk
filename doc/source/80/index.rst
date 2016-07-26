Cloud App Development
=====================

Building self-healing applications with Aodh, Zaqar and Mistral
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Explore how OpenStack can provide highly-available monitoring of your application at any scale. Automatically scaling and healing applications based on resource/application status or workload is at the heart of the OpenStack value proposition. It is one of the key capabilities that differentiate cloud vs. traditional infrastructure such as VMware. We'll talk about how to make your applications autonomous by using Zaqar to get notifications from an OpenStack cloud and use them to autonomously manage the application's own infrastructure, so that people with pagers sitting in front of monitors and clicking on things don't have to. Then we'll demonstrate how to use new features in OpenStack to build a cloud application that is self-healing in the face of VM failure.


* **Fei Long Wang** *(I'm serving at the PTL of OpenStack Messaging service project(Zaqar) since Mitaka release until now. And meanwhile, I'm in the Glance core team since Grizzly release.)*

* **Zane Bitter** *(I am one of the original developers of the OpenStack Orchestration (Heat) project and still a member of the core team. I served as the Heat PTL for the Juno cycle. I work full time on OpenStack for Red Hat, mostly on Heat and TripleO. Lately I've been thinking a lot about how we make make sure that OpenStack succeeds at providing a full cloud feature set, not just a better way to launch virtual machines.)*

* **Lingxian Kong** *(Lingxian Kong is a contributor of multiple OpenStack projects, core reviewer of Mistral project, with 5 years of experiences in cloud computing area. Lingxian has writen more than 150 technical blogs to introduce features of various OpenStack projects from 2012, helped a lot of students and employees to understand better about OpenStack. Lingxian is aslo the co-founder of Xi'an OpenStack meetup in China, He is a highly requested moderator and speaker for a variety of conferences and other events on topics related to OpenStack.)*

Serverless: How to build an event-driven, polyglot Serverless microservices framework on OpenStack.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Serverless cloud platforms are a major trend in 2016. Following on from Amazon’s Lambda service, released last year, this year has seen Google, IBM and Microsoft all launch their own solutions. Serverless microservices are executed on-demand, in milliseconds, rather than having to sit idle waiting. Users pay only for the raw computation time used. In this talk we are going to detail how to build a distributed serverless, event-driven, microservices framework on OpenStack leveraging our experience of using OpenStack Nova, Cinder, Neutron, Swift, Heat etc and other open source technologies like 1. OpenWhisk: Open source distributed compute service to execute application logic in response to events 2. Docker : To run event driven actions 3. Consul: Tool for service discovery and configuration. 4. Kafka: A high-throughput distributed messaging system. 5. StatsD/ELK/Graphite: For statistics, monitoring and logging 6. Ansible and BOSH: to deploy the serverless platform on OpenStack


* **Animesh Singh** *(Animesh Singh is an STSM and Lead for IBM Cloud Platform and Infrastructure. He has been with IBM for more than 10 years and currently works with customers in designing cloud computing solutions on OpenStack and Cloud Foundry. He has been leading cutting edge projects for IBM enterprise customers in Telco, Banking, and Healthcare Industries, around cloud and virtualization technologies. He has a proven track record of driving design and implementation of private and public cloud solutions from concept to production. He also led the design and development first IBM public cloud offering, and is currently leading initiatives in IBM around OpenStack, CloudFoundry and Bluemix)*

* **Kalonji Bankole** *(Kalonji is currently a software engineer with IBM's Cloud Computing division. He has over 3 years experience with IBM's Cloud Performance team designing and delivering customer solutions that utilize open source technologies such as Openstack,CloudFoundry, Docker, and Elasticsearch. He has spoken about this experiences working with OpenStack, Cloud Foundry and Docker at different conferences. Kalonji received a B.S. in Computer Engineering at Howard University.)*

* **James Busche** *(Jim Busche is a Senior Software Engineer, working for Open Technology and Cloud Architecture at IBM.  Jim's helped install and support multiple generations of IBM Cloud world-wide, and has 4+ years experience deploying and operating openstack for large fortune 500 customers, IBM products as as well as IBM Research projects.)*

Crafting your App with OpenStack Orchestration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session you will learn how to use the OpenStack Orchestration service to make deploying your cloud applications more simple, and most importantly - quickly repeatable. You will learn what the Orchestration service does, key template concepts, some template troubleshooting, how to use it with major configuration management platforms, and at the end will get to play Minecraft with us: deployed on OpenStack using Heat!


* **Hart Hoover** *(Hart Hoover is an OpenStack User Advocate at Cisco. Hoover started his career at Rackspace in 2007 as a Linux Systems Administrator, moving to the cloud to help create their Managed Cloud offering in 2009. He has been an advocate for the open source community, contributing to multiple open source projects. He is also the founder of the San Antonio DevOps meetup and loves tacos and coffee. You can follow him on Twitter at @hhoover.)*

Enabling AWS S3+Lambda-like functionality with OpenStack Swift and OpenWhisk
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Does the concept of server-less architecture intrigue you? OpenWhisk (https://git.io/vKeu3) accelerates innovation through creative chaining of microservices into highly scalable applications. By abstracting away infrastructure, OpenWhisk frees small teams to rapidly work on independent pieces of code simultaneously, keeping development focused solely on creating essential business logic.  OpenWhisk allows you to create rules to connect events with actions and compose microservices that get executed independently and in parallel. With a bit of code, you can have OpenWhisk process events from your Swift Object Storage; similar to what you can do with Lambda functions and AWS S3 storage.   As an example, we will demonstrate how you can create an OpenWhisk action to transform an image into a thumbnail whenever a new (larger) image is uploaded into a Swift Container. In this session, we will cover: OpenWhisk and server-less computing Code modifications required A DEMO of it in action!


* **Shaun Murakami** *(Shaun Murakami is a Senior Cloud Architect and Technical Lead for the IBM Cloud Performance team located in Silicon Valley, California. As part of the Cloud Performance team, Shaun has worked with many customers, helping them transform their business using Cloud Computing technologies and IBM integrated solutions. Shaun has helped influence the evolution of IBM Cloud technologies including the IBM SmartCloud Enterprise, IBM CloudBurst, IBM Workload Deployer, and IBM PureApplication System. He is currently working with various open source technologies such as OpenStack, Docker, and Cloud Foundry to transform some of IBM's next-gen cloud offerings. Shaun received B.S. degrees in Electrical Engineering and Computer Science from the University of Hawaii at Manoa and a M.S. degree in Computer Engineering from San Jose State University.)*

* **Andrew Bodine** *(bio)*

Openly Shift on Stack - Value of OpenShift on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has become the defacto Open Standard for IaaS. At the same time OpenShift is a containerization platform built based on Open Standards such as Open Container Initiative, Kubernetes etc.  While OpenStack and OpenShift are two separate opensource products that don't depend on each other, when they work together a natural symbiotic relationship between these two technologies gives a feeling that they are made for each other.  In this session, we will discuss the current IT landscape, IT trends, issues that Enterprise IT is trying to solve and how OpenStack and OpenShift together address these issues.


* **Veer Muchandi** *(Veer Muchandi is a PaaS Advocate with Red Hat. He helps Red Hat customers adopting OpenShift Enterprise as a Containerization Platform for their enterprise needs.  He works with development and operations teams and helps them bridge the gaps by enabling self service option for developers , thereby reducing the time to market to develop new applications and services and leading to business agility. Veer often works with OpenShift on OpenStack and promotes this combo as a natural fit for the enterprises.)*

* **Alfredo Quiroga** *(PaaS Solutions Architect)*

Innovating applications in the Cloud - Results of the Guadalajara OpenStack Cloud Apps Hackathon
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Innovating in the applications for the cloud is one of the top priorities for OpenStack. Nowadays, OpenStack is a mature platform which next challenge is to shift its community mindset from "How do I get a running cloud?" to "What can I do with a running cloud?". To accomplish this new approach, OpenStack needs cloud application developers aboard. OpenStack Cloud App Hackathons are a series of events that last a month; where developers, operators, designers, students and entrepreneurs are challenged to develop the best possible cloud based application during a weekend. Participants will be trained by top notch open cloud application developers, guided and mentored by the leaders in the cloud computing industry. The Guadalajara Hackathon is the second one of numerous of worldwide hackathons for building a stronger open cloud community in the region. The hackathon is pursuing innovation and knowledge. But above all, share and increase the number of diverse-open-cross-cloud applications.


* **Marcela Bonell** *(Cloud software engineer working on Open Source projects related to Cloud Computing at Intel. She is collaborating in the Cloud Developer Experience improvement for OpenStack through SDK development, trainings, sample apps, workload reference architectures and documentation.)*

* **Victor Diaz** *(Victor has 11 years of experience in IT. He has performed different roles from Dev to QA engineering and the few recent years He has been involved in engineering management roles. Victor has participated in the world of provisioning and self-service tools  for different domains, including hosting, network, OS and bare metal. He is currently involved in OpenStack as a manager of an Intel team focused in User Experience and the Development of tools.)*

Understanding our OpenStack Application Developers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Over the last six months, the App Ecosystem and OpenStack UX working groups have been conducting user research to identify issues that prevent application developers from adopting OpenStack. The Application Developer Study is a significant research initiative because, at the bottom line, application developers are our customers. Failure to meet these customers’ needs will have an impact on the adoption and growth of OpenStack as reference for cloud application development. The research included a series of interviews with five application developers followed by a survey completed by a larger sample of developers. The aim of the interviews was to generate rich data and help working groups propose initiatives that may impact adoption within the cloud application developer’s community. The intention of the survey was to validate the initiatives with a larger sample of application developers.


* **Marcela Bonell** *(Cloud software engineer working on Open Source projects related to Cloud Computing at Intel. She is collaborating in the Cloud Developer Experience improvement for OpenStack through SDK development, trainings, sample apps, workload reference architectures and documentation.)*

* **Danielle Mundle** *(Danielle Mundle joins the OpenStack community as a User Research Engineer. Her goal is to understand the users, workflows, and requirements of OpenStack to identify opportunities for improvements and novel solutions. As a practicing user experience consultant for the past six years, she has performed expert reviews, user-based testing, card-sorts and other user research and design activities for over 85 studies for academia, industry, healthcare, and government clients. Danielle has professional certification from the Board of Certification in Professional Ergonomics as an Associate Human Factors Professional (AHFP). She is a member of the Human Factors and Ergonomics Society (HFES), Usability Experience Professionals Association (UXPA), and the Order of the Engineer. She holds an M.S. in Industrial and Systems Engineering with a concentration in Human Factors Engineering and Ergonomics and a Certificate in Human-Computer Interaction from Virginia Tech, and a B.A. in Psychology.)*

Unified Command client and SDK for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStackClient (OSC) is an unified command client for OpenStack. It has implemented 5 core projects‘ basic commands, and provides a plugin mechanism for other clients to work with it. OpenStack SDK is a library providing APIs for those apps who want to communicate with OpenStack core services. Using OSC and SDK will avoid unnecessary dependency, and obtain well organized commands and APIs. We have made great progress in these two projects (600+ commits) in 2016. Keystone has deprecated its command client. Nuetron is migrating from Neutron client to OSC. Nova has clarified that Nova client will be deprecated, and suggested to enhance OSC. 17 other projects have implemented their clients as OSC plugin. We also integrated SDK into OSC to implement commands. OSC PTL Dean shared why we need unified client during the keynotes in Austin, but didn't give much detail. Now, many developers started to use OSC, and joined OSC and SDK community. So, it's time to know the inside of OSC and SDK.


* **Chen Tang** *(Tang Chen has been a Linux kernel developer since 2012, and mainly worked in memory management, KVM, qemu and libvirt communities. He started to work in OpenStack community since the beginning of 2015, and became a core reviewer of OpenStackClient (python-openstackclient). He is now working on Nova and OpenStackClient development.)*

* **Rui Chen** *(RuiChen is a OpenStack upstream developer team leader at Huawei, he has joined into OpenStack community since the Icehouse release. RuiChen is active contributor in OpenStack development mainly in OpenStackClient, Nova and Congress. Follow RuiChen on his blog, http://kiwik.github.io)*

Getting Started with OpenStack Python SDK
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Python SDK is designed to improve developer experience by consolidating the various OpenStack python- client libraries and command line interface into a unified, well designed, and user-focused SDK ("Software Development Toolkit"). In this talk, we'd like to discuss what the Python SDK is, how it is designed, and how one can use OpenStack Python SDKs. With a consumer application requiring various individual pythons clients to install, each with different APIs and nuances, it becomes increasingly difficult to consume OpenStack clouds. The python-OpenStack SDK project proposes a new project with a single API namespace ("OpenStack") that would provide users with a single point of entry and series of supporting functions/methods from which to build applications and tools.  


* **Shaifali Agrawal** *(# Shaifali Agrawal Shaifali Agrawal - Open Source enthusiast, Python developer, - Outreachy Intern for OpenStack, - 2015 Google Summer of Code Intern, - Working as a Full Stack Developer at Zaya Learning Labs. - [Blog](http://exploreshaifali.github.io/)- [Github](https://github.com/exploreshaifali/)- [Twitter](http://twitter.com/exploreshaifali)- [Linkedin](https://www.linkedin.com/profile/view?id=257818581)- [Google](https://plus.google.com/u/0/+ShaifaliAgrawal))*

Quick Start Guide for OpenStack developers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every year OpenStack receives hundreds of new users and developers. New developers need to start somewhere in order to develop features, automate processes, build tools, execute tests and many other tasks.  This session will provide a few shortcuts and tips to those new individuals in order to help them in their new endeavor. This session will show new Stackers how to create a Python application that uses the software development kits (SDK) already available to them in order to play with OpenStack and show all the results from a self-contained web interface using common open source tools. Creating an application in a short time using open source tools will provide them the confidence they need to add value to the OpenStack community and contribute to the organic grow we expect when everyone is included.


* **Adrian Moreno Martinez** *(Adrian is a software engineer at EMC. He is part of a team focused on engaging and enabling modern application developers, DevOps teams and next-gen ISVs. He is responsible for leading some OpenStack and DevOps related projects. In the last 5 years he has been mainly working in Cloud computing and distributed systems. Prior to EMC, he had the oportunity to work in an FP7 european project at the University Rovira i Virgili in Tarragona, Spain. There, he was one of the founders of StackSync, a fully-featured personal cloud that integrates with the OpenStack platform.)*

* **Julio Colon** *(I’m a Consultant Software Engineer for Emerging Technology Division.  I have been working EMC Storage Arrays and SAN technologies for about 15 years.  During my time at EMC I have performed multiple roles: Quality Engineering, Developer, Security, QA Manager, Development Manager, and Release Manager.  My current roles cover: deployments, software and hardware testing, customer enablement, engineering escalations, apps and tools development. When I am not working in EMC, I like to work with new technologies (e.g. IoT electronics, computer languages), mentoring, and spend time with the family.)*

Changes on the Horizon? Diving into Apple's new programming language and the future of UI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Apple's new programming language, Swift, which made its first appearance in 2014, has quickly gained popularity. Building cross-platform apps has never been more streamlined! This session will include the history, the basics, and the best practices for UI development. Some of the specific topics include, what this new language means for modern UI development, how it makes use of popular design patterns, the tools used for development, and how it compares to other options available. We will take a look at the strides made in creating Swift frameworks and packages, and more specifically how it could influence Horizon, the official OpenStack Dashboard, going forward.


* **Megan Kostick** *(Megan Kostick is a Software Engineer for the IBM Cloud and Open Source Technologies team working in the Seattle area. She focuses on IBM cloud solutions leveraging the OpenStack, Cloud Foundry, Apple Swift and Docker open source projects. Her previous roles include work in virtualization software products and IBM's Linux Technology Center. Megan is also a Co-Organizer of the Seattle Swift Meetup.)*

* **Cindy Lu** *(Cindy Lu has been a software engineer at IBM since 2012, focused on OpenStack community development efforts. She's been an active technical contributor to Horizon since the end of the Icehouse release. She is a core reviewer in the Horizon project.)*

Monitor and manage your OpenStack cloud on the go!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Technology is advancing rapidly, and the marriage of mobile technology and virtualization is the next cornerstone towards the world of tomorrow. With this in mind, we combined OpenStack, Apple's Swift Language, and mobile devices to help realize how cloud technology will be used in the years to come. With OpenStack mobile, our goal is to bring greater productivity for OpenStack administrators, to bridge the gap between masters and novices of cloud management, and to make the cloud a more seamless part of our daily lives. Mobile accomplishes this by making cloud more accessible and more manageable for all. Key features: Decrease service downtime from anywhere responding to situations immediately from your mobile device Ease of access enhances the user experience for your OpenStack Cloud providing essential tools in a mobile-friendly format Gain control over your cloud computing bottom line using mobile devices to track pertinent environment information and cost consumption


* **Megan Kostick** *(Megan Kostick is a Software Engineer for the IBM Cloud and Open Source Technologies team working in the Seattle area. She focuses on IBM cloud solutions leveraging the OpenStack, Cloud Foundry, Apple Swift and Docker open source projects. Her previous roles include work in virtualization software products and IBM's Linux Technology Center. Megan is also a Co-Organizer of the Seattle Swift Meetup.)*

* **Michael Brewer** *(Michael Brewer is a Software Engineer for IBM's Cloud and Open Source Technologies team. Michael's primary focus since joining IBM has been the operation and implementation of OpenStack. Michael graduated from Texas State University with a B.S. degree in Computer Science.)*

Deploying Apps on OpenStack: Things we found while playing around
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When infrastructure becomes invisible and boring, great applications can shine. Let's talk about what happens when you try apps on OpenStack, putting OpenStack itself behind the scenes. Let's take a journey from OpenStack contributor to OpenStack consumer. With an application developer mindset, deploying applications on OpenStack can be frustrating and error-prone, yet for many use cases and environments it makes the most sense. Let's learn about floating IPs and tenant IDs by trying to deploy a staging environment for a docs site.


* **Anne Gentle** *(Anne Gentle works in open source projects with the OpenStack project at Cisco, using open source techniques for API design, developer support, and documentation. She governs projects by serving as an elected member of the OpenStack Technical Committee for more than 30 projects written in Python across hundreds of git repositories. She advocates for cloud users and administrators by providing accurate technical information to increase OpenStack adoption as a cloud for the world. Prior to working on OpenStack in 2010, Anne worked as a community publishing consultant, providing strategic direction for professional writers who want to produce online content in collaborative ways. Her enthusiasm for community-based documentation methods prompted her to write a book about using social publishing techniques for technical documentation titled Conversation and Community: The Social Web for Documentation. As a supporter of women in technology, Anne coordinated efforts to connect OpenStack to the GNOME Outreach Program for Women, now named Outreachy. She writes about open source and community techniques for web content development at justwriteclick.com. As the mom of two youngsters with an awesome husband, she relishes every opportunity to talk with people who are as fascinated with technology as she is.)*

* **Hart Hoover** *(Hart Hoover is an OpenStack User Advocate at Cisco. Hoover started his career at Rackspace in 2007 as a Linux Systems Administrator, moving to the cloud to help create their Managed Cloud offering in 2009. He has been an advocate for the open source community, contributing to multiple open source projects. He is also the founder of the San Antonio DevOps meetup and loves tacos and coffee. You can follow him on Twitter at @hhoover.)*

Building services on top of Openstack APIs: unleash the power of your applications
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Since more than 2 years, OVH works to integrate Openstack as the foundation to its new Public Cloud. Because we want to provide the best user experience for each customer who starts his cloud experience in our Public Cloud, we daily work on top of Openstack APIs to develop APIs, tools, workarounds. Openstack APIs are great tools for developers, on which you can easily add value, automatize actions, gain some time, but you can also lose time by trying to understand how it works and how to achieve your goal. Thanks to our 2 years of experience, we will try to demistify through this talk the Openstack APIs, and how to use it, to help you on your first steps as an API developer.


* **Nathan Castelein** *(Backend developer @OVH, working on public cloud projects using Openstack. Experience on using Openstack APIs through Perl and Golang languages.)*

Unikernels on OpenStack: Toward Secure and Lightweight Software Appliances in the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Unikernels are sealed, specialized machine images and are emerging as efficient and secure alternative for deploying applications. An application built as a unikernel is compiled and linked with only the OS components necessary for its operation.  By design, unikernels boot extrememly fast, have small footprints and small attack surfaces. These characteristics make unikernel a perfect fit for deploying software appliances (e.g. NFV, Security appliance) in a cloud environment.  Because unikernels are specialized per application, new lifecycle management methodology and tools need to be developed to compile, build, and deploy unikernels efficiently in the cloud. In this talk, we demonstrate and discuss: 1) extensions to OpenStack (Glance, Nova, and Solum) to enable unikernel as a first-class resource like VM and container, 2) impact of using unikernels to deploy software appliances in the cloud, and 3) lessons and challenges from operationalizing unikernels using OpenStack.


* **Michael Le** *(Michael Le is currently a research staff member at the IBM T. J. Watson Research Center. His current research focus is on cloud infrastructure and cloud platform management. Michael has previously worked on automating deployment of secure and compliant data analytics platform using OpenStack Sahara and is currently working on how to better secure and isolate applications deployed on the cloud.)*

* **Hui Kang** *(Hui is a research staff member at IBM T.J. Watson Research Center. He is currentlywith the cloud infrastructure team, focusing on OpenStack, Docker, Linux kernel, etc. Hui has contributed to several open source projects, including openstack/kolla, Docker, CRIU, and ovn-scale-test. He also enjoys hacking OS kernel and learning hardware techniques.)*

* **Shu Tao** *(Shu Tao is manager of cloud infrastructure and data services department at IBM T J Watson Research Center.  He has been working on various OpenStack-related projects since 2012.  His current interests about OpenStack include control plane performance and scalability, Neutron plugins, and support for data intensive applications on OpenStack cloud.)*

Deploying composable services with Heat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A demonstration of composable mechanisms in Heat and how those can be combined and used to help software deployment.


* **Dan Prince** *(Dan has been involved with OpenStack since Bexar and been involved with many OpenStack projects over the years including Nova, Glance, TripleO and others.)*

* **Steven Hardy** *(Steven is core reviewer and contributor to both the OpenStack Heat (orchestration) and TripleO (deployment) projects.)*

A day in the life of an cloud-native app developer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Spend a day in the life of one of our App Developers. From first commit we’ll share how we get Apps from IDE to production cloud environment. See how we’ve commoditized cloud-native pipelines using open source tools to deliver microservices on OpenStack or AWS.


* **Lachlan Evenson** *(Cloud Platform Team Lead at Lithium Tech. Cloud evangelist and tire kicker. Pushing cloud to it's limits in a public/private SaaS environment. Passionate about infrastructure automation, architecture and cloud deployment strategy. As a believer in open source and an active member of the community contributing to several projects. Spent the last year enabling microservices.)*

Openstack Murano and Puppet: An easy way to bring your manifests into the cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Developing a new Openstack application from scratch can be be challenging. At the same time there are a lot of Puppet code written and published and used in production. In this presentation I want to show an elegant way to reuse your Puppet code for developing applications for Openstack and to tell why and how we use Murano with the Puppet to develop applications and how these tools complement each other.


* **Alexey Khivin** *(Cloud applications developer in Mirantis)*

* **Sergey Kraynev** *(Sergey Kraynev is working at Mirantis. He began to contribute to OpenStack community since 2012, now he focusing on openstack Heat and Murano Applications, he is core review member of openstack Heat community and ex-PTL of Heat project.)*

Towards micro-services & API-centric application development
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Micro-services and API is becoming a fundamental technology for cloud application development. In this session we will discuss how to design and implement a cloud-based application by leveraging micro-services architecture pattern and API-centric model. We will examine how to partition an application into multiple micro-services and communicate them through APIs. We will illustrate the architecture using a media application that we have built in our environment. We will also describe how OpenStack API and services can play an important role in this architecture design. In particular, we will explain how to utilize OpenStack SDK to communicate with Nova and Swift services, via API, as part of the application logic.


* **Dr Yih Leong Sun** *(Dr Sun accumulated more than 16 years of experience in software development and infrastructure deployment. He obtained PhD Computer Science (Multi-Cloud Infrastructure) in 2013. He spent the past 7 years on Multi-Cloud infrastructure development. He currently serves as a Senior Software Cloud Architect for Intel Open Source Technology Center. Prior to that, he was a Principal Software Engineer for a Fortune-100 Insurance Group, working for the next-generation Cloud platform project. He also led the engineering team of a few start-up companies in Singapore and Silicon Valley. His expertise is in Multi-Cloud orchestration and with a strong interest in building an Enterprise Multi-Cloud platform.)*

* **M.Sc. Omar Bazavilvazo** *(M.Sc. Bazavilvazo has more than 20 years of experience in software development. He obtained his Degree of Master in Information Sciences (HPC on cluster of multi-core processors) from Tohoku University in 2009. He has been working at Intel for the last 7 years. He is currently a Senior Software Developer for Intel Open Source Technology Center focusing on Enterprise Cloud Experience for Developers. Prior to that he worked for IBM and HP among other IT companies working with different technologies. His interests are making OpenStack and Cloud applications easier for Developers to adopt.)*

Service Application Building and Maintaining based on Private&Hybrid OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this topic, we will introduce our experience on cloud native service application buildup and maintenance based on OpenStack which includes full life cycled continous delivery, from perspective of software development to service maintenance and daily operating. this include:1. Service functional definition and deployment topology design.2. Packaging source codes to support integration and testing,3. Build management with multiple snapshots supported4. service scale up and node auto-replacement based on OpenStack Heat engine5. A/B testing, old service runtime cooling and taking over to support new runtime bits promotion6. some experience sharing for delivery iterationAnd in order to make the service running happily, which features of OpenStack should be reinforced, which features should be avoided to use.


* **HUI ZHAO** *(ZHAO HUI is working for Cloud Foundation Service in IBM. He has more expericence in Cloud native service buildup and maintenance.)*

* **Guang Yi Xu** *(Guang is working for IBM Cloud Foundation Service team, he has rich experience on cloud native service development and maintenance with full life cycled continous delivery.)*

* **Yu Jie Gu** *(Gu YuJie is working for IBM Cloud Foundation Service team. She has more experience on cloud native service buildup, development and maintenance with full life cycled continous delivery)*

Cloud Native DevOps, why is it different?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud Native DevOps, why is it different? As Enterprises continue to accelerate their adoption of cloud infrastructures, enterprises are looking at different ways to increase the delivery speed of new apps/innovation. We worked with different enterprises, including large banks, and created a specific methodology to help them embrace Cloud Native DevOPS, by organizing a Hackathon with their developers. Hear about the experience of these large enterprises as they are adopting a new platform & methodologies to develop Cloud Native Applications. Learn about the tools and DevOps best practices  (leveraging key tools including Git, Jenkins, testing tools)  used to deploy both traditional applications and  Cloud Native applications.


* **Marc BERNIS** *(Marc Bernis is part of the HPE Software EMEA Strategy & Technology team which provides presales leadership and profound solution, technical, and business value expertise across the complete HP Software portfolio. Marc is expert in architecting software component for cloud computing and DevOps, offering guidance across a wide range of areas including architecture, products, and research and development, as well as cloud implementation in various environments. Marc is an active contributor of HPE Hybrid IT & cloud reference architecture design and the corresponding software components and their integration in HP cloud solutions. Marc has worked with enterprise customers for more than 20 years to define and deliver IT strategies and solutions He has a background that spans numerous vertical industries, having worked with telecoms and financial services, integrators, and large enterprises. Marc is a graduate in Computer science, automation and software engineering from Aix-Marseille University.)*

* **Christian SCHUTZ** *(Christian Schutz work as an EMEA Cloud Pre Sales for HPE Cloud Business unit.I am supporting both PaaS/DevOPS and NFV/Openstack projects with large enterprise (including Tier 1 EMEA telecom operators).Helping key EMEA customers define their cloud strategy and helping them adopt and implement this new style of IT based on Cloud, NFV and PaaS solutions. Work around Public, Private and Hybrid solutions.I work closely with HP field to pursue cloud opportunities across EMEA and assist them to answers to customer RFx, produce solution designs and deliver solution presentations to customers.Representing HP at key industry events (HP Discover, Openstack Summit and Mobile World Congress).)*

* **Mike Bright** *(Mike is a Solution Architect working for Hewlett-Packard Enterprise, in the HPE EMEA OpenNFV Labb. He is based in Grenoble, France. Mike uses and installs OpenStack on a daily basis, platforms to be used to run customer and partners PoCs or onboarding of ISV VNFs, as part of the HPE OpenNFV program. Mike is also a container advocate, forever interested in container and orchestraton technologies. He runs a local Python User Group in Grenoble, France.)*

Applications for OpenStack, Developing and Consuming using Community Application Catalog
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Now when OpenStack is mature and have it up and running is not a big deal, focus of OpenStack community and customers shifts from "how do I get a running cloud" to "what do I do with running cloud". Variety of applications is huge, from LAMP stacks and legacy Java apps to telco workloads and VNF apps. There is working group which works on a definition of "What is OpenStack application", hopefully community will agree on definition soon. Definition is not yet there, but there is already an integration and distribution point for OpenStack applications, Community Application Catalog (https://apps.openstack.org). There are many applications in the catalog, contributed by OpenStack vendors, Linux and other software vendors and independent contributors.


* **Igor Marnat** *(Igor Marnat runs several engineering groups in Mirantis, which focus on Mirantis OpenStack Platform Products. Among other projects Igor  manages the development of the Murano, Murano Apps, Glare, Heat, Community Application Catalog projects in Mirantis. Previously, Igor ran several engineering teams in the Mirantis Cloud Services division, working on cloud enablement for applications, DevOps automation, and creation of data-intensive services utilizing modern technology stack components such as Hadoop, Cassandra, Storm, and Lucene/Solr. Igor has also headed several projects in the area of networking and embedded applications.)*

* **Christopher Aedo** *(  Christopher Aedo, Cloud Architect at IBM, is an IT veteran for consulting, design and technology companies. He is also an outspoken public advocate for OpenStack, cloud computing, software defined networking, and software defined storage. He's recognized as a community thought leader and has spoken at numerous OpenStack conferences in addition to speaking or participating on panels in multiple international conferences, including OSCon, CloudOpen, PuppetConf, and Okinawa OpenStack Days as well as numerous regional developer groups.)*

App Delivery to App Catalog: Deploying Direct to Murano for More Consumable Solutions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Whatever the specifics of a cloud use-case may be, the need for speed is universal. Most private, public and hybrid cloud users want to reduce time-to-value by speeding up Dev/Test and deploying faster to staging and production. Mirantis has introduced a set of technologies called Murano that serves these needs directly. Murano leverages Community App Catalog to accumulate and share expertise, and supports compiling and delivering pre-defined apps, on demand, as building blocks for different use cases. In this session, I'll discuss recent upgrades to Murano and describe how it can be used to package, standardize, and facilitate consumption and application of software development, application lifecycle management, container cluster, I'll show how apps can be built and deployed directly into Murano from standard IDEs and as the end-product of CI/CD toolchains, to further accelerate access to tools.


* **Nicholas Gulrajani** *(Nicholas Gulrajani currently in the role of a Sr Director PaaS solutions at Mirantis has 20+ years of experience in software development of Middleware Applications and implementation of best practices, for software configuration and change management, along with build and CI/CD systems such as SVN, Git, ANT, Maven, Jenkins, and Nexus and Artifactory.   More recently, Nick has worked with customers to streamline their DevOps implementations utilizing cloud-based infrastructure as code, such as Chef/Puppet along with Application Release Automation Solutions.  His key focus area is in providing best practices and implementing scenarios with use cases for managing Agile software development in the cloud with end-to-end traceability from product backlog and builds to deployment.   Currently with Mirantis in the role of Director of Enterprise PaaS solutions.   Previously with CollabNet for 10+ years in the role of Senior Software Solutions Architect, and prior to (10+ years) with IBM Rational as a Sr Developer, Tech Lead and a Product Manager.)*

Application Catalogs: understanding Glare, Murano and Community App Catalog
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack matured and began reaching the upper layers of the Cloud stack, a number of OpenStack projects started working with cloud applications. Soon enough several initiatives emerged to build services which would provide various catalog-like functionality for these apps. The most notable of these initiatives are project Murano, an Openstack big-tent project officially known as "Application Catalog for Openstack", project Glare (aka GLance ARtifact REpository, previously known as Glance v3) and a Community Application Catalog, an initiative backed by Openstack Foundation, hosting some cloud apps at apps.openstack.org.


* **Alexander Tivelkov** *(Being one of the core developers of Murano project, Alexander is driving a number of inititives there, being a co-author of Murano's DSLs and owning several other large features. Also, Alexander is one of the drivers behind the Artifact Repository initiative in Glance, going to be consumed not only by Murano and Community Application Catalog, but by other OpenStack projects as well, Alexander has more than 10 years of experience in Software Development in both enterprise and open-source projects. He currently works full-time on the Upstream Openstack activities.)*

* **Kirill Zaitsev** *(Murano upstream developer since early 2015, Murano core and PTL for Newton cycle, Community App Catalog developer and core.)*

Applications as first-class citizens on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has delivered on the promise of democratizing management of infrastructure layer for operations' teams. But what about application developers? App developers' concern are primarily based around life-cycle management of their applications. Can they deploy applications written in their language of choice on OpenStack? Can they easily configure CI/CD pipelines for their applications? Is it possible to trigger application deployment by pushing code to their applications' repositories? How to achieve resource isolation across application life-cycle stages of test, build, and deploy? Can they define scaling policies? How about choosing containers vs. VMs as application deployment targets? This, and much more is now possible natively on OpenStack. In this talk we present how OpenStack Solum has made applications first-class citizens of OpenStack enabling app developers to abstract away infrastructure in their application development pursuits.


* **Devdatta Kulkarni** *(Dr. Devdatta Kulkarni is a senior software developer at Rackspace and the current PTL of OpenStack Solum. Devdatta's interests are in solving problems for application developers by designing platforms and services that make it easy to design, build, deploy, and manage applications through their life-cycle stages.Currently he is doing that through his work with the Solum project, and previously did that by designing a high-level programming framework for context-aware applications as part of his PhD dissertation research.Devdatta is a published author, having published research papers in the Association for Computing Machinery (ACM) and IEEE conferences and journals. He has given talks and presentations at ACM conferences and USENIX workshops, and at the OpenStack Summit in Tokyo, Japan. Devdatta earned his PhD in Computer Science from the University of Minnesota in Minneapolis. He is currently teaching a course in modern web application development in the computer science department at the University of Texas at Austin.  )*

* **Vijendar Komalla** *(Vijendar Komalla is a Software Development Engineer at Rackspace. He contributes to Openstack Heat, Magnum and Solum projects.)*

* **James Li** *(I have been working on OpenStack Solum project since April 2014, and serving as a Solum core since October 2014. I've made contributions to multiple OpenStack projects including Solum, Glance, Nova-docker and Oslo.)*

The Cloud Management Roundup: CMP vs. PaaS vs. Orchestration (Application & Infrastructure)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The goal of all cloud management tools, as the name implies, is to have your application fully managed. There are three subtly different categories that offer tooling for this: PaaS (Platform as a Service), CMP (Cloud Management Platforms), and orchestration tools - where some are better for managing resources (e.g. VMs, data, secrets) and chargeback, when others excel at dev >> test >> build straight from your IDE, while others are standard-driven, e.g. TOSCA, and are targeted at hybrid stacks and environments.  


* **T Trammell** *(Trammell listens to a lot of music and even plays sometimes. He is also a Cloudify Product Expert at Gigaspaces.)*

* **Nati Shalom** *(Nati Shalom, Founder and CTO at GigaSpaces, is a thought leader in Cloud-Computing and Big-Data Technologies. Shalom was recently recognized as a Top Cloud Computing Blogger for CIOs by The CIO Magazine and his blog listed as an excellent blog by *technical founders* by YCombinator. Shalom is the founder and also one of leaders of OpenStack-Israel group, and is a frequent presenter at industry conferences.  )*

Let's Learn Go!
~~~~~~~~~~~~~~~

**Abstract:**

Let's get together and quickly build an application in Go.  The Go language has exploded in popularity over the past few years as Python programmers, Ruby developers, and systems C programmers have switched over to the language for its ease of learning, relative flexibility, increased performance, and quick compilations. It is a relatively bare bones language without a lot of features, but that means that it's approachable for new developers and that it's very easy to quickly become proficient and productive in it.


* **Christopher MacGown** *(Christopher was the Founder and CTO of Piston which was acquired by Cisco in June 2015. At Piston he was responsible for building and managing the R&D team that built Piston CloudOS™ which grew out of the development of Piston OpenStack. Prior to Piston, he helped lead the development of a seismic risk analysis engine for the Global Earthquake Model, helped launch OpenStack in 2010, was one of the originating members of the nova-core team, and was an early employee of Slicehost prior to its acquisition by Rackspace. He's served on both Piston's corporate board as well as the OpenStack Foundation board, is an advisor to startups, and drives development of both CloudOS and the adoption of new technologies at Cisco.  )*

Exposing Custom Self-service Applications on OpenStack? Horizon, Heat, CLI, Keystone, Oh My!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You built a custom self-service application (with RESTful APIs) and now you want to expose it to all users of your OpenStack cloud. Though APIs are the ultimate way to interact with any service, users typically consume different OpenStack services via Horizon, CLI, or Heat. Further, users expect that their keystone token should get them access to all services (albeit at different privilege levels depending on their keystone roles). So, unless you integrate your application with all of these OpenStack services and tools, you will have hard luck enticing users to try out your application. In this session, we share our experiences in exposing a self-service networking and analytics application that runs on OpenStack. Further we also present the lessons learned (especially pitfalls-to-avoid when developing your application) and opportunities for improvements in these OpenStack services (Horizon, Heat, etc.) and their architectures that ease building and exposing self-service applications.


* **Praveen Yalagandula** *(Praveen Yalagandula is the OpenStack Architect at Avi Networks, responsible for designing and developing the integration of Avi Networks’ Cloud Application Delivery Platform with OpenStack infrastructure services. At Avi, Praveen also leads the application performance visibility component of the Avi’s solution and has developed a scalable and distributed log analytics system. Prior to Avi, Praveen was a Principal Scientist at HP Labs in Palo Alto, where he spent 8 years exploring several aspects of data center networks, software defined networking, and large-scale distributed systems. Praveen received his Ph.D. in Computer Science from the University of Texas at Austin in 2005. He is currently a senior member of IEEE and ACM.)*

Heat and Its Alternatives: Application Deployment in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When dealing with the deployment of arbitrarily complex virtual application stacks, OpenStack comes with a highly powerful built-in facility: Heat. However, Heat is not the only way to deploy applications within OpenStack — in this session, we'll look at Heat plus two available alternatives: Juju, and Cloudify. In particular, this session covers the following questions: How can I deploy applications with Heat, Juju, and Cloudify? What architectural assumptions does each tool make? How can I deploy multi-node cloud applications? How specific to OpenStack is each solution? What's my expected learning curve? Having worked with all three tools extensively, we're able to give an unbiased, impartial comparison of all three tools.  


* **Florian Haas** *(Florian has been an active member of the OpenStack community since early 2011. He has driven and contributed to lively discussions within the community about OpenStack high availability, distributed storage integration, automation and deployment, and other topics. Florian has spoken about OpenStack at previous OpenStack Summits and also at OSCON, LinuxCon, linux.conf.au and many other conferences. When he is not speaking at conferences, Florian discharges his duties as CEO of professional services firm hastexo (which has a strong OpenStack focus), and also acts as a Principal Consultant serving hastexo's high-profile clients.)*

How to build Murano cloud application from scratch
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Imagine, you have access to OpenStack cloud and need to spin on some complex workload there. Usually, most parts of workload are common, such as database, web server, proxy and so on. But in real life, it often happens that some important part of picture, like, for example, brand new service written on Go, is missing in the community catalog. How user can deal with it? Murano project suggests a solution. Using Murano, users can build complex cloud environments from ready-made blocks and bake new ones if necessary.


* **Sergey Slipushenko** *(Sergey has worked on the cloud solutions at Mirantis for the past three years. He is currently a core contributer for the RefStack project.)*

* **Alexey Zvyagintsev** *(TBD)*

Metadata search: Finding a needle in OpenStack Swift
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every day, terabytes, if not petabytes, of unstructured data is uploaded into OpenStack Swift. The problem with unstructured data is just that, it’s unstructured. To help empower end-users and make the data more valuable, indexing metadata that resides in Swift makes for a very powerful solution in a large amount of use-cases. Marrying object storage, and it's native metadata capabilities, with indexing technologies like Elasticsearch greatly simplifies and enhances the data and makes it more valuable and actionable. In this session we will provide examples of how to work with metadata in Swift, indexing it all, and searching across your pool of valuable data.


* **Timur Alperovich** *(Timur Alperovich is a software engineer at SwiftStack and a contributing member to the OpenStack Swift community. He has also made contributions to a number of additional open source projects including jclouds, Fog, Rails, MySql2 Ruby gem, and others. See https://github.com/timuralp for details.)*

* **Martin Lanner** *(Martin Lanner is an Engagement Manager at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Martin has been working as an entrepreneur and specialized IT consultant involved in OpenStack projects. Martin is active in many large Swift deployments with SwiftStack customers worldwide.)*

Learn to fly before you can soar with eagles :Move  from non-virtualized platform to openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This tech session will guide on process behind moving non virtualized  application to Openstack , what are high level steps , what approach to take convert non virtualized application to Openstack deployment application . How to design application for Openstack world What are the Gotchas How licenses are handled for 3PP in Openstack world How to design networking for new application . We will go over some real life example.


* **Amol Chobe** *(Amol Chobe has 16 years of experience building Telco products and maintaining infrastructure for supporting products. Amol is Prinicipal Deployment Architect at Ericsson, where he works with Engineering and Development teams to design and build systems to support new services. Currently, he is leading infrastructure team focused on Ericsson Cloud Management implementation and POC .)*

OneOps "Code More. Live Better" - Walmart Application life cycle management solution for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Walmart has open sourced OneOps, our tool that allows us to deliver an irresistible Developer Experience. OneOps provides continuous lifecycle management — Once a developer launches their application through OneOps, it can run that app on “auto-pilot.” OneOps automatically scales, heals/repairs and even replaces infrastructure when needed if unforeseen things go awry in the cloud Walmart understands OneOps will be stronger with a large community of collaboration and development We want to move OneOps into OpenStack to increase the rate of innovation OneOps is already a public project github.com/oneops


* **Vitaliy Zinchenko** *(Vitaliy Zinchenko is one of the 3 original co-founders of OneOps, aquired by Walmart in 2013. He has more then 20 years experience designing and implementing large, scalable systems with high availability. Prior to OneOps, he was a Principal Engineer at eBay, where he was responsible for the design and implementation of eBay operations automation systems. He has a Master's degree in Applied Mathematics from National Technical University of Ukraine.)*

* **Kire Filipovski** *(Kire Filipovski is a Co-Founder of OneOps Inc. Mr. Filipovski has 15 years of experience architecting, developing and operating Internet-based services. Prior to OneOps, he managed the Engineering Services organization at eBay, where he was responsible for delivering software automation solutions that were used to manage eBay Marketplace online properties. He holds a Bachelor's degree in Electrical Engineering from Villanova University.)*

So you've got OpenStack. Now what?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So you've finally got OpenStack installed - either through DIY or you got it though a vendor. But there are still a hundred ways to fail with OpenStack. Now, how do you make the best use of OpenStack to ensure your success as application developers and deployers? In this presentation, we will take you through the challenges and best practices around app development and lifecycle management on top of OpenStack, based on our experiences working with several enterprises. We will cover the strengths and gaps within OpenStack, architecting your applications for OpenStack, developing to the OpenStack APIs, image management, CI/CD, Heat, PaaS etc. Basically, we will discuss topics relevant to any application developer and architect to be able to develop and deploy applications  for OpenStack.    


* **Sudarshan Acharya** *(Sudarshan is Senior Developer & Architect at Rackspace and is currently working on Rackspace Private Cloud Solutions focusing on integrating platforms and applications with OpenStack. He is passionate about solving business needs using a mix of OpenStack, DevOps and Bigdata technologies and he has been a contributor to OpenStack and ecosystem projects.)*

* **Daniel Curran** *(Daniel has been a DevOps Engineer at rackspace going on 4 years now. He has been using/deploying and developing for OpenStack for close to 3 years. He has deployed OpenStack in a number of configurations, set up continuous integration systems, created heat templates and integrated CloudFoundry, Ceph and LDAP. Daniel also has experience with config management tools such as SaltStack, Chef, Puppet and Ansible. Daniel also has interest in mobile app development, big data technologies and artificial intelligence.)*

Beyond Horizon: Building custom interfaces with the JavaScript SDK
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn how to use the JavaScript SDK to control OpenStack directly from your web browser. Since the release of Mitaka, OpenStack's services support direct API access from the web browser. This opens the door to a new class of powerful web applications, backed by popular frameworks such as AngularJS and React. This presentation will provide a comprehensive walk through of these features, including the following: How do you configure your Cloud to permit browser access. How do you start a new JavaScript project. How do you configure your project to talk to your cloud. How do you make an API request. How do you authenticate to Keystone. Time permitting, we will also go over the projects' roadmap.


* **Michael Krotscheck** *(Michael works on OpenStack on behalf of HPE, tirelessly advocating modern JavaScript approaches in a sea of Python developers. He is also the co-chair of the App Ecosystem working group, improving OpenStack for all app developers everywhere.)*

Building Bridges to Fill Gaps between AWS and OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AWS Lambda is a serverless compute service that runs application code in response to events. Lambda automatically manages the underlying compute resources for you. You can use AWS Lambda to extend other AWS services with custom logic, or create new back-end services that operate at AWS scale, performance, and security. AWS Lambda can automatically run code in response to multiple events, such as modifications to objects in Amazon S3 buckets or table updates in Amazon DynamoDB. There is currently no equivalent project in the OpenStack Big Tent. Iron.io is an enterprise job processing system for building powerful job-based asynchronous software that can deliver the same capabilities and functions as AWS Lambda. Simply put: developers write jobs in any language using familiar tools like Docker, then trigger the code to run using Iron.io’s REST API, webhooks, or the built-in scheduler.


* **Bruce Basil Mathews** *(Bruce has been a Senior Solutions Architect in the computer industry for almost forty years, working at Information International, Inc., Symbolics, Inc. Prime Computers, Inc., Computervision, Sun Microsystems, Hewlett-Packard, and now Mirantis. During his career, Bruce has provided integration services, application development, and large scale deployments for major corporate initiatives at companies such as PayPal, Salesforce.com, Wells Fargo, McKessen, Intel, and Dreamworks, Technicolor, American Express, CitrixOnLine, and Amgen to name a few. Bruce became involved with OpenStack in 2010 as a member of Hewlett-Packard’s Public Cloud team where he successfully on-boarded more than fifty customers, migrating application services from in-house to OpenStack on versions from Diablo+ to Grizzly, living with them through the upgrade process. Bruce was also heavily involved with the initial release of HP’s Helion Openstack based on the Juno release. Bruce has maintained an active role in the OpenStack, Big Data and Open Source communities. He is certified as an Administrator for OpenStack, Cloudera, and MapR.Customer engagements have typically included technical design, build, implementation, customization, integration and ongoing administration of multi-vendor servers, storage, SAN and network elements, hosted on-premises, implemented as a managed service, and/or publically hosted in the cloud.  Successful implementations have generally included multi-vendor Operating Systems (Solaris, HP-UX, AIX, Irix, RedHat, Ubuntu, CentOS, Debian, Fedora, Windows and Mac,) multi-vendor databases (Microsoft SQL Server, Oracle, MySQL, DB2, Sybase, Informix, PostGres, GreenPlum, Vertica, Cache, etc.) and NoSQL offerings such as CouchBase, CouchDB, Cassandra, MongoDB, etc. Applications implemented and supported have included a wide variety of multi-vendor commercial and non-commercial applications such as Microsoft ERP, Data Warehousing and Business Analytics, SAP, Oracle Manufacturing and Financials, PeopleSoft, etc. and Big Data solutions such as Cloudera, MapR, HortonWorks, and the eco-system that supports them based on Six Sigma methodologies. )*

* **Jun Park** *(  Jun is an experienced problem solver focused on overcoming critical business challenges in variety of fields including Cloud computing/storage, high performance computing, distributed systems, wireless networks, Internet protocols, and network security. His greatest skills focus on the strategic leadership of technical teams in the creation of new technologies around future use cases, designing and developing new systems, as well as tuning and optimizing software/hardware components from prototype to mature product. Jun strongly promotes and facilitate teamwork, communication, and mentoring. Jun currently leads Adobe’s strategic OpenStack based private/hybrid Cloud effort from conception and design through deployment. Jun deals with a variety of use cases including CI/CD frameworks, container-orchestration frameworks such as Kubernetes and Mesos via OpenStack Heat/Magnum/Murano. Jun promotes and leverages use of advanced technologies including Software-Defined-Networking (SDN) and Software-Defined-Storage (SDS) towards the Software-Defined-Economy (SDE).)*

Using Murano deploy ci-cd with one click
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CI/CD plays a more and more important role in the development and testing process, how to quickly deploy CI/CD many companies concerned about the topic, this article demonstrates how to use Murano deployment of the CI/CD environment with one click.


* **Liu Qing Jing** *(Senlin Core)*

Juggling Flaming Swords – Continuously Integrating Environments using OpenStack and Heat Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Developing Cloud aware apps can be difficult. Managing the build, test, and deployment environments of cloud-aware apps increases its complexity. As your application uses more services the complexity increases exponentially. At Intel we attacked the problem by leveraging OpenStack and Jenkins (a continuous integration system) to simplify environment management for developers. In this session we will cover the logical and physical architecture of our integration of Jenkins and OpenStack; Demonstrate examples of Heat templates and their uses in the different development environments; expose the pitfalls that we uncovered in automating the management of these environments; and share the best practices of developing in a dynamic cloud environment.


* **Darren Pulsipher** *(Darren Pulsipher is a Enterprise Solution Architect at Intel. He works in the Data Center Group with a focus on spreading Private Cloud to the Enterprise. He is a software engineering professional known for pulling technology and people together. During his career he has been involved in several different industries including medical imaging, telecom, electronic design automation, cloud computing, business consulting and even nutritional supplements.  Darren is a published author with 3 books on technology and technology management and over 50 articles published in several different industry trade magazines.  He is also known for his speaking ability and has spoken at several conferences focusing on highly technical subjects and managing people and technology. As an inventor, Darren has 10 patents in Cloud and Grid computing infrastructures. His technology has been used in companies to decrease product development lifecycle time through build, test and deployment optimization and virtualization.  Darren enjoys working with people and taking on challenging problems. With his analytical abilities and his ability to relate and interact with people, he has been able to help dysfunctional organizations make changes and succeed. He is known for tackling complex and difficult organizational situations, assessing current culture, and helping the organization become more effective. Darren has 10 children and 1 grandchild. They have lived in several different places over the last 25 years but calls Folsom, CA home at the moment. He spends his spare time at the swimming pool, Baseball fields, Basketball court, orchestra concerts watching his children perform and shopping for his granddaughter.)*
