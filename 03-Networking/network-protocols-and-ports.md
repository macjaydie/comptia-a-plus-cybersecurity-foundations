# Network Protocols and Ports



This document explains common network protocols and the port numbers they use. Understanding these is essential in cybersecurity because network monitoring and threat detection rely heavily on recognizing normal and abnormal traffic.



---



## What Is a Protocol



A protocol is a set of rules that define how devices communicate over a network.



Protocols determine:

- How data is formatted

- How it is transmitted

- How errors are handled



---



## What Is a Port



A port is a logical communication endpoint used by applications and services.



IP address = identifies the device  

Port number = identifies the specific service on that device



Example:

A web server might have IP `192.168.1.10` and use port `80` for web traffic.



---



## Common Protocols and Their Ports



### HTTP – Port 80

Used for unencrypted web traffic.



### HTTPS – Port 443

Encrypted web traffic using SSL/TLS.



### FTP – Port 21

Used for file transfers. Insecure if not encrypted.



### SSH – Port 22

Secure remote login to systems, commonly used in Linux administration.



### RDP – Port 3389

Remote Desktop Protocol used to remotely access Windows systems.



### DNS – Port 53

Resolves domain names (like google.com) into IP addresses.



### SMTP – Port 25

Used for sending email between mail servers.



### POP3 – Port 110

Used for receiving email.



### IMAP – Port 143

Used for accessing email stored on a server.



---



## TCP vs UDP



Many protocols use either TCP or UDP.



### TCP (Transmission Control Protocol)

- Reliable

- Connection-based

- Used when data accuracy is important (e.g., HTTP, HTTPS, FTP)



### UDP (User Datagram Protocol)

- Faster but less reliable

- No connection setup

- Used for streaming, gaming, and DNS



---



## Why Protocol and Port Knowledge Matters in Cybersecurity



Security professionals use port and protocol knowledge to:

- Identify suspicious network traffic

- Detect unauthorized services

- Investigate malware communication

- Configure firewalls and intrusion detection systems



For example, unexpected traffic on port 3389 (RDP) could indicate an attempted remote access attack.
