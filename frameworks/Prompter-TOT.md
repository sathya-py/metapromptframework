# Prompter-ToT

Tree of Thought (ToT) prompting is a method that allows LLMs to **branch and evaluate multiple reasoning paths** before committing to a final answer. It mimics human deliberation by encouraging idea generation, branching logic, and critical comparison across alternatives — especially useful for **complex reasoning**, **planning**, or **creative decision-making**.

## Core Structure

ToT prompting includes:

1. **Problem Statement** – What needs solving
2. **Initial Thoughts** – Brainstorm several possibilities or sub-paths
3. **Branch Exploration** – Explore each thought path individually
4. **Evaluation** – Compare the branches against criteria
5. **Final Answer** – Pick the best path or synthesize the best outcome

## Template

Problem: [Insert problem]

Step 1: Brainstorm 3 possible thought paths.  
Step 2: Explore each path in detail.  
Step 3: Evaluate all paths for feasibility, creativity, or impact.  
Step 4: Choose the best solution and justify it.

## Example Usage

Problem: Design a unique magic system for a fantasy RPG.

Step 1: Brainstorm  
- Path A: Magic through music  
- Path B: Memory-based spell recall  
- Path C: Emotion-powered rituals

Step 2: Explore  
- A: Songs act as spell codes. Players compose melodies to cast.  
- B: Spells fade unless remembered; players maintain mental “spellbooks”.  
- C: Emotions fuel casting, but drain psyche; high-risk/high-reward.

Step 3: Evaluate  
- A is creative but complex to implement  
- B has great gameplay tension  
- C offers emotional storytelling but may feel punishing

Step 4: Final Answer  
Go with Path B — memory-based magic. It balances lore, gameplay, and user retention.
