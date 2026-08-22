---
project: cybersecurity
type: architecture
status: active
last_updated: 2026-08-22
tags: [project/cybersecurity]
---

# Architecture

There is no application architecture in the software sense — this note documents the **file layout and page navigation** instead.

## Layout

All files live flat at the repo root (no subdirectories):

- `Resourcehub.html` — the hub/landing page; links out to the topic pages below.
- `Resources.html` — free cybersecurity learning resources.
- `Certification Guide.html` — cybersecurity education & certification guide.
- `Certifications.html` — list of cybersecurity certifications.
- `Conferences.html` — cybersecurity conferences & events.
- `Forums & Community.html` — cybersecurity learning & community hub (forums, Discords, subreddits, etc.).
- `Leading Cybersecurity Companies.html` — notable vendors/companies.
- `Paid Trainings.html` — paid cybersecurity training resources.
- `Acronyms.html` — cybersecurity acronym glossary.
- `Tiktok.md` — curated list of tech/cybersecurity TikTok accounts (Markdown, styled as an HTML fragment/page body).
- `FULL Cybersecurity Resources.docx` — a Word document, likely the original/master source these HTML pages were generated from.
- `Untitled Diagram.drawio` — a draw.io diagram file (untitled/unpopulated at last check).
- `SECURITY.md` — GitHub's default unfilled security-policy template.

## Navigation pattern

Every topic page shares the same visual template (dark GitHub-style theme via Tailwind CDN, card sections, Inter font from Google Fonts) and includes a "Back to Main" link pointing at `index.html`. `Resourcehub.html` itself also links to `index.html`.

**Known issue:** the repo's landing/entry file was renamed from `index.html` to `Resourcehub.html` (see [[Changelog]]), but the "Back to Main" links across the other pages were not updated — they still point at the now-nonexistent `index.html`. See [[Tasks]].

## Related notes

- [[Project]] — overview and purpose
- [[Features]] — content inventory per page
- [[Tasks]] — the broken-link issue and other gaps
