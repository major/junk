Global Load Balancing for VNF’s and PaaS in a Largely Distributed Cloud
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

AT&T is delivering its Network on Demand, by embracing Network functions virtualization (NFV) and software-defined networking (SDN).  As we learn to incorporate geographic redundancy across the VNF traffic, we quickly run into the lack of GSLB functionality inherently within OpenStack. The Kosmos project approach to GSLB , although promising doesn’t; seem to properly encapsulate the ability to incorporate existing solutions in the market. Organizations might  already be utilizing  an existing GSLB vendor. We need an approach that integrates GSLB seamlessly into the OpenStack ecosystem, and provide a simple mechanisms to integrate with existing solutions. We’ll review the proposed Kosmos architecture, how we leverage it, how we plan to implement the architecture at a regional or local level, and finally discuss our implementation and how it is been utilized to help improve the reliability of  our VNF’s and largely distributed PaaS applications.


* **Rodolfo Pacheco** *(Rodolfo Pacheco (rp2723@att.com) works at AT&T as the Leader of the AIC Design TEam , and as a   Cloud Architect helping build the AT&T AIC OpenStack Cloud. The foundational platform for AT&T’s Network On Demand platform.  Prior to that, he was the code Developer and Architect for the AT&T Netbond service.)*

* **Ganeshkumar Natarajan** *(Ganeshkumar Natarajan (ganeshkumar.natarajan@att.com) works at AT&T Inc. USA, as Principal Technical Architect. He is one of the lead Cloud solution architect currently working on ATT Integrated Cloud (AIC). AIC is AT&T's largest enterprise cloud built on Openstack that serves all AT&T traffic for mobility, IT workloads and Network Functions. His broad experience includes solution architecture, design, and development of the product all the way to production deployment.  Before AIC work, he was lead developer for ATT CDN Cache and Streaming platforms and has also successfully developed and deployed many Enterprise Android Mobile Cloud based application products for AT&T.)*

* **Ram Sateesh Talari** *(Works with AT&T as Development Lead for AIC DNSaaS and GSLBaaS Teams.  Is currently working on creating and implementing blueprints with openstack designate.  Previously worked with AIC DBaaS and was Developer for the AT&T CaaS platform.)*
