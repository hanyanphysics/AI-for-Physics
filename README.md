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

> [!NOTE]
> Only sources with clear redistribution permission are copied into this
> repository. Sources without a clear license are kept as links only.

| Repository | Description | Note |
| --- | --- | --- |
| [google-deepmind/science-skills](https://github.com/google-deepmind/science-skills) | Agent skills for scientific research tasks across genomics, structural biology, cheminformatics, literature search, and more. 37 skills copied. | Copied to [`skills/third-party/google-deepmind-science-skills/`](skills/third-party/google-deepmind-science-skills/) under upstream license terms. |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | A broad collection of ready-to-use scientific and research skills. 108 skills copied; 31 skipped after license triage. | Partially copied to [`skills/third-party/k-dense-scientific-agent-skills/`](skills/third-party/k-dense-scientific-agent-skills/). |
| [InternScience/scp](https://github.com/InternScience/scp) | Scientific skill collection; 13 physics, math, materials, experimental-analysis, and general science skills copied. | Partially copied to [`skills/third-party/internscience-scp/`](skills/third-party/internscience-scp/). Biomedical, drug-discovery, clinical, genomics, virology, and structural-biology skills were skipped. |
| [yorkeccak/scientific-skills](https://github.com/yorkeccak/scientific-skills) | Natural-language scientific literature search skills. 2 broad search skills copied: `arxiv-search` and `literature-search`. | Partially copied to [`skills/third-party/yorkeccak-scientific-skills/`](skills/third-party/yorkeccak-scientific-skills/). Biomedical, drug, clinical, and chemistry-specific search skills were skipped. |
| [Weizhena/Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) | Structured deep-research workflow collection. 5 English Codex research workflow skills copied. | Partially copied to [`skills/third-party/weizhena-deep-research-skills/`](skills/third-party/weizhena-deep-research-skills/). Chinese duplicates and non-Codex variants were skipped. |
| [huggingface/skills](https://github.com/huggingface/skills) | Hugging Face model, dataset, paper, evaluation, and training workflows. 5 ML research skills copied. | Partially copied to [`skills/third-party/huggingface-skills/`](skills/third-party/huggingface-skills/). Broad Hub administration, app deployment, and demo skills were skipped. |
| [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) | Curated index of scientific skills and related repositories. | Linked only: used as a discovery source; no skill files copied. |
| [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | Earlier Claude-oriented K-Dense scientific skill collection with 128+ skills. | Linked only: overlaps with the newer `scientific-agent-skills` source already triaged and copied. |
| [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) | Scientific writing and research workflow tool with 19+ writing-related skills. | Linked only for now: useful, but overlaps with existing writing, citation, and review skills already imported from K-Dense. |
| [HughYau/AcademicForge](https://github.com/HughYau/AcademicForge) | Academic writing and research workflow collection. | Linked only: relevant skills overlap with existing imports, and included submodules can carry their own licenses. |
| [tririver/skills](https://github.com/tririver/skills) | Includes `arxiv-reading`, a single skill for reading arXiv papers and building reusable notes. | Linked only: no license file found. |
| [tririver/skills](https://github.com/tririver/skills) | Includes `cited-by`, a single skill for finding and filtering papers that cite a target arXiv paper. | Linked only: no license file found. |
| [ChenLiu-1996/figures4papers](https://github.com/ChenLiu-1996/figures4papers) | Script collection for making high-quality scientific figures. | Linked only: no license file found. |

## Third-Party Material

Copied and linked external sources are documented in
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md), [`THIRD_PARTY.md`](THIRD_PARTY.md), and
[`NOTICE.md`](NOTICE.md). Third-party material remains under its original
license. Repositories without a clear license are linked only.
