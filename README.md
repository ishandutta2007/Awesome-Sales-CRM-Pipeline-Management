# Awesome-Sales-CRM-Pipeline-Management

# Awesome Sales CRM & Pipeline Management

> A curated list of top Sales CRM and Pipeline Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing leads, deals, and sales pipelines from first contact to closed-won.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Salesforce Sales Cloud](#salesforce-sales-cloud)
  - [HubSpot Sales Hub](#hubspot-sales-hub)
  - [Pipedrive](#pipedrive)
  - [Freshsales](#freshsales)
  - [Zoho CRM](#zoho-crm)
  - [Close](#close)
  - [Copper](#copper)
  - [Nutshell](#nutshell)
- [Open-Source Software](#-open-source-software)
  - [EspoCRM](#espocrm)
  - [Twenty](#twenty)
  - [Odoo CRM](#odoo-crm)
  - [Frappe CRM](#frappe-crm)
  - [SuiteCRM](#suitecrm)
  - [Hermit CRM](#hermit-crm)
  - [amagi-crm](#amagi-crm)
  - [OpenCRM (clawnify)](#opencrm-clawnify)
  - [RealTimeX CRM](#realtimex-crm)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Sales CRM and Pipeline Management platforms. These are not open-source but are included as reference points for feature comparison.

### Salesforce Sales Cloud
**Type:** Enterprise CRM standard with deep customization
Salesforce Sales Cloud is the long-standing enterprise standard, offering lead and opportunity management, forecasting, territory management, and extensive customization through its metadata-driven architecture. It is the benchmark against which all other CRMs are measured, with a vast ecosystem of apps and integrations. Pricing scales significantly with features and user count.

### HubSpot Sales Hub
**Type:** CRM-integrated sales engagement and pipeline
HubSpot Sales Hub combines deal pipeline management with sequences, email tracking, meeting scheduling, and CRM integration. It offers a free tier for basic pipeline management, with paid tiers adding automation and advanced reporting. Best suited for organizations already using HubSpot's marketing or service tools.

### Pipedrive
**Type:** Visual pipeline-first sales CRM
Pipedrive is built around the visual sales pipeline, with drag-and-drop deal stages that make it immediately intuitive for small sales teams. It focuses on activity-based selling with reminders and next-step prompts. Pricing is per-seat with tiered plans.

### Freshsales
**Type:** Unified CRM with built-in telephony and AI
Freshsales (part of Freshworks) provides contact and deal management with built-in cloud telephony, live chat, and Freddy AI for lead scoring. It is positioned as an accessible alternative to enterprise suites for mid-market organizations.

### Zoho CRM
**Type:** Budget-friendly CRM with broad feature set
Zoho CRM offers a free edition for 3 users, with paid tiers adding scoring rules, sales forecasting, Blueprint process design, and anomaly detection [from previous context]. It integrates with the broader Zoho suite and is a strong value choice for SMBs.

### Close
**Type:** Sales CRM with built-in calling and SMS
Close is designed for inside sales teams, combining pipeline management with built-in calling, SMS, and email sequences. It emphasizes speed and efficiency for high-volume outbound sales.

### Copper
**Type:** CRM built for Google Workspace
Copper integrates natively with Gmail and Google Workspace, automatically capturing emails and contacts. Its pipeline management is designed for teams that live in Gmail rather than wanting a separate CRM interface.

### Nutshell
**Type:** Sales CRM with email automation
Nutshell provides pipeline management, contact management, and sales automation for small to mid-sized teams. It includes email sequences and reporting to help teams close more deals.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Sales CRM and Pipeline Management tools. The open-source ecosystem spans **mature enterprise platforms**, **modern developer-friendly CRMs**, and **niche CLI-driven tools**.

### EspoCRM
**Stack:** PHP / MySQL/PostgreSQL | **License:** AGPL-3.0
EspoCRM is one of the most complete open-source CRMs, with a clean user interface and powerful in-app administration that lets you customize fields, layouts, workflows, and dashboards without writing code [citation:2][citation:9][citation:11]. It covers leads, contacts, opportunities, marketing campaigns, support cases, and a calendar with Google/Outlook sync [citation:2]. The Entity Manager adds custom entities and relationships. A REST API connects it to other systems. **Trade-off:** The codebase is large with home-made backend and frontend frameworks, making deep code customization challenging despite the complete API [citation:11]. Docker deployment is available for quick setup [citation:9].
**Best for:** Organizations wanting a proven, feature-rich CRM with strong out-of-the-box administration and a complete API, accepting a large codebase and AGPL licensing.

### Twenty
**Stack:** TypeScript / NestJS / React / PostgreSQL | **License:** AGPL-3.0 (core)
Twenty is a modern open-source CRM positioned as a developer-friendly alternative to Salesforce, with a clean SaaS-like interface and modular architecture [citation:12]. Version 2.0 added **AI integration via MCP** (Model Context Protocol), allowing external AI clients like Claude to access CRM data via OAuth-secured interfaces [citation:12]. The SDK was split into subpaths, reducing bundle size by a factor of 700 for serverless environments. OAuth now mandates PKCE for security. Supports custom objects, pipelines, and GraphQL API. **Trade-off:** Some enterprise features are under a commercial license; the core is AGPL-3.0.
**Best for:** Developer-friendly teams wanting a modern, extensible CRM with AI agent integration and a path away from Salesforce/HubSpot.

### Odoo CRM
**Stack:** Python / PostgreSQL / OWL JS | **License:** LGPL-3.0 (Community)
Odoo CRM is part of the broader Odoo ERP suite, covering sales pipelines, lead management, email integration, and reporting [citation:11]. It is consistently ranked as a top open-source CRM in 2026 comparisons [citation:7]. The Community edition is free; Enterprise adds advanced features and support. **Trade-off:** Odoo is a behemoth covering every business function, with a huge codebase that typically requires specialized Odoo developers. Best for organizations wanting CRM integrated with a full ERP suite [citation:11].
**Best for:** Organizations wanting CRM integrated with finance, inventory, and manufacturing, particularly those already using or planning to adopt Odoo.

### Frappe CRM
**Stack:** Python / Frappe Framework / Vue | **License:** GPL-3.0
Frappe CRM is a modern CRM built on the Frappe framework (same ecosystem as ERPNext), providing lead and deal management, email integration, telephony, and a customizable desk interface [from previous context]. It is ranked among the top open-source CRMs in 2026 [citation:7]. The Frappe ecosystem offers a path to ERPNext for organizations wanting integrated ERP and CRM in one stack.
**Best for:** Teams already in or considering the Frappe/ERPNext ecosystem, wanting CRM integrated with broader business operations.

### SuiteCRM
**Stack:** PHP / MySQL/MariaDB | **License:** AGPL-3.0
SuiteCRM is the successor to SugarCRM Community Edition, offering enterprise-class CRM with sales automation, marketing automation, workflow, and reporting [citation:11]. It has a large user base and rich plugin ecosystem. **Trade-off:** The codebase is old with outdated coding practices and a dated UI, making it less suitable for simple CRM needs or modern development [citation:11]. Ranked #2 in one 2026 open-source CRM comparison [citation:7].
**Best for:** Organizations with existing SuiteCRM expertise or specific legacy requirements, wanting a feature-rich platform despite technical debt.

### Hermit CRM
**Stack:** Python / Markdown / Git | **License:** Open Source
Hermit CRM is a **file-based, Git-native CRM** where every company, contact, and interaction is stored as a Markdown file, with Git providing history and audit [citation:5]. It features a pipeline board with customizable stages, a follow-up radar for unanswered threads, tasks, a calendar, and an **MCP server** for AI assistant access. A bookmarklet turns web pages into filled-in forms. **Trade-off:** It is a CLI-driven tool with no traditional web UI (though it has a local server mode); best suited for technical founders comfortable with Git workflows [citation:5].
**Best for:** Technical founders and small teams wanting a Git-native, file-based CRM with full data ownership and AI assistant access, without a database or SaaS dependency.

### amagi-crm
**Stack:** Python / SQLite or PostgreSQL | **License:** Open Source
amagi-crm is a CLI-first CRM that runs on SQLite with one command or PostgreSQL via Docker [citation:4]. Features include a deal pipeline board with stage totals, contact import from CSV with dry-run and duplicate detection, and an **audit chain with cryptographic verification** (`amagi-crm audit verify`). Encrypted fields require backing up the `.env` file, as lost keys mean unrecoverable data [citation:4].
**Best for:** Technical users and small teams wanting a lightweight, CLI-driven CRM with SQLite simplicity and cryptographic audit trails.

### OpenCRM (clawnify)
**Stack:** SQLite / REST API | **License:** Open Source
OpenCRM (clawnify) is a lightweight HubSpot alternative for SaaS, managing contacts, companies, and deals with custom attributes, relations, and a REST API [citation:13]. It supports custom field definitions and relation columns, with flexible filtering operators for list endpoints. Positioned for developers wanting a simple, API-first CRM foundation.
**Best for:** SaaS teams wanting a minimal, API-driven CRM with custom fields and relations, accepting a lighter feature set than enterprise platforms.

### RealTimeX CRM
**Stack:** React / TypeScript / Supabase | **License:** MIT
RealTimeX CRM is a fork of Atomic CRM with **"Bring Your Own Database"** configuration via Supabase [citation:8]. Features include contact organization, tasks, notes, email capture (CC the CRM), a Kanban deal pipeline, import/export, OAuth login (Google, Azure, Keycloak, Auth0), and API integration. Deploys via CLI (`npx create-realtimex-crm`) or manual clone. Customization requires TypeScript/React skills [citation:8].
**Best for:** Developer teams wanting a React-based CRM they can fully customize and connect to their own Supabase instance, accepting the technical setup requirements.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Pipeline Board | Custom Fields | AI/MCP | Self-Hosted | Best For |
|----------|---------|-------|----------------|---------------|--------|-------------|----------|
| **Salesforce** | Proprietary | Cloud | ✅ | ✅ Deep | (Einstein) | ❌ | Enterprise customization |
| **HubSpot** | Proprietary | Cloud | ✅ | ✅ | (Breeze) | ❌ | CRM + marketing integration |
| **Pipedrive** | Proprietary | Cloud | ✅ Visual | ✅ | ❌ | ❌ | Sales-first pipeline |
| **EspoCRM** | AGPL-3.0 | PHP/MySQL | ✅ | ✅ Entity Manager | ❌ | ✅ | Feature-complete OSS CRM |
| **Twenty** | AGPL-3.0 | TypeScript | ✅ | ✅ | ✅ MCP | ✅ | Modern developer CRM |
| **Odoo CRM** | LGPL-3.0 | Python/Postgres | ✅ | ✅ | (AI) | ✅ | ERP-integrated CRM |
| **Frappe CRM** | GPL-3.0 | Python/Frappe | ✅ | ✅ | ❌ | ✅ | ERPNext ecosystem |
| **SuiteCRM** | AGPL-3.0 | PHP/MySQL | ✅ | ✅ | ❌ | ✅ | Feature-rich legacy |
| **Hermit CRM** | Open Source | Python/Markdown | ✅ | ✅ | ✅ MCP | ✅ | Git-native + AI |
| **amagi-crm** | Open Source | Python/SQLite | ✅ Stage totals | (Check) | ❌ | ✅ | CLI + audit trail |
| **RealTimeX** | MIT | React/Supabase | ✅ Kanban | ✅ | ❌ | ✅ | Customizable React CRM |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Sales CRM or Pipeline Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem offers strong options across the spectrum: **EspoCRM** for a feature-complete, administration-rich platform with a complete API [citation:11], **Twenty** for a modern developer-friendly CRM with MCP-based AI integration [citation:12], **Odoo CRM** for ERP-integrated sales management [citation:11], and **Hermit CRM** for a Git-native, file-based approach with full data ownership [citation:5]. For teams wanting the simplest possible self-hosted setup, **amagi-crm** runs on a single SQLite file with cryptographic audit trails [citation:4].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
