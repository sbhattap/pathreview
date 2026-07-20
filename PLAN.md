## Solution plan

**Issue:** [issue title and link]

### Understand
This is an enhancement to the existing RAG system. Currently, the system retrieves chunks based on a hybrid search method but does not utilize re-ranking to improve the quality of the retrieved chunks.

The goal is to add a new re-ranker file that will generate a score for each chunk based on the query and the chunk content. The top k chunks will then be passed to the LLM for generation.

### Map
- rag/retriever/ (new reranker.py)
- rag/retriever/hybrid.py

### Plan
What are the steps to fix this issue?
- Add a new reranker.py file in the rag/retriever/ directory.
- Implement a function that takes the query and the retrieved chunks as input and returns a score for each chunk.
- Modify the hybrid.py file to call the reranker function after retrieving the chunks and before passing them to the LLM for generation.

### Inputs & outputs
What does your fix take as input? What should it produce or change?

### Risks & unknowns
What could go wrong? What are you still unsure about?

### Edge cases
What inputs or states should your fix handle gracefully?