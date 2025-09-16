# 😎 Awesome Retrieval-Augmented Generation (RAG)

A curated list of the most **powerful, innovative, and production-ready Retrieval-Augmented Generation (RAG)** projects.

RAG is a technique where large language models (LLMs) fetch external context (documents, knowledge bases, databases, or APIs) to enrich their responses. This approach enables LLMs to provide **factual, up-to-date, and domain-specific answers** that go beyond their pretraining data.

This list focuses on **real implementations, complete applications, and frameworks** that showcase the true potential of RAG.

---

## 📖 Contents

* [ℹ️ What is RAG?](#ℹ️-what-is-rag)
* [🚀 Full Applications](#-full-applications)
* [🧰 Frameworks](#-frameworks)
* [🔬 Innovative Approaches](#-innovative-approaches)
* [📊 Vector Databases](#-vector-databases)
* [🧪 Demos & Starter Projects](#-demos--starter-projects)
* [🤝 Contributing](#-contributing)

---

## ℹ️ What is RAG?

In a typical RAG pipeline:

1. **Chunk & Embed:** Documents are split into chunks and converted into embeddings.
2. **Store:** Embeddings are stored in a vector database.
3. **Query:** A user query is embedded and compared to stored vectors.
4. **Retrieve:** The most relevant chunks are retrieved.
5. **Augment Prompt:** Retrieved text is added to the LLM’s context.
6. **Generate:** The LLM produces a grounded, context-aware response.

This enables LLMs to **use external knowledge** dynamically, improving **accuracy, trustworthiness, and adaptability**.

---

## 🚀 Full Applications

Here are **complete end-to-end RAG apps** you can run today.

### [RAGify](https://github.com/OthmaneBlial/RAGify) ⭐ *Highlighted Project*

A modern, modular RAG chat application built with **FastAPI** and a **Vite-powered frontend**.
RAGify makes it easy to **create knowledge bases, upload documents, and build chatbots** connected to **100+ models via OpenRouter**.

**Features:**

* Knowledge base management (PDF, DOCX, TXT)
* Semantic search with **pgvector**
* Streaming chat with real-time responses
* Redis caching & async background tasks
* RESTful API + auto-generated docs
* Responsive web frontend (Vite)
* Secure architecture with rate limiting

**Stack:** FastAPI · PostgreSQL · pgvector · Redis · OpenRouter · Vite
**Maturity:** Emerging but production-oriented
**Why it matters:** Unlike many RAG demos, RAGify is **full-stack and modular**, showing how to build scalable RAG systems.

---

### [PrivateGPT](https://github.com/imartinez/privateGPT)

Run an LLM + RAG pipeline fully **offline and private**. Query your documents with no data leaving your machine.

**Stack:** LangChain · llama.cpp · Chroma
**Maturity:** Production-ready
**Use case:** Privacy-first enterprises and individuals.

---

### [Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)

Enterprise-ready **knowledge assistant**. Connects to **Google Drive, Slack, GitHub, Confluence**, and more, and answers questions using RAG with access controls.

**Stack:** Python · Elasticsearch · Postgres
**Maturity:** Production-ready
**Use case:** Company-wide search & Q\&A.

---

### [Verba](https://github.com/weaviate/Verba)

An out-of-the-box **chatbot over your data** by Weaviate. Works with local or API LLMs and stores embeddings in Weaviate DB.

**Stack:** Weaviate · LangChain
**Maturity:** Plug-and-play demo
**Use case:** Easy local RAG chatbot setup.

---

### [Chat-with-your-Docs](https://github.com/mayooear/ai-pdf-chatbot-langchain)

Upload PDFs and **chat with them**. A popular starter RAG app showing document ingestion → embeddings → chat.

**Stack:** LangChain · OpenAI · Chroma
**Maturity:** Demo, widely forked
**Use case:** Academic papers, manuals, contracts.

---

## 🧰 Frameworks

Frameworks that **accelerate building RAG systems**:

* [LangChain](https://github.com/langchain-ai/langchain) – Modular framework for chaining LLM components, strong RAG support.
* [LlamaIndex](https://github.com/jerryjliu/llama_index) – Connect data to LLMs via flexible indices & query engines.
* [Haystack](https://github.com/deepset-ai/haystack) – Production-ready pipelines for RAG and QA.
* [Cognita](https://github.com/truefoundry/cognita) – Modular, production-oriented RAG framework.
* [Flowise](https://github.com/FlowiseAI/Flowise) – No-code drag & drop builder for RAG pipelines.

---

## 🔬 Innovative Approaches

Advanced research & experimental projects pushing RAG forward:

* [GraphRAG](https://github.com/microsoft/graphrag) – Retrieval with **knowledge graphs** for reasoning.
* [RAPTOR](https://github.com/parthsarthi03/raptor) – Tree-structured summarization & retrieval.
* [HippoRAG](https://github.com/allenai/hipporag) – **Long-term memory** inspired by hippocampus.
* [Self-RAG](https://github.com/facebookresearch/self-rag) – Self-reflective RAG that critiques its own outputs.
* [MemoRAG](https://github.com/Tongji-KGLLM/MemoRAG) – Global memory system for persistent RAG knowledge.

---

## 📊 Vector Databases

Core building blocks for efficient retrieval:

* [Weaviate](https://github.com/weaviate/weaviate) – Cloud-native vector DB.
* [Milvus](https://github.com/milvus-io/milvus) – Open-source vector DB for AI apps.
* [Chroma](https://github.com/chroma-core/chroma) – Lightweight AI-native vector store.
* [Pgvector](https://github.com/pgvector/pgvector) – PostgreSQL extension for vectors.
* [Qdrant](https://github.com/qdrant/qdrant) – High-performance vector database.

---

## 🧪 Demos & Starter Projects

* **[OpenAI ChatGPT Retrieval Plugin](https://github.com/openai/chatgpt-retrieval-plugin)** – Template to add retrieval to ChatGPT.

---

## 🤝 Contributing

This list is evolving! Contributions are welcome:

* Add new production-ready RAG apps
* Suggest research projects with clear code & docs
* Submit PRs for corrections or updates

🙌 Together we can make this the **definitive Awesome RAG list**.


