<h2 align="left">
  Hi, I'm <strong>Ziroh Katana Mae</strong><br/>
  <sub>Senior Software Engineer specializing in Fintech, ISP Automation & Enterprise Systems. I build scalable payment infrastructure, billing systems, and API-driven platforms across African markets.</sub>
</h2>

<p align="left">
 Software Engineer & Systems Architect focused on payment systems, ISP infrastructure, and enterprise SaaS platforms. Experienced in building high-volume, production-grade systems in fintech and telecom environments.
</p>
<p align="left">
Founder & Senior Software Engineer building fintech, ISP billing, and enterprise automation systems for African markets. Specializing in scalable APIs, payment reconciliation, and distributed system design.
</p>
<p align="left">
  <a href="https://www.linkedin.com/in/ziroh-katana-24b23ba9/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ezems.developers@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://youtube.com/@zirohmae" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  <a href="https://www.facebook.com/ezemstech" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
</p>

---

## Engineering impact

| Metric | Result |
|--------|--------|
| 💳 Monthly transaction volume | $500K+ processed via M-Pesa integrations |
| 🌐 ISP subscribers managed | 15,000+ across 3 providers |
| ⚡ Manual processing time reduced | 85% via intelligent automation |
| 🏢 SME clients on ERP platform | 50+ across Kenya |
| 📱 Automated customer interactions | 100,000+/month via WhatsApp + SMS + Email |

---

## Featured projects

### 🏦 M-Pesa Payment Integration System

> Enterprise-grade payment engine — event-driven architecture, async queue processing, and automated reconciliation for high-volume African fintech systems.

**Stack:** `Laravel` · `PHP` · `Redis` · `MySQL` · `M-Pesa Daraja API` · `Laravel Horizon`

---

## 🏗 Architecture Overview

- **Payment API Layer**
  Handles STK Push, C2B, B2C, STK Query, and balance inquiry operations through Safaricom Daraja API with real-time status tracking.

- **Webhook Ingestion Layer**
  Secure, idempotent webhook handlers with signature validation and Redis-based deduplication to guarantee exactly-once processing.

- **Queue Processing System**
  Redis-backed async worker pool processes all payment events outside request cycle with retry logic and dead-letter queue handling.

- **Transaction Ledger**
  Immutable financial record system with audit-grade logs and double-entry-compatible transaction structure.

- **Reconciliation Engine**
  Nightly automated matching of Safaricom statements against internal ledger with anomaly detection and dispute flagging.

---

## 📊 Production Impact

- 💳 10,000+ transactions processed monthly  
- ⏱ Reconciliation time reduced: 4 hours → 15 minutes  
- 💰 $500K+ monthly transaction volume processed  
- 🤖 Fully automated dispute resolution pipeline  
- 🔁 Zero duplicate transaction incidents in production  

---

## ⚙️ Key Engineering Outcomes

- Built exactly-once payment processing system using Redis locks + idempotent webhooks  
- Designed event-driven architecture separating API layer from payment processing logic  
- Implemented fault-tolerant queue system with retry, backoff, and dead-letter handling  
- Automated reconciliation pipeline eliminating manual financial verification work  
- Achieved production-grade fintech reliability under real transaction load  

---

### 🌐 ISP Management & Billing Platform

> End-to-end ISP operations platform — subscriber lifecycle management, real-time bandwidth control via MikroTik RouterOS API, RADIUS authentication, and M-Pesa-driven automated billing.

**Stack:** `PHP` · `MikroTik RouterOS API` · `React` · `TypeScript` · `FreeRADIUS` · `MySQL` · `SMS Gateway`

---

## 🏗 Architecture Highlights

- **RouterOS API Integration**
  Enables real-time bandwidth throttling, PPPoE session management, and hotspot user provisioning from a single unified admin interface.

- **FreeRADIUS Authentication Layer**
  Handles subscriber authentication and accounting with custom attribute mapping per package tier, ensuring accurate session tracking and policy enforcement.

- **Billing Engine**
  Supports dynamic package pricing, prorated renewals, and automated suspension/reactivation triggered instantly via M-Pesa payment callbacks.

- **Multi-Tenant Architecture**
  ISP-level isolation with per-tenant router configuration separation and subscriber namespace isolation to ensure data security and scalability across multiple providers.

---

## 📊 Production Impact

- 👥 5,000+ active subscribers managed across 3 ISPs  
- 🎯 99.8% billing accuracy achieved  
- 🤖 100% automation of suspension and reactivation workflows  
- 📡 3 ISP providers running on a single platform (multi-tenant system)  
- ⚡ Real-time bandwidth policy enforcement via RouterOS API  

---

## 🔐 Key Engineering Outcomes

