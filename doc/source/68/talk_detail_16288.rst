RabbitMQ at Scale, Lessons Learned
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Operating RabbitMQ at large scale comes with it's own set of challenges. This talk will take you on the journey Cisco faced with operating a large (800+ node) environment inside a single RabbitMQ cluster. We will share the pains, lessons learned and best practices to stabilize and improve messaging performance and reliability. This talk includes: OpenStack service configurations related to messaging Kombu driver enhancements Considerations when virtualizing the control plane, and how default network buffer settings can be insufficient. RabbitMQ Erlang arguments related to TCP_USER_TIMEOUT and their impact The overhead of Queue Mirroring Kernel level network settings to improve RabbitMQ failover and provide faster service re-connect Alerting and Monitoring RabbitMQ Recovering from a cluster partition Architectural decisions 


* **Matthew Popow** *(Matt is a Senior Engieer working for Cisco Cloud Services. Matt has experience working on OpenStack since the Grizzly release, and focuses on quality engineering, operations, and release management. )*

* **Wei Tie** *(Wei is a senior platform engineer at Cisco Cloud Service, working on global OpenStack based cloud build, operation and optimization. Wei started his journey with OpenStack from Essex release and is actively working on stabilizing Icehouse and Liberty platforms.)*

* **Weiguo Sun** *(Weiguo has been working in IT industry for over two dacades. His past experience includes large scale database support on various unix platforms and high performance web farms. Since Grizzly and Havana releases, Weiguo has been a tech lead for the Cisco Cloud Services, focusing on the stability and scalability of Neutron / OVS / Rabbitmq and other backend services.)*
