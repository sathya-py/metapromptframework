# Prompter-ReAct

Prompter-ReAct combines **reasoning** and **action** into an iterative prompting framework. The model doesn’t just think — it *thinks out loud*, acts based on intermediate thoughts, observes the results, and continues. It's especially powerful for **tool-augmented LLMs**, **search + synthesize flows**, and **complex decision chains** where thought and behavior need to interleave.

## Core Structure

ReAct consists of:

1. **Thought** – The model’s reasoning about the problem
2. **Action** – A decision or external operation based on that reasoning
3. **Observation** – Input/result from that action
4. *(Repeat)* – Loop until the final answer

## Template

Question: [Insert your query or problem]
Thought: [Model’s reflection or intermediate reasoning]
Action: [A function/tool call, step taken, or simulated operation]
Observation: [Result from action or feedback]
... repeat as needed ...
Final Answer: [Conclude based on the above]