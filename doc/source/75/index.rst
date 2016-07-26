Security
========

Automating OpenStack Log Management & Security with Elastic Stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

tbd


* **Nathan Randall** *(Nathan works for the OpenStack IaaS group at Charter Communications (formerly Time Warner Cable) in the United States. He lives (and prefers to work) in the mountains west of Denver, Colorado.  Nathan comes to DevOps from the Operations side, having started in IT working as a VMware Cloud Engineer, Cisco Network Engineer, Linux SysAdmin, and Security Engineer. He has since seen the light and is now devoted to developing open-source applications for open-source infrastructure. He is somewhat obsessed with the idea that Information Security has been a forgotten bystander in the DevOps revolution, and he seeks to one day rectify this grave injustice. Said another way, Nathan is trying to automate his way out of ever having to talk to a compliance auditor.)*

Identity in Tripleo
~~~~~~~~~~~~~~~~~~~

**Abstract:**

Getting a security-hardened OpenStack deployment is a daunting challenge. You want to integrate your TripleO deployment into your organization's existing security management toolchain. You already have a way to manage your X509 certificates for network transport layer security. You already store your user database and may expose it via LDAP and Kerberos or federate it via SAML. TripleO has a complex deployment process that is daunting to the neophyte. However, once you understand the mechanics, you can customize your TripleO deployment in many ways. You’ll also be able to security-harden your TripleO deployment with industry-standard encryption.


