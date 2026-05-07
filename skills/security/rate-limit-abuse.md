# 🔁 Abuse & Rate Limiting Check

## 🎯 Objective

Prevent abuse of the system through uncontrolled usage.

---

## 🧠 Prompt to run

Analyze how this system could be abused.

Identify:

- endpoints without rate limiting
- brute force risks
- spam scenarios

Propose protections:

- rate limiting
- throttling
- usage quotas

---

## ⚠️ What to look for

### Backend
- No request limits
- No protection on auth endpoints

### Frontend / Mobile
- No usage restrictions
- Easy automation via scripts

---

## ✅ Expected outcome

- Controlled API usage  
- Protection against abuse  

---

## 💡 Why it matters

Not all attacks are sophisticated.

👉 Some are just repeated requests.
