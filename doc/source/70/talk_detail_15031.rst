StackTask, Granular Roles and RBAC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Deployment of public, production OpenStack Cloud regions present all manner of challenges, not least of which being the management and delegation of user permissions and roles. Our users have long requested the ability to delegate roles more granular than "_member_", reset passwords securely and invite new users to their own projects; none of which being easily done with base unfederated Keystone or the default policies. We present the method by which we enabled our users to self-manage a significant amount of this (within controlled boundaries), leaving more time for our engineers to develop new features, expand our regions, and sleep peacefully at night.Principally: * Limitations in Keystone, Horizon and the APIs, and the reasons behind them. * Concepts, design goals and architecture in StackTask that overcome many of these. * Horizon dashboard integration. * Rate limiting. * Modification of default RBAC policies to include more granular roles.


* **Michael Richardson** *(Spends his days ensuring the smooth operation of our public, production OpenStack cloud regions as they grow into this ever expanding universe, transparently fitting the requirements of our users.)*

* **Adrian Turjak** *(Principle developer on StackTask, with a strong interest in roles, permissions and delegation.)*

* **Dale Smith** *(Senior OpenStack developer and operations engineer, working on the Catalyst Cloud.)*
