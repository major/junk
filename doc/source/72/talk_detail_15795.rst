Trunked 40G Interfaces with QoS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Usually, OpenStack network architecture is complex and costly. Using multiple 10GbE NICs and Switches for management, storage, internal and public… will be a headache for the operators.   In the past, our private openstack deployment used many 10GbE interfaces with 2-link bonding. As a result, we had to manage 8 links!   This year, we introduced 40GbE NIC to simplify the situation, and we found this can reduce initial costs and everyday maintenance costs.   In this presentation, we will show: How to reduce many 10GbE links to trunked and 2-link bonded 40GbE NIC How to use Quality of Services (QoS) features to ensure bandwidth of each logical links when introducing 40GbE NIC.


* **Masaki Matsushita** *(Masaki Matsushita is a software enginner at NTT Communications.Masaki started contributing to OpenStack from Kilo release.He also contributes to Ruby as a committer mainly for performance improvement.He says, "I like Python too.")*

* **Mahito Ogura** *(Mahito Ogura is a Engineer at NTT Communications, working on Cloud technology R&D team.  He joined the team in late 2014 and since has been focused on to improve OpenStack in his company's cloud, to R&D OpenStack and to educate the cloud engineer.  Mahito has experience in distributed system development.  In the past 5.5 years he has been working for NTT Comware, defining and developing IaaS, NoSQL, configuration tools, KVS as a service, DBaaS(similar to Trove) and Hadoop as a Service (similar to Sahara) . He started contributing to OpenStack from Kilo release. He is actively contributing to DevStack.)*

* **Takeaki Matsumoto** *(Takeaki is software engineer at NTT Communications, working on Cloud technology R&D team.He joined the team in 2015 and since has been focused on to R&D OpenStack.)*
