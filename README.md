# Super Micro Computer

Super Micro Computer (Supermicro) is a global leader in high-performance, high-efficiency server technology and innovation, providing complete server, storage, and networking solutions for data center, cloud, AI, and edge applications. Supermicro exposes its server management capabilities through the DMTF Redfish RESTful API standard, enabling programmatic management of servers, storage, and networking hardware via BMC.

**URL:** [APIs.yml](https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml)

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

## APIs

### Supermicro Redfish API

Supermicro's implementation of the DMTF Redfish RESTful API standard for out-of-band server management via BMC. Provides programmatic access to server health monitoring, power management, BIOS/BMC firmware updates, storage configuration, network configuration, user account management, and event logging across Supermicro server platforms.

- **Human URL:** [https://www.supermicro.com/en/solutions/management-software/redfish](https://www.supermicro.com/en/solutions/management-software/redfish)
- **Base URL:** `https://{bmc-ip}/redfish/v1`

#### Properties

| Type | URL |
|------|-----|
| Documentation | [Redfish Reference Guide](https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm) |
| Documentation | [Redfish User Guide PDF](https://www.supermicro.com/manuals/other/RedfishUserGuide.pdf) |
| OpenAPI | [supermicro-redfish-openapi.yml](openapi/supermicro-redfish-openapi.yml) |
| JSON Schema | [supermicro-computer-system-schema.json](json-schema/supermicro-computer-system-schema.json) |
| JSON Structure | [supermicro-computer-system-structure.json](json-structure/supermicro-computer-system-structure.json) |
| JSON-LD | [super-micro-computer-context.jsonld](json-ld/super-micro-computer-context.jsonld) |
| Spectral Rules | [supermicro-redfish-rules.yml](rules/supermicro-redfish-rules.yml) |
| Capabilities | [server-management.yaml](capabilities/server-management.yaml) |
| Vocabulary | [super-micro-computer-vocabulary.yml](vocabulary/super-micro-computer-vocabulary.yml) |
| GitHub Repository | [supermicro/redfish](https://github.com/supermicro/redfish) |

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/redfish.yaml](capabilities/shared/redfish.yaml) | Supermicro Redfish API — full BMC consumes definition (sessions, systems, chassis, managers, accounts, events, firmware) |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/server-management.yaml](capabilities/server-management.yaml) | Server Management — unified REST and MCP interfaces for data center server operations (15 tools) |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.supermicro.com](https://www.supermicro.com) |
| Developer Portal | [https://www.supermicro.com/en/solutions/management-software](https://www.supermicro.com/en/solutions/management-software) |
| Documentation | [Redfish Reference Guide](https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm) |
| GitHub Organization | [https://github.com/supermicro](https://github.com/supermicro) |
| Blog | [https://www.supermicro.com/en/newsroom](https://www.supermicro.com/en/newsroom) |
| Support | [https://www.supermicro.com/en/support](https://www.supermicro.com/en/support) |

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
