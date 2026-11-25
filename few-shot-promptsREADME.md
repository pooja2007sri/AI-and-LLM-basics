# Create Few-Shot Prompts

## What I Did
I tested few-shot prompting by giving input/output examples inside the prompt and comparing it against a zero-shot prompt in a free AI tool (ChatGPT / Gemini) to get a clean, consistent response format.

---

## Prompt 1: Zero-Shot vs. Few-Shot Prompting
- **Zero-Shot Prompt:** Classify this feedback and pull out the main issue: "The lab portal keeps timing out when I try to upload my assignment."
- **Output:** The feedback is negative, and the main issue is that the lab portal is timing out during assignment uploads.

- **Few-Shot Prompt:**
  ```text
  Classify the sentiment and extract the core issue from the student feedback using the exact format shown in the examples.

  Example 1:
  Input: "The lecture notes were super clear and easy to revise."
  Output: Sentiment: Positive | Issue: None

  Example 2:
  Input: "The video player freezes whenever I switch to full screen."
  Output: Sentiment: Negative | Issue: Video playback freeze in full screen

  Input: "The lab portal keeps timing out when I try to upload my assignment."
  Output:Negative | Issue: Lab portal timeout during assignment upload
