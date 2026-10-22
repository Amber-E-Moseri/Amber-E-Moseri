# Hi, I'm Amber 👋

**I build production systems that replace spreadsheets, scattered tools, and manual workflows, and I own them end to end.**

I'm a third-year Computer Science student at York University and the sole architect and engineer behind four live platforms serving real teams. I started with process automation in Google Apps Script and now ship full-stack products where I own product, architecture, security, and operations.

📍 GTA, Ontario · 🔎 Open to software engineering, backend/platform, data, and automation roles (full-time or contract)

---

## 🧠 How I Work

**Map → Identify → Build → Measure → Improve**

I map the process before I write any code:

> People → Steps → Dependencies → Data → Bottlenecks → Sources of Truth

Once the system is visible, it's clear what to simplify, automate, or rebuild. Getting something working is the starting line. I keep asking: *Can this be simpler? More reliable? Is there redundant work left to remove? Is the architecture still right as usage grows?*

That's why my projects evolve into each other. A Google Apps Script reporting automation became Nexus's reporting layer, and the relationship workflows from my Flock CRM were folded into Nexus.

---

## 🚀 Production Platforms

### [NEXUS](https://github.com/Amber-E-Moseri/Nexus.git): Operations Platform
**40 active users · 5 departments · Solo architect & developer**

A custom operations platform for BLW Canada that replaced fragmented task tools, spreadsheets, contact systems, meeting notes, email workflows, and standalone automations.

| Area | What it does |
|------|--------------|
| **Operations** | Departmental spaces, Kanban boards, tasks, sprints, role-aware workflows |
| **People & CRM** | Relationship and follow-up workflows (evolved from Flock CRM) |
| **Communications** | Campaigns, A/B testing, bounce management, CASL-aware workflows, Resend |
| **Meetings** | Whisper transcription, AI summaries, attendance, structured minutes |
| **Reporting** | Live operational data → health reports, metrics, engagement flags, stakeholder delivery |
| **Intelligence** | Adoption, onboarding, operational health, and activity signals |
| **Security** | PostgreSQL RLS and role-aware access |

**Impact:** Reporting that took ~2.5 hours of manual spreadsheet work now takes under 5 minutes.
**Ownership:** Product · Architecture · Schema · Security · Frontend/Backend · Integrations · Deployment · Production Ops

---

### [Rock Solid Ops](https://github.com/Amber-E-Moseri/Rock-Solid-Ops.git): EdTech Operations
**36 active users · Enrollment-to-graduation lifecycle**

Foundation School operations platform replacing scattered spreadsheets. Enrollment to graduation in one place, so no one is lost between spreadsheets.

- Applicant registration, review, placement, and waitlisting
- Class and teacher management, attendance, and student progress
- Moodle enrollment integration and automated communications
- Missed-class and at-risk escalation, plus graduation workflows
- Retry/recovery tooling, operational health, and audit trails
- Role-aware access

**What it taught me:** workflow state machines, asynchronous processing, external-system failure handling, retries, and operational reliability.

---

### [RAF / Nomi](https://github.com/Amber-E-Moseri/raf_app.git): Personal Finance Platform
**Multi-tenant · PostgreSQL security · Deterministic financial domain**

A personal finance and stewardship platform built around a deterministic Revenue Allocation Formula. Most finance tools explain where money went. RAF starts one step earlier:

> **Where should this money go?**

- Multi-workspace / household tenancy with PostgreSQL Row-Level Security and least-privilege runtime roles
- Accounts, reconciliation, bank-statement imports, and duplicate detection
- Transaction categorization and attribution
- Goal and debt tracking, including payment-pace and balance-trajectory modeling
- Deterministic 30/60/90-day cash-flow forecasting
- Monthly review lifecycle with immutable snapshots
- Audit trails and production monitoring
- AI assistant with strict financial-authority boundaries

**Architecture principle:** *AI can explain financial state. It doesn't define financial truth.*

This is where I'm going deepest on domain modeling, multi-tenancy, financial correctness, authorization, and backend architecture.

---

### [BLW York Hub](https://github.com/Amber-E-Moseri/club_management): Club Management Platform
**39+ members · Community operations · Solo architect & developer**

A full-stack platform that brings membership, outreach, communication, leadership accountability, and personal development into one system, replacing fragmented forms, spreadsheets, and group chats. I built it while serving as club president, so I was solving problems I understood from the inside.

| Area | What it does |
|------|--------------|
| **Membership** | Applications, approvals, member profiles, lifecycle |
| **People & Outreach** | Contact logging, follow-ups, cell assignments, engagement tracking |
| **Communications** | Announcements, personal messages, push notifications |
| **Meetings & Events** | Coordination, event management, attendance |
| **Personal Development** | Devotional resources, habit tracking, integrated e-reader |
| **Leadership** | Hierarchical structure, progress monitoring, accountability |
| **Security** | Supabase Auth, PostgreSQL RLS, role-aware permissions |

**Impact:** Centralized operations for 39+ members, giving leaders visibility into engagement, follow-ups, and individual progress.
**Ownership:** Product · Requirements · Architecture · Database · Security · Frontend/Backend · Testing · Deployment

> *Good software should make it easier to serve people, not create more work for them.*

---

## ⚡ Focused Automation

### [Drive File Alert](https://github.com/Amber-E-Moseri/google-apps-scripts.git)

Not every problem needs a platform. This Google Apps Script monitors Drive and notifies stakeholders when files arrive, eliminating manual folder checks.

- Checks every 15 minutes during peak Sunday uploads, every 2 hours otherwise
- Batches uploads from the same person within a 7-minute window
- Runs entirely inside Google's infrastructure, with no dedicated server

---

## 🧬 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React · Vite · TypeScript · JavaScript |
| **Backend & Data** | Node.js · PostgreSQL · Supabase · SQL · RLS · REST APIs |
| **AI & Automation** | Claude API · Whisper · Google Apps Script · LLM workflows |
| **Infrastructure** | Vercel · Render · Neon · Resend · Sentry · GitHub Actions |
| **Other** | Java · Git |

---

## 📚 Currently Focused On

- **Data engineering:** pipelines, data modeling, analytics, multi-user systems
- **Backend & system design:** reliability, authorization, queues, observability, distributed systems
- **LLM architecture:** RAG, semantic search, tool use, agentic workflows
- **Lean Six Sigma:** structured process analysis applied to software and operations

---

## 📫 Connect

- **GitHub:** [@Amber-E-Moseri](https://github.com/Amber-E-Moseri)
- **Email:** moseriamber@gmail.com

I'm looking for full-time or contract roles where I can build meaningful systems and keep growing alongside strong engineers.
