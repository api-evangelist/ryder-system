# Ryder System (ryder-system)

Ryder System, Inc. is a leading provider of supply chain, dedicated transportation, and fleet management solutions. Ryder operates a developer portal offering REST APIs for fleet management and supply chain operations, enabling customers to integrate Ryder services into their business systems. The Fleet Management APIs support customers who lease, rent, and maintain vehicles, while the Supply Chain Solutions APIs support carrier management, load tracking, shipment management, and last-mile delivery operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Fleet Management
- Logistics
- Supply Chain
- Transportation
- Trucking

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Ryder Fleet Management API

The Ryder Fleet Management API (FMS) enables seamless integration of fleet and location data into business systems. It provides access to Ryder fleet details including vehicle information and specifications, location data with address and service hours, historical maintenance records, and invoice details with line items and payment status. Requires API key authentication via the Ocp-Apim-Subscription-Key header.

- **Human URL:** [https://developer.ryder.com/fms/overview](https://developer.ryder.com/fms/overview)
- **Base URL:** `https://developer.ryder.com/fms/apis`

#### Tags

- Fleet Management
- Invoices
- Locations
- Service History
- Vehicles

#### Properties

- [Documentation](https://developer.ryder.com/fms/docs/fms-fleet-api/overview)
- [Getting Started](https://developer.ryder.com/fms/docs/fms-fleet-api/getting-started)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-fleet-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ryder-carrier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-carrier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-fleet-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-fleet-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-tm-shipment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-tm-shipment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ryder Carrier API

The Ryder Carrier API enables carriers to push updates to Ryder for managing transportation, brokerage, and tracking services. It supports resource assignment and tracking for load tenders, event updates for load events and milestones, vehicle locations, and document uploads to the RyderShare platform.

- **Human URL:** [https://developer.ryder.com/scs/docs/scs-carrier/overview](https://developer.ryder.com/scs/docs/scs-carrier/overview)
- **Base URL:** `https://api.ryder.com/rcsc/events/v1`

#### Tags

- Carrier Management
- Load Tracking
- Supply Chain
- Transportation

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/scs-carrier/overview)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-carrier-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ryder-carrier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-carrier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-fleet-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-fleet-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-tm-shipment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-tm-shipment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ryder TM Shipment Management API

The Ryder TM Shipment Management API enables seamless integration for customers to manage shipments, loads, and tracking updates. It uses OAuth 2.0 Client Credentials flow via Okta combined with an API subscription key. Supports Shipment, Load, Ship Confirmation, Ship Status, and Event Notifications.

- **Human URL:** [https://developer.ryder.com/scs/docs/tm-shipment-management/overview](https://developer.ryder.com/scs/docs/tm-shipment-management/overview)
- **Base URL:** `https://api.ryder.com/tmshipment/v1`

#### Tags

- Shipment Management
- Supply Chain
- Transportation

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/tm-shipment-management/overview)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-tm-shipment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ryder-carrier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-carrier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-fleet-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-fleet-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-tm-shipment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-tm-shipment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ryder Last Mile API

The Ryder Last Mile API handles last-mile delivery operations, enabling integration with Ryder's last-mile delivery network for e-commerce fulfillment and parcel delivery management.

- **Human URL:** [https://developer.ryder.com/scs/docs/ryder-last-mile/overview](https://developer.ryder.com/scs/docs/ryder-last-mile/overview)

#### Tags

- E-Commerce
- Last Mile Delivery
- Supply Chain

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/ryder-last-mile/overview)
- [Postman Collection](collections/ryder-carrier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-carrier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-fleet-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-fleet-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-tm-shipment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-tm-shipment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ryder 3PA Load Tracking API

The Ryder 3PA Load Tracking API provides third-party logistics load tracking functionality, enabling visibility into load status and location throughout the shipment lifecycle.

- **Human URL:** [https://developer.ryder.com/scs/docs/3pa-load-tracking/overview](https://developer.ryder.com/scs/docs/3pa-load-tracking/overview)

#### Tags

- Load Tracking
- Logistics
- Supply Chain

#### Properties

- [Documentation](https://developer.ryder.com/scs/docs/3pa-load-tracking/overview)
- [Postman Collection](collections/ryder-carrier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-carrier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-fleet-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-fleet-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ryder-tm-shipment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ryder-tm-shipment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ryder)
- [LinkedIn](https://www.linkedin.com/company/ryder-system-inc)
- [Website](https://www.ryder.com)
- [Developer Portal](https://developer.ryder.com)
- [Documentation](https://developer.ryder.com/fms/overview)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/vocabulary/ryder-system-vocabulary.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-ld/ryder-system-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/rules/ryder-spectral-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-vehicle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-shipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
