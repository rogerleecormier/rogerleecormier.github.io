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

### 📦 Box → Vena Serverless ETL
**Stack:** Azure Functions • GitHub Actions • Java ETL • Box API

Replaced a legacy server-based batch script with a cloud-native, serverless pipeline that processes ad hoc financial data files from Box into Vena using a Java-based ETL. The solution includes schema validation, idempotent retry logic, detailed logging with Azure Application Insights, and secret management via Azure Key Vault. Azure Communication Services handles real-time email alerts, and GitHub Actions automates the build and deployment workflow for consistent, version-controlled releases.

- Retired legacy infrastructure, eliminating infrastructure and maintenance overhead
- Cut integration failure rates by 75% via validation, retries, and notifications
- Improved auditability and supportability with structured logs and config-driven design

---

### 🤖 AI-Augmented & Cloud Native Development  
**Stack:** GitHub Codespaces • GitHub Copilot • Claude Sonnet 3.7 • ChatGPT-4o

Adopted an AI-first engineering workflow to accelerate automation and DevOps delivery. Used **GitHub Codespaces** to launch pre-configured, containerized environments—eliminating setup drift and reducing provisioning time from hours to minutes.

Integrated multiple LLMs to optimize across the pipeline:

- **Claude Sonnet 3.7** (via Copilot Chat and CLI) for multi-step reasoning, YAML/config generation, and API design patterns.
- **ChatGPT-4o** for debugging, Markdown structuring, and parsing ambiguous or undocumented APIs.
- **GitHub Copilot** for in-editor code suggestions, scaffolding utilities, and templating Python, SuiteScript, and PowerShell logic.

AI tools were used across the SDLC—not just to write code, but to reason about it:

- **Code Acceleration**: Cut delivery time of automation scripts and workflows by up to 5×.
- **CI/CD Optimization**: Used LLMs to test, debug, and improve GitHub Actions pipelines.
- **Self-Documenting Systems**: Generated context-aware code comments and developer onboarding docs.
- **Edge-Case Validation**: Simulated logic paths and failure modes before production rollout.

> These practices reclaimed over **100 developer-hours/month** and established AI as a core contributor in my DevOps stack.

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

### 🌐 Portfolio Site 
**Stack:** MkDocs (Material) • Python • GitHub Actions • GitHub Pages • VS Code • GitHub Copilot • ChatGPT • HTML/CSS

Built this portfolio itself as a standalone DevOps project to **“treat documentation like code.”**  
Key architecture points:

| Layer | Detail |
|-------|--------|
| **Static‑site generator** | MkDocs 1.6 + Material 9.x theme |
| **Docs as Code** | Markdown in `docs/`, version‑controlled in Git |
| **Plugins & Enhancements** | `search`, `mkdocs-awesome-nav`, `social`, `admonition`, `pymdown-extensions`, `mdx_math` |
| **CI/CD** | Two GitHub Actions workflows:<br>• **Deploy** – installs deps, runs `mkdocs build`, publishes `site/` to `gh-pages` via **peaceiris/actions-gh-pages**<br>• **pages-build-deployment** – GitHub‑managed final publish step |
| **Hosting** | GitHub Pages with custom domain **rcormier.dev** (DNS via Porkbun) |
| **Authoring** | VS Code with Copilot for YAML/Markdown scaffolding; ChatGPT for structure & copyediting |
| **Performance** | Build under 10 s; output optimized to ~2 MB; instant‑loading navigation via Material’s `navigation.instant` |

**Why it matters:**

- **DevOps for Docs** — PR‑driven content updates with branch previews  
- **Zero servers** — static hosting means no runtime patches or bills  
- **Auditable change history** — every edit is traceable via GitHub  
- **Skill depth** — demonstrates expertise in static‑site generators, HTML/CSS theming, and GitHub Actions YAML orchestration  

---

### 🛠️ Custom Automation Utilities  
**Stack:** Python • Power Automate • SuiteScript • Smartsheet API • Excel XML • Outlook • Teams  

A suite of targeted tools that bridge gaps traditional SaaS vendors leave open:

| Utility | Purpose | Impact |
|---------|---------|--------|
| **CalPERS XLSX → XML Transformer** | Convert pension spreadsheets to county‑standard XML via Python | Eliminated manual re‑entry; ensured compliance |
| **Box → Smartsheet Indexer** | Recursively catalog docs and push metadata to Smartsheet | Real‑time inventory across finance ops |
| **NetSuite CSV Data Pipeline** | Clean & transform exports for accurate re‑import | Faster month‑end close; fewer posting errors |
| **Outlook → Smartsheet Tickets** | Auto‑create tickets from emails with Power Automate | 300 + support requests triaged monthly |
| **Onboarding Tracker Flows** | Populate Smartsheet from Teams/Outlook events | Improved SLA adherence for new hires |


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
- - 🌐 **<10s** static‑site builds, **$0** hosting cost on GitHub Pages  

---

## 🔑 Skills & Keywords

`Azure Functions` · `GitHub Actions` · `CI/CD Automation` · `MkDocs Static‑Site Generator` · `HTML/CSS Theming` ·  
`Python Scripting` · `SuiteScript` · `Power Automate` · `Box‑Vena ETL` · `AI‑Enhanced Development` ·  
`ERP Integration` · `GitHub Pages Hosting` · `VMware LabOps` · `POS Rollouts` · `DevOps Tooling` · `Cloud Ops`

---

> **“Velocity without traceability is vanity; true DevOps balances shipped value with defensible compliance.”**

