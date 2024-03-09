# Designed-and-Implemented-a-Scalable-WAN-Network-for-Google-Search-Project
The WAN comprises three Local Area Networks (LANs), each catering to five departments: Admin, IT, Staff, Student, and Management.
Each LAN is allocated a dedicated IP address range:
LAN 1: 172.16.0.0 - 172.16.1.255
LAN 2: 172.16.2.0 - 172.16.3.255
LAN 3: 172.16.4.0 - 172.16.5.255
To enhance network resilience and redundancy, I implemented the following protocols on each LAN:
Hot Standby Router Protocol (HSRP): Ensures uninterrupted routing by providing a primary and backup router.
Open Shortest Path First (OSPF) routing: Optimizes routing paths between networks for efficient data flow.
Link Aggregation Control Protocol (LACP) ether channeling: Combines multiple physical links into a single logical link, increasing bandwidth and fault tolerance.
VLAN Trunk Protocol (VTP): Simplifies VLAN management across the network.
Virtual LANs (VLANs): Logically segments the network for improved security and manageability.
Rapid Spanning Tree Protocol (RSTP): Prevents loops and ensures rapid convergence in case of network topology changes.
