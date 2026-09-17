# LOOP

**Live Fail-Slow Diagnosis for Large-Scale LLM Training**

LOOP is a distributed, training-aware system for diagnosing fail-slow behavior during large-scale LLM training. It supports a live diagnostic loop through three operations:

- **Record:** retain bounded, rank-local execution history.
- **Ask:** query and compare evidence across ranks.
- **Change:** adjust supported collection settings while training continues.
