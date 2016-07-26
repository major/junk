Scenario tests, Tempest, CI and other beasts in the Sahara world
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Releasing working software artifacts is always a challenge. Releasing a huge set of projects like OpenStack increases the difficulty. Luckily, the quality assurance (QA) project has been one of the pillars of OpenStack since its inception. Still, quality is really a shared responsibility in the OpenStack community, and each project should work with the QA team to actively follow, use, and locally adapt the testing tools and guidelines.In this talk we’ll show how testing is organized in the Sahara world and performed in Sahara’s continuous improvement (CI) system. We’ll discuss the reasons for the creation of the separate Sahara tests repository and the new capabilities it allows. We’ll also share the design of the scenario tests framework itself (end-to-end), and we’ll talk about the consolidation of the Tempest-based and other high-level testing artifacts for related projects.


* **Luigi Toscano** *(Luigi is a Senior Quality Engineer on the Red Hat OpenStack Quality Engineering team, with focus on Sahara (and previously Trove). Free-as-in-speech-Software enthusiast since last century, FSFE Fellow, he is contributing to different open source communities including KDE. He is also co-maintainer for the Sahara tempest tests, a member of core reviewers team for the "sahara-tests" repository.)*

* **Evgeny Sikachev** *(Evgeny has been working with OpenStack Data Processing (Sahara) on position Automation QA Engineer. He has been implementing the initial version of sahara-scenario which then has been moved to the main sahara-tests repository. He supports Sahara benchmarks for Rally project and is now responsible for Sahara scale testing activities in Mirantis. Evgeny has also been participating in the managing process of Sahara-CI.)*

* **Vitaly Gridnev** *(Vitaly is Software Engineer working with Mirantis. He is a core upstream contributor, Project Technical Lead, and downstream productization for the OpenStack Data processing service (Sahara), which provides Big Data cluster management and Elastic Data Processing in OpenStack. He has contributed to OpenStack since the Juno release.)*
