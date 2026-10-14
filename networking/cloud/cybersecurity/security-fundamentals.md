
# Cybersecurity Fundamentals Study Guide

Welcome to this free cybersecurity study guide! This resource introduces essential security concepts for IT students, aspiring security analysts, and people preparing for cybersecurity certifications.

Learn the fundamentals, review practical examples, and test your understanding with original practice questions.

## Table of Contents

- [What Is Cybersecurity?](#what-is-cybersecurity)
- [The CIA Triad](#the-cia-triad)
- [Common Security Threats](#common-security-threats)
- [Security Controls](#security-controls)
- [Identity and Access Management](#identity-and-access-management)
- [Incident Response](#incident-response)
- [Practice Questions](#practice-questions)
- [Answers and Explanations](#answers-and-explanations)
- [Learning Resources](#learning-resources)

## What Is Cybersecurity?

Cybersecurity is the practice of protecting systems, networks, applications, and data against unauthorized access, disruption, damage, and theft.

Its goals include:
- Protecting sensitive information.
- Maintaining system availability.
- Preventing unauthorized changes.
- Detecting suspicious activity.
- Responding effectively to security incidents.

Cybersecurity combines technology, processes, and people. Technical controls alone cannot eliminate every risk.

## The CIA Triad

The CIA triad is a foundational information security model.

### 1. Confidentiality

Confidentiality means ensuring that information is accessible only to authorized people and systems.

Examples:
- Encrypting sensitive files.
- Restricting access using permissions.
- Protecting account credentials.

### 2. Integrity

Integrity means protecting information against unauthorized or improper modification.

Examples:
- Using cryptographic hashes to detect changes.
- Applying access controls to important records.
- Keeping appropriate audit logs.

### 3. Availability

Availability means ensuring that authorized users can access systems and information when needed.

Examples:
- Maintaining backups.
- Reducing single points of failure.
- Using redundancy and recovery procedures.
- Protecting services against denial-of-service attacks.

**Memory tip:** Confidentiality protects secrecy, integrity protects correctness, and availability protects access.

## Common Security Threats

### Phishing

Phishing uses deceptive messages or websites to trick people into revealing information, opening malicious files, or taking unsafe actions.

Defenses include:
- Verifying unexpected requests.
- Checking links and sender identities.
- Using multifactor authentication.
- Reporting suspicious messages.

### Malware

Malware is software designed to perform harmful or unauthorized actions.

Common categories include:
- Ransomware
- Spyware
- Trojans
- Worms
- Viruses

Defenses include patching systems, limiting privileges, using appropriate endpoint protection, and maintaining tested backups.

### Password Attacks

Attackers may try stolen credentials, password guessing, or automated attempts to access accounts.

Defenses include:
- Unique passwords for each service.
- Password managers.
- Multifactor authentication.
- Rate limiting and account protection.
- Monitoring suspicious sign-in activity.

### Social Engineering

Social engineering manipulates people into disclosing information or performing actions that weaken security.

A request may appear to come from a manager, coworker, vendor, or technical support agent.

Verify unusual requests through a trusted communication channel, especially when they involve payments, credentials, or sensitive data.

### Denial of Service

A denial-of-service attack attempts to make a system or service unavailable.

Possible defenses include traffic filtering, rate limiting, redundancy, monitoring, and suitable denial-of-service protection services.

## Security Controls

Security controls help prevent, detect, or reduce the impact of threats.

### Preventive Controls

Designed to reduce the likelihood of an incident.

Examples:
- Access restrictions.
- Security awareness training.
- System hardening.
- Network segmentation.

### Detective Controls

Designed to identify suspicious activity or security incidents.

Examples:
- Security logs.
- Intrusion detection systems.
- Endpoint monitoring.
- Security alerts.

### Corrective and Recovery Controls

Help restore secure operation after a problem.

Examples:
- Restoring verified backups.
- Removing malicious software.
- Applying security patches.
- Rebuilding compromised systems.

Controls can also be categorized as administrative, technical, and physical.

## Identity and Access Management

Identity and Access Management (IAM) ensures that users and services receive appropriate access to resources.

### Least Privilege

Give each identity only the permissions necessary to perform its assigned tasks.

### Multifactor Authentication

Multifactor authentication (MFA) requires two or more authentication factors from distinct categories, such as:
- Something you know.
- Something you have.
- Something you are.

A password and a PIN are both knowledge factors, so they do not constitute two different factor categories by themselves.

### Role-Based Access Control

Role-based access control assigns permissions through roles associated with job responsibilities or functions.

### Authentication vs. Authorization

- **Authentication:** Verifies an identity.
- **Authorization:** Determines what an authenticated identity is permitted to do.

For example, signing in verifies your identity; permission checks determine whether you can access a particular file.

## Incident Response

Incident response is the structured process of handling security incidents.

A common high-level lifecycle includes:

1. **Preparation:** Establish policies, tools, roles, and response plans.
2. **Detection and analysis:** Identify suspicious activity and assess its scope.
3. **Containment:** Limit the incident's impact.
4. **Eradication:** Remove the cause and malicious artifacts.
5. **Recovery:** Restore systems safely and monitor their operation.
6. **Lessons learned:** Review the incident and improve defenses.

Actual response procedures depend on the incident and the organization's established framework.

## Practice Questions

These are original educational questions, not actual certification exam questions.

### Question 1

Which part of the CIA triad focuses on preventing unauthorized changes to information?

A. Confidentiality  
B. Integrity  
C. Availability  
D. Authentication  

### Question 2

An employee receives a deceptive email asking them to enter their company password on a fake login page. What type of threat is this?

A. Phishing  
B. Redundancy  
C. Encryption  
D. Network segmentation  

### Question 3

What is the primary purpose of multifactor authentication?

A. To eliminate every cybersecurity threat  
B. To add another authentication factor from a distinct category  
C. To replace every access control  
D. To guarantee that a device contains no malware  

### Question 4

Which principle recommends giving users only the permissions they need?

A. High availability  
B. Least privilege  
C. Open access  
D. Non-repudiation  

### Question 5

What is the difference between authentication and authorization?

A. Authentication verifies identity; authorization determines permitted actions.
B. Authentication encrypts data; authorization creates backups.
C. They always mean exactly the same thing.
D. Authorization verifies identity; authentication defines file permissions.

### Question 6

Which incident-response activity aims to limit the spread or impact of an active incident?

A. Preparation  
B. Containment  
C. Lessons learned  
D. Asset procurement  

## Answers and Explanations

**Question 1: B — Integrity**

Integrity protects information against unauthorized or improper modification.

**Question 2: A — Phishing**

Phishing uses deceptive communications to trick recipients into unsafe actions or disclosure of sensitive information.

**Question 3: B — To add another authentication factor from a distinct category**

MFA makes account compromise more difficult by requiring multiple types of evidence to verify identity.

**Question 4: B — Least privilege**

Least privilege limits unnecessary permissions and reduces the potential impact of compromised accounts.

**Question 5: A — Authentication verifies identity; authorization determines permitted actions.**

These processes work together but serve different purposes.

**Question 6: B — Containment**

Containment limits an incident's impact while the response team investigates and works toward eradication and recovery.

## Learning Resources

Use established resources to expand your cybersecurity knowledge:

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [NIST Computer Security Resource Center](https://csrc.nist.gov/)
- [CISA Cybersecurity Resources](https://www.cisa.gov/topics/cybersecurity-best-practices)
- [OWASP](https://owasp.org/)
- [ISC2](https://www.isc2.org/)

For certification preparation, consult the current official exam objectives for the certification you are pursuing.

## More Certification Practice

Looking for additional IT certification preparation resources and practice questions?

Visit [ExamsTeacher.com](https://examsteacher.com/) to explore available study materials and practice resources.

Choose material that matches your target certification and supports learning through clear explanations.

## Disclaimer

This is an independent educational resource. It is not affiliated with or endorsed by NIST, CISA, ISC2, CompTIA, or any other certification provider.

All practice questions in this guide are original educational exercises, not actual or leaked certification exam questions.

## Contributing

Suggestions, corrections, and original contributions are welcome. Please ensure all submissions are accurate, responsibly sourced, and appropriate for an educational audience.
