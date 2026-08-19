# MCPVOT | Cyberpunk Portfolio

> **Building AI agents, real-estate platforms, and on-chain economies.**

Live at **[https://mcpvot.github.io](https://mcpvot.github.io)** · [mcpvot.xyz](https://mcpvot.xyz) · [xpequi.xyz](https://xpequi.xyz) · [github.com/MCPVOT](https://github.com/MCPVOT)

![Next.js](https://img.shields.io/badge/Next.js_16-000000?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![R3F](https://img.shields.io/badge/React_Three_Fiber-000000)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?logo=githubpages&logoColor=white)

This repository hosts the static export of the **MCPVOT cyberpunk portfolio** — the personal site for [MCPVOT](https://github.com/MCPVOT) (ENS: `mcpvot.eth`), built with Next.js and React Three Fiber, served on GitHub Pages.

## About the Site

A dark, neon cyberpunk portfolio covering the full engineering identity of MCPVOT: AI agents, real-estate platforms, and on-chain economies, converging toward **S.D.A.E.** — a Sustainable Decentralized Autonomous Ecosystem.

Key sections:

- **About** — full-stack AI agents (from Pequi's Colombian rental-law negotiation to on-chain micro-payment protocols where autonomous agents pay each other in USDC)
- **Certifications** — AMD AI Academy: *AI on AMD*, *Hugging Face on AMD*, *Kubernetes on AMD Instinct GPUs*
- **Projects** — flagship builds and their ecosystems (see table below)
- **x402 Facilitator** — official x402 facilitator on Base (USDC · ERC-1155): "Stripe for AI agents"
- **ML & Reinforcement Learning** — PPO, GRPO, RLVR; multi-model consensus as an RL-inspired reliability mechanism
- **How I Architect** — spec-first, agent-driven pipeline: *SPEC → ORCHESTRATE → BUILD → SHIP* with a 3-stage evaluation gate (lint → typecheck → integration)
- **Agent Swarm Architecture** — orchestrating harness, specialist sub-agents, a council of models, persistent memory, security automation
- **Developer Tooling** — Hermes Agent, OpenCode, Cline, Codex, MCP protocol
- **Automation & DevOps** — n8n, DeerFlow, VoltAgent, GitHub Actions CI/CD, Vercel Cron, Sentry, Upstash rate limiting
- **Tech Stack** — full breakdown across languages, frontend, backend/DB, AI/agents, ML/RL, payments, blockchain, cloud/infra, identity, and storage/IPFS
- **Recent Improvements** — changelog of notable updates (mobile overhaul, Wompi payouts, agent streaming, SEO discovery, Dashboard V3, and more)

## Projects

| # | Project | Description | Link |
|---|---------|-------------|------|
| 01 | **Pequi** | AI-powered real-estate platform for Colombia. Live in Ibagué (64 barrios) + Bogotá (212 barrios, 20 localidades). 15 AI tools, 18-endpoint public API, Ley 820 contracts, c402 monetization, Wompi payments, DeepSeek V4 agent with GRPO fine-tuning. | [xpequi.xyz](https://xpequi.xyz) |
| 02 | **MCPVOTS** | AI agent micro-payment ecosystem on Base. VOTS token with deflationary burns, n8n automation, VoltAgent orchestration, autonomous trading, MCP protocol marketplace. | [mcpvot.xyz](https://mcpvot.xyz) |
| 03 | **MCPVotsAGI** | Multi-model consensus SDK — specialist LLM outputs aggregated by a reward model into a single high-confidence answer; A2A protocol gateway, Redis-backed persistent memory. | [MCPVOT/mcpvotsagi](https://github.com/MCPVOT/mcpvotsagi) |
| 04 | **Village of Thousands** | Sustainability-focused skateboard-culture lifestyle brand. Hybrid e-commerce: Shopify + custom Next.js storefront + Supabase Realtime. NYFW featured. | [villageofthousands.io](https://villageofthousands.io) |
| 05 | **xpequi-api** | Colombia's first public real-estate data API. 18 endpoints, 276 barrios (Ibagué + Bogotá), c402 Protocol monetization, AVM valuation, live UVR/IPC, IPFS contract pinning, TypeScript + Python SDKs, MCP server. | [MCPVOT/xpequi-api](https://github.com/MCPVOT/xpequi-api) |

## Repository Layout

This repo tracks the **compiled static export** of the Next.js application so GitHub Pages can serve it directly (`.nojekyll` is committed so the `_next/` assets are served verbatim).

```
mcpvot.github.io/
├── index.html          # Home page (static export)
├── 404.html            # Custom 404 page
├── _next/              # Next.js build assets (chunks, static)
├── favicon.ico         # Site icon
├── pequi-logo.png      # Pequi logo asset
├── .nojekyll           # Disables Jekyll processing on GitHub Pages
└── *.svg               # Inline SVG assets
```

## Running Locally

The site is fully static — serve the repo root with any static file server:

```bash
# Python
python -m http.server 3000

# Node
npx serve .

# Or with http-server
npx http-server . -p 3000
```

Then open `http://localhost:3000`.

## Deployment

This is a GitHub Pages user site:

- **Source:** root of the `main` branch (contains the static export directly)
- **URL:** `https://mcpvot.github.io`

To update the live site, regenerate the static export from the Next.js source (maintained separately) and commit the fresh output to this repository. The `404.html` file is used by GitHub Pages for unmatched routes.

## Links

- 🌐 [mcpvot.xyz](https://mcpvot.xyz) — MCPVOT hub
- 🏠 [xpequi.xyz](https://xpequi.xyz) — Pequi real-estate platform
- 🐦 [X / Twitter — @MCPVOT](https://x.com/MCPVOT)
- 🐙 [GitHub — MCPVOT](https://github.com/MCPVOT)
- 🧬 ENS: `mcpvot.eth`

---

*MCPVOT © 2026 · Built with Next.js + React Three Fiber*
