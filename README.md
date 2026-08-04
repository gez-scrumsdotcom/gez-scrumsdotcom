<h1 align="center">Gerald Neves</h1>
<p align="center"><strong>CEO, Scrums.com</strong> — building the Software Engineering Orchestration Platform.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Software%20Engineering.-Sorted.-135BFF?style=for-the-badge&labelColor=0A0A0A" alt="Software Engineering. Sorted." />
  <img src="https://img.shields.io/badge/Scrums.com-SEOP-135BFF?style=for-the-badge&labelColor=0A0A0A" alt="Scrums.com SEOP" />
  <img src="https://img.shields.io/badge/Company--as--Code-open%20source-135BFF?style=for-the-badge&labelColor=0A0A0A" alt="Company-as-Code" />
</p>

<p align="center">
  <a href="https://www.scrums.com"><img src="https://img.shields.io/badge/scrums.com-135BFF?style=flat-square&logo=googlechrome&logoColor=white&labelColor=0A0A0A" alt="scrums.com" /></a>
  <a href="https://www.linkedin.com/company/scrums-com/"><img src="https://img.shields.io/badge/LinkedIn-135BFF?style=flat-square&logo=linkedin&logoColor=white&labelColor=0A0A0A" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/London%20··%20New%20York%20·%20Joburg%20·%20Nairobi%20·%20Cape%20Town-135BFF?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0A0A0A" alt="Locations" />
  <img src="https://img.shields.io/badge/Sorted%20by-Sudo.-135BFF?style=flat-square&labelColor=0A0A0A" alt="Sorted by Sudo." />
</p>

---

## The mission

Software delivery is not a services problem. It is an orchestration problem.

Scrums.com is an AI-native **Software Engineering Orchestration Platform (SEOP)**. It helps organizations plan, build, scale, and operate software products, platforms, and technology capabilities through coordinated orchestration of AI agents, engineering talent, delivery teams, tooling, and infrastructure.

It serves founders, executives, private-equity firms, venture-backed companies, and enterprise leadership teams running software at scale — engineering organizations from 20 to 5,000 engineers across North America, the UK, and South Africa, with concentration in FinTech and scaling technology businesses.

Five product lines. One orchestration layer.

<p>
  <img src="https://img.shields.io/badge/Talent-135BFF?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Delivery-135BFF?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Infra-135BFF?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/AI%20Agents-135BFF?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/SaaS-135BFF?style=for-the-badge&labelColor=0A0A0A" />
</p>

---

## Company-as-Code

Most companies run on tools. We run on a repo.

**Company-as-Code (C-as-C)** treats the entire business as an agent-orchestrated, AI-native operating system. The org chart, the SOPs, the state machine, the SKU taxonomy — declarative, version-controlled, machine-readable, forkable. Infrastructure-as-code, applied one layer up.

Two front doors. One backend.

```
scrums.ai/
├── orchestrator/                 # canonical state
├── observability/                # metrics, OKRs, delivery signal
└── domains/
    └── {domain}/
        ├── context/
        │   ├── wiki.md           # strategy, SOPs, constraints
        │   ├── tasks.md          # current state, in flight
        │   └── skills.md         # compounding execution memory
        └── agents/
            └── {agent}/
                └── context.md    # policy contract
```

`domains.yaml` is the single source of truth. Every other surface is a generated artifact.

**The invariants:**

| Principle | What it means |
|---|---|
| Unidirectional mutation | All state originates platform-layer downward. Downstream systems read and report. They never write upstream. |
| Coordinate, never replicate | DB holds canonical codes and cross-system IDs. Not copies. |
| Vocabulary is never unified | Only meaning is. Deterministic mapping tables bridge incompatible state models. |
| Enforce with mechanism, not instruction | Prose is guidance. Worktrees, allocators, gates and branch protection are enforcement. |
| Curation precedes automation | Automation follows hardening. Never the reverse. |

Open-sourcing the substrate: the `domains.yaml` spec, the agent gateway spec, and the SKU taxonomy. Releases the substrate and powering the network growth. The intelligence telemetry layer stays Scrums.com.

<p>
  <img src="https://img.shields.io/badge/domains.yaml-spec-135BFF?style=flat-square&logo=yaml&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Agent%20Gateway-spec-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/SKU%20Taxonomy-open-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/A2A%20Procurement-MCP-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/licence-MIT-135BFF?style=flat-square&labelColor=0A0A0A" />
</p>

---

## Agent Arbiter 

Agentic Swarms don't fail on capability. They fail on collision, especially in teh enterprise.

