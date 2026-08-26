# Thomas Hotton — Portfolio

**AI-native operator & builder** — turning messy business processes into practical systems, automations, and AI solutions.

🔗 Live site: [thomas2143.github.io/Portfolio](https://thomas2143.github.io/Portfolio/)
💻 Repo: [github.com/thomas2143/Portfolio](https://github.com/thomas2143/Portfolio)
💼 LinkedIn: [linkedin.com/in/thomas-hotton](https://www.linkedin.com/in/thomas-hotton)

---

## About

3.5 years managing B2B portfolios across 3 markets (+194% / +187% peak NRR, €392K generated, zero churn on key accounts), now building the AI/automation layer myself. I map how systems actually work, find the gap with how they should work, and ship the fix — HubSpot workflows, AI agents, data flows, and the failure handling that keeps them safe in production.

Available for: **Business Systems & AI Analyst** · **AI Builder** · **AI Automation & RevOps**

---

## Work samples

### 📥 MiddleCorp — AI-Driven Inbound Lead Strategy
*Technical challenge, July 2026*
Lead routing architecture across 4 segments (Enterprise / SMB / Partners / existing customers) redesigned natively in HubSpot, plus a 3-tier AI triage agent (rule-based pre-filter → LLM → human) for inbound emails keyword routing can't handle. Full system prompt, guardrails, evaluation metrics, and off-switch criteria included — then actually built as a working **n8n workflow** (webhook → HubSpot lookup → Groq/Llama 3.3 70B triage → escalation tasks).
[View the deck](https://thomas2143.github.io/Portfolio/middlecorp/index.html)

### 🔎 Meridian CA — Grounded RAG Assistant
*Portfolio project, August 2026*
Pre-sales assistant that treats refusal as a first-class, verifiable outcome — three enforced behaviours (`answer` / `escalate` / `refuse`) instead of answering from a chunk that merely sounds related. Visible retrieval trace, cross-lingual (EN/RU) retrieval validated with paired tests, no vector DB.
**0.978** behaviour accuracy · **0.000** hallucination rate · **$0.0024** per quality-passing query, across 45 labelled eval cases.
[Try it live](https://meridian-chat-avkz.vercel.app/) · [View the deck](https://thomas2143.github.io/Portfolio/meridian/index.html)

### 📋 Debrief — Pre-call brief generator
*Live, May 2026*
Paste raw CRM notes, emails, tickets, and Slack threads — Debrief generates a complete pre-call brief: account timeline, open commitments, risk signals, sentiment, and a suggested opening line. Saved accounts get richer over time; a weekly watchlist flags what needs attention.
Stack: Groq (llama-3.3-70b-versatile), Supabase auth, Stripe webhooks, 6 Vercel serverless functions.
[Open app](https://call-prep-uokh.vercel.app/landing.html) · [Case study](https://thomas2143.github.io/Portfolio/debrief/index.html)

### 📊 Pulse — Implementation Health Tracker
*Live, June 2026*
Tracks SaaS retail implementations from kickoff to post go-live. Live health score across 4 dimensions (stakeholder alignment, delivery confidence, adoption, timeline adherence); multi-country rollouts get independent parallel timelines per site, visible at a glance.
Stack: Groq (llama3-8b-8192), Supabase Postgres, 6 Vercel serverless functions, token-based auth.
[Open app](https://thomas2143.github.io/pulse/app.html)

### 🧭 Job Pipeline Tracker
*Live, AI-powered*
A job-hunting pipeline built on B2B sales CRM logic. Paste a JD, get structured extraction (company, title, salary, location) plus a full CV-vs-JD fit analysis naming exactly what's strong and what's missing.
Stack: Groq (llama-3.3-70b), single Vercel serverless proxy, deterministic JSON output.
[Open app](https://job-pipeline-chi.vercel.app)

### 🔌 HubSpot Custom Objects — API Integration
*Certified, 2026*
Practicum behind the "Integrating With HubSpot I" certification (57/60). Node/Express app doing full CRUD on a HubSpot custom object via the CRM REST API v3 — the same integration muscle the MiddleCorp routing architecture relies on.
Stack: Node.js, Express, HubSpot CRM API v3, Axios, Pug.
[View the code](https://github.com/thomas2143/thomas-hotton-iwh-i-practicum)

### 📄 Consulting case studies
- **Maison X** — Brand & digital audit for a Moroccan dress specialist (6-point strategic analysis). [Read](https://thomas2143.github.io/Portfolio/maison-x/index.html)
- **90-Day Plan** — Founding Growth & Customer Associate onboarding plan for an Agtech startup. [Read](https://thomas2143.github.io/Portfolio/agtech-field-report/index.html)

---

## Stack

`Claude` `n8n` `HubSpot` `Groq` `Vercel` `GitHub` `Supabase` `Lucidchart` `Trello`

## Certifications

**Anthropic:** Building with the Claude API · Claude Code in Action · Claude Platform 101 · AI Fluency (Builders / Educators / Small Businesses) · Claude Code 101 · Introduction to Subagents & Agent Skills · Introduction to Claude Cowork
**HubSpot Academy:** Revenue Operations · Sales Hub · Service Hub · Data Integrations · Inbound Marketing · Frictionless Selling · Inbound Sales · Inbound
**Gainsight:** AI-Powered Customer Success · Durable Growth Playbook

Full list with verification links on the [live site](https://thomas2143.github.io/Portfolio/#faq).

---

## Structure

```
.
├── index.html                  # portfolio home
├── middlecorp/                 # MiddleCorp case study (deck + n8n workflow screenshot)
├── meridian/                   # Meridian CA case study
├── debrief/                    # Debrief case study
├── maison-x/                   # Maison X audit case study
├── agtech-field-report/        # 90-Day Plan case study
└── README.md
```
(Debrief, Pulse, Job Pipeline Tracker, and the HubSpot API practicum are deployed as their own live apps / repos, linked above.)

---

## Contact

Open to remote **Business Systems & AI Analyst / RevOps** roles, EOR or full-time. UTC+6, EMEA & EST overlap. FR / EN, RU in progress.
[LinkedIn](https://www.linkedin.com/in/thomas-hotton) · [Book a call](https://koalendar.com/e/rencontrer-thomas-hotton-8)
