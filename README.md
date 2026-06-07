# GuestBook

**STR Revenue Intelligence Platform** — Full-stack analytics, AI messaging, compliance, and multi-agent coordination for short-term rental operators.

> Built by an operator, for operators. Running live on 3 properties in Austria.

---

## What it is

Short-term rental platforms give you bookings. They don't give you a business. Revenue attribution breaks across month boundaries, compliance is manual, guest communication is reactive, and there's no single view of what your portfolio is actually doing.

GuestBook fixes that. It syncs booking data from a PMS, calculates revenue and occupancy metrics with correct cross-month attribution, runs AI-assisted guest messaging across Telegram and WhatsApp, and handles Austrian regulatory compliance end to end.

---

## Features

**Analytics Dashboard**
Revenue, occupancy, ADR, RevPAR, and ALOS with cross-month pro-rata attribution. GitHub-style occupancy heatmap. Property and portfolio views.

**Channel Intelligence**
Revenue by source — Airbnb, Booking.com, VRBO, Direct. Commission tracking. Net revenue after platform fees.

**AI Command Centre**
Natural language queries against live booking data. BusinessChat with RAG over a property knowledge base. Multi-provider AI routing: Claude → OpenAI → Gemini → Ollama.

**Guest Messaging**
Trigger-based AI drafts — booking confirmed, pre-arrival, check-in, checkout. Confidence-based auto-send. Multi-channel delivery via Telegram and WhatsApp. Multilingual: DE / PL / EN.

**Austrian Compliance**
Meldezettel generation, Ortstaxe calculation, Statistik Austria reporting. Digital check-in flow built in.

**Email Marketing**
Campaign builder, drip sequences, audience segmentation, open and click tracking via Resend.

**Multi-Tenant Admin**
Tenant management, user lifecycle, agent observability, row-level security across all tables.

**V2 Mission Runtime**
Operator missions with explicit state transitions, approval gates, transactional continuity, resumable execution, and budget-capped agent loops.

---

## Tech Stack

| Concern | Technology |
|---------|-----------|
| Framework | Next.js 16 App Router, TypeScript strict |
| UI | Tailwind CSS v4, Shadcn/UI (Radix primitives), Recharts v3 |
| Database | Supabase (PostgreSQL), pgvector for embeddings |
| Auth | Supabase Auth + Row Level Security |
| AI | Claude, OpenAI, Gemini, Ollama — unified provider abstraction |
| Email | Resend |
| Messaging | Telegram Bot API, WhatsApp Business API |
| PMS | Uplisting (REST + webhooks) |
| Pricing | PriceLabs |
| Testing | Vitest |
| Deploy | Vercel (cron jobs, edge functions) |

---

## Roadmap

### Done
- Core infrastructure, auth, RLS
- Data import (CSV, Excel, PDF)
- Analytics dashboard V1 + V2
- Guest management and compliance engine
- Email marketing engine
- Brain Intelligence Engine (RAG, BusinessChat)
- Channel intelligence and commission tracking
- Omnichannel messaging (Telegram, WhatsApp)
- Multi-tenant admin
- Austrian compliance (Meldezettel, Ortstaxe, Statistik Austria)

### In Progress
- Voice AI provider integration
- Autonomous agent operator
- Admin panel invite flow and role management

### Upcoming
- Direct PMS API integrations (Airbnb, Booking.com)
- Revenue forecasting
- Mobile-responsive dashboard

---

## Development Methodology

Built using **Agent OS** — spec-driven AI-assisted development with structured task breakdowns, parallel agent dispatch, and persistent shared memory across sessions.

Multi-agent work is coordinated through a shared BRAIN memory system (curated knowledge, discovery logs, per-session scratchpads) and a SWARM task registry that tracks which agent owns what across concurrent work streams.

```
agent-os/specs/YYYY-MM-DD-feature/
├── spec.md          # Requirements
├── tasks.md         # Implementation checklist
└── orchestration.yml  # Agent assignments per task group
```

---

## About

Built for short-term rental operators who need stronger revenue intelligence, automation, and compliance workflows. Code is private.

Use the repository contact options if you're an STR operator, investor, or builder interested in what's here.
