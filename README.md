# Gravitee (gravitee)

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

Gravitee.io is an open-source API management platform from GraviteeSource, combining a high-performance API Gateway, full-lifecycle API Management, Access Management (IAM), Cockpit (multi-environment control plane), an Alert Engine, a Kubernetes Operator, and a new AI Agent Management suite with native MCP and LLM-proxy capabilities. The core projects are Apache 2.0 OSS, with an Enterprise commercial offering and a managed Gravitee Cloud SaaS. The platform supports synchronous and asynchronous APIs across REST, GraphQL, WebSocket, gRPC, SSE, Webhooks, Kafka, MQTT, AMQP, and Model Context Protocol (MCP).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Gateway
- API Management
- Access Management
- Identity
- Event-Driven
- Event Management
- Kafka Gateway
- Kafka
- MQTT
- GraphQL
- gRPC
- AI Gateway
- MCP
- A2A
- LLM Proxy
- Multi-Gateway Federation
- Developer Portal
- Open Source
- Apache 2.0

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-21

## APIs

### Gravitee API Management

Gravitee API Management (APIM) is the core product — an open-source, flexible, blazing-fast API gateway, management plane, and developer portal. It supports v2 "proxy" APIs and v4 message-oriented APIs over REST, GraphQL, WebSocket, gRPC, SSE, Webhooks, Kafka, MQTT, AMQP, Solace, RabbitMQ, and MCP. Lifecycle, policies, plans, applications, subscriptions, federation, and analytics are all managed through the Management API and consoles.

