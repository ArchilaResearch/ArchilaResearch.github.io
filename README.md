# archilaresearch.github.io

Website of the **Mario Archila Research Group**: Translational Neuro-AI and Cognitive Neuroscience. Independently owned and portable; currently based within [BPCN](https://github.com/bpcn-lab) at Friedrich Schiller University Jena.

Built with [Quarto](https://quarto.org) and deployed to GitHub Pages.

## Portability first

Every affiliation-dependent value lives in [`_variables.yml`](_variables.yml): affiliation, relationship statement, title, contact. Changing institution is a **config edit**, not a migration; URLs stay stable. See [`GOVERNANCE.md`](GOVERNANCE.md) for the portability test.

## Local development

Requires [Quarto ≥ 1.6](https://quarto.org/docs/get-started/) and Node ≥ 20.

```bash
quarto preview          # live local preview
quarto render           # build → _site/
npm run check           # validate metadata + internal links (after a render)
```

## Where things live

| Path | What |
|---|---|
| `_variables.yml` | **Portable site settings**: affiliation, relationship, title, contacts. |
| `_quarto.yml` | Navigation, footer, theme wiring. |
| `*.qmd` | Pages (home, research, publications, code-data, teaching, about, contact, legal). |
| `content/` | Structured content, empty at launch. |
| `styles/theme.scss` | Design tokens (independent identity). |
| `scripts/`, `.github/` | Validation, CI, issue forms. |

## Contributing

Use an [issue form](../../issues/new/choose); see [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Deployment

Push to `main` → build → validate → internal-link check → deploy to GitHub Pages.
