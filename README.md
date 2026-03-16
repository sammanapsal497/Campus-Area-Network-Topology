🏨 Campus-Area-Network-Topology using Packet Tracer
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Introduction
This project showcases the architecture and deployment of a secure, high-availability Campus Area Network (CAN) connecting a Corporate HQ to a Remote Branch. The design utilizes a Hierarchical Model (Core, Distribution, and Access) to ensure scalability and efficient traffic flow across the enterprise.

🔑 Key technical implementations include:
* Redundancy & Reliability: Deployment of HSRP for gateway redundancy and EtherChannel for increased bandwidth and link-failover between switches.
* Dynamic Routing & Connectivity: Implementation of OSPF to manage reachability between HQ and Branch locations, utilizing a structured IPv4 allocation scheme to prevent subnet overlap.
* Unified Communications & Wireless: Integration of Cisco WLC and Lightweight APs for seamless campus-wide mobility, alongside IP Telephony (CME) and DHCP IP-Helper services for automated device provisioning.
* Hardened Security: Execution of a 'Defense-in-Depth' strategy using MD5 OSPF Authentication, VTY Access Control Lists (ACLs), and SSH to secure the management plane across the entire infrastructure."

