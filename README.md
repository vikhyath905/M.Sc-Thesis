# M.Sc-Thesis
MSc thesis research: evaluating LLM response consistency in hydrometeorological disaster advisory contexts using semantic and lexical metrics across temperature settings.
# LLM Response Consistency in Hydrometeorological Disaster Response

**MSc Computer Science Thesis — SRH Leipzig, September 2026**  
**Author:** Vikhyath S

---

## Overview

This repository contains all research artefacts for the thesis:

> *LLM Response Consistency in Hydrometeorological Disaster Response: Measuring Semantic and Lexical Stability of Large Language Models in Disaster Advisory Contexts*

The study evaluates whether large language models produce stable, reproducible responses across repeated prompts in disaster advisory settings, using a custom eight-metric evaluation framework.

---

## Research Questions

- **RQ1:** Do lexical and semantic metrics yield different consistency estimates for LLM disaster advisory responses?
- **RQ2:** Does paraphrase variation in prompts affect response consistency across models?
- **RQ3:** Does temperature setting influence response consistency, and does this vary by model or question type?

---

## Models Evaluated

| Model | Provider | Temperature Settings |
|---|---|---|
| Llama 3.1-8B | Meta / Groq | 0.3, 0.7, 1.0 |
| Mistral 7B | Mistral / Groq | 0.3, 0.7, 1.0 |
| Llama 4 Scout | Meta / Groq | 0.7 only |

---
