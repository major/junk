Big Data
========

Efficient ways to run big data in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Customers are eager to put big data services into Cloud. There are many projects like Sahara, Cloudera Director, or Cloudbreak in the market to help the customers to implement Hadoop in the cloud. But performance is always the most critical issue when considering big data in OpenStack. In this presentation, we would like to teach you how to configure Hadoop/Spark in OpenStack. We will use some real customer cases to point out most of the issues that you may concern when running a real big data workload in OpenStack. We did lots of performance testing and would like to show you the results and the gaps between bare metal and virtualization. We also proposed several efficient ways including both OpenStack and Hadoop/Spark configuration to enhance the performance and reduce the gap to integrate big data services into OpenStack easier.


* **Weiting Chen** *(Weiting is a software engineer at Intel Software Service Group. He is working on "Big Data on Cloud" Solution for several years. One of his responsibility is as a consultant to engage with the customer integrating Big Data solution into their Cloud infrastructure. He has already contributed on Sahara project for past two years and currently is focusing on container based Big Data solution in OpenStack. Weiting is also familiar with Big Data and OpenStack architecture design and researching the emerging technology in this area.  )*

Build the Artificial Intelligence Cloud - Provision and Manage TensorFlow cluster with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

TensorFlow was a new open source platform for artificial intelligence by Google Brain Team. Because of its powerful features and high scalability, it gains extensive attention once open source. In the other hand, as the most widely used cloud platform, thousands of organisations host their data processing platforms on OpenStack with Sahara project. Can we bring TensorFlow together with OpenStack? 


* **Lin Peng** *(Principal Technologist, Architect in EMC. Leading Cloud Management & Orchestration, Converged Infrastructure initiatives in EMC CTO Office. 10+ patents related to cloud, software-defined data centers and big data. He has also authored a book titled Big Data Strategy, Technology and Application. Contribution to OpenStack include: Heat Murano (Lattice package) Cinder, QoS Puppet Module for VNX integrating OpenStack)*

* **Accela Zhao** *(Technologist at EMC ARD (Advanced Research & Development), 3 year experience in Openstack and distributed storage, active Cinder contributor, former presenter at Tokyo Summit. He has been working on a series of innovations related the 3rd cloud platform and emerging storage technologies. Previously he worked for Openstack solutions in Cisco Webex, one of the largest SaaS globally.)*

Object Storage Analytics: Leveraging Cognitive Computing For Deriving Insights And Relationships
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Object storage has become a de facto cloud storage. Analytics over data stored on object store for deriving greater insights is an obvious exercise being looked by implementers. In object stores like SWIFT, user-defined metadata associated with objects has the ability to provide quick relevant insights of data and can be leveraged for analytics. But having relevant user defined metadata with every object is one of the inhibitors for such analytics. On the other hand, there are Cognitive Computing services that are now available which leverage extreme data analysis using machine learning techniques for data interpretation. In this presentation, we discuss how cognitive services can help enrich object stores for analytics by self-tagging objects which can be used for data analytics as well as for deriving object relationships. The presentation includes a manifestation of the above using on OpenStack SWIFT implementation and a popular cognitive service in marketplace like IBM Watson.


* **Sandeep Patil** *(Sandeep Ramesh Patil works as a storage cloud architect with IBM labs and has over 15 years of extensive product architecture and design experience. Sandeep is IBM Master Inventor with over 150+ US patent filings in the field of storage cloud, security, filesystem, etc and is among the leading inventors in India in the mentioned field. Sandeep has authored numerous articles and paper publications in the filed of computer science with subjects over security, storage clouds, etc and has presented in various international conferences across the world.)*

* **Smita Raut** *(Smita has been working with IBM for the last five years in storage area. She has been working on Network Attached Storage products on features related to disk and filesystem management, Active Cloud Engine (wan-caching across geos), Information Lifecycle Management and Object protocol for cloud storage. Her current focus is on Object storage protocol for cloud enablement.)*

