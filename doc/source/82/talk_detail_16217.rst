Live from Oslo
~~~~~~~~~~~~~~

**Abstract:**

A large number of changes happened in oslo libraries over the last cycle. We would like the opportunity to be able to showcase, explain, and educate contributors to what these changes are. oslo.policy  - implemented embed policy defaults in code and allow for a policy file to override them.  This would allow deployers to only configure policies that they specifically want to override. oslo.messaging(zmq) - There were zmq driver deployment configurations added like proxy and pub-sub . we'll talk about these variants of deployment and what benefits you can get using zmq driver. oslo.config - Mutable config is the ability to reload configuration (also logging configuration!) at runtime without a service restart. It is live in Nova Newton now.  oslo.messaging AMQP 1.0 driver - Introduce the new router-based messaging backend supported by the Newton release. Targetted to deployers who'd like to "kick the tires" of this backend.


* **Oleksii Zamiatin** *(Oleksii Zamiatin is working at Mirantis for about 2 years (since 2014). In OpenStack community he contributes to Oslo related projects, particularly to oslo.messaging project (core reviewer). For the last year he is mostly focused on ZeroMQ driver support and contribution. Previously he worked at Samsung RnD Ukraine, Quickoffice, Aldec Inc.)*

* **ChangBo Guo** *(ChangBo had been working on the OpenStack project since October of 2012, with the first batch of OpenStackers from theIBM’s CSTL cloud team in BJ. His first OpenStack contribution can be traced back to 2012, when he worked on the PowerVM driver under Nova to support IBM Power Systems. see his interview from OpenStack [1]. Now, he mainly focuses on OpenStack Oslo and Nova at EasyStack,  he is Oslo core-reivewer and contribute to some OpenStack projects.   [1]http://www.openstack.org/blog/2014/02/open-mic-spotlight-chang-bo-guo/)*

* **Alexis Lee** *(Alexis has been working on OpenStack for Hewlett-Packard Enterprise since 2013, helping to maintain and package Nova for Helion OpenStack. He has been working on OpenStack since Grizzly and helped maintain HP Public Cloud. His current focus is on Oslo, producing features to benefit the whole community. Ask him to play a game.)*

* **Kenneth Giusti** *(Ken is an active contributor to the Oslo.Messaging library.  He is also a member of the Apache QPID project.  The Apache QPID project provides messaging tools based on the Advanced Message Queuing Protocol (AMQP) standard.  AMQP is an an open protocol for reliable, high-performance messaging systems.  He also has an extensive background developing software for the telecommunications industry.)*

* **Joshua Harlow** *(Joshua Harlow is one of the technical leads on the OpenStack GoDaddy team. Goal in life: make things more awesome!)*
