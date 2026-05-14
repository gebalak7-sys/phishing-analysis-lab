Markdown

# Phishing Analysis Lab

SOC-style phishing investigation project focused on email analysis, IOC extraction, and threat analysis techniques.

---

## Project Overview

This project simulates a phishing investigation workflow performed by a SOC Analyst during the analysis of suspicious emails and potential credential theft attempts.

The objective of the investigation was to:
- analyze suspicious email content
- verify sender legitimacy
- inspect email headers
- identify malicious indicators
- extract IOC (Indicators of Compromise)
- assess phishing techniques used during the attack

---

## Technologies Used

- VirusTotal
- Email Header Analysis
- IOC Analysis
- Threat Intelligence Techniques

---

## Investigation Workflow

### 1. Email Inspection
Initial analysis of suspicious email content, formatting, sender information, and social engineering indicators.

### 2. Header Analysis
Verification of:
- SPF records
- DKIM signatures
- Return-Path inconsistencies
- sender spoofing attempts

### 3. URL and Domain Verification
Analysis of suspicious links and domains using reputation checks and threat intelligence techniques.

### 4. IOC Extraction
Identification of:
- malicious URLs
- suspicious domains
- attacker infrastructure indicators

### 5. Threat Assessment
Evaluation of phishing tactics and potential impact on the targeted user.

---

## Example Indicators of Compromise

```txt id="9o3mce"
Suspicious Domain: fake-login-security[.]com
Malicious URL: hxxps://secure-account-update[.]com
Spoofed Sender: support@micr0soft-support[.]com
