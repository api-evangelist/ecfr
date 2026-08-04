# eCFR (ecfr)

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
