---
title: Statement of Applicability (SoA)
description: ZanReal Labs' Statement of Applicability defining the scope of the Information Security Management System and applicable ISO 27001/27002 controls
categories: [iso27001, iso27002, isms, security-controls, compliance, risk-management, audit]
---

ZanReal Labs ("ZanReal Labs", "we", "us", or "our") has established this Statement of Applicability (SoA) as part of our Information Security Management System (ISMS) to define the scope of our information security controls and their applicability to our business operations.

This Statement of Applicability is aligned with ISO/IEC 27001:2022 and references the security controls from ISO/IEC 27002:2022.

## ISMS Scope

### Organizational Scope

- **Company**: ZanReal Labs - ZANREAL Mateusz Janota
- **Business Activities**: Comprehensive technology services including software development, marketing services, remote IT support, SEO optimization, UI/UX design services, cloud platforms, and AI-powered solutions
- **Geographic Coverage**: Global operations with distributed workforce
- **Regulatory Environment**: GDPR, CCPA, PIPEDA, SOX, HIPAA (where applicable)

### Technical Scope

- All cloud infrastructure (AWS, Microsoft Azure, Google Cloud Platform)
- All customer-facing applications and platforms
- All internal systems and networks
- All data processing and storage systems
- All third-party integrations and services
- All physical and virtual assets

### Excluded from Scope

- Physical security of third-party data centers (managed by cloud providers)
- Customer-managed infrastructure and applications
- Third-party vendor internal security (covered by vendor assessments)

---

## ISO 27002:2022 Controls Applicability

### 5. Organizational Controls

| Control | Title | Status | Justification |
|---------|-------|--------|---------------|
| 5.1 | Policies for information security | ✅ Applicable | Comprehensive Information Security Policy implemented |
| 5.2 | Information security roles and responsibilities | ✅ Applicable | Defined in Information Security Policy section 3 |
| 5.3 | Segregation of duties | ✅ Applicable | Implemented through role-based access controls |
| 5.4 | Management responsibilities | ✅ Applicable | Executive oversight and accountability established |
| 5.5 | Contact with authorities | ✅ Applicable | Incident response procedures include authority notification |
| 5.6 | Contact with special interest groups | ✅ Applicable | Security community engagement and threat intelligence |
| 5.7 | Threat intelligence | ✅ Applicable | Wazuh SIEM and external threat feeds implemented |
| 5.8 | Information security in project management | ✅ Applicable | Security by design in development lifecycle |
| 5.9 | Inventory of information and other associated assets | ✅ Applicable | Asset management procedures implemented |
| 5.10 | Acceptable use of information and other associated assets | ✅ Applicable | Defined in Information Security Policy |
| 5.11 | Return of assets | ✅ Applicable | Asset return procedures for departing personnel |
| 5.12 | Classification of information | ✅ Applicable | Data classification framework implemented |
| 5.13 | Labelling of information | ✅ Applicable | Data labeling standards implemented |
| 5.14 | Information transfer | ✅ Applicable | Secure data transfer protocols implemented |
| 5.15 | Access control | ✅ Applicable | Comprehensive access control framework |
| 5.16 | Identity management | ✅ Applicable | Centralized identity management with SSO |
| 5.17 | Authentication information | ✅ Applicable | Strong authentication with MFA/Passkeys |
| 5.18 | Access rights | ✅ Applicable | Role-based access control (RBAC) implemented |
| 5.19 | Information security in supplier relationships | ✅ Applicable | Supplier security assessment procedures |
| 5.20 | Addressing information security within supplier agreements | ✅ Applicable | Security clauses in vendor contracts |
| 5.21 | Managing information security in the ICT supply chain | ✅ Applicable | Supply chain security assessments |
| 5.22 | Monitoring, review and change management of supplier services | ✅ Applicable | Ongoing supplier monitoring procedures |
| 5.23 | Information security for use of cloud services | ✅ Applicable | Cloud security framework for AWS/Azure/GCP |
| 5.24 | Information security incident management planning and preparation | ✅ Applicable | Comprehensive incident response plan |
| 5.25 | Assessment and decision on information security events | ✅ Applicable | Event triage and escalation procedures |
| 5.26 | Response to information security incidents | ✅ Applicable | Incident response procedures with Wazuh SIEM |
| 5.27 | Learning from information security incidents | ✅ Applicable | Post-incident review and improvement process |
| 5.28 | Collection of evidence | ✅ Applicable | Digital forensics and evidence handling |
| 5.29 | Information security during disruption | ✅ Applicable | Business continuity and disaster recovery |
| 5.30 | ICT readiness for business continuity | ✅ Applicable | Technology recovery procedures |

