Not sure if it’s just Cinder that is lacking in testing..or all of OpenStack
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Testing is critical to writing code that actually works. Openstack was groundbreaking for a large open source project in both its formalised review process and gate testing that every commit goes through. This helped the project through early stages till the current maturity level. The problem: We’ve reached the limits of the single node, quick tests. Its vendor CI’s are unreliable. Integration tests miss a variety of areas. Its in-tree and Tempest functional tests are limited. Its code coverage from unit tests is inadequate and what exists are low quality in terms of actually catching issues, and they are often an impediment to refactoring rather than an aid. Bugs slip in causing major regressions in functionality between releases. We need a new approach to testing, to augment and enhance what we already have. Unfortunately, testing falls victim to the tragedy of the commons - any company that fails to invest in it still shares the value provided by others.


* **Kendall Nelson** *(Kendall Nelson is a Software Developer working on Cinder since she started in June of 2015.  She has worked on some smaller scheduler changes to Cinder and a larger effort to make the sample configuration file generation a more dynamic process.  She recently had a spec merged for and has begun working on dynamic reconfiguration of services based on changes to the configuration file. Lately she has also been involved in the refactor of much of os-brick. In addition, she is the cross project liaison for Cinder and given many intro to Cinder presentations to IBMers getting into cloud computing. At the Austin Summit, she had the privilege to give two talks- one to the Women of OpenStack about what she's learned in her first year as an upstream developer and the other on the basics of Cinder and setting up multiple backends.)*

* **Duncan Thomas** *(Involved in Openstack since Cactus, and large HPC systems as adeveloper and admin before that. Worked on one of the first large Openstackpublic clouds, and one of the founding members of the Cinder team.)*

* **Eric Harney** *(OpenStack engineer at Red Hat since Folsom, and avid pool player.)*
