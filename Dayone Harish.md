My self 
### Gunda Harish, 
Designation : Security Engineer.

I am here to file my daily bases work I do to get in practise as-well-as to improve my skills level.

##Topics of the Day 

### Different websites : 
1. Shodon.io (account created)
2. Censys.io (account created)
3. CRT.sh
4. Archive.org
5. MXtoolbox.com
6. Kitterman
7. Greynoise.io
8. Hunter.io
9. Recon.dev
10. Spiderfoot.net

### Different types of TOOLS 
1. Dig
2. Nmap
3. Aquatone
4. Sublist3r
5. Go buster

### Websites 

## Shodan.io

Shodan is also a search engine, but one designed specifically for IoT devices. It scours the invisible parts of the Internet most people won’t ever see. Any connected device can show up in a search, including:server, printers, webcams, traffic lights, security camaras and control systems etc...,

Shodan works based on 3 service contecnts. 
a. The Algorithm
b. The Service Banner
c. The ports

* The Algorithm:

   1. Generate a random IPv4 address.
   2. Collect a real-time list of connected devices online.
   3. Query a supported port.
   4. Check the IPv4 address on the port.
   5. Grab a service banner.
   6. Repeat.

* The Service Banner:

Service banners contain all the metadata related to a specific device.

   1. Geographic location
   2. Default username and passwords
   3. IP address
   4. Software version
   5. Make and model

* The Ports:

 With just a quick search or scan on Port numbers, you can explore the wider lot and spot key vulnerabilities in connected devices.
   1. Port 554 – Real Time Streaming Protocol
   2. Port 5060 – SIP(Session Initiation Protocol)
   3. Port 25 – SMTP(Simple Mail Transfer Protocol)
   4. Port 161 – SNMP(Simple Network Management Protocol.)
   5. Port 23 – Telnet
   6. Port 993 – IMAP(Internet Message Access Protocol)
   7. Port 22 – SSH(Secure Shell)
   8. Port 21 – FTP(File Transfer Protocol)
   9. Ports 8443, 443, 8080, and 80 – HTTPS/HTTP
 
## Censys.io

Censys is also a public search engine allows computer scientists to ask questions about the devices and networks that compose the Internet.

Censys maintains three datasets through daily ZMap scans of the Internet and by synchronizing with public certificate transparency logs:

   * Hosts on the Public IPv4 Address Space
   * Websites in the Alexa Top Million Domains
   * Certificates

##### IPv4 Banners

Lightweight banner grabs on more than 1000 popular ports across all hosts in the IPv4 address space.

##### Certificates 

Raw and parsed data certificates synchronized with public CT logs or discovered via Internet-wide scans 

##### Websites 

Port and protocol scan data for websites in the Alexa top million domains 



## CRT.sh
(https://crt.sh/)

* CRT.sh Certificate Search Recon Script.

The tool https://crt.sh/ is a certificate log monitor. So it’s visible how many certificates are created with a domain name.



## Archive.org


Using the Internet Archive Wayback Machine, it is possible to search for the names of sites contained in the Archive (URLs) and to specify date ranges for your search. We hope to implement a full text search engine at some point in the future.

(https://archive.org/) In simple it is place where we can search webpages in detail by using its URL.

## MXtoolbox.com


MxToolbox supports global Internet operations by providing free, fast and accurate network diagnostic and lookup tools for blacklist, email, dns, website, and network performance.

MXtoolbox also deal with below commands:

>Command 	  	Explanation
1. blacklist: 	  	Check IP or host for reputation
2. smtp: 	  	Test mail server SMTP (port 25)
3. mx: 	  	DNS MX records for domain
4. a: 	  	DNS A record IP address for host name
5. spf: 	  	Check SPF records on a domain
6. txt: 	  	Check TXT records on a domain
7. ptr: 	  	DNS PTR record for host name
8. cname: 	  	DNS canonical host name to IP address
9. whois: 	  	Get domain registration information
10. arin: 		Get IP address block information
11. soa: 		Get Start of Authority record for a domain
12. tcp: 		Verify an IP Address allows tcp connections
13. http: 		Verify a URL allows http connections  
14. https: 		Verify a URL allows secure http connections  
15. ping: 		Perform a standard ICMP ping
16. trace: 		Perform a standard ICMP trace route
17. dns: 		Check your DNS Servers for possible problems 

