# CS305-SoftwareSecurity
- Client and Software Requirements:
Artemis Financial, a financial planning consultancy, wanted to upgrade their web app's security. They needed Global Rain to add a file verification step for secure data transfer. The tasks included recommending an encryption method, creating self-signed certificates, implementing secure communications, and conducting testing.

- Key Achievements in Addressing Security Vulnerabilities:
Selected the Advanced Encryption Standard (AES) for its security and wide use.
Made the application use HTTPS for secure communication and generated self-signed certificates using Java Keytool.
Implemented hash algorithms for data verification during data transfer.
Checked for additional vulnerabilities introduced during the process using OWASP Dependency-Check Maven.
Followed industry standards to code securely, ensuring data protection and company reputation.
Importance of Coding Securely:
Coding securely is vital to safeguard financial and client data, build trust, and prevent financial losses from breaches.

- Challenges and Insights from the Vulnerability Assessment:
Ensuring the refactored code met client needs and industry standards was a challenge. The vulnerability assessment helped find potential security gaps and offered a systematic approach to fixing them.

- Increasing Layers of Security:
Added security layers by implementing HTTPS, using cryptographic hash algorithms, and conducting static and functional testing. Chose AES encryption and self-signed certificates for robust security.

- Ensuring Code and Software Application Security:
After refactoring, ensured code functionality and security through manual code review, functional testing, and static testing using OWASP Dependency-Check Maven. Regular testing and fixing identified vulnerabilities were crucial for maintaining a secure application.

- Resources, Tools, and Practices Used:
Encryption: AES algorithm cipher
Certificate Generation: Java Keytool in Eclipse
Cryptographic Hash: Implemented hash algorithms
Secure Communication: Refactored code to use HTTPS
Testing: OWASP Dependency-Check Maven for static testing
Coding Practices: Followed industry-standard best practices for secure coding
Future Use and Presentation to Employers:
This project demonstrates a practical understanding of encryption, secure communication, and addressing security concerns in a methodical manner. The use of widely accepted tools and practices, such as OWASP Dependency-Check Maven and Java Keytool, showcases practical skills applicable in real-world scenarios. This work is a strong example to exhibit skills in secure software development to potential employers.
