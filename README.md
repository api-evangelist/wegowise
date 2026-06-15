# WegoWise (wegowise)

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
