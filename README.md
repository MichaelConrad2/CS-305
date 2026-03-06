# CS 305 Module Eight Journal

## Client Summary

The client, Artemis Financial, is a financial services company that provides customized financial planning services for its customers. Because the company handles sensitive financial information, it is critical that their software systems maintain strong security practices. The goal of the project was to identify potential security vulnerabilities in the existing application and implement improvements that protect data integrity and secure communication between the client and server.

## Software Security Importance

During the vulnerability assessment process, I analyzed the application to determine where security improvements were needed. Secure coding is important because it protects sensitive information from unauthorized access, tampering, and cyberattacks. In this project, implementing SHA-256 hashing and secure HTTPS communication helped ensure that data transmitted through the application remained encrypted and verifiable. Strong security practices add value to an organization by protecting customer trust, preventing data breaches, and supporting regulatory compliance.

## Challenges During the Vulnerability Assessment

One challenging aspect of the vulnerability assessment was understanding how cryptographic algorithms and secure communication protocols work together to protect data. However, learning how to integrate SHA-256 hashing and configure SSL certificates made the process very valuable because it provided practical experience with real-world security tools used in software development.

## Increasing Layers of Security

Several security layers were added to strengthen the application. The project implemented SHA-256 cryptographic hashing to verify the integrity of transmitted data. The application was also refactored to use HTTPS by configuring SSL/TLS with a PKCS12 keystore and a self-signed certificate generated through Java Keytool. These additional layers help prevent man-in-the-middle attacks and protect sensitive financial information during transmission.

## Ensuring Functional and Secure Code

After refactoring the application, testing was performed to ensure the program still ran correctly while maintaining improved security. The application was executed to confirm there were no functional errors, and dependency-check tools were used to scan for potential vulnerabilities in external libraries. This testing ensured that security improvements did not introduce new issues.

## Helpful Resources and Tools

Several tools and resources were useful during this project. The Java Keytool utility helped generate the SSL certificate and configure the keystore needed for HTTPS communication. Dependency-check tools helped identify potential vulnerabilities in project dependencies. Secure coding documentation and cryptography best practices also helped guide the development process.

## Value for Employers

This assignment demonstrates my ability to identify software vulnerabilities, implement cryptographic security solutions, and apply industry standard best practices such as HTTPS and SHA-256 hashing. It also shows my ability to refactor code while maintaining functionality and improving security. These skills are valuable to employers because they demonstrate an understanding of secure software development and the importance of protecting sensitive data in modern applications.
