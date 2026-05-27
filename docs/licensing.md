# Licensing And Attribution

This repository may contain both first-party material and third-party material.
Respecting upstream copyright is part of the curation process.

## First-Party License

Unless otherwise noted, original AI-for-Physics material is licensed under the
Apache License 2.0. See [`../LICENSE`](../LICENSE).

This top-level license does not relicense copied third-party material. Files
under `skills/third-party/`, `rag/third-party/`, and any other clearly marked
third-party location remain under their upstream licenses and notices.

## Rules For Third-Party Skills

Before copying a skill into this repository:

1. Confirm the upstream license allows redistribution.
2. Copy required license files or notices.
3. Record the upstream URL and commit hash in `ATTRIBUTIONS.md`.
4. Preserve copyright headers.
5. Mark any local modifications.

If a repository has no license, do not copy its files. Link to it instead or
ask the author for permission.

## Recommended Attribution Block

```md
## Attribution

- Source: https://github.com/owner/repo
- Upstream commit: <commit-hash>
- License: <license-name>
- Copyright: <copyright-holder>
- Local modifications: <summary or "none">
```

## License Notes From Current Sources

- `google-deepmind/science-skills`: repository-level Apache-2.0 for software,
  with CC-BY-4.0 for other materials and additional third-party data-source
  terms noted upstream.
- `K-Dense-AI/scientific-agent-skills`: repository-level MIT, while individual
  skills may specify their own license in `SKILL.md`.
- Repositories without a visible license should remain links until permission is
  clarified.

Current copied and linked sources are recorded in `ATTRIBUTIONS.md`,
`THIRD_PARTY.md`, and `NOTICE.md`.
