Mechanism Driver – Ironic deploying on VXLAN supported
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

Ironic project is young but important and fast-growing nowadays. Supporting VXLAN isolated tenant networks automated booting Baremetal server is the competitive point of all vendors. There are blueprints that support isolation tenant networks for above issue in Ironic side and Nova side [1] [2]. In Neutron side, the solution is based on Mechanism Driver – that is in possession of each vendor. I would like to propose Mechanism Driver with VXLAN isolated tenant network supported. The Mechanism Driver work with HW switch relied on OVSDB and JSON RPC communication. The Mechanism Driver acts as the OVSDB-client to remotely configure the OVSDB then builds networks on hardware (HW) Switch [3].   [1]: https://goo.gl/lCcd1z [2]: https://goo.gl/KpOvBf  [3]: https://goo.gl/LBCuoM


* **tu ha** *(Company: Fujitsu Vietnam Limited Position: Software engineer Openstack registration: Jan 2016  )*

* **Xuan Hoang Cao** *(Cao Xuan Hoang Software engineer at Fujitsu Vietnam Limited. He is in-charging to support and develop new features to apply to OpenStack components, especially in Neutron, Nova and Ironic.)*

* **Isao Watanabe** *(He is a Software Development Engineer of Fujitsu Limited. Mayjor active in Neutron and openstack-infra. He build the Fujitsu 3rd party CI for Cinder, Ironic and Neutron. He also is the main maintainer of the Fujitsu CI systems.)*
