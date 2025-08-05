# Prompter-Agent

## Description

Prompter-Agent is a modular prompt blueprint for creating agent-like LLM behaviors. It structures the prompt to simulate a named role, scoped task, defined input, and expected output — making it perfect for multi-agent pipelines or delegated subtasks.

## Why Use It

If you're building agent-based systems — whether in AI simulations, assistant platforms, or tool-integrated environments — this meta-prompt gives you plug-and-play control. Each agent can be spun up as a stateless or memory-aware prompt unit.

## Examples

### 🤖 Example 1 — Code Review Agent

Agent Name: ReviewBot  
Domain: Backend Engineering  
Task: Identify inefficiencies in the provided Python code  
Input: A Python function that loops over large data  
Constraints: Output only critical performance issues  
Output Format:  
- Issue  
- Line Number  
- Suggested Fix

---

### 🤖 Example 2 — Marketing Critique Agent

Agent Name: AdSniper  
Domain: Copywriting  
Task: Critique a Facebook ad for tone and clarity  
Input: Ad copy text  
Constraints: Evaluate as if targeting Gen Z audience  
Output Format:  
- Clarity Score (1–10)  
- Engagement Potential  
- Suggested Rewrite

## Tip

Define clear Output Format if chaining multiple agents. This ensures clean handoffs and deterministic output in complex workflows.
