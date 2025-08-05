# Prompter-CoT

Prompter-CoT (Chain-of-Thought) is a step-by-step reasoning prompt structure that encourages an LLM to **think out loud** before giving an answer. Rather than jumping straight to a solution, the model breaks down its logic path — leading to more accurate, explainable, and robust outputs.

## Core Principles

- **Sequential logic** improves reasoning accuracy.
- **Intermediate steps** expose where thinking goes right or wrong.
- **Encourages slower, deliberate problem-solving**, especially for math, logic, analysis, or deduction tasks.

## Template

Question: [Insert the task or problem]

Let’s think step by step.

[Step-by-step reasoning here...]

Answer: [Final answer]

## Use Cases

- Math problems (word problems, equations)
- Logic puzzles
- Legal or medical reasoning
- Strategic analysis
- Debugging and diagnostics

## Example

Question: John has 3 red marbles and 5 blue marbles. He gives away 2 red marbles. How many does he have left?

Let’s think step by step.  
- John starts with 3 red marbles and 5 blue marbles.  
- He gives away 2 red marbles.  
- That leaves him with 1 red marble and 5 blue marbles.  

Answer: 1 red marble and 5 blue marbles
