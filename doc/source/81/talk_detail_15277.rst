Toward 10,000's containers on OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Kubernetes, Swarm and Mesos have been shown to scale to hundreds orthousands of nodes and tens of thousands of containers, handlingmillions of requests per second. On OpenStack, they can be easilydeployed and managed by Magnum, but how do they scale? Building thecorrect infrastructure plays a critical role in the performance andscalability for the containers, and this needs to be implemented in Magnum.Working toward this goal, we have built a collection of Rally plugins totrack the performance and scalability of both Magnum and the ContainerOrchestration Engines (Kubernetes, Swarms, Mesos). We have been runningthe benchmarks on large OpenStack environments to collect measurementsand study the behavior of the system. In this talk, we will present ourfindings along with some of the best practices we found for operatinglarge container environments.


* **Winnie Tsang** *(Normal 0 false false false EN-US X-NONE X-NONE /* Style Definitions */ table.MsoNormalTable {mso-style-name:"Table Normal"; mso-tstyle-rowband-size:0; mso-tstyle-colband-size:0; mso-style-noshow:yes; mso-style-priority:99; mso-style-parent:""; mso-padding-alt:0in 5.4pt 0in 5.4pt; mso-para-margin:0in; mso-para-margin-bottom:.0001pt; mso-pagination:widow-orphan; font-size:10.0pt; font-family:"Calibri","sans-serif";} Winnie Tsang is a software engineer in IBM working on cloud performance. She work on OpenStack Heat on some debugging features in Juno cycle. In this current cycle she is working on a Rally plugin for Magnum. It will allow users to test the performance and scalability of Magnum for Kubernetes, Swarm and Mesos.)*

* **Ricardo Rocha** *(Ricardo Rocha is a software engineer at CERN. He's currently a member of the CERN OpenStack team, focusing on service and application orchestration and container deployments. Previous work included development of data storage, bookkeeping and monitoring services for the LHC Computing Grid (LCG).)*

* **Spyros Trigazis** *(Spyros Trigazis work at CERN.)*
