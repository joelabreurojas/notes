# Comprehensive RAG Learning Path and Resources

This document is a curated collection of resources for learning Retrieval-Augmented Generation (RAG), from foundational concepts to advanced, framework-based implementations.

## 1. Foundational Concepts & Tutorials

This section covers the core mechanics of building a RAG pipeline from the ground up, without relying on high-level frameworks like LangChain or LlamaIndex.

- **Video:** [RAG from Scratch Tutorial](https://www.youtube.com/watch?v=sVcwVQRHIc8) - Covers the motivation for RAG, the RAG process, query translation, routing, query construction, document indexing, active RAG, and corrective RAG.
- **Video:** [RAG from Scratch: Conversational RAG Without LangChain or LlamaIndex](https://www.youtube.com/watch?v=8sSHg1034r0) - Expands on the "RAG from scratch" concept by focusing on building a conversational RAG system.
- **Article:** [Building RAG Applications Without LangChain or LlamaIndex](https://blog.futuresmart.ai/building-rag-applications-without-langchain-or-llamaindex) - Discusses the feasibility and approaches for building RAG applications using fundamental libraries.

## 2. RAG from Scratch: A Step-by-Step Course

This course provides a structured approach to understanding each component of the RAG pipeline.

- **Video:** [Understanding AI Models](https://www.youtube.com/watch?v=jcgaNrC4ElU&list=PLOspHqNVtKAC-FUNMq8qjYVw6_semZHw0) - Covers different types of AI models, which is foundational knowledge for RAG.
- **Video:** [The 5 Levels Of Text Splitting For Retrieval](https://www.youtube.com/watch?v=8OJC21T2SL4) - Explores strategies for splitting text data to optimize retrieval.

### Course Lessons:

1.  **Overview**
    - [Presentation Link](https://docs.google.com/presentation/d/1C9IaAwHoWcc4RSTqo-pCoN3h0nCgqV2JEYZUJunv_9Q/)
2.  **Indexing**
    - [Presentation Link](https://docs.google.com/presentation/d/1MhsCqZs7wTX6P19TFnA9qRSlxH3u-1-0gWkhBiDG9lQ/)
3.  **Retrieval**
    - [Presentation Link](https://docs.google.com/presentation/d/124I8jlBRCbb0LAUhdmDwbn4nREqxSxZU1RF_eTGXUGc)
4.  **Generation**
    - [Presentation Link](https://docs.google.com/presentation/d/1eRJwzbdSv71e9Ou9yeqziZrz1UagwX8B1kL4TbL5_Gc)
5.  **Query Translation (Multi-Query)**
    - [Presentation Link](https://docs.google.com/presentation/d/15pWydIszbQG3Ipur9COfTduutTZm6ULdkkyX-MNry8I)
6.  **Query Translation (RAG-Fusion)**
    - [Presentation Link](https://docs.google.com/presentation/d/1EwykmdVSQqlh6XpGt8APOMYp4q1CZqqeclAx61pUcjI)
7.  **Query Translation (Decomposition)**
    - [Presentation Link](https://docs.google.com/presentation/d/1O97KYrsmYEmhpQ6nkvOVAqQYMJvIaZulGFGmz4cuuVE)
    - **Reference Paper:** [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/pdf/2205.10625)
8.  **Query Translation (Step-back)**
    - [Presentation Link](https://docs.google.com/presentation/d/1L0MRGVDxYA1eLOR0L_6Ze1l2YV8AhN1QKUtmNA-fJlU)
    - **Reference Paper:** [Take a Step Back: Evoking Reasoning via Abstraction in Large Language Models](https://arxiv.org/pdf/2310.06117)
9.  **Query Translation (HyDE)**
    - [Presentation Link](https://docs.google.com/presentation/d/10MmB_QEiS4m00xdyu-92muY-8jC3CdaMpMXbXjzQXsM)
    - **Reference Paper:** [Precise Zero-Shot Dense Retrieval without Relevance Labels](https://arxiv.org/pdf/2212.10496)
10. **Routing (Logical + Semantic)**
    - [Presentation Link](https://docs.google.com/presentation/d/1kC6jFj8C_1ZXDYcFaJ8vhJvCYEwxwsVqk2VVeKKuyx4)
11. **Query Structuring**
    - [Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_10_and_11.ipynb)
12. **Multi-Representation Indexing**
    - [Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)
13. **RAPTOR**
    - [Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)
    - **Video:** [Building Long Context RAG with RAPTOR from Scratch](https://www.youtube.com/watch?v=jbGchdTL7d0)
14. **ColBERT**
    - [Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)
    - **Reference Paper:** [ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT](https://arxiv.org/pdf/2004.12832)

## 3. LangGraph & Framework-Based Implementations

This section contains resources for building advanced RAG systems using frameworks like LangGraph.

- **Video:** [Self-reflective RAG with LangGraph: Self-RAG and CRAG](https://www.youtube.com/watch?v=pbAd8O1Lvm4) - Introduces LangGraph for building sophisticated RAG workflows using state machines.
- **Video:** [Reliable, fully local RAG agents with LLaMA3.2-3b](https://www.youtube.com/watch?v=bq1Plo2RhYI) - A tutorial on building a RAG agent using Llama 3.2 locally with LangGraph.

### Key LangGraph Tutorials:

- **Adaptive RAG (Local):** [Link](https://www.baihezi.com/mirrors/langgraph/tutorials/rag/langgraph_adaptive_rag_local/index.html)
- **Self-RAG:** [Link](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_self_rag/)
- **Corrective RAG (CRAG):** [Link](https://www.datacamp.com/tutorial/corrective-rag-crag)
- **Agentic RAG:** [Link](https://qdrant.tech/documentation/agentic-rag-langgraph/)
- **GitHub Examples:** [LangGraph RAG Examples](https://github.com/langchain-ai/langgraph/tree/main/examples/rag)gg
