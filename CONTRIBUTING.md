# Contributing: archilaresearch.github.io

## Easiest: open an issue

Use an [issue form](https://github.com/ArchilaResearch/archilaresearch.github.io/issues/new/choose) to request a profile update, publication addition, or accessibility/privacy correction.

## For maintainers

- Site-wide and affiliation settings live in `_variables.yml` (this keeps the site portable). Edit there, not in pages.
- Page content is in `*.qmd`; structured content lives under `content/`.
- Work on a branch, open a pull request; `main` stays deployable.
- Build, metadata, and internal-link checks must pass before merge.

## Consent & rights (required)

Before publishing anyone's name, photo, or bio: obtain and record consent (`consent_recorded: true`), and record each image's source, rights basis, and alt text. Honour correction/removal requests. Distinguish supervision, employment, collaboration, and alumni status on profiles.

Do not commit participant/clinical data, student assessments, secrets, or build output (`_site/`).

## Local build

See [`README.md`](README.md).
