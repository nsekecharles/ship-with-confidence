# 🧪 Failure Scenario Simulator

## 🎯 Objective

Evaluate how the system behaves when things go wrong and ensure it fails gracefully.

---

## 🧠 Prompt to run

Simulate failure scenarios for this system.

Consider:

- database unavailable
- external API down
- network latency or timeouts
- partial failures (only some components failing)

For each scenario:

1. Describe what happens today
2. Identify weaknesses in error handling
3. Evaluate user impact
4. Propose improvements (fallbacks, retries, timeouts, circuit breakers)

---

## ⚠️ What to look for

- No error handling or fallback strategy  
- System crashes instead of degrading gracefully  
- Blocking calls to external services  
- No retry mechanisms  
- No timeout handling  

---

## ✅ Expected outcome

- Better failure resilience  
- Graceful degradation instead of crashes  
- Improved user experience under failure conditions  

---

## 💡 Why it matters

Failures are not exceptions.

👉 They are part of normal system behavior.

---

## 🧠 Key mindset

Don’t ask “if it fails”.

👉 Ask “how it fails”.

---

## 🔥 Bonus prompt

If one dependency fails, how can the system continue operating in a degraded mode?
