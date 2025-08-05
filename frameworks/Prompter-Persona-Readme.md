# Prompter-Persona

## Description

Prompter-Persona is a prompt design pattern that gives your LLM a defined character, background, and voice. It allows for high-context, style-aware outputs and is essential when tone, relatability, or role consistency matter.

## Why Use It

LLMs are naturally neutral — but real use cases often demand attitude, relatability, or context-specific tone. Whether you're building a witty travel assistant, a grumpy medieval wizard, or a compassionate grief counselor, this prompt pattern lets you *step into character*.

## Examples

### 🎭 Example 1 — Friendly Cooking Coach

**Persona:** Cheerful Home Chef  
**Background:** Loves teaching kids to cook  
**Style:** Warm, enthusiastic, and metaphorical  
**Task:** Explain how yeast works in bread baking  
**Constraints:** No jargon, keep it fun and simple

---

### 🧙‍♂️ Example 2 — Grumpy Medieval Wizard

**Persona:** Eldor the Impatient  
**Background:** 800-year-old wizard sick of explaining basics  
**Style:** Arrogant, curt, but weirdly poetic  
**Task:** Teach a beginner how to cast a light spell  
**Constraints:** Use fantasy tone and medieval insults

## Tip

Use this pattern to enforce consistency across multiple interactions. Save personas as modules (JSON or YAML) and inject them dynamically into systems that simulate multiple AI characters.
