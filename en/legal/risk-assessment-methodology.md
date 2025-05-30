---
title: Risk Assessment Methodology
description: ZanReal Labs' systematic approach to identifying, analyzing, and evaluating information security risks across all business operations and technology assets.
categories: [iso27001, iso27002, risk-management, security, isms, compliance, threat-assessment, vulnerability-management]
tags: [risk-assessment, iso27001, security, isms, threat-analysis, vulnerability-assessment, risk-management, compliance]
---

ZanReal Labs ("ZanReal Labs", "we", "us", or "our") implements a comprehensive risk assessment methodology to systematically identify, analyze, and evaluate information security risks. This methodology forms the foundation of our Information Security Management System (ISMS) and ensures consistent, repeatable risk assessment processes across all business operations.

## Purpose and Scope

This methodology applies to:

- All information assets owned, operated, or managed by ZanReal Labs
- All business processes and supporting technology systems
- All physical and virtual environments
- All third-party services and supplier relationships
- All employees, contractors, and authorized users

## Risk Assessment Framework

### Risk Assessment Principles

Our risk assessment approach is based on the following principles:

- **Asset-Based Analysis**: Risks are assessed based on potential impact to information assets
- **Threat-Centric Approach**: Current and emerging threats are systematically evaluated
- **Vulnerability-Focused**: Known vulnerabilities are identified and assessed for exploitability
- **Business Impact Alignment**: Risk evaluation considers business impact and operational consequences
- **Quantitative and Qualitative Analysis**: Both methodologies are used as appropriate
- **Continuous Assessment**: Risk assessment is an ongoing process with regular updates

### Risk Components

Each risk assessment evaluates three core components:

#### Assets

- **Information Assets**: Data, databases, documentation, intellectual property
- **Technology Assets**: Hardware, software, systems, networks, cloud services
- **Physical Assets**: Facilities, equipment, mobile devices
- **Human Assets**: Personnel knowledge, skills, reputation
- **Intangible Assets**: Brand reputation, customer trust, business relationships

#### Threats

- **Malicious Threats**: Cybercriminals, hackers, malicious insiders, nation-state actors
- **Accidental Threats**: Human error, system failures, misconfigurations
- **Natural Threats**: Natural disasters, environmental factors, power outages
- **Technical Threats**: Hardware failures, software bugs, network outages
- **Supplier Threats**: Third-party service disruptions, vendor security incidents

#### Vulnerabilities

- **Technical Vulnerabilities**: Software flaws, misconfigurations, weak encryption
- **Physical Vulnerabilities**: Inadequate physical security, environmental risks
- **Procedural Vulnerabilities**: Inadequate processes, missing controls, poor documentation
- **Human Vulnerabilities**: Lack of awareness, inadequate training, social engineering susceptibility
- **Organizational Vulnerabilities**: Insufficient governance, resource constraints, cultural issues

## Risk Assessment Process

### Phase 1: Asset Identification and Valuation

#### Asset Discovery

- Conduct comprehensive asset inventory using automated discovery tools
- Interview business process owners and system administrators
- Review network diagrams, system documentation, and architectural designs
- Identify cloud services, SaaS applications, and third-party dependencies

#### Asset Classification

Assets are classified using the following criteria:

**Confidentiality Requirements**:

- **Public (C0)**: No confidentiality requirements
- **Internal (C1)**: Limited internal distribution
- **Confidential (C2)**: Restricted access required
- **Highly Confidential (C3)**: Strict access controls mandatory

**Integrity Requirements**:

- **Basic (I1)**: Minor impact if corrupted
- **Important (I2)**: Moderate impact if corrupted
- **Critical (I3)**: Severe impact if corrupted

**Availability Requirements**:

- **Standard (A1)**: Standard business hours availability
- **High (A2)**: Extended hours with minimal downtime
- **Critical (A3)**: 24/7 availability required

#### Asset Valuation

Each asset is assigned a business value based on:

- **Replacement Cost**: Cost to replace or recreate the asset
- **Business Criticality**: Impact on business operations if unavailable
- **Regulatory Requirements**: Compliance obligations and potential penalties
- **Revenue Impact**: Direct or indirect revenue implications
- **Reputation Impact**: Potential damage to organizational reputation

**Asset Value Scale**:

