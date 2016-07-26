Cisco Intercloud migration from Ceph to Swift while in production
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This is the story about how Cisco Intercloud migrated from Ceph Rados Gateway (RGW) to OpenStack Swift while in production and without service interruption. To prepare for the migration we collected vital data in the Cisco labs on storage requirements, throughput, latency, etc. A migration plan including all dependencies, such as RGW, Swift, networking, load balancing, SSL termination, Keystone endpoint switch-over and data migration was created. If any of these things weren't planned in detail, a seamless cut-over could not be guaranteed. The SwiftStack data migrator and cluster shunt middleware were key components to the migration. The migrator maintains thresholds to make sure the data movement won't hurt throughput in the Ceph cluster. The SwiftStack shunt middleware allows RGW and Swift to co-exist and ensures service during the cutover period. Throughout the migration, monitoring is watching the status of both Ceph and Swift, providing status reports of the migration progress.


* **Johnny Wang** *(Johnny is currently a Sr. Cloud Storage Engineer in Cisco Inter-Cloud and as the leader of Object Storage architects.  Prior to joining Cisco, he spent four years building a File Sync and Share system base on Object Storage in Hewlett Packard Enterprise after spending over nine years in a variety of design and development engineering and manager roles in Quanta Computer Inc. Johnny holds a BS and MS in Management Information System and is working as Ph.D candidate in Computer Engineering from Santa Clara University in California.)*

* **Martin Lanner** *(Martin Lanner is an Engagement Manager at SwiftStack. SwiftStack is a technology innovator of private cloud storage for today’s applications, powered by OpenStack Swift. Martin has been working as an entrepreneur and specialized IT consultant involved in OpenStack projects. Martin is active in many large Swift deployments with SwiftStack customers worldwide.)*
