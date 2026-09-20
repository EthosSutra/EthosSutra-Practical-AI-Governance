# AI Control Testing

## Document Metadata

| Field | Value |
|-------|-------|
| Document Name | AI Control Testing |
| Project | EthosSutra Enterprise AI Governance Reference Implementation |
| Client | GlobalBank Corporation |
| AI System | GlobalBank Nexus |
| AI System ID | AIS-001 |
| Document Owner | Internal Audit |
| Governance Owner | AI Governance Office |
| Executive Sponsor | Chief Risk Officer |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Effective Date | June 2026 |
| Review Frequency | Quarterly or Following Material Control Changes |

---

# Executive Summary

Enterprise AI Governance controls must operate effectively throughout the AI lifecycle to ensure risks remain within the organization's approved risk appetite.

The AI Control Testing Framework establishes the methodology for validating that governance controls are designed appropriately, implemented correctly and operating effectively.

Unlike the AI Control Library, which documents governance controls, this framework verifies whether those controls consistently achieve their intended objectives through structured testing, evidence collection and independent validation.

The outcome of Control Testing supports governance assurance, regulatory compliance, internal audit and continuous improvement activities.

---

# 1. Purpose

The purpose of this document is to establish a standardized enterprise methodology for testing AI governance controls supporting GlobalBank Nexus.

The framework enables GlobalBank Corporation to:

- Verify control effectiveness.
- Detect control failures.
- Validate governance implementation.
- Produce audit-ready testing evidence.
- Support regulatory compliance.
- Identify remediation opportunities.
- Strengthen enterprise AI assurance.

---

# 2. Scope

This framework applies to governance controls across:

- AI Governance
- AI Risk Management
- Human Oversight
- Data Governance
- Information Security
- Privacy
- AI Lifecycle Management
- Third-Party Governance
- Operations & Monitoring
- Incident Management

---

# 3. Enterprise Control Testing Objectives

## CT-001 — Design Effectiveness

Confirm that each governance control has been designed to adequately mitigate the identified risk.

---

## CT-002 — Operating Effectiveness

Verify that implemented controls operate consistently under normal business conditions.

---

## CT-003 — Compliance Validation

Confirm controls satisfy internal policies and external regulatory obligations.

---

## CT-004 — Evidence Verification

Validate that sufficient operational evidence exists to demonstrate control execution.

---

## CT-005 — Continuous Assurance

Support ongoing governance assurance through recurring control testing activities.

---

## CT-006 — Continuous Improvement

Identify weaknesses and improvement opportunities before governance failures occur.

---

# 4. Enterprise Control Testing Framework

```text
          Control Selected
                 │
                 ▼
      Review Control Design
                 │
                 ▼
      Execute Control Test
                 │
                 ▼
      Collect Test Evidence
                 │
                 ▼
      Evaluate Test Results
                 │
                 ▼
      Pass / Fail Decision
                 │
          ┌──────┴──────┐
          ▼             ▼
       PASS           FAIL
          │             │
          ▼             ▼
 Continue Monitoring  Corrective Action
```

---

# 5. Enterprise Control Testing Types

| Testing Type | Objective | Example |
|--------------|-----------|---------|
| Design Testing | Verify control design is appropriate | Review Human Approval workflow |
| Operating Effectiveness Testing | Confirm control operates consistently | Verify approval records over last 90 days |
| Compliance Testing | Validate regulatory compliance | Review EU AI Act control implementation |
| Technical Testing | Validate technical enforcement | Test RBAC and DLP configurations |
| Evidence Testing | Confirm supporting evidence exists | Review monitoring logs and audit trails |

---

# 6. Enterprise Control Testing Inventory

| Test ID | Control Tested | Testing Method | Frequency | Owner |
|---------|----------------|----------------|-----------|-------|
| CT-001 | AI Governance Policy | Documentation Review | Annual | AI Governance Office |
| CT-002 | AI Risk Assessment | Sample Review | Quarterly | Enterprise Risk Management |
| CT-003 | Human Approval | Workflow Verification | Quarterly | Business Owner |
| CT-004 | Model Validation | Technical Review | Before Release | AI Validation Team |
| CT-005 | Bias Testing | Report Verification | Quarterly | AI Validation Team |
| CT-006 | DLP Enforcement | Configuration Testing | Monthly | Privacy Office |
| CT-007 | RBAC | Access Review | Quarterly | Information Security |
| CT-008 | Vendor Assessment | Documentation Review | Annual | Vendor Risk Management |
| CT-009 | Monitoring Controls | Dashboard Verification | Monthly | AI Operations |
| CT-010 | Incident Management | Tabletop Exercise | Semi-Annual | AI Operations |

---

# 7. Enterprise Test Result Classification

| Result | Definition | Governance Action |
|---------|------------|-------------------|
| Pass | Control operated effectively | Continue monitoring |
| Pass with Observation | Minor improvement identified | Track improvement |
| Fail | Control ineffective | Immediate remediation |
| Not Tested | Test not completed | Schedule testing |

---

# 8. Control Testing Evidence Requirements

Each control test shall produce sufficient evidence to support audit and governance assurance.

