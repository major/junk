How To & Best Practices
=======================

Automating ITIL Configuration Management for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the traditional, non-virtual datacenter, enterprises have evolved ITIL systems such as CMDB and DNS to manage their infrastructure.  However, with OpenStack, there is no automatic method to integrate the VM creation with these features.  This presentation will provide a detailed, in depth engineering analysis of the design we have developed to automatically update DNS and CMDB when a VM is created.  Conversely, we automatically remove the CMDB record and DNS record when the VM is destroyed.  These methods are automatic and do not impact the creation or deletion of the VM; nor do they change the API calls to create/destroy VMs in OpenStack.  Further, ths is the best part, our software does not modify the OpenStack code so upgrading is very easy.


* **William Bloom** *(William has 25 years of experience as a UNIX system administrator, manager, storage engineer, and most recently as a Cloud design engineer.  William has worked in Intel Manufacturing, LSI Logic Manufacturing, Legato IT, EMC.  Most recently, William just completed 10 years at Cisco in a variety of  IT roles from data protection design, storage design, and most recently OpenStack design.  William is currently working as a software developer and Scrum Master for CITEIS (Cisco IT Elastic Infrastructure Services).)*

Do you need bare metal in your OpenStack Cloud? Ironic is your answer!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are multiple scenarios where bare metal performance is required in a cloud environment. Fortunately, in OpenStack clouds, there is a way to achieve this: project Ironic.


