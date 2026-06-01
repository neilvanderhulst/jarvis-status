# JARV1S

Personal AI assistant for small-business owners — musicians, educators, freelancers.

Built and operated by [Neil van der Hulst](https://neilhollyn.com).

## What it does

JARV1S is a personal AI system that handles:
- **Conversation routing** — classifies intent, routes to the right model (Gemini, Claude, Mistral, local Ollama)
- **Calendar & email** — creates calendar events, drafts emails via natural language
- **Background intelligence** — nightly memory consolidation, weekly innovation watch, system health monitoring
- **Cost discipline** — tracks every model call, enforces monthly budget caps

## Status

Currently in personal use (v0). Building toward a v1 product for small-business owners by May 2027.

**Current phase:** Foundation complete. Adding multi-user isolation before onboarding first test user.

## Tech stack

- n8n (workflow automation + routing shell)
- Supabase (Postgres, vector search, RLS)
- LiteLLM (unified model gateway)
- Python (introspect-api: tools, memory, notifications)
- Cloudflare Tunnel (secure external access)

## Build log

Build sessions are logged in the FR1DAY tab of the private Cockpit UI.

---

*Private codebase. This repo is the public-facing status page.*
