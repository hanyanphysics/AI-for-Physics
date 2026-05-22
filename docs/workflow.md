# Local Workflow

This repository is intended to be developed locally first, then committed and
pushed to GitHub when changes are ready.

## Basic Git Flow

```sh
git status
git add README.md skills/ docs/ metadata/
git commit -m "Describe the change"
git push origin main
```

## Working Notes

- Keep third-party copied material isolated under `skills/third-party/`.
- Update `THIRD_PARTY.md` and `metadata/sources.yaml` when adding external
  sources.
- Keep first-party skills under `skills/first-party/`.
- Prefer small commits with clear messages.
- Run any relevant validation or examples before committing nontrivial skills,
  scripts, or harnesses.
