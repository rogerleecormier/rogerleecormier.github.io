# ☁️ Cloud & DevOps Engineering

I operate at the intersection of product leadership and hands‑on engineering, turning fragmented SaaS ecosystems into automated, audit‑ready pipelines. Across education, fintech, and retail, my projects eliminate manual toil, harden release governance, and surface real‑time insight for hundreds of end‑users — all while keeping compliance teams happy.

---

## 🔧 Core Tooling & Stack

| Domain | Primary Tools & Services |
|--------|--------------------------|
| **Cloud & CI/CD** | Azure Functions, Azure Communication Services, Azure Key Vault, Azure Application Insights, GitHub Actions |
| **Automation & Scripting** | Python, PowerShell, SuiteScript, Power Automate, Batch |
| **SaaS Surface Area** | NetSuite, Vena, Box, Ramp, Checkbook.io, Smartsheet |
| **Environments** | Git-first workflows, serverless architecture, VMware test labs |

---

## 🔁 Portfolio Highlights

### 📦 Box → Vena Serverless ETL
**Stack:** Azure Functions • GitHub Actions • Java ETL • Box API

Replaced a legacy server-based batch script with a cloud-native, serverless pipeline that processes ad hoc financial data files from Box into Vena using a Java-based ETL. The solution includes schema validation, idempotent retry logic, detailed logging with Azure Application Insights, and secret management via Azure Key Vault. Azure Communication Services handles real-time email alerts, and GitHub Actions automates the build and deployment workflow for consistent, version-controlled releases.

- Retired legacy infrastructure, eliminating infrastructure and maintenance overhead
- Cut integration failure rates by 75% via validation, retries, and notifications
- Improved auditability and supportability with structured logs and config-driven design

---

### 🤖 AI-Augmented & Cloud Native Development
**Stack:** GitHub Codespaces • GitHub Copilot • Claude • ChatGPT

Leveraged AI and cloud-based developer environments to optimize backend automation and integration workflows. Used GitHub Codespaces to provision consistent, pre-configured dev environments for rapid iteration on Python and SuiteScript projects. Combined Copilot, Claude, and ChatGPT to scaffold code, debug, and accelerate internal tool development. AI was also used to draft internal documentation, explain API behaviors, and test edge-case scenarios.

- Reduced environment setup time from hours to minutes via Codespaces
- Automated low-level scripting tasks, reclaiming ~100 dev-hours/month
- Accelerated delivery of finance automation tools and CI/CD optimizations

---

### 💳 Finance Ops Orchestration
**Stack:** Oracle NetSuite • SuiteScript • REST APIs

Engineered a NetSuite-native ACH automation that directly integrates with Checkbook.io via REST API, eliminating all manual file uploads and payor selection by AP staff. The legacy process introduced financial risk due to duplicate file submissions and incorrect payor choices—risks that Checkbook.io’s interface could not detect or block. The new customization transmits payment data programmatically from NetSuite, enforces entity-specific rules, and validates GL segments before submission.

- Eliminated duplicate and misrouted ACH payments
- Removed all manual interaction with Checkbook.io's UI
- Implemented GL validation and role-based controls via SuiteScript
- Thoroughly tested in sandbox environments and deployed with AP team training
- Supports 300+ charter school users across multiple entities

---

### 🛠️ Custom Automation Utilities  
**Stack:** Python • Power Automate • SuiteScript • Smartsheet API • Excel XML • Outlook • Microsoft Teams  

Developed lightweight, task-specific automation tools to streamline finance operations, data formatting, and service request handling. These standalone utilities were built to meet precise use-case requirements where no off-the-shelf solution could suffice:

---

#### 🔁 CalPERS XLSX → XML Transformer  
A Python utility that converts the CalPERS pension contribution spreadsheet into a standards-compliant XML document required by county systems.  
*Reduced manual rework, ensured submission compliance, and eliminated formatting errors.*

---

#### 📁 Box-to-Smartsheet Documentation Indexer  
A Python app that recursively scans documentation folders in Box, extracts file metadata, and pushes structured results to a Smartsheet dashboard via REST API.  
*Enabled live inventory tracking of documentation assets across finance and operations.*

---

#### 🧾 NetSuite CSV Data Pipeline for Accounting Reports  
Transforms raw NetSuite-exported CSVs into validated accounting reports, applying custom logic for categorization, GL accuracy, and data cleanup. Final output is auto-formatted for import back into NetSuite.  
*Improved month-end reconciliation speed and reduced human error.*

---

#### 📬 Outlook-to-Smartsheet Ticket Automation (Power Automate)  
Built cloud flows that scan incoming emails in Microsoft Outlook and generate new Smartsheet tickets when they match pre-configured criteria. Includes parsing of email content and assignment rules.  
*Streamlined intake and response time for 300+ support requests monthly.*

---

#### 👥 Onboarding Tracker Integration via Teams & Outlook (Power Automate)  
Created flows that listen for onboarding-related emails or Teams messages, extract key data, and populate SmartSheet onboarding trackers.  
*Improved onboarding SLA adherence and centralized handoff tracking.*

---

### 🖥️ Retail POS Automation at Scale
**Stack:** Python • VBScript • Windows Batch • VMware

Authored 30+ automation scripts to patch Toshiba TCxSky/4690 POS nodes, push zero-day security fixes, and capture forensic logs across 150+ stores. A fleet of 50+ VMware clones mirrors production for pre-rollout validation.

- Field deployment speed up 3×
- Ticket volume down 40%
- First-time-pass installs above 95%

---

## 📈 Measured Impact

- 🕒 **20+ hours/week** of manual integration effort eliminated via Azure Functions    
- 🤖 **100+ hours/month** reclaimed using AI-assisted DevOps tooling  
- 🧾 **300+ users** across 50+ clients onboarded to fully automated finance pipelines
- 🚀 Accelerated deployment cycles via GitHub Actions and repeatable workflows  

---

## 🔑 Skills & Keywords

`Azure Functions`, `GitHub Actions`, `CI/CD Automation`,  
`Python Scripting`, `SuiteScript`, `Power Automate`,  
`Box-Vena ETL`, `AI-Enhanced Development`, `ERP Integration`,  
`VMware Automation`, `POS Rollouts`, `DevOps Tooling`, `Cloud Ops`

---

> **“Velocity without traceability is vanity; true DevOps balances shipped value with defensible compliance.”**

