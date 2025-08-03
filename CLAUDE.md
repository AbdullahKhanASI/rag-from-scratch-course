# RAG From Scratch Course

This directory contains a comprehensive course on building Retrieval-Augmented Generation (RAG) systems from scratch. The course is organized into 5 Jupyter notebooks covering 18 parts, progressing from basic concepts to advanced techniques.

## Course Overview

This course builds towards a broader understanding of the RAG landscape, covering the entire pipeline from document indexing to generation with various optimization techniques.

## Notebooks Structure

### 📚 Notebook 1: `rag_from_scratch_1_to_4.ipynb` - Foundation & Basic RAG
**Parts 1-4**: Core RAG concepts and implementation
- **Part 1**: Overview and basic RAG pipeline using LangChain
- **Part 2**: Indexing fundamentals (document loading, tokenization, embeddings, similarity)
- **Part 3**: Retrieval mechanisms and vector search
- **Part 4**: Generation with LLMs and prompt engineering

### 🔄 Notebook 2: `rag_from_scratch_5_to_9.ipynb` - Query Transformations
**Parts 5-9**: Advanced query processing techniques
- **Part 5**: Multi-Query - generating multiple query variations
- **Part 6**: RAG-Fusion - combining queries with reciprocal rank fusion
- **Part 7**: Decomposition - breaking complex questions into sub-questions
- **Part 8**: Step Back - generating higher-level contextual questions
- **Part 9**: HyDE - hypothetical document embeddings for improved retrieval

### 🛣️ Notebook 3: `rag_from_scratch_10_and_11.ipynb` - Routing & Query Construction
**Parts 10-11**: Intelligent query routing and structuring
- **Part 10**: Logical and semantic routing with function calling
- **Part 11**: Query structuring for metadata filtering and structured search

### 🏗️ Notebook 4: `rag_from_scratch_12_to_14.ipynb` - Advanced Indexing
**Parts 12-14**: Sophisticated indexing strategies
- **Part 12**: Multi-representation indexing (summaries for retrieval, full docs for context)
- **Part 13**: RAPTOR - recursive abstractive processing with tree organization
- **Part 14**: ColBERT integration for token-level dense retrieval

### ⚡ Notebook 5: `rag_from_scratch_15_to_18.ipynb` - Advanced Retrieval & Generation
**Parts 15-18**: State-of-the-art retrieval and generation techniques
- **Part 15**: Re-ranking with RAG-fusion and Cohere Re-rank
- **Part 16**: CRAG (Corrective RAG) for error correction
- **Part 17**: Self-RAG for self-reflective retrieval
- **Part 18**: Long context considerations and impact

## Key Technologies Used

- **LangChain**: Primary framework for RAG implementation
- **OpenAI**: GPT models for generation and embeddings
- **ChromaDB**: Vector database for document storage
- **Cohere**: Re-ranking and embeddings
- **RAGatouille**: ColBERT integration
- **LangSmith**: Tracing and monitoring

## Course Progression

The course follows a logical progression:

1. **Foundation** → Basic RAG concepts and simple implementation
2. **Query Enhancement** → Techniques to improve query understanding
3. **Smart Routing** → Directing queries to appropriate data sources
4. **Advanced Indexing** → Sophisticated document organization strategies
5. **Optimization** → Cutting-edge retrieval and generation improvements

## Learning Outcomes

By completing this course, you'll understand:

- Core RAG architecture and components
- Document indexing and chunking strategies
- Vector similarity search and embeddings
- Query transformation and enhancement techniques
- Intelligent routing and classification
- Advanced retrieval methods (multi-query, fusion, decomposition)
- Re-ranking and result optimization
- Self-reflective and corrective RAG approaches
- Performance considerations for production systems

## Environment Setup

The course requires:
- Python environment with Jupyter notebook support
- API keys for OpenAI, LangSmith, and Cohere
- Installation of required packages: `langchain`, `chromadb`, `openai`, `cohere`, `ragatouille`

## Usage Notes

- Each notebook is self-contained but builds upon previous concepts
- Code examples include both basic implementations and production-ready patterns
- Extensive use of LangSmith for tracing and debugging
- Real-world examples using actual blog posts and Wikipedia data

This course provides a comprehensive foundation for building sophisticated RAG systems, from basic prototypes to production-ready applications.