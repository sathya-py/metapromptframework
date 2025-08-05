# Prompter-Reflect

Prompter-Reflect is a meta-prompt pattern that injects self-evaluation and feedback into the LLM’s output loop. Instead of stopping at one answer, the model is prompted to *analyze, critique, and refine* its own initial response — producing higher-quality, more thoughtful outputs.

This pattern is essential in:
- Complex reasoning or logic tasks
- Sensitive content (legal, ethical, financial)
- Creative revision and quality assurance
- Multi-turn autonomous agents

## Structure

1. **Initial Task Prompt** — A standard prompt with the core task
2. **Reflective Evaluation Step** — Ask the model to critique/analyze its own output
3. **Revised Output Step** — Ask it to improve the response based on the reflection

## Usage Flow

Task → Response → Reflection → Revised Response


### Optional: Reflection Criteria
- Accuracy
- Clarity
- Brevity
- Empathy
- Creativity

## Template

**Task:** [Your main instruction]  
**Response:** [Let model generate response]  
**Reflect:** "Now evaluate your response. What could be improved?"  
**Revise:** "Improve your response based on your reflection."

## Example

**Task:** Summarize the key point of Stoicism in one paragraph.  
**Response:** [Model gives a summary]  
**Reflect:** "How clear and accurate is your answer? Would you change anything?"  
**Revise:** [Improved version based on self-review]
