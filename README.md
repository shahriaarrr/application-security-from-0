**Yasho Application Security Course (YAS)**

[List of recommended books for the course](./books.md)

[Chapter 1 - What is this course](https://www.youtube.com/watch?v=xBRyTsOMQRk)

- Who am I?
- What is going to be covered?
- How is this course going to be published?

Chapter 2 - Internet
- Introduction
- Network nodes
	- server
	- client
	- host
- What is the Internet?
- OSI model
  - Introduction and example
  - TCP/UDP
- Connection
	- IP and Port
	- Public and Private IP
	- 3-way TCP handshake
	- Netcat, make a connection 
- Web server
	- Concept
	- Connecting to a webserver
- Domain name system (DNS)
	- Concept
	- How DNS works?
	- DNS server
	- DNS client
	- Name server
	- DNS lookup by DIG
	- Host file
- Capturing the traffic
	- Wireshark
	- TCPDump
- Final words

Chapter 3 - HTTP protocol
- Versions and RFCs
- Webserver again
- URLs
  - Syntax and parts
  - Check a URL list 
- HTTP
  - Message
  - Request line
  - HTTP method
  - Status line
  - Headers
  - Body
- Sending some HTTP requets
- [the list of all headers](https://developer.mozilla.org/en-US/docs/Web/API/Headers)
  - Important headers
    - Authentication
    - Caching
    - Conditional
    - Cookie
    - CORS
    - Message Body
    - Proxies
    - Redirects
    - Request Context
    - Security
- HTTPS
  - Reveiw, Problem
  - Symmetric Encryption
  - Asymmetric Encryption
  - Signature and authentication
  - SSL Protocol
  - Certificates and authorities
  - Trust chain
  - How does SSL work?
  - The handshake
  - Implementation
  - Security issues

Chapter 4 - Web application architecture

- Web server
  - Installing Apache
  - Configuring Apache
    - ServerRoot
    - Listen
    - User and Group
    - ServerName
    - DocumentRoot
    - ErrorLog
    - Directory
    - Files
    - IfModule
    - Include
    - IncludeOptional
  - Process owner
  - Packet flow
  - Some comcepts
    - Virtual host
      - Configuration
      - Access
    - Mapping
    - htaccess
    - Wrerite module
  - Security
    - IP based authentication
    - Checking referrer header
    - Denying sensitive directories
    - Authentication
      - types
      - Configuring basic authentication
      - Attack on basic authentication
  - Static vs dynamic resources
- What is a web application?
- Traditional architecture
  - Web server + language
- Modern architecture
  - TODO
- Digging HTTP content types
  - TODO
- TODO

Chapter 5 - Security
- Vulnerability
  - The root cause
  - Technical vulnerabilities
  - Logical vulnerabilities
  - Severity
  - Categories
  - CVSS score
  - Exploit
  - Payload
  - Attack vector
  - CVE
  - 0day, 1day
  - OWASP
  - The security triangle
    - Availability
    - Integrity
    - Confidentiality
- Security Concepts
  - Privilege escalation
  - Sniffing
  - Man in the middle
  - Security assessment tools and scripts
  - Security scanners
  - Kali linux
  - Defense in depth
  - Devices
    - Firewall
    - IDS, IPS
    - WAF
- Definitions
  - SSLDC
  - Hardenning
  - Vulnerability assessment
  - Penetration test
  - Red team penetration test
  - Bug bounty
  - SIEM and SOC

Chapter 6 - OWASP TOP 10
- Introduction to SQL injection
- Introduction to Command injection
- Introduction to Remote Code Injection
- Introduction to Broken Authentication
- Introduction to Sensitive Data Exposure
- Introduction to XML External Entities
- Introduction to Broken Access Control
  - Concept
  - Insecure Direct Object Reference
- Introduction to Security Misconfiguration
- Introduction to Cross-Site Script
  - Concept
  - Discovery
  - Impact
- Introduction to Insecure Deserialization
- Using component with known vulnerabilities
- Insufficient Logging and Monitoring

Chapter 7 - More vulnerabilities
- Introduction to Open Redirect
- Introduction to Server Side Request Forgery
- Introduction to Race Condition
- Introduction to HTTP Smuggling
- Introduction to HTTP Cache Poisoning
- Introduction to HTTP Cache Deception

Chapter 8 - The end
- Vulnerability discovery
- The assessment methodology
- The hunting methodology
