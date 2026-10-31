# Pagar.me

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

Pagar.me is the API-first online payments platform from Stone Co., one of Brazil's largest financial technology companies. Often called "the Stripe of Brazil," Pagar.me provides Brazilian e-commerce merchants, marketplaces, SaaS companies, and subscription businesses with a single REST API and a set of official SDKs to accept credit and debit cards, Pix instant payments, boletos, vouchers, and digital wallets, with built-in 3DS 2.0 anti-fraud, payment splitting and recipient management for marketplaces, recurring billing through plans and subscriptions, anticipation of receivables, payment links, an embedded Checkout, and signed webhooks. The Pagar.me Core API v5 (2021-09-01) is the current stable surface, exposed at https://api.pagar.me/core/v5 with HTTP Basic authentication, and is backed by SDKs in Node.js, Python, PHP, Ruby, Java, .NET, and Go. Pagar.me is PCI DSS Level 1 certified and powers payments for Brazilian brands including Leroy Merlin, Casa & Vídeo, Polishop, Usaflex, and Catarse.

**Areas:** Payments · Financial Services · Fintech · Brazil · Latin America · Stone Co · Pix · Boleto · Credit Cards · Marketplace · Split Payments · Subscription

## Pagar.me on APIs.io

Everything profiled for Pagar.me is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pagar-me/](https://apis.io/providers/pagar-me/)** — or go straight to one of the APIs or properties below.

### APIs (30)

- [Pagar.me Orders API](https://apis.io/apis/pagar-me/pagarme-orders-api/) — Create, list, retrieve, and manage orders — the top-level payment object in the Pagar.me Core API v5. Each order can contain one or more charges paid via…
- [Pagar.me Charges API](https://apis.io/apis/pagar-me/pagarme-charges-api/) — Manage individual charges (cobranças) — the unit of capture inside an order. Get a charge, edit its payment method or saved card, capture a pre-authorized…
- [Pagar.me Customers API](https://apis.io/apis/pagar-me/pagarme-customers-api/) — Create and manage end-customer (buyer) records — personal data, CPF/CNPJ, contact info, and addresses — so that orders, subscriptions, and saved cards can…
- [Pagar.me Cards API](https://apis.io/apis/pagar-me/pagarme-cards-api/) — Tokenize, save, and edit credit/debit cards inside a Pagar.me customer wallet, off-load PCI scope, and reuse cards for one-click buy and recurring charges.…
- [Pagar.me Plans API](https://apis.io/apis/pagar-me/pagarme-plans-api/) — Define reusable recurring billing plans — pricing, billing cycle (days/weeks/months), trial period, installment count, accepted payment methods, and items —…
- [Pagar.me Subscriptions API](https://apis.io/apis/pagar-me/pagarme-subscriptions-api/) — Create customer subscriptions either from a saved plan or as standalone (avulsa) subscriptions, renew billing cycles, edit payment method / card / discount…
- [Pagar.me Recipients API](https://apis.io/apis/pagar-me/pagarme-recipients-api/) — Onboard and manage recipients (recebedores) — the sub-merchants that receive split payments in a marketplace. Create the recipient, run the KYC / prova de…
- [Pagar.me Transfers API](https://apis.io/apis/pagar-me/pagarme-transfers-api/) — Create, cancel, list, and retrieve transfers from a recipient's Pagar.me balance to their registered bank account, plus pull the official transfer receipt…
- [Pagar.me Balance Operations API](https://apis.io/apis/pagar-me/pagarme-balance-operations-api/) — Inspect the per-recipient balance ledger — every credit, debit, fee, refund, chargeback, anticipation, transfer, and adjustment that moves money in or out…
- [Pagar.me Receivables API](https://apis.io/apis/pagar-me/pagarme-receivables-api/) — List the merchant's future receivables — the installments of credit-card sales that will settle over the coming weeks and months. The basis for cash-flow…
- [Pagar.me Anticipation API](https://apis.io/apis/pagar-me/pagarme-anticipation-api/) — Anticipate receivables (antecipação) — Pagar.me's working-capital product that lets a merchant or marketplace recipient pull future credit-card installments…
- [Pagar.me Settlements API](https://apis.io/apis/pagar-me/pagarme-settlements-api/) — Retrieve settlements (pagamentos) — the actual money movements out of Pagar.me to recipients — individually, in bulk, or scoped to a specific recipient.…
- [Pagar.me Disputes & Chargebacks API](https://apis.io/apis/pagar-me/pagarme-disputes-api/) — List and retrieve disputes (disputas) and chargebacks raised against the merchant's transactions, including the new chargeback-specific charge status. Lets…
- [Pagar.me Payment Links API](https://apis.io/apis/pagar-me/pagarme-payment-links-api/) — Generate, list, retrieve, activate, and cancel payment links — short URLs that wrap a Pagar.me Checkout for sale-by-link, WhatsApp commerce, Instagram bio…
- [Pagar.me Contracts & URs API](https://apis.io/apis/pagar-me/pagarme-contracts-api/) — Manage contract effects and Unidades de Recebíveis (URs) under the Brazilian Central Bank's Resoluções BCB 264 and 349 receivables-registry regime. List…
- [Pagar.me Webhooks API](https://apis.io/apis/pagar-me/pagarme-webhooks-api/) — Subscribe to and receive signed webhook events for every meaningful state change on Pagar.me — order.paid, charge.captured, charge.refunded,…
- [Pagar.me Hosted Checkout](https://apis.io/apis/pagar-me/pagarme-checkout-pagarme/) — Pagar.me's drop-in hosted Checkout. Embed Pagar.me's PCI-compliant payment form to take credit card, Pix, and boleto for one-off orders and subscriptions,…
- [Pagar.me Contestations API](https://apis.io/apis/pagar-me/pagar-me-contestations-api/) — The Contestations API from Pagar.me — 1 operation(s) for contestations.
- [Pagar.me Customers API](https://apis.io/apis/pagar-me/pagar-me-customers-api/) — The Customers API from Pagar.me — 2 operation(s) for customers.
- [Pagar.me Disputas API](https://apis.io/apis/pagar-me/pagar-me-disputas-api/) — Operações relacionadas à busca de disputas de chargeback. Aqui é possível ver o estado atual da disputa, histórico de eventos daquela disputa, dentre outras…
- [Pagar.me Hooks API](https://apis.io/apis/pagar-me/pagar-me-hooks-api/) — The Hooks API from Pagar.me — 3 operation(s) for hooks.
- [Pagar.me Invoices API](https://apis.io/apis/pagar-me/pagar-me-invoices-api/) — The Invoices API from Pagar.me — 3 operation(s) for invoices.
- [Pagar.me Orders API](https://apis.io/apis/pagar-me/pagar-me-orders-api/) — The Orders API from Pagar.me — 5 operation(s) for orders.
- [Pagar.me Paymentlinks API](https://apis.io/apis/pagar-me/pagar-me-paymentlinks-api/) — The Paymentlinks API from Pagar.me — 4 operation(s) for paymentlinks.
- [Pagar.me Plans API](https://apis.io/apis/pagar-me/pagar-me-plans-api/) — The Plans API from Pagar.me — 5 operation(s) for plans.
- [Pagar.me Recipients API](https://apis.io/apis/pagar-me/pagar-me-recipients-api/) — The Recipients API from Pagar.me — 7 operation(s) for recipients.
- [Pagar.me Settlement Obligations API](https://apis.io/apis/pagar-me/pagar-me-settlement-obligations-api/) — The Settlement Obligations API from Pagar.me — 2 operation(s) for settlement obligations.
- [Pagar.me Settlements API](https://apis.io/apis/pagar-me/pagar-me-settlements-api/) — The Settlements API from Pagar.me — 2 operation(s) for settlements.
- [Pagar.me Subscriptions API](https://apis.io/apis/pagar-me/pagar-me-subscriptions-api/) — The Subscriptions API from Pagar.me — 17 operation(s) for subscriptions.
- [Pagar.me Tokens API](https://apis.io/apis/pagar-me/pagar-me-tokens-api/) — The Tokens API from Pagar.me — 1 operation(s) for tokens.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [pagar-me-mcp.yml](https://apis.io/servers/pagar-me/pagar-me-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Pagar Me Agentic Access](https://apis.io/agentic-access/pagar-me/pagar-me-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Dispute](https://apis.io/schemas/pagar-me/pagar-me-dispute/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Pagar Me Context](https://apis.io/jsonld/pagar-me/pagar-me-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Pagar.me API Rules](https://apis.io/rules/pagar-me/pagar-me-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Pagar Me Authentication](https://apis.io/security/pagar-me/pagar-me-authentication/)
- [Pagar Me Domain Security](https://apis.io/security/pagar-me/pagar-me-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Pagar Me Plans Pricing](https://apis.io/plans/pagar-me/pagar-me-plans-pricing/)

#### FinOps (1)

What the API costs to run, by operation.

- [Pagar Me Finops](https://apis.io/finops/pagar-me/pagar-me-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://pagar.me)
- [Documentation](https://docs.pagar.me)
- [Getting started](https://docs.pagar.me/reference/getting-started-with-your-api)
- [API reference](https://docs.pagar.me/reference)
- [Pricing](https://www.pagar.me/ofertas)
- [Support](https://pagarme.helpjuice.com/)
- [Blog](https://pagar.me/blog)
- [GitHub](https://github.com/pagarme)
- [Status](https://status.pagar.me/)

## API Evangelist rating

**Kin Score 49.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 60.7 |
| Contract governance | 22.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 81.0 |
| Access clarity | 31.6 |

**Agent readiness 33.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pagar-me/](https://apis.io/providers/pagar-me/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Pagar.me: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pagar-me/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