- **Low (1-2)**: Minimal business impact, easily replaceable
- **Medium (3-4)**: Moderate business impact, some difficulty replacing
- **High (5-6)**: Significant business impact, difficult to replace
- **Critical (7-8)**: Severe business impact, extremely difficult to replace
- **Vital (9-10)**: Business-critical, irreplaceable or catastrophic impact

### Phase 2: Threat Identification and Analysis

#### Threat Source Identification

- **External Threats**: Cybercriminals, hacktivists, nation-state actors, competitors
- **Internal Threats**: Malicious insiders, negligent employees, contractors
- **Environmental Threats**: Natural disasters, infrastructure failures, pandemics
- **Technical Threats**: System failures, software bugs, network outages

#### Threat Intelligence Integration

- Leverage threat intelligence feeds from multiple sources
- Monitor security advisories and vulnerability databases
- Analyze industry-specific threat reports and indicators
- Participate in threat intelligence sharing communities

#### Threat Likelihood Assessment

Threats are evaluated using the following likelihood scale:

- **Very Low (1)**: Highly unlikely to occur (0-5% annually)
- **Low (2)**: Unlikely to occur (6-25% annually)
- **Medium (3)**: Possible to occur (26-50% annually)
- **High (4)**: Likely to occur (51-75% annually)
- **Very High (5)**: Almost certain to occur (76-100% annually)

### Phase 3: Vulnerability Assessment

#### Vulnerability Identification Methods

- **Automated Scanning**: Use Nessus Professional and other vulnerability scanners
- **Manual Testing**: Penetration testing and security assessments
- **Code Review**: Static and dynamic application security testing
- **Configuration Review**: Security configuration assessments
- **Process Review**: Procedural and administrative control assessments

#### Vulnerability Rating

Vulnerabilities are rated using the Common Vulnerability Scoring System (CVSS) v3.1:

- **Critical (9.0-10.0)**: Immediate attention required
- **High (7.0-8.9)**: High priority remediation
- **Medium (4.0-6.9)**: Medium priority remediation
- **Low (0.1-3.9)**: Low priority remediation
- **Informational (0.0)**: No immediate security impact

#### Exploitability Assessment

For each vulnerability, we assess:

- **Attack Vector**: Network, adjacent network, local, physical
- **Attack Complexity**: Low or high complexity required
- **Privileges Required**: None, low, or high privilege level needed
- **User Interaction**: None or required user interaction
- **Scope**: Unchanged or changed from vulnerable component

### Phase 4: Risk Calculation and Evaluation

#### Risk Formula

**Risk = Asset Value × Threat Likelihood × Vulnerability Rating**

#### Risk Matrix

Risks are categorized using a 5×5 risk matrix:

| Impact/Likelihood | Very Low (1) | Low (2) | Medium (3) | High (4) | Very High (5) |
|-------------------|--------------|---------|------------|----------|---------------|
| **Critical (5)**  | Medium       | High    | High       | Critical | Critical      |
| **High (4)**      | Low          | Medium  | High       | High     | Critical      |
| **Medium (3)**    | Low          | Low     | Medium     | High     | High          |
| **Low (2)**       | Very Low     | Low     | Low        | Medium   | High          |
| **Very Low (1)**  | Very Low     | Very Low| Low        | Low      | Medium        |

#### Risk Scoring Scale

- **Critical (20-25)**: Immediate action required, senior management escalation
- **High (15-19)**: Urgent attention required, treatment plan within 30 days
- **Medium (10-14)**: Treatment plan required within 90 days
- **Low (5-9)**: Treatment plan required within 180 days
- **Very Low (1-4)**: Monitor and review annually

### Phase 5: Risk Treatment Options

#### Risk Treatment Strategies

For each identified risk, one of the following strategies must be selected:

**Risk Avoidance**:

- Eliminate the risk by discontinuing the risky activity
- Change business processes to avoid risk exposure
- Select alternative technologies or approaches

**Risk Mitigation**:

- Implement security controls to reduce likelihood or impact
- Apply defense-in-depth strategies
- Enhance monitoring and detection capabilities

**Risk Transfer**:

- Purchase cyber insurance coverage
- Outsource risky activities to qualified third parties
- Implement contractual risk transfer mechanisms

**Risk Acceptance**:

- Formally accept residual risk after treatment
- Document business justification for acceptance
- Establish monitoring and review procedures

## Risk Assessment Frequency

### Regular Assessments

- **Annual Comprehensive Assessment**: Complete organizational risk assessment
- **Quarterly Updates**: Review of critical and high risks
- **Monthly Monitoring**: Ongoing threat and vulnerability monitoring
- **Ad-hoc Assessments**: Triggered by significant changes or incidents

