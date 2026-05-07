# 🧠 AI Engineering Validation Skills

**A collection of prompt-based engineering validation skills to run before every push.
Built for developers using AI to ship fast without losing control over security, scalability, and reliability.**

---

## 🚀 Why this exists

AI can generate code faster than ever.

But speed creates a new problem:

👉 You can ship things you don’t fully understand.

This repository is not about writing code.

It’s about **validating what you are about to ship**.

---

## ⚠️ The problem

When using AI to code, most people validate like this:

* “It works”
* “No errors”
* “Looks good”

But in real-world systems, that’s not enough.

You need to think about:

* Security
* Access control
* Data exposure
* Scalability
* Failure scenarios
* Abuse patterns

👉 Things that don’t break… until they do.

---

## 🧩 What are “Skills”?

A skill is a **reusable validation unit**:

* a prompt
* a mindset
* a specific engineering check

Each skill helps you **challenge your code before pushing it**.

---

## 📂 Repository Structure

---

### 🔐 Security

```
skills/security/
├── trust-boundary.md
├── auth-audit.md
├── attack-simulation.md
```

---

### ⚡ Performance

```
skills/performance/
├── load-reasoning.md
├── query-analysis.md
```

---

### 🧱 Architecture

```
skills/architecture/
├── coupling-detector.md
├── scalability-check.md
```

---

### 🛡️ Reliability

```
skills/reliability/
├── edge-case-hunter.md
├── failure-scenarios.md
```

---

### 📊 Observability

```
skills/observability/
├── logging-audit.md
├── debug-readiness.md
```

---

### 🧠 Each skill includes

* 🎯 Objective
* 🧠 Prompt to run
* ⚠️ What to look for
* ✅ Expected outcome

---

> 💡 Each skill is designed to be executed on a code diff or feature before pushing.

---

## 🛠️ How to use

1. Generate or write your code (with or without AI)
2. Take your diff / modified files
3. Run the relevant skills (copy/paste prompts)
4. Review the output critically
5. Fix issues before pushing

---

## 🔁 Recommended workflow

Before every push, at minimum:

* Run a **Security skill**
* Run an **Access / Auth skill**
* Run an **API exposure skill**
* Run a **Performance reasoning skill**

👉 Think of this as your **pre-push engineering checklist**

---

## 🔥 Core skills included

* Trust Boundary Detector
* Attack Simulation
* Auth Scope Breaker
* API Surface Minimizer
* Load Reasoning
* Coupling Detector
* Edge Case Hunter
* Abuse Scenario Builder
* Failure Scenario Simulator
* Debug Readiness Check

---

## 🧠 Philosophy

AI is not the problem.

Blind usage is.

👉 These skills are here to shift you from:

* “AI generated it, so it’s probably fine”

To:

* “I understand what I’m about to ship”

---

## 💡 Important

These prompts are not magic.

They won’t replace:

* real testing
* production monitoring
* engineering experience

But they will:

👉 expose what you’re not seeing yet

---

## 🤝 Contributing

Feel free to:

* add new skills
* improve prompts
* share real-world cases

---

## 📌 Final note

**I don’t ask AI to write code for me.
I ask it to challenge what I build.**
