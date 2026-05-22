# Skills

This is the main home for reusable AI-agent skills. A skill is a compact set of
instructions, scripts, references, and examples that helps an agent do a
specific research task more reliably.

## What You Will Find

| Path | Purpose |
| --- | --- |
| [`first-party/`](first-party/) | Original skills written for this project. |
| [`third-party/`](third-party/) | External skills included with attribution and license notes. |
| [`templates/`](templates/) | Starting points for creating new skills in a consistent format. |

## How To Use This Directory

Browse by topic, read the skill's `README.md` first, then inspect its
`SKILL.md` for the instructions used by compatible agents. When a skill includes
scripts, examples, or reference files, that skill's README explains how they fit
together.

## Typical Skill Layout

```text
skill-name/
  README.md
  SKILL.md
  metadata.yaml
  scripts/
  references/
  examples/
```

The `README.md` explains the skill for people. The `SKILL.md` provides the
structured instructions consumed by compatible AI agents.
