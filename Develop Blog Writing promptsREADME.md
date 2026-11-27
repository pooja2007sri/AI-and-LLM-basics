# Develop Blog Writing Prompts

## Goal
Create structured prompts for blog writing and AI-assisted coding workflows—covering clear specifications, explanations, unit tests, debugging, and code review—while keeping final ownership and security in mind.

## What I Did
- Drafted structured prompts specifying language, framework, inputs, outputs, and constraints.
- Created prompts to request code explanations, unit tests, debugging help with exact error messages and relevant snippets, and code reviews.
- Tested and verified outputs by reviewing, running, and testing generated code while ensuring no secrets or private keys are ever shared in prompts.
- Added this task in its own folder in my GitHub repository with step-by-step commits.

## How to Run or Read
1. Open the prompt templates in this folder and paste them into your LLM/AI tool.
2. Fill in your target topic/language, framework, inputs/outputs, error logs, and constraints (without any API keys or secrets).
3. Run, test, and review the resulting output or code before using it.

## What I Learned
- Treating AI as a pair programmer works best when you set clear constraints and review, run, and test every output yourself.
- Sharing clear inputs, outputs, and exact error messages leads to much sharper debugging and unit test suggestions.
- Keeping secrets and private keys out of prompts is essential good practice.
