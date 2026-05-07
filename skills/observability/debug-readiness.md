# 🧪 Debug Readiness Check

## 🎯 Objective

Evaluate whether the system can be debugged effectively in production conditions.

---

## 🧠 Prompt to run

Analyze this system from a debugging perspective.

Assume a bug happens in production.

Evaluate:

- do we have enough logs to understand the issue?
- can we reproduce the problem?
- do we have visibility into system behavior?
- are errors handled properly?

Then:

1. Identify missing debugging capabilities
2. Describe what would make debugging difficult
3. Propose concrete improvements

---

## ⚠️ What to look for

- Silent failures (errors swallowed or ignored)  
- Missing error handling  
- No monitoring or alerting signals  
- No way to correlate events (requestId, traceId)  
- Lack of visibility into external dependencies  

---

## ✅ Expected outcome

- Clear understanding of debugging gaps  
- Better error visibility  
- Improved observability and monitoring readiness  

---

## 💡 Why it matters

A system is not “done” when it works.

👉 It’s done when you can **debug it under pressure**

---

## 🧠 Key mindset

If it breaks at 2am:

👉 Can you understand what happened in minutes, not hours?

---

## 🔥 Bonus prompt

Simulate a production bug:

- API returns 500 randomly  
- Some users report missing data  

How would I investigate this with the current system?
