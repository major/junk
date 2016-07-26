Generate and re-use your templates conditionally in dev & test environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Newton release, Heat is enhanced with following features:1. conditions in HOT template version 2016-10-14It helps to write an common HOT template and use it conditionally based on the various facts like - test vs production enviornment- scaling vs normal test environment- with or without a floating IP, security group, etc2. new project os-hot-get to generate HOT using python APIBased on the requirements, It helps to generate the HOT template dynamically using python api.In OpenStack, it could be levaraged by heat-translator, magnum, tacker, senlin, etc projects.Also this could be used by global orchestration solution, which uses the heat for orchestratingthe OpenStack.This presentation will demo an user case base on these two featuers and details/tutorials on how to use them.


* **Tianhua Huang** *(Tian Hua Huang is working at Huawei. She began to contribute to OpenStack community since 2013, now she focusing on openstack heat design and bug fixing, she is core review member of openstack heat community.)*

* **Kanagaraj Manickam** *(  Huawei Senior System Architect @ Huawei Technology India Pvt. Ltd. OpenStack Core-reviewer @ OpenStack Orchestration Service (Heat) Core-reviewer @ OpenStack NFV Orchestration Service (Tacker) Establishing OpenStack Manager (Namos) Open-O Active participant and contributor in Open-O community)*
