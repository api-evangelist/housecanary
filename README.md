# HouseCanary (housecanary)

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
