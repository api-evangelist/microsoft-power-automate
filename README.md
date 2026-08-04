# Microsoft Power Automate (microsoft-power-automate)

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

Microsoft Power Automate is a cloud-based service that helps you create automated workflows between your favorite apps and services to synchronize files, get notifications, collect data, and automate business processes. It supports automated, instant, and scheduled cloud flows, as well as desktop flows for robotic process automation.

**URL:** [Visit APIs.json URL](https://powerautomate.microsoft.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Business Process, Integration, Low-Code, Microsoft, Power Platform, RPA, Workflow

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Power Automate Management API
REST API for managing flows, environments, connections, connectors, and flow permissions in Power Automate. Enables programmatic creation, update, deletion, and lifecycle management of cloud flows.

**Human URL:** [https://learn.microsoft.com/en-us/power-automate/web-api](https://learn.microsoft.com/en-us/power-automate/web-api)

#### Tags:

 - Automation, Connectors, Environments, Flow Management, Flows

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-automate/web-api)
- [OpenAPI](openapi/microsoft-power-automate-management-api.yaml)
- [JSONSchema](json-schema/power-automate-management-api-flow-schema.json)
- [JSONSchema](json-schema/power-automate-management-api-environment-schema.json)
- [JSONSchema](json-schema/power-automate-management-api-flow-run-schema.json)
- [JSONSchema](json-schema/power-automate-management-api-connector-schema.json)
- [JSONStructure](json-structure/power-automate-management-api-flow-structure.json)
- [JSONStructure](json-structure/power-automate-management-api-environment-structure.json)
- [JSONStructure](json-structure/power-automate-management-api-flow-run-structure.json)
- [JSONStructure](json-structure/power-automate-management-api-connector-structure.json)
- [Example](examples/power-automate-management-api-flow-example.json)
- [Example](examples/power-automate-management-api-environment-example.json)
- [Example](examples/power-automate-management-api-flow-run-example.json)
- [Example](examples/power-automate-management-api-connector-example.json)
- [Authentication](https://learn.microsoft.com/en-us/power-automate/web-api#authentication)
- [APIReference](https://learn.microsoft.com/en-us/connectors/flowmanagement/)

## Common Properties

- [Portal](https://make.powerautomate.com)
- [DeveloperPortal](https://learn.microsoft.com/en-us/power-automate/)
- [Blog](https://powerautomate.microsoft.com/en-us/blog/)
- [Support](https://powerautomate.microsoft.com/en-us/support/)
- [StatusPage](https://status.powerplatform.microsoft.com/)
- [Training](https://learn.microsoft.com/en-us/training/powerplatform/power-automate)
- [Pricing](https://powerautomate.microsoft.com/en-us/pricing/)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [TermsOfService](https://www.microsoft.com/en-us/servicesagreement)
- [GitHubRepository](https://github.com/microsoft/PowerApps-Samples)

## Features

| Name | Description |
|------|-------------|
| Automated Cloud Flows | Create event-triggered automations that run when specific events occur. |
| Instant Cloud Flows | Start automations on demand with the push of a button. |
| Scheduled Cloud Flows | Run automations on a recurring schedule. |
| Desktop Flows (RPA) | Automate desktop and legacy application tasks using robotic process automation. |
| Copilot Integration | Create flows using natural language descriptions powered by AI. |
| 1000+ Connectors | Connect to over 1000 pre-built connectors for Microsoft and third-party services. |
| Custom Connectors | Build custom connectors using OpenAPI definitions. |
| Flow Templates | Start from pre-built templates for common automation scenarios. |
| Approval Workflows | Build approval workflows with built-in support for multi-stage approvals. |
| Error Handling | Configure error handling, retry policies, and notifications for flow failures. |

## Use Cases

| Name | Description |
|------|-------------|
| Email Automation | Automatically process, route, and respond to emails based on content or sender. |
| Data Synchronization | Keep data synchronized across multiple systems and applications. |
| Approval Processes | Automate business approval workflows across teams and departments. |
| Document Processing | Automate document creation, routing, and archival workflows. |
| IT Process Automation | Automate IT helpdesk tickets, provisioning, and monitoring workflows. |
| Social Media Monitoring | Track brand mentions and automatically respond or alert teams. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft 365 | Deep integration with SharePoint, Outlook, Teams, and other Microsoft 365 apps. |
| Microsoft Dataverse | Native integration with Dataverse for data storage and management. |
| Azure Services | Connect to Azure Logic Apps, Functions, and other Azure services. |
| Dynamics 365 | Automate business processes within Dynamics 365 CRM and ERP. |
| SAP | Connect to SAP systems for enterprise process automation. |
| Salesforce | Integrate with Salesforce for CRM automation workflows. |

## Solutions

| Name | Description |
|------|-------------|
| Power Automate Premium | Premium plan with advanced connectors, AI Builder, and process mining. |
| Power Automate Process | Per-process licensing for unattended RPA and hosted machines. |
| Power Automate Hosted | Hosted machine groups for scaling desktop automation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Power Automate Management API](openapi/microsoft-power-automate-management-api.yaml)

### JSON Schema

- [Flow](json-schema/power-automate-management-api-flow-schema.json)
- [Environment](json-schema/power-automate-management-api-environment-schema.json)
- [FlowRun](json-schema/power-automate-management-api-flow-run-schema.json)
- [Connector](json-schema/power-automate-management-api-connector-schema.json)

### JSON Structure

- [Flow](json-structure/power-automate-management-api-flow-structure.json)
- [Environment](json-structure/power-automate-management-api-environment-structure.json)
- [FlowRun](json-structure/power-automate-management-api-flow-run-structure.json)
- [Connector](json-structure/power-automate-management-api-connector-structure.json)

### JSON-LD

- [Power Automate Management API Context](json-ld/microsoft-power-automate-management-api-context.jsonld)

### Examples

- [Flow](examples/power-automate-management-api-flow-example.json)
- [Environment](examples/power-automate-management-api-environment-example.json)
- [FlowRun](examples/power-automate-management-api-flow-run-example.json)
- [Connector](examples/power-automate-management-api-connector-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Power Automate Management API](capabilities/shared/management-api.yaml) — 10 operations for flow, environment, and connector management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Flow Automation](capabilities/flow-automation.yaml) | Power Automate Management API | 10 | Automation Engineer, Platform Administrator |

## Vocabulary

- [Microsoft Power Automate Vocabulary](vocabulary/microsoft-power-automate-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 10 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Microsoft Power Automate Spectral Rules](rules/microsoft-power-automate-spectral-rules.yml) — 21 rules across 7 categories enforcing Power Automate API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
