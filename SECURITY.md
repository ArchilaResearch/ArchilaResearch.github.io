# Security policy: archilaresearch.github.io

## Reporting

Report security or privacy concerns (including accidentally published sensitive data) to **mario.archila@uni-jena.de**. Do not open a public issue for sensitive reports.

## Practices

- Two-factor authentication required; no shared accounts.
- Protected `main` branch; changes via pull requests.
- Least-privilege GitHub Actions permissions (`contents: read`, `pages: write`, `id-token: write`).
- No secrets in the repository; `_variables.yml` contains only public information.
- Pinned third-party actions; reviewed dependencies.
- Secure domain recovery; recovery codes stored personally and safely.

## Incident procedure (accidental sensitive publication)

1. Remove public access.
2. Rotate exposed credentials.
3. Notify affected people and any relevant institutional contacts.
4. Purge repository history if necessary.
5. Invalidate caches where possible.
6. Document the event and strengthen controls.
