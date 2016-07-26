The way of telemetering: How we land Ceilometer in real world
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ceilometer provide a unique point of measurements and events data from other projects of OpenStack for upstream users. The use casese can be: resource metric statistics reports, billing, infrastructure service monitoring, alarming, trend analysis for capacity planning, events history auditing, root cause analysis. In the real world, we have met some problems when using Ceilometer. This presentation want to show you the improvements in deployments, in configuration, even in code level. We have a public cloud is based on a OpenStack deployment with more than 1000 hosts, during the real operation, how to ensure the efficiency of metric data recording and query? how to ensure the metric data accurate and reliable? and how to ensure the alarming service accurate and prompt? This presentation will share you what we have met in operation, what we have done of Ceilometer improvements and what we will try in future.


* **Sheng Liu** *(Devoting to OpenStack community contribution, especially in Ceilometer(renamed to "Telemetry" now) project, Sheng Liu have done well in code commit, code review, community involvement to improve Ceilometer capability, stability, usability, etc. In 2015.9, Sheng Liu has been proposed as a core contributor of Ceilometer project. In the last 2+ years working for Huawei, Sheng Liu have also participate development works of Huawei's FusionShpere OpenStack product, and mainly involved NFV scoped features in Nova, such as Numa instance, SRIOV support.)*
