# Prompter-Compose

## Description

Prompter-Compose is a compositional prompt architecture that breaks complex tasks into modular blocks. Each block performs a focused function, and blocks are executed in sequence or parallel with data passed between them.

---

## Why Use It

Most prompts try to do too much at once. This fixes that by:
- Letting you reuse prompt “functions”
- Chaining multi-step logic cleanly
- Making debugging & iteration easier
- Enabling AI pipelines or agent workflows

Perfect for complex workflows, automation, and precision control.

---

## Examples

### 🧱 Example 1 — Research Agent Chain

1. **Module-1 (Search)**  
   Prompt: “Search the web for recent AI breakthroughs.”  
2. **Module-2 (Summarize)**  
   Prompt: “Summarize the findings in plain English.”  
3. **Module-3 (Opinion)**  
   Prompt: “Add a short commentary on ethical implications.”

---

### 🧱 Example 2 — Educational Tutor Flow

1. **Module-1 (Explain)**  
   Prompt: “Explain the Pythagorean theorem to a 10-year-old.”  
2. **Module-2 (Quiz)**  
   Prompt: “Generate 3 simple math problems based on that explanation.”  
3. **Module-3 (Feedback)**  
   Prompt: “Evaluate the student’s answers and offer corrections.”

---

## Tip

Think like a software engineer: treat prompts like modular components. You can version, A/B test, and reuse them across workflows. Bonus: integrate with external tools for API-style prompt chaining.
