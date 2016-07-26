Enabling AWS/Azure's VPN and DirectConnect/ExpressRoute in OpenStack - The missing pieces
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Connecting openStack with your VPC in AWS or Microsoft Azure seems to become a common use case and a basic requirement. Other cloud platforms make it easy to do this end-to-end setup by just entering basic information and doing the setup themselves. What would it take for OpenStack to do that? Should OpenStack be doing more to help manage those integration points? Or maybe this should live in higher layers that abstract the cloud API and let one provision cloud resources in a platform-agnostic way using other tools. This talk will show Neutron’s BGP, VPNaaS and L2GW APIs can be used to automate private cloud connections in Hybrid clouds. We will then propose next steps to make these setups truly self-service and hassle-free.


* **Ryu Ishimoto** *(Ryu Ishimoto is the technical lead of Midokura Japan, currently leading the effort to integrate MidoNet and OpenStack Neutron.  He is also responsible for designing and implementing the MidoNet API as well as some parts of the MidoNet cluster and agent.  He is a Neutron contributor.   Prior to joining Midokura, he spent 10 years as a developer for various technologies including data mining, ad server, financial systems, and e-commerce applications.  In 2004, he received a Master's Degree in Computer Science from UCLA.)*

* **Alon Harel** *(Before Midokura, I have hold architecture positions at Marvell Semiconductors and Mellanox Technologies dealing with Ethernet switching, cloud virtualization and SDN technologies. I have spent the first half of my career as a software engineer and a software team leader developping software for embedded systems in the communication industry.)*
