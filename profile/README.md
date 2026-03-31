<div align="center">
  <img src="https://github.com/arcnem-ai/.github/raw/main/profile/arcnem-logo.svg" alt="Arcnem AI" width="160" />
  <h3>AI products and consulting, built from Tokyo.</h3>
  <p>
    <a href="https://arcnem.ai">Website</a>
  </p>
</div>

---

We build AI products and help businesses cut through the hype to ship software that actually matters. Our work spans products, consulting, and community — all grounded in the belief that AI should help people think better, not think less.

## Open Source

Alongside our product and consulting work, we publish open-source tools that reflect how we like to build: local-first, inspectable, and grounded in real workflows.

- **[arcnem-vision](https://github.com/arcnem-ai/arcnem-vision)** — Turn images into searchable, meaningful data. A platform combining mobile camera capture with AI agent orchestration via LangGraph and MCP. Flutter client, Bun/Hono API, React dashboard, and Go agent services.
- **[autoarc](https://github.com/arcnem-ai/autoarc)** — Benchmark-guided code improvement for local repositories. An open-source Gleam service that runs measured code experiments in isolated worktrees, asks models to propose changes, and records the results in SQLite.
- **[picvec](https://github.com/arcnem-ai/picvec)** — Local-first image similarity search. A Go CLI that runs vision models (CLIP, SigLIP2) locally via ONNX Runtime and stores embeddings in a local libsql database.
- **[texvec](https://github.com/arcnem-ai/texvec)** — Local-first text similarity search. A Go CLI that summarizes and embeds documents locally with ONNX models, stores vectors in a local libsql database, and ranks matches with cosine distance.
- **[omnivec](https://github.com/arcnem-ai/omnivec)** — API-first asset librarian for local-first document and image similarity analysis. A Python service that combines `texvec` and `picvec` to analyze uploaded corpora and return structured JSON plus a markdown report.
