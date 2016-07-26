Enhanced Platform Awareness (EPA): boosting dataplane performance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Network Function Virtualization (NFV) is all about deterministic, maximal network packet processing performance. The Openstack community has implemented various technologies towards this goal, but those need carefully configured and combined to be effective. This talk will show how to configure Openstack to provide this performance for NFV workloads using Enhance Platform Aware (EPA) features already available, such as CPU pinning, Huge Pages, PCI pass-through and Single Root I/O Virtualization (SR-IOV), showing best practices applied in Telefonica NFV Reference Lab with Red Hat OpenStack Platform. NFV workloads require to assign dataplane interfaces to guests in order to maximize Virtual Network Function (VNF) performance. This is usually accomplished by allowing the VNF to rely on DPDK technologies, alone or in conjunction with the pass-through of physical and virtual functions (the latter commonly denominated SR-IOV) from the host to the VNF guests.


* **Ricardo Noriega** *(Ricardo is a Software Engineer in the Office of Technology working as NFV Partner Engineer at Red Hat. He's been doing R&D related to OpenStack for the past three years. He is passionate about new technologies (NFV/SDN) and everthing related to the Open Source world. Ricardo holds a MSc Degree in Telecomunications from Technical University of Madrid (UPM). He loves music, photography and outdoor sports.)*

* **Jean-Philippe Jung** *(Jean-Philippe (JP) Jung joined Red Hat in 2014 as part of the eNovance acquisition. JP is currently working as Engineering Partner Manager, interacting with partners in the OpenStack/NFV space to define, track and coordinate the development of upstream features. JP worked before as Technical Project Manager overseeing Openstack project deliveries in North America in agile mode, working on cloud migrations and feature development coordination. Driven by the love of technology, he previously mixed former infrastructure design and virtualization experiences with SAP skills to design and run extensive virtual SAP environments starting as early as 2006.)*

* **Antonio López Gracia** *(-)*
