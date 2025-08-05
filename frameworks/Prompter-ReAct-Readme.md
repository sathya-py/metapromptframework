# Prompter-ReAct

## Description

Prompter-ReAct blends logical reasoning with interactive actions. The model “thinks”, takes an action (e.g., a tool call or simulated decision), observes the result, and loops back. This method mirrors how humans make decisions — iterating between reasoning and action.

## Why Use It

If your task requires **step-by-step analysis + external operations**, this format crushes it. Whether it’s web search, calculator use, memory lookup, or API calls — ReAct makes LLMs feel *alive* and *agent-like*.

## Examples

### ⚙️ Example 1 — LLM + Web Search Agent

Question: Who won the Ballon d'Or in 2024?

Thought: I need to search recent sports results.  
Action: Search “Ballon d'Or 2024 winner”  
Observation: Jude Bellingham won in 2024  
Thought: No further info needed  
Final Answer: Jude Bellingham

---

### ⚙️ Example 2 — Debugging Assistant

Question: This Python code throws a KeyError. Why?

Thought: I should inspect the dictionary usage.  
Action: Analyze line 22 where the error is triggered  
Observation: Line 22 tries `data['score']` but key is missing  
Thought: Likely cause is inconsistent keys  
Action: Suggest using `dict.get()` instead  
Final Answer: Use `data.get('score')` to avoid KeyError.

## Tip

ReAct is most effective when **actions have clear observations**. Always simulate or plug in tool outputs, even if mock — it keeps the loop tight and grounded.
