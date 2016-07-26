Policy-based Kubernetes Scheduling driven by Congress, OPA, Magnum, and the rest of the BigTent
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

 In this talk we describe how OpenStack Congress, the recent open-source project Open Policy Agent (OPA), and Magnum work together to give an OpenStack operator the ability dynamically control the container placement logic of Kubernetes by writing rich, declarative policy statements.  As a first use case, we demonstrate policies where Kubernetes pods need to be scheduled so they have local access to Cinder-backed storage.  Importantly, this integration is accomplished with NO changes to Magnum or Cinder; the exact same integration works to implement policies that draw on data from any (combination) of the BigTent projects.


* **Tim Hinrichs** *(Tim Hinrichs is the PTL of OpenStack Congress and the CTO and co-founder of Styra, Inc.  Before that he spent 2 years as a software engineer at VMware, and in 2008 he received his Ph.D. in declarative programming languages from Stanford University.  He spent the last 15 years designing and implementing policy-aware systems in different domains, such as networking, (what at the time was called) utility computing, configuration management, web security, game-playing, and access-control.)*

* **Ramki Krishnan** *(Ramki has over 20 years of proven industry experience in the areas of Networking, High Performance Switching and System Management. He has over 10 years of experience in Standards Development and Leadership, Research Leadership and Managerial role. He has previous startup experience.  He combines deep technology understanding with strategic thinking to bring customer-winning products and solutions to reality with a direct impact on revenue generation. His expertise includes a wide range of technologies and market trends, including: Networking Protocols (BGP etc.), SDN, NFV, SDS, SDI, Cloud, Security, Open source (OpenStack, OpenDaylight, OSM, and OPNFV etc.), Intel Processors, Servers, Storage, Agile and DevOps, REST, YAML, IPMI, Redfish etc. He is a recognized innovator with 19 US patents and 8 IEEE conference papers including a best paper award. He is a thought leadership speaker in key conferences such as ONS, OpenStack, OpenDaylight, NFV World Congress etc. He is a leader and active participant in several research and standards organizations such as IRTF, IETF and ETSI NFV etc. )*

* **Eric Kao** *(Software engineer at VMware and core reviewer on Congress.)*
