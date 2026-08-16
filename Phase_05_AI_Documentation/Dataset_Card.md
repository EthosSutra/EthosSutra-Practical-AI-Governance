# Dataset Card

## Document Metadata

| Field            | Value                                                        |
| ---------------- | ------------------------------------------------------------ |
| Document Name    | Dataset Card                                                 |
| Project          | EthosSutra Enterprise AI Governance Reference Implementation |
| Client           | GlobalBank Corporation                                       |
| AI System        | GlobalBank Nexus                                             |
| AI System ID     | AIS-001                                                      |
| Dataset Name     | GlobalBank Enterprise Knowledge Repository                   |
| Dataset ID       | DS-001                                                       |
| Dataset Type     | Enterprise RAG Knowledge Base                                |
| Document Owner   | Chief Data Officer                                           |
| Technical Owner  | Enterprise Data Engineering Lead                             |
| Governance Owner | AI Governance Lead                                           |
| Version          | 1.0                                                          |
| Classification   | Internal                                                     |
| Status           | Approved                                                     |
| Review Frequency | Quarterly or Upon Material Change                            |

---

# 1. Executive Summary

The GlobalBank Enterprise Knowledge Repository is the governed dataset used by GlobalBank Nexus to support enterprise knowledge retrieval, document summarization, policy guidance and AI-assisted decision support.

This dataset is not used to train the foundation model. It is used as a controlled retrieval source within the Retrieval-Augmented Generation architecture of GlobalBank Nexus.

The purpose of this Dataset Card is to document the dataset architecture, source systems, ingestion pipeline, metadata structure, access controls, quality metrics, data risks and governance traceability associated with DS-001.

---

# 2. Dataset Architecture

```text
Approved Enterprise Sources
        │
        ▼
Data Ingestion Layer
        │
        ▼
Validation and Classification
        │
        ▼
Metadata Extraction
        │
        ▼
Chunking Pipeline
        │
        ▼
Embedding Generation
        │
        ▼
Vector Store
        │
        ▼
Retrieval Engine
        │
        ▼
GlobalBank Nexus Response Generation
```

---

# 3. Enterprise Data Source Inventory

| Source ID | Source System               | Content Type                   | Owner                | Classification          | Refresh Frequency | Connector Type     |
| --------- | --------------------------- | ------------------------------ | -------------------- | ----------------------- | ----------------- | ------------------ |
| SRC-001   | Policy Repository           | Policies and standards         | Compliance           | Internal / Confidential | Weekly            | API                |
| SRC-002   | Knowledge Management Portal | Knowledge articles             | Operations           | Internal                | Daily             | Search Connector   |
| SRC-003   | Procedure Library           | SOPs and process guides        | Business Operations  | Internal                | Weekly            | Document Connector |
| SRC-004   | Risk Repository             | Risk and control documentation | Risk Management      | Confidential            | Monthly           | API                |
| SRC-005   | Governance Repository       | AI governance artifacts        | AI Governance Office | Internal                | Monthly           | Repository Sync    |

---

# 4. Dataset Composition

| Attribute       | Description                                                                       |
| --------------- | --------------------------------------------------------------------------------- |
| Dataset Format  | Structured and unstructured enterprise documents                                  |
| Primary Content | Policies, SOPs, knowledge articles, governance documents and operational guidance |
| Language        | English                                                                           |
| Data Volume     | Medium enterprise knowledge corpus                                                |
| Update Method   | Controlled ingestion from approved sources                                        |
| Usage Pattern   | Retrieval grounding for AI-generated responses                                    |
| Training Use    | Not used for foundation model training                                            |
| Retrieval Use   | Used for RAG-based enterprise response generation                                 |

---

# 5. Metadata Schema

| Metadata Field     | Purpose                                         | Required |
| ------------------ | ----------------------------------------------- | -------- |
| Document ID        | Unique source document identifier               | Yes      |
| Source System      | Originating enterprise repository               | Yes      |
| Business Owner     | Accountable business function                   | Yes      |
| Classification     | Information classification                      | Yes      |
| Version            | Document version                                | Yes      |
| Effective Date     | Date document became active                     | Yes      |
| Review Date        | Scheduled content review date                   | Yes      |
| Access Group       | Authorized user group                           | Yes      |
| Retention Category | Records retention requirement                   | Yes      |
| Embedding Status   | Indicates whether the document has been indexed | Yes      |

