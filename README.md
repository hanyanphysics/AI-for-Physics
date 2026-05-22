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

| Skill Name | Description | Source |
| --- | --- | --- |
| `science-skills` | Agent skills for scientific research tasks across genomics, structural biology, cheminformatics, literature search, and more. | <https://github.com/google-deepmind/science-skills> |
| `scientific-agent-skills` | A broad collection of ready-to-use scientific and research skills. | <https://github.com/K-Dense-AI/scientific-agent-skills> |
| `arxiv-reading` | Read an arXiv paper, extract sections and equations, and build a reusable memory file. | <https://github.com/tririver/skills> |
| `cited-by` | Fetch papers that cite a target arXiv paper, filter them by topic, and optionally hand selected papers off to `arxiv-reading`. | <https://github.com/tririver/skills> |
| `figures4papers` | Python scripts for high-quality publication figures. | <https://github.com/ChenLiu-1996/figures4papers> |
