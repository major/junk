Is OpenStack Neutron production ready for large scale deployments?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Neutron with ML2 OVS has always been a challenging component in terms of performance and scalability. However, in recent releases, several enhancements and bug-fixes have resulted in significant improvements in overall reliability, performance and scalability of Neutron. In this talk, we will share the results of our testing (both control-plane and data-plane) at large scale and provide a detailed data-driven analysis that explores the true scale limits and bottlenecks of Neutron. We also discuss better ways to tune Neutron configuration parameters for large scale. Moving forward, we expect further improvements based on planned optimizations. With these changes, is Neutron ready for large-scale production deployments? If customers are planning to deploy vanilla Neutron in their production deployments, what can they expect? How does the reference implementation stack up against other commercial alternatives? These are some of the questions the presentation tries to address.


* **Oleg Bondarev** *(Oleg Bondarev is a Senior Software Engineer at Mirantis working on OpenStack Neutron both in upstream and in Mirantis OpenStack (MOS). He started contributing to OpenStack in Havana release where he took an active part in development of LBaaS v1.0. In Icehouse he became a Neutron Core Team member and now his main focus of contribution is Neutron stability, scalability and performance.)*

* **Satish Salagame** *(Satish Salagame is the Director of Engineering, Networking at Mirantis focused on OpenStack networking, Container networking, SDN and NFV solutions. Satish is a seasoned technology professional in the Networking industry with strong experience in Software Design/Development, Solutions integration, Network Architecture, Product Management, and Engineering Management. Prior professional associations include several startups, StrataCom, Cisco Systems, Calient Networks and Infinera among others.  )*

* **Elena Ezhova** *(Elena has been working on OpenStack since Grizzly release and has contributed to such projects as Neutron and its advanced services, especially Octavia, LBaaS, as well as VPNaaS, Oslo, Tempest and Keystone. She was responsible for graduating the oslo.service library and currently is a member of its core team.)*
