**OWASP ZAP Web Application Security Assessment**

**Project Overview**
This repository documents a practical web application security assessment conducted using **OWASP ZAP (Zed Attack Proxy)**. The project demonstrates how automated and active security scanning techniques are used to identify common vulnerabilities in web applications within a controlled testing environment.

The target application used for this assessment is **DVWA (Damn Vulnerable Web Application)**, a deliberately insecure web app designed for learning and practice.

 **Tool Used: OWASP ZAP**
OWASP ZAP is a free, open-source web application security testing tool maintained by the Open Web Application Security Project (OWASP). It is widely used by security professionals and beginners to identify security weaknesses in web applications.

ZAP operates as an intercepting proxy, allowing it to sit between a web browser and a target application to inspect, intercept, and analyze HTTP/HTTPS traffic.

**Key Features**
- **Automated Scanning** – Quickly identifies common vulnerabilities such as SQL Injection and Cross-Site Scripting (XSS).
- **Passive Scanning** – Detects issues without actively attacking the application (non-intrusive).
- **Active Scanning** – Actively tests the application using known attack payloads to uncover deeper vulnerabilities.
- **Spidering (Crawling)** – Automatically maps the structure of the target application and discovers hidden endpoints.
- **API & Automation Support** – Can be integrated into CI/CD pipelines for continuous security testing.

---

 **Scan Description**
An Automated Scan was launched against DVWA hosted at: http://172.17.0.2/dvwa



