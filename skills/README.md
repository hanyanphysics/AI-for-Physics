# Skills

This directory stores agent skills and skill bundles for AI-assisted physics
research.

## Layout

| Path | Purpose |
| --- | --- |
| [`first-party/`](first-party/) | Skills authored in this repository. |
| [`third-party/`](third-party/) | Copied or adapted skills from external repositories. |
| [`templates/`](templates/) | Templates for new skill directories and metadata. |

## Adding a Skill

Each skill should have:

- `SKILL.md` with the actual agent instructions.
- `README.md` with human-facing purpose, usage, and examples.
- `metadata.yaml` or equivalent structured metadata when useful.
- `LICENSE` or attribution notes when copied from another source.

Third-party skills must include source, license, upstream commit, and local
modification notes before they are committed.
