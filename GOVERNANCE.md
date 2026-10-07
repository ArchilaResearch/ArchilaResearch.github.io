# Governance: archilaresearch.github.io

Covers ownership, portability, domains/services, handover, and backups.

## Ownership & decision rights

- **Mario Archila** has final authority over this site's content, identity, and technical decisions.
- This organization and site remain **independently controlled** and must not depend on `bpcn-lab` access.
- Recommended: one trusted **emergency administrator** with recovery access, and secure storage of org/domain recovery codes.

## Portability (must stay true)

Independent control includes: the `ArchilaResearch` org, the canonical domain and DNS, this repository, brand assets, design tokens, analytics account (if any), contact infrastructure, independently owned project/teaching/software repositories, backups, and structured content metadata. **No repository transfer from `bpcn-lab` is required for the core independent identity.**

Portability test (rehearse on a branch): replace the affiliation, update the relationship statement, **preserve all URLs**, keep historical affiliations fixed, update footer/structured-data/contact/legal, publish a transition note, leave `bpcn-lab` operational, and move the lab profile to alumni/collaborator status. All affiliation-dependent values live in [`_variables.yml`](_variables.yml) so this is a config change, not a migration.

## Content ownership register

This site owns Mario Archila's biography, research vision, independently led projects, supervised students, courses, software, and future-group identity. Lab-wide/institutional content is owned by [BPCN](https://github.com/bpcn-lab) and only summarized-and-linked here. Joint items record their single canonical owner in the item's metadata.

## Domain & service register

| Service | Address | Controlled by |
|---|---|---|
| Site (fallback) | `archilaresearch.github.io` | GitHub org `ArchilaResearch` |
| Custom domain | _TBD (personally controlled registrant)_ | Mario Archila |
| Contact email | `mario.archila@uni-jena.de` (current; portable target TBD) | Mario Archila |
| Source | `github.com/ArchilaResearch/archilaresearch.github.io` | GitHub org |

## Handover / backup

The repository is the backup; recover by cloning, building (`README.md`), and redeploying. Keep org and domain recovery codes in a personally controlled secure store. See [`SECURITY.md`](SECURITY.md).
