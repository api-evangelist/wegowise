# WegoWise (wegowise)

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

WegoWise (now Comply by Measurabl) is a building energy and water benchmarking platform enabling property owners, managers, and energy service providers to programmatically manage building portfolios, track utility meter data, and benchmark energy and water performance. The REST API supports building management, apartment and commercial area tracking, utility meter data import, and normalized monthly usage analytics across multifamily and commercial properties.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Benchmarking
- Building Energy
- Energy Efficiency
- Multifamily
- Property Management
- Utility Data

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-19

## APIs

### WegoWise API

The WegoWise REST API (now Comply API) for managing building portfolios, utility meters, and energy data. Supports buildings, apartments, commercial areas, developments, meters, and raw usage datapoints. Authenticated via OAuth 1.0.

- **Human URL:** [https://www.wegowise.com/api](https://www.wegowise.com/api)

#### Tags

- Apartments
- Benchmarking
- Buildings
- Developments
- Energy Data
- Meters
- REST
- Utility Companies
- Water Data

#### Properties

- [Documentation](https://www.wegowise.com/api)
- [OpenAPI](openapi/wegowise-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wegowise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wegowise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wegowise-building-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wegowise-meter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wegowise-building-structure.json)
- [JSON-LD](json-ld/wegowise-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### WegoWise Pro API

The WegoPro API for multifamily and commercial property portfolios. Provides endpoints for buildings, apartments, areas, meters, raw data, and monthly normalized usage data. The primary API for property managers.

- **Human URL:** [https://www.wegowise.com/api/wego_pro](https://www.wegowise.com/api/wego_pro)

#### Tags

- Apartments
- Buildings
- Commercial Areas
- Multifamily
- Pro

#### Properties

- [Documentation](https://www.wegowise.com/api/wego_pro)
- [Postman Collection](collections/wegowise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wegowise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WegoWise Data API

The WegoData API for data-only accounts. Enables meter management and automated utility data import without the full building structure hierarchy. Supports all utility types: Electric, Gas, Oil, Water, Steam, Propane, Solar.

- **Human URL:** [https://www.wegowise.com/api/wego_data](https://www.wegowise.com/api/wego_data)

#### Tags

- Automated Import
- Data Only
- Meters
- Utility Data

#### Properties

- [Documentation](https://www.wegowise.com/api/wego_data)
- [Postman Collection](collections/wegowise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wegowise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WegoWise Public API

Public endpoints accessible without authentication. Provides a list of utility companies supported for automated data import, useful for finding utility_company_id values when configuring meters.

- **Human URL:** [https://www.wegowise.com/api/public](https://www.wegowise.com/api/public)

#### Tags

- Public
- Utility Companies

#### Properties

- [Documentation](https://www.wegowise.com/api/public)
- [Postman Collection](collections/wegowise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wegowise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/wegowise)
- [LinkedIn](https://www.linkedin.com/company/wegowise-inc)
- [Documentation](https://www.wegowise.com/api)
- [Website](https://www.wegowise.com)
- [Product  Tour](https://www.wegowise.com/tour)
- [Energy  Service  Providers](https://www.wegowise.com/customer-profiles/energy-service-providers)
- [Compliance](https://www.wegowise.com/compliance)
- [Blog](http://blog.wegowise.com/)
- [Spectral Rules](rules/wegowise-rules.yml)
- [Vocabulary](vocabulary/wegowise-vocabulary.yml)
- [JSON-LD](json-ld/wegowise-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