- **Human URL:** [https://www.gravitee.io/platform/api-management](https://www.gravitee.io/platform/api-management)
- **Base URL:** `https://documentation.gravitee.io/apim`

#### Tags

- API Gateway
- API Management
- Lifecycle
- Developer Portal
- Federation
- Open Source

#### Properties

- [Documentation](https://documentation.gravitee.io/apim)
- [Getting Started](https://documentation.gravitee.io/apim/getting-started)
- [Changelog](https://documentation.gravitee.io/apim/release-information/changelog)
- [License](https://github.com/gravitee-io/gravitee-api-management/blob/master/LICENSE.txt)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-api-management)
- [SDK](https://github.com/gravitee-io/gravitee-clients-sdk)
- [SDK](https://github.com/gravitee-io/terraform-provider-apim)
- [C L I](https://github.com/gravitee-io/graviteeio-cli)
- [Kubernetes Operator](https://github.com/gravitee-io/gravitee-kubernetes-operator)
- [Helm Chart](https://github.com/gravitee-io/helm-charts)
- [Docker Image](https://hub.docker.com/r/graviteeio/apim-gateway)
- [OpenAPI](openapi/gravitee-apim-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [J S O N- L D  Context](json-ld/gravitee-context.jsonld)
- [J S O N  Schema](json-schema/gravitee-api-schema.json)
- [J S O N  Schema](json-schema/gravitee-plan-schema.json)
- [Kubernetes C R D](crd/gravitee.io_apidefinitions.yaml)
- [Kubernetes C R D](crd/gravitee.io_apiv4definitions.yaml)
- [Kubernetes C R D](crd/gravitee.io_apiresources.yaml)
- [Kubernetes C R D](crd/gravitee.io_applications.yaml)
- [Kubernetes C R D](crd/gravitee.io_subscriptions.yaml)
- [Kubernetes C R D](crd/gravitee.io_managementcontexts.yaml)
- [Kubernetes C R D](crd/gravitee.io_sharedpolicygroups.yaml)
- [Kubernetes C R D](crd/gravitee.io_groups.yaml)
- [Kubernetes C R D](crd/gravitee.io_notifications.yaml)
- [Plan](plans/gravitee-plans-pricing.yml)
- [Rate  Limit](rate-limits/gravitee-rate-limits.yml)
- [Fin Ops](finops/gravitee-finops.yml)
- [Capabilities](capabilities/api-gateway-operations.yaml)
- [Capabilities](capabilities/traffic-observability.yaml)

### Gravitee Access Management

Gravitee Access Management (AM) is an open-source Identity and Access Management solution offering OAuth2, OpenID Connect (OIDC), UMA 2.0, CIBA, SCIM 2.0, and SAML 2.0. It manages security domains, applications, users, identity providers, MFA factors, bot detection, certificates, flows, forms, themes, and policies. AM provides an admin REST API (Management API) and a runtime authorization server (Gateway).

- **Human URL:** [https://www.gravitee.io/platform/access-management](https://www.gravitee.io/platform/access-management)
- **Base URL:** `https://documentation.gravitee.io/am`

#### Tags

- Identity
- Access Management
- OAuth2
- OIDC
- SAML
- SCIM
- UMA
- Open Source

#### Properties

- [Documentation](https://documentation.gravitee.io/am)
- [Reference](https://documentation.gravitee.io/am/reference/am-api-reference)
- [Changelog](https://documentation.gravitee.io/am/releases-and-changelog/release-notes)
- [License](https://github.com/gravitee-io/gravitee-access-management/blob/master/LICENSE)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-access-management)
- [SDK](https://github.com/gravitee-io/gravitee-access-management/tree/master/gravitee-am-management-api-sdk-java)
- [Helm Chart](https://github.com/gravitee-io/helm-charts/tree/master/helm/gravitee-am)
- [Docker Image](https://hub.docker.com/r/graviteeio/am-gateway)
- [OpenAPI](openapi/gravitee-am-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [J S O N- L D  Context](json-ld/gravitee-context.jsonld)
- [J S O N  Schema](json-schema/gravitee-domain-schema.json)
- [Capabilities](capabilities/access-management.yaml)

### Gravitee Cockpit

Gravitee Cockpit is the multi-environment, multi-installation control plane for Gravitee. It centralizes management of multiple APIM and AM installations (dev, staging, prod, regions) into one console, enabling promotion of APIs across environments, centralized inventory, and organization-wide governance.

- **Human URL:** [https://documentation.gravitee.io/cockpit](https://documentation.gravitee.io/cockpit)
- **Base URL:** `https://cockpit.gravitee.io`

#### Tags

- Control Plane
- Multi-Environment
- Cockpit

#### Properties

- [Documentation](https://documentation.gravitee.io/cockpit)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-cockpit-connectors)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-cockpit-api)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gravitee Alert Engine

Gravitee Alert Engine (AE) is a real-time API monitoring solution that tracks performance, availability, errors, quota approach, and security events across all Gravitee gateways. It evaluates conditions, fires triggers, and routes notifications through webhooks, email, Slack, and other channels.

- **Human URL:** [https://documentation.gravitee.io/ae](https://documentation.gravitee.io/ae)
- **Base URL:** `https://documentation.gravitee.io/ae`

#### Tags

- Alerting
- Monitoring
- Observability
- Notifications

#### Properties

- [Documentation](https://documentation.gravitee.io/ae)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-alert-api)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-ae-connectors)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gravitee AI Agent Management

Gravitee AI Agent Management brings the API management discipline to agentic AI ecosystems. It is delivered as an Enterprise add-on package and includes an LLM Proxy (model routing, prompt-token tracking, prompt guard-rails, RAG), an MCP Proxy and MCP Tool Server, an A2A Proxy for agent-to-agent flows, an Agent Catalog, and AI-aware Identity and Authorization (MCP resource server, OpenFGA permission engine, AuthZen PDP).

- **Human URL:** [https://www.gravitee.io/platform/ai-agent-management](https://www.gravitee.io/platform/ai-agent-management)
- **Base URL:** `https://documentation.gravitee.io/apim`

#### Tags

- AI Gateway
- MCP
- LLM Proxy
- Agentic
- A2A
- RAG
- Enterprise

#### Properties

- [Documentation](https://documentation.gravitee.io/apim)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-apim-mcp-server)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-inference)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-inference-service)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-policy-ai-prompt-token-tracking)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-policy-ai-prompt-guard-rails)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-policy-ai-retrieval-augmented-generation)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-resource-ai-model-api)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-resource-ai-vector-store-api)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-resource-ai-model-text-classification)
- [GitHub Repository](https://github.com/gravitee-io/llamaj.cpp)
- [Capabilities](capabilities/mcp-publishing.yaml)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gravitee Kafka Gateway

The Gravitee Kafka Gateway brings full API management discipline to Apache Kafka. It sits in front of one or more Kafka clusters and applies authentication mediation, ACLs, quotas, message filtering and routing, schema and serialization policies, virtual topics, and subscription workflows — exposing Kafka as a governed, productized event streaming surface for internal and external consumers.

- **Human URL:** [https://www.gravitee.io/platform/kafka-gateway](https://www.gravitee.io/platform/kafka-gateway)
- **Base URL:** `https://documentation.gravitee.io/apim`

#### Tags

- Kafka
- Event Streaming
- Event Gateway
- Message Broker
- Governance
- Open Source

#### Properties

- [Documentation](https://documentation.gravitee.io/apim)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-api-management)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gravitee Kubernetes Operator

The Gravitee Kubernetes Operator (GKO) is a Go-based Kubernetes operator that lets platform teams declare Gravitee APIs, applications, subscriptions, shared policy groups, and management contexts as Kubernetes custom resources. It reconciles those resources against one or more Gravitee APIM installations.

- **Human URL:** [https://documentation.gravitee.io/apim/kubernetes-operator](https://documentation.gravitee.io/apim/kubernetes-operator)
- **Base URL:** `https://github.com/gravitee-io/gravitee-kubernetes-operator`

#### Tags

- Kubernetes
- Operator
- GitOps
- CRD
- Open Source

#### Properties

- [Documentation](https://documentation.gravitee.io/apim/kubernetes-operator)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-kubernetes-operator)
- [Helm Chart](https://github.com/gravitee-io/gravitee-kubernetes-operator/tree/master/helm/gko)
- [License](https://github.com/gravitee-io/gravitee-kubernetes-operator/blob/master/LICENSE.txt)
- [Kubernetes C R D](crd/gravitee.io_apidefinitions.yaml)
- [Kubernetes C R D](crd/gravitee.io_apiv4definitions.yaml)
- [Kubernetes C R D](crd/gravitee.io_apiresources.yaml)
- [Kubernetes C R D](crd/gravitee.io_applications.yaml)
- [Kubernetes C R D](crd/gravitee.io_subscriptions.yaml)
- [Kubernetes C R D](crd/gravitee.io_managementcontexts.yaml)
- [Kubernetes C R D](crd/gravitee.io_sharedpolicygroups.yaml)
- [Kubernetes C R D](crd/gravitee.io_groups.yaml)
- [Kubernetes C R D](crd/gravitee.io_kafkaroutes.yaml)
- [Kubernetes C R D](crd/gravitee.io_notifications.yaml)
- [Postman Collection](collections/gravitee-am.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-am.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gravitee-apim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gravitee-apim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/gravitee-io)
- [Website](https://www.gravitee.io/)
- [Documentation](https://documentation.gravitee.io/)
- [Getting Started](https://documentation.gravitee.io/apim/getting-started)
- [Blog](https://www.gravitee.io/blog/all)
- [Pricing](https://www.gravitee.io/pricing)
- [Changelog](https://documentation.gravitee.io/apim/release-information/changelog)
- [GitHub Organization](https://github.com/gravitee-io)
- [GitHub Repository](https://github.com/gravitee-io/gravitee-api-management)
- [Community](https://community.gravitee.io/)
- [Issue  Tracker](https://github.com/gravitee-io/gravitee-api-management/issues)
- [Partners](https://www.gravitee.io/partners)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [J S O N- L D  Context](json-ld/gravitee-context.jsonld)
- [J S O N  Schema](json-schema/gravitee-api-schema.json)
- [J S O N  Schema](json-schema/gravitee-plan-schema.json)
- [J S O N  Schema](json-schema/gravitee-domain-schema.json)
- [Plan](plans/gravitee-plans-pricing.yml)
- [Rate  Limit](rate-limits/gravitee-rate-limits.yml)
- [Fin Ops](finops/gravitee-finops.yml)
- [Capabilities](capabilities/api-gateway-operations.yaml)
- [Capabilities](capabilities/traffic-observability.yaml)
- [Capabilities](capabilities/mcp-publishing.yaml)
- [Capabilities](capabilities/api-management.yaml)
- [Capabilities](capabilities/access-management.yaml)
- [M C P Server](https://github.com/gravitee-io/gravitee-apim-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
