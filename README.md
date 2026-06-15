# Secureworks (secureworks)

Secureworks is a cybersecurity company that provides the Taegis XDR (Extended Detection and Response) platform, offering threat detection, investigation, and response capabilities backed by 20 years of security intelligence. Taegis ingests and correlates telemetry across endpoints, network, cloud, and identity sources to detect threats and automate response workflows. The Taegis XDR API exposes GraphQL APIs for alerts, investigations, endpoint assets, identities, threat intelligence, connectors, collectors, playbooks, and users, with OAuth2 client credentials authentication and multi-region deployment support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Cybersecurity
- XDR
- Threat Detection
- Security Operations
- Incident Response
- MDR
- Threat Intelligence

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Secureworks Taegis XDR API

The Secureworks Taegis XDR API provides GraphQL-based programmatic access to the Taegis extended detection and response platform. The API supports alerts, investigations, endpoint assets, identities, threat intelligence, collectors, connectors, playbooks, and audit operations. Authentication uses OAuth2 client credentials flow with bearer token authorization. The platform is available across multiple regions in the US and EU, with each region served by a dedicated API endpoint.

- **Human URL:** [https://docs.taegis.secureworks.com/apis/using_xdr_apis/](https://docs.taegis.secureworks.com/apis/using_xdr_apis/)
- **Base URL:** `https://api.ctpx.secureworks.com`

#### Tags

- XDR
- Threat Detection
- Security Operations
- GraphQL
- Incident Response

#### Properties

- [OpenAPI](openapi/secureworks-taegis-xdr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/secureworks-taegis-xdr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/secureworks-taegis-xdr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.taegis.secureworks.com/apis/using_xdr_apis/)
- [Authentication](https://docs.taegis.secureworks.com/apis/api_authenticate/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/secureworks)
- [Website](https://www.secureworks.com)
- [Documentation](https://docs.taegis.secureworks.com/apis/using_xdr_apis/)
- [Authentication](https://docs.taegis.secureworks.com/apis/api_authenticate/)
- [GitHub Organization](https://github.com/secureworks)
- [SDK](https://github.com/secureworks/taegis-sdk-python)
- [Documentation](https://us2.vdr.secureworks.com/api/v2/spec)
- [Blog](https://www.secureworks.com/blog/show-me-the-apis)
- [JSON Schema](json-schema/secureworks-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/secureworks-investigation-structure.json)
- [J S O N L D Context](json-ld/secureworks-context.jsonld)
- [Example](examples/secureworks-query-alerts-example.json)
- [Spectral Ruleset](rules/secureworks-rules.yml)
- [Vocabulary](vocabulary/secureworks-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
