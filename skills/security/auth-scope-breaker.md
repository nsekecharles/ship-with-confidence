# Auth Scope Breaker

Look for authorization gaps and scope escalation paths.

## What to check
- Missing authorization checks on new/changed endpoints
- Overly broad scopes/roles
- Horizontal/vertical privilege escalation
- IDOR risks (insecure direct object references)

## Prompts
- "For each endpoint touched, show the exact authZ decision and required scope/role."
- "Try to access another user's resources—what prevents it?"

## Red flags
- Relying on client-provided identifiers without server-side ownership checks
- Using `isAdmin` flags without strong provenance
