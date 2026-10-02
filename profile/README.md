## Headwater

**Documentation rots because nothing holds it accountable.** Headwater turns a documentation corpus into a contract a machine can check.

- **Typed documents.** Each document declares what it is (a decision, a specification, an obligation) and what it relates to, in front matter that a taxonomy defines.
- **Governed code.** A document declares which code it governs. When that code changes, the document is flagged for review, and an edit to a governed file names the documents that govern it.
- **Checked on every commit.** A Rust engine checks the corpus against its taxonomy in a pre-commit hook and in CI, with deterministic verdicts and no model in the loop.
- **Exact context for AI coding agents.** Hooks, an MCP server and editor plugins hand an agent the documents that govern its task or its file, by lookup over the graph rather than by similarity search.

Headwater governs its own corpus, and its efficacy claims are measured and reported, not assumed.

[headwater.tools](https://headwater.tools/) · [Source](https://github.com/headwater-ai/headwater) · Apache-2.0