- Eliminated manual ISP suspension processes through event-driven billing automation  
- Reduced billing inconsistencies to near-zero using reconciliation logic tied to M-Pesa callbacks  
- Improved operational scalability by introducing tenant-isolated ISP environments  
- Enabled real-time network control directly from web-based admin dashboards  

---

### 📊 Enterprise ERP & CRM Platform

> Multi-tenant SaaS business management platform — double-entry accounting, FIFO inventory costing, CRM, and automated invoicing serving 50+ SME clients across Kenya.

**Stack:** `Laravel` · `React` · `TypeScript` · `MySQL` · `Redis` · `SendGrid` · `M-Pesa Daraja API`

---

## 🏗 Architecture Overview

- **Multi-Tenant SaaS Layer**
  Schema-level isolation with domain-based tenant resolution ensuring complete data separation per client while maintaining a shared application core.

- **Accounting Engine**
  Fully automated double-entry system generating balanced journal entries for every financial transaction, with support for financial statements (P&L, Balance Sheet, Cash Flow).

- **Inventory System**
  FIFO costing engine with automated COGS journal entries, stock tracking, reorder alerts, and multi-warehouse transfer workflows.

- **CRM Module**
  End-to-end lead management system — leads → opportunities → quotes → invoices → payments with full activity tracking and pipeline visibility.

- **Invoicing & Payment Pipeline**
  Automated invoice generation, branded PDF templates, multi-channel delivery (Email + WhatsApp), and real-time reconciliation via M-Pesa callbacks.

- **RBAC & Audit System**
  Role-based access control with granular permissions across all modules and full audit trail tracking for every data operation.

---

## 📊 Production Impact

- 🏢 50+ SME clients actively using the platform  
- 📈 70% improvement in reporting efficiency  
- 🔒 Zero cross-tenant data leakage incidents (3+ years)  
- 🤖 100% automation of invoicing workflows  
- 📦 Fully automated FIFO inventory costing and journal posting  

---

## ⚙️ Key Engineering Outcomes

- Eliminated manual accounting and invoicing operations through full automation  
- Implemented scalable multi-tenant architecture supporting multiple businesses on a single system  
- Reduced financial reporting time significantly through automated statement generation  
- Improved operational accuracy via real-time reconciliation with M-Pesa payment flows  
- Designed system for future microservice extraction with clean domain boundaries  

---

### 🤖 WhatsApp Business Automation Suite

> Multi-channel communication platform — intelligent routing across WhatsApp Business Cloud API, Twilio SMS, and SendGrid Email with NLP chatbot, campaign automation, and analytics tracking.

**Stack:** `Node.js` · `TypeScript` · `Redis` · `MySQL` · `WhatsApp Business Cloud API` · `Twilio` · `SendGrid`

---

## 🏗 Architecture Overview

- **Inbound Message Router**
  Normalizes incoming messages from WhatsApp Webhooks, Twilio SMS, and SendGrid inbound email into a unified event format for processing.

- **NLP Chatbot Engine**
  Handles intent classification, entity extraction, and conversation state management with configurable confidence-based escalation to live agents.

- **Outbound Routing Layer**
  Smart channel selection with fallback logic:
  WhatsApp → SMS → Email based on delivery success and contact preferences.

- **Campaign Scheduler**
  Queue-based campaign execution with rate limiting, audience segmentation, and controlled delivery windows to comply with platform API limits.

- **Analytics Engine**
  Tracks delivery status, engagement metrics, and chatbot resolution performance across all communication channels.

---

## 📊 Production Impact

- 📱 100,000+ automated interactions per month  
- 💰 60% reduction in support operational costs  
- 🤖 40% of tier-1 queries fully automated  
- 📊 Unified communication across WhatsApp, SMS, and Email  
- ⚡ Real-time escalation to human agents based on NLP confidence scoring  

---

## ⚙️ Key Engineering Outcomes

- Built a unified multi-channel messaging abstraction layer across 3 external APIs  
- Implemented queue-driven rate limiting system to prevent API throttling  
- Designed NLP-based intent routing system for automated customer support  
- Reduced human intervention through automated resolution workflows  
- Created scalable campaign system capable of handling high-volume messaging safely  

---

## Tech stack

### Languages & frameworks

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

