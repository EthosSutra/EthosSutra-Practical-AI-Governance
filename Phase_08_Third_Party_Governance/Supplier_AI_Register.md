# Supplier AI Register

## Document Metadata

| Field             | Value                                                        |
| ----------------- | ------------------------------------------------------------ |
| Document Name     | Supplier AI Register                                         |
| Project           | EthosSutra Enterprise AI Governance Reference Implementation |
| Client            | GlobalBank Corporation                                       |
| AI System         | GlobalBank Nexus                                             |
| AI System ID      | AIS-001                                                      |
| Document Owner    | Vendor Risk Management Team                                  |
| Governance Owner  | AI Governance Lead                                           |
| Executive Sponsor | Chief Risk Officer                                           |
| Version           | 1.0                                                          |
| Classification    | Internal                                                     |
| Status            | Approved                                                     |
| Effective Date    | June 2026                                                    |
| Review Frequency  | Quarterly or Upon Material Supplier Change                   |

---

# Executive Summary

GlobalBank Nexus depends on multiple third-party AI and technology suppliers to deliver enterprise AI capabilities including foundation model access, embedding generation, vector search, observability, monitoring, security, privacy controls and cloud infrastructure.

The Supplier AI Register provides the authoritative inventory of all external suppliers, platforms, services and third-party AI dependencies supporting GlobalBank Nexus.

This register enables GlobalBank Corporation to identify supplier relationships, understand dependency criticality, assess AI-related third-party exposure and support downstream due diligence, vendor assessment, contract review and third-party risk management activities.

This document is not a vendor risk assessment. It is the inventory foundation that enables vendor risk assessment.

---

# 1. Purpose

The purpose of the Supplier AI Register is to maintain a centralized record of all third-party suppliers involved in the design, deployment, operation, monitoring or governance of GlobalBank Nexus.

The register enables GlobalBank Corporation to:

* Identify all external AI dependencies.
* Classify supplier roles and services.
* Track supplier ownership and accountability.
* Support AI vendor due diligence.
* Enable third-party AI risk assessment.
* Maintain visibility of critical AI supply chain dependencies.
* Support audit readiness and regulatory review.

---

# 2. Scope

This register applies to all third-party suppliers supporting GlobalBank Nexus, including:

* Foundation model providers.
* Embedding model providers.
* Cloud AI platforms.
* Vector database providers.
* AI observability platforms.
* AI evaluation platforms.
* AI security testing tools.
* Data governance platforms.
* Privacy and DLP platforms.
* Monitoring and logging platforms.
* Incident management platforms.
* External consultants and managed service providers supporting AI operations.

Internal GlobalBank teams are excluded unless they manage third-party AI services on behalf of the enterprise.

---

# 3. Supplier AI Register Principles

## SUP-PR-001 — Complete Supplier Visibility

Every third-party AI supplier supporting GlobalBank Nexus shall be recorded in the Supplier AI Register.

---

## SUP-PR-002 — Dependency Transparency

The register shall identify the business, technical and governance dependency created by each supplier.

---

## SUP-PR-003 — Risk-Based Classification

Suppliers shall be classified based on criticality, data access, AI impact and operational dependency.

---

## SUP-PR-004 — Continuous Maintenance

The Supplier AI Register shall be reviewed quarterly and updated whenever a supplier, service, integration or risk profile materially changes.

---

## SUP-PR-005 — Downstream Traceability

Each supplier record shall link to vendor due diligence, vendor assessment, contract review and third-party risk records where applicable.

---

# 4. Supplier Classification Model

| Supplier Class               | Description                                          | Example                                          |
| ---------------------------- | ---------------------------------------------------- | ------------------------------------------------ |
| Foundation Model Provider    | Provides Large Language Model capability             | OpenAI, Anthropic, Google, AWS, Microsoft        |
| Cloud AI Platform            | Hosts AI services, APIs or model infrastructure      | Azure AI, AWS Bedrock, Google Vertex AI          |
| Embedding Provider           | Generates vector embeddings for retrieval            | OpenAI Embeddings, Cohere Embed                  |
| Vector Database Provider     | Stores and retrieves vectorized enterprise content   | Pinecone, Weaviate, Milvus                       |
| AI Observability Provider    | Monitors prompts, responses and model behaviour      | LangSmith, Arize, WhyLabs                        |
| AI Evaluation Provider       | Supports model, prompt and response validation       | DeepEval, Promptfoo, Azure AI Foundry Evaluation |
| AI Security Provider         | Supports adversarial testing and AI threat detection | Garak, PyRIT, Lakera                             |
| Data Governance Provider     | Supports classification, lineage and data controls   | Microsoft Purview, Collibra                      |
| Privacy & DLP Provider       | Detects and protects sensitive information           | Microsoft Purview DLP, Presidio                  |
| Incident Management Provider | Supports incident lifecycle and remediation tracking | ServiceNow, Jira                                 |

