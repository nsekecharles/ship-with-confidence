# Trust Boundary Detector

## Objective

Identify where the system trusts data it should not trust and enforce strict validation at every boundary.

---

## Prompt to run

Analyze this system and identify all trust boundaries:

- Frontend → Backend
- Mobile → Backend
- Backend → Database
- Backend → External services

For each boundary:

1. Identify what data is being trusted
2. Explain why this is risky
3. Propose validation and sanitization strategies

---

## What to look for

### Frontend / Mobile
- Trusting client-provided fields (role, userId, flags)
- Hidden fields used for business logic
- No validation before sending data

### Backend
- No validation of incoming requests
- Direct use of request data in business logic
- No schema validation

---

## Expected outcome

- Clear identification of trust violations  
- Strong validation strategy  
- Reduced attack surface  

---

## Why it matters

The client is always untrusted.

Always.
