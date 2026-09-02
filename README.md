### Hi, I'm Osama Ansar

Senior Software Engineer with 5+ years shipping production web apps (Angular, React, Vue, Node.js) — now going deep on **TypeScript RAG systems, agentic pipelines, and LLM evaluation infrastructure**.

I read library source before I trust it. That habit has turned into two live PRs against real vector-database clients this month.

---

### 🔭 Independent AI/RAG projects

All TypeScript, all with real test suites and live demos — no framework hiding the mechanics.

- **[refract-rag](https://github.com/OsamaAnsar/refract-rag)** — hybrid BM25 + HNSW retrieval fused with Reciprocal Rank Fusion, multi-hop agentic decomposition, and a UI that visualizes every retrieval score live instead of hiding it behind a spinner. → [demo](https://refract-rag.vercel.app)
- **[rag-eval-harness](https://github.com/OsamaAnsar/rag-eval-harness)** — LLM-judge eval harness for RAG pipelines (faithfulness, relevance, context precision/recall) with a CI regression gate. → [live report](https://osamaansar.github.io/rag-eval-harness/)
- **[agentic-rag](https://github.com/OsamaAnsar/agentic-rag)** — multi-hop agentic RAG: decomposes questions, retrieves per sub-question with from-scratch BM25, checks sufficiency, synthesizes a cited answer.
- **[hnsw-vector-index](https://github.com/OsamaAnsar/hnsw-vector-index)** — HNSW approximate-nearest-neighbor search implemented from scratch, benchmarked against brute-force (recall@k: 66% → 100% as efSearch increases).
- **[doc-chat-citations](https://github.com/OsamaAnsar/doc-chat-citations)** — a docs chat assistant where every claim cites and jumps to its exact source passage, built on from-scratch BM25.
- **[generative-ui-chat](https://github.com/OsamaAnsar/generative-ui-chat)** — a chat assistant that streams back real interactive React components (charts, tables, booking cards) instead of plain text.

### 🌱 Open source

- **[weaviate/typescript-client#471](https://github.com/weaviate/typescript-client/pull/471)** — fixed `Boost` time/numeric decay silently dropped by `fromPartial`, plus a stray debug log.
- **[weaviate/typescript-client#464](https://github.com/weaviate/typescript-client/pull/464)** — fixed `data.ingest()` silently storing empty objects for the documented unwrapped input shape.
- **[qdrant/qdrant-js#171](https://github.com/qdrant/qdrant-js/pull/171)** — fixed the client silently dropping a reverse-proxy path prefix when constructed via `url`.

### 🛠️ Stack

`TypeScript` `Next.js` `Node.js` `Vercel AI SDK` `LangChain.js` `Vector Databases (Qdrant, Weaviate, Pinecone, Supabase)` `Vitest` `Angular` `React` `Vue`

### 📫 Reach me

[Portfolio](https://osama-ansar.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/osama-ansar-93271a144/) · [osama.ansar.pk@gmail.com](mailto:osama.ansar.pk@gmail.com)
