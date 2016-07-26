How to test OpenStack for large NfV deployments (POPs) without miles of cables ?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Based on answering RFI/RFP for Service providers and equipment manufacturers a recurring question appears: How far apart can control and compute/storage be spread in a large real service provider network ?   This talk aim at providing metrics, tools and how to induce latency and errors (WAN simulation) for developers without a large network to test (miles of cables) in order to help the community make OpenStack thriving in those environments. Agenda for the talk (explanations AND live demonstration) :- Setting the problem, Point of presence, exchange, central office- How are going to simulate a Tier 1 network ?- Getting metrics, what to measure ?- Validating latency ism induced- impact on metrics.- Architecture considerations (stretch, multi-region) - Lesson for cells   Methods and code will be made available for the OpenStack community to simulate/test/measure and then enhance the OpenStack code for those use cases. 


* **Nicolas Thomas** *(Among the "founder" of the NfV realm, working on 2 of the initial use cases used to create ETSI NfV IG which defines and promote NfV. Member of ETSI NfV IG group before creation. 18 years of experience helping Telco use open platforms and ride the wave of IT innovation adapted to the telco space. Public speaker and hands-ons engineering. Former participant in Telco and platform standards : SAForum, Scope-Alliance, PICMG,  TC commite for OpenSAF and founder of CP-TA alliance. Currently NfV Solution Architect at Canonical, active participant to osm.etsi.org, ETSI NfV IG, OPNFV, Open-O https://fr.linkedin.com/in/nicolasthomasfr for details.)*
