# Secret Exposure Check

## Objective

Prevent exposure of sensitive information such as API keys, tokens, and credentials.

---

## Prompt to run

Analyze this codebase and identify:

- hardcoded secrets
- exposed API keys
- insecure storage of credentials

---

## What to look for

### Frontend / Mobile
- API keys in code
- Secrets in config files
- Tokens stored in insecure storage

### Backend
- Secrets in source code
- Missing environment variable usage
- Logging sensitive data

---

## Expected outcome

- Secure secret management  
- No exposed credentials  

---

## Why it matters

Once exposed, a secret is compromised forever.
