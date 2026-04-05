🛡️ Web Application Security Assessment (Portfolio Project)

📌 Overview

This project presents a security assessment of a self-developed portfolio web application, conducted to identify common vulnerabilities and misconfigurations found in modern web environments.

The goal was to apply practical penetration testing techniques and evaluate the application against widely accepted security best practices, including the OWASP Top 10.

🎯 Objectives

Assess the security posture of a web application I developed
Identify vulnerabilities using industry-standard tools
Analyze common web security misconfigurations
Demonstrate practical knowledge of web application security

🧰 Tools & Technologies

OWASP ZAP – Automated vulnerability scanning
Nmap – Network discovery and port scanning
Node.js (Express) – Application backend
HTML, CSS, JavaScript – Frontend

🔍 Assessment Approach

The assessment was conducted using a combination of:

Passive vulnerability scanning
Network enumeration
Manual validation of findings

Testing was performed in a controlled local environment (localhost:3000).

⚠️ Key Observations

The assessment identified several security misconfigurations that are commonly found in early-stage or development environments:

Exposure of server technology via HTTP headers
Absence of critical security headers
Lack of enforced secure communication (HTTPS)
Missing protections against common web-based attacks

While no critical vulnerabilities were identified, these issues could pose risks if deployed in a production environment.

🛠️ Security Improvements

The following improvements were identified to strengthen the application:

Removal of unnecessary server-identifying headers
Implementation of security headers (e.g., CSP, X-Frame-Options)
Enforcement of HTTPS for secure data transmission
Addition of CSRF protection mechanisms
Hardening of overall application configuration

📸 Screenshots

Screenshots from the assessment process (OWASP ZAP results and application interface) are included in the /images directory.


📊 Key Skills Demonstrated

Web Application Security Testing
Vulnerability Identification & Analysis
Use of Security Testing Tools (OWASP ZAP, Nmap)
Secure Configuration Practices
Understanding of OWASP Top 10

💡 Project Significance

This project demonstrates the ability to:

Evaluate an application from a security perspective
Identify and prioritize real-world risks
Apply both offensive and defensive security concepts
Bridge the gap between development and security

👨‍💻 Author

Keabetswe Basetsana Mashigo
Aspiring Cybersecurity Specialist

📚 References
OWASP Top 10 (2021)
OWASP Web Security Testing Guide
