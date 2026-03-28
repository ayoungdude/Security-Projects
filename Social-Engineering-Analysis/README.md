# Lab: Phishing Analysis & Threat Identification
**Part of the Google Cybersecurity Professional Certificate**

## 🎯 Objective
The goal of this lab was to analyze various communication samples to identify social engineering tactics and technical Indicators of Compromise (IoCs) used in phishing campaigns.

## 🛠️ Skills & Tools
* **Skills:** Social Engineering Detection, Link Analysis, Email Header Inspection, Risk Assessment.
* **Concepts:** Urgency, Authority, Scarcity, URL Masking.

## 🔍 Identified Red Flags
During the analysis of the provided samples, I identified the following common phishing techniques:

### 1. Psychological Triggers
* **False Urgency:** Attackers used language like "Immediate Action Required" or "Account Deletion" to bypass critical thinking.
* **Authority Impersonation:** Emails mimicked official department heads or IT support to gain trust.

### 2. Technical Discrepancies
* **Display Name Spoofing:** The "From" name appeared legitimate (e.g., "HR Department"), but the underlying email address did not match the organization's domain.
* **URL Mismatches:** Hovering over call-to-action buttons revealed destination links that were unrelated to the supposed sender.

## 🛡️ Mitigation & Prevention
To protect an organization from these threats, I recommend the following "Defense in Depth" strategies:
1. **User Awareness:** Regular training on identifying "hover-over" URL discrepancies.
2. **Technical Controls:** Implementing SPF, DKIM, and DMARC to prevent domain spoofing.
3. **Multi-Factor Authentication (MFA):** Ensuring that even if credentials are stolen via phishing, the attacker cannot gain account access.

---
*This lab demonstrates my ability to identify initial access vectors—a critical skill for any SOC Analyst or Security Researcher.*
