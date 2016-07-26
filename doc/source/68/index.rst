Operations War Stories
======================

Things you MUST know before you deploy OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Real world lessons and war stories about Catalyst IT’s experience in rolling out an OpenStack based public cloud in New Zealand. This is an opportunity to learn first-hand about useful techniques we have used to increase service levels, perform in place upgrades and how the cost of your own OpenStack cloud compares to Amazon AWS.


* **Bruno Lago** *(Bruno Lago is a solutions architect that has been involved with the Catalyst Cloud (New Zealand’s first public cloud based on OpenStack) from its inception. He is passionate about open source software, cloud computing, disruptive technologies and always eager to share lessons learned from real world experience.)*

What I learned from running a cloud since Diablo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In 2012 we deployed our first productive OpenStack private cloud within SUSE and have continuously operated one since then, running the Essex, Grizzly, Icehouse and Liberty versions for quite a while and with positive results.


* **Bernhard M. Wiedemann** *(  1977 born in Berlin 1998 start studying computer science in Berlin 2005 finish studying 2010 code automated OS install testing (openQA) 2010 started working for SUSE in Nuremberg since 2012 work on OpenStack cloud packaging, CI and operations)*

Network Troubleshooting for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Here we plan to transmit some of our experience troubleshooting different scenerious that we have found in real life regarding OpenStack Neutron service. Learn from the experts: How to detect a duplicate IP? What are the points you need to check and how to troubleshoot the different pain points on an openstack environment? We will share experiences that has happened to us with our customers by letting you know how we detected and how we managed to solve them.


* **Jose Casimiro** *(Jose 'Kaz' Casimiro started using linux since 1994 and has been working at opensource enterprises such as Rackspace and Red Hat doing a wide variety of IT roles including: instructor, developer, sysadmin and support engineer. He currently works at Rackspace as an OpenStack Engineer.)*

* **Kent Wolfe** *(Kent Wolfe is a Red Hat Certified Architect who currently works for Rackspace Hosting Inc. as an OpenStack Engineer. His professional interests include troubleshooting a wide range of technologies surrounding Linux and OpenStack. In his previous role, Kent enjoyed mentoring new administrators and serving as an escalation point.)*

* **Carlos Martinez** *(Carlos Martinez is a Openstack Engineer who has done a lot of troubleshooting on Production Openstack Environments, with 8 years of experience as a Linux Engineer)*

Container based Auto Deployment and Intelligent Operation for private cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As we known, there are strong demands to deploy and operation for private cloud. And it’s a challenge to make the deployment fast and operation automatic. In kylincloud, we did lots of work to accomplish these goals. The following topics will be covered in this presentation: How we accomplish the goal to quick deployment for private cloud for different requirements from various of clients. The technology details for Intelligent Operation based on container. Practical experiences on deployment and operation.


* **Yusong Tan** *(Dr. Yusong Tan is the CTO of Kylin Cloud. He focuses on cloud computing and big data processing technologies. Currently Dr. Tan leads one group to deploy and optimize OpenStack on TianHe-2 supercomputer of Guangzhou National Supercomputer Center. Dr. Tan had leaded some high-technology research projects founded by China government.)*

Deploying OpenStack, Astara and Ceph: from concept to public cloud (and hell in the middle)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When DreamHost started developing, deploying and selling cloud services in 2011, the team embarked in a life-long learning effort, full of obstacles and with the promise of a wonderful destination. DreamHost ventured in uncharted territory betting on young and promising open source technologies: OpenStack, Ceph and Astara. Observed from the distance, DreamObjects and DreamCompute appear as mature products powered by solid Continuous Integration and Deployment, leveraging Chef, Jenkins, Jenkins Job Builder, and fpm. But looking back at the journey log, DreamHost team has collected lots of stories to tell: there was a time when we had to summon dozens of engineers from 4 companies to debug crashing SSD disks; and another time when our TechOps folks had to defeat snow blizzards. Pioneers’ trips are never easy but their stories are rewarding. Join this session to learn how DreamHost team has architected  OpenStack, Ceph and Astara to power the DreamCloud products.


