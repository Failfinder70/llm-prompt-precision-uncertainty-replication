# Prompt Precision and Uncertainty in LLMs: Replication Study (Project 2.1)

## Overview

This project is a direct replication of Project 2, re-examining whether 
increasing factual precision in prompts predictably triggers uncertainty 
responses in large language models. The same prompt ladder methodology 
was applied to a partially overlapping set of models to test the 
consistency of findings across different model configurations.

## Models Tested

- Gemini
- Grok
- ChatGPT
- DeepSeek R1:14b (offline)
- Llama 3.2-vision:11b (offline)

## Primary Finding

The central thesis was again not confirmed. Increasing prompt precision 
did not predictably trigger uncertainty responses across models.

## Secondary Finding

The secondary finding from Project 2 replicated cleanly. Response quality 
increases with prompt precision. Retrieval-capable models surfaced 
Operation Nordwind at the same prompt precision stage as in Project 2. 
Non-retrieval models again failed to surface it at any precision level. 
The consistency of this pattern across both projects strengthens the 
secondary finding despite the non-confirmation of the primary thesis.

## Repository Contents

- Full research report
- Raw model response annexes by platform

## Related
Substack: https://normaldood.substack.com/p/chasing-uncertainty-part-2
- [Project 2 (Original Study)](https://github.com/Failfinder70/llm-prompt-precision-uncertainty)
- Substack post — *link here*
