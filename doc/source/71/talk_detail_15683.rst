Message Routing: a next-generation alternative to RabbitMQ
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

A broker can only scale so far.  The limitations of a broker-based messaging service are becoming apparent as Openstack deployments are pushed to ever higher scales and wider distributions.  An alternative to the broker-based message bus is needed. This presentation will introduce that alternative.  With the Newton release, the Oslo.Messaging library now includes support for a highly scalable, distributed, and fault tolerant brokerless message bus based on message routing rather than queueing. With this new technology one can achieve high availability through redundancy rather than clustering.  This message bus is optimized for operation across geographically distant sites, allowing for cloud distribution not possible with the single or federated broker approach.


* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*

* **Andrew Smith** *(Principal Software Engineer at Red Hat, Inc. - Enterprise Messaging)*
