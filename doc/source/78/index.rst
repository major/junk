Project Updates
===============

Cinder Project Update
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During Newton, the Cinder team has made progress in various areas.  In this session, we will provide an update on what has been accomplished in Newton and also discuss what may be coming in the Ocata release.


* **Xing Yang** *(Xing is a senior consultant technologist from the Office of the Global CTO at EMC. She has expertise in storage, data protection, disaster recovery, cloud and virtualization technologies. Xing has been an OpenStack contributor since the Grizzly release and is a core member in Cinder and Manila.)*

* **Sean McGinnis** *(Sean McGinnis is a software architect and project lead with the Dell Storage group. He focuses on enabling integration of Dell Storage capabilities with external systems to streamline the ease of use and availability of the various Dell storage offerings to meet application needs.)*

* **Jay Bryant** *(Jay has worked for IBM since 2001 on Linux virtualization, supercomputing and storage related initiatives.  Jay started working with OpenStack during the Grizzly release and has been focussed on Cinder since Havana.  As the Cinder Subject Matter Expert for IBM's Cloud Division, Jay serves as the liason between the OpenStack Community and IBM's internal storage software development teams.  Jay has also been a member of Cinder's core reviewer team since the Icehouse release and serves Cinder's Oslo liaison. )*

Levelling the playing field: Baremetal Console
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you using Ironic in production?  Do you find troubleshooting a baremetal instance without a console limiting? Unlike VMs, Ironic has no console support in Horizon. In this session, we will focus on how to facilitate troubleshooting baremetal instances by exposing console support. This talk aims to illustrate the following: * The issue we are trying to solve * Our proposal/work: What is necessary if you want to use Ironic in production? How Ironic serial console works? * How does this currently work for Nova? Why do we want to leverage that for Ironic? * How we managed to architect a solution for the graphical console keeping a minimal vertical footprint through horizontal scaling and leveraging docker to secure client sessions * We will showcase how the console works live in production with some demonstrations! * What, except for the console is necessary if you want to use Ironic in production? Graphic console, multi-tenant network, volume, ... 


* **Yuiko Mori** *(Yuiko Takada began working on OpenStack "Havana" in 2013. She is Ironic Inspector core developer and also working for Ironic.)*

* **Hironori Shiina** *(Hironori Shiina has been working for Fujitsu for 10 years. He developed middleware for mission critical systems on Linux. Currently, he belongs to OpenStack development team in Fujitsu.)*

* **Wajdi Al-Hawari** *(Wajdi is a Full Stack Developer for Internap working out of Montreal. Passionate about test driven development and continuous integration, he is mainly responsible for the architecture and development of server and network automation solutions for Internap's Baremetal public cloud solution. When Wajdi isn't developing solutions for the cloud, he is usually a human jungle gym for his two children, enjoys running and dabbling with his guitar. )*

Ciao: A modern, secure, scalable and performant compute service for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Cloud Integrated Advanced Orchestration (ciao) project brings a fresh perspective to cloud software stacks. It rethinks cloud orchestration and networking by focusing on modern requirements, notably security, scalability, simplicity, workload agnosticism and continuous deployment. Ciao is implemented in Go and provides a highly performant cloud orchestration layer that is fully TLS based, requires minimal configuration and is easily updateable. Ciao relies on several OpenStack components, including Keystone, Glance, Cinder and Swift. In ciao, containers, VMs and bare metal host L2 interconnected, equal citizen user workloads, providing a scalable elastic cloud. This presentation describes the architectural innovations in the areas of scheduling, networking and component interconnection that allow ciao to meet the requirements of the modern cloud. It identifies where ciao’s implementation differs from OpenStack and explains how ciao integrates with several OpenStack components.


* **Samuel Ortiz** *(I'm a software Engineer at the Intel Open-source Technology Center (OTC) where I'm currently working on the ciao project.)*

Present and Future of OpenStack Ironic Drivers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Drivers are core components of Ironic. They define how Ironic interacts with hardware and ensure that different types of hardware can be represented by a consistent API. At the time of writing, Ironic has 24 production drivers in its source tree.It has become apparent that the way we compose and name drivers does not scale well. In the Newton release cycle we decided to completely rethink the notion of drivers in Ironic. This talk begins with the way drivers used to work in Ironic before the Newton cycle. It will then cover challenges we've faced with this schema. Finally, I will present the ideas and the results of the work known as Ironic driver composition reform. I will show how this change affects all of the interested parties: end users, operators and driver developers. I will also briefly cover the results of an effort to provide a 3rd party CI for all in-tree drivers.


* **Dmitry Tantsur** *(Ironic core developer, Ironic Inspector project founder. Bass player in leasure time.)*

What's new in OpenStack File Share Services (Manila)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Manila provides multi-tenant file-share services to OpenStack. It can work with default storage types, or through its driver model, with a range of storage backends. The ability to provide file-shares to serve existing applications, containers, DevOps environments, departmental shares, and other use cases broadens OpenStack’s storage capabilities.  As a result, with OpenStack rolling out in high-profile enterprises, Manila is rapidly gaining momentum with new features. Over the last cycle, the community has worked on a number of useful enhancements, including an updated installer for Fuel. Topics covered will include: Share Groups for performing tasks on groups of file shares Enhanced snapshot restoration capabilities Share migration and retyping capabilities Access Groups for shares to specify the same access policies to multiple shares Deployment using the Fuel plugin for Manila. and more.  Multiple demos will be included!


* **Akshai Parthasarathy** *(Akshai Parthasarathy is a Technical Marketing Engineer at NetApp, working on all things OpenStack and cloud computing. He has over 7 years of experience in the technology industry, having previously worked at Amazon Web Services and Dell. Prior to that, Akshai obtained his Bachelors (with Highest Honor) and Masters from the School of Electrical and Computer Engineering at Georgia Institute of Technology. )*

* **Gregory Elkinbard** *(Gregory Elkinbard is Sr. Technical Director at Mirantis, where he is responsible for building on-demand IaaS and PaaS layers for public and private clouds at marquis Fortune 1000 and late stage venture-funded customers, with a focus on the intersection of cloud and distributed data storage strategies.)*

The Meaning of Life: An Ironic Story of a Bare Metal Node
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In the OpenStack world, where automation is key, the instantiation of the underlying hardware nodes becomes critical to the operation and growth of the cloud environment. Enter Project Ironic. The goal of Project Ironic is to perform full life cycle management of these supporting infrastructure nodes, from enrollment to deployment to decommissioning, taking care of everything along the way. This talk will discuss the various states that these nodes will transition through, what they mean and what improvements we can look for in the the future in regards to state reporting. Once we have covered the project from a theoretical perspective, we will transition into how Project Ironic is used in practice today. We'll look at what happens behind the scenes when there's a request to provision a node including interactions with other OpenStack projects such as Neutron and Glance. The talk will conclude covering some of the more common issues that can occur and how to troubleshoot them.


* **Raviv Bar-Tal** *(Raviv has multiple years of experience in enterprise environments and complex hardware solutions, primarily in the telecom industry. While working in this industry, Raviv witnessed the rise of enterprise virtualization and experienced the growth and evolution of running Linux on a single virtual machine to what we have today, full scale clouds containing thousands of virtual machines running many different operating systems.Today Raviv works as a Quality Engineer at RedHat with a special focus on the Ironic project.  Raviv is involved in the verification of new Request For Enhancements, executing automated as well as manual testing of Ironic features and functionality.)*