---

# 6. Ingestion and Processing Pipeline

| Stage                | Activity                                         | Control                 |
| -------------------- | ------------------------------------------------ | ----------------------- |
| Source Selection     | Identify approved enterprise repositories        | Data Owner approval     |
| Data Extraction      | Extract documents through approved connectors    | Secure connector access |
| Classification Check | Validate information classification              | DG-014                  |
| PII Screening        | Detect sensitive personal information            | DLP control             |
| Metadata Extraction  | Capture ownership, version and access attributes | Metadata validation     |
| Chunking             | Split content into retrievable segments          | Chunking standard       |
| Embedding            | Generate semantic embeddings                     | Embedding success check |
| Indexing             | Store embeddings in vector store                 | Index validation        |
| Retrieval Testing    | Validate retrieval quality                       | Test query set          |

---

# 7. Chunking Strategy

| Parameter                    | Standard                                         |
| ---------------------------- | ------------------------------------------------ |
| Chunking Method              | Semantic section-based chunking                  |
| Target Chunk Size            | 500–1,000 tokens                                 |
| Overlap                      | 10–15% where context continuity is required      |
| Header Preservation          | Required                                         |
| Source Citation Preservation | Required                                         |
| Sensitive Data Handling      | Restricted content excluded or access-controlled |
| Chunk Refresh                | Triggered when source document changes           |

---

# 8. Embedding and Vector Index Strategy

| Component         | Description                                        |
| ----------------- | -------------------------------------------------- |
| Embedding Scope   | Approved enterprise knowledge content              |
| Embedding Refresh | Triggered by source updates                        |
| Vector Store      | Enterprise-approved vector database                |
| Access Control    | Enforced before retrieval                          |
| Index Validation  | Required after ingestion                           |
| Failed Embeddings | Logged and remediated                              |
| Retrieval Filters | Classification, role, source and business function |

---

# 9. Data Classification Matrix

| Classification    | AI Retrieval Use           | Approval Required       | Handling Requirement                   |
| ----------------- | -------------------------- | ----------------------- | -------------------------------------- |
| Public            | Permitted                  | No                      | Standard retrieval                     |
| Internal          | Permitted                  | No                      | Enterprise access controls             |
| Confidential      | Restricted                 | Business Owner approval | RBAC, logging and monitoring           |
| Highly Restricted | Prohibited unless approved | CDO and CISO approval   | Explicit governance exception required |

---

# 10. Access Control Matrix

| User Group            |           Public |         Internal |     Confidential | Highly Restricted |
| --------------------- | ---------------: | ---------------: | ---------------: | ----------------: |
| General Employees     |              Yes |              Yes |               No |                No |
| Operations Teams      |              Yes |              Yes |          Limited |                No |
| Risk Management       |              Yes |              Yes |              Yes |                No |
| Compliance            |              Yes |              Yes |              Yes |           Limited |
| Internal Audit        |              Yes |              Yes |              Yes |           Limited |
| AI Governance Office  |              Yes |              Yes |              Yes |           Limited |
| System Administrators | Technical Access | Technical Access | Technical Access |   No Business Use |

---

# 11. Data Quality Metrics

| Metric                    |                    Target | Current Status   |
| ------------------------- | ------------------------: | ---------------- |
| Metadata Completeness     |                     ≥ 95% | On Track         |
| Document Freshness        | ≥ 90% within review cycle | On Track         |
| Duplicate Content Rate    |                      ≤ 5% | Monitored        |
| Failed Embedding Rate     |                      ≤ 2% | Monitored        |
| Retrieval Relevance Score |                     ≥ 85% | Under Validation |
| Broken Source Links       |                0 Critical | Monitored        |
| Classification Coverage   |                      100% | Required         |
| Access Control Coverage   |                      100% | Required         |

---

# 12. Dataset Risk Matrix

