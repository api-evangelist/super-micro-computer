# Super Micro Computer (super-micro-computer)

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

Super Micro Computer (Supermicro) is a global leader in high-performance, high-efficiency server technology and innovation, providing complete server, storage, and networking solutions for data center, cloud, AI, and edge applications. Supermicro exposes its server management capabilities through the DMTF Redfish RESTful API standard, enabling programmatic management of servers, storage, and networking hardware via BMC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml)

## Tags

- Servers
- Data Center
- Hardware
- Server Management
- Redfish
- BMC
- IPMI
- Fortune 500
- Infrastructure
- Cloud

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Supermicro Redfish API

Supermicro's implementation of the DMTF Redfish RESTful API standard for out-of-band server management via BMC. Provides programmatic access to server health monitoring, power management, BIOS/BMC firmware updates, storage configuration, network configuration, user account management, and event logging across Supermicro server platforms.

- **Human URL:** [https://www.supermicro.com/en/solutions/management-software/redfish](https://www.supermicro.com/en/solutions/management-software/redfish)
- **Base URL:** `https://{bmc-ip}/redfish/v1`

#### Tags

- Redfish
- Server Management
- BMC
- IPMI
- Hardware
- Data Center

#### Properties

- [Documentation](https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm)
- [Documentation](https://www.supermicro.com/manuals/other/RedfishUserGuide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/openapi/supermicro-redfish-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-schema/supermicro-computer-system-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-structure/supermicro-computer-system-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-ld/super-micro-computer-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/rules/supermicro-redfish-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/vocabulary/super-micro-computer-vocabulary.yml)
- [GitHub Repository](https://github.com/supermicro/redfish)
- [Postman Collection](collections/supermicro-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supermicro-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/supermicro)
- [Website](https://www.supermicro.com)
- [Developer  Portal](https://www.supermicro.com/en/solutions/management-software)
- [Documentation](https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm)
- [GitHub Organization](https://github.com/supermicro)
- [Blog](https://www.supermicro.com/en/newsroom)
- [Support](https://www.supermicro.com/en/support)
- [Pricing](https://www.supermicro.com/en/products/servers)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
