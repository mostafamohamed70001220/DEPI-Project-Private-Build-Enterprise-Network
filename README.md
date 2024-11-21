# Project Overview
This project involves designing and building a private enterprise network spanning two sites. The network is designed for scalability, high availability, and security, utilizing advanced networking protocols and configurations

# Team Members
* Mostafa Mohamed - EtherChannel Specialist and Support Configurator for network redundancy.
* Mostafa Hesham - Network Designer & Lead Configurator for Multi-Layer Switches, HSRP, Inter-VLAN Routing, SSH, and ACL.
* Marwan Mohamed - IP Addressing Scheme Architect Subneting.
* Youssef Fahmy - VLAN Configuration Specialist and Access/Distribution Switch Configurator.
* Ahmed Abdelhakim - OSPF Configuration Specialist.

# Project Timeline 

## Week 0:Project Ideation & Network Blueprint
   * Tasks:
        * Network Desgin-Lead Designer:Mostafa Mohamed
          
## Week 1: Internal Network Setup
   * Tasks:
        * IP Addressing Scheme: Create a complete IP addressing scheme and assign IP addresses and default gateways for 44 end devices, 7 switches, 4 multi-layer switches, and 2 routers – Marwan Mohamed
        * VLAN Configuration: Set up VLANs for the network switches and associated devices – Youssef Fahmy
        * Access and Distribution Switch Configuration: Configure access and distribution switches for each site – Youssef Fahmy

## Week 2:Switch Configuration
   * Tasks:
        * Multi-Layer Switch Configuration: Configure 4 multi-layer switches – Mostafa Hesham
        * Inter-VLAN Routing: Enable and verify Inter-VLAN Routing – Mostafa Hesham
        * HSRP Setup: Configure the Hot Standby Router Protocol (HSRP) for network redundancy – Mostafa Hesham
        * EtherChannel Setup: Configure EtherChannel using both PAgP and LACP for link aggregation – Mostafa Mohamed

 ## Week 3:
   * Tasks:
       * OSPF Configuration: Implement OSPF protocol for dynamic routing between sites – Ahmed Abdelhakim
       * SSH and ACL Configuration: Secure the network by configuring SSH for remote access and ACLs for access control – Mostafa Hesham
    
 ## Week 4:
    * Tasks: 
      * Final Presentation: Compile and present the completed project – All team members
      * Network Troubleshooting: Identify and resolve any issues to ensure network functionality – All team members

# Descrption

This project demonstrates a simulated enterprise network spanning two branches for the same company, designed and configured in Cisco Packet Tracer. The network incorporates advanced networking protocols and security measures, emphasizing scalability, high availability, and secure data transfer across sites.

# Key Features include

 * VLAN Segmentation: Each branch employs multiple VLANs, isolating traffic to enhance network efficiency and security.

 * Inter-VLAN Routing: Efficient routing within branches allows seamless communication between VLANs, ensuring optimized traffic flow and minimized latency.

 * EtherChannel: Configured using both PAgP and LACP protocols, EtherChannel provides increased bandwidth and link redundancy, which is essential for minimizing downtime and improving performance.

 * HSRP (Hot Standby Router Protocol): Implements router redundancy to enhance network availability by allowing immediate failover, ensuring continuous network operation even if one router fails.

 * OSPF (Open Shortest Path First): Configures dynamic routing between branches, allowing for efficient path determination and faster convergence times in case of link failure.

 * SSH (Secure Shell): Secures remote access to devices, ensuring encrypted connections and protecting management traffic from eavesdropping.

 * ACL (Access Control List): Establishes fine-grained traffic filtering, restricting unauthorized access to sensitive network resources while enhancing overall security.

# Key Outcomes

 * Network Efficiency: VLANs and Inter-VLAN routing improve internal communication and reduce congestion within branches.
 * High Availability and Redundancy: HSRP and EtherChannel reduce the risk of downtime and ensure continuous connectivity across the network.
 * Security: SSH and ACL configurations protect network integrity and prevent unauthorized access.

# Tools and Technologies

 *  Cisco Packet Tracer: Used for network design and simulation.
 * Protocols: VLAN, HSRP, SSH, ACL, Inter-VLAN Routing, OSPF, EtherChannel (PAgP & LACP)
