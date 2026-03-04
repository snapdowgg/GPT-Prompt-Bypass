Bypassed Prompt on GPT
===========================
<img width="895" height="1387" alt="image" src="https://github.com/user-attachments/assets/d68f9837-5dda-4fb7-943c-0e16983dd7b3" />


Overview
--------
This repository focuses on AI prompt behavior analysis and safety testing.

The purpose of this project is to study how different large language models
respond to edge-case prompts, how safety filters react, and how patch updates
change model behavior over time.

This is about understanding AI systems — not abusing them.


What This Project Covers
------------------------
- Prompt stress testing
- Model response comparison
- Safety filter behavior analysis
- Patch impact observation
- Structured logging for research


Tested Models
-------------
- DeepSeek
- Grok
- Gemini

Note:
Model behavior may change over time due to internal updates and safety patches.


Why This Matters
----------------
AI systems are constantly evolving.

Understanding how models react to difficult or ambiguous prompts helps:

- Improve defensive AI design
- Strengthen safety mechanisms
- Reduce false positives and false negatives
- Document behavioral changes after updates


Limitations
-----------
- Some providers may rate-limit heavy testing
- Repeated automated requests can trigger temporary restrictions
- Model outputs may vary across versions


Usage Concept
-------------
1. Send structured prompts to selected AI model.
2. Capture full responses.
3. Log outputs for comparison.
4. Document filter triggers or behavior changes.
5. Analyze differences across updates.


Important Notice
----------------
This repository is intended for educational and authorized research purposes only.

Do NOT use this project to:
- Bypass AI safeguards
- Abuse AI APIs
- Automate harmful content generation
- Exploit model weaknesses

AI research should improve safety, not weaken it.
