Security-Aware Scheduling - Extensible security attribute management in Nova
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Scheduling workloads based on Trust Attestation of hosts, Asset Tag/geo-tags stored on hosts, and other security attributes such as presence of security accelerators, etc  today requires calling into an external service to retrieve the host attributes.  This has serious consequences for performance and scale.  How can host security attributes be used for scheduling, securely and without impacting scalability or scheduling performance?   This session will detail the Intel Attestation Reporting Hub, which uses an extensible framework to securely push cryptographically verifiable host attestation attributes to the openstack scheduler, rather than letting the scheduler request attestations.  This works in conjunction with modifications to OpenStack Nova, which create new interfaces to receive secured host attributes from a trusted external source, and an updated Trust Filter, which uses the new local attributes for scheduling instead of making external requests.


* **Raghu Yeluri** *(Raghu Yeluri is a Principal Engineer and lead Security Solutions Architect in the Data Center & Cloud Products Group at Intel Corporation with focus on virtualization and cloud security usages, solution architectures and technology initiatives. In this role, he drives security solution Pathfinding and development to deliver hardware-assisted security solutions that enable deep visibility , orchestration and control in multi-tenant Clouds.  Raghu is a regular technical speaker at conferences like OpenStack Summit, Intel Developer FOrum, VMWorld, on trust and security in Cloud computing, boundary control and Geo-fencing for sensitive workloads with OpenStack, and trusted docker Containers.  )*

* **Timothy Knoll** *(Timothy Knoll is a Systems Engineer in Intel's DataCenter Group.  Tim has been working to develop and integrate Intel's Cloud Integrity Technology over the past four years.)*
