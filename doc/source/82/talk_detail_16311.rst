Jumping on a live Grenade!
~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Aiming for a smoother live upgrade? Today, with your project running multiple services on different stable releases, it’s never been more important to test compatibility. As with any distributed system, it is common for OpenStack to have services running on the current release exchanging messages with services from previous releases. Without a gate to provide adequate compatibility testing, there is a possibility for a breakdown in production which will make diagnosing bugs difficult or lead to costly fixes. Implementing a partial grenade testing gate with nodes running services of different OpenStack releases can catch compatibility issues early in the development cycle. This session walks you through the steps to set up a multi-node partial grenade gate in the OpenStack CI infrastructure: Introduction to OpenStack CI Upgrade Testing: Grenade vs Partial Grenade Demo: Cinder Use Case Going from experimental non-voting to full-fledged voting job Lessons learned


* **Luz Cazares** *(Luz is currently working on OpenStack community's QA program for Intel. She is a contributor on several projects including Tempest, Refstack, and os-testr. She is part of the Intel OpenStack Innovation Center (OSIC) working upstream to make OpenStack more enterprise friendly.)*

* **Karthik Prabhu Vinod** *(I work as a Cloud Software Engineer with Intel's OpenStack Innovation Center. I make upstream contributions to the Block Storage Project: Cinder.)*
