<h2 align="left">
  Hi, I'm <strong>Ziroh Katana Mae</strong><br/>
  <sub>Senior Software Engineer &amp; Founder — Ezems Tech Developers · Mombasa, Kenya 🇰🇪</sub>
</h2>

<p align="left">
  I architect <strong>payment infrastructure, ISP billing systems, and enterprise automation</strong> for African markets — systems that handle real financial load, not demos. With 8+ years of production experience, I build full-stack solutions from MikroTik RouterOS API integrations to M-Pesa Daraja reconciliation engines, serving clients across Kenya and EMEA.
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

> Enterprise-grade payment engine with event-driven architecture and automated reconciliation

**Stack:** `Laravel` · `M-Pesa Daraja API (C2B / B2C / STK Push / STK Query)` · `Redis Queue Workers` · `MySQL` · `Webhook Management`

**Architecture highlights:**
- Redis-backed async queue workers handle transaction processing with exponential backoff retry logic
- Idempotent webhook handlers prevent duplicate transaction recording under network failures
- Real-time STK Push status polling with configurable timeout and fallback notification
- Reconciliation pipeline cross-checks Safaricom statements against internal ledger — automated, nightly, zero manual intervention
- PCI-DSS aligned audit logging with immutable transaction records and dispute resolution workflow

**Impact:** 10,000+ transactions/month · reconciliation cut from 4 hours → 15 minutes · dispute resolution fully automated

---

### 🌐 ISP Management & Billing Platform

> End-to-end ISP operations platform covering subscriber lifecycle, bandwidth control, and billing

**Stack:** `PHP` · `MikroTik RouterOS API` · `React` · `TypeScript` · `FreeRADIUS` · `MySQL` · `SMS Gateway`

**Architecture highlights:**
- RouterOS API bridge enables real-time bandwidth throttling, PPPoE session management, and hotspot user provisioning from a single admin interface
- FreeRADIUS integration handles subscriber authentication and accounting with custom attribute mapping per package tier
- Billing engine supports dynamic package pricing, prorated renewals, and automated suspension/reactivation triggered by M-Pesa payment callbacks
- Multi-ISP multi-tenancy with per-tenant router config isolation and subscriber namespace separation

**Impact:** 5,000+ active subscribers · 99.8% billing accuracy · zero manual suspension operations

---

### 📊 Enterprise ERP & CRM Platform

> Multi-tenant SaaS business management platform with accounting, inventory, and CRM modules

**Stack:** `Laravel` · `React` · `MySQL` · `REST APIs` · `Multi-tenancy` · `Role-based Access Control` · `PDF Generation`

**Architecture highlights:**
- Tenant isolation implemented at DB schema level — shared application, separate data namespaces
- Double-entry accounting module with FIFO inventory costing and automated journal entries
- Row-level RBAC spanning accounting, HR, and operations modules with granular permission scoping
- Automated invoicing pipeline with PDF generation, delivery tracking, and payment reconciliation
- Domain boundaries designed for eventual microservice extraction — clean service interfaces throughout

**Impact:** 50+ SME clients · reporting efficiency improved 70% · zero cross-tenant data incidents in 3 years

---

### 🤖 WhatsApp Business Automation Suite

> Multi-channel communication platform with intelligent routing across WhatsApp, SMS, and Email

**Stack:** `Node.js` · `WhatsApp Business Cloud API` · `Twilio` · `SendGrid` · `Queue Processing` · `Chatbot NLP`

**Architecture highlights:**
- Unified routing layer normalises message delivery across WhatsApp, SMS, and Email with per-channel fallback logic
- Template management system enforces Meta's 24-hour session window constraints and handles template approval state tracking
- Queue-backed campaign scheduler with per-tier API rate limiting to stay within WhatsApp Cloud API caps
- Chatbot NLP layer handles tier-1 support resolution with configurable confidence threshold for live agent handoff
- Analytics dashboard tracks delivery rates, open rates, and resolution ratios per campaign and channel

**Impact:** 100,000+ automated interactions/month · 60% cost reduction vs manual support · 40% of tier-1 queries auto-resolved

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
  <img src="https://github-readme-stats.vercel.app/api?username=Tella86&count_private=true&include_all_commits=true" height="160" alt="GitHub Streak" />
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
