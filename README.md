# Awesome AI Shopping Agents

### TRY [Kael.im](https://kael.im/home)(NotebookLM slides alternative) and register at this link for 100 pages free daily quota (nbp)!

A curated list of AI shopping agents, platform policies, and the emerging agentic commerce landscape.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> AI shopping agents autonomously browse, compare, and purchase products on your behalf. In March 2026, major platforms began restricting third-party agents while building their own. This list tracks the agents, the policies, and the protocols shaping this space.

## Contents

- [The Agents](#the-agents)
- [Platform Policies](#platform-policies)
- [Protocols and Standards](#protocols-and-standards)
- [Key Events Timeline](#key-events-timeline)
- [Contributing](#contributing)

---

## The Agents

| Agent | Builder | Type | Key Features | Open Source |
|-------|---------|------|-------------|-------------|
| **Operator** | OpenAI | Browser agent | Autonomous web browsing, form filling, multi-step purchases | No |
| **Perplexity Shopping** | Perplexity AI | Search + buy | Product search, price comparison, one-click buy | No |
| **Google Shopping AI** | Google | Search integration | Built into Google Search, visual product matching, price tracking | No |
| **Rufus** | Amazon | In-app assistant | Product Q&A, comparison, recommendation within Amazon | No |
| **ShopBot** | eBay | Buyer agent | Autonomous bidding, deal finding within eBay | No |
| **Klarna AI** | Klarna | Payment + shopping | Price comparison across retailers, payment integration | No |
| **MultiOn** | MultiOn | Browser automation | Works across any website, multi-tab shopping, autonomous checkout | No |
| **Agent Commerce Kit** | ACK Contributors | Toolkit | Open-source toolkit for building agentic commerce apps | [Yes](https://github.com/agentcommercekit/ack) |
| **Daydreams Skills Market** | Daydreams AI | Skills marketplace | Marketplace for agentic commerce skills and workflows | [Yes](https://github.com/daydreamsai/skills-market) |

---

## Platform Policies

As of March 2026, major e-commerce platforms are taking divergent approaches to AI shopping agents.

| Platform | Third-Party Agents | Own Agent | Policy Date | Notes |
|----------|-------------------|-----------|-------------|-------|
| **Amazon** | Blocked | Rufus (in-app) | March 2026 | Banned external AI agents. Invested $50B in OpenAI for agentic commerce. Updated ToS to disable external AI tools. |
| **eBay** | Blocked | ShopBot (in-app) | March 2026 | Launched own AI buyer agent. Blocked third-party agent access. |
| **Shopify** | Allowed | Sidekick (merchant-side) | Ongoing | Open to third-party agents via Storefront API. Sidekick assists merchants, not buyers. |
| **Walmart** | Limited | Internal pilots | 2025 | Limited API access for agents. Internal AI shopping experiments underway. |
| **Target** | No public policy | None announced | -- | No public stance on AI shopping agents as of March 2026. |

---

## Protocols and Standards

Emerging standards for how AI agents interact with commerce platforms.

| Protocol | Maintainers | Stars | Description |
|----------|------------|-------|-------------|
| **[Agentic Commerce Protocol (ACP)](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol)** | OpenAI, Stripe | 1,267 | Open standard for connecting buyers, AI agents, and businesses to complete purchases. Defines interaction models for agent-to-merchant communication. |
| **[Trusted Agent Protocol](https://github.com/visa/trusted-agent-protocol)** | Visa | 131 | Universal standard of trust between AI agents and merchants. Focuses on authentication, authorization, and transaction verification. |
| **[Agent Commerce Kit (ACK)](https://github.com/agentcommercekit/ack)** | Community | 132 | Open-source reference implementation for agentic commerce. Includes SDKs, examples, and integration patterns. |

---

## Key Events Timeline

| Date | Event |
|------|-------|
| **March 2026** | Amazon and eBay ban third-party AI shopping agents. Both launch proprietary alternatives. |
| **March 2026** | Agentic Commerce Protocol (ACP) by OpenAI and Stripe surpasses 1,200 GitHub stars. |
| **January 2026** | OpenAI launches Operator, a browser-based autonomous agent capable of shopping tasks. |
| **2025** | Perplexity adds shopping features with one-click purchasing integration. |
| **2025** | Klarna AI assistant handles 2/3 of customer service chats, expands to shopping. |
| **2024** | MultiOn demonstrates autonomous multi-site shopping agent in public demos. |
| **2024** | Amazon launches Rufus in-app shopping assistant to select markets. |

---

## Contributing

Contributions welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

**Inclusion criteria:**
- Agent must be a product or project focused on autonomous shopping
- Platform policies must be sourced from official announcements or reliable reporting
- Protocols must have a public repository
- We prioritize accuracy over comprehensiveness

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
