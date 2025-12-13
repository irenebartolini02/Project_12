# Baselines Causal Reasoning Evaluation
## Gemma 2 9B Instruct

**SYSTEM_PROMPT**: "You are solving SemEval 2026 Task 12: Abductive Event Reasoning. 
    Given an event, context documents, and four options (A–D),
    choose which option(s) are the most plausible direct cause of the event. 
    Respond ONLY with the letters of all correct options, 
    separated by commas (e.g. 'A', 'A,B', or 'D'). 
    Do not output any explanations.

**Context building strategy**: Concatenating "--- Document {i} ---\nTitle: {doc.get('title')}\nText: {clean_text}\n\n until a maximum number of characters (6000)

**Total Questions: 400**

**Results**

|         | Number | Percentage |
|---------|--------|------------|
| Correct | 180    | 45.0%      |
| Partial | 90     | 22.5%      |
| Wrong   | 130    | 32.5%      |
| Score   | 225.0  | 56.25%     |

## ⁠Llama 3.1 8B Instruct (Meta)

## ⁠Solar 10.7B Instruct v1.0

## ⁠Hermes 3 - Llama 3.1 8B

## ⁠Qwen 2.5 7B Instruct
