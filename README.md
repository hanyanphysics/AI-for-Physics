# AI-for-Physics

This is my working collection of AI tools for physics research. I use it to
collect useful LLM skills, RAG systems, agents, harnesses, workflows, examples,
and notes that can make scientific work more effective.

> [!NOTE]
> This repo is still young and evolving. Suggestions, issues, and contributions
> are very welcome and highly appreciated!

## Repository Map

| Path | Purpose |
| --- | --- |
| [`skills/`](skills/) | Agent skills and skill bundles for scientific and physics workflows. |
| [`rag/`](rag/) | Retrieval-augmented generation systems and reference implementations. |
| [`agents/`](agents/) | Agent definitions, role prompts, tool-use policies, and orchestration notes. |
| [`harnesses/`](harnesses/) | Evaluation harnesses, benchmarks, test tasks, and reproducibility checks. |
| [`workflows/`](workflows/) | End-to-end research workflows assembled from skills, agents, and scripts. |
| [`examples/`](examples/) | Minimal runnable examples and demonstrations. |
| [`scripts/`](scripts/) | Utility scripts for repo maintenance, conversion, indexing, and validation. |
| [`docs/`](docs/) | Design notes, licensing guidance, curation criteria, and project documentation. |
| [`metadata/`](metadata/) | Machine-readable indexes, manifests, tags, and source metadata. |

## Using The Skills

Most copied skills live under [`skills/third-party/`](skills/third-party/).
Each skill is usually a folder containing a `SKILL.md` file, and sometimes
supporting scripts, examples, or reference notes.

To use a copied skill with an agent that supports local skills:

1. Find the skill folder you want to use.
2. Read its `SKILL.md` and any nearby `README.md` or `COPIED_SKILLS.md`.
3. Copy the whole skill folder into your agent's local skills directory, keeping
   any `scripts/`, `references/`, or example files with it.
4. Restart or reload your agent if it does not discover new skills
   automatically.
5. Ask the agent to use the skill by name, or describe the task naturally.

For example, a Codex user can copy selected folders into `~/.codex/skills/`;
a Claude Code user can copy selected folders into `~/.claude/skills/`. Some
upstream bundles also document their own installer commands, so check the local
bundle README before installing a larger collection.

Linked-only entries are different: they are pointers to useful external
repositories, but this repo does not copy their files. To use a linked-only
skill, visit the upstream repository and follow that project's own license and
installation instructions.

## Current Skill Index

> [!NOTE]
> Only sources with clear redistribution permission are copied into this
> repository. Sources without a clear license are kept as links only.

| Repository | Description |
| --- | --- |
| [google-deepmind/science-skills](https://github.com/google-deepmind/science-skills) | Agent skills for scientific research tasks across genomics, structural biology, cheminformatics, literature search, and more; 37-skill bundle.<br>37 skills copied locally to [`skills/third-party/google-deepmind-science-skills/`](skills/third-party/google-deepmind-science-skills/) under upstream license terms. |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | Broad collection of ready-to-use scientific and research skills; 139 skills reviewed.<br>108 skills copied locally to [`skills/third-party/k-dense-scientific-agent-skills/`](skills/third-party/k-dense-scientific-agent-skills/); 31 skipped after license triage. |
| [InternScience/scp](https://github.com/InternScience/scp) | Scientific skill collection spanning many science domains; 13 physics, math, materials, experimental-analysis, and general science skills selected.<br>13 skills copied locally to [`skills/third-party/internscience-scp/`](skills/third-party/internscience-scp/); biomedical, drug-discovery, clinical, genomics, virology, and structural-biology skills skipped. |
| [yorkeccak/scientific-skills](https://github.com/yorkeccak/scientific-skills) | Natural-language scientific literature search skills across several sources; broad search skills include `arxiv-search` and `literature-search`.<br>2 skills copied locally to [`skills/third-party/yorkeccak-scientific-skills/`](skills/third-party/yorkeccak-scientific-skills/); biomedical, drug, clinical, and chemistry-specific search skills skipped. |
| [Weizhena/Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) | Structured deep-research workflow collection for Claude Code, OpenCode, and Codex; 5 English Codex workflow skills selected.<br>5 skills copied locally to [`skills/third-party/weizhena-deep-research-skills/`](skills/third-party/weizhena-deep-research-skills/); Chinese duplicates and non-Codex variants skipped. |
| [huggingface/skills](https://github.com/huggingface/skills) | Hugging Face model, dataset, paper, evaluation, and training workflows; 5 ML research skills selected.<br>5 skills copied locally to [`skills/third-party/huggingface-skills/`](skills/third-party/huggingface-skills/); broad Hub administration, app deployment, and demo skills skipped. |
| [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) | Curated index of scientific skills and related repositories.<br>Linked only as a discovery source; no skill files copied locally. |
| [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | Earlier Claude-oriented K-Dense scientific skill collection with 128+ skills.<br>Linked only because it overlaps with the newer `scientific-agent-skills` source already triaged and copied. |
| [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) | Scientific writing and research workflow tool with 19+ writing-related skills.<br>Linked only for now because it overlaps with existing writing, citation, and review skills already imported from K-Dense. |
| [HughYau/AcademicForge](https://github.com/HughYau/AcademicForge) | Academic writing and research workflow collection.<br>Linked only because relevant skills overlap with existing imports, and included submodules can carry their own licenses. |
| [tririver/skills](https://github.com/tririver/skills) | Includes `arxiv-reading` for reading arXiv papers into reusable notes and `cited-by` for finding papers that cite a target arXiv paper.<br>Linked only: no license file found, so no skill files copied locally. |
| [ChenLiu-1996/figures4papers](https://github.com/ChenLiu-1996/figures4papers) | Script collection for making high-quality scientific figures.<br>Linked only: no license file found, so no files copied locally. |

## Current RAG Index

| Repository | Description |
| --- | --- |
| [xingyang-yu/cyber-witten](https://github.com/xingyang-yu/cyber-witten) | Retrieval-augmented question-answering system grounded in Edward Witten's papers, useful as a physics-specific RAG reference implementation.<br>Code copied locally to [`rag/third-party/cyber-witten/`](rag/third-party/cyber-witten/) under MIT license terms. The generated corpus is not included: upstream ships code only, not the Witten paper list, paper metadata, chunks, FAISS index, downloaded sources, or PDFs. These artifacts must be rebuilt locally because the underlying paper content has separate copyright and redistribution constraints. |

## Third-Party Material

Copied and linked external sources are documented in
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md), [`THIRD_PARTY.md`](THIRD_PARTY.md), and
[`NOTICE.md`](NOTICE.md). Third-party material remains under its original
license. Repositories without a clear license are linked only.
