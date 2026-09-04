# 🤖 Awesome WebMCP [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of _awesome_ things related to the WebMCP proposal.

[WebMCP](https://github.com/webmachinelearning/webmcp) is a proposal that enables web applications to expose JavaScript-based tools to AI agents and assistive technologies, creating collaborative, human-in-the-loop workflows.

> Your contributions are always welcome! Please read the [contributing guidelines](CONTRIBUTING.md) to get started.

## WebMCP Explained

- [WebMCP explainer](https://github.com/webmachinelearning/webmcp/blob/main/README.md) for web developers and authors
- [WebMCP spec draft](https://webmachinelearning.github.io/webmcp/) for implementers

## Try out WebMCP

- [Chrome WebMCP Early Preview ](https://developer.chrome.com/blog/webmcp-epp) and [detailed instructions](https://docs.google.com/document/d/1rtU1fRPS0bMqd9abMG_hc6K9OAI6soUy3Kh00toAgyk/)
- [MCP-B open-source project](https://github.com/WebMCP-org) by Alex Nahas
- [An early WebMCP open-source project](https://github.com/jasonjmcghee/WebMCP) by Jason McGhee
- [Run headless Chrome with the WebMCP flag enabled via Cloudflare](https://developers.cloudflare.com/browser-run/features/webmcp/)

## Contents

- [Articles](#articles)
- [Benchmarks](#benchmarks)
- [Blogs](#blogs)
- [Community](#community)
- [Demos and Samples](#demos)
- [Frameworks](#frameworks)
- [Presentations](#presentations)
- [Testimonials](#testimonials)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Websites](#websites)

## Articles

- 2026.02 [Google Chrome ships WebMCP in early preview, turning every website into a structured tool for AI agents](https://venturebeat.com/infrastructure/google-chrome-ships-webmcp-in-early-preview-turning-every-website-into-a) by Sam Witteveen / VentureBeat

## Benchmarks

- [WindTunnel](https://github.com/nekuda-ai/WindTunnel) - Open-source benchmark comparing WebMCP with other browser-agent interfaces across task success, execution time, token usage, and cost.

## Blogs

- 2026.02 [WebMCP: The Web Standard That Makes Every Website a Tool for Agents](https://www.arcade.dev/blog/web-mcp-alex-nahas-interview) by RL Nabors, based on Alex Nahas interview
- 2026.09 [I added WebMCP to a live Stripe checkout in ~40 lines](https://dev.to/flovoice53tech/i-added-webmcp-to-a-live-stripe-checkout-in-40-lines-4ekk) by Florin Arsenie, on adding WebMCP to a product that already takes real money

## Community

- [W3C Web Machine Learning Community Group](https://www.w3.org/groups/cg/webmachinelearning/) develops the WebMCP spec ([how to join](https://webmachinelearning.github.io/community/#join))
- [WebMCP GitHub repo](https://github.com/webmachinelearning/webmcp/) for spec development and related technical discussions
- [Awesome WebMCP GitHub repo](https://github.com/webmachinelearning/awesome-webmcp/) for sharing other _awesome_ things related to the WebMCP proposal (you're here!)

## Demos

- [Demos](https://github.com/GoogleChromeLabs/webmcp-tools/#demos) by Google Chrome Labs
- [Demos](https://github.com/GoogleChromeLabs/webmcp-tools/blob/main/AWESOME_WEBMCP.md#demos) by 3rd-party developers
- [CliDeck MCP — Network Evidence Workbench](https://mcp.clideck.com/demo) - Live, read-only, version-aware network knowledge demo exposing deterministic lookup, change review, snapshot analysis, upgrade guidance, and topology analysis through WebMCP tools ([source](https://github.com/SmartRoot7/clideck-mcp)).
- [isainative.dev](https://isainative.dev/) - Audits public GitHub repositories for AI coding readiness and exposes both declarative and imperative WebMCP tools.

## Frameworks

- [agentk](https://github.com/stevysmith/agentk) - Command palette library (a cmdk fork) where tools defined once as JSON Schema become human-facing forms and WebMCP registrations; handles the `navigator.modelContext` to `document.modelContext` move and AbortSignal-based unregistration.
- [Shopware WebMCP Plugin](https://github.com/agentic-commerce-lab/webmcp-plugin) - Adds WebMCP support to storefronts built with Shopware, an open-source ecommerce platform.
- [simple-webmcp](https://github.com/emingure/simple-webmcp) - Turns existing JavaScript and TypeScript functions into callable WebMCP tools via `webmcp(fn)`, avoiding a separate tool layer while supporting schema patching, React lifecycle helpers, and execution hooks for approvals, HITL flows, and analytics.
- [webmcp-go](https://github.com/seunghan91/webmcp-go) - Go net/http middleware that serves the WebMCP Origin-Trial token header.
- [webmcp-django](https://github.com/seunghan91/webmcp-django) - Django integration for WebMCP: Origin-Trial token middleware and template tags for the declarative form API.

## Presentations

## Testimonials

## Tools

- [AIC (Agent Interaction Control)](https://github.com/VPAI-Grok/AIC) - Open-source contracts, cross-surface evidence, parity verification, and fail-closed reliance checks for WebMCP tools and their human UI, MCP, and API equivalents.
- [Collection of WebMCP tools](https://github.com/GoogleChromeLabs/webmcp-tools/) by Google Chrome Labs
- [webmaxru/agent-skills: WebMCP](https://github.com/webmaxru/agent-skills/tree/main/skills/webmcp) - Agent skill for implementing and debugging browser WebMCP integrations in JavaScript and TypeScript web apps
- [Conscriba](https://conscriba.com/) — Automatic WebMCP Creation for AI Agents, Analytics & Tracking
- [webmcp.com](https://webmcp.com/) — Live directory of WebMCP-enabled websites with a JSON API for agent-side discovery.
- [Ask nekuda](https://chromewebstore.google.com/detail/ask-nekuda/amochnnbmnkjjlblolhpddkokhnalkjp) — Chrome side-panel AI assistant that picks up WebMCP tools exposed by the active tab; BYOK or hosted Gemini.
- [WSG WebMCP Experiment](https://mgifford.github.io/wsg-webmcp-experiment/) - An effort to learn about WebMCP by applying it to the [Web Sustainability Guidelines](https://github.com/w3c/sustainableweb-wsg)
- [admintoolkit.io](https://admintoolkit.io/) - A suite of 24 read-only WebMCP tools for infrastructure diagnostics, including a WebMCP tool validator.
- [WebConverter](https://webconverter.app/webmcp.html) — Privacy-first, in-browser file converter (images, PDF, audio, video, OCR, 3D models). Every conversion is exposed as a WebMCP tool via `navigator.modelContext` so agents can convert files locally — no uploads, no API keys.
- [webmcpify](https://github.com/TueJon/webmcpify) - Agent skill that integrates WebMCP into an existing web app end to end — inventories the app, proposes a tool manifest for approval, integrates the tools, then verifies each one in a real browser and heals failures
- [WebMCP Kit](https://github.com/nekuda-ai/webmcp-kit) - Plugin for coding agents with an interactive visual Explorer that maps a site's user journeys to proposed WebMCP tools for review and approval, then implements and verifies them in a real browser.
- [WebMCP Today](https://webmcp.today/) - Open-source package registry for discovering site-specific WebMCP packages and installing them with per-site install commands ([source](https://github.com/robertn702/webmcp-today)).

## Tutorials

## Videos

- 2026.04 [WebMCP Explained](https://www.youtube.com/watch?v=GbfZSjJBQQ0&list=PLNhYw8KaLq2ViBncoyLc2TSGOjzSqe8Pr), by Andrew Nolan, presented at W3C AC Meeting 2026
- 2026.04 [WebMCP and the Agentic Web](https://www.youtube.com/watch?v=M1cME470ugM), by [Dominic Farolino](https://domfarolino.com), presented at BlinkOn 21
- 2026.02 [WebMCP: Agents on the Web and in the Browser](https://www.youtube.com/watch?v=6Po39iD6Pfs&t=31s) by Alex Nahas, interviewed by RL Nabors
- 2025.11 [Web AI Summit 2025: Don't let AI agents push your buttons - use WebMCP instead!](https://www.youtube.com/watch?v=p1l8nkQAoUw) by Khushal Sagar
- 2025.10 [WebMCP demo recording](https://screen.studio/share/hbGudbFm) by Alex Nahas, presented at W3C TPAC 2025

## Websites

- [Archipelago](https://warrenperez.com/en/archipelago/) - Maps a Notion workspace as a nautical chart, entirely in the browser. Four WebMCP tools let an agent draw the chart from structured data, read it back, highlight a computed set of databases, and annotate islands - on the same map the human is watching.
- [Scholar Sidekick](https://scholar-sidekick.com/integrations/webmcp) - Resolves scholarly identifiers (DOI, PMID, arXiv, ISBN…) and verifies citations, exposing seven WebMCP tools (`verifyCitation`, `auditBibliography`, `checkRetraction`, `checkOpenAccess`, `resolveIdentifier`, `formatCitation`, `exportCitation`) via `navigator.modelContext`, so in-browser agents can verify a citation or audit a whole bibliography, format citations, and check retraction and open-access status directly.
- [agent-ready.dev](https://agent-ready.dev/) - Scores any website for AI-agent readability against the Vercel Agent Readability Spec, llms.txt, and agent-protocol manifests, and exposes WebMCP tools (`scan_site`, `get_scan`, `ask`) via `navigator.modelContext` so in-browser agents can run scans directly.
- [Stacktree](https://stacktr.ee) - Agent-first HTML hosting. The production dashboard and docs expose site-management tools (publish, update, gate, share) over WebMCP from a command palette, so humans and in-browser agents share one tool catalog.
- [sms-florin](https://flo-voice1.com/esim) - eSIM and virtual phone number store. WebMCP tools are registered on the live Stripe checkout flow (not a separate demo), so an agent browses plans and completes a real purchase through the same code path a human uses. [Integration source](https://github.com/flovoice53-tech/sms-florin-webmcp-demo)
- [TrickyBird](https://trickybird.com) - Web proxy whose home page registers one imperative tool, `open_site`, through `document.modelContext`, so an in-browser agent can hand it an address and the tab navigates to the proxied page.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
