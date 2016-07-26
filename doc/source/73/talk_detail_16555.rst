Bring your own backup vendor!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

We are proposing a backup service with RESTful interface to discover instances, create guest quiesced, CG snapshots of Openstack instances that can be read out for backup, archiving, DR. The APIs would allow any backup vendor to read vdisk snapshots, block map, changed blocks (since previous backup) from outside of Openstack over HTTP(S) by a backup vendor or from within a service running in Openstack (for existing backup drivers). The proposed backup service would internally communicate with nova for discovery and taking instance level (image) snapshots. The service would mount cinder snapshots as block devices over different protocols, e.g. Iscsi, SAN, librados etc. to local system as it does today and would expose them over RESTful APIs. Eg. A snapshot read interface would look like : “https://<IP>:<PORT>/backup/v1/read/<vdisk snap id>” along with POST data containing a list of offset,length pairs for vdisk blocks to be read.


* **Ketan Mahajan** *(A software professional with 9 years of experiance on storage technologies. Currently working with Veritas on OpenStack storage technologies.)*

* **Ravindra Teli** *(A software professional with 17 years of experiance on storage technologies. Currently working with Veritas on OpenStack storage technologies.)*
