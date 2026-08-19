Cisco Packet Tracer — Observe Traffic Flow in a Routed Network
Overview

A hands-on Cisco Packet Tracer activity focused on observing network traffic behavior in an unrouted LAN and then comparing it with a routed network using multiple IPv4 subnets.

The activity involved analyzing ARP broadcasts, observing ICMP traffic in Simulation Mode, reconfiguring the network into separate departmental subnets, renewing DHCP-assigned IP addresses, and examining how routing contains broadcast traffic within individual networks.

Skills Practiced
IPv4 addressing
Subnetting fundamentals
ARP analysis
MAC address analysis
ICMP connectivity testing
Ping command usage
DHCP address renewal
Router interface configuration analysis
Network segmentation
Broadcast domain analysis
Routed network traffic observation
Cisco Packet Tracer Simulation Mode
Basic network troubleshooting
Network Configuration

The activity included:

Edge Router
ISP cloud
Accounting Switch
Finance Switch
Sales Switch
Accounting 1
Accounting 2
Finance 1
Finance 2
Sales 1
Sales 2
Web Server
IPv4 Network Design
Department	IPv4 Network	Default Gateway
Accounting	192.168.1.0/24	192.168.1.1
Finance	192.168.2.0/24	192.168.2.1
Sales	192.168.3.0/24	192.168.3.1
Router Interfaces
Interface	IP Address	Network
GigabitEthernet0/0	192.168.1.1	Accounting
GigabitEthernet1/0	192.168.2.1	Finance
GigabitEthernet2/0	192.168.3.1	Sales
GigabitEthernet3/0	10.10.10.1/30	ISP
Traffic Observation
Unrouted LAN

Initially, all departments shared the same IPv4 network.

When the ARP cache was empty and Sales 2 pinged Sales 1, an ARP request was generated using the broadcast MAC address:

FFFF.FFFF.FFFF

The ARP broadcast was processed by devices throughout the shared LAN.

Routed Network

After the network was divided into separate IPv4 subnets, the department switches were connected directly to different router interfaces.

When Sales 2 pinged Sales 1, the ARP broadcast remained within the Sales subnet instead of being propagated to the Accounting and Finance networks.

This demonstrated how routing and subnetting reduce unnecessary broadcast traffic.

Connectivity Verification

Commands used during the activity:

arp -a
arp -d
ipconfig
ipconfig /renew
ping <destination-IP>

Example connectivity tests included:

ping 192.168.3.1
ping 192.168.1.1

Successful communication between the Sales network and the router was verified, and inter-network routing was observed through the Edge router.

What I Practiced

This activity helped me understand how ARP broadcasts behave inside a shared LAN and how subnetting and routing change traffic flow.

I practiced analyzing MAC and IP addresses, observing ARP and ICMP PDUs in Packet Tracer Simulation Mode, configuring separate departmental networks, renewing DHCP addresses, and verifying connectivity between different IPv4 networks.

Key Learning

A single large LAN creates a large broadcast domain where ARP broadcasts can reach many unnecessary devices.

Dividing an enterprise network into multiple IPv4 subnets allows broadcast traffic to remain within the relevant network while the router handles communication between departments.

This improves network efficiency, scalability, and traffic management.

Files
File	Description
Observe-Traffic-Flow-in-a-Routed-Network.pka	Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
README.md	Activity documentation
Status

⚠️ Practically Completed — Packet Tracer Assessment Issue

The required network configuration, IP addressing, routing, and connectivity tests were completed successfully.

However, the Packet Tracer assessment reported the activity as incomplete because the Finance 2 IP Address item was not updated correctly after running:

ipconfig /renew

The Finance 2 device successfully obtained an IP configuration, but the assessment remained at 5/6.

Learning Note

This is one of my networking practice activities. It helped me strengthen my understanding of ARP, ICMP, IPv4 subnetting, DHCP, routing, broadcast domains, and network traffic analysis using Cisco Packet Tracer.

More labs, experiments, activities, and cybersecurity projects will be added to this repository as I continue learning and building hands-on experience.