* **Julio Villarreal Pelegrino** *(Julio Villarreal Pelegrino is an RHCA with over 15 years of experience in Enterprise IT. Currently, he is a Sr. Cloud Architect in the Red Hat's Cloud Infrastructure Practice. In his role, Julio helps customers to architect and implement OpenSource cloud and virtualization solutions (e.g: OpenStack, Red Hat Enterprise Virtualization).Before joining Red Hat he worked for Oracle and Dell where he held different roles within the IT and Services organizations.)*

* **Chris Paquin** *(Senior Infrastructure and Cloud Consultant with over 15 years experience working with Unix, Linux, Virtualization, and Cloud. )*

OpenStack and Ansible: Automation born in the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Automation is the only way operations teams will keep pace with growing business expectations to deliver faster, increase availability and do so efficiently without adding more resources. OpenStack offers the infrastructure blueprints, API endpoints and Heat for delivering one-click infrastructure-as-a-service. Ansible provides an agentless platform for configuring, deploying and automating complex application software stacks in the cloud once the infrastructure is provisioned. Together OpenStack Heat and Ansible provide end-to-end solutions for deploying even the most complex application stacks, effortlessly.  


* **Keith Tenzer** *(Keith Tenzer has over 15 years of enterprise IT experience. He has a strong software engineering background but mostly worked as a systems and storage administrator. He has worked for high-profile companies such as Intuit, NetApp and Red Hat. Keith has worked in the USA and Europe. Through his career Keith has focused much of his time around application integration and has built distinct expertise in this area. Currently Keith occupies the position of Solutions Architect at Red Hat. Keith operates a blog that mostly focuses on cloud, specifically OpenStack http://keithtenzer.com. Software Engineering Accomplishments Coding provides Keith with a creative outlet for his many ideas. It also helps him understand how software is built and operates. Keith has worked on many software engineering projects and some notable ones are mentioned below. Integra – Provider based automation framework that enables IT teams to automate anything without creating technical debt. Integra is simple to understand and easy to use. It is truly a next-gen automation platform. NetApp Snap Creator Framework – Snapshot based backup framework integrating applications with NetApp snapshot technology. Snap Creator is a backup product offered by NetApp and Keith is the inventor. Perfstat – Systems monitoring tool fashioned after another monitoring tool from 90s called Big Brother. Snap2cloud – A framework for backing up storage snapshots to the cloud. Currently it implements NetApp to Amazon S3 but it could be extended to other storage vendors and cloud providers. Patents Keith does not believe in software patents and sees much more value in contributing to open source. Nevertheless he is proud of his accomplishments. Frameworks for Providing backup Functionalities to Different Applications Identification of Virtual Applications for Backup in a Cloud Computing System Provision of Backup Functionalities in Cloud Computing Systems)*

Continuous Documentation for OpenStack Resources with RedHat and Atlassian
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How can I make software-architecture documentation available to all stakeholders in a project and which best practices make this easier? How does autmoated documentation work in the Age of DevOps? That is the question that we are trying to discuss with the community at large and answer on a practical level – using arc42 (http://www.arc42.org) as a framework and the toolsets provided by our partners Atlassian and Redhat - with an open source project for Continuous Documentation (or ConDoc) for short, which we at NetworkedAssets started last October. By the time you’ll see this presentation we will be able to present our DoS (Documentation from System Configuration) module, which focuses on deployments on RedHat OpenStack and RedHat OpenShift Enterprise (= Docker/Kubernetes, running on top of RedHat OpenStack) and the community home that we created for this project (outside of Github and our own website).


* **Joerg Mueller-Kindt** *(Joerg Mueller Kindt is the CEO of NetworkedAssets, specializing as an Atlassian Expert and RedHat Advanced Business partner on JVM software architectures on Linux and the technical aspects of DevOps automation. Joerg Mueller-Kindt has 20+ years of experience in the service-provider and telecommunications industry. He is a Certified Scrum Master, a registered Prince2 Practitioner and an ITIL Practitioner and he still spends most of his time to explain what it actually is he is doing for a living.)*

Heat widespread difficulties and how to SHOOT them or why I've not known about it before.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During this presentation we plan to go through the widespread beginner's mistakes and guide how to deal with them by using Heat features. This presentation will cover following topics: 1. Heat template versions and intrinsic Functions  2. Resource Group and Nested templates 3. New API for Outputs and how to reach ResourceGroup attributes 4. Issues with port + Server combination


* **Sergey Kraynev** *(Sergey Kraynev is working at Mirantis. He began to contribute to OpenStack community since 2012, now he focusing on openstack Heat and Murano Applications, he is core review member of openstack Heat community and ex-PTL of Heat project.)*

* **Oleksii Chuprykov** *(Oleksii Chuprykov is working at Mirantis. He began to contribute to OpenStack community since 2014, now he focusing on openstack heat, he is core review member of openstack heat community.)*

* **Peter Razumovsky** *(Peter Razumovsky is working at Mirantis. He began to contribute to Openstack community since 2014 and now is working at Heat design and bug fixing. He is core reviewer member of openstack heat community.)*

Writing A New Puppet OpenStack Module Like A Rockstar
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying OpenStack is a complex task, and Puppet modules for OpenStack bring scalable and reliable IT automation to OpenStack cloud deployments. Puppet modules enable you to deploy most OpenStack services, some that you already know, like Nova and Neutron, but also new projects, like Octavia and Mistral. Puppet OpenStack maturity helped us learn from our successes and mistakes each time we had to write a new module. In this presentation, we’ll share these learnings and teach you how to successfully write a new Puppet module that’s compliant, tested, consistent, and ready for production deployments.


* **Emilien Macchi** *(Emilien is a Principal Software Engineer at Red Hat, who has contributed to several OpenStack projects but mostly to TripleO and Puppet OpenStack Project, on which he's the current Project Technical Leader. When he isn't working to make OpenStack deployement simpler, faster, stronger, he's improving his running stats, or exploring beautiful Canada.)*

From Our Code To Your Production Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For an OpenStack developer, it's sometimes challenging to understand how a feature will be integrated in production. And sometimes cloud users might wonder how a feature has been developed, integrated, and automated in a production cloud deployment. In this talk, we'll laugh about the famous "it worked on devstack". We'll also show you step-by-step how we develop a feature in OpenStack and then integrate it in TripleO, which is a project aimed at installing, upgrading, and operating OpenStack clouds. Come and see how your production cloud is developed and deployed under the hood.


* **Emilien Macchi** *(Emilien is a Principal Software Engineer at Red Hat, who has contributed to several OpenStack projects but mostly to TripleO and Puppet OpenStack Project, on which he's the current Project Technical Leader. When he isn't working to make OpenStack deployement simpler, faster, stronger, he's improving his running stats, or exploring beautiful Canada.)*

* **David Moreau Simard** *(David is a Senior Software Engineer in the RDO engineering team at Red Hat where his efforts are around empowering the community to deliver a reliable OpenStack distribution. He brings his expertise around operations, infrastructure, tooling and CI to ensure RDO is the most stable OpenStack packaging distribution. Previously, he was at iWeb, a server and datacenter infrastructure provider where he held various technical and leadership roles in the span of nearly a decade. In the last years, his focus was around deploying and supporting a highly available multi-region OpenStack public cloud in different datacenters around the world.He holds a blog on https://dmsimard.com where he shares articles about what he learns and his interests.)*

* **Pradeep Kilambi** *(Pradeep Kilambi is a Principal Engineer working on OpenStack at Red Hat, Inc. His interests span across various aspects of OpenStack including Cloud Metering, Monitoring, Containers Management, Deployments and Networking. He is a Ceilometer Core Contributor and an Active Technical Contributor for various projects in OpenStack and actively works with the community. Prior to Red Hat, Pradeep was working on OpenStack at Cisco Systems.)*

Policy in Business Reality for OpenStack Operations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Keystone provides the mechanism for RBAC thoughout the OpenStack deployment. The access right depends on the policy at the entry of API. This presentation will walk though the policy custom in business reality. To start, we'll give a basic tutorial about policy with upstream keystone and share the real case we encountered and the way we solved in reality. This will be an interactive session and attendees will be encouraged to ask questions, make comments and share their experiences with the policy they custom in real business.    


* **Jialong Zhang** *(Jialong Zhang is a software developer in AWcloud, now is responsiblefor OpenStack Nova development.)*

Connecting Cloud Platforms: Federating Access and Control
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack can evolve to attract more cloud application development by simplifying base services required by most applications. User, roles, access management are among the services which are common requirements for all applications. However, these base requirements for Identity Access Management are complicated by the fact that enterprises need identity federation and common access management. Configuring Keystone for Identity Federation is a well known concept, but it is only half the picture. Configuring Keystone to also use a common access management solution brings OpenStack closer to the proposition that application developers simply drop-in their core business value.  Overview the benefits of connecting a centralized security policy and control point to keystone. We will detail our vendor neutral implementation along with how to tips and lessons.


* **Shawn Mullen** *(hawn Mullen has worked for a variety of computer companies and organizations including the last 25 years with IBM. His current role is Cloud Security Architect for IBM’s Cloud Infrastructure Services, leading the architecture and development of security products and technology. You can view Shawn at the Tokyo OpenStack Summit discussing IBM’s hardware based Trusted Cloud implementation https://ibm.biz/TrustedCloudTPM-TXT . Shawn’s previous roles was Power Systems Security Architect, were he owned and developed the security roadmap, product strategy, architecture, and led the development products such as PowerSC. You can view a video of Shawn discussing PowerSC and its IBM Redbook: http://www.youtube.com/watch?v=w58MMb-XbwQ Shawn has played leadership roles in standards organizations, to reach consensus with competitors and customers. Shawn is the Chairman of The Open Group Security Forum. Shawn has over 100 granted US patents.)*

* **Henry Nash** *(Henry works in IBM's Cloud division as an OpenStack Architect and a core contributor to OpenStack Keystone, driving enterprise capabilities into OpenStack as well as IBM's products that use OpenStack. He has a long history in the creation of enterprise software, having founded a number of successful companies in Europe and the USA, coming to IBM via acquisition in 2009. He holds a 1st class honours degree in Electrical Engineering from the University of Southampton, UK.)*

* **Jeff Rosas** *(To be added later. )*

* **Stephen SooHoo** *(Stephen is a cloud developer specializing is developing and deploying highly secure and robust cloud security services. )*

Put applications/NFV performance optimization intelligence into your cloud.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We believe not all environments behaving the same. As private cloud owner, Having an infrastructure that is flexible enough to be configured in different models is likely the right direction to enable and empower your own applications, at the end, what we want enable is all about how application perform, and how our business perform based on all server side optimizations we are doing. In this talk, we will explore multiple options within modern operating system which potentially give us opportunities to fine tune system performance in addition to generic cloud interface based on VM characteristics, we will also share the way we are doing in Cisco WebEx cloud incubation to achieve the goal of VM performance optimization, and also share the result and recommendation with the people who care more about applications than fancy cloud features.


* **Ian  Zhang** *(Working at Cisco WebEx for 11 years, cloud platform architect for Cisco WebEx Openstack deployment. observer of data center and infrastructure evolvement. Skillful in distributed file system, cloud platform, high availability, and application/software cloudification. The guy under the philosophy of building best marriage between infrastructure and application...  )*

* **Liping Mao** *(Working as devops at Cisco Webex Cloud Service, develop and operate Openstack Private Cloud in Cisco Webex. Participate in Kuryr Upstream work, active developer in Kuryr Project.  )*

Mission Critical OpenStack - Running production workloads in a programmable infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session we will demonstrate two advanced use cases as deployed in production for a finance institution in Australia using infrastructure as code by leveraging on Ansible and Jenkins. 1) "Data Cloning as a Service", how to automate the cloning of a 24 x 7 Mission critical database from a Production tenant to a testing tenant. Ansible is used to place an Oracle database in backup mode, take a snapshot of the volume containing the Database, clone the cinder volume and get  transferred to a development tenant who will automatically start a clone of the production workload for testing purposes. The job is fully automated from Jenkins.   2) Automated deployment of an enterprise load-balanced infrastructure that makes use of Octavia to provide HA grade redundancy in the customer web farm. We will cover some failover scenarios for Octavia as part of the demos as well as some known limitation and how to adress them.


* **Alejandro Tesch** *(Alex Tesch Alex has been working with Open Source enterprise technologies for the better part of his 15 years IT career in companies like Hewlett-Packard Enterprise, Red Hat, IBM and Sun Microsystems. He started his OpenStack journey with Grizzly, delivering the first HPC cloud in APAC for a Singapore University making use of SRIOV technologies combined with big data.  He has extensive deployment experience on configuration management and automation of private cloud based on OpenStack. Alex is currently an APJ Cloud Consultant in the Helion Cloud team at Hewlett-Packard Enterprise, where he evangelizes the OpenSource side of the Helion portfolio (OpenStack / Cloud Foundry / Ceph). He enjoys running automation workshops and seminars in the APJ region for cloud adopters. )*

* **Damia Pastor** *(Damia started as a sysadmin for a project related to Swift (late 2011) to then switch to StackOps, one of the first OpenStack distributions to deliver and operate projects from Brussels to Manila. After being in Mirantis for both EMEA and APJ, moved to HPE professional services working in production projects and helping create new solutions.)*

Delivering reliability in the cloud - People, Process, Tools
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session an overall view of delivering reliability and availability will be discussed.Frombest practices in processes definition to integrating sensu with pager duty and resolver - auto healing infrastructure. Sensu: How to design and architect monitoring solution for your cloud. Resolver (Auto-healing): How to build a resolver framework based on sensu input containing | <--> resolver worker node <--------> Task on dest msg ---> [Broker] <--> Resolver -> | <--> resolver worker node <--------> Task on dest | <--> resolver worker node <--------> Task on dest Processess: Including reporting mechanisms, machine<>operator interactions and more.


* **Ivo Vasev** *(Ivo has been working on and contributing to Open Source software for most of his career and has been primarily contributing to OpenStack since 2012. Projects that Ivo contributed include Nova, Tempest, CloudCAFE. Currently Ivo is responsible for shared services and customer supportability tools development projects in IBM.)*

* **Suparna Roy** *(Suparna Roy is director of Engineering of openstack projects in IBM)*

Tuning and optimization of openstack shared services - RabbitMQ and DBs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Tuning and optimization of openstack shared services Rabbitmq and Galera DB clusters.One of the key ingredients for having good openstack cloud is deploying shared services on scale with proper configurations and plugins available for higher performance and running on scale. This presentation will show performance validated and tested configuration options for the openstack most common messaging service. Also will touch some HA proxy best practices. Will take a dive in some of the plugins like shoveler for reducing manual/scripts load on supporting the system.


* **Ivo Vasev** *(Ivo has been working on and contributing to Open Source software for most of his career and has been primarily contributing to OpenStack since 2012. Projects that Ivo contributed include Nova, Tempest, CloudCAFE. Currently Ivo is responsible for shared services and customer supportability tools development projects in IBM.)*

Building a Sandbox for Red Hat OpenStack Platform / RDO
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, we will cover the best practices to build a sandbox for RHOSP / RDO using director, including our personal experience and what we did in order to achieve the current virtual lab that we use for tests / proofs of concept / onboarding for new techs. We will review the hardware and hypervisor configurations that we require and will transmit the knowledge according to our own field experience.


* **Jose Casimiro** *(Jose 'Kaz' Casimiro started using linux since 1994 and has been working at opensource enterprises such as Rackspace and Red Hat doing a wide variety of IT roles including: instructor, developer, sysadmin and support engineer. He currently works at Rackspace as an OpenStack Engineer.)*

* **Kent Wolfe** *(Kent Wolfe is a Red Hat Certified Architect who currently works for Rackspace Hosting Inc. as an OpenStack Engineer. His professional interests include troubleshooting a wide range of technologies surrounding Linux and OpenStack. In his previous role, Kent enjoyed mentoring new administrators and serving as an escalation point.)*

OpenStack and Magnum: Kubernetes as a Service for everyone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kubernetes is one the major orchestration solutions for Linux containers. It's makes easy to have distributed, self-healing and autoscaling containers clusters.  However operators can have a hard time setting up a Kubernetes cluster. Quite some efforts have to be put in place even for the creation of a simple cluster. Things get even more challenging when security, flexibility and scalability have to be taken into account. And what about making everything automated to satisfy the requests of all the tenants?  Now all developers and operators can run away from this complexity by using the Kubernetes offerings inside of the OpenStack clouds. This talk will show how OpenStack can act as the perfect platform to run Kuberenetes clusters by using the Magnum project. OpenStack Magnum component simplifies the required integration with Kubernetes, and allows for cloud users who can already launch OpenStack resources to also create application containers to run their applications.


* **Michal Jura** *(Michal is associated with SUSE Linux since 2013 as Linux HA/Cloud Developer in Cloud Team. Engineering graduate from the Faculty of Security Systems, Electronics, Wroclaw University of Technology. During his studies he worked in the Institute of Technical Cybernetics and directed the Computing and Autonomous Adaptive Systems scientific student group. He gathered the experience by designing and participating in the construction of different Data Centers. He designed and implemented server infrastructure solution based on Linux Containers. Linux and the idea of Open Source enthusiast.)*

* **Flavio Castelli** *(Flavio Castelli is the engineering manager for the Containers team at SUSE. Flavio has been following Docker since its early days and focused on its integration within the openSUSE and SUSE ecosystems.Flavio developed experience in creating and managing systems while working on products such as SUSE Studio and SUSE Manager. Flavio is also a contributor to various open source projects.)*

Migrating legacy workload to openstack lively
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

At present, openstack has been widely used, but before that many companies have had their own traditional virtualization solution running for long periods. Now these companies want to apply openstack, and at the same time they want previous virtualization solutions to be integrated to and managed by openstack platform, Existing integration solution  is to export original virtual machine as a openstack image, and then import image into openstack platform. There are two problems in this solution, the first is low performance caused by multiple image conversion and image copy, the second is interrupted VM services. we provide our solution to solve them.


* **James Guo** *(I am a senior engineer at H3C. From 2013 I began to pay attention to openstack and became a contributor. My main work is to refine our company's private cloud solutions based on openstack. Currently I focus on nova, ironic and neutron.)*

Galera Cluster - The Highly Available Database Behind OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A recent survey shows that Galera Cluster is the de-facto standard for high-availability of the OpenStack back-end database, protecting Keystone, Nova and Neutron data. This talk will describe the things that are important to know about this critical infrastructure component. In this session, we will discuss:* The role of Galera Cluster as part of the back-end OpenStack infrastructure;* The way Galera operates and how it achieves active-active, multi-master high availability;* The tools that are available for monitoring Galera, the important metrics to watch and the situations that can arise operationally;


* **Philip Stoev** *(Philip Stoev is QA and Release Manager with Galera Cluster, responsible for the overall quality of the product. He has worked on distributed systems and databases for more than a decade at Oracle, MariaDB and NuoDB. His database testing framework, the RQG, is widely used in the MySQL ecosystem and won the Application of the Year MySQL Community Award in 2014.)*

Lessons learnt from running the Linaro Developer Cloud on AArch64
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Linaro is providing developers with access to a cloud-based native ARM development environment, which can be used to design, develop, port and test server, cloud and IoT applications without substantial upfront hardware investment. The Developer Cloud is based on OpenStack Liberty, leveraging both Debian and CentOS, as the underlying cloud OS infrastructure. It will use ARM based server platforms from Linaro members AMD, Cavium, Huawei and Qualcomm Technologies, Inc., and will expand with demand, and as new server platforms come to market. These platforms will include both single socket and dual socket configurations as well as 10/40Gb networking, scalable storage and integrated accelerators that ARM SOC partners are bringing to market. This talk is about how we deployed the Linaro Developer Cloud and how we opened it to developers. We will also explain what the operation of it looks like and talk about the main issues we've encountered.


* **Gema Gomez-Solano** *(I like to make software better, that is essentially how I became a quality engineer and a technical lead. OpenStack and Software Defined Infrastructure has been the main target of my work for the past few years. As the SDI Tech Lead at Linaro I am working closely with many different upstream projects and stakeholders to ensure a good user experience of OpenStack on AArch64. )*

* **Andy Doan** *(I've been working on embedded Linux plaforms since 2006 on everything from bootloaders to managing production aarch64 services. I'm currently the lead of a systems engineering team that's managing a pure 64-bit ARM deployment of OpenStack.)*

Best practices & performance tuning - OpenStack Cloud Storage with Ceph
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, we discuss best practices and performance tuning for OpenStack cloud storage with Ceph to achieve high availability, durability, reliability and scalability at any point of time.  Also discuss best practices for failure domain, recovery, rebalancing, backfilling, scrubbing, deep-scrubbing and operations priority to get high availability and maximum throughput along with maximum IO operations.  It also includes performance tuning for Nova, Cinder, Glance and Swift projects.


* **Ranga Swami Reddy Muthumula** *(Working with Reliance Jio  -  Architect  for Public and Private clouds.)*

* **Pandiyan M** *(Openstack ATC, Working for  Reliance Jio Cloud)*

* **Satish Venkatasubramanian** *(Openstack ATC)*

Cinder Always On - Reliability And Scalability Guide
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cinder (OpenStack Block Storage project) can be found in >80% of OpenStack deployments. Configuring it to be robust, resilient and fast is important. However considering its high customizability, such as choice of deployment architecture, volume backend or backup backend, an always on Cinder is not a simple goal to achieve. In this talk we will explain how Cinder can be deployed in ways guaranteeing increased reliability and performance, as close as possible to "always on". We will walk you through latest innovations that are letting you keep your control plane and data plane up during upgrades, increased load or when experiencing breakdowns. These features include: cinder-volume service in A/A mode rolling upgrades support volume replication volume migration We will also share insight on the improvements in these matters that are planned for the future cycles.                  


* **Michał Dulko** *(Michał is software engineer working at Intel, engaged in OpenStack-related activities since Folsom release. Starting from Newton cycle he is serving the OpenStack community as a core reviewer in Cinder, where he is focused on control plane availability, scalability and upgradability. His professional interests are HA solutions, cluster management and building reliable distributed systems.)*

* **Gorka Eguileor** *(Cinder Core and Senior Software engineer at Red Hat contributing to OpenStack's Block Storage Service. Previous experience includes Artificial Intelligence, Embedded Systems and High Availability mobile payment platforms. Besides leading the effort to support Active-Active High Availability configurations in Cinder, he's also been working during the N cycle on removing DB access races on API nodes, optimizing DB queries on most common operations, and making improvements to the Rolling Upgrades and Microversions mechanisms in Cinder.)*

It's Not Working, What Now?
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Serviceability is an awkward term, and implies that something needs to be fixed -- a situation none of us wants to find ourselves in. But all software has bugs, and all hardware breaks at some point, and so we need to know what to do when the inevitable happens.Serviceability is a design goal: how can each of the projects in the OpenStack ecosystem maximize the ease with which problems are identified, isolated and resolved? What has been done to date, and what can we do to continue and extend the process(es) already in place?Join HPE Distinguished Technologist Harry Sutton in an exploration of these questions, and join the discussion around how to keep your OpenStack environment running with a minimum of disruption.


* **Harry Sutton** *(Harry Sutton, a forty year veteran of the IT industry, is a Distinguished Technologist working in Andover, Massachusetts with GSD Engineering Resolution in HPE’s Technology Services Support organization. He is the global lead for HPE’s Professions organization, and active in several open source communities within and outside of HPE, including most recently the OpenStack Foundation. Harry lives in Newburyport, Massachusetts, and enjoys spending time with his wife and their extended family of pets, especially his African Grey parrot, Toby.)*

Managing clusters of thousands of VMs using Senlin
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Efficient resource pool management is crucial to achieve high scalability and elasticity in a cloud environment. In this presentation, users from China Mobile will share their experiences on managing thousand of VMs using Senlin service. Topics like integrating Ceilometer/Gnocchi with Senlin to support auto-scaling, optimizing OpenStack services to achieve high concurrency, and deploying Senlin on multiple hosts to support service HA will be discussed.


* **Yanyan Hu** *(Yanyan Hu is a researcher from IBM China Research Lab. His research field is mainly about Cloud computing and virtualization. He is now contributing to several Openstack projects, including Senlin, Zun/Higgins, Heat, Ceilometer and also working on business solutions that related to private cloud. Currently, he is focusing on continuous service deployment and management cross multiple region/cloud and hybrid cloud environment, especially autoscaling related topics.)*

* **Qiming Teng** *(Qiming Teng is a researcher working at the Cloud Infrastructure and Service department, IBM China Research Lab (CRL). His research interests include system software, virtualization, cloud, Java resource management, performance profiling tools. Starting from early 2013, Qiming has been researching topics related to high availability, auto-scaling of virtual machines, applications in a cloud environment. His focus is on the Heat and the Senlin project in the OpenStack community. Before Joining IBM, Qiming Teng received a Ph.D. in computer science from Peking University in 2006.)*

* **Eldon Zhao** *(Eldon is staff engineer of China Mobile. He is now focusing on cloud computing and has abundant experience on cloud development and operating.)*

Managing in place upgrades Mitaka to Newton
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Efficient operations: how to upgrade from Mitaka to Newton the easy way. OpenStack is moving fast - it has to to be able to keep up with the rapid pace of chanfge in the technology space. With each new release comes a host of new features that organisations want to take advantage of as quickly as possible so being able to upgrade from one version to another whilst minimising disruption to running workloads is vital. In this session we will talk through how to get from Mitaka to Newton by running an inplace upgrade and how to ensusre that future updates and upgrades will be handled without the complexities that have plagued upgrades in the past.


* **Mark Baker** *(Product Manager at Canonical where I've spent the last 5+ years helping shape Ubuntu server and Ubuntu OpenStack. Previously held positions MySQL and Red Hat helping them disrupt Billion dollar encumbant enterprise software companies. Seem to be on the same path with OpenStack and Ubuntu.)*

Ceph OSD hardware - a pragmatic guide
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session you will learn how to pick the OSD node which just right for your deployment. We will share with you all the lessons we’ve learned the hard way when operating our two Ceph clusters over the past several years. We will cover some recommendations on picking the right hardware for Ceph, as well as some tips on optimising the deployed Ceph cluster for OpenStack.


* **Piotr Wachowicz** *(Piotr Wachowicz is a Cloud Integration Lead for Bright Computing. He's passionate about clouds, networking, and all things software defined. He's been working with OpenStack for several years, and his daily focus is looking after the deployment process, and management/monitoring of Bright OpenStack.)*

Performance Tuning for Openstack Specific Hypervisor
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hypervisors suitable to Openstack are the key to run a cloud, the reality is Openstack performance is not stable as expected due to lack of experience on hypervisor. We will at first summarize Openstack performance issues and bottleneck, introduce resource isolation and density technologies as solutions for tuning Openstack specific KVM based hypervisor, and share best practices about Openstack hypervisor performance tuning. The agenda is as below:1. Performance issues and bottleneck on Openstack2. How to tune a generic KVM hypervisor to an Openstack specific hypervisor for high performance3. Hypervisor tuning introduction on Isolation and density of CPU, network, memory and IO4. Hypervisor workload monitoring and benchmark5. Openstack performance tuning statistics analysis and comparison among various flavors of hypervisor6. Openstack Hypervisor operation experience including update/upgrade/migration7. Best practices on Openstack hypervisor performance tuning


* **Long Quan Sha** *(Long Quan Sha is a software engineer at IBM. His working areas were from IBM Systems Director, Flex System Manager to IBM Cloud Management (ICM). Currently his work mainly focus on public cloud performance solution . He has rich experience on openstack solution deployment, integration and performance tuning.        )*

* **Ethan Lynn** *(Ethan Lynn is a software engineer in IBM, and he starts working on openstack projects at 2013. During his school time, he focus on IPv6 and IPv4 translation technicals, and help to build experimental IPv6/IPv4 translation router on BUPT CERNET2 node. During his work in IBM, he helps to build up IBM cloud production based on openstack, and help design and deliver HighAvailability solution for openstack services. He contributes lots of codes and reviews to openstack projects, especially heat and senlin project, and receive open source recognition award from IBM.)*

You Got Your Cloud in My Mainframe!  Confessions of a 3rd-Party CI Operator & Enterprise Consultant
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We've seen patterns emerge in mainframe cloud deployments, and from running our Third-Party CI system.   OpenStack on z/VM runs the hundreds of Ubuntu, Red Hat, and SUSE VMs in the LinuxONE Community Cloud ... and its OpenStack controller... on a single system.   Our CI system runs 20 tempest runs in parallel, with 4 x86 blades all pounding away at a single system.   Our enterprise users include major banks, insurance companies, payroll processors, healthcare providers, and IT service providers.   We'll share things we've learned along the way about playing nice with what-is in the enterprise, scaling compute nodes, and images that go Bump! in the night.


* **John Arwe** *(I've grunged around in the mainframe kernels (z/OS SRM/WLM mostly, recently a bit of z/VM and zKVM) for many years, and took a wide detour doing standards and open source work (W3C SML and LDP, OSLC, OASIS, DMTF, Eclipse, REST APIs, Linked Data) in the middle. Lately I've been schizophrenically focused on both the z/VM nova CI system and architecting/debugging client deployments of the OpenStack and hypervisor back-end components.)*

* **Ji  Chen** *(Ji Chen is a software engineer in IBM who focuses mainly on z/VM system management (s390x arch).  His daily work includes mainframe z/VM virtualization enablement on OpenStack, including the total stack of z/VM system management software such as SMAPI, xCAT, OpenStack enablement components, etc.  He is an active nova upstream community contributor.  Before working in IBM, he worked in Samsung and UTStarcom majoring in embedded system development such as embedded DBMS, operating system , file system etc.)*

Production Readiness for Private Clouds with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack offers a lot of different ways to be deployed and even more to be configured. Every enterprise has their own security and operations standards and requirements that are known as Cloud Production Readiness. In this session, we will share the requirements for Workday’s production ready cloud as well as the development work implemented by the Cloud Engineering team in order to fulfill them all. Attendees will learn from a real production cluster how to achieve production readiness in a private cloud without making the typical pitfalls which normally brings frustration to the team and lost of trust to the stakeholders of the project. During the session we will show monitoring and logging real-time dashboard to demonstrate how the “Network Operation Center” monitor the health of the production platform.


* **Edgar Magana** *(Edgar is an emerging leader who has specialized in Cloud Computing, Network Virtualization, Software-defined Networking (SDN), Network Functions Virtualization (NFV), OpenFlow and OpenStack. He has developed excellent software development skills and outstanding customer and business driven experience. Currently, he is core member of the Neutron OpenStack development community. Edgar has strong experience in fully automated Cloud Computing deployments by means of puppet and chef orchestration languages. He has lead OpenStack development, third-party integration and deployment teams for over the last three years. Edgar is the lead architect responsible for driving the Cloud Operations initiatives that maximize the pace of innovation with Development and Operations. He is in charge of provifing architectural oversight for Workday’s Hybrid Cloud including the OpenStack based Private Cloud, bursting to multiple Public Clouds and extensive automation. Through strong collaboration, develop architectures, detailed designs, and in some cases POCs to support Development driven features requiring changes to the infrastructure.Establish tight alignment with Development Architects, representing Cloud Operations in the Technology Architecture Group. Edgar has an extensive experience on Cloud and Grid Computing, Policy-based Management Systems, Monitoring and Scheduling of networking and computational resources on distributed networks. He has been involved in multiple projects such as Cisco Quad, Cisco Enterprise Policy Manager, Access Control Server and Application Performance Assurance.)*

Supercharging Heat with the Open Patterns Engine
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Heat orchestration templates are very useful on their own, but combine them with Salt for configuration management, Git for source code management, a media library for binary files, a graphical/text editor for your source code, and a runtime management system for "day two" operations and you have something that truly supercharges Heat.  We call this powerful combination of technologies the Open Patterns Engine. By an "open pattern" we are speaking of a means for using open technologies to describe the OS images, application software, configuration management scripts, and orchestration steps that go together to deploy and manage a software stack.  These patterns provide a way to treat infrastructure as code.  We call the engine that interprets these patterns the Open Pattern Engine.  Our presentation will describe and demonstrate how you can put the Open Pattern Engine we've built to use, or learn how you can build a similar one of your own.


* **Joe Wigglesworth** *(Joe Wigglesworth is a Senior Technical Staff Member at IBM and has been a member of the OpenStack community since 2013. His current assignment is with an IBM development team, focusing on integration with open technologies such as OpenStack and Docker.  He is co-author of the textbook: "Java Programming: Advanced Topics" and a recipient of the University of Toronto School of Continuing Studies' Excellence in Teaching Award.)*

* **Radu Mateescu** *(Radu Mateescu is a Senior Software Engineer at IBM, based out of Toronto, Canada, who is focused on open source solution for systems management, virtualization and cloud technologies. He has been involved with the OpenStack community since 2013. He holds a M.S. degree in Computer Science.)*

Managing Mistral Workflows with CloudFlow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CloudFlow is a brand new graphical toolkit for managing Mistral workflows in the most convenient way possible. The Mistral workflow service has been around for 3 years, gaining a solid community of users who apply Mistral for a large variety of use cases. Since the beginning however, it's been challenging to work with complex parallel workflows that consist of tens or even hundreds of tasks, just by using command line interface or RESTful API. Not easy to trace errors, see the entire workflow structure or make changes. Something has always been missing... But what?  Presenting CloudFlow! With CloudFlow it’s now easy to build workflows in a drag-n-drop style. CloudFlow provides the ability to view graphical representations of workflows, run & debug them, trace errors and do a bunch of cool stuff. In this session, we'll introduce the shiny new member of the OpenStack community, code-named CloudFlow, and show a demo of how managing Mistral workflows just became a walk in the park…


* **Renat Akhmerov** *(Senior Software Engineer at Nokia. His primary expertise is distributed computing and HPC, Concurrent Programming, Java, Spring and In-Memory Data Grids (GridGain, GemFire, Coherence) as well as significant experience in framework development. For the last two and a half year he's been mostly working on Mistral Workflow Service for OpenStack. Since the very beginning of the project he’s been actively contributing in both architecture design and implementation. He’s also been working as a community lead and presenting the project publicly.)*

* **Guy Aharonovsky** *(Full-Stack developer in the broader sense of the term. From pixels to metal through business domain, startup mentality and building A teams. Jack of all trades and master of some.)*

Cinder, Manila, Smaug Standalone deployment could be as sds controller
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

 With Cinder, Manila,Smaug,Keystone but not other openstack component as software-defined storage controller to manage and automate all storage resources for traditional and next-generation cloud storage platforms. The solution is based on opensource Cinder, Manila, Smaug, but more than that. It is storage automation software that centralizes and transforms storage into a simple, extensible, and open platform. It abstracts and pools resources to deliver automated, policy-driven storage services on demand through a self-service catalog,resource-oriented protectable service with Cinder, Nova and Smaug – reducing time, cost, and risk.


* **Tao Bai** *(Over 12 years on IT software design and development. 3 years Cinder development and contribution.  Right now, working in Huawei Company as OpenStack Architect in the private cloud and public cloud domain. Responsible for Cinder, Manila development and an opensource software-defined storage controller , data protection in public cloud and private cloud domain.)*

Anatomy Of OpenStack Neutron through the eagle eyes of troubleshooters
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The anatomy of an OpenStack project is different when looked at from the perspective of different roles, such as developers, system administrators, and support engineers (troubleshooters), etc. While a developer prefers to concentrate on certain areas of the code, an architect perceives the project as different pieces that need to be reconciled. System administrators and support engineers have to see both worlds when it comes to troubleshooting.In this session, you’ll learn the anatomy of OpenStack Neutron troubleshooting from the point of view of a system administrator and a support associate. We’ll discuss how a Neutron looks when we hit an issue, and how we troubleshoot to isolate the problem to a specific component. We’ll explain these challenges using examples from real troubleshooting production issues.


* **Sadique Puthen** *(I am passionate about building, designing and supporting Infrastructure for workloads, especially Cloud IaaS, using open source technologies, primarily concentrating on Openstack and Virtualization with good knowledge of core Red Hat Enterprise Linux, clustering, storage and networking. Experienced in designing and building Infrastructure (Network, Storage, Operating Systems, etc) for complex applications and workloads for their entire life cycle from development, test cycles, production deployment, and post production monitoring and support of the infrastructure. Area of Expertise, - Cloud IaaS implementation, design and support using Openstack.- Virtualization RHEV, VMware and etc- Skilled in Virtualization and cloud with continuous working experience starting with RHEL/CentOS + Xen/UML back in 2003, RHEL+ KVM, RHEV, VMware, HyperV and Openstack.- Designing and supporting Networking, storage and High Availability solutions.- Expert level knowledge on Linux, especially Red Hat Enterprise Linux.)*

Linux Containers - LXD - Integration with Nova
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

eBay Inc. has one of the largest deployments of Openstack clouds and has been at the forefront of deploying Openstack in several environments that include eBay MarketPlaces, development, analytics and QA environments. In this talk we present the challenges faced in integrating with nova LXD to serve our massive muti-tenant cloud needs and our architecture and solutions to address them. We will go through our topology, deployment patterns, migration, feature implementations and enhancements to Openstack Nova LXD. Some of the areas we will discuss are listed below: Brief overview of the cloud architecture at eBay LXD onboarding and deployment process LXC Instance resize and migration Overlay (SDN environment) and Bridge Networking Monitoring and Remediation LXC Instance booting on remote volume Version compatibility with other components LXD vs Docker We will conclude with our observations and best practices recommendations.  


* **Vivek Jain** *(Leading Load Balancing and Storage Solutions at eBay Inc.)*

* **Xiaobin (Andrew) Qu** *(An software engineer focusing on: Baremetal services Cloud orchestration Undercloud stuffs)*

* **Dakshi Kumar** *(Openstack developer)*

Private Floating IPs for openstack Tenants
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Separate the notion of Floating from the actual network from which these IPs can be derived. This means that have a tenant specific FIP pool from which these Floating IPs can be derived. Via this mechanism we can restrict opening up access to backend systems directly to the data center/internet network and still achieve IP Failover using a pool of private Floating IPs


* **Shashank Jain** *(Shashank Jain has around 16 years of applications development experience based on different application servers and Cloud platforms.  Have worked in area of cloud computing on platforms like AWS, Openstack and Cloud Foundry. Has been working in area of containerization with Docker and Rocket. Has interests in area of distributed computing and Big Data platforms)*

Automate Windows Images for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Building Windows images for OpenStack can be tricky if you're not experienced in automating Windows, from Windows 7 until Windows Server 2016. In this session we will describe and demo the automated tools used to fully automate the official Microsoft Windows Server OpenStack trial images, including drivers for multiple hypervirors (KVM, Hyper-V, ESXi), including Cloudbase-Init, performing Windows updates and much more.  We will also demo how to use Cloudbase-Init to run userdata PowerShell scripts on Nova boot and Heat templates to easily automate Windows workloads.


* **Alessandro Pilotti** *(Alessandro Pilotti is the CEO of Cloudbase Solutions, a company focused on cloud computing interoperability and the main contributor of all the OpenStack Windows and Hyper-V components in Nova, Neutron, Cinder, Ceilometer and Heat since the Folsom release. Alessandro lives in Timisoara, Romania. When not hacking or travelling, he is flying with his paraglider into old fashioned clouds.  )*

* **Peter Pouliot** *(I help to maintain OpenStack integration with Microsoft's Virtualization platform Hyper-V. My tenure at Microsoft began in March 2012 with a task of organizing community members to restore and maintain Hyper-V intgration within OpenStack.  Our team was successful in restoring the Hyper-V functionality to OpenStack in time for the Folsom release and the Continouous Integration Infrastructure running for the Juno release. I currently act as the OpenStack subject matter expert within Microsoft as well as the evangelist for OpenStack awareness and adoption of OpenStack Windows platforms. Prior to Microsoft I worked for Novell in the Joint Interoperabilty Lab with Microsoft.  There our team focused on testing and validating Linux workloads on Hyper-V and Windows workloads on Xen and KVM.  In April 2011 I successfully deployed the first OpenStack Cloud using Hyper-V and began my evangelism for Hyper-V within the OpenStack community. Additional experiance includes linux high avialability, network and datacenter infrastructure and security.    )*

* **Adrian Vladu** *( Started with JS/Php, moved up to C#/.Net and now navigating through the dev-ops spaces, both Linux and Windows. During the past four years, I have been working on OpenStack integration with Microsoft technologies and contributing to other open source projects. One of my favourite activity at and outside the office is giving back to the people the knowledge I have accumulated. When I am not debugging some issue from a far-away galaxy, you can find me reading science-fiction, playing League of Legends or enjoying a nice German beer.)*

Deep performance tuning with Intel Resource Director Technology to make sure the QOS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In a NFV environment, we need to guarantee VNF nodes quick response to provide high quality service. Currently, no good solutions yet. Intel® Resource Director Technology (RDT) provides the hardware framework for monitoring and control of shared data center resources. It includes Cache Allocation/Monitoring Technology (CAT/CMT),  Memory Bandwidth Allocation/Monitoring (MBA/MBM) etc. With these help, we will have good control for our cache, memory bandwidth resource, we can reserve resource for much more import workload such as for an NVF node, import data base server etc. As also RDT provides resource monitors we could use it to monitor resource usage on all OpenStack cluster which will provide a new metric for the cluster administrator to measure cluster. In this session, we will share an experience how we use RDT on OpenStack to control cache/memory bandwidth in our routine testing environment, which help use to immensely improve the work efficiency.


* **Qiaowei Ren** *(Joined intel in 2012. Be responsible for linux kernel enabling and the development in OpenStack.)*

* **Chen Meng** *(System Engineer @ Intel)*

T-Systems Open Telekom Cloud (OTC) powered by OpenStack: Experience with DefCore certification.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Open Telekom Cloud builds on a cascaded OpenStack configuration that is accompanied by vendor specific software to provide the advantage of cloud specialized hardware to IaaS customers. At the core OpenStack Juno with dedicated backports from younger releases is used making this a tailored version.  Committed to open source and to ensure compatibility to OpenStack capabilities and APIs we are bound to do the DefCore certification. Even it is not challenging enough to pass the tests in this configuration itself the setup of OpenStack has to fulfill product requirements from T-Systems to provide a secure and quality services for customers on top of it. This talk is about our journey and learning to archive DefCore certification. We want to share how we bridge the technical obstacles originated from demands of the different parties and cultures involved, as well as what we were able to give back to the DefCore team to improve OpenStack as the leading open source cloud platform.


* **Christian Kortwich** *(- Build cloud platform with OpenStack for small and medium business partners since 2012 at Deutsche Telekom and T-Systems International - Software development and integration for multi service access network nodes (MSAN). - Build platforms for telecommunication systems in mobile core network, business support and access network. - Software Development and cunsulting for command and control systems for police and fire brigades - Working in ESA and ESPRIT research projects for robotics and spaceflight (LORA) - Software development on robotic test beds - Feasibility studies for industry to improve effiicentiveness - Administration of UNIX and DEC machines and networks)*

Open Telekom Cloud: Hybrid-cloud management with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Working together with Huawei, T-Systems has built a large-scale European public cloud, the Open Telekom Cloud, using OpenStack. Separate OpenStack clouds deployed in multiple data centres are consolidated into single cloud environment using Cascading OpenStack (also known as the Tricircle project under the Big tent). Furthermore, through the use of unified Neutron overlay networks, and API connectors for other clouds, we have succeeded in integrating multiple heterogeneous 3rd party clouds such as AWS and vCloud, into the unified Cascading OpenStack framework. This allows us to flexibly deploy virtual machines & Docker containers across this hybrid environment using the full standard OpenStack APIs and SDKs with consistent capabilities and seamless user experiences. Additionally, storage replicators have been developed for easy migration of virtual machines & Docker containers from one cloud to another—truly an open cloud!


* **Anthony Clarke** *(Anthony Clarke has worked in IT for over 25 years and in outsourcing for more than 15. During that time, he has held various roles in software development, server, storage, firewall and database operations, architecture and management. In recent years, he has focused on cloud computing solutions, supporting colleagues and customers in making the best use of this fascinating and dynamic technology.)*

* **Dennis Gu** *(Chief Architect of Cloud Computing solution of Huawei Technology, key member of the expert group of “China Cloud” project sponsored by Ministry of Science and Technology, lead the technical planning and architecture designing of Huawei Cloud OS FusionSphere, and convergent infrastructure FusionCube, which have supported Huawei to win over 350 Cloud Computing commercial projects around the globe. Joined Huawei Technology in 1998, served as Chief Architect of Huawei Mobile Softwitch product and IP Multimedia Sub-system(IMS) solution, which ranked No.1 in the Telecom industry on both technology competence and market share , and deployed in leading Telco carriers like Vodafone, DT, Orange, Comcast, CMCC etc. Winner the National Science and Technology Award of China in Year 2012 & Year 2014. Owning 30 + authorized technical innovation patents.)*

Deploy cloud service with Heat and Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this topic, we will show you how to leverage Ansible and Heat to bootstrap clustered applications in Openstack cloud platform. The OpenStack cloud platform is built on a variety of separate interlocking services - including separate services for storage, networking, identity, and more. We use Heat to orchestrate the resources of clustered applications. And configuring application is an complex task. We’ve got frontend and backend services, databases, monitoring, networks, and storage for an application. Each has their own role to play with their own configuration and deployment. We use Ansible tool to ensure all these tasks happen in the proper order. After all, we have the performance report for the newly configured application cluster according to presumed workload for user informantion.


* **Zi Lian Ji** *(Work in IBM for 5 years and focus on Cloud Comuputing  & OpenStack Telemetry project now.)*

* **Tianhua Huang** *(Tian Hua Huang is working at Huawei. She began to contribute to OpenStack community since 2013, now she focusing on openstack heat design and bug fixing, she is core review member of openstack heat community.)*

* **Linjuan Xia** *(Xia Linjuan has worked for IBM since April 2015 on cloud related products. She started working on openstack community during L and M release and has been focussed on Ceilometer/Gnocchi. She has contributed several patches in the community. )*

Reality check for OpenStack and CloudFoundry: Perfect Marriage or Divorce in the Making
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud Foundry is an open source PaaS that provides a choice of clouds, developer frameworks and application services. With Cloud Foundry, a developer can easily and quickly build, test, deploy and scale micro-service applications. OpenStack IaaS and CloudFoundry PaaS is considered by some to be a perfect marriage. But as in any marriage, there are many challenges and hardships we need to overcome in order to be successful. This session will explore the deployment process and share the most common challenges with storage, networking, API connectivity, etc. that users will face during the deployment process as well as how to troubleshoot them. We will also discuss how the Cloud Foundry uses BOSH to deploy, manage and monitor the life cycle of distributed applications and how everything ties together with OpenStack. Are OpenStack and Cloud Foundry a match made in heaven? Come find out in this session.


* **Magdy Salem** *(Magdy has more than 18 years of experience with enterprise software development in a wide variaty of languages such as Java, C++, C#, Python and Go. His work at EMC is focused on the design and development of cloud base applications using microservices architecture, CloudFoundry and OpenStack. )*

* **Adrian Moreno Martinez** *(Adrian is a software engineer at EMC. He is part of a team focused on engaging and enabling modern application developers, DevOps teams and next-gen ISVs. He is responsible for leading some OpenStack and DevOps related projects. In the last 5 years he has been mainly working in Cloud computing and distributed systems. Prior to EMC, he had the oportunity to work in an FP7 european project at the University Rovira i Virgili in Tarragona, Spain. There, he was one of the founders of StackSync, a fully-featured personal cloud that integrates with the OpenStack platform.)*

* **Rabih Majzoub** *(Rabih is a senior systems engineer working for EMC Canada for the last 5 years. He spends his time on helping EMC customers with their openstack deployment as well as troubleshooting and resolving any issues that might arise. He also helps with automating some of the deployments by writing python and bash scripts. Rabih is a active member within the EMC community and the cloud world fascinates him. He currently live in Vancouver, Canada.)*

Getting the Most Out of Rally for Improving Scaling Behavior
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Rally project gives OpenStack developers and operators relevant and repeatable benchmarking data to determine how their clouds operate at scale. In this session, learn how to use Rally to deploy your cloud, runs specified scenarios, and retrieve/analyze the results of those tests. In this session, you will learn how to install Rally, then configure and connect it to your OpenStack instance. We’ll then discuss best practices to design and run benchmark scenarios, and how to generate benchmark data reports. If you need to know how your OpenStack cloud will handle scaling, this session is for you. Scaling is hard, but Rally can help. Attend this session to unlock a wealth of community wisdom on how to make sure your OpenStack cloud is up to the challenges of scaling.


* **Magdy Salem** *(Magdy has more than 18 years of experience with enterprise software development in a wide variaty of languages such as Java, C++, C#, Python and Go. His work at EMC is focused on the design and development of cloud base applications using microservices architecture, CloudFoundry and OpenStack. )*

* **Javier Soriano** *(TBD)*

* **Mohammad Itani** *(Expert with Networking and Data Center Architecture and Troubleshooting. Escalation Engineering for IAAS managed by OpenStack. Testing IAAS Architectures around OpenStack solutions.)*

Hello World for Murano - end to end process in a Docker container and more
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We've all faced challenges in porting applications to run on OpenStack. Murano helps by enabling cloud admins to publish a well-tested set of on-demand and self-service applications. End users can simply use the applications. But, have you ever wanted to set up Murano to explore its features, but been frustrated with putting all the required packages and their dependencies together and configure them correctly? Have you ever tried to build your own application catalog or create your own images, only to find out you are facing a steep learning curve. In the presentation, we will demonstrate a simple end-to-end process for getting Murano running on your dev environment or your laptop by running Murano in Docker containers. We will also demonstrate the details in case you want to dive deep into Murano including configuring murano API server and engine, building your own application images and catalog, how to upload the application catalog and deploy them using cli or UI.


* **Magdy Salem** *(Magdy has more than 18 years of experience with enterprise software development in a wide variaty of languages such as Java, C++, C#, Python and Go. His work at EMC is focused on the design and development of cloud base applications using microservices architecture, CloudFoundry and OpenStack. )*

* **Lida He** *(Lida He is a cloud solution architect at EMC Corporation. He has been developing OpenStack based cloud solutions including VxRack Neutrino, a hyper-converged multi-service cloud native solution, and has been helping customers to design IaaS and PaaS to support third platform applications in a wide variety of environments. He also worked on OpenStack monitoring solution for availability, performance and chargeback, and was involved with developing cinder drivers for some industry leading storage products. In addition, he has been actively involved with deploying Cloud Foundry on OpenStack and developing applications on top of it. He is inspired to become an active contributor to the OpenStack projects and community.)*

* **Julio Colon** *(I’m a Consultant Software Engineer for Emerging Technology Division.  I have been working EMC Storage Arrays and SAN technologies for about 15 years.  During my time at EMC I have performed multiple roles: Quality Engineering, Developer, Security, QA Manager, Development Manager, and Release Manager.  My current roles cover: deployments, software and hardware testing, customer enablement, engineering escalations, apps and tools development. When I am not working in EMC, I like to work with new technologies (e.g. IoT electronics, computer languages), mentoring, and spend time with the family.)*

Four studies, one conclusion: Who is an OpenStack user?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack UX project has collaborated with the user committee, foundation, and individual projects to conduct a series of studies with users to help improve the overall user experience associated with our projects.  The research efforts spanned multiple areas; including quotas, support and documentation, application developer experience and the OpenStackClient.   The OpenStack UX team will briefly discuss each of the studies that have been conducted on behalf of the community - including research methodologies, findings, and how the results impact OpenStack development.  The talk will have a greater emphasis on the results and, when appropriate, recommended solutions.


* **Piet Kruithof** *(Piet is an accomplished User Experience (UX) Architect and User Researcher with over fourteen years of focused contributions to software and hardware development. He is currently working as a Sr UX Architect with Intel's Open Source Technology Group and is PTL for the OpenStack UX project. Piet is a former Director with the Board of Certification in Professional Ergonomics (BCPE). The board was established in 1990 as an independent nonprofit organization and is the certifying body for individuals whose education and experience indicate broad expertise in the practice of human factors, ergonomics and user experience research. His education includes a bachelor's degree in Industrial Design from Western Washington University and master's degree in Human Factors Engineering from Virginia Tech.)*

* **Ju Lim** *(Ju Lim is a Consulting Engineer at Red Hat. She has over 12 years experience focusing on User Experience on a wide range of platforms including storage, compute, networking, and cloud. In recent years, Ju has been driving user experience improvements in several Open Source projects. She has 5 patents awarded to-date.)*

* **Danielle Mundle** *(Danielle Mundle joins the OpenStack community as a User Research Engineer. Her goal is to understand the users, workflows, and requirements of OpenStack to identify opportunities for improvements and novel solutions. As a practicing user experience consultant for the past six years, she has performed expert reviews, user-based testing, card-sorts and other user research and design activities for over 85 studies for academia, industry, healthcare, and government clients. Danielle has professional certification from the Board of Certification in Professional Ergonomics as an Associate Human Factors Professional (AHFP). She is a member of the Human Factors and Ergonomics Society (HFES), Usability Experience Professionals Association (UXPA), and the Order of the Engineer. She holds an M.S. in Industrial and Systems Engineering with a concentration in Human Factors Engineering and Ergonomics and a Certificate in Human-Computer Interaction from Virginia Tech, and a B.A. in Psychology.)*

QoS QoS Baby
~~~~~~~~~~~~

**Abstract:**

Quality of Service (QoS) is typically associated with networking, however it can be applied to all components that make up the cloud infrastructure (i.e. compute, network and storage).  In fact, unless a cloud-wide approach to QoS is taken, enabling QoS features may not have much of an effect on performance. This session will explore the QoS features that are currently available or upcoming in OpenStack, with an eye toward coordinating QoS across the entire cloud infrastructure in order to ensure that the cloud will meet the demands of critical applications.


* **Anne McCormick** *(Anne is a Software Engineer who joined the Cisco OpenStack team in 2014, and has attended the past four OpenStack summits. She is an active member of Women of Openstack, and has a background in networking, video, high-availability and virtualization.)*

* **Robert Starmer** *(With 20+ years in systems automation and datacenter applications, I find all things cloud interesting, with a focus on all of the automating possible these days!  Intrested in enabling operable OpenStack with bare-metal, virtualized, and conterized compute, the CAPS tools, and Dev/Ops CI/CD pipelines as well as enabling performance and scale for multi-tenant services.)*

* **Alka Sathnur** *(Alka is a Software Engineer who joined the Cisco Content Delivery Network team in 2015, and has been a member of the DevOps team managing on-prem Customer CDNs. She has a background in networking, video, high-availability and Dev Ops.)*

Single pane of glass management of OpenStack, Ceph, OpenShift with Ceph running Containers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A vital need for any technology group is to present new, cloud-based associated administration that can help advance product and service offerings. These may include versatile applications, cloud client gateways, and dedicated systems administrations.   Building a scalable Open Source hybrid cloud built on a combination of OpenStack, Ceph, OpenShift, Anisble and CloudForms can enable customers and service providers to simplify the provisioning of a multi-tier architecture that can be presented to multiple tenants, customers, business units or resellers.    This infrastructure design is implemented to help support the growing continuous integration and DevOps model. OpenStack-based clouds allow the flexibility for both customers and service providers to achieve and exceed service level agreements. 


* **Nicholas Gerasimatos** *(As a Cloud Evangelist, I work with key Certified Cloud Service Providers to design, build and integrate Red Hat product offerings into the Certified Cloud Service Providers portfolios, data centers, lines of business, and route-to-market offerings. I also work closely with Certified Cloud Service Providers to create and deploy Public, Private, and Hybrid Cloud solutions. My primary responsibilities are developing executive relationships, acting as a trusted advisor and helping influence and accelerate the adoption of Red Hat emerging technologies within Certified Cloud Service Providers.Share the Red Hat vision of multi-product offerings, create awareness of emerging technologies and positioning Red Hat as a thought leader in Public, Private and Hybrid Cloud.  Partnering with the Alliance teams I help develop Red Hat Enterprise Linux OpenStack Platform and OpenShift/Atomic Platform-as-a-Service, Red Hat CloudForms, Red Hat Storage, and the Red Hat JBoss Middleware technology portfolio. Technology Focus: Software Defined Storage, Software Defined Networking, Infrastructure as a Service; OpenStack, CloudStack, Amazon Web Services, Google Compute, Azure, Platform as a Service; OpenShift, Middleware, Continuous Integration Tools, Git, Subversion, Jenkins, Vagrant, Docker, Puppet, Ansible, Salt.)*

* **Jeff Ekstrom** *(Jeff Ekstrom is a cloud evangelist for Red Hat’s Certified Cloud and Service Provider program. He has extensive experience with cloud strategy and architecture, with industry experience in Telecommunications, Federal Government, and Insurance. His cloud strategy focus includes both open source technologies and hybrid cloud enablement. Jeff joined Red Hat in late 2015, where he has been promoting and designing Red Hat solutions within Red Hat's partner ecosystem. Prior to that, Jeff's experience includes companies such as Accenture, The Coca-Cola Corporation, and SAIC. )*

A day in the life of an OpenStack operator
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A lot of focus is spent on just deploying OpenStack. However, the real effort in operating OpenStack involves continuous validation, monitoring, troubleshooting, patching, scaling, reconfiguring, capacity planning, securing, and upgrading your private cloud.Join our session to learn best practices around OpenStack operations and day two activities:* Patching, upgrading, and scaling (Ansible and TripleO)* Monitoring (Sensu, Uchiwa, ElasticSearch, Kibana, Fluentd, Collectd, Grafana, and more)* Configuration management, backup, restore, and version control* Capacity management, chargeback, and showback (ManageIQ)* Continuous environment validation (Rally and Tempest)* Containerizing upstream operations tools (Docker)* User-facing operationsLearn how to take advantage of upstream projects to become an efficient OpenStack operator.


* **Krzysztof Janiszewski** *((Chris) Krzysztof Janiszewski is a memeber OpenStack Solution Architects Team at Red Hat. His main background is in designing, developing, and administering multiplatform, clustered, software-defined, and cloud environments. Chris previously worked as an OpenStack and HPC Architect for Lenovo Professional Services and also led System Test efforts for the IBM OpenStack cloud-based solution for x86, IBM System z, and IBM Power platforms.)*

* **Jonathan Jozwiak** *(Jon Jozwiak is a Sr. Cloud Solutions Architect at Red Hat.  His focus is on helping customers develop innovative cloud solutions based on OpenStack and Red Hat's cloud portfolio.  Jon has spent several years consulting with OpenStack and was involved in developing the cloud practice within Red Hat's consulting organization.  Previous to that Jon's background has been working for large enterprises focused initially on Unix/Linux infrastructure, virtualization, and then cloud. )*

Best Practices for Deploying OpenStack Trove: An Inside Look at Database as a Service Architecture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This hands-on workshop will will share best practices for operating Database as a Service using OpenStack Trove.  You will learn how Trove works along with ways to deploy, configure, and use OpenStack Trove. This session will also share how to use Trove to provision and manage both relational and non-relational databases, take and restore backups, create replicas and use database clusters. You will be able to answer the questions: How are different organizations using OpenStack Trove? What are common architectures for deploying database as a service on OpenStack? What are the supported databases along with the supported functionality? What are the updates to the Trove project in the Newton cycle? What are some common use cases for OpenStack DBaaS You will also have live access to an OpenStack environment that includes Trove pre-configured with databases.  This will allow you to learn basic OpenStack database as a service concepts.


* **Sriram Kalyanasundaram** *(Director of Implementation @ Tesora. )*

Twisted Little Passages: Findinig the path from Heat to setting values on a server
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It is a twisted path from setting a tripleo heat template value to setting configuration setting on a client server.   This presentation will detail the data flow path from setting a value in a heat template to the application of configuration parameters with client puppet modules. This presetnation will use actual configuration options and follow the data path through the heat stack and onto the client machine.


* **Keith Schincke** *(Keith Schincke joined Red Hat in 2014 after many years working at universities shaping minds and for the government where they send people and satellites into space. He is an RHCA III currently working withCeph and Open Stack.)*

The Story of booting VM from Ceph RBD volume
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

eBay has a large scale OpenStack deployment. As a consequence, hypervisor failure is a common thing in daily life. This, in turn, becomes a real harassment for our internal cloud users in terms of VM availability. This talk will go through the overall story of how we address the issue by enabling VM boot from Ceph RBD volume in eBay. In this talk, we will go through different alternatives of booting VM from Ceph storage, the changes we did to make RBD VM as default option based on policy settings (image, flavor, production/dev etc), the challenges along the way and how we managed to fix. In the end, we were able to gradually rollout Ceph RBD based VM in a controlled manner. This talk will also share the latest effort of RBD VM auto-remediation to minimize VM downtime that end users can feel.


* **Yu Qiu (QY)** *(OpenStack Handyman)*

* **Vivek Jain** *(Leading Load Balancing and Storage Solutions at eBay Inc.)*

* **Emile Snyder** *(Emile has developed software on GNU/Linux systems for many years in C++, Python, Clojure and other languages.)*

Can't we all agree?: OpenStack Personas, GUI and UI Text Guidelines for a single user experience
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack community's operators have spoken - there is no consistency between projects and it’s impacting adoption.  Over the past nine months, a team made-up of contributors from the OpenStack WG, User Experience, Docs and Horizon have been working on a set of guidelines that help to build a consistent user experience across OpenStack’s projects. This presentation will discuss the three guidelines including the OpenStack Personas, GUI patterns guidelines and GUI text and how they can be leveraged by the individual projects.


* **Piet Kruithof** *(Piet is an accomplished User Experience (UX) Architect and User Researcher with over fourteen years of focused contributions to software and hardware development. He is currently working as a Sr UX Architect with Intel's Open Source Technology Group and is PTL for the OpenStack UX project. Piet is a former Director with the Board of Certification in Professional Ergonomics (BCPE). The board was established in 1990 as an independent nonprofit organization and is the certifying body for individuals whose education and experience indicate broad expertise in the practice of human factors, ergonomics and user experience research. His education includes a bachelor's degree in Industrial Design from Western Washington University and master's degree in Human Factors Engineering from Virginia Tech.)*

* **Jeffrey Calcaterra** *(I am a user experience (UX) researcher. I specialize in products for managing servers and other information technology (IT) infrastructure. I am currently the user research lead for the Hybrid Cloud team. Before that I was the design lead for IBM Cloud Manager with OpenStack. I am also work with the OpenStack Community. I also have a number of patents and chair the Systems user interface patent board at IBM. I started my career designing the first versions of many software utilities still shipping on ThinkPad laptops and in between worked on a number of websites, Eclipse plugins and lots of other things. I have a Masters Degree in Human Factors and Industrial Organizational Psychology from Wright State University and I have a Computer Programming Certificate and a Bachelors degree in Psychology from North Carolina State University. I love the challenge of finding simplicity in a big mess of complexity.)*

* **Rodrigo Caballero** *(Born in Mexico, Rodrigo studied Engineering Physics and Technical Writing in Germany. His experience extends across multiple industries, such as finance, electrical and mechanical engineering, and software development. Hired by Intel in 2014, Rodrigo spearheaded the documentation effort for the Linux Foundation's Zephyr Project for IoT devices. Today, Rodrigo is focused on improving the OpenStack documentation as well as the overall user experience.)*

Pitfalls on the way of migrating legacy applications to latest OpenStack (Xenial+Mitaka)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NTT West, Japanese major telecommunication provider company, migrated existing virtualized environment consist from legacy servers and SAN storages to OpenStack Mitaka on Ubuntu16.04 LTS.   This project caused various changes of infrastructure, operation and culture. We focused issues derived by those changes which are conflicts with migration and operation of existing application. To mitigate these issues, we adopt multi vendor Cinder storage and use them as boot volume with multiple AZ. This enables virtual servers to be configured HA cluster with shared volume.We also designed cinder-volume and cinder-backup use cases based on existing backup process.   In this presentation, we introduce issues and resolution not only for migration of legacy application but also caused by using latest version of Mitaka and Ubuntu16.04(Xenial). We also share existing issues and future improvements.


* **Shigeaki Kimura** *(Shigeaki Kimura is an assistant manager at R&D Center, NTT-West.He is engaged in the development of a server platform for providing telecommunication services.He is challenging the OpenStack to evolve NTT-West's server infrastructure every day.)*

* **Hiroshi Koiwai** *(Hiroshi Koiwai has been active mainly on infrastructure technology several years and leads an organization of OSS/Cloud technical development & promotion recently.)*

* **Takahiro Higashi** *(Takahiro is a Senior Architect at Solinea KK which is Japanese liaison of Solinea, Inc. Takahiro brings over 20 years of technology and management experience to the Solinea KK. Prior to joining Solinea, Takahiro worked for cloud company and managed cloud platform support force. His background is in software development product management.)*

Pacemaker Debugging
~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Pacemaker is being used to manage core services in many OpenStack installations (Ubuntu, Red Hat, Suse, Mirantis, and others). For operators who wish to be more familiar with its inner workings, this talk will go over Pacemaker's architecture and basic troubleshooting steps. We will cover troubleshooting approaches, log analysis, and the architecture of Pacemaker itself.


* **Michele Baldessari** *(Michele has juggled many different IT roles in the last 15 years. He has worked as a translator, trainer, manager, system administrator and linux support engineer. He currently works in the High Availability team at Red Hat as a senior software engineer, working on the high-availability control plane for openstack. He is based in South Tyrol where he enjoys hiking and raising his kids.)*

* **Andrew Beekhof** *(Andrew is best known for his work on Pacemaker which he created inMunich while working for SuSE. Since then he as moved back toMelbourne and is currently employed by Red Hat as a Principal SoftwareEngineer, consulting on Pacemaker and creating architectures to meethigh availabilty requirements.)*

Enable GPU virtualization in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nowadays, GPUs have become much more powerful while being energy efficient. With the rise in popularity of 3D applications, growth in Big Data analytics, High Performance Computing, and streaming video, GPUs are being pressed into service to gain performance. Traditionally in virtualization usages,  a physical GPU is allocated to a VM using PCI device pass-through, an approach that limits resource sharing. However, graphics virtualization support today enables GPU sharing on par with CPU sharing with tenant isolation, enabling cloud workloads to benefit from GPU processing while allowing cloud providers better returns on their infrastructure investments and thus reducing total cost of ownership. This presentation will introduce how to accelerate GPU intensive workloads in OpenStack with Intel GPU virtualization technology. We shall demo its use in OpenStack. Come learn how to make your cloud richer and even more performant to meet the demands of the workloads of today and tomorrow.


* **Shaohe Feng** *(Shaohe  Feng, a senior software engineer at Intel, has been working on OpenStack since the Kilo release, with contributions to Heat for object versioning, Nova live migration, Nova API enhancements, and V3 API. He also actively contributes to Heat and Magnum. Prior to Intel, he worked at IBM on virtualization, and brings a depth of knowledge on KVM/libvirt and its ecosystems. He was a core developer of kimchi, an open source project for data center management product for virtual environments.)*

* **Yingxin Cheng** *(OpenStack developer (major in Nova and Congress)    2015.7.1 - Now Software Engineer in Intel                                        2015.7.1 - Now Nanjing University, Software Institute                        2008 - 2015  )*

* **Fred LI** *(Manager of FusionSphere OpenStack opensource team. Leading the team to link OpenStack community and Huawei FusionSphere cloud OS product. Have being worked in Huawei since 2002. Served as System Engineer, Project Manager in Carrier Software area. Now working on productizing OpenStack.)*

A road to active-active mode of MySQL Galera in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Official OpenStack High availability guide configures MySQL Galera into active-backup mode, and so did all OpenStack Distribution we known. But in fact, MySQL Galera is a Multi-matser Cluster which is designed to work in active-active mode. So why OpenStack uses active-backup mode? Can we change it to active-active mode? This topic will give you a deep analysis on the performance and influence of both mode in stress tests. We will dig into each SQL and show you which part of the SQL is blocking us to use active-active mode.  Finally, we will share our solutions of how to optimize these SQLs.


* **Gangyi Luo** *(Engaged in OpenStack related work since 2014 and specialized in Nova, Ceilometer and OpenStack high availiability. )*

* **Bin Li** *(Specialized in MySQL Galera development.)*

* **Felix Ma** *(Specialized in Cinder.)*

Large Scale OpenStack Cloud Management Using Puppet and Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many people manage OpenStack clusters with Puppet-OpenStack, and some one with Ansible. Everyone knows, Puppet is good at defining the final state of services, whereas Ansible is good at task scheduling. For OpenStack cluster deployment and management, we just need to combine the advantages of both. How? We use Puppet-OpenStack to manage cluster, and ansible to schedule Puppet-OpenStack. So that we cloud rapidly deploy cluster and converges it to the final state. In Qihoo 360, we already use this way to manage a plurality of large OpenStack clusters, and it really makes our lives easier.


* **Xiaohua Yuan** *(Technologist at Qihoo 360. 3 year experience in Puppet-Openstack. Xiaohua Yuan has been working on a series of innovations related with automated operation for large-scale cloud based on OpenStack. Contribution to OpenStack: puppet-nova puppet-trove puppet-cinder)*

Early Performance testing of Openstack Cloud using an Automated performance test framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As we are building value add services in the openstack cloud and functional testing them build on build, it is also critical to performance test those new APIs or functions earlier in the cycle. The performance bottlenecks and the performance trends of APIs build over build are identified using an automated performance test framework that covers deployment to reporting.        In this presentation we will cover:Automated deployment of the performance test bed using AnsiblePerformance test cases for the services (API/Component level) under testHow to Integrate the performance test cases in a CI environmentHow to measure the performance metrics build on build and generate trend graphs in automated fashion


* **Siva Subramaniam M** *(I am working in Hewlett Packard Enterprise for the past 4 years.  Worked on products based on openstack, mainly involved in scale and performance testing using rally, functional testing.  Have worked on CI tools such as jenkins, and written various automation for the CI processes.)*

* **Balaji Ramamoorthi** *(6.5 Years of Experience with Virtaulization, Storage Currently working in Hewlett Packard Enterprise (HPE) as Helion Openstack QA  Scale & Performance Engg )*

* **Maheshkumar Pandurangan** *(Cloud test architect working at HPE)*

RabbitMQ operations: intermediate and advanced topics
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a collection of services that use messaging to communicate. Understanding the messaging layer is important for a successful OpenStack deployment.In this talk, we will cover recommended practices in running RabbitMQ as well as other intermediate-level troubleshooting and operations topics.


* **Michael Klishin** *(Michael is an experienced software engineer focusing on service-oriented architectures, data, and data services. He's currently a staff engineer at Pivotal working on all things RabbitMQ.)*

OpenStack Troubleshooting for beginners
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is powerful. And complex. Troubleshooting OpenStack is not always straightforward because the functionality in OpenStack is delivered by several projects/services working together. We believe that while there is a wealth of well-presented documentation on different services in OpenStack there is a clear lack of good knowledge when all the pieces come together in a real world scenario. We believe that with the learnings and experiences we faced in the field on OpenStack deployment we will be able to present the viewer with a clear step by step procedure on tacking most common issues that we face today in OpenStack. This session is going to re-iterate and reinforce the ideas of an experienced OpenStack troubleshooter and will work as a revision session for them.


* **Nebu Mathews** *(I have expertise in Solution Architecture and design of Fault and Performance management solution. I am fully conversant in the process of designing a solution, including study of network design and identifying software components that shape a performance management solution. I have extensive hands on experience & customisation knowledge of EMC M&R (Formerly APG Watch4net), EMC SRM Suite, EMC SAS Suite, EMC VxRacks Neutrino, Openstack Platform, Mycom NIMS-PrOptima, HPOV TeMIP, HPOV TSM.)*

* **Rabih Majzoub** *(Rabih is a senior systems engineer working for EMC Canada for the last 5 years. He spends his time on helping EMC customers with their openstack deployment as well as troubleshooting and resolving any issues that might arise. He also helps with automating some of the deployments by writing python and bash scripts. Rabih is a active member within the EMC community and the cloud world fascinates him. He currently live in Vancouver, Canada.)*

* **Jesus Gracia** *(TBD)*

OpenStack troubleshooting: So simple even your kids can do it
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is supposed to make your life easier, right? But what happens when you provision a project environment for a developer and they come back with issues. Like . . . “My instance won’t launch,” or “My floating IP isn’t reachable,” or “Why isn’t OpenStack working?”Join us to learn more about common failure scenarios and how to resolve them quickly to get your cloud back to work. We’ll discuss the following scenarios:- All-too familiar “No hosts found”- Can’t reach the floating IP address, tracking packets along the multiple hops- How to track the lifecycle of an instance from boot to terminate- Message queue dropping messages- Database not accepting connections- Image validation- Backend volume storage issues


* **Jonathan Jozwiak** *(Jon Jozwiak is a Sr. Cloud Solutions Architect at Red Hat.  His focus is on helping customers develop innovative cloud solutions based on OpenStack and Red Hat's cloud portfolio.  Jon has spent several years consulting with OpenStack and was involved in developing the cloud practice within Red Hat's consulting organization.  Previous to that Jon's background has been working for large enterprises focused initially on Unix/Linux infrastructure, virtualization, and then cloud. )*

* **Vinny Valdez** *(Vinny Valdez is an RHCA/RHCSS who has almost 20 years of enterprise IT experience. He is a Sr. Principal Architect in the Emerging Technology Practice within Red Hat Consulting specializing on cloud infrastructure. He focuses on designing and deploying OpenStack and underlying infrastructure such as HAProxy, pacemaker, virtualization and other cloud related technologies for customers. He works with Red Hat’s partners and internal teams to architect cloud solutions and enable internal consulting and other architects to effectively design and implement these solutions. Vinny co-authored the "OpenStack Architecture Design Guide": http://docs.openstack.org/arch-design with 12 other OpenStack community members. Most importantly, he enjoys raising two geek-infused daughters who enjoy the finer things in life like Weird Al and Minecraft.)*

Designate - The "Why" and the "How"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation, Graham Hayes and Kiall Mac Innes will show the a few of the different options for deploying Designate, and how it can fit into different uses cases, including Public Cloud, and different types of public cloud setups. Graham and Kiall have both ran Designate as a public cloud service, and have produced productised versions of Designate for use in private clouds. We will highlight the benifits for end users, using tools like Heat, python bindings, Shade and Ansible and others, and how this also benifits Cloud Operators in both private and public clouds.


* **Kiall Mac Innes** *(Kiall is the PTL of the OpenStack Designate project, and Technical Lead for the HP Cloud DNS team. )*

* **Graham Hayes** *(Graham is a the PTL of Designate Graham works as part of the DNSaaS team in HP Helion. As part of this team he is responsible for operating a publicly accessible deployment of Designate, while working on new features for Designate, and developing a Designate in a box product for private cloud use. He has been working on Designate for over three years, and previously has experience in both startup and enterprise software development.)*

* **Tim Simmons** *(Tim is a Software Developer at Rackspace on the Cloud DNS team, and a member of Designate core. He has been working on Designate for over two years, and is working on developing and operating Designate at scale for Rackspace.)*

Load Balance without Load Balancer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It's almost A year and half after Kakao's revealing its network model in Vancouver summit ("SDN without SDN"). For preparing very fast growth, We made /32 bit subnet and full routing based network. VM's numbers is now heading for the 10,000 (it was not more than 1,000 at the time of last year's presentation), but we can manage very large number of VM with very small group of people due to OpenStack and Our Network Model  as well. We developed several Virtual Network Function based on our network model. One is Floating IP, The other one is programmable and scalable Load Balancer.  In Production service, people needs a way to assign Public IP or VIP through Neutron's Network node for a VM. Before Neutron's DVR is released and stablized, We also have to find a way for this network functionality. During this session we'll share about the story of developing scalable NAT and Loadbalancer without using traditional Load Balancer leveraging technology like BGP, MPLS , ECMP and Neutron.


* **yongjoon kong** *(Andrew Kong is now Cloud Computing Cell Lead at DaumKakao. Prior to joining Daumkakao, Andrew developed a lots of cloud and big data service for Korean Telecommunication companies.  Now Andrew and his team is responsible for designing and developing highly scalable, geographically distributed infrastructure and platforms to meet the unique requirement from developers. )*

OpenStack on Kubernetes - Lessons learned
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Due to its important number of components, deploying and managing OpenStack is known to be a complex and error-prone process. On the other hand, containers recently introduced consistent deployment capabilities and container management systems brought robust application lifecycle administration at scale. Therefore, we’ve decided earlier this year to bring the worlds of VMs and containers together by containerizing OpenStack services and managing them using Kubernetes. This effort enables companies to deploy a scalable and self-healing OpenStack platform in less than 5 minutes on top of Kubernetes. During this session, we will share the experience that we gained during the kubification of OpenStack, demonstrate how this work simplifies and accelerate OpenStack deployments and operations, and describe how what was initially a proof of concept is growing into a production-ready product.


* **Sergey Lukjanov** *(Sergey is the head of OpenStack Containerized Control Plane initiative at Mirantis. He is responsible for architecture and execution of CCP implementation. Previously Sergey was the Project Technical Lead of OpenStack Data Processing program ("Sahara", ex. "Savanna"). He has been involved in the project from the first days. One of his main responsibilities is architecture design and community-related work in Sahara. Also he is a top contributor and reviewer of Sahara and he oversees all Launchpad and Gerrit activity. Sergey is experienced in Big Data projects and technologies (Hadoop, HDFS, Cassandra, Twitter Storm, etc.) and enterprise-grade solutions. He implemented HA for Twitter Storm and Sergey is contributing to different open source projects now including Twitter Storm and OpenStack. Also, he's currently the OpenStack Infrastructure core/root team member.)*

* **Piotr Prokop** *(Piotr Prokop is Cloud Solution Engineer at Intel. Currently working on Stackanetes, project which aims to deliver OpenStack working on top of Kubernetes. For about a year he was working with container based orchestration systems.Piotr has an engineering degree in the specialization of sound and vision processing from Gdansk University of Technology in Poland.In his free time he loves to read books and listen to music from 70's.)*

* **Quentin Machu** *(Quentin Machu is a software engineer at CoreOS. In addition to working on Stackanetes, he is the author of Clair, an open source project for the static analysis of vulnerabilities in appc and docker containers. open source project, an analyze containers for vulnerabilities. Quentin completed an award-winning OpenStack project as part of his master's in computer engineering.)*

Keep your workload up
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the perfect world everyone runs cloud-native application in their data centers, even external customers in public clouds. However, the real world is not perfect and most of VMs are treated as Cowcats or Pets. But what if it comes to situation where you will really need to keep your workload up? In our talk we will explain two primary mechanisms offered by OpenStack, which are evacuation and live-migration. Both are here to help you deal with problems that your VMs, nodes or even a datacenter might hit. We will show you different use cases that OpenStack can handle in order to minimize possible downtime that your workload can struggle with. We will share best practices and explain the difference during a live demo.


* **Dawid Deja** *(Dawid Deja is a software engineer at Intel, focusing on OpenStack high availability and Pacemaker. For about a year he was working on resolving pet vs cattle problems by providing and testing mechanisms that would be able to automatically resurrect lost instances. Additionally he was involved in detecting noisy neighbours VMs and have general interest in distributed systems topics. Dawid has an engineering degree in IT from Gdańsk University of Technology in Poland, where he currently lives. In his free time, he transforms into board game geek, spending all evening around the table.)*

* **Pawel Koniszewski** *(Pawel is Software Engineer at Intel involved in OpenStack since Folsom release. He started his adventure with clouds developing a SLA plugin to nova-scheduler. Currently he works full-time on the upstream OpenStack activities, with primary focus on “Win the Enterprise” effort. He is a member of nova team and a member of live migration subteam. Apart from that Pawel is interested in performance optimizations. In his free time he loves to ride a bike and travel over the world.)*

Easily Deploying OpenStack CIs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

From the first CI for testing Microsoft Hyper-V support on Openstack Nova, towards more than 10 CIs on Nova, Neutron, Cinder, Manila, Open vSwitch and more! Challenges faced from deploying the first Microsoft Openstack CI to scaling to over 300 hardware nodes and over 10 projects. Uncovering tips&tricks for: deploying mixed linux-windows environments varied hardware configurations coping with hardware/software/connectivity failures maximizing hardware usage by mixing the virtual and bare-metal test nodes migrating from hybrid OpenStack-On-OpenStack on Havana to bare-metal deployments on Mitaka migrating from VLANs over a flat linuxbridge network to OVS tunneling build times optimizations for reducing the execution time to less than half of the original issues, problems and limitations encountered and how we overcame them By the end of session one will know how to easily deploy a CI, quickly customize it for the required project and requirements and how to monitor and support it.


* **Octavian Ciuhandu** *(Octavian Ciuhandu is the COO of Cloudbase Solutions, a company focused on cloud computing interoperability, based in Timisoara, Romania.Octavian is a young entrepreneur that started his own business in 2004, right after graduating a research M.Sc. in DCU, Dublin, Ireland. He has over 20 years of experience with Microsoft and Linux platforms, network management and security. Proficiency in designing applications for scalability and availability is ensured following his research masters area of expertise. Since 2012, focusing on Openstack, integrating Openstack and Windows, and especially on deploying and running Openstack CIs for Microsoft Windows. In his free time, Octavian enjoys off-road driving and skiing. Cloudbase Solutions provides integration between OpenStack and Windows, including the Hyper-V Nova Compute driver and Cloudbase-Init (Cloud-Init for Windows).)*

* **Hashir Abdi** *(Currently Leading a team of Test Engineers to maintain Linux Integration Services (LIS) drivers that were contributed in June 2009 by Microsoft to the Linux kernel under my Test Guidance . Team is geographically dispersed across the globe and works to ensure that the LIS integration is maintained across the various Linux distributions by engaging with these Linux vendors and their communities.)*

Ironic with Lenovo xClarity practice in the big datacenter
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic is the OpenStack project which provisions physical hardware as opposed to virtual machines. It's to make physical servers as easy to provision as virtual machines in cloud. Lenovo XClarity is a new centralized resource management solution that enables administrators to deploy infrastructure faster and with less effort. The Lenovo Openstack realized the Lenovo driver which integrated the Ironic and xClarity into one cloud solution to provide the hardware management and virtualization management into one portal. China Life Insurance (Group) Company constitute the largest commercial insurance group in Mainland China. The Lenovo Openstack integrated xCalrity manages the thousands of x86 servers in the cloud.


* **Jinbing Guo** *(Jinbing Guo has over 13 years of extensive in IT background with 4 years Linux programming, 4 year Linux system level testing and 5 years delivery service experience. He has rich knowledge in OpenStack architecture design, cloud solution delivery, KVM/VMware/PowerVM virtualization, Linux/AIX system administration and C/C++, bash/perl programming. Now he is working on cloud delivery for AP customers as Openstack architecture in Lenovo China. He has worked as project manager, developing lead at IBM for 7 years and has strong leadership on project delivery management, asset developing management, testing management. He submitted 50 patches for the Linux Test Project(https://github.com/linux-test-project/ltp) and KVM-Autotest Project(https://github.com/autotest/virt-test) and published 7 papater in IBM DeveloperWorks.)*

Top Considerations for Migrating Your Databases to OpenStack: Loading Data into Trove
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the challenges faced when migrating data to OpenStack is how to get it into a newly provisioned database. Many database engines have platform-specific tools for loading large amounts of data in a more efficient way than just using inserts. However these tools are often not usable in an OpenStack environment, therefore the solution to loading data into Trove is not a trivial one. This talk will cover the techniques and best practices that can be employed to solve this problem.


* **Matthew Van Dijk** *(I have spent my entire career in the database industry, working first on database engine development and more recently on database-as-a-service platforms.)*

Hiding in the Clouds: Secret Management with OpenStack Barbican
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We recently packaged OpenStack Barbican for RDO(RPM Distribution of OpenStack) and SOC(SUSE OpenStack Cloud), and created puppet manifests and chef recipes respectively to deploy it. We would like to share our experience doing this and the various problems we tackled in the process. Barbican is used by Cinder, Swift, LBaaS, Magnum and other services for various use cases which require the storage and retrieval of secrets. We will share our experiences in setting up these use cases and provide heat templates to allow others to easily replicate our results. Ultimately, attendees will get an idea of how to securely use barbican in a full-fledged OpenStack Cloud environment.


* **Sayali Lunkad** *(I started with OpenStack almost three years ago as an Outreachy intern and have been contributing to OpenStack since. I have worked on horizon previously. I have conducted various OpenStack workshops and frequently speak at events and meetups. Currently working as a developer at SUSE Linux.)*

* **Johannes Grassler** *(Johannes Grassler is an active OpenStack developer, specializing on Heat but also dabbling in other projects occasionally. He currently works as a Cloud Developer for SUSE Linux GmbH. Before that he used to work at SysEleven GmbH, where he built, operated and used an OpenStack cloud since 2014. He has been an an active member of OpenStack DACH e.V., a German OpenStack user group since its inception in 2014.)*

* **Ade Lee** *(Ade works for Red Hat, and has been involved in Dogtag development (and its integration into FreeIPA) for a number of years now. He has worked to integrate Dogtag and FreeIPA with Openstack, and is a core contributor to the Barbican project. Most recently, he has worked on puppet modules to deploy Barbican in Triple-O and RDO.)*

All the Amazing Resources You Never Knew Existed
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How many times have you thought "I wish OpenStack had.." and then later found out that it already existed? There's so many great resources and tool available from both the OpenStack Foundation as well as the broader community that can make your life way easier. Groups you can join Great informational resources including roadmaps and release details How-to and Getting started Guides Mailing lists you can join Tools for deploying, operating, and consuming OpenStack In this session, you'll need to count how many times you think "Wow, I didn't know that existed!"  


* **Tyler Britten** *(Tyler has spent the last 15 years working with cloud, virtualization, and infrastructure technologies. Prior to joining Blue Box, an IBM Company, Tyler was a Principal Technical Marketing Manager and a vSpecialist at EMC. He also worked as a technical consultant for a small infrastructure reseller, a network engineer for a Fortune 1000 company, and also freelanced as an IT consultant for small businesses.)*

Migrating a bare metal server into the OpenStack platform: it's possible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

After releasing our bare-metal offering based on OpenStack's Ironic, we had a choice to make regarding our current customers’ existing product and services. Being hell-bent on providing them with long term, viable solutions, we decided to convert as much of their infrastructure as possible to the new platform. From dedicated servers to fully Ironic-managed ones, Maxime Bélanger and Paul Millette will present a process that attendees can follow to convert servers and infrastructure, to adapt network models and to ensure compatibility between the two platforms. They will also walk through the tools developed and used through this conversion process and the challenges faced along the way.


* **Maxime Belanger** *(An experienced software developer, Maxime is relatively new to the world of Cloud Engineering Technologies. Despite that, he is quickly learning to appreciate the complexities and possibilities that they bring, especially OpenStack. His first encounter with cloud technologies was at CAE inc. where, as a software architect, he was responsible for the Continuous Integration and Continuous Delivery platform. This platform enabled CAE to quickly deliver better software on Full Flight Aircraft Simulators (FFS) for multiple airlines and CAE's training centers. At Internap, he is the Technical Lead of the Business Facing development team, responsible of automating business processes such as Cloud ordering, delivery and configuration, billing and invoicing. On a side note, as we all know, a software developer is a sedentary animal. So Maxime is religiously following a CrossFit class, so that he can continue to be a consummate foodie.)*

How to Deploy to an OpenStack Cloud and Create a Highly Effective Team Along the Way 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The real reason organizations want OpenStack is to run applications, but having an OpenStack Cloud at their disposal is just the beginning. There is configuration management, automation, containers, and wealth of other interesting technologies to choose from. What's more, organizations have old legacy apps sitting behind their firewalls that just won't go away.  In this session, I'll dive deep into best practices and the fundamental questions organizations need to answer to successfully and reliably go from code to production on an OpenStack cloud. I'll talk about the real-world deployment of Designate on Rackspace Public Cloud to manage its legacy DNS infrastructure. I'll provide some concise examples of how to make sure that both the dev team and operators have a clear conceptual model of what environments look like, how to update them, and the best practices that ensure organizations can go from a single cloud server to managing an entire cluster along side legacy infrastructure.


* **Eric Larson** *(Eric Larson is a Core on Designate project and the author of CacheControl, the recommended HTTP caching library for the popular requests library. He is also a software developer working at Rackspace on the CloudDNS team. Outside of writing code, Eric is a proud father and musician.)*

Infrastructure Updates with OpenStack on vSphere
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Infrastructure updates: We all know we need them, but we tend to dread them.This talk will be a deep-dive into how users can implement patches, with minimal downtime, on the VMware infrastructure that powers their OpenStack workloads. Topics will include: Bulk instance migrationHypervisor patch deployment


* **Trevor Roberts Jr** *(Trevor Roberts, Jr. is the Senior Technical Marketing Manager for OpenStack at VMware and the lead author of DevOps for VMware Administrators (available from VMware Press). He enjoys speaking to customers and partners about the benefits of using OpenStack with VMware technologies.   In his spare time, Trevor shares his insights on data center technologies at http://www.VMTrooper.com, via the vBrownBag Professional OpenStack and Professional VMware podcasts, and on Twitter (@VMTrooper). His contributions to the IT community have garnered recognition by his designation as a VMware vExpert, Cisco Data Center Champion, and EMC Elect.)*

Let's run Openstack Bare Metal cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running bare metal cloud on Openstack is not trivial nowadays. We're not only far from full feature parity with VMs but also need to handle more use cases specific to bare metals. In this talk we would like to present our approach to the problem of deploying bare metal cloud. We mixed Ironic Discovery with RadosGW and K8s to establish status of nodes and interconnections between them. We will walk you through the whole lifecycle - getting nodes into the datacenter, HW discovery and finally handing nodes over to customers.


* **Lukasz Leszczuk** *(Lukasz is working as a cloud solution engineer at Intel where he is working on automating internal and external labs using open source technologies.)*

* **Michal Redlarski** *(Michal is a profesional System Administrator at Intel Corp. with 10 years of experience in IT, managing server infrastructure hosted on various OS platforms (Linux, Windows, VMware). Skilled system ingegrator and problem troubleshooter. customer and quality oriented. Fresh to but very passionate about Cloud technologies.)*

Enterprise ready OpenStack upgrades with Kubernetes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Want to see a production ready OpenStack deployment and upgrade in less that 5 minutes! See how we’ve refactored the openstack-salt project to deliver containerized OpenStack services. From seamless upgrades, patching and even rollbacks, discover our take on making OpenStack operationally manageable for the enterprise. Coupling best-of-breed open source tooling with OpenStack projects to provide an experience that the enterprise has come to expect. Come prepared to be blown away by live demos.


* **Lachlan Evenson** *(Cloud Platform Team Lead at Lithium Tech. Cloud evangelist and tire kicker. Pushing cloud to it's limits in a public/private SaaS environment. Passionate about infrastructure automation, architecture and cloud deployment strategy. As a believer in open source and an active member of the community contributing to several projects. Spent the last year enabling microservices.)*

* **Jakub Pavlík** *(Jakub Pavlik is CTO and chief architect of tcp cloud (http://opentcpcloud.org). He is focused to virtual private cloud and private cloud solutions based on OpenStack and Kubernetes and vendors derivates. He is responsible for whole infrastructure solution (architecture, implementation, operation). He is member of OpenContrail Advisory Board.)*

OpenStack sizing
~~~~~~~~~~~~~~~~

**Abstract:**

At the Tokyo summit, we covered how to size OpenStack based on standard metrics and user experience. But what about retrieving accurate data from the environment? We finally have tools that provide that information, along with guidelines based on your own environment about the status, the trend, how many virtual machines can we handle, etc.


* **Victor Estival** *(Victor joined Open Source communities a long time ago, and he has been working several years on traditional Unix systems as a Consultant and as an Architect, working with IBM Power Servers and AIX for a long long time. In 2010 he changed his area to Cloud environments and he has been collaborating in the design and architecture on several Private and Public clouds working with a System Integrator, and got involved in different projects, one of them was OpenStack. Since then, he tried to integrate OpenStack with the existing technologies as well to understand how OpenStack fits in the current Customer's ecosystem as an Architect In 2014 he joined Canonical to expand the architecture of their products and add his expertise to the business, as well as complex architecture's integration experiences By the end of 2015 he left Canonical but he is still interested on OpenStack and following the community very closely)*

How to manage multiple OpenStack regions from a central point of view
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Managing multiple regions in OpenStack is one of the most difficult tasks for OpenStack administrators. Now we have ways to manage multiple OpenStack regions -- and get consolidated reports. Join us to learn how we use a Cloud Management Platform to do this. You’ll also see how a Cloud Management Platform allows us to get into hybrid environments, create services, and much more.


* **Victor Estival** *(Victor joined Open Source communities a long time ago, and he has been working several years on traditional Unix systems as a Consultant and as an Architect, working with IBM Power Servers and AIX for a long long time. In 2010 he changed his area to Cloud environments and he has been collaborating in the design and architecture on several Private and Public clouds working with a System Integrator, and got involved in different projects, one of them was OpenStack. Since then, he tried to integrate OpenStack with the existing technologies as well to understand how OpenStack fits in the current Customer's ecosystem as an Architect In 2014 he joined Canonical to expand the architecture of their products and add his expertise to the business, as well as complex architecture's integration experiences By the end of 2015 he left Canonical but he is still interested on OpenStack and following the community very closely)*

Non-distruptive OpenStack upgrade while skipping a release
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the growing adoption of OpenStack in production environments, upgrading deployments is going to be a more relevant topic for operators.We have previously shared our experience with upgrading an Openstack Cloud while skipping a release. While we still follow the same upgrade strategy,  our customers demanded zero downtime of the OpenStack workloads along with skipping a release. This lead to restructuring the upgrade process and formulating a better workflow while making it non-disruptive. This talk gives a technical overview on how we achieved a non disruptive upgrade in an OpenStack Cloud. It will walk through the complete workflow of the process along with the pre-requisites and other requirements. We provide useful hints both for OpenStack operators and future upstream development.


* **Rick Salevsky** *(I work as SUSE Cloud Engineer since February 2015 on various SUSE OpenStack Cloud product parts. I started with the system management and configuartion via Chef and focused in the last year on the automated deployment solution for our cloud product. My openSource experience is much longer. I started using Linux when I was 15 years old and joined SUSE as an apperentice in 2012.)*

* **Nanuk Krinner** *(Nanuk Krinner is an OpenStack Developer at SUSE Linux and actively working on the OpenStack product since 2012. He is active within the OSLO project and also has first hand with deploying and maintaining OpenStack in production environments. He is also an active developer of the Crowbar deployment framework. Nanuk Krinner is an experienced speaker, who has, among other occasions, spoken at the CeBIT exhibition when accepting an award that was awarded to the OpenStack project and at the OpenStack Summit 2016 in Austin.)*

Help, I've fallen and I can't get up!: Developing the ultimate help system for OpenStack operators
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack operators have to make important decisions quickly. They have a vast range of resources on how to design, deploy, and manage OpenStack at their disposal. So what do they do when the production server goes down despite their best efforts, and their jobs are on the line? That's what we wanted to find out.  The OpenStack UX and Documentation teams are developing research that aims to give an insight into real-word problem solving, so that we can develop useful, streamlined solutions for operators. The ability to identify and consume relevant information is largely dependent on OpenStack adoption and consumption.  This talk discusses the problems we are aiming to solve, the research methodologies, and the results of our efforts. It also aims to draw some castles in the sky of what the ultimate help solution might look like.


* **Lana Brindley** *(Lana Brindley has several university degrees, a few of which are even relevant to her field. She has has been playing and working with technology since she discovered the Hitchhikers' Guide to the Galaxy text adventure game in the 80's. Eventually, she worked out a way to get paid for her two passions – writing and playing with gadgetry – and has been a technical writer ever since. Right now, she’s working for Rackspace from her home in Brisbane Australia, getting her hands dirty on cloud documentation, and loving every minute of it. She is passionate about open source, cake decorating, and great docs, and is raising her very own geek girl. One day, Lana hopes to write the manual for that, too.)*

* **Danielle Mundle** *(Danielle Mundle joins the OpenStack community as a User Research Engineer. Her goal is to understand the users, workflows, and requirements of OpenStack to identify opportunities for improvements and novel solutions. As a practicing user experience consultant for the past six years, she has performed expert reviews, user-based testing, card-sorts and other user research and design activities for over 85 studies for academia, industry, healthcare, and government clients. Danielle has professional certification from the Board of Certification in Professional Ergonomics as an Associate Human Factors Professional (AHFP). She is a member of the Human Factors and Ergonomics Society (HFES), Usability Experience Professionals Association (UXPA), and the Order of the Engineer. She holds an M.S. in Industrial and Systems Engineering with a concentration in Human Factors Engineering and Ergonomics and a Certificate in Human-Computer Interaction from Virginia Tech, and a B.A. in Psychology.)*

* **Laura Clymer** *(Laura Clymer is a Senior Manager at Rackspace, with over eighteen years of experience in developing and documenting software at large, global companies. She holds a M.B.A with an Management Information Systems concentration, a PMP certification, and an MA in English education from Stanford. She has broad experience building and managing large teams with staff in multiple geographic locations. She has an ITIL foundation certification, as well as several published articles and presentations on Agile approaches for information development.    )*

Documentation Belongs in DevOps
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

At IBM Blue Box, our entire documentation process is completely integrated into the DevOps environment, using the same tools our software developers use. This best practice ensures that the most accurate information is delivered in the most efficient and timely way from engineering directly to operations and support staff, and also to our customers, thus saving everyone lots of time and energy. This is a simpler process than the OpenStack documentation process, so the learning curve is easier, but the results are excellent. It is highly suitable for a corporate team.


* **Leslie Lundquist** *(Leslie Lundquist is a technology professional with years of experience as a software programmer, system administrator, and technical writer. She currently works at IBM Blue Box, where she is Director of Technical Content Development, and works as the technical lead for Blue Box documentation with all Blue Box software development teams worldwide. She is a contributor to the OpenStack documentation. Leslie holds a B.A. degree in Philosophy from Stanford University and two Masters’ degrees. She is the author of two trade computer books, published worldwide and translated into several languages. She has worked as an advisor to the U.S. Department of Commerce and The White House.)*

From Baremetal to Production OpenStack Cloud in Hours
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You’ve heard countless times that the path to adopting OpenStack in your company will be long and complicated. Well the Operations team at the OpenStack Innovation Center (OSIC) has focused significant effort on improving the OpenStack deployment process. We’ve built a repository of code and documents which make it possible for anyone with a minimal level of proficiency to end up with a living OpenStack environment on any number of baremetal servers. These documents have been continuously improved during our weekly test cycles where novices (system admins who are new to OpenStack) start with a rack of baremetal nodes and end up with a fully functioning OpenStack installation.  Come find out how you can use what we’ve learned to get a production OpenStack cloud up and running in hours!


* **Ala Raddaoui** *(Ala is a Cloud software engineer at Intel Corporation working in the Openstack Innovation Center, TX. Ala started working on OpenStack as a researcher and a user with Bell Labs, Paris and then as a contributor with the Openstack Innovation center at Rackspace. His main interests are distributed systems, security, IOT and anything Linux.)*

* **Isaac Gonzalez** *(Isaac Gonzalez is a Cloud Engineer, Software Engineer and DevOps Specialist. He is working for Intel Corporation at the OpenStack Innovation Center based in San Antonio at Rackspace HQ. He has been working with clouds since 2014, his primary focus is OpenStack deployment and reference architecture design.)*

Instance Level QOS tiers for services provided by OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Private or Public OpenStack providers operate in a very fast-growing and internal/external competitive market, always looking for an edge – a way to offer differentiated services with exceptional efficiency with their clouds. You can increase your user stickiness and stand apart from other cloud offerings by offering guaranteed quality of service (QoS) for each service tier on storage level, despite highly unpredictable customer workloads. We'll discuss how users have kept smaller hardware footprint with the cloud hypervisor heterogeneity and propelled the growth of their cloud usage .


* **Dhiraj Sehgal** *(OpenStack Enthusiastic)*

Keep it simple: End to End Visibility for troubleshooting OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

DevOps has led to the accelerated adoption of OpenStack-based private cloud regardless of the industry vertical. As developers excel at building, testing, updating, deploying, and running, and maintaining the applications, operators are proactively looking at removing roadblocks underneath. To succeed, Operators should have end to end latency visibility for Instances supporting the several application parts in all the stages s to remove bottlenecks in the host, network or storage. Such speed and agility will accelerate DevOps adoption in the environment. In this session, we'll share actual use cases, how end to end latency visibility have helped OpenStack private cloud operators drastically reduce response time without taxing hardware, WAN or reconfiguring environment settings for each phase and has lessened the burden on them.


* **Dhiraj Sehgal** *(OpenStack Enthusiastic)*

Ironic, Heat, & TripleO Deployments:  Finding out what happened when things go wrong.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With Heat, Ironic & TripleO deployments becoming more and more the norm, being able to debug errors as they happen is critical.  An active depoloyment will be debugged, demonstrating the tools and resources available in the install process . A review of what will happen and when during the deployment and how to find out where your deployment is.   Items that you can expect to learn: Basic Debugging tools Resources availble to the Community Demonstration of TripleO, Heat and Ironic in action General progression of a typical deployment


* **Randy Perryman** *(With a background in the IT industry, designing and implementing networks, server infrastructure, and network services for data centers, specific applications and facilities. Randy brings to the Dell Big Data and Cloud Solution team his experience in creating architecture of Servers, Network, and Security. Currently, Randy is responsible for creating Reference Architectures for Dell’s OpenStack Cloud Solutions. )*

Datacenter Automation Through Continuity: A Cloud in a Box.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Datacenter infrastructures are not homogenous systems, which create unique challenges for automation of Openstack as an End-to-End (E2E) installation process on bare metal servers.  New hardware, disaster recovery, and failed upgrade processes require a quick and seamless process to deploy new or augment existing environments and code levels. Installation of Openstack on new bare metal servers is a time consuming process, which involves: hardware configuration, installation of the OSP utility hypervisor, and manual data collection and configuration prior to beginning the ironic introspection process.  Through the combined use of IPAM, OSP, and CloudForms; greater efficiencies can be gained by automating hardware, network, and flavor provisioning.  Session attendees will learn strategies to further automate the deployment of OpenStack across new and existing bare metal servers to create an extensible solution for new deployments, failed upgrades, and disaster recovery scenarios.   


* **Karl Martin** *(Karl Martin, leads a cloud infrastructure team at Verizon Wireless, which is focused on pre-production methodologies, automation, and datacenter expansion.  Karl has worked in wireless telecommunications for 9 years and in virtualization for 15 years across many industries. )*

* **Ryan Wyse** *(Ryan Wyse is a member of the North American Cloud Practice at Red Hat where he is working daily to deploy OpenStack to support NFV solutions.   His main background is in designing, developing, and administering multiplatform, clustered, software-defined, and cloud environments. Ryan previously worked as an OpenStack and HPC Administrator for the University of Minnesota's SuperComputing Institute. He also led a team of systems administrators in delivering services supporting research, cluster usage, OpenStack based solutions, and providing highly available computing resources including storage to campus.)*

Troubleshooting OpenStack Is Not Art, It’s Super Art
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A: Look, I spent two days to troubleshoot a problem on my OpenStack cloud B: What was the issue and how did you resolve it? A: Floating ip was not working randomly. I had to flush iptables after two days of investigation to resolve it. B: Are you crazy?! You need two days to flush iptables? A: Troubleshooting OpenStack is not art; it's SUPER ART. B: :DOne may have to tread many wrong paths before accurately troubleshooting an OpenStack issue. Throughout this session, we will share examples like above where we had to spend a lot of time troubleshooting simple issues. We’ll discuss what went wrong during initial troubleshooting and what drove us to tread a lot of wrong paths during the whole effort. This will help system administrators, architects, and support engineers to be cautious and effectively isolate issues while troubleshooting problems related with OpenStack deployments.


* **Sadique Puthen** *(I am passionate about building, designing and supporting Infrastructure for workloads, especially Cloud IaaS, using open source technologies, primarily concentrating on Openstack and Virtualization with good knowledge of core Red Hat Enterprise Linux, clustering, storage and networking. Experienced in designing and building Infrastructure (Network, Storage, Operating Systems, etc) for complex applications and workloads for their entire life cycle from development, test cycles, production deployment, and post production monitoring and support of the infrastructure. Area of Expertise, - Cloud IaaS implementation, design and support using Openstack.- Virtualization RHEV, VMware and etc- Skilled in Virtualization and cloud with continuous working experience starting with RHEL/CentOS + Xen/UML back in 2003, RHEL+ KVM, RHEV, VMware, HyperV and Openstack.- Designing and supporting Networking, storage and High Availability solutions.- Expert level knowledge on Linux, especially Red Hat Enterprise Linux.)*

Rolling upgrade of bare metal Cloud (Ironic)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic is now widely used to manage bare metal provisioning in data centers, but large-scale data centers have multiple ironic services (conductor/api) running in a cloud. This causes a serious problem when operators try to upgrade the cloud to the latest version: how to upgrade the cloud with minimal downtime? Because at the moment, ironic only supports a cold upgrade, whereby operators upgrade all ironic services simultaneously, which breaks the service and is time consuming. We propose a rolling upgrade solution to ironic in order to support upgrading ironic services with minimal downtime. In this solution, there is no need to take down all the ironic services and upgrade them at the same time. Operators are able to upgrade ironic services one by one with the rest of the services still available. This provides a better experience for users and operators of the cloud.


* **Lin Tan** *(Software Engineer, Intel)*

Use Zaqar for software-config metadata and signaling
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Zaqar provides a simple messaging service which allows heat and orchestrated services to efficiently communicate with each other, which make it ideal for software-config metadata distribution and signaling. This topic will talk about how the Zaqar works with Heat, what's the benift and advantage of this kind of software-config way and what is the next step to enhance it.


* **Tianhua Huang** *(Tian Hua Huang is working at Huawei. She began to contribute to OpenStack community since 2013, now she focusing on openstack heat design and bug fixing, she is core review member of openstack heat community.)*

* **wang hao** *(Wang Hao is a Software Engineer at Huawei Technologies. He is part of the OpenStack development team at Huawei. Wang Hao has continued to be active in the OpenStack community as a contributor to the Cinder, Nova project and a core reviewer in Zaqar project.)*

* **hanzhang shi** *(Expertise in Networking domain and active contributor/follower of Openstack Neutron)*

The best practices of SDN in Chinac Cloud Platform
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, I will share the best practices of SDN in our company, and talk about the SDN enablement process from Juno to Mitaca. It will includes the following topics: "How did we get start? Which kind of SDN scenario we pick up? What did we do for SDN performance? Operation experiences of SDN etc." Chinac is a big cloud computing services provider in China. We are dedicate to provide stable, security and scalable services which include Private, Public and Managed Cloud.


* **Zhikun Liu** *(Zhikun Liu is a Technical Manager at Chinac which is a big cloud computing service provider in China. He is interested in Linux, Virtulization, Baremetal Management, SDN etc.)*

The Infrastructure As Code
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Handling infrastructure as code is the vision that led to OpenStack and what we want to carry all the way through. The session has for goal to explain how TripleO is to be used to deliver your infrastructure as code.  We will describe our end vision for the project, demonstrate how it can and is already be applied today. What are the next steps and why it’s crucial for our users to start consuming OpenStack using these principles.


* **Jaromir Coufal** *(Jaromir is Sr. Product Manager for OpenStack at Red Hat. He joined Red Hat in 2012 as an Interaction Designer and developed his role within various positions to product management. Prior to this role, Jaromir was core contributor to Horizon and TripleO projects. He started gathering people around User Experience and lead the group to the foundations of becoming an oficial program under OpenStack. Jaromir is originaly from Czech Republic and is residing in Boston area, MA.)*

* **Nick Barcet** *(Nick is the Director of Product Management for OpenStack at Red Hat.  Nick joined Red Hat in June 2014, as part of the acquisition of eNovance, where he was VP of Products. Prior to that role, Nick was Ubuntu Server and Cloud Product manager at Canonical, where he participated in the definition and success of Ubuntu as a platform above and under the cloud. Nick joined the OpenStack project since its first summit in Austin and founded the Ceilometer project, now known as OpenStack Telemetry, at the Folsom summit in April 2012, to handle centralised metering on OpenStack. He has been project leading it for its first year and until it was integrated by OpenStack's technical committee. Nick was also a Director of the Board of the OpenStack Foundation in 2013. Nick has been involved in Free Software since 2000 working with Novell and Intel in various technical and management roles. Nick is a french citizen residing in the Boston area, MA and is 48 years old.)*

Operating OpenStack and Docker on a Budget
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As you can imagine, life gets busy for a tiny OpenStack team of 2 responsible for 1K+ virtual machines, and growing, and thousands of containers in a multi data-center cloud, while the recommended best practice for admin to VM ratio is closer to 1 to 250. Setting up global monitoring and administration for two multiple centers can be a challenge and a balancing act to meet the requirements for rapid prototyping in Dev/Test environments, as well as the needs for stability required for running traditional workloads like telephony and back-office apps. This session will discuss the transition from a public to a private cloud and how it enables us to do so much more by using the KISS principle, with the same resources yet without over-simplifying our setup. Here we share our best practices and our mistakes that we learned ever since deploying OpenStack Grizzly, all the way to Mitaka. Get a taste of the alphabet soup plunging headlong into the project.


* **Samir Ibradžić** *(At Midokura, I take care about internal IT infrastructure, whose main part is the 'MidoCloud', a production level MidoNet based OpenStack private cloud, split over 2 datacenter worldwide. Prior to Midokura, I worked mainly with VoIP systems, as a distributed and HA infrastructure architect. I earned a Master's Degree at Tokyo Institue of Technology in 2009.  )*

A Better Way to Cook RabbitMQ Cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying OpenStack in a large scale environment, we can regard a message queue(MQ) as a bottleneck. To reduce the message consumption per MQ cluster, OpenStack operators typically allocate a component with high communication costs on another MQ cluster separately.However, for those operators, managing multiple MQ clusters could be a nightmare. Therefore, in order to relieve the operators’ work load, we will present our evaluation result on a large OpenStack deployment with a single large RabbitMQ cluster, which is easier to manage. We tackled with the following two evaluations. First, we investigated details of messaging mechanism in OpenStack to reveal the bottleneck. Second, we conducted examination of RabbitMQ’s ha-mode, queue mirroring, and load balance to find the best practices.Then, we applied the above results to our staging environment and evaluated our RabbitMQ cluster in a large OpenStack deployment.


* **Chihiro Yokoyama** *(Chihiro Yokoyama is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*

* **Mahito Ogura** *(Mahito Ogura is a Engineer at NTT Communications, working on Cloud technology R&D team.  He joined the team in late 2014 and since has been focused on to improve OpenStack in his company's cloud, to R&D OpenStack and to educate the cloud engineer.  Mahito has experience in distributed system development.  In the past 5.5 years he has been working for NTT Comware, defining and developing IaaS, NoSQL, configuration tools, KVS as a service, DBaaS(similar to Trove) and Hadoop as a Service (similar to Sahara) . He started contributing to OpenStack from Kilo release. He is actively contributing to DevStack.)*

* **Yoshifumi Sumida** *(Yoshifumi Sumida is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*

Performance Evaluation of Swift-Hummingbird and All Flash
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As IoT and BIGdata progresses, high performance for PUT/GET small objects(n KB to n*10 KB) is needed for object storages. This presentation shows improved throughput performance of Hummingbird with NVMe, ten times as faster as that of Swift. Moreover, Hummingbird with NVMe is able to solve the performance cliff problem cased by the cache mishit due to the lack of available memory.


* **Kimihiro Yamamoto** *(A team member of NTT, and concerned with the Storage, especially, its performance.)*

Best of automation - OpenStack, ManageIQ and Ansible as an integrated solution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Like OpenStack, Ansible and ManageIQ are open source projects. Learn how Ansible and ManageIQ integrated with OpenStack provides the best solution in its class for the orchestration and automation of OpenStack clouds. From one single request, a user will be able to deploy multiple resources, like networks and instances, and automate applications and configurations to have a ready-to-use environment from both the deployment and management point of view.


* **Loic Avenel** *(Working in Software solution for last 20 years in many organisation in various area like Software Management, Harware Management, Customer Communication, Output Management. Join Red Hat in 2014 to embrace OpenSource community ManageIQ.org and Openstack.org. In Product Manager role working how to better integrate Red Hat CloudForms (downstream project of ManageIQ) with OpenStack)*

Customizing the TripleO-deployed OpenStack cloud configuration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

TripleO is a great deployment tool, but it can seem very complex initially. For most administrators, the learning curve is steep. In this session, we’ll discuss how to configure a cinder backend, enable multipath support, and set simple parameters -- like file descriptor limit in Rabbit MQ. You’ll also learn how to customize configuration of OpenStack services, such as keystone, nova, and neutron, using configuration classes and ExtraConfig.


* **Harald Jensås** *(I have more than 15 years experience in IT, specializing in delivery of Infrastructure solutions as consultant, Deployment/Implementation specialist and technical support analyst. Had the privileged to work on projects in several countries in Europe and the Middle-East, working with international teams.Technology driven person, hungering to work with cool technology. Open Source is my passion.)*

How Walmart uses OpenStack-Ansible to upgrade and deploy OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Walmart uses OpenStack-Ansible to reliably deploy and upgrade OpenStack from source at scale. This session will cover the configurability and management of an OpenStack-Ansible deployment, the benefits of deploying OpenStack services from source and into containers, and the lessons and best practices Walmart has learned along the way.


* **Jimmy McCrory** *(Jimmy McCrory is a Senior Cloud Engineer with Walmart's Global eCommerce division. He was a member of the team responsible for the deployments of Walmart's first production OpenStack clouds, and now has 3 years' experience deploying and operating large production OpenStack environments.)*

* **Michael Gugino** *(Michael Gugino works for Walmart on their Cloud Operations team at in Reston, Virginia, USA. He has knowledge and experience with Python, Ansible, Puppet, C, MySQL, RabbitMQ, NoSQL, and of course, Linux. Michael contributes regularly to OpenStack-Ansible.)*

Building a Fortress: The easiest way to get full Role-based Access Control in Openstack Keystone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Keystone doesn’t support full Role-based access control (RBAC) by itself, but there is a very easy way to fix that by using a third-party application—Apache Fortress. Apache Fortress is an access management system based on the ANSI RBAC (INCITS 359) standard. It stores rules in OpenLDAP or Active Directory and has a nice web interface for viewing and modifying permission. Apache Fortress has everything you need for RBAC: ANSI RBAC implementation. Everything is already created, described, and documented. Apache Fortress stores entities (users, roles, permissions) in OpenLDAP or Active Directory, making it perfect for enterprises who already use LDAP or Active Directory for identity management. Because of Fortress' use of standardized LDAP backends, it is easily integrated with many other enterprise applications. Apache Fortress has RESTful APIs and a web interface. Apache Fortress integration with Keystone requires only a few lines of code changes to oslo.policy.


* **Kseniya Tychkova** *(Software developer with five years experience working in IT as a software developer, web developer, deployment engineer, integration engineer, and database administrator. Joined the OpenStack community in 2015. Currently works at Mirantis in the Enterprise Readiness Engineering team. The main goal of the team is to make OpenStack suitable for the Enterprise world. Areas of interests : Keystone, SSO (SAML), Kerberos, Apache Fortress RBAC System.)*

Keystone and WebSSO: A unified login system for OpenStack and other web services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack provides the ability to use one login for all of an organization's web services, providing a way to seamlessly sign on to each system rather than using different usernames and passwords for each system. To make this possible, you can configure Openstack Keystone and Horizon for Web Single Sign-on (WebSSO) so the user can log in to the Horizon dashboard using credentials that are authenticated using a remote authentication service. This talk describes how to configure WebSSO on Windows and Linux machines.


* **Kseniya Tychkova** *(Software developer with five years experience working in IT as a software developer, web developer, deployment engineer, integration engineer, and database administrator. Joined the OpenStack community in 2015. Currently works at Mirantis in the Enterprise Readiness Engineering team. The main goal of the team is to make OpenStack suitable for the Enterprise world. Areas of interests : Keystone, SSO (SAML), Kerberos, Apache Fortress RBAC System.)*

Great Cloud Migrations: Do we need them? What options do we have?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack successfully co-exists with other cloud technologies such as AWS, VMware and Azure. Users decide to move from one cloud technology to another, from one OpenStack provider to another or even to bring a set of different cloud technologies into their DC simply because they can do it. All clouds are built to be used - in other words, to run workloads.  One of the challenges users might face is a workload migration: between two OpenStack clouds, from AWS to OpenStack or from even OpenStack to Azure (why not?). We would like to have a discussion about cloud migrations. Are they that necessary for OpenStack cloud users? If so, in which use cases? What are the different migration strategies that have proven to be effective in the field and used by real Deployment Engineers in real production clouds? What challenges do migration mechanisms present to the whole cloud industry, and how can we overcome them?  


* **Ayrat KHAYRETDINOV** *(Ayrat Khayretdinov is Openstack Deployment and Migration Engineer at CloudOps. Was part of large scale Openstack deployment AIC and migration project in ATT. Currently involved in Live Swift cluster Migration for public cloud provider Cloud.ca. In his free time Ayrat is organizing and presenting on OpenStack, Docker and Kubernetes meetups in Montreal. In the past Ayrat worked with OSS and BSS solution integration, migration and monitoring at Ericsson. Ayrat graduated with Master degree in Electrical Engineering from Concordia University, Montreal, Canada )*

* **Roman Verchikov** *(Roman Verchikov is software engineer of Mirantis, with vast experience in different software technology stacks. Last 3 years spent in improving Openstack experience for Mirantis customers with extending functionality of different openstack services, analyzing and improving performance of a large production openstack cloud, and working on load migration.  Currently he is engaged in all Mirantis migration projects and coordinates the CloudFerry tool development that facilitates resource and workload migration between OpenStack clouds.)*

* **Octavian Ciuhandu** *(Octavian Ciuhandu is the COO of Cloudbase Solutions, a company focused on cloud computing interoperability, based in Timisoara, Romania.Octavian is a young entrepreneur that started his own business in 2004, right after graduating a research M.Sc. in DCU, Dublin, Ireland. He has over 20 years of experience with Microsoft and Linux platforms, network management and security. Proficiency in designing applications for scalability and availability is ensured following his research masters area of expertise. Since 2012, focusing on Openstack, integrating Openstack and Windows, and especially on deploying and running Openstack CIs for Microsoft Windows. In his free time, Octavian enjoys off-road driving and skiing. Cloudbase Solutions provides integration between OpenStack and Windows, including the Hyper-V Nova Compute driver and Cloudbase-Init (Cloud-Init for Windows).)*

* **Hashir Abdi** *(Currently Leading a team of Test Engineers to maintain Linux Integration Services (LIS) drivers that were contributed in June 2009 by Microsoft to the Linux kernel under my Test Guidance . Team is geographically dispersed across the globe and works to ensure that the LIS integration is maintained across the various Linux distributions by engaging with these Linux vendors and their communities.)*

* **Evgeniya Shumakher** *(Evgeniya Shumakher is Senior Manager of Technology Partnerships and Alliances at Mirantis, where she coordinates and leads efforts to help Mirantis partners navigate the OpenStack ecosystem, and to expand the utility of Mirantis OpenStack to customers via integration of partner products and technologies.)*

Deployment Silver Bullets: OpenStack Dockerization Pros and Cons
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Installing and configuring OpenStack never was a simple endeavour. Is it now? Modern deployment tools often add complexity to the process and introduce even more "consultingware". Docker proliferation makes new promises in complete product lifecycle management and projects like OpenStack Kolla gain more and more popularity. Is Docker a new Silver Bullet that solves installation and configuration issues? What are new solutions and at the same time new constraints?


* **Vladislav Belogrudov** *(Started my career as researcher in Robotics, went thru various areas of telecommunications, storage, search technologies. Finally landed at Oracle to do amazing things in OpenStack project, dockerizing and orchestrating the latter, leading QA testing of Oracle OpenStack for Oracle Linux releases.)*

* **Paul Bourke** *(I am a software developer working with Oracle in Dublin, Ireland. I have been involved with OpenStack in one way or another since the Cactus release, originally working on Glance in a public cloud environment. Currently I am part of a team in Oracle that produce OpenStack for Oracle Linux based on the Kolla project, of which I am also part of the core team.)*

Datacenter Genesis: A Datamodel for Mastering Deployments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

“Your new datacenter: the final deployment.These are the steps of your favorite automation tool.It’s mission: to install bare machines, to deploy new Ceph clusters and a new OpenStack installation, to boldly establish new networks and tenants where no man has provisioned a VNF before.” In a not too distant future no datacenter operator will ponder on questions such as: “How was everything designed?” or “What is the origin of this deployment?” This is because of the universally adopted use of a standard for describing datacenter deployments. Today, however, a common datamodel is missing that is understood by different automation tools. This talk will thus: * motivate the need for a tool-agnostic datamodel that covers the various aspects of datacenter deployments * highlight the many benefits when adopting such a model * and last but not least: present an approach that builds on top of established projects.  


* **Ta’id Holmes** *(Ta’id loves to meet people, enjoys interacting with computers, and yearns for Indian cuisine. Although rumors of a relationship with Sherlock Holmes are baseless, he likes the association. As a Computer Scientist and Organic Chemist he is fascinated by synthesis, believes in the power of models, and aims for holistic solutions.)*

Cloud Benchmarking
~~~~~~~~~~~~~~~~~~

**Abstract:**

How will my OpenStack cloud perform against my other/existing infrastructure? How will it perform against the big three public clouds? And again other OpenStack options? When making the decision to get an OpenStack cloud it is important to anticipate performance, cost and value of that cloud with respect to the alternatives in the market. In this session, we will be defining a set of usable metrics to use to produce that comparision or scorecard and we will perform a few live tests with some workloads on the different types of clouds mentioned above, including obviously a set of OpenStack clouds built in different ways. If you want to know what to expect from OpenStack and how to relate it to other technologies, you should attend this session. If you want to know how a specific workload will perform in your OpenStack cloud, you should also attend this session


* **Arturo Suarez** *(I am the BootStack and Training Product Manager for Canonical. BootStack is the managed hosted (or on-prem) cloud service offered by the leading OpenStack OS company. The service includes a unique combination of long pursued features within the industry: SLA driven, optional cloud control transfer and reasonable commitment period. We manage your cloud as if it was our own, literally. After pitching OpenStack to several hundreds of companies, I do believe this unique combination constitutes the easiest way to enjoy the benefits of OpenStack without shifting a large quantity of resources from other, probably more relevant, tasks. I have been selling, talking and living OpenStack since its creation in 2010. That very same year, I co-founded an OpenStack native company that made the first OpenStack Distribution available worldwide. I am also a regular speaker in OpenStack, Hosting or Cloud events worldwide. Prior to OpenStack...there is nothing)*

* **Omar Lara** *(Omar Lara has served as consultant and promoter of FLOSS in both private and public sector in the last 15 years as an expert in Cloud Computing for the hosting industry in Latin America, he has led the largest Latin America OpenStack strategy for the most important datacenters in the region and a former CTO of the largest hosting company in Mexico, currently he serves as solutions architect for Latin America at Canonical, showing the best open source tools by the openstack market share leader in the region.)*

Test OpenStack on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This topic will talk about the possiblity of run OpenStack on OpenStack. In this way, you can try and test the OpenStack over OpenStack in most case. No more need baremetal at all. I will share the best practis to implment this. All of this is implemented by the Kolla project, which deploying the OpenStack in container. 


* **Jeffrey Zhang** *(Early OpenStack practitioners Provide private cloud solution and secondary development based on OpenStack. Planning and implementation multi private cloud plateform. Active community developer. Contribute to Keystone, Nova, Zaqar and Kolla projects.)*

Manage and deploy Heat Templates with ManageIQ
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As the core orchestration engine for OpenStack, Heat is a powerful component. However managing Heat templates can be complex and requires an effort to learn and master.  ManageIQ, the leading Open Source cloud management project,  can reduce the complexity of managing templates and help you to manage multiple Heat templates and create Services ready to deploy by a simple click.  The capabilities provided by ManageIQ  include the discovery of existing deployed Stacks, creation of dialogs to interact with user, reporting and chargeback.  Learn how to use ManageIQ to make Heat template management easier.


* **Anandeep Pannu** *(Anandeep has been involved with OpenStack since 2011 and has been at two different companies that do OpenStack distributions.  He has been a speaker at the OpenStack summit previously and has years of experience managing large scale OpenStack deployments at enterprises.   Previously Anandeep was the Program Manager for the Open Source Software Lab at Microsoft, at startups doing big data analytics before the term big data was invented and a researcher at a leading university in the US.   Anandeep has a Masters in Intelligent Systems and a Masters in Industrial Administration from Carnegie Mellon University.)*

Volkswagen Car Configurator: Running Cloud-Friendly Applications on OpenStack in the Real World
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When was the last time you saw a true cloud-native application in the wild? How about in the wilderness that is a large enterprise? Enterprises are adopting cloud technologies in the context of larger operational and organizational transformations. As they undergo these changes their architects and developers must find ways to conform to IT constraints and leverage the data assets extant in their environments during the transition. Enterprise IT cannot adopt wholesale cloud native architectures because applications must use the enormous amounts of critical data that only exists in legacy systems. In this talk we’ll use the example of Volkswagen’s Car Configurator to explore how Volkswagen has leveraged OpenStack to bridge the legacy world into the cloud, utilizing data services, continuous delivery, software defined load-balancing, and other techniques to enable agile response to business needs.


* **Craig Peters** *(Craig, a product manager at Mirantis, has spent his career making complex systems easier to consume in a variety of industries. His mission to improve the developer experience in distributed systems has developed through work on Documentum, Hadoop, and even Lotus Notes. His experience has been forged through experience at EMC, Yahoo!, Strava, and HGST. His current responsibilities include enabling PaaSes, containers, and analytic workloads on OpenStack.)*

* **Ricardo Ameixa** *(Ricardo started as a developer at a small company in Portugal, and for the past three years has been a Systems Analyst at Volkswagen AG. His work focuses on the delivery of Volkswagen country specific websites and Volkswagen web applications for users around the world. Recent activity has been on development process and operations of the Volkswagen Car Configurator and Volkswagen Dealer Search web applications.)*

Full OpenStack Lifecycle Management with Fuel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Managing an OpenStack cloud has always been complex. Even simple configuration changes on a set of nodes do not come cheap when you have to keep HA OpenStack installation up. Some teams do it with CM tools, some add home-brewed orchestration on top. This often turns into a unique suite of tightly integrated tools that becomes hard to maintain for DevOps teams. That’s what we let our users avoid with project Fuel - we provide end-to-end pipeline from the user-friendly deployment instructions to low-level state enforcement executed by a smart data driven orchestrator. New Fuel Mitaka capabilities allow for better, faster and smoother execution of complex operator-defined workflows, along with integration with external services and data sources (CMDB, LDAP, IPAM, etc.). We will show how to use these features both for day-to-day operations (change service config, install extra packages, add an OpenStack service) as well as for trickier ones (cloud upgrade, control plane recomposition).


* **Vladimir Kuklin** *(Vladimir has been working on Project Fuel since its inception in mid-2012,  responsible for the end-to-end deployment cycle, from basic provisioning of OpenStack cluster nodes, DB, AMQP and HA configuration to final configuration of all options selected by the end user as well as working on orchestration and business logic framework.)*

* **Dmitriy Novakovskiy** *(Dmitriy has been doing OpenStack clouds with Mirantis for 3 years. Transitioning from Professional Services through Solution Architecture into Product Management, Dmitriy is now busy developing new features for Mirantis OpenStack and Fuel project that make consumption of Private Cloud as joyful experience as it can reasonably be.)*

Utilizing an Infrastructure-Based Approach for Easier Deployment of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many approaches have been taken to enhance and simplify the deployment process for storage in OpenStack environments. One approach, from partners like Mirantis, is to focus on the Infrastructure layer using the Fuel framework, which provides a single UI to deploy OpenStack as well as third party infrastructure components. Come to this session to learn more about the benefits of this approach and to view a short demo of how Mirantis Fuel Plugins can provide faster time-to-market for EMC ScaleIO customers using Mirantis OpenStack!


* **Jason Sturgeon** *(Jason is the ScaleIO Product Manager with a focus to make ScaleIO the absolute best block storage option for OpenStack. Jason has 20 years of experience in Information Technology, he joined EMC in 2008 as part of the Isilon Systems start-up. He has had many different roles in his career from IT Manager, Technical Trainer, Corporate Systems Engineering, but has always had a love for the technical and helping customers use it in the best way possible.)*

* **Paul Roberts** *(Paul works at Mirantis.)*

Health-Monitoring of Large-scale Multi-site OpenStack Clusters based on Tempest and Docker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With rapid development and maturation of Openstack community, more corporations are running their core businesses on OpenStack. Operation engineers usually need to manage lots of clusters, some of which have a large scale and are heteroideous. Openstack has a lot of components, which leads to complex deployment and configurations. And the basic service monitoring cannot be able to reflect the status of a cluster comprehensively. In this situation, Qihoo360 uses Tempest to do integration testing for each cluster. We use docker and kubernetes to construct several isolated environments to host tempest. The solution is used in our dozens of clusters, which is proven to be effective.


* **Xiaohua Yuan** *(Technologist at Qihoo 360. 3 year experience in Puppet-Openstack. Xiaohua Yuan has been working on a series of innovations related with automated operation for large-scale cloud based on OpenStack. Contribution to OpenStack: puppet-nova puppet-trove puppet-cinder)*

Openstack Deployment As a Mistral Workflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack deployment procedure typically involves many tasks. Mistral's model assures a perfect fit for easy management of different tasks within an Openstack deployment workflow. In Mistral , Openstack deployment workflow can be further divided into set of tasks.These tasks can run independently or in parallel.Openstack deployment workflow can further be paused/resumed as required and the tasks can be re-run independently in case of any unseen problems.  Mistral provides a convenient way to manage and debug the tasks, as each of these tasks have their own state and error information.  


* **Hardik Parekh** *(Very much interested in cloud teachnology. He has 3 years of experience in software development. He has started working for openstack in September-2015 and actively contributing to Mistral project. Before openstack, he has worked in server/storage domain.)*

* **Anusha Ramineni** *(Cloud developer with experience in storage and virtualization domains. Anusha has been part of openstack community since Icehouse release . She is an active contributor in openstack developement and her primary contributions are in Ironic and Congress projects. She is currently Core developer in Congress project.)*

* **SONU KUMAR** *(Keen interest in Cloud and Virtualization technologies.)*

Lessons and know-hows learned at upgrading OpenStack from Icehouse to Liberty with 400 compute nodes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk shows lessons based on the case of upgrade OpenStack Icehouse to Liberty in large scale deployment by RDO.   NTT Resonant Inc., one of NTT group company, is an operator of the "goo" Japanese web portal and a leading provider of Internet services. We have been operating OpenStack as our service infrastructure since October 2014 in production with 400 compute nodes to provide more than 90 web services.   We upgraded our OpenStack from Icehouse to Liberty directly on June in 2016. Some lessons were learned from that, also good and bad know-hows were discovered during the test and the performance. We’d like to share our experience with those who concerned about the upgrading.


* **Kazuhiro Tooriyama** *(Kazuhiro Tooriyama has been working at NTT Resonant Inc. as an engineer. He mainly designs and administer operational workflows for a private cloud based on OpenStack in the company.)*

* **Tomoya Hashimoto** *(I have been working at NTT Resonant Inc. since 2001. I took a role of the design, deployment and operation for our services such as goo blog, goo QA site and so on. I'm in charge of the design, deployment and operation of the company-wide infrastructure services for most of company services.  )*

Nginx in OpenStack:  a High Availability Solution for API services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Apache is the default web server to host Openstack API services, which is running well in small-scale clusters.  When a cluster reaches hundreds of nodes and api reach hundreds of concurrent requests,  shortcomings reveals. It cannot handle so many concurrent requests from external. In Qihoo’s production environments, we use Nginx rather than Apache to host API services, such as nova-api, glance-api, cinder-api and keystone etc. Besides, there are different release versions in a single cluster(for example, we are using the Kilo release of keystone, Liberty of nova, neutron etc.). And different versions depend on different package versions.  To overcome this disgusting problem, we use docker to isolate different versions of API services in a single node. With this solution, we get much better performance than ever on our production environment.


* **Xiaohua Yuan** *(Technologist at Qihoo 360. 3 year experience in Puppet-Openstack. Xiaohua Yuan has been working on a series of innovations related with automated operation for large-scale cloud based on OpenStack. Contribution to OpenStack: puppet-nova puppet-trove puppet-cinder)*

Method for Monitoring Business Critical Baremetal servers using Monasca.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With Openstack Ironic-Baremetal neutron network provisioning in place, it became very easy to manage baremetal servers, including legacy servers like Web/Outlook/DNS/DHCP servers into cloud for tenants utilization. Though openstack successfully included baremetal servers into cloud, Cloud Admin should also be able to understand time-to-time baremetal server status, their metrics which is not currently available in openstack. This problem can be solved by monitoring various metrics of baremetal server like network utilization (Tx/Rx), CPU, Memory utilization using Monasca. Neutron ports of type baremetal contains physical switch/port information. From new Monasca plug-in we poll network metrics of physical switch using Netconf/SNMP and populate these metrics in Monasca API.This way User can understand time to time performance of the baremetal based on derived metrics.Monasca configuration will also allows users to specify which servers and metrics to be monitored by Monasca agent.


* **KRISHNA MOULI TANKALA** *(Currently working as Software Engineer at Hewlett Packard Enterprise, India. Major contributor to Neutron, Baremetal network provisioning, Lbaas, Octavia.)*

* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **selvakumar s** *(I have been working as a neutron developer from the Juno release openstack and contributed the L2 gateway from the plugin side.)*

Navigating in OpenStack: source of truth about everything
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you ever tried, for example,  to find the list of projects to be able to compare them by their role for the ecosystem? How many application catalogs or installation tools do we have? There are a lot of questions related to the entirety of the ecosystem. That’s why we started the project to create an interactive map of projects. We hope that this initiative will be the first step to create the user-friendly navigation system for current experienced Stackers and for new beings. By the way, such a tool is very important thing to attract new members to the OpenStack Community. We already mentioned this point in the article about OpenStack Day in Israel [1]. OpenStack community has an opportunity to find a right way to help everyone to navigate through that maze. And frankly speaking that’s the only chance for all of us to keep growing without losing the general high-level view of the ecosystem.


* **Evgeniya Shumakher** *(Evgeniya Shumakher is Senior Manager of Technology Partnerships and Alliances at Mirantis, where she coordinates and leads efforts to help Mirantis partners navigate the OpenStack ecosystem, and to expand the utility of Mirantis OpenStack to customers via integration of partner products and technologies.)*

* **Ilya Stechkin** *(Ilya Stetchkin is the author of "Journalists and the Internet" (2014). From 2004 to 2008, he headed the Department of internet-projects at REN TV, and from 2003 - 2004 he worked as a manager of an internet-project in the Rambler.  His current position is Marketing Content manager at Mirantis, he leads Community App Catalog Digest and works as a special correspondent for OpenStack: Unlocked. )*

Best practices for deploying & integrating OpenStack and Ceph with Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will provide a detailed overview of deploying OpenStack and Ceph with Ansible. We will go through the best practices for deploying OpenStack with openstack-ansible[1] and Ceph with ceph-ansible[2]. What we will cover:    Brief overview of Ansible, OpenStack and Ceph    How to install OpenStack with openstack-ansible and Ceph with ceph-ansible    How to integrate OpenStack with Ceph    How to enable Swift API compatible access to your Ceph with radosgw    How to manage Galera cluster failure    How to manage RabbitMQ cluster partitions    How to add/remove controller nodes    How to add/remove compute nodes    How to leverage dynamic inventory    How to destroy and rebuild service specific containers    Upgrading your OpenStack environment    How to make environment specific configurations    Provide tips and tricks for daily operations


* **Syed Armani** *(Syed is an expert in OpenStack and Ceph deployments, and one of the many organizers of meetups and community gatherings of OpenStack community in India. He frequently speaks about OpenStack at user group meetings in India and has extensive experience of deploying OpenStack in production. He has also spoken on OpenStack at CloudOpen Japan, OpenStack meetup in Israel, OpenStack Korea Day (Seoul) and in previous OpenStack Summits (Hong Kong and Paris).)*

Credential and switch management CLI’s for bringing physical switches in the cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation talks about managing the switch credentials of the physical switches as part of Baremetal Network provisioning. Currently there is no way to represent the physical switches in Neutron space. After Ironic Neutron integration, for Baremetal enrollment there is a need to keep the switch credential information to plumb the networks in the Neutron upon receiving the Ironic notifications.We have written a generic client framework that can support credential management for any vendor switch and their management protocol .All the credentials information are encrypted in the DB using Barbican Client library. Administrator can create the credentials using CLI and associate the physical switch for network provisioning. Administrator can see the physical switches in the Neutron. Later Baremetal servers can be provisioned using the Ironic.  


* **Koteswara Rao Kelam** *(Currently working as a Software Engineer at HPE India. Major contributor to neutron, baremetal network provisioning, networking-l2gw and monasca. Contributed some defect fixes in FWaaS and Ceilometer.)*

* **MANJUNATH PATIL** *(Working as a software engineer at HP India. Major code contributor to networking-l2gw. Active code contributor to openstack neutron.)*

* **Nalina Maraiah** *(Currently working in Openstack ironic project with 2.5 years of experience in networking. Previously had worked in software defined network application Hpconverged control which is l2gateway discover and management project which provides communication for NSX hosted VXLAN booted Virtual machines attached to Logical switches with vlan configured unmanaged Baremetals. This projects brings an idea of extending ironic provisioned baremetals in VLAN network communicate with VXLAN booted virtual machines hosted on openstack compute nodes. Aspire to expertise my career in Openstack and bring in lot more inventions to provide best solutions to customers and own the success.)*

Automate Physical Switch port configuration for hypervisors
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session is on automatic configuration of VLAN for the hypervisor connected switch ports on the TOR switch. Currently Cloud/Network administrator needs to configure VLANs manually for each physical switch port that belongs to hypervisor, as number of hypervisors increases, there is a need to automate the VLAN configuration programmatically so that manual intervention can be avoided. Usually hypervisor connected ports are trunk ports. We can also specify trunk port configuration using the baremetal network provisioning CLI. This project is available in Github.https://github.com/hp-networking/baremetal-network-provisioning


* **KRISHNA MOULI TANKALA** *(Currently working as Software Engineer at Hewlett Packard Enterprise, India. Major contributor to Neutron, Baremetal network provisioning, Lbaas, Octavia.)*

* **MANJUNATH PATIL** *(Working as a software engineer at HP India. Major code contributor to networking-l2gw. Active code contributor to openstack neutron.)*

* **Nalina Maraiah** *(Currently working in Openstack ironic project with 2.5 years of experience in networking. Previously had worked in software defined network application Hpconverged control which is l2gateway discover and management project which provides communication for NSX hosted VXLAN booted Virtual machines attached to Logical switches with vlan configured unmanaged Baremetals. This projects brings an idea of extending ironic provisioned baremetals in VLAN network communicate with VXLAN booted virtual machines hosted on openstack compute nodes. Aspire to expertise my career in Openstack and bring in lot more inventions to provide best solutions to customers and own the success.)*

Running an OpenStack Public Cloud with a small team
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this presentation we will talk about how ScaleUp launched a Public Cloud Service based on OpenStack. Initally a commercial stack was used but had license restrictions and lacked scalability and innovation. Since an object based storage service was needed, OpenStack Swift was deployed. The Swift installation was later merged into a new installation for Nova, which replaced the commercial cloud stack. We will talk about how we operate this "Vanilla" OpenStack cloud with a small team. Also, we will share our experience on upgrading the initlal Swift installation from Icehouse to Juno and also about our experiences (and problems) upgrading the full-stack (Nova, Neutron, Swift, ...) from Juno to Kilo and Kilo to Liberty.


* **Christoph Streit** *(Christoph is Co-Founder and Technology Evangelist at ScaleUp Technologies, a Managed Hosting Provider based in Hamburg and Berlin, Germany. He has shaped the company from the outset in various technical and commercial positions. As Technology Evangelist, he combines this knowledge in a unique way in personal customer consultations and the development of customized hosting solutions. Christoph has been a member of the OpenStack community since attending the OpenStack Summit in Santa Clara back in 2011.)*

* **Frank Gemein** *(Frank Gemein is the Chief Operations Officer at ScaleUp. Together with his team, he is responsible for the smooth operation of our four data centers. Frank has in-depth knowledge of Linux technologies for corporate use and is considered one of the pioneers of cloud computing in Germany.)*

Transforming Enterprise IT using OpenStack with Automation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is not only for cloud native workload. Recently OpenStack has been releasing fantastic capabilities for supporting traditional workload such as VM live migration and Shared File Storage. However, enterprise user is not satisfied only by these features. To operate mission critical workload on OpenStack, we need to develop more functions to keep NFR. e.g. HA cluster support / backup & restore / monitoring. And the client hopes to deploy these features with minimal labor hour. So we need to develop automation solution with OpenStack.This session will provide architecture and operation patterns for hosting traditional enterprise applications into IBM BlueBox Dedicated on SoftLayer with fully automation.This session is based on a real transformation case. LIXIL is the most comprehensive and connected global company in the housing and building industry, delivering human-centric innovation that enhances people's living spaces. GROHE and AMERICAN STANDARD are subsidiary companies.


* **Matsuo Sawahashi** *(MATSUO SAWAHASHI matsuos@jp.ibm.com 19-21, Nihonbashi Hakozaki-cho, Chuo-ku, Tokyo 103-8510 Japan TEL: 080-3150-3266 EXECUTIVE ARCHITECT IBM Japan Global Technology Services  )*

Chasing 1000 nodes scale
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Performance working group is working on identifying best OpenStack performance verification since Mitaka, and this session is about one of our researches done during Newton release cycle. This research is targeting on how  evaluating OpenStack workability and performance at large scale. In particular, we will discuss in this presentation 1000 nodes cloud emulation testing on top of two different testbeds. Scripts that have been used to perform those tests are freely available so that anyone can evaluate the performance of an OpenStack deployment either on different hardware as well as software parameters.  


* **Simonin Matthieu** *(Matthieu Simonin is permanent research engineer at INRIA. His primary task is to help research teams to build and develop various software and experimentation on large infrastructures. His topics of interest include :  distributed systems, cloud computing IT automation Data visualisation)*

* **Dina Belova** *(Dina has been working with OpenStack as a cloud platform for more than four years, both taking part in private cloud tuning and upstream contributing. Her experience includes close interaction with all OpenStack projects and their improvement to satisfy the needs of cloud users. Dina leads upstream Performance team initiative and is part of Mirantis scale/performance testing initiatives.)*

* **Aleksandr Shaposhnikov** *(Aleksandr joined the OpenStack community during the Folsom release. His main activity is helping companies adopt Openstack for development and production use cases. Aleksandr is guru of scale testing, he likes to move the limits forward by tuning and boosting the performance.)*

Openstack & Enterprise Hypervisor - A Nightmare for service providers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Installing Openstack on a greenfield seems much easier and boosts confidence over using an enterprise hypervisor like vmware/hyper-v.Since Openstack is evolving very quick and changes get in more frequently the challenges keeps piling up. There are lots of challenges in terms of selecting the right set of packages and Integrating enterprise supported version packages.We miss out on many feaures as the stable release of enterprise gets in late in market. We are trying to find a way how we can stabilize this situation and get a stable installation and working solution everytime we deploy openstack.  


* **Himanshu Dwivedi** *(Nearly 10 Years of experience in Cloud consulting and Infrastructure Design (Primarily IaaS and Paas ), PreSales, Client PoC, Virtualization (vmware/HyperV/KVM), UseCase Design and Execution , Data Center Consolidation and OpenStack Evangelism.   Founder member of OpenStack india user group and  focus has been customers, technologies and products and how do they interact with each other. Wealth of experience in datacenter technologies ranging from compute, networking to storage.  )*

* **Soumit Mishra** *(7 Years of experience in design and implemention of Automation frameworks, covering UI , CLI, REST API,  across various domains like Virtulization, NMS, Public cloud, SDN, NFV.)*

* **Vaidyanath Manogaran** *(A technically astute professional with 10+ years of experience in quality assurance, project management, solution architecting, develops & puppets, cloud computing and openstack on the cloud and storage technology)*

The Policy Engine: Managing Permissions in OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation explains how to implement proper user- and permission management in OpenStack. Clouds have certain requirements when it comes to user- and permission management: A hard separation of individual projects is necessary — and it must work reliably. In OpenStack, the built-in policy engine is responsible for defining and enforcing access levels. While things seem great at a first glance, a closer look brings a number of challenges to light. This presentation gives a basic introduction into the OpenStack permission model and how policy enforcement works for the individual services. It will elaborate on a number of issues of the current implementation and will show ways to address them. If you want to know why using the OpenStack default policy files may not be a good idea, this presentation is for you.


* **Martin Loschwitz** *(Martin Loschwitz became a member of the Open Source Community in 2000 and has been a Debian developer since 2003. He had his first contact with OpenStack in late-2011 and currently holds the position of the teamlead of the OpenStack team at SysEleven in Berlin, Germany. His primary technical focus are Software Defined Storage and Software Defined Networking solutions.)*

* **Harald Wagener** *(Harald is working in IT for almost 20 years, and his jobs covered all aspects from being a cable monkey to building infrastructure for global deployments. After working for a global IT company for more than seven years, he joined SysEleven in May 2015; as CTO he works on making sure that the company goals are supported by the right choices in processes and technology. Besides SysEleven, Harald dabbles in photography and collaborative storytelling. He grew up in Northern Germany and lives in Berlin.)*

How to quickly build a multi-hypervisor dev/test environment on a single node using virtual computes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Openstack today supports a variety of hypervisors such as KVM, ESXi, Hyperv, etc., as compute nodes. Devstack is the primary choice for developers to bring up a single node dev-test environment. A single node devstack supports only one kvm. Additional physical nodes are required to setup a multi-hypervisor environment. To address this issue, we are proposing a solution using nested hypervisors on ESXi which will instantiate multiple hypervisors on a virtual machine. We have developed an automation tool, which deploys devstack on a virtual machine, and multiple virtual hypervisors on separate virtual machines. A multi hypervisor dev-test environment can be instantiated on a single node by executing a single script. In this presentation, we will cover the following:• How to create a nested hypervisor using ESXi• How to use nested hypervisors for nova compute and neutron agents• Demo on how to run the tool and bring up a multi hypervisor environment


* **Siva Subramaniam M** *(I am working in Hewlett Packard Enterprise for the past 4 years.  Worked on products based on openstack, mainly involved in scale and performance testing using rally, functional testing.  Have worked on CI tools such as jenkins, and written various automation for the CI processes.)*

* **Balaji Ramamoorthi** *(6.5 Years of Experience with Virtaulization, Storage Currently working in Hewlett Packard Enterprise (HPE) as Helion Openstack QA  Scale & Performance Engg )*

* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*

Continuously Battle Tested OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You run into this problem with your own applications everyday. You’ve got a great CI/CD process, with robust gate tests, but you still see issues appear once code gets to production. In your own applications you are lucky, you can deploy a hotfix to remedy the issue in minutes. That doesn’t translate to your OpenStack environment does it? You aren’t set up to continuously deploy OpenStack, and you can’t afford an army of OpenStack experts to track and merge any bugs that might occur when OpenStack is put in real world, production situations. Well the Ops Team at the OpenStack Innovation Center (OSIC) is here to help. We’ve developed a multi-node reference implementation and are constantly testing it with current upstream code. That means we discover OpenStack’s production and scale bugs so that you don’t have to. We publish all the tests we perform and file and follow all the bugs we find. This means a more reliable OpenStack release for you.


* **Isaac Gonzalez** *(Isaac Gonzalez is a Cloud Engineer, Software Engineer and DevOps Specialist. He is working for Intel Corporation at the OpenStack Innovation Center based in San Antonio at Rackspace HQ. He has been working with clouds since 2014, his primary focus is OpenStack deployment and reference architecture design.)*

* **Ala Raddaoui** *(Ala is a Cloud software engineer at Intel Corporation working in the Openstack Innovation Center, TX. Ala started working on OpenStack as a researcher and a user with Bell Labs, Paris and then as a contributor with the Openstack Innovation center at Rackspace. His main interests are distributed systems, security, IOT and anything Linux.)*

* **Denise Gregg** *(Software engineering manager new to OpenStack as of 2016.  Veteran to enterprise IT with experience in technology and financial services industries spanning project management, product management, and software development team management.      )*

Public Cloud Agility with Your OpenStack Private Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enterprise IT organizations have an important strategic goal:  Ensure their private clouds are as agile as public cloud deployments without compromising, security, scale, or performance.  Faced with the demands of application development teams, which require rapid provisioning of infrastructure for test, development and production; IT organizations are wrestling with the above conflicting mandates.  One of the key drivers for the OpenStack platform is to provide an alternative to proprietary ‘lock in’ found in other cloud platforms.  Critical to broad adoption of the OpenStack platform will be HEAT, Murano, and the ability to orchestrate and automate full stack application deployments.    


* **Matthew Quill** *(I have been in the technology for over eighteen years with a significant background in storage, data protection, layer 4-7 networking.  I have been with F5 for over 5 years and have been responsible for developing the F5 Openstack partnership ecosystem for over two years. Open source for F5 is a brave new world that we are embracing with special energy. )*

Demystifying TripleO (Or How I Learned to Stop Worrying and Love the Owl)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we will explore the way in which the various OpenStack services in TripleO work together to deploy and manage an OpenStack cloud.  Topics include best practices, troubleshooting techniques, and network requirements.


* **Ian Pilcher** *(Ian is a Principal Product Manager for OpenStack and Virtualization at Red Hat.  He has been involved with open source software for more than 20 years.)*

Downstream Gate - How to set up and run pre-merge, gating CI using OpenStack CI tooling
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we'll show how to set up the OpenStack CI tooling to run tests "downstream", i.e., after code has merged upstream. Everyone is talking about CI/CD pipelines these days. But "CI/CD" means a lot of different things to different people. We'll demonstrate techniques that bring the powerful OpenStack continuous integration (CI) tooling to benefit Cloud Operators. Learn how these tools allow you to run CI to test your specific deployment with the exact code you plan to deploy to production....before the proposed changes to deployment tooling or local patches are even merged into your local code repository.  Once you are able to run CI in this manner, continuous deployment (CD) can be achieved with a much higher confidence level.


* **Dan Moravec** *(Dan has had numerous roles in Software Development projects over the course of his career, including Software Architect, Chief Programmer & Development Lead. He began his OpenStack journey about the time of the Paris Summit. In his current role as DevOps Lead, he is leading a squad that does the infrastructure and programming around a CI/CD system, utilizing an OpenStack Cloud to drive automation. Dan is actively involved with the QA and Infra OpenStack projects.)*

* **John Warren** *(John has been with IBM for over 15 years. Over that time he has been involved in several different software development projects in a variety of roles, including lead architect.  John started working on OpenStack in 2013 and has made some contributions to upstream projects, although his work has been mostly focused on continuous delivery and quality-assurance of IBM OpenStack-based solutions, including IBM Cloud Manager with OpenStack and IBM public cloud offerings.)*

* **Clint Byrum** *(Current IBM Cloud Architect, former "OpenStack on OpenStack" PTL, and OpenStack infrastructure team member; Clint Byrum is a full-time developer with a primary focus on deployment and operations of OpenStack. In addition to developing OpenStack, Clint is also an Ubuntu core developer and Debian developer, bringing years of experience working in open source and high scale operations to the table. When he's not fine tuning MySQL, building disk images, or breaking stuff in general, Clint enjoys playing hockey and experiencing the outdoors in Los Angeles with his wife, three sons, and daughter.)*

Day 2 Operations: How To Constantly Improve The Upgrade Process
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

How do you upgrade OpenStack regions of thousands of hypervisors without your users noticing? Better yet, how do you do it at regular intervals that follow community releases?Even though everybody's doing OpenStack upgrades these days, it’s still not trivial, or even easy to do. In an ideal world, you'd be able to upgrade the packages with changes to the config files or start new Docker images, apply a new database schema, and making sure everything works. Easy, right?Unfortunately, the real­life scenario is way more complex. This session will detail about how we constantly improve our Openstack upgrade process at Symantec.


* **Gabriel Capisizu** *(Gabriel Capisizu is part of the Symantec’s Cloud Platform Engineering team. He has over 10 years years of experience with large scale distributed systems, Unix and networking.  Gabriel started with OpenStack in 2011 as part of PayPal’s cloud engineering. His focus is deployment automation, security and high availability within OpenStack.)*

* **Mykyta Gubenko** *(Mykyta Gubenko is a Deployment Engineer at Mirantis working for the Services department. As an experienced system engineer, he helps Mirantis customers to be successful with Openstack. Mykyta is focused on deployment automation and large-scale openstack projects.)*

* **Alexander  Sakhnov** *(Alexander Sakhnov is a Senior Software Engineer working for the Mirantis Services department. He has been with Mirantis for more than 6 years, and joined the OpenStack community from the very beginning of the Cactus release. His main activity is helping customers with production OpenStack deployments.)*

m1.Boaty.McBoatface: The joys of flavor planning by popular vote
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As enterprise cloud usage grows, operators struggle to maintain a low-cost, monolithic infrastructure while satisfying users’ increasingly-specialized requirements and usage demands. Most cloud operators understand the value of OpenStack (Nova) flavors in mitigating this issue, but some struggle to effectively utilize this feature because:   They lack an adequate process and automation for flavor lifecycle management They look at tenant requirements in a siloed fashion and lack a big picture focus on the larger need to offer specialized, but standardized configurations On the other extreme, they make the mistake of trying to standardize too much without permitting the degree of specialization needed for different use-cases (the 'everything must be the same!' mantra) They have sub-optimal flavor geometries that do not maximize use of available resources In this session we'll look at how to design flavors to prevent these problems.


* **Craig Anderson** *(Craig Anderson (canderson@mirantis.com) works at Mirantis, Inc. as an OpenStack solutions architect, where he has lead the design of large scale, distributed, highly customized OpenStack private clouds for fortune 20 customers.)*

* **Ben Silverman** *(Currently Ben is the Principal Cloud Architect on the Open Cloud Services Team at OnX Enterprise Solutions where works with account executives, customers and sales teams to develop custom cloud solutions based on the OpenStack platform. Prior to OnX, Ben was a Senior Cloud and System Architect at Mirantis. He was responsible for creating enterprise OpenStack architectures for some of the most recognizable companies worldwide. His work can be seen at many Fortune 100 companies.  Before Mirantis, Ben was the Lead Technical Architect and Engineer for OpenStack at American Express and was directly responsible for the deployment of the largest financial services OpenStack cloud in production at the time. Today, this same cloud supports over 10,000 workloads.  Ben is currently an active technical contributor to the OpenStack community and is active in the Large Deployment and Performance and Scale groups. Ben often speaks at OpenStack conferences, meetups and special vendor events where he is an avid OpenStack evangelist. Ben has a Master's of Science degree in Information Management from Arizona State University's W.P. Carey School of Business. When he's not out proselytizing more people into the cloud lifestyle he likes to spend time with his wife and two boys in Phoenix, AZ.)*

Analyzing OpenStack Performance :  A case study from large scale OpenStack testing.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Recently, Intel and VMware conducted a study of OpenStack performance across large number of physical hosts. We deployed an OpenStack Cloud on the OpenStack Innovation Center (OSIC) and ran a few performance testing experiment. In this session we will present our findings from the study, identify key bottlenecks, provide tips on tuning the parameters and guidance on a large-scale deployment architecture. This session will be immensely beneficial to anyone who is planning to run large-scale OpenStack in production.  


* **Arvind Soni** *(Arvind leads OpenStack efforts at VMware. Arvind manages product strategy and execution for integrating OpenStack with VMware products. Arvind is also the lead PM on development of VMware’s OpenStack Distribution, VMware Integrated OpenStack.  Arvind has over 10years of technology industry experience. Arvind holds an MBA from University of Chicago, Booth School of Business. He also has Masters in Computer Sc from North Carolina State along with Bachelors in Computer Sc from IIT Bombay.)*

CI/CD testing of OpenStack releases before moving to Production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack releases cycles are very fast and staying up to date with the latest release is a very daunting task. Many companies struggle keeping their OpenStack deployments up to date due to lack of time, development environment to test, the tools or methodologies to validate your environment against the newer version. There are a number of well know projects that automate the deployments but it is difficult to set up and track the results. In this talk, you will learn how Rackspace has partnered with Red Hat leveraging their Distributed Continuous Integration (DCI) product to provide CI/CD testing of new versions of Red Hat OpenStack Platform to our customers. This allows us to replicate customer environments and testing things like upgrade through automation. It will also share those results with Red Hat to help create and track issues. In this presentation, you will learn how Rackspace is leveraging Red Hat DCI Platform to help you organize and track the results of your tests.


* **Manuel Rodriguez** *(Currently working at Rackspace as OpenStack Engineer, Previously working as a System Administrator and Network Security Adminitrator using Free Software. - Undergraduate studies from: Université Nancy 2 - Administrateur de Systèmes et Réseaux Avec du Logiciel Libre - Graduate studies from: Universitat Oberta de Catalunya - Software Libre)*

Down the RabbitMQ hole. Succeeding with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Unfortunately, Rabbitmq has a negative connotation in the OpenStack world. We think this is without merit. This presentation will give you some important tips to prevent, rather than cure, problems with OpenStack due to RabbitMQ. We will cover things like OS settings, installation, high availability, tuning and monitoring, security and encryption, performing upgrades, troubleshooting, and more importantly key things we have learned about RabbitMQ running in large deployments.


* **Gabriel Capisizu** *(Gabriel Capisizu is part of the Symantec’s Cloud Platform Engineering team. He has over 10 years years of experience with large scale distributed systems, Unix and networking.  Gabriel started with OpenStack in 2011 as part of PayPal’s cloud engineering. His focus is deployment automation, security and high availability within OpenStack.)*

Moving from traditional to cloud application - Turbo mode
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation showcases how to move a traditional application to the cloud. After highlighting the value and benefits of moving your application to the cloud, the presentation uses a real-world example to walk through the transition. Along the way, we’ll share best practises and experiences.


* **Ruchika Kharwar** *(Ruchika Kharwar am a Cloud Success Architect at Redhat. She spends her time working with customers helping them take their POCs to production by enabling integration of various features and components to given them the cloud they want. She helps them with phasing their adoption of the cloud and working across the spectrum with engineerings, sales and process. Ruchika comes with several years of embedded system development at Texas Instruments and she gradually transitioned to the server industry working on ceph storage solutions and then expanding her skills to openstack.   )*

Repeatable Deployments:  A methodology for developing a repeatable deployment infrastructure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Being able to always have the same deployment stood up quickly and easily is essential for a team.  This ability will empower your team with a minimal viable product that can be used to launch the next generation application.  In this session, you will learn what infrastructure, deployment tools, and be shown a deployment in action and how it is achieved. Randy Perryman and Steve Reichard have been developing installation practices for OpenStack, since the Bexar(2011), come hear what the lessons they learned working with different customers, tools,  and releases.  Learn what is available today and how today release is have built on what was there to achieve the ability of a repeatable deployment.


* **Randy Perryman** *(With a background in the IT industry, designing and implementing networks, server infrastructure, and network services for data centers, specific applications and facilities. Randy brings to the Dell Big Data and Cloud Solution team his experience in creating architecture of Servers, Network, and Security. Currently, Randy is responsible for creating Reference Architectures for Dell’s OpenStack Cloud Solutions. )*

* **Steven Reichard** *(Steve Reichard is a consulting software engineer and manager in Red Hat's System Engineering group. This team mission is to eliminate roadblocks to the wider adoption & ease-of-use of our product portfolio to solve ever more demanding customer/partner solutions. He has been focusing on OpenStack and enabling  Red Hat partners with thier OpenStack bsed solutions. Steve is a Red Hat Certified Engineer (RHCE) who has more than 20 years of computer industry experience. Previously, Steve worked at HP and presented at several events including HP Tech, StorageWorks, and various  customer forums.)*

OpenStack and ManageIQ: Installation, configuration, and usage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Installing ManageIQ for OpenStack is easy. But how do we utilize ManageIQ over OpenStack effectively? In this session, we will install ManageIQ on OpenStack and then look at using ManageIQ from three different perspectives: operators, infrastructure administrators, and end users. From the operator's perspective, we will show how to create service catalogs; user, project, quota, and roles management; and chargebacks based on metrics from OpenStack Ceilometer and service catalogs. We will also demonstrate a typical user's workflow, including lifecycling of resources, scaling resources up and down based on the application's requirement, using service catalogs, and viewing resource and application usage and billing. From the perspective of an infrastructure administrator, we’ll show how to do capacity planning, right sizing, and monitoring and managing resources. You will also learn to query infrastructure capabilities and view system-wide applications usage, chargeback reports, etc.


* **Kiran Thyagaraja** *(Kiran Thyagaraja comes to the world of OpenStack with over 15 years of experience with HPC. Prior to joining Red Hat, Inc. Kiran worked at Rice University as an HPC Architect. He also deployed OpenStack-based private cloud for Rice community. At Red Hat, Kiran works in the Systems Design and Engineering Group with primary focus on reference architectures.)*

A New Approach to Scheduling Database Management Tasks in Trove with Mistral
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

One of the features that has long been on the Trove roadmap was support for scheduled backups. One of the challenges with implementing this is the need for a scheduler and something to control scheduled execution. Re-inventing these components in Trove was something that no one in the community wanted to do. This session will discuss how a Trove-Mistral integration can meet these requirements as well as needs far beyond scheduling backups, features such as auto-scaling clusters or master database auto-failover. In this talk we will share how users can use Mistral to provide Trove-centric views to schedules and events. This approach provides example workflows for such functions as periodic database maintenance or reconfiguring replication sets when a site fails (i.e., failover).    


* **Morgan Jones** *(Morgan Jones is a Software Architect at Tesora. )*

The Hybrid Stack - Deploying Applications Across OpenStack, Azure, GCP, VMware and AWS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hybrid cloud deployments for the most part rely on a least common denominator approach of abstracting the infrastructure layer and forcing limited use of the underlying cloud infrastructure, especially around compute. This completely defeats the advantage that open source cloud through OpenStack inherently provides, which is exposing all of the underlying APIs to maximize the use of your infrastructure. In order to achieve true hybrid cloud, and expose many of the more advanced features of the underlying infrastructure as well as mission critical services such as database, analytics, and LBaaS, you need to build a hybrid stack with cloud portability in mind. This talk will discuss the current state of hybrid cloud and API abstraction, as well as how to deploy applications across all major clouds without having to compromise on infrastructure layer abstraction.


* **Nati Shalom** *(Nati Shalom, Founder and CTO at GigaSpaces, is a thought leader in Cloud-Computing and Big-Data Technologies. Shalom was recently recognized as a Top Cloud Computing Blogger for CIOs by The CIO Magazine and his blog listed as an excellent blog by *technical founders* by YCombinator. Shalom is the founder and also one of leaders of OpenStack-Israel group, and is a frequent presenter at industry conferences.  )*

* **Arthur Berezin** *(Arthur Berezin is an active member of the OpenStack community and a hands-on OpenStacker since the early Essex release of OpenStack in 2012. During this time Arthur has built multiple production data centers based on OpenStack, helped dozens of organizations in planning their OpenStack environments, and in executing their software defined data center strategy. Prior to OpenStack, Arthur worked on KVM virtualization management project oVirt/RHEV and open source virtualization management technologies for mission critical environments. Arthur is the Director of Product for *Cloudify* at GigaSpaces working on an open-source and open-standard cloud application orchestration platform with cloud aware applications in mind that run natively on OpenStack and other private and public clouds. Prior to Cloudify, Arthur was a Senior Technical Product Manager for OpenStack at Red Hat and Product Owner of Keystone, Heat, Horizon, RHEL OpenStack Platform Installer (Foreman/Puppet based Project Staypuft), Packstack, and OpenStack High Availability. In the past 14 years, Arthur has served in various management and technical positions in the high-tech industry, including working as a founder and technical lead of a start up, a product line lead, Linux consultant, technical pre/post sales, and as a Linux Instructor for Red Hat Certified Engineer (RHCE) exams. You can find Arthur on Twitter as @ArthurBerezin or on his blog at www.Berezins.com.)*

Overcoming Deployment Challenges: High Quality Deliveries Quickly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While it is easy to throw together a single Rack Openstack Cluster, scaling out to 20+ Racks with over 300 nodes across 74 zones in combination with Contrail networking can be a real challenge.  In this presentation, we will describe our scale-out model, collaborative approach and quality checks using several automation methodologies to deliver high-quality AT&T Integrated Cloud (AIC) zones. How to rapidly deploy cloud software across many global sites to meet customer demands with high-quality zones. How several unique automation methods and best practices were used in a large-scale deployment. Automation to update BIOS/Firmware on 300+ nodes in less than 2hrs & Bootstrap Opssimple tool which AT&T Developed to deploy non-OpenStack Environments in a zone Automation to validate all the Hardware errors, OpenStack Services using Ansible Script 3 types of quality testing (PVT, SDV and ORT) Without losing sight of stability and quality delivering high-quality zones in a large telco


* **Uttam Dravidam** *(Uttam Dravidam works as Sr.Technical Director at AT&T, his team is responsible for delivering AT&T Integrated Cloud(AIC) across AT&T. AIC is a unified cloud platform for both internal and external AT&T (services).  AIC leverages open source OpenStack components along with multiple hypervisors, middleware and OS environments in a variety of physical locations to provide enterprise grade cloud services.  Uttam got several years of experience in Openstack Architecture, Operations with very strong System Administrator background.  Uttam has presented several topics on cloud within AT&T and as well External presentations. His Recent presentation was in 29th IEEE conference.  Before joining AT&T, Uttam worked at Telcordia Technologies, as Linux System administration. Uttam holds a MS in Engineering with a major in Mechanical Engineering from Florida International University, 1999 and BS in Production Engineering from Osmania University, 1997.)*

* **Marcellus Duke** *(Marcellus Duke, Director-Technology Operations: Technology Planning & Engineering Marcellus Duke has provided leadership for System Deployment which consists of server build and configuration across the various operating system platforms (AIX, HPUX, Solaris, Windows and Linux). The deployment function also includes the quality or verification testing to move servers from install state to production status. He currently leads the Infrastructure Instantiation organization delivering servers for AT&T cloud software deploy and bare metal server solutions along with go-live verification testing.    Marcellus joined AT&T in 1985 as an applications developer in the information technology organization. He has a broad range of IT operational and management experience in applications development, quality & process improvement, customer service, LAN/WAN operations, desktop support and data center operations.  He was instrumental in developing and implementing real-time and historical LAN/WAN utilization capability resulting in significant service and cost improvements.  He additionally led the design, implementation and operations of the nation’s largest windows based thin-client server farm in support of SBC Wireless in 1998.  Marcellus also led an effort to automate and implement management practices and tools in the office print output space resulting in secured print capability, enriched multi-print functionality and multi-million dollar annualized savings.  He managed all IT supported windows based server operations for AT&T delivering secure infrastructure access, Citrix server farm access, virtualization using VMware, email and messaging services and software distribution using Microsoft System Center (SCCM).  In his 30 plus years of service at AT&T, Marcellus has experienced tremendous change in the telecommunications industry and contributed to the successful integration of several huge mergers including SNET, Pacific Telesis, Ameritech, AT&T, Cingular, Bell South and Direct TV.   Before joining AT&T, Marcellus worked at the Tulsa Public Schools Education Service Center in the Information Systems department as a computer programmer for 2 years. Marcellus holds a BS in Business Administration with a major in Management Science and Computer Systems from Oklahoma State University, 1982.)*

How to troubleshoot a highly available OpenStack Cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It can easily become very complex to efficiently troubleshoot a highly available OpenStack cluster. OpenStack components, such as messaging services, load-balancers, and databases, need to be configured properly and tuned for optimum performance. Post-deployment, issues which arise need to be efficiently identified and resolved. Future deployments should benefit from lessons learned during troubleshooting. Throughout this session, we will discuss some of the more common issues which administrators encounter in their high availability deployments, how we learned to troubleshoot them, what the root cause was, and how we arrived at the right solution. Some of these problems are related with scaling load balancers that sit in front of API services, scaling rabbitmq message bus, issues related to MariaDB + Galera, and pacemaker fencing.


* **Andreas Karis** *(I am passionate about all things related to networking, to Linux and to the cloud. Currently, I am  specializing in all aspects of OpenStack and particularly Neutron.)*

* **Jack Waterworth** *(I work with Linux and I do what I love.  I have experience in High Availability cluster including OpenAIS, Corosync, and Pacemaker. Ive spent a lot of time supporting all aspects of Storage, including configuration and troubleshooting on host, fabric, and backend against arrays from NetApp, EMC and many others. I am currently specializing in all aspects of OpenStack and Ceph Cloud Storage. I specifically provide OpenStack support for all components of the stack, including Horizon, Neutron, Cinder, Glance, Nova as well as the supporting software such as MariaDB/MySQL with Galera, MongoDB, HAProxy, RabbitMQ and Pacemaker.  Due to the nature of the cloud, a lot of support includes collaborating closely with the OpenStack development engineers.)*

Deploying Watson IoT  on OpenStack: An Enterprise Use Case
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will describe how Watson IoT with Blue Box OpenStack and Bluemix makes the Internet of Things a reality for enterprises, drawing upon examples from an enterprise deployment. When the Watson IoT team was asked to deploy to China it needed to choose a new cloud infrastructure to host the offering and implement a new deployment process to perform the deployment. We will explain why we chose Blue Box OpenStack as the cloud environment and Ansible as the configuration management technology. We will describe how the two technologies complement each other, resulting in a dramatic reduction in deployment time. We will also describe how we used Security Groups and Security Group Rules to control access to the instances in the environment and how we used the Load Balancer as a Service component to distribute both HTTP and MQTT traffic across within the offering. Finally, we summarise the advantages of using OpenStack to host the Watson IoT solution over other cloud environments.


* **Madhulima Pandey** *(Lima Pandey is Program Director for Product Management in IBM's Blue Box Cloud group. Previously, she led Product Management at Nebula for Nebula Cosmos OS for building enterprise private and hybrid cloud. Prior to that, she led Product Management at Sentilla (acquired by Ericsson), that developed real-time analytics for IT infrastructure optimization. She has also led Product Management at Yahoo in Cloud Services group and at EMC in Backup and Recovery (Data Domain) group. She had co-founded and led CloudTrust, a company for website acceleration and security. She began her career as a software engineer and she spent several years at engineering leadership roles at Sun Microsystems. She holds a BS and MS in Electrical and Computer Engineering and MBA from Wharton, University of Pennsylvania.  )*

* **Martin Smithson** *(Martin Smithson is an Architect working on the Watson IoT Platform at the IBM Software Lab in Hursley England. He is primarily responsible for designing the process that is used to deploy the offering to OpenStack environments. He has 20 years of experience working in the IT industry, including both software architecture, software development and technical consultancy roles. His areas of expertise include the architecture, design and development of JEE applications; he is also an expert on IBM WebSphere Application Server. He has authored several developerWorks articles and co-authored several Redbooks: WebSphere Application Server V6 System Management and Configuration Handbook , WebSphere Application Server V6.1: System Management and Configuration, WebSphere Service Registry and Repository Handbook, and CCF Connectors and Database Connections Using WebSphere Advanced Edition -- Connecting Enterprise Information Systems to the Web. Martin also developed the IBM Client Application Tool for JMS.)*

DevOps on Cisco Metapod OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

TCS & Cisco Metapod team shall share key learnings & advantages of DevOps on Metapod as part of this session. Cisco Metapod is an OpenStack based cloud that is integrated with TCS’s DevOps framework. TCS has on-boarded several open source tools for requirements management, source code configuration management, build, test and deployment and monitoring. All these tools are pre-integrated to give a seamless Continuous integration, delivery and deployment environment and the framework uses OpenStack API to instantiate virtual sand boxes for build, test and deployment. The framework leverages OpenStack HEAT templates, Nova, Cinder and Ceilometer API to provide the cloud customers the possibility of automated CI/CD environment. The framework is fully containerized using Docker. The framework is flexible to work on KVM based virtual machine environment and is future ready with support for Docker container based virtualization


* **Srinivas Tadepalli** *(Srinivas is the Solution Architect in Technology Business Unit’ NextGen initiatives to identify new offerings and use cases to drive adoption of NFV & DevOps. His focus is on developing and demonstrating NFV solution enablers and opensource contributions in OpenStack & OPNFV. He is a core contributor to tosca-parser and heat-translator openstack projects.)*

* **Chris Riviere** *(Chris Riviere is a Cloud Solutions Architect on the Cisco Metapod team. He joined Cisco via its acquisition of Piston Cloud Computing. Previous to Piston, Chris had Professional Services and Sales Engineering roles at OPNET Technologies (acquired by Riverbed). There he was passionate about application and network performance helping customers around the world optimize the reliability and performance of their mission critical applications. He enjoys traveling, hiking, biking, and scuba diving.)*

* **Prateek Tripathi** *(Cloud architect and automation expert with 13 years experience . Have worked with multiple clients on providing automation solution on Clouds (AWS,Rackspace,Openstack,etc) and containers. )*

Tips and tricks to making your instances highly maintainable and available
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Instance migration is a requirement for any highly available OpenStack deployment and can help to significantly reduce downtime for a cloud’s customers. Migration is important for several reasons: During maintenance work, instances need to be moved to different hypervisors. Resource constraints may make it necessary to move virtual machines to specific hardware. Automated solutions are needed to recover instances in case bare metal machines fail without warning. This presentation will explain the differences between the different forms of migration and evacuation. Administrators will learn how to avoid common pitfalls by applying good practices from the start. Troubleshooting migration has its own challenges. Through different use cases, attendees will learn how to identify and fix typical problems which occur before or after failed migrations, such as resource constraints and database problems.


* **Andreas Karis** *(I am passionate about all things related to networking, to Linux and to the cloud. Currently, I am  specializing in all aspects of OpenStack and particularly Neutron.)*

* **Jack Waterworth** *(I work with Linux and I do what I love.  I have experience in High Availability cluster including OpenAIS, Corosync, and Pacemaker. Ive spent a lot of time supporting all aspects of Storage, including configuration and troubleshooting on host, fabric, and backend against arrays from NetApp, EMC and many others. I am currently specializing in all aspects of OpenStack and Ceph Cloud Storage. I specifically provide OpenStack support for all components of the stack, including Horizon, Neutron, Cinder, Glance, Nova as well as the supporting software such as MariaDB/MySQL with Galera, MongoDB, HAProxy, RabbitMQ and Pacemaker.  Due to the nature of the cloud, a lot of support includes collaborating closely with the OpenStack development engineers.)*

OpenStack and Distributed Virtual Routing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the introduction of Distributed Virtual Routers, administrators now have the ability to implement highly available networking environments without having to rely on separate network nodes or controllers. In addition to the High Availability (HA) benefits, distributed virtual routers relieve other OpenStack projects such as OpenStack Trove and OpenStack Sahara from experiencing network bottlenecks that affect Hadoop workloads and Database services . In this session, we will review and provide attendees an analysis of network data captured while running Hadoop and database workloads with Distributed Virtual Routers.  Attendees will also learn best practices, design considerations, and potential use cases for running Distributed Virtual Routing in their OpenStack environments.


* **Taylor Biggs** *(Mr. Biggs is a Cloud Consultant who also possesses strong Platform and Leadership skills. He usesthese abilities to engage customers, solve strategic technical, procedural, and policy-based challengesutilizing open-source technologies, practices, process improvements, and principles. Mr. Biggs hasworked as a Consultant, a System Administrator, System Owner, and Technical Lead on many projects,including a few utilizing hundreds of RHEL platforms, on which Satellite, Puppet, OpenShift, OpenStack,KVM, RHEV, Xen, Nagios, Ganglia, WareWulf/Perceus, MPI, RHDS, ArcSight, SourceFire, Splunk,Tripwire, and dozens of other proprietary and open-source software components/suites were installed.He uses his extensive and broad background to successfully deliver high-quality projects and procedureson-time and in excess of client expectations.)*

* **Yonathan Goitom** *(I am currently a Senior OpenStack Consultant with Red Hat and have been so for the past two years. As a consultant I provide assistance to customer looking to adopt new technologies like OpenStack, CEPH and containers. Prior to joining Red Hat, I was fortunate enough to provide support to NASA’s first IaaS offering, Nebula, located out of the Goddard Space Flight Center  in Greenbelt,MD. Over the past several years I’ve worked customers ranging from federal agencies to prestigious academic institutions.   I currently hold a Masters Degree in Information Assurance and currently enrolled in Capitol Technology University's PhD program. During my free time I enjoy weight lifting, bowling and researching emerging technology trends. )*

Who are you? Leveraging OpenStack Identity to enable Federation, Policy and Custom Features
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

You've heard of OpenStack features like Keystone Federation, Policy and Middleware, but how can you leverage these features in your own environments? IBM Blue Box has a long history of enabling and operationalizing OpenStack features, and have made use of these constructs to deliver reliable, compliant IaaS solutions for our customers. In this session we will remove the theory behind these OpenStack constructs and demonstrate, in a real, practical manner, how you can leverage these OpenStack Identity components to enforce corporate security policies as well as enable new features. Attendees will walk away with a first-hand accounts of how to shape OpenStack into the cloud your customers demand. Specifically, we will dive deep into how Keystone Federation is implemented and operationalized, how service policies cant be hammered into shape, and how you can easily impement your own custom middleware to enable new features and further extend your custom OpenStack offering.  


* **Craig Tracey** *(With over fifteen years of experience building scalable, automated infrastructure solutions, Craig serves Lead Architect for IBM Blue Box. In his role, Craig leads a team responsible the development of OpenStack-based on and off-prem private cloud solutions.  His focus includes everything from operations, support, and new feature development for all production OpenStack environments. Prior to Blue Box, Craig was the Cloud Automation Technical Lead at HubSpot where he designed software solutions for delivering SaaS products on top of a variety of public cloud offerings as well as home-grown private OpenStack implementations. Prior to HubSpot he helped engineer Carbonite's backup solution to over 60 petabytes and at VMware maintained network device drivers for both ESX and vSphere. Craig is an active contributor to a number of cloud ecosystem projects including OpenStack, Neutron, Nova, Giftwrap, cloud-init, Ursula and Chef for OpenStack. He holds a Bachelor of Science degree in Computer Science from Providence College and is based out of Boston, Massachusetts.)*

Workshop on Openstack Designate and Possible Customizations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Currently Openstack designate can be customized to perform in varrying conditions.  Few of the conditions that we have resolved at AT&T with DNSaaS are: Backend Plugin for nsupdates rather than following rndc Designate Sink operating on Tenant based domains Configuring LBaaS to work with Designate We will dwell into possible solutions that can be worked out with base openstack designate.


* **Ram Sateesh Talari** *(Works with AT&T as Development Lead for AIC DNSaaS and GSLBaaS Teams.  Is currently working on creating and implementing blueprints with openstack designate.  Previously worked with AIC DBaaS and was Developer for the AT&T CaaS platform.)*

Openstack and Infrastructure High Availability for a Production deployment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most of the production installations do need High Availability on both openstack side and Infrastructure side. Most of the implementations are done today considering openstack 'is highly available' and will take care of it.This may not be always true. A failure can happen on VM, Server, disk, network, switches anywhere apart from any glitches/bugs with openstack services. A case study of deploying a production openstack with HA and study done by faults injected at component and infra level will be shown.A topology of multiple Cisco UCS Fabrics and domains along with switches in the infra along with multiple controllers, hypervisors and ceph nodes spread across these domains and achieving HA will be revealed.


* **Rama Nishtala ** *(RamaKrishna Nishtala has around 20 yrs of experience in IT infrastructure, Virtualization, and Cloud computing. In his current role as technical leader, in Cisco Systems, he works on best practices, optimziation and performance tuning on Open stack and Storage solutions.)*

SDN Topology Orchestration with PLUMgrid and Python
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A look at orchestrating complex virtual network topologies with PLUMgrid and Python.  By utilizing a terse network topology description and Object Oriented Design, Swisscom has developed a simple means of standing up arbitrarily complex topologies.  A look at the description language and design patterns used, followed by a demo.


* **Douglas Copas** *(Swisscom Elastic Cloud Engineer, SDN lead.  Software developer, technology enthusiast, aspiring writer.)*

Cisco: Kraken CI platform - how to strain your code and sleep well at night
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Continuous Integration is the often glossed over link between Operations and Developers. It's simple, but complicated. It's beautiful (when done "right"), but ugly (when done "wrong"). Ultimately, it's the core power behind agile itself.  We plan to bring to light a CI reference model at an enterprise scale, not only delivering Openstack, Containers, ACI, and Bare Metal, but stability, velocity, and a happier more balanced life =). 


* **Alex Altman** *(https://www.linkedin.com/in/alex-altman-09942265   CI Architect at Cisco Systems.    Previously, founded two companies. Worked at Netapp for ~10 years. And briefly worked for a heavy engineering (think military technology) provider.    I'm interested in having business impact across organizations by understanding end to end software development and delivery, including the human system and organization thereof.       )*

Troubleshooting Openstack with Pacemaker High Availability Cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Troubleshooting Openstack issues related to, or possibly caused by Pacemaker High Availability Cluster : Learn how to differentiate between a resource issue (resources being components of Openstack) and a Pacemaker cluster issue (issues resulting directly from the Pacemaker daemon stack, either configuration of the cluster, stability of the underlying servers, and normal cluster behavior impacting your environment. Addtionally, we'll cover some basic troubleshooting techniques available in Pacemaker cluster, and general statuses of resources to help you understand what each status means to pacemaker, what steps can be taken in pacemaker to recover from a failure, and how to achieve basic pacemaker stability. We will cover the concepts of quorum, clone resources, resource constraints, and why STONITH fencing is a requirement for the environment.


Datacenter Deployments of OpenStack from ToR Switches
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With current networking technologies, many top of rack switches are not being used for their full potential. Most are installed, plugged in to their uplinks and various servers and storage, and forgotten about. What if you could deploy OpenStack to an entire rack of servers that the switch is connected to? What if you could deploy the rack next to it from a single switch? What if you were able to deploy an entire Datacenter from a top of Rack Switch for a scalable OpenStack deployment? With Ubuntu, Juju, and MAAS, this is possible to do from a top of rack switch. This presentation will go over the configuration of installing Ubuntu, MAAS, and Juju on a top of rack switch, and then, using that switch, deploying OpenStack on to a rack of servers, and even having it provision another top of rack switch to show that this process can be managed for future buildout across an entire data center.


* **Lucas Williams** *(With over 22 years experience in the IT field,  there is not a whole lot Lucas hasn't seen. However, with the trends in technology, he is constantly learning and trying new technologies to keep up with markets and company demands for new technologies to meet their needs. He currently is a Technical Partner Manager for Canonical specializing in Snappy Ubuntu Core and Whitebox switches.)*

Let’s Make Live Migrations Great Again
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Live migrations are critical to the life cycle management of OpenStack clouds and workloads running on them. The general problem is getting a predictable process that minimizes failure, the overloading of hosts, and workload downtime. Several features were introduced in Mitaka and Newton, wuch as live migration force complete, and post copy. In previous releases, there were few techniques available to ensure that the migration process finishes successfully, so all of these features are important for cloud admins to understand.   In this session, we will share our benchmark results, including different scenarios aimed to determine patterns of workload activity that affect performance of live migration as well as the reasons for those effects.


* **Timofey Durakov** *(Timofey Durakov has worked on the Openstack Nova project over the past 2 years. Prior to Openstack, Timofey was engaged in developing banking systems written in Java.)*

* **Volodymyr Nykytiuk** *(Volodymyr Nykytiuk leads the Enterprise readiness engineering team in Mirantis, and has experience in building and integrating large enterprise systems. Currently, he is focused on making OpenStack services more enterprise friendly.)*

Malware Analysis Environments using OpenShift and CloudForms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Malicious software, or malware analysis environments present additional complexity and challenges since they need to guarantee isolation, allow for quick rebuilds and customizations, and mimic production environments as closely as possible.  In this session, we will explore a solution to the quick construction and purging of template-driven Malware networks with CloudForms and OpenStack.  A malware analyst would then be able to quickly create a production-like environment in which to experiment and execute malicious software, and as easily safely sanitize and destroy the environment once the analysis is completed.


* **Taylor Biggs** *(Mr. Biggs is a Cloud Consultant who also possesses strong Platform and Leadership skills. He usesthese abilities to engage customers, solve strategic technical, procedural, and policy-based challengesutilizing open-source technologies, practices, process improvements, and principles. Mr. Biggs hasworked as a Consultant, a System Administrator, System Owner, and Technical Lead on many projects,including a few utilizing hundreds of RHEL platforms, on which Satellite, Puppet, OpenShift, OpenStack,KVM, RHEV, Xen, Nagios, Ganglia, WareWulf/Perceus, MPI, RHDS, ArcSight, SourceFire, Splunk,Tripwire, and dozens of other proprietary and open-source software components/suites were installed.He uses his extensive and broad background to successfully deliver high-quality projects and procedureson-time and in excess of client expectations.)*

* **Yonathan Goitom** *(I am currently a Senior OpenStack Consultant with Red Hat and have been so for the past two years. As a consultant I provide assistance to customer looking to adopt new technologies like OpenStack, CEPH and containers. Prior to joining Red Hat, I was fortunate enough to provide support to NASA’s first IaaS offering, Nebula, located out of the Goddard Space Flight Center  in Greenbelt,MD. Over the past several years I’ve worked customers ranging from federal agencies to prestigious academic institutions.   I currently hold a Masters Degree in Information Assurance and currently enrolled in Capitol Technology University's PhD program. During my free time I enjoy weight lifting, bowling and researching emerging technology trends. )*

How to be an OpenStack Operator and still sleep
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack clouds scale larger and larger, a knowledge (and expectation) gap is opening between people tasked with architecting and implementing the cloud, and those whose job is to operate it day to day. In such situations, innocent actions may produce unintended consequences. Ops engineers and teams may experience sleepless nights (and stressful days) as a result — forced to do forensics on unfamiliar cloud architecture and configurations, while under heavy pressure from the business to keep end users happy, and comply with SLAs. This session aims to close the knowledge gap and head off stress by sharing best practices and lessons learned in the trenches of OpenStack production ops. We'll discuss some of the technical flora and fauna you may encounter, propose methods for informing yourself about OpenStack clouds you didn't engineer, and discuss oft-overlooked configuration and service tunings that can improve stability, and help you get a good night's sleep.


* **Raul Flores** *(Raul has been involved with supporting a variety of OpenStack clouds, both public and private, since the Essex release.  He began working with OpenStack as part of the HP Public Cloud team and is currently an OpenStack Operations Engineer at Mirantis where his focus is assisting customers maintain and operate their clouds.)*

Culture Diversity: Importance of Technical Translations in the Growth of the Platform Abroad.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the diversity of skills needed on Openstack, translation plays a key role in the extension of the platform abroad. In this presentation, Openstack developers: Talk about their journey as developers and translators Demonstrate how a push by the community to improve translation efforts for documentations, localization of UI, error messaging and logging... can further promote the adoption of Openstack worldwide and increase community participation and collaboration. Take a look at the current state of the documentation and translations, show their importance on the platform, and propose new ideas to engage developers to be more active.


* **Alexis Rivera De La Torre** *(Bachelor's Computer Science. Worked for a small startup (CrowdSource - now OneSpace) doing QA and Web Development. Started with AT&T in June 2015 and have been working both community work (mainly the Barbican and Horizon projects) and developing an internal cloud application to bring together monitoring, logging, metering, and other cross cloud metrics into a single dashboard.)*

Growing pains - network, storage, and control plane woes. Lessons learned.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While Openstack has matured significantly over the years there are still scaling challenges with "out of the box" configurations. This talk will highlight some of the challenges encountered, solutions reviewed, and lessons learned. We'll take a look at Neutron, Rabbit, Cinder and other services that have failed to perform at scale. We'll also look at solutions; some simple some not so simple. Ultimately the user should walk away with a better idea of what to expect from certain services in large configurations. 


* **Wade Lewis** *(Wade Lewis is an Openstack Dedicated Architect for Rackspace Private Cloud. He's been a Racker for 12 years and has been involved with large scale Openstack clouds since Folsom. His current projects involve working with financial and media institutions that are migrating legacy workloads to the cloud. )*

Two years of running a SaaS on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running a SaaS is not easy. It presents endless challenges. We have faced them over 2 years of developing, deploying and running our own multitenant SaaS for realtime data processing. We have learned a lot and we want to share some of the challenges we faced and how we solved them. This includes managin 100s of users, storing TBs of data, building our own custom deployer and creating a custom CI/CD pipeline.


* **Marc Solanas Tarre** *(Big data on Cloud Computing researcher at Cisco.)*

* **Xinyuan Huang** *(Xinyuan is a software engineer at Cisco conducting research and development in machine data analytics, data platform and applications, and data driven optimizations, etc. He is also an developer and researcher in Openstack scheduler and smart solutions for cloud resource optimizations. He has practical knowledge in Machine Learning, Intelligent Control/Optimization Systems, and Signal Processing. http://www.linkedin.com/in/huangxinyuan  )*

* **Johnu George** *(Johnu is a software engineer in the Office of the Cloud CTO at Cisco. He is primarily involved in building scalable distributed systems. He is currently working on real time streaming data processing and analytics. He holds a MS in computer science from Texas A&M university,College Station.)*

Failed OpenStack Update?! Now What?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With each OpenStack version release, new components, services, and feature sets are included to improve overall functionality. However, with the advantage of those new features comes the very real possibility of having an OpenStack failed update. Prior to attempting an update,  you are likely to ask yourself: What do I need to back up prior to the update? How do I backup my databases? How do I restore my databases? If I need to rollback all of the services, which do I start first? To answer these questions you need a comprehensive strategy to backup and restore from a failure.  This session dives into best practices on how to properly backup and restore an OpenStack environment from a failed update and will provide attendees the answers to the critical questions: What do I need to back up for the overcloud nodes and undercloud node? What is the restore process for the overcloud nodes and undercloud node?


* **Roger Lopez** *(Roger Lopez is a principal software engineer in Red Hat’s Solutions Engineering group. This team identifies high-value solution stacks based on input from Sales, Marketing, and Engineering teams and develops reference architectures for internal and external customers. Roger is a Red Hat Certified Engineer (RHCE) with more than 9 years of computer industry experience at Dell and Red Hat. I've presented at conference such as Red Hat Summit, Collaborate, Oracle World over the course of those nine years. I've currently been working on OpenStack for almost two years with my focus around Performance and Scalability, and Backup and Recovery. Below are some blogs and reference architectures around OpenStack that I've written: http://redhatstackblog.redhat.com/2015/08/17/performance-and-scaling-your-red-hat-enterprise-linux-openstack-platform-cloud/ https://access.redhat.com/node/1507893/40 https://access.redhat.com/articles/2165131  )*

Challenges and Solutions of customizing Horizon for Enterprise Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

NTT Communications has been providing Enterprise Cloud 2.0 (ECL2.0) as public cloud service since March/01 2016, which is currently available across 5 regions by July 2016 and planned to expand up to 14 regions in the near future. ECL2.0 is developed based on OpenStack and consists of a variety of independent micro-services with well-defined APIs. Our team is responsible for developing the customer portal by customizing Horizon and supplementing applications for non-compatible services. In addition to the web-based GUI system, recently there have been increasing requirements of advanced interfaces for high-level resource orchestration and performance analysis in the company, which also leads to the needs of CLI/SDK for batch access and management of service APIs. This presentation describes the design and architecture of the across region GUI portal, as well as CLI/SDK and other information publishing components in ECL2.0.


* **Xinni Ge** *(I am a software engineer in NTT Communications, a company providing OpenStack-based public cloud services called Enterprise Cloud 2.0 since March 2016. Our team is now responsible for the development and deployment of the customer portal system of ECL2.0 by customizing Horizon project.)*

How to calculate the transition between two states of your OpenStack cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The shortest path between two points is not always a straight line, and the transition between two states of your OpenStack cluster can be more complicated than just a set of sequential changes. That's when you need to move from configuration management to orchestration. We faced this same question when solving the Lifecycle Management problem in Fuel: how do we calculate the optimal way to make these transitions? Fuel Mitaka uses the context of current and expected states of a cluster and calculates the transition graph based on introduced changes. We use YAQL (Yet Another Query Language), developed by the Murano community, to make the process of calculation fully data driven. It means that each granular part of the transition graph watches its own context changes and makes a separate decision about whether to be skipped or to be executed.


* **Alexey Shtokolov** *(Since 2015 - Fuel Developer and Development Lead at Mirantis 2010 - 2015 - CIO/CTO at Sistema Mass-Media 2004 - 2010 - Physicist and Software Developer at Moscow State University and University of Washington State)*

* **Vladimir Kuklin** *(Vladimir has been working on Project Fuel since its inception in mid-2012,  responsible for the end-to-end deployment cycle, from basic provisioning of OpenStack cluster nodes, DB, AMQP and HA configuration to final configuration of all options selected by the end user as well as working on orchestration and business logic framework.)*

Estimating Resiliency: Is your cloud carrier-grade?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Your cloud runs mission critical applications. You’ve designed your applications to be resilient – but they depend on your cloud for resiliency. Is your cloud resilient? Will it fail when you need it the most? This is one of the primary challenges facing organizations seeking to deploy Openstack based private clouds today. In this presentation we will present a formal method for analyzing infrastructure software running a cloud platform. We cover various areas from high availability, failover, upgrades, configuration failures & auditing, upgrades, etc. The focus will be on analyzing software faults, identifying the impacts of those faults, verifying the findings and using specific prescriptive methods to mitigate and/or fix problems identified.


* **Gautam Divgi** *(Gautam Divgi is a Principal Systems Architect with AT&T working on resiliency & performance of AT&T's cloud platform. While working for AT&T Gautam completed his M.S. and Ph.D. in Computer Science from the Illinois Institute of Technology. Gautam Divgi has 20 years of experience designing and implementing frameworks for highly performant and distributed systems. Other interests (especially from the Ph.D.) includes estimation and modeling of heavy tailed distribution. Currently his main focus is the software resiliency and reliability of AT&T's cloud installation along with its various added services and VNFs.)*

* **Rahul Neelakantan** *(Over 15 years of Information Technology experience.  Subject matter expertise in NoSQL databases (LDAP, Cassandra).Led platform architecture, strategy and roadmap development. Currently actively researching and working on container technology for NFV implementations)*

* **Geetha Sankuratri** *(Geetha is a Director with the Software Resiliency Engineering group at AT&T. She has been with the company since 2002. Prior to this role Geetha has worked on a wide range of roles with leading operations and production support teams as well as application and technology portfolio teams.)*

Skipping OpenStack Releases: (You Don’t) Gotta Catch ‘Em All
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most of the commonly-deployed OpenStack projects have been using a six-month release cycle for the majority of their existence.  In the early days of OpenStack’s lifetime in particular, a relatively short release cycle made a lot of sense due to the rapid pace of feature addition and new projects joining the fold.  Six years in, OpenStack is now a much more robust, mature platform that has attracted a much more diverse user base.  As the user base has expanded, it’s become apparent that not all operators wish to upgrade their clouds every six months.     Is it really possible to skip upstream releases?  Under what circumstances might you consider doing so, and what issues can you expect to encounter?  How can you orchestrate a skip-release upgrade? In this talk, we’ll dive into our experiences with skipping upstream releases on production clouds.


* **Mark Voelker** *(Mark Voelker is currently the OpenStack Architect with VMware, but generally prefers to think of himself as a breadth-first technologist. In past lives he has worked as a software engineer, engineering manager, and architect designing web applications, automation systems, mobile apps, traffic generators, and more weasely hacks than he can shake a stick at. He also helped design and support the infrastructure supporting his software, including LANs, award-winning SANs, load balancing, and servers. Mark currently works on enterprise cloud architecture, software defined networking, and distributed systems. He's been enamoured of Open Source approximately since his first exposure to the Internet, helped found Cisco's Open Source Conference and was part of the OpenStack@Cisco team before joining VMware in 2014 where he leads architecture for the VMware Integrated OpenStack R&D team. Mark has been active in the OpenStack community since 2011 when he attended the Diablo Design Summit and has been an attendee and/or speaker at every Summit since.  He is OpenStack Foundation member #54 and owns enough OpenStack t-shirts that he can go long stretches without doing laundry.  Mark co-founded the Triangle OpenStack Meetup in Research Triangle Park, NC in 2013 and currently leads the group's 830+ members.  As an application developer and infrastructure afficionado, Mark is concerned with interoperability of cloud platforms and is the co-chair of the DefCore Committee.  He is also a former core reviewer on the Puppet OpenStack project.  He has a habit of including vacation photos and Douglas Adams quotes in his presentations and his time can generally be bought with a sufficient quantity of doughnuts. When not holed up within the trail-photo covered walls of his workspace at home near Research Triangle Park, North Carolina, Mark can be found hiking, camping, backpacking, or making sawdust with extreme prejudice. Mark is a proud alumni of the Park Scholarships at NC State University and currently serves as a Regional Selection Leader for the scholarship. You can also find him on Twitter, LinkedIn, SlideShare, or at his occasional blog.)*

* **Sidharth Surana** *(Sidharth Surana is a Staff Engineer at VMware Inc. developing the VMware Integrated OpenStack product. He has been instrumental in design/implement various features for the VIO product. Few of the key features include OpenStack upgrade, patching for the product.)*

* **Karol Stepniewski** *(Karol is a Member of Technical Staff on the Openstack team at VMware. Originally from Poland, Karol joined the VMware team in Palo Alto in 2014. Prior to that, he spent 6+ years working on IT projects for big telco companies like Orange and T-Mobile Poland. Having customer-facing experience in scalable systems design & architecture, he joined VMware R&D to work on OpenStack. Karol's interests include cloud computing, SDN, and distributed systems, but also software UX & usability. He is a big fan of Go & Ruby programming languages (yes, he will rewrite entire OpenStack in Go some day).)*

Leveraging OpenStack-Ansible to deploy the Nova-LXD compute driver
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

There are many ways of running containers in an OpenStack environment.  Many deployment scenarios run containers inside of instances.  However, containers can also be deployed outside of instances, and one method of doing that is by using the nova-lxd compute driver.  OpenStack-Ansible is a community-driven way to deploy an OpenStack cloud, including a mixed hypervisor cloud utilizing the new nova-lxd compute driver.  LXD allows the resource and performance benefits of application containers, without sacrificing core system services such as logging, or requiring application rewrites to utilize existing software.  In this talk, we will show users how to configure OpenStack-Ansible to deploy a mixed hypervisor environment using KVM and LXD.


* **Michael Gugino** *(Michael Gugino works for Walmart on their Cloud Operations team at in Reston, Virginia, USA. He has knowledge and experience with Python, Ansible, Puppet, C, MySQL, RabbitMQ, NoSQL, and of course, Linux. Michael contributes regularly to OpenStack-Ansible.)*

* **Jimmy McCrory** *(Jimmy McCrory is a Senior Cloud Engineer with Walmart's Global eCommerce division. He was a member of the team responsible for the deployments of Walmart's first production OpenStack clouds, and now has 3 years' experience deploying and operating large production OpenStack environments.)*

Your Cloud Architecture in Yoga Pants: Staying Flexible Over Time
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Today OpenStack has become a powerful, extremely flexible platform that can fit a lot of different needs and use cases. There are specialized OpenStack deployments for NFV and for e-commerce. Clouds that host production workloads and clouds intended for developers. But most OpenStack clouds whether big or small have one trait in common: they change. More often than not, OpenStack clouds grow as they pick up new workloads. They add or swap out hardware and upgrade underpinning software.  They get tasked with new requirements or different constraints around uptime or performance.  They add new projects from upstream, or change backends for existing projects.  Given time, almost every dimension of an OpenStack cloud is subject to change. So since there’s no one-size-fits-all deployment architecture, it’s clear that you’ll need your cloud to evolve with you In this talk, we’ll dive into our experiences with changing deployment architecture on production clouds.  


* **Sidharth Surana** *(Sidharth Surana is a Staff Engineer at VMware Inc. developing the VMware Integrated OpenStack product. He has been instrumental in design/implement various features for the VIO product. Few of the key features include OpenStack upgrade, patching for the product.)*

* **Karol Stepniewski** *(Karol is a Member of Technical Staff on the Openstack team at VMware. Originally from Poland, Karol joined the VMware team in Palo Alto in 2014. Prior to that, he spent 6+ years working on IT projects for big telco companies like Orange and T-Mobile Poland. Having customer-facing experience in scalable systems design & architecture, he joined VMware R&D to work on OpenStack. Karol's interests include cloud computing, SDN, and distributed systems, but also software UX & usability. He is a big fan of Go & Ruby programming languages (yes, he will rewrite entire OpenStack in Go some day).)*

Cloud Comparisons with PerfKit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Use Google's perfkit to compare a real private cloud with some public ones.


* **David Medberry** *(Open source advocate for 15+ years. OpenStack developer, deployer since 2011... Frisbee thrower as long as I can remember... https://etherpad.openstack.org/p/AUS-BoF-OVN  )*

Make easy use of Active Directory in your OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Come listen to how your corporation can best configure keystone and other OpenStack services to work with your Active Directory identity service in your organization. This presentation will go in depth with each configuration option of keystone to hook it up with AD.


* **Eric Brown** *(As a Software Engineer for many years, Eric specializes in security for many of those years.  Today he focuses on delivering features for VMware Integrated OpenStack, a distribution of OpenStack dedicated for VMware software.)*

Building AT&T’s Integrated Cloud: How to implement a custom architecture using Fuel Plugins
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Fuel is a great tool to deploy clouds in an user friendly way with the added bonus of having a flexible plugin engine and deployment task graph. In this talk, members of the AT&T Integrated Cloud (AIC) Fuel Automation team demonstrate how to achieve a target state architecture that differs from the out-of-the-box one deployed by OpenStack Fuel. Through a technical demonstration, we intend to show how to create a Fuel plugin that distributes OpenStack services across multiple node roles, integrates third party plugins that enable features like Contrail and how to manipulate the deployment task graph.


* **Omar Rivera** *(Joined AT&T's Integrated Cloud project in 2015 under Andrew Leasck, Director of Technology Development for AT&T's Integrated Cloud. Became a DevOps Engineer at AT&T working with the Security team and presently the Automation and Deployment team using OpenStack Fuel and Puppet. I am interested in infrastructure deployment, automation, lifecycle management, ease of operations, and networking.)*

* **Pavel Basov** *(Joined Mirantis in 2015 as an Openstack Deployment Engineer. Deploying customer clouds, working on improving Fuel and its plugins. Interested in automation, networking and cloud computing in general.)*

Swift Encryption at Rest in the field
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Encryption at Rest has landed for OpenStack Swift.   Learn first hand how to get this feature up and running from a core Swift developer.  Review the steps to convert existing cluser data to encrypted.  Review performance benchmarks, what to avoid, and next steps of Encyption on OpenStack Swift.


* **Doug Soltesz** *(Doug is currently a Director of Product Solutions at SwiftStack and has over 15 years of experience working in Information Technology. Prior to joining SwiftStack, Doug was VP of IT at Budd Van Lines. Doug has been recognized and received innovation awards in the areas of green initiatives, virtualization, disaster readiness, and workflow consolidation. Prior to Budd Van Lines, Doug was President of NetTech Solutions, a Systems Integrator servicing the NYC Metro Area.)*

* **Clay Gerrard** *(Clay Gerrard is a Sr. Software Engineer at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Clay was part of the original development team at Rackspace that created Rackspace Files, which became the Swift project within OpenStack when it was made open source. Clay has continued to be active in the OpenStack community as a contributor to the Swift project.)*

Enabling Enterprise: How Accenture delivers skills for Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have thousands of employees? Do you want a way to empower your enterprise resources and build their skills without losing productivity? At the center of this growth, Openstack brings a set of market-valued skills to every technical resource in Cloud Computing. Learn how Accenture was able to successfully meet client demands through enabling skills for Openstack delivery. One key factor to keep in mind that Openstack is not just a technology decision – but also a business decision . Make sure your enterprise is ready!    


* **Amanda Abdalla** *(Amanda Abdalla brings 8 years to the technology and business workforce with unique experiences in driving technology enablement and solutions. She’s been instrumental in the growth and success of Accenture clients around Cloud infrastructure and management consulting.)*

Migrate workloads from any cloud to any cloud - The "Easy Button"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many companies are trying to leverage their existing hardware to move from legacy or virtual environments to updated technology through the use of migration tools or methodologies. Honestly it takes lots of effect building out the API enabled framework that can pull data from sometime old, obscure hardware or complex workloads, or vendor locked environments wanting to have the freedom offered by OpenSource. At Accenture we have built and implemented our latest migration technical platform with integrated services to move existing virtual and legacy to OpenStack. This session is a technical deep dive to help attendees understand what are the key operational elements needed to build a converted that provides an end to end operational model that is integrated into an intelligent orchestration platform. We will use customer use cases to help work through several scenarios and talk about real experiences that you can take home and use for your migration activities.


* **Denise Glasscock** *(Global OpenStack Lead and Community of Practice lead for OpenStack.  I am responsible for the Strategic direction for OpenStack and lead the Red Hat Cloud Offering.  I provide the enablement, act as the technology SME for OpenSource Cloud solutions, and help drive client pipeline and Sales enablement.  I have almost 10 years of Cloud experience across all of the large cloud platforms and I have 20 years of experience in Datacenter and systems integration.  I am certified as a TOGAF and IBM Architect in infrastructure and Integrator knowledge domains.  I hold certifications in OpenStack and have an instructor rating within VMware and Red Hat.  I also provide workshops at all levels to help Accenture and our clients grow their knowledge and understanding of market and technology.)*

Cisco: Testing strategies for openstack based production cloud platforms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As part of the Quality Engineering team at Cisco, we have to ensure the quality and stability of the various environments and to find issues before our customers do. In this presentation we will go over the test strategies we use to accomplish this goal.  Our tests include: sanity test ongoing regression test incremental feature test user experience test perf/scale test Much attention is given to perf/scale testing, but housekeeping of production environments has not been previously discussed.Some tests run everyday to mark a baseline, while some tests are run when changes/upgrades are made. Some tests run for comparison, before and after the change window or peak and off peak hours. Also, we test the platform both, as an end user and as an admin. This ensures we hit the same pain points that an end user would hit and any ops issues an admin would see.We will also discuss the vision of automating this, which will be presented to the community separately.


* **Manisha Yeshwanth** *(Manisha Yeshwanth is a QE test lead at Cisco Systems Inc., working on the Quality Engineering team.She started working on Openstack since the Havana release. Responsible for ensuring the quality of the environments before they are made production and since. Testing involves end to end integrated solution testing of the entire cloud platform of which Openstack is a huge part.  Attended the Austin summit with hopes of getting some information on the testing procedures used by various companies. Received very few pointers. Now that we have a built strategy we would like to share that at the next summit. )*

* **Mohan Natarajan** *(Mohan is a QA manager at Cisco Systems, leading multiple QA teams responsible for testing features for Cisco’s Openstack based Cloud Services offering in an Agile environment. Working on an initiative to centralize execution of test automation using open source tools to enable scalability of testing and reduce test execution footprint.  Mohan currently resides in High Point, North Carolina with his family.)*

* **Saravanan  Kuppuswamy** *(Responsible for driving, coordinating all QA test efforts across new sites/releases of Cisco’s Cloud Services offering. Driving a diverse team of engineers focusing on all aspects of features/services, that are packaged for the Openstack Cloud Solution by Cisco. Saravanan currently resides in Cary, North Carolina with his family)*

Extending OpenStack Swift usage to all users in the enterprise
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It has been said OpenStack Swift is a great storage platform – for engineers. Swift is a great storage product, But the truth is, in the enterprise, how do users interact with the data? How do you manage ACLs? How do you share data? The answer is the same - become an engineer. You need a modular suite of applications that you can grow and sculpt to fit an organization, and then re-sculpt as the needs evolve. This session will show how to make users productive and how admins can simplify management and compliance of swift data. Traditional storage requests have become self service, in an intuitive interface, via any OS, device or App. OpenStack Swift is required to offer a similar capability ie. enable users to pick what works best for them, provide the same storage view from anywhere, let users securely share data inside and outside a company if that makes the workforce more productive.


* **Erik Joelsson** *(Prior to Storage Made Easy Erik has worked in both engineering and operations. Early in his career, Erik relocated from Sweden to the US to become Director of Engineering for a medical device company, building digital imaging storage and delivery systems. Since then he has excelled in many industries and roles. He led teams of engineers designing both software products and operational systems to ensure technical excellence for government and large enterprises. He led the team responsible for all compute and storage for the San Francisco International Airport, during several years of double digit passenger growth. In later years Erik has worked as both a manager and individual contributor for Big Data consultants and cloud storage vendors.)*

Simple Scale Test for OpenStack Control Plane
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scale testing the OpenStack controller with physical or virtual hosts is not always feasible and is bounded by the resources available. In this talk we dive in to the various steps we followed to scale test the Platform9 Control plane with limited resources.With almost every OpenStack project it is possible to create a fake driver that creates the relevant objects either in memory or as simple files on the filesystem. Scale testing control plane using a fake driver allows creation of many hosts that connect and consume the control messages like a real host. This allows evaluating performance of various api processes, messaging queues and databases with thousands of hosts interacting with the OpenStack.Areas that we will discuss may include - enhancements made to fake driver in nova, implementation of similar fake drivers for cinder and possibly neutron. Other aspects of this talk would include performance metrics that we collected running OpenStack under various load conditions.


* **Pushkar Acharya** *(Pushkar Acharya is an early engineer with Platform9 Systems Inc., working on vSphere integration with Platform9 primarily in the nova, cinder and glance. Recently also started working on integrating VMware NSX plugin in neutron with Platform9 OpenStack.)*

* **Sachin Manpathak** *(I lead core openstack projects at Platform9 such as Nova, Cinder and Keystone. In the past, I was an engineer in  VMware Resource Management group responsible for Storage DRS and Storage IO Control. I am passonate about Cloud, Resource Management, Storage and Containers.)*

Is it still raining? Getting weather reports from the clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Weather has been a blackbox for ages until humanity learned how to observe and measure it's certain aspects. It was not until August of 1861 that the first ever weather report was published in The Times, giving people knowledge about conditions outside and allowing to plan their adventures a bit ahead of time. Luckily enough, we do not have to wait another century to be able to take a peek into today's clouds. OpenStack gives us a vast number of resources to master and for every successful cloud deployment it is crucial to know the resources at hand. Having this knowledge helps to plan ahead and adapt to ever changing conditions, wether it is a sunny Saturday's afternoon or Monday's heavy storms.This presentation takes focus on methods for metric processing and taking preemptive actions to avoid potential downtime. It covers key metrics and data points on the example of Nova and Cinder services. We will take a look into existing solutions, both from a big tent and from outside.


* **Maciej Szankin** *(Maciej is a Cloud Software Engineer at Intel and is part of OSIC initiative that aims to ready OpenStack for enterprise workloads of tomorrow. He started his OpenStack adventure with Kilo release, with main focus on contribution to Nova. In private life a Jenga master and philosopher.)*

* **Alicja Kwaśniewska** *(Alicja is a software engineer at Intel working with Openstack. For past year she has been a part of "Win the Enterprise effort", with her primary focus on Kolla project - Openstack deployment using containers, where she is a core reviewer now. She graduated cum laude with Masters degree from University Of Technology in Gdansk and continues her education on PhD degree.)*

* **Szymon Wróblewski** *(Szymon is software engineer at Intel, parto of OSIC team, contributing to OpenStack. Currently he is focusing on improving HA capabilities of OpenStack as a part of “Win the Enterprise” effort. Photographer in free time.)*

Quark Performance
~~~~~~~~~~~~~~~~~

**Abstract:**

Rackspace's Neutron Quark plugin has been optimized for many performance related scenarios; from its recycling IP addresses and re-using them algorithms and more. For  this reason, much testing and investigation was doneto fully convey all the performance improvements of Quark plugin over upstream Openstack's Neutron performance.


* **Besan Abu Radwan** *(My name is Bess, I go by beslemon most places. I am a developer, a performance engineer, a HPC (High Performance Computing) fanatic, a researcher, and much more.)*

* **Justin Hammond** *(None)*

Addressing Open Issues in Container Orchestration using OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Frameworks such as mesos, kubernetes and docker swarm make it possible to run containerized applications at scale across a fleet of container host. However, there are several open issues that are yet to be addressed around operationalizing these frameworks in productions. Issues such as managing the lifecycle of the underlying infrastructure (onboarding, decommissioning, maintenance, autoscaling etc), health check and monitoring, identity management, certificate / key management, security & access control, integration with existing systems (IPAM etc) and more.In this session we will list out the open challenges around operationalizing the container frameworks and propose ways in which OpenStack can be used as the platform to address these gaps, making it easy for enterprises to take these container frameworks to production.


* **Santhosh Sundararaman** *(Santhosh Sundararaman is a Product Manager in VMware's Cloud Management Business Unit, where he focusses on the product strategy for VMware Integrated OpenStack and other cloud infrastructure products. He also works closely with the Networking, Storage and Management business units in VMware to drive integration between OpenStack and the VMware infrastructure products. Prior to this Santhosh was an engineer in the Networking and Security Business Unit at VMware developing vSphere networking features for VDS and the NSX networking virtualization platform. Santhosh holds a bachelor's degree in Information Technology and a Master's in Computer Science. Santhosh has spoken at various technology conferences such as VMworld, PEX and at multiple past OpenStack design summits.)*

* **Giridhar Jayavelu** *(Giridhar Jayavelu is a Staff Engineer from the NFV group at VMware. Giridhar workson VMware Integrated OpenStack (VIO) enabling features to meet the carrier grade requirementsfrom customers in Telco space. He has been involved in various automation initiatives within VMware.Prior to joining OpenStack team, Giridhar worked on vSphere networking and NSX team for about 8 years.Giridhar holds a Master's degree in Computer Engineering from the University of Arizona, Tucson.If OpenStack and NFV don't keep him busy, you can find him involved in short film productions.)*

Duct Tape and Super Glue - Monitoring an OpenStack Deployment with Tools in Your Bag
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In an OpenStack take on Trust-but-Verify, JR Rivers, CTO & co-founder of Cumulus Networks, will demonstrate a techniquesl for monitoring and troubleshooting OpenStack deployments using common DevOps frameworks such as Bash, Python, Ansible, and InfluxDb.


* **JR Rivers** *(JR is the co-founder and CTO of Cumulus Networks where he is deeply involved in the company, product, and technology direction.  JR has been involved with networking since Ethernet only ran on coaxial cables.  He's worked on some of the most foundational networking products of their time, from early Network Interface Cards at 3Com through switching and routing products at Cisco. JR's early involvement in home-grown networking at Google and as the VP of System Architecture for Cisco's Unified Computing System both helped fine tune his perspective on networking for the modern datacenter.)*

Vendor-neutral distributed Multi-Site OpenStack cloud architecture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many customers today are looking for distributed OpenStack cloud architecture spread across multiple data centers. Key aspect is vendor-neutral and no lock-in cloud. The solution is to have the OpenStack control plane with required common services in each data center and have a separate region for each vendor. Each region runs OpenStack services like Nova, Neutron, Cinder, Heat etc. from any of the OpenStack vendors and these services will be registered in common Keystone. Another approach is to have two independent clouds running OpenStack, with federated Keystone services which will be LDAP or AD integrated. WebSSO enabled for Horizon for seamless sign-on to multiple regions. Swift Container Synchronization can be used to ensure mirrored copies of data. Glance using Swift as storage backend, will have access to the mirrored copies of images. Presenters:  Subhrangshu Kumar (subhrangshu-kumar.sarkar@hpe.com) Sudhindra Subbarao (sudhindra.s@hpe.com) Sunitha K (sunitha.kannan@hpe.com)


* **Sunitha Kannan** *(Working at HPE India, Global Solution Engineering team. Have 15+ years of experience in IT. Core expertise is in OpenStack Cloud and Storage. )*

* **sUdhindra Subbarao** *(Sudhindra Subbarao is the EMEA Region lead for the NFV POC COE works out of Grenoble, France. 11 years of experience in various roles – Development, Program management, Presales, Solutioning and Consulting. Recognized expert in Openstack, Cloud & Automation and Licensing domain.  Responsible for solution designing, deploying and demonstratng Carrier Grade POCs for various Telcos in EMEA and APJ.  Also responsible for solutioning Cloud brokerage solutions through a market palce portal (HP CSA /OO) to consume hetergoenous clouds spanning across private and public cloud providers. Be it AWS, Azure, HPE Helion or IBM Softlayer. And providing Technical Leadership in the area of Openstack, Cloud and Automation for Enterprise, Financial isntitution and Telcos.)*

It’s Installed! Now what? - Day 2 Operations and TripleO
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

TripleO was developed to provide the ability to install, upgrade, and operate OpenStack clouds using OpenStack's own cloud facilities as the foundation. As OpenStack and TripleO continue to mature, we can leverage their feature sets to solve more complex operational tasks.   This session aims to walk through common Day 2 Operational scenarios you might encounter with an Openstack installation deployed with TripleO and provide attendees the answers to implementing tasks such as: Backing up and restoring your undercloud Restoring a failed overcloud node Applying configuration customisations via TripleO Keeping your overcloud current with the latest packages Scaling out your cloud


* **Roger Lopez** *(Roger Lopez is a principal software engineer in Red Hat’s Solutions Engineering group. This team identifies high-value solution stacks based on input from Sales, Marketing, and Engineering teams and develops reference architectures for internal and external customers. Roger is a Red Hat Certified Engineer (RHCE) with more than 9 years of computer industry experience at Dell and Red Hat. I've presented at conference such as Red Hat Summit, Collaborate, Oracle World over the course of those nine years. I've currently been working on OpenStack for almost two years with my focus around Performance and Scalability, and Backup and Recovery. Below are some blogs and reference architectures around OpenStack that I've written: http://redhatstackblog.redhat.com/2015/08/17/performance-and-scaling-your-red-hat-enterprise-linux-openstack-platform-cloud/ https://access.redhat.com/node/1507893/40 https://access.redhat.com/articles/2165131  )*

* **Graeme Gillies** *(Graeme is a Systems Administrator/Openstack Operator by trade, currently working within Openstack Engineering at Red Hat. He has been actively deploying Openstack inside Red Hat for four years, as well as assisting others with deployment and management of Openstack at all scale.)*

Got Backup? Hybrid Backup for Hybrid Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Using hybrid backup for your hybrid cloud architecture, you control which components are backed up to which backends dynamically.  This functionality is offered to our customers via the EMC Data Protection Extension for OpenStack functionality extended via the DPE Management API. Our session will illustrate the use cases of: Backing Up Tenancy Data-instances-metadata (nova, neutron, etc.)-keys Restoring Tenancy Data-restore as new-restore as original-restore to differnet zones File Level Recovery-restore files from backups Performance Enhancements-see Data Protection Extension perform on ScaleIO, VMAX, VNX & more Watch as tenancy information can be restored with ease.  See exciting new features coming from the EMC Data Protection backlog.  Find out how you can get started backing up your OpenStack tenancy today.


* **Mark West** *(Mark West has been a software professional for over 15 years. He is currently a Principal Software Engineer and Architect leading OpenStack Data Protection design and development project at EMC.  Mark’s experience spans from IT Operation to Engineering Development specializing in cloud computing on Microsoft, VMware, and OpenStack platforms.  As an architect for OpenStack Data Protection, Mark has involved in various design discussions with large enterprises and service providers and has a deep understanding of many OpenStack deployments and their data protection needs.)*

* **David Lombardi** *(David is a manager within EMC's Global Technology Office.)*

Implementing OpenStack in the Financial Services Industry using lessons learned from Telco.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While the Financial Services Industry and the Telco industry would appear to be on separate paths, experience shows that many of the requirements, issues, and tasks required to build, deploy, operate OpenStack are the same.  This session will compare and contrast both industries but ultimately show that a common pattern emerges. Using lessons learned from the Telco Industry, we will show that you can satisfy your requirements, eliminate issues, and get on the right path to success. 


* **Brent Clements** *(Been working with OpenStack since Diablo and absolutely love building solutions using the OpenStack Framework.  I've done a little bit of everything with OpenStack from deploying, architecting, & developing code all the way to selling OpenStack Solutions to Service Providers and Enterprises. Currently working as the Practice Lead for the Consulting Architect team at Canonical. We help customers focus on their business rather than the technical complexities of software. We do this by providing open source software that allows for model-driven operations of "big software".   )*

* **Christian DeYoung** *(Specializing in business development and design of architecture that supports "First of a Kind" projects. Chris has over 20 years experience in the IT industry. Most of his last fifteen years has been in the Cloud & HPC field from a pre-sales design phase through implementation. Chris specializes in Enterprise Architecture, reference architecture, design, sizing and implementation of infrastructure and services. He gets it delivered on time and within budget.Chris' objective is to influence individuals, groups and society; empowering them to advance their business by designing & delivering the tools, systems and support they need to meet their business goals. Specialties include : Enterprise Architecture, Business Development, IT Architecture, Cloud, consulting, HPC. Linux, High Performance Computing, Clusters,Unix,Red Hat, SuSE, Novell, PBS, MPICH, SAN, Design, HA, RFP, RFI, Sales, Proof of Concept.)*

RabbitMQ Architecture for Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Recommended architecture and best practices for setting up scalable and high available rabbitmq environment to support large scale openstack deployments 


* **venkatesh gnanasekaran** *(Decisive, results-oriented and proactive professional with extensive experience in analysis, design, development and implementation of various Java and NoSQL applications. Have made a significant impact to every project that I have worked. Also have filed four patent applications with US Patent office and three more ideas for which internal review is in progress. )*
