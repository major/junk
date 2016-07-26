Collectd, InfluxDB & Grafana used to meter OpenStack base infrastructure and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

To be able to debug complex systems, investigate on their performance and to do capacity planning, metrics of the various components in your cloud are getting very important. While Ceilometer provides metrics and events of OpenStack related components, Cloud Platform Engineers require insights that go beyond that and also need metrics from base infrastructure and services. Thus Swisscom deployed collectd and makes use of its many plugins to collect basic system metrics as well as metrics from services such as HAProxy or RabbitMQ. The metrics are stored and down sampled over time in InfluxDB. In the end Grafana is used to browse and analyze the metrics.In this talk I will introduce the architecture of our metering setup and share the experience with it.


* **Janosch Rohdewald** *(Janosch Rohdewald is working as an OpenStack system engineer at Swisscom. Having a storage related background, he has a strong focus on cloud/software defined storage.)*
