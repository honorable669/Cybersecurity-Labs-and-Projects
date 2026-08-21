Cisco Packet Tracer — Use the ipconfig Command
Overview:

A hands-on Cisco Packet Tracer activity focused on using the ipconfig /all command to identify and correct an incorrectly configured PC.

The activity involved examining the IP address, subnet mask, and default gateway configuration of four PCs on a 192.168.1.0/24 network. One PC was incorrectly configured and unable to access the www.cisco.pka web server. The incorrect configuration was identified by comparing the network settings of all PCs and then correcting the affected PC through the IP Configuration settings.

Skills Practiced:
IPv4 configuration analysis
Static IP addressing
Subnet mask verification
Default gateway verification
Command-line network troubleshooting
Using ipconfig
Using ipconfig /all
Identifying incorrect network configuration
Correcting PC network settings
Network connectivity troubleshooting
Basic LAN troubleshooting
Network Configuration

The activity included:

PC0
PC1
PC2
PC3
Web Server

All PCs were configured using static IPv4 addressing on:

Network: 192.168.1.0/24

The PCs were expected to access:

www.cisco.pka

One of the four PCs contained an incorrect network configuration.

What I Practiced:

This activity helped me practice using ipconfig /all to troubleshoot network configuration problems on Windows-based PCs.

I examined the IP address, subnet mask, and default gateway of each PC and compared their configurations to identify the incorrectly configured device.

After identifying the affected PC, I opened its Desktop → IP Configuration settings and corrected the network configuration so that it could properly communicate with the network and access the web server.

Commands Used:
ipconfig /all
Troubleshooting Process:

The activity followed these main steps:

Opened the Command Prompt on each PC.
Executed ipconfig /all.
Recorded the IP configuration of each PC.
Compared the IP addresses, subnet masks, and default gateways.
Identified the PC with the incorrect configuration.
Opened the affected PC's IP Configuration settings.
Corrected the misconfigured network settings.
Verified the corrected configuration.
Key Observation:

The ipconfig /all command provides important network configuration information that can be used to identify configuration errors.

By comparing the settings of multiple PCs on the same network, an incorrectly configured IP address, subnet mask, or default gateway can be identified and corrected.

Files:
File	Description
Use-the-ipconfig-Command.pkt	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, troubleshooting network configurations, and building hands-on experience with networking and cybersecurity concepts.
