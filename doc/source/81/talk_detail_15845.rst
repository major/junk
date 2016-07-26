Kubernetes SDN Performance and Architecture Evaluation at Scale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Over last year Kubernetes has become similar platform for containers as OpenStack in virtual machines. We spent last 6 month of running Kubernetes for microservices applications as well as for OpenStack itself. We containerazed whole OpenStack including libvirt for more than 100 compute nodes. We discover that networking is one of the most challenging aspects to running Kubernetes. Therefore over the last month, tcp cloud has run extensive performance and diagnostics tests across multiple overlay providers (OpenContrail, Calico, Romana, etc.) as well as against the base Kubernetes Flannel configurations and have come to several insights into CPU penalties. Network design issues at scale as well as performance comparisons use different encapsulation techniques. We deployed Kubernetes cluster on 300 physical servers!  


* **Jakub Pavlík** *(Jakub Pavlik is CTO and chief architect of tcp cloud (http://opentcpcloud.org). He is focused to virtual private cloud and private cloud solutions based on OpenStack and Kubernetes and vendors derivates. He is responsible for whole infrastructure solution (architecture, implementation, operation). He is member of OpenContrail Advisory Board.)*

* **Marek Celoud** *(Responsibility of legacy networking including Data Center Network as well as SDN which includes desing, monitoring, configuration and automation. Focus on OpenContrail, Calico (for Kubernetes) and Cisco Networking solution. Expercience with orchestration of infrastructure services through OpenStack Salt, development and testing OpenStack environment and Kubernetes. Focus on Openstack/SDN based NFV orchestrator platforms. Responsible for Networking Support of enterprise customers and providing professional consulting in the field of NFV/SDN. Experience with architecture, implementation, security and upgrades of networking solution in tcp cloud environment. Hands-on experience with deployment of OpenStack (Juno, Kilo, Liberty and Mitaka) with OpenContrail 3.0 and 3.0.2 using OpenStack Salt.  )*
