# Blaze-stack

Hi, I'm Trenton Waters, a full-stack indie developer building AI tools, web apps, automation systems, decentralized experiments, and security-minded utilities.

## Current Focus

- Edie: experiments around chat, language tooling, personal assistants, and model workflows.
- Discrupt: a privacy-first rebuild for consent-based community data exports and dataset prep.
- Defensive utilities: small tools for password hygiene, proxy health checks, local log review, and safer security education.
- Decentralized systems: signed compute offers, public hash-chain logs, local-first messaging, and deployable coordination tools.

## Showcase Rebuilds

| Project | Status | Direction |
| --- | --- | --- |
| [Blaze Ops Stack](https://github.com/Blaze-stack/blaze-ops-stack) | New | Docker Compose deployment companion for running the Chainlog, EdgePower, Mesh, and status services together. |
| [EdgePower Admin UI](https://github.com/Blaze-stack/edgepower-admin-ui) | New | Browser control surface for EdgePower coordinator nodes, jobs, receipts, and audit events. |
| [EdgePower CLI](https://github.com/Blaze-stack/edgepower-cli) | New | Operator CLI for creating jobs, inspecting results, and viewing coordinator events. |
| [EdgePower Marketplace](https://github.com/Blaze-stack/edgepower-marketplace) | New | Marketplace registry API for capacity offers, job requests, and auditable matches. |
| [Machine Fleet Agent](https://github.com/Blaze-stack/machine-fleet-agent) | New | Privacy-preserving machine health agent that publishes public-safe telemetry to Chainlog or JSON. |
| [Chainlog Server](https://github.com/Blaze-stack/chainlog-server) | New | Deployable FastAPI public transparency log with verifiable hash-chained events. |
| [Chainlog CLI](https://github.com/Blaze-stack/chainlog-cli) | New | Operator CLI for appending, listing, verifying, and exporting Chainlog events. |
| [Chainlog Python SDK](https://github.com/Blaze-stack/chainlog-python-sdk) | New | Stdlib Python SDK and CLI for appending, reading, and verifying Chainlog events. |
| [Chainlog Search API](https://github.com/Blaze-stack/chainlog-search-api) | New | Mirror and search service for Chainlog events with SQLite FTS/fallback search. |
| [Chainlog Pages Publisher](https://github.com/Blaze-stack/chainlog-pages-publisher) | New | Static GitHub Pages publisher for Chainlog feeds and transparency snapshots. |
| [Chainlog Anchor](https://github.com/Blaze-stack/chainlog-anchor) | New | Signed Chainlog head anchoring and local anchor verification CLI. |
| [Chainlog Alert Router](https://github.com/Blaze-stack/chainlog-alert-router) | New | Deployable rule engine for routing deduped Chainlog, search, and status alerts to Discord or Chainlog. |
| [Chainlog Monitor Agent](https://github.com/Blaze-stack/chainlog-monitor-agent) | New | Uptime and synthetic monitoring agent that emits public-safe Chainlog and Discord status events. |
| [Chainlog Redactor Agent](https://github.com/Blaze-stack/chainlog-redactor-agent) | New | Log tailer that redacts secrets before publishing public-safe Chainlog, Discord, or JSONL events. |
| [Chainlog Webhook Relay](https://github.com/Blaze-stack/chainlog-webhook-relay) | New | Deployable webhook relay that verifies external events and writes them into Chainlog. |
| [Chainlog Webhook Lab](https://github.com/Blaze-stack/chainlog-webhook-lab) | New | Safe CLI for validating, redacting, signing, sending, and replaying webhook fixtures. |
| [Chainlog GitHub Action](https://github.com/Blaze-stack/chainlog-github-action) | New | GitHub Action for publishing workflow evidence, deployment notes, and release events into Chainlog. |
| [Repo Pulse Chainlog](https://github.com/Blaze-stack/repo-pulse-chainlog) | New | Read-only GitHub repo fleet auditor with SQLite history plus Chainlog and Discord pulse events. |
| [Blaze Repo Dashboard](https://github.com/Blaze-stack/blaze-repo-dashboard) | New | Static dashboard generator and sample site for GitHub repo pulse and Chainlog exports. |
| [Proofpack Chainlog](https://github.com/Blaze-stack/proofpack-chainlog) | New | File and folder proof notarization CLI with signed manifests and Chainlog publishing. |
| [Discord Chainlog Bot](https://github.com/Blaze-stack/discord-chainlog-bot) | New | Official Discord slash-command bot for approved users to publish Chainlog events. |
| [Ops Discord Control Bot](https://github.com/Blaze-stack/ops-discord-control-bot) | New | Official Discord ops bot for Chainlog, EdgePower, status checks, and Mesh Relay commands. |
| [Discord Ops Brief Bot](https://github.com/Blaze-stack/discord-ops-brief-bot) | New | Official Discord bot and webhook helper for deterministic operations briefings. |
| [Ops Briefing AI](https://github.com/Blaze-stack/ops-briefing-ai) | New | Ops briefing service and CLI with local summaries plus optional provider-neutral LLM HTTP support. |
| [Chainmesh TUI](https://github.com/Blaze-stack/chainmesh-tui) | New | Terminal dashboard/client for Chainlog and Mesh Relay events, messages, filters, and verification. |
| [Mesh Relay](https://github.com/Blaze-stack/mesh-relay) | New | HTTP/WebSocket message relay with per-room append-only hash-chained logs. |
| [Mesh Relay Client](https://github.com/Blaze-stack/mesh-relay-client) | New | CLI client for posting, reading, verifying, and listening to Mesh Relay rooms. |
| [Public Ops Status](https://github.com/Blaze-stack/public-ops-status) | New | Status page and JSON API for monitoring public tools and service endpoints. |
| [Market Sentinel Bot](https://github.com/Blaze-stack/market-sentinel-bot) | New | Market alert and paper-trading bot with Discord and Chainlog outputs. |
| [Market Data Chain](https://github.com/Blaze-stack/market-data-chain) | New | Market data logger and alert service with SQLite history plus Chainlog and Discord outputs. |
| [EdgePower Coordinator](https://github.com/Blaze-stack/edgepower-coordinator) | New | FastAPI coordinator for safe allowlisted distributed edge-compute jobs. |
| [EdgePower Worker](https://github.com/Blaze-stack/edgepower-worker) | New | Service worker that polls a coordinator and runs only built-in safe jobs. |
| [EdgePower Docker Worker](https://github.com/Blaze-stack/edgepower-docker-worker) | New | Deny-by-default Docker execution adapter for allowlisted EdgePower compute jobs. |
| [EdgePower Task Pack](https://github.com/Blaze-stack/edgepower-task-pack) | New | Allowlisted task handlers and schemas for real EdgePower worker jobs. |
| [EdgePower Capacity Oracle](https://github.com/Blaze-stack/edgepower-capacity-oracle) | New | Capacity scoring and snapshot service for EdgePower marketplaces and coordinator APIs. |
| [EdgePower Node](https://github.com/Blaze-stack/edgepower-node) | New | Privacy-preserving edge compute node that benchmarks safely and signs capacity offers. |
| [EdgePower Ledger](https://github.com/Blaze-stack/edgepower-ledger) | New | Signed local-first ledger for machines advertising compute capacity. |
| [Public Chainlog](https://github.com/Blaze-stack/public-chainlog) | New | Append-only hash-chained transparency log for public events. |
| [Chainlog Dashboard](https://github.com/Blaze-stack/chainlog-dashboard) | New | Static viewer for inspecting and verifying public JSONL chain logs. |
| [Datacenter Chain Sim](https://github.com/Blaze-stack/datacenter-chain-sim) | New | Decentralized compute scheduler simulation with auditable hash-chained receipts. |
| [Market Brief Bot](https://github.com/Blaze-stack/market-brief-bot) | New | Offline market brief generator for watchlists, CSV candles, and research notes. |
| [Bot Forge](https://github.com/Blaze-stack/bot-forge) | New | Safe scaffold generator for local and official-platform automation bots. |
| [Signal Lab](https://github.com/Blaze-stack/signal-lab) | New | Educational CSV-based trading-signal research CLI. |
| [Machine Watch](https://github.com/Blaze-stack/machine-watch) | New | Local machine health and inventory reports. |
| [Mesh Note](https://github.com/Blaze-stack/mesh-note) | New | Local-first signed message packets. |
| [AI Prompt Eval Kit](https://github.com/Blaze-stack/ai-prompt-eval-kit) | New | Provider-neutral evaluator for saved AI outputs. |
| [Defensive Log Sentinel](https://github.com/Blaze-stack/defensive-log-sentinel) | New | Local log scanner for defensive security signals. |
| [Discrupt](https://github.com/Blaze-stack/Discrupt) | Rebuilt | Consent-first data export and anonymization toolkit. |
| [edie-chatbot](https://github.com/Blaze-stack/edie-chatbot) | Legacy cleanup | Local response engine and offline trainer workflow. |
| [Powdercoat](https://github.com/Blaze-stack/powdercoat) | Rebuilt | Project polish and repo scaffold generator. |

## Portfolio Standards

Every active project should clearly answer:

- What is this?
- Can I run it?
- Is it safe and legal to use?
- What is the current status?
- How do I test or contribute?

Repos that used to contain unsafe automation or credential-capture patterns are being retired, rewritten, or converted into defensive education.

## Tech I Use

Python, JavaScript, TypeScript, Node.js, Docker, Linux, SQL, Cloudflare, Vercel, Raspberry Pi, OpenCV, TensorFlow, FastAPI, SQLite, and pragmatic glue code.

## Links

- Website: https://blazedev.co
- GitHub: https://github.com/Blaze-stack
