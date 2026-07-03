# 🌍 How The Web Works

> **Learning Path:** Pre Security
> **Module:** 03 — How The Web Works
> **Platform:** TryHackMe
> **Status:** ✅ Completed

---

# 📖 About This Module

The World Wide Web is one of the largest and most important communication systems ever created. Every day, billions of users access websites, cloud applications, APIs, online banking, social media platforms, and streaming services through web technologies.

Behind every webpage lies a complex sequence of communication involving DNS, web servers, HTTP requests, browsers, databases, encryption, and network protocols.

This module explores the complete lifecycle of a web request—from typing a URL into a browser to receiving a fully rendered webpage. It introduces the technologies that make modern websites possible and builds the foundation required for understanding web application security, penetration testing, and secure software development.

Understanding how the web functions is essential for identifying vulnerabilities, analysing attacks, and building secure web applications.

---

# 🎯 Learning Objectives

After completing this module, I was able to:

* Explain how websites are delivered over the Internet.
* Understand the role of web browsers and web servers.
* Describe how DNS translates domain names into IP addresses.
* Explain the HTTP protocol and the request–response model.
* Understand how web pages are rendered by browsers.
* Recognise the interaction between clients, servers, databases, and APIs.
* Build a foundation for studying web security.

---

# 📚 Rooms Completed

| Room                    | Status      |
| ----------------------- | ----------- |
| DNS in Detail           | ✅ Completed |
| HTTP in Detail          | ✅ Completed |
| How Websites Work       | ✅ Completed |
| Putting It All Together | ✅ Completed |

---

# 🌍 Why Web Technologies Matter

Modern organisations rely heavily on web applications.

Examples include:

* Online Banking
* E-commerce Platforms
* Social Media
* Government Portals
* Cloud Dashboards
* Email Services
* Healthcare Systems
* Educational Platforms
* AI Applications

Because these services are publicly accessible, they are among the most common targets for cyber attacks.

A cybersecurity professional must understand how web applications function before learning how they can be attacked or defended.

---

# 🧠 Core Concepts

Throughout this module I explored the following concepts:

## Domain Name System (DNS)

DNS acts as the Internet's directory service.

Instead of remembering numerical IP addresses, users access websites through human-readable domain names. DNS resolves these domain names into IP addresses that computers use for communication.

Examples:

* google.com
* github.com
* microsoft.com

---

## Web Browsers

A web browser serves as the client that requests information from web servers.

Examples include:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari

The browser is responsible for:

* Sending HTTP requests
* Rendering HTML pages
* Executing JavaScript
* Displaying CSS styling
* Managing cookies and sessions

---

## Web Servers

Web servers receive requests from clients and deliver web resources.

Common web servers include:

* Apache HTTP Server
* Nginx
* Microsoft IIS
* LiteSpeed

Their responsibilities include:

* Processing client requests
* Serving web pages
* Managing sessions
* Communicating with databases
* Returning HTTP responses

---

## HTTP

HyperText Transfer Protocol (HTTP) is the primary protocol used for communication between clients and web servers.

HTTP follows a request–response model.

Common request methods include:

* GET
* POST
* PUT
* DELETE
* PATCH

HTTP status codes communicate the result of a request.

Examples:

* 200 OK
* 301 Moved Permanently
* 302 Found
* 403 Forbidden
* 404 Not Found
* 500 Internal Server Error

---

## HTTPS

HTTPS is the secure version of HTTP.

It encrypts communication using TLS (Transport Layer Security), helping protect:

* User credentials
* Banking information
* Personal data
* Session cookies

HTTPS significantly reduces the risk of interception during data transmission.

---

## Website Components

A typical website consists of several technologies working together:

* HTML
* CSS
* JavaScript
* Web Server
* Database
* APIs
* Authentication Systems

These components combine to deliver interactive and dynamic web experiences.

---

# 🔄 The Web Request Lifecycle

Every webpage request follows a sequence of events:

```text
User
   │
   ▼
Browser
   │
   ▼
DNS Lookup
   │
   ▼
IP Address
   │
   ▼
Internet
   │
   ▼
Web Server
   │
   ▼
Application
   │
   ▼
Database
   │
   ▼
HTTP Response
   │
   ▼
Browser Rendering
```

Understanding this workflow is essential for troubleshooting and security analysis.

---

# 🛠 Skills Gained

By completing this module, I developed an understanding of:

* DNS resolution
* Browser behaviour
* Web server communication
* HTTP request and response flow
* Website architecture
* Client-server communication
* Web technologies
* Basic Internet infrastructure

---

# 💼 Real-World Applications

The concepts learned in this module directly apply to:

* Web Application Security
* Penetration Testing
* Bug Bounty Hunting
* API Security
* Secure Software Development
* Reverse Proxy Configuration
* Cloud Web Services
* Security Operations Centres (SOC)
* Digital Forensics
* Network Traffic Analysis

---

# 🌐 Knowledge Map

```text
Internet
│
├── DNS
│      │
│      ▼
│   IP Address
│
├── Browser
│      │
│      ▼
│   HTTP / HTTPS
│
├── Web Server
│      │
│      ▼
│   Application
│      │
│      ▼
│   Database
│
└── Response
       │
       ▼
Rendered Web Page
```

---

# 🔗 Connections to Future Modules

This module provides the foundation for understanding:

* Web Application Security
* OWASP Top 10
* SQL Injection
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Authentication
* Session Management
* Cookies
* APIs
* Reverse Proxies
* Cloud Web Applications
* Bug Bounty Hunting

Understanding how legitimate web applications function is the first step toward identifying security weaknesses.

---

# 📋 Revision Checklist

* [x] Understand DNS resolution
* [x] Explain the role of web browsers
* [x] Explain the role of web servers
* [x] Understand HTTP requests and responses
* [x] Understand HTTPS and TLS
* [x] Identify common HTTP methods
* [x] Recognise common HTTP status codes
* [x] Explain the complete web request lifecycle

---

# 📌 Key Takeaways

* Every website relies on communication between clients and servers.
* DNS translates human-readable domain names into IP addresses.
* HTTP enables communication between browsers and web servers.
* HTTPS secures communication through encryption.
* Modern websites integrate browsers, servers, databases, and APIs into a unified system.
* Understanding web technologies is essential before learning web application security.

---

# 📖 Further Reading

* Mozilla Developer Network (MDN)
* OWASP Foundation
* RFC 7231 — HTTP/1.1 Semantics
* RFC 9110 — HTTP Semantics
* Let's Encrypt Documentation
* Microsoft Learn — Web Fundamentals

---

# 🏆 Module Completion

**Module:** How The Web Works
**Learning Path:** Pre Security
**Platform:** TryHackMe

**Status:** ✅ Completed

---

> *"Every secure web application begins with understanding how the web communicates. Master the fundamentals first, then learn how attackers exploit them—and how defenders stop them."*
