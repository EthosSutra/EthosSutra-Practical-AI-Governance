# Enterprise AI Governance Glossary

## Document Metadata

| Field | Value |
|-------|-------|
| Document Name | Enterprise AI Governance Glossary |
| Project | EthosSutra Enterprise AI Governance Reference Implementation |
| Client | GlobalBank Corporation |
| AI System | GlobalBank Nexus |
| Document Owner | AI Governance Office |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Review Frequency | Annual |

---

# Executive Summary

A common governance language is essential for successful enterprise AI governance.

AI Governance brings together professionals from technology, legal, compliance, audit, privacy, cybersecurity, risk management and business operations. Each discipline often uses different terminology, creating inconsistencies that can lead to misunderstandings, governance gaps and implementation risks.

The Enterprise AI Governance Glossary establishes a standardized vocabulary for GlobalBank Corporation, ensuring that governance terminology is interpreted consistently across all phases of the Enterprise AI Governance Framework.

Unlike a traditional dictionary, this glossary explains why each concept matters, where it is applied within the governance program and how it relates to internationally recognized AI governance frameworks.

---

# Purpose

The Enterprise AI Governance Glossary enables GlobalBank Corporation to:

- Establish a common governance language.
- Improve communication across business and technical teams.
- Standardize AI governance terminology.
- Support audit and regulatory consistency.
- Accelerate onboarding of new governance professionals.
- Improve understanding of repository artifacts.

---

# How to Use This Glossary

Each glossary entry contains:

| Section | Description |
|----------|-------------|
| Definition | Plain-language explanation of the term |
| Enterprise Relevance | Why the term is important within an enterprise AI governance program |
| Repository Usage | Where the concept is implemented in this repository |
| Related Standards | Relevant international frameworks or regulations |
| Related Artifacts | Repository documents where the concept is applied |

---

# Glossary Entries

---

# AI Governance

## Definition

The system of policies, processes, organizational structures and controls used to ensure Artificial Intelligence is designed, deployed, operated and monitored responsibly throughout its lifecycle.

## Enterprise Relevance

AI Governance provides executive oversight, accountability and risk management while enabling organizations to deploy AI safely, ethically and in compliance with applicable regulations.

## Repository Usage

Appears throughout every phase of the Enterprise AI Governance Framework.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- AI_Governance_Policy.md
- RACI_Matrix.md
- Internal_Audit_Checklist.md

---

# AI System

## Definition

A software system that uses machine learning, generative AI, rules or other AI techniques to perform tasks that normally require human intelligence.

## Enterprise Relevance

Every AI system must be inventoried, governed and monitored according to enterprise governance requirements.

## Repository Usage

Primary governance subject throughout the repository.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- AI_System_Register.md
- AI_Use_Case_Intake_Form.md

---

# AI Risk

## Definition

The possibility that an AI system may produce outcomes resulting in operational, legal, ethical, financial, security or reputational harm.

## Enterprise Relevance

AI risks must be identified, assessed, mitigated and continuously monitored before and after deployment.

## Repository Usage

Primary focus of Phase 03.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act Article 9

## Related Artifacts

- AI_Risk_Assessment.md
- Risk_Register.md

---

# Human Oversight

## Definition

The ability for qualified individuals to supervise AI outputs, intervene when necessary and override automated decisions to prevent harm.

## Enterprise Relevance

Human Oversight is one of the most important governance controls for high-risk AI systems.

## Repository Usage

Implemented during Phase 05 and operationalized throughout deployment and monitoring.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act Article 14

## Related Artifacts

- Human_Oversight_Plan.md
- RACI_Matrix.md

---

# AI Inventory

## Definition

A centralized register containing information about every AI system operating within the organization.

## Enterprise Relevance

The AI Inventory provides visibility, ownership and governance scope for all enterprise AI systems.

## Repository Usage

Implemented during Phase 02.

## Related Standards

- NIST MAP
- ISO Clause 8
- EU AI Act Article 11

## Related Artifacts

- AI_System_Register.md

---

# AI Lifecycle

## Definition

The complete lifecycle of an AI system from business request and design through deployment, monitoring, retirement and archival.

## Enterprise Relevance

Governance controls apply throughout every lifecycle stage rather than only during development.

## Repository Usage

Referenced throughout repository.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Monitoring_Plan.md
- Validation_Report.md

---

# Risk Appetite

## Definition

The amount and type of AI-related risk that GlobalBank Corporation is willing to accept while pursuing its business objectives.

## Enterprise Relevance

Risk Appetite guides governance decisions by defining acceptable risk boundaries before AI systems are approved for deployment.

## Repository Usage

Used during AI Risk Assessment, Governance Review and Executive Risk Acceptance.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- AI_Risk_Assessment.md
- Risk_Register.md

---

# Residual Risk

## Definition

The level of risk that remains after governance controls and mitigation measures have been implemented.

## Enterprise Relevance

Residual Risk determines whether an AI system can be approved for production or requires additional controls.

## Repository Usage

Evaluated during Risk Assessments and Executive Risk Reviews.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001

## Related Artifacts

- Risk_Register.md
- AI_Risk_Assessment.md

---

# Model Card

## Definition

A structured document describing an AI model's purpose, architecture, limitations, performance characteristics and intended use.

