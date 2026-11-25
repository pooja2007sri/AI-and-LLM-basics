# Implement Chain-of-Thought Prompting

## What I Did
I practiced Chain-of-Thought (CoT) and step-by-step reasoning prompts in a free AI tool (ChatGPT / Gemini) and compared direct answers against prompts that ask the model to think step by step, use few-shot examples, and separate sections with delimiters (`###`).

---

## Prompt 1: Step-by-Step Logical & Math Reasoning
- **Direct Prompt (Without CoT):** A tank is filled at 6 liters per minute and has a leak draining 2 liters per minute. How many minutes will it take to fill a 100-liter tank? Give only the number.
- **Output:** 25

- **Chain-of-Thought Prompt:**
  ```text
  ### Task
  Solve the word problem below. Think step by step before giving the final answer.

  ### Problem
  A tank is filled at 6 liters per minute and has a leak draining 2 liters per minute. How many minutes will it take to fill a 100-liter tank?

  ### Output Format
  1. Step-by-step calculation
  2. Final Answer
