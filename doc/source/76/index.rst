HPC / Research
==============

Clustered HPC and Big Data on-demand
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will teach you how you can use OpenStack, Heat, (and Ceph) to offer your users the ability to create complex, reproducible, extendible, clustered infrastructures, in minutes, at a push of a button. We call our approach Cluster-as-a-Service and we happen to use it for offering our users self-managed and fully monitored virtualized services like Hadoop, Spark, OpenStack, HPC, all in a as-a-Service manner. But you can use this, or a similar, approach for offering whatever you want.


* **Piotr Wachowicz** *(Piotr Wachowicz is a Cloud Integration Lead for Bright Computing. He's passionate about clouds, networking, and all things software defined. He's been working with OpenStack for several years, and his daily focus is looking after the deployment process, and management/monitoring of Bright OpenStack.)*

Arrebol: easy and efficient execution of Bag-of-Task applications on federated clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We present Arrebol, a service for the easy execution of Bag-of-tasks (BoT) applications in private, public and hybrid clouds. Arrebol provides an intuitive scripting language to define large BoT jobs in a succinct way. Using a command line interface, users can submit jobs to the Arrebol submission service. It parses the jobs and interacts with the underlying cloud to create the infrastructure required to run them. Then, it submits tasks to execute in parallel, and dismantles the infrastructure when it is no longer needed, making the management of the execution of jobs completely transparent to the users. BoT applications are ideally suited to be executed over elastic cloud infrastructures. We also discuss how Arrebol leverages Fogbow, a middleware for federating clouds, to increase the capacity of the infrastructure by exploiting different hybrid settings, including cloudbursting and cloud federation. Both Arrebol and Fogbow are available as open source under Apache 2.0 license.


