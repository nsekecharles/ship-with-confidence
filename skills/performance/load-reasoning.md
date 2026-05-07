# Load Reasoning

## Objective

Evaluate how the system behaves under increasing load and identify potential bottlenecks before they happen in production.

---

## Prompt to run

Analyze this system and simulate its behavior under load.

Consider the following scenarios:

- 100 users
- 1,000 users
- 10,000+ users

For each level:

1. Identify bottlenecks (database, API, network, CPU)
2. Explain why these bottlenecks occur
3. Estimate the impact on performance
4. Propose concrete improvements

Focus on:

- request flow
- database interactions
- external API calls
- synchronous vs asynchronous behavior

---

## What to look for

- Too many database queries per request  
- Blocking operations (synchronous calls)  
- No caching strategy  
- Heavy computations on request path  
- Repeated external API calls  

---

## Expected outcome

- Clear identification of bottlenecks  
- Understanding of system limits  
- Concrete actions to improve scalability  

---

## Why it matters

Your system won’t break when it stops working.

It will break when it becomes slow.

---

## Key mindset

Performance issues are often invisible at low scale.

They appear only when it’s too late.

---

## Bonus prompt

If I multiply traffic by 10 overnight, what breaks first and why?
