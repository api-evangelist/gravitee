---
name: gravitee-create-and-publish-plan
description: Create a new plan for an API and publish it so it becomes available to consumers.
api: openapi/gravitee-plans-api-openapi.yml
operations:
- createApiPlan
- publishApiPlan
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gravitee-plans-api-openapi.yml ; every operationId checked against the contract
---

# gravitee-create-and-publish-plan

Create a new plan for an API and publish it so it becomes available to consumers.

## Steps

1. 1. Call `createApiPlan` with the required request body fields (e.g., `name`, `description`, `security`, `status`) and include an authentication header (BasicAuth, BearerAuth, CookieAuth, or gravitee-auth).
2. 2. Verify the response contains the newly created `planId`.
3. 3. Call `publishApiPlan` using the `planId` from step 2, again providing an authentication header.

## Rules

- Authentication: one of BasicAuth, BearerAuth, CookieAuth, or gravitee-auth must be sent in the request headers.
- Idempotency: `publishApiPlan` is not idempotent; calling it multiple times on the same plan will return an error.
- Errors: HTTP 4xx/5xx responses indicate failure; handle validation errors from `createApiPlan` and state errors from `publishApiPlan`.
