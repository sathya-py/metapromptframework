# Prompter-PHP

Prompter-PHP (Prompt Hooks Protocol) is a modular prompting architecture that treats prompts like software — breaking them into reusable "hooks" that can be injected or overridden. Inspired by plugin systems in software frameworks, this approach makes prompts **extensible, composable, and dynamically controllable**.

## Hook-Based Prompt Structure

A prompt is divided into standard, named hooks:

- [HOOK:ROLE] – The persona or expertise the model should assume
- [HOOK:CONTEXT] – Background, situation, or reference material
- [HOOK:INSTRUCTION] – The specific task to be performed
- [HOOK:STYLE] – Tone, language, or format requirements
- [HOOK:GOAL] – The ultimate purpose behind the task

This structure allows you to:
- Compose prompts dynamically (from UI, scripts, agents)
- Swap in different hooks for different personas or tasks
- Maintain a central library of reusable prompt components

## Prompt Skeleton Template

[HOOK:ROLE]
[HOOK:CONTEXT]
[HOOK:INSTRUCTION]
[HOOK:STYLE]
[HOOK:GOAL]

## Example

[HOOK:ROLE]
You are a science journalist with a knack for making complex topics simple.

[HOOK:CONTEXT]
You’re writing about a new discovery in quantum computing.

[HOOK:INSTRUCTION]
Summarize the breakthrough in 3 paragraphs for high school readers.

[HOOK:STYLE]
Use analogies and avoid jargon. Make it feel like a fun story.

[HOOK:GOAL]
Get students curious about physics and computer science.

## Implementation

- Store hooks as JSON, YAML, or plain text segments
- Inject dynamically at runtime (e.g. in a prompt template engine)
- Use version control to track hook changes individually