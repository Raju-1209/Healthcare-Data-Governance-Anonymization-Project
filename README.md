# 🏥 Healthcare Data Governance & Anonymization Project (CA Hospital Dataset – Q1 2025)

## 📌 Overview

This project showcases a practical application of **Data Governance** and **Privacy Compliance** using a synthetic California hospital dataset. We focused on detecting Personally Identifiable Information (PII), Protected Health Information (PHI), and sensitive fields in patient records, followed by **anonymizing** them using standard techniques to meet **HIPAA** and **CCPA** guidelines.

The goal is to simulate how real-world healthcare organizations must handle patient data responsibly — ensuring **data privacy**, **regulatory compliance**, and **ethical data usage**.

---

## 🔐 Why We Must Follow Data Governance Policies like HIPAA & CCPA

| Regulation | Description | Key Focus |
|------------|-------------|-----------|
| **HIPAA** (USA) | Health Insurance Portability and Accountability Act | Protects patient health data, mandates secure handling of PHI |
| **CCPA** (California) | California Consumer Privacy Act | Grants California residents rights over their personal data, including access, deletion, and opt-out |
| **GDPR** (EU) | General Data Protection Regulation | (For EU citizens) Emphasizes transparency, consent, and data minimization |

Failure to comply with these can lead to:

- 💸 **Hefty fines** (up to $1.5M per year under HIPAA)
- ⚖️ **Legal penalties and lawsuits**
- 🧱 **Business reputational damage**
- ❌ **Loss of customer and stakeholder trust**

---

## 🚨 Why Anonymization is Crucial in Healthcare Data

Anonymization transforms sensitive data into a format that **cannot be linked to any individual**, thus:
- Ensures **privacy protection** for patients
- Allows **safe sharing** of data with researchers, insurers, or vendors
- Reduces **legal and financial risks** in case of data breaches
- Complies with **"minimum necessary"** rule under HIPAA
- Helps organizations adopt **AI and analytics** safely

---

## 🧪 What Anonymization Techniques Were Used

| Column         | Anonymization Strategy Used                  |
|----------------|-----------------------------------------------|
| `first_name` & `last_name` | Masked with first letter only (e.g., R****) |
| `dob`          | Converted into age groups (e.g., 21–30)       |
| `phone`        | Masked all but last 3 digits (e.g., ****789)  |
| `email`        | Obfuscated domain (e.g., ra****@***.com)      |
| `zip`          | Truncated to 3-digit region code              |
| `address`      | Dropped entirely for safety                   |

This preserves **statistical value** while ensuring privacy.

