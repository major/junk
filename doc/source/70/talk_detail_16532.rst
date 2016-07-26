Maat - Adaptive System Configuration and Recovery with Predicates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Maat is an SCM system with automatic system recovery. It defines system correctness with simple predicates and can adaptively find solutions to recover from system resource changes. We will demonstrate Maat provisioning an OpenStack cluster and recovering from system changes. * System correctness is specified with simple predicate functions in Python. * Reconfigurations for system changes achieve minimal disruption of service. * Operators can be notified and control when a system reconfiguration is required to avoid thrashing during transient failures. * User-defined fitness functions select solutions that optimize system characteristics such as resource usage and disposition. We developed Maat to automate the life cycle of OpenStack clusters, from initial provisioning, failure recovery, cluster component changes, and software upgrades. We will demonstrate Maat deploying and recovering from failures on a multi-node DevStack deployment.


* **Noel Burton-Krahn** *(Noel has over 25 years software development experience, with particular interest in distributed systems and fault tolerance. This recent work has been automating OpenStack deployments for Piston and now Cisco. )*
