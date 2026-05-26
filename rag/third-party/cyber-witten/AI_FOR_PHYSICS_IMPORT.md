# AI-for-Physics Import Note

This directory is a copied snapshot of `xingyang-yu/cyber-witten`, an
MIT-licensed retrieval-augmented question-answering system grounded in Edward
Witten's papers.

## Attribution

- Source: https://github.com/xingyang-yu/cyber-witten
- Upstream commit: `cde681d1c027f26e8a153b6ba35fe6a3311e8667`
- License: MIT
- Copyright: Copyright (c) 2026 Xingyang Yu
- Date accessed: 2026-05-26
- Local modifications: removed upstream `.git/` metadata only; source files are
  otherwise copied verbatim.

## Scope Notes

The copied repository ships code only. It does not include the generated Witten
paper list, the RAG database, or local `data/` artifacts described by upstream,
such as `data/metadata/papers.jsonl`, downloaded papers, parsed chunks, FAISS
indexes, lookup tables, or private/manual PDFs. Those artifacts must be rebuilt
locally from the pipeline scripts before the system can answer questions
against a corpus.

Upstream documents separate provenance for corpus data:

- code is MIT-licensed;
- arXiv content remains under each paper author's selected arXiv license;
- INSPIRE or journal PDF content is for local ingestion and is not redistributed.