### 6. People Controls

| Control | Title | Status | Justification |
|---------|-------|--------|---------------|
| 6.1 | Screening | ✅ Applicable | Background check procedures for personnel |
| 6.2 | Terms and conditions of employment | ✅ Applicable | Security clauses in employment agreements |
| 6.3 | Information security awareness, education and training | ✅ Applicable | Mandatory security training program |
| 6.4 | Disciplinary process | ✅ Applicable | Security violation consequences defined |
| 6.5 | Information security responsibilities after termination or change of employment | ✅ Applicable | Termination security procedures |
| 6.6 | Confidentiality or non-disclosure agreements | ✅ Applicable | NDAs for all personnel and contractors |
| 6.7 | Remote working | ✅ Applicable | Remote work security guidelines |
| 6.8 | Information security event reporting | ✅ Applicable | Security incident reporting procedures |

### 7. Physical Controls

| Control | Title | Status | Justification |
|---------|-------|--------|---------------|
| 7.1 | Physical security perimeters | ⚠️ Limited Applicability | Office security measures; cloud DCs managed by providers |
| 7.2 | Physical entry | ⚠️ Limited Applicability | Office access controls; cloud DCs managed by providers |
| 7.3 | Protection against environmental threats | ⚠️ Limited Applicability | Office environmental controls; cloud resilience |
| 7.4 | Working in secure areas | ✅ Applicable | Secure workspace guidelines |
| 7.5 | Desk and screen | ✅ Applicable | Clean desk and screen lock policies |
| 7.6 | Removal of assets | ✅ Applicable | Asset removal authorization procedures |
| 7.7 | Secure disposal or reuse of equipment | ✅ Applicable | Secure data destruction procedures |
| 7.8 | Equipment siting and protection | ✅ Applicable | Equipment security and protection |
| 7.9 | Security of assets off-premises | ✅ Applicable | Mobile device and remote asset security |
| 7.10 | Storage media | ✅ Applicable | Secure handling of storage media |
| 7.11 | Supporting utilities | ⚠️ Limited Applicability | Office utilities; cloud infrastructure resilience |
| 7.12 | Cabling security | ⚠️ Limited Applicability | Office network security; cloud managed infrastructure |
| 7.13 | Equipment maintenance | ✅ Applicable | IT equipment maintenance procedures |
| 7.14 | Secure disposal or reuse of equipment | ✅ Applicable | Equipment disposal and sanitization |

### 8. Technological Controls

