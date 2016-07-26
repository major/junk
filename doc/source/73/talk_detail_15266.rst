Doppelgänger - Towards Disaster Recovery Support in Ceph
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceph is a highly scalable distributed storage system and the heart of SUSE's software defined storage solution. Ceph clusters are usually deployed in single site. Although a multi-site configuration is also possible, it may hurt the overall performance due to the conjunction of strong consistency and high-latency channels. Disaster recovery (DR) is an imperative feature for maintaining critical data safe. In the newest version of Ceph (codename Jewel), a solution for disaster recovery support was designed and implemented for the block device interface, and named as RBD Mirroring. The approach to support DR is based on the asynchronous propagation of block device operations to a remote (geo-distant) site. By being asynchronous, the operation mirroring does not interfere with the critical path of the primary site functioning, and thus the performance penalty becomes negligible.


* **Ricardo Dias** *(Ricardo Dias is currently a senior software engineer at SUSE Enterprise Storage Team working in the development of Ceph a distributed storage solution. Previously, he was a researcher in the areas of concurrent programming and distributed systems, published several scientific papers, and received a doctoral degree from NOVA University of Lisbon.)*
