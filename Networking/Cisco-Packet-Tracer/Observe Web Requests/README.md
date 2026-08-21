Cisco Packet Tracer — Observe Web Request
Overview:

A hands-on Cisco Packet Tracer activity focused on observing client/server traffic between a PC and a web server when requesting web services.

The activity involved verifying DNS connectivity, accessing a web server through a domain name, examining the HTML code hosted on the server, and using Packet Tracer's Simulation Mode to observe TCP and HTTP traffic between the client and web server.

Skills Practiced:
Client/server communication
DNS name resolution
Web server connectivity
HTTP communication
TCP communication
TCP connection establishment
TCP acknowledgements
Web browser configuration
HTML source code inspection
Packet Tracer Simulation Mode
Complex PDU creation
Simulation event filtering
Network traffic analysis
Packet flow observation
Understanding network traffic overhead
Network Configuration

The activity included:

External Client
ciscolearn.web.com web server
DNS service
HTTP service
TCP communication

The web server was accessed using:

ciscolearn.web.com

The activity also used the following Complex PDU configuration:

Application: HTTP
Starting Source Port: 1000
Periodic Interval: 120 seconds
What I Practiced:

This activity helped me understand how a client communicates with a web server when requesting web services.

I practiced using the ping command with a domain name to observe how DNS resolves ciscolearn.web.com to an IP address. I then accessed the web server through the simulated web browser and examined the HTML source code responsible for generating the displayed webpage.

I also practiced using Packet Tracer's Simulation Mode to create and analyze a Complex PDU. By filtering for TCP and HTTP traffic, I was able to observe the packets exchanged between the External Client and the web server.

Commands Used:
ping ciscolearn.web.com
Simulation Process:

The activity followed these main steps:

Verified connectivity to ciscolearn.web.com.
Observed the IP address returned through DNS resolution.
Opened the web server using the simulated browser.
Examined the server's index.html file.
Compared the HTML code with the webpage displayed on the client.
Entered Packet Tracer Simulation Mode.
Configured the event filters to display TCP and HTTP.
Created a Complex PDU from the External Client.
Configured HTTP as the application.
Set the starting source port to 1000.
Set the periodic interval to 120 seconds.
Played the simulation and observed the traffic flow.
Examined the Event List and packet exchanges.
Key Observation:

The activity demonstrated that HTTP uses TCP for communication. TCP requires connection establishment and acknowledgements, which results in additional traffic being exchanged between the client and web server.

The simulation therefore provided a practical view of the traffic overhead associated with TCP-based HTTP communication.

Files:
File	Description
Observe-Web-Request.pkt	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, analyzing network traffic, and building hands-on experience with networking, web protocols, and cybersecurity concepts.
