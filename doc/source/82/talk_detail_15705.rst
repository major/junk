Isolated development environments for OpenStack with GNU Guix
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Software developers would love to live in a world where bugs are reproducible. Unfortunately, they do not: some bugs happen "in production", but not on their development machines. The behaviour of a program is indeed linked to both the packages installed on the system and the environment (environment variables, filesystem), which makes it hard to reproduce bugs. In order to get reproducible results when running unit tests, virtualenv is often used. It allows developers to create an environment that is almost isolated from the rest of the system and to install packages inside it. We will see during the presentation why virtual environments are not completely reproducible, and why they are not truly isolated. We will show how a functional package manager such as Nix or GNU Guix can help us build reproducible build environments truly isolated from the rest of the system.


* **Cyril Roelandt** *(Free Software developer, GNU/Linux user, GNU Guix developer.)*
