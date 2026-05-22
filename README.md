# GuestBook

**STR Revenue Intelligence Platform** — Analytics, AI guest messaging, and compliance for short-term rental operators.

> Private beta. Built for Austrian STR operators.

---

## The Problem

Short-term rental platforms give you bookings. They don't give you a business. Revenue attribution is broken across month boundaries, compliance paperwork is manual, guest communication is reactive, and there's no single view of what your portfolio is actually doing.

GuestBook fixes that.

---

## What It Does

**Analytics Dashboard**
Revenue, occupancy, ADR, RevPAR, and ALOS with correct cross-month pro-rata attribution. GitHub-style occupancy heatmap. Property and portfolio views. Channel intelligence with net revenue after commission.

**AI Guest Messaging**
Trigger-based message drafts — booking confirmed, pre-arrival, check-in, checkout. Confidence-based auto-send. Multi-channel delivery via Telegram and WhatsApp. Multilingual (DE / PL / EN).

**Austrian Compliance**
Meldezettel generation, Ortstaxe calculation, Statistik Austria reporting. Digital check-in flow built in.

**AI Command Centre**
Natural language queries against live booking data. Conversational analytics over your property knowledge base. Multi-provider AI routing.

**Email Marketing**
Campaign builder, drip sequences, audience segmentation, open and click tracking.

**Multi-Tenant Admin**
Tenant management, user lifecycle, agent observability, row-level security across all tables.

---

## Stack

| | |
|---|---|
| Framework | Next.js 16, TypeScript |
| UI | Tailwind CSS v4, Shadcn/UI, Recharts |
| Database | Supabase (PostgreSQL + pgvector) |
| AI | Claude, OpenAI, Gemini, Ollama |
| Messaging | Telegram Bot API, WhatsApp Business API |
| Email | Resend |
| PMS | Uplisting |
| Pricing | PriceLabs |
| Deploy | Vercel |

---

## Status

| Feature | Status |
|---|---|
| Analytics dashboard | Done |
| Guest management & compliance | Done |
| AI messaging (Telegram / WhatsApp) | Done |
| Email marketing engine | Done |
| Multi-tenant admin | Done |
| Austrian compliance engine | Done |
| Voice AI integration | In progress |
| Autonomous operator agent | In progress |
| Direct OTA integrations | Planned |
| Revenue forecasting | Planned |

---

## About

Built by a short-term rental operator who needed a tool that didn't exist. Running live on 3 properties in Austria.

Code is private. Reach out via [LinkedIn](https://linkedin.com/in/david-dilallo) if you're an STR operator or investor interested in what we're building.
