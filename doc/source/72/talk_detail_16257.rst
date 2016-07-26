Container Networking Strategies in OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

For cloud architects looking to build secure networks that span several docker hosts in their OpenStack cloud, there are a bunch of different options available. One approach is to use the Kubernetes pod model. This involves creating pod CIDRs and privately accessible services that front-end the pods. You can then selectively expose some parts of your application to the external network by opening up the required ports to serve traffic. In this model, you are presented with a variety of networking options such as neutron overlay, flannel, calico, contiv etc. Another option is to use docker swarm with isolated docker networks created using the built-in overlay network driver. You could use a custom docker network driver plugin implemented as a remote-driver for LibNetwork, providing several additional features. Another approach is to use the capabilities provided by the OpenStack Magnum project. This talk will explore the variety of networking models available and demystify them.


* **Naveen Joy** *(Naveen Joy is a cloud computing architect at Cisco Systems with several years of OpenStack solutions development, integration and deployment experience. He has been a speaker at the past OpenStack conferences and his current focus is in the area of microservices, kubernetes, automation and networking. He has contributed code to the development and integration of OpenStack based cloud services for large customers. Naveen holds a master’s degree in Computer Science from the University of Southern California.)*

* **Rohit Agarwalla** *(Rohit Agarwalla currently works in Cisco's OpenStack team. He was one of the first OpenStack contributors from Cisco and has been involved in the OpenStack project since the Bexar release. He is currently active in a wide range of product development, customer and community efforts around OpenStack. Prior to this, Rohit developed and contributed to a variety of cloud computing related projects as part of Cisco's CTO office. Rohit holds a Masters degree in Computer Science from Cornell University.)*
