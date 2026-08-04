# Truckstop (truckstop)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Truckstop is a freight marketplace and load board platform offering a REST API for managing load postings, carrier searches, rate negotiation, and freight payment processing. The platform serves shippers, brokers, and carriers with tools for truck and lane searching, rate insights, carrier compliance monitoring, tender management, risk factor analysis, and document management. Founded in 1995 as the first load board on the internet, Truckstop provides API integrations requiring a signed Systems Integration Agreement (SIA) and supports both Resource Owner Password and Authorization Code OAuth 2.0 flows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truckstop/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truckstop/refs/heads/main/apis.yml)

## Tags

- Freight
- Load Board
- Trucking
- Logistics
- Freight Marketplace
- Carrier Search
- Rate Insights
- Transportation
- Broker
- Shipper

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Truckstop Load Management API

REST API for posting, updating, refreshing, and deleting loads on the Truckstop load board. Includes Load Boost for promoted visibility, pause/unpause for BIN loads, and tender management for booked loads.

- **Human URL:** [https://developer.truckstop.com/reference/load-management-1](https://developer.truckstop.com/reference/load-management-1)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Load Management
- Load Board
- Freight

#### Properties

- [Documentation](https://developer.truckstop.com/reference/load-management-1)
- [OpenAPI](https://developer.truckstop.com/llms.txt) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Truckstop Load Search API

API for carriers and brokers to search available loads on the Truckstop load board with filtering, sorting, and bulk detail retrieval.

- **Human URL:** [https://developer.truckstop.com/reference/load-operations](https://developer.truckstop.com/reference/load-operations)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Load Search
- Freight
- Carrier

#### Properties

- [Documentation](https://developer.truckstop.com/reference/load-operations)

### Truckstop Carrier Network API

API for managing carrier networks, including bulk add/update/remove by DOT number, preferred carrier lists, carrier groups, compliance status access, and carrier search within groups.

- **Human URL:** [https://developer.truckstop.com/reference/general-overview](https://developer.truckstop.com/reference/general-overview)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Carrier Network
- Compliance
- Broker

#### Properties

- [Documentation](https://developer.truckstop.com/reference/general-overview)

### Truckstop Rate Insights API

API for accessing predictive rate data including booked rate estimates and trendlines over 4-week and 36-month periods, posted rate estimates, and rate crowdsourcing submissions.

- **Human URL:** [https://developer.truckstop.com/reference/rate-insights-v3](https://developer.truckstop.com/reference/rate-insights-v3)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Rate Insights
- Freight Rates
- Analytics

#### Properties

- [Documentation](https://developer.truckstop.com/reference/rate-insights-v3)

### Truckstop Risk Factor API

API for carrier risk analysis including single and multiple carrier risk reports by MC/DOT number, search by email or phone, RMIS certification status queries, and monitored carrier list management.

- **Human URL:** [https://developer.truckstop.com/reference/general-overview](https://developer.truckstop.com/reference/general-overview)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Risk Factor
- Compliance
- RMIS
- Carrier

#### Properties

- [Documentation](https://developer.truckstop.com/reference/general-overview)

### Truckstop Truck Management API

API for posting trucks with equipment options, searching posted trucks, viewing truck details individually and in bulk, deleting trucks, and accessing Hot Prospects hidden capacity search.

- **Human URL:** [https://developer.truckstop.com/reference/general-overview](https://developer.truckstop.com/reference/general-overview)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Truck Posting
- Capacity
- Carrier

#### Properties

- [Documentation](https://developer.truckstop.com/reference/general-overview)

### Truckstop Document API

API for managing freight-related documents associated with loads and transactions on the Truckstop platform.

- **Human URL:** [https://developer.truckstop.com/reference/document-api](https://developer.truckstop.com/reference/document-api)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Documents
- Freight

#### Properties

- [Documentation](https://developer.truckstop.com/reference/document-api)

### Truckstop Booked Rates API

API for retrieving booked load details by Load ID, tender details by Tender ID, CSV exports of booked loads, and tenders by account for freight payment processing.

- **Human URL:** [https://developer.truckstop.com/reference/booked-rates](https://developer.truckstop.com/reference/booked-rates)
- **Base URL:** `https://api.truckstop.com`

#### Tags

- Booked Rates
- Tender Management
- Freight Payment

#### Properties

- [Documentation](https://developer.truckstop.com/reference/booked-rates)

## Common Properties

- [Website](https://truckstop.com/)
- [Documentation](https://developer.truckstop.com/)
- [Git Hub Org](https://github.com/truckstop)
- [LinkedIn](https://www.linkedin.com/company/truckstop/)
- [Blog](https://truckstop.com/blog/)
- [Pricing](https://truckstop.com/product/load-board/pricing/)
- [Status Page](https://status.truckstop.com/)
- [X (Twitter)](https://x.com/trckstopdotcom)
- [Plans](plans/truckstop-plans-pricing.yml)
- [Rate Limits](rate-limits/truckstop-rate-limits.yml)
- [Fin Ops](finops/truckstop-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
