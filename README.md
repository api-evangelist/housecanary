# HouseCanary (housecanary)

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

HouseCanary is a property analytics platform providing REST APIs for automated valuation model (AVM) data, property details, rental estimates, market forecasts, and flood/risk data across more than 100 million US residential properties. The Analytics API supports property-level endpoints including value, rental value, land value, sales history, tax history, and LTV calculations accessed via HTTP Basic Authentication. The Order Manager API allows clients to programmatically order HouseCanary valuation and inspection products and receive results via webhook. HouseCanary also offers a Python SDK and a Postman collection for integration testing.

APIs.json: https://raw.githubusercontent.com/api-evangelist/housecanary/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=housecanary-api-evangelist&utm_content=repo

## Tags

- Real Estate
- Property Analytics
- AVM
- Valuation
- Rental Estimates
- Market Forecasts
- Mortgage
- Property Data

## APIs

### HouseCanary Analytics API

REST API providing property-level data including AVM valuations, rental value, land value, LTV, sales history, tax history, flood data, school info, and geographic features for US residential properties.

- Human URL: https://www.housecanary.com/resources/developer-tools
- Base URL: https://api.housecanary.com
- Documentation: https://api-docs-legacy.housecanary.com/

### HouseCanary Order Manager API

REST API for clients and partners to programmatically create valuation and inspection orders, receive status updates via webhook, export results, and download reports. Includes a sandbox environment for testing.

- Human URL: https://order-manager-api.housecanary.com/docs/index.html
- Base URL: https://order-manager-api.housecanary.com
- Documentation: https://order-manager-api.housecanary.com/docs/client-api.html
- SDK Documentation: https://order-manager-api.housecanary.com/sdkdocs/index.html

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/housecanary-plans-pricing.yml](plans/housecanary-plans-pricing.yml)
- Rate Limits: [rate-limits/housecanary-rate-limits.yml](rate-limits/housecanary-rate-limits.yml)
- FinOps: [finops/housecanary-finops.yml](finops/housecanary-finops.yml)

### Pricing Summary

| Plan | Monthly | Annual |
|------|---------|--------|
| Basic | $19/mo | $190/yr |
| Pro | $79/mo | $790/yr |
| Teams | $199/mo | $1,990/yr |
| Enterprise | Custom | Custom |

API call costs range from $0.05 to $6.00 per successful call depending on endpoint tier.

### Rate Limits

- Analytics API: 250 requests/minute, 1,000 requests/day (self-serve)
- Value Report endpoint: 10 requests/minute, 100 requests/day
- Batch POST: up to 100 items per request
- HTTP 429 returned when limits are exceeded

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.housecanary.com |
| Documentation | https://www.housecanary.com/resources/developer-tools |
| GitHub Organization | https://github.com/housecanary |
| LinkedIn | https://www.linkedin.com/company/housecanary-inc |
| X (Twitter) | https://twitter.com/housecanary |
| Blog | https://www.housecanary.com/resources/blog |
| Pricing | https://www.housecanary.com/pricing |
| Status Page | https://status.housecanary.com/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
