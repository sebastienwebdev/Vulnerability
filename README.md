<h1> Apache HTTP Server </h1>

 ### [Medium Article Demonstration](https://medium.com/@sebastienwebdev/exploit-apache-http-server-vulnerabilities-a18049ee1f05)

<h2>Description</h2>
This project showcases a Python script aimed at understanding and exploiting a Denial of Service (DoS) vulnerability, specifically CVE-2023–43622, found in Apache HTTP Server versions prior to 2.4.58. The vulnerability involves manipulating the initial window size in HTTP/2 connections, potentially causing server resource exhaustion. The script utilizes socket for TCP connections, threading for concurrent attacks, and h2.connection for HTTP/2 protocol handling, demonstrating how to establish a TCP connection, initialize an HTTP/2 connection, manipulate window size, and send requests to flood the server with difficult-to-process connections.

Designed for educational purposes and conducted in a controlled environment, this demonstration highlights the importance of upgrading to Apache version 2.4.58 or later to mitigate the vulnerability. By exploring this exploit, cybersecurity enthusiasts can gain practical insights into the mechanisms of DoS attacks and the significance of continuous server maintenance and vulnerability assessment in enhancing cybersecurity defenses.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Pulsar (Text Editor)</b>
- <b>Nessus Vulnerability Scanner </b>

<h2>Environments Used </h2>

- <b>MacOS</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch Nessus: <br/>
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*45Y3OjTUP0ag81eILYtLdg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the Vulnerability:  <br/>
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*q-VsWKR0BGSt0SJ4lkXSFA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
