---
name: gravitee-manage-api-lifecycle
description: Create a new API, deploy it to the gateway, and start it for use.
api: openapi/gravitee-apis-api-openapi.yml
operations:
- createApi
- deployApi
- startApi
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gravitee-apis-api-openapi.yml ; every operationId checked against the contract
---

# gravitee-manage-api-lifecycle

Create a new API, deploy it to the gateway, and start it for use.

## Steps

1. 1. `createApi` – provide the API definition fields (e.g., `name`, `version`, `description`, `proxy`, `paths`).
2. 2. `deployApi` – specify the `apiId` path parameter; no additional body fields required.
3. 3. `startApi` – specify the `apiId` path parameter; no additional body fields required.

## Rules

- Authentication: include a Bearer token in the `Authorization` header (BearerAuth).
- Idempotency: `createApi` is not idempotent; repeated calls may create duplicate APIs.
- Errors: on failure, the API returns standard HTTP error codes (e.g., 4xx for client errors, 5xx for server errors).
