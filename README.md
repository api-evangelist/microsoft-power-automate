# Microsoft Power Automate (microsoft-power-automate)
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
