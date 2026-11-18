# Plaxswap

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

Plaxswap, operated by SAMZAL LLC, offers a decentralized crypto swap service, self‑custody wallet, payment gateway and payment links. Users can swap any coin directly to their wallet without an account, integrate payment APIs, and access a sandbox for testing. The platform emphasizes non‑custodial transactions, live pricing, and developer tools for embedding crypto payments.

**Areas:** Company · Crypto · Payments · Wallet · Swap

## Plaxswap on APIs.io

Everything profiled for Plaxswap is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/plaxswap-com/](https://apis.io/providers/plaxswap-com/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Plaxswap Accounts API](https://apis.io/apis/plaxswap-com/plaxswap-com-accounts-api/) — Optional accounts with no sign-up: order history, address book, referrals. The account key lives in an HttpOnly cookie; writes need x-px-account: 1.
- [Plaxswap Checkout API](https://apis.io/apis/plaxswap-com/plaxswap-com-checkout-api/) — What the hosted checkout page calls. No key; the payer's browser.
- [Plaxswap Merchant account API](https://apis.io/apis/plaxswap-com/plaxswap-com-merchant-account-api/) — Sign up, your account's settings, keys and webhook deliveries.
- [Plaxswap Orders API](https://apis.io/apis/plaxswap-com/plaxswap-com-orders-api/) — Reading and changing an order. Changes need the order token.
- [Plaxswap Partner portal API](https://apis.io/apis/plaxswap-com/plaxswap-com-partner-portal-api/) — Your volume, commission, webhook deliveries and withdrawals. Needs your API key.
- [Plaxswap Payment gateway API](https://apis.io/apis/plaxswap-com/plaxswap-com-payment-gateway-api/) — Accept crypto on your website: create a payment, send the payer to the hosted checkout, get a signed webhook. Needs your merchant key (pxs_live_... or…
- [Plaxswap Payment links API](https://apis.io/apis/plaxswap-com/plaxswap-com-payment-links-api/) — "Pay me exactly X of coin Y": links that anyone can pay with any supported coin.
- [Plaxswap Price alerts API](https://apis.io/apis/plaxswap-com/plaxswap-com-price-alerts-api/) — One Telegram message when a rate crosses a number.
- [Plaxswap Sandbox API](https://apis.io/apis/plaxswap-com/plaxswap-com-sandbox-api/) — Only where developer tools are on.
- [Plaxswap Service API](https://apis.io/apis/plaxswap-com/plaxswap-com-service-api/) — Mode, coins, status and policies. No authentication.
- [Plaxswap Support API](https://apis.io/apis/plaxswap-com/plaxswap-com-support-api/) — Support requests without an account, read on a private page.
- [Plaxswap Swaps API](https://apis.io/apis/plaxswap-com/plaxswap-com-swaps-api/) — Prices, quotes and new orders, and the website swap form's decentralized routes (/api/v1/dex). An API key is optional and adds your commission; on swap-form…
- [Plaxswap Webhooks API](https://apis.io/apis/plaxswap-com/plaxswap-com-webhooks-api/) — Signed POST requests to your webhook URL.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Plaxswap Com Webhooks](https://apis.io/asyncapis/plaxswap-com/plaxswap-com-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Plaxswap Agentic Access](https://apis.io/agentic-access/plaxswap-com/plaxswap-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CheckoutView](https://apis.io/schemas/plaxswap-com/plaxswap-com-checkout-view/)
- [CreateOrderRequest](https://apis.io/schemas/plaxswap-com/plaxswap-com-create-order-request/)
- [CreatePaymentRequest](https://apis.io/schemas/plaxswap-com/plaxswap-com-create-payment-request/)
- [MetaResponse](https://apis.io/schemas/plaxswap-com/plaxswap-com-meta-response/)
- [OrderView](https://apis.io/schemas/plaxswap-com/plaxswap-com-order-view/)
- [PaymentView](https://apis.io/schemas/plaxswap-com/plaxswap-com-payment-view/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Plaxswap Com Context](https://apis.io/jsonld/plaxswap-com/plaxswap-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Plaxswap API Rules](https://apis.io/rules/plaxswap-com/plaxswap-com-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Plaxswap Authentication](https://apis.io/security/plaxswap-com/plaxswap-com-authentication/)
- [Plaxswap Domain Security](https://apis.io/security/plaxswap-com/plaxswap-com-domain-security/)
- [Plaxswap Vulnerability Disclosure](https://apis.io/security/plaxswap-com/plaxswap-com-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://plaxswap.com)
- [Documentation](https://plaxswap.com/developers/payments)
- [API reference](https://plaxswap.com/developers)
- [Support](https://plaxswap.com/help)
- [Security](https://plaxswap.com/security)
- [Terms of service](https://plaxswap.com/legal/terms)
- [Privacy policy](https://plaxswap.com/legal/privacy)
- [Status](https://plaxswap.com/status)

## API Evangelist rating

**Kin Score 50.9** — developing · rubric 0.28.0 · scored 2026-11-18

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 67.7 |
| Contract governance | 79.1 |
| Operational transparency | 31.0 |
| Developer ergonomics | 39.8 |
| Access clarity | 17.0 |

**Agent readiness 48.1** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 27.7** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/plaxswap-com/](https://apis.io/providers/plaxswap-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Plaxswap: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/plaxswap-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
