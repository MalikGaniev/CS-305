# CS 305 — Software Security Portfolio

## Artemis Financial — Practices for Secure Software

### Project Overview

Artemis Financial is a financial consulting company that develops individualized financial plans for customers, including savings, retirement, investments, and insurance. The company wanted to modernize its web application and improve the protection of sensitive customer information. My responsibility was to identify security vulnerabilities and implement security improvements, including encrypted communications and checksum verification.

### Reflection

**1. What did I do well when identifying vulnerabilities, and why is secure coding important?**

I successfully implemented security improvements using Java and Spring Boot. I configured HTTPS, generated a self-signed certificate, and implemented SHA-256 checksum functionality. Secure coding is important because it helps prevent unauthorized access, data breaches, and manipulation of sensitive information. Strong software security also protects a company's reputation and builds customer trust.

**2. Which part of the vulnerability assessment was challenging or helpful?**

The most challenging part was using OWASP Dependency-Check. The report identified 40 potential vulnerabilities across four dependencies. I also experienced problems updating the National Vulnerability Database because of API key and database issues. This experience taught me the importance of understanding security tools, troubleshooting errors, and reviewing vulnerability findings.

**3. How did I increase layers of security?**

I increased security by configuring HTTPS with TLS 1.2 and TLS 1.3, creating a self-signed certificate using Java Keytool, and implementing SHA-256 checksum verification. I also used security-related HTTP response headers and an environment variable for the keystore password. In future projects, I would use vulnerability scanning, automated testing, code reviews, and security advisories to select appropriate mitigation techniques.

**4. How did I make sure the application was functional and secure?**

I used Maven to compile and test the application. All four automated tests passed. I also verified that the application returned a SHA-256 checksum through the HTTPS endpoint on port 8443. I ran OWASP Dependency-Check to identify possible security vulnerabilities. The scan reported dependency vulnerabilities, and later scans were blocked by database update problems. Additional remediation and testing would be necessary before considering the application fully secure.

**5. What resources, tools, and coding practices did I use?**

I used Java, Spring Boot, Visual Studio Code, Maven, Java Keytool, and OWASP Dependency-Check. I learned how to configure secure communications, generate certificates, implement cryptographic hashing, and troubleshoot software security issues. These skills will be useful in future programming assignments and professional development projects.

**6. What would I show future employers?**

I would show future employers my Artemis Financial Practices for Secure Software Report and the security improvements I implemented. This project demonstrates my knowledge of secure Java development, HTTPS, cryptographic hashing, automated testing, vulnerability assessment, and technical documentation. It also shows my ability to troubleshoot problems and identify security risks requiring further attention.

### Portfolio Artifact

**CS305_Project_Two_Security_Report.docx**

This report documents the security enhancements, testing procedures, vulnerability assessment findings, and lessons learned from the Artemis Financial project.

### AI Usage Acknowledgment

I used OpenAI ChatGPT to help troubleshoot technical errors, explain security concepts, and organize and revise my written reflection. I reviewed the content against my project work and testing results.
