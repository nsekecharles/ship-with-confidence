# Explain Unknowns

## Objective

Identify what you don’t fully understand in the code and expose hidden assumptions, implicit logic, and potential blind spots.

---

## Prompt to run

Analyze this code as if I did not fully understand everything in it.

Your goal is to identify:

- parts of the code that are not immediately clear
- implicit decisions or assumptions
- logic that “works” but is not explained
- areas where hidden complexity might exist

For each point:

1. Explain it in simple terms
2. Highlight why it might be risky
3. Suggest how to make it more explicit or safer

---

## What to look for

- Magic values or unexplained constants  
- Complex logic without clear naming  
- Code that relies on implicit behavior  
- External dependencies not clearly understood  
- Patterns copied without explanation  

---

## Expected outcome

- Better understanding of the code  
- Identification of hidden risks  
- Clearer and more explicit logic  
- Reduced cognitive load  

---

## Why it matters

The biggest risk when using AI is not bad code.

It’s **code you don’t understand but still ship**

---

## Key mindset

If you cannot explain it:

you don’t control it

---

## Bonus prompt

Explain this code as if I had to teach it to another developer tomorrow.

What parts would I struggle to explain clearly?
