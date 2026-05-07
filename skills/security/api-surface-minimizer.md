# API Surface Minimizer

## Objective

Reduce unnecessary data exposure and minimize attack surface.

---

## Prompt to run

Analyze all API responses.

For each endpoint:

1. List all returned fields
2. Identify sensitive or unnecessary data
3. Propose a minimal response structure

---

## What to look for

### Backend
- Returning full objects instead of required fields
- Exposing internal IDs or metadata
- Sending sensitive information (emails, tokens)

### Frontend / Mobile
- Using more data than necessary
- Storing sensitive data locally

---

## Expected outcome

- Minimal and secure API responses  
- Reduced data exposure  

---

## Why it matters

The more you expose, the more you risk.
