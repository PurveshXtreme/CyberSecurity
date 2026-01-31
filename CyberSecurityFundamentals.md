# Introduction to Information Security

## What is Information Security?

**Information Security (InfoSec)** is the practice of protecting information from:

- Unauthorized access  
- Unauthorized use  
- Unauthorized disclosure  
- Disruption  
- Modification  
- Destruction  

It ensures that information remains **safe, accurate, and available** only to authorized users.

---

## Core Objectives – CIA Triad

Information Security is based on three fundamental principles called the **CIA Triad**:

### 1. Confidentiality
- Ensures that information is accessible only to authorized users
- Prevents unauthorized data exposure

**Examples:**
- Password protection
- Encryption
- Access control

### 2. Integrity
- Ensures that information is accurate, complete, and unaltered
- Prevents unauthorized modification of data

**Examples:**
- Hashing
- Digital signatures
- Version control

### 3. Availability
- Ensures that information is accessible when needed
- Prevents system downtime and service disruption

**Examples:**
- Backups
- Redundant systems
- DDoS protection

---

## Example

Protecting login credentials so that:
- Only the rightful user can access them (**Confidentiality**)
- Credentials are not tampered with (**Integrity**)
- The login system is available 24/7 (**Availability**)

---

## Why is Information Security Important?

Information Security is critical because modern organizations rely heavily on data and digital systems.

### Key Reasons

### 1. Safeguards Sensitive Data
Protects:
- Personal data
- Financial records
- Health information

Prevents data leaks and misuse.

### 2. Prevents Identity Theft and Fraud
- Stops attackers from stealing credentials and personal details
- Protects users from financial and reputational loss

### 3. Protects Business Assets and Reputation
- Prevents loss of intellectual property
- Maintains customer trust
- Avoids financial penalties due to breaches

### 4. Ensures Legal and Regulatory Compliance
- Helps organizations comply with security laws and regulations

**Examples:**
- GDPR – General Data Protection Regulation
- HIPAA – Health Insurance Portability and Accountability Act

### 5. Ensures Business Continuity
- Prevents service downtime
- Protects systems from cyber attacks and disasters

---

## Example

A healthcare organization encrypting patient records:
- Protects patient privacy
- Prevents unauthorized access
- Complies with HIPAA regulations

---

## Information Security vs Cyber Security

| Aspect | Information Security | Cyber Security |
|------|----------------------|---------------|
| Scope | Protects all forms of information (digital & physical) | Protects digital systems and networks |
| Data Type | Digital + physical data (files, papers) | Digital data only |
| Focus | Policies, processes, and protection of information | Protection against cyber attacks |
| Examples | Data encryption, access control, physical security | Firewalls, malware protection, IDS/IPS |

---

## Key Difference

- **Information Security** is a broader concept
- **Cyber Security** is a subset of Information Security

---
---

---

## Practice MCQs

<details>
<summary>📘 Show MCQs</summary>

### Q1. What is the primary goal of Information Security?

- To increase system performance  
- To protect information from unauthorized access and misuse  
- To develop software applications  
- To monitor network traffic  

<details>
<summary>See answer</summary>

**Correct answer:** To protect information from unauthorized access and misuse

</details>

---

### Q2. Which of the following is NOT a part of Information Security?

- Confidentiality  
- Integrity  
- Availability  
- Scalability  

<details>
<summary>See answer</summary>

**Correct answer:** Scalability

</details>

---

### Q3. What does Confidentiality in the CIA Triad ensure?

- Data is always available  
- Data is accurate and unaltered  
- Data is accessible only to authorized users  
- Data is backed up regularly  

<details>
<summary>See answer</summary>

**Correct answer:** Data is accessible only to authorized users

</details>

---

### Q4. Which technique is commonly used to ensure data integrity?

- Encryption  
- Hashing  
- Firewalls  
- Load balancing  

<details>
<summary>See answer</summary>

**Correct answer:** Hashing

</details>

---

### Q5. Availability in Information Security mainly focuses on:

- Preventing unauthorized access  
- Ensuring data accuracy  
- Ensuring systems are accessible when needed  
- Encrypting sensitive information  

<details>
<summary>See answer</summary>

**Correct answer:** Ensuring systems are accessible when needed

</details>

---

### Q6. Which of the following is an example of ensuring availability?

- Password protection  
- Digital signatures  
- Regular data backups  
- User authentication  

<details>
<summary>See answer</summary>

**Correct answer:** Regular data backups

</details>

---

### Q7. Why is Information Security important for organizations?

- To reduce hardware costs  
- To improve UI design  
- To protect sensitive data and business reputation  
- To increase internet speed  

<details>
<summary>See answer</summary>

**Correct answer:** To protect sensitive data and business reputation

</details>

---

