Hands-on Workshops
==================

Getting Started With OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is the de facto standard for private Clouds. But how can someone quickly get started? This workshop will walk participants through an overview of the history and governance model of the poject, followed by a hands-on tour of the most deployed OpenStack components. As part of this workshop, we will assist attendees with deploying a test OpenStack instance on their laptops using Vagrant, VirtualBox, and RDO. (The relevant Vagrant file and pre-workshop instructions can be found below.) We will then walk attendees through the horizon dashboard and the OpenStack CLI to manage and use their new OpenStack instance. ---------------------------------------------------- Before you arrive at this session please complete the "Preparation" section of these instructions: https://radez.fedorapeople.org/GettingStartedWithOpenStack.html  It will take some time and bandwidth, please plan accordingly.


* **Kenneth Hui** *(Kenneth Hui is a Senior Technical Marketing Manager and a Cloud Evangelist at Rackspace. Ken is passionate about helping customers with their Cloud Computing journey and is an official OpenStack Ambassador. Ken blogs about cloud computing, distributed systems, and OpenStack at http://cloudarchitectmusings.com. He lives in New York City where he can indulge in his love of great food from all around the world. You can follow Ken on Twitter @kenhuiny.)*

* **Dan Radez** *(Dan Radez has worked for Red Hat for 8 years from the company's headquarters office in Raleigh, NC. With Red Hat he's worked in systems release engineering, product engineering and development operations. Dan has been extended invitations internationally to present and participate in OpenSource communities. He has presented introductory / getting started sessions as well as architectural design sessions on OpenStack and OPNFV to international audiences. He's published the book OpenStack Essentials on getting started with OpenStack and is currently focused on involvement in the OPNFV project. Dan enjoys racing triathlons and tinkering with electronics projects.)*

OVN based OpenStack Cloud Deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying OpenStack cloud is not an easy task. It is especially difficult when you are new to OpenStack. There are so many configuration parameters and plugins that you can choose from when you deploy OpenStack cloud. These parameters and plugins make OpenStack cloud very flexible and full of possibilities, but for a new OpenStack developer or a cloud administrator, It creates a steep learning curve, when it comes to OpenStack Neutron, that difficulties just jump to a whole new level. In this hands-on workshop, I will introduce a simple bash script based vagrant project and show you how you can easily deploy an OpenStack cloud onto either virtual machines or physical machines. I will use the OVN plugin as an example. If you like to experience different neutron plugins such as LinuxBridge, OVS, you can simply change one flag in this project configuration file, you will have an OpenStack cloud with your chosen neutron plugin.      


* **Tong Li** *(Tong is a senior software engineer at IBM and is an active contributor to OpenStack. He has worked on OpenStack projects since 2012 and contributed to project Nova, Swift and Ceilometer over the years. While he mainly focuses on OpenStack Neutron project at present, he has also participated in other software development such as Cloud Foundry service broker, Kafka, OpenStack monasca. His interest include internet security, virutal computers, physical and virutal networking, system monitoring and data collection. At his spare time, he normally works on small and medium size home improvement projects in North Carolina.)*

* **Yong Sheng Gong** *(I am working with 99cloud inc. as chief architect, active contributor to neutron, tacker, odl and onos projects. As a ex-core reviewer of neutron, I am doing a lot code reviewers and seeking a feasible NFV solution for community.)*

Red Hat OSP 8 director Installation and managment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The workshop educates on how to install Red Hat OSP 8 director using one conmtroller, compute and ceph nodes. Later shows how to migrate instances and scale the compute nodes.


* **Snehangshu Karmakar** *(I offer an extensive background in all things related to Linux, enthusiasm to learn new technologies, as well as high quality standards; I can implement scalable and reliable tools, design architectures and APIs, create proof-of-concept prototypes or intuitively and quickly analyze existing architectures both for what works and what doesn't; I have experience in small scale deployments and academia as well as in enormous high-availability infrastructures serving millions of users; I'mused to distributed collaboration in an open source model and telecommuting; I enjoy teaching/mentoring, offer strong interpersonal and communications skills, a curious and open mind and very strong work ethics.• 11+ years of industry experience, strong innovative and technical background.• 9+ years at Red Hat as Technical Consultant and now as Cloud Curriculum Manager, invloved helping to write and shape up current and future cloud courses based on Openstack. • 1+ year at Oracle as Senior Sales Consultant, helped to build traction by assisting Enterprise   Sales Manger to provide solution and migrate applications in EMEA region to Oracle Linux  and Oracle VM.• 2+ year at Amazon Web Services as Technical Trainer, educating customer with Amazon   Web Services offering and best practices.• Amazon Web Services contribution at https://github.com/snehangshuk.)*

Running web applications/services on OpenStack - 101
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Solum provides a platform to test, build, deploy and scale applications on OpenStack starting from application source code. In this interactive workshop, the Solum team will walk attendees through installation and configuration of Solum on virtual machine. Attendees will leave with an understanding of the various components of Solum and how it can be used to test, build, and deploy applications on OpenStack.Attendees will learn: Solum Architecture How to Install and Configure Solum How to build application-specific custom runtime environments How to build, test, and deploy applications starting from application source code How to scale up and scale down application instances Integration with Github to trigger execution of application life-cycle stages How to use Solum for CI/CD How to build applications that use other services (such as DBaaS) End user usage of the API, CLI and Horizon UI Contributing to Solum


* **Devdatta Kulkarni** *(Dr. Devdatta Kulkarni is a senior software developer at Rackspace and the current PTL of OpenStack Solum. Devdatta's interests are in solving problems for application developers by designing platforms and services that make it easy to design, build, deploy, and manage applications through their life-cycle stages.Currently he is doing that through his work with the Solum project, and previously did that by designing a high-level programming framework for context-aware applications as part of his PhD dissertation research.Devdatta is a published author, having published research papers in the Association for Computing Machinery (ACM) and IEEE conferences and journals. He has given talks and presentations at ACM conferences and USENIX workshops, and at the OpenStack Summit in Tokyo, Japan. Devdatta earned his PhD in Computer Science from the University of Minnesota in Minneapolis. He is currently teaching a course in modern web application development in the computer science department at the University of Texas at Austin.  )*

* **Vijendar Komalla** *(Vijendar Komalla is a Software Development Engineer at Rackspace. He contributes to Openstack Heat, Magnum and Solum projects.)*

Hands-on Workshop: Learn about microservices architectures with Docker Swarm, Etcd, Kuryr, Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Microservices architectures are revolutionizing the way software is envisioned and built. OpenStack has started to play a key role in enabling the microservices architectures and focused groups inside OpenStack community are working towards this goal: Magnum, Kuryr etc.Docker is one of the key components here and combining them all, we get to build microservices architectures using tools like Docker Swarm, Etcd, Kuryr and Neutron. This workshop will provide attendees with the opportunity to gain experience with various Docker features and uses cases integrated with the OpenStack ecosystem. The lab will cover wide range of topics: Introduction to Docker and OpenStackDocker Swarm: Architecture and usageEtcdKuryr and Neutron: Architecture and usage with DevStackDeploying MicroservicesBreaking Docker, Kuryr and debugging it! Attendees simply need to come in (with their laptop). Workshop speaker/organizer will provide instructions and will be available to answer any questions.


* **Fawad Khaliq** *(Fawad has been a member of the OpenStack community for over four years and a core developer in the Networking ecosystem. He has contributions in several OpenStack projects including Neutron, Nova, Kuryr, Magnum, DevStack. He is also the author and maintainer of networking-plumgrid subproject under Neutron umbrella and has over four years experience in implementing software defined networking, containers, high availability, distributed system and APIs. Fawad is a Senior Software Engineer at PLUMgrid, where he is involved in design and development of cloud computing software components, solving networking problem for new technologies and representing PLUMgrid in various open source forums. Currently, he is working on improving the area of container networking in the OpenStack, Docker and Mesos communities. In future, he plans to solve the problem of application service discovery inside the OpenStack ecosystem. )*

Hands-on lab: Integrate cloud platforms on my enterprise...really integrate it!!.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every enterprise is “on the cloud” nowadays, but majority are just consuming the product and not really embedding it on their IT, apps, and processes, The target of the session is to expose different approaches to simplify the consumption of the cloud, embedding it on the enterprise systems and apps, creating “smart applications” and “smart processes” that simplifies the flow of cloud consumption, using cloud APIs and monitoring tools. The hands-on lab will guide along the way to integrate a ERP (ODOO) with OpenStack keeping track of the "cloud" assets


* **Hans Kristian Moen** *(Work for IBM)*

* **Jesus Arteche Gonzalez** *(Working in IBM for the last 5 years as a global cloud architect. Engaging with customers to amke them succesful on their jouney with cloud technologies. Speaker in other IBM conferences and events www.notesfromchechu.com)*

Workshop-  OpenShift 101: Technology and Architecture for Beginners
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenShift Container Platform is a self-service on-demand application development and deployment platform that runs applications as Containers. OpenShift offers a choice of programming languages, frameworks, databases and development tools enabling you to get the job done, using the languages and tools you already know and trust. This workshop will cover OpenShift's architecture, technology capabilities, and how it runs on the top of OpenStack to run applications as containers.  This is a hands-on lab, so bring your laptop! We will have a pre-provisioned OpenShift environment that you can learn to use to deploy your containers!


* **Veer Muchandi** *(Veer Muchandi is a PaaS Advocate with Red Hat. He helps Red Hat customers adopting OpenShift Enterprise as a Containerization Platform for their enterprise needs.  He works with development and operations teams and helps them bridge the gaps by enabling self service option for developers , thereby reducing the time to market to develop new applications and services and leading to business agility. Veer often works with OpenShift on OpenStack and promotes this combo as a natural fit for the enterprises.)*

* **chakradhar jonagam** *(Chakradhar Rao Jonagam (Internet name debianmaster)  is a Solutions Architects at Red Hat specialized in Container Orchestration technologies. Nodejs and Docker fanatic.  Likes automating tasks. Previously worked as a Developer in various tech Mobile (Native & Hybrid), Web, DB's,  Frontend and Docker.  You can follow on  twitter @debianmaster and github @debianmaster)*

* **Alfredo Quiroga** *(PaaS Solutions Architect)*

Building a Heat Template from the Ground Up
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will teach you to build a OpenStack Heat template from the ground up. The traditional approach to learning Heat usually involves setting up WordPress or another application through a Heat template. This lab is different. Namely, there will be no application at the end of it, just a VM with "Hello, world" in its message of the day. This gives us the luxury of focussing on what comes before the user-data script that deploys WordPress. The aim of this lab is a more basic understanding of two things: First, the building blocks and infrastructure an OpenStack based setup of one or more servers consists of: virtual machines, virtual networks and floating IP addresses, to name but a few. Second, it will teach participants how to describe all of these building blocks reproducibly in terms of a Heat template. This Heat template will be assembled step by step, with debugging practice for various common errors along the way.


* **Johannes Grassler** *(Johannes Grassler is an active OpenStack developer, specializing on Heat but also dabbling in other projects occasionally. He currently works as a Cloud Developer for SUSE Linux GmbH. Before that he used to work at SysEleven GmbH, where he built, operated and used an OpenStack cloud since 2014. He has been an an active member of OpenStack DACH e.V., a German OpenStack user group since its inception in 2014.)*

* **Cameron Seader** *(Cameron is currently a Sr. Data Center Strategist with an emphasis on Enterprise Cloud Computing environments; has a diverse background that includes technical sales, solutions architecture, consulting, and engineering. With over a decade of experience at companies such as Hewlett Packard, Micron, Interland (now Web.com) and Idaho Power, he excels in specific areas of data center design, specializing in system solutions on mainframes to high performance clusters. Cameron has also authored and published documentation and guides for several leading products and emerging technology concepts. As a Certified Linux Engineer he is a trusted adviser to SUSE's most strategic customers.)*

Neutron Ninja 101: A Hands-On Workshop with Neutron Networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Heard Neutron is super powerful but finding it too confusing to really understand?  In this hands-on workshop, participants will take a fun, easily accessible journey through Neutron and how it relates to real-world networking basics.  Each participant will gain hands-on Neutron experience by receiving credentials to a live OpenStack environment!  By the end of this hands-on workshop, participants will not only know how to create networks, subnets, routers, floating ips, and security groups, but truly understand the magic taking place behind the scenes that make all of it a reality!  No prior OpenStack experience is necessary!


* **Matt Dorn** *(Matt Dorn is a Cloud Technology Instructor with Rackspace focused on helping IT teams around the world build private clouds with OpenStack.  He understands that many feel a great deal of intimidation when approaching open source projects and is fanatical about providing an easy to understand learning path that makes OpenStack accessible and fun.  His experience includes joining a 4-person hosting startup in Philadelphia to a leadership position for Dell’s Cloud Services team.  Matt blogs about OpenStack at madorn.com.)*

* **Phil Hopkins** *(Phil Hopkins, Principal Engineer at Rackspace. has an Electrical Engineering Degree from the University of South Florida and has been working on Linux systems for over 15 years. In the past he has taught Cisco Networking classes and worked as a Cisco Admin as well as designing VOIP systems using Asterisk. He is active teaching and writing about Openstack software defined networks (SDN). He has written and currently gives an advanced class teaching OpenStack Networking. Phil has spoken about Cloud Technologies at a number of events including The Red Hat Summit in 2011, OpenStack Summits in 2013 and 2014, and Linux Foundation CloudOpen 2014.)*

Hands-On: Orchestrating Container-based Services in the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Leveraging orchestrated services can be a huge time and productivity saver for your cloud users.  The process of configuring and preparing the resources for those services, however, can be complex and intimidating. OpenStack has several projects for orchestrating services (Heat) and for managing containers (Magnum) that can help you take the sting out of automated deployments.  Join us to get some hands-on time using Magnum and Heat together to create some basic container-based services that you can then expand to fit your specific needs for your own environment.


* **Alejandro Bonilla** *(Alejandro is a SUSE Technical Strategist specialized in OpenStack, CEPH, MongoDB, Hadoop, Public Cloud and Distributed Computing projects. His everyday tasks involve evangelizing open source and bridging communication between engineering and the end consumer. Alejandro has presented at previous OpenStack summits, SHARE, Interop, Hadoop World, Vault and SUSECon amongst some.)*

* **Rick Ashford** *(Rick Ashford has been working for SUSE as a Systems Engineer since 2008. While he spends most of his time evangelizing SUSE Linux, he is most passionate about OpenStack and Ceph.  He has worked extensively with large enterprise customers who are struggling to learn how to integrate these new technologies into their datacenters.  Rick lives in Austin, TX with his wife and four children and enjoys spending what little free time he has building things (electronics, carpentry, whatever) and playing his guitars.)*

Hands-on deep dive with Red Hat Enterprise Linux OpenStack Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this lab, you’ll have dedicated access to a live Red Hat Enterprise Linux OpenStack Platform environment and get hands-on experience with OpenStack. At a minimum, we'll walk you through: The creation and modification of images and snapshots via Glance The definition and configuration of networks, floating-IPs, and load balancers via Neutron The creation and life-cycle management of instances via Nova The creation and life-cycle management of volumes and backups via Cinder The definition and monitoring of a stack template via Heat The creation of users, projects, and associated policies via Keystone Bring-Your-Own Laptop, download the KVM VM images and get hands-on help from Red Hat OpenStack experts wile you work through the lab.


* **Guil Barros** *(Guil is an OpenStack Product Manager at RedHat focused on partner enablement. He works with internal and external engineering groups to leverage our partner value-add towards making OpenStack easier to consume. His personal mission is to remove barriers to entry in the OpenStack space.)*

Secure Your Cinder: A Hands-On Workshop with Cinder Encryption
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We all know Cinder provides the awesome ability to attach block storage to our Nova instances but how secure is the data we place on these volumes? Join us as we explore the potential security vulnerabilities in using unencrypted Cinder storage and setup a live OpenStack environment to utilize block device level encryption.  Participants will learn the history of Linux encryption methods and how Cinder can utilize these methods to securely write data to block volumes.  All participants will receive a live OpenStack environment and step-by-step instruction on the Linux packages and OpenStack configuration files necessary to implement a secure Cinder infrastructure.  After completing the workshop,  participants walk away with peace of mind when faced with the possibility of bare-metal attacks on their OpenStack environment!


* **Matt Dorn** *(Matt Dorn is a Cloud Technology Instructor with Rackspace focused on helping IT teams around the world build private clouds with OpenStack.  He understands that many feel a great deal of intimidation when approaching open source projects and is fanatical about providing an easy to understand learning path that makes OpenStack accessible and fun.  His experience includes joining a 4-person hosting startup in Philadelphia to a leadership position for Dell’s Cloud Services team.  Matt blogs about OpenStack at madorn.com.)*

Fire Up the Build: A Hands-On Workshop with the Heat Orchestration Service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So you finally had a chance to create some instances, networks, and volumes. How do you bring it all together with a single click? Join us as we take OpenStack beginners on an immersive interactive journey through Heat, the OpenStack orchestration service. This workshop provides an easy-to-understand introduction to the world of Heat by not only presenting a fun look at the history of cloud orchestration, but a step-by-step walkthrough on leveraging the power of Heat Orchestration Templates to easily fire up an OpenStack application in seconds!


* **Phil Hopkins** *(Phil Hopkins, Principal Engineer at Rackspace. has an Electrical Engineering Degree from the University of South Florida and has been working on Linux systems for over 15 years. In the past he has taught Cisco Networking classes and worked as a Cisco Admin as well as designing VOIP systems using Asterisk. He is active teaching and writing about Openstack software defined networks (SDN). He has written and currently gives an advanced class teaching OpenStack Networking. Phil has spoken about Cloud Technologies at a number of events including The Red Hat Summit in 2011, OpenStack Summits in 2013 and 2014, and Linux Foundation CloudOpen 2014.)*

* **Matt Dorn** *(Matt Dorn is a Cloud Technology Instructor with Rackspace focused on helping IT teams around the world build private clouds with OpenStack.  He understands that many feel a great deal of intimidation when approaching open source projects and is fanatical about providing an easy to understand learning path that makes OpenStack accessible and fun.  His experience includes joining a 4-person hosting startup in Philadelphia to a leadership position for Dell’s Cloud Services team.  Matt blogs about OpenStack at madorn.com.)*

Autoscale 101: A Hands-On Workshop with Heat & Ceilometer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Although Autoscaling has certainly been one of the buzziest buzzwords, what's the real magic that makes it all work?  Join us as we setup OpenStack autoscaling with the help of the Heat and Ceilometer services.  This workshop provides an easy-to-understand introduction to autoscaling in OpenStack by not only presenting a fun look at the history of the feature, but a step-by-step walkthrough on how to setup your very own autoscaling application!  Learn how to prepare your application for world-wide popularity as demand begins to spike and decrease your capacity during those less busy times!


* **Phil Hopkins** *(Phil Hopkins, Principal Engineer at Rackspace. has an Electrical Engineering Degree from the University of South Florida and has been working on Linux systems for over 15 years. In the past he has taught Cisco Networking classes and worked as a Cisco Admin as well as designing VOIP systems using Asterisk. He is active teaching and writing about Openstack software defined networks (SDN). He has written and currently gives an advanced class teaching OpenStack Networking. Phil has spoken about Cloud Technologies at a number of events including The Red Hat Summit in 2011, OpenStack Summits in 2013 and 2014, and Linux Foundation CloudOpen 2014.)*

OSA 201: Deep dive into deploying OpenStack with OSA
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session is to provide a detailed review of how to deploy OpenStack using the community supported Ansible playbooks (OSA) located on OpenStack GitHub repo (https://github.com/openstack/openstack-ansible). We'll focus on: Overall deployment process: the nuts and bolts Pre-deployment node setup steps Node sizing and network requirements How to make environment specific configurations (allinone or full distributed design) Provide tips and tricks to handling the deployment Let's Build Your Cloud: hands-on workshop session Attendees will be present with all the little details around how to deploy OSA and things to look out for during the implementation.  Session is intended to be a very interactive and provide 'how-to' answers to building distributed OpenStack clouds.


* **Walter Bentley** *(I am a Rackspace Private Cloud Technical Marketing Engineer with a diverse background in Production Systems Administration and Solutions Architecture.  I have over 15 years of experience across numerous industries such as Online Marketing, Financial, Insurance, Aviation, Food Industry, Education and now in the technology product space.  In the past, I was typically the requestor, consumer and advisor to companies to use technologies such as OpenStack, now promoter of OpenStack technology and Cloud educator.)*

Keystone in the Real World: A Hands-On Workshop with Keystone v3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Now that more organizations are upgrading to the Keystone v3 API, how can we use it to setup a real-world, multi-domain OpenStack environment?  Join us in this hands-on interactive workshop as we walk through a live install and configuration of Keystone v3.  Participants will not only learn the history of the Keystone project but receive access to a live OpenStack environment where they will complete the challenge of setting up Keystone for a real-world organization.  Learn the proper way to create domains for business units while ensuring your domain and projects admins only have access to their assigned areas.  Create custom roles and apply those roles to groups that span multiple business units and projects.  Go beyond creating a simple Keystone deployments and step into Keystone in the Real World!


* **John McKenzie** *(Software developer at Rackspace working on the Barbican project. I have also been a technical trainer specializing in OpenStack.)*

Barbican Workshop - Securing the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security is at, or near, the top of everyone's list of "stuff that's important," yet the management of security artifacts (such as keys and certificates) has been lacking a cohesive solution.  This is where Barbican comes into the picture.  Barbican provides secure storage and provisioning of secrets, including keys and certificates.  This workshop provides a tour through the magical world of Barbican, led by core members of the Barbican project. By the end of the class you will know: Importance of secret storage How to store and retrieve secrets with Barbican How to submit an order with Barbican How to create a container How to use quotas Uses for additional user metadata Dogtag Certificate System Integration Key Management Interoperability Protocol (KMIP) Device Integration Hardware Security Module (HSM) Setup Performance Barbican Dev-Ops Architecture Use cases for Barbican / Examples Castellan (Generic Key Management Interface) Use Cases Barbican's Roadmap


* **Douglas Mendizábal** *(Douglas is a Racker, and the current PTL for the Key Management (Barbican) project.  Before being involved in OpenStack, Douglas was a software development consultant specializing in secure development of mobile and web applications.  Douglas also helps organize the Alamo City Python Users Group in his home town of San Antonio, Texas.)*

* **Ade Lee** *(Ade works for Red Hat, and has been involved in Dogtag development (and its integration into FreeIPA) for a number of years now. He has worked to integrate Dogtag and FreeIPA with Openstack, and is a core contributor to the Barbican project. Most recently, he has worked on puppet modules to deploy Barbican in Triple-O and RDO.)*

* **Kaitlin Farr** *(Kaitlin Farr is a Software Engineer at the Johns Hopkins University Applied Physics Laboratory (JHU/APL). She has been contributing upstream to security-related features for OpenStack since 2013.  She is on the core team for the key manager project Barbican and the main contributor to Castellan, the key manager interface library. Kaitlin received her M.S. in Computer Science from the Johns Hopkins University and a B.S. also in Computer Science from Texas A&M University.)*

* **Elvin Tubillara** *(Elvin is a software engineer at IBM and works on the Blue Box dedicated cloud offering. He is originally from Chicago, IL and received his B.S. at the University of Illinois in Urbana Champaign. He currently lives in Austin, TX.)*

* **Fernando Diaz** *(Fernando Diaz is an active OpenStack Core Contributor, focusing on Barbican Development. Born and raised in Miami, Florida, Fernando recieved his B.ASc. in Computer Science at Florida International University. Fernando is currently a Cloud Developer for IBM and works on Key Protect, IBM's Key Management Solution. Currently resides in Austin, Texas. He helps keep Austin weird.)*

Help: I have Trove deployed, how do I build guest images?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

"Help: I have Trove deployed, how do I build guest images?"   This is the #1 question asked by new users of Trove, the OpenStack DBaaS project.   Trove allows users to provision and manage the lifecycle of over a dozen relational and NoSQL databases. To operate Trove, users register guest images for specific database versions, and users can then request instances, replicated pairs, or clusters of those databases. A vital step in making this possible is to build these guest images.   This talk walks users through the process for creating guest images using tools provided by the Trove upstream project. Attendees will learn about the Trove architecture, and learn how to use the OpenStack DiskImage Builder tool to build database images for operation with Trove.   The presenters are Mariam John (of IBM), Amrith Kumar (of Tesora) who are contributors to the Trove project, and Gregory Haynes (of IBM) who is a contributor to the diskimage-builder tool.


* **Amrith Kumar** *(Amrith Kumar is an active technical contributor to the OpenStack project, and a member of the Trove core review team. He is also a member of the OpenStack Foundation Job Analysis Task Force and an author of the book on OpenStack Trove. He is the author of the book on OpenStack Trove (published by Apress, http://www.apress.com/9781484212226). He brings more than two decades of experience delivering industry-leading products for companies specializing in enterprise storage applications, fault tolerant high performance systems and massively parallel databases to Tesora, which he co-founded. Earlier, he served as vice president of technology and product management at Dataupia, maker of the Satori Data Warehousing platform , and Sepaton’s director and general manager where he was responsible for the development of the core virtual tape library product. As a director of product development at Netezza, he managed end-to-end product delivery for all customers and prospects. Amrith studied mathematics at the University of Madras (India) and management at the Indian Institute of Management. )*

* **Mariam John** *(Mariam John is a Software Engineer in the IBM Cloud Architecture and Technology organization. Mariam started working on Openstack during the Icehouse release and is currently an active technical contributor and Core on the Trove project. Prior to that, she worked on different product development and advanced technology teams related to business service management, autonomic computing and capacity planning within IBM.)*

* **Gregory Haynes** *(Greg is an Open Source hacker and technology enthusiast who has contributed to a wide variety of projects both in and out of OpenStack. In his spare time, he enjoys fishing, making flying robots, and trying to come up with ways to combine the two.)*

Get started with the OpenStack REST API
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A lot of people out there are using OpenStack in some way, not as many have been interacting with OpenStack from their own application - but a lot of these people would gain a lot of the possibility to do so. The goal with this session is to do an introduction to the OpenStack REST APIs and end up with a created server in an OpenStack public cloud - completely via the REST API. Python is the most used programming language around OpenStack, but to make this more common for the regular web developer, this session will use PHP, HTML and JavaScript. This session is both a guide to get started with the API, as well as a "hands on lab" - you can follow along and create your own scripts during the session.


* **Tobias Rydberg** *(Software developer at the leading cloud infrastructure company in Europe - City Network. Over 10 years industry experience with a focus on web applications/systems. Todays focus is designing City Networks cloud management platform, based upon OpenStack. Have been working with OpenStack for the last two years, touching the most of the core modules of OpenStack.)*

Learn to debug OpenStack code - a hands-on with the Python debugger and PyCharm.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learning to debug the OpenStack code can save you tons of time. If you are looking to contribute to OpenStack, this is an essential skill! In this introductory hands-on session,  you will learn how to use Python debugger (pdb) and PyCharm to debug OpenStack code.  We will cover the following: Make code changes to an OpenStack subsystem Deploy the code to devstack Run the debugger (both pdb and PyCharm) Step through your code changes We will also show how PyCharm can be used for remote debugging, where PyCharm is run on a local machine and devstack is on a remote virtual machine. Please bring your laptops with VirtualBox installed. We will provide you with a VM image that has devstack and debugging tools. Once you instantiate the VM in your laptop, you will be able to start debugging the code.


* **Vincent Button** *(Director of Innovation at AT&T Foundry, Plano Vincent has been a coder, an engineer and an innovator for over 20 years.  He's worked with most emerging technologies from VoIP, to PONS, to IPTV, to Connected Cars, and now to the Openstack Cloud. Through Innovation and Entreprenurial engagement, Vincent has worked with the AT&T Foundry to bring compelling new solutions to market, and now accelerates AT&T's transition to a software based company using Openstack and SDN. As Co-Foundry of the Gravity Center incubator in Plano, he created an environment that became host to 20 North Texas startup companies.  The Gravity Center was superceded by The DEC which serves entrepreneurial startups community in Dallas. As Solution Specialist with Alcatel-Lucent and ngConnect Vincent created prototyped new solutions using emerging technologies such as IPTV, Augmented Reality, and Mobile Apps.    )*

* **Kamal Hussain** *(Kamal has close to 20 years of experience software engineering, team leadership and entrepreneurship. He has worked on more than 30 projects as a team leader, architect and software engineer. His areas of expertise include cloud, software defined networking, open source software, Linux and web applications.  He has worked on different programming languages such as Python, Java, Perl, PHP and Javascript. He has built both platform and application software products and has experience in procedural, object oriented and functional programming paradigms. He likes building products that solving real customer problems. He has been instrumental in creating many innovative ideas that have become part of Nokia's product offerings. Kamal likes exploring new ideas, learning new technologies and helping the community.)*

Getting Started with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hearing a lot about OpenStack and want to check it out for yourself? See how quick and easy it is to install and start using OpenStack using containers running within a VM on your own laptop. Acquaint yourself with the environment. Learn your way around Horizon (GUI) and the CLI to view and operate an OpenStack cloud, both from the perspective of a cloud administrator and as a tenant/user of the cloud. See how to automate typical workflows such as deploying a new multi-tier application. Best of all, take what you learn with you and experiment on your own to discover all OpenStack offers you.


* **Charles Eckel** *(Charles is a developer evangelist in Cisco DevNet with a passion for open source software and open standards. His journey with open source began in 1999 as a founding member of Vovida Networks where he developed some of the industry's first open source Voice over IP (VoIP) protocol stacks and applications. Now at Cisco, Charles has become a recognized champion of open standards, open source, and interoperability. He runs the Open Source Dev Center, which focuses on Cisco’s major open source contributions, use, and community engagements, including OpenStack, OpenDaylight, and OPNFV. Last year, he successfully introduced open source hackathons into IETF and MEF, revolutionizing the way these SDOs operate and uniting open source software with open standards to maximize the pace and relevance of both. Charles speaks regularly at CiscoLive and has also been a speaker at previous OpenStack, RedHat, LinuxCon, and MPLS SDN NFV World Congress events.)*

Automatic deployment & integration of OpenStack and Ceph with Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you looking for a flexible, customizable, agentless method of deploying OpenStack services and compute nodes? Look no further! Ansible to the rescue. This session will provide a detailed overview of deploying OpenStack and Ceph with Ansible. We will use openstack-ansible[1] for deploying OpenStack and ceph-ansible[2] for deploying Ceph. What we will cover:    Brief overview of Ansible, OpenStack and Ceph    How to install OpenStack with openstack-ansible and Ceph with ceph-ansible    How to integrate OpenStack with Ceph    How to enable Swift API compatible access to your Ceph with radosgw    How to manage Galera cluster failure    How to manage RabbitMQ cluster partitions    How to add/remove controller nodes    How to add/remove compute nodes    How to leverage dynamic inventory    How to destroy and rebuild service specific containers    Upgrading your OpenStack environment    How to make environment specific configurations    Provide tips and tricks for daily operations 


* **Syed Armani** *(Syed is an expert in OpenStack and Ceph deployments, and one of the many organizers of meetups and community gatherings of OpenStack community in India. He frequently speaks about OpenStack at user group meetings in India and has extensive experience of deploying OpenStack in production. He has also spoken on OpenStack at CloudOpen Japan, OpenStack meetup in Israel, OpenStack Korea Day (Seoul) and in previous OpenStack Summits (Hong Kong and Paris).)*

Monasca Bootcamp
~~~~~~~~~~~~~~~~

**Abstract:**

In this sessions every attendee will download and use Monasca on their own laptops. You will learn by practical exercises how to configure Monasca to monitor your DevStack environment. Learn how to send metrics and logs to get acquainted with Kibana and Grafana to visualize your data. Finally, attendees will see how to use metrics and logs to create alerting rules, and how both of these entities can be correlated. This lab session will cover the following topics: Enhanced Monasca Horizon Grafana for metrics Kibana for logs Monasca REST API (metrics and logs) The Monasca CLI Deterministic Alarms Alarms on Logs Overview of the Monasca Agents (metrics and logs) Each attendee should come with his own laptop and will receive Devstack with Monasca installed.


* **Roland Hochmuth** *(Roland Hochmuth is a software architect, developer and evangelist at Hewlett Packard Enterprise and the Project Technical Lead (PTL) for the open-source OpenStack Monitoring-as-a-Service Monasca project. His current focus is on architecture, development and helping to lead the team that develops a highly performant, scalable and reliable turn-key monitoring and logging solution that leverages the industries newest trends and innovations around near real-time stream processing systems, analytics and big data, such as Apache Kafka, Apache Storm, Apache Spark, HPE Vertica and others. Prior to working on Monasca, he was an architect, developer and tech lead on the metrics processing pipeline for HP's Public Cloud. From roughly 2009-2012, he was an architect and tech lead on WebOS on the PC. From 2002-2009 he was a founder, architect, developer and tech lead on the highly successful remote desktop visualization product Remote Graphics Software (RGS), which served as the foundation for launching two products within HP, HP Workstation Blades and HP Halo Videoconferencing. In the early 2000's he worked on HP's e-utilica solution, which was a predecessor for cloud computing. From 1990-2000, he worked on 3-D graphics geometry processing, rasterization, and NURBS surface tessellation algorithms. Roland has experience in a number of software disciplines and domains ranging from 3-D computer graphics, remote desktop visualization, cloud computing and monitoring. He has a history of innovation and leading successful products and teams. He has around sixty to seventy patents and patent applications and frequently presents at conferences. In his free time he studies statistics and Deep Learning.)*

* **Kamil Choroba** *(I am a senior software developer at Fujitsu Enabling Software Technology in Munich for cloud management software. My current focus is on OpenStack Monitoring Service (Monasca).)*

* **Tomasz Trębski** *(What to tell...I am a guy whose work is his pride. I am always trying to push myself and others to try and see all variables of the equation as for me there's no ideal solution.There is no such thing as closed door that I wouldn't try to open, the only problem is the time I need to unlock it. I am a person who believes in all the things he can touch, smell and see.Raised to think for himself and to always fight for his beliefes.Never to back down, because nobody will give me what I desire. There are few things that I consider most important in my life, yet my wife and daughter happiness is one of those things.Everything I ever accomplished and will accomplish is dedicated to them.)*

Hands-on Lab: Test Drive your OpenStack Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron is deployed in the majority of OpenStack clouds but it still constitutes one of the key areas of concerns for organizations worldwide. The transition from traditional hardware-centric networking to the software defined model takes time and learning and requires a mental shift as well as a change in workflows, procedures, tools and best-practices. In this session each participant will be provided with a personal sandbox OpenStack running a live Liberty-based environment and will work on common use cases and applications of SDNs in an OpenStack Cloud. The class will focus on test cases that will move beyond the basics of L2 and L3 and deploy VNFs such as NAT and security policies on top of a 3-tier application topology. The class will also go through exercises that are focused on monitoring and troubleshooting SDNs in an OpenStack cloud.


* **Valentina Alaria** *(Valentina Alaria has been part of the OpenStack community for 5+ years and has worked with 100s of users throughout their journey of learning, designing and deploying OpenStack-based cloud solutions.  A product innovation strategist and technology evangelist, Valentina has 10+ years experience with Cloud and Datacenter Infrastructure and has been involved with SDN since the early days throughout her endeavors at PLUMgrid, Nicira and Cisco. Valentina has held roles across engineering, Product Management and Marketing and currently runs Product and Solutions Marketing & Training for PLUMgrid.)*

Howto configure your cloud to be able to charge your users using official OpenStack components !
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Selling the services provided by a Cloud is one of the essential aspect of the life of a Cloud Provider (both Public or Private). Thus being able to define the various prices and policies that needs to be apply needs to be done using some components at the root of the infrastructure. In this workshop you'll have the chance to learn how access the new way to handle metrics in an OpenStack Cloud but also to use them for your pricing rules. and ONLY using some official components ! This hands-on (you need to bring your laptop) will tackle the following aspects : reminder of the main openstack components used : gnocchi and cloudkitty installation of gnocchi installation of cloudkitty configure cloudkitty to use gnocchi define a standard pricing policy using horizon


* **Christophe Sauthier** *(My Name is Christophe Sauthier, a french guy living in the nice city of Toulouse. Living with my wife and father of 2 beautiful small guys (of course), I am also CEO of a company that I have funded 6 years ago Objectif Libre that only deals with Linux Infrastructure. I have been really involved in the Ubuntu community, being a developper and in various boards, then my life crossed OpenStack... The results being that Objectif Libre became (many times) one of the Top20 contributor and developped a real expertise and lots of services around it.)*

* **Julien Danjou** *(Julien is a Free Software hacker since 1998. He works as a Principal Software Engineer at Red Hat, daily improving OpenStack, a project he has been working on since 2011. He leads the OpenStack Telemetry project as its PTL and contribute to common OpenStack code in Oslo.)*

* **Stéphane Albert** *(Hi, my name is Stéphane Albert, a french guy living in Toulouse. I work at Objectif Libre mainly around OpenStack and IT automation. My main task is to bring CloudKitty to life to add reporting and pricing with Ceilometer metrics in OpenStack. My main interests are Python, OpenStack (how surprising ;)), networking and Open Source software. When I'm not at my computer I repair arcade systems and hack on electronics.)*

Designate Interactive Workshop - Install, Operate, Profit - Hands-On
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

RSVP required. In this interactive workshop, the Designate team will walk attendees through the installation andconfiguration of Designate on a virtual machine.Attendees will leave with an understanding of the various components of Designate and with a workingsingle-VM install on their laptops.Attendees will learn: - Designate Architecture 101 - How to Install and Configure Designate- How to set up Nova and Neutron Integration  - Assigning domains to neutron networks  - Reverse DNS- How to use Designate (API, CLI)- Designate Use CasesAttendees will also have the chance to ask the Designate maintainers questions.


* **Tim Simmons** *(Tim is a Software Developer at Rackspace on the Cloud DNS team, and a member of Designate core. He has been working on Designate for over two years, and is working on developing and operating Designate at scale for Rackspace.)*

* **Graham Hayes** *(Graham is a the PTL of Designate Graham works as part of the DNSaaS team in HP Helion. As part of this team he is responsible for operating a publicly accessible deployment of Designate, while working on new features for Designate, and developing a Designate in a box product for private cloud use. He has been working on Designate for over three years, and previously has experience in both startup and enterprise software development.)*

* **Eric Larson** *(Eric Larson is a Core on Designate project and the author of CacheControl, the recommended HTTP caching library for the popular requests library. He is also a software developer working at Rackspace on the CloudDNS team. Outside of writing code, Eric is a proud father and musician.)*

Vitrage hands-on lab
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Get hands-on with Vitrage, the fault management service for Root Cause Analysis and Deduced Alarms.Are you a cloud admin managing a large deployment, struggling with fault management in your system? Or an OpenStack distro vendor seeking to help your customers deal with increasingly complex fault scenarios in their production environments?  Vitrage is an official OpenStack project, designed to organize, visualize and analyze faults in your Cloud. To do this, it provides features like Root Cause Analysis and Deduced Alarms, in a clear, user friendly interface that makes complex networks easily and visually understood. In this hands-on lab, our core developers will present an overview of what Vitrage is all about, and guide you through the process of installing, configuring and experimenting with Vitrage on your own laptop. By the end of this session, you will know how to personalize Vitrage for your own system structure and needs; Enough to "make it your own".


* **Dr. Elisha Rosensweig** *(Dr. Rosensweig received his PhD from UMass Amherst in 2012, which focused on Content Oriented Networks (CON) as part of the Future Internet Architecture (FIA). He then joined CloudBand as a developer, where he worked the CloudBand Management System, a forerunner of NFV Management Platforms. He is now an R&D Director at CloudBand, and a core developer of Vitrage - a newly-minted OpenStack project dedicated to organizing, analyzing and visualizing the Cloud, specifically with a focus on Fault Management and Root Cause Analysis.)*

* **Alexey Weyl** *(Alexey is a senior software engineer in Cloudband Nokia with over 10+ years of experience in software development, in fields ranging from imaging and security to cloud and analytics.  He is currently a core developer of the OpenStack Vitrage project, dedicated to organizing, analyzing and visualizing the OpenStack Cloud, with a current focus on fault management and Root Cause Analysis (RCA).)*

* **Dan Offek** *(Dan has over 30 years of experience in development. He began programming from a young age, and following his hobby, continued developing as part of his military service and after that, on Network management systems, and Cloud orchestration. Today Dan is a member of Analytics Insight team in Nokia's CloudBand. On his free time, when not spending time with his family, Dan likes cliff climbing, wall climbing and bouldering. He also enjoys bike riding.)*

Configure, Deploy and Troubleshoot OpenStack secured L2 gateway in a devstack environment-Hands-on
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

L2 Gateway (openstack/networking-l2gw) is a service plugin for Openstack Neutron which allows the user to connect an Openstack tenant’s virtual L2 network with a physical L2 network external to the Openstack deployment.This session will be a hands-on workshop for the audience to gain knowledge on installation and configuration of L2 gateway in a secured environment.        


* **Gowri Manickavasagam** *(Gowri Manickavasagam, Senior R&D Test Engineer at HPE, is responsible for quality deliverables of HPE Cloud system and Helion Openstack L2 gateway modules. She is also involved in neutron-ironic integration activities to provide the automatic deployment and network connectivity of bare metals to the cloud,)*

* **Maruti Kamat** *(An active contributor in OpenStack Neutron (especially in networking-l2gw) . Have been working in OpenStack Neutron for past 3 years. Being with the networking business of Hewlett Packard Enterprise (cloud development) and earlier in BYOD and campus edge networking, played a major role in design and development of solutions delivered to valuable customers. Published several papers and patents in these areas.  )*

* **vikas d m** *(Active openstack/networking-l2gw contributor)*

Branding Horizon: A Guide to Customize All The Things!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the theming architecture now available in Horizon, customizing the look and feel is now easier than it has ever been.  Although the base user interface of Horizon is perfectly usable, most of the companies that deploy Horizon for enterprise purposes seek to reband and customize many aspects of the current UI.  In the past, this has been possible, but only through the burden of maintaining many patches and a spaghetti mess of CSS specificity.  This tends to be less than ideal, as it makes it difficult for branding customizations to survive between releases and ever evolving code.


* **Diana Whitten** *(Diana is a Senior Software Engineer with over 10 years of full stack software development, test and system administration experience.  She hails from Tucson, AZ and has a Bachelor of Science degree from New Mexico State Univerisity with majors in Mathematics, Applied Mathematics, and Computer Science. She is an OpenStack UX and Horizon Core and is currently leading the theming development effort in Horizon.)*

Advanced Heat: Getting the Most Out of Your Stacks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Heat is an extremely useful OpenStack service — and one that you're almost certainly not using to its full potential. In this workshop, you'll learn about advanced Heat concepts, and use Heat to the best of its abilities. Among the things you'll learn, we'll include: A refresher on cloud-init, cloud-config and its Heat resource, OS::Heat::CloudConfig — an extraordinarily useful means to configure your VMs right when you boot them OS::Heat::WaitCondition and OS::Heat::WaitConditionHandle — allowing you to streamline the deployment of dependent resources OS::Heat::ResourceGroup — enabling you to define arbitrarily complex resource bundles, and using them as you would any other simple Heat resource These advanced Heat features are highly useful, but badly under-utilized — you should know and use them! In hands-on lab sessions, you'll learn how you'll use these advanced resource types to deploy complex virtual environments quickly and easily, on an OpenStack cluster of your own.


* **Florian Haas** *(Florian has been an active member of the OpenStack community since early 2011. He has driven and contributed to lively discussions within the community about OpenStack high availability, distributed storage integration, automation and deployment, and other topics. Florian has spoken about OpenStack at previous OpenStack Summits and also at OSCON, LinuxCon, linux.conf.au and many other conferences. When he is not speaking at conferences, Florian discharges his duties as CEO of professional services firm hastexo (which has a strong OpenStack focus), and also acts as a Principal Consultant serving hastexo's high-profile clients.)*

Don’t get burned! :  Playing with fire (Aodh) and Heat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Creating your virtual application is just the first step in supporting it.  How do you make sure that nothing goes wrong?  What can you do to prevent it from crashing and burning? One solution is to monitor/manage your application by using Aodh and Heat together to set up alarms and react to them automatically.  This lab will give you *HANDS ON* experience with setting up alarms via Aodh and then triggering responses specified via Heat templates. Don’t get caught unaware!  Come to this session and learn how to FIREPROOF your applications.


* **Paul Ballman** *(Paul is a Product Architect at Ericsson, currently involved in defining the requirements and architecture for Ericsson Cloud Manager.  He has over 30 years experience in the Telecom and financial industries, including more than 25 years in large scale system development and design.  Paul holds a Master’s degree in Computer Science.)*

* **Amol Chobe** *(Amol Chobe has 16 years of experience building Telco products and maintaining infrastructure for supporting products. Amol is Prinicipal Deployment Architect at Ericsson, where he works with Engineering and Development teams to design and build systems to support new services. Currently, he is leading infrastructure team focused on Ericsson Cloud Management implementation and POC .)*

Deploying Magnum with OpenStack Ansible, Hands-On Lab
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud users are excited about using container tools to simplify and accelerate the deployment and management of applications. Magnum brings leading container platforms to OpenStack. In this lab you will install and configure OpenStack Magnum using OpenStack Ansible (OSA). Learn how OSA simplifies maintenance of cloud infrastructure and how Magnum makes it easy for your users to launch Kubernetes, Docker Swarm, or Apache Mesos clusters. We will focus on:* OpenStack Ansible architecture* OpenStack Magnum architecture* Installation of a new service (Magnum) into an existing OSA cloud* Configuration of Magnum* Creation of a Kubernetes/Swarm/Mesos cluster* Pitfalls encountered during operation of an OSA cloud


* **Drago Rosson** *(Drago Rosson completed his B.S. in Electrical Engineering from Texas A&M University. He is a software developer working on Magnum and Heat at Rackspace.)*

* **Adrian Otto** *(Adrian is a Distinguished Architect at Rackspace, after a successful career as a serial entrepreneur. He has over 20 years of experience in technology leadership. He served as the founding PTL for both the OpenStack Solum and OpenStack Magnum projects, and founded the OpenStack Containers Team. He believes that a rich ecosystem of open source projects is a key to cloud technology adoption. Adrian  believes deeply in keeping a strategic long-term view paired with achievable tactical goals. He has spent his recent years working extensively in collaborative pursuits that organize numerous companies to agree and work together. He is rational, reasoned, principled, and knows how to drive consensus. Adrian holds integrity as his highest virtue.)*

Docker for DevOps: Deploying your application to containers using Magnum
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This workshop will lead you through the process of productizing your application, taking advantage of continuous integration (CI) and continuous development (CD) techniques to automate builds and testing to produce a solid product through a series of frequently tested builds. We will then look at how your product can be put into production using Magnum, the OpenStack containers service.


* **Haïkel Guémar** *(Haïkel is a long-time Fedora developer, where he actually serve as Fedora Engineering Steering Committee and Cloud WG member. He is part of the CentOS Cloud SIG member, where he maintains CentOS packaging for OpenStack. He is the former PTL and current core contributor for the RPM packaging project He works at Red Hat in the RDO Engineering team as one of the driving force for OpenStack packaging.  )*

* **Mike Bright** *(Mike is a Solution Architect working for Hewlett-Packard Enterprise, in the HPE EMEA OpenNFV Labb. He is based in Grenoble, France. Mike uses and installs OpenStack on a daily basis, platforms to be used to run customer and partners PoCs or onboarding of ISV VNFs, as part of the HPE OpenNFV program. Mike is also a container advocate, forever interested in container and orchestraton technologies. He runs a local Python User Group in Grenoble, France.)*

Generate and re-use your templates conditionally in dev & test environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Newton release, Heat is enhanced with following features:1. conditions in HOT template version 2016-10-14It helps to write an common HOT template and use it conditionally based on the various facts like - test vs production enviornment- scaling vs normal test environment- with or without a floating IP, security group, etc2. new project os-hot-get to generate HOT using python APIBased on the requirements, It helps to generate the HOT template dynamically using python api.In OpenStack, it could be levaraged by heat-translator, magnum, tacker, senlin, etc projects.Also this could be used by global orchestration solution, which uses the heat for orchestratingthe OpenStack.This presentation will demo an user case base on these two featuers and details/tutorials on how to use them.


* **Tianhua Huang** *(Tian Hua Huang is working at Huawei. She began to contribute to OpenStack community since 2013, now she focusing on openstack heat design and bug fixing, she is core review member of openstack heat community.)*

* **Kanagaraj Manickam** *(  Huawei Senior System Architect @ Huawei Technology India Pvt. Ltd. OpenStack Core-reviewer @ OpenStack Orchestration Service (Heat) Core-reviewer @ OpenStack NFV Orchestration Service (Tacker) Establishing OpenStack Manager (Namos) Open-O Active participant and contributor in Open-O community)*

Hands on Lab: Operating & Upgrading OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will walk users through common OpenStack operational tasks such as deployment, adding/removing capacity, patching, upgrading etc. Each attendee will have access to a live OpenStack environment with the opportunity to try these operations hands-on.   The users shall also be exposed to a few handy troubleshooting and monitoring workflows that will help them quickly identify issues / failures in an OpenStack environments and recover from them. Log aggregation and operations management tools in the live environment provided to the users, will be used to walk users through typical failure scenarios encountered in a real OpenStack environment.


* **Santhosh Sundararaman** *(Santhosh Sundararaman is a Product Manager in VMware's Cloud Management Business Unit, where he focusses on the product strategy for VMware Integrated OpenStack and other cloud infrastructure products. He also works closely with the Networking, Storage and Management business units in VMware to drive integration between OpenStack and the VMware infrastructure products. Prior to this Santhosh was an engineer in the Networking and Security Business Unit at VMware developing vSphere networking features for VDS and the NSX networking virtualization platform. Santhosh holds a bachelor's degree in Information Technology and a Master's in Computer Science. Santhosh has spoken at various technology conferences such as VMworld, PEX and at multiple past OpenStack design summits.)*

The Ceph Power Show :: Hands-on Lab to learn Ceph "The most popular Cinder backend"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Roll up your sleeves and learn deploying, configuring and provisioning storage using Ceph. Below is our agenda where attendees will be investing their 90-minute to learn about Opening Presentation [15 min] Ceph introduction & architecture Integration status: OpenStack & Ceph Ceph use cases wrt OpenStack components Hands-on Lab [60 mins] Create virtual infrastructure on public cloud for Ceph cluster Using ansible to Install and configure multi node Ceph Jewel cluster Setup & provision Ceph Block storage Setup & provision Ceph Object storage via swift and S3 Closing Presentation [15 mins] Case study: what performance you can expect from Ceph Q&A Attendees will get some free credits to Red Hat Ceph Storage Test Drive portal, that they can use later for learning and evaluating Red Hat {Ceph,Gluster} Storage. Ceph is open source SDS which tightly integrated with several OpenStack components such as Cinder,Glance,Nova,Swift,Keystone,Manila & Ceilometer. See http://ceph.com/


* **Karan Singh** *(Karan Singh is working as senior storage architect at Red Hat based in Finland. At Red Hat his responsibilities include designing, implementing and testing various reference architectures, performance and sizing guides based on Ceph. He is deeply involved in Ceph performance evaluation across wide range workloads and industry standard hardware from different providers. Karan has been working with OpenStack, Ceph, DevOps tools and helped building multiple IaaS clouds at CSC-IT Center for Science where he worked before Red Hat. Karan enjoys writing and has authored a few titles on Ceph Learning Ceph : https://www.packtpub.com/application-development/learning-ceph Ceph Cookbook : https://www.packtpub.com/application-development/ceph-cookbook  He devotes a part of his time to R&D and learning new technologies. When not working on Ceph and OpenStack, Karan can be found working with emerging technologies or automating stuffs. He loves writing about technologies and is an avid blogger at www.ksingh.co.in.)*

* **Brent Compton** *(Brent Compton is Director Storage Solution Architectures at Red Hat, leading the team responsible for building Ceph and Gluster storage reference architectures with Red Hat Storage partners.  Before Red Hat, Brent was responsible for emerging non-volatile memory software technologies at Fusion-io.  Previous enterprise software leadership roles include VP Product Management at Micromuse (now IBM Tivoli Netcool) and Product Marketing Director within HP’s OpenView software division.  Within enterprise IT, Brent also served as Director Middleware Development Platforms at the LDS Church and as CIO at Joint Commission International. Clips from a recent conference presentation: https://www.youtube.com/watch?v=ngsxyn2dfus&feature=youtu.be)*

Installing Watcher and demo of a Watcher optimization
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Watcher is an open source software package which provides a flexible and scalable resource optimization service for multi-tenant OpenStack-based clouds. Watcher provides a complete optimization loop—including everything from a metrics receiver, optimization processor and an action plan applier. This provides a robust framework to realize a wide range of cloud optimization goals, including the reduction of data center operating costs, increased system performance via intelligent virtual machine migration, increased energy efficiency, etc.


* **David TARDIVEL** *(David is senior software engineer in the Cloud Computing Lab @ b-com. and he is one of the original implementers of Watcher, the Resources Optimization framework for OpenStack. The bcom Institute of Research & Technology is dedicated to boost development and marketing of tools, products and services that improve everyday’s life, thanks to research and innovation in digital technologies. In concrete terms, bcom  innovates at the highest level in the areas of hypermedia (ultra high definition images, 3D sound and images, intelligent content, virtual and augmented reality, etc.), smarter and faster networks and e-health as the first area of application. It is based in Rennes, France and was launched at the end of 2012. It is supported by French government, Brittany Region and Cities Councils.    )*

* **Vincent FRANCOISE** *(Vincent is a software engineer that has been working on Watcher to eventually become one of its core contributor. Ever since, he's been heavily committed to this project. )*

* **Gang Zhai** *(Gang joined Intel in 2003 as kernel engineer for driver development. From 2005, Gang switched to open source virtualization, like xen/kvm, with interests in VT enabling, live migration, GPU virtualization. In 2014, joined openstack community and mainly focused on telemetry work.  )*

Learning OpenStack - A Hands-On Guide to Extend and Customize OpenStack Compute Capabilities
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is the industry standard cloud infrastructure. Every OpenStack users are expecting OpenStack can continue to adopt new features. However, as a mature open source project, OpenStack can not expand too much to accommodate many new features. The alternative way is to let OpenStack users to extend and customize OpenStack by themselves. This hands-on workshop will guide audiences to understand the open architecture of OpenStack, and will instruct them to practice developing OpenStack extension code from API layer to driver layer (mostly for Nova and Neutron), in order to implement new capabilities which is not supported by existing OpenStack code, or customizing the behavior of existing OpenStack functionality. Those extension and customization need to be always compatible with latest OpenStack code, so that it can continue to work with newer OpenStack releases. This hands-on workshop will also introduce CI concept and practice to ensure the compatibility of extension code.


* **Qin Zhao** *(Qin Zhao is the architect for IBM Cloud Manager. He is OpenStack Nova subjec matter expert, focus on x86 hypervisor enablement. His primary job is to work with OpenStack community and ICM product team for feature design and development, bug fixing and product technical support. He also works with technical sales to design and implement cloud solution for IBM enterprise customers.)*

* **Feng Xi Yan** *(Feng Xi Yan is IBM Cloud Manager developer. His primary job is to develop enterprise feature extension for OpenStack to manage VMware platform. He also works in OpenStack community for code upstream and 3rd party CI.)*

* **Zhen Mei Ma** *(Zhen Mei Ma is VMware Integrated OpenStack developer. Her primary job is VIO networking development, including Neutron driver and NSX driver. She also works on VIO provisioing and DevOps.)*

Tacker Newton features hands-on lab
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, participants will be provided with an overview of OpenStack Tacker and the basic principles of NFV orchestration. The lab will contain a series of exercises to help users become familiar with Tacker workflow and get hands on experience with some of the advanced service features introduced in Netwon release.   - Alarm based monitoring   - Auto-scaling and manual scaling of VNFs   - VNF Forwarding Graphs using Service Function Chaining (SFC)   - Eventing mechanism In this hands on lab the participants will deploy, manage, and monitor complex network services that are self-healing and auto-scalable.    


* **Jeff Rametta** *(Jeff Rametta is a Solution Architect at Brocade where he works in the software networking business unit.  He has a background in network engineering and system administration.  )*

* **Sripriya Seetharam** *(Works as a Senior Software Engineer at Brocade. Tacker project committer. Open source enthusiast. Interested in SDN and NFV related projects.)*

Astara: A Hands-on Installation & Tutorial Workshop
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this interactive workshop, the Astara team will walk attendees through the installation and configuration of Astara on virtual machines. Attendees will leave with an understanding of the various components of Astara and with a working multi node VM install on their laptops.  Attendees will learn: Astara Reference Architecture  How to Install and Configure Astara How to set up Nova and Neutron Integration - Linux Bridge or OVS How to perform day to day network operations tasks Admin user usage of the API, CLI and Horizon UI Advanced Feature functionality Tips and Tricks for using Astara Contributing to Astara


* **Eric Lopez** *(Eric has over 16 years of experience in information security, distributed systems, networking and virtualization technologies. As a Solution Architect for Akanda, Eric helps customers implement and integrate Akanda's Astara Platform and Openstack. Prior to joining Akanda, Eric provided I.T. technical and consulting services to customers at VMware, Nicira, Q1 Labs, Symantec, Vontu, Brightmail and Sun Microsystems. Eric holds Master’s degree in Business Administration from University of San Francisco and Bachelor of Science in Electrical Engineering & Computer Science and Nuclear Engineering from University of California, Berkeley. Eric is a Certified Information Systems Security Professional and VMware VCDX-NV.)*

App Ecosystem Working Group - Working Session
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will be for the App Ecosystem Working group, hands-on, face to face working session. We would like a double time block for this session (ie. 90 mins)


* **Michael Krotscheck** *(Michael works on OpenStack on behalf of HPE, tirelessly advocating modern JavaScript approaches in a sea of Python developers. He is also the co-chair of the App Ecosystem working group, improving OpenStack for all app developers everywhere.)*

* **Patricia Montenegro** *(Program Manager working for the Open Source Technology Center at Intel with extensive UX background.)*

Pocket-OpenStack: Build a usable multinode setup (Controller, 3xCompute, Network) on your 8GB laptop
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This hands-on workshop will lead you in 90 minutes to a full blown multinode setup with Controller, 3x Compute and NetNode on your >=8 GB laptop. You will install the setup in a specially prepared, containerized virtual environment using Fedora or any other recent distribution. With this setup it is also possible to test and try out things like IPA integration or special storage environments like NFS or Ceph. We will touch those capabilities as well. The way we install the whole setup allows you to use the full (not! nested) virtualization power of your CPU and almost all of the RAM for your VMs, so that real life workloads of OpenStack are possible (within the scope of your laptops CPU). So if you are a developer, tester or consultant and in constant resource pressure for doing real tests with multiple machines for many purposes as testing features, easily extending and rebuilding setups, PoCs, learning, developing and preparation of presentations, then this workshop is for you.


* **Joachim von Thadden** *(Joachim joined Red Hat in 2016 to support the Tiger Team. He has some years experience with OpenStack, NFV and SDN as he was developing these subjects for his former employer.There he was responsible for providing PoCs, seminars, trainings and presales activities in the mentioned subjects. Before that Joachim worked for a Linux only company where he conductedmany projects and trainings in various Linux infrastructure projects. Joachim has a deep technical Linux based background and hasn't touched this other operating system for years. If he is not in front of his computer he is probably dealing with a bunch of children and a wife who constantly try conquer his time.)*

Training Labs
~~~~~~~~~~~~~

**Abstract:**

Training Labs is 


* **Pranav Salunke** *(I am working as a Cloud Enginner at SUSE Linux working on SUSE Cloud Products. I have been involved with OpenStack as a student and now as a professional since the last 4 years. I am leading training-labs team and also an active part of install-guides under OpenStack Documentation.)*

Pirates of the OpenStack Alley: How to protect your application via neutron extensions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are security groups adequate for protecting your application ? What can be done to ensure that your deployed application (in form of VMs or Vapp or Stack) is protected within and across data centers/sites? Here comes Firewall-as-a-service and Virtual-private-network-as-a-service (both of which are neutron extensions) to your rescue!  The Firewall-as-a-Service (FWaaS) provides the ability to assign network-level port security for all traffic entering and exiting a tenant network. The Virtual-Private-Network-as-a-Service (VPNaaS) extension enables OpenStack tenants to extend private networks across the public telecommunication infrastructure. We will have a hands-on session which will help you gain knowledge on how to use and setup FWaaS and VPNaaS in OpenStack .


* **Amol Chobe** *(Amol Chobe has 16 years of experience building Telco products and maintaining infrastructure for supporting products. Amol is Prinicipal Deployment Architect at Ericsson, where he works with Engineering and Development teams to design and build systems to support new services. Currently, he is leading infrastructure team focused on Ericsson Cloud Management implementation and POC .)*

* **Paul Ballman** *(Paul is a Product Architect at Ericsson, currently involved in defining the requirements and architecture for Ericsson Cloud Manager.  He has over 30 years experience in the Telecom and financial industries, including more than 25 years in large scale system development and design.  Paul holds a Master’s degree in Computer Science.)*

How to Write a Network Function and Deploy in your OpenStack Cloud in less than 30 mins!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So, you have implemented a super cool network function and want to make it available to your cloud users. You want the network function to be a part of a service chain composed of other functions, or your awesomesauce network function supports the combination of functions in the chain. Your network function simply needs data ports and management ports, you don’t care about how the network plumbing happens. Your network function supports a simple CRUD API for instantiation, configuration, health and usage monitoring. Beyond that you expect the higher level orchestration to manage the lifecycle of your network function regardless of whether this happens over-the-cloud or under-the-cloud. With the help of a policy-based framework, we will show you just how to do all of this in OpenStack. We call this the Bring Your Own Function (BYOF) paradigm. You will stand up an OpenStack cloud with the policy-based framework and the Network Function Plugin that will drive your network functions.


* **Sumit Naiksatam** *(Sumit Naiksatam is a Principal Engineer at Cisco Systems. He contributes to several OpenStack projects and is currently involved in driving and implementing the Group Based Policy project. In the recent past he was involved in driving the efforts around integration of L4-7 services and more specifically Firewall-as-a-Service in Neutron.)*

* **Hemanth Ravi** *(Hemanth is responsible for the development of One Convergence's innovative solutions. Hemanth brings comprehensive experience as an architect of products in data networking, multimedia networking and in building highly scalable data center solutions. Hemanth holds several patents in the area of multimedia networking. Prior to One Convergence, Hemanth was Director of Engineering at NetContinuum and held senior engineering positions at Microsoft, Vxtreme and Wollongong. Hemanth holds a Master of Computer Science from Michigan State University and a Bachelor of Computer Science from REC, Trichy, India.)*

* **Dinko Mitic** *(Cloud Architect at Sungard Availability Services I have build infrastructure for Public and Private clouds for the last three years. My background of over 10 years in Enterprise IT prior to that helps me understand the needs of our customers. My goal is to help transform Enterprise IT organizations as they transition their applications to Cloud. At the same time, I would like to help OpenStack become a platform that is mature and stable, and include some resiliency features expected by traditional IT organizations.  )*

Baremetal containers with Ironic and Magnum
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Magnum supports Ironic through Heat templates and therfore can deploy containers on bare metal nodes. In this lab we will explore what is there and what is missing in Magnum as well as deploy containerised example application with the help of Magnum, Heat and Ironic


* **Saulius Alisauskas** *(Software engineer passionate about cloud tech, automation and software development.)*

Everything you need to know to get started with Neutron - Workshop
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Understanding OpenStack networking (Neutron) can be challenging if you are new to Networking or OpenStack. In this workshop, we will provide hands-on workshops which will allow the audience to familiarise themselves with OpenStack networking, and to uncover Neutron to its simplest form. This workshop is ideal for OpenStack beginners, or intermediate level users wanting to understand the complete networking workflow, or to operators wishing to further their understanding and troubleshooting ability for Neutron deployments.


* **Alok Kumar** *(My name is Alok Kumar and I am a full-stack web application developer currently based in Bangalore, India with over 6 years of extensive experience in python and django in designing, developing and maintaining web solutions. Over the past year, I have been exploring OpenStack internals, and maintains a major focus on Dashboard & Networking components of OpenStack. I have shared my OpenStack learning journey with beginners wishing to learn more about Neutron and how to contribute to OpenStack in numerous articles which have been shared on Superuser. I have also conducted Neutron workshops as part OpenStack Days to large ops & dev audiences, assisting them in a wider range of OpenStack projects including storage and automation. You will find me highly enthusiastic and passionate about a range of topics, from learning new technologies and automation tricks to sharing knowledge within the community and discussing football strategies.)*

Interconnecting OpenStack based containerized workloads with legacy using HEAT templates.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We will be providing hands on lab which will cover spawning KVM based VM's and nova/docker containers all in the same cluster interconnected together with opensource neutron solution. The labs will cover step by step instructions on how to launch a multi-tier application with one tier containerized and other implemented in VM's. It'll also cover a packet walk through of how traffic flows between VM's and docker containers. Further we will demostrate how such multi-tier application can be orchestrated by HEAT templates and in the process we will cover some nifty debugging tips and tricks.      


* **Sanju Abraham** *(Sanju is a software engineer at Juniper Networks working on Opencontrail. He works with customers and prospects on developing and optimizing solutions for virtual network implementations for private and publicclouds.  )*

* **Fawad Shaikh** *(Sr. Solutions Engineer at Juniper Networks working on OpenContrail.)*

* **Dilip Sundarraj** *(Principal SW Engineer at Juniper networks working on OpenContrail.)*

Make Me a MidoNet Master: Hands-On Workshop
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

MidoNet is a popular Neutron plugin for large scale OpenStack clouds (1000+ cores). MidoNet is an open source network platform that can be used to build arbitrary network topologies on top of existing IP networks without having to modify the underlying infrastructure. Today, the most common use case for MidoNet is with OpenStack deployments. You do not need special hardware for using MidoNet, as it is all based on software. Come and learn from the engineers that contribute to the Neutron and Kuryr projects! This hands-on workshop will provide the know-how for participants to install MidoNet themselves using Ansible, walk-through an environment to learn MidoNet components, configure various network topologies including load-balancers, firewalls, security groups, & advanced networking, and finally implement best practices and troubleshooting skills.


* **Cynthia Thomas** *(Cynthia is a Systems Engineer at Midokura. Her background in networking spans Data Center, Telecommunications, and Campus/Enterprise solutions. She is a frequent speaker at cloud conferences such as OpenStack Summits, OpenStack meetups and the IT Cloud Computing Conference (IC3). Cynthia has earned a number of professional certifications, including: Alcatel-Lucent Network Routing Specialist II (NRS II) written certification exams, Brocade Certified Ethernet Fabric Professional (BCEFP), Brocade Certified IP Network Professional (BCNP), and VMware Technical Sales Professional (VTSP) 5 certifications. Cynthia received her B.Sc.(Eng) and M.Sc.(Eng) from Queen’s University in Kingston, Canada.)*

* **Abel Boldú del Castillo** *(Abel specializes in System Administration and Support Engineering with UNIX systems.  His expertise lies across various specialties: Cloud computing, OpenStack, KVM, XEN, XenServer, VmWare, Hyper-V, GNU/Linux, Qemu, Docker, Ansible, Centos, Debian, Archlinux, Pacemaker, DRDB, HA, Apache, Nagios, Munin, Rsnapshot, Networking, Python, Bash, Zsh. Abel is currently playing a DevOp and IT role by maintaining systems and automating OpenStack deployments.  )*

* **Alexander Gabert** *(http://agabert.github.io/ Professional career since 1999, began as data center engineer for NT4 clusters and DEC FC storage.As Gentoo developer responsible for porting and packaging of kernel+userland security patches. TODAY: focus on Linux in a data center environment, pure L3 network fabrics, fun with network overlays.)*

Time to roll up your sleeves – Cloud Aware Application Development with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

If you are an application developer, this is the hands on lab for you! In this session you will learn how to develop multi-tier cloud aware applications utilizing OpenStack Services. Specifically we will cover how to write a Heat Template for the development, test and deployment of an application that contains a message queue, database, worker nodes, and a web front end. We will also leverage OpenStack Services like Trove, Designate, and Zaqar to develop an example application. This hands on Lab will allow developers to work directly with OpenStack Services and develop real applications. By the end of this session attendees will have a better understanding of the challenges, the best known practices and the pitfalls of developing Cloud Aware Applications in OpenStack.


* **Darren Pulsipher** *(Darren Pulsipher is a Enterprise Solution Architect at Intel. He works in the Data Center Group with a focus on spreading Private Cloud to the Enterprise. He is a software engineering professional known for pulling technology and people together. During his career he has been involved in several different industries including medical imaging, telecom, electronic design automation, cloud computing, business consulting and even nutritional supplements.  Darren is a published author with 3 books on technology and technology management and over 50 articles published in several different industry trade magazines.  He is also known for his speaking ability and has spoken at several conferences focusing on highly technical subjects and managing people and technology. As an inventor, Darren has 10 patents in Cloud and Grid computing infrastructures. His technology has been used in companies to decrease product development lifecycle time through build, test and deployment optimization and virtualization.  Darren enjoys working with people and taking on challenging problems. With his analytical abilities and his ability to relate and interact with people, he has been able to help dysfunctional organizations make changes and succeed. He is known for tackling complex and difficult organizational situations, assessing current culture, and helping the organization become more effective. Darren has 10 children and 1 grandchild. They have lived in several different places over the last 25 years but calls Folsom, CA home at the moment. He spends his spare time at the swimming pool, Baseball fields, Basketball court, orchestra concerts watching his children perform and shopping for his granddaughter.)*

Hands on training in enhancing openstack HEAT and Ceilometer for TELCO use cases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As we already know Telcos are moving further along in embracing Openstack inorder to build next generation Telco cloud offerings and one of the main pillar around this is Network Functions Virtualization or NFV. One of the key aspect of rolling out a effective NFV based offering is agility. Agility manifests in the form of template driven orchestration of the the network function and how the network functions can  scale UP or DOWN based on the changing parameters or threshold. In this session we are going to demonstrate and guide the participants through a hands on lab leveraging Openstack Neutron  , Openstack HEAT , Openstack Ceilometer and their respective extensions.


* **Vivekananda Shenoy** *(https://www.linkedin.com/in/vivekanandashenoy)*

* **Sree Sarva** *(None)*

Workshop - Deploying a Cloud w/ Juju + Charms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying clouds can be tricky, but using deployment tools is a must. In this session, we'll learn how to deploy an OpenStack cloud using Juju and the OpenStack Charms. Go from zero to hero as we stand up a Newton cloud using the OpenStack charms.


* **Billy Olsen** *(Billy is a software engineer working in the Sustaining Engineering Group at Canonical.)*
