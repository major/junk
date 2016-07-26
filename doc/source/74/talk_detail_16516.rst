Vendor-neutral distributed Multi-Site OpenStack cloud architecture
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Many customers today are looking for distributed OpenStack cloud architecture spread across multiple data centers. Key aspect is vendor-neutral and no lock-in cloud. The solution is to have the OpenStack control plane with required common services in each data center and have a separate region for each vendor. Each region runs OpenStack services like Nova, Neutron, Cinder, Heat etc. from any of the OpenStack vendors and these services will be registered in common Keystone. Another approach is to have two independent clouds running OpenStack, with federated Keystone services which will be LDAP or AD integrated. WebSSO enabled for Horizon for seamless sign-on to multiple regions. Swift Container Synchronization can be used to ensure mirrored copies of data. Glance using Swift as storage backend, will have access to the mirrored copies of images. Presenters:  Subhrangshu Kumar (subhrangshu-kumar.sarkar@hpe.com) Sudhindra Subbarao (sudhindra.s@hpe.com) Sunitha K (sunitha.kannan@hpe.com)


* **Sunitha Kannan** *(Working at HPE India, Global Solution Engineering team. Have 15+ years of experience in IT. Core expertise is in OpenStack Cloud and Storage. )*

* **sUdhindra Subbarao** *(Sudhindra Subbarao is the EMEA Region lead for the NFV POC COE works out of Grenoble, France. 11 years of experience in various roles – Development, Program management, Presales, Solutioning and Consulting. Recognized expert in Openstack, Cloud & Automation and Licensing domain.  Responsible for solution designing, deploying and demonstratng Carrier Grade POCs for various Telcos in EMEA and APJ.  Also responsible for solutioning Cloud brokerage solutions through a market palce portal (HP CSA /OO) to consume hetergoenous clouds spanning across private and public cloud providers. Be it AWS, Azure, HPE Helion or IBM Softlayer. And providing Technical Leadership in the area of Openstack, Cloud and Automation for Enterprise, Financial isntitution and Telcos.)*
