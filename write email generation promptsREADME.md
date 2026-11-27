# Write Email Generation Prompts

## Goal
Create structured prompts for email generation and AI-assisted coding workflows—specifying clear inputs, outputs, constraints, explanations, unit tests, debugging context, and code review checks while keeping final ownership and security in mind.

## What I Did
- Drafted structured prompts defining target context/language, framework, inputs, outputs, and formatting constraints.
- Built prompt templates to request clear explanations, unit tests, debugging assistance (with exact error messages and relevant snippets), and quality reviews.
- Tested and verified all AI-generated outputs by reviewing, running, and validating them—making sure no secrets or private keys are ever pasted into prompts.
- Organized the prompt files and notes inside a dedicated folder in my GitHub repository.

## How to Run or Read
1. Open the prompt templates in this folder and copy a prompt into your AI/LLM tool.
2. Fill in your specific inputs, expected outputs, constraints, or error details (without including any API keys, passwords, or private keys).
3. Review, run, and test the generated output before using or sending it.

## What I Learned
- Treating AI as a pair programmer produces great suggestions, but you always own the final output—reviewing and testing everything is essential.
- Providing explicit inputs, outputs, constraints, and exact error messages dramatically improves debugging and test generation.
- Never pasting secrets or private keys into prompts is a critical security habit.
