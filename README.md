# Rex Quintenta

AI Automation Engineer - LLM Integration - Full-Stack Web and Mobile

Philippines, remote-first - [owenquintenta@gmail.com](mailto:owenquintenta@gmail.com) - [LinkedIn](https://linkedin.com/in/owendev) - [Upwork](https://www.upwork.com/freelancers/~016d94e91b51fc9dec)

---

My work runs in production. n8n workflow automation, Claude API and GPT-4 integrations, agentic AI pipelines, full-stack web apps in Next.js and TypeScript, mobile apps in React Native. I scope the problem, pick the right tool, and ship something that works without me babysitting it.

Currently building with Claude Code as my primary development environment. The constraint is always the problem, not the language or framework.

---

## What I've shipped

### [autoflow-studio](https://github.com/RexOwenDev/autoflow-studio) - Multi-tenant SaaS Reference Architecture

A reference implementation of a production-grade multi-tenant SaaS built across 8 gated phases. Stack: Next.js 16, Supabase with row-level security, Stripe usage metering, WorkOS SSO and SCIM, HMAC webhook verification, SOC2-aligned audit logging with tamper-evident export.

Includes 120 Vitest unit and integration tests plus 45 pgTAP database assertions. Built this to answer the question: what does "production-ready" actually look like end to end?

---

### [ai-content-pipeline](https://github.com/RexOwenDev/ai-content-pipeline) - Generative AI Editorial Automation

Six connected n8n workflows running live for a media client. The flow: RSS ingestion, deduplication, GPT-4.1-mini quality gate with structured JSON output, AI-assisted content drafting, WordPress REST API publishing, Slack notification, Google Sheets audit log.

Every quality threshold and topic filter lives in a Google Sheet. The editorial team tunes parameters without touching a single workflow node.

**Outcome: $20/month in AI API costs replaced 80 hours/week of manual editorial work. 6,800+ executions/month.**

---

### [recruitment-pipeline](https://github.com/RexOwenDev/recruitment-pipeline) - AI-Powered Candidate Screening Automation

Seven n8n workflows connected across seven platforms through a single trigger. A candidate fills out a Typeform, and Claude API scores them across three structured dimensions - role fit, experience relevance, and response quality - each with a numeric score and explicit reasoning chain. That output writes to HubSpot, alerts the team in Slack, queues a personalized Gmail, creates a ClickUp task, and logs everything to Google Sheets.

Human approval gate is required before any offer-stage email fires. The AI scores but never sends autonomously.

**Outcome: full candidate processing in under 10 seconds, zero manual data entry across seven platforms.**

---

## More projects

| Project | Description |
|---|---|
| [rag-chat-app](https://github.com/RexOwenDev/rag-chat-app) | Enterprise RAG app - hybrid BM25 plus pgvector retrieval, Cohere Rerank 3, inline source citations, async faithfulness evaluation, multi-tenant with Supabase RLS |
| [employee-onboarding-pipeline](https://github.com/RexOwenDev/employee-onboarding-pipeline) | 10-workflow n8n automation - BambooHR new hire event triggers Claude role classification, then provisions Google Workspace, Slack, Notion, ClickUp in sequence. Zero IT tickets per hire |
| [content-factory](https://github.com/RexOwenDev/content-factory) | AI content pipeline in 12 languages - Claude API for drafting, DeepL for transcreation, LLM-as-judge quality evaluation before publish |
| [proposal-studio](https://github.com/RexOwenDev/proposal-studio) | Collaborative AI proposal editor - real-time Tiptap editing, Claude-assisted generation, client acceptance flow, full audit trail in Supabase |
| [saas-billing-starter](https://github.com/RexOwenDev/saas-billing-starter) | Stripe billing starter with plan tiers, usage-based metering, customer portal, and webhook event handling |
| [seobot](https://github.com/RexOwenDev/seobot) | SEO content automation - keyword input to AI-generated article to WordPress or Shopify publish, fully automated |

---

## Stack

**Workflow automation:** n8n, Python scripting, JavaScript and TypeScript, webhook design, HMAC-SHA256 verification, cron scheduling, REST API integration, OAuth 2.0

**AI and LLM:** Claude API (Anthropic), GPT-4.1 and GPT-4.1-mini, generative AI workflow integration, RAG pipelines, pgvector, BM25 retrieval, Cohere Rerank 3, structured JSON output, agentic workflow patterns, LLM-as-judge quality evaluation, prompt engineering

**Web:** Next.js 16, React 19, TypeScript, Tailwind CSS v4, Supabase, PostgreSQL, Stripe, Vercel, Railway

**Mobile:** React Native, Expo, cross-platform iOS and Android

**Integrations I've connected in production:** HubSpot, Slack, Gmail API, Google Workspace, BambooHR, ClickUp, Notion, Airtable, Typeform, WordPress REST API, Shopify Admin API, Stripe, Twilio

---

Open to remote AI automation contracts, LLM integration projects, full-stack engagements, and enterprise roles in Metro Manila.
