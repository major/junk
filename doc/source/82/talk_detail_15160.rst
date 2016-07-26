From Tempest to Neutron - Test migration from Tempest to OpenStack Projects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As OpenStack keeps growing and there's an unknown number of yet-to-come related projects, there has been a need to move API and Scenario tests from Tempest to their own projects, using tempest.lib and its stable interfaces in the process. One of the main advantages is that tests are now tied to their projects and the reviews could be directly done by developers with deep knowledge about their project, making the review process more efficient and fast. However, this process has also been proven to be challenging, as the migration implies being familiar with three key elements: Tempest Plugin Tempest.lib Stable Interfaces The OpenStack project itself In this talk we'll: Describe the current status Talk about the advantages of moving test to projects, and how to handle that Describe a real-life example about how this has been done for Neutron scenario tests and how we'll apply that experience to other projects


* **Genadi Chereshnya** *(Openstack Networking Senior QE Engineer)*

* **Itzik Brown** *(Openstack Networking Senior QE Engineer)*
