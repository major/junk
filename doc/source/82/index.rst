Upstream Development
====================

The challenge of running OpenStack on AArch64
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running OpenStack on a new architecture for which archives are not fully built is challenging. At Linaro we started building packages for OpenStack and trying to build a developer cloud based on OpenStack a while ago. This session is about what we learnt, what we’ve done and what is left to do. We’d like to contribute gate jobs for AArch64, make sure the main distros include the relevant packages to be able to run OpenStack on this architecture and ensure developers out there get access to it to be able to debug/fix any issues in the most architecture inclusive way. We are also making sure that OpenStack on AArch64 is interoperable with other clouds.


* **Gema Gomez-Solano** *(I like to make software better, that is essentially how I became a quality engineer and a technical lead. OpenStack and Software Defined Infrastructure has been the main target of my work for the past few years. As the SDI Tech Lead at Linaro I am working closely with many different upstream projects and stakeholders to ensure a good user experience of OpenStack on AArch64. )*

* **Marcin Juszkiewicz** *(Long time ARM/Linux hacker. Moved to AArch64 (64-bit ARM) as soon as it was possible. Handled build failures in several build systems and distributions.)*

* **Jack He** *(I work for ARM. I am also an Linaro member engineer. I am mostly focused on making OpenStack work smoothly for AArch64.)*

DELIMITER - Cross Project Quota Enforcement and Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Quotas are frequently used and the same time complex piece of code that most projects in OpenStack(Nova, Cinder, Neutron) needs for proper usage and management of resources. Any project which plans to impose restriction on resource consumption would have the need for quotas functionality in near future. So given that even though quota is a common requirement there is not a common entity at present which enforces quota where as the approach taken by OpenStack is to have every project build its own quota framework  needed to enforce and manage quotas. Hence, this is an attempt to build a common entity so that new and existing projects can seek benefit from it. None of the Openstack projects that enforce and manage quotas seem to be happy about the way the Quota implementation is done for respective projects and through various mailing list discussions & project meetings its clear that some effort to fix the existing implementation would definitely help the project. 


