# Agentic AI Tutorial — LangGraph & LangChain

A hands-on tutorial on building agentic AI applications from scratch with **LangGraph** and **LangChain**: agents that think, use tools, remember, and collaborate to solve complex tasks on their own.

![Status](https://img.shields.io/badge/status-in%20progress-orange)

---

## What You'll Learn

- **Agentic AI fundamentals:** how agents differ from traditional AI models, and their key parts: memory, tools, and decision-making.
- **LangChain:** the building blocks for LLM applications, from loading data to retrieval.
- **LangGraph:** designing agent workflows as graphs, with state, transitions, and event-driven behaviour.
- **Single agents:** agents with memory and tool use.
- **Multi-agent systems:** agents collaborating through message passing and shared goals.
- **Deployment:** taking agentic applications to production and optimising them.

**Projects you'll build:** an autonomous research assistant, a task automation bot, and RAG (retrieval-augmented generation) agents.

## Prerequisites

- Basic Python: variables, functions, and classes.
- A basic understanding of APIs and REST services.
- Familiarity with LLM concepts, such as OpenAI or Hugging Face models.

No prior experience with LangGraph is needed.

---

## Tutorial Outline

| Part | Topic | Status |
|------|-------|--------|
| 1 | LangChain foundations (RAG building blocks) | Available |
| 2 | Agentic AI fundamentals | Coming soon |
| 3 | LangGraph: state, nodes, edges, memory | Coming soon |
| 4 | Single agents with tools | Coming soon |
| 5 | Multi-agent collaboration | Coming soon |
| 6 | End-to-end projects and deployment | Coming soon |

---

## Part 1 — LangChain Foundations

The building blocks of RAG and agent applications: getting data in, turning it into vectors, and retrieving it.

### Data ingestion

Load text, PDF, web, XML, and Wikipedia content, then split it into chunks a model can work with. You'll compare character, recursive, HTML-header, and JSON splitting.

### Embeddings

Turn text into vectors with hosted models (OpenAI) and local open-source models (Hugging Face).

### Vector databases

Store and search embeddings with Chroma, FAISS, and Pinecone, and learn the trade-offs between local and managed stores.

### Better retrieval

Combine keyword search (BM25) with vector search using an ensemble retriever, rerank results with a cross-encoder, and write a custom retriever.

### Key takeaways

- How a document is chunked strongly affects retrieval quality.
- Hybrid search plus reranking usually beats plain vector similarity.
- Loading a saved FAISS index unpickles it, so only load indexes you created yourself.

---

## Up Next

Part 2 covers agentic AI fundamentals, followed by LangGraph.

---

*An educational tutorial. Not affiliated with LangChain or any third-party service mentioned.*