---

# 5. Enterprise Supplier AI Register

| Supplier ID | Supplier Name                | Supplier Class               | Service / Capability                             | Criticality | Status | Business Owner     |
| ----------- | ---------------------------- | ---------------------------- | ------------------------------------------------ | ----------- | ------ | ------------------ |
| SUP-001     | Microsoft                    | Cloud AI Platform            | Enterprise cloud AI services and monitoring      | Critical    | Active | CTO Office         |
| SUP-002     | Foundation Model Provider    | Foundation Model Provider    | Large Language Model API                         | Critical    | Active | AI Engineering     |
| SUP-003     | Embedding Model Provider     | Embedding Provider           | Text embedding generation                        | High        | Active | AI Engineering     |
| SUP-004     | Vector Database Provider     | Vector Database Provider     | Semantic retrieval and vector storage            | High        | Active | Data Engineering   |
| SUP-005     | AI Observability Provider    | AI Observability Provider    | Prompt, trace and response monitoring            | Medium      | Active | AI Operations      |
| SUP-006     | AI Evaluation Tool Provider  | AI Evaluation Provider       | AI quality, robustness and regression testing    | Medium      | Active | AI Validation Team |
| SUP-007     | Data Governance Platform     | Data Governance Provider     | Data classification, lineage and DLP             | High        | Active | Chief Data Office  |
| SUP-008     | Incident Management Platform | Incident Management Provider | Incident workflow and corrective action tracking | Medium      | Active | AI Operations      |

---

# 6. Supplier Dependency Matrix

| Supplier ID | Dependency Type          | Dependency Description                                    | Impact if Unavailable                 |
| ----------- | ------------------------ | --------------------------------------------------------- | ------------------------------------- |
| SUP-001     | Platform Dependency      | Hosts AI infrastructure, monitoring and security services | Critical AI service disruption        |
| SUP-002     | Model Dependency         | Provides language model capability                        | AI response generation unavailable    |
| SUP-003     | Embedding Dependency     | Converts enterprise content into embeddings               | New content cannot be indexed         |
| SUP-004     | Retrieval Dependency     | Stores vector index for enterprise search                 | RAG retrieval degraded or unavailable |
| SUP-005     | Observability Dependency | Provides prompt and response traceability                 | Reduced monitoring visibility         |
| SUP-006     | Validation Dependency    | Supports AI testing and regression evaluation             | Reduced validation automation         |
| SUP-007     | Governance Dependency    | Provides classification and DLP controls                  | Increased data governance risk        |
| SUP-008     | Operational Dependency   | Supports incident response workflow                       | Incident handling may be delayed      |

---

# 7. Supplier Criticality Rating

| Criticality | Definition                                                                             | Governance Requirement                                |
| ----------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| Critical    | Supplier failure may materially disrupt GlobalBank Nexus or create regulatory exposure | Full due diligence, executive approval, annual review |
| High        | Supplier failure may degrade AI performance, security, privacy or governance           | Full due diligence and periodic review                |
| Medium      | Supplier supports operational efficiency but is not mission-critical                   | Standard due diligence                                |
| Low         | Supplier provides non-critical support capability                                      | Basic supplier review                                 |

---

# 8. AI Data Access Classification

| Supplier ID | Data Access Level | Data Type Processed                               | Data Residency Consideration             |
| ----------- | ----------------- | ------------------------------------------------- | ---------------------------------------- |
| SUP-001     | High              | Logs, telemetry, infrastructure metadata          | Regional hosting required                |
| SUP-002     | Medium            | User prompts and retrieved context where approved | Contractual processing controls required |
| SUP-003     | Medium            | Enterprise text content for embeddings            | Approved processing region required      |
| SUP-004     | High              | Vectorized enterprise knowledge                   | Enterprise-controlled access required    |
| SUP-005     | Medium            | Prompt traces and response logs                   | Sensitive logging controls required      |
| SUP-006     | Low               | Test prompts and synthetic validation outputs     | Synthetic data preferred                 |
| SUP-007     | High              | Enterprise data classification metadata           | Internal governance controls required    |
| SUP-008     | Medium            | Incident records and operational evidence         | Access controls required                 |