### Q8. Which regulation focuses on protecting personal data in the European Union?

- HIPAA  
- PCI-DSS  
- GDPR  
- ISO 27001  

<details>
<summary>See answer</summary>

**Correct answer:** GDPR

</details>

---

### Q9. Which statement best describes Cyber Security?

- Protection of physical documents  
- Protection of digital systems and networks  
- Protection of company policies  
- Protection of employees  

<details>
<summary>See answer</summary>

**Correct answer:** Protection of digital systems and networks

</details>

---

### Q10. What is the relationship between Information Security and Cyber Security?

- They are completely unrelated  
- Cyber Security is broader than Information Security  
- Information Security is a subset of Cyber Security  
- Cyber Security is a subset of Information Security  

<details>
<summary>See answer</summary>

**Correct answer:** Cyber Security is a subset of Information Security

</details>

</details>

---
---

# Hacking and Cyber Threats

## What is Hacking?

**Hacking** means doing something in an unconventional way or using a shortcut to achieve a goal.

### In cybersecurity context:
- Gaining unauthorized access to systems, networks, or data
- Exploiting weaknesses in software, hardware, or human behavior

### Literal Meaning:
- Cutting or breaking something using sheer force
- In computing, it refers to breaking security controls

---

## Who is a Hacker?

A **hacker** is a person who uses technical skills to:
- Access systems
- Test security
- Exploit vulnerabilities (legally or illegally)

---

## Types of Hackers

| Type | Description |
|----|------------|
| Black Hat Hackers | Malicious hackers who break into systems illegally to steal data, spread malware, or cause damage |
| White Hat Hackers | Ethical hackers authorized to test security and help organizations fix vulnerabilities |
| Gray Hat Hackers | Act between black hat and white hat; may hack without permission but not for malicious intent |
| Script Kiddies | Beginners who use ready-made tools or scripts with limited technical knowledge |
| Suicidal Hackers | Hack without caring about consequences; focus on destruction or attention |
| State-Sponsored Hackers | Hackers employed by governments for cyber espionage or cyber warfare |
| Cyberterrorists | Use hacking to create fear or disruption, targeting critical infrastructure |
| Hacktivists | Hack for political or social causes such as protests or ideology |
| Insider Threats | Employees or trusted insiders who abuse legitimate access |
| Advanced Persistent Threat (APT) | Highly skilled attackers who target specific organizations and remain hidden for long periods |

---

## Common Cyber Threats

| Threat | Description |
|------|-------------|
| Malware | Malicious software including viruses, worms, ransomware, and trojans |
| Phishing | Fake emails or messages used to steal passwords and credit card details |
| Physical Theft | Devices such as laptops, USB drives, or phones being stolen or lost |
| Social Engineering | Manipulating people into revealing confidential information |
| Denial-of-Service (DoS) | Overloading systems or networks to make services unavailable |
| Man-in-the-Middle (MitM) | Intercepting and altering communication between two parties |
| SQL Injection | Exploiting database vulnerabilities to read, modify, or delete data |
| Zero-Day Vulnerabilities | Exploiting unknown software flaws with no available patch |
| Data Breaches | Unauthorized access to sensitive personal or corporate data |
| IoT Vulnerabilities | Exploiting weak security in smart devices like cameras and routers |
| Unpatched Software | Exploiting known vulnerabilities in outdated software |
| Rogue Access Points | Unauthorized Wi-Fi access points allowing network intrusion |

---

## Basic Security Terminologies & Important Cybersecurity Terms

| Term | Meaning |
|----|--------|
| Vulnerability | A weakness in a system that can be exploited |
| Exploit | A technique used to take advantage of a vulnerability |
| Attack | An attempt to damage, disrupt, or gain unauthorized access |
| Payload | The malicious code delivered during an attack |
| Asset | Anything valuable to an organization such as data, systems, or people |
| Asset Value | Importance or worth of an asset |
| Hack Value | Benefit gained by an attacker from hacking |
| Threat | A potential cause of harm to a system |
| Risk | Probability of a threat exploiting a vulnerability |
| Bot | An automated program performing tasks |
| Botnet | A network of compromised devices controlled by an attacker |
| Trojan | Malware disguised as legitimate software |
| Daisy Chaining | Using access to one system to attack additional systems |
| Personally Identifiable Information (PII) | Data that identifies a person such as name, Aadhaar, PAN, email, or phone number |
| Doxing | Publicly revealing private or personal information of individuals |

---

## Impacts of Hacking

### 1. Reputational Impact
- Loss of trust
- Damage to brand image

### 2. Operational Impact
- System downtime
- Business disruption

### 3. Financial Impact
- Cost of repairs
- Loss of revenue
- Ransom payments

### 4. Legal Impact
- Lawsuits
- Regulatory penalties
- Compliance violations

---
---
