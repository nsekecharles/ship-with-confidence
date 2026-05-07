# Input Validation Audit

## Objective

Ensure all inputs are validated, sanitized, and safe before processing.

---

## Prompt to run

Analyze all user inputs in this system.

Identify:

- missing validation
- incorrect validation
- lack of sanitization

For each input:

1. Define expected format
2. Identify risks
3. Propose validation rules

---

## What to look for

### Frontend / Mobile
- No client-side validation
- Over-reliance on frontend validation

### Backend
- Accepting raw input without validation
- No schema enforcement
- Direct use in queries

---

## Expected outcome

- Strong validation layer  
- Reduced injection risks  

---

## Why it matters

All attacks start with input.
