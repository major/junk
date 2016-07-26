Monitoring Kubernetes with Monasca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Considering the constantly increasing amount of applications running in containers, providing a reliable and efficiently operable container infrastructure is crucial – in particular at scale. Running Kubernetes, an opensource-system for automatic deployment, scaling and management of containerized applications, on-top of OpenStack have been proven a popular option for container management. The draw-back of this approach was the missing operational link between OpenStack and Kubernetes.In this session we show how Kuberntes run on OpenStack can be comfortably monitored with Monasca (OpenStack Monitoring as a Service). Furthermore we explain how the gained insights can be utilized for operations like alerting, log management and node auto-scaling.In our scenario Monasca is used as the Storage Backend for metrics coming from Heapster and for pod logs. We levarege Monasca alerting functionality to trigger the auto-scaling with Heat. Finally, we will give a demo of our solution.


* **Christoph Held** *(As a cloud architect at Fujitsu, Christoph is passionate about OpenSource in the area of datacenter management. He was working in the OpenStack Monasca project and defined its logging-as-a-service component. Since late 2014, Christoph has been focusing on the usage of Kubernetes in large scale enterprise environments and is now deeply engaged in the Dashboard project.)*

* **Witek Bedyk** *(Witek Bedyk is senior software developer at Fujitsu EST for cloud management software. His current focus is on OpenStack Monitoring Service (Monasca).)*

* **Kamil Choroba** *(I am a senior software developer at Fujitsu Enabling Software Technology in Munich for cloud management software. My current focus is on OpenStack Monitoring Service (Monasca).)*