| Evidence Type | Example |
|---------------|---------|
| Screenshots | RBAC configuration |
| Audit Logs | Prompt logging evidence |
| Reports | Bias testing report |
| Approval Records | Human oversight approvals |
| Monitoring Dashboards | Operational KPI evidence |
| Configuration Exports | Security settings |
| Incident Records | Control failure investigations |

---

# 9. Testing Roles & Responsibilities

| Role | Responsibility |
|------|----------------|
| AI Governance Office | Define testing requirements |
| Internal Audit | Independently validate controls |
| Control Owner | Support testing activities |
| AI Operations | Provide operational evidence |
| Information Security | Validate security controls |
| Privacy Office | Validate privacy controls |
| Enterprise Risk Management | Review testing outcomes |

---

# 10. Control Testing Deliverables

Completion of the Control Testing process enables GlobalBank Corporation to produce:

- Control testing reports
- Pass/fail assessments
- Evidence packages
- Remediation plans
- Executive assurance reports
- Audit support documentation
- Inputs to continuous improvement

---

# 11. Enterprise Control Testing Methodology

The Enterprise Control Testing Methodology establishes a standardized process for validating that AI governance controls operate effectively throughout the AI lifecycle.

Unlike one-time implementation reviews, control testing is a recurring assurance activity designed to confirm that governance controls continue to mitigate identified risks under real operating conditions.

Testing results provide evidence for Internal Audit, Regulatory Compliance, AI Governance Committees and Executive Management.

```text
          Enterprise Control Testing Lifecycle

             Select Governance Control
                      │
                      ▼
            Understand Control Objective
                      │
                      ▼
            Review Control Design
                      │
                      ▼
           Execute Testing Procedure
                      │
                      ▼
            Collect Test Evidence
                      │
                      ▼
         Evaluate Operating Effectiveness
                      │
                      ▼
           Record Test Results
                      │
                      ▼
        Remediation (If Required)
                      │
                      ▼
          Governance Assurance Report
```

---

# 12. Enterprise Control Testing Procedure

| Step | Activity | Primary Owner | Evidence Produced |
|------|----------|---------------|-------------------|
| 1 | Select control for testing | Internal Audit | Annual Test Plan |
| 2 | Review control objective | AI Governance Office | Control Specification |
| 3 | Understand implementation | Control Owner | Process Documentation |
| 4 | Execute testing procedure | Internal Audit | Test Working Papers |
| 5 | Collect supporting evidence | Control Owner | Screenshots, Logs, Reports |
| 6 | Evaluate effectiveness | Internal Audit | Test Results |
| 7 | Document observations | Internal Audit | Audit Observation Register |
| 8 | Assign corrective actions | Control Owner | Remediation Plan |
| 9 | Re-test corrected controls | Internal Audit | Validation Report |

---

# 13. How to Perform Enterprise Control Testing

The following guidance illustrates how governance controls should be validated in production environments.

## AI Governance Policy

### Objective

Confirm that governance policies remain approved, communicated and actively used.

### Testing Procedure

- Verify latest policy version.
- Confirm executive approval.
- Review annual review date.
- Confirm policy distribution records.
- Interview governance stakeholders.

### Evidence

- Approved policy
- Version history
- Approval records
- Governance meeting minutes

### Recommended Tools

- Microsoft SharePoint
- Confluence
- ServiceNow GRC

---

## Human Oversight Control

### Objective

Confirm that high-risk AI decisions receive mandatory human review.

### Testing Procedure

- Select a representative sample of AI decisions.
- Verify approval records.
- Confirm no workflow bypass occurred.
- Review escalation records.
- Validate approval timestamps.

### Evidence

- Workflow logs
- Approval history
- Service tickets
- Audit trail

### Recommended Tools

- ServiceNow
- Microsoft Power Automate
- Jira
- Azure DevOps

---

## Role-Based Access Control (RBAC)

### Objective

Verify only authorized personnel can access GlobalBank Nexus.

### Testing Procedure

- Export current user access list.
- Compare permissions against approved roles.
- Identify privileged accounts.
- Review dormant accounts.
- Validate segregation of duties.

### Evidence

- User access reports
- RBAC configuration
- Identity reports
- Access review logs

### Recommended Tools

- Microsoft Entra ID
- Azure Portal
- SailPoint
- CyberArk

---

## Data Loss Prevention (DLP)

### Objective

Validate that sensitive information cannot leave approved environments.

### Testing Procedure

- Trigger a test DLP policy.
- Attempt transmission of sensitive data.
- Verify policy enforcement.
- Confirm alert generation.
- Review incident records.

### Evidence

- DLP alerts
- Policy reports
- Incident tickets
- Audit logs

### Recommended Tools

- Microsoft Purview
- Symantec DLP
- Forcepoint DLP

---

## Prompt Logging

### Objective

Verify prompts and AI responses are recorded for governance and investigations.

### Testing Procedure

- Submit controlled prompts.
- Verify prompt logging.
- Confirm timestamps.
- Validate user attribution.
- Review retention policy.

### Evidence

- Prompt logs
- Response logs
- Log Analytics reports
- Monitoring dashboards

### Recommended Tools

