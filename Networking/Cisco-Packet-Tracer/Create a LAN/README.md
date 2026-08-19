Cisco Packet Tracer — Create a LAN
Overview:

A hands-on Cisco Packet Tracer activity focused on creating and configuring a Local Area Network (LAN) for a new branch office.

The activity involved connecting network devices and hosts, configuring both dynamic and static IPv4 addressing, verifying local and remote connectivity, accessing a web server through both an IP address and a URL, and using networking commands to examine host and network information.

Skills Practiced:
LAN setup and deployment
Network device connectivity
Ethernet cabling
Router and switch connectivity
DHCP configuration
Static IP addressing
IPv4 configuration
Subnet mask configuration
Default gateway configuration
DNS verification
Printer configuration
Network connectivity testing
Command-line verification using ipconfig
Route tracing using tracert
Basic network troubleshooting
Network Configuration
The activity included:
Office Router
Office Switch
Admin PC
Manager PC
Printer
Internet Cloud
Web Server
Device addressing:
Device	IP Address	Configuration Type
Admin PC	DHCP	Dynamic
Manager PC	DHCP	Dynamic
Printer	192.168.1.100	Static
Web Server	209.165.200.225	Preconfigured
Network information:
LAN Network: 192.168.1.0/24
Printer IP Address: 192.168.1.100
Subnet Mask: 255.255.255.0
PC Address Assignment: DHCP
Web Server IP Address: 209.165.200.225
Files:
File	Description
Create-a-LAN.pkt	Completed Cisco Packet Tracer activity
Create-a-LAN.html	Original activity instructions and reference
What I Practiced:

This activity helped me practice how to build a basic office LAN by physically connecting network devices and end devices using Ethernet cables. I learned how to configure hosts to obtain IPv4 addresses automatically through DHCP while assigning a static IP address to a network printer.

I also practiced verifying connectivity between local devices using the ping command, testing internet connectivity through both IP addresses and domain names, and analyzing network information using the ipconfig and tracert commands.

Additionally, this activity improved my understanding of DHCP, DNS, default gateways, subnet masks, local network communication, and the differences between dynamic and static IP addressing.

Commands Used:
ipconfig
ipconfig /all
ping 192.168.1.100
tracert www.cisco.pt
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, improving my networking skills, and building hands-on experience with Cisco technologies and cybersecurity concepts.
