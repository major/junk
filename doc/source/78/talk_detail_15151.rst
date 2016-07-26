Security groups & Firewalls logging: How we capture and store security events in Neutron
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This session will introduce a logging feature for security groups and firewalls [1][2] and show its benefit to operator and tenant. Today, logging becomes critical to ensure the enterprise has visibility into traffic entering and leaving the environment. Tracking DROP events is the good way to identify threat, logging ACCEPT events gives greater insight into malicious traffic. This session introduces a mechanism [2] to capture and store security events (ACCEPT/DROP) related to security groups and firewalls when they occur. We can collect security events for a specific VM, tenant, security group or firewall via Rest API or OSC. The log-data can be consumed by Monasca service or forwarded to external system to: Detect illegal communication Detect attack patterns and alert abnormal activities This feature also exposes a way to help tenant make sure security rules work as expected. This session includes a demo of the work in progress. [1] https://goo.gl/Cs7Koo [2] https://goo.gl/f2k52l


* **Phuong An Nguyen** *(Nguyen Phuong An software engineer at Fujitsu Limited.  I'm an openstack-neutron developer. Currently, I'm focus on developing new networking features (e.g:  security group logging).)*

* **Xuan Hoang Cao** *(Cao Xuan Hoang Software engineer at Fujitsu Vietnam Limited. He is in-charging to support and develop new features to apply to OpenStack components, especially in Neutron, Nova and Ironic.)*

* **Yushiro FURUKAWA** *(Yushiro FURUKAWA Software Engineer, Fujitsu Limited. He has been working in Neutron and Neutron-FWaaS since Kilo development cycle. Currently, he focuses on development of neutron plugin(ML2), Neutron, Neutron-FWaaS and Ironic.)*
