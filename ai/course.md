# RAG from Scratch Resources

## YouTube Videos

### [Understanding AI Models](https://www.youtube.com/watch?v=jcgaNrC4ElU&list=PLOspHqNVtKAC-FUNMq8qjYVw6_semZHw0)
 The different types of AI models, potentially covering their architectures, functionalities, and how they are used in various applications, which could include the language models used in RAG systems.

### [RAG from Scratch Tutorial](https://www.youtube.com/watch?v=sVcwVQRHIc8)
Tutorial that teaches you how to implement Retrieval Augmented Generation (RAG) from scratch. Key topics include the motivation for RAG, the RAG process, query translation, routing, query construction, document indexing, active RAG, and corrective RAG.

### [The 5 Levels Of Text Splitting For Retrieval](https://www.youtube.com/watch?v=8OJC21T2SL4)
Top strategies and granularities for splitting text data to optimize retrieval in RAG systems. It probably covers the pros and cons of various splitting methods and their impact on search relevance.

## Lessons and References

### 1. RAG from scratch: Overview
[Presentation Link](https://docs.google.com/presentation/d/1C9IaAwHoWcc4RSTqo-pCoN3h0nCgqV2JEYZUJunv_9Q/)

### 2. RAG from scratch: Indexing
[Presentation Link](https://docs.google.com/presentation/d/1MhsCqZs7wTX6P19TFnA9qRSlxH3u-1-0gWkhBiDG9lQ/)

### 3. RAG from scratch: Retrieval
[Presentation Link](https://docs.google.com/presentation/d/124I8jlBRCbb0LAUhdmDwbn4nREqxSxZU1RF_eTGXUGc)

### 4. RAG from scratch: Generation
[Presentation Link](https://docs.google.com/presentation/d/1eRJwzbdSv71e9Ou9yeqziZrz1UagwX8B1kL4TbL5_Gc)

### 5. RAG from scratch: Query Translation (Multi-Query)
[Presentation Link](https://docs.google.com/presentation/d/15pWydIszbQG3Ipur9COfTduutTZm6ULdkkyX-MNry8I)

### 6. RAG from scratch: Query Translation (RAG-Fusion)
[Presentation Link](https://docs.google.com/presentation/d/1EwykmdVSQqlh6XpGt8APOMYp4q1CZqqeclAx61pUcjI)

### 7. RAG from scratch: Query Translation (Decomposition)
[Presentation Link](https://docs.google.com/presentation/d/1O97KYrsmYEmhpQ6nkvOVAqQYMJvIaZulGFGmz4cuuVE)

**References:**

* [LEAST-TO-MOST PROMPTING ENABLES COMPLEXREASONING IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2205.10625)
* [Interleaving Retrieval with Chain-of-Thought Reasoningfor Knowledge-Intensive Multi-Step Questions](https://arxiv.org/pdf/2212.10509)

### 8. RAG from scratch: Query Translation (Step-back)
[Presentation Link](https://docs.google.com/presentation/d/1L0MRGVDxYA1eLOR0L_6Ze1l2YV8AhN1QKUtmNA-fJlU/edit?slide=id.g268cfa65240_0_0#slide=id.g268cfa65240_0_0)

**References:**

* [TAKE A STEP BACK: EVOKING REASONING VIA ABSTRACTION IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2310.06117)

### 9. RAG from scratch: Query Translation (HyDE)
[Presentation Link](https://docs.google.com/presentation/d/10MmB_QEiS4m00xdyu-92muY-8jC3CdaMpMXbXjzQXsM)

**References:**

* [Precise Zero-Shot Dense Retrieval without Relevance Labels](https://arxiv.org/pdf/2212.10496)

### 10. RAG from scratch: Routing (Logical + Semantic)
[Presentation Link](https://docs.google.com/presentation/d/1kC6jFj8C_1ZXDYcFaJ8vhJvCYEwxwsVqk2VVeKKuyx4)

### 11. RAG from scratch: Query Structuring
[Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_10_and_11.ipynb)

**References:**

* [Query Construction](https://blog.langchain.dev/query-construction/)
* [Enhancing RAG-based application accuracy by constructing and leveraging knowledge graphs](https://blog.langchain.dev/enhancing-rag-based-applications-accuracy-by-constructing-and-leveraging-knowledge-graphs/)
* [How to do "self-querying" retrieval](https://python.langchain.com/docs/how_to/self_query/)

### 12. RAG from scratch: Multi-Representation Indexing
[Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)

**References:**

* [Dense X Retrieval: What Retrieval Granularity Should We Use?](https://arxiv.org/pdf/2312.06648)
* [How to retrieve using multiple vectors per document](https://python.langchain.com/docs/how_to/multi_vector/)
* [How to use the Parent Document Retriever](https://python.langchain.com/docs/how_to/parent_document_retriever/)
* [Multi-Vector Retriever for RAG on tables, text, and images](https://blog.langchain.dev/semi-structured-multi-modal-rag/)
* [Multi-modal RAG on slide decks](https://blog.langchain.dev/multi-modal-rag-template/)

### 13. RAG From Scratch: RAPTOR
[Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)

**References:**

* [RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval](https://github.com/langchain-ai/langchain/blob/master/cookbook/RAPTOR.ipynb)
* [RAPTOR: RECURSIVE ABSTRACTIVE PROCESSINGFOR TREE-ORGANIZED RETRIEVAL](https://arxiv.org/pdf/2401.18059)
* [Building Long Context RAG with RAPTOR from Scratch](https://www.youtube.com/watch?v=jbGchdTL7d0) - This video discusses retrieval methods for long context language models (LLMs), focusing on a new method called RAPTOR. It explores whether RAG is becoming obsolete with long context LLMs and covers the cost and latency considerations. It also shows how to build RAPTOR from scratch.

### 14. RAG From Scratch: ColBERT
[Notebook Link](https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb)

**References:**

* [ColBERT: Efficient and Eective Passage Search via Contextualized Late Interaction over BERT](https://arxiv.org/pdf/2004.12832)
* [How ColBERT Helps Developers Overcome the Limits of RAG](https://hackernoon.com/how-colbert-helps-developers-overcome-the-limits-of-rag)
* [Exploring ColBERT with RAGatouille](https://til.simonwillison.net/llms/colbert-ragatouille)
* [ColBERT](https://github.com/stanford-futuredata/ColBERT)
* [RAGatouille](https://github.com/AnswerDotAI/RAGatouille)
