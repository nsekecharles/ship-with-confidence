# Security

Validation skills focused on preventing security regressions before shipping.

Use these skills to audit your code for common vulnerabilities, broken access controls, and data exposure risks before every push.

## Skills

| File | Description |
|------|-------------|
| [trust-boundary.md](./trust-boundary.md) | Identify where the system trusts data it should not, and enforce strict validation at every boundary. |
| [auth-scope-breaker.md](./auth-scope-breaker.md) | Verify users can only access what they are authorized to access — no privilege escalation. |
| [attack-simulation.md](./attack-simulation.md) | Think like an attacker to surface entry points, attack vectors, and exploitation scenarios. |
| [input-validation.md](./input-validation.md) | Ensure all user inputs are validated and sanitized before processing. |
| [api-surface-minimizer.md](./api-surface-minimizer.md) | Reduce unnecessary data exposure and minimize your API attack surface. |
| [secret-exposure.md](./secret-exposure.md) | Detect hardcoded secrets, exposed API keys, and insecure credential storage. |
| [rate-limit-abuse.md](./rate-limit-abuse.md) | Identify endpoints vulnerable to abuse, brute force, and spam through missing rate limits. |

## When to use

Run at least one security skill before every push, especially when you:

- Add or modify authentication or authorization logic
- Introduce new API endpoints
- Handle user-submitted data
- Add third-party integrations or credentials
