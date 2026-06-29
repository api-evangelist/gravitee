# Programmatic API Onboarding — Gravitee

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Gravitee: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`gravitee-api-auth.mjs`](gravitee-api-auth.mjs)
- Run `node gravitee-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/07/12/gravitee-gets-closer-than-most/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
