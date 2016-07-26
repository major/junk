Testing IBM Blue Box Cloud the OpenStack way
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ursula is a collection of open source Ansible scripts that IBM uses to deploy its IBM Blue Box OpenStack clouds.  It comes with some basic multi-node OpenStack regression and integration tests that we have setup to run against every proposed change to the codebase.  The infrastructure services we use to accomplish this differ from upstream in almost every way, though. Where upstream uses Gerrit, we use GitHub.  Where upstream uses Zuul, we use Jenkins.  Where upstream uses Nodepool for multi-node provisioning, we use Heat.  So, what would it take to get these tests running the "OpenStack Way" (e.g. with nodepool and zuul) and what would the preceived benefits, drawbacks, and challenges be with this solution? This talk will attempt to answer these questions by walking through our evaluation with the hope it will prove educational both to prospective users of these infrastructure services and the people developing them.


* **Tim Chavez** *(Tim has spent the better part of eight years developing continuous integration solutions with open source technologies.  Currently, Tim is the CI squad lead for IBM Blue Box, where he works with a team of engineers to build, deploy and support the foundational services used to develop and test our private managed cloud product offering.  Prior to IBM, Tim worked at Hewlett Packard Enterprise as a developer on Gozer which was an internal deployment of OpenStack infra services that ran thousands of tests per month for a diverse set of customers.)*
