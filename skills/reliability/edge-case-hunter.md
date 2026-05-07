# Edge Case Hunter

## Objective

Identify edge cases and unexpected inputs that could break the system or produce incorrect behavior.

---

## Prompt to run

Analyze this code and identify all potential edge cases.

Focus on:

- invalid inputs
- null or undefined values
- empty datasets
- unexpected formats
- boundary conditions

For each edge case:

1. Describe the scenario
2. Explain what would currently happen
3. Identify the risk (crash, incorrect data, silent failure)
4. Propose a fix or safeguard

---

## What to look for

- Missing input validation  
- Assumptions about data presence  
- No handling of empty or partial data  
- Lack of defensive programming  
- Silent failures instead of explicit errors  

---

## Expected outcome

- Clear list of edge cases  
- Improved robustness  
- Reduced risk of runtime errors  
- Safer handling of unexpected situations  

---

## Why it matters

Users don’t break your system on purpose.

They break it by using it in ways you didn’t expect.

---

## Key mindset

Your system is only as strong as its weakest edge case.

---

## Bonus prompt

What is the smallest unexpected input that could break this system?
