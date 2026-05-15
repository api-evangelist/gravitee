# Gravitee (gravitee)

Gravitee.io is an open-source API management platform from GraviteeSource, combining a high-performance API Gateway, full-lifecycle API Management, Access Management (IAM), Cockpit (multi-environment control plane), an Alert Engine, a Kubernetes Operator, and a new AI Agent Management suite with native MCP and LLM-proxy capabilities. The core projects are Apache 2.0 OSS, with an Enterprise commercial offering and a managed Gravitee Cloud SaaS.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party
- **License:** Apache 2.0 (core projects)

## Tags

API Gateway, API Management, Access Management, Identity, Event-Driven, Kafka, MQTT, GraphQL, gRPC, AI Gateway, MCP, Open Source, Apache 2.0

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-15

## APIs

### Gravitee API Management

Gravitee APIM is an open-source, blazing-fast API gateway, management plane, and developer portal supporting v2 proxy APIs and v4 message-oriented APIs over REST, GraphQL, WebSocket, gRPC, SSE, Webhooks, Kafka, MQTT, AMQP, Solace, RabbitMQ, and MCP.

- [Documentation](https://documentation.gravitee.io/apim)
- [GitHub](https://github.com/gravitee-io/gravitee-api-management)
- [OpenAPI](openapi/gravitee-apim-openapi.yml)
- [Helm Charts](https://github.com/gravitee-io/helm-charts)
- [Kubernetes Operator](https://github.com/gravitee-io/gravitee-kubernetes-operator)

### Gravitee Access Management

Open-source IAM with OAuth2, OIDC, UMA 2.0, CIBA, SCIM 2.0, SAML 2.0, MFA factors, risk-based authentication, and pluggable identity providers.

- [Documentation](https://documentation.gravitee.io/am)
- [GitHub](https://github.com/gravitee-io/gravitee-access-management)
- [OpenAPI](openapi/gravitee-am-openapi.yml)

### Gravitee Cockpit

Multi-installation control plane that centralizes management of many APIM/AM installations into one console with API promotion across environments.

- [Documentation](https://documentation.gravitee.io/cockpit)
- [GitHub](https://github.com/gravitee-io/gravitee-cockpit-connectors)

### Gravitee Alert Engine

Real-time API monitoring with rule-based triggers and connectors for Slack, email, webhook, PagerDuty, and Microsoft Teams.

- [Documentation](https://documentation.gravitee.io/ae)
- [GitHub](https://github.com/gravitee-io/gravitee-alert-api)

### Gravitee AI Agent Management

Enterprise add-on bringing API management discipline to agentic AI: LLM Proxy, MCP Proxy, MCP Tool Server, A2A Proxy, Agent Catalog, prompt-token tracking, prompt guard-rails, RAG, and AI-aware Identity / Authorization (OpenFGA, AuthZen).

- [Product Page](https://www.gravitee.io/platform/ai-agent-management)
- [MCP Server](https://github.com/gravitee-io/gravitee-apim-mcp-server)
- [AI Policies](https://github.com/gravitee-io?q=ai)

### Gravitee Kubernetes Operator

Go-based Kubernetes operator (GKO) reconciling Gravitee APIs, applications, subscriptions, and shared policy groups as CRDs against one or more APIM installations.

- [Documentation](https://documentation.gravitee.io/apim/kubernetes-operator)
- [GitHub](https://github.com/gravitee-io/gravitee-kubernetes-operator)

## Kubernetes CRDs

| CRD | Group | Kind |
|-----|-------|------|
| [ApiDefinition](crd/gravitee.io_apidefinitions.yaml) | gravitee.io | ApiDefinition |
| [ApiV4Definition](crd/gravitee.io_apiv4definitions.yaml) | gravitee.io | ApiV4Definition |
| [ApiResource](crd/gravitee.io_apiresources.yaml) | gravitee.io | ApiResource |
| [Application](crd/gravitee.io_applications.yaml) | gravitee.io | Application |
| [Subscription](crd/gravitee.io_subscriptions.yaml) | gravitee.io | Subscription |
| [ManagementContext](crd/gravitee.io_managementcontexts.yaml) | gravitee.io | ManagementContext |
| [SharedPolicyGroup](crd/gravitee.io_sharedpolicygroups.yaml) | gravitee.io | SharedPolicyGroup |
| [Group](crd/gravitee.io_groups.yaml) | gravitee.io | Group |
| [KafkaRoute](crd/gravitee.io_kafkaroutes.yaml) | gravitee.io | KafkaRoute |
| [Notification](crd/gravitee.io_notifications.yaml) | gravitee.io | Notification |

## Artifacts

### OpenAPI

- [Gravitee APIM Management API v2](openapi/gravitee-apim-openapi.yml)
- [Gravitee Access Management API](openapi/gravitee-am-openapi.yml)

### JSON Schema

- [API](json-schema/gravitee-api-schema.json)
- [Plan](json-schema/gravitee-plan-schema.json)
- [Domain](json-schema/gravitee-domain-schema.json)

### JSON Structure

- [API Structure](json-structure/gravitee-api-structure.json)

### JSON-LD

- [Gravitee Context](json-ld/gravitee-context.jsonld)

### Examples

- [Create API](examples/gravitee-apim-create-api-example.json)
- [Get API](examples/gravitee-apim-get-api-example.json)
- [Create Plan](examples/gravitee-apim-create-plan-example.json)
- [Create Subscription](examples/gravitee-apim-create-subscription-example.json)
- [Create AM Domain](examples/gravitee-am-create-domain-example.json)
- [Create AM Application](examples/gravitee-am-create-application-example.json)

### Spectral Rules

- [Gravitee Rules](rules/gravitee-rules.yml)

### Vocabulary

- [Gravitee Vocabulary](vocabulary/gravitee-vocabulary.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into workflows.

### Shared Per-API Definitions

- [Gravitee APIM Management API](capabilities/shared/gravitee-apim.yaml)

### Workflow Capabilities

| Workflow | Persona |
|----------|---------|
| [API Gateway Operations](capabilities/api-gateway-operations.yaml) | API Platform Engineer |
| [Traffic Observability](capabilities/traffic-observability.yaml) | SRE / API Observer |
| [MCP Publishing](capabilities/mcp-publishing.yaml) | AI Platform Engineer |
| [API Management](capabilities/api-management.yaml) | API Producer |
| [Access Management](capabilities/access-management.yaml) | Security Engineer |

## Commercial

- [Plans](plans/gravitee-plans-pricing.yml) — API Commons Plans 0.1 (Planet $2,500/mo, Galaxy/Universe custom, Comet $1,250/mo, Meteor/Asteroid custom, Agent Management and Enterprise Auth add-ons)
- [Rate Limits](rate-limits/gravitee-rate-limits.yml) — API Commons Rate Limits 0.1 (self-hosted; operator-configured Rate Limit, Quota, Spike Arrest, and AI Prompt Token Tracking policies)
- [FinOps](finops/gravitee-finops.yml) — FOCUS 1.3 aligned (platform_subscription, production_gateways, federated_brokers, managed_apis, throughput_calls, ai_tokens, seats)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
