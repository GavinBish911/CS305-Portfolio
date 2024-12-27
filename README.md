# CS305-Portfolio

Project Title:

Practices for Secure Software Development

Overview
This project focuses on implementing and documenting secure software practices for Artemis Financial. The objective is to enhance the security of their applications by using cryptographic algorithms, secure communication protocols, and best practices for secure software development and testing.

Key Features

Secure Encryption Algorithm:
Utilized SHA-256 with 256-bit keys to encrypt sensitive data.
Ensured robust protection against brute-force attacks and collisions.
Certificate Generation:
Generated and implemented security certificates for client-server communication.
Deployment of Cipher:
Verified checksum integrity of encrypted files to ensure authenticity.
Secure Communication:
Integrated TLS for encrypted communication between the client and server.
Enforced HTTPS to prevent insecure sessions and mitigate man-in-the-middle attacks.
Code Quality and Security:
Refactored code to comply with secure coding standards.
Performed dependency checks to identify vulnerabilities.
Project Deliverables

Algorithm Cipher:
Implemented SHA-256 for data encryption in Java.
Recommended for securing long-term archived files with symmetrical encryption keys.
Certificate Implementation:
Deployed SSL/TLS certificates to ensure secure client-server interactions.
Secure Communications:
Ensured all communication occurred over encrypted HTTPS connections.
Testing and Verification:
Conducted functional testing to validate the refactored code.
Performed dependency-check scans to identify potential vulnerabilities.
Development Tools and Environment

Programming Language: Java
IDE: Eclipse
Security Libraries: Java Cryptography Architecture (JCA)
Testing Tools: Dependency-checker, functional testing frameworks
Best Practices for Secure Software

Dependency Management: Regularly check for vulnerabilities in third-party libraries and update dependencies accordingly.
Input Validation: Apply whitelisting techniques to validate user inputs, ensuring secure interactions.
Secure Coding Standards: Follow guidelines to avoid common vulnerabilities like SQL injection, XSS, and buffer overflows.
Layered Security: Combine encryption (SHA-256), TLS, and secure certificate management to provide multi-layered protection.
Regular Code Reviews: Identify and mitigate potential issues during development and maintenance.
