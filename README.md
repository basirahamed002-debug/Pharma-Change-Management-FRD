# 💊 Change Management Software Module (CMSM)

## 📌 Overview
This repository contains the Functional Requirements and Implementation Plan for a **Change Management Software Module (CMSM)** designed for the pharmaceutical industry.

The system replaces legacy paper-based change control with a **fully digital, GxP-compliant platform**, managing the complete lifecycle of Change Requests (CRs).

---

## 🎯 Objectives

- 🚀 **Efficiency**: Reduce change cycle time by 40%
- ✅ **Compliance**: Ensure 100% audit readiness (21 CFR Part 11)
- ⚠️ **Risk Reduction**: Enforce structured impact & risk assessments

---

## 📜 Compliance Standards

- 21 CFR Part 11  
- ICH Q10  
- EU GMP Annex 11  
- GAMP 5  

---

## ⚙️ Core Features

### 🧾 Change Request (CR) Intake
- Dynamic submission form
- Auto-generated CR ID (CR-YYYY-NNNNN)
- Auto-fill user data (name, department, site)
- File attachments (up to 20 files)

### ⚠️ Risk Assessment
- Automated RPN Calculation (Severity × Probability × Detectability)
- High-risk escalation (RPN > 125)
- GxP impact checklist (Validation, Regulatory, Training)

### ✍️ E-Signatures (21 CFR Part 11)
- Dual authentication (credentials + intent)
- Cryptographic linking of signatures
- Full audit trail tracking

### 🔄 Implementation & Tracking
- Task activation post QA approval
- Evidence-based task completion
- Automatic Effectiveness Review (90 days)

---

## 🚀 Implementation Roadmap (10-Sprint Plan)

| Sprint | Focus Area       | Key Milestones |
|--------|----------------|----------------|
| 1–2    | 🏗️ Foundation   | SSO integration (Azure AD / Okta), CR intake forms |
| 3–4    | ⚙️ Logic Engine | RPN risk matrix, workflow routing engine |
| 5–6    | 📜 Compliance   | 21 CFR Part 11 E-signatures, Gantt tracking |
| 7–8    | 🔗 Connectivity | API integrations (DMS, LMS), dashboards |
| 9–10   | ✅ Validation   | UAT, GAMP 5 validation (IQ/OQ/PQ) |

---

## 🧩 System Modules

- Authentication (SSO)
- Change Request Management
- Risk Engine
- Workflow Engine
- Compliance & Audit Trail
- Dashboard & Reporting
- Integration Layer (DMS/LMS)

---

## 🖥️ UI Mockups

### 📊 Operations Dashboard
- KPI Tiles (Open CRs, Pending Approvals, Regulatory Impact)
- Recent Activity Table
- SLA & Compliance Charts

### 📝 CR Initiation Wizard
- Step-by-step guided form
- Change classification & scope selection
- Technical justification input

### ⚠️ Risk Assessment Screen
- Interactive risk matrix
- RPN auto-calculation
- Impact checklist & mitigation plan

### ✅ Approval Workflow
- Multi-level approval tracking
- E-signature panel
- Real-time audit trail

---

## 🔄 Development Methodology

- Agile (Scrum)
- 2-week sprints
- Continuous validation approach
- Compliance-first architecture

---

## ✅ Validation Approach (GAMP 5)

- **IQ** – Installation Qualification  
- **OQ** – Operational Qualification  
- **PQ** – Performance Qualification  

---

## 📈 Expected Outcome

A **fully validated, audit-ready Change Management System** that:
- Ensures regulatory compliance
- Improves operational efficiency
- Reduces risk in pharmaceutical processes

---

## 📎 Repository Contents

- 📄 FRD Document  
- 🧩 Implementation Plan  
- 🎨 UI Mockups (Conceptual)  

---

## ⭐ Contribution

Feel free to fork, improve, or suggest enhancements.

---

## 📬 Contact

For queries or collaboration, reach out via GitHub.

---

⭐ *Star this repo if you find it useful!*
