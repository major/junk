Quick Triaging of common OpenStack issues using Ansible.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

As part of troubleshooting issues in an openstack cloud, admin runs through various checkpoints to find the root cause and spends a lot of time in repeating the same troubleshooting steps for multiple occurrences of the same issue. We have captured the common troubleshooting checkpoints and created ansible playbooks that will run through the troubleshooting steps quickly and helps to narrow down the problem. For example, one of the common issue in the cloud is VM not getting an IP. To triage, an admin has to go through multiple manual troubleshooting steps like finding whether the qdhcp for the network is created (or) whether the ports are active and so on. By running the triage playbook that already contains these troubleshooting steps, common checkpoints are validated and the root cause is identified quickly. Agenda:1. How the playbooks are developed with the checkpoints using Ansible2. How to add more checkpoints to the playbooks3. Illustrate with examples


* **Vinnarasu Ganesan** *(I am a QA Engineer in HPE working on Helion openstack scale and performance tests. )*

* **Balaji Ramamoorthi** *(6.5 Years of Experience with Virtaulization, Storage Currently working in Hewlett Packard Enterprise (HPE) as Helion Openstack QA  Scale & Performance Engg )*

* **Siva Subramaniam M** *(I am working in Hewlett Packard Enterprise for the past 4 years.  Worked on products based on openstack, mainly involved in scale and performance testing using rally, functional testing.  Have worked on CI tools such as jenkins, and written various automation for the CI processes.)*
