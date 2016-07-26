Oslo.Messaging ZeroMQ driver update and messaging drivers benchmarking
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In contrast to AMQP-based 'message broker' systems like RabbitMQ, ZeroMQ is a project that aims to create a brokerless ('zero latency') RPC mechanism for OpenStack — one that answers to the extreme requirements of very large, and/or very high-performance clouds. The current version of ZeroMQ driver (new version) has been in development since June 2015 (first spec approved) and currently supports about five different deployment architectures, each appropriate to a range of cloud requirements (large scale, high performance etc.). In this talk, we are going to explain these deployment variants, in order to help operators make good choices when using ZeroMQ as an OpenStack messaging transport. Our team has also developed a benchmarking tool to test oslo.messaging drivers and compare them with one another, exposing strong and weak aspects of each driver. We will share benchmark results obtained from different drivers and make some suggestions for how best to use oslo.messaging drivers.


* **Dmitry Mescheryakov** *(Dmitry is a Principal Software Engineer at Mirantis currently working on oslo.messaging's RabbitMQ driver. He also works on OCF script for Pacemaker which maintains RabbitMQ cluster in OpenStack installed by Fuel. While working on messaging stack Dmitry has accumulated experience helping with it both customers and his colleagues working on other OpenStack components.)*

* **Oleksii Zamiatin** *(Oleksii Zamiatin is working at Mirantis for about 2 years (since 2014). In OpenStack community he contributes to Oslo related projects, particularly to oslo.messaging project (core reviewer). For the last year he is mostly focused on ZeroMQ driver support and contribution. Previously he worked at Samsung RnD Ukraine, Quickoffice, Aldec Inc.)*
