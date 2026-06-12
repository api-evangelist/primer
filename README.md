# Primer (primer)

Primer is a payment orchestration platform that enables merchants to build flexible payment flows across multiple processors through a single REST API integration. The platform provides intelligent routing, automatic fallback logic, fraud detection integrations, and a no-code Workflows builder for managing payment rules without engineering effort. Primer supports 60+ payment methods including cards, digital wallets, and regional alternatives such as iDEAL, Klarna, and Alipay, and processes billions of dollars monthly with 99.99% uptime.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/primer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/primer/refs/heads/main/apis.yml)

**Naftiko:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=primer-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=primer-api-evangelist&utm_content=repo)

## Tags

- payments
- payment orchestration
- payment processing
- fintech
- fraud detection
- smart routing
- checkout
- payment methods
- reconciliation
- webhooks

## APIs

### Primer Payments API

REST API for creating and managing payments, client sessions, and saved payment methods. Supports the full payment lifecycle including authorization, capture, refund, cancellation, and dispute management. Versioned via `X-Api-Version` header with current GA version 2.4.

- **Documentation:** [https://primer.io/docs/api-reference/get-started/overview](https://primer.io/docs/api-reference/get-started/overview)
- **Base URL (Production):** `https://api.primer.io`
- **Base URL (Sandbox):** `https://api.sandbox.primer.io`

## Plans, Rate Limits, and FinOps

- **Plans / Pricing:** [plans/primer-plans-pricing.yml](plans/primer-plans-pricing.yml) — Custom enterprise pricing; Primer for Growth offers qualifying startups one year of complimentary access.
- **Rate Limits:** [rate-limits/primer-rate-limits.yml](rate-limits/primer-rate-limits.yml) — Not publicly disclosed; API versioning enforced via `X-Api-Version` header (current GA: v2.4).
- **FinOps:** [finops/primer-finops.yml](finops/primer-finops.yml) — FOCUS-aligned cost profile covering platform fees, processor pass-through costs, and optimization opportunities via smart routing and network tokenization.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://primer.io/](https://primer.io/) |
| Documentation | [https://primer.io/docs/api-reference/get-started/overview](https://primer.io/docs/api-reference/get-started/overview) |
| GitHub Organization | [https://github.com/primer-io](https://github.com/primer-io) |
| LinkedIn | [https://www.linkedin.com/company/primerapi/](https://www.linkedin.com/company/primerapi/) |
| X / Twitter | [https://x.com/primer_io](https://x.com/primer_io) |
| Blog | [https://primer.io/blog](https://primer.io/blog) |
| Pricing | [https://primer.io/blog/primer-launches-primer-for-growth](https://primer.io/blog/primer-launches-primer-for-growth) |
| Status Page | [https://status.primer.io/](https://status.primer.io/) |
| Changelog | [https://primer.io/docs/changelogs/android-sdk](https://primer.io/docs/changelogs/android-sdk) |

## Maintainers

- **Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
