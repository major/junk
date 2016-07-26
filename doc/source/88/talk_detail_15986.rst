Creating a virtual data center with OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

When we decided to provide an OpenStack-based public cloud in multiple locations worldwide while maintaining some of our current infrastructure, we knew we would have a big problem to solve: how to alleviate data center hardware complexity. Buying a set of expensive core routers and $100K switches for each developer was not an option. Our solution was to write a complete set of mocking software for all the different types of hardware present in our data centers. Martin Roy and Jonathan Provost will explain how this virtual approach allowed us to quickly iterate through our OpenStack implementation while maintaining a completely automated software process. We will show how the system works and how it can be extended to fit a variety of developer needs.


* **Jonathan Provost** *(Jonathan is a lead developer for Internap.  Mainly focused on the architecture and development of the Baremetal public cloud solution based on OpenStack. He is also the team’s Scrum Master, involved in managing server delivery, backup and network automation. On top of internal responsibilities, Jonathan has also modestly contributed to the upstream Ironic project.)*

* **Martin Roy** *(Powered by Pepsi and classic Jazz, Martin is a coding ninja that is so versatile, he puts swiss army knives to shame.  Just after saying he's not good at something you know that he's gonna show you something about it that you don't know the next day. He's the man behind Netman, a network equipment abstraction layer used at Internap to configure the network layer for Internap's Baremetal public cloud solution.)*
