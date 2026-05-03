# Volkswagen

Volkswagen AG is a German automotive company and parent of the VW Group, manufacturing vehicles under brands including Volkswagen, Audi, SEAT, Skoda, CUPRA, Porsche, Lamborghini, and Bentley. The OKAPI (Open Konfigurator API) provides programmatic access to VW AG product data for vehicle catalog browsing, interactive configuration, buildability validation, WLTP emissions data, configuration images, and order/pricing information across global markets.

- **Website:** [https://productdata.volkswagenag.com/](https://productdata.volkswagenag.com/)
- **Developer Portal:** [https://okapi-ddp.productdata.volkswagenag.com/dev-portal/](https://okapi-ddp.productdata.volkswagenag.com/dev-portal/)
- **Documentation:** [https://productdata.volkswagenag.com/swagger-doc.html](https://productdata.volkswagenag.com/swagger-doc.html)
- **Guide:** [https://productdata.volkswagenag.com/introduction.html](https://productdata.volkswagenag.com/introduction.html)

## APIs

### Volkswagen OKAPI - Open Konfigurator API

The VW OKAPI API v3 provides catalog and configuration operations. Catalog endpoints (GET) browse countries, brands, models, types, and options. Operation endpoints (POST) handle buildability checking, recovery, configuration, WLTP emissions, images, and order data.

- **Base URL:** `https://productdata.volkswagenag.com/v3`
- **Authentication:** Bearer Token (request via Developer Portal)
- **OpenAPI:** [openapi/volkswagen-okapi-openapi.yml](openapi/volkswagen-okapi-openapi.yml)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/volkswagen-okapi-openapi.yml](openapi/volkswagen-okapi-openapi.yml) | VW OKAPI — catalog and configuration API |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [json-schema/volkswagen-vehicle-config-schema.json](json-schema/volkswagen-vehicle-config-schema.json) | Vehicle configuration resource schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [json-structure/volkswagen-vehicle-config-structure.json](json-structure/volkswagen-vehicle-config-structure.json) | Configuration field-level documentation |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [json-ld/volkswagen-context.jsonld](json-ld/volkswagen-context.jsonld) | Linked data context mapping to schema.org/Car |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [rules/volkswagen-rules.yml](rules/volkswagen-rules.yml) | VW OKAPI API linting rules |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/vehicle-configuration.yaml](capabilities/vehicle-configuration.yaml) | Vehicle configuration workflow (11 tools) |
| [capabilities/shared/volkswagen-okapi.yaml](capabilities/shared/volkswagen-okapi.yaml) | Shared OKAPI API consumed definition |

### Examples

| Example | Description |
|---------|-------------|
| [examples/volkswagen-listCountries-example.json](examples/volkswagen-listCountries-example.json) | List supported markets |
| [examples/volkswagen-checkBuildability-example.json](examples/volkswagen-checkBuildability-example.json) | Check configuration buildability |
| [examples/volkswagen-getOrderInformation-example.json](examples/volkswagen-getOrderInformation-example.json) | Get pricing and tech specs |
| [examples/volkswagen-getWltpData-example.json](examples/volkswagen-getWltpData-example.json) | Get WLTP emissions data |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [vocabulary/volkswagen-vocabulary.yml](vocabulary/volkswagen-vocabulary.yml) | VW OKAPI domain vocabulary |

## Scope

- **Type:** Index
- **Tags:** Automobiles, Cars, Vehicles, Automotive, Vehicle Configuration

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

