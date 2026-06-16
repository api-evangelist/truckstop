# Truckstop (truckstop)

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
