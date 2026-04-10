# Secure Messaging Application (End-to-End Encryption)

## Overview

Designed a secure messaging system that ensures confidentiality, integrity, authentication, and privacy using modern cryptographic techniques. The application implements end-to-end encryption so that only communicating users can read messages, while the server acts only as a relay.

---

## Objectives

* Protect messages from interception and tampering
* Implement end-to-end encryption (E2EE)
* Secure communication channels using TLS
* Protect local device storage
* Ensure user authentication and privacy

---

## Technologies Used

* Signal Protocol (X3DH + Double Ratchet)
* AES-256 Encryption
* HMAC-SHA256
* TLS 1.3
* Python (simulation)

---

## Methodology

### 1. Key Exchange & Session Setup

* Implemented X3DH key agreement
* Established secure session using Diffie-Hellman

### 2. End-to-End Encryption

* Messages encrypted using AES-256
* Keys rotated using Double Ratchet algorithm

### 3. Secure Communication Channel

* TLS 1.3 with Perfect Forward Secrecy
* Prevents MITM and packet sniffing

### 4. Secure File Transfer

* Files encrypted before upload
* Server stores only encrypted data

### 5. Secure Local Storage

* Encrypted database storage
* Protected encryption keys

### 6. Authentication & Access Control

* User authentication with secure session handling
* Prevents unauthorized access

---

## Key Features

* End-to-End Encryption (E2EE)
* Forward Secrecy & Future Secrecy
* Secure Voice Communication
* Encrypted File Sharing
* Privacy-focused (Zero-knowledge server)


---

## Security Benefits

* Protects against Man-in-the-Middle (MITM) attacks
* Prevents message interception
* Secures data even if server is compromised
* Ensures privacy and confidentiality

---

## Key Learning

* Real-world cryptographic implementation
* Importance of E2EE in messaging apps
* Secure communication architecture
* Privacy-first system design

---

## Full Report

Detailed documentation available in: [report.pdf]
