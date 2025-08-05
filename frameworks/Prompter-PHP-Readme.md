# Prompter-PHP

## Description

Prompter-PHP (Prompt Hooks Protocol) is a composable prompting format that splits prompts into named sections or “hooks” like ROLE, CONTEXT, INSTRUCTION, STYLE, and GOAL. Each hook can be reused, injected, or versioned independently.

## Why Use It

This system is perfect for anyone building LLM pipelines, prompt chains, or agent frameworks. It gives you clean separation of concerns, makes prompts easier to debug, and allows partial updates without rewriting everything. Think of it as the MVC pattern, but for prompt engineering.

## Examples

### 🧠 Example 1 — Prompt for a Travel Blog Post

[HOOK:ROLE]
You are a humorous and descriptive travel blogger.

[HOOK:CONTEXT]
You’re covering a road trip from Delhi to Spiti Valley.

[HOOK:INSTRUCTION]
Write a 500-word blog post highlighting the drive, food stops, and weather.

[HOOK:STYLE]
Use humor and vivid imagery.

[HOOK:GOAL]
Inspire readers to plan their next trip.


---

### 🧠 Example 2 — Prompt for Teaching Python

[HOOK:ROLE]
You are a friendly coding tutor.

[HOOK:CONTEXT]
The student is struggling with Python loops.

[HOOK:INSTRUCTION]
Explain for and while loops with examples and when to use each.

[HOOK:STYLE]
Use simple language and emoji to lighten the mood.

[HOOK:GOAL]
Help the student write their first loop-based program.


## Tip

Store hooks in separate files or variables, and load them into templates at runtime. This makes your prompt system flexible, scalable, and easier to maintain across large projects.

