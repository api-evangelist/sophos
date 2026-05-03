# Sophos

Sophos is a global cybersecurity leader delivering advanced endpoint protection, network security, cloud security, and SIEM integration through the Sophos Central platform. The Sophos Central API enables partners, organizations, and tenants to automate security operations including alert management, event retrieval, endpoint policy enforcement, and threat response.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sophos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sophos/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Cybersecurity, Endpoint Protection, Security, SIEM, Threat Detection, Incident Response

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-02

## APIs

### Sophos Central SIEM API

The Sophos Central SIEM API provides access to security alerts and events for automating threat detection, incident response, and SIEM integration workflows. Retrieve real-time alerts and events from Sophos Central to feed into security operations tooling.

**Human URL:** [https://developer.sophos.com/](https://developer.sophos.com/)
**Base URL:** `https://api1.central.sophos.com/gateway`

#### Tags

Cybersecurity, SIEM, Alerts, Events, Security Operations

#### Properties

- [Documentation](https://developer.sophos.com/intro)
- [Reference](https://developer.sophos.com/apis)
- [Getting Started](https://developer.sophos.com/getting-started)
- [Change Log](https://developer.sophos.com/whatsnew)
- [OpenAPI](openapi/sophos-central-siem-openapi.yml)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Sophos Central SIEM API | [openapi/sophos-central-siem-openapi.yml](openapi/sophos-central-siem-openapi.yml) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| Sophos Rules | [rules/sophos-rules.yml](rules/sophos-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|-----|------|
| Sophos Central SIEM | [capabilities/shared/sophos-central-siem.yaml](capabilities/shared/sophos-central-siem.yaml) |

**Workflow Capabilities:**

| Workflow | File | Description |
|----------|------|-------------|
| Security Operations | [capabilities/security-operations.yaml](capabilities/security-operations.yaml) | Alerts and event monitoring for SOC analysts |

### JSON Schemas

| Schema | File |
|--------|------|
| Alert | [json-schema/sophos-alert-schema.json](json-schema/sophos-alert-schema.json) |
| Event | [json-schema/sophos-event-schema.json](json-schema/sophos-event-schema.json) |

### JSON Structures

| Structure | File |
|-----------|------|
| Alerts Response | [json-structure/sophos-alerts-response-structure.json](json-structure/sophos-alerts-response-structure.json) |

### JSON-LD Contexts

| Context | File |
|---------|------|
| Sophos | [json-ld/sophos-context.jsonld](json-ld/sophos-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| List Alerts | [examples/sophos-list-alerts-example.json](examples/sophos-list-alerts-example.json) |

### Vocabulary

| Vocabulary | File |
|------------|------|
| Sophos | [vocabulary/sophos-vocabulary.yml](vocabulary/sophos-vocabulary.yml) |

## Common Properties

- [Portal](https://developer.sophos.com/)
- [Documentation](https://developer.sophos.com/intro)
- [Website](https://www.sophos.com/)
- [Community](https://community.sophos.com/sophos-central-api)
- [GitHub Org](https://github.com/sophos)
- [Postman Collection](https://github.com/sophos/sophos-central-apis-postman)
- [Integrations](https://www.sophos.com/en-us/integrations)
- [Support](https://support.sophos.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
