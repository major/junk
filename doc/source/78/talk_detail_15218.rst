Centralized Quota Management with Kingbird
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Multiple regions. Centralized Keystone. Fragmented quota management. Sounds familiar? Currently quotas are defined on a per-region basis. The fact that quotas are split accross Nova, Neutron and Cinder complicates things even further. All this makes it hard for operators to provide flexible resource allocation for users across regions. So what can we do about it? In this session we will show our approach to solving quota management in multiple regions, which is based on using the existing OpenStack APIs and doesn't require any modification of the existing compute, network and storage services. We will also introduce a new OpenStack project "Kingbird" that provides implementation of our ideas.


* **Dimitri Mazmanov** *(Dimitri is a systems engineer in Ericsson specializing on the topics of cloud management and orchestration. He has a degree in Electrical Engineering and Distributed Systems. Dimitri works on the NFV related topics in OpenStack. He's a core comitter in the OPNFV Multisite project and core developer in OpenStack Kingbird. He's not a terrible musician, and loves playing drums whenever he's got time for it.)*

* **Ashish Singh** *(Ashish is a software engineer working for Ericsson. He's a core developer in the Kingbird project, working on the use cases of multisite OpenStack deployments. He has worked on deploying private cloud based on openstack grizzly. Worked on automated VM migartion across hypervisors and across clouds(AWS => OS & viceversa), p2v, v2v, v2cloud migrations.)*
