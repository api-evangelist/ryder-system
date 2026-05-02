# Ryder System

Ryder System, Inc. is a leading provider of supply chain, dedicated transportation, and fleet management solutions. Ryder operates a developer portal at developer.ryder.com offering REST APIs for fleet management and supply chain operations, enabling customers to integrate Ryder services into their business systems. The Fleet Management APIs support customers who lease, rent, and maintain vehicles, while the Supply Chain Solutions APIs support carrier management, load tracking, shipment management, and last-mile delivery operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml)

## Tags

- Fleet Management
- Logistics
- Supply Chain
- Transportation
- Trucking

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-02

## APIs

### Ryder Fleet Management API

Enables seamless integration of fleet and location data into business systems. Provides vehicle information and specifications, location data with address and service hours, historical maintenance records, and invoice details. Requires API key authentication via the Ocp-Apim-Subscription-Key header.

**Human URL:** [developer.ryder.com/fms/overview](https://developer.ryder.com/fms/overview)

**Base URL:** `https://developer.ryder.com/fms/apis`

#### Properties

- [Documentation](https://developer.ryder.com/fms/docs/fms-fleet-api/overview)
- [Getting Started](https://developer.ryder.com/fms/docs/fms-fleet-api/getting-started)
- [OpenAPI](openapi/ryder-fleet-management-api-openapi.yml)

### Ryder Carrier API

Enables carriers to push updates to Ryder for managing transportation, brokerage, and tracking services. Supports load tender management, load event updates, vehicle location tracking, and document uploads to RyderShare.

**Human URL:** [developer.ryder.com/scs/docs/scs-carrier/overview](https://developer.ryder.com/scs/docs/scs-carrier/overview)

**Base URL:** `https://api.ryder.com/rcsc/events/v1`

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/scs-carrier/overview)
- [OpenAPI](openapi/ryder-carrier-api-openapi.yml)

### Ryder TM Shipment Management API

Enables customers to manage shipments, loads, and tracking updates via OAuth 2.0 Client Credentials flow. Supports shipment creation, load management, ship confirmation, and real-time status tracking.

**Human URL:** [developer.ryder.com/scs/docs/tm-shipment-management/overview](https://developer.ryder.com/scs/docs/tm-shipment-management/overview)

**Base URL:** `https://api.ryder.com/tmshipment/v1`

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/tm-shipment-management/overview)
- [OpenAPI](openapi/ryder-tm-shipment-api-openapi.yml)

### Ryder Last Mile API

Handles last-mile delivery operations for e-commerce fulfillment and parcel delivery management.

**Human URL:** [developer.ryder.com/scs/docs/ryder-last-mile/overview](https://developer.ryder.com/scs/docs/ryder-last-mile/overview)

### Ryder 3PA Load Tracking API

Provides third-party logistics load tracking functionality for visibility into load status throughout the shipment lifecycle.

**Human URL:** [developer.ryder.com/scs/docs/3pa-load-tracking/overview](https://developer.ryder.com/scs/docs/3pa-load-tracking/overview)

## Artifacts

### OpenAPI

- [Fleet Management API](openapi/ryder-fleet-management-api-openapi.yml)
- [Carrier API](openapi/ryder-carrier-api-openapi.yml)
- [TM Shipment Management API](openapi/ryder-tm-shipment-api-openapi.yml)

### Spectral Rules

- [Ryder API Rules](rules/ryder-spectral-rules.yml)

### Capabilities

- [Fleet Operations](capabilities/fleet-operations.yaml)
- [Supply Chain Visibility](capabilities/supply-chain-visibility.yaml)

#### Shared Definitions

- [Fleet Management](capabilities/shared/fleet-management.yaml)
- [Carrier API](capabilities/shared/carrier-api.yaml)
- [TM Shipment](capabilities/shared/tm-shipment.yaml)

### JSON Schema

- [Vehicle](json-schema/ryder-vehicle-schema.json)
- [Shipment](json-schema/ryder-shipment-schema.json)

### JSON Structure

- [Vehicle](json-structure/ryder-vehicle-structure.json)
- [Shipment](json-structure/ryder-shipment-structure.json)

### Examples

- [List Fleet Vehicles](examples/ryder-list-fleet-vehicles-example.json)
- [Get Service History](examples/ryder-get-service-history-example.json)
- [Create Shipment](examples/ryder-create-shipment-example.json)

### JSON-LD Context

- [Ryder System Context](json-ld/ryder-system-context.jsonld)

### Vocabulary

- [Ryder System Vocabulary](vocabulary/ryder-system-vocabulary.yml)

## Common Properties

- [Website](https://www.ryder.com)
- [Developer Portal](https://developer.ryder.com)
- [Documentation](https://developer.ryder.com/fms/overview)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
