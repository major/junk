Octavia Load Balancer as the last line of your cloud application defense
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

This talk is about turning on HTTPs handling in Octavia, the Open-Stack Load-Balancing as a Service. Octavia's Load-Balancer nodes can terminate the HTTPs connections at the Load-Balancer tier. It can improve your service performance by off-loading the TLS work from your back-end servers. It is required if you want to apply Octavia's L7 Load-balancing rules while using HTTPs. Cool!, so WHAT ARE THE ISSUES? (Q1) How much load is cause by TLS stuff? Answer: It depends.... but it may be significant (Q2) Can the Load-Balancer handle it? Answer: Usually not! -- you need ACTIVE-ACTIVE (Q3) Is it secure? Answer: Yes, but read the fine print... Follow-up questions: With Active-Active turned on several Load-Balancer nodes can handle the TLS load, but there is a new piece to the puzzle -- the Distributor. (Q4) Can the Distributor handle the load? Answer: Yes! (Q5) Is the Distributor secure? Answer: Yes, but read the fine print...


* **Dean Lorenz** *(Dr. Dean H. Lorenz is Research Scientist at IBM Research HaifaLab, a technical leader at the Cloud Networking group of the Cloud Platforms department. Dr. Lorenz received his B.Sc. in Computer Engineering (Summa Cum Laude) and Ph.D. in Electrical Engineering, both from the Technion – Israel Institute of Technology. He has more than 15 years of experience in research, hands-on development, and innovation in Networking, Virtualization, Storage, and Mobile Technologies. Dr. Lorenz has held technical positions at leading companies in these industries, including IBM Research, Akamai, Adobe Omniture, and Qualcomm. He has re-joined IBM Research in 2014, and is currently researching Cloud technologies, with focus on Cloud networking, elasticity, and operation efficiency.)*

* **Banashankar  Kalebelagund** *(...)*
