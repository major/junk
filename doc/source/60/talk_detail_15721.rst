Service Flows for Containerized VNF Distributed across clouds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

The VNF in telecom or other industry are interested in capabilities like service chain so they can dynamically stich services together as needed. The requirement is being able to both define service chain and also manage the data flows to those chains based on dynamic configurations like user profiles. A service chain defined in Networking-SFC is applied to port pairs and will act on all the traffic following those ports. A combination of NSH headers and ODL based policy enforcements are possible but they require the service aware VNFs be deployed for the flows to work. In order for VNFs be deployed as is and have the data flows redefined to suit the data path requirement is the focus of our technologies that are based on OVS / OVN and/or Neutron. This presentation will offer a few options and also demonstrate one of our implementations. Our current implementation is for containerized VNF, though will work seamlessly for VM based VNF or a combination of both as well as multi-cloud.


* **Murali Rangachari** *(Murali has been deeply involved with cloud technologies for more than a decade. His current focus is with Neutron, OVS/OVN, Docker & OPNFV communities implementing solutions for Telecom services in 5G at Huawei R&D Center in Santa Clara. Among other innovations, Murali had involvements in developing new backup technologies at NetApp for Windows/Hyper-v and storage modules at VMware for ESXi.)*

* **David Dai** *(David Dai is the head of technology developments at NFV Competence Center at Huawei Research labs at Santa Clara.)*
