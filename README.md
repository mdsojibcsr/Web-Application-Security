# Web Application Security
### A Complete Web Application Security Syllabus.
# Table of Contents #
  ### [Module 01 - Introduction to Web Application Security](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#introduction-to-web-application-security)
  * [Security threats and vulnerabilities](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#security-threats-and-vulnerabilities)
  * [Attack vectors and motivations](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#attack-vectors-and-motivations)
  * [CIA triad (Confidentiality, Integrity, Availability)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#cia-triad-confidentiality-integrity-availability)
  * [Secure Development Lifecycle (SDLC)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#secure-development-lifecycle-sdlc)
  ### [Module 02 - Web Application Reconnaissance](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#web-application-reconnaissance)
  * [Information gathering techniques](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#information-gathering-techniques)
  * [Finding subdomains](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#finding-subdomains)
  * [Web application fingerprinting](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#web-application-fingerprinting)
  * [Identifying technologies and frameworks](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#identifying-technologies-and-frameworks)
  * [API analysis](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#api-analysis)
  ### [Module 03 - Client-Side Attacks](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#client-side-attacks)
  * [Cross-Site Scripting (XSS) - Reflected, Stored, DOM-based](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#cross-site-scripting-xss---reflected-stored-dom-based)
  * [Cross-Site Request Forgery (CSRF)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#cross-site-request-forgery-csrf)
  * [Clickjacking](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#clickjacking)
  * [Client-side validation bypasses](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#client-side-validation-bypasses)
  * [Web Cache Poisoning](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#web-cache-poisoning)
  ### [Module 04 - Server-Side Attacks](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#server-side-attacks)
  * [All Injection Attacks (SQLi, XSS, LDAP, etc.)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#all-injection-attacks-sqli-xss-ldap-etc)
  * [File Upload Vulnerabilities (including path traversal and Prototype Pollution)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#file-upload-vulnerabilities-including-path-traversal-and-prototype-pollution)
  * [Server-Side Request Forgery (SSRF)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#server-side-request-forgery-ssrf)
  * [Business Logic Flaws](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#business-logic-flaws)
  * [Remote Code Execution (RCE)](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#remote-code-execution-rce)
  * [Exploiting Third-Party Dependencies](https://github.com/mdsojibcsr/Web-Application-Security/blob/main/README.md#exploiting-third-party-dependencies)
  ### Module 05 - Authentication and Authorization
  * Secure authentication mechanisms (password hashing, multi authentication)
  * Session management vulnerabilities
  * Broken Access Control (BAC)
  * Authorization models and best practices
  ### Module 06 - Security Protocols and Standards
  * Secure Sockets Layer (SSL) / Transport Layer Security (TLS)
  * WebSockets security considerations
  * JSON Web Tokens (JWT) and security implications
  * Cross-Origin Resource Sharing (CORS)
  ### Module 07 - Cloud Security
  * Cloud security architecture principles
  * Shared responsibility model
  * Securing web applications in the cloud environment
  ### Module 08 - Security Testing and Tools
  * Manual and automated testing methodologies (penetration testing)
  * Static and dynamic application security testing (SAST & DAST)
  * Web vulnerability scanners and exploit frameworks
  ### Module 09 - Advanced Topics
  * Web LLM (Large Language Model) attacks (emerging threats)
  * Race Conditions and security implications
  * Security Assertion Markup Language (SAML)
  * Reverse Engineering techniques for vulnerability research
  * Fingerprint Web Server
  ### Module 10 - Secure Coding Practices
  * Secure coding principles (input validation, output encoding)
  * Common coding weaknesses and prevention strategies
  * Secure coding standards and frameworks
  ### Module 11 - Security Incident Response
  * Incident response planning and procedures
  * Vulnerability disclosure and remediation
  * Security monitoring and logging practices
  ### Module 12 - Legal and Ethical Considerations
  * Laws and regulations regarding web application security (e.g., GDPR, CCPA)
  * Ethical hacking and responsible disclosure practices
# Introduction to Web Application Security
Web application security is a branch of information security that specifically deals with the security of websites, web applications and web services. It is designed to ensure that these applications are protected from unauthorized access, modification or destruction. Web application security is important because it can protect web applications from various types of threats.It is a broad discipline, but its ultimate goals are to keep web applications running smoothly and protect businesses from cyber vandalism, data theft, unethical competition and other negative consequences. The global nature of the Internet exposes web applications and APIs to attacks from many locations and with varying levels of scale and complexity. As such, web application security encompasses a variety of techniques and covers many parts of the software supply chain.

Why is web application security important?

Web applications are essential components of modern business. They are used for everything from online sales and customer support to data collection and storage. As a result, they are prime targets for attackers. According to a report by Verizon (https://www.verizon.com/business/resources/reports/dbir/), web application attacks are one of the most common types of cyber attacks. In fact, they account for more than 40% of all data breaches.These attacks can have a devastating impact on businesses. They can lead to data loss, financial loss, reputational damage and even legal issues. Let's see an example! In 2017, a data leak at Equifax exposed the personal information of 147 million Americans. The leak was caused by an SQL injection vulnerability that allowed attackers to gain access to the company's database.The leak caused a huge financial loss for Equifax, and forced the company's CEO to resign.
That's why web application security is an important issue.

## Security threats and vulnerabilities
Web applications have become indispensable in our daily life. But, like anything, web applications face or are facing security threats. These threats can take advantage of application vulnerabilities to harm our data, privacy and even money.

A security threat is anything that compromises the security of a web application. They can be operated either by a person (hacker) or a program (malware).Common security threats are:
SQL Injection, Cross-Site Scripting (XSS), Malware, Denial-of-Service (DoS) attacks etc.

And a vulnerability is any weakness in a web application that opens the door to security threats. This can be due to coding mistakes, misconfigurations or software design flaws. Among the common weaknesses are: Un-updated software: If the web application and its dependent software are not updated, they may contain known vulnerabilities.
Weak Password Policy: If users are allowed to choose weak passwords, it will be very easy for attackers to guess or crack them.
Improper input validation: Web applications should validate user input to prevent malicious code from being injected.
Misconfigured security settings: Incorrect security settings can leave the application vulnerable to attack
Insecure File Permissions: Files containing sensitive information should be restricted to authorized users.Hackers can take advantage of these vulnerabilities to attack and take our important data. As it happened, Equifax (the case on the page above) failed to keep their applications and software updated. Even though it has a patch available against a known SQL injection vulnerability, Equifax has not installed it on their systems. Equifax did not use adequate security measures to secure their systems. This leak could have been prevented if a web application firewall (WAF) was installed. That is why it is important for us to be aware of this.

## Attack vectors and motivations
In the world of web application security, understanding attack vectors and motivations is critical to building strong defenses.
Attack vector:
An attack vector is the method an attacker uses to exploit a vulnerability in a web application. It is the path they take to gain unauthorized access to a system, steal data, disrupt operations, or achieve other nefarious goals. Here are some common attack vectors: SQL Injection, Cross-Site Scripting (XSS), Malware, Phishing Attacks, Denial-of-Service (DOS) Attacks, Insecure Direct Object Reference (IDOR), File Upload Vulnerabilities,

Motivations:
Understanding why someone would attack a web application helps security measures. Common motivations include: Financial gain:
Stealing financial information (credit card details, bank account numbers) or using stolen data for identity theft are common targets. Attackers can also launch ransomware attacks, demanding payment to regain access to data.
Disturbance:
Hacktivists or competitors may aim to cause chaos and bring down websites or applications. Espionage:
The theft of sensitive information such as trade secrets or intellectual property is a major concern for businesses.
Distortion:
Discrediting a website by changing its content can be a way for attackers to gain notoriety or promote a cause.State-sponsored attacks:
Governments may sponsor attacks to steal information, disrupt critical infrastructure, or gain an advantage in cyber warfare. By understanding attack vectors and motivations, you can proactively protect your web applications and the data they store.
## CIA triad (Confidentiality, Integrity, Availability)
No content
## Secure Development Lifecycle (SDLC)
No Content

# Web Application Reconnaissance
Upcoming
## Information gathering techniques
upcoming
## Finding subdomains
upcoming
## Web application fingerprinting
upcoming
## Identifying technologies and frameworks
upcoming
## API analysis
upcoming

# Client-Side Attacks
upcoming
## Cross-Site Scripting (XSS) - Reflected, Stored, DOM-based
upcoming
## Cross-Site Request Forgery (CSRF)
upcoming
## Clickjacking
upcoming
## Client-side validation bypasses
upcoming
## Web Cache Poisoning
upcoming

# Server-Side Attacks
upcoming
## All Injection Attacks (SQLi, XSS, LDAP, etc.)
upcoming
## File Upload Vulnerabilities (including path traversal and Prototype Pollution)
upcoming
## Server-Side Request Forgery (SSRF)
upcoming
## Business Logic Flaws
upcoming
## Remote Code Execution (RCE)
upcoming
## Exploiting Third-Party Dependencies
upcoming

# Authentication and Authorization
upcoming
## Secure authentication mechanisms (password hashing, multi authentication)
upcoming
## Session management vulnerabilities
upcoming
## Broken Access Control (BAC)
upcoming
## Authorization models and best practices
upcoming

# Security Protocols and Standards
upcoming
## Secure Sockets Layer (SSL) / Transport Layer Security (TLS)
upcoming
## WebSockets security considerations
upcoming
## JSON Web Tokens (JWT) and security implications
upcoming
## Cross-Origin Resource Sharing (CORS)
upcoming

# Cloud Security
upcoming
## Cloud security architecture principles
upcoming
## Shared responsibility model
upcoming
## Securing web applications in the cloud environment
upcoming

# Security Testing and Tools
upcoming
## Manual and automated testing methodologies (penetration testing)
upcoming
## Static and dynamic application security testing (SAST & DAST)
upcoming
## Web vulnerability scanners and exploit frameworks
upcoming

# Advanced Topics
upcoming
## Web LLM (Large Language Model) attacks (emerging threats)
upcoming
## Race Conditions and security implications
upcoming
## Security Assertion Markup Language (SAML)
upcoming
## Reverse Engineering techniques for vulnerability research
upcoming
## Fingerprint Web Server
upcoming

# Secure Coding Practices
upcoming
## Secure coding principles (input validation, output encoding)
upcoming
## Common coding weaknesses and prevention strategies
upcoming
## Secure coding standards and frameworks
upcoming

# Security Incident Response
upcoming
## Incident response planning and procedures
upcoming
## Vulnerability disclosure and remediation
upcoming
## Security monitoring and logging practices
upcoming

# Legal and Ethical Considerations
upcoming
## Laws and regulations regarding web application security (e.g., GDPR, CCPA)
upcoming
## Ethical hacking and responsible disclosure practices
upcoming