* **Bill Owen** *(Bill Owen is Senior Software Engineer with IBM's Spectrum Scale team.  He is responsible for the integration of OpenStack with Spectrum Scale.  He has worked in various development roles within IBM for the past 15 years.  Prior to joining IBM, Bill developed and deployed grid management software for electric utilities.)*

Big Data and Flash. This is your future!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Flash is enabling a new generation of large scale real-time applications. Many of the tried and true methods rules for deploying big data storage using HDD must be reexamined when brought into the flash world. This presentation will present alternative storage architectures for big data systems that exploit the advantages of flash technologies to provide vastly superior performant systems at cost levels that rival traditional solutions.


* **Allen Samuels** *(Allen joined SanDisk in 2013 as an Engineering Fellow, he is responsible for directing software development for SanDisk’s system level products. He has previously served as Chief Architect at Weitek Corp. and Citrix, and founded several companies including AMKAR Consulting, Orbital Data Corporation, and Cirtas Systems. Allen has a Bachelor of Science in Electrical Engineering from Rice University. Allen is a member of the Ceph Advisory Board and is heavily involved in the evolution of this critical open source technology.)*

HDFS and Private Cloud
~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Traditionally, Hadoop clusters have been built using dedicated hardware separated from the rest of the data center IT infrastructure. The rapid growth of HDFS/Hadoop/Spark/Yarn applications makes it desirable to share the services-oriented virtualized infrastructure commonly known as private cloud. While virtualizing compute and network interconnectivity is a relatively well-solved problem. Virtualizing the HDFS storage component into the private cloud work has unique challenges. This talk explores those challenges and offers multiple prescriptive solutions along with criteria to allow planners and architects to meaningfully compare and contrast the different approaches.


* **Allen Samuels** *(Allen joined SanDisk in 2013 as an Engineering Fellow, he is responsible for directing software development for SanDisk’s system level products. He has previously served as Chief Architect at Weitek Corp. and Citrix, and founded several companies including AMKAR Consulting, Orbital Data Corporation, and Cirtas Systems. Allen has a Bachelor of Science in Electrical Engineering from Rice University. Allen is a member of the Ceph Advisory Board and is heavily involved in the evolution of this critical open source technology.)*

Hadoop on Openstack Cloud: The Elephant can fly!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Traditionally Hadoop is deployed on physical servers located on customer premise. This trend is changing with the advancements of cloud technology. A cloud deployment offers the ability to conveniently scale the cluster as needed. Multi-tenancy is also a big advantage when it comes to facilitating multiple users on the same physical hardware. Furthermore, a cloud deployment, coupled with multi-tenancy, is greatly complimented by the resources and security segregation. Each tenant has full control over their resources without incurring any risk to the resources managed by the other tenants. Join us and learn how Hadoop can be deployed on an Openstack cloud using the Openstack Sahara project. The presentation will also show how an Openstack cloud can be optimized to get the performance of a Big Data workload on the Cloud to match as closely as possible that on a bare-metal configuration.


* **Nicholas Wakou** *(Nicholas Wakou is a Principal Performance Engineer with the Dell Revolutionary Cloud and Big Data Solutions team. Nicholas's role, interest and activity is focused on the characterization and optimization of the performance of Dell Cloud and Big Data solutions. Nicholas has been involved and is engaged with Industry efforts to define performance benchmark specifications. He is active on the SPEC (www.spec.org) Cloud committee and several committees of the TPC (www.tpc.org).  Nicholas represents Dell on the Board of Directors of the TPC and on its Technical Advisory Board (TAB). Previously, he was Chair of the TPC Public Relations standing committee. Nicholas has an MS. Electrical Engineering from Oklahoma State University, MS. Microelectronics Technology from Middlesex University, London and a BSc. Electrical Engineering from Makerere University, Kampala, Uganda.)*

* **arkady kanevsky** *(Arkady has been a member of OpenStack since Grizzly. He is director of engineering leading a team of developers responsible for development of Dell OpenStack solutions.  Arkady has PhD. in CS from UIUC.  He straddled academic, research, architect, developer, and product owner roles.  Arkady roles included  but not limited to, research publications and Program committee member for various conferences like FAST (https://www.usenix.org/legacy/events/fast11/organizers.html), Chair or board member  of several standard activities, like DAT (http://www.datcollaborative.org),  OpenFabric (https://www.openfabrics.org/index.php) and MPI-RT (http://www.cse.msstate.edu/~yogi/dandass-mpirt-2004.pdf) to product delivery, like EMC Atmos, Dell OpenStack solutions among others.   Arkady is passionate advocate of OpenStack and making its usage easier for users and administrators. He concentrates efforts of his team on extending OpenStack capabilities for enterprise use cases, from automatic deployment, and robustness, to HA, upgrade, extensibility and validation.)*

* **Micheal Woodside** *(Michael is a Senior Manager with the Dell Open Source Solutions team.)*

Avoiding Datageddon: Ensuring availability as data growth multiplies
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As organizations increasingly turn to OpenStack to build their cloud native applications, the amount of data generated is exponentially increasing as well. This data is more critical to organizations than ever, but ensuring its availability and preventing data loss is non-trivial due to this growth. Organizations are looking for scalable data protection and restoration solutions that can keep up with their data footprint. Come join us on this informative session where panelists will talk about do’s and don’ts for data protection on OpenStack, share real life experiences, debate various approaches, and discuss the relevance of Docker, SWIFT and much more.


* **Ashish Nadkarni** *(IDC)*

* **Ambarish Chandrasekaran** *(EMC - OpenStack community expert)*

Big Data Reference Architecture for Enterprise
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation is a result of a joint collaboration effort in the Enterprise Working Group compiling Enterprise Workload Reference Architectures. There is a growing demand for Enterprise IT department to provide Hadoop as a Service in on-premises environment. In this session we present a reference architecture of Hadoop workload that runs on top of OpenStack that can be used to build Big Data applications. We compile a list of necessary technical components which are derived from real world Hadoop architectures. This includes basic technology components like network layouts for Hadoop cluster (such as separation of enterprise, data and management LANs), the design and placement of different Hadoop node types, and installation procedures with or without local repositories. Different characteristic workloads such as batch, stream and predictive analytics are also included in the architecture discussion.


* **Peter Dr. Meitz** *(In the IT-Business since the mid 90th Technical background in Java Development, Database Design (Oracle, MSSQL), DW, Middleware Technology, OpenSource - Linux, Hadoop, Openstack and other! Employee of Computacenter since 1999 in different positions. 2011 Solution Manager and Solution Architect for Big Data Technology - Technical Leader for the Big Data Business of Computacenter in Germany - Design and Implementation of Big Data Solutions (focus Hadoop) - Design Big Data Openstack Solutions 2005 Senior Consultant with the focus on architecture Database and DW Solutions - Design of Database and DW Solution for our Enterprise and Global Accounts)*

* **Thomas Bludau** *(Thomas Bludau loves and lives with Open Source Software after his first steps with it in the last late century. With his decision to make his hobby to his job he had until today insight into a lot of open source technologies obtained. His primary topics are automatical Linux Deployments in Enterprise environments (f.e. SAP HANA or Hadoop with RedHat and SUSE), OpenStack, Configurations and Systemmanagement and High Availibility with Open Source tools. OpenSource Solution Architect Technology focus on Redhat, SUSE, OpenStack, Hadoop Certifications amongst others: Red Hat Certified Architect / RHCA  Red Hat Certified System Administrator in Red Hat Openstack Employee of: Since 2011  - OpenSource Solution Architect - Computacenter AG & co oHG November 2005 – Dezember 2010 - Linux Senior Consultant - Gonicus GmbH)*

Monasca-analytics: Sharing Tailored Data Analytics Tools for Monasca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Infrastructure management analytic challenges include root cause analysis, trends detection, custom overviews creation and anomaly detection. In Openstack this is repeated by every organization, causing work redundancy and suboptimal algorithms. Monasca-analytics is a new framework that extends Monasca, OpenStack Monitoring-as-a-Service project, with pluggable data science tools. Its features include: 1. Algorithmic flow definition: Enables sharing of complex algorithmic recipes in the community. 2. Thin orchestration layer: Uses the algorithmic flow and instantiates in an execution environment. 3. Execution engine independence: Support for Spark, with Flink in progress. Monasca Analytics can detect anomalies or reduce alert fatigue by analyzing large volumes of data; example algorithms 1-Class SVM, LiNGAM and statistics are provided. Algorithmic flow use cases will be demonstrated, showing how to achieve faster and better problem resolutions via community shared recipes.


* **David Subiros Perez** *(working as a research engineer in the manageability Lab, in Hewlett Packard Enterprise. With experience in large scale infrastructure management, cloud computing, machine learning algorithms, and data security. My background is in Telecomunication engineering.)*

* **None None** *(None)*

Blockchain and OpenStack - Building Trusted Chains
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Financial organisations are currently looking with great interest at Blockchain databases. This is the same technology behind most crypto-currencies including bitcoin. The goal of Blockchain is to maintain a timestamped, immutable, continually growing list of records. Each block can hold batches of transactions and the results of any blockchain executables.OpenStack lends itself perfectly to the OpenStack platform for hosting as well as potentially providing solutions to some governance challenges such as those being addressed by the Congress Project.This talk will examine the architecture and profile of a blockchain application hosted on OpenStack, examine the challenges and the requirements that still need to be met as well look at what can already be achieved. Finally we will look at how this technology might provide governance solutions to cloud tenants within the platform and dovetail with the work going on in the Congress project and some potential benefits of this union.


* **Glyn Bowden** *(Glyn Bowden is the Chief Technologist for HPE's open source Cloud Consulting organisation in EMEA. He specialises in enterprise cloud, data center transformation, shared infrastructure and using IT services to enable business. He has over 15 years experience designing and implementing cloud solutions both with vendors and multi-national end user organisations.)*

* **Eric LAJOIE** *(Eric Lajoie is a OpenStack & NFV Architecture Consultant for HP Professional Services (PS) – Helion OpenStack, Germany. In his current capacity, Eric is responsible for end to end solution design, be it IPv6, EPC, or virtualization solutions. His key interests and achievements are in design and implementation of carrier grade Helion OpenStack solutions as well as integration with SDN, EPC, LTE, VoLTE, Femto, M2M, VMware, and all flavors of Linux including RHEL, Ubuntu, Debian, CentOS, and Gentoo. He is responsible for solution, design, service implementation and assessments related to service providers environments. Joined HP Enterprise in December 1st 2014 10 Years of SP Industry Experience in Networks and Telecommunication Solutions. Projects thus far: Telefonica UNICA OpenStack and NFV Project including Nuage/DCN Joined Cisco in September 2005 till end of November 2014 Projects while at Cisco: vGi-LAN virtualization proof of concept in Germany EPC field support and enablement in Japan EPC solution design in France IPv6 M2M design & implementation in UK Team Lead for Cisco's first EPC Pilot Projects in Norway IPv6 Assessment lead in Nigeria implemented IPv6 technologies CSG2 with DPI and GGSN optimization and design in USA Femto Design & Implementation in USA. CSFB Integration with Mavenir IWF in Düsseldorf Germany Industry Recognized Certifications: BS in Electrical Engineering CCNA, CCNP, CCDA, CCDP, CCIP VCA-DCV Wireless# Programming for Everybody (Python) by University of Michigan on Coursera)*

MidoNet - Turn your overlay network "Insight Out"!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

MidoNet's MEM Insights data analytics gives cloud operators a better view into their virtual networks. MEM Insights analyzes and visualizes data including: Physical host tunnel traffic counters Virtual topology (routers, networks, ports) traffic counters Historical flow analysis Tenant bandwidth  usage Live flow tracing The session describes how operators can use the provided APIs to gain insight to virtual network  data. We will explain how we built our analytics platform using open source technologies like Elasticsearch and Logstash. By combining this data with additional network data extracted from the network virtualization overlay, thanks to the controller cluster's extensible architecture, operators can inspect their virtual traffic for any operational facets of interest.


* **Ernest Artiaga** *(Ernest landed at Midokura after working on distributed file systems at Barcelona Supercomputing Center. Before that, he designed the monitoring system for the MareNostrum supercomputer, and worked on computer security at CERN; now he is enjoying the cool world of virtualized networks, and is the tech lead for the MEM Insights team at Midokura.)*

* **Jan Hilberath** *(Jan works as a Support Engineer at Midokura Japan. Originally being a Software Engineer for many years, after his move from Germany to Japan in 2008 he slowly moved away from development into Linux/Unix administration and customer support. Jan joined Midokura in 2014 and is part of the global support team, assisting customers around the globe with installation, management and troubleshooting of production-level OpenStack clouds. He is responsible for the MidoNet user documentation and occasionally providing OpenStack and MidoNet training to customers and partners in Japan.)*

Big Data and Machine Learning on OpenStack backed by Nova-LXD
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Hadoop was built with bare metal in mind - get your commodity hardware, stick hadoop on it and let YARN do all the hard work managing resources. However, Big Data software deployments on other substrates such as AWS (ec2 and EMR), AZURE, GCE are gaining popularity. We look at the challenges and a relevant solution related to deploying big data software in an OpenStack cloud.  Perhaps most interestingly, we discuss and demonstrate what it looks like to run a machine learning job with Nova-LXD in that cloud to address data locality issues in virtualized environments, and to demonstrate that hypervisor overhead does not necessarily hinder Big/Fast Data processing.


* **Andrew McLeod** *(A Kiwi who now lives in Barcelona, with a background in infrastructure, networking, devops and other random industry keywords. Working at canonical as a big data software dev, shortly moving into Openstack and CI.)*

* **Ryan Beisner** *(Ryan is QA Engineer on the Ubuntu OpenStack Engineering Team, a global open source software development team at Canonical, the company behind Ubuntu Linux.  He focuses on test automation and application modeling.  His team's CI/CD systems deploy and test hundreds of OpenStack clouds per month, in multiple combinations of topology, architecture and release/build version. Other areas of focus include bare metal cluster management, private cloud administration, service orchestration, modeling language development, general distribution work and consulting support for customer-facing teams. Ryan joined Canonical in 2014.  His background is in network engineering and open source system integration.  Previously, as Operations Director for a US ISP/telecom, he lead the private cloud engineering and deployment efforts for that carrier and its clients.)*

Multitenant TensorFlow on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Machine learning, deep learning and other fancy words make us all excited. However, the true challenge is to enable these techniques in production. How do we setup a system that works as a Service (aaS), is multi tenant and scales to offer the desired performance, taking advantage of OpenStack's components? At Cisco, we decided to do just that. After choosing TensorFlow to run our workloads, we want to share how we built a multitenancy service with TensorFlow and the many challenges we faced.


* **Marc Solanas Tarre** *(Big data on Cloud Computing researcher at Cisco.)*

* **Xinyuan Huang** *(Xinyuan is a software engineer at Cisco conducting research and development in machine data analytics, data platform and applications, and data driven optimizations, etc. He is also an developer and researcher in Openstack scheduler and smart solutions for cloud resource optimizations. He has practical knowledge in Machine Learning, Intelligent Control/Optimization Systems, and Signal Processing. http://www.linkedin.com/in/huangxinyuan  )*

* **Johnu George** *(Johnu is a software engineer in the Office of the Cloud CTO at Cisco. He is primarily involved in building scalable distributed systems. He is currently working on real time streaming data processing and analytics. He holds a MS in computer science from Texas A&M university,College Station.)*

Build a self healing Openstack cluster using Cognitive
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data driven applications on cloud infrastructure increasingly rely on Machine Learning. This often requires application developers and data scientists to write their own machine learning pipeline or deploy other packages to do some kind of data transformation and apply ML primitives. Data scientists also need to have an easy way to rapidly experiment with data without having to write basic infrastructure for the above operations. Often setting up data pipelines is the biggest barrier to rapid exploration of the design space and application development.  Cognitive is a ML service on top of OpenStack which provides ML based services to tenants (API, workbench, compute service).  In this talk, we present how you can use Cognitive to learn how to cluster activity from Openstack logs, obtain data insights and take corrective measures in realtime.  Openstack systems generate huge amounts of logs/metrics which can be fed into Cognitive for realtime predictive analytics and cluster tuning. 


* **Johnu George** *(Johnu is a software engineer in the Office of the Cloud CTO at Cisco. He is primarily involved in building scalable distributed systems. He is currently working on real time streaming data processing and analytics. He holds a MS in computer science from Texas A&M university,College Station.)*

* **Xinyuan Huang** *(Xinyuan is a software engineer at Cisco conducting research and development in machine data analytics, data platform and applications, and data driven optimizations, etc. He is also an developer and researcher in Openstack scheduler and smart solutions for cloud resource optimizations. He has practical knowledge in Machine Learning, Intelligent Control/Optimization Systems, and Signal Processing. http://www.linkedin.com/in/huangxinyuan  )*

* **Marc Solanas Tarre** *(Big data on Cloud Computing researcher at Cisco.)*
