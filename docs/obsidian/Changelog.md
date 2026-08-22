---
project: cybersecurity
type: changelog
status: active
last_updated: 2026-08-22
tags: [project/cybersecurity]
---

# Changelog

Reconstructed from `git log`. The repository currently has a single commit in its visible history (likely imported/squashed rather than built up incrementally), plus the initial content this audit found already in place.

## History

- **ee9960f — Rename `index.html` to `Resourcehub.html`.** The original landing page was renamed, but internal "Back to Main" links across the other pages were not updated to match — see [[Tasks]] for the resulting broken-link issue.

## Baseline content (present as of this audit, predates visible git history)

- Resource hub and eight topic pages (Resources, Certification Guide, Certifications, Conferences, Forums & Community, Leading Cybersecurity Companies, Paid Trainings, Acronyms) — all static HTML with a shared dark Tailwind-based theme.
- `Tiktok.md` — TikTok accounts list, self-dated November 2024.
- `FULL Cybersecurity Resources.docx` — master/source resource document.
- `Untitled Diagram.drawio` — draw.io diagram, purpose undetermined.
- `SECURITY.md` — GitHub's default unfilled template.

## 2026-08-22 — Added Obsidian documentation knowledge base

- Added `docs/obsidian/` (this note set: [[Project]], [[Architecture]], [[Features]], [[Tasks]], [[Changelog]]) documenting the repo's actual purpose (curated cybersecurity resource links, not an application).
- Installed the `obsidian-sync` skill and `/sync-docs` command, and a `CLAUDE.md` documentation-sync policy, to keep these notes current going forward.
- No existing content was modified.
