# AI Email Client Project

## Build & Test Commands
- Install: `npm install`
- Dev: `npm run dev`
- Build: `npm run build`

## Architecture: Agent OS
- **Framework**: Next.js 14+ (App Router)
- **Styling**: Tailwind CSS
- **AI Integration**: Claude 3.5 Sonnet (via Vercel AI SDK)
- **Authentication**: NextAuth.js (OAuth for Gmail/Outlook)

## Core Agents
- **Triage Agent**: Prioritizes incoming emails.
- **Summary Agent**: Generates executive summaries for the inbox view.
- **Draft Agent**: Context-aware reply suggestions.
