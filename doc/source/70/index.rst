Ops Tools
=========

OpenStack Discovery N Assurance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

I have developed a new and exciting Assurance tool for OpenStack in highly distributed large deployments. a new solution for cloud operations team interfaces to OpenStack API, DB and Command Line tools to gather a lot of data for analysis. it then figures out dependencies and graph the inventory and dependency in easy to navigate UI, monitors objects to provide status, statistics, runs impact analysis, root cause analysis to help OS admin to maintain their environment. I would like to share, educate participants about the major issues it solves and the methods used to tackle the problems. The solution is meant to be open-sourced soon.The tool dramatically simplifies openstack administrator maintenance and troubleshooting processes and lowers the troubleshooting, discovery time (guarantee 90% discovery, troubleshooting time reduction for many use cases). I will share my own field experiences and demonstrate how this technology enhances admin operations around openstack facilities.


* **koren lev** *(likes things that are software defined with some underlying high performing hardware to support it. i've been presenting at big conferences around the world, like cisco live, vmworld and others ... currently working for Cisco CTO organization and recently transitioned into this role from CVG (Cloud Virtualication Group @ cisco).worked as a Solution Architect in Cisco's Advanced Services Cloud and Virtualization Practice. Developed several orchestration products for openstack and other platforms. Authored some patents.  Hands-on experience with the Design, installation, administration and operation of Big Data Centers with a focus on automation. Designed and supported major Cloud related projects around Europe, spanning service providers, financial enterprises and other key customers. Holds many industry certifications from several vendors, Quadruple CCIE certification in storage, design, security and networking. experianced in large scale openstack deployments. Currently develops a unique model-driven assurance solution for openstack.)*

Bilean - Trigger type billing service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The mission for Bilean is to provide a generic billing service for an OpenStack cloud, it implements trigger-type billing based on other OpenStack services' notification.  


* **Li Yingjun** *(Yingjun Li is the leader of development department from Kylin Cloud. He has years of experiences in cluster management, virtualization and cloud computing. He is also an ATC for Openstack, core in Rally and Searchlight, has contributed hundreds of patches to various openstack projects.)*

* **Dongbing Lv** *(Dongbing Lv is a software engineer from kylin cloud. Currently he mainly focuses on the deployment of billing component of Kylin Cloud. He is also an ATC.)*

Increase Utilization Without Killing Your SLAs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack clouds *can* be highly efficient when it comes to resource utilization. In practice, however, fear of violating SLAs leads to gross over­subscription, provisioning far more infrastructure than should be necessary. In fact, utilization rates under 20% are not uncommon. In this session, we’ll look at how new approaches like Soft Container can isolate containers to make better use of idle resources, responding dynamically to increase utilization while safeguarding SLAs. Participants will get an overview of new resource utilization and scheduling techniques, and the session will provide an analysis of how resource interference impacts co-­located applications, and the way to mitigate this.


* **Accela Zhao** *(Technologist at EMC ARD (Advanced Research & Development), 3 year experience in Openstack and distributed storage, active Cinder contributor, former presenter at Tokyo Summit. He has been working on a series of innovations related the 3rd cloud platform and emerging storage technologies. Previously he worked for Openstack solutions in Cisco Webex, one of the largest SaaS globally.)*

* **Lin Peng** *(Principal Technologist, Architect in EMC. Leading Cloud Management & Orchestration, Converged Infrastructure initiatives in EMC CTO Office. 10+ patents related to cloud, software-defined data centers and big data. He has also authored a book titled Big Data Strategy, Technology and Application. Contribution to OpenStack include: Heat Murano (Lattice package) Cinder, QoS Puppet Module for VNX integrating OpenStack)*

StackTask, Granular Roles and RBAC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deployment of public, production OpenStack Cloud regions present all manner of challenges, not least of which being the management and delegation of user permissions and roles. Our users have long requested the ability to delegate roles more granular than "_member_", reset passwords securely and invite new users to their own projects; none of which being easily done with base unfederated Keystone or the default policies. We present the method by which we enabled our users to self-manage a significant amount of this (within controlled boundaries), leaving more time for our engineers to develop new features, expand our regions, and sleep peacefully at night.Principally: * Limitations in Keystone, Horizon and the APIs, and the reasons behind them. * Concepts, design goals and architecture in StackTask that overcome many of these. * Horizon dashboard integration. * Rate limiting. * Modification of default RBAC policies to include more granular roles.


* **Michael Richardson** *(Spends his days ensuring the smooth operation of our public, production OpenStack cloud regions as they grow into this ever expanding universe, transparently fitting the requirements of our users.)*

* **Adrian Turjak** *(Principle developer on StackTask, with a strong interest in roles, permissions and delegation.)*

* **Dale Smith** *(Senior OpenStack developer and operations engineer, working on the Catalyst Cloud.)*

Openstack, Ansible, & Ironic: making baremetal deployments easy!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying OpenStack has been considered the wild west frontier for some time, but then along came OpenStack Ansible which has made it simple for operators to deploy production OpenStack, making use of Ansible and lxc containers. Not content with the basic set of OpenStack components, a small band of developers set out with a plan to add Ironic to the list of supported services, resulting in the development of the os_ironic role. Join us as we talk about our journey to add baremetal provisioning to the OpenStack Ansible project. We will discuss how we made it easy to deploy and support OpenStack across not just containers, but also baremetal (introducing yet another buzzword)! Come and hear about the challenges we faced, how they were overcome, and what we learnt in the process. We’ll also gaze into the future and talk about what the next steps might be, and how you can help us get there.


* **Andy McCrae** *(Andy is a software developer at Rackspace working within the Rackspace Private Cloud team. Andy began his career as a Linux Systems Administrator after completing a Masters of Engineering (MEng) majoring Computer Science at University College London (UCL). Andy specialises in Swift (Object Storage) and Ansible. Andy was previously a core reviewer on the openstack-chef project, and is now working as a core reviewer on the openstack-ansible project within OpenStack.)*

* **Michael Davies** *(Michael Davies has been working with OpenStack since 2013, as part of the Rackspace Cloud Builders Australia team, tinkering with Ironic, Nova and OpenStack-Ansible ever since. As penalty for his sins, he is now a core reviewer on the openstack-ansible-os_ironic repository. Michael is a self-proclaimed open source zealot, holds to the Agile manifesto, and is an advocate for modern software engineering practices.  All of these get him into trouble, but especially when he tries to combine them. In his spare time, Michael assists the running of the linux.conf.au open source conference, primarily through helping to lead the papers selection committee. Away from the keyboard, Michael attempts to run, pulls a pretty mean espresso, and spend as much time as he can with his wife and 3 kids, enjoying the Australian outdoors.)*

The Infrastructure Behind the Curtain
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As it turns out installing OpenStack isn't really the hard part any more.  Operating and maintaining OpenStack is much harder.  At IBM Blue Box we provide a managed private cloud solution.  This means that we run a large number of single tenant clouds and the infrastructure to operate and support many cloud deployments. We'll cover everything from how we can install OpenStack anywhere in the world with just a laptop (or a USB stick) with some inception level PXE booting, to how we provide secure access for operations to manage servers  ( bastion, ipmi, dashboards ), and how we perform monitoring and logging. Years of OpenStack operational experience and wisdom, distilled down into what you need to know about what really goes on behind the scenes to make cloud work.  


* **Paul Czarkowski** *(Paul Czarkowski is a Cloud Engineer at IBM Blue Box where he implements OpenStack for Enterprise clients and does Docker R&D.  When he isn't coding you can find him baking bread and winning cookoffs around Austin TX.)*

* **Myles Steinhauser** *(Software Engineer focused on Automation and Operations for IBM Blue Box.)*

CentOS Opstools SIG and collaboration with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operating an OpenStack cloud infrastructure is a complex task. Running an OpenStack cloud infrastructure turns out to create a complex environment. OpenStack itself does not provide additional tools to handle and to support operators. The CentOS distribution is a stable, predictable and manageable platform derrived from the sources of Red Hat Enterprise Linux. As part of the CentOS project, the Opstools SIG is focused on delivering necessary tools to ease the pain of OpenStack operators.    


* **Matthias Runge** *(Matthias is a Software developer living in the middle of nowhere in Germany. He is a core reviewer in Horizon, currently shifting his focus to tooling for operators .)*

Using OpenStack Infra to Benchmark Your OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Faced with the problem of measuring various  workloads we used OpenStack Infra. Few of these required a long running OpenStack deployment with constant workload resembling real world scenarios. Our initial focus was to attempt to emulate these workloads using a number of tools such as Tempest, Heat Stacks, Rally, User Stories, etc.It becomes difficult for any team, both small and large, to tackle this task and provide quality feedback without making this another project on its own.We thought why even simulate a workload when we can have a real thing? With Big Tent, OpenStack Infrastructure requirements for computing resources grows with every project or developer. That means they are in constant need of resources.In this talk we would like to present how we used OpenStack Infrastructure workload to measure API uptime and VM performance of our OpenStack deployments and helpedOpenStack community at the same time.


* **Melvin Hillsman** *(Currently working as Ops Team Tech Lead at OpenStack Innovation Center | Rackspace. I live in the great city of Houston, TX with my awesome family. I enjoy spending most of my time learning more about all kinds of aspects of the technology field from innovations in microprocessing, changes in DataCenter infrastructure, to the latest trends in Cloud Computing. Working with the OpenStack community is a great experience as I assist in leading a monthly OpenStack User Group.)*

* **Michał Jastrzębski** *(Michal is a senior cloud software engineer at Intel Corporation and one of tech leads of Openstack Innovation Center. Michal is making Openstack better since Grizzly. Michal is a Kolla core reviewer since the Liberty cycle with a focus on diagnostics and upgrades.)*

* **Isaac Gonzalez** *(Isaac Gonzalez is a Cloud Engineer, Software Engineer and DevOps Specialist. He is working for Intel Corporation at the OpenStack Innovation Center based in San Antonio at Rackspace HQ. He has been working with clouds since 2014, his primary focus is OpenStack deployment and reference architecture design.)*

Ceph: Deploying to Bare Metal with Ceph-Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Automating your Ceph deployments can be a truly daunting task.  But the Ceph-Ansible Project is a set of roles and playbooks that can help.  This talk will do a demo install on bare metal.  Topics Include:   Configuring Ceph-Ansible OpenStack specific configuration Organizing a multi-cluster configurations Updating an existing cluster Lessons learned from a large-scale, multi-cluster production environment      


* **James Saint-Rossy** *(Principal Engineer for the Ceph storage infrastructure at Comcast.  Over 15 years of Linux and UNIX experience doing operations and systems engineering for major government and commercial organizations.)*

Zuul + Ironic: Automate you Lab as Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Zuul manges Openstack infrastructure workflows and OpenStack Ironic is baremetal service. In our team (100*X), we are deploying Zuul and using FusionSphere (Huawei OpenStack with baremetal service) as CI cloud in each lab or a group of racks.  In our labs, our business is testing FusionSphere (Huawei OpenStack) itself with different scenarios. It looks like community running its infrastructure on OpenStack public clouds, which means we are testing Cloud on Cloud. The difference or the challenge is that vm service is far from enough. We need strong baremetal service to run complex real deployment and mange devices other from physical servers, switches. And we have face more design points on baremetel cloud, such as affinity/anti-affinity, group provision ability etc. Currently, we don't have a 100% good sulotion yet, but we could share what we have thought about and current difficulties. Futher, those experiences are also helpful for the datacentor automation.


* **Zhenguo Niu** *(Software Engineer, working on the OpenStack Bare Metal and Dashboard services, contributing to openstack as Horizon core member, involving in Ironic, Nova, etc. As an OpenStack contributor for Huawei, Zhenguo is responsible for developing projects and features from inception to conclusion in OpenStack, driving contributions on behalf of the internal development team, acting as an interface toward OpenStack, promoting needed architectual changes required for our projects.)*

* **Kun Huang** *(Kun has been working on cloud computing 5 years. He has great experience on open source contributing, performance analysis and continuious integretion. And also he is core reviewer in rally team. Kun was in UnitedStack and he majored in OpenStack Swift, designed and developed early version of boot system of UOS 1.0. After joining Huawei, Kun firstly was invoived in designing cloud image service and help initialize OPNFV team. Currenetly Kun is leading CI&CD team of Cloud OS and trying to build high automated infrastructure.)*

* **wang hua** *(As an OpenStack contributor from Huawei, Hua Wang is responsible for upstream development. Now he is focused on Magnum and the integration of Container and OpenStack. Previously he participated in Huawei FusionSphere OpenStack and has experience in Nova and Glance.)*

Measuring and Visualizing Cloud Performance with PerfKit Benchmarker and Kibana​
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

At times, the need for an effective tool to evaluate the data plane performance of cloud environments becomes important. For example, you may want to compare and validate the performance of certain workloads on your cloud after an update. In this talk, we detail how we can leverage three open source tools to easily satisfy this need.1. Google PerfKit Benchmarker: A benchmarking tool geared towards data plane performance measuring. This is in contrast to Rally, a Benchmark-as-a-Service project for OpenStack, which is more for control plane performance at this time. Out-of-the box, PerfKit can run nearly 30 popular micro-benchmarks and workloads, and supports ten different cloud platforms including OpenStack.2. Elasticsearch: A search engine that stores and indexes JSON documents.3. Kibana: An interface plugin that provides visualization capabilities on top of the data indexed by Elasticsearch.Join us to discover how you can use these tools for your performance analysis!


* **Catherine C. Diep** *(Catherine C. Diep is a Solutions Architect and Performance Engineer with IBM Cloud Business Unit at the Silicon Valley Lab. Her responsibilities include providing technical leadership for proof-of-concept, scalability design & testing. Catherine is the PTL of the Refstack project for the Mitaka cycle.)*

* **Ted Chang** *(Ted Chang is a software and performance engineer at IBM Open Technology and Cloud Performance. He has been working on various enterprise and open source cloud solutions. At the moment, his focus is OpenStack performance tuning and characterization.)*

* **Paul Van Eck** *(For the past two and a half years, Paul has been involved in the cloud solutions and performance team at IBM. Currently he is active in the RefStack project as a core contributer.)*

Massive data plane and storage scale at your fingertip with KloudBuster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While there are a lot of flexibility for building and configuring an OpenStack cloud, hardware and configuration differences can have significant impacts on cloud performance and scale. It is therefore critical to know how your cloud performs at scale before going to production. KloudBuster is a open source tool under OpenStack big tent that allows anybody even with little OpenStack experience to load any OpenStack cloud at massive data plane and storage scale swiftly and effortlessly, and comes "all batteries included" without the need for expensive test equipment. KloudBuster is capable of generating any amount of HTTP traffic involving real HTTP servers and simulated HTTP users, or spawning any amount of storage intensive clients. The testing can be driven from a nice and well designed Web UI, and results will be provided in the form of charts that characterize the behavior of the cloud under load.


* **Yichen Wang** *(Yichen is a software engineer at Cisco Systems. He is part of the OpenStack System Engineering team, and actively working on the fronts of Performance and Scale for Cisco OpenStack NFVi solutions. He is the key contributor for developing VMTP and KloudBuster, which are great tools available on OpenStack for measuring data plane and storage performances and scalabilities for OpenStack clouds. Prior to his experiences in OpenStack, he was a key developer in Cross-OS project, which is a C library that provides the infrastructure support for networking applications across all Cisco Operating Systems. He was involved mostly in Interface Manager subsystem, as well as the implementation of serviceability and white-box testing.)*

* **Alec Hothan** *(Alec is a Principal Engineer at Cisco leading the Openstack Performance and Scale team. He has authored the openstack/vmtp OpenStack data plane performance measurement tool, the KloudBuster data plane scale tool and contributed in numerous OpenStack reviews related to scale, most notably in Oslo Messaging and Neutron. Prior to OpenStack, Alec led the Performance and Scale effort on the control plane of all major Cisco switching, wireless and routing platforms involving high performance tracing, scale tuning with multiple communication protocols, unicast/multicast designs, High Availability, stacking and cluster distributed architectures.  )*

Automated OS Image building for fun and profit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How to keep your OS images up-to-date? How to customize and harden the images? What if the vendor provided “one-size-fits-all image” doesn't suit your needs? Well – go and build your own! At CeBIT 2016 Deutsche Telekom launched the Open Telekom Cloud (OTC) as a OpenStack-based public cloud offering. To keep the promise of the marketing slogan “Simple – Secure – Affordable” in regards to our OS images we have built an fully automated, programmatic way, to build our OS images.   This is the Image Factory project!   Utilizing tools like openSUSE kiwi, the OpenStack API suite, git and local repositories we build public images, entirely optimized to run on OTC. The images are built, uploaded, registered and tested fully automatically. Following this approach we are able to apply changes quickly, include security patches in near-realtime and do hardening and customization. And thinking further – we might even open it up to customers as ImageFactory-as-a-service.


* **Sebastian Wenner** *(I started my careen in 1997 at IBM Germany, doing a dual study for infarmation technologies. During my studies we came across a open-source operating system called Linux which drew a lot of my attention and continued to do so until present time. In my later work at IBM I always followed the Linux and Open Source path, doing several years of project work at customer sites until I switched to the Outsourcing part to work for and later to head the Linux team. As the pure technical side war not satisfying enough for me, I got the chance to do an MBA program and take a look at the dark side ;) In 2012 I moved to T-Systems, heading there the Linux & Solaris Team and later on a team called Cross Platform Integration. There I got in contact with OpenStack and the idea to create a OpenStack based cloud offering for Deutsche Telekom and T-Systems. That endavour ended in what we are today offering as Open Telekom Cloud, me being senior product developer / the technical platform lead for it. Apart from doing all that computer stuff, I am married, have a son and enjoy a lot doing some cooking & baking, spending time with my family and travelling throughout the wolrd.)*

