# Logging Audit

## Objective

Ensure that the system produces meaningful, structured, and actionable logs to understand behavior in production.

---

## Prompt to run

Analyze this code and evaluate its logging strategy.

Identify:

- missing logs
- useless or noisy logs
- lack of structure (unstructured text vs structured logs)
- missing context (userId, requestId, etc.)
- critical operations that are not logged

For each issue:

1. Explain why it is a problem
2. Describe what information is missing
3. Propose concrete logging improvements

---

## What to look for

- No logs on critical actions (auth, payments, data updates)  
- Logs without context (no user, no request, no correlation id)  
- Logs that are too generic (“error occurred”)  
- Sensitive data accidentally logged  
- No distinction between info / warning / error  

---

## Expected outcome

- Clear and structured logging strategy  
- Better traceability of user actions  
- Easier debugging in production  
- Reduced noise and more signal  

---

## Why it matters

When something breaks in production:

Logs are your first (and sometimes only) source of truth

---

## Bonus prompt

If a user reports a bug, can I trace their journey through logs alone?

If not, what is missing?
