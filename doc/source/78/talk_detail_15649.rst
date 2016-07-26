Through the Looking Glass: Unifying Image Generation in OpenStack Sahara
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

OpenStack Sahara users can now drive image packing, image validation, and clean image provisioning from one human-readable, yaml-based image declaration. This feature may be of interest to operators (who build images) and to developers (who may wish to consider the ideas for reuse.) Many provisioning services in OpenStack spawn their applications from pre-packed images. In plugin-based services like Sahara, the plugin must be responsible for image validation and for logic to spawn a cluster from a clean, OS-only image. However, elements used in traditional OpenStack image generation are not easily usable by the controller services. The OpenStack Sahara team has pushed all image generation logic into the plugin and created tooling (using libguestfs’ python API) to run the same logic before Nova spawn (on an image file) or after (on a running instance.) Now when operators change the human-readable manifest, all three flows are updated and cannot fall out of sync.


* **Elise Gafford** *(Elise has contributed to the Sahara community since the Juno release, where she is an upstream core reviewer. She authored features such as Manila share integration and EDP job configuration, and is currently working on revisions to Sahara’s image generation capabilities. She works on the Red Hat OpenStack storage team, where she provides agile coaching and productization support in addition to her work on Sahara.See https://www.linkedin.com/in/elise-gafford-3b036336)*

* **Luigi Toscano** *(Luigi is a Senior Quality Engineer on the Red Hat OpenStack Quality Engineering team, with focus on Sahara (and previously Trove). Free-as-in-speech-Software enthusiast since last century, FSFE Fellow, he is contributing to different open source communities including KDE. He is also co-maintainer for the Sahara tempest tests, a member of core reviewers team for the "sahara-tests" repository.)*

* **Nikita Konovalov** *(Nikita has been working with OpenStack Data Processing (Sahara) from the early days of the project. He has been implementing the initial version of Sahara UI which then has been accepted to main OpenStack Dashboard codebase. He added support for Sahara benchmarking for Rally project and is now responsible for Sahara scale testing activities in Mirantis. Nikita has also been participating in the OpenStack StoryBoard initiative being a core member of the team responsible for backend and SDK development.)*
