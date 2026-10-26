# Primer (primer)

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
