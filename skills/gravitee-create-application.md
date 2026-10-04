---
name: gravitee-create-application
description: Create a new application and then list all applications in a security domain.
api: openapi/gravitee-application-api-openapi.yml
operations:
- createApplication
- listApplications
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gravitee-application-api-openapi.yml ; every operationId checked against the contract
---

# gravitee-create-application

Create a new application and then list all applications in a security domain.

## Steps

1. 1. Call `createApplication` with the required request body fields for the new application and include an `Authorization` header (BearerAuth, BasicAuth, CookieAuth, or gravitee-auth).
2. 2. Call `listApplications` with optional query parameters for pagination and include the same `Authorization` header.

## Rules

- Authentication: All requests must include a valid `Authorization` header using one of the supported schemes (BasicAuth, BearerAuth, CookieAuth, gravitee-auth).
- Pagination: `listApplications` supports standard pagination query parameters (e.g., `page`, `size`).
