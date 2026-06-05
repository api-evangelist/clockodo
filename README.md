# Clockodo (clockodo)

Clockodo is a German-built, cloud-based time-tracking and project- management application used by service firms, agencies, and freelancers. In addition to its web and mobile apps, Clockodo exposes a REST API at my.clockodo.com that mirrors the objects in the UI: time entries, customers, projects, services, users, absences, holiday quotas, lump-sum services, and a real-time stop-clock. Authentication uses a per-user email plus per-user API key delivered as the X-ClockodoApiUser/X-ClockodoApiKey header pair (or HTTP Basic), and every call must include the X-Clockodo-External-Application header identifying the integrating application.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Absence Management
- Billing
- Project Management
- Stop Clock
- Time Tracking
- Timesheets

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-19

## APIs

### Clockodo API

The Clockodo API is a REST interface at my.clockodo.com that lets developers automate time tracking and project management. v2 endpoints under /api/v2 cover entries, customers, projects, services, users, lump-sum services, and the stop-clock; legacy endpoints under /api cover absences and holiday quotas. Calls authenticate with X-ClockodoApiUser plus X-ClockodoApiKey (or HTTP Basic with the same credentials) and identify the calling app via X-Clockodo-External-Application; responses are JSON.

- **Human URL:** [https://www.clockodo.com/en/api/](https://www.clockodo.com/en/api/)
- **Base URL:** `https://my.clockodo.com/api`

#### Tags

- Absence Management
- Billing
- Project Management
- Stop Clock
- Time Tracking

#### Properties

- [Documentation](https://www.clockodo.com/en/api/)
- [Authentication](https://www.clockodo.com/en/api/authentication/)
- [OpenAPI](openapi/clockodo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clockodo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clockodo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/clockodo)
- [Website](https://www.clockodo.com/en/)
- [Documentation](https://www.clockodo.com/en/api/)
- [Blog](https://www.clockodo.com/en/blog/)
- [Pricing](https://www.clockodo.com/en/pricing/)
- [Terms of Service](https://www.clockodo.com/en/terms-and-conditions/)
- [Privacy Policy](https://www.clockodo.com/en/data-privacy/)
- [OpenAPI](openapi/clockodo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/clockodo-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/clockodo-context.jsonld)
- [Spectral Rules](rules/clockodo-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
