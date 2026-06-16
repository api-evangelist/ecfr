# eCFR (ecfr)

Electronic Code of Federal Regulations REST API for accessing the official US Code of Federal Regulations, searching regulations, and retrieving regulatory version history.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/apis.yml)

## Tags

- Federal Regulations
- Government
- Legal
- Compliance
- Open Data
- United States

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### eCFR Versioner API

Provides access to the full text of CFR titles, parts, sections, and appendices at specific dates, as well as version history for regulatory content. Supports XML format responses for hierarchical regulatory structure.

- **Human URL:** [https://www.ecfr.gov/developers/documentation/api/v1](https://www.ecfr.gov/developers/documentation/api/v1)
- **Base URL:** `https://www.ecfr.gov/api/versioner/v1`

#### Tags

- Regulations
- Version History
- CFR Titles

#### Properties

- [Documentation](https://www.ecfr.gov/developers/documentation/api/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/openapi/ecfr-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### eCFR Search API

Full-text search across all Code of Federal Regulations content, with support for filtering by title, agency, date ranges, and content type. Returns ranked results with hierarchical context and full-text excerpts.

- **Human URL:** [https://www.ecfr.gov/developers/documentation/api/v1](https://www.ecfr.gov/developers/documentation/api/v1)
- **Base URL:** `https://www.ecfr.gov/api/search/v1`

#### Tags

- Search
- Full-Text Search
- Regulations

#### Properties

- [Documentation](https://www.ecfr.gov/developers/documentation/api/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/openapi/ecfr-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### eCFR Admin API

Provides metadata about federal agencies and their CFR references, enabling lookup of which titles and chapters correspond to specific agencies.

- **Human URL:** [https://www.ecfr.gov/developers/documentation/api/v1](https://www.ecfr.gov/developers/documentation/api/v1)
- **Base URL:** `https://www.ecfr.gov/api/admin/v1`

#### Tags

- Agencies
- Metadata
- Government

#### Properties

- [Documentation](https://www.ecfr.gov/developers/documentation/api/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/openapi/ecfr-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.ecfr.gov)
- [Documentation](https://www.ecfr.gov/developers/documentation/api/v1)
- [Git Hub Org](https://github.com/usgpo)
- [Blog](https://www.federalregister.gov/blog)
- [Pricing](https://www.ecfr.gov/developers)
- [Plans](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/plans/ecfr-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/rate-limits/ecfr-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/finops/ecfr-finops.yml)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/openapi/ecfr-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/agency.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/cfr-title.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/search-result.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/content-version.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/correction.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-schema/cfr-ancestor.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/vocabulary/ecfr-vocabulary.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/json-ld/ecfr-context.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/examples/titles-response.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/examples/agencies-response.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/examples/search-results-response.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/examples/ancestry-response.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ecfr/refs/heads/main/examples/versions-response.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
