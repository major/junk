STEER: An Implementation of Service Function Chains using Network Service Header (NSH) Encapsulation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Modern networks due to the explosion of connected devices obligates the need to support different levels of quality of experience whether it is for web browsing, online games, messaging etc. This level of experience is expected to be provisioned by the way the traffic is steered across the network by a set of network service functions (SFs) called service function chains (SFCs). The SFs need not reside on the direct data path and can reside on the cloud or data centers. In this talk and demo, we introduce a simplified solution for Dynamic SFC orchestration (STEER) which implements Network Service Header (NSH) encapsulation inside OpenStack as per IETF recommendation. The solution consists of a control plane (SFC Controller) with REST based APIs to configure the data plane (Traffic Classifier, Service Function Forwarder and Service Function Proxy). The STEER APIs makes SFC implementation and prototyping simple and fast. The solution supports both NSH-Aware and NSH-Un-aware SFs.


* **Shamik Mishra** *(Shamik Mishra is currently a Technology Director with the Cloud Innovation Team at Aricent. He has extensive experience in software development in cloud, wireless technologies and platform software. His research interests are Network Function Virtualization, Cloud Computing and Machine Learning. Shamik has a bachelor’s and a master’s degree from Indian Institute of Technology (IIT) Kharagpur.)*
