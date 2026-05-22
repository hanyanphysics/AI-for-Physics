# AI-for-Physics

This is my working collection of AI tools for physics research. I use it to
collect useful LLM skills, agents, harnesses, workflows, examples, and notes
that can make scientific work more effective.

> [!NOTE]
> This repo is still young and evolving. Suggestions, issues, and contributions
> are very welcome.

## Repository Map

| Path | Purpose |
| --- | --- |
| [`skills/`](skills/) | Agent skills and skill bundles for scientific and physics workflows. |
| [`agents/`](agents/) | Agent definitions, role prompts, tool-use policies, and orchestration notes. |
| [`harnesses/`](harnesses/) | Evaluation harnesses, benchmarks, test tasks, and reproducibility checks. |
| [`workflows/`](workflows/) | End-to-end research workflows assembled from skills, agents, and scripts. |
| [`examples/`](examples/) | Minimal runnable examples and demonstrations. |
| [`scripts/`](scripts/) | Utility scripts for repo maintenance, conversion, indexing, and validation. |
| [`docs/`](docs/) | Design notes, licensing guidance, curation criteria, and project documentation. |
| [`metadata/`](metadata/) | Machine-readable indexes, manifests, tags, and source metadata. |

## Current Skill Index

Only sources with clear redistribution permission are copied into this
repository. Sources without a clear license are kept as links only.

| Skill Name | Description | Source | Bundle Size | Inclusion Status |
| --- | --- | --- | --- | --- |
| `science-skills` | Agent skills for scientific research tasks across genomics, structural biology, cheminformatics, literature search, and more. | <https://github.com/google-deepmind/science-skills> | 37 copied skills | Copied to [`skills/third-party/google-deepmind-science-skills/`](skills/third-party/google-deepmind-science-skills/) under upstream license terms |
| `scientific-agent-skills` | A broad collection of ready-to-use scientific and research skills. | <https://github.com/K-Dense-AI/scientific-agent-skills> | 108 copied skills; 31 skipped after license triage | Partially copied to [`skills/third-party/k-dense-scientific-agent-skills/`](skills/third-party/k-dense-scientific-agent-skills/) |
| `arxiv-reading` | Read an arXiv paper, extract sections and equations, and build a reusable memory file. | <https://github.com/tririver/skills> | Single skill | Linked only: no license file found |
| `cited-by` | Fetch papers that cite a target arXiv paper, filter them by topic, and optionally hand selected papers off to `arxiv-reading`. | <https://github.com/tririver/skills> | Single skill | Linked only: no license file found |
| `figures4papers` | Python scripts for high-quality publication figures. | <https://github.com/ChenLiu-1996/figures4papers> | Script collection | Linked only: no license file found |

## Third-Party Material

Copied and linked external sources are documented in
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md), [`THIRD_PARTY.md`](THIRD_PARTY.md), and
[`NOTICE.md`](NOTICE.md). Third-party material remains under its original
license. Repositories without a clear license are linked only.
