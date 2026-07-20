## Week 7 — Issue selection

**Issue link:** [https://github.com/ascherj/pathreview/issues/34]

**Issue title:** [Implement a re-ranking step that uses an LLM to score retrieved chunks before generation]

**Tier:** Tier 3

**Problem summary:**
This is an enhancement to the existing RAG system. Currently, the system retrieves chunks based on a hybrid search method but does not utilize re-ranking to improve the quality of the retrieved chunks.

A successful fix would involve implementing a re-ranking step for the chunks before the top k chunks are passed to the LLM for generation. This only affects the RAG system.

**Branch name:** fix/34-rerank-rag [https://github.com/sbhattap/pathreview/tree/fix/34-rerank-rag]

**Setup confirmation:** [ ] App runs locally at localhost:5173

**Issue Link:** https://github.com/ascherj/pathreview/issues/34

## Week 8 — Reproduction & solution planning

**Reproduction commit link:** [Adding a feature so N/A]

**Implementation summary:**
[Described in PLAN.md]

**PLAN.md link:** [https://github.com/sbhattap/pathreview/blob/fix/34-rerank-rag/PLAN.md]

**Walkthrough video (recommended):** [link to your Loom video, ≤2 min — shared for early feedback]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]