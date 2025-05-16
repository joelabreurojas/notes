## YouTube Videos

### [Self-reflective RAG with LangGraph: Self-RAG and CRAG](https://www.youtube.com/watch?v=pbAd8O1Lvm4)
This video introduces Lang graph, a tool for building sophisticated Retrieval Augmented Generation (RAG) workflows using state machines. Key points covered: Basic RAG flow, Active RAG, State Machines, CAG corrective rag, LangGraph, Flow Engineering, Implementation of CAG in LangGraph, LangSmith. The video emphasizes the benefits of using graphs for building more complex and well-engineered RAG workflows.

### [Reliable, fully local RAG agents with LLaMA3.2-3b](https://www.youtube.com/watch?v=bq1Plo2RhYI)
This video provides a tutorial on building a Retrieval Augmented Generation (RAG) agent using the Llama 3.2 3 billion parameter model, which can run locally on a laptop. Here's a breakdown: Introduction to Llama 3.2, RAG Agent Overview, Tools and Setup, Building the RAG Agent, Orchestration with LangGraph, Testing the Agent, Conclusion.

## LangGraph Tutorials

### [Langgraph adaptive rag local](https://www.baihezi.com/mirrors/langgraph/tutorials/rag/langgraph_adaptive_rag_local/index.html)
Adaptive RAG is a strategy for RAG that unites query analysis with active / self-corrective RAG. This tutorial focuses on using local LLMs.

### [Self-RAG](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_self_rag/)
Self-RAG is a strategy for RAG that incorporates self-reflection / self-grading on retrieved documents and generations.

### [Adaptive RAG](https://www.analyticsvidhya.com/blog/2025/03/adaptive-rag-systems-with-langgraph/)
Adaptive RAG adjusts retrieval depth based on query complexity and dynamically selects the optimal retrieval strategy.

### [CRAG](https://www.datacamp.com/tutorial/corrective-rag-crag)
Corrective RAG (CRAG) incorporates self-assessment of retrieved documents to improve the accuracy and relevance of generated responses.

### [Agentic RAG](https://qdrant.tech/documentation/agentic-rag-langgraph/)
Agentic RAG introduces AI agents that can orchestrate multiple retrieval steps and smartly decide how to gather and use the information you need.

## Arxiv Papers

### [RARE: Retrieval-Augmented Reasoning Modeling](https://arxiv.org/pdf/2503.23513)
RARE decouples knowledge storage from reasoning optimization, externalizing domain knowledge to retrievable sources and internalizing domain-specific reasoning patterns during training.

### [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403)
Adaptive-RAG dynamically selects the most suitable strategy for retrieval-augmented LLMs based on the query complexity.

### [Corrective Retrieval Augmented Generation](https://arxiv.org/abs/2401.15884)
CRAG improves the robustness of generation by assessing the overall quality of retrieved documents and triggering different knowledge retrieval actions.

### [Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG](https://arxiv.org/abs/2501.09136)
Agentic RAG embeds autonomous AI agents into the RAG pipeline to dynamically manage retrieval strategies and adapt workflows to meet complex task requirements.

## LangGraph Examples

### [LangGraph RAG Examples](https://github.com/langchain-ai/langgraph/tree/main/examples/rag)
This GitHub repository provides examples of RAG implementations using LangGraph.
