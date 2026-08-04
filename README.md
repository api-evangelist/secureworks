# Secureworks (secureworks)

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
