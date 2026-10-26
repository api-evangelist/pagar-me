# Pagar.me (pagar-me)

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

Pagar.me is the API-first online payments platform from **Stone Co.**, one of Brazil's largest financial technology companies — often referred to as "the Stripe of Brazil." A single Core API v5 surface (and a fleet of official SDKs) lets Brazilian e-commerce merchants, marketplaces, SaaS companies, and subscription businesses accept credit and debit cards, **Pix** instant payments, **boletos**, vouchers, and digital wallets, with built-in 3DS 2.0 anti-fraud, payment splitting and recipient management for marketplaces, recurring billing through plans and subscriptions, anticipation of receivables, payment links, an embedded Checkout, and signed webhooks. Pagar.me is PCI DSS Level 1 certified and powers payments for Brazilian brands including Leroy Merlin, Casa & Vídeo, Polishop, Usaflex, and Catarse.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/pagar-me/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Payments, Financial Services, Fintech, Brazil, Latin America, Stone Co, Pix, Boleto, Credit Card, Marketplace, Split Payments, Subscriptions, Recurring Billing, Anti-Fraud, 3DS, Checkout, Payment Links, Webhooks, E-commerce, Anticipation

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Platform at a glance

| Surface | What it is |
|---|---|
| Base URL | `https://api.pagar.me/core/v5` |
| Current version | Core API **v5** (2021-09-01) — legacy v1–v4 still accessible |
| Auth | HTTP **Basic** with a Pagar.me API key (Access Keys) |
| Docs | [docs.pagar.me](https://docs.pagar.me) (guides) + [docs.pagar.me/reference](https://docs.pagar.me/reference) (reference) |
| Agent index | [`docs.pagar.me/llms.txt`](https://docs.pagar.me/llms.txt) — Markdown index of every doc page and OpenAPI endpoint |
| SDKs | Node.js / TypeScript, Python, PHP, Ruby, Java, .NET Standard, Go |
| Modules | Magento 2 / Adobe Commerce, WooCommerce, VTEX, Nuvemshop, Shopify |
| Compliance | PCI DSS Level 1; Res. BCB 264 / 349 receivables registry |
| Parent | **Stone Co.** (NASDAQ: STNE) |

## APIs

### Pagar.me Orders API
Top-level payment object in Core API v5. Create orders containing one or more charges paid via credit/debit card, Pix, boleto, voucher, Google Pay, or private label card; manage cancellation, capture, refund, items, customers, and split rules for marketplaces.

- [Reference — Create order](https://docs.pagar.me/reference/criar-pedido-2)
- Payment methods: [credit card](https://docs.pagar.me/reference/cartão-de-crédito-1), [debit card](https://docs.pagar.me/reference/cartão-de-débito-2), [Pix](https://docs.pagar.me/reference/pix-2), [boleto](https://docs.pagar.me/reference/boleto-1), [voucher](https://docs.pagar.me/reference/voucher-1), [Google Pay](https://docs.pagar.me/reference/google-paytm-api)

### Pagar.me Charges API
Manage individual charges (cobranças) — the unit of capture inside an order. Get, edit payment method or saved card, capture pre-authorized amounts, refund all or part of a charge, and track the chargeback lifecycle.

- [Reference — Charges](https://docs.pagar.me/reference/obter-cobrança)

### Pagar.me Customers API
Create and manage end-customer (buyer) records — personal data, CPF/CNPJ, contact info, and addresses — and tie them to orders, subscriptions, and saved cards. Underpins the customer wallet / one-click-buy experience.

- [Reference — Create customer](https://docs.pagar.me/reference/criar-cliente-1)

### Pagar.me Cards API
Tokenize, save, and edit credit/debit cards inside a Pagar.me customer wallet, off-load PCI scope, and reuse cards for one-click buy and recurring charges. Supports network tokens (token de bandeira) and the Card Updater service.

- [Reference — Cards object](https://docs.pagar.me/reference/cartões-1)
- [Card Updater](https://docs.pagar.me/docs/card-updater)

### Pagar.me Plans API
Define reusable recurring billing plans — pricing, billing cycle, trial period, installment count, accepted payment methods, items — to back subscription products.

- [Reference — Plans object](https://docs.pagar.me/reference/planos-1)

### Pagar.me Subscriptions API
Create customer subscriptions from a plan or standalone (avulsa), renew cycles, edit payment method / card / discount / minimum price, change items, and inspect each cycle's invoice and charges. Powers SaaS, streaming, education, and club-of-the-month businesses on Pagar.me.

- [Reference — Subscriptions object](https://docs.pagar.me/reference/assinaturas-1)
- [Reference — Create subscription from plan](https://docs.pagar.me/reference/criar-assinatura-de-plano-1)

### Pagar.me Recipients API
Onboard and manage recipients (recebedores) — the sub-merchants that receive split payments in a marketplace. Run the KYC / prova de vida flow, attach bank accounts, configure transfer settings, and create KYC links.

- [Reference — Recipients object](https://docs.pagar.me/reference/recebedores-1)
- [Recipients guide](https://docs.pagar.me/docs/recebedores-2)

### Pagar.me Transfers API
Create, cancel, list, and retrieve transfers from a recipient's Pagar.me balance to their registered bank account, plus pull the official transfer receipt (comprovante).

- [Reference — Transfer object](https://docs.pagar.me/reference/objeto-transferência)

### Pagar.me Balance Operations API
The per-recipient balance ledger — every credit, debit, fee, refund, chargeback, anticipation, transfer, and adjustment that moves money in or out of a Pagar.me account. Canonical source of truth for finance reconciliation.

- [Reference — Balance operations](https://docs.pagar.me/reference/operação-de-saldo)

### Pagar.me Receivables API
List future receivables — installments of credit-card sales that will settle over the coming weeks and months. Basis for cash-flow forecasting and anticipation simulation.

- [Reference — Receivables](https://docs.pagar.me/reference/retornando-recebíveis)

### Pagar.me Anticipation API
Pagar.me's working-capital product — pull future credit-card installments to today's balance for a fee. Spot simulation, limits inspection, create, list, and cancel pending anticipations.

- [Reference — Anticipation object](https://docs.pagar.me/reference/objeto-antecipação)
- [Anticipation quick guide](https://docs.pagar.me/guia-rápido-sobre-antecipações)

### Pagar.me Settlements API
Retrieve settlements (pagamentos) — the actual money movements out of Pagar.me to recipients — individually, in bulk, or by recipient.

- [Reference — Settlements object](https://docs.pagar.me/reference/objeto-settlements)

### Pagar.me Disputes & Chargebacks API
List and retrieve disputes (disputas) and chargebacks raised against the merchant's transactions, including the new chargeback-specific charge status.

- [Reference — Disputes](https://docs.pagar.me/reference/disputas)

### Pagar.me Payment Links API
Generate, list, retrieve, activate, and cancel payment links — short URLs that wrap a Pagar.me Checkout for sale-by-link, WhatsApp commerce, Instagram bio links, and lightweight invoicing.

- [Reference — Payment link object](https://docs.pagar.me/reference/checkout-link)
- [Reference — Create link](https://docs.pagar.me/reference/criar-link)

### Pagar.me Contracts & URs API
Contract effects and Unidades de Recebíveis (URs) under the Brazilian Central Bank's Resoluções BCB 264 and 349 receivables-registry regime — list contract effects, contest a contract, list contests, pull URs by recipient.

- [Reference — Contract effects v5](https://docs.pagar.me/reference/retornando-efeitos-de-contratos-v5)
- [Reference — Res. 264/349 manual](https://docs.pagar.me/reference/res264346-manual-de-integração)

### Pagar.me Webhooks API
Subscribe to and receive signed webhook events — `order.paid`, `charge.captured`, `charge.refunded`, `subscription.created`, `recipient.kyc_updated`, `dispute.opened`, and the rest of the catalog.

- [Webhooks overview](https://docs.pagar.me/reference/visão-geral-sobre-webhooks)
- [Webhook events](https://docs.pagar.me/reference/eventos-de-webhook-1)
- [Webhooks guide](https://docs.pagar.me/docs/webhooks)

### Pagar.me Hosted Checkout
Pagar.me's drop-in PCI-compliant payment form for one-off orders and subscriptions, with first-class AI/agent integration patterns (Claude Code, Codex, Cursor, Copilot) documented as **Checkout Skills**.

- [Checkout overview](https://docs.pagar.me/docs/checkout-use)
- [Connect Checkout using AI](https://docs.pagar.me/docs/conecte-o-checkout-pagarme-usando-ia)
- [Checkout Skill — Orders](https://docs.pagar.me/docs/checkout_pagarme_skill_order)
- [Checkout Skill — Subscriptions](https://docs.pagar.me/docs/checkout_pagarme_skill_subscription)

## Brazilian payment methods

| Method | Reference |
|---|---|
| Credit card | [docs.pagar.me/reference/cartão-de-crédito-1](https://docs.pagar.me/reference/cartão-de-crédito-1) |
| Debit card | [docs.pagar.me/reference/cartão-de-débito-2](https://docs.pagar.me/reference/cartão-de-débito-2) |
| Pix | [docs.pagar.me/reference/pix-2](https://docs.pagar.me/reference/pix-2) · [Pix guide](https://docs.pagar.me/docs/pix-1) · [Pix simulator](https://docs.pagar.me/docs/simulador-pix) |
| Boleto | [docs.pagar.me/reference/boleto-1](https://docs.pagar.me/reference/boleto-1) |
| Voucher | [docs.pagar.me/reference/voucher-1](https://docs.pagar.me/reference/voucher-1) |
| Google Pay | [docs.pagar.me/reference/google-paytm-api](https://docs.pagar.me/reference/google-paytm-api) · [Google Pay guide](https://docs.pagar.me/docs/google-pay-tm-guide) |
| Private label card | [docs.pagar.me/reference/cartão-private-label-2](https://docs.pagar.me/reference/cartão-private-label-2) |

## SDKs

| Language | Repo |
|---|---|
| Node.js / TypeScript | [pagarme/pagarme-nodejs-sdk](https://github.com/pagarme/pagarme-nodejs-sdk) |
| Python | [pagarme/pagarme-python-sdk](https://github.com/pagarme/pagarme-python-sdk) |
| PHP | [pagarme/pagarme-php-sdk](https://github.com/pagarme/pagarme-php-sdk) |
| Ruby | [pagarme/pagarme-ruby-sdk](https://github.com/pagarme/pagarme-ruby-sdk) |
| Java | [pagarme/pagarme-java-sdk](https://github.com/pagarme/pagarme-java-sdk) |
| .NET Standard | [pagarme/pagarme-net-standard-sdk](https://github.com/pagarme/pagarme-net-standard-sdk) |
| Go | [pagarme/pagarme-core-api-go](https://github.com/pagarme/pagarme-core-api-go) |

## E-commerce platform modules

- [Magento 2 / Adobe Commerce](https://github.com/pagarme/magento2) — [guide](https://docs.pagar.me/docs/magento-2-overview)
- [WooCommerce](https://github.com/pagarme/woocommerce) — [guide](https://docs.pagar.me/docs/woocommerce-introdução)
- [VTEX](https://docs.pagar.me/docs/ativação-de-funcionalidades-vtex) — [marketplace sellers](https://docs.pagar.me/docs/vtex-sellers-marketplace)
- [Nuvemshop](https://docs.pagar.me/docs/instalando-o-aplicativo-ns)
- [Shopify](https://docs.pagar.me/docs/shopify)
- [E-commerce Module Core (PHP)](https://github.com/pagarme/ecommerce-module-core)

## Common links

- [Pagar.me Portal](https://pagar.me)
- [Documentation](https://docs.pagar.me)
- [API Reference](https://docs.pagar.me/reference)
- [Getting Started with the API](https://docs.pagar.me/reference/getting-started-with-your-api)
- [Access Keys (Auth)](https://docs.pagar.me/docs/chaves-de-acesso)
- [Rate Limits](https://docs.pagar.me/reference/rate-limit)
- [Security & PCI](https://docs.pagar.me/reference/segurança-1)
- [IP Allowlist](https://docs.pagar.me/docs/ip-allowlist)
- [3DS 2.0 Authentication](https://docs.pagar.me/docs/autenticação-via-3ds)
- [Help Center](https://pagarme.helpjuice.com/)
- [Sign In](https://id.pagar.me/signin)
- [Pricing / Offers](https://www.pagar.me/ofertas)
- [llms.txt (AI agent index)](https://docs.pagar.me/llms.txt)
- [GitHub — pagarme](https://github.com/pagarme)

## Reference profiles

- [api-evangelist/anthropic](https://github.com/api-evangelist/anthropic) — Claude is one of the AI coding assistants Pagar.me explicitly targets in its Checkout Skills and llms.txt-driven integration patterns for AI-assisted payment integration.
