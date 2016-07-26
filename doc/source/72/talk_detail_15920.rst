The race conditions of Neutron L3 HA's scheduler under scale performace
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Neutron's Router presents a L3 interface that connects VMs to an external network. In its legacy mode, a router can be scheduled only to one agent at a time, presenting a single point of failure - if that node fails, all communications are halted. L3 HA mitigates this issue by presenting an Active/Passive configuration where a router can be scheduled to multiple agents which recover the datapath automatically during failures using a dedicated network that hosts keepalived processes. Using L3 HA presents an orchestration problem: since a router now appears in more than one agent and another dedicated network is required for the keepalived processes, there are a lot more resources involved. We performed L3 HA scale testing for Liberty and Mitaka, which showed benefits of L3 HA and uncovered a number of race conditions in Neutron code both on L3 agent and on server side. We'll present results of this scale testing and showcase some of these race conditions.


* **John Schwarz** *(Working for Red Hat and on Neutron for the past two years, soldier at the IDF beforhand. Coding enthusiast, review fanatic and speaking hobbiest.)*

* **Ann Taraday** *(Ann is a Software engineer, Neutron core-reviewer with a focus on databases, contributing to Neutron since Havana.)*

* **Kevin Benton** *(Kevin Benton is currently a Software Engineer at Mirantis. He has been contributing to Neutron since Havana while he was working at Big Switch Networks and has been a core reviewer since 2014. He is the Lieutenant of the reference implementation and also serves on the Neutron drivers team, helping the PTL define the direction of the project by selecting features to work on. He prefers to spend time improving the stability and performance of Neutron and its reference implementation to give deployers reliable OpenStack networking without immediately turning to a vendor.)*
