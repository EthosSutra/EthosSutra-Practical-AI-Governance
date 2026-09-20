# Third-Party AI Risk Register

## Document Metadata

| Field | Value |
|-------|-------|
| Document Name | Third-Party AI Risk Register |
| Project | EthosSutra Enterprise AI Governance Reference Implementation |
| Client | GlobalBank Corporation |
| AI System | GlobalBank Nexus |
| AI System ID | AIS-001 |
| Document Owner | Enterprise Risk Management |
| Governance Owner | AI Governance Lead |
| Executive Sponsor | Chief Risk Officer |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Effective Date | June 2026 |
| Review Frequency | Quarterly or Upon Material Supplier Change |

---

# Executive Summary

The adoption of external AI suppliers introduces operational, technical, regulatory and strategic risks that remain throughout the supplier lifecycle, even after successful onboarding and vendor approval.

Unlike internal AI risks, third-party AI risks originate from external organizations that develop, operate or support AI services used by GlobalBank Nexus.

This Third-Party AI Risk Register provides a centralized repository for identifying, assessing, monitoring and mitigating residual risks associated with AI suppliers throughout their contractual relationship.

The register supports continuous third-party governance, executive oversight and regulatory compliance while enabling proactive risk management across the enterprise AI supply chain.

---

# 1. Purpose

The purpose of this document is to establish a structured register for managing residual risks associated with third-party AI suppliers.

The register enables GlobalBank Corporation to:

- Identify supplier-related AI risks.
- Assess likelihood and business impact.
- Assign accountable risk owners.
- Track mitigation activities.
- Monitor residual risk over time.
- Support enterprise risk reporting.
- Produce audit-ready governance evidence.

---

# 2. Scope

This register applies to all external AI suppliers supporting GlobalBank Nexus, including:

- Foundation model providers
- Cloud AI platforms
- Embedding model providers
- Vector database providers
- AI observability platforms
- AI evaluation platforms
- AI security vendors
- Data governance platforms
- Managed AI services
- Third-party APIs
- External implementation partners

---

# 3. Third-Party Risk Management Objectives

GlobalBank Corporation establishes the following objectives.

## TPR-001 — Supplier Risk Visibility

Maintain complete visibility of AI supplier risks throughout the supplier lifecycle.

---

## TPR-002 — Risk-Based Decision Making

Prioritize mitigation activities based on business impact and residual risk exposure.

---

## TPR-003 — Continuous Monitoring

Monitor supplier risks continuously rather than only during onboarding.

---

## TPR-004 — Regulatory Assurance

Demonstrate effective management of third-party AI risks during internal and external audits.

---

## TPR-005 — Operational Resilience

Reduce operational disruption resulting from supplier failures or service degradation.

---

## TPR-006 — Continuous Improvement

Review supplier risks regularly and update mitigation strategies as suppliers, technologies and regulations evolve.

---

# 4. Enterprise Third-Party AI Risk Framework

```text
        AI Supplier Approved
                │
                ▼
     Identify Residual Risks
                │
                ▼
     Assess Likelihood & Impact
                │
                ▼
      Calculate Risk Rating
                │
                ▼
     Define Risk Treatment Plan
                │
                ▼
      Assign Risk Ownership
                │
                ▼
    Continuous Supplier Monitoring
                │
                ▼
      Periodic Risk Reassessment
```

---

# 5. Enterprise Third-Party AI Risk Categories

| Risk Category | Description | Example |
|--------------|-------------|---------|
| Operational Risk | Supplier service disruption affecting AI availability | Cloud platform outage |
| AI Model Risk | Changes in model behaviour or quality | Foundation model update changes responses |
| Security Risk | Supplier cyber compromise or API abuse | Compromised API credentials |
| Privacy Risk | Exposure of customer or enterprise information | Cross-border data transfer |
| Compliance Risk | Supplier fails to satisfy regulatory obligations | Loss of certification |
| Commercial Risk | Vendor lock-in or licensing changes | Unexpected pricing increase |
| Financial Risk | Supplier financial instability | Bankruptcy or acquisition |
| Technical Risk | API changes or service incompatibility | Deprecated API version |

---

# 6. Enterprise Third-Party AI Risk Register

| Risk ID | Risk Description | Supplier | Likelihood | Impact | Inherent Risk | Mitigation Strategy | Residual Risk | Risk Owner |
|---------|------------------|----------|------------|--------|---------------|--------------------|---------------|------------|
| TPR-001 | Foundation model behaviour changes after vendor update | Foundation Model Provider | Medium | High | High | Version pinning and regression testing before deployment | Medium | AI Engineering |
| TPR-002 | Vendor outage interrupts AI services | Cloud AI Platform | Medium | High | High | Multi-region deployment and failover strategy | Medium | AI Operations |
| TPR-003 | Prompt data processed outside approved jurisdiction | Foundation Model Provider | Low | High | Medium | Regional processing and contractual controls | Low | Privacy Office |
| TPR-004 | Vector database unavailable | Vector Database Provider | Medium | Medium | Medium | Backup indexes and recovery procedures | Low | Data Engineering |
| TPR-005 | AI observability platform unavailable | AI Observability Provider | Low | Medium | Low | Secondary monitoring and log retention | Low | AI Operations |
| TPR-006 | Supplier security breach | Cloud AI Platform | Low | Critical | High | Continuous security monitoring and incident notification clauses | Medium | Information Security |
| TPR-007 | API rate limits exceeded | Foundation Model Provider | Medium | Medium | Medium | Request throttling and capacity planning | Low | AI Engineering |
| TPR-008 | Vendor lock-in limits migration options | Foundation Model Provider | High | Medium | High | Multi-model architecture and abstraction layer | Medium | Enterprise Architecture |

