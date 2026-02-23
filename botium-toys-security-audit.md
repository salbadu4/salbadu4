# Botium Toys Security Audit

**Author:** Salatiel Badu
**Date:** 2/23/2026

---

## 📌 Objective

The purpose of this audit is to assess the security posture of Botium Toys and identify risks, vulnerabilities, and compliance gaps. This audit aligns with the NIST Cybersecurity Framework (CSF) to evaluate the organization’s current controls.

---

## 🏢 Company Overview

Botium Toys is a small U.S.-based business that sells toys both in-store and online. The company manages customer data, payment information, and internal business systems. As the company expands globally, including customers in the European Union, security and compliance requirements have become increasingly important.

---

## 📊 Scope

This audit covers:

* Internal network
* Employee devices
* Data storage systems
* E-commerce systems
* Payment processing systems

---

## ⚠️ Risk Assessment Summary

Botium Toys has a high risk score of **8/10** due to insufficient security controls and incomplete compliance with industry regulations.

### Key Risks:

* Unauthorized access to sensitive data
* Lack of encryption for credit card information
* No disaster recovery plan
* Weak access controls
* Missing intrusion detection system (IDS)

---

## 🛡️ Controls Assessment

| Control                    | Status                |
| -------------------------- | --------------------- |
| Least Privilege            | Not Implemented       |
| Disaster Recovery Plan     | Not Implemented       |
| Password Policy            | Implemented (Weak)    |
| Separation of Duties       | Not Implemented       |
| Firewall                   | Implemented           |
| Intrusion Detection System | Not Implemented       |
| Backups                    | Not Implemented       |
| Antivirus Software         | Implemented           |
| Legacy System Monitoring   | Partially Implemented |
| Encryption                 | Not Implemented       |
| Password Management System | Not Implemented       |
| Physical Locks             | Implemented           |
| CCTV Surveillance          | Implemented           |
| Fire Detection Systems     | Implemented           |

---

## 💳 PCI DSS Compliance

Botium Toys is **not compliant** with PCI DSS due to:

* Lack of encryption for credit card data
* Excessive user access to sensitive data
* Weak password policies
* Lack of proper security controls

---

## 🇪🇺 GDPR Compliance

Botium Toys is **partially compliant** with GDPR.

### Strengths:

* Breach notification plan (72-hour rule)
* Privacy policies are documented

### Weaknesses:

* Poor data protection controls
* Lack of data classification
* Excessive access to sensitive information

---

## 🧾 SOC Compliance

Botium Toys is **partially compliant** with SOC standards.

* Data integrity and availability controls are in place
* However, access controls and data confidentiality measures are weak

---

## 🧠 Recommendations

To improve security posture, Botium Toys should:

* Implement least privilege access controls
* Enforce strong password policies and password management systems
* Encrypt all sensitive and payment data
* Deploy an intrusion detection system (IDS)
* Establish a disaster recovery plan
* Perform regular backups of critical data
* Improve asset management and classification

---

## ✅ Conclusion

The audit identified several critical vulnerabilities and compliance gaps within Botium Toys’ infrastructure. Addressing these issues will reduce security risks, protect customer data, and ensure compliance with industry regulations such as PCI DSS and GDPR.
