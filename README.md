# Secureworks (secureworks)

Secureworks is a cybersecurity company that provides the Taegis XDR (Extended Detection and Response) platform, offering threat detection, investigation, and response capabilities backed by 20 years of security intelligence. Taegis ingests and correlates telemetry across endpoints, network, cloud, and identity sources to detect threats and automate response workflows. The Taegis XDR API exposes GraphQL APIs for alerts, investigations, endpoint assets, identities, threat intelligence, connectors, collectors, playbooks, and users, with OAuth2 client credentials authentication and multi-region deployment support.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
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
- **Modified:** 2026-05-02

## APIs

### Secureworks Taegis XDR API

The Secureworks Taegis XDR API provides GraphQL-based programmatic access to the Taegis extended detection and response platform. The API supports alerts, investigations, endpoint assets, identities, threat intelligence, collectors, connectors, playbooks, and audit operations. Authentication uses OAuth2 client credentials flow with bearer token authorization. The platform is available across multiple regions in the US and EU.

#### Properties

- [OpenAPI](openapi/secureworks-taegis-xdr-openapi.yml)
- [API Documentation](https://docs.taegis.secureworks.com/apis/using_xdr_apis/)
- [Authentication](https://docs.taegis.secureworks.com/apis/api_authenticate/)

## Common Properties

- [Website](https://www.secureworks.com)
- [Taegis API Documentation](https://docs.taegis.secureworks.com/apis/using_xdr_apis/)
- [GitHub Organization](https://github.com/secureworks)
- [Taegis Python SDK](https://github.com/secureworks/taegis-sdk-python)

## Artifacts

### JSON Schema

- [Alert Schema](json-schema/secureworks-alert-schema.json)

### JSON Structure

- [Investigation Structure](json-structure/secureworks-investigation-structure.json)

### JSON-LD

- [Context](json-ld/secureworks-context.jsonld)

### Examples

- [Query Alerts](examples/secureworks-query-alerts-example.json)

### Rules

- [Spectral Ruleset](rules/secureworks-rules.yml)

### Capabilities

- [Threat Detection and Response](capabilities/threat-detection-response.yaml)
  - Shared: [Taegis XDR](capabilities/shared/taegis-xdr.yaml)

### Vocabulary

- [Secureworks Vocabulary](vocabulary/secureworks-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
