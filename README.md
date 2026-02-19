          Simple Office Network Design

This project demonstrates a Simple Office Network Design created using Cisco Packet Tracer.  
The network is designed for a small office environment with three departments:

   Admin (VLAN 10)
   Finance (VLAN 20)
   Customer (VLAN 30)

                 1.VLAN Configuration

| Department | VLAN ID | Network Address | Subnet Mask | Default Gateway |
|------------|----------|----------------|--------------|----------------|
| Admin      | 10       | 192.168.10.0   | 255.255.255.0 | 192.168.10.1 |
| Finance    | 20       | 192.168.20.0   | 255.255.255.0 | 192.168.20.1 |
| Customer   | 30       | 192.168.30.0   | 255.255.255.0 | 192.168.30.1 |

            2.Network Topology

 1 Router (Inter-VLAN Routing)
 1 Core Switch (Cisco 2960)
 3 Access Points (One per department)
    PCs, Laptops, Tablets, Smartphones
    Network Printers
Each department is logically separated using VLANs while connected to a central switch.
  
          3.Configurations Implemented
 VLAN Creation (10, 20, 30)
 Access Port Assignment
 Trunk Configuration (Switch ↔ Router)
 Inter-VLAN Routing (Router-on-a-Stick)
 Wireless Access Point Configuration
 IP Address Assignment (Static)
 Connectivity Testing using Ping

        4.Network Features

 Departmental Network Segmentation
 Reduced Broadcast Traffic
 Secure Inter-Department Communication
 Wired and Wireless Device Integration
 
       5. Tools
 Cisco Packet Tracer
 Cisco Router
 Cisco 2960 Switch
 Access Points
 End Devices (PCs, Laptops, Printers, Smartphones)

       6.Testing & Verification

 Successful communication within same VLAN
 Inter-VLAN communication through router
 Wireless devices connected and tested
 End-to-end connectivity verified using ping

      7.Diagram
<img width="781" height="428" alt="Net Design" src="https://github.com/user-attachments/assets/7e6954b3-8bbc-4881-bfff-37ee36b858ec" />

     8.Project Objectives

 Understand VLAN implementation
 Practice subnetting and IP addressing
 Configure trunking and inter-VLAN routing
 Simulate a real-world small office network


  Amariya Tesfaw
