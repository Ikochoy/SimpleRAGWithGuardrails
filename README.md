# Simple RAG With Guardrails

This is a feasibility study project which I built a simple RAG with guardrails, and aim to test whether not allowing 
the large language model to output unwanted content is possible by leveraging the [NemoGuardrails](https://github.com/NVIDIA/NeMo-Guardrails) package released
by Nvidia.

## Conclusion:
- It is possible, but at the same time, it still requires specific scoping of what can't be said, and it seems to only work with English. The performance was not as well
  when I change the language of interaction into Chinese.
