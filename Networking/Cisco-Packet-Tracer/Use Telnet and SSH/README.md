Cisco Packet Tracer — Use Telnet and SSH
Overview:

A hands-on Cisco Packet Tracer activity focused on establishing remote connections to a router using Telnet and Secure Shell (SSH).

The activity involved verifying the PC's DHCP-assigned IP address, testing connectivity to the remote HQ router, attempting a Telnet connection, and then using SSH to securely access the router after Telnet was rejected.

Skills Practiced:
Remote device access
Telnet connectivity testing
SSH remote access
DHCP verification
IPv4 addressing
Network connectivity testing
Router accessibility verification
Command-line networking
Secure remote administration
Basic troubleshooting
Understanding secure vs. insecure remote access
Network Configuration

The activity included:

HQ Router
PC0
PC1
HQ Router:
Interface: G0/0/1
IP Address: 64.100.1.1
Subnet Mask: 255.255.255.0
PCs:
PC0: DHCP
PC1: DHCP
What I Practiced:

This activity helped me understand how remote access protocols are used to manage network devices.

I practiced verifying the IP configuration received through DHCP using ipconfig, testing connectivity to the HQ router using ping, and attempting to establish a remote connection using Telnet.

The Telnet connection was intentionally rejected because the router was configured not to allow insecure Telnet access. I then used SSH with the provided administrator credentials to securely access the router.

After successfully connecting through SSH, the router displayed the HQ# prompt, confirming that remote access was successful.

Commands Used:
ipconfig
ping 64.100.1.1
telnet 64.100.1.1
ssh -l admin 64.100.1.1
SSH Credentials:
Username: admin
Password: class
Remote Access Process:

The activity followed these main steps:

Verified the PC's DHCP-assigned IP address.
Tested connectivity to the HQ router using ping.
Attempted to access HQ using Telnet.
Observed that the Telnet connection was closed by the remote host.
Used SSH instead of Telnet.
Authenticated using the provided credentials.
Successfully accessed the HQ router.
Verified access by observing the HQ# command prompt.
Key Observation:

The activity demonstrated the difference between Telnet and SSH for remote device administration.

Telnet access was rejected by the HQ router, requiring the use of SSH for remote access. This demonstrated why secure remote-access protocols are important when managing network infrastructure.

Files:
File	Description
Use-Telnet-and-SSH.pkt	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, practicing secure network administration, and building hands-on experience with networking and cybersecurity concepts.