### Infrastructure & integrations

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MikroTik](https://img.shields.io/badge/MikroTik_RouterOS-000000?style=flat-square)
![M-Pesa](https://img.shields.io/badge/M--Pesa_Daraja_API-2EB82E?style=flat-square)
![FreeRADIUS](https://img.shields.io/badge/FreeRADIUS-CC0000?style=flat-square)
![WhatsApp API](https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

### Tools & practices

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![CI/CD](https://img.shields.io/badge/CI%2FCD-4285F4?style=flat-square)
![Agile](https://img.shields.io/badge/Agile%2FScrum-0052CC?style=flat-square)

---

## Areas of expertise

**Fintech & Payments**
Deep hands-on expertise with the M-Pesa Daraja API suite — C2B, B2C, STK Push, STK Query, and balance inquiry endpoints. Payment reconciliation pipelines, fraud detection hooks, and PCI-DSS compliant audit logging.

**ISP & Network Automation**
MikroTik RouterOS API integration for PPPoE/hotspot management, FreeRADIUS for RADIUS authentication and accounting, automated bandwidth policies, and subscriber lifecycle management from sign-up to suspension.

**Enterprise Architecture**
Multi-tenant SaaS system design with schema-level isolation, row-level RBAC, event-driven processing via queues, and clean domain boundaries for long-term maintainability. ERP, CRM, and billing modules built for scale.

**Workflow Automation**
End-to-end automation across WhatsApp Business Cloud API, Twilio SMS, and SendGrid Email — unified routing layers, campaign schedulers, chatbot NLP, and analytics pipelines.

**Technical Leadership**
Led distributed engineering teams across EMEA and EAT time zones. Full SDLC ownership from requirements, architecture design, and sprint planning through production deployment and incident response.

---

## GitHub activity

> **Note on contribution counts:** Approximately 60% of my active development work lives in private client repositories — enterprise systems under NDA, proprietary fintech integrations, and ISP platform work. Public contributions represent the remaining ~40%.

**What the patterns mean:**
- **Activity spikes** — project launches, major feature releases, and intensive delivery phases
- **Consistent baseline** — ongoing maintenance, bug fixes, and incremental client improvements
- **Lower periods** — focus on private client deliverables, system architecture planning, and consulting engagements

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Tella86&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tella86&layout=compact&theme=tokyonight&langs_count=8" height="160" alt="Top Languages" />
</div>
<div align="left" style="margin-top:10px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tella86&theme=tokyonight" height="160" alt="GitHub Streak" />
</div>


---
## Remote readiness

| Area | Detail |
|------|--------|
| ⏰ Time zones | EMEA, EAT (UTC+3), US EST/PST — 5+ years of async-first collaboration |
| 📝 Documentation | OpenAPI/Swagger specs, ADRs, inline code docs, runbook authoring |
| 🔄 Async tools | Slack · Notion · Linear · Jira · GitHub Projects |
| 🎯 Ownership | Full responsibility for system stability, performance, and long-term maintainability |
| 🛠 Process | Scrum, Kanban, sprint planning, continuous delivery, incident post-mortems |

---

## Open to opportunities

### Currently exploring

✅ **Senior / Lead Software Engineer** roles at fintech or infrastructure-focused companies  
✅ **Technical Architect** positions for payment systems and enterprise integrations  
✅ **Strategic consulting** for ISP automation, billing platforms, and M-Pesa integrations  
✅ **Long-term partnerships** with companies building products for African markets  
✅ **Open-source collaboration** on payment infrastructure and developer tooling  

### Ideal environment

- Remote-first, async culture with strong engineering ownership
- Fintech, SaaS, or ISP verticals — preferably serving emerging markets
- Teams that care about system correctness, not just shipping speed
- EMEA / EAT-compatible working hours

### Not currently available for

❌ Engagements under 3 months  
❌ Equity-only arrangements  
❌ Roles requiring full-time on-site presence  

---

## Continuous learning

- Exploring: AWS infrastructure, microservices patterns, and blockchain payment rails for African markets
- Current focus: Scaling fintech systems beyond Kenya — cross-border M-Pesa, mobile money interoperability
- Contributing to: Open-source Laravel packages, React component libraries, and developer tooling
- Sharing knowledge: Technical tutorials on [YouTube @zirohmae](https://youtube.com/@zirohmae), mentoring junior developers

---

<p align="left">
  🏢 <strong>Brand:</strong> Ezems Tech Developers<br/>
  🌐 <strong>Website:</strong> <a href="https://ezems.co.ke">ezems.co.ke</a><br/>
  📧 <strong>Email:</strong> ezems.developers@gmail.com<br/>
  📞 <strong>Phone / WhatsApp:</strong> +254 101 086 123<br/>
  📍 <strong>Location:</strong> Mombasa, Kenya 🇰🇪 — open to remote<br/>
  💼 <strong>Status:</strong> Available for senior/lead roles and strategic consulting
</p>

<p align="left">
  <em>"I don't just write code — I build systems businesses depend on. From MikroTik API to M-Pesa reconciliation engine, I architect solutions that handle real load, generate real revenue, and run reliably in production."</em>
</p>

---

<p align="center">
  <sub>⭐ If any of my projects are useful to you, a star goes a long way · 🤝 Always open to interesting engineering conversations and collaboration</sub>
</p>
