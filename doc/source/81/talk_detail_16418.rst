Best practices for using containers to simulate Computes for scalability testing  of Openstack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scalability testing of OpenStack require huge number of baremetal computes.Addition of more bare metal computes for meeting increased simulation demands is redundant in the long run.A cheap alternative required to do control path testing and data path testing . Docker containers can help in simulating computes : 1. Using a single baremetal server , user can create 100+ containers2. Each of these containers is used to simulate compute nodes by installing required openstack components/services on it.3. On simulated computes lightweight VMs are spawned4. Effectively we can create 100+ computes using a single baremetal server. This session will present following: 1. How one can use Docker containers to simulate computes.2. Using this environment, test the scalability limit of cloud infrastructure 3. Using this environment, perform VM lifecycle operations.4. Test datapath of simulated VMs    


* **Alok Maurya** *(Working as  Sr. Software engineer at  HPE . I and  responsible  for  performing scalability  testing of  HPE Helion  products . I have  been actively involved  in  contributing in upstream  in  different  projects networking-l2gw , monsaca , tempest .)*

* **Ashish Gupta** *(I'm working with Openstack more than 4 years. Now I'm Senior Software developer at Hewlett Packard. My main interest is in Cloud computing especially OpenStack .Contributed my work in neutron related project such as vpnaas,lbaas,fwaas , networking-l2gw ,automation (tempest), ironic baremetal networking provisioning mech driver implementaion,monasca-agent ovs/libvirt plugin  implementation and testing.Currently involve in automating monasca-agent ovs/libvirt plugin.)*

* **Rajkumar Thiyagarajan** *(I am  working as  Sr. Software engineer at HPE , I  work  on  scalability testing of  products.)*
