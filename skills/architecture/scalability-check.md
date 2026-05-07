# Scalability Check

## Objective

Evaluate whether the current architecture can handle growth in users, data, and features.

---

## Prompt to run

Analyze this system and evaluate its scalability.

Simulate the following scenarios:

- 100 users
- 1,000 users
- 10,000+ users

For each level, identify:

- bottlenecks (database, API, network, CPU)
- single points of failure
- inefficient patterns (N+1 queries, blocking calls, etc.)

Then:

1. Explain why these issues occur
2. Estimate their impact
3. Propose concrete improvements

---

## What to look for

- Synchronous blocking operations  
- No caching strategy  
- Inefficient database queries  
- Tight coupling between services  
- Lack of horizontal scalability  

---

## Expected outcome

- Clear bottleneck identification  
- Understanding of system limits  
- Actionable improvements for scaling  

---

## Why it matters

Most systems don’t fail because they don’t work.

They fail because they **don’t scale**.

---

## Bonus prompt

If traffic suddenly increases x10 overnight, what part of the system breaks first and why?