* **Darin Sorrentino** *(Darin has over 18 years of IT experience, wearing various hats over the years ranging from application development to database administrator to system administrator to enterprise architect.  It is his experience in such broad categories that allows him to help others in understanding and utilizing cloud platforms such as OpenStack to effectively deliver solutions that make sense.  Darin is currently working as an OpenStack Senior Solutions Architect on the Red Hat OpenStack Tiger Team assisting in Proof of Concept deployments, technical deep dives and assistance with problem resolution.  Prior to working at Red Hat, Darin's previous OpenStack experience was helping a value added reseller (VAR) devise a cloud strategy to deliver for government agencies and prior to that, working for Mirantis.)*

OpenStack is not orphan any more: scheduling and networking among OpenStacks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Tricircle provides an OpenStack APIs gateway and networking automation to allow multiple OpenStack instances runnning in one site or multiple sites or in hybrid cloud to act as a single OpenStack cloud.  With the help of the Tricircle, OpenStack instance is no need run as an orphan in your large scale or multisite cloud. There are exciting features developed in Newton release like: dynamic OpenStack scheduling and binding with the tenant when there are multiple bottom OpenStack instances under the Tricircle; strech the L2 network from one OpenStack instance to another one so that the tenant's virtual machines can be plugged into same L2 network, this is a quite critical feature in cloud capacity expansion if one OpenStack instance reaches the capacity limit, and also benefit the tenant level east-west traffic through L3 networking across multiple OpenStack instances. This session will provides details of the design and implementation of such innovative features.


* **Chaoyi Huang** *(Principal architect of Huawei FusionSphere (OpenStack based Cloud OS).  The initial and current PTL of the Tricircle project ( https://github.com/openstack/tricircle ) for distributed multi-site cloud and  large scale cloud. The initial and current PTL and key committer of OPNFV multisite project: https://wiki.opnfv.org/multisite The initiator, founder and core reviewer of OpenStack Kingbird project ( https://launchpad.net/kingbird, https://github.com/openstack/kingbird ) The key system architect for one tier 1 Europe operator's cloud, which is OpenStack based, covers up to multiple geographically distributed data centers, and can also integrate AWS into the cloud. He has worked in software area over 10 years from in-memory customized database to cloud computing.)*

* **Shinobu Kinjo** *(Current Working At Red Hat as Support Engineer for the OpenStack, the Ceph Storage Cluster Before Working At OIST as IT pricinple. Fields: HPC Storage Filesystem: Lustre, GPFS, Ceph, NFS Networking: Ethernet(L4, L3, L2, L1), IB Core System (DNS, Authenticatin, Email, Etc) Automation System such a KVM, Puppet, Cobbler VoIP infrastructure SAN L2 VPN infrastructure Programming for Computation C++, C Other IT Facility such a Data Centre, Etc Pretty much Everything!!)*

* **Zhiyuan Cai** *(Join Huawei in April 2014. Mainly focus on Huawei public cloud maintenance and operations, and OpenStack community contribution, used to work in project like Neutron, Keystone and OpenStack Client. Now pay more effort on Tricircle, which is the project for cascading solution, and Kingbird, a newly started project for multi-site management. Recently working with engineers from NEC together to run a demo which utilizes the cascading solution to deploy web services with a database cluster backend across China and Japan.)*

Security groups & Firewalls logging: How we capture and store security events in Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will introduce a logging feature for security groups and firewalls [1][2] and show its benefit to operator and tenant. Today, logging becomes critical to ensure the enterprise has visibility into traffic entering and leaving the environment. Tracking DROP events is the good way to identify threat, logging ACCEPT events gives greater insight into malicious traffic. This session introduces a mechanism [2] to capture and store security events (ACCEPT/DROP) related to security groups and firewalls when they occur. We can collect security events for a specific VM, tenant, security group or firewall via Rest API or OSC. The log-data can be consumed by Monasca service or forwarded to external system to: Detect illegal communication Detect attack patterns and alert abnormal activities This feature also exposes a way to help tenant make sure security rules work as expected. This session includes a demo of the work in progress. [1] https://goo.gl/Cs7Koo [2] https://goo.gl/f2k52l


* **Phuong An Nguyen** *(Nguyen Phuong An software engineer at Fujitsu Limited.  I'm an openstack-neutron developer. Currently, I'm focus on developing new networking features (e.g:  security group logging).)*

* **Xuan Hoang Cao** *(Cao Xuan Hoang Software engineer at Fujitsu Vietnam Limited. He is in-charging to support and develop new features to apply to OpenStack components, especially in Neutron, Nova and Ironic.)*

* **Yushiro FURUKAWA** *(Yushiro FURUKAWA Software Engineer, Fujitsu Limited. He has been working in Neutron and Neutron-FWaaS since Kilo development cycle. Currently, he focuses on development of neutron plugin(ML2), Neutron, Neutron-FWaaS and Ironic.)*

Mechanism Driver – Ironic deploying on VXLAN supported
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic project is young but important and fast-growing nowadays. Supporting VXLAN isolated tenant networks automated booting Baremetal server is the competitive point of all vendors. There are blueprints that support isolation tenant networks for above issue in Ironic side and Nova side [1] [2]. In Neutron side, the solution is based on Mechanism Driver – that is in possession of each vendor. I would like to propose Mechanism Driver with VXLAN isolated tenant network supported. The Mechanism Driver work with HW switch relied on OVSDB and JSON RPC communication. The Mechanism Driver acts as the OVSDB-client to remotely configure the OVSDB then builds networks on hardware (HW) Switch [3].   [1]: https://goo.gl/lCcd1z [2]: https://goo.gl/KpOvBf  [3]: https://goo.gl/LBCuoM


* **tu ha** *(Company: Fujitsu Vietnam Limited Position: Software engineer Openstack registration: Jan 2016  )*

* **Xuan Hoang Cao** *(Cao Xuan Hoang Software engineer at Fujitsu Vietnam Limited. He is in-charging to support and develop new features to apply to OpenStack components, especially in Neutron, Nova and Ironic.)*

* **Isao Watanabe** *(He is a Software Development Engineer of Fujitsu Limited. Mayjor active in Neutron and openstack-infra. He build the Fujitsu 3rd party CI for Cinder, Ironic and Neutron. He also is the main maintainer of the Fujitsu CI systems.)*

Monasca: One year later
~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Monasca was accepted into the OpenStack Big Tent about a year ago and has come a long way and is under rapid development. It is the OpenStack Monitoring as a Service (MONaaS) project with a focus on metrics and log management. This session will provide an update and overview on the current state of the project including the following. Exciting new features that have been added: Deterministic alarms Non-periodic notifications Alarms on logs, correlation of metrics and logs OVS vSwitch monitoring Major new areas of development such as: Monasca Log API Monasca Transform and Aggregation Engine Monasca Analytics. Updates on the project including: Integrations with other OpenStack projects including Heat, Ceilometer and Congress. Integrations with third-party projects such as Grafana, ELK and others. Community involvement and ecosystem. Active deployments and companies/organizations that are using Monasca in their distributions and products. What's next for Monasca?


* **Roland Hochmuth** *(Roland Hochmuth is a software architect, developer and evangelist at Hewlett Packard Enterprise and the Project Technical Lead (PTL) for the open-source OpenStack Monitoring-as-a-Service Monasca project. His current focus is on architecture, development and helping to lead the team that develops a highly performant, scalable and reliable turn-key monitoring and logging solution that leverages the industries newest trends and innovations around near real-time stream processing systems, analytics and big data, such as Apache Kafka, Apache Storm, Apache Spark, HPE Vertica and others. Prior to working on Monasca, he was an architect, developer and tech lead on the metrics processing pipeline for HP's Public Cloud. From roughly 2009-2012, he was an architect and tech lead on WebOS on the PC. From 2002-2009 he was a founder, architect, developer and tech lead on the highly successful remote desktop visualization product Remote Graphics Software (RGS), which served as the foundation for launching two products within HP, HP Workstation Blades and HP Halo Videoconferencing. In the early 2000's he worked on HP's e-utilica solution, which was a predecessor for cloud computing. From 1990-2000, he worked on 3-D graphics geometry processing, rasterization, and NURBS surface tessellation algorithms. Roland has experience in a number of software disciplines and domains ranging from 3-D computer graphics, remote desktop visualization, cloud computing and monitoring. He has a history of innovation and leading successful products and teams. He has around sixty to seventy patents and patent applications and frequently presents at conferences. In his free time he studies statistics and Deep Learning.)*

* **Shinya Kawabata** *(I have started openstack contribution activity in September 2015. My most interested area is Monasca and especially UI. Recently I'm working to support cassandra as metric data store.)*

* **Witek Bedyk** *(Witek Bedyk is senior software developer at Fujitsu EST for cloud management software. His current focus is on OpenStack Monitoring Service (Monasca).)*

Keystone Domains - Why would I use them and how?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Domains construct is an important component in supporting multiplegroups of users in an OpenStack deployment. Domains provide the ability to define a source of authentication as well logically contain all of the projects andusers for a discrete group or organization. This presentation will provide a basic tutorial of the Domains function and the nuances of configuring domains via the Horizon web interface.


* **Tim Cuddy** *(Sr. Product Manager, Hewlett Packard Enterprise Cloud Business Unit Sr. Product Manager, Cisco Systems, Inc. Sales and Sales Support, Apple Computer IT Network Planning, Sprint)*

Journey To FPGA - hardware accelerators orchestration in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nowadays we can observe significant growth of hardware accelerators usage to offload certain types of workloads from CPU. There are number of different hardware available today: GPU, FPGA based accelerators or even specialized ones like Googles' TPU. In this presentation we would like to focus on FPGA. We will discuss what are the use cases, how currently FPGA accelerators are used in OpenStack. Dynamic nature of FPGA leads to new challenges with resource management and scheduling. There are couple of initiatives to provide FPGA accelerators in projects like Nova and Nomad which we would like to present.


* **Zhipeng Huang** *(Zhipeng Huang is currently a standard manager and open source community operator for Huawei. His activities mainly involves open source projects like OPNFV, OpenStack, Open Container Project, OpenDaylight and so forth.)*

* **Roman Dobosz** *(Known as  a person with both feet on the ground, with a background of several different angles of software development – from heterogeneous large MES system to mobile solution, Roman is Software Engineer in Software Defined Infrastructure team at Intel. In OpenStack world he is relatively new, and his main activities are connected with work within the Win The Enterprise group, which main focus is to bring the OpenStack to the Enterprise around HA topics. Recently, he is involved in enabling non trivial resources like FPGA into OpenStack.)*

* **Fei Chen** *(Fei Chen is an OpenStack developer from IBM. He got this Ph.D on the direction of computer architecture, working on virtualization technology, heterogeneous computing and cloud technology. In recent years he focuses on the integration of FPGA, GPU heterogeneous computation and cloud infrastructure. He now is the technical lead of the acceleration service on IBM SuperVessel Cloud.)*

Centralized Quota Management with Kingbird
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Multiple regions. Centralized Keystone. Fragmented quota management. Sounds familiar? Currently quotas are defined on a per-region basis. The fact that quotas are split accross Nova, Neutron and Cinder complicates things even further. All this makes it hard for operators to provide flexible resource allocation for users across regions. So what can we do about it? In this session we will show our approach to solving quota management in multiple regions, which is based on using the existing OpenStack APIs and doesn't require any modification of the existing compute, network and storage services. We will also introduce a new OpenStack project "Kingbird" that provides implementation of our ideas.


* **Dimitri Mazmanov** *(Dimitri is a systems engineer in Ericsson specializing on the topics of cloud management and orchestration. He has a degree in Electrical Engineering and Distributed Systems. Dimitri works on the NFV related topics in OpenStack. He's a core comitter in the OPNFV Multisite project and core developer in OpenStack Kingbird. He's not a terrible musician, and loves playing drums whenever he's got time for it.)*

* **Ashish Singh** *(Ashish is a software engineer working for Ericsson. He's a core developer in the Kingbird project, working on the use cases of multisite OpenStack deployments. He has worked on deploying private cloud based on openstack grizzly. Worked on automated VM migartion across hypervisors and across clouds(AWS => OS & viceversa), p2v, v2v, v2cloud migrations.)*

OpenStack Dragonflow - Overview and Updates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Dragonflow is a "Big Tent" project, implementing Neutron in a fully distributed SDN-based architecture.  We are heavily using OpenFlow and OVS. In this session, we will give a short overview of Dragonflow and share some updates for upcoming Newton release. We will also share our plans for IPv6 and for Containers networking


* **Eshed Gal-Or** *(I'm an avid technologist, innovation leader and problem solver, with 20 years of R&D experience in diverse domains, such as networking, virtualization, telecom, BSS, IT infrastructure, cloud and security. As an architect, I'm practiced at setting and realizing technology vision and roadmap in highly complex global organizations, while crossing between business/product management and technical research/development teams. I currently manage a team of open source developers and PTLs in Huawei, focusing mainly on 3 OpenStack Big Tent projects: Dragonflow, Smaug and Kuryr  )*

Cluster Run: Resource Pool Operations Made Easy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When using an OpenStack Cloud, users often need an extensible, flexible tool to manage resources (such as Nova servers, Heat stacks, Bare-metal servers, or Containers that comprise an application workload) as collections rather than individually. Operators often deploy telemetry toolkits to monitor the status of their resource pools. When certain pre-defined alarms triggered, operations are performed automatically or manually to remediate such situations. Operations concerning a cluster (group of resources) include the creation and updating of nova servers, provisioning or upgrading of software on specific nodes, detection and recovery of node failures, resizing the cluster based on certain measurements etc. The Senlin service fills this gap by providing a framework and APIs for users to execute custom actions on subsets of nodes or the whole cluster--like running operations by specific node types, executing shell scripts on specific nodes, or even running Ansible playbooks directly.


* **Xinhui Li** *(Xinhui Li is a Staff Engineer, development lead at VMware and a core of Senlin project. Her work focuses on design and optimization of distributed systems, mostly in the Cloud computing and big data fields. She has 13 international patents, published 3 technical documents, and 5 papers on international PIC top/target academy journal and conferences.  )*

* **Qiming Teng** *(Qiming Teng is a researcher working at the Cloud Infrastructure and Service department, IBM China Research Lab (CRL). His research interests include system software, virtualization, cloud, Java resource management, performance profiling tools. Starting from early 2013, Qiming has been researching topics related to high availability, auto-scaling of virtual machines, applications in a cloud environment. His focus is on the Heat and the Senlin project in the OpenStack community. Before Joining IBM, Qiming Teng received a Ph.D. in computer science from Peking University in 2006.)*

* **Mark Voelker** *(Mark Voelker is currently the OpenStack Architect with VMware, but generally prefers to think of himself as a breadth-first technologist. In past lives he has worked as a software engineer, engineering manager, and architect designing web applications, automation systems, mobile apps, traffic generators, and more weasely hacks than he can shake a stick at. He also helped design and support the infrastructure supporting his software, including LANs, award-winning SANs, load balancing, and servers. Mark currently works on enterprise cloud architecture, software defined networking, and distributed systems. He's been enamoured of Open Source approximately since his first exposure to the Internet, helped found Cisco's Open Source Conference and was part of the OpenStack@Cisco team before joining VMware in 2014 where he leads architecture for the VMware Integrated OpenStack R&D team. Mark has been active in the OpenStack community since 2011 when he attended the Diablo Design Summit and has been an attendee and/or speaker at every Summit since.  He is OpenStack Foundation member #54 and owns enough OpenStack t-shirts that he can go long stretches without doing laundry.  Mark co-founded the Triangle OpenStack Meetup in Research Triangle Park, NC in 2013 and currently leads the group's 830+ members.  As an application developer and infrastructure afficionado, Mark is concerned with interoperability of cloud platforms and is the co-chair of the DefCore Committee.  He is also a former core reviewer on the Puppet OpenStack project.  He has a habit of including vacation photos and Douglas Adams quotes in his presentations and his time can generally be bought with a sufficient quantity of doughnuts. When not holed up within the trail-photo covered walls of his workspace at home near Research Triangle Park, North Carolina, Mark can be found hiking, camping, backpacking, or making sawdust with extreme prejudice. Mark is a proud alumni of the Park Scholarships at NC State University and currently serves as a Regional Selection Leader for the scholarship. You can also find him on Twitter, LinkedIn, SlideShare, or at his occasional blog.)*

Searchlight in Horizon: Finally a fast web UI for managing your cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this talk we'll present the speedy web features now available by using the new Searchlight-UI Horizon plugin. Learn about this exciting new feature and see how easy it is to deploy! Searchlight is a cloud-resource indexing service which, coupled with new work in Horizon, gives users a simple, powerful, and pluggable interface for quickly navigating their resources and workflows. When using an indexed search, many of the paradigms of categorical navigation fade away, and new opportunities, like user-defined views and cross-resource monitoring, become possible. We'll look at use cases that are massively improved, provide some tips on how to quickly master search techniques, and demonstrate how to build your own library of searches so you can build views specific to your workflow


* **Matt Borland** *(Matt Borland is a long-time web developer and currently is on the Horizon team, working at Hewlett Packard Enterprise.)*

* **Travis Tripp** *(Travis has served as Searchlight PTL and core reviewer, a Horizon core reviewer, OpenStack User Experience core reviewer, and an architect for HP Helion where he is currently focusing on improving the OpenStack user experience by leveraging technologies such as AngularJS and Elasticsearch while working closely with the community on new UX designs and interaction patterns. He's led multiple cloud software products intermingling between lead product architect and lead developer roles. He's presented to Gartner, Forester, and IDC, has presented at multiple OpenStack summits, was a DevOps panelist, and has contributed to the OASIS TOSCA specification. In his free time he loves hiking and climbing mountains in his home state of Colorado.)*

* **Tyr Johanson** *(Tyr has been developing applications at HP/HPE for over sixteen years and is a contributor to both Horizon and Searchlight-UI.)*

OpenStack Requirements  : What we are doing, what to expect and whats next
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Syncing of requirements for OpenStack projects is a very important task since the way python package installation with pip works, this means that if you get lucky you'll end up with a working system. If you don't you can easily break all of OpenStack on a requirements update. Global requirements gives us a single place where we can evaluate these things so that we can make a global decision for OpenStack on the suitability of the library. The requirements team is trying hard to fulfil the REQUIREMENTS of managed projects with validating different requirements updates, auto-update of upper constraints for requirements to name a few tasks.


* **Swapnil Kulkarni** *(I work at Red Hat as Senior Software Engineer - OpenStack and Containers. I contribute to many OpenStack projects. On the containers side, I am a Core Reviewer in OpenStack Kolla team working on containerizing OpenStack services for deployment and I am also Core Reviewer in OpenStack Requirements team taking care of requirements for all OpenStack projects. I also contribute to different modules in TripleO project. I write at http://blog.coolsvap.net  and you can find my profile at http://coolsvap.net/profile )*

* **Davanum Srinivas** *(Davanum Srinivas (a.k.a Dims) is a member of the Mirantis Community Engineering team working on OpenStack Nova, Oslo, KeyStone, Magnum and related projects. Dims is actively helping with Requirements and ReleaseTeams in OpenStack as well. At Mirantis, he leads a team working on improving KeyStone project and infrastructure components like RabbitMQ, MySQL Galera through Oslo projects like Oslo.Messaging and Oslo.DB. He previously worked on IBM PureApplication product as an Architect and lead a team working on Web Services support in WebSphere. Dims has a long track record in open source projects including Apache Cocoon, Axis2, Geronimo at the Apache Software foundation and co-founded WSO2 based on the open source business model.)*

BGP dynamic routing within OpenStack environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

BGP Dynamic routing was introduced as a Neutron service plugin in M release. It support advertising tenant prefix and FloatingIP host routes to external devices, such as Router, L3 Switch, Router reflactor and vRouter. In N release, it had been split out from Neutron as a subproject under Neutron Staduim.This topic will introduce how to use it within OpenStack.1. How to deploy it with devstack, and how to test in generally.2. How to deploy and meet your for different requirments in production deployment.3. Introduce the roadmap of BGP Dynamic routing project.- Split out the code and setup a new project in N release - Complete the more functions which used in project.- Need access another powerful driver for implementing more BGP functions.4. Divergent thinkingSupporting for mutil-AS in internal Openstack, the internal tenant could exchange their self routes with other tenants or external devices. What should we do next?  


* **hanzhang shi** *(Expertise in Networking domain and active contributor/follower of Openstack Neutron)*

The Challenge and Solution for Glance Image Copy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Cloud senario, users uses the same image or images with particular content for the most of the time, sharing and backup will be a common user demand, this needs Glance to be able to provide the ability of copy images. From v1 API to v2 API, Glance have provided this kind of ability in various ways: copy-from, location-add and task-import, all of them have problems more or less, which lead to very bad user experiance of image copy, and Glance service could be unusable in the worst case senario. The Glance team is already aware about this and is trying to provide better functionality through refactor of the provided functionalities. This topic will introduce and discuss how image copy can be done with the current Glance implementation and what are the limitations and cons for each method, what will be modified to provide better user experiences.


* **Xiyuan Wang** *(Xiyuan Wang joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Zaqar, Glance and Cinder. He is one of the zaqar core members.)*

Spanning your overlay network across clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the up-take of Hybrid Cloud, spanning the network across clouds is becoming a necessity. However, this capability is as-of-yet not supported by the cloud infrastructure. Moreover, OpenStack networking is designed as a “single network domain”, lacking the model to define a network that crosses the cloud boundary. In a Hybrid Cloud environment, you want to be able to define a virtual network that connects your virtual machines, regardless of their network domain. In this session, we will present a solution and reference design that enables OpenStack to connect multiple remote networks, allowing users to establish Virtual Network connections between VMs across different clouds.    


* **Ofer Ben-Yacov** *(I'm a long-time veteran of the Networking industry with over 20 years of experience in development, deployment and architecture design of datapath and virtual networking. I am currently working for Huawei as a Cloud Network Researcher and developer. I have been committing to OpenStack for 6 months, mainly around Neutron and OVS.  )*

How Shadow Users is powering Federation in Keystone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Find out how Keystone is unifying identities and extending Federation to make Federated identities a first class citizen! Shadow Users is a new feature that unifies identities (LDAP, Federation…) and is powering Federation. Thus, all of Keystone identities are now stored in the database, allowing for referential integrity and improved performance, as well facilitating account linking. Meaning, that the new identity model allows a user to be associated to an LDAP identity and a Federated identity for example. And there is even more! Because of Shadow Users, Federated identities are now treated like any other identity and therefore, can receive concrete role assignments. This opens the door to a whole slew of features around Federation, such as automatically bootstrapping your users and projects through Federation. This talk will focus on the new features around unified identity and Federation, as well as upcoming features that will take Federated identities to the next level.


* **Ronald De Rose** *(Ron is an experienced software engineer at Intel, where much of his time have been focused on Identity & Access Management (IAM).  He is passionate about open-source software and has been an active contributor to the Keystone project.  Ron lives with his family in Arizona and enjoys playing basketball and tennis.)*

What's New with OpenStack Trove in Newton, What's On Deck for Ocata
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Trove, the Database as a Service project for OpenStack, has been evolving rapidly over the last several cycles and contains many new features in Newton. Work during the Newton cycle aimed at improving UX for both the operator and the end-user, expanding the capabilities across datastores and adding more availability and scalability support to databases. These features will be discussed in detail with particular attention to how the improvements address enterprise use cases. The presentation will conclude with a discussion of what’s on the roadmap for Ocata.


* **Doug Shelley** *(VP, Product Development at Tesora. )*

Cross Release Themes: Update
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalability, Resiliency, Modularity, Interoperability, Manageability, User Experience and Security - these are the themes that the OpenStack community is using to help guide the project teams as they deliver on the roadmap. In this session members of the Product Working Group will discuss how these themes are defined and used. And, more importantly give you an opportunity to provide feedback on the areas that you think are most important for the teams to focus on. 


* **Pete Chadwick** *(Pete Chadwick is senior product manager of Cloud Infrastructure solutions for SUSE. Chadwick has more than 20 years of experience at global technology organizations such as IBM, US Robotics, 3Com and Novell. At SUSE, his responsibilities include comprehensive market and business analysis required to deliver go-to-market strategies for one of SUSE’s priority business areas – cloud. Chadwick is responsible for bringing SUSE Linux Enterprise Server to Amazon EC2. Most recently he championed the company’s work with and significant contributions to OpenStack, an open source cloud computing project.  He is a member of the OpenStack Product and Enterprise Working Groups and  has presented at the OpenStack Summit and at many industry events including Gartner Data Center, LinuxCon, CloudOpen, Brainshare, SUSEcon, Open Source Business Conference and Cloud Computing Expo. He is a published author including the 2012 Forbes article “Why Cloud Computing Needs To – And Will – Go Open Source”.)*

* **arkady kanevsky** *(Arkady has been a member of OpenStack since Grizzly. He is director of engineering leading a team of developers responsible for development of Dell OpenStack solutions.  Arkady has PhD. in CS from UIUC.  He straddled academic, research, architect, developer, and product owner roles.  Arkady roles included  but not limited to, research publications and Program committee member for various conferences like FAST (https://www.usenix.org/legacy/events/fast11/organizers.html), Chair or board member  of several standard activities, like DAT (http://www.datcollaborative.org),  OpenFabric (https://www.openfabrics.org/index.php) and MPI-RT (http://www.cse.msstate.edu/~yogi/dandass-mpirt-2004.pdf) to product delivery, like EMC Atmos, Dell OpenStack solutions among others.   Arkady is passionate advocate of OpenStack and making its usage easier for users and administrators. He concentrates efforts of his team on extending OpenStack capabilities for enterprise use cases, from automatic deployment, and robustness, to HA, upgrade, extensibility and validation.)*

Chaos and Order: the user experience is king
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

An important aspect of enterprise ready is to enhance the user experience, CLI is the first channel for outside users interacting with OpenStack, that impact the user experience directly. Currently each service has offered thier own CLI application, but the project specific CLIs creates a horrible user experience for those trying to interact with the CLI as one have to continuously switching between different formatting, command structures, capabilities and requires a deep knowledge of which service is responsible for different tasks, this leads to high technical threshold and poor user experience. OpenStackClient project appears on the right path, it provide OpenStack users with a consistent, simple and predictable CLI user experience, reduce the complexity of OpenStack interaction. Topics discussed the issues encountered in OpenStack operation by using project specific CLI, as well as mission of OpenStackClient project, current ecological communities and the future plan.


* **Rui Chen** *(RuiChen is a OpenStack upstream developer team leader at Huawei, he has joined into OpenStack community since the Icehouse release. RuiChen is active contributor in OpenStack development mainly in OpenStackClient, Nova and Congress. Follow RuiChen on his blog, http://kiwik.github.io)*

* **Chen Tang** *(Tang Chen has been a Linux kernel developer since 2012, and mainly worked in memory management, KVM, qemu and libvirt communities. He started to work in OpenStack community since the beginning of 2015, and became a core reviewer of OpenStackClient (python-openstackclient). He is now working on Nova and OpenStackClient development.)*

* **Sheng Liu** *(Devoting to OpenStack community contribution, especially in Ceilometer(renamed to "Telemetry" now) project, Sheng Liu have done well in code commit, code review, community involvement to improve Ceilometer capability, stability, usability, etc. In 2015.9, Sheng Liu has been proposed as a core contributor of Ceilometer project. In the last 2+ years working for Huawei, Sheng Liu have also participate development works of Huawei's FusionShpere OpenStack product, and mainly involved NFV scoped features in Nova, such as Numa instance, SRIOV support.)*

Daisy Distributed System Installer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Daisy is yet another installer like fule, juju etc. Previously, it is a closed source project which is used to deploy closed source openstack vairiations developed by ZTE. A couple of month ago we made it a opensource project to support original openstack distributions. Daisy is designed base upon experience and practice of software which running in the large data center. It will bring a bunch of cool stuff to speed up OpenStack deployment for large clusters.  


* **Zhijiang Hu** *(  Name: Zhijiang HuEmployer: ZTE CorporationPosition: Senior Software EngineerPhone No.: +86-17712888993E-Mail:hu.zhijiang@zte.com.cn, Personal E-mail: huzhijiang@gmail.comAddress: Huashen Rd.6, Yuhuatai District, Nanjing, P.R. ChinaWork Experience:I develop and maintain network stack (TIPC/Corosync) for cluster communication.I develop and maintain quorum disk for Pacemaker baased OpenStack HA scenarios.I am PTL of a opensource OpenStack installer project Daisy(http://www.daisycloud.org/) and Daisy4NFV(https://wiki.opnfv.org/display/PROJ/Daisy4NFV).)*

Kerberos and Health Checks and Bare Metal, Oh My! Updates to OpenStack Sahara in Newton.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Data Processing service (Sahara) has been a part of OpenStack for quite a while. With the development of highly-anticipated features including bare metal cluster provisioning, Sahara is more ready than ever to unlock the promise of truly elastic data processing. We will discuss new features in Newton, including: Bare Metal cluster provisioning with Ironic Clusters security management with Kerberos integration Cluster management improvements including event logging and cluster health checks Streamlined image generation capabilities New approach to integration testing with a specifically designed testing framework


* **Nikita Konovalov** *(Nikita has been working with OpenStack Data Processing (Sahara) from the early days of the project. He has been implementing the initial version of Sahara UI which then has been accepted to main OpenStack Dashboard codebase. He added support for Sahara benchmarking for Rally project and is now responsible for Sahara scale testing activities in Mirantis. Nikita has also been participating in the OpenStack StoryBoard initiative being a core member of the team responsible for backend and SDK development.)*

* **Vitaly Gridnev** *(Vitaly is Software Engineer working with Mirantis. He is a core upstream contributor, Project Technical Lead, and downstream productization for the OpenStack Data processing service (Sahara), which provides Big Data cluster management and Elastic Data Processing in OpenStack. He has contributed to OpenStack since the Juno release.)*

* **Elise Gafford** *(Elise has contributed to the Sahara community since the Juno release, where she is an upstream core reviewer. She authored features such as Manila share integration and EDP job configuration, and is currently working on revisions to Sahara’s image generation capabilities. She works on the Red Hat OpenStack storage team, where she provides agile coaching and productization support in addition to her work on Sahara.See https://www.linkedin.com/in/elise-gafford-3b036336)*

OpenStack Charms: Project Update
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Charms project provides a flexible and scalable way for deploying and operating an OpenStack Cloud, based on operational experience and OpenStack feature enablement since the Essex release of OpenStack. The OpenStack Charms project joined the OpenStack Big Tent during the Newton development cycle. This session will provide an overview of what the OpenStack Charms provide, a retrospective of the last 6 months of development for the OpenStack Charms project, and details on our roadmap for the Octata release cycle.


* **James Page** *(James as been involved in Open Source software since 2000, evangelising and delivering the use of Free and Open Source technologies in a major UK bank. In 2010, James discovered Ubuntu and became involved in both the development of Ubuntu and shortly afterwards OpenStack. James is part of the team responsible for delivering and supporting OpenStack as part of every Ubuntu release and for the Juju Charms for OpenStack, the best way for deploying and managing OpenStack deployments on Ubuntu at any scale.)*

Cinder-Nova API Interactions: The New Century
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nova and Cinder both belong to the core components of OpenStack and they are working and evolving closely together. Since the two modules are tightly coupled today, it highly affects both the interaction between their APIs and the possibilities to further enhance the features they can offer. The two teams started to work together on introducing some changes in order to improve the cooperation between the APIs and the coordination of the developers.During this panel we will discuss the shortcomings of the current architecture and interaction model between the two modules. We will highlight the upcoming changes in the Cinder API that will allow this component to be more standalone, while providing the avenue to introduce new functionality more easily. The panellists will also talk about the challenges in driving the changes between two large projects, and share the experiences of cross-project collaboration.


* **Ildiko Vancsa** *(Ildikó is coordinating the OpenStack related activities within Ericsson and also engaged in the OPNFV community. Beyond this she is a software developer working in the O&M area of cloud development. She has been contributing to OpenStack since November 2013, her main focus area is Ceilometer, but she is contributing to other projects too, like OpenStack Manuals, Nova or Oslo. She joined to the core team of Ceilometer in March 2014. Before Ericsson Ildikó worked for OptXware Research and Development Ltd. focusing on O&M, system management and virtualization areas.)*

* **Matt Riedemann** *(Matt Riedemann has been with IBM for over 10 years.  He started working on build tools and frameworks to spending 5 years working in the Update Manager component of IBM Systems Director. Matt has worked on OpenStack for over 2 years and is part of one of the earliest teams in IBM to be involved with contributing to the OpenStack community.  He has experience with continuous integration/build/packaging systems for OpenStack, is a top contributor to OpenStack from IBM and is a core reviewer in multiple projects. Matt is also the Nova project technical lead (PTL) for the Newton release.)*

* **John Griffith** *(John Griffith, Principal Software Engineer at SolidFire, helped to create the Cinder project in OpenStack.  His primary responsibility at SolidFire is technical contributor to OpenStack and Open Source technologies.  He served as Technical Lead for the Block Storage Project since it's beginning through the Juno release, and also has held an elected seat on the OpenStack Technical Committee on and off over the past four years. John has over fifteen years of engineering experience in both hardware and software engineering.  He’s been an active user and contributor to open source for close to a decade, and has been focused on OpenStack since January of 2011. In addition to his technical contributions, John also spends a lot of his time talking to people who are interested in learning about OpenStack as well as gathering feedback from current users.)*

* **Walter A. Boring IV** *(Walt is a software engineer at Hewlett-Packard currently working in the Management and Solutions Development Unit focusing on storage systems enablement.   He has been working at Hewlett-Packard since 2007.  Since 2012, he has been working on OpenStack for HP enabling several of HP’s storage systems.  He became a core member of the OpenStack Cinder team in 2013 after co-authoring the Fibre Channel protocol support in OpenStack’s Nova and Cinder projects.    He codeveloped the 3PAR iSCSI and FibreChannel drivers for OpenStack Cinder as well as helped develop the Cinder Fibre Channel Zone Manager. Also created the os-brick shared library that's used by Cinder and Nova to manage discovery and removal of volumes from a host as part of the attach and detach process for OpenStack.)*

* **Scott DAngelo** *(Scott DAngelo is a Senior Software engineer at Hewlett-Packard Enterprise who works as a developer on Helion OpenStack Cinder. He is a member of the Cinder core team and works on the core Cinder code, Cinder testing, and Cinder-Nova API interactions. He has been with HP since 2007 and has worked on OpenStack since 2012.)*

Behind the Database: An Inside Look at OpenStack Trove Administration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Trove, the OpenStack Database as a Service offering, supports both relational and non-relational databases, enabling users to administer almost a dozen different types of databases. This session will explore what actually happens when a user issues a Trove create against MongoDB versus MySQL or Couchbase. This talk will highlight: An overview of the administration of different databases with Trove's Database as a Service. A look into what OpenStack Trove does “under the covers”. Challenges encountered with designing Trove compatibility with different databases. The databases we will discuss include both relational and non-relational databases such as Cassandra, Couchbase, and MySQL, all supported by Trove while the Tesora DBaaS Platform runs on Mitaka, Liberty, and Kilo.     


* **Emily Wilson** *(Emily is a QA Engineer at Tesora. She currently lives in Cambridge, Massacchusetts. )*

Freezer: What's new? Plugins and deduplication!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Freezer is the backup and restore solution for OpenStack. All OpenStack deployments are different. Freezer allows you to ensure your data is always ready, no matter the diversity of your environment, thanks to its flexibility to support any kind of storage, application or system.Backup policies sometimes force you to accumulate a big amount of data. Most of your storage ends up being taken by similar backups. How could we help freeing up space by saving only what's necessary? Join us while we present some exciting features we've been working on this cycle to solve these issues.Plugin layers: Adding a new backend storage or compatibility with an application has never been so simple. Your filesystem provides a shiny snapshotting capability? Freezer can now support it very easily. Let's talk about how we implemented this. Deduplication: We will present how we plan on implementing freezer-level deduplication for your backups.


* **Pierre Mathieu** *(OpenSource passionate, Linux fanatic and OpenStack addict. Presently working for HPE, Pierre has been using and loving Linux systems and Open Source for the past ten years. He started focusing on Cloud computing and OpenStack with the Folsom release. He has a strong tendency to want to automate everything. Curently Freezer PTL as well as in charge of the deployment automation of Freezer for HPE products.)*

* **Guillermo Ramirez Garcia** *(Mexican software and systems engineer at HPE, I'm currently living in Galway Ireland where I'm working with the Profressional Services team, my main role is to develop Freezer, a backup and restore tool for OpenStack and Pratai an event driven compute platform for OpenStack)*

Common OpenStack rpm-packaging
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Typical OpenStack software binary distributions consist of binary packages for the particular used distribution. At the Vancouver Summit the idea of joining the forces into a common RPM Packaging for OpenStack project, which is aiming to become a cross-distribution and cross-vendor effort to create common templates for building OpenStack packages for RPM based Linux and OpenStack distributions. RPM Packaging for OpenStack is an cross-distribution and cross-vendor effort and currently has contributions from Mirantis, Red Hat and SUSE. This talk gives an overview about the current project status, gives a glimpse at the tooling that has been developed, shows pitfalls and gives an outlook about the O-cycle goals for the project.


* **Thomas Bechtold** *(Thomas is a OpenStack Manila core team member and Manila's Oslo liaison. He's also one of the initiators of the upstream rpm-packaging group and a core member of the requirements team. At SUSE he works on integrating new OpenStack features into SUSE OpenStack Cloud.)*

* **Dirk Müller** *(Dirk Mueller is a Senior Software Engineer working at SUSE currently focusing on Cloud, OpenStack, SUSE's deployment and OpenStack distribution. He's being developing for and using Linux for more than 15 years and is doing Software packaging, distribution and software development for more than 10 years. Dirk is currently involved in the RPM Packaging for OpenStack project as a PTL and core contributor and has spent recently effort in extending SUSE OpenStack Cloud to other architectures than x86_64.  )*

Vitrage under-the-hood: a window into the inner workings of a Root Cause Analysis (RCA) engine
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Go under-the-hood of OpenStack Vitrage to take a good look into the inner workings of a remarkable RCA engine.Vitrage is a new and official OpenStack project dedicated to Root Cause Analysis. Vitrage receives inputs from numerous data sources, both internal and external to OpenStack, and produces insights into what causes faults. But how does it do all this? This session is the place for anyone interested in getting in on a fascinating ride into the realm of Root Cause Analysis and fault management in OpenStack. We will take you on a tour of the features & architecture of the project, and then dive deep into its algorithmic core. Find out all about our innovative graph representation of the Cloud – the Vitrage Entity Graph – and understand how to populate it from the various data sources. We will discuss and demonstrate how Vitrage efficiently uncovers patterns in this graph, deals with conflicting fault-management policies, and generates RCA reports based on it.


* **Dr. Elisha Rosensweig** *(Dr. Rosensweig received his PhD from UMass Amherst in 2012, which focused on Content Oriented Networks (CON) as part of the Future Internet Architecture (FIA). He then joined CloudBand as a developer, where he worked the CloudBand Management System, a forerunner of NFV Management Platforms. He is now an R&D Director at CloudBand, and a core developer of Vitrage - a newly-minted OpenStack project dedicated to organizing, analyzing and visualizing the Cloud, specifically with a focus on Fault Management and Root Cause Analysis.)*

* **Alexey Weyl** *(Alexey is a senior software engineer in Cloudband Nokia with over 10+ years of experience in software development, in fields ranging from imaging and security to cloud and analytics.  He is currently a core developer of the OpenStack Vitrage project, dedicated to organizing, analyzing and visualizing the OpenStack Cloud, with a current focus on fault management and Root Cause Analysis (RCA).)*

Cloudkitty, the OpenStack component for chargeback and rating in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CloudKitty, the rating and chargeback Open Source component in OpenStack, is part of the Big Tent for a year now. So it is a good time to come join us and learn more about this component and its features. CloudKitty helps cloud providers define rules and charge cloud usages of their users. Using a highly modular rating engine to interface directly with your OpenStack cloud, application or everything else. In this talk we will introduce CloudKitty : A global description of its architecture and capabilities Introduction to built-in plugins (collectors, rating, storage) Focus on the latest features introduced in the Newton cycle. Demonstration of Horizon integration and configuration scenari Description of the roadmap and envisaged features for the Ocata cycle Return of experience from a user of the component CloudKitty is getting integrated by various OpenStack clouds around the world, so why not yours?


* **Christophe Sauthier** *(My Name is Christophe Sauthier, a french guy living in the nice city of Toulouse. Living with my wife and father of 2 beautiful small guys (of course), I am also CEO of a company that I have funded 6 years ago Objectif Libre that only deals with Linux Infrastructure. I have been really involved in the Ubuntu community, being a developper and in various boards, then my life crossed OpenStack... The results being that Objectif Libre became (many times) one of the Top20 contributor and developped a real expertise and lots of services around it.)*

* **Stéphane Albert** *(Hi, my name is Stéphane Albert, a french guy living in Toulouse. I work at Objectif Libre mainly around OpenStack and IT automation. My main task is to bring CloudKitty to life to add reporting and pricing with Ceilometer metrics in OpenStack. My main interests are Python, OpenStack (how surprising ;)), networking and Open Source software. When I'm not at my computer I repair arcade systems and hack on electronics.)*

* **Sergio Colinas** *(Sergio Colinas is a Software Engineer with more than eight years working in the software industry as a developer and architect. During the last two years Sergio has been developing with the NubeliU team different products for Openstack like Nubeliu Rocket Dashboard, NubeliU Showback and Chargeback, NubeliU Monitoring and Alarming. Sergio also collaborate with some official Openstack projects like Ceilometer, Gnocchi, Aodh and Cloudkitty.)*

Through the Looking Glass: Unifying Image Generation in OpenStack Sahara
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Sahara users can now drive image packing, image validation, and clean image provisioning from one human-readable, yaml-based image declaration. This feature may be of interest to operators (who build images) and to developers (who may wish to consider the ideas for reuse.) Many provisioning services in OpenStack spawn their applications from pre-packed images. In plugin-based services like Sahara, the plugin must be responsible for image validation and for logic to spawn a cluster from a clean, OS-only image. However, elements used in traditional OpenStack image generation are not easily usable by the controller services. The OpenStack Sahara team has pushed all image generation logic into the plugin and created tooling (using libguestfs’ python API) to run the same logic before Nova spawn (on an image file) or after (on a running instance.) Now when operators change the human-readable manifest, all three flows are updated and cannot fall out of sync.


* **Elise Gafford** *(Elise has contributed to the Sahara community since the Juno release, where she is an upstream core reviewer. She authored features such as Manila share integration and EDP job configuration, and is currently working on revisions to Sahara’s image generation capabilities. She works on the Red Hat OpenStack storage team, where she provides agile coaching and productization support in addition to her work on Sahara.See https://www.linkedin.com/in/elise-gafford-3b036336)*

* **Luigi Toscano** *(Luigi is a Senior Quality Engineer on the Red Hat OpenStack Quality Engineering team, with focus on Sahara (and previously Trove). Free-as-in-speech-Software enthusiast since last century, FSFE Fellow, he is contributing to different open source communities including KDE. He is also co-maintainer for the Sahara tempest tests, a member of core reviewers team for the "sahara-tests" repository.)*

* **Nikita Konovalov** *(Nikita has been working with OpenStack Data Processing (Sahara) from the early days of the project. He has been implementing the initial version of Sahara UI which then has been accepted to main OpenStack Dashboard codebase. He added support for Sahara benchmarking for Rally project and is now responsible for Sahara scale testing activities in Mirantis. Nikita has also been participating in the OpenStack StoryBoard initiative being a core member of the team responsible for backend and SDK development.)*

Data is Beautiful: Insights into your Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack deployments grow, the Gnocchi community aims to meet increased demands. With Gnocchi v3, the goal is to provide a scalable solution to track and monitor billions of individual datapoints across millions of metrics in a responsive manner. This talk highlights some of the changes made in the past version to improve performance and minimise storage footprint. It also will show some of the benchmark tests conducted over the past months which led to improved results. Additionally, it will provide architectural guidance on how to deploy your Gnocchi service. This talk will features lots of pretty graphs!


* **Gordon Chung** *(Gordon Chung is part of the Canadian Research Centre R&D team within Huawei. His current role involves testing services at scale while relaying feedback to the community in addition to developing new features. Gordon is the former PTL of the OpenStack Telemetry project and is also the co-author of the pyCADF library which is the python implementation of the Cloud Audit Data Federation (CADF) specification. Gordon graduated from Queen's University with a degree in Computer Engineering. In his free time, he coaches youth baseball where he teaches valuable skills such as how to maintain focus after six straight walks and how to walk off getting hit by a pitch.)*

* **Julien Danjou** *(Julien is a Free Software hacker since 1998. He works as a Principal Software Engineer at Red Hat, daily improving OpenStack, a project he has been working on since 2011. He leads the OpenStack Telemetry project as its PTL and contribute to common OpenStack code in Oslo.)*

Ironic Support of Hardware Configuration and Firmware Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Ironic added support for RAID configuration, firmware setting and firmware update as part of the bare metal preparation for deployment.   With these features, users can automate hardware configuration, manage firmware and provision bare metal all within Ironic. Moreover, once ironic configures RAID or updates firmware, users can use the RAID level or firmware version as Nova flavor to place their workloads on a bare metal node with the matching RAID level or firmware version.   This feature can be used to optimize workload placement on bare metal instances. This session will give an overview and demo of these new Ironic capabilities.    


* **Wan-yen Hsu** *(I am a distinguished technolgist at HP Enterprise.  I am working on Ironic, Magnum and container orchestration engines.)*

* **Nisha Agarwal** *(I am an engineer at HPE Enterprise.  I am an active contributor of Ironic project.)*

High Availability for Pets and Hypervisors - State of The Nation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

By now, high availability for the OpenStack control plane is well understood, and to a large extent a solved problem which the community continues to refine. In stark contrast, most solutions for compute node HA (i.e. where VMs are automatically restarted on a different compute node if there is a failure in the hypervisor or its underlying hardware) are still either relatively young, or experimental, or in the design phase.  This is despite the high demand for this feature, which calls into question the older belief held by some that OpenStack should only accommodate "cattle" VMs which have resilience built in at the application layer. Since Tokyo, the OpenStack HA community and Product Working Group have been collaborating towards a unified upstream solution.  In this talk which follows on from the similarly named Austin talk, community members from Intel, NTT and SUSE summarise the status quo of the existing technology, future plans, and how anyone interested can get involved.


* **Adam Spiers** *(Adam Spiers is a Senior Software Engineer at SUSE, focusing on OpenStack, Pacemaker, Chef and Crowbar.  He was architectural lead for the projects to make SUSE OpenStack Cloud capable of deploying highly available control and compute planes, and helped SUSE win the Ruler Of The Stack competitions at the OpenStack summits in Vancouver and Paris.  He set up the #openstack-ha IRC channel and also the weekly HA community IRC meetings, which he currently chairs. Adam has been a passionate supporter and developer of F/OSS since 1995, with a particular interest in automation and orchestration.  For the last 13 years his professional focus has been on Linux-oriented enterprise technologies in the data center. He holds a degree in Mathematics and Computation from Oxford University, and currently lives and works in London, UK. Adam juggles his IT career with a long-running parallel career as a musician, a (less successful) pre-occupation with marathons and triathlons, and occasionally also juggles balls, clubs, and fire.)*

* **Dawid Deja** *(Dawid Deja is a software engineer at Intel, focusing on OpenStack high availability and Pacemaker. For about a year he was working on resolving pet vs cattle problems by providing and testing mechanisms that would be able to automatically resurrect lost instances. Additionally he was involved in detecting noisy neighbours VMs and have general interest in distributed systems topics. Dawid has an engineering degree in IT from Gdańsk University of Technology in Poland, where he currently lives. In his free time, he transforms into board game geek, spending all evening around the table.)*

* **Sampath priyankara** *(Sampath serves as a Software Engineer at NTT SIC. Before he joined NTT in 2013, he engaged in research on wireless sensor networks, embaded system development, and active contributer to ns-2 (The Network Simulator). In NTT, he focuses on openstack based cloud system development and worked with cinder, glance, and nova projects in openstack.)*

The Future of Root Cause Analysis (RCA) through the eyes of OpenStack Vitrage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

What is the future of RCA in OpenStack? Explore project Vitrage and the challenges ahead. Vitrage is a new and official OpenStack project dedicated to root cause analysis (RCA) and deduced insights into the behavior of the Cloud. With the help of a graphical model representing the different relationships between system entities, and a friendly UI, Vitrage hopes to achieve its mission of organizing, analyzing and visualizing a holistic view of the system. While Vitrage has already built strong foundations for delving deep into this realm, there is still much to be done.   In this session, we will sketch out the future of RCA and fault management in OpenStack, as seen from the perspective and experience of the Vitrage Project. Several central issues will be discussed, including role-based views of RCA, alarm aggregation, RCA history, multi-layered RCA and much more. We will survey these challenges, and outline options for addressing them in coming OpenStack releases.


* **Alexey Weyl** *(Alexey is a senior software engineer in Cloudband Nokia with over 10+ years of experience in software development, in fields ranging from imaging and security to cloud and analytics.  He is currently a core developer of the OpenStack Vitrage project, dedicated to organizing, analyzing and visualizing the OpenStack Cloud, with a current focus on fault management and Root Cause Analysis (RCA).)*

* **Ifat Afek** *(Ifat Afek is a System Architect in Nokia CloudBand, and the PTL of Vitrage project - OpenStack RCA service for organizing, analyzing and visualizing OpenStack Alarms and Events. In her role, she has lead the Vitrage effort from day one towards its acceptance into the Big Tent six months later. She now focuses on Vitrage productization and new features for Newton, as well as the design and roadmap for Ocata. She is also involved in OPNFV projects which have relevance to Vitrage (Doctor, PinPoint, VES).)*

Shared Filesystems Management with Manila; a look forward
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Manila is the OpenStack shared filesystem service that was announced September 2013. In January 2015 it was labeled as an officially incubated OpenStack program. Now with the current stable release in Mitaka, Manila is providing the management of file shares (for example, NFS and CIFS) as a core service to OpenStack. Manila currently works with a variety of vendors, including NetApp, Red Hat Storage (GlusterFS), EMC, IBM GPFS, Hitachi, HPE, and on a base Linux NFS server. In this session, we will provide an introduction to the Manila file share service, a description of the logical architecture of Manila and its API structure, examples of use cases, an exploration of whats coming in Newton from share replication, LVM, cephfs, data copy service, and a brief demo using NetApp.


* **Cameron Seader** *(Cameron is currently a Sr. Data Center Strategist with an emphasis on Enterprise Cloud Computing environments; has a diverse background that includes technical sales, solutions architecture, consulting, and engineering. With over a decade of experience at companies such as Hewlett Packard, Micron, Interland (now Web.com) and Idaho Power, he excels in specific areas of data center design, specializing in system solutions on mainframes to high performance clusters. Cameron has also authored and published documentation and guides for several leading products and emerging technology concepts. As a Certified Linux Engineer he is a trusted adviser to SUSE's most strategic customers.)*

* **Anika Suri** *(Anika Suri is a Technical Alliance Manager with NetApp's Global Alliances team, managing the OpenStack Ecosystem. She has over 6 years of experience in the technology industry, having previously worked at Brocade. Prior to that, Anika obtained her Masters from San Jose State University in Computer Engineering (specializing in Networking).)*

Native HTML5 consoles for VMware
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The VMware driver in Nova has support for VNC consoles since the early days. However, cloud operators are facing multiple problems with deployment, scalability and security when providing VNC consoles to OpenStack instances running on the VMware stack. During the last three releases of OpenStack we have made several API changes in Nova which allow using the native protocol for VMware consoles and solve the previous hassles with VNC. In this presentation we will show how to deploy Nova with support for VMware consoles and the advantages compared to VNC.


* **Radoslav Gerganov** *(Radoslav Gerganov is part of the OpenStack team @ VMware. He contributes to the Nova project and maintains the VMware driver there.)*

Masakari 2.0: Upstream Solution for Instance High Availability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Masakari is an open source project to provide Virtual Machine High Availability (VMHA) service for OpenStack. It can recovering the Virtual Machine (VM) s from failure events such as host failure, VM process failure, and provisioning process failure. Masakari 1.0 born on github with task engine and 3 failure monitors. To enhance the operability and extensibility, Masakari 2.0 provides API service for operation and enhanced and extensible recovery engine for customizable recovery patterns. Current Masakari live in the Openstack code namespace and follow the “Openstack way”. Masakari community working with Product Working Group and Openstack HA community for satisfy the requirements of User Story: High Availability for Virtual Machines user. This presentation will cover design and architecture of Masakari 2.0 and live demo of its new features. We will also discuss the use cases, operation strategies and our TODO which includes the collaboration with Mistral, Monasca, and Congress.


* **Sampath priyankara** *(Sampath serves as a Software Engineer at NTT SIC. Before he joined NTT in 2013, he engaged in research on wireless sensor networks, embaded system development, and active contributer to ns-2 (The Network Simulator). In NTT, he focuses on openstack based cloud system development and worked with cinder, glance, and nova projects in openstack.)*

* **Toshikazu Ichikawa** *(Toshikazu Ichikawa is a Senior Manager of Cloud Services, NTT Communications Corporation in Tokyo, Japan. He manages the team in charge of virtual server service development and operation, which consists of ECL2.0 public cloud using OpenStack. Prior to this job, he was a Senior Research Engineer for NTT Software Innovation Center of NTT Corporation in Tokyo, Japan. He led a OpenStack development team in charge of  community upstream activities to develop the cloud infrastructure system using OpenStack for NTT Group companies for two years. He was a Sr. Manager of Japan Business Development and Architecture for Verio Inc., which is a subsidiary of NTT America, in Utah, U.S.A.. He worked for the design and development of public cloud service named cloudn and the business development of managed hosting services from 2011 to 2014. He also has a research engineer backgroud at NTT Sharing Platform Laboratories of NTT Corporation. He worked for the research and development of the system including cloud computing and distributed storage system for 10 years.)*

* **masahito muroi** *(Masahito Muroi is a software enginer in NTT. He is now working as a cloud architect for NTT's public/private cloud, and also working as a core developer of OpenStack Congress Project and Masakari. He's started to join OpenStack Community and develop NTT's cloud with OpenStack since Diablo release.)*

Localize OpenStack better and better
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack I18n project translates OpenStack dashboard, documentation, and so on into various languages. Also, we create and maintain our toolchains. In June 2015, I18n working group became an official project. Then, we have become bigger project. This session covers recent I18n project efforts, such as Stacklytics integration (new metrics "translations"), translation glossary, release notes translation, and dashboard translation check site. Also, this session provides translation tips from some active language teams.


* **Tomoyuki KATO** *(Kato is a service manager at Fujitsu. He is the coordinator of Japanese translation team, and I18n Project Team Lead in Newton cycle. He is contributing OpenStack, mainly I18n and Documentation, for about 3 years.)*

* **Alex Eng** *(None)*

Watcher, the Infrastructure Optimization service for OpenStack: Plans for the O-release and beyond
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Watcher is an open source software package which provides a flexible and scalable resource optimization service for multi-tenant OpenStack-based clouds. Watcher provides a complete optimization loop. This provides a robust framework to realize a wide range of cloud optimization goals, including the reduction of data center operating costs, increased system performance via intelligent virtual machine migration,increased energy efficiency, etc. Watcher provides several out-of-box optimization routines for immediate value-add, but it also supports a pluggable architecture. The overall goal is that OpenStack-based clouds equipped with Watcher will decrease their Total Cost of Ownership (TCO) by way of more efficient use of their infrastructure through targeted optimizations and close-loop automation. 


* **Susanne Balle** *(Susanne is a senior Principal Engineer at Intel working on SDI and Cloud architecture and pathfinding. She has been involved in OpenStack since the Essex OpenStack summit. Her latest focus is on Watcher a service to optimize the Datacenter TCO via Data-analytics and ML models for OpenStack and non-OpenStack Clouds.)*

* **Charlotte Han** *(xxx)*

* **Taylor Peoples** *(Software engineer from IBM working on PowerVC and Watcher.)*

Serve hot objects fast and move iced ones to the fridge! Place your Objects based on it’s metadata
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While object stores are predominantly used for archive, capabilities of multiprotocol access opens up newer use cases which require faster access to unstructured data. In SWIFT, with SwiftonFile open source modules which supports multiprotocol access, the object store sits over different tiers of storage pools that have different characteristics in terms of price/performance. Placing the right object at the right tier requires intelligent tiering of objects across the pools based on the object heat which is a direct reflection of it's access w.r.t time. Additionally, object store characteristic of having user defined metadata with objects can be used for tiering. With this, one can control tiering of objects based on object metadata, irrespective of when the metadata is updated.


* **Smita Raut** *(Smita has been working with IBM for the last five years in storage area. She has been working on Network Attached Storage products on features related to disk and filesystem management, Active Cloud Engine (wan-caching across geos), Information Lifecycle Management and Object protocol for cloud storage. Her current focus is on Object storage protocol for cloud enablement.)*

* **Simon Lorenz** *(Simon Lorenz is an IT Architect in IBM Research and Development Germany. Hejoined IBM Germany in 1993 and worked on productivity and manufacturing qualityimprovements within IBM Disk Drive Manufacturing Management software. Duringinternational assignments, he helped to improve fully automated chip factories in the US andAsia. Simon has held various positions within IBM Research and Development. Since 2009,he has worked on Storage Systems Management software and has been responsible forsubcomponents, such as system health reporting, cluster configuration management, andrecovery. Simon joined the IBM Spectrum Scale (built upon IBM GPFS) development team in 2014 and works on the integration of Openstack with Spectrum Scale.)*

* **Sandeep Patil** *(Sandeep Ramesh Patil works as a storage cloud architect with IBM labs and has over 15 years of extensive product architecture and design experience. Sandeep is IBM Master Inventor with over 150+ US patent filings in the field of storage cloud, security, filesystem, etc and is among the leading inventors in India in the mentioned field. Sandeep has authored numerous articles and paper publications in the filed of computer science with subjects over security, storage clouds, etc and has presented in various international conferences across the world.)*

Manila and Cinder Under the Hood - Discussions & Q/A with a panel of developers.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Come join us for an interactive session with a panel of OpenStack developers who work behind the scenes on OpenStack Cinder and Manila! They will share details about some of the things that they are working on, exciting new developments, and their thoughts on the future of these two projects. They will also answer any questions you may have regarding how things work under the hood. Panelists include Tom Barron, Alex Meade, Rodrigo Barbieri, Goutham Pacha Ravi, and Sumit Kumar.


* **Goutham Pacha Ravi** *(Goutham is an active contributor to OpenStack Block Storage and Shared File Systems projects. Prior to OpenStack, he has worked on several projects involving data protection across storage systems. Aside from his code contributions, Goutham spends a lot of his time building cross project synchronization and advocating for user experience and API stability. He is the API working group liaison for the Shared File Systems project.)*

* **Rodrigo Barbieri** *(Rodrigo is a core reviewer in Manila since Mitaka release, driver developer for Hitachi since Juno release, and a researcher in the field of Fault Tolerance. He is focused on Manila upstream development and has contributed with several new major features, notably Share Migration and Data Service. He started working with OpenStack in Juno release by deploying OpenStack distributions and developing Hitachi storage device drivers for Cinder and Manila projects.    )*

* **Alex Meade** *(Alex has been developing across various projects in OpenStack since the Cactus release in 2011. Alex has a wide breadth of OpenStack experience having been a top commiter in Nova, a core member of Glance, and key operator of the Rackspace Public Cloud. Currently, he focuses on solidifying Cinder and Manila as enterprise ready projects.)*

* **Tom Barron** *(Tom works on the Red Hat OpenStack Platform storage team, contributing primarily to the Manila and Cinder projects.  He started late in the Juno release, working at first on NetApp Cinder drivers, and then moving on to work on core Cinder code, especially the Cinder backup service.  He is now quite involved with Manila and has developed a keen environment in overlaps and common problems between projects. He has worked as a developer and as a deployer of a variety of storage and network technologies over the course of his career and really enjoys the chance to apply this experience working on open source, especially a project with the reach and impact that OpenStack has.)*

* **Sumit  Kumar** *(Sumit earned his bachelor's degree in Computer Engineering from Virginia Tech in May 2015. He then joined NetApp as a Technical Marketing Engineer, and has been involved with OpenStack since. He has been an active participant in various Openstack meetups, and has presented sessions on various topics on Openstack forums. He is very excited about the future and potential of OpenStack, and looks forward to contributing to the OpenStack community.)*

Running virtual machines and system containers on a single compute host effectively
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Since Kilo there is a new hypervisor type “parallels” in Nova brought up via libvirt. It was renamed to Virtuozzo in Liberty while its nova.conf parameter remains the same. Since Liberty there is a new Cinder volume driver called vzstorage. How do these two OpenStack components connect to each other and what benefits do they bring in addition to the most mature and widely used QEMU/KVM hypervisor? If you are interested in running via KVM not only Linux guests effectively but also Windows ones, if you are interested in creating elastic cloud where Virtual Machines can live side by side with System containers, if you are interested in live migration production quatily not only for virtual machines but also for containers, it will be worth visiting the presentaion. I will try to concentrate not on Virtuozzo product itself, but on improvements we are making regarding virtualization in opensource ecosystem in general and OpenStack in particular.  


* **Maxim Nestratov** *(Maxim has been working for more than 10 years in virtualization sphere taking part in building both server and consumer software products. Maxim helped as lead developer to impement key parts of Parallels Desktop for Mac such as memory management, suspend/resume/snapshot features. He played the key role in developing networking engine in Parallels Containers for Windows product. Currently Maxim is a maintainer of Virtuozzo driver in libvirt and he is a lead developer in the team that integrates Virtuozzo stack of products with OpenStack.)*

* **Andre Moruga** *(Andre Moruga is a Director of Program Management at Virtuozzo. He worked at Parallels on Parallels Automation, which is a service delivery platform that helps telcos and service providers to aggregate the cloud services they are offering. Andre has succeeded in driving integration efforts with the products and services that fit into “Infrastructure as a Service” and “Platform as a Service” category.)*

Achieving Zen-like Bliss With Glance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Everyone uses Glance, but not everyone uses Glance. Uploading VM disks or data assets has always been the most commonly used feature of Glance. In this talk, we will explore features that extend beyond image upload -- features that operators can use to secure and improve the performance of their Glance deployment, as well as features operators can use to enable their end users toward better collaboration and discovery of data assets. In general, we will answer: How do I discover disk images ? How do I share images effectively with my organization ? How do I ensure the authenticity of image data using digital signatures ? How can I improve the performance of glance image uploads/downloads ? How can I make better use of my image metadata using property protections? What are image locations, and how can I tell if they’re appropriate for my cloud? And more..


* **Sabari Kumar Murugesan** *(Sabari is a Senior Member Technical Staff at VMware working with OpenStack since the Havana Release. Currently, he is a core reviewer and contributor to the Glance project. In the past, he has been associated with Nova and Oslo projects. At VMware, he primarily works as a developer on the VMware Integrated Openstack product team a.k.a "Team OpenStack @ VMware". He is based out of Palo Alto but considers NYC his home away from home. He calls himself an amateur photographer but no one has ever seen his work.)*

* **Nikhil Komawar** *(Nikhil Komawar is the PTL for Glance in Newton release and a Glance subject matter expert at IBM. He's a Open Source and Open Community enthusiast.  He's a former Project Technical lead for the OpenStack Searchlight project and core there. He is also a mentor for the Outreachy program for technical development of the under-represented groups. He loves technical and process evolution.)*

* **Brian Rosmaita** *(Brian Rosmaita is a Senior Software Developer at Rackspace.  He's been an active technical contributor to OpenStack since the Folsom release and was a software developer on the Rackspace first generation cloud.  He's a core contributor to the Glance and Searchlight projects, and is the Glance technical lead for the OpenStack Innovation Center.  In his spare time, he's the host of Radio Ethiopia, a reggae and African music show that's broadcast on K-RACK, Rackspace's internal internet radio station.)*

Enhanced platform awareness in OpenStack for mortals
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack has over a number of releases grown a large number of features that grant the compute scheduler enhanced visibility of the capabilities of the OpenStack environment and the hypervisors within it. These features when combined enable fine-grained matching of workloads with the capabilities of the platform that they require, sometimes referred to as Enhanced Platform Awareness (EPA). Currently exposed capabilities include NUMA topologies, dedicated CPU cores, CPU thread policies, huge pages, SR-IOV physical functions, SR-IOV virtual functions, network interface cards, and other PCIe devices like GPUs. While these faciliies are already proving extremely useful for high performance computing (HPC), network function virtualization (NFV), and software defined networking (SDN) networking use cases the steps involved in requesting these capabilities for a virtual machine and the ways the features do and don't work in conjunction with each other are not always obvious.


* **Stephen Gordon** *(Stephen is a product manager focused on OpenStack tenant workloads at Red Hat be they virtualized, containerized, orbaremetal. He is currently a facilitator of the Kubernetes OpenStack SIG, an avid collector of “Internet points” at  the Foundation's Q&A portal, ask.openstack.org, and a regular contributor to the Red Hat Stack blog - http://redhatstack.com/. Previously Stephen was a technical writer producing documentation for Red Hat Enterprise Linux OpenStack Platform, Red Hat Enterprise Virtualization, and related open source projects including the OpenStack documentation project, oVirt, and Fedora.  )*

Glare - a unified binary repository for OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Glare (from GLance Artifact REpository) is a new service in the Glance project that provides a secure and customizable unified binary repository for OpenStack. The idea behind Glare is to allow various OpenStack services to catalog different objects they use to operate. Images used by Nova to run the VMs are just the best known examples of such objects; other examples include Heat templates, Tacker blueprints, Murano packages, and so on. Obviously, this functionality is common for different kinds of objects, and is usually unrelated to the primary mission of respective projects using these objects. That's why we implemented a dedicated service that will take care of managing various data assets in OpenStack clouds. The talk will describe how Glare helps to manage different artifacts across the cloud, how you can build your own private and secure catalog with artifacts for your service, what deployers need to know about the installation process, and what is coming in the future.


* **Mike Fedosin** *(Mike Fedosin is a full-time upstream OpenStack developer with more than 10 years of experience in Software Development in enterprise, scientific and open-source projects. He has the title of Ph.D. in the development of cloud service architectures. Being one of the core developers of Glance, Mike is driving a number of cross-project initiatives there, like adoption of Glance v2 API across OpenStack, and owning several other large features. Also, Mike leads project Glare, which provides secure and customizable unified binary repository for OpenStack.)*

* **Kairat Kushaev** *(Software Engineer in Mirantis)*

Horizon Project Overview
~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

During the past few cycles, the Horizon team has made progress in several areas. In this session, we will provide an update on the team's accomplishments and where Horizon is heading in the Ocata release. Come hear the current and former PTL detail the project's successes and where things are headed in Ocata.


* **David Lyle** *(David is an OpenStack Architect at Intel where he is focused on contributing to and improving OpenStack. He served five terms as Horizon Project Technical Lead. David previously helped drive use and adoption of Horizon as the user interface for use in OpenStack public clouds. He has directly contributed to the development, packaging, deployment and support of a large public cloud running OpenStack.)*

* **Rob Cresswell** *(Rob is a Software Engineer at Cisco Systems and PTL for the Openstack Dashboard (Horizon) project.)*

Fuel Me Once Shame On You, Fuel Me Twice Shame On Me
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Users are incredibly ingenious when using a product in new and unexpected ways. OpenStack Fuel had to endure the rigors of deploying a large infrastructure like AT&T's.  As a critical part of the AT&T Integrated Cloud (AIC), the Fuel community was challenged to implement change based on new perspectives and functional requirements in order to meet the needs of enterprise large scale deployments. AIC provided a complexity unseen by developer community and added new use cases, architecture design, and network intricacies. As a result the Fuel project has grown and improved in leaps. Find out how AIC helped to advance the Fuel project to be a more resilient and flexible solution.


* **Matthew Ernst** *(As part of AT&T Integrated Cloud (AIC), I am involved in the management and development of Automated Deployment for AT&T's distributed clouds. Working with OpenStack since 2014, I have grown passionate about the possibilities that OpenStack enables corporations to provide innovative and cutting-edge capabilities. My role in AIC involves being a Scrum Master for the Fuel development team and the Production Support team that provides automation for current defects. As a leader in the automation space, I work to make sure the deployments are performed successfully by working with teams from development, automation, and deployment to better understand what is being deployed and how automation can help to improve the process.)*

* **Kayla Fromme** *(I am managing development of OpenStack core components (upstream and internal customizations) at AT&T and deployment of OpenStack using Fuel in enterprise data centers.  My first summit was Vancouver 2015.  I enjoy learning about OpenStack and how other companies are using & deploying OpenStack.  I joined the  Women of OpenStack shortly before the Austin Summit and I am looking forward to becoming more involved. In my spare time I like to snowboard, cheer on the St. Louis Cardinals, and play soccer. )*

* **Omar Rivera** *(Joined AT&T's Integrated Cloud project in 2015 under Andrew Leasck, Director of Technology Development for AT&T's Integrated Cloud. Became a DevOps Engineer at AT&T working with the Security team and presently the Automation and Deployment team using OpenStack Fuel and Puppet. I am interested in infrastructure deployment, automation, lifecycle management, ease of operations, and networking.)*

Understanding Keystone Federation using K2K
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Let’s take a deep dive K2K federation to learn more about keystone’s federation support. Keystone2Keystone federation is a feature of keystone that allows keystone to be run as both an identity provider and a service provider in a federation. First introduced in the Juno release it has been updated and improved in all releases since. K2K allows us to experiment with keystone’s federation support without having to mess with overly complicated identity providers. This talk will dive deep into the technical details of setting up a small K2K federation using the Mitaka release. Most of the setup will be done through the command-line interface. We’ll be discussing each command and its significance as we go. We’ll also be configuring non-OpenStack software, like Apache. Along the way you’ll hear about core federation concepts, like mapping, and how they may apply to federating to external identity providers.


* **David Stanek** *(  David Stanek has been developing software professionally for over 15 years. He is currently a Software Developer at Rackspace.  Python has been his language of choice for over 12 years both on and off of the job. David spends much of his free work time working on open source projects and sharpening his technical skills. He helps organize the Cleveland Area Python Interest Group. He enjoys reading technical books and listening to a variety of podcasts and audio books. Google him for more information. When he's not working he enjoys spending time with his beautiful wife and 4 wonderful children.)*
