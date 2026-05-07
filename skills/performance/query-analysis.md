# 🗄️ Query Analysis

## 🎯 Objective

Identify inefficient database access patterns and optimize data retrieval strategies.

---

## 🧠 Prompt to run

Analyze the database queries and data access patterns in this code.

Identify:

- N+1 query problems  
- unnecessary queries  
- missing indexes  
- inefficient joins or filters  
- over-fetching or under-fetching data  

For each issue:

1. Explain why it is inefficient
2. Describe its impact at scale
3. Propose optimized query patterns

---

## ⚠️ What to look for

- Queries inside loops  
- Multiple queries where one would suffice  
- Fetching entire objects when only a few fields are needed  
- Lack of pagination  
- Missing or incorrect indexing  

---

## ✅ Expected outcome

- Optimized database interactions  
- Reduced load on the database  
- Faster response times  

---

## 💡 Why it matters

The database is often the first bottleneck.

👉 And the hardest to fix once in production.

---

## 🧠 Key mindset

Every query has a cost.

👉 At scale, small inefficiencies become major issues.

---

## 🔥 Bonus prompt

Rewrite these queries as if the system had to support 10x more data and traffic.
