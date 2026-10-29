# Crypto.com

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

Crypto.com is a cryptocurrency exchange, brokerage and payments company serving retail and institutional customers across spot, margin and derivatives trading, staking, custody, card and payment acceptance, and on-chain development on the Cronos EVM and Cronos zkEVM networks. Its public developer surface spans four programmable products: the Crypto.com Exchange API v1 (REST, WebSocket and FIX 4.4) for market data, order entry, advanced OCO/OTO/OTOCO orders, trading bots, portfolio, wallet and staking operations; the Crypto.com Pay API for merchant payment acceptance, refunds, subscriptions and invoicing with webhooks and idempotent refunds; the Crypto.com Developer Platform API for Cronos tokens, contracts, transactions, blocks, wallets, CronosID and DeFi; and an agent layer consisting of a published MCP server, an agent-first Rust CLI, and provider-authored Agent Skills for trading through the Crypto.com App and Exchange.

**Areas:** Cryptocurrency · Cryptocurrency Exchange · Trading · Derivatives · Market Data · Digital Assets · Payments · Merchant Payments · Blockchain · cronos · DeFi · Staking

## Crypto.com on APIs.io

Everything profiled for Crypto.com is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/crypto-com/](https://apis.io/providers/crypto-com/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Crypto.com Exchange WebSocket API v1](https://apis.io/apis/crypto-com/cryptocom-exchange-websocket-api-v1/) — WebSocket API for the Crypto.com Exchange, split into a Market Data stream (public channels for book, ticker, trade, candlestick, index, mark price,…
- [Crypto.com Exchange FIX API](https://apis.io/apis/crypto-com/cryptocom-exchange-fix-api/) — FIX 4.4-based API for institutional order entry, market data and drop copy on the Crypto.com Exchange, with tags borrowed from later FIX versions. Covers…
- [Crypto.com Pay API](https://apis.io/apis/crypto-com/cryptocom-pay-api/) — Merchant payments API for accepting cryptocurrency payments, issuing refunds, running subscriptions and recurring invoices, managing customers, products and…
- [Crypto.com Developer Platform API](https://apis.io/apis/crypto-com/cryptocom-developer-platform-api/) — On-chain developer platform service API for Cronos EVM and Cronos zkEVM, exposing native and ERC-20 token balances and transfers, smart contract ABI and…
- [Crypto.com Account Balance and Positions API](https://apis.io/apis/crypto-com/crypto-com-account-balance-and-positions-api/) — Retrieve real-time and historical snapshots of wallet balances, open positions, margin requirements, and collateral status. Use these endpoints to monitor…
- [Crypto.com Advanced Order Management API](https://apis.io/apis/crypto-com/crypto-com-advanced-order-management-api/) — Advanced Order Management provides trigger orders and multi-leg execution strategies beyond basic LIMIT and MARKET orders. Use these endpoints for…
- [Crypto.com Crypto Wallet API](https://apis.io/apis/crypto-com/crypto-com-crypto-wallet-api/) — Manages the user's wallet. Most of the endpoints are only available at master account level. Some endpoints requires Withdrawal setting to be enabled for…
- [Crypto.com Fiat Wallet API](https://apis.io/apis/crypto-com/crypto-com-fiat-wallet-api/) — Manages the user's fiat wallet. Most of the endpoints are only available at master account level. Some endpoints requires Withdrawal setting to be enabled…
- [Crypto.com OTC RFQ for Taker API](https://apis.io/apis/crypto-com/crypto-com-otc-rfq-for-taker-api/) — OTC RFQ (Request For Quote) enables takers to request block trade quotes from multiple liquidity providers, evaluate received quotes, and execute trades at…
- [Crypto.com Reference and Market Data API](https://apis.io/apis/crypto-com/crypto-com-reference-and-market-data-api/) — Reference and market data endpoints provide public, unauthenticated access to instrument metadata, real-time market data, and historical pricing…
- [Crypto.com Staking API](https://apis.io/apis/crypto-com/crypto-com-staking-api/) — Stake crypto assets on-chain to earn rewards directly from the Exchange. Staking locks your tokens for a period, during which you earn periodic rewards.…
- [Crypto.com Trading API](https://apis.io/apis/crypto-com/crypto-com-trading-api/) — Private trading endpoints manage order placement and lifecycle. All order operations (create, amend, cancel) are asynchronous — the REST response confirms…
- [Crypto.com Trading Bot API](https://apis.io/apis/crypto-com/crypto-com-trading-bot-api-api/) — Manage automated trading bots including DCA (Dollar-Cost Averaging), TWAP (Time-Weighted Average Price), GRID, and Funding Arbitrage strategies. ## Bot…
- [Crypto.com Transaction History API](https://apis.io/apis/crypto-com/crypto-com-transaction-history-api/) — History will be stored for recent 6 months record only. For records over 6 months, please contact our support team.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Crypto Com Event Surface](https://apis.io/asyncapis/crypto-com/crypto-com-event-surface/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [cdcx](https://apis.io/servers/crypto-com/cdcx/)

#### Collections (1)

Postman and Open Collection request collections.

- [Crypto.com Exchange API v1](https://apis.io/collections/crypto-com/open-crypto-com-exchange/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Crypto Com Exchange Overlay](https://apis.io/overlays/crypto-com/crypto-com-exchange-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Crypto Com Authentication](https://apis.io/security/crypto-com/crypto-com-authentication/)
- [Crypto Com Domain Security](https://apis.io/security/crypto-com/crypto-com-domain-security/)
- [Crypto Com Trust Center](https://apis.io/security/crypto-com/crypto-com-trust-center/)
- [Crypto Com Vulnerability Disclosure](https://apis.io/security/crypto-com/crypto-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Crypto Com Plans Pricing](https://apis.io/plans/crypto-com/crypto-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Crypto Com Rate Limits](https://apis.io/rate-limits/crypto-com/crypto-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://crypto.com/)
- [Documentation](https://exchange-developer.crypto.com/exchange/v1/docs/api/rest-introduction)
- [Getting started](https://exchange-developer.crypto.com/exchange/v1/docs/api/rest-common-api-reference)
- [API reference](https://exchange-developer.crypto.com/exchange/v1/docs/api/rest/crypto-com-exchange-api-v-1)
- [Pricing](https://crypto.com/exchange/fee)
- [Sign up](https://crypto.com/exchange/signup)
- [Support](https://help.crypto.com/en/)
- [Blog](https://crypto.com/en/product-news)
- [Security](https://help.crypto.com/en/articles/9154034-vulnerability-disclosure-and-bug-bounty)
- [Compliance](https://crypto.com/en/security)
- [Trust centre](https://crypto.com/en/security)
- [Terms of service](https://crypto.com/exchange/terms)
- [Privacy policy](https://crypto.com/en/privacy)
- [GitHub](https://github.com/crypto-com)
- [Status](https://status.crypto.com/)

## API Evangelist rating

**Kin Score 65.6** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 63.3 |
| Contract quality | 55.2 |
| Contract governance | 18.2 |
| Operational transparency | 92.1 |
| Developer ergonomics | 85.7 |
| Access clarity | 60.5 |

**Agent readiness 46.3** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 38.9** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/crypto-com/](https://apis.io/providers/crypto-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Crypto.com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/crypto-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