---

# 7. Residual Risk Summary

| Residual Risk Level | Number of Risks | Governance Action |
|---------------------|----------------:|-------------------|
| Critical | 0 | Immediate Executive Review |
| High | 2 | Monthly Governance Review |
| Medium | 4 | Quarterly Risk Review |
| Low | 2 | Standard Monitoring |

---

# 8. Third-Party Risk Ownership Matrix

| Risk Category | Primary Owner | Supporting Function |
|--------------|---------------|---------------------|
| AI Governance | AI Governance Lead | Enterprise Risk Management |
| Operational | AI Operations | Platform Engineering |
| Technical | AI Engineering | Enterprise Architecture |
| Security | Information Security | AI Security Team |
| Privacy | Privacy Office | Legal |
| Commercial | Procurement | Vendor Risk Management |
| Compliance | Compliance Office | Internal Audit |

---

# 9. Risk Review Triggers

The Third-Party AI Risk Register shall be reviewed whenever one or more of the following events occur:

| Trigger Event | Required Action |
|--------------|-----------------|
| New AI supplier onboarded | Perform initial risk assessment |
| Foundation model version changes | Reassess AI model risks |
| Major supplier outage | Update operational risk assessment |
| Security incident involving supplier | Review security and privacy risks |
| Regulatory changes | Reassess compliance obligations |
| Contract renewal | Revalidate commercial and operational risks |
| Annual vendor review | Perform full risk reassessment |

---

# 10. Risk Register Deliverables

Implementation of the Third-Party AI Risk Register enables GlobalBank Corporation to produce:

- Enterprise third-party AI risk inventory
- Residual risk register
- Supplier risk trend reports
- Executive risk dashboards
- Risk treatment plans
- Governance committee reporting
- Audit-ready supplier risk evidence
- Inputs to enterprise risk management

---
# 11. Enterprise Third-Party Risk Management Methodology

The Enterprise Third-Party Risk Management Methodology establishes a standardized process for identifying, assessing, treating and continuously monitoring risks associated with external AI suppliers supporting GlobalBank Nexus.

The methodology aligns vendor governance activities with Enterprise Risk Management (ERM), Information Security, Privacy, Procurement and AI Governance to ensure third-party AI risks remain within GlobalBank Corporation's approved risk appetite.

```text
        Enterprise Third-Party Risk Lifecycle

         Third-Party AI Supplier Approved
                      │
                      ▼
            Identify Residual Risks
                      │
                      ▼
        Assess Likelihood & Business Impact
                      │
                      ▼
           Calculate Risk Rating
                      │
                      ▼
        Select Risk Treatment Strategy
                      │
                      ▼
         Assign Risk Owner & Actions
                      │
                      ▼
      Continuous Supplier Monitoring
                      │
                      ▼
      Periodic Risk Reassessment
                      │
                      ▼
     Governance Committee Reporting
```

---

# 12. Enterprise Third-Party Risk Assessment Procedure

| Step | Activity | Primary Owner | Evidence Produced |
|------|----------|---------------|-------------------|
| 1 | Review supplier assessment results | Vendor Risk Management | Assessment Review |
| 2 | Identify residual risks | Enterprise Risk Team | Risk Identification Log |
| 3 | Evaluate likelihood and business impact | AI Governance | Risk Assessment Worksheet |
| 4 | Assign inherent and residual risk ratings | Enterprise Risk Management | Risk Register |
| 5 | Define treatment strategy | Risk Owner | Treatment Plan |
| 6 | Assign accountable owner | Business Owner | Ownership Register |
| 7 | Establish monitoring frequency | AI Governance | Monitoring Schedule |
| 8 | Report risks to Governance Committee | Chief Risk Office | Risk Dashboard |
| 9 | Reassess risks periodically | Enterprise Risk Management | Updated Risk Register |

---

# 13. Enterprise Risk Scoring Model

Each identified third-party AI risk shall be evaluated using a standardized enterprise scoring methodology.

## Likelihood Scale

| Score | Description |
|------:|-------------|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost Certain |

---

## Business Impact Scale

| Score | Description |
|------:|-------------|
| 1 | Insignificant |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Severe |

---

## Risk Calculation

```text
Risk Score

=

Likelihood × Impact
```

---

## Risk Rating Matrix

