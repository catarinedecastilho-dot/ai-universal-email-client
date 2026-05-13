# Architecture Documentation: Universal AI Email Client

## 1. Overview
A mobile-ready PWA built for unified email management (Gmail, O365, IMAP) with integrated AI agents for productivity.

## 2. Tech Stack
- **Frontend**: Next.js, React, Tailwind CSS.
- **Backend**: Next.js API Routes.
- **Connectivity**: Nylas SDK (Unified Email API).
- **AI**: Vercel AI SDK + Anthropic Claude.
- **Deployment**: Vercel.

## 3. Agentic Workflow
Using a multi-agent system to process incoming data:
- **Input**: Email stream via Webhooks.
- **Processing**: Agents analyze, summarize, and prioritize.
- **Output**: Enriched UI with AI-driven insights.
