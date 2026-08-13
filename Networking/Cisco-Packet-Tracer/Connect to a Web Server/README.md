Cisco Packet Tracer — Connect to a Web Server

Overview

A hands-on Cisco Packet Tracer activity focused on establishing communication between a client computer and a web server using IPv4 addressing.

The activity involved verifying network connectivity with ICMP, testing communication through the command line, and accessing a web server through a web browser using its IP address.

Skills Practiced

IPv4 addressing
IP configuration analysis
ICMP connectivity testing
Ping command usage
Web client configuration
Web server connectivity
Client-server communication
Basic network troubleshooting
Cisco Packet Tracer navigation

Network Configuration

The activity included:

PC0 (Client)
Internet cloud
LearnIP Web Server

Client configuration:

Setting	Value
IP Address	192.168.1.100
Subnet Mask	255.255.255.0
Default Gateway	192.168.1.1
DNS Server	192.168.1.2

Web server configuration:

Setting	Value
Hostname	LearnIP Web Server
Domain	www.learnIP.com
IP Address	172.33.100.50

Connectivity Verification

Command used:

ping 172.33.100.50

Result:

Successful communication between the client and the web server
ICMP replies received from the destination server
Network connectivity successfully verified

Web Server Access

The web server was accessed through the PC web browser using:

http://172.33.100.50

Web page message:

Welcome to the Learn IP Web Site

Files

File	Description
Connect-to-a-Web-Server.pka	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference

What I Practiced

This activity helped me understand how a client device communicates with a web server across a network using IP addressing. I also practiced connectivity verification using the ping command and learned how web clients establish connections with web servers.

Status

✅ Completed

Learning Note

This is one of my networking practice activities. More labs, experiments, activities, and cybersecurity projects will be added to this repository as I continue learning and building hands-on experience.