---

# 9. Supplier Governance Status

| Supplier ID | Due Diligence Required | Vendor Assessment Required | Contract Review Required | Risk Register Required |
| ----------- | :--------------------: | :------------------------: | :----------------------: | :--------------------: |
| SUP-001     |           Yes          |             Yes            |            Yes           |           Yes          |
| SUP-002     |           Yes          |             Yes            |            Yes           |           Yes          |
| SUP-003     |           Yes          |             Yes            |            Yes           |           Yes          |
| SUP-004     |           Yes          |             Yes            |            Yes           |           Yes          |
| SUP-005     |           Yes          |             Yes            |            Yes           |       Conditional      |
| SUP-006     |           Yes          |         Conditional        |        Conditional       |       Conditional      |
| SUP-007     |           Yes          |             Yes            |            Yes           |           Yes          |
| SUP-008     |           Yes          |         Conditional        |            Yes           |       Conditional      |

---

# 10. Supplier Integration Inventory

| Supplier ID | Integration Type     | Integration Point                       | Authentication Method      | Monitoring Required |
| ----------- | -------------------- | --------------------------------------- | -------------------------- | :-----------------: |
| SUP-001     | Cloud Platform       | AI infrastructure and monitoring        | Enterprise IAM             |         Yes         |
| SUP-002     | API                  | Foundation model endpoint               | API key / managed identity |         Yes         |
| SUP-003     | API                  | Embedding generation endpoint           | API key / managed identity |         Yes         |
| SUP-004     | Database Connector   | Vector retrieval layer                  | Service identity           |         Yes         |
| SUP-005     | SDK / API            | Prompt tracing and observability        | Service token              |         Yes         |
| SUP-006     | CI/CD / CLI          | Validation and regression testing       | Service credentials        |         Yes         |
| SUP-007     | Platform Integration | Data classification and DLP             | Enterprise IAM             |         Yes         |
| SUP-008     | Workflow Integration | Incident tickets and corrective actions | Enterprise SSO             |         Yes         |

---

# 11. Supplier Risk Indicators

| Indicator                     | Description                                     | Review Frequency          |
| ----------------------------- | ----------------------------------------------- | ------------------------- |
| Service Availability          | Supplier uptime and reliability                 | Monthly                   |
| Security Certification Status | ISO 27001, SOC 2 or equivalent status           | Annual                    |
| Subprocessor Changes          | Changes to downstream service providers         | Quarterly                 |
| Data Residency Changes        | Changes to data processing locations            | Quarterly                 |
| Model Behaviour Changes       | Changes to model performance or outputs         | Upon notification         |
| Contractual Changes           | SLA, audit rights or liability changes          | Upon renewal or amendment |
| Incident History              | Supplier-related incidents or outages           | Quarterly                 |
| Regulatory Exposure           | Supplier exposure to AI regulatory requirements | Annual                    |

---

# 12. Supplier Ownership Matrix

| Role                   | Responsibility                                           |
| ---------------------- | -------------------------------------------------------- |
| Business Owner         | Confirms business need for supplier use                  |
| AI Governance Lead     | Ensures supplier aligns with AI governance requirements  |
| Vendor Risk Management | Performs supplier risk oversight                         |
| Procurement            | Manages commercial onboarding and supplier records       |
| Legal                  | Reviews contractual terms and obligations                |
| Information Security   | Reviews security posture and certifications              |
| Privacy Office         | Reviews privacy and data protection obligations          |
| AI Engineering         | Reviews technical integration and operational dependency |
| AI Operations          | Monitors supplier performance and operational incidents  |

---

# 13. Supplier Review Workflow

```text
             New AI Supplier Identified
                        │
                        ▼
              Register Supplier in SUP Register
                        │
                        ▼
               Determine Supplier Criticality
                        │
                        ▼
             Perform Vendor Due Diligence
                        │
                        ▼
              Complete Vendor Assessment
                        │
                        ▼
              Complete Contract Review
                        │
                        ▼
             Record Third-Party Risks
                        │
                        ▼
              Governance Approval
                        │
                        ▼
              Ongoing Supplier Monitoring
```

---

# 14. Recommended Enterprise Tools

