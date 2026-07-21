# Cloud Identity & Access Management – Securing the New Perimeter

**Prepared By:** Mohammad Hesham Wazir Ali Behlum

**University:** Rochester Institute of Technology (RIT) Dubai

**Program:** Bachelor of Science in Cybersecurity

**Internship:** Sohail Smart Solutions Summer Training Program 2026

---

## Overview

This repository contains the **Week 6 Tuesday assignment** completed as part of the Sohail Smart Solutions Summer Training Program 2026.

The objective of this assignment is to design a secure **Identity and Access Management (IAM)** strategy for a fictional organization migrating its Learning Management System (LMS) to **Amazon Web Services (AWS)**.

This task builds directly on Monday's cloud security foundations assignment and continues the cloud migration scenario for **EduTrack Learning Solutions**. The focus is on securing cloud identities, defining access permissions, applying the principle of least privilege, and identifying common IAM risks that could affect the confidentiality, integrity, and availability of cloud resources.

---

## Repository Contents

- ✅ Monday – Cloud Security Foundations: Shared Responsibility & Cloud Threat Model
- ✅ Tuesday – Cloud Identity & Access Management (IAM)
- ⏳ Wednesday – Cloud Configuration & CSPM
- ⏳ Thursday – Cloud Data Protection & Compliance
- ⏳ Friday – Cloud Security Assessment Report

---

## Learning Objectives

This assignment focuses on the following cloud security concepts:

- Understand Identity and Access Management (IAM).
- Learn Role-Based Access Control (RBAC).
- Apply the Principle of Least Privilege.
- Understand Multi-Factor Authentication (MFA).
- Learn Identity Federation and Single Sign-On (SSO).
- Design secure IAM roles.
- Identify common IAM misconfigurations.
- Map IAM risks to ISO/IEC 27001 access control requirements.

---

## Cloud Environment

| Item | Details |
|------|---------|
| **Cloud Provider** | Amazon Web Services (AWS) |
| **Cloud Service Model** | Infrastructure as a Service (IaaS) |
| **Organization** | EduTrack Learning Solutions |
| **Migration Target** | Learning Management System (LMS) |
| **Industry** | Education Technology (EdTech) |

---

## IAM Roles

The cloud environment uses four primary IAM roles.

| Role | Purpose |
|------|---------|
| Cloud Administrator | Manages cloud infrastructure, networking, IAM configuration, and security settings. |
| Developer | Builds, tests, and deploys applications without administrative access. |
| Auditor | Reviews logs, security reports, and compliance evidence using read-only permissions. |
| Read-Only User | Monitors cloud resources without making changes. |

All roles follow the **Principle of Least Privilege**, ensuring users receive only the permissions required for their assigned responsibilities.

---

## Permission Boundaries

### Cloud Administrator

- Full administration of AWS infrastructure.
- MFA required.
- Administrative actions are logged.
- Uses dedicated administrator accounts.

### Developer

- Access only development resources.
- Cannot modify IAM policies.
- Cannot access billing services.
- Cannot manage security configurations.

### Auditor

- Read-only access.
- Reviews CloudTrail logs and compliance reports.
- Cannot modify cloud resources.

### Read-Only User

- View cloud dashboards.
- Monitor system health.
- Cannot create, edit, or delete resources.

---

## Least Privilege

The Principle of Least Privilege means every user should receive only the permissions necessary to complete their work.

Following this principle helps organizations:

- Reduce unauthorized access.
- Limit the impact of compromised accounts.
- Prevent accidental configuration changes.
- Improve compliance with security standards.
- Reduce insider threats.

---

## Identity Federation and Single Sign-On (SSO)

Identity Federation allows employees to access AWS using their existing corporate accounts instead of maintaining separate cloud accounts.

Single Sign-On (SSO) enables users to authenticate once and securely access multiple approved cloud applications without signing in repeatedly.

Together, these technologies simplify user management, strengthen authentication, and improve the overall user experience.

---

## IAM Risks Identified

The following identity-related risks were identified during the cloud migration:

1. Administrator accounts without Multi-Factor Authentication (MFA).
2. Developers with unnecessary administrator privileges.
3. Privilege creep caused by outdated permissions.
4. Active accounts belonging to former employees.
5. Weak password practices.
6. Excessive access to sensitive cloud resources.

---

## IAM Audit Findings

| Audit Finding | Risk | ISO/IEC 27001 Control |
|---------------|------|-----------------------|
| Administrator accounts do not use MFA. | Stolen credentials may provide full administrative access. | A.5.17 – Authentication Information |
| Developers retain administrator permissions after projects end. | Creates privilege creep and increases security risk. | A.5.15 – Access Control |
| Former employee accounts remain active. | Unauthorized users may continue accessing cloud resources. | A.5.18 – Access Rights |

---

## Security Recommendations

EduTrack Learning Solutions should:

- Implement Role-Based Access Control (RBAC).
- Enforce Multi-Factor Authentication (MFA) for privileged accounts.
- Review user permissions regularly.
- Remove inactive accounts immediately.
- Use Identity Federation and Single Sign-On (SSO).
- Monitor IAM activity using AWS CloudTrail.
- Perform regular access reviews.
- Audit privileged accounts periodically.

---

## Technologies & Standards

This assignment references the following technologies, frameworks, and standards:

- Amazon Web Services (AWS)
- Infrastructure as a Service (IaaS)
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Identity Federation
- Single Sign-On (SSO)
- AWS CloudTrail
- ISO/IEC 27001
- Cloud Security Best Practices

---

## Skills Demonstrated

This assignment demonstrates practical knowledge in:

- Cloud Identity and Access Management
- Cloud Governance
- Role-Based Access Control (RBAC)
- Least Privilege Design
- Identity Federation
- Single Sign-On (SSO)
- Permission Boundary Design
- Security Risk Assessment
- Identity Governance
- ISO/IEC 27001 Access Control Mapping
- Cloud Security Best Practices

---

## Repository Goal

The purpose of this repository is to document the practical cloud security tasks completed during **Week 6** of the Sohail Smart Solutions Summer Training Program.

Each assignment builds on the same fictional cloud migration scenario involving **EduTrack Learning Solutions**, demonstrating how governance, cloud security, identity management, compliance, and risk management work together throughout a cloud adoption project.

By the end of Week 6, this repository will document the complete cloud security engagement, from understanding cloud security foundations to assessing cloud configurations, protecting sensitive data, and producing a final cloud security assessment report.

---

## Week 6 Progress

- ✅ Monday – Cloud Security Foundations: Shared Responsibility & Cloud Threat Model
- ✅ Tuesday – Cloud Identity & Access Management (IAM)
- ⏳ Wednesday – Cloud Configuration & CSPM
- ⏳ Thursday – Cloud Data Protection & Compliance
- ⏳ Friday – Cloud Security Assessment Report

---

*This repository represents coursework completed as part of the Sohail Smart Solutions Summer Training Program 2026. The organization, EduTrack Learning Solutions, is a fictional client used for educational purposes to demonstrate cloud governance, cloud security, and Identity and Access Management (IAM) concepts.*
