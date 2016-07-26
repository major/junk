Problem prediction/detection assisted by AI running on Distributed Analytics & Monitoring framework.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Robustness against unexpected problems such as silent failures caused by software bugs and failures of server components is important for operators of telecom and cloud services. Fast detection of problems, and predicting them is crucial for us to avoid serious situations. We propose Distributed Analytics & Monitoring (DAM) framework to achieve real-time failure management in OpenStack. For fast detection, DAM deploys an analytics/monitoring agent into each compute node, and each agent can collect statistics from the local environment and analyze them very rapidly. A typical application of DAM for prediction is running AI to learn huge statistics locally, so that we recognize problems 30 minutes in advance of actual failure with 94% precision. Optionally, an orchestrator reacts to invoke auto-healing. DAM greatly helps improve the scalability and real-timeness of cloud and NFV infrastructure. DAM also helps us detect micro-bursts of demand, fast change of configuration, etc.


* **yuki kasuya** *(Yuki Kasuya work for KDDI Laboratories as a research engineer. He investigates how to build NFVI using OpenStack effectively and to solve performance and operation problem in NFV.)*

* **Hyde Sugiyama** *(Driving NFV/SDN technology partnership at Red Hat APAC as a member of Red Hat NFV Initiative Leading team 28 years experience in the Information Communications Technology industry.)*

* **Ryota Mibu** *(Ryota Mibu has been working on integrating cloud technologies to telecommunication platform form 2012 in NEC. He has been contributing OpenStack projects, including Neutron, Ironic and Ceilometer. He is the Project Lead of "Doctor" which is one of the OPNFV projects and focusing on building a framework for fault management for high availability of Network Services on top of virtualized infrastructure.)*