* **Adam Young** *(Adam Young is a member of Red Hat's OpenStack team and a core developer on Keystone, the identity management service for OpenStack. Adam has worked on various systems management tools, including the Identity Management component of Red Hat Enterprise Linux based on the FreeIPA technology.A 19 year industry veteran, Adam contributed to multiple projects, products and solutions from Java based eCommerce Web Sites to Kernel modifications for Beowulf clustering.  )*

* **Juan Osorio Robles** *(Juan Antonio (Ozz) is a member of Red Hat's OpenStack Identity team and a core developer onBarbican, the secret storage as a service solution for OpenStack; and TripleO (OpenStack overOpenStack), a cloud installer. In Red Hat, he has been actively working in TripleO to enable TLS in boththe public and internal services of the deployment.)*

Nokia - SDN & NFV: Security & Threat Detection with Nuage Networks and CloudBand
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security is a major concern within Cloud Infrastructures. With an exponential growth in IoT and mobile devices, cyber thieves are using malware to take advantage of the increased attack surface to access sensitive personal & business information. Malware does not just affect the end-user, but also affects performance and signaling of the cloud network. This session will demonstrate an OpenStack Security Solution, named NetGuard Endpoint Security, used to detect IoT and network traffic infection for Mobile & Enterprise Networks. We will present key concepts of an OpenStack Cloud Infrastructure and include new innovations that every enterprise is trying to understand and include in their cloud. These concepts are: Orchestration of the SDN-vProbe, Virtual NIDS, and Analytics Portal; using Nuage and CloudBand -OpenStack. Virtual Tapping of high throughput network traffic. A new tapping mechanism requiring no tapping infrastructure be available within OpenStack.  SDN Service Chaining.  


* **Sami Assaad** *(I have worked for some of the most influential IT and Engineering companies on the globe; Nortel Network, Ericsson, Alcatel-Lucent, and now at Nokia. My recent experiences range from the Design & Development of Virtual Machines, security applications, Intel DPDK, Network Function Virtualization (NFV), CentOS/Redhat Linux 6-7, using Intel & HP equipment, Client/Server VM Applications, Network Load Balancing, SR-IOV, PCI Pass-through, Packet Decoding, VM Performance Measurements, etc... Additionally, I have a strong background in the design of Wireless Networks, specifically with Modem design for LTE, UMTS, and WCDMA networks. I lead a team that introduced the first virtual UMTS solution which was demoed at MWC 2012. We used this virtual UMTS solution to present a seamless handover of a mobile between a Carrier Network and local Wifi. This demonstration won the "Best Infrastructure Technology Award" for the Light-Radio Network at MWC 2012. I studied at Concordia University, in Montreal, Quebec. During my studies I was the Recipient of the Prix Bombardier Award for 'Entrepreneurial Design Marketability’ (Province of Quebec Engineering Competition – 1988. Subsequently selected to compete in Moncton, N.B. at the 1988 Canadian Engineering Competition.)*

OpenStack Compliance the DevOps Way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Chances are if you run an OpenStack cloud, you have some form of compliance you have to adhere to. It may be some internal CIO driven compliance written in 1993, or external compliance requirements like HIPPA or PCI. We'll show you how Blue Box Cloud manages its compliance by utilizing the power of DevOps and open source software to not only enforce (Ansible) our adherence to compliance but to actively monitor and alert (Serverspec, Sensu, ELK) the moment a server falls out of compliance. Of course this is not a magic wand that will make your systems PCI compliant, the underlying operating system and software need to have the appropriate features to support the compliance requirements. For example, we are not injecting any magic to perform automated password rotation in keystone (that would need to be solved in keystone itself, or custom middleware) but rather enabling or configuring the keystone options to do so.


* **Paul Czarkowski** *(Paul Czarkowski is a Cloud Engineer at IBM Blue Box where he implements OpenStack for Enterprise clients and does Docker R&D.  When he isn't coding you can find him baking bread and winning cookoffs around Austin TX.)*

* **Zachary Sais** *(Zachary Sais is a Software Engineer at IBM Cloud where he automates and deploys monitoring frameworks for enterprise OpenStack clients. Prior to IBM, he graduated from the University of Texas at Austin with a degree in Computer Science. In his downtime, you can find Zach brewing delicious beer and playing golf in Austin, Tx.)*

* **Rachel Wong** *(Rachel Wong is a software engineer at IBM Cloud where she works with the Security and QA Testing team in order to test Openstack UI, APIs, and infrastructure. Before working at IBM, she graduated from the University of Texas at Austin with a BS in Computer Science. Currently residing in Austin, TX, she spends most her time playing Ultimate Frisbee and attending happy hours.)*

Title: Container Defense in Depth
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Defense in depth is an information assurance technique used to protect a system from any particular attack - use of blended countermeasures, working together to meet control and governance requirements. In a containerized world, defense in depth is applied by thinking about security within a container, on the container host and at the container platform layer. This talk will cover numerous technologies and practices at each layer - from kernel quality, SELinux (svirt), SECCOMP, and use of root, to measuring attack surface, patch remediation, and platform level authentication/authorization, these are the droids you are looking for. This talk will help an end user understand the breadth of tooling that is available at each level and how they will help protect their system from intrusions and compromises.  


* **Scott McCarty** *(At Red Hat, Scott McCarty helps to educate IT professionals, customers, and partners on all aspects of Linux containers, from organizational transformation to technical implementation, and works to advance Red Hat's go-to-market strategy around containers and related technologies. He also liaises with engineering teams, both at the product and upstream project level, to help drive innovation by using feedback from Red Hat customers and partners as drivers to enhance and tailor container features and capabilities for the real world of enterprise IT.Scott is a social media start-up veteran, an e-commerce old timer, and a weathered government research technologist, with experience across a variety of companies and organizations, from seven person start-ups to 8,000 employee technology companies. This has culminated in a unique perspective on open source software development, delivery, and maintenance.)*

Can Keystone integrate with my existing authentication system?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Keystone service offers a wide variety and expanding list of different external authentication options. This session will provide an assessment of the current state of functionality for each supported option including LDAP, Microsoft Active Directory, SAML-based Identity Providers, multi-factor authentication and certificate-based systems.The information in the session is based on extensive HPE Helion OpenStack engineering participation and experience in the Keystone project, product readiness testing and reviews, and supporting multiple customer installations.


* **Tim Cuddy** *(Sr. Product Manager, Hewlett Packard Enterprise Cloud Business Unit Sr. Product Manager, Cisco Systems, Inc. Sales and Sales Support, Apple Computer IT Network Planning, Sprint)*

Session Title  Managing secrets securely using Barbican and multiple Hardware Security Modules
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security needs vary from one enterprise to the other, and from one type of workload (Dev/QA, production and compliant) to another, based on the risk profile and compliance requirements.  Managing secrets (passwords, keys, tokens and certs) is critical to proactively protect against data thefts and other types of attacks, meet regulatory compliance and scalability needs.   Enterprises need multiple back end key managers or HSMs to manage secrets for various types of workloads with different security needs.  Upstream Barbican project addresses this use case by providing the capability to configure and manage secrets using multiple HSMs through its plugin mechanisms.During this track we will provide an overview of various security use cases  to manage secrets, along with a reference architecture and demonstration to manage secrets (keys used for encrypting Cinder block storage data  and LBaaS certs) using multiple types of key managers (PKCS#11 and KMIP compliant).


* **Joy Dorairaj** *(Joy is a Principal Product Manager, part of the Helion OpenStack Product Management team with Hewlett Packard Enterprise responsible for security.  She specialises in OpenStack Security and Compliance, driving the product strategy & roadmap, prioritizing requirements and working with her engineering team to ensure that HPE is delivering a secure OpenStack distribution for customers. She has over 18 years of industry experience, having spent the last 10 years in a variety of Product Management roles in the area of security (OpenStack security, Analytics and Big Data Security, Cloud endpoint protection products, Wireless SaaS security, Security services for Telcos, Compliance products etc.) She has a Bachelors degree in Computer Science & Engineering and a Masters degree in Applied Mathematics, and enjoys running and community volunteering in her spare time.)*

* **Arun Kant** *(Arun is a OpenStack Engineer in Hewlett Packard Enterprise. He has been working in OpenStack since 2012. He has architected number of initiatives in HP Public Cloud and HPE Helion OpenStack keystone and barbican.)*

Best practices for securing and running a compliant OpenStack cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While security continues to be a big barrier to cloud adoption, compliance remains a bigger headache for enterprises as they transition to the cloud.  As OpenStack cloud adoption gathers mainstream and enterprises deploy their production workloads, it becomes critical to adopt best practices for securing and remaining compliant.This session will cover (based on customer case studies) best practices for hardening, and staying compliant, using a summary of controls from PCI and HIPAA. Topics shall include but not limited to- Building a layered defense - Bootstrapping security- Securing the infrastructure & data- Network segmentation & isolating tenants- Managing encryption keys & certificates- Securing Audit Trails, Monitoring & Patching- API security


* **Joy Dorairaj** *(Joy is a Principal Product Manager, part of the Helion OpenStack Product Management team with Hewlett Packard Enterprise responsible for security.  She specialises in OpenStack Security and Compliance, driving the product strategy & roadmap, prioritizing requirements and working with her engineering team to ensure that HPE is delivering a secure OpenStack distribution for customers. She has over 18 years of industry experience, having spent the last 10 years in a variety of Product Management roles in the area of security (OpenStack security, Analytics and Big Data Security, Cloud endpoint protection products, Wireless SaaS security, Security services for Telcos, Compliance products etc.) She has a Bachelors degree in Computer Science & Engineering and a Masters degree in Applied Mathematics, and enjoys running and community volunteering in her spare time.)*

* **Simon Leech** *(Simon Leech is a Certified Information Systems Security Professional with a specialisation in Security Architecture (CISSP-ISSAP), Certified Information Security Manager (CISM), Certified in Risk and Information Systems Control (CRISC), Certified in Cloud Security Knowledge (CCSK) and Chief Technologist Security within the Hewlett Packard Enterprise EMEA Hybrid IT Team. Within Hewlett Packard Enterprise, Mr Leech is responsible for influencing and evangelising the security strategy of the Hybrid IT team. Simon is active on Twitter as @DigitalHeMan)*

Holistic security for OpenStack clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Nothing clears out a conference room faster than a discussion around information security. Securing complex computer systems, such as OpenStack clouds, is extremely difficult. To make matters worse, attackers can make many mistakes without consequences. A defender’s single mistake could lead to a breach. Don't let fear rule the discussion around security. Operators need a simple and scalable method for securing OpenStack clouds. That starts with grouping components into compartments and then looking at how those compartments interact with each other. Those interactions form the backbone of security policies and technical controls. In this vendor-neutral talk, Major Hayden, principal architect at Rackspace, will break down the complexity of securing OpenStack clouds using real-world scenarios. Attendees will learn how to: Divide OpenStack deployments into compartments Analyze the interactions between each component Develop security policies and apply technical controls


* **Major Hayden** *(Major Hayden builds OpenStack clouds as a Principal Architect at Rackspace. Major is a core developer in the OpenStack-Ansible project with a focus on improving information security in OpenStack deployments.  He holds multiple Red Hat and Global Information Assurance Certification (GIAC) certifications and has written extensively about securing virtualized Linux environments. Outside of OpenStack, Major has contributed to several open source projects including dracut, systemd, and Ansible. Within the Fedora Linux community, Major serves on the Fedora Security Team and Fedora Server Working Group. Major enjoys writing on his personal blog, major.io, and he talks about technical topics on Twitter as @majorhayden.)*

Experiences deploying Keystone and Future Priorities by Operators and Developers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this panel session, we bring together several Keystone experts to discuss their experiences with using Keystone in both private clouds and public clouds at scale. We will discuss the efforts they have been involved in with configuring and deploying Keystone to address issues such as improving performance at scale. We will discuss their experiences using advanced Keystone features such as Fernet tokens and how these features have improved their deployments, and also what accommodations were needed to support new features such as this properly. We will also discuss how they are preparing for upcoming feature deprecations such as Keystone's deprecation of its eventlet deployment model. Panel members from private cloud and public cloud, both vendor and non-vendor, will discuss Keystone issues that are most impactful to them and how they are driving Keystone in upcoming releases to improve its deployability, operability, and consumability.


* **Steve Martinelli** *(Steve Martinelli is a contributor to the OpenStack project, specifically focused on its Identity, Authentication and Authorization. He is currently the Project Team Lead for the Keystone project, OpenStack's Identity service. He primarily focuses on enabling Keystone, to better integrate into enterprise environments. Steve was responsible for adding Federated Identity and OAuth support to Keystone and was one of the leading contributors to Keystone to Keystone federation support for interoperable hybrid cloud enablement. Steve is also a core contributor to other OpenStack projects, such as: OpenStackClient, pyCADF, cliff, os-client config, oslo.cache, and oslo.policy. Steve is a co-author of Identity, Authentication & Access Management in OpenStack, a book published by O'Reilly Media in 2015. Steve received his B.ASc. in Computer Engineering from York University.)*

* **Dolph Mathews** *(Dolph is an open source developer working in the OpenStack community. He truly enjoys fixing bugs, writing documentation, and helping the engineers around him become more productive. As a result, he has served as an OpenStack project technical lead (PTL) and on the OpenStack technical committee (TC).)*

* **Jesse Keating** *(Jesse Keating is a Lead OpenStack Engineer at IBM. He has been a part of the Linux community for over 13 years, as a user, contributor, instructor, author, and evangelist. A believer in Continuous Integration and Continuous Delivery.)*

* **Alvaro Lopez Garcia** *(Currently I works as a researcher at the Spanish National Research Council (CSIC). In 2007 I held a research associate position at the Italian National Institute for Nuclear Physics (INFN), where I started to work with virtualization so as to deliver on-demand services. I have taken part in several European projects about distributed and Grid and Cloud computing, such as EGEE-II/III (FP6, FP7), Int.Eu.Grid (FP6), EUFORIA (FP7), EGI-InSPIRE and more recently EGI-Engage and INDIGO-Datacloud. With the advent of Cloud computing I moved towards this field, working in the adaptation of the current Cloud middleware and infrastructures to fit the specific needs (parallelism, performance) of the scientific computing applications. In fact the CSIC deployed one of the first OpenStack infrastructures in Spain, back in the Essex release. I am a member of the Openstackfoundation, and I have been an Active Technical Contributor for several cycles, even if my activity has been related with bugfixing .)*

* **Brad Topol** *(Dr. Brad Topol is an IBM Distinguished Engineer in the IBM Cloud Architecture and Technology organization. In his current role, Brad leads a development team focused on contributing to and improving OpenStack and he has cross-IBM responsibility for coordinating its contributions to OpenStack. Brad is an OpenStack core contributor to Keystone-Specs, Pycadf, and Heat-Translator and has personally contributed to multiple OpenStack projects including Keystone, Pycadf, Heat-Translator, and DevStack. He is a co-author of Identity, Authentication & Access Management in OpenStack, a book published by O'Reilly Media in 2015.    )*

Achieving end-to-end compliance based on hardware root of trust
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Study shows that security is still the biggest barrier to cloud adoption, with compliance and data protection being top concerns for a CISO.    Enterprises often have a need to enforce policies (based on data sovereignty requirements) such as virtual workloads should only be placed, or migrated, based on location and assurance of hardware platform. Some others want to launch VMs/Apps/Containers on Servers with Boot Integrity – Platform Trust, while some have a need to extend the chain of trust from platform to workload (VM/Container). This session features a demo along with a reference architecture that shows end-to-end compliance (boot time to shutdown) using hardware and software attestations, as well as continuous compliance monitoring for drifts in an OpenStack cloud.   


* **Joy Dorairaj** *(Joy is a Principal Product Manager, part of the Helion OpenStack Product Management team with Hewlett Packard Enterprise responsible for security.  She specialises in OpenStack Security and Compliance, driving the product strategy & roadmap, prioritizing requirements and working with her engineering team to ensure that HPE is delivering a secure OpenStack distribution for customers. She has over 18 years of industry experience, having spent the last 10 years in a variety of Product Management roles in the area of security (OpenStack security, Analytics and Big Data Security, Cloud endpoint protection products, Wireless SaaS security, Security services for Telcos, Compliance products etc.) She has a Bachelors degree in Computer Science & Engineering and a Masters degree in Applied Mathematics, and enjoys running and community volunteering in her spare time.)*

OpenStack Hardening With TripleO
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

TripleO makes OpenStack deployments easier, but for security-conscious admins, architects and engineers, TripleO presents another layer of complexity. How do you migrate from shell scripts and Puppet manifests to a TripleO-friendly deployment? In this session, we'll show you how to make TripleO an asset instead of an obstacle, and how to harden your controllers and compute nodes from the OS to all layers of the stack.


* **Jason Ritenour** *(Click to edit summaryWith a diverse background in virtualization, storage, containerization, directory services, and open source technologies, what I love more than anything is solving complex problems. Whether it is the most efficient way to deliver an application, or how to automate a traditionally manual process, I enjoy coming up with ways to utilize the vast array of open source tools at my disposal to improve existing processes, or start a greenfield environment off on the right foot.  )*

* **Yonathan Goitom** *(I am currently a Senior OpenStack Consultant with Red Hat and have been so for the past two years. As a consultant I provide assistance to customer looking to adopt new technologies like OpenStack, CEPH and containers. Prior to joining Red Hat, I was fortunate enough to provide support to NASA’s first IaaS offering, Nebula, located out of the Goddard Space Flight Center  in Greenbelt,MD. Over the past several years I’ve worked customers ranging from federal agencies to prestigious academic institutions.   I currently hold a Masters Degree in Information Assurance and currently enrolled in Capitol Technology University's PhD program. During my free time I enjoy weight lifting, bowling and researching emerging technology trends. )*

Fortifying OpenStack Clouds Against Security Breaches
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security has become a global issue and as cloud deployments rise, security is a critical consideration in architecting and building clouds. In 2015, a zero-day vulnerability was uncovered every week and more than half a billion personal records were stolen or lost. Security admins are no longer asking “if” there will be a breach, but “when” and how to contain a breach from spreading or accessing the entire data center. The traditional model of perimeter security with firewalls is no longer sufficient to protect data centers and additional measures that not only prevent attacks but contain and neutralize attacks must be taken. With OpenStack, there are a number of options available from networking layer all the way to the application layer. In this session, speakers will discuss fortifying OpenStack clouds including methods to ensure protection for OpenStack API endpoints from DDoS attacks, separation of tenant and provider networks.


* **Rick Kundiger** *(CEO of Awnix Inc.  Rick Kundiger was born in Milwaukee Wisconsin and moved to Kansas at age 7. He was in the US Navy from 1993 - 1998 and has traveled and worked and lived all over the world since then. Rick has been working in government IT since 2000. He has worked on complex projects for the Department of Defense supporting over 900 locations in 18 countries.  Rick began designing and implementing virtual environments in 2004 and has continued to push the envelope of technology ever since; always wanting more capabilities at lower costs.    Rick worked as the Director of Architecture for the US Army in Europe from 2009 - 2001; after which he took a chief architect position at the USDA's National Information Technology Center in Kansas City.  There he led a dynamic team of IT personnel in the design and implementation of new data center infrastructure and platforms.  It was here that Rick began working with OpenStack.   In November of 2014 Rick left the USDA to form his own company, along with his co-founder Mike Meskill.  The company, Awnix Inc., specializes in products and services related to the deployment and integration of OpenStack + Software Defined Networking.)*

* **Erez Berkner** *(Erez Berkner, Director of Product Management for Data Center Security at Check Point(NASDAQ:CHKP), leads the company’s cloud security strategy. Erez joined Check Point in 2004 and has held key management positions in the R&D and Product organizations. As the Director of the Platforms organization, he led the development groups in building the Check Point vSEC product line for securing private and public cloud platforms.  Currently, he spends most of his time driving Check Point’s vision for securing the Software Defined Data Centers, Private Cloud & SDN, Public IaaS and Telco infrastructures (NFV). Erez holds a B.Sc. Cum Laude degree in Mathematics & Computer Science.)*

* **Faisal Mushtaq** *(Innovative senior executive with extensive experience creating and developing technology solutions that positively impact and support overall business goals, sales and revenue growth. Visionary leader with proven track record of building exceptional teams and successful products that achieve market leadership in both fast pace startup environment and Fortune 500 companies.)*

Hardening Security Inside Out for OpenStack Services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security is changing rapidly as attacks evolve beyond DDoS, brute force, browser, or shellshock type methods. While firewalls and perimeter based designs are standard practice, new security approaches are emerging as virtualization and cloud become prevalent and provide additional layers of security that may not be available previously. From preventative to active security techniques, OpenStack operators have the opportunity to secure north-south and east-west traffic not only from bare metal machines, but virtual machines and containers on a per tenant basis with hardened OS, active insertion of firewalls anywhere in virtual topologies to monitoring security by using policy-based virtual TAP and advanced GUI views. In this session, speakers will discuss how security models are changing with the onset of virtualization and cloud, and what tools are available for OpenStack operators to bolster their security.


* **Wendy Cartee** *(Wendy Cartee is VP of Product Management and Marketing at PLUMgrid, Inc., the leader of secure and scalable Container and OpenStack networking for companies building private and public clouds.  Wendy has participated in open source and standards activities for many years, and helped launch the IO Visor Project which is part of the Linux Foundation. Prior to PLUMgrid, Wendy worked for companies such as Cisco Systems, Juniper Networks, and HP.    An avid technology and user advocate, Wendy has 8 U.S. patents in networking technologies and is listed in the CCIE Hall of Fame.  She provides pro-bono consulting through Stanford Developing Economies and volunteers for STEM initiatives. Wendy has a BSEE/MBA, and is a graduate of the Stanford Executive Program from the Graduate School of Business.)*

* **Bryan Thompson** *(Bryan Thompson is a Sr. Director of Product Management at Rackspace and leads the product team for Rackspace Private Cloud.  Prior to joining Rackspace, Bryan served as VP of Product management at Tier 3 and held product and technology leadership roles at Limelight Networks and Amazon.com.  He brings over fifteen years of experience in technology building, deploying and operating solutions for the enterprise.)*

Containers and cloud security models
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the growth of the container movement and the interest from the OpenStack community in running containers, the challenges of securing the container environment are becoming more prominent – indeed, according to a recent survey by Cluster HQ, 60% of respondents mentioned that security was either a major or moderate barrier to adoption. This session will look at some of the challenges around the container deployment model, and talk about approaches that can be taken as part of a wider cloud security model to protect the container environment. This will include looking at some best practices in architecting the solution, as well as securely managing the applications and interactions


* **Simon Leech** *(Simon Leech is a Certified Information Systems Security Professional with a specialisation in Security Architecture (CISSP-ISSAP), Certified Information Security Manager (CISM), Certified in Risk and Information Systems Control (CRISC), Certified in Cloud Security Knowledge (CCSK) and Chief Technologist Security within the Hewlett Packard Enterprise EMEA Hybrid IT Team. Within Hewlett Packard Enterprise, Mr Leech is responsible for influencing and evangelising the security strategy of the Hybrid IT team. Simon is active on Twitter as @DigitalHeMan)*

How to futureproof your OpenStack Deployment to ensure compliance with GDPR
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

General Data Protection Regulation is here and it is law so come 25th of May 2018 you better have your things in order or it will hurt you pretty hard. There are severe penalties for breaking GDPR, 4% of your global turnover. You are affected even if your company outside the EU as long as you do business with EU citizens. Cloud is the magic bullet to solving your compliance issues but you need to run it correct to avoid the chopping block. We will look through OpenStack configurations and policies and have a look at what need to be done and what need to be changed. We will have a discussion what Privacy by Design means in terms of OpenStack. What can be done within OpenStack itself and what are appropriate step to take with other tools. How to set up a compliant architecture. All base on real case law. With this session we hope to bring GDPR from the lawyers and in to the datacenter. It is not just a legal discussion where it usually stops but most certainly a technical one as well.


* **Kim Hindart** *(Huge Open Source fan boy and developer. With a background in mobility and especially Symbian and Android. I am a really geeky dude that was forced to handle security and compliance so the only coding I do is on my spare time. Luckily that's also what I like to do in my spre time, work. But real work and not just a lot of complinace and regulations but something that is acctually for the betterment of mankind.  Unfortunately I happen to bee good at security, especially social engineering, and now I am stuck. But I am happy to share my knowledge and experience in making thins both secure and compliant. And no they are not alwas the same thing.  Compliance is solved through the cloud. Epecially smarter clouds. OpenStack is the key to this. OpenStack is 42 to compliance. One stack to forever in the darkness bind them.  )*

Automatic Secured Application Deployment in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud services by allowing mutualizing infrastructure makes them an attractive target for malicious users. It also creates new attack vectors between tenants. Most cloud providers offer default security policies that do not always fit tenants custom security needs. IQ-Orchestra is a user-centric approach proposing automatic deployment and securing of complex distributed applications on Cloud platforms. From a user-friendly high-level description of the application and its security requirements, IQ-Orchestra automatically computes security configurations according to best pratices and standards then orchestrates the deployment of the secured application in Openstack. During this talk, there will be a demonstration of a secured deployment with IQ-Orchestra on top of RDO illustrating the mitigation of top threats.


* **Haïkel Guémar** *(Haïkel is a long-time Fedora developer, where he actually serve as Fedora Engineering Steering Committee and Cloud WG member. He is part of the CentOS Cloud SIG member, where he maintains CentOS packaging for OpenStack. He is the former PTL and current core contributor for the RPM packaging project He works at Red Hat in the RDO Engineering team as one of the driving force for OpenStack packaging.  )*

* **Arnaud Lefray** *(Co-founder and CTO at Qirinus, Arnaud is working on innovative solutions for Cloud Security.)*

* **Eddy Caron** *(Eddy Caron is an Associate Professor at Ecole Normale Supérieure de Lyon and holds a position with the LIP laboratory (ENS Lyon, France). He is a Member of AVALON project from INRIA and Technical Manager for the DIET software package. He received his PhD in C.S. from University de Picardie Jules Verne in 2000 and his HDR (Habiliation Diriger les Recherches) from the Ecole Normale Suprieure de Lyon in 2010. His research interests include parallel libraries for scientific computing on parallel distributed memory machines, problem solving environments, and grid and cloud computing. He is involved in many program committees (as HCW, IPDPS, ISPA, HotP2P, etc.). Since 2000, he contributed to more than 29 articles in journal or book chapter and more than 60 publications in international conferences. He was co-chair of the GridRPC working group in OGF. He was coordinator of two french ANR project (LEGO and SPADES). He is the supervisor of 13 Phd (3 in progress). He teaches Distributed system, Architecture Operating System and Network, Grid and Cloud, etc. Moreover he was the Co-funder and Scientif Consultant of the SysFera company (2010-2015). he is the Co-funder and Scientif Consultant of the Qirinus company (www.qirinus.com). See http://graal.ens-lyon.fr/ ecaron for further information.)*

Simplifying Security Orchestration for  Multi-Vendor OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security is often deployed as multiple VNFs such as virtual firewalls, IPS, DPI, etc. in OpenStack clouds. A key challenge for OpenStack operators is to deploy and manage a broad portfolio of security services for virtual machines and containers to ensure data center resources are protected and always up to date. Simplifying the task of security orchestration is key and helps operators meet compliance. A multi-vendor security orchestrator to manage security services from a single pane of glass simplifies the task of managing security. Join this panel for the latest state of security, challenges, security use cases, architectures, and open source options for collaboration/community updates. Topics include: Use cases, challenges of deploying security at rate of cloud (1000s of VMs & containers) Requirements and approaches of orchestrating security   Service insertion, function chaining and impact to security


* **Erez Berkner** *(Erez Berkner, Director of Product Management for Data Center Security at Check Point(NASDAQ:CHKP), leads the company’s cloud security strategy. Erez joined Check Point in 2004 and has held key management positions in the R&D and Product organizations. As the Director of the Platforms organization, he led the development groups in building the Check Point vSEC product line for securing private and public cloud platforms.  Currently, he spends most of his time driving Check Point’s vision for securing the Software Defined Data Centers, Private Cloud & SDN, Public IaaS and Telco infrastructures (NFV). Erez holds a B.Sc. Cum Laude degree in Mathematics & Computer Science.)*

* **John McDowall** *(John McDowall is SDN/Virtualization Architect at Palo Alto Networks where he is working on the dynamic insertion of security policy into virtual environments and clouds. Currently he has been actively contributing to Openstack Service Function Chaining, Openstack Neutron-OVN and OVS/OVN to enable service function chaining. Previously he was at Cisco where he developed the programmable network architecture that played a key role in Cisco’s SDN strategy, which he presented to large customers and internally. He has presented to industry forums on web services, security, and SAAS. John has an MSc from UC Berkeley and a BSc from University of Glasgow.BD)*

* **Giuseppe de Candia** *(Based in Barcelona, Pino de Candia joined Midokura as a Software Engineer in late 2010. He helped build early versions of MidoNet and in 2011 started and managed the Barcelona-based Network Controller team. Over the next 3 years Pino helped grow Midokura's Barcelona office to nearly 20 engineers. From early 2013 through August 2014, Pino was VP of Engineering after which he transitioned to his current role of Chief Architect, responsible for MidoNet's overall architecture as well as the design of Midokura's Enterprise MidoNet (MEM). In late 2015, Pino also assumed the role of CTO. Prior to Midokura, Pino was in a number of software development roles. The most recent was at Amazon.com: first leading the team that developed Dynamo, a NoSQL data store; then managing an internal infrastructure software team focused on caching tools and systems. Pino did his B.S. and M.Eng. degrees in Computer Science at Cornell University.)*

* **Wendy Cartee** *(Wendy Cartee is VP of Product Management and Marketing at PLUMgrid, Inc., the leader of secure and scalable Container and OpenStack networking for companies building private and public clouds.  Wendy has participated in open source and standards activities for many years, and helped launch the IO Visor Project which is part of the Linux Foundation. Prior to PLUMgrid, Wendy worked for companies such as Cisco Systems, Juniper Networks, and HP.    An avid technology and user advocate, Wendy has 8 U.S. patents in networking technologies and is listed in the CCIE Hall of Fame.  She provides pro-bono consulting through Stanford Developing Economies and volunteers for STEM initiatives. Wendy has a BSEE/MBA, and is a graduate of the Stanford Executive Program from the Graduate School of Business.)*

* **Manish Dave** *(Manish Dave is a Platform Architect, working in Intel's Datacenter Platform Security Division. He has over 20 years of broad experience in networking and security. In his previous role as Intel IT Principal Engineer he was responsible for the network security architecture for Intel IT’s datacenters which host hundreds of applications on several thousands servers. Manish is very interested in software defined infrastructure and policy based networks; he has 5 patent filed in the areas of networks and security. Manish recently presented Tech-Talk "Intel’s Open Security Controller Platform: Bringing Advanced Security to OpenStack" at Openstack Austin summit and also presented a detailed talk at the OpenDaylight Summit 2015 on the topic of "Getting real with Policies for Software Defined Infrastructure”. He has broadly published articles and papers on topics of IT enterprise infratructure, networks, security and policy over the years. He can be reached at manish.dave@intel.com.)*

What can TLS/SSL do for you?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

What can TLS/SSL do for you? There’s a 100% chance you are already using TLS/SSL to protect your public endpoints in your production cloud in order to satisfy compliance and security needs. But TLS/SSL can do much more. In this session, we’ll explore the following: Certificate-based authentication from your browser, CLI, and middleware. Hence, eliminating the need for passwords. Single sign-on (SSO) to multiple regions or clouds. Service-to-service authentication and trust using certificates. Tokenless authentication and authorization to the Keystone APIs. Deployment options. The joys and pains of TLS/SSL. There will be demos! Yes, this is a show-n-tell session. We will show what you can do today and what you can do with the patches to be submitted upstream. This is an interactive session where audience participation is encouraged and greatly appreciated.


* **Guang Yee** *(I am the Tech Lead for HPE Helion OpenStack Keystone and a Core Contributor for OpenStack Keystone. I have been operating and hacking on Keystone ever since I joined HP Public Cloud in 2011. I wrestled with public key infrastructure (PKI) throughout my career and still have the scars to prove it!  )*

* **Sam Leong** *(I am a senior developer for HPE Helion OpenStack Keystone. I have been dealing with public key infrastructure (PKI) since my first job out of college when I joined RSA Security back in 1998. I was also one of the lead developers for Certicom’s MobileTrust service.  )*

Securing Microservices in OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As microservices grow, traditional firewall rules based on network ACLs are no longer scalable and fall short of providing fine-grained enforcement. Group Based Policy (GBP) is a flexible policy language that allows users to specify policy enforcement based on intent, independent of network infrastructure and IP addressing. Using micro-segmented virtual domains, administrators can define policies at a centralized location and use IO Visor technology for distributed enforcement. This provides infrastructure independent rules, template-based policy definitions, and scale-out policy enforcement for a solution that secures and scales with microservices.   The discussion will also cover using GBP for Cloud Foundry application spaces where microservices are deployed and need scalable, efficient security policies.    


* **Brenden Blanco** *(Brenden is part of PLUMgrid's tecnical team. He is involved in several open source products including IO Visor, he works on various areas of cloud networking assocaited with security, multi-tenancy and high avalability.)*

Scope in the token - A fire in the RBAC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Current OpenStack API protection model provides several ways to controll user access to different API's. However, only the default one is widely used and at least barely known. There are several not so obvious options to set up secure environments with flexible access control: - oslo.policy provides an interface to plug third-party application (such as Apache Fortress)  in and even store and operate policies dynamically - another approach is to handle separation of duties and enforce policies internally in keystone - no more scoped tokens. This one is under active discussion - your opinion is invaluable! Logically, provided keystone becomes a manager of service policies, it has everything to enforce API protection without the need to issue, pass and, consequently - validate authorization information (AKA 'token scope'). That, in turn, means OpenStack doesn't require tokens to operate! Let's discuss!


* **Adam Young** *(Adam Young is a member of Red Hat's OpenStack team and a core developer on Keystone, the identity management service for OpenStack. Adam has worked on various systems management tools, including the Identity Management component of Red Hat Enterprise Linux based on the FreeIPA technology.A 19 year industry veteran, Adam contributed to multiple projects, products and solutions from Java based eCommerce Web Sites to Kernel modifications for Beowulf clustering.  )*

* **Alexander Makarov** *(Alexander is a senior software developer in Mirantis with the responsibility to improve keystone and keep it fresh and healthy both in MOS and OpenStack itself. Joined the Community in 2014, has 10 years experience with commercial distributed computations systems development. Graduated Bauman Moscow State Technological University at 2004.)*

Using Existing Security Features for End-to-End Confidentiality and Integrity in the Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A recent survey by the Cloud Security Alliance indicated that cloud security is an executive- or board-level concern for 61% of companies [1]. Despite this concern, a significant number of security features are currently available in OpenStack and ensure the confidentiality and integrity of data across its services. This presentation starts with a short primer on information assurance (IA) and illustrates how OpenStack’s existing security features address common security concerns. In particular, we provide an overview of key management, image signing and encryption, block storage encryption, and object storage encryption. We show how these features individually and collectively secure data in OpenStack. This presentation concludes with an overview of ongoing efforts to add new security features and remaining gaps that should be addressed.


* **Joel Coffman** *(Joel Coffman is a Senior Cyber Engineer at the Johns Hopkins University Applied Physics Laboratory (JHU/APL), which he joined in 2012. Joel contributes to a variety of sponsored and internally-funded research and development projects where he applies software engineering expertise to improve software quality. Joel also serves as the technical lead for JHU/APL’s involvement in the OpenStack cloud computing project where he has overseen the contribution of a variety of security features to the community.Joel received his Ph.D. and M.S. in Computer Science from the University of Virginia under the guidance of Alfred C. Weaver and a B.S. in Computer Science from Furman University. While in school, Joel conducted research in topics spanning ranking methods for keyword search, search engine query log analysis, timing analysis, non-volatile memory, and computer science education. Joel’s Ph.D. research focused on keyword search in databases where he used a systematic evaluation of existing approaches to guide advances in ranking methods to improve search effectiveness.In addition to his work at JHU/APL, Joel serves as a lecturer in the Johns Hopkins University Engineering for Professionals program where he currently teaches software engineering.)*

PCI via Federation and Keystone
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The Payment Card Industry Data Security Standard (PCI DSS) define industry security standards around monetary transactions, specifically the handling of credit card data. There are many Identity Providers that are compliant with these security standards, and one can use Federation with Keystone to be PCI compliant. Within Keystone, you will find that we have added new PCI features in Newton. With the goal to eventually have OpenStack be PCI compliant out-of-the-box! Why is PCI DSS important?  All major credit card companies require services that process and/or store credit card data to meet PCI DSS security requirements.  Thus, if you are doing business in the cloud, you will have to meet these requirements. In this talk we shall discuss how to offload the burden of compliance with PCI DSS standards to other Identity Providers, what to do with existing user directories and how to accept the burden and still be compliant.


* **Boris Bobrov** *(Software developer with five years experience working in IT as a software developer, web developer and software engineer. Joined the OpenStack community in 2014. Currently works at Mirantis in the OpenStack Engineering team, focused on Keystone. Boris is actively working on Keystone Federation, Multi-DC support and support for large deployments for Mirantis OpenStack.)*

* **Kseniya Tychkova** *(Software developer with five years experience working in IT as a software developer, web developer, deployment engineer, integration engineer, and database administrator. Joined the OpenStack community in 2015. Currently works at Mirantis in the Enterprise Readiness Engineering team. The main goal of the team is to make OpenStack suitable for the Enterprise world. Areas of interests : Keystone, SSO (SAML), Kerberos, Apache Fortress RBAC System.)*

* **Ronald De Rose** *(Ron is an experienced software engineer at Intel, where much of his time have been focused on Identity & Access Management (IAM).  He is passionate about open-source software and has been an active contributor to the Keystone project.  Ron lives with his family in Arizona and enjoys playing basketball and tennis.)*

Trust-based delivery of sensitive material to a Virtual Machine or Docker Container
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Have you ever wondered how to validate that that a VM or the container being launched is trusted and secure before you push secrets and sensitive content to it?   Not only that, what if we can bind secrets so that they are only accessible on the specific server on which the container is running?   This turns out to be one of the key pain points and requirements for container developers.  This can be done today using Intel TXT, Intel Cloud Integrity Technology and TPMs on hardware. In this session Intel and IBM Security Architects will walk through the solution architecture with OpenStack and CloudFoundry and demonstrate how it is possible to:  Verify the integrity of the Docker platform on which the container image is being launched Verify the integrity of the container images being launched Release the secrets and keys based on the verification of this integrity Wrap the keys/secrets with the host platform TPM binding key so only that platform can release the keys/secrets


* **Raghu Yeluri** *(Raghu Yeluri is a Principal Engineer and lead Security Solutions Architect in the Data Center & Cloud Products Group at Intel Corporation with focus on virtualization and cloud security usages, solution architectures and technology initiatives. In this role, he drives security solution Pathfinding and development to deliver hardware-assisted security solutions that enable deep visibility , orchestration and control in multi-tenant Clouds.  Raghu is a regular technical speaker at conferences like OpenStack Summit, Intel Developer FOrum, VMWorld, on trust and security in Cloud computing, boundary control and Geo-fencing for sensitive workloads with OpenStack, and trusted docker Containers.  )*

* **Travis McPeak** *(Travis enjoys securing and breaking security of software equally.  He is a firm believer in the necessity of intelligent security automation.  When not working on security and software he enjoys snowboarding, travelling, and consuming quality food and beer.)*

Keystone and Barbican working together to improve Fernet security
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Fernet, Fernet, Fernet. Since the last Openstack release Fernet tokenshave been get a lot of attention. Key management is integral tosecurity with Fernet. Unfortunately this is left as an implementationdetail to be handled by the local devops team. Surely there is abetter way.This presentation will guide you through:      1. What is Fernet? Why should you consider switching to it?      2. How can Barbican improve the management of Fernet tokens.      3. What are the pros and cons of using Barbican. Is it more secure?      4. Proof of concept demo which will show Keystone using Barbican         for Fernet key storage and a tool to rotate the keys while         stored in Barbican.We will show that it is possible to leverage the Operator's investmentin HSM and Barbican to improve the security and management of Fernetwith minimal interaction with the Configuration Management system.


* **Sean Perry** *(Sean Perry has been a Linux and open source developer for the last 18years. Starting at a local ISP back in the modem days and then VALinux, he has since worked on iSCSI management, Xen, workstation DiskEncryption and Honeypot networks for Symantec, and now OpenStack atHPE. For the last year and a half Sean has been part of the HPE HelionOpenStack team working on Keystone.)*

* **Fernando Diaz** *(Fernando Diaz is an active OpenStack Core Contributor, focusing on Barbican Development. Born and raised in Miami, Florida, Fernando recieved his B.ASc. in Computer Science at Florida International University. Fernando is currently a Cloud Developer for IBM and works on Key Protect, IBM's Key Management Solution. Currently resides in Austin, Texas. He helps keep Austin weird.)*

Incident response and anomaly detection using osquery
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

  Attendees will learn about osquery and how it can be used to actively monitor an environment. The focus will be specifically around indicators of compromise and anonomly detection within an openstack environment. Additionally I will demonstrate how to extend osquery using osquery-python and write custom query packs to detect flaws. 


* **Grant  Murphy** *(Grant is a Seattle based security researcher and a member of the OpenStack Vulnerability Management Team.)*

Maintaining Privacy and Security on Your OpenStack Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack continues to evolve to the on-premises cloud of choice, it never hurts to review your deployments of OpenStack with a keen focus on Privacy and Security. This presentation will focus on these concepts and provide practical experiences from Enterprise users such as Technicolor. Peter Lopez III of Technicolor leads their corporate architecture team pertaining to Cloud Technologies and operational methodologies, including Cloud Security, and will explain what steps they take to maintain the security of their cloud, such as writing secure code, appropriate patch management, and making sure that development teams understand what's expected of them.


* **Bruce Basil Mathews** *(Bruce has been a Senior Solutions Architect in the computer industry for almost forty years, working at Information International, Inc., Symbolics, Inc. Prime Computers, Inc., Computervision, Sun Microsystems, Hewlett-Packard, and now Mirantis. During his career, Bruce has provided integration services, application development, and large scale deployments for major corporate initiatives at companies such as PayPal, Salesforce.com, Wells Fargo, McKessen, Intel, and Dreamworks, Technicolor, American Express, CitrixOnLine, and Amgen to name a few. Bruce became involved with OpenStack in 2010 as a member of Hewlett-Packard’s Public Cloud team where he successfully on-boarded more than fifty customers, migrating application services from in-house to OpenStack on versions from Diablo+ to Grizzly, living with them through the upgrade process. Bruce was also heavily involved with the initial release of HP’s Helion Openstack based on the Juno release. Bruce has maintained an active role in the OpenStack, Big Data and Open Source communities. He is certified as an Administrator for OpenStack, Cloudera, and MapR.Customer engagements have typically included technical design, build, implementation, customization, integration and ongoing administration of multi-vendor servers, storage, SAN and network elements, hosted on-premises, implemented as a managed service, and/or publically hosted in the cloud.  Successful implementations have generally included multi-vendor Operating Systems (Solaris, HP-UX, AIX, Irix, RedHat, Ubuntu, CentOS, Debian, Fedora, Windows and Mac,) multi-vendor databases (Microsoft SQL Server, Oracle, MySQL, DB2, Sybase, Informix, PostGres, GreenPlum, Vertica, Cache, etc.) and NoSQL offerings such as CouchBase, CouchDB, Cassandra, MongoDB, etc. Applications implemented and supported have included a wide variety of multi-vendor commercial and non-commercial applications such as Microsoft ERP, Data Warehousing and Business Analytics, SAP, Oracle Manufacturing and Financials, PeopleSoft, etc. and Big Data solutions such as Cloudera, MapR, HortonWorks, and the eco-system that supports them based on Six Sigma methodologies. )*

* **Peter Lopez** *(Peter leads corporate architecture for Cloud Technologies, Platform Development and operational methodologies at Technicolor. He has been responsible for architecting an SDDC implementation leveraging existing technologies and services while establishing cloud services both on premise and off. Prior to Technicolor, Peter led systems architecture and engineering at companies such as Walt Disney, Northrop Grumman, Nicholas Enterprises and Westfiled. Peter has spoken at conferences such as Citrix Synergy, DockerCon, Okta Oktaine, ArchiTECHS Spring Invitational and CloudStack Collaboration Conference.)*

Security Service Insertion and Security functions Orchestration without a SDN controller.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Inserting security functions like Next Gen firewalls in OpenStack requires service insertion capabilities which can be addressed either by SDN controllers natively or by using Networking SFC that is currently being developed. In this session we will discuss how the Open Security Controller uses a modular plug-in based approach for security service insertion. We will articulate what we see as gaps in OpenStack that need to be addressed in order to enable automated security service insertion without a SDN controller. Additionally we will demonstrate an approach we have used as a workaround and discuss how we plan to integrate with a fully functional networking SFC as it evolves.


* **Tarun Viswanathan** *(I am an IT practitioner in Intel's Network Platform Group and am responsible for working with Enterprise and Cloud end customers to define solutions architecture that helps accelerate the adoption of Software Defined Networking and Network Function Virtualization. I started my career as a Network Specialist responsible for configuration and management of Routers, Switches and Firewalls in the enterprise and then took on the role of a Security Architect responsible for Data Protection, End Point Protection and Cloud Security before moving to my current role as the Platform Solution Architect. I have three US patetns to my name and have been with Intel for over 16 years.  )*

* **Manish Dave** *(Manish Dave is a Platform Architect, working in Intel's Datacenter Platform Security Division. He has over 20 years of broad experience in networking and security. In his previous role as Intel IT Principal Engineer he was responsible for the network security architecture for Intel IT’s datacenters which host hundreds of applications on several thousands servers. Manish is very interested in software defined infrastructure and policy based networks; he has 5 patent filed in the areas of networks and security. Manish recently presented Tech-Talk "Intel’s Open Security Controller Platform: Bringing Advanced Security to OpenStack" at Openstack Austin summit and also presented a detailed talk at the OpenDaylight Summit 2015 on the topic of "Getting real with Policies for Software Defined Infrastructure”. He has broadly published articles and papers on topics of IT enterprise infratructure, networks, security and policy over the years. He can be reached at manish.dave@intel.com.)*

Leverage Ironic to secure bare metal service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Bare metal services in an OpenStack environment is traditionally not secure due to gaps in boot methodologies and mode of boot. Shared resources could expose unintended data breaches. Legacy boot of bare metal servers is unsecure due to possibility of altering of boot-time drivers. This unscrupulous activity could expose users to hacks and breaches. Bare metal service is exposed for exploitation due to the unsecure characteristics of PXE boot environment. Other aspect We explore how to secure it for enterprises using Ironic. Traditionally when a tenant is un-provisioned there are manual steps to make sure user data is scrubbed before allocating the same set of resources to another user/tenant. If these manual steps are not followed properly we could expose one user’s data to another leading to data breaches. Session will talk on how to offer bare metal as a service in secure and reliable manner for enterprise grade deployments. UCS policy framework will address each of these issues.


* **Vish Jakka** *(Vish Jakka is a Product Manager for Cisco Unified Computing System focusing on management and cloud solutions. He is responsible for the definition and lifecycle of solutions combining OpenStack and Cisco Data Center products that address a broad range of customer needs including cloud, virtualization, infrastructure, monitoring and management. He has held product management and engineering roles in data center compute, storage and services industry.)*

* **RAJESH KHARYA** *(https://in.linkedin.com/in/rkharya Experience Summary - • Product Feature QA/Testing, Product Feature Technical Escalation Support, System test, E2E testing & Solutions Engineering• large scale global data centre project implementation & operations experience catering to multiple business application environments on physical or virtual platforms with hosting solutions having 3000+ UNIX/Linux hosts Specialties - - Converged compute/storage/networking/virtualization management software feature QA/Testing- Open Stack, VMWare, vDVS, Private/Hybrid Cloud- Cisco's UCS product range and UCS management platform- Unix File system QA/Testing, System Test, Product feature escalation support- RISC based Unix platforms(HP/Sun/RHEL), Storage(EMC/NetApps/Veritas SF products) systems, clusters and network- P2V, RISC to x86 Migrations- Large scale Global Data Center project implementations, operations and planning- Building and Leading technical teams   Skill Sets - Data Center: Blade Enclosures & Servers(UCS), Unified Fabric, Ethernet, FCoE, VNTag, Virtual Port Channel (vPC), LLDP, DCB, DCBX, Converge Network Adaptor(CNA)Virtualization: OpenStack, VMWare, dVS, Private/Hybrid CloudClusters: Veritas Cluster Server (VCS), Sun cluster, HP’s MC/SG & Linux Clusters and VMware HA/DRServer System Mgmt.: UCS Manager, Compute - BIOS, BMC, IPMI, KVM, Firmware Management, System Integration Solution Testing, Fault Management, Host Boot Methods, Overall System DebuggingStorage: FC, FCoE, iSCSI, SAN, NAS (NFS), RAIDStorage Mgt.: Veritas File System/Cluster File System (VxFS), Veritas Volume Manager (VxVM), LVM & EMC’s SRDF/SEPlatforms: HP-UX, Solaris, AIX, Linux RHEL & SLESH/w: Cisco UCS Product Line – blade, rack servers, chassis, fabric interconnects, HP Blade Systems/rx/rp/SD, Sun Enterprise/Netra, IBM Blade Center/P-series, Cisco Routers 7200/3900/2900, Cisco Catalyst/Nexus 7K/5K/MDS, EMC/NetApp Storage ArraysLanguages: Shell scripting, Perl, Python and elementary knowledge of C   Professional Engagement - Technical Leader - Solutions Engineering (TME), Cisco Systems  )*

Improving cloud trust with the TPM
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most of what you've heard about the TPM is all about measurement and the difficulty of connecting it to cloud applicatons.  However, this talk won't talk about this.  Instead I'd like to concentrate on a couple of use cases where we can improve cloud trust by using the TPM.  Besides measurement, TPMs can manage and escrow secret keys (escrow means you can load a key into the TPM in a way it can never be extracted) and bind and seal secrets.  Some of the most significant cloud trust problems are how you load your keys and secrets into a cloud application in such a way that a hacker can't seal them.  This talk will present a practical use case for this for VPNaaS, which is likely to be the foundation for hybrid cloud.  We'll also discuss some of the limitations, like an escrowed key can only be uploaded to a single known TPM, which is tied to a physical system, so cloud use of the TPM presents placement and migration problems for cloud orchestration systems.


* **James Bottomley** *(James Bottomley is a Distinguished Engineer at IBM Research where heworks on Cloud and Container technology.  He is also Linux Kernelmaintainer of the SCSI subsystem. He has been a Director on the Boardof the Linux Foundation and Chair of its Technical Advisory Board. Hewent to university at Cambridge for both his undergraduate anddoctoral degrees after which he joined AT&T Bell labs to work onDistributed Lock Manager technology for clustering. In 2000 he helpedfound SteelEye Technology, a High availability company for Linux andWindows, becoming Vice President and CTO.  He joined Novell in 2008 asa Distinguished Engineer at Novell's SUSE Labs, Parallels (later Odin)in 2011 as CTO of Server Virtualization and IBM Research in 2016.)*

Bringing L7 Security to Kubernetes with OpenStack Kuryr
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We demo a solution for bringing L7 security to Kubernetes (K8s). Openstack Kuryr's new K8s components enable the placement of Pods on Neutron-managed networks, in turn enabling Neutron's service-chaining to redirect traffic to security Pods for inspection. The Neutron topology is inferred by Kuryr's K8s API Watcher from standard K8s models. We are proposing a small extension to K8s' new Network Policy template to map workloads to externally defined and named security policies. Our design leverages Kuryr's new CNI Driver and API Watcher "Raven", MidoNet Neutron Plugin, Forcepoint Containerized Next Generation Firewall (NGFW) and Intel Open Security Controller (OSC) as service orchestrator. In our demo: 1) An admin defines a DPI policy for traffic between Pods matched by label keys and values 2) OSC deploys a preconfigured containerized NGFW 3) OSC calls Neutron APIs to redirect appropriate packets into the NGFW 4) Layer 7 attacks are then blocked by the NGFW


* **Manish Dave** *(Manish Dave is a Platform Architect, working in Intel's Datacenter Platform Security Division. He has over 20 years of broad experience in networking and security. In his previous role as Intel IT Principal Engineer he was responsible for the network security architecture for Intel IT’s datacenters which host hundreds of applications on several thousands servers. Manish is very interested in software defined infrastructure and policy based networks; he has 5 patent filed in the areas of networks and security. Manish recently presented Tech-Talk "Intel’s Open Security Controller Platform: Bringing Advanced Security to OpenStack" at Openstack Austin summit and also presented a detailed talk at the OpenDaylight Summit 2015 on the topic of "Getting real with Policies for Software Defined Infrastructure”. He has broadly published articles and papers on topics of IT enterprise infratructure, networks, security and policy over the years. He can be reached at manish.dave@intel.com.)*

* **Giuseppe de Candia** *(Based in Barcelona, Pino de Candia joined Midokura as a Software Engineer in late 2010. He helped build early versions of MidoNet and in 2011 started and managed the Barcelona-based Network Controller team. Over the next 3 years Pino helped grow Midokura's Barcelona office to nearly 20 engineers. From early 2013 through August 2014, Pino was VP of Engineering after which he transitioned to his current role of Chief Architect, responsible for MidoNet's overall architecture as well as the design of Midokura's Enterprise MidoNet (MEM). In late 2015, Pino also assumed the role of CTO. Prior to Midokura, Pino was in a number of software development roles. The most recent was at Amazon.com: first leading the team that developed Dynamo, a NoSQL data store; then managing an internal infrastructure software team focused on caching tools and systems. Pino did his B.S. and M.Eng. degrees in Computer Science at Cornell University.)*

* **Binh Phan** *(Binh Phan is an accomplished networking and cloud security professional/evangelist with a proven track record of success and 20 years of experience in IP networking and information security field. His experience spans across a broad range of disciplines including network security operations, technical product marketing and solutions engineering. Binh's designed, implemented and supported large-scale networks for 1000s of world-wide customers including Fortune 1000 companies and tier-1/tier-2 service providers. He has a great passion for customer success, technology innovation and creativity to apply technologies to solve customer's business problems in the most optimal and cost-effective ways. In the recent years, Binh has emerged in the world of cloud and software defined infrastructure where he's spent time designing solutions for some of the largest customers and to advocate cloud adoption to help customers achieve business agility. His most recent works include designing and implementing security solutions for Openstack, Amazon Web Services and software defined infrastructure. Binh holds several industry-leading certifications including CCIE #16507, CISSP and GIAC GCIH. He currently works as a Senior Solutions Architect at Forcepoint LLC,  a cyber security company.)*

Security Group for Baremetal - How to ensure more safety and performance for baremetal servers?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session explains security group feature without performance degradation for baremetal servers. Currently Ironic and Neutron are working on implementation of multi-tenant network for baremetal servers. Having implemented the feature, tenant network for baremetals can be isolated each other in the same way as VMs. However there is a critical gap between baremetals and VMs in terms of security area in production environment. Baremetals does not have L2 layer security feature same as security group for VMs, that is to say baremetal cannot filter packets which sent from same subnet. Therefore, we propose security group implementation without performance degradation for baremetal servers.


* **Takanori Miyagishi** *(Software Engineer, Fujitsu Limited  )*

How to make legacy systems compliant without needing to change them by using smarter clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Regulatory agencies are launching new regulations and directives at a great pace. GDPR, NIS, Basel, Solvency are just a few that the EU are spitting out. The challenges are that how do you take the regulations and the laws and translate them into technical demands and solutions. Then how do you make your legacy systems that run as an internal organ in your organization compliant with modern standard. Often rebuilding them would be the equivalent of open heart surgery.  The solution is a smarter cloud. By utilizing the new features OpenStack has to offer you can keep your legacy systems and still be compliant.  We will take out important demands from all the regulations and map them against standards like ISO270xx. Then we will show you a high level architecture that is compliant for Internet banking within the EU. That standard will be good enough for most other applications as well. We will look at both tech and processes that are required.


* **Kim Hindart** *(Huge Open Source fan boy and developer. With a background in mobility and especially Symbian and Android. I am a really geeky dude that was forced to handle security and compliance so the only coding I do is on my spare time. Luckily that's also what I like to do in my spre time, work. But real work and not just a lot of complinace and regulations but something that is acctually for the betterment of mankind.  Unfortunately I happen to bee good at security, especially social engineering, and now I am stuck. But I am happy to share my knowledge and experience in making thins both secure and compliant. And no they are not alwas the same thing.  Compliance is solved through the cloud. Epecially smarter clouds. OpenStack is the key to this. OpenStack is 42 to compliance. One stack to forever in the darkness bind them.  )*

Simple, Scalable, and Secure OpenStack Clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Data is no longer confined to discrete physical servers in bunker-like data centers. With OpenStack,VMs containing sensitive data can reside on any number of physical hosts in any number of physical locations. This presents an issue, as many customers, e.g. financial or healthcare institutions, are bound by government regulations to prove that sensitive data is kept within specific geographic boundaries, and that the host running the VM is uncompromised. We’ll show how you can quickly and easily create, deploy and scale an OpenStack environment using Fuel plugins and Intel’s CIT (Cloud Integrity Technology) to establish and maintain hardware trust, and Citrix’ XenServer hypervisor to provide a verifiable host environment. Attendees will learn how hardware trust and hypervisor functionalities interlock to provide reliable security and automated policy compliance in OpenStack, and understand a toolkit for configuring, deploying and scaling trust-enabled clouds with speed and efficiency.


* **Abhishek Gupta** *(Dr. Abhishek Gupta is a Cloud Security Architect at Intel Corp, USA. In this role, he performs research and development of solutions for cloud security with focus on software defined infrastructures, containers, Docker, Mesos etc. He received his Ph.D. from the Department of Computer Science at the University of Illinois at Urbana-Champaign. His PhD thesis was focused on effective High Performance Computing (HPC) in the Cloud. Prior to that, he received a B.Tech and MS in Computer Science from IIT Roorkee, India, and UIUC respectively.)*

* **Bob Ball** *(Bob Ball is a Staff Software Engineer at Citrix Systems, where he has been working for 5 years - contributing to the XenServer integration with OpenStack since the Grizzly release.  In addition to managing the XenServer OpenStack team, Bob also has a strong focus on Partner integrations.)*

* **Irina Povolotskaya** *(Maintainer of Fuel Plugins SDK. Currently, drive different integration types like Fuel Plugins and OpenStack Drivers/Plugins validations. Constantly support dialog with Community to make the workflow clear, transparent and easy-to-go for contributors.)*

Project-Independent Key Management using Open Standards
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack continues to mature with an increasing number of security features that have the need to store secrets (e.g., encryption keys). Applying best practices for key management is a critical aspect of security. Unfortunately, the Barbican project for key management has not been widely adopted. The latest OpenStack user survey from April 2016 indicates just 2% of production deployments include Barbican. In this presentation, we introduce Castellan, a key management interface that takes the pain out of key management. We demonstrate Castellan’s seamless interoperability with Barbican and appliances that support the Key Management Interoperability Protocol (KMIP) standard. KMIP is an OASIS standard for key management that is already widely used within industry. Its support in OpenStack facilitates the inclusion of existing, hardened vendor solutions for key management as has been adopted by other commercial cloud providers.


* **Kaitlin Farr** *(Kaitlin Farr is a Software Engineer at the Johns Hopkins University Applied Physics Laboratory (JHU/APL). She has been contributing upstream to security-related features for OpenStack since 2013.  She is on the core team for the key manager project Barbican and the main contributor to Castellan, the key manager interface library. Kaitlin received her M.S. in Computer Science from the Johns Hopkins University and a B.S. also in Computer Science from Texas A&M University.)*

Recon security audit tool in OpenStack deployment and operation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

HPE security released the Recon tool for system audit and hardening.I'd like to show what are the good ways to apply it in cloud deployments.Specifically, why is it useful for spot checks on existing systems and for repeated tests in the QA pipeline, and why is it useful on virtualisation hosts and guests.This also explains why is it useful to talk about Recon in context of Openstack deployment and operation.I'll talk about why did we write a new tool and how does it compare to existing, known projects.I'll also show what does/doesn't Recon do compared to other security tools like rootkit hunters, integrity scanners, vulnerability scanners - and how can they integrate.


* **Stanisław Pitucha** *(Stan is a generalist with past experience in jobs ranging from microprocessor programming to web development and server automation. He works as a security engineer atHewlett Packard Enterprise and is one of the creators of the Anchor project. He's also extremely excited about the recent progress in unikernels and system containers.)*

Securing Intra-Cloud via Distributed Security - Contain, Block, and Neutralize Attacks Anywhere
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

While firewalls are effectively deployed for perimeter security across different cloud networks, the problem remains for securing traffic inside a cloud with multiple tenants. One way to address this is via distributed virtual security with policies that protect north-south and east-west traffic within a cloud. With overlay topologies, distributed virtual firewalls can be deployed in multi-tenant networks. With distributed virtual firewalls, operators can distribute, automate actions such as contain, block, redirect to neutralize attacks by bringing up firewall instances anywhere in a cloud. Topics will include:      Holistic solution approach: Multi-vendor Integration to deliver solutions faster        Securing north-south and east-west traffic      Role of overlay networks and micro-segmentation      Virtual security policies and distributed virtual firewalls      Deployment scenarios such as securing 3-tier applications      Demo of virtual distributed security


* **Ivan Bojer** *(Customer-focused technologist with 10+ years of diverse technology and leadership experience. Mr. Bojer is experienced in building new products and creating solutions that yield new product features in order to simplify complex use and increase adoption by customers and the channel. Ivan joined the ‘cloud movement’ because he sees how disruptive the cloud is in Enterprise IT with strong belief that cloud security is a complex subject that is just now emerging after being an afterthought for a longest time.)*

* **Siddharth Gogar** *(Siddharth Gogar has completed Masters in Computer Engineering from NYU Polytechnic School of Engineering and has received a Bachelor's degree in Electronics and Telecommunications from University of Mumbai. He is currently working as an SDN Developers in RackScale Platform group with Flex | Ciii. He was SDN intern at Intel Corporation working on enabling SDN and NFV solutions on Intel Architecture in Spring 2015 and Summer Technology Intern at AIG for developing dashboard for team leads of support team. He has previous experience of working in a team deploying OpenStack Cloud and managing Hadoop Clusters. His interests includes computer networks and cloud technologies and believes in the concept of 'Digital Sandbox' which helps in creating a test environment different from production environment where industry experts and fresh graduates can collaborate to learn new ideas and technologies. He also enjoys playing volleyball and ping pong in free time.)*

* **Jamal Arif** *(I am currently involved in building SDN based OpenStack Private/Public Cloud infrastructures for various range of customers including enterprises, telcos, & service providers etc. Working with Dev-Ops and Network Operations teams to design and implement highly available, scalable and secure multi-tenant cloud systems for different cloud computing models (IaaS, PaaS, SaaS), and using virtualization techniques for networks functions virtualization. Have earlier experiences in core IP and telecommunication networks (CS/PS Core networks and IP/MPLS Networks) working in a multi-vendor environment (NSN Rel4, Huawei R4, Cisco, Juniper). In addition have hands-on knowledge of NGN networks (3G, 4G LTE), and legacy 2G GSM TDM networks, and Core & IP signaling protocols.)*

Are your images Golden, Gilded, or Tarnished? Know what’s in your Glance Store.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are the images in your Glance store full of vulnerabilities? Where would you even start checking the mass of public and private images? At Symantec, we’ve built secure image management into our cloud from the beginning. Even at enterprise scale, we’re continually refining vulnerability scanning and image categorization policies. As we've moved to a hybrid cloud model, we've also built unified image management across the separate cloud providers. Development versus Production Images. Public, Private, and Community levels of visibility. All of these, and more, must be considered to ensure your images are properly secured. We will cover the following topics: How Symantec built its unified image management solution Different use cases and requirements for public, private, shared, and (coming soon) community images How to automate validation with an image release pipeline The tools to provide your users with to help them help you keep vulnerabilities from becoming security incidents


* **Brad Pokorny** *(Brad has been contributing to OpenStack since 2013 and is currently developing user interface solutions at Symantec. He is excited about improving user adoption of OpenStack within Symantec, pushing the limits of scaling in the cloud.)*

* **Timothy Symanczyk** *(Tim has been a professional software developer for 18 years, and is currently focusing on Glance within Symantec. His passion is developing bullet-proof software. He is relatively new to the OpenStack community, and is tremendously impressed at everything that’s been accomplished so far.)*

* **Richard Gooch** *(Richard is a Technical Director at Symantec.)*

Non-public public cloud with confidence
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Companies increasingly look at public clouds also to process highly confidential data. To facilitate this, public cloud providers need to invest into solid security protection. Security specifications in an isolated private environment are a challenge. For a public accessible environment they are a nightmare. In this session we will address security topics from the perspective of public cloud providers. After starting with common & best practices, like the importance of a central logging with a good set of queries and the use of VPNs to access internal networks & applications without exposure to public networks, we will have a look on security tools and frameworks, inside and outside the OpenStack ecosystem. Documentation, business processes and education are other important topics that need to be revisited in the context of security. The presentation will give a look behind the scenes of Open Telekom Cloud (an OpenStack based public cloud) with respect to those security aspects.  


* **Christian Berendt** *(Christian is the CEO and co-founder of Betacloud Solutions GmbH. He is one of the OpenStack Ambassadors, founded the OpenStack user group in Stuttgart / Germany and is part of the OpenStack documentation core reviewer team. In his  time off he occupies himself with software development, artificial intelligence, micro controllers and much more. He is a seasoned speaker at all kinds of Open Source and IT events such as CeBIT, LinuxTag, and various others. )*

* **Kurt Garloff** *(I grew up in Germany where I graduated in Physics at University of Dortmund. I moved to Eindhoven (The Netherlands) to do postgrad research on plasma physics.I had developed an interest in computers and in particular in the Open Source and Linux movements in parallel and had contributed some code successfully to the Linux kernel when the community was still small. I also succeeded contributing little pieces to a number of other projects (amongst which glibc and gcc).In the end the computer side won over physics and I ended up working for SUSE Linux AG (later part of Novell Inc) as a freelancer and quickly as employee.  I worked as kernel engineer but also took some responsibility in security projects. I ended up running SUSE Labs, where I had the privilege to work with some of the smartest engineers in our research department hosting the open source kernel, toolchain (compiler ...) and X11 engineers.Subsequently, I had a number of technical, people and business leadership roles (Head Architect, acting VP Engineering, VP Product Management, VP Business Development, VP Partner Engineering) and I'm grateful to Novell for sending me to the HBS Program for Leadship Development to enhance my business skills before taking over business management functions.The acquisition of Novell by Attachmate ended my career with SUSE and the next step was being part of the BU Cloud Services in Deutsche Telekom's P&I which had a lot of the startup spirit I was looking for... In my VP Cloud Technology function I headed the unit that developed the Consumer Cloud Storage platform (DLS/Mediencenter) and the OpenStack based hosting infrastructure for hosting the software partners' apps in DT's TelekomCloud BusinessMarketplace and I had the pleasure to present on this in a keynote in the San Francisco Summit.I supported Huawei's Enterprise IT R&D department to build a great cloud engineering team in Europe and to enhance the capabilities of Huawei's OpenStack based FusionSphere solutions in 2014/15. Since fall 2015, I have been supporting T-Systems with the launch and further development Open Telekom Cloud, a large public cloud in Europe based on OpenStack and developed in close collaboration with Huawei and the OpenStack community.PS: When I don't work on computers, I spend my time with my great wife and two wonderful kids.)*

Secure application deployment in the age of continuous delivery
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Traditionally, when datacentre operators talk about application security, there has been a tendency to focus on issues related to key management, firewalls and data access. By contrast, application developers have a security focus which is more aligned with code analysis and fuzzing techniques. The reality is, secure application deployment principles extend from the infrastructure layer through the application and include how the application is deployed. With the prevalence of continuous deployment, it’s imperative to focus efforts on what attackers’ view as vulnerable; particularly in an environment where new exploits are being disclosed almost daily. In this session we’ll present: How known vulnerabilities can make their way into production deployments How exploit impact is maximized through knowledge gaps A methodology for ensuring deployment of vulnerable code can be minimized A methodology to minimize the potential for vulnerable code to be redistributed


* **Tim Mackey** *(Tim is a Senior Technical Evangelist for Black Duck Software, and was most recently the community manager for XenServer and part of the Citrix Open Source Business Office. Tim has held roles in mission critical engineering, performance monitoring and large scale data center operations. He has spoken globally on a variety of topics, and at well known events such as OSCON, CloudOpen, Interop, CA World, Cloud Connect, and USENIX LISA.)*

Digital Forensics vs. OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The growing popularity of cloud technologies with an increased degree of cloud-based virtualization creates new challenges for the investigation of cyber attacks and early incident response. The modern cloud architecture dictates the requirements for the forensic investigation and incident response model should be: Scalable Elastic Easy to integrate and manage (integration with data and control plane) To address these requirements, the paradigm of Forensics-as-a-Service has been introduced in a number of scientific papers. And digital forensic tools for OpenStack (including the FROST project), have been created to provide trustworthy forensic acquisition of virtual disks, API logs, and guest firewall logs. We will discuss: Challenges to find digital evidence in a scalable cloud environment Practices for incident response in clouds Infrastructure solutions (network sniffers, IDS/IPS, malware sandbox) How to avoid cloud service standstill during forensic investigation


* **Johan Christenson** *(Johan Christenson has extensive experience in the online space and is the CEO of City Network that runs one of the larges public clouds based on OpenStack.)*

* **Anders Carlsson** *(Anders Carlsson, a Swedish Navy officer in past, is an author of a course in forensics. He gives lectures in Blekinge Institute of Technology and takes a position of a general manager of the ENGENSEC (Educating the next generation of security experts) EU academic project aimed to develop security courses for the Master program.)*

* **Mariano Cunietti** *(After serving for several years as an enthusiast Linux system administrator in an ISP environment, Mariano became CTO at Enter.it and in 2011 started the company first Openstack based project running on Essex (cloudup.it and selfserver.it) On August 2013 the first italian region for EnterCloudSuite.com (ECS) was launched. It was the first public IAAS running in Italy on Openstack, one of the first in Europe. On April 2014 the German and Dutch region followed. On October 2015, EnterCloudSuite was awarded by the EU Commission to be an official provider of public IAAS to the 52 EU Institution. Before running open source infrastructure, Mariano earned a Master of Arts in Classical Guitar, and almost one in Greek and Latin Literature. )*

* **Alexander Adamov** *(At Mirantis, Alexander writes security best practices for OpenStack engineers. He moved into cloud from information security, with more than ten years’ experience in the antivirus industry working for Kaspersky Lab and Lavasoft. Alexander is also a university lecturer developing new courses for EU universities, presenting lectures and trainings that address network security, reverse engineering, and malware analysis simultaneously. At present he is researching a PhD project related to cloud security and sandboxing.  )*

Smart Orchestration –Trusted Docker Containers with Kubernetes and Intel Cloud Integrity Technology
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

App Containers are very effective way to deploy applications abstracted from the underlying infrastructure. Kubernetes is one of the key container orchestration/cluster management software of choice. Security is concern with container technology, and many app container developers have key questions like:  “Are my approved and curated set of container images launched?”,  “Are my containers running on secure servers” “How can Kubernetes use platform (Host and Docker Engine) Integrity verification while scheduling my containers"                                                                                              If these questions are interesting and relevant for your work, than this session is for you.  The session will provide a Solution Architecture (and a Live demonstration) of how to integrate platform integrity assurance and  container image integrity with Kubernetes.   


* **Raghu Yeluri** *(Raghu Yeluri is a Principal Engineer and lead Security Solutions Architect in the Data Center & Cloud Products Group at Intel Corporation with focus on virtualization and cloud security usages, solution architectures and technology initiatives. In this role, he drives security solution Pathfinding and development to deliver hardware-assisted security solutions that enable deep visibility , orchestration and control in multi-tenant Clouds.  Raghu is a regular technical speaker at conferences like OpenStack Summit, Intel Developer FOrum, VMWorld, on trust and security in Cloud computing, boundary control and Geo-fencing for sensitive workloads with OpenStack, and trusted docker Containers.  )*

* **Ryan Savino** *(TBA..)*

OpenStack PKI is basically magic. Here’s some spells to get you started.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack clouds tend not to fit into traditional security architectures.  After all, the primary purpose of a cloud is to take external workloads and data and position them deep within your data center.   Any OpenStack cloud will be a composition of many interacting and optional services. These services often bridge security domains and networks. Over the last few releases, developers have worked hard to ensure that deployers have the option to secure individual connections between services with Transport Layer Security (TLS).  However,  this has left how to manage PKI, the fundamental system of certificates underpinning TLS as an exercise for the cloud operator.   In this presentation we guide the audience through a number of considerations and approaches to securing a cloud with PKI before exploring some specific reference architectures that we have created to make secure deployment easier for everyone.


* **Ade Lee** *(Ade works for Red Hat, and has been involved in Dogtag development (and its integration into FreeIPA) for a number of years now. He has worked to integrate Dogtag and FreeIPA with Openstack, and is a core contributor to the Barbican project. Most recently, he has worked on puppet modules to deploy Barbican in Triple-O and RDO.)*

* **Robert Clark** *(Robert is an IBM Distinguished Engineer, he helps drive security strategy across IBM's cloud portfolio and is the current PTL of the OpenStack Security team. His career has its roots in threat modelling, vulnerability analysis and virtualization security. He is passionate about security and driving up standards in OpenStack which he has been working on for the last four years.)*

* **Juan Osorio Robles** *(Juan Antonio (Ozz) is a member of Red Hat's OpenStack Identity team and a core developer onBarbican, the secret storage as a service solution for OpenStack; and TripleO (OpenStack overOpenStack), a cloud installer. In Red Hat, he has been actively working in TripleO to enable TLS in boththe public and internal services of the deployment.)*

Security on OpenStack: Best practices from Hypervisor to Tenant
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When you deploy OpenStack in an enterprise as a private cloud, the deployment is usually behind a firewall and inside the trusted network with existing systems. However, when you deploy OpenStack in as public facing cloud, no assumptions can be made regarding the trust level of the domains, and the list of attack vectors increases significantly. Such attacks might result in loss of data, functionality, and reputation. In this presentation we will discuss security best practices that should be applied to each and every OpenStack cloud, public or private. We will start you off with best practices that will help you secure your Hypervisors, and show you how to enforce security across tenants by creating and enforcing policies.


* **Chris Paquin** *(Senior Infrastructure and Cloud Consultant with over 15 years experience working with Unix, Linux, Virtualization, and Cloud. )*

* **Julio VIllarreal** *(Julio Villarreal is an RHCA with over 15 years of experience in Enterprise IT. Currently, he is a Sr. Cloud Architect in the Red Hat's Cloud Infrastructure Practice. In his role, Julio helps customers to architect and implement OpenSource cloud and virtualization solutions (e.g: OpenStack, Red Hat Enterprise Virtualization).Before joining Red Hat he worked for Oracle and Dell where he held different roles within the IT and Services organizations.)*

Smashing OpenStack for Fun and Profit!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The key to securing the underlying Openstack infrastructure is by first understanding the architecture and then by weaving the security layer into the build & Deploy process. Today we are going to talk about the Penetration testing phase and go over our methodology and cover some of our Zero Day Vulnerabilities (XSS, Access Control, Malicious File Upload, etc.) that we identified as part of this research. A Detailed Analysis of threats, vulnerabilities along with the Attack Scenarios to compromise your OS environment taking advantage of both known and zero day vulnerabilities like – leveraging Keystone Vulnerabilities to compromise OS, Compromising Standard Images and Application Packages, Weak Input Validation and Stored XSS on Contrail Networking Component. The talk will also focus on hardening recommendations like, How to diffuse these Attack Scenarios, How to monitor and identify threats in OS, Locking down Configurations and using the OS Security Guide as baseline.


* **Ganesh Devarajan** *(Ganesh is the Sr. Manager within Accenture’s Security practice Team. His focuses are Applications security, Network security, Malware Analysis, Reputation Service, and Cloud security.   Prior to joining Accenture in 2013, he led all of GoDaddy’s security products and helped architect a better security posture for their environment. He also worked as a security researcher for the TippingPoint DVLabs and The CASE Research Center in Syracuse, NY. He has publications in a variety of fields, ranging from Supervisory Control and Data Acquisition (SCADA) Securities, Role Based Access Control (RBAC), Wireless Securities, and Runtime Software Application patches. His research has been presented at various venues, including RSA, Department of Defense (DoD) Cybercrime conference, Computer Security Convention DEFCON, LayerOne, Reboot, National Petrochemicals & Refiners Association (NPRA), SMi, Hawaii International Conference on Social Sciences (HICSS), International Information Security Conference (IFIP/SEC), Hacker Halted, and Open Web Application Security Projects (OWASP). Ganesh has 5 patents issued and has 16 other patents in "patent pending" state all in the computer security space. Ganesh received a Masters Degree in Computer Engineering from Syracuse University and also, has an Executive MBA from Kellogg School of Business, Northwestern University.)*

* **Julie Ferranti Fitzpatrick** *(Julie Ferranti Fitzpatrick is Sr. Technical Director for AT&T Integrated Cloud organization, leading initiatives to provide Operational Support, Monitoring, Security and Resiliency of the AT&T Integrated Cloud solution. In support of AT&T’s Integrated Cloud (AIC), Julie leads engineers that are responsible for the development and delivery of monitoring tools, T4 operational support of OpenStack and Non-OpenStack components, Tenant Support and ensuring the infrastructure is secure. Prior to her move, Julie led multiple IT teams where she was responsible for development of AT&T’s Hosting & Application Services efforts for the commercial cloud solution along with the tools and Middleware technology.  She received a CIO award in 2011 for the creation of an innovative high performance compiler for ASCI application models that dramatically improved the performance of generated code thereby reducing required hardware by more than 50%. Previously, Julie’s management experience spans across multiple subsidiaries.  She worked as a Remote Maintenance Technician in Southwestern Bell Telecom where she handled all changes for Texas. Also, worked at Southwestern Bell Mobile Systems, where she held several roles of increasing scope and responsibility within mobility.  While in mobility, she gained extensive experience in leadership as well as supporting small and large customers for the external sales organization, local and wide area networking, IT development, voice routing on Nortel switches and vendor management.  While the teams were small, through collaboration and innovation they assisted in the start-up of Rochester, NY; Central Illinois (Cellular One); Jefferson City, MO and Cape Girardeau, MO market areas and celebrated 1M customers.  Julie started her career at Southwestern Bell Telephone in the Customer Service Bureau handling repair and 911 calls where she learned the company from the bottom up. Since 2009, Julie has been participating in the high potential Leadership program at AT&T.  She was selected by ranking in the top 10% of the company.  She is a member of OxyGEN, Women of AT&T and Women in Finance.  She serves on the AT&T Employee Network for Women in Technology and Network Collegiate Committee to promote women in STEM fields within ATO organization.  Julie volunteers to promote AT&T and STEM education and workforce development within and outside of AT&T. Julie holds a Bachelors of Science from Maryville University and a Masters of Computer Science from Webster University, both of St. Louis.  She and her husband, Tom, and kids, Evan and Madelyn, reside in St. Louis.)*

* **Chase Sylvester** *(Chase joined Accenture in May 2014 after graduating from Brigham Young University in IT with an emphasis in security. He is part of TVM and while at Accenture he has been involved in penetration tests and IT asset management projects. In the past Chase has worked with several companies to penetration test their applications and infrastructure. He has evaluated over ten vulnerability scanners including HP’s WebInspect, IBM’s AppScan, Rapid7 Nexpose, Accuentix’s Web Scanner, and WhiteHat Security.)*

Encryption & Compliance: Assessors at the Gates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Security remains a major concern for companies moving into the cloud, and Compliance frameworks frequently dictate architecture and security controls for a production deployment. In this talk Mike Lange, HPE Compliance Manager, and Nathaniel Dillon, HPE Security Engineer, will look at several compliance frameworks and focus on controls that give shared assurance, focusing on privacy and encryption. Specifically, Mike and Nathaniel will look at an OpenStack deployment that is leveraging Anchor for encryption in transit, Leeson for disk encryption, and Barbican for key management. The implementation details around key rotation and scale will be highlighted to outline both where these controls are called out and how to present them to an auditor. 


* **Nathaniel Dillon** *(Nathaniel Dillon is a security engineer at Hewlett Packard Enterprise, focusing on the Helion portfolio driving security through code review, vulnerability management, and more. He is a member of the OpenStack Security Project and core reviewer on the OpenStackSecurity Guide.)*

* **Mike Lange** *(Mike Lange is the Compliance Manager for HPE Helion where he utilizes his over 13 years of security experience to apply auditable processes and controls for Helion OpenStack.)*

Incorporating BSIMM for OpenStack Security
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Security is evolving slower than its components.  Especially OpenStack software need to be robust even when it is under attack. This calls for all organizations, groups and individuals agreeing on a common ground on OpenStack software security.  BSIMM fits that bill.  As BSIMM is measuring stick for software security, it will give OpenStack developers, users, IT managers and executives a non-subjective determination of where each component of OpenStack component stand individually and collectively. As most of the leading cloud and software companies are adoping BSIMM as a measuring stick for security, OpenStack development, deployment and management community will benefit in adoping BSIMM.  As BSIMM has evolved since late nineties and in its sixth major version with data from 78 leading firms, OpenStack community can leverage this collective work that is already done.  


* **Ravi Jagannathan** *(Ravi Jagannathan has 25 years of Computer industry experience. As a MS Cybersecurity graduate of NSA program, currently he is focusing on developing and deploying high performance, secure cloud.   Ravi is a hands on coder and is a project-lead.  His interests are Cryptography, Virtualiation, Cloud, Cloud-security, Secure Boot, protecting assets in private/public/hybrid cloud. He works extensively with developers, customers, partners, and VCs providing mentorship and leadership as a project lead, hands on technical manager, and second-level manager.  He continues to code in various languages. He has worked across various organizations in proposing and successfully defining and delivering products.)*

Fundamentals of Container Security
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk discusses the fundamentals of container security. Red Hat's global cloud strategy evangelist, Thomas Cameron, will discuss what a container is (architecture), what a container is not (mythbusting), what makes up container security, kernel namespaces (with examples), Linux control groups (with examples), the Docker daemon security tips, Linux capabilities and how they keep you safe, Security Enhanced Linux and how it keeps you safe (including a simulated exploit), and some tips and tricks regarding container security.


* **Thomas Cameron** *(Thomas Cameron is a Global Cloud Strategy Evangelist at Red Hat. He has been in the information technology industry since 1993, and has held certifications as a Novell Certified NetWare Engineer and a Microsoft Certified Systems Engineer/Trainer. Thomas is currently a Red Hat Certified Architect (RHCA), a Red Hat Certified System Administrator in Red Hat OpenStack, a Red Hat Certified Datacenter Specialist (RHCDS), a Red Hat Certified Security Specialist (RHCSS), a Red Hat Certified Virtualization Administrator (RHCVA), and and a Red Hat Certified Examiner (RHCX). He's been working with cloud technologies since 2010, and specializes in cloud security and integration.)*

Building OpenStack Securely: Architectural Recommendations From the OpenStack Security Guide
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Security Guide is the key reference to securely deploying OpenStack. Originally written as a collaboration between HPE, the NSA, and Rackspace, this guide has evolved with each OpenStack release and is now vital for anyone looking to deploy OpenStack in production. In this talk, Nathaniel Dillon, HPE Security Engineer and Security Guide core reviewer will step through using the Security Guide to deploy a hardened OpenStack cloud, highlighting the sections designed to assist in the architecture and planning stages, checklists for implementation and validation, and searching through the Guide for service and project-specific information when an issue arises. Nathaniel will then round up the session by covering future plans for the guide including the deploy checklists and project reviews where you can help contribute to the security of OpenStack through these specific domain sections.


* **Nathaniel Dillon** *(Nathaniel Dillon is a security engineer at Hewlett Packard Enterprise, focusing on the Helion portfolio driving security through code review, vulnerability management, and more. He is a member of the OpenStack Security Project and core reviewer on the OpenStackSecurity Guide.)*

Security - What's New(ton)
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The OpenStack Security Project is committed to increasing security upstream through tooling, code review, documentation, and more. This talk features Security Project PTL Rob Clark, Distinguished Engineer at IBM, and Nathaniel Dillon, Security Engineer at HPE, as they highlight the security additions for the Newton release and how they impact the community, including the new threat analysis efforts, project-specific additions, and an outline of the work that came out of the mid-cycle. Finally, they will end with current efforts and roadmaps for tools such as Bandit, and how you can increase the security and assurance of the OpenStack ecosystem across a wide range of opportunities.


* **Robert Clark** *(Robert is an IBM Distinguished Engineer, he helps drive security strategy across IBM's cloud portfolio and is the current PTL of the OpenStack Security team. His career has its roots in threat modelling, vulnerability analysis and virtualization security. He is passionate about security and driving up standards in OpenStack which he has been working on for the last four years.)*

* **Nathaniel Dillon** *(Nathaniel Dillon is a security engineer at Hewlett Packard Enterprise, focusing on the Helion portfolio driving security through code review, vulnerability management, and more. He is a member of the OpenStack Security Project and core reviewer on the OpenStackSecurity Guide.)*

The Boys RBAC in Town: Facing RBAC Challenges in a Large Enterprise Setting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Correctly implementing and setting Role Based Access Controls (RBAC) at a large enterprise scale can be daunting; member and admin roles just aren’t enough, but it’s not easy to ensure custom roles behave across all OpenStack services and conform to the added constraints of enterprise security compliance. This talk will guide the audience through the challenges and triumphs faced in properly implementing RBAC in the AT&T Integrated Cloud (AIC), as well as provide insight as to the future direction of RBAC.


* **Elise Eiden** *(Developer at AT&T working to expand the company's Community presence.)*

* **Doug Schveninger** *(OpenStack Agile Systems Engineer)*

* **Tin Lam** *(Worked as a software engineer / architect for the past 12 years and started cloud development/deployment about three years ago.)*

Key management infrastructure in OpenStack-based Cloud/NFV deployments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Encryption is the foundation of OpenStack environment for enterprises moving sensitive workloads to the cloud.  Keys are used for authentication and cryptography, but can become the weakest link in securing the workload, if not well secured.  HSM (Hardware Security Module) solutions can protect the Keys in traditional environments, but are not suitable in Multi-Cloud environment, as enterprises expect to control Keys, even if the workloads are running in various clouds.  Network HSM (appliance-based HSM) come to address Key security in Cloud environments.  Secure Key Management technology for Cloud deployments go beyond network HSM, addressing not only Key security, but also high-performance secure crypto execution, by keeping the Keys in a central vault, and distributing the cryptography execution closer to the workload applications.  This session proposes an architecture for secure Key management in OpenStack-based NFV/Cloud deployments.


* **Srini Addepalli** *(Srini is a key Intel contributor, and one of the principal architects of security technologies for the Network Function Virtualization (NFV) and Software Defined Networks (SDN) industries.  Srini previously served as fellow at Freescale (Now NXP) and CTO & Chief Architect at Intoto Inc.  He is a 22-year veteran in networking and data communications and his experience spans a range of areas from routing, switching and mobility technologies to network security technologies, including firewall, VPN, intrusion detection and antivirus technologies.)*

* **Naresh Kumar Gadepalli** *(Naresh primary focus areas are data and network security at Intel.  He has been working in the field of virtualization and security for more than 7 years now. He has graduated in Computer Science from IIIT, Hyderabad.)*

Security in the cloud
~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Today in PayPal private cloud we have several availability zones with 400,000 + cores and 150,000+VMs, security in the cloud is of paramount importance. Here we would to talk about what are different strategies and process which implemented to make cloud more secure. These includes not limited to the following Trusted control plane security  Access control  Password encryption of the services  SSL communications within the services  Centralized logging Security patching  When vulnerabilities are detected how we patch close 10,000+ hypervisors and 150,000+VMs and different OS matrix.


* **ramachandra vungutur** *(Rama has extensive working experience with different cloud stacks like IaaS and PaaS, his journey with cloud started in 2011 with OpenStack Diablo release and is continuing with Kilo and beyond. In this journey he played various roles as a manager and engineer, he is currently engineer in cloud infrastructure team responsible for cloud security and reliability.)*

Security-Aware Scheduling - Extensible security attribute management in Nova
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scheduling workloads based on Trust Attestation of hosts, Asset Tag/geo-tags stored on hosts, and other security attributes such as presence of security accelerators, etc  today requires calling into an external service to retrieve the host attributes.  This has serious consequences for performance and scale.  How can host security attributes be used for scheduling, securely and without impacting scalability or scheduling performance?   This session will detail the Intel Attestation Reporting Hub, which uses an extensible framework to securely push cryptographically verifiable host attestation attributes to the openstack scheduler, rather than letting the scheduler request attestations.  This works in conjunction with modifications to OpenStack Nova, which create new interfaces to receive secured host attributes from a trusted external source, and an updated Trust Filter, which uses the new local attributes for scheduling instead of making external requests.


* **Raghu Yeluri** *(Raghu Yeluri is a Principal Engineer and lead Security Solutions Architect in the Data Center & Cloud Products Group at Intel Corporation with focus on virtualization and cloud security usages, solution architectures and technology initiatives. In this role, he drives security solution Pathfinding and development to deliver hardware-assisted security solutions that enable deep visibility , orchestration and control in multi-tenant Clouds.  Raghu is a regular technical speaker at conferences like OpenStack Summit, Intel Developer FOrum, VMWorld, on trust and security in Cloud computing, boundary control and Geo-fencing for sensitive workloads with OpenStack, and trusted docker Containers.  )*

* **Timothy Knoll** *(Timothy Knoll is a Systems Engineer in Intel's DataCenter Group.  Tim has been working to develop and integrate Intel's Cloud Integrity Technology over the past four years.)*

A Security State of Mind: Continuous Security for Containers on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

With the rise of DevOps, containers are at the brink of becoming a pervasive technology in Enterprise IT to accelerate application delivery for the business.  When it comes to adopting containers in the enterprise, Security is the highest adoption barrier.  Is your organization ready to address the security risks with containers on your OpenStack environment?   In this presentation, you'll learn about: - The underlying technologies for Containers and how containers enable DevOps - The security risks with containers in the enterprise - The dangers of untrusted content and importance of maintaining container images - Automating vulnerability, security, and compliance checking for container images  - How to make your Container workflow more secure  Join, Chris Van Tuin, Chief Technologist, West at Red Hat, as he walks through the security risks with deploying containers and how to address these security challenges without slowing down the application delivery pipeline.  


* **Chris Van Tuin** *(Chris Van Tuin, Chief Technologist for the Western US at Red Hat, has over 20 years of experience in IT and Software.   Since joining Red Hat in 2005, Chris has been architecting solutions for strategic customers and partners with a focus on emerging technologies including IaaS, PaaS, and DevOps.  He started his career at Intel in IT and Managed Hosting followed by leadership roles in services and sales engineering at Loudcloud and Linux startups.  Chris holds a Bachelors of Electrical Engineering from Georgia Institute of Technology and found his passion in technology as a C and Smalltalk developer.  Chris presented at OpenStack Vancouver.         )*

Hide&Seek - Aggressive OpenStack security for operators
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack is a rich framework that offers lots of options in configuration, architecture and technology backends. With it, there is a lenghty list of vulnerabilities and common but unhealthy practices that can be exploited. Aggressive security defense means to not only secure our environment following the standard system administration guidelines for security, but also employ penetration tools to enhance our environment defenses. OpenStack does offer an array of tactics, projects and settings that can help us reduce existing vulnerabilities, provide forensic data and limit exploit damage.


* **Damia Pastor** *(Damia started as a sysadmin for a project related to Swift (late 2011) to then switch to StackOps, one of the first OpenStack distributions to deliver and operate projects from Brussels to Manila. After being in Mirantis for both EMEA and APJ, moved to HPE professional services working in production projects and helping create new solutions.)*

Security tools & validations for OpenStack clouds 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Enhance security levels while provisioning VMs to ensure that OpenStack services will work under hardened environments and generate a safe & reliable cloud. Certification Validation tests help in validating invalid system certificates & ensure that OpenStack services work fine when they are valid & reject requests when they expire. Token Validation: Longevity tests help uncovering bugs around token life cycle where a token expires & new token generation lead to failures. File Permissions/Sensitive Data tests to ensure that passwords & DB details are encrypted & not shown in logs. Security Hardening: Ensure that OpenStack services work in hardened environments.[Password policies,disable SSH,enforce SELinux] Best Practices: It is recommended to run the below scans against the code in order to strengthen the code at the build level and identify potential security related problems. Bandit Tool, Nessus Scan, RATs Scan, AppScan


* **Archana Prabhakar** *(Archana Meda Prabhakar has almost 9 years of experience in the IT industry and is currently working as a staff software test engineer in the virtualization management, cloud and software defined systems responsible for system & scale test, hardware planning and configuration. Archana's testing roles range from Functional verification test engineer , System verification test engineer, Scale and stress test engineer, Information development test as well as QA and Test Metrics Lead.  )*

* **Rajyalakshmi Marathu** *(Rajalakshmi has almost 10 years of experience in the IT industry and is currently working as staff software test engineer in the virtualization management, cloud and software defined systems responsible for security tests. Other testing roles include Functional verification test engineer , System verification test engineer.  )*

* **Divya K Konoor** *(Divya K Konoor has 12+ years of experience in the IT industry with around 8 years in Cloud Technologies and Systems Management. She has been working on IBM Power Virtualization Console product (PowerVC) the last few years in different roles and works on OpenStack Cloud Platform and is a contributor to different OpenStack projects (nova , keystone , ceilometer, pycadf etc) . Her interest areas include security, auditing, monitoring and serviceability.)*

Evolution of Open Security Controller: Effectively orchestrating multiple security functions.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Most large enterprises enable security in their data centers by deploying multiple VNFs from different vendors to ensure that a broad range of security threats are covered. For example they will deploy vIPS, vNGFW and vADCs and enterprise operations teams face a constant challenge to manage this broad portfolio of security services and define a service function chain that ensures data center resources are protected and always up to date. The Open Security Controller has evolved over the past few months to tackle this very challenge and simplifies the task of managing security by providing a single plane of glass to orchestrate multiple security services within Openstack. In this session we will describe and demonstrate how the Open Security Controller can orchestrate multiple security services and enable security service function chaining based on the defined policy.


* **Tarun Viswanathan** *(I am an IT practitioner in Intel's Network Platform Group and am responsible for working with Enterprise and Cloud end customers to define solutions architecture that helps accelerate the adoption of Software Defined Networking and Network Function Virtualization. I started my career as a Network Specialist responsible for configuration and management of Routers, Switches and Firewalls in the enterprise and then took on the role of a Security Architect responsible for Data Protection, End Point Protection and Cloud Security before moving to my current role as the Platform Solution Architect. I have three US patetns to my name and have been with Intel for over 16 years.  )*

OpenStack Auditing
~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation is intended to provide information on how the OpenStack auditing framework currently works inclusive of the support recently added over the last few releases on different non-core services; on pycadf and keystonemiddleware and exactly how auditing can be configured and used with ceilometer (including some RBAC support that was added to ceilometer couple of releases back). This is clearly for a beginner and intended for operators (cloud service providers) who need to keep track of all their audit data.


* **Divya K Konoor** *(Divya K Konoor has 12+ years of experience in the IT industry with around 8 years in Cloud Technologies and Systems Management. She has been working on IBM Power Virtualization Console product (PowerVC) the last few years in different roles and works on OpenStack Cloud Platform and is a contributor to different OpenStack projects (nova , keystone , ceilometer, pycadf etc) . Her interest areas include security, auditing, monitoring and serviceability.)*

Digital Forensics vs. OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The growing popularity of cloud technologies with an increased degree of cloud-based virtualization creates new challenges for the investigation of cyber attacks and early incident response. The modern cloud architecture dictates the requirements for the forensic investigation and incident response model should be: Scalable Elastic Easy to integrate and manage (integration with data and control plane) To address these requirements, the paradigm of Forensics-as-a-Service has been introduced in a number of scientific papers. And digital forensic tools for OpenStack (including the FROST project), have been created to provide trustworthy forensic acquisition of virtual disks, API logs, and guest firewall logs. We will discuss: Challenges to find digital evidence in a scalable cloud environment Practices for incident response in clouds Infrastructure solutions (network sniffers, IDS/IPS, malware sandbox) How to avoid cloud service standstill during forensic investigation


* **Johan Christenson** *(Johan Christenson has extensive experience in the online space and is the CEO of City Network that runs one of the larges public clouds based on OpenStack.)*

* **Mariano Cunietti** *(I am CTO and formerly Linux System Administrator. I have a strong expertise on Linux systems and a deep knowledge of technical issues within complex Internet structures: mail services, DNS, web services, RDBMS, networking, security. )*

* **Anders Carlsson** *(Anders Carlsson, a Swedish Navy officer in past, is an author of a course in forensics. He gives lectures in Blekinge Institute of Technology and takes a position of a general manager of the ENGENSEC (Educating the next generation of security experts) EU academic project aimed to develop security courses for the Master program.)*

* **Alexander Adamov** *(At Mirantis, Alexander writes security best practices for OpenStack engineers. He moved into cloud from information security, with more than ten years’ experience in the antivirus industry working for Kaspersky Lab and Lavasoft. Alexander is also a university lecturer developing new courses for EU universities, presenting lectures and trainings that address network security, reverse engineering, and malware analysis simultaneously. At present he is researching a PhD project related to cloud security and sandboxing.  )*

MineMeld: An Open Source Threat Intelligence Framework for Protecting your Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Threat intelligence(TI) programs are increasingly becoming part of a robust network defense strategy to protect your cloud. Threat intelligence provides the ability to recognize and act upon indicators of advanced targeted attacks and compromise. Operationalizing and incorporating threat intelligence information into your OpenStack security infrastructure remains a challenge due to its availability via multiple information sources (open source, commercial et al), formats and lack of universal translation mechanism that can be understood by security policy enforcement points (firewalls et al). MineMeld is an open sourced extensible threat intelligence processing framework that provides organizations the ability to ingest information about various indicators from multiple sources, aggregate them and deliver them in a standardized format.


* **Sai Balabhadrapatruni** *(Sai is a Senior Product Marketing Manager in datacenter and cloud security team at Palo Alto Networks. His specific interests include datacenter security architecture, OpenStack security, cloud security, security policy for SDN environments He supports Palo Alto Networks  Datacenter, Cloud, SDN, Enterprise Networks Architecture marketing activities. He has 15+ years of experience in the security, data-networking/telecom industry including software/hardware architecture, product marketing and product management. He holds B.E and M.S degrees in computer science and engineering.)*

* **Ivan Bojer** *(Customer-focused technologist with 10+ years of diverse technology and leadership experience. Mr. Bojer is experienced in building new products and creating solutions that yield new product features in order to simplify complex use and increase adoption by customers and the channel. Ivan joined the ‘cloud movement’ because he sees how disruptive the cloud is in Enterprise IT with strong belief that cloud security is a complex subject that is just now emerging after being an afterthought for a longest time.)*

* **Luigi Mori** *(Luigi Mori is a solution architect at Palo Alto Networks and the brains behind the MineMeld project. )*
