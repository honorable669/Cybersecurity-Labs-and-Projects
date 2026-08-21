Cisco Packet Tracer — Use FTP Services
Overview:

A hands-on Cisco Packet Tracer activity focused on using File Transfer Protocol (FTP) to transfer files between a client PC and an FTP server.

The activity involved locating a file on a PC, connecting to an FTP server using FTP credentials, uploading the file to the server, renaming the uploaded file, downloading it back to the PC, and deleting the file from the FTP server.

Skills Practiced:
FTP client/server communication
File transfer between client and server
FTP server connectivity
FTP authentication
File upload using put
File download using get
Directory listing using dir
File renaming using rename
File deletion using delete
FTP session management
Command-line file management
Network service interaction
Basic troubleshooting
Network Configuration

The activity included:

PC-A
FTP Server (ftp.pka)
FTP Server Address:
IP Address: 209.165.200.226
Subnet Mask: 255.255.255.224
FTP Credentials:
Username: student
Password: class
FTP Ports:
Command Port: 21
Data Transfer Port: 20
What I Practiced:

This activity helped me understand how FTP is used to transfer files between a client and server over a network.

I practiced locating files on a client PC using the dir command, connecting to an FTP server using an IP address, authenticating with a username and password, and viewing files available on the server.

I also practiced uploading files using the put command, renaming files using rename, downloading files using get, and deleting files from the FTP server using the delete command.

FTP Commands Used:
ftp 209.165.200.226
dir
put sampleFile.txt
rename sampleFile.txt sampleFile_FTP.txt
get sampleFile_FTP.txt
delete sampleFile_FTP.txt
quit
File Transfer Process:

The activity followed these main steps:

Located sampleFile.txt on PC-A.
Connected to the FTP server using its IP address.
Logged in using the provided FTP credentials.
Viewed the files available on the FTP server.
Uploaded sampleFile.txt using the put command.
Verified the uploaded file using dir.
Renamed the file to sampleFile_FTP.txt.
Verified the renamed file.
Downloaded the file using the get command.
Exited the FTP session.
Reconnected to the FTP server.
Deleted sampleFile_FTP.txt using the delete command.
Key Observation:

The activity demonstrated the basic FTP file-transfer workflow between a client and server.

It also showed how FTP uses port 21 for the server command connection and port 20 for data transfer, allowing clients to authenticate and perform file-management operations such as uploading, downloading, renaming, and deleting files.

Files:
File	Description
Use-FTP-Services.pkt	Completed Cisco Packet Tracer activity
activity.html	Original activity instructions/reference
Status:

✅ Completed

Learning Note:

This is one of my networking practice activities. More labs, experiments, and cybersecurity projects will be added to this repository as I continue learning, analyzing network services, and building hands-on experience with networking and cybersecurity concepts.
