
# Cybersecurity Fundamentals: Study Guide

Welcome to this beginner-friendly cybersecurity study guide. It introduces essential security concepts for IT students and people preparing for entry-level cybersecurity certifications.

For additional learning and practice resources, visit [Examsteacher.com](https://examsteacher.com/).

## 1. What Is Cybersecurity?

Cybersecurity is the practice of protecting computers, networks, applications, and data against unauthorized access, attacks, damage, and disruption.

Common cybersecurity goals include:

- Protecting sensitive information.
- Preventing unauthorized access.
- Detecting suspicious activity.
- Responding to security incidents.
- Maintaining business operations.

## 2. The CIA Triad

The CIA triad is a foundational information security model.

### Confidentiality

Confidentiality means ensuring that information is accessible only to authorized people or systems.

Examples:
- Encrypting sensitive files.
- Using access controls.
- Protecting accounts with multifactor authentication.

### Integrity

Integrity means maintaining the accuracy and completeness of information.

Examples:
- Using file hashes to detect changes.
- Restricting unauthorized modifications.
- Maintaining audit logs.

### Availability

Availability means ensuring that authorized users can access systems and information when needed.

Examples:
- Maintaining backups.
- Using redundant systems.
- Protecting services against denial-of-service attacks.

**Remember:** Confidentiality protects secrecy, integrity protects correctness, and availability protects access.

## 3. Common Cybersecurity Threats

### Phishing

Phishing uses deceptive messages or websites to trick people into revealing sensitive information or performing unsafe actions.

**Protection:** Verify senders, inspect links carefully, use multifactor authentication, and report suspicious messages.

### Malware

Malware is malicious software designed to damage systems, steal information, spy on users, or perform unauthorized actions.

Common types include:

- **Virus:** Malicious code that attaches to files or programs.
- **Worm:** Malware that can spread between systems.
- **Trojan:** Malicious software disguised as legitimate software.
- **Ransomware:** Malware that commonly encrypts files and demands payment.
- **Spyware:** Software that secretly monitors activity or collects information.

**Protection:** Keep software updated, use reputable security tools, and avoid untrusted downloads.

### Social Engineering

Social engineering manipulates people into revealing information or granting access.

Examples include impersonating technical support, creating false urgency, and pretending to be a trusted colleague.

**Protection:** Verify requests through a separate trusted channel and follow established security procedures.

### Denial-of-Service (DoS)

A denial-of-service attack attempts to make a system or service unavailable to legitimate users by overwhelming or disrupting it.

A distributed denial-of-service (DDoS) attack uses multiple systems to carry out the attack.

**Protection:** Use appropriate network protections, traffic monitoring, filtering, and mitigation services.

### Password Attacks

Attackers may try stolen passwords, guess weak credentials, or reuse passwords exposed in previous breaches.

**Protection:** Use unique passwords, a password manager, multifactor authentication, and rate limiting where appropriate.

## 4. Authentication and Authorization

These terms are related but different.

- **Authentication:** Verifies who a user or system is.
- **Authorization:** Determines what an authenticated user or system is allowed to do.

For example, logging into a company account is authentication. Being permitted to access a particular file is authorization.

### Multifactor Authentication (MFA)

MFA requires two or more different categories of authentication factors.

The main categories are:

- **Something you know:** A password or PIN.
- **Something you have:** A security key or authentication device.
- **Something you are:** A biometric characteristic, such as a fingerprint.

Where available, phishing-resistant authentication methods such as FIDO2 security keys or passkeys provide strong protection.

### Principle of Least Privilege

The principle of least privilege means granting users and systems only the permissions they need to perform their tasks.

This reduces the potential impact of compromised accounts and accidental misuse.

## 5. Security Controls

Security controls help prevent, detect, or respond to security risks.

### Preventive Controls

Designed to stop unwanted events before they happen.

Examples:
- Access controls.
- Multifactor authentication.
- Firewalls.
- Security awareness training.

### Detective Controls

Designed to identify suspicious activity or security incidents.

Examples:
- Monitoring and alerts.
- Audit logs.
- Intrusion detection systems.
- Security event analysis.

### Corrective and Recovery Controls

Designed to address incidents and restore normal operations.

Examples:
- Restoring clean backups.
- Removing malicious software.
- Applying security patches.
- Recovering affected systems.

Controls can also be administrative, technical, or physical, depending on how they are implemented.

## 6. Encryption and Hashing

### Encryption

Encryption transforms readable data into an unreadable form using a cryptographic process and a key.

It helps protect confidentiality. Decryption by an authorized party restores the readable data.

Examples include encrypted network connections and encrypted storage.

### Hashing

Hashing produces a fixed-length digest from input data using a hash function.

It is commonly used to check data integrity and store password verifiers securely when implemented with an appropriate password-hashing algorithm.

A cryptographic hash is not intended to be decrypted back into the original data.

**Exam tip:** Encryption protects confidentiality; hashing is commonly used for integrity verification.

## 7. Network Security Basics

### Firewall

A firewall controls network traffic according to configured rules.

### Virtual Private Network (VPN)

A VPN creates an encrypted tunnel between endpoints over a network. It can help protect traffic in transit, depending on its configuration.

### Intrusion Detection System (IDS)

An IDS monitors activity for signs of suspicious or malicious behavior and generates alerts.

### Intrusion Prevention System (IPS)

An IPS monitors activity and can automatically block or prevent certain detected threats.

### Secure Protocols

Examples include:

- **HTTPS:** HTTP protected by TLS.
- **SSH:** Secure remote administration and other encrypted communications.
- **SFTP:** File transfer over SSH.
- **TLS:** A cryptographic protocol used to protect communications.

## 8. Vulnerabilities, Threats, and Risks

These terms have different meanings.

- **Vulnerability:** A weakness in a system, process, or configuration.
- **Threat:** Something capable of exploiting a vulnerability or causing harm.
- **Risk:** The potential for loss or harm, considering the likelihood and impact of an event.

Security teams reduce risk by identifying vulnerabilities, prioritizing remediation, monitoring threats, and applying appropriate controls.

## 9. Incident Response

Incident response is the organized process of handling security incidents.

A common incident response lifecycle includes:

1. **Preparation:** Establish procedures, tools, roles, and training.
2. **Detection and analysis:** Identify suspicious activity and determine its scope.
3. **Containment:** Limit the incident's spread and impact.
4. **Eradication:** Remove the cause and malicious artifacts.
5. **Recovery:** Restore systems safely and monitor them for recurring issues.
6. **Lessons learned:** Document findings and improve security practices.

Follow your organization's incident response plan and applicable reporting requirements.

## 10. Cybersecurity Best Practices

- Keep operating systems and applications updated.
- Use unique passwords and a password manager.
- Enable multifactor authentication.
- Back up important data and test restoration.
- Limit access permissions.
- Encrypt sensitive information appropriately.
- Be cautious with unexpected attachments and links.
- Monitor accounts and systems for unusual activity.
- Use secure configurations.
- Report suspected incidents promptly.

## 11. Practice Questions

Try answering the questions before checking the answer key.

### Question 1

Which part of the CIA triad focuses on preventing unauthorized changes to information?

A. Confidentiality  
B. Integrity  
C. Availability  
D. Authentication

### Question 2

What is the primary purpose of multifactor authentication?

A. To remove the need for usernames  
B. To encrypt every file automatically  
C. To require multiple different authentication factors  
D. To prevent every possible cyberattack

### Question 3

Which threat commonly uses deceptive emails or messages to steal information?

A. Phishing  
B. Hashing  
C. Encryption  
D. Redundancy

### Question 4

What does the principle of least privilege mean?

A. Every employee receives administrator access  
B. Users receive only the permissions needed for their tasks  
C. Passwords are shared across a team  
D. All security controls should be disabled during maintenance

### Question 5

Which technology is commonly used to control network traffic according to security rules?

A. Firewall  
B. Spreadsheet  
C. Text editor  
D. Printer driver

### Question 6

What is the primary purpose of a cryptographic hash when verifying a file?

A. To restore deleted files automatically  
B. To decrypt the file  
C. To help detect changes to the file's contents  
D. To grant users access permissions

## 12. Answer Key and Explanations

1. **B — Integrity.** Integrity helps ensure that information remains accurate and is not modified without authorization.
2. **C — To require multiple different authentication factors.** MFA adds protection beyond relying on a single factor.
3. **A — Phishing.** Phishing uses deceptive communications to manipulate recipients.
4. **B — Users receive only the permissions needed for their tasks.** This limits unnecessary access and reduces potential damage.
5. **A — Firewall.** A firewall applies rules to control network traffic.
6. **C — To help detect changes to the file's contents.** Comparing trusted hash values can reveal whether file contents have changed.

## 13. Recommended Learning Resources

Use trusted resources to deepen your understanding.

- [NIST Cybersecurity](https://www.nist.gov/cybersecurity)
- [CISA Cybersecurity Resources](https://www.cisa.gov/)
- [OWASP Foundation](https://owasp.org/)
- [ISC2](https://www.isc2.org/)
- [CompTIA](https://www.comptia.org/)

For certification preparation, always check the official objectives for the certification and exam version you intend to take.

## 14. Continue Learning

Explore more IT certification study resources and practice materials at [Examsteacher.com](https://examsteacher.com/).

## Disclaimer

This guide is provided for educational purposes only. It is not an official certification exam guide and does not guarantee exam success.

This repository is independent and is not affiliated with or endorsed by CompTIA, ISC2, NIST, CISA, or any other organization mentioned here. Names and trademarks belong to their respective owners.