| Control | Title | Status | Justification |
|---------|-------|--------|---------------|
| 8.1 | User endpoint devices | ✅ Applicable | Endpoint protection with Bitdefender GravityZone |
| 8.2 | Privileged access rights | ✅ Applicable | Privileged access management implemented |
| 8.3 | Information access restriction | ✅ Applicable | Access controls and data restrictions |
| 8.4 | Access to source code | ✅ Applicable | Source code access controls and version control |
| 8.5 | Secure authentication | ✅ Applicable | MFA with YubiKeys and Passkeys |
| 8.6 | Capacity management | ✅ Applicable | Cloud resource monitoring and scaling |
| 8.7 | Protection against malware | ✅ Applicable | Bitdefender endpoint protection and Wazuh monitoring |
| 8.8 | Management of technical vulnerabilities | ✅ Applicable | Nessus vulnerability management |
| 8.9 | Configuration management | ✅ Applicable | Infrastructure as Code and configuration management |
| 8.10 | Information deletion | ✅ Applicable | Secure deletion procedures |
| 8.11 | Data masking | ✅ Applicable | Data anonymization and pseudonymization |
| 8.12 | Data leakage prevention | ✅ Applicable | DLP controls and monitoring |
| 8.13 | Information backup | ✅ Applicable | Comprehensive backup and recovery procedures |
| 8.14 | Redundancy of information processing facilities | ✅ Applicable | Multi-region cloud redundancy |
| 8.15 | Logging | ✅ Applicable | Comprehensive logging with Wazuh SIEM |
| 8.16 | Monitoring activities | ✅ Applicable | Continuous monitoring with Wazuh and Cloudflare |
| 8.17 | Clock synchronisation | ✅ Applicable | NTP synchronization across all systems |
| 8.18 | Use of privileged utility programs | ✅ Applicable | Controlled use of administrative tools |
| 8.19 | Installation of software on operational systems | ✅ Applicable | Change management for software installations |
| 8.20 | Networks security management | ✅ Applicable | Network security with Cloudflare Zero Trust |
| 8.21 | Security of network services | ✅ Applicable | Network service security controls |
| 8.22 | Segregation of networks | ✅ Applicable | Network segmentation and isolation |
| 8.23 | Web filtering | ✅ Applicable | Web filtering and content security |
| 8.24 | Use of cryptography | ✅ Applicable | Encryption at rest and in transit |
| 8.25 | Secure system development life cycle | ✅ Applicable | Secure SDLC practices |
| 8.26 | Application security requirements | ✅ Applicable | Security requirements in development |
| 8.27 | Secure system architecture and engineering principles | ✅ Applicable | Security by design principles |
| 8.28 | Secure coding | ✅ Applicable | Secure coding standards and practices |
| 8.29 | Security testing in development and acceptance | ✅ Applicable | Security testing and code review |
| 8.30 | Outsourced development | ✅ Applicable | Third-party development security requirements |
| 8.31 | Separation of development, testing and operational environments | ✅ Applicable | Environment segregation |
| 8.32 | Change management | ✅ Applicable | Change management procedures |
| 8.33 | Test information | ✅ Applicable | Test data management and protection |
| 8.34 | Protection of information systems during audit testing | ✅ Applicable | Audit testing security procedures |

---

## Risk Treatment Decisions

### Controls Selected for Implementation

All applicable controls listed above have been selected for implementation based on:

- Risk assessment results
- Legal and regulatory requirements
- Business requirements and objectives
- Cost-benefit analysis

### Controls Excluded from Implementation

Limited physical controls (7.1, 7.2, 7.3, 7.11, 7.12) are partially excluded as they relate to third-party data center facilities managed by cloud service providers (AWS, Azure, GCP). These are addressed through:

- Cloud provider compliance certifications (SOC 2, ISO 27001)
- Contractual security requirements
- Regular vendor assessments

### Additional Controls

Beyond ISO 27002:2022, ZanReal Labs has implemented additional controls:

- AI-specific security controls for machine learning systems
- Enhanced privacy controls for GDPR compliance
- Advanced threat detection with behavioral analytics
- Zero trust network architecture

---

## Conclusion

This Statement of Applicability demonstrates ZanReal Labs' comprehensive approach to information security control implementation. All applicable ISO 27002:2022 controls have been implemented or are in the process of implementation, with appropriate justifications for any exclusions.

Regular reviews of this SoA will be conducted as part of the ISMS management review process to ensure continued relevance and effectiveness.

---

## Previous Versions

The previous versions of our Policies and other documents can be seen at [GitHub](https://github.com/zanreal-labs/legal)
