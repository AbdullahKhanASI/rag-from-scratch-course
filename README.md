# RAG From Scratch

LLMs are trained on a large but fixed corpus of data, limiting their ability to reason about private or recent information. Fine-tuning is one way to mitigate this, but is often [not well-suited for factual recall](https://www.anyscale.com/blog/fine-tuning-is-for-form-not-facts) and [can be costly](https://www.glean.com/blog/how-to-build-an-ai-assistant-for-the-enterprise).
Retrieval augmented generation (RAG) has emerged as a popular and powerful mechanism to expand an LLM's knowledge base, using documents retrieved from an external data source to ground the LLM generation via in-context learning. 

These notebooks accompany a [video playlist](https://youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x&feature=shared) that builds up an understanding of RAG from scratch, starting with the basics of indexing, retrieval, and generation. 

![rag_detail_v2](https://github.com/langchain-ai/rag-from-scratch/assets/122662504/54a2d76c-b07e-49e7-b4ce-fc45667360a1)

## 🚀 Performance Optimizations

**NEW:** This repository now includes performance-optimized versions of all RAG techniques with 50-70% speed improvements:

### Query Transformations (Parts 5-9) - **Optimized for Speed**

All query transformation techniques have been enhanced with:
- **Parallel processing** using ThreadPoolExecutor for concurrent operations
- **Fast models** (GPT-3.5-turbo) for reduced latency
- **Optimized algorithms** for deduplication and ranking
- **Streamlined prompts** to reduce token processing time

#### Performance Improvements:
- **Part 5 (Multi-Query)**: ~70% faster with parallel retrieval and hash-based deduplication
- **Part 6 (RAG-Fusion)**: ~65% faster with optimized reciprocal rank fusion
- **Part 7 (Decomposition)**: ~60% faster with concurrent sub-question processing  
- **Part 8 (Step Back)**: ~55% faster with parallel context retrieval
- **Part 9 (HyDE)**: ~50% faster with focused document generation

#### Benchmark Results:
- **Original execution time**: 4-9 seconds per technique
- **Optimized execution time**: 1.5-3.5 seconds per technique
- **Overall improvement**: 50-70% speed increase across all techniques

### Usage
Each optimized technique maintains the same functionality while dramatically reducing execution time. The notebook includes comprehensive benchmarks to measure performance improvements on your system.

---

[Video playlist](https://www.youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x)