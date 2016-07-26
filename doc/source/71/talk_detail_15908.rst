Direct Message Routing for Oslo.Messaging  -  Topology and Deployment Considerations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Direct messaging for RPC traffic patterns has emerged as a key requirement for very large scale and highly resilient OpenStack deployments. The use of message brokers for the RPC messaging pattern can be operationally complex due to the state management and clustering techniques required to realize a scalable and resilient control plane. With the OpenStack Newton release, the Oslo.Messaging library now includes support for an easy to setup, highly scalable, distributed and resilient brokerless message bus based on message routing rather than messaging queuing. This direct messaging support for RPC traffic patterns introduces an alternative architecture and with it new  topology and deployment considerations.


* **Andrew Smith** *(Principal Software Engineer at Red Hat, Inc. - Enterprise Messaging)*

* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*
