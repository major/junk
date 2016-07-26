Geographically resilient Object Storage with Ceph Radosgw
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Radosgw (RGW from here on) is Ceph's Object Storage frontend providing an Openstack Swift and Amazon S3 like api.It also integrates with Openstack Keystone for identity management, making it a good candidate for object storage in Openstack deployments. DR strategies are essential in ensuring that critical data is never lost. With the latest version of Ceph (Jewel) active-active multisite RGW has been implemented, allowing writes to any of the remote clusters, allowing for data and metadata to be recovered in case of a datacenter loss. Data writes are async, allowing for this to happen without taking a major performance hit.In hopes of clearly representing the place of RGW in Ceph & Openstack ecosystem, we'll look into the current status of  Multisite in Ceph and look into the internals and architecture of RGW, how objects are stored internally, synce'd across a  remote cluster and the various caveats and troubleshooting tips based on our work with RGW.


* **Abhishek  Lekshmanan** *(I'm a Software developer working on Distributed storage and related management tooling. I've been a contributor to the Ceph project for the past 2 years now, primarily on Object Storage, and have also made various fixes to Openstack keystone integration with Ceph's Object Storage. I was also one of the authors of ceilometer plugin for Radosgw. I'm also interested in operations and deployment of distributed systems in general)*

* **Karol Mroz** *(I'm a Software developer working on Distributed storage @SUSE, I've been a contributor  to Ceph for over an year now, primarily focusing on Object Storage. I've previously worked on security architectures, high availability and reliability for systems and networks, networking and protocols (TCP, SCTP, SIP).)*