**Agent Arbiter**  resolves conflicts in multi-agent systems by selecting the agent with explicit authority, based on real-world structures such as roles, contracts, and system ownership.
https://github.com/gez-scrumsdotcom/agent-arbiter
```
Orchestrator            decompose → dispatch → integrate
├── Context Broker      serves slice contracts, read-only
├── Worker A/B/C        isolated worktree, isolated branch
└── Merge Gate          arbiter → scope check → port scan → skills writer
```

Blast radius is enforced by the gate, not requested in a prompt. Anything you can only enforce with words will eventually be violated.

<p>
  <img src="https://img.shields.io/badge/Merge%20Gate-serialised-135BFF?style=flat-square&logo=git&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Scope-diff--bounded-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Memory-skills.md-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Review-human%20in%20loop-135BFF?style=flat-square&labelColor=0A0A0A" />
</p>

---

## Stack

**Platform & runtime**

<p>
  <img src="https://img.shields.io/badge/TypeScript-135BFF?style=flat-square&logo=typescript&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Node.js-135BFF?style=flat-square&logo=nodedotjs&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Hono-135BFF?style=flat-square&logo=hono&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Next.js-135BFF?style=flat-square&logo=nextdotjs&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Turborepo-135BFF?style=flat-square&logo=turborepo&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Python-135BFF?style=flat-square&logo=python&logoColor=white&labelColor=0A0A0A" />
</p>

**Data & state**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-135BFF?style=flat-square&logo=postgresql&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Prisma-135BFF?style=flat-square&logo=prisma&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Windmill-135BFF?style=flat-square&labelColor=0A0A0A" />
</p>

**Agents**

<p>
  <img src="https://img.shields.io/badge/Devin-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Codex-135BFF?style=flat-square&logo=openai&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Claude%20Code-135BFF?style=flat-square&logo=anthropic&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/MCP-135BFF?style=flat-square&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Open%20Weights-135BFF?style=flat-square&logo=huggingface&logoColor=white&labelColor=0A0A0A" />
</p>

**Infra & delivery**

<p>
  <img src="https://img.shields.io/badge/GitHub%20Actions-135BFF?style=flat-square&logo=githubactions&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Codespaces-135BFF?style=flat-square&logo=github&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Docker-135BFF?style=flat-square&logo=docker&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Cloudflare-135BFF?style=flat-square&logo=cloudflare&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Railway-135BFF?style=flat-square&logo=railway&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Auth0-135BFF?style=flat-square&logo=auth0&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/AWS-135BFF?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Google%20Cloud-135BFF?style=flat-square&logo=googlecloud&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Vercel-135BFF?style=flat-square&logo=vercel&logoColor=white&labelColor=0A0A0A" />
</p>

**Business systems**

<p>
  <img src="https://img.shields.io/badge/HubSpot-135BFF?style=flat-square&logo=hubspot&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/ClickUp-135BFF?style=flat-square&logo=clickup&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/PostHog-135BFF?style=flat-square&logo=posthog&logoColor=white&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Orb-135BFF?style=flat-square&labelColor=0A0A0A" />
</p>

---

## Entity

<details>
<summary><strong>Canonical record</strong></summary>

<br />

| Field | Value |
|---|---|
| Name | Gerald Neves |
| Role | CEO, Scrums.com |
| Organization | Scrums.com |
| Formerly | SovTech — rebranded October 2024 |
| Category | Software Engineering Orchestration Platform (SEOP) |
| Headquarters | London, United Kingdom |
| Operations | South Africa, Nigeria, Kenya, Ghana, Uganda, Ireland, UAE, USA |
| Markets served | North America, United Kingdom, South Africa |
| Product lines | Talent · Delivery · Infra · AI Agents · SaaS |
| Commit verb | Deploy |
| Agent | Sudo |

```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Gerald Neves",
  "alternateName": "Gez",
  "jobTitle": "Chief Executive Officer",
  "worksFor": {
    "@type": "Organization",
    "name": "Scrums.com",
    "alternateName": "SovTech",
    "url": "https://www.scrums.com",
    "description": "AI-native Software Engineering Orchestration Platform (SEOP)."
  },
  "knowsAbout": [
    "Software Engineering Orchestration",
    "Company-as-Code",
    "Agent Orchestration",
    "Managed Marketplaces",
    "Platform Architecture"
  ]
}
```

</details>

---

## Shipping

- Company-as-Code substrate — forkable, open, adoptable beyond Scrums.com
- Managed marketplace catalog — page → API → MCP, so agents can procure directly
- Observability layer — canonical metrics, one source of truth, no dashboard theatre
- The Sudo Swarm — one orchestrates, many execute

<p>
  <img src="https://img.shields.io/badge/Deploy-135BFF?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Sudo%20gets%20it-sorted.-135BFF?style=for-the-badge&labelColor=0A0A0A" />
</p>
