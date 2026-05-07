# 🧱 Coupling Detector

## 🎯 Objective

Identify strong coupling, hidden dependencies, and structural issues that will make the system hard to evolve.

---

## 🧠 Prompt to run

Analyze this code from an architectural perspective.

Identify:

- tightly coupled components
- duplicated logic
- unclear separation of concerns
- implicit dependencies between modules
- business logic mixed with infrastructure concerns

For each issue:

1. Explain why it is problematic
2. Describe how it will impact future changes
3. Propose a more modular and maintainable structure

---

## ⚠️ What to look for

- Functions doing too many things  
- Direct dependencies between unrelated modules  
- Copy/pasted logic instead of shared abstractions  
- Business rules spread across multiple layers  
- Hard-coded values or behaviors  

---

## ✅ Expected outcome

- Clear identification of coupling hotspots  
- Suggestions to split responsibilities  
- Improved modularity  
- Better long-term maintainability  

---

## 💡 Why it matters

AI-generated code often “works” but creates hidden coupling.

👉 It becomes harder to:
- add features
- fix bugs
- onboard new developers

---

## 🔥 Bonus prompt

If you had to scale this codebase with a team of 5 developers, what would break first in the architecture?
