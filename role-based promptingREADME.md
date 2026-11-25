# Use Role-Based Prompting

## Task Overview
Tested role-based prompting in a free AI tool (ChatGPT / Gemini) by assigning specific expert personas to see how tone, depth, and focus change compared to generic prompts.

---

## Prompt 1: Code & Logic Review
- **Prompt Without Role:** Check this logic and tell me what could go wrong: `while x > 0: x = x - 4`
- **Output:** The loop subtracts 4 from `x` while `x` is greater than 0. If `x` is not updated properly or starts negative, it may behave unexpectedly.

- **Role-Based Prompt:**
  ```text
  Act as a strict C/Python programming instructor reviewing a student's loop logic.
  Analyze this snippet: `x = 15; while x > 0: x = x - 4`.
  Trace the values step by step, state the final value of `x`, and point out one edge case a beginner might miss. Keep it concise.
