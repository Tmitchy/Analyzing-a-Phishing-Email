# 🎣 Phishing Email Analysis

![Cybersecurity](https://img.shields.io/badge/Category-Phishing%20Analysis-red)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-Email%20Analysis%20%7C%20SMTP%20%7C%20SPF%20%7C%20DKIM%20%7C%20DMARC-blue)
![Skill Level](https://img.shields.io/badge/Level-Junior%20SOC%20Analyst-orange)

## 📌 Overview

Phishing attacks continue to evolve, making it increasingly difficult to distinguish legitimate emails from malicious ones. This repository documents the analysis of a phishing email that closely impersonated my workplace using a forged domain.

Although this is not the first phishing email I have received and certainly won't be the last, it serves as an excellent real-world example of the techniques attackers use to deceive users.

At first glance, the email appeared authentic:
- Professional language
- Trusted display name
- Corporate branding
- Convincing formatting

However, a detailed investigation revealed several indicators that exposed it as a phishing attempt.

---

## 🎯 Objective

The purpose of this project is to demonstrate how a Junior SOC Analyst can identify phishing attempts through manual email analysis and by applying cybersecurity best practices.

---

# 🔍 Phishing Indicators Identified

## 1️⃣ Suspicious Sender Address

Although the sender's **display name** belonged to an employee from another department, the actual email address did not match the organization's legitimate domain.

**Red Flag**
- Display name ≠ Actual email address

---

## 2️⃣ Urgency and Pressure

The email attempted to create a false sense of urgency by encouraging immediate action.

Common phishing tactics include:
- Immediate response required
- Account suspension warnings
- Security alerts
- Document review requests

Attackers rely on emotional pressure to reduce critical thinking.

---

## 3️⃣ Questionable Links

Before clicking any hyperlinks, I hovered over them to inspect the destination URL.

The links pointed to domains unrelated to my organization, strongly suggesting malicious intent.

**Always:**
- Hover before clicking
- Verify the domain
- Check for misspellings or look-alike domains

---

## 4️⃣ Grammar and Formatting Issues

Despite appearing professional, the email contained subtle inconsistencies such as:

- Minor grammatical mistakes
- Awkward sentence structure
- Inconsistent formatting

While modern phishing emails often use AI-generated content, small errors can still reveal fraudulent messages.

---

## 5️⃣ Unexpected Request

The email requested that I review and comment on a document using the provided link.

Unexpected requests involving:

- Login pages
- Shared documents
- Password verification
- Payment requests

It should always be verified through another trusted communication channel.

---

# 🛡️ Email Authentication Checks

Beyond visual inspection, legitimate emails should also pass authentication checks.

## SPF (Sender Policy Framework)

Verifies whether the sending mail server is authorized to send emails on behalf of the domain.

---

## DKIM (DomainKeys Identified Mail)

Uses cryptographic signatures to verify that the email has not been altered during transmission.

---

## DMARC (Domain-based Message Authentication, Reporting & Conformance)

Builds upon SPF and DKIM by defining how receiving mail servers should handle unauthenticated emails.

---

## Additional Verification

Other valuable checks include:

- SMTP source IP analysis
- WHOIS domain lookup
- Domain age verification
- Reply-To address inspection
- Header analysis
- URL reputation checks

---

# 🧰 Skills Demonstrated

- Email Header Analysis
- Phishing Detection
- Threat Hunting Mindset
- Social Engineering Awareness
- URL Inspection
- Domain Verification
- SMTP Analysis
- SPF Validation
- DKIM Validation
- DMARC Verification
- Cybersecurity Documentation

---

# 📚 Key Takeaways

✔ Never trust the display name alone.

✔ Always inspect the sender's email address.

✔ Hover over links before clicking.

✔ Verify unexpected requests through official channels.

✔ Check SPF, DKIM, and DMARC whenever possible.

✔ Small inconsistencies often reveal sophisticated phishing attempts.

---

# 🚀 Lessons Learned

This exercise reinforced the importance of remaining vigilant when handling emails, even those that appear to come from trusted sources.

Modern phishing campaigns are highly sophisticated and often imitate legitimate organizations with remarkable accuracy. Taking a few extra seconds to verify an email before interacting with it can prevent credential theft, malware infections, and data breaches.

As an aspiring SOC Analyst, developing the habit of carefully analyzing suspicious emails is an essential defensive skill.

---


