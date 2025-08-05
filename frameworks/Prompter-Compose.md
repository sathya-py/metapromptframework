# Prompter-Compose

Prompter-Compose is a modular prompt design framework focused on **composability** — building complex LLM instructions by combining smaller, reusable prompt units. Think of it like prompt engineering LEGO: break down large prompts into coherent **blocks**, then stack, swap, or inject them as needed.

### When to Use:
- Automating prompt construction
- Task pipelines (e.g., Research → Summarize → Rewrite)
- Multi-turn autonomous agents
- Reducing prompt engineering overhead

---

## Structure

- **Modules**: Self-contained prompt units like `Summarize`, `Classify`, `Critique`, `Rewrite`
- **Execution Order**: Sequence of modules for chained tasks
- **Data Flow**: Passing output from one module to the next
- **Constraints**: Limits like tone, length, or format
- **Context Bridge**: Shared background fed across modules

---

## Usage Flow

[Module 1: Task] → [Output] → [Module 2: Transform] → [Module 3: Evaluate]


---

## Template

<Global Context (optional)>  
<Module-1 Prompt>  
→ <Output of Module-1>  
<Module-2 Prompt using Module-1 Output>  
→ ...  
<Final Output>

---

## Example Modules

- `Module-SUM`: “Summarize the following content…”
- `Module-EXP`: “Expand the summary into a full article…”
- `Module-TWEET`: “Compress the result into a 280-character tweet…”
- `Module-STYLE`: “Rewrite the response in pirate slang…”

---

## Example Flow

1. **Module-1 (Summarize)**  
   Prompt: “Summarize this academic article in 3 bullet points.”  
2. **Module-2 (Style Transfer)**  
   Prompt: “Rewrite the bullet points in Gen Z slang.”  
3. **Module-3 (Compression)**  
   Prompt: “Compress into a tweet under 280 characters.”  

---

## Notes

- Mix & match modules like functions in a script
- Use YAML or JSON schemas if automating
- Great for chaining multiple LLM calls or agents
