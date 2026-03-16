🏨 Campus-Area-Network-Topology using Packet Tracer
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Introduction
This project showcases the architecture and deployment of a secure, high-availability Campus Area Network (CAN) connecting a Corporate HQ to a Remote Branch. The design utilizes a Hierarchical Model (Core, Distribution, and Access) to ensure scalability and efficient traffic flow across the enterprise.

🔑 Key technical implementations include
* Redundancy & Reliability: Deployment of HSRP for gateway redundancy and EtherChannel for increased bandwidth and link-failover between switches.
* Dynamic Routing & Connectivity: Implementation of OSPF to manage reachability between HQ and Branch locations, utilizing a structured IPv4 allocation scheme to prevent subnet overlap.
* Unified Communications & Wireless: Integration of Cisco WLC and Lightweight APs for seamless campus-wide mobility, alongside IP Telephony (CME) and DHCP IP-Helper services for automated device provisioning.
* Hardened Security: Execution of a 'Defense-in-Depth' strategy using MD5 OSPF Authentication, VTY Access Control Lists (ACLs), and SSH to secure the management plane across the entire infrastructure."

🗂️ Network Overview
* Departments:
  - HEADQUARTERS: IT DEPARTMENT, BUYING & PROCUREMENT DEPARTMENT, MARKETING  DEPARTMENT, ACCOUNTING DEPARTMENT.
    
  - BRANCH: SALES FLOOR & CUSTOMER EXPERIENCE, MERCHANDISE & LOGISTICS, LOCAL HUMAN RESOURCE.
* Devices:
  - HEADQUARTERS: 6 Access Switches, 2 Multilayer Switches, 1 Core Router, 1 IP Phone Manager Router, Servers, Printers, Access Points, Workstation, IP Phones & Mobile Devices.
    
  - BRANCH: 4 Access Switch, 2 Multilayer Switch, 1 Core Router, Printers, Workstation, IP Phones & Mobile Devices.
    
* Routing Protocol: OSPF
* Services: DHCP, SSH, Port Security, WLAN, WAN, Telephony.

🖧 VLAN & IP Addressing Table
  - Kindly check the Text file uploaded.

⚙️ Implemented Technologies
  - Hierarchical Network Design
  - VLANs for departmental segmentation
  - Inter-VLAN Routing using SVI
  - OSPF is the dynamic routing protocol
  - DHCP (Using Dedicated Server)
  - SSH for secure remote access
  - Port Security on Access Switches
  - Wireless LAN (WLAN) for laptops and mobile devices
  - WAN
  - Telephony 
  - Printers
  - Cisco APs (WLC - Cisco Meraki)

🧪 Testing & Verification
  - Check out the Screenshots attached.
  ✅ Devices within each VLAN obtained IPs dynamically from DHCP
  ✅ Inter-VLAN communication verified via ping (IT dept. as open to all access)
  ✅ OSPF successfully advertised networks between routers
  ✅ SSH remote login tested from Test-PC
  ✅ Port security tested with sticky MAC
  ✅ WLAN devices connected successfully to APs
  ✅ Telephony test branch to branch, HQ to HQ, HQ to Branch

📂 Files Included
* Packet Tracer.pkt file - 
    

