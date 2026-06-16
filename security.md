# Security

## Fundamental Security Concepts

### Privacy

Privacy is the ability to control who can access your personal information.

#### Social Media
- Understand who owns and stores your data.
- Adjust privacy settings appropriately.
- Be mindful of what you share online.
- Review your friends/followers list regularly.
- Restrict profile access where possible.
- Read and understand privacy policies.
- Review your account activity.

#### Instant Messaging
- Use applications that support **end-to-end encryption** to protect messages.

#### Email
- Email is not always encrypted by default.
- Encryption settings can often be enabled for greater privacy.

#### File Sharing
- Use **File Transfer Protocol (FTP)** or the more secure **Secure File Transfer Protocol (SFTP)**.
- FTP commonly uses ports **20** and **21**.

---

## Personally Identifiable Information (PII)

PII is any information that can identify a specific person.

### Examples
- Name
- Address
- Email address
- Phone number
- Bank details
- Passport number
- IP address
- Login credentials

### Indirect PII

Indirect PII is information that may help identify a person when combined with other information.

### Examples
- Last name
- Race
- Gender
- Postcode
- Job title

---

## Cookie Consent

Cookies are small text files stored on a user's device when visiting a website.

- Websites often request consent before storing cookies.
- Cookies can remember preferences, login details, and browsing activity.

---

## General Data Protection Regulation (GDPR)

**GDPR** is a regulation designed to protect the personal data of citizens within the European Union (EU).

- Organisations must handle personal data responsibly.
- Transfers of personal data outside the EU are restricted unless adequate protections exist.

### HIPAA

The **Health Insurance Portability and Accountability Act (HIPAA)** is a United States law that protects personal healthcare information.

---

# Authentication, Authorization and Accounting (AAA)

## Authentication

Authentication verifies a user's identity.

### Single-Factor Authentication (SFA)

Uses one piece of evidence to verify identity.

#### Examples
- Username and password
- PIN

### Two-Factor Authentication (2FA)

Uses two different factors to verify identity.

#### Factors

1. **Something you know**
   - Password
   - PIN

2. **Something you have**
   - Mobile phone
   - Smart card
   - Security key

3. **Something you are**
   - Fingerprint
   - Facial recognition

### Single Sign-On (SSO)

Single Sign-On allows users to sign in once and access multiple applications or systems without signing in again.

---

## Authorization

Authorization determines what a user is allowed to do after authentication.

- Permissions are assigned by administrators.
- Controls access to files, applications, and resources.

### Principle of Least Privilege

Users should only be granted the minimum access required to perform their job.

---

## Accounting

Accounting is the process of recording and monitoring user activity within a system.

Examples include:
- Login attempts
- File access
- System changes
- Security events

### GPS and Geofencing

- **GPS** can be used to track people, devices, or equipment.
- **Geofencing** creates a virtual boundary based on a real-world location and can trigger security actions when crossed.

---

# Security Best Practices

## Security Awareness

### Social Engineering

The use of persuasion, manipulation, or intimidation to convince a victim to break security procedures.

### Lunchtime Attack

Occurs when an unattended and unlocked device is accessed without authorization.

### Shoulder Surfing

Observing someone entering passwords, PINs, or other sensitive information.

### Tailgating

Gaining unauthorized access to a secure area by following an authorized person through an entry point.

### Phishing and Smishing

Attempts to trick users into revealing sensitive information.

- **Phishing** uses email.
- **Smishing** uses SMS/text messages.

### Malware

Malicious software installed without the user's consent.

#### Examples
- Viruses
- Ransomware
- Worms
- Spyware

> **Note:** Air-gapped systems are isolated from external networks and the internet to improve security.

---

# Securing Devices

### 1. Authentication

Use either:
- Single-Factor Authentication (SFA)
- Two-Factor Authentication (2FA)

### 2. Anti-Malware Software

Software that detects, blocks, and removes malicious threats.

### 3. Firewalls

Hardware or software that protects networks and devices by filtering network traffic.

Firewalls make decisions based on:
- Source
- Destination
- Protocol

### 4. Updates and Patching

Keep operating systems and applications updated.

- Software vulnerabilities are discovered regularly.
- Older software versions pose greater security risks.

### 5. Physical Security

Examples include:
- Door locks
- Cable locks
- USB port locks

---

# Licensing

## End User License Agreement (EULA)

A legal contract governing the installation and use of software.

### Licensing Models

#### Subscription

Regular payments for continued software use.

#### Product Keys / Serial Numbers

Used to link purchased software to a specific customer.

#### Open Source

- Usually free to use.
- Source code may be modified and redistributed.

#### Proprietary Software

Software sold commercially for profit.

---

# Software Sources

When purchasing or installing software, always verify the legitimacy of the source.

## Original Equipment Manufacturer (OEM) Websites

OEM websites are operated by the company that designed and manufactured the product.

### Examples
- Dell
- HP
- Cisco

### Advantages
- Accurate information
- Official downloads
- Warranty and support information

### Disadvantages
- May only support their own products
- Sometimes less user-friendly

---

## Third-Party Websites

Third-party websites are operated by organisations other than the manufacturer.

### Examples
- Amazon
- Trustpilot

### Advantages
- Product reviews
- Price comparisons
- Independent opinions

### Disadvantages
- May not be official
- Reviews may be biased
- Information may be outdated

> **Note:** Software can usually be removed or uninstalled if no longer required.

---

# Password Best Practices

## Avoid

- Sharing passwords
- Reusing passwords
- Incrementing passwords (e.g., Password1, Password2)
- Easily guessed passwords
- Dictionary words only
- Common patterns and sequences

### Strong Passwords

Strong passwords should:
- Be long
- Include uppercase and lowercase letters
- Include numbers
- Include special characters

> **Note:** Many IoT devices ship with default passwords that should be changed immediately after installation.

---

## Password Managers

Password managers securely store and manage passwords for multiple accounts.

### Benefits
- Generates strong passwords
- Reduces password reuse
- Stores credentials securely

> **Note:** Passwords can often be reset if forgotten. Some devices also support password protection and biometric authentication.

---

# Encryption

Encryption converts **plaintext** (readable data) into **ciphertext** (unreadable data).

A key or encryption algorithm is required to decrypt the data.

---

## Data at Rest

Data stored on a device, server, database, or cloud service.

### Protection Methods
- Full-disk encryption
- File encryption
- Access permissions

### Example
- Screen lock

---

## Data in Transit

Data moving across a network or the internet.

### Examples

#### HTTPS (Hypertext Transfer Protocol Secure)

Encrypts communication between a web browser and a website.

Commonly used when:
- Shopping online
- Banking online
- Entering personal information

#### Virtual Private Network (VPN)

Creates an encrypted tunnel between a device and a network.

Benefits:
- Improves privacy
- Protects data on public Wi-Fi networks

---

# Small Wireless Network Security Configuration

### 1. Change Default Credentials

- Change the default administrator password.
- Change the default network name (SSID) if required.

### 2. Secure the Wireless Network

Ensure the network is private by using:
- A wireless password
- A Pre-Shared Key (PSK)
- Wi-Fi Protected Access (WPA)

### WPA Standards

- **WPA** – Original Wi-Fi security standard.
- **WPA2** – Improved security and widely used.
- **WPA3** – Latest and most secure wireless encryption standard.

> **Exam Tip:** WPA2 and WPA3 are the standards most commonly referenced in modern IT and cybersecurity exams.
