# 🔓 Auth Scope Breaker

## 🎯 Objective

Ensure users can only access what they are allowed to access.

---

## 🧠 Prompt to run

Analyze all endpoints and access logic.

Identify:

- missing authorization checks
- potential privilege escalation
- access to other users' data

Simulate scenarios where a user tries to access:

- another user’s data
- admin-only features
- restricted resources

---

## ⚠️ What to look for

### Backend
- ID-based access without ownership checks
- Missing role validation
- Logic relying only on frontend restrictions

### Frontend / Mobile
- Hidden features accessible via API calls
- No UI restrictions enforcement server-side

---

## ✅ Expected outcome

- Strict access control  
- No unauthorized data exposure  

---

## 💡 Why it matters

Most breaches are not hacks.

👉 They are broken access controls.
