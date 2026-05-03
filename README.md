# WegoWise

WegoWise (now Comply by Measurabl) is a building energy and water benchmarking platform enabling property owners, managers, and energy service providers to track utility usage across portfolios, identify savings opportunities, and demonstrate conservation results. The REST API enables programmatic building management, utility meter data import, and energy performance analysis.

**Website:** [wegowise.com](https://www.wegowise.com)
**API Docs:** [wegowise.com/api](https://www.wegowise.com/api)
**Scale:** 21.4M+ utility bills analyzed, 72,331 buildings, 2.51B sq ft

## APIs

| API | Description |
|-----|-------------|
| [WegoWise API](https://www.wegowise.com/api) | Full REST API for buildings, meters, and usage data |
| [WegoPro API](https://www.wegowise.com/api/wego_pro) | Multi-building portfolio management |
| [WegoData API](https://www.wegowise.com/api/wego_data) | Automated utility data import (data-only accounts) |
| [Public API](https://www.wegowise.com/api/public) | Public utility company directory |

## Artifacts

### OpenAPI Specifications
- [wegowise-openapi.yml](openapi/wegowise-openapi.yml) — Full API with 30+ operations for buildings, meters, and usage data

### Naftiko Capabilities
- [building-energy-benchmarking.yaml](capabilities/building-energy-benchmarking.yaml) — Portfolio benchmarking workflow with 12 tools
- [capabilities/shared/wegowise.yaml](capabilities/shared/wegowise.yaml) — Shared WegoWise API definition

### Spectral Rules
- [wegowise-rules.yml](rules/wegowise-rules.yml) — API linting rules for WegoWise conventions

### JSON Schemas
- [wegowise-building-schema.json](json-schema/wegowise-building-schema.json) — Building record schema
- [wegowise-meter-schema.json](json-schema/wegowise-meter-schema.json) — Utility meter schema

### JSON Structures
- [wegowise-building-structure.json](json-structure/wegowise-building-structure.json) — Building field documentation

### JSON-LD Contexts
- [wegowise-context.jsonld](json-ld/wegowise-context.jsonld) — Linked data context for WegoWise resources

### Examples
- [wegowise-list-buildings-example.json](examples/wegowise-list-buildings-example.json) — List buildings response
- [wegowise-building-data-example.json](examples/wegowise-building-data-example.json) — Monthly energy data response

### Vocabulary
- [wegowise-vocabulary.yml](vocabulary/wegowise-vocabulary.yml) — WegoWise platform terminology

## Key API Resources

| Resource | Path | Description |
|----------|------|-------------|
| Utility Companies | `/api/v1/utility_companies` | Public list of importable utilities |
| Buildings | `/api/v1/wego_pro/buildings` | Portfolio buildings CRUD |
| Apartments | `/api/v1/wego_pro/buildings/{id}/apartments` | Unit management |
| Areas | `/api/v1/wego_pro/buildings/{id}/areas` | Commercial area management |
| Developments | `/api/v1/wego_pro/developments` | Portfolio groups |
| Meters | `/api/v1/wego_pro/buildings/{id}/meters` | Utility meter listing |
| Raw Data | `/api/v1/wego_pro/meters/{id}/raw_data` | Billing period datapoints |
| Monthly Data | `/api/v1/wego_pro/buildings/{id}/data` | Normalized monthly usage |
| Data Meters | `/api/v1/wego_data/meters` | Automated import meters |
| Latest Datum | `/api/v1/wego_data/meters/{id}/latest_datum` | Most recent reading |

## Authentication

WegoWise uses **OAuth 1.0** for authenticated endpoints. Register at `/api/register` to obtain consumer credentials, then follow the standard OAuth token flow.

## Utility Data Types

Electric, Gas, Oil, Water, Steam, Propane, Solar, Trash

## Common Properties

- [Documentation](https://www.wegowise.com/api)
- [Website](https://www.wegowise.com)
- [Product Tour](https://www.wegowise.com/tour)
- [Blog](http://blog.wegowise.com/)
- [Compliance](https://www.wegowise.com/compliance)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
