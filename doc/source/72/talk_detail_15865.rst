Neutron at CERN: moving thousands of production nodes from Nova Network
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

CERN has been running a production OpenStack Cloud for several years. It was based on Nova Network from the start, with a few changes on the upstream code to adapt to the specifics of our internal networking infrastructure. With more than 6000 hypervisors split in tens of cells, 20000 virtual machines and an heterogeneous setup (KVM and HyperV) moving to Neutron with minimal disruption to users posed a significant challenge. In this talk we'll describe the Neutron plugin we wrote to integrate with our infrastructure, and additional extensions added to take into account network partitions (now covered with the upcoming segments feature being added upstream). We'll cover how we deployed Neutron and how we first enabled it in new cells, and later migrated existing cells once we were confident with the setup and sure it would scale. Finally we'll cover the new features we're looking into or have already enabled, such as Floating IPs, LBaaS and others.


* **Ricardo Rocha** *(Ricardo Rocha is a software engineer at CERN. He's currently a member of the CERN OpenStack team, focusing on service and application orchestration and container deployments. Previous work included development of data storage, bookkeeping and monitoring services for the LHC Computing Grid (LCG).)*
