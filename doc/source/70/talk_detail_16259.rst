99.99 success is too small: measuring Nova build failures
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Cloud providers regularly provide statistics about the "number of 9s" they havefor API uptime. This can help attract enterprise customers that care aboutreliability. This talk shows how Rackspace goes a bit deeper internally in calculatingthe percentage of builds that fail in Nova, covering our current technicalsolution, how this has helped us discover failure scenarios and prioritize bugfixes, and what the future of build success measurement might look like. Technologies used in the system to calculate build failures include Novanotifications, Stacktach, Logstash, and Elasticsearch. Periodic synthetic buildsto emulate customer experience also run to catch errors that wouldn't bevisible from within the control plane, like network failures after an instancegoes active or issues within the deployed image. The goal of this talk is to encourage operators of OpenStack, especially thosewith large deployments, to measure reliability accurately.


* **Mario Villaplana** *(Mario Villaplana is a software developer at Rackspace working on the OnMetal team, which provides a public baremetal cloud using OpenStack Ironic. He graduated from Stanford University in 2014 with a degree in Computer Science, focusing on Artificial Intelligence, but has since focused almost exclusively on the cloud and OpenStack. He works on upstream development reviewing code, fixing bugs, and writing and implementing specs. Downstream, he helps operate OnMetal and writes code to automate operational tasks whenever he can. He lives with his fiance, Brandon, in San Antonio, TX, but they will soon be moving to Denver. Hobbies include reading, studying languages, and running.)*
