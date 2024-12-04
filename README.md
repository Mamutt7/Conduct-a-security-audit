# Security Audit Project: Botium Toys

## Overview
This project was completed as part of the Google Cybersecurity Professional Course. The focus was to conduct a comprehensive security audit for **Botium Toys**, evaluate its existing security controls and compliance practices, and recommend improvements to strengthen its security posture.

---

## Project Scope and Goals

### Scope
The audit encompassed all assets managed by Botium Toys, including:
- Employee equipment (e.g., desktops, laptops, smartphones, etc.).
- Internal network and systems (e.g., accounting, inventory management, and e-commerce platforms).
- On-premises equipment and legacy systems.
- Physical security measures (e.g., locks, surveillance cameras, fire prevention systems).

### Goals
- Assess existing assets to identify security gaps.
- Complete the **Controls and Compliance Checklist**.
- Recommend actionable measures to align with best practices and regulatory requirements.

---

## Key Findings

### Risk Assessment
- **Overall Risk Score**: **8/10**, indicating significant vulnerabilities due to insufficient controls and compliance measures.
- **Key Risks**:
  - Unrestricted employee access to sensitive data.
  - Lack of encryption for customer credit card information.
  - No disaster recovery plans or data backups.

### Current Controls
- **Implemented**: Firewall, antivirus software, physical locks, and CCTV surveillance.  
- **Missing/Inadequate**:
  - Intrusion Detection System (IDS).
  - Disaster recovery plans and regular data backups.
  - Comprehensive password policies and centralized password management.
  - Proper implementation of least privilege and separation of duties.

### Compliance Gaps
- **PCI DSS**: Missing encryption and access controls for sensitive credit card data.
- **GDPR**: Partial compliance; lacking robust data classification processes.
- **SOC 1/SOC 2**: Missing user access policies and data availability measures.

---

## Recommendations

### Technical Improvements
- Implement an **Intrusion Detection System (IDS)** to detect and respond to unauthorized activities.
- Deploy **encryption** for all sensitive customer data, particularly credit card information.
- Establish **regular backups** and test their integrity to support disaster recovery efforts.
- Enforce a centralized **password management system** with strong password policies.

### Administrative Enhancements
- Adopt **least privilege** and **separation of duties** to limit access to sensitive systems and data.
- Develop detailed **disaster recovery plans** to minimize downtime during incidents.

### Physical Security
- Conduct routine inspections of locks, CCTV systems, and fire prevention measures to ensure ongoing functionality.

### Compliance Alignment
- For **PCI DSS**, ensure only authorized users can access credit card data and enforce encryption at all transaction points.
- For **GDPR**, classify and inventory sensitive data to improve privacy measures.
- For **SOC 1/SOC 2**, define and document user access policies to ensure data confidentiality, integrity, and availability.

---

## Deliverables
The repository includes the following documentation:
- **Scope, Goals, and Risk Assessment Report**: Comprehensive details on the audit's findings and methodology.
- **Controls and Compliance Checklist**: Assessment of implemented and missing controls and compliance measures.
- **Recommendations Summary**: Actionable steps to address gaps and strengthen Botium Toys’ security posture.

---

Thank you for reviewing this project! Please feel free to explore the provided documents for more details on the security audit process.
