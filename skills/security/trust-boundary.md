# Trust Boundary

Identify and document trust boundaries in the system.

## What to check
- Where untrusted input enters (HTTP, queues, files, CLI, env vars)
- Boundary crossings (service-to-service, tenant-to-tenant, user-to-admin)
- Data classification changes (PII, secrets, tokens)

## Prompts
- "List all trust boundaries in this change and how input is validated at each boundary."
- "What assumptions are we making about upstream data and are they enforced?"

## Outputs
- Trust boundary diagram (textual is fine)
- List of boundary checks and owners