* **Kurt Garloff** *(I grew up in Germany where I graduated in Physics at University of Dortmund. I moved to Eindhoven (The Netherlands) to do postgrad research on plasma physics.I had developed an interest in computers and in particular in the Open Source and Linux movements in parallel and had contributed some code successfully to the Linux kernel when the community was still small. I also succeeded contributing little pieces to a number of other projects (amongst which glibc and gcc).In the end the computer side won over physics and I ended up working for SUSE Linux AG (later part of Novell Inc) as a freelancer and quickly as employee.  I worked as kernel engineer but also took some responsibility in security projects. I ended up running SUSE Labs, where I had the privilege to work with some of the smartest engineers in our research department hosting the open source kernel, toolchain (compiler ...) and X11 engineers.Subsequently, I had a number of technical, people and business leadership roles (Head Architect, acting VP Engineering, VP Product Management, VP Business Development, VP Partner Engineering) and I'm grateful to Novell for sending me to the HBS Program for Leadship Development to enhance my business skills before taking over business management functions.The acquisition of Novell by Attachmate ended my career with SUSE and the next step was being part of the BU Cloud Services in Deutsche Telekom's P&I which had a lot of the startup spirit I was looking for... In my VP Cloud Technology function I headed the unit that developed the Consumer Cloud Storage platform (DLS/Mediencenter) and the OpenStack based hosting infrastructure for hosting the software partners' apps in DT's TelekomCloud BusinessMarketplace and I had the pleasure to present on this in a keynote in the San Francisco Summit.I supported Huawei's Enterprise IT R&D department to build a great cloud engineering team in Europe and to enhance the capabilities of Huawei's OpenStack based FusionSphere solutions in 2014/15. Since fall 2015, I have been supporting T-Systems with the launch and further development Open Telekom Cloud, a large public cloud in Europe based on OpenStack and developed in close collaboration with Huawei and the OpenStack community.PS: When I don't work on computers, I spend my time with my great wife and two wonderful kids.)*

* **Daniela Ebert** *(Before becoming a Senior Product Developer for Open Telekom Cloud, Daniela Ebert spent many years as an AIX Engineer in the Solution Delivery department at T-Systems. Leading up to the launch of Open Telekom Could at CeBIT 2016, she developed the technical implementation of the platform. At the moment her work is concentrated on technical development, the evaluation of technical features, and architecture issues.)*

OpenStack Scale and Performance Testing with Browbeat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Browbeat is an Open Source framework focused on scale, performance and tuning of a deployed OpenStack cloud.  It can provide the following benefits to operators, developers and businesses running OpenStack. Create and orchestrate workloads for performance and scale testing. Automate deployment of common collection and data analysis tools. Identify potential configuration problems and highlight some optimal tuning values Make run-to-run, cloud-to-cloud and build-to-build comparisons by sending test result data bundled with metadata about the cloud to Elasticsearch and visualize via Kibana Provide performance data metrics and results based on Rally and other common tools like Grafana Analyze and tune your Cloud for optimal performance. In this talk you'll hear from core Browbeat developers around how you can leverage it for your OpenStack deployment along with a demonstration showcasing some of the useful features.


* **Will Foster** *(Will Foster has been working at Red Hat since 2007 as a Sr. Systems Engineer, managing enterprise IT storage and core production infrastructure.  Since 2013 Will has been part of a small DevOps Engineering team focused on design, architecture and deployment of internal/external OpenStack, CI and R&D infrastructure.Other areas of concentration include scale and performance of real-world OpenStack customer deployments and production workloads, he is also a core contributor to the Browbeat Project (browbeatproject.org) which focuses on scalability, performance and tuning of OpenStack.  In addition to this Will serves as one of the core Engineers/Operators for Trystack.org on behalf of the OpenStack Foundation.  You can find Will over at https://hobo.house)*

* **Sai Sindhur Malleni** *(Software Engineer working on OpenStack Performace and Scale.)*

* **Alex Krzos** *(Senior Performance Engineer at Red Hat working on Openstack and ManageIQ.)*

Demystifying OpenStack:  Billing and Chargeback Best Practices
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The #1 priority listed by the most respondents in the spring 2016 OpenStack User Survey was “Saving money over alternative infrastructure choices”.   66% of all respondents listed this first. But how do you know if your OpenStack cloud is saving you money and demonstrate that to your users? A self-service cloud running on OpenStack requires reporting and tools to inform project owners and help them make decisions to right size their resources and control sprawl.  Executives and management require a different set of reports and metrics to determine services mix and plan for staffing and resource growth.  This presentation will focus on practical considerations for implementing chargeback and capacity planning in order to make informed choices and increase resource utilization.  


* **Jason Rouault** *(Jason Rouault is Senior Director of Engineering at Charter (formerly Time Warner Cable) where he is responsible for the ongoing development, operation, and support of the Charter Openstack Cloud. At Charter he has helped institute a DevOps culture and introduced tooling and automation to support continuous integration and deployment (CI/CD) of OpenStack. Prior to Charter and Time Warner Cable, Jason was with Hewlett-Packard where he worked in various technical capacities over his 16 year tenure that ranged from software developer to CTO of the Identity Management business. In his last role at Hewlett-Packard he was a Director of Engineering and was one of the original 7 technologists that helped build the HP Public Cloud business based on OpenStack from the ground up. Mr. Rouault has over 20 years of technology management and team building experience including a detailed working knowledge of Information Technologies, Software Development, Cloud Services, and the Internet & eBusiness industry.)*

* **Sanjay Mishra** *(Sanjay Mishra is Founder and CTO of Talligent, the leading provider of cost and capacity management solutions for OpenStack and hybrid clouds.  Day to day, his activities include setting company strategy, working on Openbook deployments, creating a customer driven roadmap, and writing code.  Prior to Talligent, Sanjay was involved in a wide variety of IT infrastructure startups and roles, including co-founding a venture-backed network monitoring company and engineering and consulting roles at Tivoli and IBM.)*

* **Rajesh Gwalani** *(Rajesh is a seasoned product leader in the Cloud world and has successfuly built and delivered SaaS, PaaS and IaaS offerings since 2005. He is currently focussed on improving the maangeability and operabiity apsects of OpenStack to help operators run highly available, scalable, secure and cost-effective hybrid clouds for Enterprise, Telco/NFV and Service Provider segments.  )*

Lightweight Hardware Management Libraries for Scale-out OpenStack Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will focus on the emerging technologies for scalable server systems management. Lenovo is developing open source based tools and libraries in this area, including the pyghmi hardware management library and confluent management aggregation service. These libraries provide utilities for light-weight infrastructure management, autodiscovery, autoconfiguration, alerting, console management/logging, and other general systems management operations. Additionally, they enable automation via scripting with python, CLI, and REST APIs.  These libraries were developed with particular emphasis on managing scale-out datacenter infrastructure such as HPC, Big Data, and Cloud systems managed via OpenStack.  The talk will also describe strategies to eliminate the overhead of adding/replacing server equipment by utilizing the topology information of the datacenter as the basis of the configuration, replacing all manual per-server actions.


* **Srihari Angaluri** *(Srihari Angaluri works at Lenovo Group, Ltd., as a technical architect in the Data Center Group. He leads development of solutions targeted at simplifying infrastructure deployment and management, plus implementing Cloud technologies leveraging open source tools.)*

* **Jarrod Johnson** *(Jarrod Johnson is a software architect in the Scalable Systems division of Lenovo Data Center Group. He has over a decade of experience architecting large-scale HPC systems as well as contributing to open source management tools such as eXtreme Cloud Administration Toolkit (xCAT). Jarrod has worked on deploying, automating, and testing many IBM and Lenovo HPC systems that appeared in the Top500 supercomputer list in the world.  He also actively contributes to professional standards bodies including IETF and has published security research papers.)*

Failure Analysis Under a Multi-Components Public Cloud Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Our company, NTT Communications, provides the public/hosted private cloud service "Enterprise Cloud 2.0” with OpenStack. For cloud service providers, downtime reduction is essential and thus many operation tools that support failure detection and analysis have been deployed. In our company, we have been using monitoring tools (TeMIP, Zabbix etc.) since the previous cloud service; however it takes a long time to conduct failure analysis across multi-component OpenStack-based cloud service because failure causes are more complex. Our goal is to develop an effective failure analysis tool. To achieve this goal, we added some functions such as "the automatic analysis of states/logs along the service procedure flow", "the cause suggestion based on dependency learning" after analyzing failure cases. These improvements have helped us conduct a failure analysis of service down (instance creation failure etc.) more quickly. In this presentation, we share our development knowledge and use cases.


* **Noriko Yokoyama** *(Noriko Yokoyama is a Software Engineer, working at NTT Communications in the cloud service department since 2015. She works with the operation engineering team and develops operation tools for NTT’s enterprise cloud service. Before that, she worked at NTT Service Evolution Laboratories for more than three years. Her research interests include big data analysis and action support systems. She earned her M.S. degree from Waseda University in 2012.)*

* **Hirotaka Kojima** *(Hirotaka Kojima is Software Engineer, Cloud Service Development at NTT Communications. He is working to manage OpenStack Nova based Cloud Service (e.g. Enterprise Cloud of NTT Communications). He also has one year experience working for Verio, Inc. as a system administrator for Unix/Linux Hosting Service. He graduated from Nanzan University with a Master's Degree in Information Science.)*

A tool to test and tune your OpenStack Cloud? Sharing our 1000 node China Mobile experience.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It is difficult to be confident about your cloud deployment with the many things you need to consider, particular without the ability to measure its performance and stability before making it production. It is even harder to locate annoying bottlenecks, tune the cloud, and confirm whether the optimizations really work. China Mobile kindly allowed us to test, against their 1000 node cluster, our profiling tool that non-intrusively tracks each virtual machine boot request every step of the way. We could dial up and down incoming request rates to identify bottlenecks. With the ability to enumerate every possible state of a request, we were able to troubleshoot the cloud quickly. Combined with monitoring tools, we adjusted the deployment making it 3.3 times faster and 100% stable under 800 concurrent requests per second. Confidence born through experimentation. Quality of Service Assurances backed by data. Come see how we achieved this feat and explore our profiling and analytics tools. 


* **Yingxin Cheng** *(OpenStack developer (major in Nova and Congress)    2015.7.1 - Now Software Engineer in Intel                                        2015.7.1 - Now Nanjing University, Software Institute                        2008 - 2015  )*

* **Hao Li** *(LiHao is a cloud engineer in China Mobile)*

* **Xu He Jie** *(Nova core from Intel)*

OpenStack Operations Quick Ramp-up and Survival Guide
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Every cloud lover is running the same OpenStack, but different people deploy and operate OpenStack in different ways. In this session we'd like to share our practices to ramp up an efficient OpenStack operations team, based on real-world experiences and retrospection from operating dedicated and local OpenStack clouds.


* **Joshua Guan** *(Joshua Guan is an OpenStack Operations Lead and Engineer of Blue Box. Prior to his current assignment, he has been worked as a tester, DevOps developer and Continuous Delivery tech lead on various IBM products and services. )*

* **Fan He** *(Fan is a Cloud Architect at IBM, working on design, implemenation and operation of cloud infrastructure services based OpenStack. Before that he worked as Continuous Delivery and test architect for IBM Cloud Manager with OpenStack and IBM Systems Director, with focus on automation and continuous test initiative. He has rich experience in system management, networking and embedded systems.)*

* **Chun Feng Wu** *(IBM advisory software engineer, focuses on infrastructure network and openstack operation for IBM bluebox and cloud solution landing in China. Wu also worked on networking for IBM Cloud Managed Services.)*

Skydive - Follow up on your favorite network and protocol analyzer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

SDN solutions are complex and troubleshooting/monitoring them is even harder. Skydive provides a non-intrusive way to visualize the network topology, and analyze and identify the root cause of network issues. We presented Skydive at the last summit in Austin. Since then, a lot has happened in the project, thanks to the feedbacks of the Skydive early adopters :   Tracking of the whole network topology and traffic changes eBPF probes for ultra light traffic capture overhead Improved querying capabilities to integration Skydive in operation tools Deeper introspection of traffic Better container integration with support of Kubernetes and OpenShift Traffic generation This talk will introduce those features and show how they help operators troubleshoot and monitor network environments, and will present what’s coming next.


* **Sylvain Baubeau** *(Sylvain Baubeau is a Senior Software Engineer at Redhat. He has 10+ years of software development experience and OpenStack integration. In his spare time, he likes to play drums, reverse engineer old games and build arcades.)*

* **Nicolas PLANEL** *(Nicolas PLANEL is a Principal Software Engineer at Redhat. He has 15+ years of software development experience. He has 8 years experience in DPI technology industries. His main interest in Networking technology : DPI, DPDK, OVS, SDN, OVN, ...)*

* **Sylvain Afchain** *(Sylvain Afchain is a Principal Software Engineer at Redhat. He has 15 years of software development experience. He has been involved on Openstack since the Havana release. He worked mainly on Neutron and on Network projects.)*

Save your money in a different way: A Framework for Dynamic Consolidation of VMs in Openstack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently, cloud data centers consume huge amounts of electrical energy, and operators spend much money on energy costs. Does there have a way to relieve this situation? Our team consider that dynamic consolidation of virtual machines (VMs) is an efficient approach for improving the utilization of physical resources and reducing energy consumption in cloud data centers. By using decision-making algorithms and VMs live mirgration in Nova project according to their real-time resource demand, this solution will re-allocate those resources and switch idle hosts to the sleep mode. Furthermore, more important resources in OpenStack can be considered too, like Volumes in storage. So we want to share our study and a open source platform in OpenStack that implement the prototype of this idea. Wish this will bring more thinkings and choices to cloud operators.


* **wang hao** *(Wang Hao is a Software Engineer at Huawei Technologies. He is part of the OpenStack development team at Huawei. Wang Hao has continued to be active in the OpenStack community as a contributor to the Cinder, Nova project and a core reviewer in Zaqar project.)*

* **wang hua** *(As an OpenStack contributor from Huawei, Hua Wang is responsible for upstream development. Now he is focused on Magnum and the integration of Container and OpenStack. Previously he participated in Huawei FusionSphere OpenStack and has experience in Nova and Glance.)*

Freezer Boot Camp
~~~~~~~~~~~~~~~~~

**Abstract:**

Backup and restore of OpenStack clouds presents significant new challenges. Freezer is a backup and restore as a service tool that addresses those challenges and helps operators automate the OpenStack backup and restore process. Freezer executes backups and restores as jobs, and executes these jobs independently and/or as managed sessions. This guided tour features discussions on the following topics:  1. Introduction to the Freezer Components and Architecture2. Using the Freezer Horizon Dashboard3. The Freezer REST API4. The Freezer Python Client5. Deploying Freezer and Troubleshooting6. Overview of the Freezer Agent7. Overview of the Freezer Scheduler8. Overview of the Elasticsearch Database9. Effectively Backing up and Restoring OpenStack using Freezer10.What's new and what's next for Freezer?11.Attendees will be given a guided tour of a live OpenStack deployment being backed up and restored using Freezer in a DevStack development environment.


* **Deklan Dieterly** *(Deklan Dieterly is currently a Senior Systems Software Engineer at Hewlett Packard Enterprise (HPE) where he is working in the OpenStack cloud space. He was one of the principal engineers and founding core developers of Monasca, an open-source, cloud monitoring application now housed in the OpenStack big tent. He is currently the HPE Technical Lead for the Freezer Project, an OpenStack cloud backup and restore solution residing in the OpenStack big tent. He has 20 years experience in software engineering and application development serving in various roles. He holds an MSCS degree from Stanford University.  )*

* **Pierre Mathieu** *(OpenSource passionate, Linux fanatic and OpenStack addict. Presently working for HPE, Pierre has been using and loving Linux systems and Open Source for the past ten years. He started focusing on Cloud computing and OpenStack with the Folsom release. He has a strong tendency to want to automate everything. Curently Freezer PTL as well as in charge of the deployment automation of Freezer for HPE products.)*

* **Arun Balasubramanian** *(Arun Balasubramanian is currently a Product Manager at HPE, focussed on improving the Business Continuity aspects of OpenStack.  Cloud is one of his latest passion in technologies and he has 2+ years Product experience in OpenStack and Network Function virtualization. He has 15+ years of engineering background in Networking, Embedded systems and Distributed Computing projects.)*

Scaling Atomic Host with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Leveraging containers at scale presents unique challenges. Using an operating system that is optimized for containers is essential. Red Hat Atomic Host is designed for clustering containers in production. It is fully supported and backed by Red Hat Enterprise Linux.In this session we will discuss the fundamental concepts of what containers actually are doing inside the Linux kernel. We will then go through a real-world demonstration that deploys a simple web application multiple times with multiple persistent storage backends in a single Atomic Host cluster. This application platform can will be scaled using Heat auto-scaling.Using this fundamental understanding, reinforced by practical examples, attendees will walk away with a better idea of how to leverage containers in their own infrastructure. In addition to this, all of the demo code is available as an Ansible playbook that attendees can use to replicate and expand the entire demo environment on their own.


* **Jamie Duncan** *(Jamie has been at Red Hat for about 5 years, focusing on the problems unique to Public Sector customers. Prior to Red Hat, Jamie worked in the ‘big web’ world and spent some time at a bioinformatics startup.   At Red Hat, Jamie focuses on cloud-enabling technologies like OpenStack, docker, kubernetes and OpenShift among others. With most of these technologies, he has been involved with them since their infancy.   In his spare time, Jamie lives on a small farm west of Richmond, VA with dogs, cats, frogs, chickens, deer and a very understanding wife.)*

All Together Now: Monitoring OpenStack, Security, and Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

After deployment and build-out of an OpenStack cloud, operators require a complete end to end single pane view of the SDN-based network overlay, all the associated workloads and hypervisors and physical infrastructure. This view should also encompass new type of resources being widely deployed like containers. Enterprises and cloud providers alike have aggressively adopted SDN visualization and monitoring platforms in addition to OpenStack horizon to keep their infrastructure running with 100% uptime. In this session, attendees will discover: How comprehensive visualization could help operations staff Monitoring and correlation of physical and virtual networks Monitoring and correlation of resources like VMs, containers and bare metal machines Innovative ways of visualizing security groups related informations and interactions between flows and workloads


* **Valentina Alaria** *(Valentina Alaria has been part of the OpenStack community for 5+ years and has worked with 100s of users throughout their journey of learning, designing and deploying OpenStack-based cloud solutions.  A product innovation strategist and technology evangelist, Valentina has 10+ years experience with Cloud and Datacenter Infrastructure and has been involved with SDN since the early days throughout her endeavors at PLUMgrid, Nicira and Cisco. Valentina has held roles across engineering, Product Management and Marketing and currently runs Product and Solutions Marketing & Training for PLUMgrid.)*

API Microversions for Operators: What? Why? and How?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are API microversions Good, or are they Evil? Should they be embraced, or shunned?What in the world should I do about them?Get insight into the API microversion feature in OpenStack from two developerswho implemented them in Cinder and Manila. Scott and Clinton will explain Whatmicroversions are with examples. They will walk through use cases and help toanswer the questions around Why a developer or operator might use them, or even care.They will demonstrate How to use them with clients or directly with the API in orderto access new features or remain with older behavior.


* **Scott DAngelo** *(Scott DAngelo is a Senior Software engineer at Hewlett-Packard Enterprise who works as a developer on Helion OpenStack Cinder. He is a member of the Cinder core team and works on the core Cinder code, Cinder testing, and Cinder-Nova API interactions. He has been with HP since 2007 and has worked on OpenStack since 2012.)*

* **Clinton Knight** *(Clinton has worked in enterprise storage management since 1999 and joined the OpenStack phenomenon in 2014.  He is a core reviewer on Manila and helps maintain the NetApp drivers for Manila and Cinder.)*

Architectures, tools and best practices for diagnosing and monitoring OpenStack deployments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The use of ELK (Elastic, Logstash and Kibana) and variants (EFK - Elastic, Fluentd and Kibana) for log aggregation has been well documented. What is missing is how aggregated logging can be used for advanced diagnostics, monitoring and auditing in OpenStack. The answer starts with capturing the right data, cleaning of data with filtering, addition of metadata at various stages of the log data pipeline and finally to visualize the indexed data with advanced queries and dashboards built using Kibana. Come share our experiences with log collection, filtering, metadata addition and visualization of logs using ELK stack in OpenStack environment. For instance, you might learn how to write and save a Kibana query when “nova instance fails to boot”.  Or you might learn how to create a Kibana dashboard that monitors the health of your OpenStack environment. And more with real screenshots and demos.  


* **Tushar Katarki** *(Tushar Katarki is a senior technology professional with experience in datacenter and cloud (OpenStack) architecture, product management and engineering. He is currently an Integration Architect at Red Hat driving cross product architecture and integration across Red Hat and partner products (including OpenStack). Prior to the current role, Tushar has been a product manager and a developer at Red Hat, Oracle (Sun Microsystems), Polycom, Sycamore Networks and Percona. Tushar has an MBA from Babson College and MS in Computer Science from University at Buffalo.)*

* **Peter Portante** *(Peter Portante, a Software Engineer since 1986 and a Red Hat Associate since 2011, works in the Performance Engineering team, developing tools and systems to help analyze and understand the behaviors of distributed systems. From developing methods to efficiently collect, normalize, and warehouse all sorts of data about systems, and then visualize and analyze such large volumes of data, Peter's passion is working to make such complex data sets easily accessible and useful. Working with ElasticSearch and the surrounding tool ecosystem has made it much easier to evangelize the accessibility of large data sets today. Prior to these efforts, Peter was a member of the OpenStack Swift core team. Formerly of HP/Compaq/Digital of yesteryear, Peter spent a number of years working on the POSIX Threads implementations of Tru64 Unix and OpenVMS in their two-level scheduling implementations.)*

One-stop-shop for OpenStack tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Often OpenStack operators overlook the tools available to them during -- and after -- deployment. As soon as a deployment is done, they often have questions regarding tools to characterize the stack. This presentation summarizes and showcases the entire tool arsenal available to an OpenStack user in every phase of the product deployment. We’ll also summarize and illustrate how these tools improve productivty, functionality and performance during the deployment as well as after deployment. Join us to learn more about OpenStack tools.


* **Ruchika Kharwar** *(Ruchika Kharwar am a Cloud Success Architect at Redhat. She spends her time working with customers helping them take their POCs to production by enabling integration of various features and components to given them the cloud they want. She helps them with phasing their adoption of the cloud and working across the spectrum with engineerings, sales and process. Ruchika comes with several years of embedded system development at Texas Instruments and she gradually transitioned to the server industry working on ceph storage solutions and then expanding her skills to openstack.   )*

Cloud Management integration with Ceilometer and Gnocchi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack management can grow more complex and challenging as the cloud grows to scale, and even more so as the cloud moves into the hybrid model. Red Hat Cloud Forms is the leading open source cloud management platform on the market today, providing service catalogs, chargeback, and configuration management.   In this talk we will demonstrate the successful integration of Red Hat Cloud Forms into the Rackspace Private Cloud powered by Red Hat. This talk will demonstrate chargeback through Cloud Forms integration with Ceilometer and Gnocchi, hybrid cloud through integration with multiple public cloud providers, and the development of a robust service catalog.        


* **Jeff Ekstrom** *(Jeff Ekstrom is a cloud evangelist for Red Hat’s Certified Cloud and Service Provider program. He has extensive experience with cloud strategy and architecture, with industry experience in Telecommunications, Federal Government, and Insurance. His cloud strategy focus includes both open source technologies and hybrid cloud enablement. Jeff joined Red Hat in late 2015, where he has been promoting and designing Red Hat solutions within Red Hat's partner ecosystem. Prior to that, Jeff's experience includes companies such as Accenture, The Coca-Cola Corporation, and SAIC. )*

* **Nicholas Gerasimatos** *(As a Cloud Evangelist, I work with key Certified Cloud Service Providers to design, build and integrate Red Hat product offerings into the Certified Cloud Service Providers portfolios, data centers, lines of business, and route-to-market offerings. I also work closely with Certified Cloud Service Providers to create and deploy Public, Private, and Hybrid Cloud solutions. My primary responsibilities are developing executive relationships, acting as a trusted advisor and helping influence and accelerate the adoption of Red Hat emerging technologies within Certified Cloud Service Providers.Share the Red Hat vision of multi-product offerings, create awareness of emerging technologies and positioning Red Hat as a thought leader in Public, Private and Hybrid Cloud.  Partnering with the Alliance teams I help develop Red Hat Enterprise Linux OpenStack Platform and OpenShift/Atomic Platform-as-a-Service, Red Hat CloudForms, Red Hat Storage, and the Red Hat JBoss Middleware technology portfolio. Technology Focus: Software Defined Storage, Software Defined Networking, Infrastructure as a Service; OpenStack, CloudStack, Amazon Web Services, Google Compute, Azure, Platform as a Service; OpenShift, Middleware, Continuous Integration Tools, Git, Subversion, Jenkins, Vagrant, Docker, Puppet, Ansible, Salt.)*

Eliminating Complexity using Model-Driven Design and Deployment of OpenStack and other Big Software
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack and other big software are extremely complex things that will cause you to spend much time and effort to architect and deploy.   Today, many architects and administrators spend hours upon hours creating written documents based upon business requirements, that quite frankly if wrong, can take weeks or months to re-architect and/or re-deploy.  This session will showcase a method and a solution for eliminating paperwork and reducing the complexity of Big Software through Model-Driven Design. Simply model your architecture, deploy, repeat!


* **Brent Clements** *(Been working with OpenStack since Diablo and absolutely love building solutions using the OpenStack Framework.  I've done a little bit of everything with OpenStack from deploying, architecting, & developing code all the way to selling OpenStack Solutions to Service Providers and Enterprises. Currently working as the Practice Lead for the Consulting Architect team at Canonical. We help customers focus on their business rather than the technical complexities of software. We do this by providing open source software that allows for model-driven operations of "big software".   )*

OpenStack HA Testing
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack HA testing practise over private OpenStack clusters. 1. OpenStack HA Architecture2. Openstack HA Testing Principle3. HA Testing with Tempest, Rally and other Tools, and their limitations4. The integration and enhancement of automatical testing tools for HA testing


* **Qian Li** *(LiQian graduates from ZJU in 2005, and joined Hengtian as a software development engineer. In 2007, LiQian joined StateStreet as a senior developer, and then grew up to be an architect. In 2015, LiQian joined UnitedStack as QA manager to build up a QA team focusing on OpenStack testing.)*

* **Claire Sun** *(Claire graduated from North China Institute of Aerospace Engineering in 2015, and joined UnitedStack as a QA engineer, who participated in a lot of OpenStack clusters testing work.)*

A Visit from St. Dynatrace, Patron of Digital Performance Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Twas the night before go live and no one was calm,The sysadmin stood by with sweat in his palm,You might wonder what was the occasion,Twas deployment time without DPM in the equation. Digital performance management, as every child knows,Keeps your users/customers happy and makes them no foes, From the first line of code to production deployments,Keeping in line your application's performance. What has this to do with OpenStack?If your app runs on nova and gets out of whack,You should be in the lucky position,To troubleshoot the control plane and your app in correlation. With numerous services and logs to be found,You’re experience with OpenStack should be rather profound.With huge deployments where changes are constant,It’s easy to lose track of what is important. If that’s the case, then don’t despair,I’ll help you sleep well and keeping your hair,So listen closely and see what to do,To get an holistic environment overview.


* **Dirk Wallerstorfer** *(Dirk Wallerstorfer is Technology Lead for SDN and OpenStack at Dynatrace. He has 10+ years of deep, hands-on experience in networking, security, and software engineering. Dirk spends his days on researching new trends in networking and OpenStack, blogging about them, and explaining them to others in simple language, also during his engagements as speaker at conferences and meetups. Before joining Dynatrace, Dirk’s job was to build up and lead a quality management team at a digital marketing agency. Prior to that, he had several engagements as a software engineer working with enterprise Java applications, writing Linux kernel modules for firewalls, and writing UI automation frameworks. Dirk holds a BS from University of Applied Sciences Hagenberg and a MS from Vienna University of Technology.)*

Quick Triaging of common OpenStack issues using Ansible.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As part of troubleshooting issues in an openstack cloud, admin runs through various checkpoints to find the root cause and spends a lot of time in repeating the same troubleshooting steps for multiple occurrences of the same issue. We have captured the common troubleshooting checkpoints and created ansible playbooks that will run through the troubleshooting steps quickly and helps to narrow down the problem. For example, one of the common issue in the cloud is VM not getting an IP. To triage, an admin has to go through multiple manual troubleshooting steps like finding whether the qdhcp for the network is created (or) whether the ports are active and so on. By running the triage playbook that already contains these troubleshooting steps, common checkpoints are validated and the root cause is identified quickly. Agenda:1. How the playbooks are developed with the checkpoints using Ansible2. How to add more checkpoints to the playbooks3. Illustrate with examples


* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*

* **Balaji Ramamoorthi** *(6.5 Years of Experience with Virtaulization, Storage Currently working in Hewlett Packard Enterprise (HPE) as Helion Openstack QA  Scale & Performance Engg )*

* **Siva Subramaniam M** *(I am working in Hewlett Packard Enterprise for the past 4 years.  Worked on products based on openstack, mainly involved in scale and performance testing using rally, functional testing.  Have worked on CI tools such as jenkins, and written various automation for the CI processes.)*

Accelerate the OpenStack Root Cause Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a multi-layered cloud infrastructure with many complex internal and external dependencies: Software, Hardware, Storage, OS and Networking. Hence, when the system is troubled, you need to run multiple commands and check different areas before you can define where to perform a deep dive troubleshooting. The objective here is to shorten the initial investigation and focus on the most probable cause of the issue.   This is leveraging the knowledge accumulated by escalation engineers while managing real customer environments running OpenStack. Therefore, we know what are the main checkpoints. And, we can automate the diagnostic without having to open the UI. This also provides a good snapshot (as-built) of the system configuration at different points of time.


* **Nebu Mathews** *(I have expertise in Solution Architecture and design of Fault and Performance management solution. I am fully conversant in the process of designing a solution, including study of network design and identifying software components that shape a performance management solution. I have extensive hands on experience & customisation knowledge of EMC M&R (Formerly APG Watch4net), EMC SRM Suite, EMC SAS Suite, EMC VxRacks Neutrino, Openstack Platform, Mycom NIMS-PrOptima, HPOV TeMIP, HPOV TSM.)*

* **Yassir Laraki** *(Software development and Telecom Engineer, with 12 years of hands-on experience in Solution Architecture and System Integration roles, providing technical leadership in large scale/comprehensive projects.• Have demonstrated expertise in the Integration of best practices to assure the delivery of business services at promised levels, improve operational efficiency, and optimize the resources. • Excellent ability to leverage existing functionalities and integrate/bridge multiple platforms and teams to offer innovative and creative solutions.• Have advanced understanding of Wireless and Wireline Networks as well as the Layer 1, Layer 2 & 3 architectures and their services. • Experience in converged Infrastructure based on Openstack and ScaleIO. • Excellent knowlege in supportig and troubleshooting cloud environments: Hw, Software (Linux), Network, Openstack, Docker, Database)*

Kostyor: an upgrade orchestration solution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kostyor is designed to automate the process of upgrading a deployment of OpenStack from one major version release to the next major version release. Upgrading an OpenStack installation historically has been very difficult, and not without risk. In order for OpenStack to be used for telecommunications workloads, a number of requirements related to how OpenStack is upgraded, and the impact this has upon tenants and applications has been determined. Reduction or Elimination of Tenant Downtime during an upgrade Visibility into the upgrade process Monitor and collect downtime metrics during the upgrade process In this session, the architecture and features of Kostyor will be presented and we will discuss how Kostyor solves the above requirements.  


* **Sean Collins** *(Sean Collins is a contributor to OpenStack Neutron, previously led the Neutron IPv6 working group, and also co-organizes the OpenStack Philadelphia user group. Sean began using cloud technologies in order design scientific computation clusters, and later began developing new OpenStack features in the networking space, including support for IPv6 networking, network quality of service, and firewall automation. Sean is also a co-author of the OpenStack Architecture Design Guide. Sean currently works at Mirantis)*

* **Vitaliy Nogin** *(TBD)*

* **Dmitry Stepanenko** *(TBD)*

Orchestrate once, deploy everywhere
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Installing an application once is easy, but what happens if you want to write an application that works on top of AWS, OpenStack and Bare Metal?  In this talk, we'll describe some batteries-included software we've written, deployed, and operated atop multiple public and private clouds using Kubernetes from a single set of installer tooling.  We'll also describe how we made it resilient to failures such that we can remove our bare metal nodes and kill our cloud nodes without requiring operator intervention.


* **Ken Wronkiewicz** *(Ken is a Technical Leader at Cisco working with cloud infrastructure. Previously, Ken managed the Rackspace Cloud AutoScale product. Before that he worked on monitoring and high-performance stock market data feeds.)*

* **David Wang** *(David Wang is an architect at Cisco)*

ELK Storage Analytics: Logarithmic Logs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Elasticsearch, Logstash and Kibana (ELK) stack has become somewhat of a standard as an OpenStack log management service. Elasticsearch, the immensely popular search engine, requires an immense amount of storage, by nature -- but how much is enough storage? How long can you maintain current measures before you need to add more memory? How will changing your log retention as per HIPAA compliance affect your storage capacity? This dilemma can be solved using the growing log information we have available to us along with mathematical analytics. In this talk, we’ll cover how we try to make sense of the data available to us, what deducing methods we use to craft equations for prediction models, and how more research work of this type can allow us to effectively and efficiently tackle problems of similar complexity.


* **Brian Richardson** *(Passions for topics such as Data Analysis, Game Theory, and Computer Science. Solving problems and finding patterns.   Graduated from University of Texas with Bachelor of Science in Mathematics with a specialization in Scientific Computation. Currently a Software Engineer at IBM Cloud.)*

* **Myles Steinhauser** *(Software Engineer focused on Automation and Operations for IBM Blue Box.)*

* **Zachary Sais** *(Zachary Sais is a Software Engineer at IBM Cloud where he automates and deploys monitoring frameworks for enterprise OpenStack clients. Prior to IBM, he graduated from the University of Texas at Austin with a degree in Computer Science. In his downtime, you can find Zach brewing delicious beer and playing golf in Austin, Tx.)*

Toolkit Tips to Free DevOps Teams from Dependency Hell
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Supporting different OpenStack environments can be difficult. From a DevOps perpective, how do you cope with different versions of the OpenStack client tools? Installing different versions of the client tools on the same host can easily end up in a dependency hell. Having the correct toolbox saves you and your team time and unnecessary work. Even better, having a tailor made set of tool at your dispose will make your work faster and your team more productive. We recognize that this is an issue for many stackers, including us, so we've decided to embrace the issue by building a toolkit that includes the most common pieces and parts used to operate, debug and develop an OpenStack cloud.


* **Diego Casati** *(Diego is currently working as a Corporate Systems Engineer  within  EMC’s Advanced Software Division  where he have the privilege to interact with various engineering teams, helping customers to get the most out of their clound computing systems. His previosly worked in the Telecom and IT industries as a Network Engineer, Systems Engineer, Customer Support Engineer,  Systems Integration Engineer and as a Web Security Specialist. On his spare time, he enjoy's learning more about OpenStack, BSDs and reading about sci-fi.    )*

* **Javier Soriano** *(TBD)*

* **Mohammad Itani** *(Expert with Networking and Data Center Architecture and Troubleshooting. Escalation Engineering for IAAS managed by OpenStack. Testing IAAS Architectures around OpenStack solutions.)*

One for All: Deploying OpenStack, Ceph or Cloud Foundry with a Unified Deployment Tool
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying production-ready OpenStack is a complex process that asks for a lot of knowledge. Next to OpenStack often other services do exist in a data center which have different constraints. A unified deployment tool significantly reduces the workload for operators and developers.Crowbar is a mature and extensible Open Source provisioning framework wich makes it easy to rapidly, and flexibly deploy OpenStack clouds, Ceph storage setups or other software stacks like Cloud Foundry on OpenStack onto bare metal. It also can utilize different architectures like x86 or SystemZ and platforms like Linux distributions or Microsoft Windows.This session will explain the Crowbar architecture and how to easily build custom plugins to integrate third party application. It will offer an outlook at the future of the project and how to become part of the community and contribute and influence the direction of the project.Crowbar source code and documentation live at https://github.com/crowbar


* **Nanuk Krinner** *(Nanuk Krinner is an OpenStack Developer at SUSE Linux and actively working on the OpenStack product since 2012. He is active within the OSLO project and also has first hand with deploying and maintaining OpenStack in production environments. He is also an active developer of the Crowbar deployment framework. Nanuk Krinner is an experienced speaker, who has, among other occasions, spoken at the CeBIT exhibition when accepting an award that was awarded to the OpenStack project and at the OpenStack Summit 2016 in Austin.)*

* **Rick Salevsky** *(I work as SUSE Cloud Engineer since February 2015 on various SUSE OpenStack Cloud product parts. I started with the system management and configuartion via Chef and focused in the last year on the automated deployment solution for our cloud product. My openSource experience is much longer. I started using Linux when I was 15 years old and joined SUSE as an apperentice in 2012.)*

Openstack User Access Management and Role Based Access Controls
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation covers the implementation of user access management for the AT&T Integrated Cloud (AT&T's Openstack infrastructure), as well as the need for Role Based Access Controls and the support of Openstack RBAC roles within user access management. For this talk, user access management refers to the context of managing the granting or removal of user access to Openstack resources by associating the user with an Openstack role(s) for a given tenant (or removing that role from the user).   The talk will discuss the characteristics, requirements, and architecture of a user access management system, including automated provisioning of access, support for approval authorization, auditing, and lifecycle support.   The talk will review the implementation of RBAC by Openstack services, how the Openstack data model impacts access management, and the tradeoff associated with the benefit of a new role and the impact of making local changes to Openstack roles and policies.  


* **Michael Denny** *(Currently working as an AT&T Integrated Cloud (AIC) architect.   AIC is a cloud infrastructure using Openstack.    A little of my resume:   My job experience includes Cloud Technologies (2010-present, hands-on and architecture),  Enterprise Architecture for Content Services (2007-2010), Service Delivery Platform Design (2005-2007), IT strategy development (2005-2011), Enterprise IT Strategic Architecture assessments (2002-2004), Internet services architect (2000-2002), Content Management Services segment lead (2000-2004), Network-Based Services assessment (1994-1998), and Collaborative Computing assessment (1994-1995).  Managed several groups (1982-1994) and performed associated project management in several areas, including PC Technical Support, Software Asset Management, Applications Development, Electronic Publishing Systems, On-line documentation, Unix Office Systems Support, VMS Technical Support, and UNIX Technical Support groups.  Started career in 1977 at Bell Labs, Holmdel, NJ, in the Experimental Network Administration engineering group. Holder of many patents, including: www.google.com/patents/US20070100981)*

* **Mahendra Kuncham** *(Mahendra Kuncham is a Sr Technical Director at AT&T, currently managing a team of System Engineers providing AT&T cloud consultations, assist clients to onboard virtual functions onto AT&T cloud on multiple hypervisor types. Also responsible to provide high level solution designs to integrate with AT&T cloud. Mahendra joined AT&T in 2006 and been responsible in managing System Build/Planning, Tier 3 production support team(s). Mahendra came to AT&T from Sun Microsystems worked with many clients at automotive practice. Responsible to provide HA solutions, Performance Analysis & Tuning, TCO Analysis, Server Consolidation, Solaris Zones/Containers.)*

Sleep Better at Night: OpenStack Cloud Auto­-Healing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Software­-defined everything is a new trend. How about software­-defined outage prevention and remediation? You have your cloud up and running. You monitor it through StackLight, Zabbix, Nagios or some other tool. But what's happening when one of the services is unresponsive or your free disk space is low? How quickly will you able to resolve the issue? Do you have any debugging information or logs gathered before you actually start digging into the issue? We will introduce a “robo­sysadmin” for our production OpenStack cloud that reacts to alerts and outages and helps us to speed up mean time to repair by gathering debug information and trying to fix issues automatically using predefined workflows. It’s a kind of Tier 0 support: it troubleshoots, fixes known problems, escalates to humans when necessary, and provides detailed information on what it has discovered.


* **Mykyta Gubenko** *(Mykyta Gubenko is a Deployment Engineer at Mirantis working for the Services department. As an experienced system engineer, he helps Mirantis customers to be successful with Openstack. Mykyta is focused on deployment automation and large-scale openstack projects.)*

* **Alexander  Sakhnov** *(Alexander Sakhnov is a Senior Software Engineer working for the Mirantis Services department. He has been with Mirantis for more than 6 years, and joined the OpenStack community from the very beginning of the Cactus release. His main activity is helping customers with production OpenStack deployments.)*

dotStar – A Tenant-centric Tool for OpenStack Ops Monitoring and Analytics
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud monitoring is a key element of OpenStack management operations. This presentation describes and demonstrates a novel monitoring and analytics tool, dotStar, used in Cisco Cloud Services by cloud engineering staff, operators, and customers (tenants). With the tenant (customer) centric approach, it provides the capabilities of associating cloud tenants with infrastructure components (e.g., host, Ceph, Neutron), services (e.g., VPN, load balancing, big data as a service), and usage patterns (e.g., NetFlow data, OpenStack API calls) across clouds and regions. dotStar enables cloud infrastructure management, capacity planning, service operations, and troubleshooting with deep insights in user and application behaviors.


* **Jim Huang** *(Jim Huang is an experienced engineering lead in Cisco Cloud Infrastructure and Services organization. His work involves design and implementation of cloud health monitoring and service deployment automation in OpenStack environments. Prior to his current role, he served as a senior manager for development of Cisco Intercloud Solution involving OpenStack, AWS, and MS Azure, and other Cisco products. He was also a lead in defining High Availability engineering standards and processes in the telecom industry as well as in Cisco. Jim gave High Availability Networking lectures and seminar in the Stanford University and taught Operating Systems course in the University of Minnesota. He was an author of many technical journal and conference papers and awarded US patents. Jim has a Ph.D. degree in Computer Engineering from the University of Massachusetts.)*

* **Omer Ansari** *(Omer is a seasoned Cloud Services leader responsible for Engineering at Cisco Cloud Services in support of Cisco's large scale production SaaS assets as well as key federation partners worldwide. He has overseen SDN solutions built by integrating best of breed Cisco technologies with Opensource platforms such as Openstack, next-gen XaaS revenue-generating features such as MPLS Private Link (WAN Automation), Analytics-based Load Balancer as-a-Service, VPN as-a-Service, ACI integration into Openstack, provisioned IOPS based storage to name a few. In his spare time, Omer loves to swim. )*

The Juju/Ansible Bake-Off: Which Should I Choose To Deploy and Run my OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Juju and Ansible are two highly popular means of deploying OpenStack, and they both standardize on the same core platform (Ubuntu). This makes them easy to compare fairly and impartially. In this presentation, we'll take a look at how they fare in a direct head-to-head. We'll look, in particular, at the following topics: What prerequisites exist for deploying OpenStack with Juju, and Ansible? How does an agentless and agent-driven approach compare? What does either tool offer for baremetal deployment? What architecture approach do the tools follow? What networking and storage options are available? How does either tool handle expansions/upgrades of the OpenStack environment? How can operators customize/override either tool's choices? How can operators switch from one tool to the other? This talk is free of bias toward either tool — my team and I have used both openstack-ansible and Juju to deploy OpenStack clouds in production, and have seen the pros and cons of either first-hand.


* **Florian Haas** *(Florian has been an active member of the OpenStack community since early 2011. He has driven and contributed to lively discussions within the community about OpenStack high availability, distributed storage integration, automation and deployment, and other topics. Florian has spoken about OpenStack at previous OpenStack Summits and also at OSCON, LinuxCon, linux.conf.au and many other conferences. When he is not speaking at conferences, Florian discharges his duties as CEO of professional services firm hastexo (which has a strong OpenStack focus), and also acts as a Principal Consultant serving hastexo's high-profile clients.)*

Decentralized Devops with Masterless puppet and Datacenter automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Do you want your cloud to be Several thousand Baremetals Several thousand Cores Hundred Thousands Virtual machines This Talk is for you.   Paypal has experienced enormous growth , in terms of Active users and applications which in turn means running 100k + vm in dev and production in 13 Availability Zone powered by Openstack. We'll talk about some of Paypal's innovations around OpenStack with Datacenter Automation using tools like masterless puppet , stackstorm ,git, r10k .  


* **Raj Geda** *(Raj Geda is a Sr. Cloud Engineer on the PayPal, Inc. Cloud Reliability Engineering team, responsible for raising the bar with availability and reliability.)*

* **ritesh nanda** *(Sr. Cloud Engineer on the PayPal, Inc. A result oriented technology and team leader with extensive skills in the area of Cloud Computing, Datacenter automation, Networking, and business/technology alignment. These skills are coupled with hands on experience, and demonstrated strategic, technical and thought leadership, leading to innovative developments.)*

* **venkatesh gnanasekaran** *(Decisive, results-oriented and proactive professional with extensive experience in analysis, design, development and implementation of various Java and NoSQL applications. Have made a significant impact to every project that I have worked. Also have filed four patent applications with US Patent office and three more ideas for which internal review is in progress. )*

007 ways to make Ironic's ramdisk your secret agent
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When you deploy bare metal servers with Ironic, there are a lot of tools available to improve the manageability and longevity of your hardware, but you may not be aware of them all. This presentation explains how to use custom agents and hardware managers, even if you're not a Python developer! Have confidence that your data is efficiently cleaned between uses of your servers to prevent leakage from one user to the next. Get metrics that track the age and performance of your servers. Ensure your users won't provision failing hardware. Ship useful logs into your preexisting syslog infrastructure. After attending this presentation you will have the insight needed to get the most out of Ironic with custom hardware managers and agent ramdisk configurations.


* **Jay Faulkner** *(Jay Faulkner is a core reviewer on Ironic, and has been involved in the project for over two years. He was one of the original engineers behind Rackspace OnMetal and has been operating software in production for nearly ten years. When not working on OpenStack, he enjoys a good hockey or video game.)*

Practical OpenStack Operations: What happens after Day 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You now have a fully deployed OpenStack Cloud. Great. You made the right decision. But what happens next? This presentation looks into the most common operational problems that a typical Cloud administrator will face after day 1: security, currency, monitoring, problem detection, analysis & resolution, scalability and configuration elasticity, among others. It will compare capabilities of familiar DevOps tools, such as Ansible, Juju/MaaS, Nagios/Icinga, Zabbix, ELK, Ganglia, Grafana, etc. The DevOps landscape is extensive and it can be confusing to understand the pros and cons of a particular stack of applications to complement Cloud operation needs. It's our goal in to clarify the available options and categorize them, while emphasizing their differences, strengths and weaknesses. Lastly we discuss best practices to integrate them with OpenStack to achieve flexible and effortless Cloud operations.


* **Marcelo Perazolo** *(Marcelo Perazolo is the Lead Software Architect for Operational Management in the IBM Systems Cloud Solutions Group. He is located in the IBM Software Lab in RTP, NC, and has received his MSEE and BSEE degrees from UNICAMP, then started his professional career at IBM in 1990, accounting for more than 25 years of professional experience with Infrastructure and Platform Management solutions. He drives planning and strategy for IBM's Systems Management team to exploit Open Systems Software and OpenStack to build Converged and Hyperconverged Infrastructure solutions. He is active in multiple Open organizations, such as OpenPOWER, OASIS and DMTF and focuses on furthering IBM's Open Systems agenda, and to drive open management capabilities into converged and hyperconverged infrastructure system solutions in the marketplace.)*

MAAS 2.0: hyperscale-grade physical automation for the masses
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Managing phyiscal infrastructure is a pain in the ass. That is, except if you are one of the Big Three, and have a hairy, powerful and entirely homegrown system which can discover, configure and deploy any hardware you might want to purchase. Actually, it turns out that the essential functionality you find in Google, Facebook and Amazon's toolkit is now available to anybody, free of charge. MAAS is an open source tool which is used to automate deployment of bare metal at scale, and which is increasingly seen underneath large and growing OpenStack clouds. MAAS a web UI, but the most powerful way to use it is through its cloud-style API, which lets you ask for physical infrastructure as if it were completely software-defined. As in "give me a server with at least 24 cores and 96GB of memory, configure its two 10GBe NICs into a bond, and deploy Windows on it".


* **Kiko Reis** *(I am a VP at Canonical and a long-time Ubuntu and open source contributor. I'm responsible for Canonical's storage, server enablement & automation products, but also get involved occasionally in other complicated and wonderful areas on the fringes of technology. I have an MSc in Software Engineering from ICMC USP, and live in São Carlos, Brazil, with my amazing wife Mari and two funny little toddlers.  )*

* **Blake Rouse** *(TBD)*

* **Andres Rodriguez** *(TBD)*

Billowing Storm Clouds VS. Clear Skies - Autoscaling OpenStack compute nodes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, you’ll see how a cloud management platform (CMP) can help monitor and manage your OpenStack environment. Use the data that ceilometer is already capturing to determine when your OpenStack cloud needs to be scaled up or down and then use a CMP to automatically orchestrate this activity. This same CMP can also be used to manage and monitor the lifecycle of guest workloads and provide you a single pane of glass to control all of your guest workloads across multiple OpenStack clouds.Using a CMP, such as ManageIQ, you can perform tasks such as:- autoscaling compute nodes to dynamically flex your cloud presence- provisioning instances across multiple cloud providers- orchestrate complex service bundles- integrate with 3rd party systems via REST API


* **Nate Stephany** *(Nate Stephany is a Senior Cloud Solution Architect at Red Hat who focuses on Red Hat's cloud products, such as OpenStack, CloudForms, and OpenShift. He has over 15 years of enterprise systems architecture and administration experience, with the majority of this time spent in the telecom industry.)*

* **Kevin Morey** *(Kevin Morey is a Principal Cloud Solution Architect at Red Hat who focuses on Red Hat's Cloud portfolio including OpenStack and CloudForms, Red Hat's Cloud Management Platform. Kevin has over 25 years of Enterprise Systems Administration, Professional Services as well as Systems Engineering. Kevin's passion for innovation and cloud computing led him to Red Hat.)*

Islands in the Stream - Consuming OpenStack services for more than just OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, you’ll learn the benefits of running OpenShift Container Platform on top of OpenStack. This allows your OpenShift environment to not only run in OpenStack instances, but also consume other OpenStack resources, such as Cinder volumes and Keystone authentication. Why recreate the wheel with islands of infrastructure? You can keep it all streamlined and available to both Infrastructure-as-a-Service (IaaS) and Platform-as-a-Service (PaaS).One of the key benefits of OpenShift is the ability to run legacy apps, which are generally stateful and require persistent storage, in a container. We will show you how OpenShift can dynamically provision Cinder volumes from OpenStack and mount those to containers running in your PaaS. In addition, if you have already spent the time perfecting your Keystone authentication configuration, we will show you how you can leverage that versus having yet another authentication configuration for another platform.


* **Nate Stephany** *(Nate Stephany is a Senior Cloud Solution Architect at Red Hat who focuses on Red Hat's cloud products, such as OpenStack, CloudForms, and OpenShift. He has over 15 years of enterprise systems architecture and administration experience, with the majority of this time spent in the telecom industry.)*

* **Kevin Morey** *(Kevin Morey is a Principal Cloud Solution Architect at Red Hat who focuses on Red Hat's Cloud portfolio including OpenStack and CloudForms, Red Hat's Cloud Management Platform. Kevin has over 25 years of Enterprise Systems Administration, Professional Services as well as Systems Engineering. Kevin's passion for innovation and cloud computing led him to Red Hat.)*

2nd Days of Operations Handled by Policy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A lot of requests come from users after stating a cloud. - want to allocate instances booted from same image on separated hypervisors but in same AZ due to performance and HA of their app - want to make a resource reservation for expected future usageThe requests make day2 operations more complicated. When you maintain hypervisors, where will you migrate instances on the hypervisors? When a number of available virtual resources is less than demands, how do you get the available capacity?This talk presents how the complexity of operation resolved by Policy. Congress, Governance as a Service, provides operators with a range of ways to manage and control their cloud by Policy. This will also show you real use case of requests from user and how policies resolving the operation complexity.


* **masahito muroi** *(Masahito Muroi is a software enginer in NTT. He is now working as a cloud architect for NTT's public/private cloud, and also working as a core developer of OpenStack Congress Project and Masakari. He's started to join OpenStack Community and develop NTT's cloud with OpenStack since Diablo release.)*

Cloud Management with Go
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How do we report on host utilization, point out unused quota, and perform quota management on tons of tenants in a cloud? We will investigate Comcasts strategy for using gopher-cloud and GO to manage and report on tenant utilization, from the beginnings to where we are now. This talk is for anyone who is interested in managing their openstack cloud in a more efficient way by leveraging the GO programming language.


* **Victor Howard** *(Victor Howard is a Principal Software Engineer at Comcast and has been involved in CI/CD, Packaging, Keystone, Neutron, and Heat.)*

* **Margaret Frances** *(I have worked on OpenStack development, almost exclusively in Neutron, since August of 2015. Prior to that, I worked as a web application developer for the networking and telecommunications group at University of Pennsylvania's Information Systems & Computing.)*

A Monitoring Architecture for OpenStack on Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We at Mirantis are currently working on a “Containerized Control Plane” (CCP), a project that aims at running OpenStack services in Containers deployed and managed by Kubernetes. Our goal with CCP is to create a hardened OpenStack distribution, focusing on robustness, scalability, high-availability and ease of upgrades. We are developing CCP in the open, under the umbrella of the Fuel OpenStack project. This presentation will focus on Monitoring in CCP. We think Monitoring is key, so we are developing Monitoring from the beginning of the project, as a core component of CCP. In this presentation we will describe our general Monitoring architecture, and the various open-source tools our Monitoring toolchain comprises. In particular, we will talk about Snap and Hindsight, the telemetry framework and stream processing engine we use for collecting and processing the telemetry data, and how we combine the two. [1] <http://intelsdi-x.github.io/snap/> [2] <https://github.com/trink/hindsight>


* **Éric Lemoine** *(Eric Lemoine is a Senior Software Engineer at Mirantis, working as a developer in the Logging Monitoring Alerting team. In the past Eric worked at Sun Microsystems, in the Labs first, where he did a PhD on high-performance networking, and then in the High Availability team as a Software Engineer. Eric also worked as a Technical Leader at Camptocamp, an open-source company specialized in Geographic Information Systems. As part of work at Mirantis, Eric contributed a distributed Logging solution to the OpenStack Kolla project, and participated to the design of introducing Monitoring to Kolla.)*

* **Patrick Petit** *(Patrick Petit is the engineering director managing the Stacklight project at Mirantis. Patrick Petit joined Mirantis in April 2014. With over 25 years of experience, Patrick Petit held different software engineering positions in several IT companies including Sun Microsystems where he occupied several software architect roles in the iPlanet Division and the Technology Office of the company both in California and in the Engineering Center of Grenoble.)*

* **Olivier Bourdon** *(I am a Senior Software Engineer at Mirantis, working in the StackLight team (formerly called LMA for Logging Monitoring Alerting) currently based in Grenoble FRANCE. In the past I have co-founded several startups, some having been more successfull than others ;-), and also worked for quite a long time at Sun Microsystems where I have held several positions (technical & manager) within several teams (dev, QA, support))*

Managing multiple OpenStack clouds from the ManageIQ user interface
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Learn how ManageIQ, the open source cloud management solution, can help you inventory, monitor, and manage multiple OpenStack deployed environments from one single user interface. As the foremost private cloud solution for enterprises and service providers, OpenStack needs easy-to-use management capabilities. ManageIQ integrates with OpenStack to automatically discover your OpenStack environment. ManageIQ uses OpenStack’s APIs and components to perform essential operations, such as analysing current capacity of the cloud, alerting when over-utilization of resources is imminent, and providing reports of trending patterns in the OpenStack clouds.


* **Loic Avenel** *(Working in Software solution for last 20 years in many organisation in various area like Software Management, Harware Management, Customer Communication, Output Management. Join Red Hat in 2014 to embrace OpenSource community ManageIQ.org and Openstack.org. In Product Manager role working how to better integrate Red Hat CloudForms (downstream project of ManageIQ) with OpenStack)*

* **Anandeep Pannu** *(Anandeep has been involved with OpenStack since 2011 and has been at two different companies that do OpenStack distributions.  He has been a speaker at the OpenStack summit previously and has years of experience managing large scale OpenStack deployments at enterprises.   Previously Anandeep was the Program Manager for the Open Source Software Lab at Microsoft, at startups doing big data analytics before the term big data was invented and a researcher at a leading university in the US.   Anandeep has a Masters in Intelligent Systems and a Masters in Industrial Administration from Carnegie Mellon University.)*

Oslo Config as a Service (CONFaaS)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is an highly customizable based on the deployment scenarios. This is accomplished by enabling each and every component of OpenStack to start with Oslo configuration files. In small deployment, its easy for user to login to the deployment nodes such as controller or compute node and update the configuration files. But this become an cumbersome task when the number of deployment nodes multiplies exponentially for supporting larger cloud base. This could be easier if there is common Horizon dashboard or OpenStack CLI to configure the OpenStack components across multiple deployed nodes. In OpenStack there is no such feature exist today. This problem is addressed by introducing new concept 'Oslo Config as a Service (CONFaaS)' to OpenStack.  


* **Kanagaraj Manickam** *(  Huawei Senior System Architect @ Huawei Technology India Pvt. Ltd. OpenStack Core-reviewer @ OpenStack Orchestration Service (Heat) Core-reviewer @ OpenStack NFV Orchestration Service (Tacker) Establishing OpenStack Manager (Namos) Open-O Active participant and contributor in Open-O community)*

* **Mohankumar Navaneethan** *(Mohankumar has been working as Openstack Developer at Huawei Technologies and a member of the OpenStack community for the past 1 year . Actively working in Neutron , Networking-SFC , Horizon and Heat Openstack modules. Been in Software Domain for about 4 years. He holds a MTech in Information Technology from Anna University, Chennai.                                                                     )*

Ease your deployment of OpenStack with the TripleO user interface
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack on OpenStack project is the original deployment management solution for OpenStack. TripleO development is continuing with a vibrant community. And now TripleO provides not only a powerful deployment tool but also now includes an easy to use graphical user interface (GUI).This new interface will help enterprises define deployment plans, register and introspect nodes, and run multiple deployments of OpenStack with a fully integrated, pre-deployment, in-flight, and post-deployment validation mechanism based on Ansible that builds the specified, reliable OpenStack cloud.


* **Loic Avenel** *(Working in Software solution for last 20 years in many organisation in various area like Software Management, Harware Management, Customer Communication, Output Management. Join Red Hat in 2014 to embrace OpenSource community ManageIQ.org and Openstack.org. In Product Manager role working how to better integrate Red Hat CloudForms (downstream project of ManageIQ) with OpenStack)*

* **Anandeep Pannu** *(Anandeep has been involved with OpenStack since 2011 and has been at two different companies that do OpenStack distributions.  He has been a speaker at the OpenStack summit previously and has years of experience managing large scale OpenStack deployments at enterprises.   Previously Anandeep was the Program Manager for the Open Source Software Lab at Microsoft, at startups doing big data analytics before the term big data was invented and a researcher at a leading university in the US.   Anandeep has a Masters in Intelligent Systems and a Masters in Industrial Administration from Carnegie Mellon University.)*

My spider sensu is tingling!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most of the OpenStack core projects are currently considered stable and can be installed plug-and-play fashion. Although most of the time everything seems to work fine, anyone operating an OpenStack environment dreads errors appearing silently in the background where they might stay undiscovered while they are not affecting anybody. Some of these might not be worth looking into, but some of them might cause serious trouble later on.During the last few years, many monitoring solutions have evolved around OpenStack or plug-ins for existing ones have been developed. This session introduces a few Open Source options for monitoring your OpenStack cluster. We will outline the monitoring solution we are currently using at cloudbau and Betacloud, which is based on Sensu, InfluxDB, Grafana, Elasticsearch and Collectd. We will finally conclude why we think that Open Source and community-driven solutions are best suited for monitoring OpenStack environments.


* **Christian Berendt** *(Christian is the CEO and co-founder of Betacloud Solutions GmbH. He is one of the OpenStack Ambassadors, founded the OpenStack user group in Stuttgart / Germany and is part of the OpenStack documentation core reviewer team. In his  time off he occupies himself with software development, artificial intelligence, micro controllers and much more. He is a seasoned speaker at all kinds of Open Source and IT events such as CeBIT, LinuxTag, and various others. )*

* **Jan Klare** *(Jan Klare is the co-founder of the cloudbau GmbH and has been working with OpenStack and automation (mainly Chef) since 2013. He started with very small and experimental deployments in projects for a telecommunication company and became a core reviewer for the OpenStack-Chef project early 2014. As the PTL for the OpenStack-Chef project during the mitaka cycle his main focus was on refactoring and rewriting all core cookbooks. He is currently focused on handling multiple medium sized OpenStack deployments with Chef, as well as deploying and optimizing the needed monitoring solutions (mainly containerized sensu, influxdb and elk). As a bleeding edge technology fan, he is always interested in new things and currently mainly focuses on CoreOS, rkt and kubernetes.)*

Operation tool to make OpenStack operation easy and accelerate operation speed on multi regions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NTT Communications provides the public cloud service by OpenStack which is Enterprise Cloud 2.0(ECL2.0) from this March. Our regions will be Japan, UK, Singapore, US, Australia, Hong Kong and Germany this October. In the near future, the regions will expand to 14. We created our ops tool (Operation Portal) with GUI. Operators who aren’t familiar with OpenStack can operate ECL2.0 and find which customer was affected by failure and when failure happened and was recovered by this tool. Our main target is enterprise customers. The customers in Japan expect high quality operation. ECL2.0 provides IaaS with High Availability. However our customers are not satisfied with only HA. They want a notification. Therefore operators look into failure and send a notification to them by Operation Portal. We will expand operation team to our affiliate company in India for controlling multi regions this October. Operation Portal fills in the gap of operation between Japan and India.


* **Yasutaka Morioka** *(Yasutaka Morioka is System Administrator of Cloud Service at NTT Communications. He is working as system administrator of server and storage of cloud service for six years. And also he worked at Verio, inc. as techinical account manager and cloud system administrator for one year. He graduated from Graduate School of Engineering, Osaka university. Originally he came from Osaka in Japan and likes Osaka local culture and music.)*

* **Shohei Okada** *(March, 2013  Graduated Osaka University. March, 2015  Graduated Graduate school of engineering Osaka University. Majored in the optical fiber transmission and published three papers there. April, 2015 Started working in NTT Communications. Work for service operation of cloud services.)*

* **Kazuma Masuda** *(Kazuma Masuda is working currently with cloud infrastructure as a server engineer. He grew up in the state of Georgia(U.S.) during my youth, came back to Japan for my high school, and started my computer science education during college years. For the 5 and a half years he has been with the company, his role has been a technical engineer for product operations. He has experience as a technical engineer with managed application hosting services, data storage service, and software managed VPN service. He is involved in an operation transition project for an openstack based cloud service to members across the ocean who will be mostly unfamiliar with openstack technology.)*

Performance Analysis of Workloads run with Browbeat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

So you have installed Browbeat - the framework for performance testing, collecting metrics, metadata and results data, now what?  Now you need to analyze your data to find performance bottlenecks, apply tunings, make adjustments and re-run the workloads.  With the Browbeat Framework you can compare all the results data in Kibana and review System Performance Metrics in Grafana for your entire cloud. In this talk we run through Rally and Shaker Workloads and then analyze the results and metrics data.


* **Alex Krzos** *(Senior Performance Engineer at Red Hat working on Openstack and ManageIQ.)*

* **Sai Sindhur Malleni** *(Software Engineer working on OpenStack Performace and Scale.)*

Utilizing an Application-Based Approach for Easier Deployment of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many approaches have been taken to enhance and simplify the deployment process for storage in OpenStack environments. One approach, from partners like Canonical, is to use an application and service modeling tool (Juju) to model, configure, deploy, and manage applications in the cloud, including OpenStack. Come to this session to learn more about the benefits of this approach, the offerings available, and to view a short demo of how Canonical Juju Charms can provide faster time-to-market for EMC ScaleIO customers using Canonical Ubuntu OpenStack!


* **Jason Sturgeon** *(Jason is the ScaleIO Product Manager with a focus to make ScaleIO the absolute best block storage option for OpenStack. Jason has 20 years of experience in Information Technology, he joined EMC in 2008 as part of the Isilon Systems start-up. He has had many different roles in his career from IT Manager, Technical Trainer, Corporate Systems Engineering, but has always had a love for the technical and helping customers use it in the best way possible.)*

* **Mark Brown** *(Mark works at Canonical.)*

Monitoring OpenStack: a comparison
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operators are generally unhappy with monitoring OpenStack in general. There are too many tools. There are too many places in OpenStack that require monitoring.It's not clear how and what to monitor. The amount of monitoring will have a performance impact on the whole cloud. How do you learn information about a host / service that needs monitored beforehand? How can this information be easily / automatically discovered? Traditional service monitoring? Tenant health monitoring? Expose this monitoring to tenants? Provide monitoring as a service for tenants? What is the best approach? a comparison.


* **Roberto Hernando** *(I'm a Hybrid Cloud Architect. I have worked all my career among Systems... Linux.. Windows.. HPUX.. AIX... and how to best monitor them. Right now I'm interested in deploying OpenStack and how to operate it in the best possible way.)*

* **Eric LAJOIE** *(Eric Lajoie is a OpenStack & NFV Architecture Consultant for HP Professional Services (PS) – Helion OpenStack, Germany. In his current capacity, Eric is responsible for end to end solution design, be it IPv6, EPC, or virtualization solutions. His key interests and achievements are in design and implementation of carrier grade Helion OpenStack solutions as well as integration with SDN, EPC, LTE, VoLTE, Femto, M2M, VMware, and all flavors of Linux including RHEL, Ubuntu, Debian, CentOS, and Gentoo. He is responsible for solution, design, service implementation and assessments related to service providers environments. Joined HP Enterprise in December 1st 2014 10 Years of SP Industry Experience in Networks and Telecommunication Solutions. Projects thus far: Telefonica UNICA OpenStack and NFV Project including Nuage/DCN Joined Cisco in September 2005 till end of November 2014 Projects while at Cisco: vGi-LAN virtualization proof of concept in Germany EPC field support and enablement in Japan EPC solution design in France IPv6 M2M design & implementation in UK Team Lead for Cisco's first EPC Pilot Projects in Norway IPv6 Assessment lead in Nigeria implemented IPv6 technologies CSG2 with DPI and GGSN optimization and design in USA Femto Design & Implementation in USA. CSFB Integration with Mavenir IWF in Düsseldorf Germany Industry Recognized Certifications: BS in Electrical Engineering CCNA, CCNP, CCDA, CCDP, CCIP VCA-DCV Wireless# Programming for Everybody (Python) by University of Michigan on Coursera)*

BYOS with Ansible: Adding 3rd-party services to your cloud without being broken by upgrade!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We’ve got to the point where a fully automated deployment of OpenStack is not such a big deal. We might even say that we have solved the upgrade problem; maybe not quite as seamless as we’d like, but definitely getting easier. Let’s say you have deployed a private cloud and would like to integrate Neutron with your favourite SDN, which requires additional plugin code, config settings, etc. Or maybe you also need to deploy your own inventory management service across the cloud, which requires certain ports to be open. How do you do this in a way that isn’t broken the next time you upgrade your OpenStack distro? In this session, we will discuss an approach to this problem based on an Ansible framework for deployment and general lifecycle management of the cloud. We will detail how we allow consumers of our private cloud solution to make changes to OpenStack services for integration of different 3rd-party plugins/drivers, with the integration of Neutron and OpenDaylight as an example.


* **Tom Howley** *(Tom is the Tech Lead for the HOS (Helion OpenStack) lifecycle management component, see https://github.com/hpe-helion-os. Prior to this, Tom worked on HP's Public Cloud, initially working on the block storage solution and later focussing on HA across the cloud. Before entering the world of cloud, Tom worked in data analytics in the telecom sector and also co-founded a startup (https://www.analyzeiq.com/) based on his research into machine learning, in which he holds a PhD.  )*

* **Darragh Bailey** *(Both in work and during free time for fun, spend time contributing to jenkins-job-builder, git-upstream (author), and multiple vagrant projects include vagrant & vagrant-libvirt. Most recently working on HPE's Helion OS, specially the Helion Lifecycle Manager, which involves extensive use of Sensible to deploy OpenStack. Focused on extracting the most from Ansible and providing a stable dev env for others to deliver integrated OpenStack services. Prior involved with HP's Public Cloud offering, helping many teams utilizing CI/CD to deliver code to production on a daily basis. Has worked extensively in supporting building of highly scalable solutions, starting as the Build and Release engineer for Scalable FileSystem (Lustre), HP's offering for a high performance file system in the HPC space. Subsequently working on large storage with HP's Extreme Data Storage 9100, followed by a common platform for HP's StorageWork's data storage solutions. Outside of work, enjoy travelling (visited 6 of 7 contintents - not yet seen Antartica), hiking which has taken me to Kilimanjaro, and training in TaeKwon-Do. Spend)*

* **Jan Grant** *(jan's worked for HPE on Openstack for a few years: initially on Nova, then TripleO, and now on HPE's Helion system - particularly on the tooling around deployment and upgrade,)*

Learn how to use Nagios and StackStorm to automate the recovery of OpenStack services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

I will explain why and how I created an automated deployment of a test environment using Vagrant and Ansible to deploy and configure it. The background behind this is that I needed a reliable test environment for testing new deployments and upgrades as well as running OpenStack demos.  Occassionally I found the demo environment had developed an issue just before I ran a demo so I needed a way to monitor it and ideally get it 'self heal' so it would always be ready to go. A live demo (praying to the demo gods) will show the automatic recovery of services following a simulated failure. All materials will be made availabe after the talk enabling the re-creation of the test environment.


* **Geoff Higginbottom** *(Geoff is an industry recognised expert in Cloud Computing and has designed and built numerous large scale private and public cloud infrastructures.  His IT career spans 18 years, covering all aspects of IT Design, Implementation, Project Management and Support.  Geoff has been a regular speaker and panelist at a multitude of Cloud events covering various cloud technologies including Storage, Networking, Configuration Automation, Design and Training.  Currently Geoff is helping Rackspace customers realise their ambition of deploying OpenStack Private Clouds anywhere in the world.)*

Exploiting best of Crowded Automation Tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack comes up with a lot of choices when it comes to deployment and orchestration managment e.g. heat, chef, puppet, juju, maas, fuel, dockers, kubernets, ansible, Kolla, Mistral etc. There is a big mess around users about what to use when and which one is suitable for what kind of requirements. In this presentation, I would like to discuss and explain more on usage of these tools, their comparative study and recommendations/best practices for different deployment/automation/orchestration requirements. 


* **Abhinav Agrawal** *(Working at capacity of Solutions Architect (Storage and Cloud Technologies) with NEC Technologies India Pvt. Ltd having overall more than 10 years of experience, primarily into storage and virtualization domain. Member of NEC's HS Series seondary storage development group (HYDRAstor). Have been leading product team which developed several key features in disk based distributed storage (secondary). Recently started leading team having many openstack community contributors including couple of core community members.)*

Using a Cloud Management Platform for Day Two Openstack Operations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack currently uses Horizon as the GUI for cloud management. However, Horizon is not built with the enterprise users in mind. Organizations operating an OpenStack cloud have many needs that current OpenStack tooling doesn’t meet. This is where a true cloud management platform can help.By having a cloud management platform manage your OpenStack environment, you will be able to deal with the needs of an enterprise environment: approval workflow, compliance, self-service, chargeback, quota enforcement, resource management, capacity planning, optimization, configuration management, etc. In order to add all of these things on top of your OpenStack cloud, you need a cloud management platform.Red Hat CloudForms is a cloud management platform that offers unified management for hybrid environments, providing a consistent experience and functionality across container-based infrastructures, virtualization, and private and public cloud platforms.


* **Lucy Kerner** *(Lucy Kerner is a Senior Cloud Solutions Architect for the North America Public Sector team at Red Hat. In this role, she supports the Red Hat cloud sales efforts by presenting and designing Red Hat cloud solutions for a wide range of U.S. Public Sector customers. She has over 10 years of professional experience as both a software and hardware development engineer and a pre-sales solutions architect. Prior to joining Red Hat, she worked at IBM as both a microprocessor design engineer for Mainframe microprocessors and a pre-sales solutions architect for IBM x86 servers. She has also interned at Apple, Cadence, Lockheed Martin, and MITRE, where she worked on both software and hardware development. Lucy graduated from Carnegie Mellon University with a Master of Science (M.S.) and Bachelor of Science (B.S.) in Electrical and Computer Engineering. She also graduated from Carnegie Mellon University with a Minor in Spanish.)*

* **David Huff** *(David is a senior solutions architect at Red Hat, and Team Lead for the Public Sector Virtualization and Cloud specialist group focusing on OpenStack. David has been at Red Hat for over 12 years, and has held several different roles including product development on some of Red Hat's earlier Virtualization projects.  Currently David works exclusively with the public sector supporting both federal and local customer as well as higher ED customers. )*

Deployment as a Service - Introducing Stack360
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Stack360 is a public web service that deploys private infrastructure in Software Defined Data Center(SDDC). It uses OpenStack Ironic for bare-metal provisioning, and OpenStack Compass for OpenStack or OPNFV clusters.  In this talk, we introduce the main features of Stack360, such as cloud-based deployment of infrastucture from blueprints, configuration versions, and graphical web interface for management, providing Infrascture as Code(IaC) capabilities. We also share our experience in integrating Cobbler, OpenStack Ironic, and Compass by adding remote management capabilities.  


* **Weidong Shao** *(Weidong Shao is leading Compass project, an open source project for OpenStack deployment automation.  He is active in both OpenStack and OPNFV programs. He has over 20 years of experience in software development and system architecture. He currently works at Huawei on integration, NFV solutions and partner development based on open platforms and open source technologies. )*

Deploying Cloud Applications the right way, using heat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Heat mission is to manage the entire lifecycle of infrastructure and applications in OpenStack.At Red Hat we have used Heat to deploy a number of hello-world application to Enterprise Grade application, fully automatic, almost in zero-touch provisioning way and even providing support for the application migration, from the legacy world to a cloud-oriented way.This talk will explain you how to use Heat to deploy even quite big applications, giving some trick and sharing our knowledge.


* **Krist van Besien** *(Hi there, this is Krist from Red Hat. I'm an Architect focused on OpenStack for the EMEA region.)*

Monitoring in Scale with Auto Self Resolving Framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Practically ever large cloud environment uses monitoring to capture events in the system. In this presentation, we will describe how we use Sensu monitoring in our large scale deployment and how an auto resolver framework can help reduce operational impacts.


* **Chris Doan** *(None)*

Collectd, InfluxDB & Grafana used to meter OpenStack base infrastructure and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

To be able to debug complex systems, investigate on their performance and to do capacity planning, metrics of the various components in your cloud are getting very important. While Ceilometer provides metrics and events of OpenStack related components, Cloud Platform Engineers require insights that go beyond that and also need metrics from base infrastructure and services. Thus Swisscom deployed collectd and makes use of its many plugins to collect basic system metrics as well as metrics from services such as HAProxy or RabbitMQ. The metrics are stored and down sampled over time in InfluxDB. In the end Grafana is used to browse and analyze the metrics.In this talk I will introduce the architecture of our metering setup and share the experience with it.


* **Janosch Rohdewald** *(Janosch Rohdewald is working as an OpenStack system engineer at Swisscom. Having a storage related background, he has a strong focus on cloud/software defined storage.)*

Optimizing OpenStack Performance with Genetic Algorithms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Optimizing OpenStack for api response time and minimal instance-to-instance latency is a difficult and time-consuming process, but has an enormous long-term impact on user satisfaction. Operators must balance dozens (or hundreds) of values, and many of these values impacting other parts of the system in unexpected and often suprising ways. We explore this "emergent behavior" for further optimizations by applying a genetic algorithm to the configuration superset of an OpenStack deployment.


* **John Perkins** *(John David Perkins is a Software Developer at Rackspace on the OSIC team and active contributor to Openstack. He received a B.S. in Computer Science from the University of Hawai`i at Hilo in May of 2013. While earning his degree, he volunteered to manage the resident supercomputer, Huinalu, delivering a bespoke Rocks Cluster distribution, and wrote genetic algorithms to complete research for the National Science Foundation that involved physics models and GIS map data to predict avalanche flows. Johns passions include cloud computing, OSS, and volunteerism.)*

Automation for a deployed service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Services deployed using openstack rely heavily on the infrastrcuture for its application delivery. This talk focuses on automation areas which encompass the infrastructure elements and the application of a deployed service inorder to provide continuous reliability and predictability.     


* **Girish Sivasubramanian** *(Girish is a system architect with HCL America working a consultant for CISCO Systems)*

Validation and benchmarking your OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

After deploying OpenStack successfully, one of your first tasks should be validating and testing the deployment. This session will cover how to use Tempest, an OpenStack integration test suite, to test and validate your OpenStack deployment. We’ll also discuss how to benchmark an OpenStack deployment using Rally. We will also look into benchmarking cloud application templates, and testing scalability and performance.


* **Mayur Shetty** *(Mayur Shetty is a Senior OpenStack Solution Architect on Red Hat's OpenStack Tiger team. Prior to joining Red Hat, Mayur worked as a Solution Architect with Seagate focusing on OpenStack Swift, Ceph storage, and other Software Defined Storage.   He also spent 4 years at IBM as a ISV Engineer working with Oracle Database and IBM Mid-range and Enterprise Storage. Before that he was at Sun Microsystems in the Sun Cluster team, and later ISV Engineering team where he worked on Sun Systems and Storage.)*

Detecting Black Holes and Micro-bursts with Telemetry Tools for Application Assurance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Service Level Agreements (SLA) for applications are often taken for granted as connectivity and traffic management just works without any glitch. However, when problems arise, tracing packet flows and root causing issues are very complicated in cloud networks by virtue of technologies involved, further complicating application SLA compliance in cloud networks. With multi-tenant networks, ensuring application SLAs is a critical aspect of design as various applications/organizations share the same physical and virtual infrastructure resources. This session will address the following topics: Monitor micro-bursts, traffic flow for application SLA Packet tracing and injection for root cause analysis   Mapping overlay and underlay packet flows Scaling monitoring and analytics for high density data centers


* **Bhaskar Chinni** *(Bhaskar is eesponsible for BroadView Instrumentation Software Suite, he has established an ecosystem for BroadView enabled analytics solutions.)*

* **Syd Logan** *(Syd currently works in research and development related to OpenStack and switching platform APIs. Python, some C, Ruby, SWIG. OpenStack Ceilometer, Monasca, Neutron, devstack, ML2 plugins. Ubuntu, RESTful APIs, JSON, Django, HTML, JavaScript, Lua, JQuery, Computer Networking, VXLAN, GRE, Open vSwitch, VTEP, cunit, OVSDB. Tech lead on three OpenStack github projects supporting Broadcom BroadView instrumentation.)*

* **Justin Moore** *(Justin Moore is a Principal Solutions Architect at PLUMgrid specializing in developing Cloud and SDN strategy and architecture for the enterprise. Prior to joining PLUMgrid, Justin served as a Sr. Director for Enterprise Growth at American Express, establishing and leading the Cloud and DevOps functions. At American Express, Justin led the creation of the Cloud cost model, Hybrid Cloud strategy, and PCI certification of the card processing environment. The adoption of the Cloud model led to significant cost savings over the legacy environment, as well as significant reduction in time to market for new business features through tight integration with the CI/CD pipeline.)*

Framework to automate operational steps for failure handling
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In a deployed service when application, process or infracomponents fails, alarms indicate this failure and the operations teams respond to the failure. This talk provides a framework to automate oprerations steps carried out for a response handling. intervetion from the operations team is needed only for critical failures


* **Girish Sivasubramanian** *(Girish is a system architect with HCL America working a consultant for CISCO Systems)*

Big Data use cases in Emerging Markets based on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We will talk about the use of great modeling tools to reduce the operational cost on Big Data use cases for emerging markets. Due the great CAGR and general growing in the Big Data market, the proposal and creation of new products and services in the region are demanding great tools to design, deploy and operate them, we will address these topics for a general audience.


* **Omar Lara** *(Omar comes from the Sysadmin/Devops mindset and takes advantage of Open Source Software and Python programming to help creating profitable business cases for CxO and users introducing new paradigms in terms of scale out economics and Devops tools, as well as creating high skilled talent for emerging markets. Omar deployed the first Latin American cloud based on OpenStack and has established an extensive career in the field of Cloud and OpenStack in emerging markets.)*

ARIA - Simple, Open Orchestration for OpenStack and Other Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

ARIA is an open, light (serverless), zero-footprint CLI-driven library of orchestration tools that other open projects can consume to easily build TOSCA-based orchestration solutions. With tight integration for OpenStack and conforming to TOSCA interoperability standards, ARIA’s open source and open governance project is a perfect fit for orchestrating application deployments on OpenStack along with other clouds in a hybrid environment.


* **Arthur Berezin** *(Arthur Berezin is an active member of the OpenStack community and a hands-on OpenStacker since the early Essex release of OpenStack in 2012. During this time Arthur has built multiple production data centers based on OpenStack, helped dozens of organizations in planning their OpenStack environments, and in executing their software defined data center strategy. Prior to OpenStack, Arthur worked on KVM virtualization management project oVirt/RHEV and open source virtualization management technologies for mission critical environments. Arthur is the Director of Product for *Cloudify* at GigaSpaces working on an open-source and open-standard cloud application orchestration platform with cloud aware applications in mind that run natively on OpenStack and other private and public clouds. Prior to Cloudify, Arthur was a Senior Technical Product Manager for OpenStack at Red Hat and Product Owner of Keystone, Heat, Horizon, RHEL OpenStack Platform Installer (Foreman/Puppet based Project Staypuft), Packstack, and OpenStack High Availability. In the past 14 years, Arthur has served in various management and technical positions in the high-tech industry, including working as a founder and technical lead of a start up, a product line lead, Linux consultant, technical pre/post sales, and as a Linux Instructor for Red Hat Certified Engineer (RHCE) exams. You can find Arthur on Twitter as @ArthurBerezin or on his blog at www.Berezins.com.)*

How to charge your clients?
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

After the deployment and the integration of an OpenStack environment it is a common use case to charge the users for provided and consumed resources, regardless of whether it is a public or a private cloud. While there are feasible metering services in OpenStack, billing and rating based on the metering data still is a major nuisance. We will outline the existing metering and billing solution we evaluated for the use at Betacloud and show how we integrated one solution with an online service for quoting and billing.


* **Christian Berendt** *(Christian is the CEO and co-founder of Betacloud Solutions GmbH. He is one of the OpenStack Ambassadors, founded the OpenStack user group in Stuttgart / Germany and is part of the OpenStack documentation core reviewer team. In his  time off he occupies himself with software development, artificial intelligence, micro controllers and much more. He is a seasoned speaker at all kinds of Open Source and IT events such as CeBIT, LinuxTag, and various others. )*

Adaptive OpenStack Troubleshooting: Bridging the gap between logging and monitoring
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Attend this session to know about an automated system that integrates Monasca and logging services to provide the right context for an operator to triage issues. This involves creating a log handler component that listens, detects issues and configures the log levels based on the current state of issues.  A logging agent runs on service nodes and tracks the log level of services. It periodically communicates with the monitoring service over a secure channel. Any error detected in the centralized log metrics by Monasca would automatically trigger an alarm along with a feedback to the logging agent running on relevant hosts to switch the log level. This provides context in the centralized log messages when an operator watches the logging dashboard. Once the issue is resolved, Monasca auto detects this and switches the log level of the service. A Horizon dashboard will be provided to the operators to control log levels for services on demand. The session will conclude with a live demo!


* **Venkat Sundaram** *(Venkat Sundaram (TSV) is a senior software engineer with Hewlett Packard Enterprise working on developing Openstack based cloud for Enterprises - Helion Openstack  (http://www8.hp.com/us/en/cloud/helion-overview.html?jumpid=va_uezi8g75dv) TSV is the lead engineer for Helion Centralized Logging Solution using the ELK stack and Monasca. In this role, he contributes to the monasca-log-api project. He has also contributed to the development of a monascalog transport the open source logging agent, Beaver. He has contributed in the past to Keystone and Barbican projects. He has been working with Hewlett Packard for over 18 years and have a rich experience in developing and managing software for Enterprises.)*

* **Rajesh Gwalani** *(Rajesh is a seasoned product leader in the Cloud world and has successfuly built and delivered SaaS, PaaS and IaaS offerings since 2005. He is currently focussed on improving the maangeability and operabiity apsects of OpenStack to help operators run highly available, scalable, secure and cost-effective hybrid clouds for Enterprise, Telco/NFV and Service Provider segments.  )*

* **Heather Paschall** *(Heather Paschall is a software design engineer with Hewlett Packard Enterprise working on developing Helion Openstack. She is a member of the Helion Centralized Logging team which leverages the Elastic Stack and Monasca. She has contributed to the development of the monascalog transport for Beaver to ship logs to the monasca-log-api.  Heather joined Hewlett Packard enterprise in September 2015 right after graduating from college at the Colorado School of Mines. )*

3rdparty Openstack CI - testing NFV and SR-IOV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

“If something is not tested is broken” is what you hear when you try to add a new feature to Openstack. Most often you provide tests along with your code to be run by upstream Jenkins. When a custom hardware or non-standard software configuration needs to be tested - it’s the vendor’s adventure from here.   How to deploy, configure and what are the challenges setting up 3rdparty Continuous Integration (CI) for Openstack? What are the tools provided by Openstack Infrastructure Team for this purpose? How to do it in a corporate environment? Two hardware vendors will tell their stories how they did it to test SR-IOV and NFV features in bare metal and VMs.   Keywords: sr-iov (sriov), nfv, zuul, gearman, jenkins, devstack-gate, nodepool, proxy


* **Waldemar Znoinski** *(Experienced linux sysadmin, Informix DBA sysadmin and devop of financial applications. Openstack engineer since 2014, keeping Intel NFV 3rd party CI running.)*

* **Moshe Levi** *(Moshe Levi acts as a Cloud Solutions Engineer at Mellanox Technologies. Leading the Mellanox integration with OpenStack, in which puts contribution to OpenStack projects, including Neutron and Nova, at the field of Single Root I/O Virtualization (SR-IOV) and Openstack high performance features deployments. Before his current position at the Cloud solutions team, Mr. Levi worked at Mellanox SW management teams, with developing large scale networking projects and SDN oriented POCs.)*

Cloud Management Platform lowers the threshold for adopting OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is now penetrating data centers at both corporates and service providers. Making the most efficient use of data center assets is a key strategy for successful enterprises. OpenStack is an attractive new innovative alternative. However, when planning how to deploy OpenStack, one must consider how it can co-exist with other virtualization and cloud technologies already in place. How to accomplish this and avoid unwanted complexity is a challenge.


* **Michael van Buren** *(None)*

Peeling Back The Giftwrap: How to deploy a custom and consistent OpenStack every time
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Giftwrap is an OpenStack big-tent project that allows operators and developers to build, deploy, and upgrade OpenStack environments with ease.  IBM Blue Box has a long history of delivering consistent OpenStack environments in a continuous delivery fashion, and Giftwrap has been the tool that makes this all possible. In this session we will take a deep-dive into how Giftwrap enables an operator to deploy custom OpenStack system packages and/or containers. We will pull back the curtain and provide demonstrations on how to perform a major OpenStack upgrade as well as how to ship custom code in a reliable and repeatable manner.   


* **Craig Tracey** *(With over fifteen years of experience building scalable, automated infrastructure solutions, Craig serves Lead Architect for IBM Blue Box. In his role, Craig leads a team responsible the development of OpenStack-based on and off-prem private cloud solutions.  His focus includes everything from operations, support, and new feature development for all production OpenStack environments. Prior to Blue Box, Craig was the Cloud Automation Technical Lead at HubSpot where he designed software solutions for delivering SaaS products on top of a variety of public cloud offerings as well as home-grown private OpenStack implementations. Prior to HubSpot he helped engineer Carbonite's backup solution to over 60 petabytes and at VMware maintained network device drivers for both ESX and vSphere. Craig is an active contributor to a number of cloud ecosystem projects including OpenStack, Neutron, Nova, Giftwrap, cloud-init, Ursula and Chef for OpenStack. He holds a Bachelor of Science degree in Computer Science from Providence College and is based out of Boston, Massachusetts.)*

Audit Logging framework for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

An effective audit logging mechanism assists the cloud operators in maintaining smooth operations. In this session you will be introduced to an audit logging framework for OpenStack which spans across cloud, computes, tenants and storage to provide actionable audit logs to the cloud operators


* **Vivek Agrawal** *(Vivek Agrawal is a technical lead for emerging products in Veritas Technologies LLC. He is also a contributor for OpenStack Horizon project. He has good experience in developing the UI for enterprise class products.)*

* **Rakesh Ranjan** *(Rakesh Ranjan is a Technical Lead/Architect in the emerging products division at Veritas Technologies.)*

Adiuvo Bot - Smart DevOps using bots for effective triaging and Operations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Bots are intelligent agents that are designed to assist humans in specific tasks while monitoring and learning key behaviors. Bots like Siri and Echo have popularized the emerging area of smart chat bots. We would like to highlight a smart way of using chat bots in the space of Ops monitoring and DevOps. A few direct applications include: repetitive mundane tasks (disk cleanup, workflow based jobs etc.), system health monitoring, using Chat logs for effective triaging, creating post-mortem reports and learning from knowledge bases. Using analytics and smart rules, bots enable constant learning of system behavior and can be empowered to take smart decisions.  The holy grail in this world of bots is to remove the human, and let the bots take control of the operations!   We would like to invite the community to get involved and help us drive a Bots revolution in the Openstack Ops community. For more details: https://wiki.openstack.org/wiki/AdiuvoBot


* **Yathiraj Udupi** *(Yathiraj Udupi is a Technical Leader of Engineering in the Office of the Cloud CTO at Cisco Systems working on OpenStack, BigData,  related projects.  He is actively executing and leading in building large scale, efficient cloud and streaming big data architectures with an emphasis on operational intelligence, monitoring, smart alerting, streaming analytics, and optimized cloud resource and workload placements (scheduling). He is an active Openstacker with interests in the projects such as Nova, Monasca, Telemetry. Yathiraj Udupi received his PhD in Computer Science from North Carolina State University where his research interests included Multiagent systems, Policy-based Management, Distributed AI.  He received his Bachelors (BTech) from the Indian Institute of Technology Madras (IITM) in Computer Science.)*

* **Rahul Ramakrishna** *(Rahul is a software developer @Cisco Cloud, where he primarily works on data streaming problems and building distributed and robust data pipelines. He graduated from University of Massachusetts, Amherst in Computer Science. As a part of Database and Information Management lab, he worked on package builders which is a system that tries to understand losely defined constraits and helps users navigate to intended  solutions in the search space. Prior to that he worked @ Yahoo! sports, where he worked on developing operations tools, monitoring applications and scaling cloud application platforms over large server farms.  In his free time, he keeps tinkering in Databases, Distributed Systems and Machine Learning for Bots.)*

Beyond Horizon - Moving the Dashboard to a UX that works
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  For years, Horizon has been the undisputed official Dashboard for Openstack, being the very recognizable web interface that serves many private and public cloud providers. But it still brings many unresolved pains: coupling of front-end and backend prevents designers to provide innovative interfaces in modern frameworks (e.g. 3REE), and a "skin" approach the UI/UX is designed by and for sysadmins, and does not consider other use cases no support for popular third party (non Openstack) software solutions for queue management, logging, monitoring, containers, security etc. no addressing of public providers' needs in terms of customer management instead of simple "users": billing, pricing advertising, reporting, charts etc are vital to a proper UX for customers. In this session we will provide a complete overview of a brand new open source project for a modular, extensible, reactive, appealing Openstack dashboard solving most of the pains above.


* **Mariano Cunietti** *(After serving for several years as an enthusiast Linux system administrator in an ISP environment, Mariano became CTO at Enter.it and in 2011 started the company first Openstack based project running on Essex (cloudup.it and selfserver.it) On August 2013 the first italian region for EnterCloudSuite.com (ECS) was launched. It was the first public IAAS running in Italy on Openstack, one of the first in Europe. On April 2014 the German and Dutch region followed. On October 2015, EnterCloudSuite was awarded by the EU Commission to be an official provider of public IAAS to the 52 EU Institution. Before running open source infrastructure, Mariano earned a Master of Arts in Classical Guitar, and almost one in Greek and Latin Literature. )*

* **Gabriel Adrian Samfira** *(Gabriel has been involved in systems engineering and operations for the past 10+ years, mixing systems administration with development whenever needed. He has a background in deploying and managing large scale web services mostly on GNU/Linux systems. In 2013 he became part of an amazing startup called Cloudbase Solutions which focuses on cloud computing interoperability. Based in Timisoara, Romania, Cloudbase Solutions provides integration between OpenStack and Windows, including the Hyper-V Nova Compute driver and Cloudbase-Init (Cloud-Init for Windows). He is currently the technical lead of the team responsible for automating the deployment of Microsoft workloads both in OpenStack as well as on top of OpenStack and various other scenarios.)*

Extending OpenStack-Ansible with Automated Operational Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The IBM Systems Cloud Solutions Group helps many customers realize their own private OpenStack Cloud infrastructures. Recently we looked into how to best handle this task using exclusively open community solutions. For provisioning we settled on the OpenStack-Ansible project. We have used it heavily and became familiar with its strengths and weaknesses. In addition we had to complement our solution with open DevOps tools to fulfil Operational Management aspects, such as Monitoring, Log Collection & Analysis, Performance, Scalability, Discovery and Inventory Management, among others. In this session we share our findings. In particular we show our approach to integrate a stack of Ops tools with OpenStack-Ansible for automated deployment and configuration. We also discuss how to adjust the Ops configuration elastically in order to achieve immediate coverage after our Cluster scales or when it is reconfigured. We expect that our experience and ideas will help similar endeavors.


* **Marcelo Perazolo** *(Marcelo Perazolo is the Lead Software Architect for Operational Management in the IBM Systems Cloud Solutions Group. He is located in the IBM Software Lab in RTP, NC, and has received his MSEE and BSEE degrees from UNICAMP, then started his professional career at IBM in 1990, accounting for more than 25 years of professional experience with Infrastructure and Platform Management solutions. He drives planning and strategy for IBM's Systems Management team to exploit Open Systems Software and OpenStack to build Converged and Hyperconverged Infrastructure solutions. He is active in multiple Open organizations, such as OpenPOWER, OASIS and DMTF and focuses on furthering IBM's Open Systems agenda, and to drive open management capabilities into converged and hyperconverged infrastructure system solutions in the marketplace.)*

99.99 success is too small: measuring Nova build failures
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud providers regularly provide statistics about the "number of 9s" they havefor API uptime. This can help attract enterprise customers that care aboutreliability. This talk shows how Rackspace goes a bit deeper internally in calculatingthe percentage of builds that fail in Nova, covering our current technicalsolution, how this has helped us discover failure scenarios and prioritize bugfixes, and what the future of build success measurement might look like. Technologies used in the system to calculate build failures include Novanotifications, Stacktach, Logstash, and Elasticsearch. Periodic synthetic buildsto emulate customer experience also run to catch errors that wouldn't bevisible from within the control plane, like network failures after an instancegoes active or issues within the deployed image. The goal of this talk is to encourage operators of OpenStack, especially thosewith large deployments, to measure reliability accurately.


* **Mario Villaplana** *(Mario Villaplana is a software developer at Rackspace working on the OnMetal team, which provides a public baremetal cloud using OpenStack Ironic. He graduated from Stanford University in 2014 with a degree in Computer Science, focusing on Artificial Intelligence, but has since focused almost exclusively on the cloud and OpenStack. He works on upstream development reviewing code, fixing bugs, and writing and implementing specs. Downstream, he helps operate OnMetal and writes code to automate operational tasks whenever he can. He lives with his fiance, Brandon, in San Antonio, TX, but they will soon be moving to Denver. Hobbies include reading, studying languages, and running.)*

From Bare Metal to CMDB: ITIL as Code
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has demonstrated the usefulness of an infrastructure controlled as Code, through the usage of standard APIs usable from a great variety of tools (Web dashboard, CLI and Programmatic tools). But operators need to go one step further. And today the technology and the tools are there to help them bridge the gap. With a new Open Source project called Alexandria, we aim at providing a multi-purpose aggregation brick bridging the gap. It combines, through drivers, OpenStack components such as Ironic, standards such as Redfish for HW Compute resource and CMDBs such as the Open Source iTop to provide to customers a full end to end "ITIL as Code" solution. This allows operators to keep the benefits of their ITIL approach, with a central tool gathering assets, relationships, impact measurement, incident management, ... and to have a fine grained control of their infrastructure... as code. Some recorded demo will be presented to illustrate the promise of this approach.


* **Bruno Cornec** *(Bruno Cornec is Engineer of the French Ecole Centrale de Lyon. (1987)He has been managing various Unix systems since 1987 and Linux since 1993 (0.99pl14).Bruno first worked 8 years around Software Engineering and Configuration Management Systems (Build systems, Quality tools) in Unix environments.Since 1995, he is Open Source and Linux (OSL) Technology Strategist and Evangelist, initially for an HPE reseller and since 2000 for Hewlett Packard Enterprise directly in the EMEA Customer Innovation Center. Bruno is also HP WW Linux Community Lead, OSL Advocate, Helion MVP and RHCE. Bruno is a contributor in various OSL projects: MondoRescue (2001), Mageia (2003), LinuxCOE (2006), Pause (2007), Tellico (2008), FOSSology (2008), collectl (2009), Ironic (2015), python-redfish (2015). He is also project leader for MondoRescue (GPL disaster recovery solution, 2005), dploy.org (GPL deployment server, 2006), project-builder.org (GPL build service, 2007), UUWL (LGPL/MIT Unix to Unix Wrapper Library, 2011), PUSK (GPL ProLiant USB Setup Key, 2012), python-redfish (2015). He is a member of the Solution Linux/OWF/POSS Conference Board since 2006.He is also a board member of the AFUL and OpenStack-fr associations. As part of his work he has made numerous presentations for Solution Linux in France, Libre Software Meeting, NordU, Linux World UK, Linux Expo Milano, Linux.Conf.au, OSCON, Linux Symposium, Fosdem around various topics (High Availability, Deployment solutions, System management, Disaster Recovery, Package building, Cloud...) Outside computers, Bruno also likes early and baroque music, singing and playing the recorder. He's married and father of 3 kids.)*

* **Jérôme Justet** *(Jérôme is an HPE Helion OpenStack delivery expert)*

Self-Evaluation Tool
~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It is basically a Openstack setup evaluation tool. Once Openstack (+related services) gets deployed successfully, it will evaluate all the possible configurations and intercommunication between various services and infra components. This will identify any existing problem and suggest some possible fixes as well.


* **Girija Sharan Singh** *(Having around 4 years of work experience in Software Defined Networking.I enjoy working in fast-paced environment. I am an acknowledged trouble-shooter and I believe I possess the ability to do research and find solutions to complex problems.I hold a Master’s degree in Computer Science from Department of Computer Science, University of Pune, India.Currently working as a Software Engineer in Juniper Networks India Pvt Ltd. I am a part of Cloud Services Platform team working on exciting cloud products. Prior to that, I also worked in One Convergence Devices Pvt Ltd, a high growth startup which offers products and services in the general domain of SDN & NFV and has been one of the key co-contributors for the Group Based Policy in Openstack. I was part of DevOps and Testing team and was responsible for deployment and automation testing of our product. I’ve been fortunate enough to be involved in many SDN related technologies since initial days of my career; like Openstack, Open vSwitch, OpenFlow, VXLAN, Virtual Appliances, etc. Currently, also working on Customer Premise Equipment, Docker Containers, Robot Framework, etc. Would love to continue in this exciting domain and enhance my expertise level.)*

Charming OpenStack: Capturing OpenStack operational knowledge in code
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session is a developer focus explaining what charms are and how to charm an OpenStack project to have it interrelate with the existing OpenStack charms. OpenStack charms attempt to capture the best practices and operational knowledge into devops code. The focus of the charm is on enabling users who may have little to no knowledge of a particular project to model, configure and deploy that project along side the core OpenStack services.The OpenStack Charms project is a new member of the Big Tent. The session will also cover how to participate in the OpenStack Charms project: how to hack on existing charms and how to get a new charm into the project.


* **David Ames** *(OpenStack Charm Developer working for Canonical. Interested in deploying OpenStack and managing the entire life cycle, modeling and deploying workloads on Openstack, and participating in the OpenStack community.  )*

* **Liam Young** *(Liam works at Canonical on deploying OpenStack with Juju and charms. Before that he worked as a System Administrator supporting a number of private OpenStack clouds among many other things.)*

Reclaim those unused instances, images: Mors - Lease Management for OpenStack objects.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A large section of OpenStack is used is for running Dev, Test or Sales lab. Lab means creating a large number of objects (Instances, Images, Volumes, etc). OpenStack makes creating these objects really easy, but deletion of unused items is always forgotten. Introducing Mors - a simple service that will help reclaim precious computing and storage resources. Using Mors you can set up expiration lease policies on Instances and Images per tenant, upon expiration of the lease Mors will warn owners of images or instances. Users will be able to extend their expiration leases in a constrained manner, failure to do so will mean Mors will either power-off or delete the instances. It is simple to understand and very effective. In this talk author would present how to configure and user Mors for your own OpenStack environment. Furthermore, you will also learn how to add support for more OpenStack objects to the Mors framework and extend it further.


* **Roopak Parikh** *(Roopak Parikh is one of the Co-founder and CTO at Platform9 Systems Inc. Platform9 Systems is one of the OpenStack distribution and service providers. Prior to Platform9 Systems Roopak help technical leadership roles at VMware helping them build various management products including vCloud Director (VCD).)*

* **Susmitha  Kanakamedala** *(Susmitha likes to work on system software, solve hard problems. She works on Nova, Glance & Keystone projects at Platform9. She contributed heavily to Mors (a new lease system for OpenStack objects). In past she spent time working on Resource management problems at VMware and working on networking aspects at Cisco.)*

It’s 2016, Cloud is Advanced and Your Orchestration Engine Needs a PhD
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operations and Management has for too long been seen as the harbinger of doom for IT. Much of this is because the greater advances in technology are driving higher demand for IT management capability. These demands have gone beyond a human ability to analyze innumerous elements and swiftly take the appropriate course of action. This lead Accenture to introduce the “Intelligent Orchestration Engine” for OpenStack. Accenture begins by giving the orchestration engine a PhD. in data analytics and performance optimization. The addition of intelligence combined with the workflow requirements has created a holistic and enhanced approach to automation and orchestration. These orchestration workflows algorithmically make decisions that solve inefficiencies before they become incidents or problems. This approach allows Accenture to close gaps found in traditional orchestration and take a homogeneous approach to managing the business, technology, and compliance needs.


* **David DeWan** *(System architect at Accenture under emerging technologies. Leveraging a data analytics background to provide solutions to technology and business demands for global clients.)*

Request Tracer
~~~~~~~~~~~~~~

**Abstract:**

This Request Tracer will help the user to trace down the life cycle of their requests from its origin to result/failure.This will also help beginners or users to understand the internals of exact workflow and that too in sequence.


* **Girija Sharan Singh** *(Having around 4 years of work experience in Software Defined Networking.I enjoy working in fast-paced environment. I am an acknowledged trouble-shooter and I believe I possess the ability to do research and find solutions to complex problems.I hold a Master’s degree in Computer Science from Department of Computer Science, University of Pune, India.Currently working as a Software Engineer in Juniper Networks India Pvt Ltd. I am a part of Cloud Services Platform team working on exciting cloud products. Prior to that, I also worked in One Convergence Devices Pvt Ltd, a high growth startup which offers products and services in the general domain of SDN & NFV and has been one of the key co-contributors for the Group Based Policy in Openstack. I was part of DevOps and Testing team and was responsible for deployment and automation testing of our product. I’ve been fortunate enough to be involved in many SDN related technologies since initial days of my career; like Openstack, Open vSwitch, OpenFlow, VXLAN, Virtual Appliances, etc. Currently, also working on Customer Premise Equipment, Docker Containers, Robot Framework, etc. Would love to continue in this exciting domain and enhance my expertise level.)*

Services visibility and Autohealing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Using Ceilometer, Nagios and some other available tools, it would be possible to monitor all the running services on the Openstack Cloud continuously and automatically. This will help in monitoring and taking critical decisions.


* **Girija Sharan Singh** *(Having around 4 years of work experience in Software Defined Networking.I enjoy working in fast-paced environment. I am an acknowledged trouble-shooter and I believe I possess the ability to do research and find solutions to complex problems.I hold a Master’s degree in Computer Science from Department of Computer Science, University of Pune, India.Currently working as a Software Engineer in Juniper Networks India Pvt Ltd. I am a part of Cloud Services Platform team working on exciting cloud products. Prior to that, I also worked in One Convergence Devices Pvt Ltd, a high growth startup which offers products and services in the general domain of SDN & NFV and has been one of the key co-contributors for the Group Based Policy in Openstack. I was part of DevOps and Testing team and was responsible for deployment and automation testing of our product. I’ve been fortunate enough to be involved in many SDN related technologies since initial days of my career; like Openstack, Open vSwitch, OpenFlow, VXLAN, Virtual Appliances, etc. Currently, also working on Customer Premise Equipment, Docker Containers, Robot Framework, etc. Would love to continue in this exciting domain and enhance my expertise level.)*

Effective Distributed Monitoring and Load Balancing using Consul
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Current monitoring tools like nagios etc are good for simpleton health checks. But the onus is still on the users to write scripts or manually take actions when the alarm triggers. Current monitoring apps operate like IFTT (IF this Then That). We need our applications to self-heal in the cloud environment. At least significantly reduce the downtime while firefighting issues. In this session, we’ll provide a different perspective on not only monitoring your applications, but also automatically scaling it and effectively load balancing them. We leverage Consul’s key features such as dns interface, key-value store, distributed locks to enable an effective distributed monitoring strategy. In this talk, we'll share our experience on how to we ushered into microservices infrastructure from a monolithic application and how to leverage consul for monitoring, service discovery and load balancing applications deployed to cloud.


* **Rahul Ramakrishna** *(Rahul is a software developer @Cisco Cloud, where he primarily works on data streaming problems and building distributed and robust data pipelines. He graduated from University of Massachusetts, Amherst in Computer Science. As a part of Database and Information Management lab, he worked on package builders which is a system that tries to understand losely defined constraits and helps users navigate to intended  solutions in the search space. Prior to that he worked @ Yahoo! sports, where he worked on developing operations tools, monitoring applications and scaling cloud application platforms over large server farms.  In his free time, he keeps tinkering in Databases, Distributed Systems and Machine Learning for Bots.)*

* **Yathiraj Udupi** *(Yathiraj Udupi is a Technical Leader of Engineering in the Office of the Cloud CTO at Cisco Systems working on OpenStack, BigData,  related projects.  He is actively executing and leading in building large scale, efficient cloud and streaming big data architectures with an emphasis on operational intelligence, monitoring, smart alerting, streaming analytics, and optimized cloud resource and workload placements (scheduling). He is an active Openstacker with interests in the projects such as Nova, Monasca, Telemetry. Yathiraj Udupi received his PhD in Computer Science from North Carolina State University where his research interests included Multiagent systems, Policy-based Management, Distributed AI.  He received his Bachelors (BTech) from the Indian Institute of Technology Madras (IITM) in Computer Science.)*

Cisco Litmus: Test the pH of Your Cloud!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you struggled to test your development and production clouds?We did too!!! So we created a service to do it for us!Our Quality Engineering team had a goal of automating and unifyingall of the technologies we use to verify our OpenStack clouds. After much experimentation and some false starts, we developed a framework called Litmus.Litmus configures, schedules and runs the following frameworks:1. Tempest2. Rally3. Selenium for Horizon testing4. An in-house framework we call Sanity. It provides users with a clean, polished web UI to make things easy, but also exposes a REST API that can be used by other services. During our presentation, some of the topics we'll discuss are how we've used Litmus to: - Scale our testing to all of of our clouds with distributed worker instances.- Compare region test results.- Create historical data for all of our sites.- Blacklist incompatible tests by OpenStack release.- Make the pain go away.


* **Dave Spano** *(Dave is a Cloud Engineer at Cisco Cloud Services, working on the QE Automation team.During his humble beginnings as a Linux Adminstrator of an optical lab, he discoveredOpenStack and Ceph during the Diablo release, immediately deployed it into his data center;leaving the legacy IT world forever. Currently, he works on Litmus, a Cisco project that automates and unifiestesting frameworks to simplify CI/CD, deployment upgrades and testing.Dave currently resides in Raleigh, North Carolina with his family.)*

* **Russell Sim** *(Russell Sim works at Aptira where he currently supports Cisco's with their internal cloud testing. Before that he worked for ~3 years at NeCTAR where he spent much of his time developing the SDLC pipeline, Puppet modules and writing tools that integrate with OpenStack.)*

* **Kieran Spear** *(None)*

Managing Your Cloud, the CIS Way!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When your cloud's hypervisor list spans multiple pages, it is very easy to get lost in the complexity. If it takes half an hour just to figure out which nodes are running a service, or track down all of the dependent services, then debugging any issue quickly becomes overwhelming.The Cloud Intelligence Service (CIS) acts as the single source of truth for your cloud fleet metadata. This includes metadata of virtual and physical resources , policies, configuration and billing. It aggregates and analyses events from infrastructure services to derive correlation between resources and trigger actions for optimizing the cloud. Built on top of Elasticsearch and integrating ChatOps, CIS provides cloud operators with unparalleled visibility. The capabilities include: History of state changes for cloud metadata objects A searchable web interface & API  Building reports for cost analysis, security, platform optimization etc Join us to see how CIS can light the path through your cloud.


* **Ankita Wagh** *(Ankita is working as a Senior Software Engineer in Cloud Platform Engineering Team of Symantec. She is an active open stack contributer and currently working on ceilometer. She has contributed in mistral and keystone as well.  She graduated from Texas A & M University with Masters in computer science and worked in Cisco for over a year where she contributed in router management software . She is an open source Enthusiast. She has worked on Hadoop and has proposed a new algorithm for HDFS-782 . She has done a couple of projects in computer networks .)*

Automated Recovery of OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Typical OpenStack deployment tools that exist today do a fairly good job of deployment of the cloud. But what is missing is making use of the information provided by monitoring tools to initiate an automated recovery of the cloud from certain set of well known problems. There are several issues that can happen in an OpenStack cloud post deployment including power loss , network partitions and hardware issues. We will look into recovery procedures for galera, rabbit and also how to integrate with deployment infrastructures to recover from hardware problems.  In this talk we will present a tool(CloudDoctor) to view all open issues in your cloud and an option to fix those issues. We  have a plugin model which integrates with existing monitoring tools and also deployment infrastructures. You could also perform actions like add/remove compute nodes, updates for bug fixes and replace controllers to make sure you can fully recover from existing issues. 


* **AJAY KALAMBUR** *(Ajay Kalambur works as a Technical Leader in Cisco's Openstack systems engineering team. Ajay has been involved in Openstack since the Icehouse release. Ajay started working on system and HA/resilency testing of Openstack cloud's for Cisco's intercloud offering. As part of this Ajay gained devops background in debugging openstack productions clouds and tailoring openstack configs for High Availability. He also has contributed to developing automated tools for Openstack system and HA testing including an opensource tool called Cloud99 which is a tool for HA testing of Openstack clouds.  Ajay has recently been working on developing automated deployers for openstack for Cisco's product lines. This involves working on docker containers, ansible and bare-metal Openstack deployments. )*

* **Jinay  Vora** *(Jinay Vora is a Software Engineer at Cisco working in the Openstack-Systems Group. His work evolves around Docker, Virtual Networking, Monitoring/logging and other cloud-related technologies. He has a Master's degree in Computer Networks from Georgia Institute of Technology.)*

* **Pradeep Chandrasekar** *(Pradeep Chandrasekar is a Senior Software Engineer from the Openstack Systems Engineering team at Cisco. He was one of the speaker at the Vancouver summit, presenting their Cloud99 HA tool. His experience includes Openstack deployment, Containers, Ansible etc. He has been working on Openstack since icehouse release. At Cisco, his primary work involves developing the  test infrastructure for Cisco's OpenStack High Availability clouds and various other Cisco's cloud services products. Priori to his involvement with OpenStack Pradeep was designing and developing white box test frameworks for Cisco's infrastructure components like High Availability and Inter Process Communications. He also gained his expertise in Java during his involvement with Cisco's management software called Cisco Software Manager.)*

Containers are packages: A premier on build tools and strategies
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Dockerfile can tackle a pretty large number of use cases, enabling a near flat learning curve but its limitations can lead to complexity that degrades performance benefits and space optimizations.  There is a need for organizations building OpenStack themselves from the ground up to repackage multiple components so as OpenStack's infrastructure components get containerized you'll want to become familiar with the image build toolchain that'll replace your RPM and APT toolchains. In this talk I'll introduce the various build tools at your disposal and strategies you can use to reduce the number of Dockerfiles you'll have to maintain.  Plus improve your insight into these images by utilizing declarative configuration management at build time.  As a bonus we'll leverage the the work done by the Puppet OpenStack and Docker communities to illustrate these strategies, proving that you do not need to throw out your entire infrastructure to migrate to a containerized world.


* **Cody Herriges** *(Many of the core technologies and philosophies I hold dear today were instilled in me as a student employee while attending university at Portland State: simplicity, automation, and opensource.  After promotion to a full time employee as a Lead Unix admin I eventually made a transition to Puppet, after it moved its headquarters to Portland, OR. I found that Puppet was a part of my daily life and had become the most important tool for getting things done in my infrastructure.  That fact convinced me that Puppet and automation was going to be the cornerstone of a modern technology stack, a movement I decided I wanted to be a part of.  Since then I've moved from Professional Service through Business Development to SysOps. I am now serving as a Prinicpal SysOps Engineer; where I work with internal and external partners to improve the way everyone utilizes the cloud technologies of today and tomorrow. I do this by staying close to the tech that facilitates the demands of a fast growing software company.)*

Managing infrastructure risk in RHEL OSP and Containers with operational analytics
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session and demo explores the risks associated with deploying a complex hybrid infrastructure around containers and OpenStack in public and private clouds and how to easily manage and monitor risk in your ops environments with enterprise predictive analytics from Red Hat. Learn how to stop fighting fires, identify and prioritize critical security vulnerabilities, quickly resolve configuration and deployment errors, and proactively prevent downtime in your RHEL, RHEL OSP, and container environments with Red Hat's integrated operational analytics tool, Red Hat Insights.


* **Will Nix** *(Nix is a Technical Product Marketing Manager in Red Hat's Management Business Unit. Nix is on staff with the Red Hat Insights prescriptive analytics product team, where he engages with and advocates for some of Red Hat's most strategic customers through solutions from Red Hat's open management portfolio.  With a technical background focused on system architecture and design, virtualization, and secure system and database management, Nix has worked in both public and private sector IT for over fifteen years.)*

* **Rob Williams** *(Rob Williams is a product manager for Red Hat Insights in the Red Hat Management Business Unit. Rob leads Red Hat Insight's high touch & beta programs, incorporating user's feedback directly into the product for future releases.)*

Network visibility and Automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud operations is spending a lot of time doing network related tasks manually which is adding to delays in deploying applications. Some of them include getting subnet(s) and configuring them either on a new or existing rack. It is error prone and time consuming. They are also spending time debugging duplicate IPs and mostly reactive in nature to address new capacity needs. Some of the reasons for this range from manual errors, multiple sources of truth causing maintenance issues, shared network addressing and visibility.This talk will focus on addressing these issues using an external IPAM and building automation around it. The topics covered will include the following which will significantly improve operations and time spent from day(s) to hours or minutes.1. Automate configuration of subnets in neutron2. Avoidance of IP conflicts3. Visibility of current IP usage and plan for future allocation


* **Sitaram Dontu** *(Over 17+ years of experience developing networking products. Last few years developing virtual switch for OpenStack integration and devOps role managing one of the largest private OpenStack clouds)*

Unified Monitoring addressing Virtual Machines, Legacy Baremetal, Containers and Network Fabric
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We will talk about datacenter monitoring not only for openstack itself, but also for legacy baremeal, containters, physical and logical networks. These different types of resources really start co-related together with software defined techs. SK Telecom has been developing varios tools covering operation automation, monitoring and analytics, network visualization, seperately. However, we realized that these tools need to be integrated together. Therefore, we are building standarized pipeline of gathering all the information (leveraging monasca), and developing monitoring tool chains on top of the pipeline. We will share tools we are developing and our experience to work with operation team to partially realize our ideas. Active demo of tools, architecture, difficulties to leverage openstack technologies with our legacy datacenter will be presented as well. Lastly, we will share our envision to connect monitoring with automation to simplify complicated operation jobs in the datacenter.


* **Jaesuk Ahn** *(Jaesuk Ahn have received the M.S. and Ph.D. degrees from University of Texas at Austin, in 2004 and 2009, respectively, all in Software Engineering. Upon the graduation, he joined Korea Telecom from Sept. 2009, where he started to work on Open Source Cloud Technologies, especially on OpenStack Project. he had led a development team to architect, develop, and deploy opoenstack-based cloud platform for KT's internal private cloud till 2014. He joined a venture company called cloud4u at 2014 working at developing cloud tool chain to design, orechestrate, provision, monitor systems on cloud environment. He also worked as a main architect to develop open paas platform for the government. He is currently working at SK Telecom on the research project related to Software Defined Data Center as well as production openstack deployment.   He has also been involved in openstack community from early stage. he founded OpenStack Korea User group at 2011, since then, he has been doing various activities to promote open source technologies in Korea. )*

* **Dongheon Lee** *(SDI Tech. Lab NIC (NW-IT Covergence) R&D Center  SK Telecom   )*

* **JongHyok Lee ** *(Working on data processing area about 20 years and real-time streaming data with so-called big-data solutions like IBM InfoSphere Streams or Apache Spark Streaming during last 5 years. Most of the experiences include gathering, processing, and analysis of application/machine log from devices or manufacturing equipments. Currently focusing on operation analytics and intelligence system for software defined data center on OpenStack.)*

The DevOps Train Wreck Headed for Your Data Center
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Urgent: To make the transition to DevOps, we must build the tooling we'll all need to succeed. It’s become fashionable to say: “All the interesting technology problems in DevOps are solved. We have Docker. We have Kubernetes. We have OpenStack. They’re stable, and they’re widely deployed. All that’s left to do is process transformation, teaching dullard enterprise IT teams how to consume the new-new IT.” This is dangerous thinking. The DevOps transition is placing demands on the enterprise data center that will break infrastructure models and policies designed for a dying era of monolithic apps. If we don’t work together as a community to build a new generation of tooling for the DevOps era, performance won’t meet expectations, and then we’ll all get to read articles about how DevOps failed. We can fix this. This talk will examine three areas that need attention. If we work together, we can prepare for the fundamentally new infrastructure and process demands of DevOps. 


* **Sumeet Singh** *(Sumeet Singh is the Founder & CEO of AppFormix. AppFormix optimizes enterprise clouds by providing sophisticated analytics and control of how virtualized infrastructure interacts with applications. Previously, Sumeet was the Principal lead for Hybrid Cloud Networking at Microsoft Azure.   Sumeet’s PhD. thesis at UCSD directly led to him co-founding NetSift, which was subsequently acquired by Cisco, where he led the integration of the NetSift distributed network analytics technology into Cisco products. Sumeet, has over 15 years of experience in the field of distributed systems, he holds 20 patents, has authored 15 research papers and is a recipient of the prestigious MIT Technology Review TR35 award.)*

Mastering oslo.log in structured log format
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Log collection and analytics are the problems worrying most OpenStack operators. Have you been sick of writing numbers of regular expressions to parse log outputs? In this session, we will talk about how to make log output structured by using oslo.log features.   We will show: How to make appropriate configurations of oslo.log for each OpenStack components Get JSON formatted outputs into files Direct outputs for logstash (a part of ELK  stack) and fluentd


* **Masaki Matsushita** *(Masaki Matsushita is a software enginner at NTT Communications.Masaki started contributing to OpenStack from Kilo release.He also contributes to Ruby as a committer mainly for performance improvement.He says, "I like Python too.")*

* **Takeaki Matsumoto** *(Takeaki is software engineer at NTT Communications, working on Cloud technology R&D team.He joined the team in 2015 and since has been focused on to R&D OpenStack.)*

* **Chihiro Yokoyama** *(Chihiro Yokoyama is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*

Taking Role Based Access Control into the the next generation with Tempest Driven Automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The role of RBAC policies is to restrict access to the capabilities of OpenStack API’s and provide controlled access to authorized users. This follows the principle of least privilege. To this effect AT&T has undertaken the task of creating certain buckets (set of atomic API calls) that enable certain functionality. Implementation of RBAC policies required vigorous testing through all phases of the SDLC. Tempest is the test automation tool used to test API and CLI tests to validate the Openstack deployment. The team has extended the Tempest framework and designed a role based control mechanism to insert assertions depending on the type of role and API. The framework is driven by a simple excel spreadsheet that has roles and the type of assertion required. API tests are then executed based on the defined roles & expected assertions. The framework has been very successful in testing out all the different roles defined throughout the different phases of testing using CI/CD.  


* **Bhavin Desai** *(Bhavin Desai is a Manager in the Testing Service Capability within Accenture Delivery Centers in North America. He has over 10 years experience in strategizing and delivering IT projects with focuses on Testing, Project Management, Process Design and Implementation. Bhavin is experienced in leveraging Client designated methodology, Accenture Delivery Method (ADM) and the Accenture Test Assessment framework in architecting Test Strategy and Approach. Bhavin leads teams in Test Planning, Test Automation, Defect Management, Test Execution and overall Test Project Management)*

* **Jennifer Johnson** *(I am currently the Sr. Technical Director of Testing; who manages a large global technical team of AT&T and third party vendor members (120+) charged with developing, transforming, and supporting the testing of the company’s Cloud Computing OpenStack platform of AIC – AT&T Integrated Cloud. Charged with leading the test architecture, strategy and planning, test execution, test automation and test tooling for one of the world’s largest OpenStack based private clouds. It's exciting to be part of team that is transforming the AT&T network by leveraging an opensource platform. I recently joined the Women of OpenStack and very excited to be part of the organization that embraces fellowship and wants to drive innovation and adoption in the community. #Techgeak  )*

Augmented Reality for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Smartphone-based augmented reality (AR) is now surprisingly easy to create: with mature, cross-platform, open source tools like ARToolkit providing powerful base functions for camera calibration, feature tracking, and dynamic rendering of 3D content over realtime video views. This presentation describes (and demonstrates) how phone-based augmented reality can be exploited to facilitate OpenStack cloud operations: providing heads-up informational displays elucidating the status and interactions of workloads and processes active on physical hardware, and enabling creation and interaction with virtual 3D models on tabletops or other empty 'stages.' The proposed architecture draws from an opensource toolchain rooted in Mirantis Stacklight, which is a sophisticated logging, monitoring, and alerting kit comprising components such as ElasticSearch, InfluxDB, Kibana, and Grafana.


* **John Jainschigg** *(John Jainschigg works with Mirantis broad partner ecosystem, promoting validation of new solutions with Mirantis OpenStack, and tracking emerging use-case and technology trends in areas like containers, PaaS, and hybrid cloud orchestration. He is a former software developer, virtual reality experience architect, Editor in Chief of Computer Telephony, Communications Convergence, and Online EIC of Dr. Dobb’s Journal.)*

Kolla: Operating OpenStack Clouds in Docker Containers using Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kolla is an OpenStack big tent project that deploys and operates OpenStack cloud environments using Ansible and Docker. In past presentations of Kolla, we have always talked about the technology behind Kolla as the key factor in what makes Kolla fantastic.  Over the last 18 months our IRC channel has built a tight feedback co-development loop with operators participating in the Kolla community.  The best part for operators is we have maintained our technology strengths during this change in our philosophy. With this unintended consequence of operator interaction, we have not only solved the #1 pain point (deployment) and #2 pain point (upgrades) of OpenStack, but are quickly building a tight feedback loop with operators to solve the #3 pain point (operators have unmet requirements).


* **Steven Dake** *(Steven Dake is bringing container technology to OpenStack on behalf of Cisco Systems, Inc. Steve serves as Kolla PTL for the Newton cycle and served as PTL for the Mitaka, Liberty, Kilo and Juno cycles.  Steve also contributes to the design and implementation of Kolla.  Steve also contributed heavily to the initial architecture, design, and implementation of Magnum, serving as a core reviewer for two cycles. Prior to gaining an interest in container technology, Steve initiated and led the development of OpenStack Heat with a small development team while at Red Hat, Inc.  During this period, Steve served as Heat PTL for Essex, Folsom, and Grizzly. Prior to Steve's involvement in OpenStack, Steve was primarily focused on the development of open source high availability technology leading the design and implementation of Corosync, a group communication system, which combined with Pacemaker is the de-facto standard high availability stack for Linux.  During this period of his career, Steve also served as a technical community leader for the modern Linux high availability stack.)*

* **Michał Jastrzębski** *(Michal is a senior cloud software engineer at Intel Corporation and one of tech leads of Openstack Innovation Center. Michal is making Openstack better since Grizzly. Michal is a Kolla core reviewer since the Liberty cycle with a focus on diagnostics and upgrades.)*

* **Ryan Hallisey** *(Ryan is a software engineer at Red Hat.  He has been working on Kolla since the start of the project two years ago.  Since then, he has been heavily involved in both Kolla and kolla-kubernetes projects.)*

Simplify Day 2 operations (and get some sleep!) through Craton fleet management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Use Rackspace’s proven approach for fleet management, with inventory and audit/remediation workflows. And stop spending your evenings and weekends to fix day-to-day operational issues in your OpenStack deployment! With the new Craton project, we may have new ops tools that can help you. Come see a presentation and demo of the Craton fleet management framework and working solution for OpenStack clouds, which we plan to become part of the OpenStack big tent. Craton combines two key elements, while integrating with your existing environment. First, an inventory fabric to manage your inventory of hosts/devices, along with corresponding configuration variables; and the ability to wrap seamlessly existing inventory/asset management sources. Second, Craton enables running audit and remediation workflows across the fleet to help operate your cloud. Integration APIs complete the solution with other tooling you have in place, including CI/CD, governance, logging, monitoring, and alerting.


* **Jim Baker** *(Jim is a senior software developer at Rackspace, where he works on problems that involve scale, whether that's cloud computing or big data. He is also a lecturer in computer science at the University of Colorado at Boulder. He is a graduate of Harvard College and Brown University and is a nominated member of the Python Software Foundation for his work on Jython.)*

* **Sean Roberts** *(Sean manages the platform programs and products for Walmart. Walmart is making heavy investments in agile infrastructure. New network stacks, OpenStack infrastructure, OneOps platform orchestration, CI/CD pipelines, open source contributions, and many other important changes are being implemented. Sean is working on the evolution of a traditional brick and mortar retailer into a online retail competitor. Sean has been involved with OpenStack for more than four years, with over two years as an OpenStack Board Director. He has been elected three times to represent the OpenStack Foundation Gold Membership. Sean has also held the Chair of Finance and Tax Affairs committee positions, in addition to being a member of the DefCore and Gold Membership committees. Sean is also involved with OpenStack projects. He was formerly the Akanda and Training-Guides PTL. As well as a member of DefCore, Product, and Ambassador groups. The OpenStack Foundation has recognized Sean as an OpenStack Ambassador, which leads the OpenStack user groups worldwide. In his spare time, Sean leads the San Francisco OpenStack user group with five thousand plus members. “I enjoy working with all the different people involved with OpenStack. There is constant state of optimism and a drive to improve. If I had to pick one thing that makes me feel renewed and happy about my work, it would be helping people to improve themselves. I always am humbled when I can help someone find a new job or gain a new skill. This is what keeps me going.”)*

* **Sulochan Acharya** *(Sulochan is a Software Engineer at Rackspace where he focuses on developing tools that help to run and maintain Openstack based cloud at a large scale. Currently Sulo works under OSIC (Openstack Innovation Center) to help develop fleet operations tools. He is currently focused on the Craton project, which aims to build a tool that operators can use to manage their openstack fleet. He has perviously worked as Senior Linux System Engineer ensuring reliability of Rackspace public cloud infrastructure, where he built applications to automate the day to day management of of cloud infrastructure to make Rackspace public cloud a self healing Openstack fleet. Sulo has also contributed to other Openstack projects.)*

Debugging OpenStack Networking Reloaded
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Networking is one of the least understood component of OpenStack and, consequently, one of the toughtest challenges for operators. It is impossible to diagnose most issues with an OpenStack installation without understanding the networking internals, something impractical to do manually. DON, written primarily in Python, and available as a dashboard in OpenStack Horizon, Libery release, is a network analysis and diagnostic system and provides a completely automated service for verifying and diagnosing the networking functionality of a multi-node OpenStack installation. This service verifies (or points out deviations) that the user configuration is indeed reflected in the underlying infrastructure and presents the results in an intuitive graphical display. The results of the analysis are stored in a DB for later retrieval and comparision. Please visit https://github.com/CiscoSystems/don for more recent information.


* **Amit Saha** *(Amit is a Senior Technical Leader in the office of the cloud CTO at Cisco Systems. He has had extensive experience in the field of computer networking, both wired and wireless. He focuses on automatic, system-wide verification and visualization of large scale distributed systems, with a special emphasis on networking. He has been a speaker at the Vancouver summit.)*

* **Ramaraja Ramachandran** *(Ramaraja is a senior developer and has been actively involved in several OpenStack projects. He has had extensive experience in developing applications using Python. )*

Maat - Adaptive System Configuration and Recovery with Predicates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Maat is an SCM system with automatic system recovery. It defines system correctness with simple predicates and can adaptively find solutions to recover from system resource changes. We will demonstrate Maat provisioning an OpenStack cluster and recovering from system changes. * System correctness is specified with simple predicate functions in Python. * Reconfigurations for system changes achieve minimal disruption of service. * Operators can be notified and control when a system reconfiguration is required to avoid thrashing during transient failures. * User-defined fitness functions select solutions that optimize system characteristics such as resource usage and disposition. We developed Maat to automate the life cycle of OpenStack clusters, from initial provisioning, failure recovery, cluster component changes, and software upgrades. We will demonstrate Maat deploying and recovering from failures on a multi-node DevStack deployment.


* **Noel Burton-Krahn** *(Noel has over 25 years software development experience, with particular interest in distributed systems and fault tolerance. This recent work has been automating OpenStack deployments for Piston and now Cisco. )*

Building Customised Packages for your OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Packages are the key component in operations of an OpenStack cloud. Users can use distro packages built by other companies in their PoC or production system without any changes, however many users want to have customised packages with their own patches. This talk introduces how packages are built for OpenStack projects, and demonstrates how to build customise packages by using StackBuffet: a CI-as-a-Service that automatically builds packages from your source code. StackBuffet has a built-in APT/YUM repository that makes it easy for users to consume these packages. It can also aid testing in different phases from source code testing to final production testing.


* **Shunde Zhang** *(Shunde is a senior cloud engineer at Aptira with over 15 years experience in software development, automation and system administration. He has worked with OpenStack since the Diablo cycle and has been involved in projects from OpenStack infrastructure to distributed systems running on top of OpenStack. Shunde is also experienced with HPC and scientific computing. He holds a PhD degree in Computer Science in the area of Grid Computing. Shunde loves coding, and his favourite languages are Python and Java. Shunde is passionate about the local OpenStack community, attending and presenting at OpenStack meetups and OpenStack days. He was a valuable contributor at the recent Australia day event, including sharing his knowledge with attendees as part of workshops and demonstrations to assist them with their OpenStack deployments.)*

Monitoring Openstack with Elasticsearch Logstash and Kibana
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In our Openstack installation,  BulutM cloud monitoring system use  ELK stack (Elastic) to gather: Openstack logs Tenant based top n network statistics (bandwidth, pps, error, drop)  Compute host I/O, network, memory, cpu metrics Virtual machine I/O, network, memory, cpu metric The BulutM monitoring system is written in Python.  BulutM use Openstack API to get tenant information. Tenant information is stored in redis  and used by other scripts to automatize generation of Kibana dashboard, search and visualization objects.


* **Onur Bektaş** *(Onur Bektas is currently  a chief researcher in Network Technologies Department of the Turkish Academic Network and Information Center  (ULAKBIM). Onur has more than fifteen years of experience and on FreeBSD, Linux and Solaris operating systems administration and security.)*

Ansible + OpenStack: Who, What, Where, Why, and How?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Want to learn how to automate the deployment, management, and consumption of an OpenStack cloud with Ansible? In this talk, Robyn Bergeron, Community Architect for Ansible, will share her knowledge around the various ways - and whys! - OpenStack and Ansible are used together. Numerous projects inside of OpenStack depend upon, or are built solely upon, Ansible, including Bifrost, Kolla, and openstack-ansible, as well as the CI system for OpenStack itself, operated by OpenStack's infrastructure team. Additionally, modules inside of Ansible, maintained by members of the OpenStack community, make it easy to abstract the complexities of OpenStack in an automated fashion. If you're new to Ansible, the session's demonstration of some of Ansible's OpenStack modules will show how easy it can be. And if you're an experienced user? Get to know how some of OpenStack's projects are making advanced usage of Ansible, or find out how you can participate in any of these open source communities.


* **Robyn Bergeron** *(As Ansible's Community Architect, Robyn Bergeron focuses on building bridges between Ansible and other open source communities, as well as steadily scaling Ansible's framework for collaboration and contribution as the community continues to grow. Robyn has been a sysadmin, program manager, business analyst, and developer advocate in past lives, and started her career in open source at Red Hat, where she was the Fedora Project Leader -- and she continues to follow her passion of inspiring, enabling, and empowering contributors as part of the Ansible community team at Red Hat. )*

Exploring invisible problems in OpenStack - intelligent troubleshooting with the Elastic Stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Troubleshooting OpenStack is difficult. In a real-world OpenStack system, configurations, parameters and architectures are all different in every OpenStack deployment. So, regardless of OpenStack maturity, we've found multiple problems in our OpenStack system, which often come out as error logs but sometimes not. In the latter case, problems are especially difficult to detect and fix. In this presentation, we will introduce how to manage this problem by using the Elastic Stack, not just parsing error log messages but taking more intelligent approaches. To detect invisible errors and problems, such as performance degradation caused by Keystone, DB and RabbitMQ, we have configured the Elastic Stack to collect log data in a way appropriate for analysis, extracting plenty of important information, e.g. request IDs, request URLs, response times of WSGI servers. We will show how to utilize these data for troubleshooting OpenStack and results of log data analysis in our OpenStack system.


* **Yotaro Konishi** *(Yotaro Konishi is a cloud researcher and developer at Fujitsu Laboratories Ltd. His primary responsibility is to promote automation, CI/CD, and infrastructure management to Fujitsu OpenStack cloud products, utilizing Puppet and puppet-openstack, Foreman, Ansilbe, Jenkins, etc.)*

* **Noboru Iwamatsu** *(Noboru Iwamatsu is a member of OpenStack since Icehouse. He is a research manager of cloud platform research team in Fujitsu Laboratories. His team constructed OpenStack-based large-scale private clouds for R&D (2 regions,3+ AZs, 200+ servers), and manage them in 2 years. He was one of the core developer of Xen hypervisor project (developed the paravirtulized-USB, GPU-passthrough function, ...), and continues contributing cloud infrastructure-related OSSes.  He has MS from Tokyo Institute of Technologies. He joined Fujitsu Laboratories in 2001, and has worked on Linux-based embedded system, Xen hypervisor, server architecture development and, cloud management software.  )*

* **Tatsuma Matsuki** *(Tatsuma Matsuki is a researcher in Fujitsu Laboratories Ltd. He is working on the performance of OpenStack services and his main interest in the performance management of OpenStack services, which includes log and metric analysis, job scheduling and QoS in OpenStack.)*

Formal method techniques to guarantee consistency of security policy in virtual machine migration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Dynamic changes is the key to any cloud infrastructure like OpenStack. Maintaining consistency of information while being dynamic in nature is tricky. Particularly during VM migration the global information like security policy, service level agreement etc. can become inconsistent. In such scenario Formal Method techniques can be used to verify the consistency of such critical information. We propose to show how the formal method techniques can be used to mathematically prove the consistency of crucial information while migrating the VMs across physical hosts.


* **Remish Leonard Minz** *(I am Research Engineer at Hitachi working in Formal methods for 4 years)*

Will it run on *my* OpenStack?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Cloud Foundry ecosystem uses a tool called BOSH for packaging, installation, and updating workloads. Validating that BOSH can be used on an installation of OpenStack is currently a tedious and error-prone manual task. It's made harder by the fact that usually not a single team has expertise in both areas. Our team is building an open-source validation testsuite that encapsulates expert knowledge about the interaction of BOSH and OpenStack in a tool, which is easy to use for non-experts as well. It helps to find out if an OpenStack installation is ready to run BOSH, or which changes need to be done. The testsuite provides a DSL to express the requirements of a workload on OpenStack, which can be run as a set of validation tests, and gives feedback about required changes to the OpenStack setup. In this talk, we take a look how to express workload specific requirements in a simple series of tests, and report about the experience we gained with that in the Cloud Foundry project.


* **Marco Voelz** *(Marco is working for SAP SE and is the Product Owner of the Bosh OpenStack CPI. Developed in open-source, it is the abstraction layer used in Bosh, the tool to install Cloud Foundry and its services, on everybody's favorite IaaS.)*

* **Cornelius Schumacher** *(Cornelius works as engineering manager in the cloud and systems management department at SUSE Linux, which is working on projects such as OpenStack, Docker, and a variety of systems management tools. Cornelius is driving SUSE's technical involvement with Cloud Foundry, in particular the work on the BOSH OpenStack Cloud Provider Interface. He is a long time contributor to many open source projects for more than a decade, such as KDE, openSUSE, the Open Build Service, or recently Cloud Foundry. Cornelius is a regular speaker at Linux and open source events, mostly in Europe, but also in the US or in Brazil.)*

Ansible Birds of a Feather
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ansible Birds-of-a-Feather.


* **Robyn Bergeron** *(As Ansible's Community Architect, Robyn Bergeron focuses on building bridges between Ansible and other open source communities, as well as steadily scaling Ansible's framework for collaboration and contribution as the community continues to grow. Robyn has been a sysadmin, program manager, business analyst, and developer advocate in past lives, and started her career in open source at Red Hat, where she was the Fedora Project Leader -- and she continues to follow her passion of inspiring, enabling, and empowering contributors as part of the Ansible community team at Red Hat. )*

RDO's pipeline with Software Factory and DLRN
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The first task of an OpenStack operator is deciding how to install it. If ambitious, you could install from source, although packages might prove more prudent. This talk covers the new way that RDO builds OpenStack packages with a completely open toolchain, and how you can too. This is immensely useful for building your own packages safely, tested by upstream and in-house tests and gates. Red Hat recently underwent a complete shift in how packages are built and delivered using Software Factory. Software Factory is a distribution of software that closesly resembles the development environment of the upstream OpenStack project. This has allowed us to build and test packages and entire repositories continuously. Come to this talk to learn how this software set has allowed us to accelerate our development and deployment pace, and how you can leverage it to bring the same advantages to your own cloud.


* **Benjamin Kero** *(None)*