* **Vilobh Meshram** *(Openstack developer focussing on Compute(Nova), Containers(Magnum), Distributed Group Management and Locking(Tooz) projects. Interested in distributed systems, distributed co-ordination and anything related to concurrency. Based on the contributions till date received the OpenStack Contributor Award from OpenStack Foundation @ OpenStack Summit Austin! Details http://superuser.openstack.org/articles/openstack-community-contributor-awards-recognize-unsung-heroes Presented 4 talks at OpenStack Summit at Austin 2016. 1. How we keep breaking the Compute Scheduler at Scale! - https://goo.gl/NaLK4r  2. How Yahoo! Plans to Maximize Resource Consumption! - https://goo.gl/hLavC4  3. Openstack Scheduling and Resource Management - https://goo.gl/a9UIRU    4. Quotas in OpenStack – Present and Future! - https://goo.gl/DNVf7q  Have been heavily involved inside Yahoo! to make OpenStack work at Scale. Using the experience to work at Scale by proposing new specs, blueprints that will help the community. Collaborated with CERN, HP, IBM, LSD-UFCG on Quota related efforts.   First one to introduce Nested Quota to OpenStack via Cinder. Introduced Consul driver to Tooz which will be used for DLM.)*

Anatomy of an OpenStack distro
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack development process rarely finishes when code is tagged for a release. Throughout the life cycle of a release, OpenStack distributions package, maintain, test, and turn OpenStack into a product that’s easy to consume by a large variety of users on their favorite operating system. In this presentation, you’ll get an inside look at the work that goes into shipping a stable OpenStack distribution on the same day as the upstream release. We will explain how the RDO community distribution continuously packages OpenStack from source, how we test it and how we ship it. We will share our experience, our challenges and how we overcome them in collaboration with the OpenStack community.


* **David Moreau Simard** *(David is a Senior Software Engineer in the RDO engineering team at Red Hat where his efforts are around empowering the community to deliver a reliable OpenStack distribution. He brings his expertise around operations, infrastructure, tooling and CI to ensure RDO is the most stable OpenStack packaging distribution. Previously, he was at iWeb, a server and datacenter infrastructure provider where he held various technical and leadership roles in the span of nearly a decade. In the last years, his focus was around deploying and supporting a highly available multi-region OpenStack public cloud in different datacenters around the world.He holds a blog on https://dmsimard.com where he shares articles about what he learns and his interests.)*

* **Francisco Javier Peña** *(Javier has been involved in the creation of solutions based on Open Source components for more than ten years. Before joining the OpenStack Engineering team at Red Hat, he helped customers design and build clouds based on OpenStack. Now he is contributing to the RDO community by working on the continuous packaging pipeline, the OpenStack Puppet modules and Packstack installer, and he is also involved in the definition of highly available architectures for OpenStack deployments (https://github.com/beekhof/osp-ha-deploy/blob/master/HA-keepalived.md).)*

How to move toward Keystone v3: Neutron case-study
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Keystone is at the heart of an organism called OpenStack. Without it, it would be difficult to live. That's why it is important to know how to react to changes that arise from the minds of Keystone developers. Among many important changes in the v3 API for Keystone, like groups and domains, we can see the migration from the old term "tenant" to focus instead on "project". It can be painful to understand and further debug this, having become accustomed to the old usage and meaning of the term. Neutron decided to be compliant with this change and update all references to get rid of the deprecated term "tenant". Something that initially was thought to be a pretty straightforward update, turned out to be a very complex and time consuming venture. If you want to hear what kind of issues were encountered, what kind of obstacles can be expected, and if it's even worth it to pursue this goal, you'll hear all these things in this talk.  


* **Darek Smigiel** *(Dariusz started his journey with OpenStack in December 2014 and his first contribution upstream was in March 2015. Originally worked on TripleO with Ironic, where he improved the installation process. Dariusz started woking on the Neutron Project in October 2015. He is currently implementing Keystone v3 compatibility changes. Dariusz also has experience with other OpenSource projects and cutting-edge features in an advertising clearance system. In the spare time, he gives a talks about Python at conferences and with local communities.)*

* **Henry Gessau** *(Henry Gessau is a core reviewer for Neutron. He is the database 'lieutenant' for the project, and has also contributed to IPv6 features, project testing enhancements and the effort to move third-party (vendor) code from neutron into separate sub-projects in the Neutron stadium. Henry has worked in the networking industry for many years, but his passion lies in software design and development. After using C for decades, Henry is now a big fan of Python. He has lived in several countries and loves visiting new destinations.)*

Scenario tests, Tempest, CI and other beasts in the Sahara world
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Releasing working software artifacts is always a challenge. Releasing a huge set of projects like OpenStack increases the difficulty. Luckily, the quality assurance (QA) project has been one of the pillars of OpenStack since its inception. Still, quality is really a shared responsibility in the OpenStack community, and each project should work with the QA team to actively follow, use, and locally adapt the testing tools and guidelines.In this talk we’ll show how testing is organized in the Sahara world and performed in Sahara’s continuous improvement (CI) system. We’ll discuss the reasons for the creation of the separate Sahara tests repository and the new capabilities it allows. We’ll also share the design of the scenario tests framework itself (end-to-end), and we’ll talk about the consolidation of the Tempest-based and other high-level testing artifacts for related projects.


* **Luigi Toscano** *(Luigi is a Senior Quality Engineer on the Red Hat OpenStack Quality Engineering team, with focus on Sahara (and previously Trove). Free-as-in-speech-Software enthusiast since last century, FSFE Fellow, he is contributing to different open source communities including KDE. He is also co-maintainer for the Sahara tempest tests, a member of core reviewers team for the "sahara-tests" repository.)*

* **Evgeny Sikachev** *(Evgeny has been working with OpenStack Data Processing (Sahara) on position Automation QA Engineer. He has been implementing the initial version of sahara-scenario which then has been moved to the main sahara-tests repository. He supports Sahara benchmarks for Rally project and is now responsible for Sahara scale testing activities in Mirantis. Evgeny has also been participating in the managing process of Sahara-CI.)*

* **Vitaly Gridnev** *(Vitaly is Software Engineer working with Mirantis. He is a core upstream contributor, Project Technical Lead, and downstream productization for the OpenStack Data processing service (Sahara), which provides Big Data cluster management and Elastic Data Processing in OpenStack. He has contributed to OpenStack since the Juno release.)*

Continuous Packaging, the next step after CI and before CD
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We are used to the concepts of Continuous Integration and Continuous Delivery and how they’re applied to our daily work on OpenStack. However, we tend to miss the importance of packaging, even though a large amount of the current OpenStack deployments are done using packages rather than source. Enter the world of Continuous Packaging, where every commit to your OpenStack project gets automatically packaged and tested.This allows for early detection of new dependencies and issues and enables Continuous Delivery, the packaging way.


* **Francisco Javier Peña** *(Javier has been involved in the creation of solutions based on Open Source components for more than ten years. Before joining the OpenStack Engineering team at Red Hat, he helped customers design and build clouds based on OpenStack. Now he is contributing to the RDO community by working on the continuous packaging pipeline, the OpenStack Puppet modules and Packstack installer, and he is also involved in the definition of highly available architectures for OpenStack deployments (https://github.com/beekhof/osp-ha-deploy/blob/master/HA-keepalived.md).)*

* **Daniel Mellado** *(Daniel is a software engineer at Red Hat contributing to OpenStack's Tempest and RDO. He's passionate about networking, development, and messing around with python and deployment tools! He holds a MSc Degree in Telecommunications from Universidad Carlos III de Madrid and has been part of a research team in T-Labs.)*

Effective Code Review
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Developers usually state that finding defects is the primary motivation for doing code reviews. However, research has shown that the main benefits of code reviews are; knowledge transfer, team awareness and finding alternative solutions. Code reviews when done well are more than just finding defects; it should be a discussion and conversation with other developers about finding the best solutions. We will talk about re-framing code review to encourage open discussions. This talk is for everyone that is already involved in regular code review and those hoping to start. I will talk through the code review process with the aim of making it a better and more useful experience for both the authors and the reviewers.


* **Dougal Matthews** *(  Dougal is a Pythonista based in Glasgow, Scotland. He runs the local Python user group and regularly attends and organises community events. In OpenStack he primarilly works on TripleO and Mistral.)*

From Tempest to Neutron - Test migration from Tempest to OpenStack Projects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack keeps growing and there's an unknown number of yet-to-come related projects, there has been a need to move API and Scenario tests from Tempest to their own projects, using tempest.lib and its stable interfaces in the process. One of the main advantages is that tests are now tied to their projects and the reviews could be directly done by developers with deep knowledge about their project, making the review process more efficient and fast. However, this process has also been proven to be challenging, as the migration implies being familiar with three key elements: Tempest Plugin Tempest.lib Stable Interfaces The OpenStack project itself In this talk we'll: Describe the current status Talk about the advantages of moving test to projects, and how to handle that Describe a real-life example about how this has been done for Neutron scenario tests and how we'll apply that experience to other projects


* **Genadi Chereshnya** *(Openstack Networking Senior QE Engineer)*

* **Itzik Brown** *(Openstack Networking Senior QE Engineer)*

Mutable config and you
~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Mutable config is the ability to reload configuration (also logging configuration!) at runtime without a service restart. It is live in Nova Newton and I need your help to enable more projects and options. This talk will introduce the feature and walk through the patches required to take advantage of it in your project.


* **Alexis Lee** *(Alexis has been working on OpenStack for Hewlett-Packard Enterprise since 2013, helping to maintain and package Nova for Helion OpenStack. He has been working on OpenStack since Grizzly and helped maintain HP Public Cloud. His current focus is on Oslo, producing features to benefit the whole community. Ask him to play a game.)*

Lightning Talks
~~~~~~~~~~~~~~~

**Abstract:**

Share you knowledge with your fellow upstream developers! Lightning talks here can be anything from a neat feature your editor has which allows contributing to OpenStack easier. Maybe there is a lesser known OSLO library that you know would excite a wider audience. You could also have a neat documentation tool that would get the audience putting on their fancy socks!


* **Mike Perez** *(Mike Perez has been contributing to OpenStack since 2010. He is currentlythe development coordinator at the OpenStack Foundation focusing oncross-project initiatives, and a member of the OpenStack TechnicalCommittee. He was formerly the project technical lead (PTL) of theOpenStack Block Storage project Cinder for the Kilo and Liberty release.)*

Perform schema rolling  upgrades in just one release cycle
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Reliable Openstack deployment should be as close to 100% availability as possible and always up to date with the latest release. To achieve this, during an upgrade services should be stopped and replaced with new one with noAPI downtime. In projects like keystone, glance or neutron this means keeping compatibility of DB schema between releases. The complexity of maintaining this compatibility, while keeping performance and security on a high level, is a hot topic in the community. Current approach in projects like nova or cinder requires keeping the data compatibility for 2 or 3 releases. In this presentation we want to show solutions, how to reduce the data migration time period to one release cycle. This would reduce the code complexity and performance overhead in database layer.


* **Artur Korzeniewski** *(Artur Korzeniewski is a software engineer at Intel, currently working in Neutron community on subjects related to upgradability and HA of services. He is Neutron Upgrades team member, dedicated to improve the process of upgrade. Before joining the Neutron team, he was closely coupled with OpenStack since Diablo release, working on resource scheduling and compute assurance. Artur likes new challenges, path-finding and designing solutions from scratch. He is the Python language and networking fan. Artur has master degree in IT from Gdańsk University of Technology in Poland.      )*

* **Grzegorz Grasza** *(Working at Intel on OpenStack from 2014, contributing in High Availability and Upgrades areas accross many projects. Previously developed and run network level monitoring and filtering security applications in WheelSystems.com and SurfSafe.com. Experienced Python and Erlang programmer, started at Grono.net, which was the largest deployment of Django and Python in 2005, later worked as a Solutions Architect at SensiSoft.com, making classified ads vertical portals for large UK, US and South Africa publishers.  )*

* **Hemanth Makkapati** *(Hemanth Makkapati is Senior Software Engineer at Rackspace. He primarily works on Rackspace's Cloud Images product that is based on Openstack Glance. Hemanth is a Glance core and has been involved with Openstack since Havana. He is also a part of the Openstack Innovation Center where his current focus areas include rolling upgrades and improving configuration for Glance. In his spare time, Hemanth plays badminton and follows soccer. YNWA!)*

Stewardship: bringing more leadership and vision to OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you curious about the newly formed Stewardship Working Group? Do you want to find out about the work we're doing?     Are you wondering how you can participate in the group? TC, PTL, or core reviewer burnout got you down?  Do you wonder what it is to be a 'leader' in the OpenStack Community?  Have you heard the term "servant leadership" but don't know what it means? Then this session is for you! Consider this our in-person, live FAQ for the community. We will talk about some of the changes the TC has been considering making to governance policy, and some of the resources we're working with to help provide leadership growth within the community. We would also love to hear your thoughts on what leadership in OpenStack means to you. Facts and details provided by Thierry Carrez, digressions and jokes by Monty Taylor, musical interludes and philosophizing on servant leadership by Colette Alexander, and moderated by Amrith Kumar.


* **Colette Alexander** *(Colette began playing the cello and tinkering with computers at a young age in Detroit, Michigan. Both have followed her into her adult life: she now manages a team of engineers who work on OpenStack, and also actively records and tours with rock bands. She is obsessed with learning about leadership and culture, and how to make hiring engineers a more pleasant process for everyone. She currently resides in New York City, NY.)*

* **Monty Taylor** *(I currently work on OpenStack and Zuul for Red Hat. I lead a team that works on running the Developer Infrastructure systems for the project, as well as other pure-upstream development efforts. I am PTL Emeritus of the OpenStack Infra Program and set up the original project gating infrastructure. I currently sit on the Technical Committee. Previously, I was a core developer on Drizzle and was a Senior Consultant for MySQL, Inc. I've been a Python hacker by choice since 2000, and am currently a member of the Python Software Foundation.I have a degree in Theatre Directing and went to grad school at CalArts in lighting design. The intersection of fields has led me to start more than one business around developing technology for and related to live performance. I continue to work in the theatre, and regularly light shows in New York, Seattle and Austin.)*

* **Thierry Carrez** *(Thierry Carrez is the Director of Engineering at the OpenStack Foundation, helping ensure the long-term health of the OpenStack upstream open source project. He has been the Release Manager for the OpenStack project since its inception, coordinating the effort and facilitating collaboration between contributors. He is the elected chair of the OpenStack Technical Committee, which is in charge of the technical direction of the project. Thierry spoke about OpenStack, open innovation and open source project management at various conferences around the world, including OSCON, LinuxCon, and FOSDEM. A Python Software Foundation fellow, he was previously the Technical lead for Ubuntu Server at Canonical, an operational manager for the Gentoo Linux Security Team, and an IT manager in various companies.)*

* **Amrith Kumar** *(Amrith Kumar is an active technical contributor to the OpenStack project, and a member of the Trove core review team. He is also a member of the OpenStack Foundation Job Analysis Task Force and an author of the book on OpenStack Trove. He is the author of the book on OpenStack Trove (published by Apress, http://www.apress.com/9781484212226). He brings more than two decades of experience delivering industry-leading products for companies specializing in enterprise storage applications, fault tolerant high performance systems and massively parallel databases to Tesora, which he co-founded. Earlier, he served as vice president of technology and product management at Dataupia, maker of the Satori Data Warehousing platform , and Sepaton’s director and general manager where he was responsible for the development of the core virtual tape library product. As a director of product development at Netezza, he managed end-to-end product delivery for all customers and prospects. Amrith studied mathematics at the University of Madras (India) and management at the Indian Institute of Management. )*

Debugging of OpenStack services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Murphy's law states: "Anything that can go wrong, will go wrong.". When it does, one should be able to deal with it. Complex systems like OpenStack with many moving parts inside tend to break often when deployed on a large enough scale. And when something breaks, it's crucial that a developer analyzing the failure knows where to start and has some sort of methodology to perform root cause analysis. Often people come unprepared and start trying things at random or stick to primitive debugging techniques (like inserting print statements in the code), which is at best time-consuming and inefficient and at worst does not allow finding the root cause of the problem or leads to inability to reproduce the bug in question. The goal of this presentation is to share experience of troubleshooting issues in OpenStack services during development and in production, to make developers aware of existing tools and methods for debugging typical problems.


* **Roman Podoliaka** *(Roman got his master's degree in Computer Engineering from Kharkiv National University of Radio and Electronics in 2012. Roman's programming language of choice is Python, which he used on his last 3 jobs developing Web services and backends, as well as for contributing to open-source projects. Since 2013 Roman has been working for Mirantis on various OpenStack projects (Nova, oslo.db, TripleO) with the focus on improving overall stability, performance, code quality, as well as troubleshooting and fixing of complicated issues. Roman gave a few talks at the local Python community event - KharkivPy (http://kharkivpy.org.ua/) and PyCon UA (http://ua.pycon.org/).)*

Making your service searchable in Horizon with Searchlight
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack's Searchlight service uses ElasticSearch at its core to provide powerful, fast searching of cloud resources. Horizon now has a panel plugin that makes use of Searchlight to give you lightning-fast information about your cloud inventory. As a developer, several questions quickly emerge: How do I build plugins into Searchlight-UI for my service/component? What are the best practices for giving users a consistent interface? Do I have to rewrite my existing Horizon actions? To help answer these, we'll delve into the back-end, describing how services and third-parties can easily augment the interface provided. Although many of the UI elements are auto-generated by data retrieved from the Searchlight service, the UI may also be extended to provide maximum value to an end user. "Drawer" views in results and further detailed information may all be customized based on a simple, consolidated registration system available to both developers of core services and third-party plugins


* **Matt Borland** *(Matt Borland is a long-time web developer and currently is on the Horizon team, working at Hewlett Packard Enterprise.)*

* **Travis Tripp** *(Travis has served as Searchlight PTL and core reviewer, a Horizon core reviewer, OpenStack User Experience core reviewer, and an architect for HP Helion where he is currently focusing on improving the OpenStack user experience by leveraging technologies such as AngularJS and Elasticsearch while working closely with the community on new UX designs and interaction patterns. He's led multiple cloud software products intermingling between lead product architect and lead developer roles. He's presented to Gartner, Forester, and IDC, has presented at multiple OpenStack summits, was a DevOps panelist, and has contributed to the OASIS TOSCA specification. In his free time he loves hiking and climbing mountains in his home state of Colorado.)*

* **Tyr Johanson** *(Tyr has been developing applications at HP/HPE for over sixteen years and is a contributor to both Horizon and Searchlight-UI.)*

Understanding Rolling Upgrades
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We all have heard about rolling upgrades, but except for the people involved in the implementation most will not know how it really works. Unfortunately we cannot properly review patches or efficiently change the code base without really understanding it, since any new patch can potentially break rolling upgrades.Sure, most errors will be caught at the gate, but not only is that inefficient, but also doesn't solve everything, as now you'll have to figure out the patch's issue and a solution. And let's not forget that no CI is perfect, and some issues that fall between the cracks could be caught during reviews.This talk is meant for all developers regardless of the level of adoption of rolling upgrades within their projects, as it will not only cover the different aspects of the rolling upgrades but also go a little bit deeper into the versioned objects library explaining things like backporting, relationships, manifests, the remotable decorator, version bumping, etc.


* **Gorka Eguileor** *(Cinder Core and Senior Software engineer at Red Hat contributing to OpenStack's Block Storage Service. Previous experience includes Artificial Intelligence, Embedded Systems and High Availability mobile payment platforms. Besides leading the effort to support Active-Active High Availability configurations in Cinder, he's also been working during the N cycle on removing DB access races on API nodes, optimizing DB queries on most common operations, and making improvements to the Rolling Upgrades and Microversions mechanisms in Cinder.)*

Analyzing gate failures with subunit2sql, openstack-health and elastic-recheck
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will cover how the OpenStack QA team uses subunit2sql to collect information about test results that have run in the gate and how to analyze and use data from gate with openstack-health and elastic-recheck. The resulting data empowers developers in the OpenStack community to make informed decisions about the effectiveness of their tests, identify and track test failures over time and subsequently prioritize which tests they need to prioritize improvements to.Common questions like the following and more will be covered: What is the OpenStack gate? What is subunit2sql? How is subunit2sql used with the gate to collect test results? What is openstack-health? How is data from gate handled with openstack-health? What is elastic-recheck? How is data identified and tracked in elastic-recheck?


* **Dong Ma** *(Dong Ma has worked at Hewlett Packard (now Hewlett Packard Enterprise) as Software/System Engineer since 2007. He worked on the FOSSology(www.fossology.org) project from 2009, with a focus on the Continues Integration and Delivery system. He's been an active technical contributor to OpenStack since the Liberty release. He now works on the HPE's Upstream OpenStack team, focusing on Jenkins, OpenStackCI and QA.)*

* **Masayuki Igawa** *(Masayuki Igawa is a software engineer for over 15 years on a wide range of software projects, and developing open source software related to Linux kernel and virtualization. He's been an active technical contributor to OpenStack since the Grizzly release. He is an OpenStack Tempest, subunit2sql, openstack-health, stackviz core member.)*

* **Elizabeth K. Joseph** *(Elizabeth K. Joseph is a Senior Automation & Tools Engineer at HPE focused on the OpenStack Infrastructure project. With a history of working in open source since 2002 and heavy involvement with the Ubuntu project, she's been working with OpenStack since the beginning of 2013. In addition to Infrastructure, she's the author of the book Common OpenStack Deployments and routinely speaks about Infrastructure and Quality Assurance tools used by the OpenStack project to insure high code quality.)*

How to do Objects in Neutron the right way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Upgrades are the everyday life of OpenStack dev/ops. As neutron is a very complex project - its requirements for upgrades from technical point of view are high. Tools developed in oslo libraries based on nova and cinder experiences have to be enhanced for neutron use-cases. Things like multiple primary keys, extendable resources sent over RPC or API, high performance of SQL queries based on ORM relationships in database model are just examples of challenges that neutron community had to face when trying to adopt oslo.versionedobjects (OVO) library. This session would explain in details how objects are handled, how to add new or port existing resources in neutron to use OVO and how online data migrations can be performed. All of this would be presented as examples in neutron code. This would be an excellent source of knowledge for neutron community members as well as for other projects that are using oslo.versionedobjects library on how difficult use-cases can be handled.


* **Ihar Hrachyshka** *(Ihar is a software engineer at Red Hat. He spends most of his time hacking Neutron (also serving as a core reviewer for the project), nevertheless he is also interested in cross-project initiatives (Oslo, stable maintenance). Ihar is chairing the Neutron Upgrades team meetings and pushes the upgrades story for the project. Ihar is located in a European time zone, but lives as if he is not. "Because time zones are overrated".)*

* **Artur Korzeniewski** *(Artur Korzeniewski is a software engineer at Intel, currently working in Neutron community on subjects related to upgradability and HA of services. He is Neutron Upgrades team member, dedicated to improve the process of upgrade. Before joining the Neutron team, he was closely coupled with OpenStack since Diablo release, working on resource scheduling and compute assurance. Artur likes new challenges, path-finding and designing solutions from scratch. He is the Python language and networking fan. Artur has master degree in IT from Gdańsk University of Technology in Poland.      )*

Service VM - speed up testing with containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Octavia (LBaaS project) use Service VM ideology. The project is using Nova to boot virtual machine responsible for serving our service - load balancer in that case. Testing projects like this require a lot of resources and time because on virtualized environment (gate) we're booting next virtual machines using Qemu as the hypervisor. Because of that, we're landing in nesting virtualization hell. Performance is horrible so testing the functionality of project is taking hours. In Octavia project after splitting tests into smaller chunks results with the testing time equal to around 1.5h. Because of that, there is the idea to use containers - LXD especially - to host and test that kind of projects and will be presented how to do this. What problems we had, identified bugs and how to use this technology in other projects.


* **Lubosz Kosnik** *(Lubosz Kosnik is a Cloud Software Engineer in OpenStack Innovation Center. He was responsible for a contribution to Neutron project and after a few months, he switched to Octavia (LBaaS) project where he is responsible for enabling containers to be used to serve Amphorae - image responsible for serving load balancers. Also, he was working on OpenStack Reference Architecture where he learned about how to operate and manage OpenStack cloud.)*

InfraCloud, a Community Cloud managed by the Project Infrastructure Team
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Infrastructure team, made up of contributors from multiple companies, runs the systems that support the development, testing, and hosting of OpenStack and the services that support the OpenStack community. With donated hardware and datacenter space, the team runs a private OpenStack cloud to support its automated software testing infrastructure. InfraCloud, the project born out of increasing demand from our growing developer community and a desire to "dogfood" OpenStack, is managed in the same manner as the rest of our infrastructure -- as open source, review-driven configuration. Though we've long been consumers of OpenStack clouds, running one ourselves poses new and exciting challenges. This session will discuss how we use cloud technologies to tame our hardware and how we leverage our open source infrastructure to run a cloud.


* **Paul Belanger** *(Paul has been an active contributor to OpenStack since September 2012. Paul is a full time contributor to the OpenStack Infrastructure Project; responsible for of the systems that are used in the day to day operation of the OpenStack project as a whole. Prior to joining Red Hat in April 2015, Paul worked as an Asterisk consultant specializing in call centers and automated deployments. Paul currently resides in Ottawa, Ontario, Canada with his lovely wife and 2 daughters.)*

* **RICARDO CARRILLO CRUZ** *(Ricardo works at HPE as a full-time OpenStack upstream engineer. He is core member of the OpenStack Infrastructure team, responsible for the infrastructure systems that are used daily by the OpenStack project. He is also maintainer of the Ansible OpenStack modules. Previously he worked as an infrastructure engineer on the HPE Helion CI platform, where he designed, maintained and operated the systems used by all the HPE Helion engineers. He lives at Marbella (Spain), with his lovely wife Luisa, his beloved son Mario and his supercute dogs Duque and Nemo.)*

* **Colleen Murphy** *(Colleen works at HPE as a software engineer on the OpenStack Infrastructure team and is a core reviewer on the OpenStack Puppet Modules team. Previously she worked at Puppet Labs as a modules engineer. She has a background in system administration with the Computer Action Team (The CAT) at Portland State University.)*

Ironic Grenade: Blowing up our upgrades.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Come and learn about the Ironic team’s efforts in making upgrade testing (Grenade) work. We will be discussing all the various obstacles and pitfalls that we ran into in getting Grenade to work for the Ironic project. Most everyone agrees that cloud upgrades need to be smooth, quick and reliable, with no downtime for data or the control plane. During the active code development processes it is very easy to break upgradability even with small changes. By adding larger features it becomes more likely. Ironic has become an actively developed project and in every release there are many new features added to Ironic. The Ironic Community decided that automated testing of upgrades was the #1 priority for Newton cycle. In this session, we will tell about the basic concepts of the testing of upgrades at the gates with help of Grenade. We highlight the difficulties faced by the Ironic team. Finally we will list what's currently being worked on and we'll look at the rolling upgrades roadmap.


* **John Villalovos** *(John Villalovos has been working professionally on open-source software since 1998, while working for Intel Corporation. He is an active contributer in the OpenStack community as well as being a core reviewer for the Ironic bare-metal provisioning project. He currently lives in the Portland, Oregon, USA region with his wife.)*

* **Vasyl Saienko** *(Enthusiastic deployment engineer, joined Mirantis and OpenStack Community one year ago. He is currently contributing to Baremetal space in the Community and Mirantis.)*

Tour of the OpenStack Project Infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every change submitted to the OpenStack project, from code to documentation, goes through a series of tests in the OpenStack Project continuous integration system. It is then reviewed and approved by members of the project and goes through a final series of tests before being merged into the repository. This presentation will guide you through some of the history and rationale for how this system works and provide a high level overview of each of the moving parts in this infrastructure. Common questions like the following and more will be covered: What is Zuul? How are test nodes made available? Where did Jenkins go? What do job configurations look like and how do they work? And much more as this presentation walks you every step of what happens when code is submitted to OpenStack.


* **Elizabeth K. Joseph** *(Elizabeth K. Joseph is a Senior Automation & Tools Engineer at HPE focused on the OpenStack Infrastructure project. With a history of working in open source since 2002 and heavy involvement with the Ubuntu project, she's been working with OpenStack since the beginning of 2013. In addition to Infrastructure, she's the author of the book Common OpenStack Deployments and routinely speaks about Infrastructure and Quality Assurance tools used by the OpenStack project to insure high code quality.)*

* **Paul Belanger** *(Paul has been an active contributor to OpenStack since September 2012. Paul is a full time contributor to the OpenStack Infrastructure Project; responsible for of the systems that are used in the day to day operation of the OpenStack project as a whole. Prior to joining Red Hat in April 2015, Paul worked as an Asterisk consultant specializing in call centers and automated deployments. Paul currently resides in Ottawa, Ontario, Canada with his lovely wife and 2 daughters.)*

* **Christopher Aedo** *(  Christopher Aedo, Cloud Architect at IBM, is an IT veteran for consulting, design and technology companies. He is also an outspoken public advocate for OpenStack, cloud computing, software defined networking, and software defined storage. He's recognized as a community thought leader and has spoken at numerous OpenStack conferences in addition to speaking or participating on panels in multiple international conferences, including OSCon, CloudOpen, PuppetConf, and Okinawa OpenStack Days as well as numerous regional developer groups.)*

Not sure if it’s just Cinder that is lacking in testing..or all of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Testing is critical to writing code that actually works. Openstack was groundbreaking for a large open source project in both its formalised review process and gate testing that every commit goes through. This helped the project through early stages till the current maturity level. The problem: We’ve reached the limits of the single node, quick tests. Its vendor CI’s are unreliable. Integration tests miss a variety of areas. Its in-tree and Tempest functional tests are limited. Its code coverage from unit tests is inadequate and what exists are low quality in terms of actually catching issues, and they are often an impediment to refactoring rather than an aid. Bugs slip in causing major regressions in functionality between releases. We need a new approach to testing, to augment and enhance what we already have. Unfortunately, testing falls victim to the tragedy of the commons - any company that fails to invest in it still shares the value provided by others.


* **Kendall Nelson** *(Kendall Nelson is a Software Developer working on Cinder since she started in June of 2015.  She has worked on some smaller scheduler changes to Cinder and a larger effort to make the sample configuration file generation a more dynamic process.  She recently had a spec merged for and has begun working on dynamic reconfiguration of services based on changes to the configuration file. Lately she has also been involved in the refactor of much of os-brick. In addition, she is the cross project liaison for Cinder and given many intro to Cinder presentations to IBMers getting into cloud computing. At the Austin Summit, she had the privilege to give two talks- one to the Women of OpenStack about what she's learned in her first year as an upstream developer and the other on the basics of Cinder and setting up multiple backends.)*

* **Duncan Thomas** *(Involved in Openstack since Cactus, and large HPC systems as adeveloper and admin before that. Worked on one of the first large Openstackpublic clouds, and one of the founding members of the Cinder team.)*

* **Eric Harney** *(OpenStack engineer at Red Hat since Folsom, and avid pool player.)*

A Deep Dive into Customization in Horizon
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Horizon is the official OpenStack dashboard providing access to your services via the Web UI. In recent releases, it has developed a robust plugin mechanism with customization at many levels. The goal of this release cycle was to make dashboard development as easy as possible - just one API call and a few lines of code away. Horizon now allows you to easily extend table columns, table actions, filter facets, workflows, detail views, cell templates, and much more!  We will explore all the recent enhancements to this architecture, demo how to make use of them in your dashboard, the best practices for your plugins going forward, and the roadmap for the future. This presentation is accompanied with a sample project for you to experiment with after the session.  Writing a new panel has never been this easy!


* **Cindy Lu** *(Cindy Lu has been a software engineer at IBM since 2012, focused on OpenStack community development efforts. She's been an active technical contributor to Horizon since the end of the Icehouse release. She is a core reviewer in the Horizon project.)*

* **Thai Tran** *(Thai Tran works for IBM specializing in front-end web development. He has prototyped a number of UI that is included in IBM products. On his spare time, he likes to dabble in front-end technologies, explore mobile web frameworks, and develop video games that run on the web. He is currently a core contributor to the OpenStack Horizon community.)*

* **Matt Borland** *(Matt Borland is a long-time web developer and currently is on the Horizon team, working at Hewlett Packard Enterprise.)*

Improving code quality with Python Type Hints for fun and profit.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Python type hints are a new feature in Python 3.5 which can help to improve code quality and readability, by adding information on what type parameters and return values can be. Type hints can be directly placed in Python 3.5 or higher code, or they can be placed in separate “type hint files” for all versions of Python. There are tools in the Python community that can perform static analysis of type hints in either the source code or in type hint files. This talk will go over our experience in adding type hints to an OpenStack project and performing static analysis on the project and what we learned. Did adding Python type hints improve the quality of the code? Come and find out about type hints and how they can improve your project.


* **Ganesh Maharaj Mahalingam** *(Ganesh is part of the Openstack team at Intel focused on storage and enhancing deployments and enterprise adoption. Prior to this, he was part of the Android team across various companies working on consumer products.)*

* **John Villalovos** *(John Villalovos has been working professionally on open-source software since 1998, while working for Intel Corporation. He is an active contributer in the OpenStack community as well as being a core reviewer for the Ironic bare-metal provisioning project. He currently lives in the Portland, Oregon, USA region with his wife.)*

Learning How to Create a Horizon AngularJS Plugin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This hands-on lab will introduce you to the Horizon plugin architecture and show you how to create your own AngularJS plugin. Recent enhancements to the plugin architecture has made it even easier to customize or add new content. We will briefly cover all the new extension points in this presentation. We will discuss the benefits of writing a plugin and go over different scenarios of how this architecture can benefit you. We will walk you through step-by-step on how you can write, package, and deploy your plugin. The examples will be made available online at the time of the presentation. This lab is aimed at beginners with some skills in web development. Please come prepared with a laptop and a devstack environment with Horizon installed.


* **Cindy Lu** *(Cindy Lu has been a software engineer at IBM since 2012, focused on OpenStack community development efforts. She's been an active technical contributor to Horizon since the end of the Icehouse release. She is a core reviewer in the Horizon project.)*

* **David Lyle** *(David is an OpenStack Architect at Intel where he is focused on contributing to and improving OpenStack. He served five terms as Horizon Project Technical Lead. David previously helped drive use and adoption of Horizon as the user interface for use in OpenStack public clouds. He has directly contributed to the development, packaging, deployment and support of a large public cloud running OpenStack.)*

* **Thai Tran** *(Thai Tran works for IBM specializing in front-end web development. He has prototyped a number of UI that is included in IBM products. On his spare time, he likes to dabble in front-end technologies, explore mobile web frameworks, and develop video games that run on the web. He is currently a core contributor to the OpenStack Horizon community.)*

Turning the Install Guide on its head
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

At the Austin summit, there was just one burning issue in the docs camp: The Installation Guide. It had become a problem. The Big Tent changed the way that projects go about joining the OpenStack ecosystem, and with Foundation having an increased focus on ensuring new projects have sufficient documentation, the old way of writing and testing our Install Guide before each release was simply not going to scale any further. There is no ‘right’ way to install an OpenStack cloud, and there are certainly no ‘right’ components to install. But with a small docs team, and a seemingly endless parade of new projects requiring documentation, we were faced with a big technical challenge, and everyone had some kind of skin in the game.This talk covers the problems we faced, the technical and social solutions we devised, and how we implemented them. We also discuss future changes, and how the lessons learned from this project could spread into other areas of the OpenStack docs project.


* **Lana Brindley** *(Lana Brindley has several university degrees, a few of which are even relevant to her field. She has has been playing and working with technology since she discovered the Hitchhikers' Guide to the Galaxy text adventure game in the 80's. Eventually, she worked out a way to get paid for her two passions – writing and playing with gadgetry – and has been a technical writer ever since. Right now, she’s working for Rackspace from her home in Brisbane Australia, getting her hands dirty on cloud documentation, and loving every minute of it. She is passionate about open source, cake decorating, and great docs, and is raising her very own geek girl. One day, Lana hopes to write the manual for that, too.)*

* **Tomoyuki KATO** *(Kato is a service manager at Fujitsu. He is the coordinator of Japanese translation team, and I18n Project Team Lead in Newton cycle. He is contributing OpenStack, mainly I18n and Documentation, for about 3 years.)*

* **Andreas Jaeger** *(Andreas works as Product Manager for SUSE. He is part of the OpenStack documentation and infrastructure teams where he helps projects with using the OpenStack CI infrastructure. Andreas has been contributing to Linux for nearly 20 years. He lead the development effort to port Linux to the 64-bit x86-64 architecture and ported the GNU C Library to x86-64. As project manager for the openSUSE distribution he helped creating open processes around openSUSE and was responsible for releasing the distribution.)*

* **Brian Moss** *(Technical writer at Rackspace.)*

Full GPU virtualization support is coming
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently, most devices can be passed through to guest and works fine, one of the exceptions is the GPU, the GPU differs from the normal PCI device, it is usually integrated with a VGA compatibility mode and OS may use the legacy VGA mode to access the GPU, so we must to emulate all of the legacy VGA mode operations in VMM.Moreover it has some features that work poorly in virtual environment, like GPU reset. we often need to reset GPU to put GPU into a clean state between guest reboot, but some GPUs lack of FLR or reset incorrect. it may not be a serious problem on physical machine, because GPU reset often occurs while machine reset. but in virtualization, we must ensure host running robust and reset GPU separately while guest reset.all the issues make GPU virtualization more complex than normal PCI devices. but now, we have a new implementation of GPU virtualization (Xengt/Kvmgt), this topic is to briefly introduce the implementation and the usage in openstack in the future.


* **fan chen** *(nova in openstack, libvirt, qemu and kvm virtualizaiton contributor, used towork in fujitsu, huawei, have rich experience in virtualization techology, workedalong with intel OTC team in GPU virtualization area.  now working in easystackin china.)*

Heat benchmarking and profiling using Rally and osprofiler
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

From this topic you will learn how to find bottlenecks in your service. Also you will know how to measure performance of different parts of you service. As example we will use Heat on production deployment with 200+ nodes. We will show results of such measurements with explanations.


* **Oleksii Chuprykov** *(Oleksii Chuprykov is working at Mirantis. He began to contribute to OpenStack community since 2014, now he focusing on openstack heat, he is core review member of openstack heat community.)*

* **Roman Vasylets** *(A year and a half ago he have joined to Rally team as Intern. Now he grow up to Rally Core developer. Before that he took part in competitive programing. Also Roman interested in machine learning, storage systems and sport.)*

* **Peter Razumovsky** *(Peter Razumovsky is working at Mirantis. He began to contribute to Openstack community since 2014 and now is working at Heat design and bug fixing. He is core reviewer member of openstack heat community.)*

Shipping OpenStack Fast & Furious
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Shipping OpenStack in a consumable form is quite challenging. In this session, you’ll learn what happens behind the scenes from engineers responsible for two of the most popular distributions of OpenStack. We’ll show you how Debian and RDO manage to provide high-end grade distributions while delivering right after upstream general availability. In this talk, we'll present our workflow, and how we rely on Continuous Integration and Continuous Delivery to meet upstream fast-paced deadlines.Also, how downstream collaborate together to make OpenStack a first-class citizens in their respective distros.


* **Haïkel Guémar** *(Haïkel is a long-time Fedora developer, where he actually serve as Fedora Engineering Steering Committee and Cloud WG member. He is part of the CentOS Cloud SIG member, where he maintains CentOS packaging for OpenStack. He is the former PTL and current core contributor for the RPM packaging project He works at Red Hat in the RDO Engineering team as one of the driving force for OpenStack packaging.  )*

* **Thomas Goirand** *(Thomas Goirand has been packaging OpenStack in Debian since the Cactus release five years ago. Since, he has done most of the packaging of Python modules for OpenStack, which also end up in Ubuntu, and all the server packages. For the last year, Python modules have worked together with Canonical directly in Debian. Only the server packages are different in Debian and Ubuntu.)*

Network Trunking in OpenStack Neutron: How to Achieve Consensus?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enabling trunk ports (bp/vlan-aware-vms) in Neutron has been challenging for many reasons: it is a complex feature with several use cases we needed to take into consideration, poor performance was not acceptable, moreover a lot of attention led to long discussions. The first patch was sent for review in May of 2014. Today, October of 2016, when most of the work is done, we invite you to join us to look back and to learn from this experience. This talk will go through some anecdotes, analyze the pain points and will offer some solutions and advices on how to reach consensus. You will hear about: How we went through the various API proposals until one stuck; How we kept the Neutron API backwards compatible and technology agnostic while practically changing a fundamental premise of the Neutron network-port relationship; Why we analyzed many approaches via proof-of-concepts before picking the right one; and How we learned to better design accross OpenStack projects.


* **Rossella Sblendido** *(Rossella is a Software Engineer at SUSE. She's a core reviewer for Neutron and has been involved in SDN since 2010 . She's also a mentor for the OpenStack Outreach Program for Women.)*

* **Armando Migliaccio** *(Armando Migliaccio is the PTL for the Mitaka and Newton releases of the OpenStack Neutron Project. He has been involved in the OpenStack community since its early days, and has dealt with a number of OpenStack projects, and solutions in various capacities. Most recently he has been working in various open source projects, like OpenDaylight and Open vSwitch to help the industry usher in a new era of networking.  When he is away from his desk, Armando enjoys sunny California between one travel and another. )*

* **Bence Romsics** *(Bence Romsics has spent the last decade in the technology industry, first operating then engineering and developing software. He has a keen interest in distributed systems, software architecture and scaling. He has worked two years on tooling for a large-scale virtualization platform, another three working with OpenStack networking. Today he is working on finding ways to match the needs of the telecommunications sector with the ever developing offerings of cloud systems.)*

The Gopenstack.org. rewrite. Crazy? Or just crazy enough to work?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It was (correctly) decided that introducing Go as an acceptable language inOpenStack would cause community fragmentation.Monty Taylor eloquently stated:>If we want to add Go, or any other language, into the mix for server>projects, I think it should be done with the intent that we are going to>do it because it's a markedly better choice across the board, that we>are going to rewrite literally everythingCrazy right? Maybe not, let's talk about it for 45 minutes.This thought experiment will include discourse on:What could we fix? Bad architectures, data models, operations, scope, tooling, CLIs, and performance.What would it cost? Developer skill/training, new frameworks, money, time? What would (still) suck? Review time, docs, getting started, corporate interest. Can we ever fix these things?


* **Tim Simmons** *(Tim is a Software Developer at Rackspace on the Cloud DNS team, and a member of Designate core. He has been working on Designate for over two years, and is working on developing and operating Designate at scale for Rackspace.)*

* **Eric Larson** *(Eric Larson is a Core on Designate project and the author of CacheControl, the recommended HTTP caching library for the popular requests library. He is also a software developer working at Rackspace on the CloudDNS team. Outside of writing code, Eric is a proud father and musician.)*

Testing OpenStack APIs with Gabbi and Tempest
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud developers, deployers and users can use tempest to test and validate cloud APIs and services but are limited in what they can test by the clients that are built in to tempest and the existing tempest plugins. While plugins provide a useful way to extend tempest capabilities this can be cumbersome when what is wanted is a clear way to exercise or test APIs. This presentation will introduce gabbi, a toolkit for declarative testing of HTTP APIs, and show how it can be integrated, via a small plugin, with tempest to create testing scenarios from the simple to the complex in an easy to read and write YAML-based format the directly represents HTTP requests and responses. These scenarios can become permanent parts of integration suites or, because they are easy to manipulate, be created as needed for experimentation and discovery.


* **Chris Dent** *(Chris has been working with and developing various forms of distributed systems for around 25 years. When he landed in the world of OpenStack, Chris started with the Telemetry project and has since moved into improving the scheduler in Nova. Chris is primarily interested in the ways groups of people use networked technology to collaborate, exploring the problem space of information sharing and reuse. He hopes to help make himself and everyone else less dumb. He is a core reviewer in the API working group and several telemetry related projects and is the author of Gabbi, an HTTP testing tool, and a large suite of diverse experiments for enhancing asynchronous collaboration on the internet, notably TiddlyWeb and PurpleWiki. In OpenStack, Chris is striving to bring about some semblance of maturity, composability and accessibility to the services.)*

Demystifying Concurrency: debugging + performance strategies
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Concurrent programming is one strategy to performance demands.  When is this reasonable?  When does this hit a wall, and how can you select an appropriate strategy when facing the need for speed, or when looking at existing concurrent code?  Define specifically the problem you’re observing, distill it to its essence.   Collect objective data to test your analysis and assumptions in getting to an essence.  Debug the performance issue in the essential instance, and validate.   Then, pick from the various strategies to address. We’ll walk through a specific case study.


* **Yarko Tymciurak** *(Yarko has a BSEE in Computer Engineering from the University of Arizona.He has worked on commercial UNIX kernels, POSIX command standardization, communications equipment, and mobile devices.He is currently with Intel, and has worked at Unisys, Bell Labs, Motorola, and University of Chicago,as well as several small companies on commercial systems in python. Yarko has been programming in C since 1979, and Python since 1999.He is a member of the PSF, a recipient of the Python Community Service Award,and occaisional open source contributor.For the past eight years he has been an organizer and volunteer coordinator of PyCon, the national Python conference. Yarko additionally teaches team skills, and community building workshops.)*

Isolated development environments for OpenStack with GNU Guix
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Software developers would love to live in a world where bugs are reproducible. Unfortunately, they do not: some bugs happen "in production", but not on their development machines. The behaviour of a program is indeed linked to both the packages installed on the system and the environment (environment variables, filesystem), which makes it hard to reproduce bugs. In order to get reproducible results when running unit tests, virtualenv is often used. It allows developers to create an environment that is almost isolated from the rest of the system and to install packages inside it. We will see during the presentation why virtual environments are not completely reproducible, and why they are not truly isolated. We will show how a functional package manager such as Nix or GNU Guix can help us build reproducible build environments truly isolated from the rest of the system.


* **Cyril Roelandt** *(Free Software developer, GNU/Linux user, GNU Guix developer.)*

Firehose: A unified message bus for Infra services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Development of OpenStack operates at a tremendous scale, with hundreds of repositories and thousands of contributors interacting continuously. The community infrastructure to support this has to operate at an equally large scale to ensure that it is not outpaced by the volume of upstream activity. Accordingly, enabling anyone to see what is happening in real time in this increasingly complex infrastructure becomes equally complex and large. This is why we need to have interfaces available to develop tooling to handle this. During the Newton cycle we introduced firehose.openstack.org to provide a unified message bus. Built using MQTT and the Mosquitto broker, firehose is a consistent interface where Infra's services can publish events. This will go over the origin and background behind the unified message bus, how it's constructed and used by Infra, and also explain the benefits to the wider community and how they can use it for their own needs, experimentation and innovation.


* **Matthew Treinish** *(Matthew is currently a member of the OpenStack TC (Technical Committee) and was previously the PTL (project technical lead) of the OpenStack community's QA program from OpenStack's Juno development cycle in 2014 through the Mitaka development cycle in 2016. He is a core contributor on several Openstack projects including Tempest, elastic-recheck, and many smaller projects and a core member of the OpenStack stable maintenance team. He has been working on and contributing to Open Source software for most of his career and has been primarily contributing to OpenStack since 2012. Matthew currently works for HPE's Upstream OpenStack team working to make OpenStack better for everyone. Matthew has previously been a speaker at OpenStack summits, LinuxCons Japan and North America, FOSSASIA, PyConAU's OpenStack miniconf, and linux.conf.au.  )*

* **Jeremy Stanley** *(A long-time computer hobbyist and technology generalist, Jeremy's worked as a Unix and GNU/Linux sysadmin for more than two decades focusing on information security, Internet services and data center automation. He's a core member of the OpenStack project infrastructure team and serves on the vulnerability management team. In his spare time he writes free software, hacks on open hardware projects and embedded platforms, restores old video game systems and enjoys articles on math theory and cosmology)*

You don't need a policy file
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Any project which wished to have policy enforcement in OpenStack has been using on the always reliable oslo.policy library. However, until recently it required that a project manually maintain and ship with a default policy file. This has placed a burden on packagers to ensure it's installed correctly, and on deployers who must manually check for additional policy rules that they should configure.   Recent changes to oslo.policy now allow for a project to register their default policies in code, eliminating the need for a policy file to be maintained. It is also possible to generate a sample policy file which is guaranteed to contain all used policies and which can be used to automate a check for new policies that have been added.   This talk will walk through how a project can take advantage of these new capabilities, and what benefits are offered to deployers when a project uses them.


* **Andrew Laski** *(I spent many years working on Nova for the Rackspace public cloud involved in development and operations.  Much of my focus has been on the reliability and scalability of Nova.  I now work for Mirantis and dedicate much of my bandwidth to the development of Nova, and other projects as opportunities arise, continuing to push forward on reliability and scalability.)*

Your CLI user experience matter, OpenStackClient 101
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Love it or hate it, OpenStackClient (OSC) is here to stay. Dean and Steve have been working with OSC since it's infancy and are able to discuss it's history, current status and future better than anyone. We'll give an overview of OSC's plugin framework and mention which OpenStack projects have plugins (spoiler: it's a lot!). We'll give an overview of our UX standards and the minor, but elegant UX improvements OSC has over the traditional CLIs (better error messages, bulk actions, built-in formatters). We'll also show how to use the different keystone auth plugins (Time based password, using federated identity credentials, etc) that can be used with OpenStackClient.


* **Steve Martinelli** *(Steve Martinelli is a contributor to the OpenStack project, specifically focused on its Identity, Authentication and Authorization. He is currently the Project Team Lead for the Keystone project, OpenStack's Identity service. He primarily focuses on enabling Keystone, to better integrate into enterprise environments. Steve was responsible for adding Federated Identity and OAuth support to Keystone and was one of the leading contributors to Keystone to Keystone federation support for interoperable hybrid cloud enablement. Steve is also a core contributor to other OpenStack projects, such as: OpenStackClient, pyCADF, cliff, os-client config, oslo.cache, and oslo.policy. Steve is a co-author of Identity, Authentication & Access Management in OpenStack, a book published by O'Reilly Media in 2015. Steve received his B.ASc. in Computer Engineering from York University.)*

* **Dean Troyer** *(Dean has been working on and around OpenStack from the beginning and before with the original Nova deployment at NASA.  He began the OpenStackClient project to provide a consistent command-line interface for the OpenStack APIs.  He is currently a Senoir Cloud Software Engineer at Intel working remotely somewhere in the heart of flyover country in the central US.)*

OpenStack Powered: What is the ideal interoperability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Today, multiple OpenStack clouds exist and we have many cloud users in the world. Sometimes, users want to use the other cloud for the cost efficiency or the performance. Then the OpenStack interoperability is important for users, and the OpenStack foundation is providing "OpenStack Powered" program to certificate clouds' interoperability."OpenStack Powered" program is implemented by Tempest which is a test suite. On the first certification, most clouds could pass. However this year, many clouds failed due to a Tempest change. The change has been implemented by the concept of microversion mechanism.This mechanism is considered as common and good for the interoperability in the development community, however it was difficult to share this idea with whole ecosystem completely and we are facing the certification issue and working together with many folks around the ecosystem to solve that.In this session, we will talk about the ideal interoperability and the latest status of this issue.


* **Ken'ichi Ohmichi** *(Ken'ichi has joined into OpenStack community since 2012, and he is working for OpenStack quality mainly. He has fixed many bugs as an OpenStack community member. Now he is a PTL of OpenStack QA project and a core developer of Compute(Nova).  )*

* **Ghanshyam Mann** *(Passionate about Cloud and Virtualization technologies. Ghanshyam has started working in OpenStack since 2012. He has worked in different domains like Avionics, Storage, Cloud and Virtualization etc. He is active contributor in OpenStack development mainly in Nova and Tempest. He is core developer of OpenStack QA (Tempest).)*

Oslo.Messaging ZeroMQ driver update and messaging drivers benchmarking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In contrast to AMQP-based 'message broker' systems like RabbitMQ, ZeroMQ is a project that aims to create a brokerless ('zero latency') RPC mechanism for OpenStack — one that answers to the extreme requirements of very large, and/or very high-performance clouds. The current version of ZeroMQ driver (new version) has been in development since June 2015 (first spec approved) and currently supports about five different deployment architectures, each appropriate to a range of cloud requirements (large scale, high performance etc.). In this talk, we are going to explain these deployment variants, in order to help operators make good choices when using ZeroMQ as an OpenStack messaging transport. Our team has also developed a benchmarking tool to test oslo.messaging drivers and compare them with one another, exposing strong and weak aspects of each driver. We will share benchmark results obtained from different drivers and make some suggestions for how best to use oslo.messaging drivers.


* **Dmitry Mescheryakov** *(Dmitry is a Principal Software Engineer at Mirantis currently working on oslo.messaging's RabbitMQ driver. He also works on OCF script for Pacemaker which maintains RabbitMQ cluster in OpenStack installed by Fuel. While working on messaging stack Dmitry has accumulated experience helping with it both customers and his colleagues working on other OpenStack components.)*

* **Oleksii Zamiatin** *(Oleksii Zamiatin is working at Mirantis for about 2 years (since 2014). In OpenStack community he contributes to Oslo related projects, particularly to oslo.messaging project (core reviewer). For the last year he is mostly focused on ZeroMQ driver support and contribution. Previously he worked at Samsung RnD Ukraine, Quickoffice, Aldec Inc.)*

Switching to oslo.db EngineFacade in OpenStack projects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

EngineFacade is a part of the oslo.db library, implemented in Kilo, which provides a simple way of declaratively defining session/transactional scope using function decorators or context managers. Despite many advantages, EngineFacade hasn’t yet been adopted by OpenStack projects except Ironic and Nova. We believe it should be. Attendees at this session will hear discussed: : Benefits of EngineFacade Challenges involved in switching OpenStack projects to use oslo.db EngineFacade How to switch: Examination of patches showing how Nova was switched to use EngineFacade They will leave with much-improved understanding of EngineFacade and ability to help their projects make the switch.


* **Pavel Kholkin** *(Member of Upstream development team at Mirantis IT mostly contributing to Nova and Stackalytics for about four years.)*

* **Sergey Nikitin** *(Bio Member of Upstream development team at Mirantis IT mostly contributing in Nova and Keystone for about four years.)*

OPNFV and OpenStack: how to leverage upstream testing tools?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OPNFV is an open source platform that uses OpenStack as the Virtual Infrastructure Layer to enable the integration of different upstream components. In OPNFV we don’t want to reinvent the wheel when it comes to testing and verification. For this reason, we try to leverage the upstream test frameworks to validate our platform from a functional point of view. This presentation will show what the upstream testing components are and how they are used and adapted to our needs.


* **Jose Lausuch** *(Jose is a telecommunications engineer, working as a Senior Systems Designer at Ericsson in Germany. He has been mainly focusing on designing, developing and integrating cloud systems and infrastructures services. He's been working in OPNFV since March 2015 contributing actively in the community to the Functional Testing project along with other projects such as Infra and Release Engineering.  )*

Introducing preemptible instances in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A preemptible instance is a special kind of instance that can be stopped if there are no resources available for another request with higher priority. This way a user may launch preemptible instances (probably at a fraction of the normal price) to fulfil fault-tolerant tasks (like batch processing), taking into account that they may be terminated without further advise. With the current OpenStack scheduling mechanism, instances are only spawned if there are enough available resources for. There is no way to prioritise a request against another, and there is no way a request could stop a running instance. When the computing capacity is tight, this situation lead to the underutilization of the infrastructure. This presentation will introduce a PoC for scheduling preemptible instances into nova, developed in the INDIGO-Datacloud project. With this mechanism in place the scheduler can terminate preemptible instances whenever it is needed to allocate free resources for an incoming request.


* **Alvaro Lopez Garcia** *(Currently I works as a researcher at the Spanish National Research Council (CSIC). In 2007 I held a research associate position at the Italian National Institute for Nuclear Physics (INFN), where I started to work with virtualization so as to deliver on-demand services. I have taken part in several European projects about distributed and Grid and Cloud computing, such as EGEE-II/III (FP6, FP7), Int.Eu.Grid (FP6), EUFORIA (FP7), EGI-InSPIRE and more recently EGI-Engage and INDIGO-Datacloud. With the advent of Cloud computing I moved towards this field, working in the adaptation of the current Cloud middleware and infrastructures to fit the specific needs (parallelism, performance) of the scientific computing applications. In fact the CSIC deployed one of the first OpenStack infrastructures in Spain, back in the Essex release. I am a member of the Openstackfoundation, and I have been an Active Technical Contributor for several cycles, even if my activity has been related with bugfixing .)*

Who touched my domain? it's time to move to Identity v3!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Identity API v3 has been available since the OpenStack Grizzly release. However, its adoption hasn’t been as widespread as we in the Keystone community expected. In Mitaka, we’ve decided to mark the API v2.0 as deprecated, signaling its removal in the next releases. In this talk, we’ll show the differences between Identity API v2.0 and v3;  introduce some of the various new features included in API v3, such as domains, federation, groups, hierarchical projects and inherited role assignments; we also intend to talk about the importance of authentication sessions. Finally, we will discuss the results gathered from a users and operators survey about the Identity v3 adoption.


* **Raildo  Mascena** *(Raildo Mascena is an OpenStack Active Technical Contributor. He primarily focuses on improve the Multitenancy concept in OpenStack. Raildo was responsible for adding Hierarchical Multitenancy support to Keystone and is currently focused on improve v3 support on Keystone. Raildo received a B. Sc. in Computer Science from Universidade Federal de Campina Grande.)*

* **Henrique Truta** *(Henrique is a Software Engineer at Universidade Federal de Campina Grande, that works with OpenStack, focusing on Keystone, although he’s always stepping in other OpenStack projects, like Monasca, Sahara, Heat and Nova. In the rest of the time, he is a Masters Student in Universidade Federal de Campina Grande with a work in progress thesis that’s going to analyze the impact of live migration of VMs in a private cloud, considering metrics like performance and energy saving. As part of this, he’s also engaged in speeding up hadoop jobs by using opportunistic instances and live migrations.  )*

* **Paulo Ewerton** *(Paulo is a Software Engineer at Universidade Federal de Campina Grande working as an OpenStack contributor. His work has been focused on the Horizon and Keystone projects. He has a Master's degree in Systems and Computing and a Bachelor's in Computer Information Systems.)*

A look into the future: A consistent OpenStack GUI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack operators spoke – we listened. The lack of consistency throughout GUIs frustrates people. Alex and Rodrigo will discuss the research, collaboration, time, and effort needed to create a set of patterns that are easy to follow and easy to implement; showcasing the importance of GUI conventions to drive consistency. Join us and provide your insights, needs, suggestions, and concerns regarding this effort to improve the experience for both users and developers alike. Currently, OpenStack projects with a GUI lack consistent guidelines. This session hits on that pain point and provides the developers with the opportunity to be part of the conversation, to ask questions about the plan, and to get involved in the solution. 


* **Rodrigo Caballero** *(Born in Mexico, Rodrigo studied Engineering Physics and Technical Writing in Germany. His experience extends across multiple industries, such as finance, electrical and mechanical engineering, and software development. Hired by Intel in 2014, Rodrigo spearheaded the documentation effort for the Linux Foundation's Zephyr Project for IoT devices. Today, Rodrigo is focused on improving the OpenStack documentation as well as the overall user experience.)*

* **Alexandra Settle** *(Alexandra Settle used to work remotely as a technical writer with the Rackspace Cloud Builders Australia team, but recently relocated to the United Kingdom and now resides in London working on Rackspace Private Cloud and OSIC.She is a core reviewer for OpenStack manuals, spends her spare time dabbling in the Openstack Ansible and swift docs, and mentors documentation for the Outreachy project.Alex began her career as a writer for the cloud documentation team at Red Hat, Australia. She has had a keen interest in IT since high school, prefers Fedora over other Linux distributions, and loves potatoes. Alex was also part of a team that authored the OpenStack Design Architecture Guide, and hopes to further promote involvement in the OpenStack community within Australia.)*

Process? What Process??? – User Story Workflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has well define process of bringing user requirements. This is centered on user stories, and defined process of exposing detailed requirements from these stories into openstack projects and a process for prioritization for them.


* **arkady kanevsky** *(Arkady has been a member of OpenStack since Grizzly. He is director of engineering leading a team of developers responsible for development of Dell OpenStack solutions.  Arkady has PhD. in CS from UIUC.  He straddled academic, research, architect, developer, and product owner roles.  Arkady roles included  but not limited to, research publications and Program committee member for various conferences like FAST (https://www.usenix.org/legacy/events/fast11/organizers.html), Chair or board member  of several standard activities, like DAT (http://www.datcollaborative.org),  OpenFabric (https://www.openfabrics.org/index.php) and MPI-RT (http://www.cse.msstate.edu/~yogi/dandass-mpirt-2004.pdf) to product delivery, like EMC Atmos, Dell OpenStack solutions among others.   Arkady is passionate advocate of OpenStack and making its usage easier for users and administrators. He concentrates efforts of his team on extending OpenStack capabilities for enterprise use cases, from automatic deployment, and robustness, to HA, upgrade, extensibility and validation.)*

* **Rochelle Grober** *(Rocky is an industry veteran, with experience spanning computer bring up to AI, networks and embedded. But her attention always seems to return to close to the metal, large infrastructure. Starting out in EE, she migrated to SW development then on to QA and SW Process, which is why she is a champion for operations, interoperability and usability. She has been aware and peripherally involved in Open Source since the original creation of Copy Left, but is finally fully emersed in it now, as an OpenStack resource within Huawei. She brings many years of experience in large scale systems and operations, SOA, SAAS, mobile (oh, wait, that's not a TLA!) to the table, along with experience in multiple verticals and other business jargon. But most importantly, she melds a passion for quality performance with a pragmatism gained in the real world.)*

Neutron generic mechanism driver for baremetal network provisioning for multi-vendor switches
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently openstack neutron requires separate mechanism driver for plumbing various underlay switches for different vendors and protocols for baremetal servers.This abstract is to eliminate the different vendor mechanism driver implementation and make it single generic mechanism driver. In this generic driver we can initialize the appropriate vendor driver i.e third party drivers based on the user input. We have developed this using stevedore library to load the vendor driver (third party) dynamically during network configuration.In this way we can manage multiple vendor hardware switches with different protocols.we will present how to plug a new vendor driver in the existing ML2 mechanism generic drivers for network provisioning for their hardware.    


* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*

* **KRISHNA MOULI TANKALA** *(Currently working as Software Engineer at Hewlett Packard Enterprise, India. Major contributor to Neutron, Baremetal network provisioning, Lbaas, Octavia.)*

Guerrilla TripleO for Developers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While TripleO can seem impenetrable to anyone who does not regularly work with it, the tooling for getting up and running has improved immensely in the last year, and more and more developers are getting involved. However, given time, you will inevitably run into situations like: You have succeeded in setting up a virtual environment because you need to submit a patch, reproduce an issue or just want to try it out. But now you have to do it again for a previous release Everything is fine in a minimal setup, but now you need to add more controllers or compute instances to your setup You have two computers, and it would speed things up if you could spread your deployments across them Using the existing tools and starting-from-scratch may seem like a valid approach, but there may be a better way. In this session, we explore how you can: Take one virtual setup and turn it into many Add virtual nodes to existing deployments Add virtual nodes hosted on another server


* **Brent Eagles** *(Since joining Red Hat, Inc. in 2013 to work on OpenStack, Brent has mainly focused on cloud networking, hovering precariously between Nova and Neutron. Lately, he has been diving ever deeper into TripleO with the goal helping TripleO keep apace of changes in Neutron as well as furthering the Triple project in general.  )*

Lost in a Forest of Users: Five Paths to User-Driven Development
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Developers can struggle to target the correct OpenStack users because they lack clearly defined user types, which creates inconsistent and confusing user experiences. We solve this problem by personifying five OpenStack user archetypes with key tasks, roles, responsibilities, and organizational models. These personas demonstrate how developers can target their work for specific audiences from the start, letting developers focus on solving problems and developing features. Join us as we define and describe five distinct user personas that can help you target your development for specific users. Our tools teach attendees to identify five user archetypes so developers can better understand users and deliver better user experiences. This promotes OpenStack adoption and improves the user experience.This session provides simple tools that focus on improving the user experience. 


* **Rodrigo Caballero** *(Born in Mexico, Rodrigo studied Engineering Physics and Technical Writing in Germany. His experience extends across multiple industries, such as finance, electrical and mechanical engineering, and software development. Hired by Intel in 2014, Rodrigo spearheaded the documentation effort for the Linux Foundation's Zephyr Project for IoT devices. Today, Rodrigo is focused on improving the OpenStack documentation as well as the overall user experience.)*

* **Jeffrey Calcaterra** *(I am a user experience (UX) researcher. I specialize in products for managing servers and other information technology (IT) infrastructure. I am currently the user research lead for the Hybrid Cloud team. Before that I was the design lead for IBM Cloud Manager with OpenStack. I am also work with the OpenStack Community. I also have a number of patents and chair the Systems user interface patent board at IBM. I started my career designing the first versions of many software utilities still shipping on ThinkPad laptops and in between worked on a number of websites, Eclipse plugins and lots of other things. I have a Masters Degree in Human Factors and Industrial Organizational Psychology from Wright State University and I have a Computer Programming Certificate and a Bachelors degree in Psychology from North Carolina State University. I love the challenge of finding simplicity in a big mess of complexity.)*

Agile Principles and OpenStack - Marriage Doomed to Fail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Agile Software Development has been the buzz on the market for quite a while. This talk will pick few of the most prominent principles from Agile Manifesto and use those to explain why agile methodologies are super unsuitable for OpenStack (or any similar large community opensource) development. Agile Principles are followed by multiple different implementations. This talk is not going to explain any of the implementations in depth nor it is going to list any pros or cons of the individual implementation. This talk is focusing purely to the issues that the principles of Agile Manifesto brings in at fundamental level. Obviously there is also things we can and should pick up from these Principles and lot to learn from the success of Agile Software Development, specially in the startup world. Perhaps the methologies would benefit most new projects that are just flowering within small groups.


* **Erno Kuvaja** *(During working hours Erno is mainly hacking OpenStack storage products and integration; including Glance, TripleO and Ceph. Stationed in Galway, Ireland Erno is one of the remotees in Red Hat's fleet. Before joining Red Hat, he used to work for HP(E) on multiple roles involving support, training and OpenStack development. Erno is very Enterprise minded focusing his efforts to stability, security, supportability and usability. Outside of the work the hacking turns bit more free formed and hw related involving car and automation electronics. Not to be only nerd within the four walls Erno also enjoys to play Disc Golf or taking hikes around the beautiful areas of Connemara or backwoods of Finland.)*

Developing Next-Generation OpenStack Deployment Tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This developer-focused presentation will outline the ongoing development of TripleO to provide an automated deployment mechanism for routed networks, also known as Clos or "spine and leaf" architecture. Spine-and-leaf archtitecture is the holy grail of network scalability. Using L3 routing switches, massive scalability is possible. Legacy networks use VLANs that span multiple racks, but spine-and-leaf shrinks the broadcast domain as small as a single rack, with routed uplinks between racks. This presentation will give an inside look into the development of spine-and-leaf network support in TripleO. In order to deploy OpenStack nodes on a routed network, TripleO takes advantage of some of the latest features in several different OpenStack projects. This presentation will detail how TripleO makes use of Heat, Neutron, Nova, and Ironic to automate the deployment of OpenStack on a routed network.


* **Dan Sneddon** *(Dan Sneddon is a Principal OpenStack Engineer with Red Hat, and the Network Architect of RDO and Red Hat OpenStack Platform. Dan has over 20 years of experience in large-scale networking and datacenter operations. Prior to joining Red Hat, he designed the OpenStack HA and NFV architecture for Cloudscaling, and has been developing for OpenStack since the Diablo release. Past positions include Lead Network Engineer for Apple and Network Security Architect for SLAC National Accelerator Lab.)*

Rally plugins - how to learn all that you need for a half an hour
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Rally is a tool for testing the services under the scale for OpenStack. This topic will be not about Rally itself. We will talk about how to create plugin, where it should be placed, how Rally discover them and for what purpose existing plugins was intended.


* **Roman Vasylets** *(A year and a half ago he have joined to Rally team as Intern. Now he grow up to Rally Core developer. Before that he took part in competitive programing. Also Roman interested in machine learning, storage systems and sport.)*

Vinz, a “viable" alternative to the Gerrit UI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have the recent changes to the Gerrit UI left you confused?  Don’t worry, you weren’t alone. From information overload to an over abundance of unintuitive functionality, we decided that there’s gotta be a better way! Join us as we explore the current progress of Vinz, an infra owned Gerrit UI replacement and help guide us by providing feedback on your favorite functionality or current criticisms. Vinz is 100% open source and developed in upstream gerrit. Preliminary screenshots(vinz supports themes): https://i.imgur.com/eQdV2UE.png https://i.imgur.com/TTeU3vr.png https://i.imgur.com/Q5dArq0.png https://i.imgur.com/cFkawOM.png https://i.imgur.com/agA6Dlr.png https://i.imgur.com/66fojVw.png


* **Spencer Krum** *(Spencer (nibalizer) Krum (http://spencerkrum.com) has been sysoping Linux since 2010. He works for IBM contributing upstream to OpenStack and Puppet. Spencer is a core contributor to the OpenStack Infrastructure Project. Spencer coordinates the local DevOps user group in Portland and volunteers for an ops-training program at Portland State University called the Braindump. Spencer is a published author and frequent speaker at technical conferences. Spencer is a maintainer for the voxpupuli effort(https://voxpupuli.org), which attempts to bring together a network of Puppet developers, modules, and infrastructure. Spencer lives and works in Portland, Oregon where he enjoys tennis, cheeseburgers and StarCraft II.)*

* **Diana Whitten** *(Diana is a Senior Software Engineer with over 10 years of full stack software development, test and system administration experience.  She hails from Tucson, AZ and has a Bachelor of Science degree from New Mexico State Univerisity with majors in Mathematics, Applied Mathematics, and Computer Science. She is an OpenStack UX and Horizon Core and is currently leading the theming development effort in Horizon.)*

Reconciling Datera Intent Defined Storage with Cinder's Volume-centric Model in a Cinder Driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder is designed to provide a well-defined and standard interface formanaging block storage devices. In doing so it has also standardized the wayin which we define and manipulate storage devices. This often comes in directconflict with some of the features provided on a vendor's backend storagedevice. This presentation will cover our solution for finding a happy mediumbetween the traditional Cinder "Volume-centric" storage definition and Datera's"Application/Intent-based" storage solutions and steps other storage startupslooking to join the OpenStack Cinder community can take to come to a similarcompromise. * Cinder's volume-centric view of storage* Datera's intent-defined storage* Round-peg Square-hole problem* Overview of a Cinder driver's role in defining backend storage* Datera's current solution * Possible generic-volume-group addition here (pending implementation in Newton)* Detail possible problems other storage solutions might run up against


* **Matt Smith** *(I like Python, hacking on Vim, messing with my toolchain and generally being a bit rambunctious.)*

The Red Pill for Ironic Third Party CI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, a panel of vendors who have set up CI for their Ironic drivers will provide an overview and share their knowledge and discuss experiences in building infrastructure and jobs for Ironic testing that meets the community requirements in the most diverse kinds of underlying environments and how to optimize and scale jobs using real hardware. Come dig deeper into the rabbit hole and get your questions answered.


* **Thiago Paiva Brito** *(IT MBA, but passionate for the outdoors, I'm a bird in a hi-tech cage. Involved with Openstack about two years ago, I'm exploring the limits of human endeavor by leading and coaching teams of Openstack developers of the Distributed Systems Laboratory, Federal University of Campina Grande, Brazil; focusing on several services such as Ironic, Keystone, Cinder and also the Ops team. In the spare time, I'm an adult volunteer at Scouts of Brazil.)*

* **Isao Watanabe** *(He is a Software Development Engineer of Fujitsu Limited. Mayjor active in Neutron and openstack-infra. He build the Fujitsu 3rd party CI for Cinder, Ironic and Neutron. He also is the main maintainer of the Fujitsu CI systems.)*

* **Michael Turek** *(Mike Turek is a Software Engineer at IBM in the Linux Technology Center. He graduated with a MS in Computer Science from Binghamton University in May 2014. In June 2014 he started working on OpenStack, specifically on ensuring various libvirt driver enhancements for Nova would work for IBM's Power architecture. He regularly participates in the NYC OpenStack meetups and is currently working on Power enablement for OpenStack's Ironic project.)*

* **Rajini Ram** *(Rajini Ram is software engineer at Dell working with OpenStack since Juno release. Currently she is an OpenStack contributor focusing on Cinder and Ironic.)*

* **Sam Betts** *(tbd)*

Debugging Horizon and Its Components
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Horizon is the end user facing self-service portal of OpenStack. It is built using Django and is moving towards a lighterweight Angular JS implementation. Horizon is the go to project for operators and is one of the most used projects in production environments. Join us as we will dive through some of the components of the Horizon project and show how to work on the different components of the Horizon projects. We will cover how to debug the Django framework, Angular JS, as well as the Horizon unit tests.  


* **Ankur  Gupta** *(I am a Portland native and still believe the Pacific Northwest is the best place in the world. Recently graduated and joined Intel as a Software developer. While at Intel have worked with the OpenDaylight project and OpenStack. Recently, relocated to San Antonio to join the OpenStack Innovation Center, a joint venture between Intel and Rackspace. As a part of OSIC have worked in a large team of new upstream developers. Although still learning, have contributed largely to the Horizon and Neutron projects.)*

* **Luis Daniel Castellanos Barba** *(Work as a developer for the OpenStack Innovation Center in San Antonio primarily working on the OpenStack Horizon project. )*

How to work in a cross-cultural environment; or, there's no word for 'please' in Finnish
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We're all extremely busy making OpenStack great -- working across all time zones, spanning many different cultures and communication styles. We want to get good, solid technical work done within our projects. But due to the nature of communication among OpenStack developers, misunderstandings are going to happen. Although they may be unpleasant when they occur, we have a great opportunity to learn from them -- understanding both what happened and how to communicate more effectively next time. Culture plays as big a role as pure technical knowledge when effectively collaborating with people across the world. We don't have a set of guidelines that will solve all of OpenStack's cross-cultural communication problems, but as the great philosopher Yogi Berra said, "You can observe a lot by watching." In this panel, we'll share some stories of effective interactions we've had and will have space for you to share your stories or ask your questions, too. And we promise to explain the title!


* **Erno Kuvaja** *(During working hours Erno is mainly hacking OpenStack storage products and integration; including Glance, TripleO and Ceph. Stationed in Galway, Ireland Erno is one of the remotees in Red Hat's fleet. Before joining Red Hat, he used to work for HP(E) on multiple roles involving support, training and OpenStack development. Erno is very Enterprise minded focusing his efforts to stability, security, supportability and usability. Outside of the work the hacking turns bit more free formed and hw related involving car and automation electronics. Not to be only nerd within the four walls Erno also enjoys to play Disc Golf or taking hikes around the beautiful areas of Connemara or backwoods of Finland.)*

* **Anita Kuno** *(Anita Kuno is a Cloud Automation and Distribution Engineer at HPE.  She works on upstream OpenStack as part of the Infrastructure team.  She has mentored many new contributors on how to develop with the OpenStack Infrastructure system which includes Gerrit and jenkins.Anita has served as an election official for the OpenStack Program Technical Lead Election and the Technical Committee Election for four consecutive release cycles. She has found that the people who are most successful achieving their personal goal are the ones who are most cognizant of the goals of the group. She spends quite a bit of time trying to find ways to support contributor's understanding of the larger ramifications of their choices.She is also an astrologer and acupuncturist.)*

* **Fei Long Wang** *(I'm serving at the PTL of OpenStack Messaging service project(Zaqar) since Mitaka release until now. And meanwhile, I'm in the Glance core team since Grizzly release.)*

* **Iccha Sethi** *(Iccha Sethi is a senior software developer at Rackspace. She has been a long time contributor to OpenStack and has been core on two projects – Images(code name glance) and Databases( code name trove). She is also involved in several community initiatives like CEEAS and Outreachy program and has introduced several women to open source.)*

* **Brian Rosmaita** *(Brian Rosmaita is a Senior Software Developer at Rackspace.  He's been an active technical contributor to OpenStack since the Folsom release and was a software developer on the Rackspace first generation cloud.  He's a core contributor to the Glance and Searchlight projects, and is the Glance technical lead for the OpenStack Innovation Center.  In his spare time, he's the host of Radio Ethiopia, a reggae and African music show that's broadcast on K-RACK, Rackspace's internal internet radio station.)*

Lessons from the Developer Cloud - OpenStack Innovation Center Success Stories
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Through the OpenStack Innovation Center (OSIC), the community can work together to help improve the scalability of OpenStack.  Developers can reserve dedicated bare-metal capacity or a slice of the developer test cloud, to test their projects at scale, all through osic.org.  Since its launch a year ago, the 1000-node OSIC developer cloud has been utilized by projects including HPC, SDN, Ops practices, and object storage tests.  In this panel we learn how developers have used this developer cloud, and gain insights into best practices for proposing a project and using the developer cloud. Topics will include: Upstream contributions resulting from use of the developer cloud Factors contributing to acceptance of user proposals Lessons learned for getting the most out of a dev cloud reservation


* **Antonio Ojea** *(Antonio Ojea is the QA team leader for Midokura. He was graduated Telecommunications Engineer by Vigo University (Spain) in 2002. He worked as a engineer specialist in networks, security and Linux systems in a Regional Telecommunications Company for more than 10 years. He participated in his spare time with several security reseach groups to fight malware and other network threats. He took advantage of the opportunity offered by Midokura to join the company in 2015 to apply his real-life, in-the-trenches bussiness experience to help to make midonet more robust, performant and scalable.)*

* **Arvind Soni** *(Arvind Soni is Product Line Manager in OpenStack Team @ VMware. In this role, Arvind manages VMware's integration efforts across all core OpenStack projects. Additionally, Arvind leads the product strategy and execution for VMware Integrated OpenStack, which is VMware's OpenStack distribution. Arvind is passionate about simplifying the Operational Challenges related to OpenStack Private Cloud adoption.  Arvind has more than 12years of tech industry experience including software development, produt marketing, product management and partner engagements. Arvind holds a Bachelors in Computer Sc from IIT Bombay, a Master in Computer Sc from North Carolina State Univ and an MBA from University of Chicago Booth.)*

* **Justin Shepherd** *(As a distinguished architect and CTO for Rackspace Private Cloud powered by OpenStack, Justin Shepherd is an ambassador of openness. He is often traveling the globe talking about the powers of OpenStack and private cloud, and has trained numerous companies on deploying and operating OpenStack clusters. While starting his career as a systems engineer on a small IT team working in a traditional IT environment, Justin joined Rackspace 10 years ago and has been part of OpenStack since the beginning. He is a core contributor to OpenStack and has helped found both the Chef and Ansible OpenStack communities.  )*

* **Travis Broughton** *(Travis is a Product Marketing Engineer in Intel's Open Source Technology Center, focusing on Intel's upstream contributions to cloud and data center software.  He previously spent 15 years in Intel IT, where he was an architect working on OpenStack deployment, PaaS, and cloud-native application development practices.)*

Tempest Testing with OpenStack Neutron LBaaS v2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud Load Balancers manages application traffic or workload fluctuations by distributing the weight across multiple servers and resources. So how can we be sure that a Load Balancer is working as it should? The speakers of the Neutron LBaaS test team will walk attendees through the Tempest tests for Neutron LBaaS V2 on a virtual machine running Devstack.  Attendees will leave with an understanding of how to use Tempest to test the API with a deep dive into tests scenarios and how to contribute to the Neutron-LBaaS V2 Tempest tests in the future!


* **Franklin Naval** *(Franklin Naval is a Software Developer in Test at Rackspace, the #1 Managed Cloud Company.  Prior to joining Rackspace, Franklin founded two start-ups that specialized in application development on top of the Google App Engine.  Franklin worked as a Software Test Engineer at Google Mountain View for several years, where he "worked on the cloud before there was a cloud."  This will be his second time speaking at an Openstack conference. Find him on IRC @fnaval or on Twitter at @franknaval.)*

* **Luz Cazares** *(Luz is currently working on OpenStack community's QA program for Intel. She is a contributor on several projects including Tempest, Refstack, and os-testr. She is part of the Intel OpenStack Innovation Center (OSIC) working upstream to make OpenStack more enterprise friendly.)*

YAQL: The query language inside Murano, Mistral, Heat, and Fuel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

YAQL — Yet Another Query Language has been around for several years. Initially created as a data manipulation language for Murano, it has since been employed by several other OpenStack projects. YAQL is currently used by Murano, Mistral, Heat, and Fuel. YAQL is an embeddable and extensible query language that enables you to manipulate and query arbitrarily complex data structures. It grants its users the powert to perform complex queries in a single line expression. In this presentation we’re going to cover: A brief history of how YAQL was developed An overview of YAQL’s capabilities How these OpenStack projects use YAQL to manipulate complex sets of data How you can embed YAQL into your project and extend it with project-specific fundtions Where YAQL itself is heading


* **Kirill Zaitsev** *(Murano upstream developer since early 2015, Murano core and PTL for Newton cycle, Community App Catalog developer and core.)*

* **Dmitrii Dovbii** *(Dmytro joined the Murano team at the end of 2014. He is a Murano developer and core-contributor in  murano-apps and a supporter of the murano-kubernetes app on the community app catalog.)*

* **Stan Lagun** *(One of the authors of both Murano and YAQL and a Core in both projects. Long time contributor to OpenStack projects.)*

Who Slowed Down My Cheese?
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We all know the value of finding bugs as close to their introduction as possible. The time to diagnose a problem is generally inversely proportional to the age of the code that introduced it and this applies doubly for performance bugs.  Performance bugs are notorious for showing up later in the development cycle since they often require a more sophisticated environment and more than just functional tests.  As a result, these kinds of bugs often are more difficult to diagnose, more time consuming, and more costly to fix.  This talk will discuss how we at the OpenStack Innovation Center (OSIC) have crafted a continuous integration flow using standard performance tooling to help detect performance degradations earlier than ever before.  We’ll dive into how this work is important to OpenStack upstream developers through downstream vendors and discuss how the metrics we capture will prove beneficial in establishing confidence in the stability and performance of your OpenStack cloud.


* **Steve Heyman** *(I'm an SDT (Software Developer - Test) at Rackspace which is a very cool position where I am responsible for ensuring the quality of code by writing even more code! Since Oct 2013, I've been working on QA projects for the OpenStack Innovation Center (OSIC) as well as Barbican (key management for OpenStack) and find it challenging and interesting...but most of all enjoyable. Previously, I spent 25 years working for IBM Corp with roles that span the software development lifecycle - architecture, design, development, test, performance and consulting. Outside of work I enjoy ice hockey, photography, and Formula 1 racing.)*

* **Luz Cazares** *(Luz is currently working on OpenStack community's QA program for Intel. She is a contributor on several projects including Tempest, Refstack, and os-testr. She is part of the Intel OpenStack Innovation Center (OSIC) working upstream to make OpenStack more enterprise friendly.)*

Live from Oslo
~~~~~~~~~~~~~~

**Abstract:**

A large number of changes happened in oslo libraries over the last cycle. We would like the opportunity to be able to showcase, explain, and educate contributors to what these changes are. oslo.policy  - implemented embed policy defaults in code and allow for a policy file to override them.  This would allow deployers to only configure policies that they specifically want to override. oslo.messaging(zmq) - There were zmq driver deployment configurations added like proxy and pub-sub . we'll talk about these variants of deployment and what benefits you can get using zmq driver. oslo.config - Mutable config is the ability to reload configuration (also logging configuration!) at runtime without a service restart. It is live in Nova Newton now.  oslo.messaging AMQP 1.0 driver - Introduce the new router-based messaging backend supported by the Newton release. Targetted to deployers who'd like to "kick the tires" of this backend.


* **Oleksii Zamiatin** *(Oleksii Zamiatin is working at Mirantis for about 2 years (since 2014). In OpenStack community he contributes to Oslo related projects, particularly to oslo.messaging project (core reviewer). For the last year he is mostly focused on ZeroMQ driver support and contribution. Previously he worked at Samsung RnD Ukraine, Quickoffice, Aldec Inc.)*

* **ChangBo Guo** *(ChangBo had been working on the OpenStack project since October of 2012, with the first batch of OpenStackers from theIBM’s CSTL cloud team in BJ. His first OpenStack contribution can be traced back to 2012, when he worked on the PowerVM driver under Nova to support IBM Power Systems. see his interview from OpenStack [1]. Now, he mainly focuses on OpenStack Oslo and Nova at EasyStack,  he is Oslo core-reivewer and contribute to some OpenStack projects.   [1]http://www.openstack.org/blog/2014/02/open-mic-spotlight-chang-bo-guo/)*

* **Alexis Lee** *(Alexis has been working on OpenStack for Hewlett-Packard Enterprise since 2013, helping to maintain and package Nova for Helion OpenStack. He has been working on OpenStack since Grizzly and helped maintain HP Public Cloud. His current focus is on Oslo, producing features to benefit the whole community. Ask him to play a game.)*

* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*

* **Joshua Harlow** *(Joshua Harlow is one of the technical leads on the OpenStack GoDaddy team. Goal in life: make things more awesome!)*

Adding dynamic configuration to Kolla Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kolla and Kolla Kubernetes  are two primary projects that can be used to install OpenStack using containers and Kubernetes orchestration framework respectively.  While Kolla-Kubernetes is great, it does suffer from few drawbacks: Adding new service requires changes to the central kolla-kuberntes repository. Adding the service also means a way to create configuration ansible and password scripts in one location. There is no easy way to upgrade 'configuration' and services. This talk proposes changes to kolla-kubernetes architecture into a more service oriented architecture by introducing: a) A new service Kolla-Config that centralizes the configuration. b) Introducing 'Service-Manager' per component (glance, nova etc) that is responsible for generating and updating configuration. The result is a much more dynamic OpenStack installation and upgrade experience.


* **Roopak Parikh** *(Roopak Parikh is one of the Co-founder and CTO at Platform9 Systems Inc. Platform9 Systems is one of the OpenStack distribution and service providers. Prior to Platform9 Systems Roopak help technical leadership roles at VMware helping them build various management products including vCloud Director (VCD).)*

* **Bich Le** *(Spent most of career innovating in the cloud and virtualization areas. Before co-founding Platform9, spent 14 years as a Principal Engineer at VMware, helping them innovate their way from a small startup to a multi-billion dollar powerhouse. Prior to that, architected the Aries RISC-to-IA64 dynamic translator at Hewlett Packard. Graduate of U.C. Davis Node.js enthusiast and maintainer of the fuse4js github project.)*

Behind the scenes of testing RDO, an open source community OpenStack distribution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack strives to provide APIs that abstract complex operations in order to mix and match different OpenStack projects, hardware, and network topologies. We verify that aspiration by testing an ever-growing matrix of possible combinations of installing and configuring OpenStack. This process is difficult and intensive. In this presentation, two engineers of the RDO community will share their experience testing trunk across these different installation scenarios. Join us to dive into the projects the RDO community uses to tackle this challenge, and learn how you can get involved.


* **David Moreau Simard** *(David is a Senior Software Engineer in the RDO engineering team at Red Hat where his efforts are around empowering the community to deliver a reliable OpenStack distribution. He brings his expertise around operations, infrastructure, tooling and CI to ensure RDO is the most stable OpenStack packaging distribution. Previously, he was at iWeb, a server and datacenter infrastructure provider where he held various technical and leadership roles in the span of nearly a decade. In the last years, his focus was around deploying and supporting a highly available multi-region OpenStack public cloud in different datacenters around the world.He holds a blog on https://dmsimard.com where he shares articles about what he learns and his interests.)*

* **John Trowbridge** *(John moved from a role supporting OpenStack to a role hacking on it, so he knows a little bit about a lot. Focusing on improving the new user experience of TripleO through the tripleo-quickstart[1] project. Also contributing heavily to the continuous delivery of OpenStack packages with the RDO project. [1] https://git.openstack.org/cgit/openstack/tripleo-quickstart/)*

Jumping on a live Grenade!
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Aiming for a smoother live upgrade? Today, with your project running multiple services on different stable releases, it’s never been more important to test compatibility. As with any distributed system, it is common for OpenStack to have services running on the current release exchanging messages with services from previous releases. Without a gate to provide adequate compatibility testing, there is a possibility for a breakdown in production which will make diagnosing bugs difficult or lead to costly fixes. Implementing a partial grenade testing gate with nodes running services of different OpenStack releases can catch compatibility issues early in the development cycle. This session walks you through the steps to set up a multi-node partial grenade gate in the OpenStack CI infrastructure: Introduction to OpenStack CI Upgrade Testing: Grenade vs Partial Grenade Demo: Cinder Use Case Going from experimental non-voting to full-fledged voting job Lessons learned


* **Luz Cazares** *(Luz is currently working on OpenStack community's QA program for Intel. She is a contributor on several projects including Tempest, Refstack, and os-testr. She is part of the Intel OpenStack Innovation Center (OSIC) working upstream to make OpenStack more enterprise friendly.)*

* **Karthik Prabhu Vinod** *(I work as a Cloud Software Engineer with Intel's OpenStack Innovation Center. I make upstream contributions to the Block Storage Project: Cinder.)*

Eslint rules and their purpose
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk we will discuss what eslint is, how eslinting rules work, how to use them, and how they matter in a project. We will cover the basics of eslint and why the rules are so important, especially to a project as large as OpenStack, but in fact to any size of project. The talk will aim to equip you to leave the summit ready to advocate for or apply eslint rules to your project and understand what eslint rules are and why they matter. We will be discussing: What is eslint? Why does my project need eslint? How to set up eslint for a project Great examples of eslint rules in action


* **Beth Elwell** *(Beth Elwell is a software enginner at HPE, where she leads development of the Ironic plugin for Horizon and works on helping improve UX across OpenStack through her work on both the Horizon and Storyboard projects. Beth has over 4 years development experience and is a self taught front end developer.)*

Find your Gerrit flow
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So you are an Openstack engineer which means you are most likely looking at a Gerrit screen on a daily basis. Gerrit is a powerful and very feature rich code review tool with a specific development workflow. It's central to our continuous integration system and we rely on it heavily to automate our workflow. Many people find that Gerrit can be a pleasure to use and others find it to be a grind on their mental health. This talk will attempt to get you out of your funk with Gerrit and get you into a more productive workflow. I will attempt to point out some Gerrit features and tools that might improve your outlook on Gerrit.  Are you aware that there are tools built around Gerrit that can help with creating patches and dashboards?  So, you don't like the Gerrit web UI?  Well I'll demo an alternative UI that you might like.  You don't like the alternative, then I'll run thru some ways you can contribute to improving Gerrit for Openstack.


* **Khai Do** *(I am a software engineer with a passion for improving software quality and delivery. In general I enjoy working on infrastructure projects that help improve software quality. I am an open source enthusiast and enjoy working on FOSS projects related to code review, configuration management, CI/CD, and buid/test automation tools. My typical week consists of reviewing lots of code, improving our infrastructure tools, and managing our vast cloud of VMs to support that infrastructure. I am fairly good at developing, orchestrating, organizing, documenting, testing, and deploying software. While I am most familiar with Java and Python, I am not afraid to learn new programming languages when necessary, or just for fun!.)*

New Horizons: Getting started with Horizon's AngularJS Framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Out with the old and in with the new! One of the top questions asked by new plugin developers is whether or not they should use the django / python based plugins or if they should be building new content with AngularJS. We're here to tell you that the Horizon AngularJS framework is recommended for all new development and provide you with a roadmap to jumpstart your development or customizations.


* **Richard Jones** *(Richard is a developer at Rackspace focusing on Horizon and modern web technologies, while also helping out the infrastructure team, leveraging his knowledge of Python and packaging. He is an experienced speaker, having presented keynotes, talks and tutorials at many PyCons. In his spare time he plays and develops video games.)*

* **Travis Tripp** *(Travis has served as Searchlight PTL and core reviewer, a Horizon core reviewer, OpenStack User Experience core reviewer, and an architect for HP Helion where he is currently focusing on improving the OpenStack user experience by leveraging technologies such as AngularJS and Elasticsearch while working closely with the community on new UX designs and interaction patterns. He's led multiple cloud software products intermingling between lead product architect and lead developer roles. He's presented to Gartner, Forester, and IDC, has presented at multiple OpenStack summits, was a DevOps panelist, and has contributed to the OASIS TOSCA specification. In his free time he loves hiking and climbing mountains in his home state of Colorado.)*

Neutron L3 Flavors
~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron has had a modular system to load multiple drivers to provide layer 2 connectivity since Havana. This enables a single Neutron deployment to service multiple use cases (e.g. bare metal, SR-IOV, and DPDK). However, there was no mechanism to load multiple L3 drivers so operators were forced to choose a single plugin to provide routers and floating IPs for an entire deployment. To provide this capability, the concept of 'router flavors' was introduced during the Newton development timeline.  During this talk we will cover how operators and users will interact with router flavors to create routers that provide features optimized for specific use cases (e.g. deep packet inspection, high performance hardware routing, packet logging, etc) while using regular Neutron routers for everything else. We will then give a crash course on how to develop a new driver for the flavor framework to cover all of the high-level requirements for a developer to make his/her own driver.


* **Kevin Benton** *(Kevin Benton is currently a Software Engineer at Mirantis. He has been contributing to Neutron since Havana while he was working at Big Switch Networks and has been a core reviewer since 2014. He is the Lieutenant of the reference implementation and also serves on the Neutron drivers team, helping the PTL define the direction of the project by selecting features to work on. He prefers to spend time improving the stability and performance of Neutron and its reference implementation to give deployers reliable OpenStack networking without immediately turning to a vendor.)*

* **Armando Migliaccio** *(Armando Migliaccio is the PTL for the Mitaka and Newton releases of the OpenStack Neutron Project. He has been involved in the OpenStack community since its early days, and has dealt with a number of OpenStack projects, and solutions in various capacities. Most recently he has been working in various open source projects, like OpenDaylight and Open vSwitch to help the industry usher in a new era of networking.  When he is away from his desk, Armando enjoys sunny California between one travel and another. )*

A generic network driver mechanism for Neutron -- One driver to bind them all
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron provides an extension mechanism by which network vendors can register their drivers to support the functionality of Switching, Routing and Security on their devices instead of on LB/OVS and Namespaces. Even though this works, a service provider or enterprise customer still has take care of installing the appropriate drivers and maintaining them across versions. In a mixed network vendor environment this problem gets more accentuated. The current proposal solves this issue by introducing a genric driver mechanism in the Neutron plugin flow  for L2, L3, FwaaS, LB and VPN services. This will result in day zero support of network vendor devices adhering to standards.


* **Sarath Chandra Mekala** *(Sarath is a hardcore Java progarammer and has over 13 years of industry experience in building scalable and distributed Network Management Systems. He is currently working on integrating Juniper's Switching and Security devices with Openstack Neutron. The following are his areas of interest: - Neutron (ML2 and L3) - Neutron-FwaaS - Ceilometer  He blogs @ http://sarathblogs.blogspot.in/)*

* **Chandan Dutta Chowdhury** *(Tech Lead - Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ)*

* **Sriram Subramanian** *(Director - Software Engineering, Juniper Networks Author - OpenStack Networking Cookbook - http://goo.gl/TeXSYQ Blogger - http://www.innervoice.in/blogs Speaker - https://goo.gl/JYGcFo)*

Test Tracking and Reporting with OpenStack Health
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a rather powerful and configurable platform, which provides its users with plenty of configurations options and decision to be taken when deploying a cloud. Testing such a complex system requires a lot of automation, in setting up test environments, deploying test clouds, running tests down to collecting and processing test results. Lukily the OpenStack community provides a lot tools to support quality engineering in all of these areas. In this talk I will present how to use OpenStack Health and other related technologies to collect test results from a variety of test teams and test environments, and how to use this data to help your quality organisation in tracking the status and progress of your OpenStack based software.


* **Andrea Frittoli** *(Andrea Frittoli started working with OpenStack in 2011, leading the QA for the compute service in HP's - Diablo based - public cloud offering. Before that he worked as integration engineer and architect, delivering IT projects for Telcos for several years.Since 2014 he's a core reviewer for the Tempest project, as well as a Tech Lead for QA at HP/HPE, with focus on CI, automation, testing tools and frameworks.He's also a hacker in whatever language he happens to meet, recently mostly python. )*
