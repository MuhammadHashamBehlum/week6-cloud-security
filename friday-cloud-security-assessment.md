# Cloud Security Assessment Report – Consolidating the Cloud Engagement

**Prepared By:** Mohammad Hesham Wazir Ali Behlum

**University:** Rochester Institute of Technology (RIT) Dubai

**Program:** Bachelor of Science in Cybersecurity

**Internship:** Sohail Smart Solutions Summer Training Program 2026

---

## Overview

This report concludes the Week 6 cloud security engagement by combining the findings from the previous four assignments into one client-ready Cloud Security Assessment.

The assessment evaluates the security posture of **EduTrack Learning Solutions**, a fictional organization migrating its Learning Management System (LMS) to **Amazon Web Services (AWS)** using the Infrastructure as a Service (IaaS) model.

The report summarizes the key security findings, prioritizes risks, recommends remediation actions, and maps the assessment to ISO/IEC 27017 and ISO/IEC 27018 cloud security guidance.

---

## Assessment Scope

The assessment includes:

- Cloud Security Foundations
- Shared Responsibility Model
- Identity and Access Management (IAM)
- Cloud Configuration
- Cloud Security Posture Management (CSPM)
- Data Protection
- Cloud Compliance
- Risk Assessment
- Security Recommendations

---

## Key Findings

### Cloud Security Foundations

- AWS Shared Responsibility Model correctly understood
- Initial governance processes established
- Cloud risks identified before migration

**Risk:** Medium

---

### Identity & Access Management

- Role-Based Access Control (RBAC)
- Least Privilege
- Multi-Factor Authentication (MFA)
- Identity Federation
- Single Sign-On (SSO)

**Risk:** High

---

### Cloud Configuration & CSPM

- AWS Config
- AWS CloudTrail
- CIS Benchmarks
- Continuous Compliance Monitoring

**Risk:** High

---

### Data Protection

- Encryption at Rest
- Encryption in Transit
- AWS Key Management Service (KMS)
- Tokenization
- GDPR
- UAE PDPL

**Risk:** Medium

---

## Overall Risk Rating

| Security Area | Risk |
|---------------|------|
| Cloud Foundations | Medium |
| IAM | High |
| Configuration & CSPM | High |
| Data Protection | Medium |

**Overall Assessment:** Medium-High Risk

---

## Recommendations

### Quick Wins

- Enforce MFA
- Remove excessive IAM permissions
- Block public S3 buckets
- Enable CloudTrail
- Enable AWS Config

### Medium-Term

- Deploy CSPM
- Complete Single Sign-On
- Perform IAM reviews
- Improve governance documentation

### Long-Term

- Automate compliance reporting
- Annual penetration testing
- Continuous cloud monitoring
- Regular security architecture reviews

---

## Standards Referenced

- ISO/IEC 27017
- ISO/IEC 27018
- GDPR
- UAE PDPL
- CIS Benchmarks

---

## Conclusion

The Week 6 cloud engagement demonstrates how cloud governance, IAM, secure configuration, and data protection work together to strengthen an organization's cloud security posture.

By implementing the recommendations in this assessment, EduTrack Learning Solutions can reduce security risks, improve compliance, and build a secure, resilient AWS environment capable of supporting future business growth.

---

**Week 6 Complete ✅**
