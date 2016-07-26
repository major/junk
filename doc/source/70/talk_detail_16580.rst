Exploring invisible problems in OpenStack - intelligent troubleshooting with the Elastic Stack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Troubleshooting OpenStack is difficult. In a real-world OpenStack system, configurations, parameters and architectures are all different in every OpenStack deployment. So, regardless of OpenStack maturity, we've found multiple problems in our OpenStack system, which often come out as error logs but sometimes not. In the latter case, problems are especially difficult to detect and fix. In this presentation, we will introduce how to manage this problem by using the Elastic Stack, not just parsing error log messages but taking more intelligent approaches. To detect invisible errors and problems, such as performance degradation caused by Keystone, DB and RabbitMQ, we have configured the Elastic Stack to collect log data in a way appropriate for analysis, extracting plenty of important information, e.g. request IDs, request URLs, response times of WSGI servers. We will show how to utilize these data for troubleshooting OpenStack and results of log data analysis in our OpenStack system.


* **Yotaro Konishi** *(Yotaro Konishi is a cloud researcher and developer at Fujitsu Laboratories Ltd. His primary responsibility is to promote automation, CI/CD, and infrastructure management to Fujitsu OpenStack cloud products, utilizing Puppet and puppet-openstack, Foreman, Ansilbe, Jenkins, etc.)*

* **Noboru Iwamatsu** *(Noboru Iwamatsu is a member of OpenStack since Icehouse. He is a research manager of cloud platform research team in Fujitsu Laboratories. His team constructed OpenStack-based large-scale private clouds for R&D (2 regions,3+ AZs, 200+ servers), and manage them in 2 years. He was one of the core developer of Xen hypervisor project (developed the paravirtulized-USB, GPU-passthrough function, ...), and continues contributing cloud infrastructure-related OSSes.  He has MS from Tokyo Institute of Technologies. He joined Fujitsu Laboratories in 2001, and has worked on Linux-based embedded system, Xen hypervisor, server architecture development and, cloud management software.  )*

* **Tatsuma Matsuki** *(Tatsuma Matsuki is a researcher in Fujitsu Laboratories Ltd. He is working on the performance of OpenStack services and his main interest in the performance management of OpenStack services, which includes log and metric analysis, job scheduling and QoS in OpenStack.)*