* **Francisco Brasileiro** *(Francisco Brasileiro is a full professor at the Systems and Computing Department of the Federal University of Campina Grande (UFCG) in Brazil. His research is focused on the area of distributed computing, with focus on grid and cloud computing and support for escience applications. An updated list of publications can be found at http://dblp.uni-trier.de/pers/hd/b/Brasileiro:Francisco_Vilar. He currently coordinates the EUBrazil Cloud Connect project (http://eubrazilcloudconnect.org/) and leads the team developing Fogbow (http://fogbowcloud.org/), a middleware for the federation of private clouds. He is a member of UFCG's team that contributes with the Openstack community.)*

* **Andrey Brito** *(Andrey Brito is a Professor at UFCG (Universidade Federal de Campina Grande) in the Computer Science Department. Andrey’s main interests are robustness and scalability aspects of distributed systems. He coordinates R&D teams that have been contributing to OpenStack, specially regarding federation, hierarchical multitenancy and integration between Ironic and infrastructure managers.)*

* **Thiago Emmanuel Pereira** *(I received BSc (2008) and MSc (2010) degrees in Computing Science from the Federal University of Campina. I am a currentlty PhD student with the same university, associated with the distributed systems lab (www.lsd.ufcg.edu.br).)*

The Silent Cloud Majority: Making Life Sciences Excel With OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Researchers in the Life Sciences have historically used traditional bare-metal scheduled environments for computationally-intensive work. Increasingly those who maintain infrastructure for such users are provisioning private clouds using OpenStack. Unlike the canonical cloud use-case of a database-backed web service, which can fairly easily adapt to infrastructure as a service and take the best advantage of its strengths, scientists have a large hinterland of code written for a different world. In this presentation we discuss the challenges, both technological and cultural, of running Life Sciences codes on OpenStack clouds and how we overcame them. Topics covered include shared filesystems for instances, the crucial importance of third-party tools to make successful use of a cloud, and how to bridge the impedance mismatch between users' expectations and the reality of using OpenStack. We also consider longer-term questions of directly adapting applications for running on OpenStack.  


* **Adam Huffman** *(My current role is Senior HPC and Cloud Systems Engineer at the Francis Crick Institute. One of my responsibilties is to work as part of the Operations Team running the eMedLab shared private cloud (http://www.emedlab.ac.uk/), which is using OpenStack. I will also operate a private cloud for the Crick in the new Midland Road building, in addition to being part of the team setting up and running HPC resources at the Crick. I am also a Visitor in the High Energy Physics group of the Department of Physics at Imperial College London, continuing my involvement from my previous role there, now that I'm at the Crick. For Imperial, I setup a small private cloud running OpenStack and have been involved in several cloud projects, all using OpenStack, for the CMS experiment. I also worked on OpenStack clouds for GridPP.)*

Neutron and SLURM: Software-defined Networking for HPC Clusters
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Los Alamos National Laboratory is continuing its work to enhance HPC with cloud technologies. The latest development is a SLURM plugin that allows the HPC resource manager to control a job's network access via Neutron. This plugin enables on-demand access to network resources and job segregation. I will describe how this plugin works and give a demonstration of its use. LA-UR-16-24835


* **Timothy Randles** *(Tim is a member of Los Alamos National Laboratory's HPC division.  He works on the production sysadmin team supporting existing systems while also developing next-generation HPC cluster capabilities.  His current focus is on flexible stacks.)*

Bridging Parallel File Systems with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

At Los Alamos National Laboratory (LANL) there are many types of File Systems. LANL has Lustre, GPFS, NFS as well as various other file systems available. The management of all this data can be an onerous task. In many environments external to LANL, automatic tiering mechanisms are utilized to migrate data to other storage systems based on storage policies. LANL takes a different approach to data management. In our use case the user manages and migrates the data around manually using File Transfer Agents (FTAs). In this talk, I will discuss how LANL will use OpenStack to deploy and manage this type of cluster. I will go over motivations, as well as lessons learned, and advantages of this approach.


* **Christopher Hoffman** *(Christopher Hoffman is a Computer Scientist at Los Alamos National Laboratory. He has background in Windows, Linux, and Scientific HPC Systems. He has experience in deploying multiple large multi-petabyte storage systems as well as being the lead system administrator on a variety of HPC projects.)*

Openstack and Ceph used in large scale cancer research projects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk will describe how OICR created the Cancer Genome Collaboratory, a highly-available OpenStack and Ceph environment that can scale up to 3000 cores and 15 PB object storage. The design goals and trade-offs required will be discussed. The Collaboratory currently stores 500 TB of genomic data from the International Cancer Genome Consortium (ICGC) in a triple-replicated object store, and the dataset is expected to grow to 5 PB by 2018.  Software optimized for Ceph storage was developed to authenticate and provide data access to only authorized users.  One project as an early user of the Collaboratory is the PanCancer Analysis of Whole Genomes, one of the world's largest cancer data analysis initiative exploring the whole genomes from over 2800 patients across 20 tumor types. The use case further drove the development of the ICGC Data Portal for searching data (https://dcc.icgc.org/repositories), and the development of Dockstore for sharing workflows as docker containers.


* **George Mihaiescu** *(George is a Senior Cloud Architect in the Informatics and Bio-computing Program at the bio-informatics department of Ontario Institute for Cancer Research (OICR) where he designs, builds and supports a large Openstack/Ceph environment to enable cancer research used by cancer researchers. Having started with Openstack during the Cactus release, he  brings his expertise around cloud design, operations, infrastructure, security and performance tuning in the interest of science. Previously, he was at Q9 Networks,  a major datacenter infrastructure provider in Toronto where he held various technical roles in the span of six years. In the last two years at OICR, his focus was around deploying and supporting a highly available OpenStack private cloud that grew to more than 1000 cores and 3.2 PB of Ceph storage)*

High Performance Computing - Ironically not just for baremetal
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

High Performance Compute (HPC) environments are used across many different types of business and range in size from a handful of nodes to thousands of nodes. Some companies run their HPC in the public cloud, some run in in their own private cloud, and some have to do a mix of both. Monitoring and orchestrating the size of these clusters can be done using a cloud management platform (CMP). In this session, we will present a reference architecture that leverages several different products, including OpenStack and Ansible, to help monitor your HPC clusters and scale them up or down as the current load dictates. Since this is all open source and we all like choices, you can mix and match components into your final solution. Don't want to rely on Heat for software config? We'll let Ansible handle that. Don't want to worry about a different method for scaling each provider? We'll use a CMP, such as ManageIQ, to help decide which provider to use and orchestrate the actual deployment.


* **Nate Stephany** *(Nate Stephany is a Senior Cloud Solution Architect at Red Hat who focuses on Red Hat's cloud products, such as OpenStack, CloudForms, and OpenShift. He has over 15 years of enterprise systems architecture and administration experience, with the majority of this time spent in the telecom industry.)*

* **Kevin Morey** *(Kevin Morey is a Principal Cloud Solution Architect at Red Hat who focuses on Red Hat's Cloud portfolio including OpenStack and CloudForms, Red Hat's Cloud Management Platform. Kevin has over 25 years of Enterprise Systems Administration, Professional Services as well as Systems Engineering. Kevin's passion for innovation and cloud computing led him to Red Hat.)*

HPC, Unikernels and OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session explains lessons learned integrating HPC workloads with unikernels on top of OpenStack. HPC workloads are traditionally executed in general purpose operating systems running directly on the host. Virtualized and containerised environments using these base systems are being adopted to improve flexibility and manageability of the infrastructure. To this end, the MIKELANGELO project is using a lightweight unikernel (OSv) providing bare minimum, but fully virtualized environment to these workloads. We are going to present a flexible application management that has been implemented specifically to support integration with cloud middlewares, such as OpenStack. This allows dynamic composition and execution of workloads based on user's needs. OpenFOAM CFD is being used to showcase our approach, including an integration into OpenStack dashboard. Finally, we will show how the use of a flexible telemetry system delivers in-depth insights into the infrastructure and application.


* **Gregor Berginc** *(Gregor has been self-taught software programmer since the age of 8. He has been a professional software developer, system architect and project/product manager for over 10 years providing expertise on all layers of multi-tier architectures. Over the last five years, my primary focus was on development and deployment of 3D-GIS solutions supporting emergency response centres in their efforts to provide timely and proper decisions in time-critical situations. Beginning in 2015 he took a role of a technical manager of an European project MIKELANGELO resolving few of the main pain-points large HPC centers experience when considering more flexible, Cloud-based, architectures. Besides engineering skills, he has developed great management skills leading multidisciplinary teams and interacting with external partners and clients. My greatest satisfaction is when customers are using our software and services the way they anticipated. He loves having conversations with clients discussing all aspects of the system in search for optimal solutions allowing me to translate client's pain to the language understood by my colleagues. Whenever possible, Gregor tries to employ agile software development methodology based on modern code sharing, review and testing technologies guaranteeing high quality of team's work.)*

* **Daniel Vladušič** *(Daniel Vladušič has a deep interest in computer science, which covers the fields from pure software development to the management of the technological projects. His past interests was efficiency of algorithms and artificial intelligence - most importantly, bridging the gap between traditional artificial intelligence and the machine learning. Part of his work in the field of the artificial intelligence was resulted in a PhD, which he received from the University of Ljubljana in 2005, with the thesis titled Use of qualitative models in quantitative prediction. After obtaining PhD, Daniel went to mix the the machine learning field know-how with the traditional GRID computing, within his post doctoral education, developing an add-on method to assist with the job scheduling problem. His work diversified into obtaining commercial projects from various fields, managing them and delivering the product. Given his scientific interests, he worked on lot of research projects, ranging from the FP6, FP7 and now, H2020 programmes. His work included either leadership functions or technology insight from the wealth of past experience. He is currently the coordinator of the H2020 MIKELANGELO project.)*

Using OmniPath fabric in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

High Performance Computing (HPC) workloads require a balance of computation, memory access and inter-node communication. Efficient memory access may require understanding low-level memory topology, including non-uniform memory accesses for SMP systems (NUMA). For optimal communication inside HPC cluster fabric interconnection solutions, like Intel's OmniPath, are used. Cloud computing traditionally use Ethernet-based solutions and SW-defined networking for communication. Is it possible to merge the flexibility of cloud solutions with the performance of bare metal cluster? In our presentation will show experience with using OmniPath in OpenStack. Performance results for HPC benchmarks executed on virtual machines are presented and compared with the same benchmark results obtained on the bare metal. Guidelines and examples, how to configure virtual environment, including OmniPath interfaces and NUMA nodes, to get the optimal performance results for HPC workloads are presented


* **Piotr Uminski** *(Piotr Uminski has been a software architect for Intel since 1999. He is currently working on HPC software for Intel Xeon and Intel Xeon Phi processors. Previously he participated in several wireless communication projects based on Intel IXP network processors, and took part in designing and implementing OpenGL driver for various generations of Intel graphic. During his work at Intel he participated in defining the IEEE 802.3 standard, and the OpenGL standard in the Khronos Group. Prior to Intel, Piotr was employed by Elektrobit OY and Olicom OY, focusing on telecommunication software. During that time he was also an assistant at Gdansk University of Technology, Faculty of Electronics, Telecommunication and Informatics where he conducted classes on low-level system programing. He received his PhD and M.Sc. in computer science from Gdansk University of Technology. He is an author and co-author of more than 10 publications, and contributor to numerous scientific conferences. He holds one U.S. patent.)*

* **Jakub Dlugolecki** *(Software Engineer at Intel, previously network admin in the same company.)*

Realities at a National Lab -- Caring for your HPC Pets with a Cattle Prod
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack drives the promise of an HPC cluster manager integrated with in-house virtualization infrastructures. Except our expectations were immediately brought back to earth at the first attempt to integrate an Ironic-deployed cluster with existing infrastructure services. We, at Oak Ridge and Los Alamos National Laboratories, suffered with deployment tools and documentation written for cloud environments, not our own data centers and HPC workflows. We needed the cluster to integrate with high performance network infrastructures and shared parallel filesystems, and to be able to build the images without internet connectivity. Finally after streamlining our own processes, we have some pain-saving advice to share with the community. In this talk we review deployment tools such as Kolla and openstack-ansible, as well as image building tools for HPC clusters. We compare the tools with an eye toward flexibility, and whether they were able accommodate our environments. LA-UR-16-24899


* **Timothy Randles** *(Tim is a member of Los Alamos National Laboratory's HPC division.  He works on the production sysadmin team supporting existing systems while also developing next-generation HPC cluster capabilities.  His current focus is on flexible stacks.)*

* **Blake Caldwell** *(Blake has been at Oak Ridge National Laboratory in the High Performance Computing Operations group since 2011 as a storage systems administrator. He is part of the storage team known for running some of the fastest filesystems in the world, including the 32 PB Spider-2 Lustre filesystem.Currently Blake is based in Boulder, CO while he devotes time to his PhD research in computer science at the University of Colorado. His dissertation area is creating a Linux operating system with native elastic memory capabilities.Outside of computing-related activities, Blake enjoys the outdoors and competing in cycling, running, and triathlon. From 2003-2009 he competed as a professional cyclist throughout the world and placed 2nd in the US Professional Road Race Championships in 2008.)*

* **Nathan Grodowitz** *(None)*

Image is Everything: Dynamic HPC VM Repositories using Murano
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As part of an effort to expand access to computing resources, the (US) National Science Foundation XSEDE project has funded several new computational resources with cloud provisioning capabilities – Bridges and JetStream. To facilitate sharing and reuse of scientific applications, an XSEDE Cloud Virtual Machine Repository has been proposed. Traditional delivery of applications involved monolithic images that requires development, construction, testing, maintenance, vetting, and cataloging of cloud virtual machine images which are non­trivial tasks. One solution is to use Murano, Heat, and cloud-init scripts to deliver scientific applications on a small number of generic images from Linux distribution maintainers rather than images. The use of standard OpenStack components makes the application repository usable by any standard OpenStack deployment. The details of construction, use, and highlights of a few selected applications will be covered.


* **John Lowe** *(John (Mike) holds a BS computer engineering degree from Purdue University.  He has worked in high performance computing and virtualization at Indiana University for 10 years.)*

* **Robert Budden** *(Robert is a systems developer and cluster administrator who has spent the past 10 years at the Pittsburgh Supercomputing Center working on data movement technologies, distributed filesystems, authentication and authorization, cluster scheduling, and cloud computing in HPC environments. Robert graduated from Penn State University in 2007 with a B.S. in Computer Science.)*

* **Jeremy Fischer** *(Jeremy Fischer is the Senior Technical Adviser for the Jetstream project, working for UITS Research Technologies at Indiana University. Prior to returning to IU in 2012, he was the Director for Unix Systems and Security at a regional ISP for several years and was the CEO of a multi-store retail chain for ten years following that. Finding that technology was his true professional passion, he returned to IU, first working with small scale clusters and then with practical applications of cloud computing. As part of the Jetstream team, he contributes as the technical outreach lead to researchers and also as the author and librarian for the virtual machine featured images among other duties. He has learned enough about OpenStack to be well and truly dangerous and probably shouldn't have root on those systems.)*

Docker Storage Support for Reproducible and Secure Scientific Computing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Performing scientific computing in OpenStack clouds is enabling greater collaboration among researchers.  While this is enabling more science than ever before, there are still several storage challenges including application portability, multi-tenancy and performance.  By introducing Docker, scientists can create a single portable package that encompasses all of their application dependencies, allowing scientists to share their applciations. Docker also solves many storage challenges in a scientific cloud by itsolating tenants from each other while allowing their applications to come and go with no impact to the storage subsystem.  


* **Dean Hildebrand** *(Dean Hildebrand is a senior researcher at the IBM Almaden Research Center and a recognized expert in the field of object storage as well as distributed and parallel file systems. Dr. Hildebrand pioneered pNFS, demonstrating the feasibility of providing standard and scalable access to any file system. He received a B.Sc. degree in computer science from the University of British Columbia in 1998 and M.S. and PhD. degrees in computer science from the University of Michigan in 2003 and 2007, respectively.)*

* **Nagapramod Mandagere** *(Nagapramod Mandagere received his PhD from University of Minnesota in Enterprise data management. He has been a researcher at IBM Almaden Research center since 2008 working on various systems technologies. He has coauthored several conference papers and has several patents in domain of systems management. Recent work revolves around container runtimes and is a contributer to cloudfoundry. )*

* **Amit Warke** *(Working as an Advisory Software Engineer at IBM Research in the Cloud Storage Group.)*

Chameleon: Building a Computer Science Testbed with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Chameleon testbed provides a platform for computer science research. To support a wide range of repeatable experiments, it provides capabilities such as deep reconfigurability and exclusive resource access. These features are mainly implemented with OpenStack software, in particular Ironic for bare-metal deployment and Blazar for resource reservation. Chameleon went public in July 2015 and currently supports 800+ users as well as many exciting cloud computing research and education projects. This talk will present the internal architecture of Chameleon and especially how Nova, Ironic, and Blazar interact together to provide Chameleon's core capabilities. We will share our experience with running OpenStack and identify planned upstream developments that are important for Chameleon.


* **Pierre Riteau** *(I am the Lead DevOps Engineer on the NSF-funded Chameleon project which provides a large-scale testbed for cloud computing researchers. Many of the capabilities provided by Chameleon are implemented with OpenStack.)*

OpenStack on the EGI Federated Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The EGI Federated Cloud is a multi-national cloud system that integrates institutional IaaS clouds into a scalable computing platform for data and/or compute driven applications and services. This infrastructure brings together more than 20 cloud providers, most of them deploying OpenStack, to support the computational needs of researchers all across Europe. EGI uses OpenStack to build a federation from a collection of independently operated deployments that are integrated with a set of core services to allow the interoperability with other cloud platforms. In this talk we will describe the EGI developments that extend OpenStack to build cloud federations for research and how OpenStack is deployed in the current production infrastructure of EGI. We will also highlight some of the use cases already taking profit of these resources.


* **Enol Fernández** *(Enol Fernández works as Cloud Architect for EGI Foundation and leads the EGI Federated Cloud Task Force, coordinating user support, operations and development activities to define the federation and its technologies. He has been involved several e-Infrastructure projects since 2003, first as a middleware developer and more recently giving support to users and communities to use clouds for scientific applications.)*

Driving Science in the Hybrid Cloud with Ansible
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Running HPC workloads entirely in public clouds presents a challenge because of the high cost of both the CPU/memory resources and the intensive data movement and storage requirements.  OpenStack provides the private cloud component of a hybrid cloud HPC strategy that not only accommodates a wider range of applications than specialized clusters but also reduces costs by running steady state workloads on premise and “bursting” into a public cloud.  Ansible provides the mechanism to create and maintain HPC clusters across clouds. This presentation covers impediments to doing traditional HPC workloads in a hybrid cloud and ways to mitigate them.  We present and demonstrate a set of Ansible playbooks to create a virtual cluster across clouds (OpenStack and AWS), connect them together, then provision storage and scheduler.  Finally, we discuss running analytics, genomics, and computational chemistry workloads in a hybrid cloud environment.


* **Steven Carter** *(Steven Carter is an Architect for Cisco Systems with over 15 years of industry experience working in large universities, government research and development, and the private sector.  He has spent time as a system administrator running some of the largest supercomputers in the world, built out one of the World's first SDN networks for the Department of Energy, and developed code for both network devices and supercomputers in the process.  Steven has a wide range of experience in embedded software development, large system design and build-out, and operations.  He currently works on building solutions for technical- and data-intensive cloud computing based on OpenStack and other software-defined technologies.)*

* **Jason Grimm** *(I am a husband, father and maker of things. I have lived most of my life in downtown Atlanta, but I now reside on an 11-acre sustainable family farm 1 hour north of the city. My background includes 25 years of IT experience, several certifications, various IT scar tissue and 2 technical degrees.  I am currently a Cloud Solutions Architect at Cisco and am pursuing my MIS degree at Georgia Tech. I have been working with OpenStack since the Essex release, have attended or spoken at the last 8 OpenStack summits. I am a veteran technologist with experience ranging from Naval Intelligence, freelance consulting, start-up co-founder, and a decade of professional services with Dell. My focus has been on cloud technology for the last 5 years beginning with Crowbar at Dell in 2011, Fuel at Mirantis, RPC at Rackspace and now Metacloud at Cisco. I am competent with Ruby, Python, Perl, BASH, and Java, but my greatest strengths are as a cross-discipline infrastructure architect designing and deploying complex OpenStack-based solutions and supporting sales, product and operations teams. Jason Grimm http://www.brothergrimm.com)*

* **Josh Lothian** *(Josh Lothian is an engineer at Cisco Systems.  He has over 15 years experience working in academic and high performance computing research facilities as a system administrator and developer.  He has supported the fastest HPC systems in the world, and is now leveraging that experience in an OpenStack devops role.)*

Hybrid HPC on OpenStack – Virtualization, bare metal, containers and micro-services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session we will examine the technology and use cases behind hybrid HPC on OpenStack. We will cover traditional virtualized design as well as requirements / considerations for incorporating hybrid functions, i.e. bare metal, containers and micro-services, for HPC workloads on OpenStack. We will also examine and answer related concerns and questions, such as: What are the performance returns of bare metal vs. virtualization? What are the feature / function losses when deploying on bare metal, e.g. networking, security groups, etc.? What functions are good candidates for micro-services, e.g. temporary PVFS, data transfer nodes, etc.? How do you segregate or associate tenants, instances, flavors, workloads, etc. across multiple platforms behind the same control plane? We will cover technical depth of why / how an organization may choose to leverage multi-platform capabilities for HPC as well as best practice approaches to deploying and maintaining these environments.


* **Jason Grimm** *(I am a husband, father and maker of things. I have lived most of my life in downtown Atlanta, but I now reside on an 11-acre sustainable family farm 1 hour north of the city. My background includes 25 years of IT experience, several certifications, various IT scar tissue and 2 technical degrees.  I am currently a Cloud Solutions Architect at Cisco and am pursuing my MIS degree at Georgia Tech. I have been working with OpenStack since the Essex release, have attended or spoken at the last 8 OpenStack summits. I am a veteran technologist with experience ranging from Naval Intelligence, freelance consulting, start-up co-founder, and a decade of professional services with Dell. My focus has been on cloud technology for the last 5 years beginning with Crowbar at Dell in 2011, Fuel at Mirantis, RPC at Rackspace and now Metacloud at Cisco. I am competent with Ruby, Python, Perl, BASH, and Java, but my greatest strengths are as a cross-discipline infrastructure architect designing and deploying complex OpenStack-based solutions and supporting sales, product and operations teams. Jason Grimm http://www.brothergrimm.com)*

* **Steven Carter** *(Steven Carter is an Architect for Cisco Systems with over 15 years of industry experience working in large universities, government research and development, and the private sector.  He has spent time as a system administrator running some of the largest supercomputers in the world, built out one of the World's first SDN networks for the Department of Energy, and developed code for both network devices and supercomputers in the process.  Steven has a wide range of experience in embedded software development, large system design and build-out, and operations.  He currently works on building solutions for technical- and data-intensive cloud computing based on OpenStack and other software-defined technologies.)*

* **Josh Lothian** *(Josh Lothian is an engineer at Cisco Systems.  He has over 15 years experience working in academic and high performance computing research facilities as a system administrator and developer.  He has supported the fastest HPC systems in the world, and is now leveraging that experience in an OpenStack devops role.)*

“Spartan”, a HPC - Cloud Hybrid: Delivering Performance and Flexibility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Spartan is a new breed of HPC; not a cluster but service that manages underlying clusters.  These clusters include high performance bare-metal as well as generic cloud based VMs, and many options in between. It is designed to reduce the time to output for the research community, by providing the most appropriate environment for each specific workload. Because Spartan has virtualized management and login nodes, it can easily migrate hosts as new hardware is deployed, with partitions expanding according to actual demand, rather than anticipated usage.  The totally modular approach eliminates the need for forklift upgrades, as Spartan the service will long outlive the original hardware that supports it. This presentation will cover: The vision for HPC at UoM Matching of use cases to compute Hardware selection Networking and low latency Storage Identity management SLURM, LMod, and Easybuild Performance Training


* **Greg Sauter** *(Greg Sauter is a Project Manager/Infrastructure Architect for large IT Research projects at the University of Melbourne. He has worked on the NeCTAR cloud and RDSI big storage. He is currently working on Software Designed Storage platforms and HPC in the Cloud. In the past he had a similar role working on the Amphibious Assault Ship (LHD) project for the Royal Australian Navy)*

* **Lev Lafayette** *(Lev Lafayette is the HPC Support and Training Officer at the University of Melbourne. Prior to that he spent several years in a similar role at  the recently deceased Victorian Partnership for Advanced Computing and has spent many years on the Linux Users of Victoria committee. He collects degrees for fun.)*

* **Bernard Meade** *(Bernard Meade is the Head of Research Compute Services at the University of Melbourne.  Providing researchers with cloud and high performance computing services, Bernard has been supporting the academic community for nearly 20 years.  With a keen interest in emerging technologies, he has worked with 3d printing, large scale visualisation, Internet-of-Things and was involved in the launch of the NeCTAR Research Cloud.  He is currently the Service Owner of the Melbourne Node and the central HPC services, including the latest offering, Spartan.)*

Lustre Integration for HPC on OpenStack at Cambridge and Monash
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Take a survey of scientific computing practitioners for a definition of HPC and you will undoubtedly end up with a broad picture encompassing various shapes, sizes and domains of individual and ensemble jobs. Ask about the storage needed to support these workloads and you’ll find they all need a high-performance filesystem (HPFS) designed for parallel access. OpenStack is now a hot topic in the HPC world. Whether it’s using OpenStack as a bare-metal provisioning service or looking to offer a flexible, integrated IaaS close to primary HPC. However, the question of how to integrate a HPFS with OpenStack is not yet well answered. Little wonder it was one of the priority areas surfaced by the Scientific WG in Austin. In this talk architects and operators from Cambridge University in the UK and Monash University in Australia will explain their approaches to integrating Lustre and OpenStack, the tradeoffs involved, the gaps remaining, and share performance data.


* **Blair Bethwaite** *(Blair has worked in distributed computing at Monash University for ten years, OpenStack for the last four. Team lead, architect, admin, user, researcher and occasional hacker - Blair's unique perspective has guided the evolution of the research computing engine central to Monash's 21st Century Microscope.)*

* **Wojciech Turek** *(None)*

* **None None** *(None)*

InfiniCortex and InfiniCloud: Distributing scientific computing around the World.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

InfiniCloud is the worlds first native InfiniBand based OpenStack cloud operating at a global scale. Connecting High Performance Computing facilities across four continents, spanning Asia, Australia, Europe and North America. The system supports evolving models offollow the sun energy use. InfinCloud frees Compute and Data from the traditional Data Centre boundary, creating a pool of resources for users independent of physical location while maintaining data security and sovereignty. The system takes OpenStack to new levels of network performance operating at both 56Gb/s and 100Gb/s speeds with full RDMA and High Performance Computing InfiniBand interconnect capabilities.When combined with long range and routable InfiniBand a unique model of in-place data accesshas become a reality. In this presentation we cover the InfiniCloud architecture and some of the exlempar applicationswhich been successfully operated on the system.


* **Garry Swan** *(Garry leads the Advanced Scientific Computing team in the Environmental Sciences area of the Commonwealth Scientific and Industrial Research Organisation.CSIRO, the Commonwealth Scientific and Industrial Research Organisation, is Australia's national science agency and one of the largest and most diverse research agencies in the world. CSIRO works with leading scientific organisations around the world, and is recognised internationally for the quality of its research.)*

High-performance filesystem integration - current practices and war stories
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is now a hot topic in the HPC world. Whether it’s using OpenStack as a bare-metal provisioning service or looking to offer a flexible, integrated IaaS close to primary HPC. However, the question of how to integrate a HPFS with OpenStack is not yet well answered. Little wonder it was one of the priority areas surfaced by the Scientific WG in Austin. This panel will bring together operators and practitioners from a number of research intensive institutions across the globe to discuss their various approaches to integrating high-performance filesystem access with their OpenStack clouds and provide a forum for community Q & A.


* **Blair Bethwaite** *(Blair has worked in distributed computing at Monash University for ten years, OpenStack for the last four. Team lead, architect, admin, user, researcher and occasional hacker - Blair's unique perspective has guided the evolution of the research computing engine central to Monash's 21st Century Microscope.)*

* **None None** *(None)*

* **Edgar Magana** *(Edgar is an emerging leader who has specialized in Cloud Computing, Network Virtualization, Software-defined Networking (SDN), Network Functions Virtualization (NFV), OpenFlow and OpenStack. He has developed excellent software development skills and outstanding customer and business driven experience. Currently, he is core member of the Neutron OpenStack development community. Edgar has strong experience in fully automated Cloud Computing deployments by means of puppet and chef orchestration languages. He has lead OpenStack development, third-party integration and deployment teams for over the last three years. Edgar is the lead architect responsible for driving the Cloud Operations initiatives that maximize the pace of innovation with Development and Operations. He is in charge of provifing architectural oversight for Workday’s Hybrid Cloud including the OpenStack based Private Cloud, bursting to multiple Public Clouds and extensive automation. Through strong collaboration, develop architectures, detailed designs, and in some cases POCs to support Development driven features requiring changes to the infrastructure.Establish tight alignment with Development Architects, representing Cloud Operations in the Technology Architecture Group. Edgar has an extensive experience on Cloud and Grid Computing, Policy-based Management Systems, Monitoring and Scheduling of networking and computational resources on distributed networks. He has been involved in multiple projects such as Cisco Quad, Cisco Enterprise Policy Manager, Access Control Server and Application Performance Assurance.)*

* **Thomas Connor** *(Dr Connor is a Senior Lecturer at Cardiff University. He is a Big Data Biologist whose work sits at the interface of Biology, Computer Science and Mathematics. He has a background in the population genomics and molecular epidemiology of pathogenic bacteria. Currently, his research portfolio encompasses a wide variety of activities including the development new antibiotics, tracking bacterial pathogens using next generation sequencing data, and the development of bioinformatics infrastructures.  With Nick Loman and Simon Thompson (both of Birmingham University, UK) he has led the design and implementation of the cloud infrastructure at the heart of the £8.4M MRC CLIMB project. The system is distributed over four sites (hosted at Cardiff University, Swansea University, the University of Warwick and the University of Birmingham) and is currently running OpenStack Kilo. )*

* **Stig Telfer** *(Stig's career includes research and development in HPC and SDN, and using both technologies in a cloud compute environment, starting with OpenStack Havana. Stig works as a freelance OpenStack HPC consultant with Cambridge University's Research Computing Services group.)*

SurCloud OpenStack HPC Based On Dual-ports NVMe SSD
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack all-in-one appliance is designed for HPC. SurCloud OpenStack HPC integrates all software and hardware in a half rack, with extreme performance, HA, highest data durability and good scalability at inexpensive costs. SurCloud HPC leverages latest hardware technology (such as dual-port NVMe SSD), plus optimized architecture (such as extremely short I/O path) and optimized software to enable the best performance of hardware (2M+ IOPS, few microseconds latency). SurCloud HPC totally eliminates single points of failure by 100% redundancy design. This design plus automatically fail-over for all modules & services guarantees high availability. SurCloud HPC leverages ZFS RAID-Z3 to reach 99.999999999% data durability with lowest cost. SurCloud HPC optimizes configuration of both hardware and software to ensure no single dollar is wasted. The standard configuration which is good for a couple of thousands VMs is less than $300K. It also reserves enough space for future scale-out.


* **Alex Wang** *(Alex is an excellent innovator. He was nominated as one of the Top 10 Youth Scientist by the Chinese central government in 2010. He was also recognized as one of the distinguished engineers (the only one coming from software and Internet industry) in China in 2014. Alex began to innovate on cloud storage systems in 2011. His first project SurDoc won the “Cloud Storage Excellence Award” by US Cloud Computing magazine in 2013, got 10M+ users worldwide within 2 years upon its service launched. Alex is founder of a Silicon Valley company SurCloud. He is also 1st inventor of 100+ patents worldwide.    )*
