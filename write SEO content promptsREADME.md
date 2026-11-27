# Write SEO Content Prompts

## Goal
Design and test structured prompts that generate search-friendly, accurate, and readable SEO content while guiding how a reviewer evaluates the output.

## What I Did
- Defined the one-line goal and reviewer checklist for the task before writing prompts.
- Built SEO content prompts covering target keywords, search intent, structure (headings, meta details, FAQs), and tone constraints.
- Tested the prompts with normal inputs and edge/unusual inputs (such as vague topics, missing keywords, or conflicting constraints), refining the instructions where outputs drifted.
- Organized the prompt drafts, sample outputs, and notes in this folder and committed changes step by step in Git.

## How to Run or Read
1. Open the prompt file(s) in this folder and copy the prompt into your LLM interface.
2. Replace placeholder fields (such as topic, target keyword, audience, and word count) with your test case.
3. Review the generated output against the SEO checklist and edge-case notes in this folder.

## What I Learned
- Clear constraints around search intent, structure, and factual boundaries prevent generic "fluff" SEO text.
- Testing edge cases early shows where a prompt needs stricter formatting rules or fallback instructions.
- Keeping small, incremental Git commits makes it easy to track what improved output quality.