- Azure Monitor
- Azure Log Analytics
- Microsoft Sentinel

---

## AI Monitoring Controls

### Objective

Confirm continuous monitoring identifies operational issues.

### Testing Procedure

- Review monitoring dashboards.
- Validate alert thresholds.
- Generate controlled alerts.
- Confirm incident creation.
- Verify escalation workflow.

### Evidence

- KPI dashboards
- Alert history
- Incident records
- Monitoring reports

### Recommended Tools

- Azure Monitor
- Grafana
- Datadog
- Splunk

---

## Vendor Governance Control

### Objective

Confirm approved suppliers continue meeting governance requirements.

### Testing Procedure

- Review supplier assessment.
- Validate certifications.
- Confirm contract validity.
- Review SLA performance.
- Check annual reassessment.

### Evidence

- Vendor assessment
- ISO certificates
- SLA reports
- Contract review

### Recommended Tools

- ServiceNow VRM
- OneTrust
- RSA Archer

---

# 14. Enterprise Control Testing Schedule

| Control Category | Testing Frequency |
|------------------|-------------------|
| Governance Controls | Annual |
| Human Oversight Controls | Quarterly |
| Security Controls | Quarterly |
| Privacy Controls | Quarterly |
| Monitoring Controls | Monthly |
| Vendor Controls | Annual |
| Incident Controls | Semi-Annual |
| Critical Controls | Continuous Monitoring |

---

# 15. Control Failure Response

If a governance control fails testing:

```text
Control Failure Detected
          │
          ▼
Record Finding
          │
          ▼
Assess Business Impact
          │
          ▼
Assign Control Owner
          │
          ▼
Implement Corrective Action
          │
          ▼
Re-Test Control
          │
          ▼
Close Finding
```

Critical control failures shall be immediately escalated to the AI Governance Committee and Chief Risk Officer.

---

# 16. Recommended Enterprise Testing Tools

| Capability | Recommended Tool | Enterprise Purpose |
|------------|------------------|--------------------|
| GRC Platform | ServiceNow GRC | Manage control inventory, testing schedules and remediation workflows |
| Internal Audit | RSA Archer | Execute audit programs, control testing and assurance reporting |
| Identity Governance | Microsoft Entra ID | Test RBAC, privileged access and segregation of duties |
| Data Protection | Microsoft Purview | Validate DLP controls, data classification and privacy enforcement |
| Security Monitoring | Microsoft Sentinel | Verify security monitoring, alerts and incident response controls |
| Operational Monitoring | Azure Monitor | Validate system health, KPIs and operational alerts |
| Log Analysis | Azure Log Analytics | Review prompt logs, audit trails and telemetry |
| Evidence Repository | SharePoint | Store testing evidence and audit documentation |
| Dashboard & Reporting | Power BI | Executive reporting of testing status and control effectiveness |
| Remediation Tracking | Jira / Azure DevOps | Track findings, corrective actions and re-testing activities |

---

# 17. Control Testing Checklist

## Planning

- ☐ Control selected
- ☐ Control objective reviewed
- ☐ Testing scope defined
- ☐ Test methodology approved

---

## Execution

- ☐ Testing completed
- ☐ Evidence collected
- ☐ Results documented
- ☐ Observations recorded

---

## Validation

- ☐ Pass/Fail determined
- ☐ Findings reviewed
- ☐ Corrective actions assigned
- ☐ Re-testing scheduled (if required)

---

## Reporting

- ☐ Executive summary prepared
- ☐ Evidence archived
- ☐ Dashboard updated
- ☐ Governance Committee informed

---

# 18. Enterprise Best Practices

| Best Practice | Business Value |
|--------------|----------------|
| Test controls using real operational evidence rather than documentation alone | Confirms controls operate effectively in production |
| Combine automated and manual testing techniques | Improves assurance and testing efficiency |
| Validate both control design and operating effectiveness | Provides complete governance assurance |
| Preserve all testing evidence | Supports regulatory inspections and internal audits |
| Integrate testing with continuous monitoring | Detects control degradation earlier |
| Track remediation through formal workflows | Ensures failed controls are corrected and verified |

---

# 19. Lessons Learned

| Observation | Recommendation |
|------------|----------------|
| Controls documented but never tested provide false assurance | Establish recurring testing schedules |
| Automated controls still require periodic validation | Independently verify automated enforcement |
| Evidence quality determines audit confidence | Standardize evidence collection procedures |
| Delayed remediation increases governance risk | Prioritize correction of failed critical controls |
| Control testing should evolve with AI systems | Update test procedures after major model, architecture or regulatory changes |

---

# 20. Executive Control Testing Statement

The AI Control Testing Framework provides GlobalBank Corporation with a standardized approach for validating the effectiveness of governance controls protecting GlobalBank Nexus.

By combining structured testing procedures, evidence-based validation, enterprise tooling and continuous assurance practices, the organization can demonstrate that governance controls operate consistently, effectively and in alignment with business objectives and regulatory expectations.

This document serves as the operational playbook for enterprise AI control testing and supports Internal Audit, Regulatory Compliance, AI Governance and Executive Assurance activities.

---

**End of Document**