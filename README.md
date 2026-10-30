# Flashbots

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Flashbots is a research and development organization focused on mitigating the negative externalities of Maximal Extractable Value (MEV) on stateful blockchains, starting with Ethereum. Flashbots maintains and operates a set of public infrastructure: the Flashbots Auction JSON-RPC relay for bundle submission, Flashbots Protect RPC for private mempool transactions, the MEV-Share node and protocol for orderflow sharing, MEV-Boost middleware for validators, and SUAVE - an Ethereum-native, MEV-aware, privacy-first encrypted mempool.

**Areas:** MEV · Ethereum · Blockchain · JSON-RPC · Relay · MEV-Boost · MEV-Share · Flashbots Protect · SUAVE · Block Builders · Validator

## Flashbots on APIs.io

Everything profiled for Flashbots is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flashbots/](https://apis.io/providers/flashbots/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Flashbots Auction Relay (JSON-RPC)](https://apis.io/apis/flashbots/auction-relay/) — JSON-RPC endpoint for submitting bundles and private transactions to the Flashbots block builder. Supports eth_sendBundle, eth_callBundle, eth_cancelBundle,…
- [Flashbots Auction Relay (Sepolia Testnet)](https://apis.io/apis/flashbots/auction-relay-sepolia/) — Sepolia testnet instance of the Flashbots Auction JSON-RPC relay for bundle submission and testing without mainnet ETH.
- [Flashbots Protect RPC](https://apis.io/apis/flashbots/protect-rpc/) — Public-facing Ethereum JSON-RPC endpoint that routes transactions through Flashbots' private mempool to provide frontrunning protection, potential MEV and…
- [MEV-Share Node API](https://apis.io/apis/flashbots/mev-share-node/) — Public API for the MEV-Share node, an open-source protocol that lets users, wallets, and apps internalize MEV. Users send private transactions to the node,…
- [MEV-Boost Relay](https://apis.io/apis/flashbots/mev-boost-relay/) — Public Flashbots-operated relay used by MEV-Boost middleware. Aggregates blocks from many builders and presents the most profitable one to the proposing…
- [SUAVE](https://apis.io/apis/flashbots/suave/) — Single Unifying Auction for Value Expression - an Ethereum-native, MEV-aware, privacy-first encrypted mempool and decentralized block building network.…
- [Flashbots Auction & MEV Share Relay (JSON RPC) API](https://apis.io/apis/flashbots/flashbots-flashbots-auction-mev-share-relay-json-rpc-api/) — The Flashbots Auction & MEV Share Relay (JSON RPC) API from Flashbots — 1 operation(s) for flashbots auction & mev share relay (json rpc).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [flashbots](https://apis.io/servers/flashbots/flashbots/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Flashbots Agentic Access](https://apis.io/agentic-access/flashbots/flashbots-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Flashbots Auction & MEV-Share Relay (JSON-RPC)](https://apis.io/collections/flashbots/open-flashbots/)
- [Flashbots Auction & MEV-Share Relay (JSON-RPC) Flashbots Auction & MEV Share Relay (JSON RPC) Flashbots Auction & MEV Share Relay (JSON RPC) Flashbots Auction & MEV Share Relay (JSON RPC) API](https://apis.io/collections/flashbots/open-flashbots-flashbots-auction-mev-share-relay-json-rpc-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Flashbots — relay specs rules](https://apis.io/rules/flashbots/flashbots-relay-specs-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Flashbots Authentication](https://apis.io/security/flashbots/flashbots-authentication/)
- [Flashbots Domain Security](https://apis.io/security/flashbots/flashbots-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Flashbots Plans Pricing](https://apis.io/plans/flashbots/flashbots-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Flashbots Rate Limits](https://apis.io/rate-limits/flashbots/flashbots-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Flashbots Finops](https://apis.io/finops/flashbots/flashbots-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.flashbots.net)
- [Documentation](https://docs.flashbots.net)
- [Blog](https://writings.flashbots.net)
- [Terms of service](https://writings.flashbots.net/legal)

## API Evangelist rating

**Kin Score 34.1** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 53.3 |
| Contract governance | 45.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 47.6 |
| Access clarity | 5.3 |

**Agent readiness 47.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flashbots/](https://apis.io/providers/flashbots/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Flashbots: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flashbots/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
