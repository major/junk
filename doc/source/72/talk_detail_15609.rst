OpenStack Networking Adopted and Extended to support the Next Generation Optical DCN Research
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk shows how OpenStack extensibility helps advancing DCN research. EU project COSIGN introduces Optical Circuit Switching to the data plane and a dual pair of SDN controllers to the control plane. We describe how we support both the optical data plane devices and the control plane duality by extending OpenStack Networking. For the virtual layer, we adopt Neutron API with a customized OVN plugin. For the physical layer, we extend Neutron and employ OpenDaylight to command both the Electrical Packet Switches and the Optical Circuit Switches through extended OF. We give implementation details and show a demo of the working adaptable OpenStack Networking integrated with the rest of services – Nova, Heat, and Horizon. Additionally, we give a brief overview of the COSIGN Data Plane and present the SW architecture whereby the dual-controller dynamic feedback loop allows implementing advanced circuit scheduling and traffic steering to support diverse and unpredictable traffic matrices.


* **Yaniv Ben-Itzhak** *(Yaniv Ben-Itzhak is a research staff member in Haifa IBM Research Lab. His research interests include Data-Center networks, Software Defined Networks (SDN), optical networks, network virtualization, and Network Function Virtualization (NFV). Dr. Yaniv Ben-Itzhak received his B.Sc (magna cum laude), M.Sc., and Ph.D. degrees in Electrical Engineering from the Technion – Israel Institute of Technology.)*

* **Katherine Barabash** *(Kathy is a manager and a technical leader of the Cloud Networking Group in IBM Haifa Research Lab and one of the inventors of the IBM's overlay network virtualization solution. Kathy is with IBM Research since 1997, contributing to different system research areas. Since 2007, Kathy is actively involved in cloud and data centre network virtualization research, basing on OpenStack Neutron since about 2011.)*

* **Jose Aznar** *(TBD)*
