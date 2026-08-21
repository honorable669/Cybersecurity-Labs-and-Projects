Cisco Packet Tracer — Use the ping Command
Overview:

A hands-on Cisco Packet Tracer activity focused on using the ping command to identify and troubleshoot an incorrect network configuration on a PC.

The activity involved testing web connectivity from multiple PCs, identifying the PC that could not access the web server, using ping to investigate connectivity, comparing DNS server configurations with correctly configured PCs, and correcting the affected PC's network settings.

Skills Practiced:
Network connectivity testing
Using the ping command
DNS troubleshooting
IP address verification
Static IP configuration
DNS server configuration
Using ipconfig /all
Comparing PC network configurations
Identifying network misconfigurations
Troubleshooting domain name resolution
Correcting PC network settings
Web connectivity verification
Basic network troubleshooting
Network Configuration

The activity included:

Multiple PCs with static IP addressing
Web Server
DNS configuration
www.cisco.pka web service

The web server was accessed using:

www.cisco.pka

The activity identified:

PC2

as the PC experiencing connectivity issues.

What I Practiced:

This activity helped me understand how the ping command can be used to troubleshoot connectivity problems and identify whether an issue is related to IP connectivity or DNS configuration.

I first tested the website from each PC and identified PC2 as the PC that could not connect to the web server.

I then used ping www.cisco.pka to investigate the issue and compared the DNS server configuration of PC2 with the correctly configured PCs using ipconfig /all.

The activity demonstrated that a PC may be able to reach a web server by IP address while still being unable to access it using its domain name when there is an incorrect DNS configuration.

Commands Used:
ping www.cisco.pka
ipconfig /all
Troubleshooting Process:

The activity followed these main steps:

Tested www.cisco.pka from each PC using the Web Browser.
Identified PC2 as the PC unable to connect.
Opened the Command Prompt on PC2.
Used ping www.cisco.pka.
Observed the IP address returned for the domain.
Tested the web server's IP address directly.
Compared DNS server information between correctly configured PCs and PC2.
Used ipconfig /all to examine the configurations.
Corrected the necessary settings in Desktop → IP Configuration.
Reopened the Web Browser and tested www.cisco.pka.
Verified that the configuration change resolved the connectivity problem.
Key Observation:

The activity demonstrated an important troubleshooting concept: successful IP connectivity does not necessarily mean that DNS is configured correctly.

If a PC can reach the web server using its IP address but cannot reach it using www.cisco.pka, the problem can be related to the DNS server configuration on that PC.

Files:
File	Description
Use-the-ping-Command.pkt	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, troubleshooting network connectivity, and building hands-on experience with networking and cybersecurity concepts.