| Risk ID | Dataset Risk                                      | Impact | Control                                     |
| ------- | ------------------------------------------------- | ------ | ------------------------------------------- |
| DSR-001 | Outdated policy content retrieved by AI           | High   | Refresh schedule and review date validation |
| DSR-002 | Confidential data retrieved by unauthorized user  | High   | RBAC and retrieval filtering                |
| DSR-003 | Poor metadata reduces retrieval accuracy          | Medium | Metadata completeness monitoring            |
| DSR-004 | Duplicate content creates inconsistent responses  | Medium | Duplicate detection                         |
| DSR-005 | Restricted data included in embeddings            | High   | Classification check and DLP screening      |
| DSR-006 | Source document removed but vector remains active | High   | Index synchronization control               |

---

# 13. Dataset Lineage

| Lineage Stage   | Record Maintained                                     |
| --------------- | ----------------------------------------------------- |
| Source Creation | Source document owner and version                     |
| Source Approval | Business approval and publication status              |
| Ingestion       | Connector, ingestion date and batch ID                |
| Processing      | Classification, metadata and chunking status          |
| Embedding       | Embedding timestamp and success status                |
| Indexing        | Vector index location and retrieval status            |
| Retrieval       | User query, retrieved source and access authorization |
| Response        | Source citation and generated output reference        |

---

# 14. Dataset Monitoring

| Monitoring Area              | Frequency  | Owner                |
| ---------------------------- | ---------- | -------------------- |
| Source refresh status        | Weekly     | Data Engineering     |
| Metadata completeness        | Weekly     | Data Governance      |
| Classification accuracy      | Monthly    | Data Governance      |
| Access control effectiveness | Monthly    | Information Security |
| Retrieval relevance          | Monthly    | AI Engineering       |
| Failed ingestion jobs        | Daily      | Data Engineering     |
| DLP exceptions               | Continuous | Information Security |
| Dataset risk review          | Quarterly  | AI Governance Office |

---

# 15. Governance Traceability

| Dataset Element     | Linked Artifact                      |
| ------------------- | ------------------------------------ |
| AI System           | System Card                          |
| Model Dependency    | Model Card                           |
| Data Handling Rules | Data Handling Guidelines             |
| Risk Controls       | AI Risk Assessment and Risk Register |
| Human Review        | Human Oversight Plan                 |
| Change Updates      | AI Change Management                 |
| Audit Evidence      | Future Audit Evidence Repository     |
| Monitoring          | Future Monitoring Plan               |

---

# 16. Retention and Disposal

| Data Element     | Retention Rule                                          |
| ---------------- | ------------------------------------------------------- |
| Source Documents | According to enterprise records schedule                |
| Metadata Records | Retained while source remains active                    |
| Embeddings       | Deleted when source document is retired                 |
| Ingestion Logs   | Retained for audit period                               |
| Retrieval Logs   | Retained according to monitoring and audit requirements |
| Access Logs      | Retained according to security logging policy           |

---

# 17. Related Documents

* System_Card.md
* Model_Card.md
* AI_Decision_Log.md
* Data_Handling_Guidelines.md
* AI_Risk_Assessment.md
* Risk_Register.md
* AI_Change_Management.md
* Human_Oversight_Plan.md

---

# 18. Dataset Ownership

| Field               | Value                              |
| ------------------- | ---------------------------------- |
| Dataset Owner       | Chief Data Officer                 |
| Technical Custodian | Enterprise Data Engineering Lead   |
| Governance Owner    | AI Governance Lead                 |
| Security Reviewer   | Chief Information Security Officer |
| Business Owners     | Source-specific business functions |
| Review Frequency    | Quarterly or Upon Material Change  |

---

# Revision History

| Version | Date      | Author     | Description                                |
| ------- | --------- | ---------- | ------------------------------------------ |
| 1.0     | June 2026 | EthosSutra | Initial technical Dataset Card for DS-001. |

---

# Dataset Statement

The GlobalBank Enterprise Knowledge Repository is a governed enterprise dataset supporting AI-assisted knowledge retrieval for GlobalBank Nexus.

Its trustworthiness depends on controlled ingestion, accurate metadata, strong access controls, reliable classification, monitored retrieval quality and continuous governance oversight.

This Dataset Card serves as the authoritative technical and governance reference for DS-001.

---

**End of Document**
