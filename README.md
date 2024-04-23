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
The CIA triad is a basic security model used to manage information security practices.

Confidentiality:
This policy ensures that only authorized users can access sensitive information on websites and applications. It focuses on preventing unauthorized access, disclosure or viewing of data by the web and application owner. Examples of privacy measures include access control, data encryption, and user authentication.

Integrity: This policy ensures that information is accurate, complete and reliable. It focuses on protecting data from unauthorized alteration, destruction or manipulation. Examples of integrity measures include data verification, checksums, and digital signatures.

Availability:
This policy ensures that authorized users can access information and resources on websites and applications whenever needed. It focuses on keeping systems and data updated and running and preventing outages or interruptions. Examples of availability measures include system backup, redundancy, and disaster recovery planning.

Why is the CIA Triad important?

The CIA Triad provides a simple framework for organizations to assess their security posture and identify potential vulnerabilities. By focusing on the three principles, organizations can develop a more comprehensive security strategy.

And that is why adopting these three principles is very important in web application security.

## Secure Development Lifecycle (SDLC)
The Secure Development Lifecycle (SDLC) is a framework that integrates security practices throughout the entire software development process. It's not just about finally fixing bugs; It's about proactively building security into the application from the start. Here's a breakdown of the SDLC stages and how security is incorporated:

Planning and Requirements:
Security requirements are identified alongside functional requirements. Threat modeling is performed to identify potential vulnerabilities and attacks.

Design and Prototyping:
Secure coding practices are emphasized from the start. The security architecture is designed to mitigate identified threats.

Development:
Developers use secure coding techniques to avoid common vulnerabilities. Static code analysis tools are used to detect potential security flaws early.

Examination:
Security testing is integrated throughout the development process. This includes manual penetration testing and automated security scanning.

Installation and Maintenance:
Safe deployment practices are followed to minimize vulnerabilities. Regular security updates and patches are applied to keep the software up to date.

Secure SDLC is an essential practice for building secure and reliable software applications. By integrating security throughout the development lifecycle, organizations can significantly reduce the risk of vulnerabilities and protect their data and systems.
# Web Application Reconnaissance
Web Application Reconnaissance, often abbreviated as Recon, is the basic phase in which information about a web application is gathered. This intel is crucial for ethical hackers (pen testers) and bug bounty hunters to identify potential security vulnerabilities before malicious actors exploit them. Similarly, security engineers use Recon techniques to proactively find and patch vulnerabilities in their own applications.

Think of it like scouting a building before attempting a security assessment. Recon helps us understand our application's layout, defenses, and potential weak points. By gathering this information, we can develop more targeted and efficient methods for finding and exploiting vulnerabilities.

Here's a breakdown of why Recon is important:
Solid foundation:
A thorough understanding of application functionality and underlying infrastructure allows for more informed and effective attack strategies.

Vulnerability detection: Recon helps identify areas of weak security practices, such as outdated libraries or poorly configured services.

Prioritization: By understanding the critical components of the application, testers can prioritize their efforts in areas with the highest potential impact. There are two main methods of recon:
Passive reconnaissance: This involves gathering information without interacting with the application. Strategies include:
Collecting public information: (https://www.searchenginejournal.com/alternative-search-engines/271409/) and seeking information about the Application, its developer and the technology used to create it through social media.
Domain Name System (DNS) Lookups: You can use tools like (https://research.domaintools.com/) to uncover details about domain name registrations.
Active Reconnaissance: This involves directly interacting with the application to search for vulnerabilities. Strategies include:Application Mapping: Identifying all the different functionalities and features offered by the application.
Test for Common Vulnerabilities: Uses automated tools to scan for known vulnerabilities such as SQL injection or cross-site scripting (XSS).

We have tried to cover several topics in Web Application Recon module. They are - Information gathering techniques, Finding subdomains, Web application fingerprinting, Identifying technologies and frameworks and API analysis.

Remember, recon is a powerful tool, but it should be used responsibly and ethically. There are legal and ethical considerations when recon in web applications Always get permission from the owner before actively searching for vulnerabilities.

## Information gathering techniques
Gathering information for web application security is the first step in which a hacker attempts to obtain information about a target. Hackers use various sources and tools to get more information and some of them are briefly explained here. You will need this information for web application security.

What is Information Gathering?
Information Gathering is the act of gathering various types of information against a target victim or system. It is the first step or initial phase of ethical hacking or web application security, where penetration testers or hackers or pen-testers (both black hat and white hat) perform this phase; Performing this is a necessary and important step. The more information gathered about the target, the more likely it is to get relevant results. Data collection is not only a phase of security testing; This is an art that every penetration-tester (pen-tester) and hacker should master for a better penetration testing experience. There are various tools, techniques and websites that help hackers gather information, including public sources like Whois, nslookup. This step is necessary because you may need any information when attacking any target (like his pet's name, best friend's name, age or phone number password guessing attack or other types of attacks) etc.
We have tried to categorize Information Gathering into three main categories.
1. [Footprinting](https://www.w3schools.in/ethical-hacking/footprinting/)
2. [Scanning](https://www.w3schools.in/ethical-hacking/scanning-techniques/)
3. [Enumeration](https://www.eccouncil.org/cybersecurity-exchange/ethical-hacking/enumeration-ethical-hacking/)
Click on the articles for details on these three main topics.

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