### Assessment Triggers

Risk assessments must be conducted when:

- New systems or services are implemented
- Significant changes to existing systems occur
- New threats or vulnerabilities are identified
- Security incidents occur
- Regulatory requirements change
- Business processes are modified
- Third-party relationships are established or changed

## Risk Assessment Documentation

### Risk Register

All identified risks must be documented in the organizational risk register including:

- **Risk ID**: Unique risk identifier
- **Risk Description**: Clear description of the risk scenario
- **Asset**: Affected information asset(s)
- **Threat**: Applicable threat source(s)
- **Vulnerability**: Exploitable vulnerability(ies)
- **Likelihood**: Probability of risk occurrence
- **Impact**: Potential business impact
- **Risk Score**: Calculated risk rating
- **Treatment Strategy**: Selected risk treatment approach
- **Controls**: Implemented or planned security controls
- **Residual Risk**: Risk level after treatment
- **Owner**: Risk owner responsible for management
- **Review Date**: Next scheduled risk review

### Risk Assessment Reports

Each risk assessment produces:

- **Executive Summary**: High-level findings and recommendations
- **Risk Landscape**: Overview of organizational risk profile
- **Critical Risks**: Detailed analysis of critical and high risks
- **Treatment Recommendations**: Prioritized risk treatment plan
- **Resource Requirements**: Estimated resources for risk treatment
- **Timeline**: Implementation schedule for risk treatments

## Roles and Responsibilities

### Risk Assessment Team

- **Risk Manager**: Overall responsibility for risk assessment process
- **Information Security Team**: Technical risk analysis and assessment
- **Business Process Owners**: Asset identification and business impact assessment
- **IT Operations**: Technical vulnerability identification and assessment
- **Legal and Compliance**: Regulatory and legal risk assessment

### Risk Governance

- **Executive Leadership**: Risk appetite and tolerance decisions
- **Risk Committee**: Risk assessment oversight and approval
- **Business Unit Managers**: Risk treatment implementation and monitoring
- **Internal Audit**: Independent risk assessment validation

## Quality Assurance

### Assessment Validation

- **Peer Review**: All risk assessments undergo peer review
- **Independent Validation**: Annual independent risk assessment review
- **Accuracy Verification**: Regular validation of risk data and calculations
- **Consistency Checks**: Ensure consistent application of methodology

### Continuous Improvement

- **Methodology Updates**: Annual review and update of methodology
- **Lessons Learned**: Incorporate feedback from risk incidents
- **Industry Benchmarking**: Compare with industry best practices
- **Tool Enhancement**: Evaluate and improve risk assessment tools

## Training and Competence

### Risk Assessment Training

All risk assessment team members must complete:

- Initial risk assessment methodology training
- Annual refresher training and updates
- Specialized training for specific assessment tools
- Industry threat intelligence briefings

### Competence Requirements

Risk assessors must demonstrate:

- Understanding of business operations and technology
- Knowledge of information security principles and practices
- Familiarity with threat landscape and attack vectors
- Analytical and problem-solving skills
- Communication and documentation abilities

## Integration with ISMS

### ISMS Alignment

Risk assessment results inform:

- **Security Control Selection**: Based on identified risks and requirements
- **Treatment Planning**: Prioritized implementation of security measures
- **Resource Allocation**: Budget and staffing decisions for security programs
- **Performance Monitoring**: KPIs and metrics for risk management effectiveness
- **Management Review**: Regular reporting to senior management

### Continuous Monitoring

Risk assessment supports:

- **Threat Detection**: Enhanced monitoring based on identified risks
- **Incident Response**: Risk-informed incident prioritization and response
- **Change Management**: Risk assessment for all significant changes
- **Compliance Management**: Risk-based compliance monitoring and reporting

## Contact Information

For questions about risk assessment methodology:

**Risk Management Team**: [risk@zanreal.com](mailto:risk@zanreal.com)

**Information Security Team**: [security@zanreal.com](mailto:security@zanreal.com)

**Legal Team**: [legal@zanreal.com](mailto:legal@zanreal.com)

Any concerns and/or complaints arising under or related to this Risk Assessment Methodology should be reported to [legal@zanreal.com](mailto:legal@zanreal.com).

## Previous Versions

The previous versions of our Policies and other documents can be seen at [GitHub](https://github.com/zanreal-labs/legal)
