# Hey, I'm Amber 👋

I build solutions to real problems. I love creating systems that actually work — ones that fit how people operate, not the reverse. I'm obsessed with data, automation, and eliminating redundant work through systems thinking.

I started with process automation (Google Apps Script, eliminating redundant work). Now I'm building full platforms in production, handling all technical and product decisions solo.

---

## How I Think

I approach problems with a **systems and processes lens** — understanding workflow, dependencies, and data flow before reaching for tools. I iterate: lessons from one system (like building the BLW report automation in Apps Script) inform architecture decisions in the next (how reporting integrates into the OS as a first-class layer, not an afterthought). I default to simple, controlled stacks (Apps Script for team workflows, Supabase + React for platforms) over complexity, and I own the full stack—architecture, schema design, RLS, feature decisions, and operations.

---

## Production Platforms

### [NEXUS](https://github.com/Amber-E-Moseri/Nexus) — 30 active users

Custom ops platform for a 30-person organization across 5 departments. The why: Existing team management tools are expensive and don't fit the actual workflow. Built custom to match their structure:

- **Communications** — Campaigns with A/B testing, bounce management, CASL compliance, Resend integration
- **Meetings** — Automated transcription (Whisper) + Claude summaries, attendance tracking, report generation
- **Spaces/Kanban** — Drag-drop boards with RLS isolation per department, sprint management
- **Campus mapping** — Real-time presence tracking across 358 Canadian campuses
- **Automated reporting** — Integrated report generator that pulls live data from the platform, transforms it into weekly health reports (subgroup metrics, attendance patterns, engagement flags), and emails stakeholders. I cut my teeth on this with Google Apps Script automation—took those learnings and rebuilt it as a proper system layer for the OS. **The multiplier: What took 2.5 hours of manual sheet-wrangling now runs in under 5 minutes, freeing the team to act on insights instead of compiling them.**

Solo architect, own all decisions.

---

### [Foundation School](https://github.com/Amber-E-Moseri/Rock-Solid-Ops) — 10 active users

Full ed-tech platform in production. The why: Students were tracked across multiple scattered Google Sheets — enrollment, attendance, grades, graduation tracking. No visibility into at-risk students, no proper escalation. Now consolidated into one system with flagging and escalation workflows. **Enrollment to graduation in one place. No one is lost.** Teachers and admins manage daily classroom operations with clarity on every student's status.

---

## Custom Solutions

### [Flock — Pastoral CRM](https://github.com/Amber-E-Moseri/Flock_CRM_Dev)

Lightweight relationship management built for one-person pastoral outreach (intentionally scoped for maintainability and focus). The why: Existing CRMs (Salesforce, HubSpot, Pipedrive) are built for sales pipelines, not personal outreach. They don't answer the actual question: Who do I call next and why? Flock does one thing well — make the next action obvious. AI-assisted call logging, smart cadence-based scheduling, priority dashboard, offline queue. Built with Google Apps Script + Sheets — the right tool for one person's workflow. Maintained, not actively expanding.

---

## Automations & Process Optimization

### [Google Apps Scripts](https://github.com/Amber-E-Moseri/google-apps-scripts)

**BLW Report Suite** — Automated a 2.5-hour weekly reporting process → under 5 minutes. Generates follow-up + first-timer reports for 6 subgroups from Elvanto data with automatic grading, colour-coded health bands, PDF export, and email delivery. One click replaces dozens of manual steps. *(Foundation for the reporting layer in BLW Canada OS.)*

**Drive File Alert** — Monitors Google Drive and notifies via email when files are uploaded — eliminating manual folder checks. Smart scheduling (every 15 mins on Sunday when uploads peak, every 2 hours other days), batches uploads from same person within 7 minutes into one notification. Runs free inside Google's infrastructure, zero servers.

---

## What Gets Me Excited

- **Automation & process optimization** — Eliminating redundant work. 2.5 hours → 5 minutes is the why I build.
- **Data** — Cleaning it, migrating it, visualizing patterns, making decisions from it
- **Structural thinking** — Understanding the problem before the solution. Systems over shortcuts.

---

## Stack

**Production:** React, Vite, Supabase (PostgreSQL + RLS), Resend, Claude API, Whisper, @dnd-kit  
**Automation:** Google Apps Script, JavaScript/TypeScript  
**Other:** Java, SQL

---

## Current Focus Areas

- **Data engineering** — Real-time attribution pipelines and analytics for multi-user platforms (IBM, Google, Andrew Ng specializations)
- **Lean Six Sigma** — Cross-departmental audit and process optimization; pursuing formal certification
- **LLM architecture** — Exploring agentic workflows and semantic search for platform automation

---

**Location:** GTA, Ontario, Canada  
**GitHub:** [@Amber-E-Moseri](https://github.com/Amber-E-Moseri)  
**Email:** [moseriamber@gmail.com](mailto:moseriamber@gmail.com)

**Looking for:** Open to contract work, full-time roles, or learning partnerships — particularly interested in problems where I can own platform architecture and learn from building systems at scale.
