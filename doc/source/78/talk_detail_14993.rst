Levelling the playing field: Baremetal Console
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Are you using Ironic in production?  Do you find troubleshooting a baremetal instance without a console limiting? Unlike VMs, Ironic has no console support in Horizon. In this session, we will focus on how to facilitate troubleshooting baremetal instances by exposing console support. This talk aims to illustrate the following: * The issue we are trying to solve * Our proposal/work: What is necessary if you want to use Ironic in production? How Ironic serial console works? * How does this currently work for Nova? Why do we want to leverage that for Ironic? * How we managed to architect a solution for the graphical console keeping a minimal vertical footprint through horizontal scaling and leveraging docker to secure client sessions * We will showcase how the console works live in production with some demonstrations! * What, except for the console is necessary if you want to use Ironic in production? Graphic console, multi-tenant network, volume, ... 


* **Yuiko Mori** *(Yuiko Takada began working on OpenStack "Havana" in 2013. She is Ironic Inspector core developer and also working for Ironic.)*

* **Hironori Shiina** *(Hironori Shiina has been working for Fujitsu for 10 years. He developed middleware for mission critical systems on Linux. Currently, he belongs to OpenStack development team in Fujitsu.)*

* **Wajdi Al-Hawari** *(Wajdi is a Full Stack Developer for Internap working out of Montreal. Passionate about test driven development and continuous integration, he is mainly responsible for the architecture and development of server and network automation solutions for Internap's Baremetal public cloud solution. When Wajdi isn't developing solutions for the cloud, he is usually a human jungle gym for his two children, enjoys running and dabbling with his guitar. )*
