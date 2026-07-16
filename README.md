# test

## Webhook retry behavior (current)

Current client webhook dispatch behavior is **single-attempt only** (no retries on failure).

## hello1 provisioning (v2 contract source section)

Use this exact section as the source text for operational runbooks:

1. Provision vendor credentials for the target environment.
2. Configure the v2 callback/webhook endpoint for that environment.
3. Validate connectivity with a test event before enabling traffic.

## Login page styling note

The current green styling is being replaced with a yellow/red gradient as part of **PLAT-2041**.