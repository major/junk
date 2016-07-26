Scope in the token - A fire in the RBAC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Current OpenStack API protection model provides several ways to controll user access to different API's. However, only the default one is widely used and at least barely known. There are several not so obvious options to set up secure environments with flexible access control: - oslo.policy provides an interface to plug third-party application (such as Apache Fortress)  in and even store and operate policies dynamically - another approach is to handle separation of duties and enforce policies internally in keystone - no more scoped tokens. This one is under active discussion - your opinion is invaluable! Logically, provided keystone becomes a manager of service policies, it has everything to enforce API protection without the need to issue, pass and, consequently - validate authorization information (AKA 'token scope'). That, in turn, means OpenStack doesn't require tokens to operate! Let's discuss!


* **Adam Young** *(Adam Young is a member of Red Hat's OpenStack team and a core developer on Keystone, the identity management service for OpenStack. Adam has worked on various systems management tools, including the Identity Management component of Red Hat Enterprise Linux based on the FreeIPA technology.A 19 year industry veteran, Adam contributed to multiple projects, products and solutions from Java based eCommerce Web Sites to Kernel modifications for Beowulf clustering.  )*

* **Alexander Makarov** *(Alexander is a senior software developer in Mirantis with the responsibility to improve keystone and keep it fresh and healthy both in MOS and OpenStack itself. Joined the Community in 2014, has 10 years experience with commercial distributed computations systems development. Graduated Bauman Moscow State Technological University at 2004.)*
