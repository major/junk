A Better Way to Cook RabbitMQ Cluster
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deploying OpenStack in a large scale environment, we can regard a message queue(MQ) as a bottleneck. To reduce the message consumption per MQ cluster, OpenStack operators typically allocate a component with high communication costs on another MQ cluster separately.However, for those operators, managing multiple MQ clusters could be a nightmare. Therefore, in order to relieve the operators’ work load, we will present our evaluation result on a large OpenStack deployment with a single large RabbitMQ cluster, which is easier to manage. We tackled with the following two evaluations. First, we investigated details of messaging mechanism in OpenStack to reveal the bottleneck. Second, we conducted examination of RabbitMQ’s ha-mode, queue mirroring, and load balance to find the best practices.Then, we applied the above results to our staging environment and evaluated our RabbitMQ cluster in a large OpenStack deployment.


* **Chihiro Yokoyama** *(Chihiro Yokoyama is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*

* **Mahito Ogura** *(Mahito Ogura is a Engineer at NTT Communications, working on Cloud technology R&D team.  He joined the team in late 2014 and since has been focused on to improve OpenStack in his company's cloud, to R&D OpenStack and to educate the cloud engineer.  Mahito has experience in distributed system development.  In the past 5.5 years he has been working for NTT Comware, defining and developing IaaS, NoSQL, configuration tools, KVS as a service, DBaaS(similar to Trove) and Hadoop as a Service (similar to Sahara) . He started contributing to OpenStack from Kilo release. He is actively contributing to DevStack.)*

* **Yoshifumi Sumida** *(Yoshifumi Sumida is a software engineer at NTT Communications, working on Cloud technology R&D team. He joined the team in early 2016 and started to R&D OpenStack mainly.)*