| Capability           | Recommended Tool                 | Enterprise Purpose                                  |
| -------------------- | -------------------------------- | --------------------------------------------------- |
| Vendor Inventory     | ServiceNow VRM, Archer, OneTrust | Maintain supplier inventory and risk workflow       |
| Procurement Workflow | Coupa, SAP Ariba                 | Supplier onboarding and commercial approval         |
| Contract Management  | Ironclad, DocuSign CLM, Icertis  | Contract review, renewal and obligation tracking    |
| Security Review      | SecurityScorecard, Bitsight      | External security posture monitoring                |
| Data Governance      | Microsoft Purview, Collibra      | Data classification, lineage and privacy evidence   |
| AI Observability     | LangSmith, Arize                 | Monitor third-party AI behaviour and output quality |
| Issue Tracking       | Jira, Azure DevOps               | Track supplier remediation actions                  |
| Executive Reporting  | Power BI                         | Vendor risk dashboards and governance reporting     |

---

# 15. Supplier Evidence Register

| Evidence ID | Evidence                        | Owner                      |
| ----------- | ------------------------------- | -------------------------- |
| SE-001      | Supplier AI Register            | Vendor Risk Management     |
| SE-002      | Supplier Criticality Assessment | Vendor Risk Management     |
| SE-003      | Vendor Due Diligence Record     | Procurement                |
| SE-004      | Vendor Assessment Report        | AI Governance              |
| SE-005      | Contract Review Checklist       | Legal                      |
| SE-006      | Security Review Evidence        | Information Security       |
| SE-007      | Privacy Review Evidence         | Privacy Office             |
| SE-008      | Third-Party Risk Register Entry | Enterprise Risk Management |

---

# 16. Supplier Register Maintenance

The Supplier AI Register shall be reviewed and updated under the following conditions:

* New AI supplier introduced.
* Existing supplier service materially changes.
* Supplier gains access to new data categories.
* Supplier criticality changes.
* Contract terms materially change.
* Supplier experiences a material outage or incident.
* Regulatory obligations change.
* Annual or quarterly vendor review cycle occurs.

---

# 17. Implementation Checklist

## Supplier Onboarding

* ☐ Supplier identified.
* ☐ Supplier added to Supplier AI Register.
* ☐ Supplier class assigned.
* ☐ Supplier criticality assessed.
* ☐ Business owner assigned.
* ☐ Data access classification completed.
* ☐ Due diligence requirement confirmed.
* ☐ Vendor assessment initiated.
* ☐ Contract review initiated.
* ☐ Risk register entry created where required.

---

## Supplier Review

* ☐ Supplier status reviewed.
* ☐ Data access validated.
* ☐ Security certification reviewed.
* ☐ Privacy obligations reviewed.
* ☐ Service availability reviewed.
* ☐ Incident history reviewed.
* ☐ Contract obligations reviewed.
* ☐ Risk rating updated.
* ☐ Governance approval recorded.

---

# 18. Enterprise Best Practices

| Best Practice                                             | Business Value                                |
| --------------------------------------------------------- | --------------------------------------------- |
| Maintain a complete register of all AI suppliers          | Prevents hidden third-party AI exposure       |
| Classify suppliers by AI criticality and data access      | Enables risk-based governance                 |
| Link supplier records to due diligence and risk registers | Strengthens audit traceability                |
| Review supplier changes continuously                      | Detects emerging third-party risk             |
| Include AI-specific supplier categories                   | Improves visibility of modern AI dependencies |
| Assign clear supplier ownership                           | Improves accountability and remediation speed |

---

# 19. Lessons Learned

| Observation                                                         | Recommendation                                        |
| ------------------------------------------------------------------- | ----------------------------------------------------- |
| AI systems often depend on more suppliers than initially documented | Map the full technical and operational supply chain   |
| Foundation model providers create unique governance risks           | Apply enhanced due diligence to model providers       |
| Vector databases may store sensitive enterprise knowledge           | Classify vector stores as high-risk data dependencies |
| Observability tools may capture sensitive prompts and responses     | Apply privacy and logging controls                    |
| Supplier inventory must be continuously updated                     | Integrate supplier updates into AI change management  |

---

# 20. Supplier Register Statement

The Supplier AI Register provides GlobalBank Corporation with a centralized and auditable inventory of all third-party AI suppliers supporting GlobalBank Nexus.

By documenting supplier roles, dependencies, data access, criticality, integration points and governance requirements, this register enables risk-based supplier oversight and strengthens the enterprise AI governance framework.

This document serves as the foundational artifact for vendor due diligence, vendor assessment, third-party risk management and contractual governance activities.

---

**End of Document**
