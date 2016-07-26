'Stacked Storage with Ceph at CERN: Glance, Cinder, ... Manila?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CERN IT has been operating Cinder and Glance services, backed by Ceph, for close to three years. The technologies involved have demonstrated their flexibility when building higher-level IT applications (we now host more than 2200 Cinder volumes). So the obvious question is... what's next? On the one hand, both the growth and age of these services has required us to refresh the hardware behind our largest Ceph cluster. We'll present how we transparently doubled of largest Ceph cluster to six petabytes. On the other hand, we have recently started evaluating CephFS for HPC use-cases. Though it's still early days, the initial feedback from users has been positive, and we've therefore wondered: if our CephFS/HPC tests are successful and we decide to open it as a wider service, then could OpenStack Manila help use manage a large, multi-user CephFS system?


* **Dan van der Ster** *(Dan is a Storage Engineer and Ceph Manager in CERN IT's Storage Group. Prior to working on storage, Dan worked in Grid Computing for the ATLAS experiment at CERN. Dan earned a PhD in Computer Engineering at the University of Victoria in 2008.)*