## Enterprise Relevance

Model Cards improve transparency and support governance, audit and regulatory compliance.

## Repository Usage

Created during Phase 05.

## Related Standards

- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Model_Card.md

---

# Data Sheet

## Definition

Documentation describing datasets used for training, validation and operation of AI systems.

## Enterprise Relevance

Data Sheets improve transparency regarding data quality, origin, limitations and governance.

## Repository Usage

Used during Data Governance and Model Documentation.

## Related Standards

- EU AI Act Article 10
- ISO/IEC 42001

## Related Artifacts

- Data_Sheet.md

---

# Bias

## Definition

Systematic unfairness that causes AI systems to produce inaccurate or discriminatory outcomes for particular individuals or groups.

## Enterprise Relevance

Bias can create legal, ethical and reputational risks requiring continuous testing and mitigation.

## Repository Usage

Validated during AI Testing and Model Validation.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Bias_Testing_Report.md

---

# Hallucination

## Definition

A response generated by an AI model that appears credible but contains fabricated, inaccurate or unsupported information.

## Enterprise Relevance

Hallucinations introduce operational, legal and customer trust risks, particularly within enterprise AI assistants.

## Repository Usage

Assessed during Validation and Monitoring.

## Related Standards

- NIST AI RMF

## Related Artifacts

- Validation_Report.md
- Monitoring_Plan.md

---

# Prompt Injection

## Definition

A security attack in which malicious instructions manipulate an AI model into ignoring intended safeguards or revealing unauthorized information.

## Enterprise Relevance

Prompt Injection represents one of the highest operational risks for enterprise Generative AI systems.

## Repository Usage

Evaluated during Security Testing and Red Team exercises.

## Related Standards

- NIST AI RMF
- EU AI Act

## Related Artifacts

- Security_Testing_Report.md
- Robustness_Testing_Report.md

---

# Explainability

## Definition

The ability to understand and communicate how an AI system produced a particular output or recommendation.

## Enterprise Relevance

Explainability improves trust, accountability and regulatory compliance.

## Repository Usage

Considered during Model Validation and Human Oversight.

## Related Standards

- NIST AI RMF
- EU AI Act

## Related Artifacts

- Model_Card.md
- Human_Oversight_Plan.md

---

# Traceability

## Definition

The capability to trace governance activities, decisions, risks, controls and evidence throughout the AI lifecycle.

## Enterprise Relevance

Traceability enables audit readiness, regulatory compliance and effective investigations.

## Repository Usage

Implemented across governance documentation and audit evidence.

## Related Standards

- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Audit_Evidence_Mapping.md
- Internal_Audit_Checklist.md

---

# Governance Control

## Definition

A policy, process or technical safeguard implemented to reduce AI-related risk and ensure governance objectives are achieved.

## Enterprise Relevance

Governance Controls form the operational foundation of enterprise AI Governance.

## Repository Usage

Designed, tested and audited throughout the repository.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Control_Library.md
- Control_Testing.md

---

# Audit Evidence

## Definition

Objective information demonstrating that governance controls have been implemented and are operating effectively.

## Enterprise Relevance

Audit Evidence supports internal audits, certification activities and regulatory inspections.

## Repository Usage

Collected continuously throughout governance operations.

## Related Standards

- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- Audit_Evidence_Mapping.md
- Internal_Audit_Checklist.md

---

# AI Governance Committee

## Definition

A cross-functional decision-making body responsible for overseeing enterprise AI Governance.

## Enterprise Relevance

The committee provides executive oversight, governance approvals and strategic direction.

## Repository Usage

Referenced throughout governance, risk management and audit phases.

## Related Standards

- ISO/IEC 42001
- NIST AI RMF

## Related Artifacts

- AI_Governance_Policy.md
- RACI_Matrix.md

---

# Artificial Intelligence Management System (AIMS)

## Definition

A structured management system established in accordance with ISO/IEC 42001 for governing AI throughout its lifecycle.

## Enterprise Relevance

The AIMS integrates governance, leadership, operational controls, performance evaluation and continual improvement into one management framework.

## Repository Usage

Established during Regulatory Alignment.

## Related Standards

- ISO/IEC 42001

## Related Artifacts

- ISO_IEC_42001_Mapping.md

---

# Red Teaming

## Definition

A structured assessment technique that simulates adversarial attacks against AI systems to identify security weaknesses, unsafe behaviors and governance gaps.

## Enterprise Relevance

Red Teaming validates AI resilience before deployment and during production operations.

## Repository Usage

Performed during Validation and Security Assurance.

## Related Standards

- NIST AI RMF
- EU AI Act

## Related Artifacts

- Security_Testing_Report.md
- Robustness_Testing_Report.md

---

# Responsible AI

## Definition

The practice of designing, developing, deploying and governing AI systems in a manner that is ethical, lawful, transparent, safe and accountable.

## Enterprise Relevance

Responsible AI represents the strategic objective of the Enterprise AI Governance Program.

## Repository Usage

Referenced throughout every governance phase.

## Related Standards

- NIST AI RMF
- ISO/IEC 42001
- EU AI Act

## Related Artifacts

- AI_Governance_Policy.md
- Cross_Framework_Matrix.md

---

# End of Glossary