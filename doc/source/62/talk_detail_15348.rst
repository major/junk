OpenStack Director using Opendaylight to manage underlay and overlay networking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In this session, we’ll demonstrate how to use OpenStack Director (OSP-D) along with Opendaylight (ODL) controller to exploit a full-fledged stack. OSP-D is an OpenStack installer introduced with Kilo-based RH-OSP-7. ODL is a software-defined network (SDN) controller and is used here to manage both underlay and overlay networks, enabling different OpenStack components to function in harmony with each other. Open vSwitch Database (OVSDB) clustering in ODL can be used to achieve highly available infrastructure. You’ll also see OpenFlow rule modifications that allow the underlying Kernal-based Virtual Machines (KVMs) to communicate with each other. We’ll show how the east-west and the north-south traffic flows in such an implementation on the overlay network, and how the transition happens from L2->L3 from the overlay-underlay network using openflow table transitions. An add-on to this demo will be learning to use Ansible Tower to job-schedule various steps of OSP-D installation.


* **Anand Nande** *(Senior Technical Support Engineer at Red Hat and a Cloudophelic who loves to learn and experiment with various upcoming technologies to develop better solutions to migrate the physical workloads to cloud.)*

* **Janki Chhatbar** *(Janki Chhatbar currently works as software engineer in RedHat. She has experience of working with different SDN controllers, OVS switches and OpenStack. She is contributor to OpenStack Tacker. She writes about different technologies including Docker at simplyexplainedblog.wordpress.com.  )*
