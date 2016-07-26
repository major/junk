Eliminating bottlenecks by rethinking storage design
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The traditional design of Distributed FS binds storage control nodes and storage media within a storage server, and connects storage servers by Ethernet networking. All of major DFS such as Ceph, HDFS and Gluster FS use the same design. Nowadays, this old design already constitutes the bottleneck of storage system. It is the time to rethink this old design, and make a change. SurFS introduces a new architecture. It separates storage control nodes from storage media but rather converges storage control nodes and compute nodes resulting in extremely short I/O path. SurFS also leverages SAS-3 networking which has very large bandwidth (up to 96Gb) and very low latency (a few microseconds) to constitute an ultra-fast storage system at low cost. Furthermore, this new architecture has a unique feature of globally shared storage pool. This feature enables RAID for DFS (instead of RAIN) to reduce 50%+ disks at same data durability, which is ideal for HA and enabling re-balancing in seconds.


* **Alex Wang** *(Alex is an excellent innovator. He was nominated as one of the Top 10 Youth Scientist by the Chinese central government in 2010. He was also recognized as one of the distinguished engineers (the only one coming from software and Internet industry) in China in 2014. Alex began to innovate on cloud storage systems in 2011. His first project SurDoc won the “Cloud Storage Excellence Award” by US Cloud Computing magazine in 2013, got 10M+ users worldwide within 2 years upon its service launched. Alex is founder of a Silicon Valley company SurCloud. He is also 1st inventor of 100+ patents worldwide.    )*