| Risk Score | Risk Rating | Required Action |
|------------|-------------|-----------------|
| 1–5 | Low | Standard monitoring |
| 6–10 | Medium | Quarterly review |
| 11–15 | High | Management action required |
| 16–25 | Critical | Executive escalation and immediate mitigation |

---

# 14. Enterprise Risk Treatment Strategy

Every identified third-party AI risk shall have a documented treatment approach.

| Treatment Strategy | Description | Example |
|--------------------|-------------|---------|
| Avoid | Remove the source of risk | Do not onboard the supplier |
| Reduce | Implement mitigating controls | Introduce additional monitoring or contractual safeguards |
| Transfer | Shift financial or contractual responsibility | Cyber insurance or contractual indemnification |
| Accept | Formally accept residual risk | Executive risk acceptance for low-impact risks |

---

# 15. Continuous Vendor Monitoring Framework

Third-party AI risks do not end after onboarding.

Critical suppliers shall be continuously monitored throughout the supplier lifecycle.

| Monitoring Activity | Frequency | Owner |
|---------------------|-----------|-------|
| SLA performance review | Monthly | AI Operations |
| Security certification validation | Annual | Information Security |
| AI model change notifications | Continuous | AI Engineering |
| Privacy and data processing review | Quarterly | Privacy Office |
| Regulatory compliance review | Annual | Compliance Team |
| Incident and outage review | As Occurred | Vendor Risk Management |
| Contract performance review | Annual | Procurement |

---

# 16. Recommended Enterprise Risk Management Tools

| Capability | Recommended Tool | Enterprise Purpose |
|------------|------------------|--------------------|
| Third-Party Risk Management | ServiceNow VRM | End-to-end supplier risk lifecycle management |
| Enterprise Risk Management | RSA Archer | Centralized risk register and governance reporting |
| Security Risk Monitoring | SecurityScorecard / Bitsight | External cyber posture monitoring |
| Data Governance | Microsoft Purview | Data protection and compliance monitoring |
| Operational Monitoring | Azure Monitor | Monitor availability of AI platform dependencies |
| Vendor Performance Reporting | Power BI | Executive supplier risk dashboards |
| Contract Management | Icertis / Ironclad | Monitor contractual obligations and renewal dates |
| Collaboration | Microsoft Teams | Cross-functional risk reviews and governance meetings |

---

# 17. Third-Party Risk Review Checklist

## Governance

- ☐ Residual risks reviewed
- ☐ Risk owners assigned
- ☐ Risk acceptance documented
- ☐ Governance approval obtained

---

## Security

- ☐ Security certifications remain valid
- ☐ Recent incidents reviewed
- ☐ Vulnerability disclosures assessed
- ☐ Security monitoring active

---

## Privacy

- ☐ Data residency unchanged
- ☐ Data processing agreement remains valid
- ☐ Prompt retention practices verified
- ☐ Privacy incidents reviewed

---

## Operations

- ☐ SLA achieved
- ☐ Service availability reviewed
- ☐ Vendor support performance assessed
- ☐ Disaster recovery commitments validated

---

## Commercial

- ☐ Contract remains active
- ☐ Licensing model reviewed
- ☐ Vendor financial health reviewed
- ☐ Exit strategy remains viable

---

# 18. Enterprise Best Practices

| Best Practice | Business Value |
|--------------|----------------|
| Treat supplier risks as ongoing governance activities rather than one-time assessments | Improves long-term resilience |
| Reassess critical suppliers after major AI model or platform changes | Detects emerging AI risks |
| Link supplier risks to enterprise risk appetite | Supports consistent governance decisions |
| Maintain complete traceability from supplier inventory to risk treatment | Strengthens audit readiness |
| Establish contractual rights to audit critical suppliers | Improves supplier accountability |
| Define exit strategies for critical AI suppliers | Reduces vendor lock-in and business disruption |

---

# 19. Lessons Learned

| Observation | Recommendation |
|------------|----------------|
| AI supplier risks evolve continuously | Implement continuous monitoring rather than annual reviews alone |
| Foundation model providers can change behaviour without notice | Require change notification processes and regression testing |
| Vendor lock-in increases strategic risk over time | Design multi-vendor or portable architectures where feasible |
| Third-party incidents can quickly become enterprise incidents | Integrate supplier risk monitoring with Incident Management |
| Strong governance requires cross-functional ownership | Involve Procurement, Security, Privacy, AI Governance and Business stakeholders throughout the supplier lifecycle |

---

# 20. Executive Third-Party Risk Statement

The Third-Party AI Risk Register establishes GlobalBank Corporation's enterprise framework for managing residual risks associated with external AI suppliers supporting GlobalBank Nexus.

By combining structured risk assessment, standardized treatment strategies, continuous supplier monitoring and executive governance oversight, the organization can maintain operational resilience while reducing regulatory, security, privacy and business risks introduced by third-party AI services.

This document serves as both an enterprise third-party risk management playbook and an audit-ready governance artifact supporting Vendor Risk Management, Enterprise Risk Management, Procurement and AI Governance.

---

**End of Document**