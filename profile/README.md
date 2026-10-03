<p align="center">
  <img src="https://cdn.duskstate.dev/logos/dusk-state-wordmark-light-cropped-tight.png" alt="Dusk State" height="180" />
</p>

<br /><br />

<p align="center">
  <img src="https://cdn.duskstate.dev/icons/dusk-state-icon-light-tight.png" alt="Dusk State icon" height="72" />
</p>


<br /><br />

<p align="center">
  <strong>Plugins &nbsp;·&nbsp; SKILLS &nbsp;·&nbsp; Templates</strong>
 <br /><br />
  Operational software and verified intelligence for production agents.
  <br />
  <sub>MCP Registries \ Agent Tool Safety | Change Monitoring / Audits</sub>
</p>

<br /><br />


## About

Dusk State publishes production-grade tools and verified, machine-readable intelligence for autonomous software agents and the humans and organisations that deploy them. Its products make capabilities, pricing, terms, provenance, and operational change easier to discover, compare, and audit—without presenting inference as fact or automation as authority.

<br /><br />

> **Slogan:** Evidence before action.  
> **Market line:** Know what changed before your agent acts.

<br /><br />

<img src="https://cdn.duskstate.dev/Iconographs/protocol-grird.png" alt="Supported agent and coding protocols" width="90%" />

<br /><br />

## What We Build

Dusk State focuses on **trust-and-change intelligence** for agent teams:

- **Tool Trust & Terms Feed** — A licensed API and MCP service containing normalised capabilities, pricing, terms, provenance, security observations, operational status, and change history for agent-consumable tools and services.

- **Agent-Readiness Audit** — A fixed-scope assessment of discovery, machine-readable metadata, schemas, authentication, terms, key scopes, status, payment readiness, security controls, and handoff paths.

- **MCP Schema-Diff Watcher** — Snapshots tools, descriptions, schemas, scopes, and endpoints; alerts on risk-relevant changes; contributes history to the flagship feed.

- **Agent Vendor Pack** — Generates and validates a vendor's machine-readable pricing, terms, capabilities, discovery, OpenAPI/MCP, and trust-page assets.

<br /><br />

## Core Principles


> Explicit over implicit. Evidence over assumption. Authority before action. Human approval for consequential change. Built for production. Honest about limits.

1. **Evidence over claims** — We publish retrieval timestamps, source URLs, hashes, correction history, and confidence levels. Never "safe," "certified," or "approved" without defining the exact check and scope.

2. **Agent-first, principal-authorised** — Agents are operational customers; humans and organisations remain the legal and economic buyers. We never describe an agent as the legal contracting party.

3. **Restrained and honest** — Independent, specialist, credible. No fictional teams, false scale, invented users, vanity metrics, or unsupported customer claims.

4. **Production-grade** — Versioned schemas, signed releases, explicit limitations, source attribution, security reporting, and visible change logs.

<br /><br />

## Who We Serve

| Role | Description |
|------|-------------|
| **Autonomous agents** | Discover and consume structured records, APIs, MCP tools, quotes, status, and evidence |
| **Agent builders** | Developers building production agent workflows who need to avoid unsafe, stale, incompatible, or unexpectedly expensive dependencies |
| **Operators** | People accountable for running agent systems who monitor change, failures, spend, and permissions |
| **Publishers/vendors** | MCP server, API, SaaS, data, or tool providers who need to become accurately discoverable and easier to approve |
| **Economic principals** | Humans or organisations funding and authorising the account, setting authority, limits, terms, and payment method |

<br /><br />

## Technology Stack

- **Runtime:** Cloudflare Workers
- **Language:** TypeScript
- **Build:** Turborepo with pnpm workspace
- **Database:** PostgreSQL through Prisma
- **Storage:** Cloudflare R2
- **Authentication:** Auth.js with WorkOS
- **Agent Runtime:** Cloudflare Agents SDK, Durable Objects, Workflows, and Queues
- **Agent Protocol:** Authenticated MCP over Streamable HTTP

<br /><br />

## Public Repositories

| Repository | Description |
| ------------ | ------------- |
| [`dusk-state`](https://github.com/dusk-state/dusk-state) | Main Turborepo webstack: public site, API, contracts, UI, domain-trust logic |
| [`tool-trust-feed`](https://github.com/dusk-state/tool-trust-feed) | Tool Trust & Terms Feed API and MCP server |
| [`agent-readiness-audit`](https://github.com/dusk-state/agent-readiness-audit) | Audit intake, scoring, and deliverable generation |
| [`vendor-pack`](https://github.com/dusk-state/vendor-pack) | Agent Vendor Pack generator and validator |
| [`mcp-schema-watcher`](https://github.com/dusk-state/mcp-schema-watcher) | MCP schema, description, and terms change detection |

<br /><br />

## Documentation

- [Dusk State Develop](https://duskstate.dev) — Primary documentation and product site
- [API Reference](https://duskstate.dev/api) — REST/OpenAPI and MCP tool documentation
- [Trust Records](https://duskstate.dev/records) — Public tool and service trust records

<br /><br />

## Security

Dusk State follows strict security and governance controls:

- Deny by default; authentication is not authorisation
- Human and machine principals use distinct identities
- Agents receive typed, scoped tools—not raw database or provider access
- Consequential mutations require explicit policy and, by default, recorded human approval
- Public facts, prices, terms, compatibility, and security claims require evidence and verification dates
- Secrets never enter source, logs, client bundles, `NEXT_PUBLIC_*`, Turbo cache, or public preview environments

Report security issues via [security@duskstate.dev](mailto:security@duskstate.dev).

<br /><br />

## Brand Identity

- **Master brand:** Dusk State
- **Wordmark:** DUSK STATE
- **Domain:** [duskstate.dev](https://duskstate.dev)
- **Package scope:** `@dusk-state/*`

The Dusk State mark is a state-transition symbol: outlined square (unresolved/discoverable) connected to solid square (resolved/verified). Primary presentation is near-black (`#060606`) on warm off-white (`#F1F1ED`). Typography uses Geist Sans and Geist Mono.

<br /><br />

## Contact

- **General enquiries:** [hello@duskstate.dev](mailto:hello@duskstate.dev)
- **Security reports:** [security@duskstate.dev](mailto:security@duskstate.dev)
- **Location:** England, United Kingdom

<br /><br />

---
© 2026 Dusk State. Independent technical publisher. All rights reserved.