* **Jonathan LaCour** *(Jonathan has been in the world of software since 1997, when he started writing Medical Records software at an early stage startup with an esoteric programming language called "Python." Jonathan harnessed his passion for user experience in the computer science program at Georgia Tech by taking courses in psychology, cognitive science, and education. Armed with this interdisciplinary experience, Jonathan is keenly aware of how people learn and solve problems. HIs early experience with Python also saw Jonathan nominated and accepted as a Fellow in the Python Software Foundation. In 2007, Jonathan helped found ShootQ, a cloud-based studio management solution for professional photographers, where he served as CTO. In 2010, ShootQ was acquired by Pictage, where Jonathan served as the Vice President of Software Products. Jonathan joined DreamHost in 2011 as Vice President of Software Development, bringing with him his experience and knowledge running engineering and product teams. In 2012, Jonathan became DreamHost's Vice President of Product and Development. In 2014, Jonathan took over the Cloud business unit at DreamHost as the Vice President of Cloud, and now serves as the Vice President of Cloud and Development. During his time at DreamHost, Jonathan has led the development and operation of DreamObjects and DreamCompute, which are publc cloud storage and compute services built on top of OpenStack and Ceph. Jonathan also was involved in the creation of Inktank, which developed the Ceph software defined storage project, and was eventually sold to RedHat. Jonathan also co-founded Akanda, the network services virtualization company behind the OpenStack Astara project. When not hunkered down behind his laptop, Jonathan loves spending time with his beautiful and brilliantly creative wife, Lacey, his daughter Colette, his son William, and their two dogs, Winston and Nelson. Beyond his culinary interests, Jonathan spends Saturday afternoons in the fall rooting for his alma mater and the University of Miami and enjoying his favorite southern creation - bourbon.)*

* **Stefano Maffulli** *(I have built my career around Free Software and open source: from pre-sales engineer and product manager at Italian GNU/Linux distribution MadeInLinux to Italian country director of the Free Software Foundation Europe. Under my watch as community manager at Rackspace and at the OpenStack Foundation, OpenStack became the fastest growing open source project. My daily job as Director of Cloud Marketing and Community at DreamHost keeps me busy growing the community of app developers on the Open Source cloud. In my spare time, I sail small boats in the shark infested, choppy San Francisco Bay.  )*

* **None None** *(None)*

Patching 100 OpenStack compute nodes with zero-day patch within 16 hours
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Undisclosed vulnerabilities are very serious threats to the cloud security. Once the flaw leaks to the public information, the risk of attacks increases dramatically. Because of that, it is crucial to apply zero-day patches in cloud environment as fast as possible and transparently to the end user. In our talk we will go through case study of applying zero-day patch on 100 OpenStack compute nodes running 4000 virtual machines within 16 hours. We will talk about the challenges we have encountered and how we dealt with them. Additionally, we will present how patching process using live migration affected the workload running inside of the virtual machines. At the end we will answer the most important question – did we make it within 16 hours.


* **Kamil Szczygiel** *(Kamil is a Cloud Solutions Engineer at Intel. His adventure with OpenStack started with Grizzly release. He loves mixing the automation with the cloud. He has a background in Ansible, OpenStack and VMware. Kamil spends his free time with his family, gaming or watching television series.)*

* **Pawel Koniszewski** *(Pawel is Software Engineer at Intel involved in OpenStack since Folsom release. He started his adventure with clouds developing a SLA plugin to nova-scheduler. Currently he works full-time on the upstream OpenStack activities, with primary focus on “Win the Enterprise” effort. He is a member of nova team and a member of live migration subteam. Apart from that Pawel is interested in performance optimizations. In his free time he loves to ride a bike and travel over the world.)*

* **Patryk Wolsza** *(Patryk is a Data Center Architect in the Intel Cloud Platforms Group, with a focus on Software Defined Infrastructure. With more than 12 years of expertise in different virtualization and cloud platforms, Patryk has broad experience in cloud solutions, system designs, influencing data center designs and understanding connections between ordinary Data Centers, virtualization and SDI. He believes that mastering the purpose of existing cloud solutions is the key to deliver and maintain the complete product, hardware and software, for any demand.)*

Troubleshooting Neutron: Physical and Virtual Networks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron has become much more mature in recent cycles, but challenges remain. Having an effective troubleshooting game plan is key. In this session, we will look at how to solve common Neutron issues such as: connectivity issues among instances connecting to instances on the associated floating IP SSH working only part of the time application struggling to transfer large payloads even though it has network connectivity  


* **Mohammad Itani** *(Expert with Networking and Data Center Architecture and Troubleshooting. Escalation Engineering for IAAS managed by OpenStack. Testing IAAS Architectures around OpenStack solutions.)*

* **Lida He** *(Lida He is a cloud solution architect at EMC Corporation. He has been developing OpenStack based cloud solutions including VxRack Neutrino, a hyper-converged multi-service cloud native solution, and has been helping customers to design IaaS and PaaS to support third platform applications in a wide variety of environments. He also worked on OpenStack monitoring solution for availability, performance and chargeback, and was involved with developing cinder drivers for some industry leading storage products. In addition, he has been actively involved with deploying Cloud Foundry on OpenStack and developing applications on top of it. He is inspired to become an active contributor to the OpenStack projects and community.)*

* **Diego Casati** *(Diego is currently working as a Corporate Systems Engineer  within  EMC’s Advanced Software Division  where he have the privilege to interact with various engineering teams, helping customers to get the most out of their clound computing systems. His previosly worked in the Telecom and IT industries as a Network Engineer, Systems Engineer, Customer Support Engineer,  Systems Integration Engineer and as a Web Security Specialist. On his spare time, he enjoy's learning more about OpenStack, BSDs and reading about sci-fi.    )*

BrokenStack: OpenStack Failure Stories
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We have all heard the stories of overcoming the trials and tribulations of OpenStack and emerging into the glistening dawn of a new Cloud day.  But what about the ones who didn’t make it? What about the ones who awakened not in the bliss of Cloud Nirvana, but in the depths of Cloud Hell? What went wrong? What can we learn from these failures? How can we ensure that we do not suffer the same fate? For answers to these questions and more, attend “BrokenStack: OpenStack Failure Stories.”  


* **Jonathan Kelly** *(Jonathan's first exposure to OpenStack was as an attendee at the Bexar summit.  He was one of the initial engineers on Rackspace's Openstack Private Cloud team, and has been working on OpenStack in one capacity or another since then.  He has experience within the OpenStack private cloud space as a System Engineer, Systems Architect, Product Manager, and most recently as a Solutions Architect.  He currently works for the MetaCloud organization within Cisco.)*

The way of telemetering: How we land Ceilometer in real world
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceilometer provide a unique point of measurements and events data from other projects of OpenStack for upstream users. The use casese can be: resource metric statistics reports, billing, infrastructure service monitoring, alarming, trend analysis for capacity planning, events history auditing, root cause analysis. In the real world, we have met some problems when using Ceilometer. This presentation want to show you the improvements in deployments, in configuration, even in code level. We have a public cloud is based on a OpenStack deployment with more than 1000 hosts, during the real operation, how to ensure the efficiency of metric data recording and query? how to ensure the metric data accurate and reliable? and how to ensure the alarming service accurate and prompt? This presentation will share you what we have met in operation, what we have done of Ceilometer improvements and what we will try in future.


* **Sheng Liu** *(Devoting to OpenStack community contribution, especially in Ceilometer(renamed to "Telemetry" now) project, Sheng Liu have done well in code commit, code review, community involvement to improve Ceilometer capability, stability, usability, etc. In 2015.9, Sheng Liu has been proposed as a core contributor of Ceilometer project. In the last 2+ years working for Huawei, Sheng Liu have also participate development works of Huawei's FusionShpere OpenStack product, and mainly involved NFV scoped features in Nova, such as Numa instance, SRIOV support.)*

800 hosts, a solid sandbox to run crash tests
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Huge infrastructure leads to huge problems! With public cloud, you need to manage thousands of bare metal servers, the problems you will encounter then are totally different from those with a rather small infrastructure. The best way to avoid failure is to fail constantly. With such matters you cannot learn by playing with toy models, we thus had no other choice but to run a real scaled infrastructure, call our crazy monkeys to crash the system and unplug different components, both hardware and software. During this journey, come with us to learn what we discovered, what we fixed and how we improved our recovery time to prevent new crashes. There was born our Crash Test infrastructure with more than 800 physical hosts.


* **Arnaud Morin** *(I am a devops at OVH. I am mostly involved in deploying OpenStack for the public cloud infrastructure at OVH. At OVH, we love automation, what could be better than automate a huge OpenStack deployment? Deploy other ones!)*

How to skip OpenStack releases
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Stability vs innovation is the dilemma facing enterprise IT organizations today. OpenStack's six month release cycle is great for driving innovation and delivering new functions, but it does not always fit well within the systems operation model of an enterprise. In this session, we will explore one path that enabled us [XXX, waiting for approval to name the company] to take a production OpenStack environment based on Juno and upgrade it to Liberty with minimal disruption.


* **Vincent Untz** *(Vincent Untz is an active Free Software enthusiast, involved since more than ten years in high-profile projects such as OpenStack, openSUSE and GNOME. His interests range from technical topics to organizational areas of the communities. He has held several leadership positions throughout the years: GNOME Foundation director (2006-2010) and Chairman (2009-2010), GNOME Release Manager (2008-2011), as well as Chairman of the openSUSE Board (2012-2014). Vincent is currently working at SUSE as senior project manager for SUSE OpenStack Cloud.)*

How OpenStack Cloud helped Transform iLayers Service provision
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

iLayer has been providing Cloud Services to it's clients in Europe for many years. Being firmly committed to Open Source solutions this infastructure was initially built using IBM Hardware and SUSE Linux Enterprise Server capabilities, such as KVM. One massive limitation of the environment that we built was the Self Service aspect of cloud that has become a key capability for service provision, also the administration burden on iLayer to manage the environment reduced the productivity of our delivery model. With the advent of OpenStack we have been able to move from this highly intensive, mangement heavy environment offering limited customer autonomy to a much more poweful Infrastructure as a Service allowing us and our customers to gain. Join us and discuss how our journey to an OpenStack Cloud helped.


* **None None** *(None)*

One control plane to rule them all:­ Managing physical and  virtual infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Real production experience using Ironic is scarce­­ and it's even more scarce when combined with Nova for VMs. The general problem is the need to provide a single API layer and portal for managing bare­metal servers and virtual machines in a data center to make end­users' lives easier and even moreso in the multi­datacenter use­case when you either need to have single control plane to manage them all or share permissions across multiple OpenStack deployments. Additionally, users need to provision servers for their apps with an easy-­to­use virtualization layer. We will share our experience at Symantec in using Ironic and Nova in a single OpenStack deployment to enable both cases.


* **Alexander  Sakhnov** *(Alexander Sakhnov is a Senior Software Engineer working for the Mirantis Services department. He has been with Mirantis for more than 6 years, and joined the OpenStack community from the very beginning of the Cactus release. His main activity is helping customers with production OpenStack deployments.)*

* **Mykyta Gubenko** *(Mykyta Gubenko is a Deployment Engineer at Mirantis working for the Services department. As an experienced system engineer, he helps Mirantis customers to be successful with Openstack. Mykyta is focused on deployment automation and large-scale openstack projects.)*

Performance Analysis and Results for OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Workday is running OpenStack in production for over the last six months. During the testing and pre-production time a huge amount of performance tests were executed in order to understand the limits of the cloud based on the architecture and hardware configuration. In this session we will share our numbers and what is even more important how we measure and what we have changed to obtain the best performance possible for our cloud.  If you ever wonder what are the limits of your cloud and how to calculate them, this is a session that will provide benchmark information of a production cloud and how the cloud operations team collected that information and even better what has been done to improve the overall performance and what bottlenecks were found.


* **Edgar Magana** *(Edgar is an emerging leader who has specialized in Cloud Computing, Network Virtualization, Software-defined Networking (SDN), Network Functions Virtualization (NFV), OpenFlow and OpenStack. He has developed excellent software development skills and outstanding customer and business driven experience. Currently, he is core member of the Neutron OpenStack development community. Edgar has strong experience in fully automated Cloud Computing deployments by means of puppet and chef orchestration languages. He has lead OpenStack development, third-party integration and deployment teams for over the last three years. Edgar is the lead architect responsible for driving the Cloud Operations initiatives that maximize the pace of innovation with Development and Operations. He is in charge of provifing architectural oversight for Workday’s Hybrid Cloud including the OpenStack based Private Cloud, bursting to multiple Public Clouds and extensive automation. Through strong collaboration, develop architectures, detailed designs, and in some cases POCs to support Development driven features requiring changes to the infrastructure.Establish tight alignment with Development Architects, representing Cloud Operations in the Technology Architecture Group. Edgar has an extensive experience on Cloud and Grid Computing, Policy-based Management Systems, Monitoring and Scheduling of networking and computational resources on distributed networks. He has been involved in multiple projects such as Cisco Quad, Cisco Enterprise Policy Manager, Access Control Server and Application Performance Assurance.)*

Tales from the field: Openstack problems and solutions from user's point of view
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, we will demonstrate real world OpenStack problems that are faced by our users. These problems result from high load, hardware capability and massive scale outs. We will focus mainly on problems encountered in Nova, Neutron, Cinder, Glance, MySQL Galera and RabbitMQ. We will also go over the solutions and workarounds that we have implemented in customers' environments and proven to work. Moreover, we will offer a concentrated knowledge base resulting from a few months of actual escalation experience.   This session will help attendees address their openstack issues quickly and efficiently thus reducing frustration and troubleshooting time. The solutions proposed are based on real scenarios that we had seen at various customers’ sites and proven to work.


* **Rabih Majzoub** *(Rabih is a senior systems engineer working for EMC Canada for the last 5 years. He spends his time on helping EMC customers with their openstack deployment as well as troubleshooting and resolving any issues that might arise. He also helps with automating some of the deployments by writing python and bash scripts. Rabih is a active member within the EMC community and the cloud world fascinates him. He currently live in Vancouver, Canada.)*

* **Yassir Laraki** *(Software development and Telecom Engineer, with 12 years of hands-on experience in Solution Architecture and System Integration roles, providing technical leadership in large scale/comprehensive projects.• Have demonstrated expertise in the Integration of best practices to assure the delivery of business services at promised levels, improve operational efficiency, and optimize the resources. • Excellent ability to leverage existing functionalities and integrate/bridge multiple platforms and teams to offer innovative and creative solutions.• Have advanced understanding of Wireless and Wireline Networks as well as the Layer 1, Layer 2 & 3 architectures and their services. • Experience in converged Infrastructure based on Openstack and ScaleIO. • Excellent knowlege in supportig and troubleshooting cloud environments: Hw, Software (Linux), Network, Openstack, Docker, Database)*

* **Todd Robbins** *(Hi, I am Principal Software Engineer working at EMC Corporation with 10+ years experience. I provide escalation engineering for VxRack Neutrino. Neutrino is OpenStack deployment that allows for turnkey IaaS.)*

The nightmare of Ironic Standalone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic is the Bare Metal provisioning service of OpenStack project whose role and features will be quickly reminded first. One aspect of Ironic is that it can be used standalone, without the other OpenStack component. So we proposed that approach to one of our customers who had that use case. However, when you want to do that to control UEFI based servers using an ilo-agent, on non yet released platforms, then the nightmare begins ! You first need to understand how all that works, and there is lots of developer docs but much less operation ones. And then you deal with areas much less tested so you have to report bugs, provide patches, contact some key developers in order to make it work. With Bifrost, will we be able to transform our nightmare into a dream for our customer ? Come to this session to know. Simple recorded demos will be displayed in order to illustrate the different aspects covered during the presentation.


* **Bruno Cornec** *(Bruno Cornec is Engineer of the French Ecole Centrale de Lyon. (1987)He has been managing various Unix systems since 1987 and Linux since 1993 (0.99pl14).Bruno first worked 8 years around Software Engineering and Configuration Management Systems (Build systems, Quality tools) in Unix environments.Since 1995, he is Open Source and Linux (OSL) Technology Strategist and Evangelist, initially for an HPE reseller and since 2000 for Hewlett Packard Enterprise directly in the EMEA Customer Innovation Center. Bruno is also HP WW Linux Community Lead, OSL Advocate, Helion MVP and RHCE. Bruno is a contributor in various OSL projects: MondoRescue (2001), Mageia (2003), LinuxCOE (2006), Pause (2007), Tellico (2008), FOSSology (2008), collectl (2009), Ironic (2015), python-redfish (2015). He is also project leader for MondoRescue (GPL disaster recovery solution, 2005), dploy.org (GPL deployment server, 2006), project-builder.org (GPL build service, 2007), UUWL (LGPL/MIT Unix to Unix Wrapper Library, 2011), PUSK (GPL ProLiant USB Setup Key, 2012), python-redfish (2015). He is a member of the Solution Linux/OWF/POSS Conference Board since 2006.He is also a board member of the AFUL and OpenStack-fr associations. As part of his work he has made numerous presentations for Solution Linux in France, Libre Software Meeting, NordU, Linux World UK, Linux Expo Milano, Linux.Conf.au, OSCON, Linux Symposium, Fosdem around various topics (High Availability, Deployment solutions, System management, Disaster Recovery, Package building, Cloud...) Outside computers, Bruno also likes early and baroque music, singing and playing the recorder. He's married and father of 3 kids.)*

* **Gallig Renaud** *(Gallig is a Hewlett Packard Enterprise Technology Strategist)*

Heat Optimization
~~~~~~~~~~~~~~~~~

**Abstract:**

Dive in detail about a big task in Heat: To optimize application experiences in OpenStack. This task aim to provide datacenter ready Orchestration service on OpenStack and make heat, murano, sahara, tripleO and anyother services (who uses heat) to have trusted and stable Orchestration over cloud.


* **Rico Lin** *(Rico Lin,  Heat core member since Liberty, Chief OpenStack Technologist, inwinSTACK, the Lead of OpenStack team in inwinSTACK, which is a OpenStack service consultant company. Our team focused on OpenStack contributions and all relative projects development. Rico start working with OpenStack since Havana and start contribute to Heat project since Liberty. He led the effort of contribute to OpenStack from inwinSTACK and is passionate about OpenStack. Keynote Speaker in Austin Summit. Speaker for Vancouver summit, 2016 Taiwan Day and China Day.)*

* **Anant Patil** *(Anant Patil is Specialist Technologist at Hewlett Packard Enterprise and works primarily on OpenStack Heat Orchestration Project.)*

Start small think big - a journey from manual VPS to the cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We share our OpenStack journey: from a manual VPS provisioning to a growing self-service OpenStack cloud. We will focus on how we were able to start small but design for scale. We will cover the whole lifecycle of the service from design to deployment to operations. We'll share our lessons learned and give you some tips on how to get started with your own OpenStack cloud.


* **Maxime Guyot** *(I am a System Engineer passionated with cloud, devops and networking. I work in planning and deploying OpenStack clouds for a local public cloud provider.)*

Top Considerations for Operating Database as a Service in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Databases are a key component in the vast majority of workloads that are a great fit for OpenStack. Using Trove to easily dispense database instances in an as-a-service model is an attractive option for those deploying OpenStack. In this talk, we will open the “trove” of wisdom to discuss different facets of how to ensure successful deployment and ongoing operations of a Database-as-a-Service (DBaaS) offering within an OpenStack deployment.Attendees will gain insight into: Ideal use cases best addressed by leveraging DBaaS capabilities Important architectural considerations when designing the infrastructure for DBaaS Operational best practices in maintaining production DBaaS deployments Attendees should leave with improved knowledge around how to deploy and maintain production-grade DBaaS, as well as information about upcoming features in Trove that aim to improve the operator’s experience.


* **Bob Callaway** *(Bob Callaway is Director of Solution Architecture with Red Hat. He focuses on strategy, business development activities, and reference architectures that promote the benefits of Red Hat's market leading open source software offerings in cloud & middleware environments. Prior to joining Red Hat, he spent two years at NetApp as principal architect within the Cloud Solutions Group, and over 8 years in various roles within IBM focused on application integration middleware and cloud computing. He is an ATC on various OpenStack projects, and holds the PhD degree in Computer Engineering from NC State University. He also serves as an Adjunct Assistant Professor at NC State University. Bob has presented at the Atlanta, Paris, and Vancouver Summits on various OpenStack topics.)*

* **Doug Shelley** *(VP, Product Development at Tesora. )*

Integrated Distribution of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Distribution OpenStack have multiple shards deployment in different geography, these shards don't know each other.  This presentation introduce how to distribute workloads from end users to different shards and help end users operate OpenStack cloud with unified account management.


* **Shao Mei Ji** *(Shao Mei Ji joined in IBM cloud team since 2012.  As a team member，responsible for SCE, ICM, AccessTrail successively. Have rich experience in devOps, UI development , and openstack tempest.  )*

* **Hong Jun Tu** *(Hong Jun Tu is senior software engineer of IBM and worked in cloud team. Rich system architeture and development. Rich openstack skill and network, hypervisor tuning.)*

* **Wen Cheng Ma** *(Wen cheng ma joined ibm since 2013 and worked in cloud team. Rich in openstack community.)*

Telemetry: Practice In Large-scale Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We have a more than 300 nodes OpenStack enviroment. With scale came the challenges of operations and telemetry of this cloud. We enhanced our monitor system with ceilometer, aodh, zabbix and other monitoring software. We use independent message queue system to improve stability and isolation, and redesigned the way we record the metric and samples to deal with high concurrent queries and manage data life cycle. And change cluster form to improve the writing ability of database. Then we try to collect physical machine monitoring information with other software and send them to ceilometer for unified storage and preparing for alarm.


* **Chen chaozhe** *(Tech Lead and Founding Engineer from Easystack. He contributes primarily on OpenStack telemetry and trove Project, also works on Easystack billing system. Now his main responsibility is focusing on building monitoring and billing system for Easystack products. )*

Solution And Pit : Manual Deployment In Order To Solve Problem After Large-scale  Automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Manual deployment in order to solve problem after large-scale automation.For example, adjust the network architecture，adjust the storage architecture, to do something with the third party solution, solve the problem of the network, the storage, the bill and so on. All kinds of large-scale deployment scenarios，it is not easy for large-scale deployment automation.It requires the solution and keep away from the pit.


* **Ji Xuefeng** *(Leading to participate in designing the architecture of cloud computing platforms of the Ningxia electric power company，China, and lead to participate in implementing the customized deployment.(Has been running more than one year)(OpenStack) Leading to participate in designing the architecture of Lenovo ThinkCloud AIO S Series Hyper-Converged System and realize the cloud computing platform integrated optimization and automation of deployment.(OpenStack) Leading to participate in designing the implementation of the architecture of small and medium-sized enterprise cloud (1000 nodes up ),and lead to participate in implementing the customized deployment.(Project phase 1, 180 nodes)(OpenStack) Participate in implementing the customized deployment (Project phase 1) of cloud computing platforms of Samsung Institute in Beijing.(OpenStack) Participate in implementing the customized deployment (Project phase 1) of cloud computing platforms of China Education Television.(OpenStack) Participate in implementing the customized deployment (Project phase 1) of cloud computing platforms of clouds of AWcloud.(OpenStack))*

OpenStack journey and challenges of the BBVA storage team
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building a small OpenStack PoC Environment can be challenging for traditional IT teams but when you have to do a real production deployment to support your platform and development teams, new unexpected challenges come your way.  BBVA is the second largest bank in Spain and like many other big organizations BBVA is also on a journey to transform its IT. But, being a Bank BBVA has it's special hurdles as the stakes are way high. Today that BBVA is close to production readiness, we in this session will talk about how the BBVA storage team started its OpenStack journey and what kind of challenges they faced. We will discuss how the Storage team  overcame both technological and cultural challenges and what did they learn from these experiences. Then we will go on and discuss the architecture and use cases for the cloud deployment at BBVA and will focus on what kind of storage architectural decisions were taken and the reasons for such decisions. 


* **Jose Maria Ruesta** *(Global Head of ‘Engineering & Projects’ at BBVA, with over 25 years experience in technology management and transformation projects in financial markets.Having previously led the BBVA Global Technical Architecture team, his current responsibilities now include designing and implementing the Cloud infrastructure required to deploy the new BBVA scale-out architectures, based on commodity HW and OpenSource.Previous postions include a variety of executive responsibilities at BBVA such as Head of Global Technical Architecture, Head of LATAM Architecture, and lead a range of projects in the countries in which BBVA operates.)*

* **Luis Sanchez** *(Luis is the head of storage architechture and global deployement and BBVA. He has strong background and experience in Storage design and architecture in Enterprise IT.)*

* **Lourdes Peñas** *(Senior Storage Architect with over 19 years of Information Technology experience in diverse fields and disciplines: presales, support services and education for distributed systems, and a deep knowledge of the Storage/Data Management IndustrySpecialties:- Primary Storage and Data Services Solutions- Storage Virtualization Solutions- Data Protection Solutions- Business Continuity and Disaster Recovery Solutions- Storage Networking Solutions)*

OpenStack Storage Panel Featuring Customers and Field Architects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Please join us for a panel discussion featuring customers and field architects. The theme of the discussion will be the use of all kinds of storage in OpenStack - block (Cinder), file (Manila), and object (Swift). Some of the questions our panel will guide you through will include: What types of storage are these and other customers using? What workloads are benefitting from OpenStack storage? What were some storage design challenges encountered? What were some takeaways upon overcoming these challenges? What are some DO's and DON’T's for OpenStack storage? What are the cost savings and efficiency gains using OpenStack Cinder, Manila, and Swift? How have customers planned for disasters and backups? What public clouds are customers using?


* **Marc Koderer** *(Active contribuiter since 2013 with the focus on storage and QA for enterprise usage. Part of the OpenStack cloud inititive at SAP.)*

* **Paavan Shanbhag** *(Paavan works as a software engineer building some of the key cloud services at Platform9 Systems, Inc. Prior to Platform9, he spent close to 6 years working at VMware, where he has contributed to various cloud management products working across the VMware stack, mainly on ESXi and VirtualCenter platforms. )*

* **Ed Balduf** *(Ed Balduf is a Cloud Solutions Architect at SolidFire/NetApp, focusing on OpenStack, Containers and Agile Infrastructure. Ed wrote the SolidFire Puppet module, contributes to Cinder and container storage drivers. Ed has been working over 20+ years in technology, consulting and sales.  Ed is highly technical but has always chosen to work in roles involving interaction with customers and partners as he excels at solving new problems and knowledge sharing. Ed was most recently Sr. Staff Storage Architect with Fusion-io/SanDisk working with Hyperscale customers on scale out storage deployments. Ed lead Fusion-io’s technical efforts around OpenStack.     Ed has extensive history and experience in Fibre Channel, Real-time processing, NAND Flash, Training development and packet routing.)*

* **Kapil Arora** *(Kapil Arora is a Cloud Platform Architect at NetApp in the EMEA region. He helps customers with OpenStack proof of concept implementations and production deployments and focusses on innovation, evangelization, and promoting the benefits of NetApp storage and software in cloud computing environments. He has 9 years of IT indsustry experience including 6+ years in the Storage industry. Kapil is also an experienced Java programmer and has a Bachelors degree in Information Technology from Bharati Vidyapeeth College of Engineering, Pune.)*

* **Akshai Parthasarathy** *(Akshai Parthasarathy is a Technical Marketing Engineer at NetApp, working on all things OpenStack and cloud computing. He has over 7 years of experience in the technology industry, having previously worked at Amazon Web Services and Dell. Prior to that, Akshai obtained his Bachelors (with Highest Honor) and Masters from the School of Electrical and Computer Engineering at Georgia Institute of Technology. )*

Making OpenStack your own
~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack has a very programmable API. You can use this api to easily incorporate an openstack cluster into your current infrastructure. For example we used the openstack api to Under certain conditions sync users from Active Directory to Openstack. Manage our flavors through a yaml file to keep them uniform Create projects and resources from a yaml template.


* **Atze de Vries** *(I have a background in astrophysics and art. I've started operating Openstack 3 years ago. We then did our own deployment using Puppet. Our newer Openstack deployments are deployed with Fuel.  In my free time i like to do some alpine climbing and rock climbing. )*

Ops Log Book: Volkswagen’s Group IT Operations Team’s adventurous journey to the land of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Originally, the Group IT Operations team was responsible for managing infrastructure for the Volkswagen Group. The team operates central backend data centers, servers and core services for the Volkswagen Group - following a traditional Enterprise IT approach. Then, in Q3/2015 the Volkswagen Group IT decided to go with OpenStack for their new internal private cloud project. And the Operations team had an additional task and a new challenge: Bring OpenStack into production and run it. This was the day when the Group IT Cloud Operations team’s excellent adventure to the land of OpenStack and cloud began. In this session the team will provide insight into the challenges it faced, the solutions it found, and the day to day issues it experiences with clashes between the classic IT world and the new cloud world.  


* **Gerd Prüßmann** *(Gerd Prüßmann is a technical leader and Director Cloud Solutions at Mirantis Germany. He became an Openstack addict when Openstack Cactus was released. Gerd led developers' teams implementing Openstack and CEPH based production platforms since 2012. He is one of the Forces behind the German "Openstack DACH day" initiative. Gerd has a ~30 years track record in IT, software development and cloud computing. Prior to Mirantis, Gerd led technology creating companies, departments and teams and built up top engineering, operations and DevOps teams. He managed technology projects across various branches such as consumer goods, services sector, media and television, internet business, healthcare, transportation, construction, financial, biotech, industry and logistics.)*

* **Tilman Schulz** *(Tilman Schulz studied Mathematics at RWTH Aachen and University of London and earned a PhD in Mathematics of RWTH Aachen. He joined VOLKSWAGEN AG in 2002, where he was first responsible for a PKI project, after which he joined the Unix Team in 2005. Starting in 2011, he assumed responsibility for server operation. At present, Tilman is heavily involved in a VOLKSWAGEN Group private cloud project.)*

Tech refresh your production infrastructure. Rebuilding hypervisors while keeping the 9’s
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our oldest and largest OpenStack cluster has been running for a while and it’s been through a few OpenStack upgrades but there comes a time when the hardware and/or OS reaches EOL and needs to be refreshed. We have been given the task of re-imaging the entire fleet of hypervisors with minimal or no downtime to our users. This presentation will address some of the issues we have had with VM mass migrations and how we solved them. Preparation, cleaning to free capacity – No extra capacity was going to be available for the migration process Patching nova, backporting changes and CI for packages Testing – provisioning, integration, migration offline and online Communication to users Manual and automated migration, use of automation Impact of migrations on the infrastructure – from control plane to hypervisors and network Migrating XL flavors Bugs and Issues (timeout, missing image, libvirt bios, half migrated instances) Migrations and overprovisioning What have we learned


* **Gabriel Capisizu** *(Gabriel Capisizu is part of the Symantec’s Cloud Platform Engineering team. He has over 10 years years of experience with large scale distributed systems, Unix and networking.  Gabriel started with OpenStack in 2011 as part of PayPal’s cloud engineering. His focus is deployment automation, security and high availability within OpenStack.)*

* **Sergii Kashaba** *(Prinicpal Software engineer. Having more than 14 years of experience in different areas of software development. Now work closely with OpenStack, adopting it for large enterprise customers.)*

Upgrading Clouds with Fuel and Octane: AT&T's Diesel Project
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The AT&T Integrated Cloud (AIC) program faced a challenge of upgrading deployed Mirantis OpenStack clouds without migrating tenants and moving to a new reference architecture without redeploying from scratch.  Leveraging Octane, an open source project to upgrade Fuel nodes, the Diesel (Fuel + Octane) development team was able to create an automated procedure that would result in an upgraded OpenStack cloud. In this talk, the members of the development team explain their challenges, setbacks, and successes of achieving OpenStack upgrades.


* **Alexis Rivera De La Torre** *(Bachelor's Computer Science. Worked for a small startup (CrowdSource - now OneSpace) doing QA and Web Development. Started with AT&T in June 2015 and have been working both community work (mainly the Barbican and Horizon projects) and developing an internal cloud application to bring together monitoring, logging, metering, and other cross cloud metrics into a single dashboard.)*

* **Aaron McLean** *(I have been involved in software design and architecture for 17 years at AT&T as a Principal Technical Architect. I recently joined the Fuel/Octane team and am working working on upgrading our cloud using an in place update project called Diesel.)*

RabbitMQ at Scale, Lessons Learned
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operating RabbitMQ at large scale comes with it's own set of challenges. This talk will take you on the journey Cisco faced with operating a large (800+ node) environment inside a single RabbitMQ cluster. We will share the pains, lessons learned and best practices to stabilize and improve messaging performance and reliability. This talk includes: OpenStack service configurations related to messaging Kombu driver enhancements Considerations when virtualizing the control plane, and how default network buffer settings can be insufficient. RabbitMQ Erlang arguments related to TCP_USER_TIMEOUT and their impact The overhead of Queue Mirroring Kernel level network settings to improve RabbitMQ failover and provide faster service re-connect Alerting and Monitoring RabbitMQ Recovering from a cluster partition Architectural decisions 


* **Matthew Popow** *(Matt is a Senior Engieer working for Cisco Cloud Services. Matt has experience working on OpenStack since the Grizzly release, and focuses on quality engineering, operations, and release management. )*

* **Wei Tie** *(Wei is a senior platform engineer at Cisco Cloud Service, working on global OpenStack based cloud build, operation and optimization. Wei started his journey with OpenStack from Essex release and is actively working on stabilizing Icehouse and Liberty platforms.)*

* **Weiguo Sun** *(Weiguo has been working in IT industry for over two dacades. His past experience includes large scale database support on various unix platforms and high performance web farms. Since Grizzly and Havana releases, Weiguo has been a tech lead for the Cisco Cloud Services, focusing on the stability and scalability of Neutron / OVS / Rabbitmq and other backend services.)*

If I could go back: lessons learned after 4 years of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Constant Contact began building its private cloud with the OpenStack "Folsom" release in early 2013. Today, the majority of Constant Contact's web services are now hosted on OpenStack. Nearly 4 years and 7 releases later, our small team of operators has accrued a long and colorful list of practices, stories, and regrets. This talk is directed atÂ our past selves, still in theÂ planning process, and looks back at what we got wrong, what we got right, andÂ applies lessons learned to our future plans. To support a continuously growing cloud with a small team, we've been pragmatic about which services to provide, done extensive work to integrate OpenStack with our existing infrastructure, and designed a deployment that exaggerates our team's strengths. The resulting cloud may not be conventional, but it meets our needs and is low maintenance.


* **David Arroyo** *(None)*

DevOops: Lessons Learned From a Cloud Network Architect
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

No one said networking was easy. Toss in Neutron with its dozens of configuration options, features and sometimes questionable documentation, and you're bound to have a hard time. Join us as we discuss some of the 'gotchas' that one will encounter when architecting and operating OpenStack clouds at both small and large scale. Participants will learn which OpenStack cloud networking technologies offer the most promise and which ones to avoid in the short and long term.  


* **James Denton** *(James Denton is a Principal Network Architect for Rackspace, and has been involved with OpenStack as part of the Rackspace Private Cloud team since 2012. He is the author of "Learning OpenStack Networking (Neutron)" released in 2014, "Learning OpenStack Networking (Second Edition)", and "OpenStack Networking Essentials".  )*

* **Jonathan Almaleh** *(Jonathan Almaleh joined the Rackspace Private Cloud team in 2014, and has been architecting and building fake networks ever since.)*
