Load Balance without Load Balancer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

It's almost A year and half after Kakao's revealing its network model in Vancouver summit ("SDN without SDN"). For preparing very fast growth, We made /32 bit subnet and full routing based network. VM's numbers is now heading for the 10,000 (it was not more than 1,000 at the time of last year's presentation), but we can manage very large number of VM with very small group of people due to OpenStack and Our Network Model  as well. We developed several Virtual Network Function based on our network model. One is Floating IP, The other one is programmable and scalable Load Balancer.  In Production service, people needs a way to assign Public IP or VIP through Neutron's Network node for a VM. Before Neutron's DVR is released and stablized, We also have to find a way for this network functionality. During this session we'll share about the story of developing scalable NAT and Loadbalancer without using traditional Load Balancer leveraging technology like BGP, MPLS , ECMP and Neutron.


* **yongjoon kong** *(Andrew Kong is now Cloud Computing Cell Lead at DaumKakao. Prior to joining Daumkakao, Andrew developed a lots of cloud and big data service for Korean Telecommunication companies.  Now Andrew and his team is responsible for designing and developing highly scalable, geographically distributed infrastructure and platforms to meet the unique requirement from developers. )*
