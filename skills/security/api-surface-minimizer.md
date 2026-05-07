# API Surface Minimizer

Reduce the exposed attack surface and accidental public APIs.

## What to check
- New endpoints, ports, ingress rules
- Unnecessary methods/fields in APIs
- Admin/debug endpoints exposed in prod
- Over-permissive CORS

## Prompts
- "List all new externally reachable surfaces introduced by this change."
- "Which endpoints can be made internal-only or removed?"

## Output
- Surface inventory + justification for each exposure
