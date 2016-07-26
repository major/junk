Hyper-Converged Red Hat OpenStack Platform and Red Hat Ceph Storage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This presentation describes how to deploy Red Hat OpenStack Platform and Red Hat Ceph Storage in a way that both the OpenStack Nova Compute services and the Ceph Object Storage Daemon (OSD) services reside on the same node. A server which runs both compute and storage processes is also known as a hyper-converged node. There is increasing interest in the field for hyper-convergence for cloud (NFVi and Enterprise) deployments. The reasons include smaller initial deployment foot prints, a lower cost of entry, and maximized capacity utilization. The presentations covers the customization of TripleO and Ceph-Ansible to produce a completely automated hyper-converged deployment which supports adding new nova/osd servers, configuration updates and software upgrades. It also covers tunings made to the system in order to improve performance and isolate resources with NUMA. These tunings are then applied in an automated fashion using the same techniques covered in the configuration section.


* **John Fulton** *(John Fulton works in Systems Engineering at Red Hat and focuses on OpenStack and Ceph integration with TripleO and Ansible. He has spent the past six months focused on hyper-converged OpenStack/Ceph deployment; i.e. running Nova Compute and Ceph OSD services on the same servers. Prior to joining Systems Engineering John worked with customers in the highly competitive Financial Services Industry as a technical resource to build private clouds based on Open Stack. He blogs at johnlikesopenstack.com.)*
