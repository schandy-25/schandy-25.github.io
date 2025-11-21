---
title: "Metacognition in LLMs — Reporting & Control Axis Probing"
description: "Replication + multi-dataset extension of neurofeedback-driven metacognition in LLMs."
---

## Metacognition in LLMs — Reporting & Control Axis Probing

Replicated and extended **“Neurofeedback-Driven Metacognition in Language Models”** using Qwen2.5 models, evaluating metacognitive reporting and explicit/implicit control across **5 binary datasets**.

### Key Contributions
- Extracted hidden states and trained logistic-probe semantic axes at single layers.
- Implemented prompt-position neurofeedback labels for reporting evaluation.
- Measured explicit vs implicit control using Z-scored projections + Cohen’s d.
- Found strong generalization across datasets except **BoolQ**, consistent with a weak semantic axis.

**GitHub:** https://github.com/schandy-25/metacognition_LLM
