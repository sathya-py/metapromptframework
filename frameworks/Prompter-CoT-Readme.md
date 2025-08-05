# Prompter-CoT

## Description

Prompter-CoT (Chain-of-Thought) prompting helps the LLM reason through problems by explicitly modeling its thought process step by step. This format increases accuracy in logical tasks and provides transparent reasoning.

## Why Use It

When you need reliable answers in logic-heavy tasks — math, code, planning, law, etc. — CoT helps the model slow down and simulate a thinking path. It’s also excellent for debugging *why* an answer went wrong.

## Examples

### 🧠 Example 1 — Legal Reasoning

Question: Can a person be convicted based solely on circumstantial evidence?

Let’s think step by step.  
- Circumstantial evidence refers to indirect evidence.  
- Many legal systems allow convictions based on circumstantial evidence alone.  
- However, it must meet the threshold of "beyond a reasonable doubt."  
- Therefore, yes, if the evidence is strong enough.

Answer: Yes, a person can be convicted based on circumstantial evidence.

---

### 🧠 Example 2 — Business Planning

Question: Should the company expand to Southeast Asia in Q3?

Let’s think step by step.  
- Q2 revenue exceeded projections by 20%, indicating strong growth.  
- Southeast Asia has growing demand in our sector.  
- However, logistics costs and currency volatility are rising.  
- We also lack local partners.  
- A phased approach with one test market might be better.

Answer: Proceed with a phased expansion in one Southeast Asian market.

## Tip

Always add "Let’s think step by step" in your CoT prompts. It primes the model to enter a deliberate reasoning mode.
