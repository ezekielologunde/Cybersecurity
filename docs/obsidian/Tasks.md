---
project: cybersecurity
type: tasks
status: active
last_updated: 2026-08-22
tags: [project/cybersecurity]
---

# Tasks / Gaps

Observations from auditing the repo — not commitments, just noted gaps.

- **Broken navigation links.** `Resourcehub.html` and every topic page link back to `index.html`, but the entry file was renamed to `Resourcehub.html` (see [[Changelog]]). All "Back to Main" / hub links are currently dead. Fix: update the `href="index.html"` references to `Resourcehub.html`, or add an `index.html` that redirects/duplicates the hub.
- **`SECURITY.md` is an unfilled template.** It still contains GitHub's generic placeholder version table and instructions ("Use this section to tell people..."). Either fill it in with a real policy relevant to a static content repo, or remove it if not needed.
- **`Untitled Diagram.drawio` has no descriptive name or confirmed content.** Worth renaming and documenting once its purpose is clear, or removing if stale.
- **Relationship between `FULL Cybersecurity Resources.docx` and the HTML pages is undocumented.** Unclear whether the `.docx` is the source of truth that HTML is generated from, or a separate/older artifact. Worth clarifying in [[Project]] once known.
- **`Tiktok.md` content is dated** (self-reported "Last updated: November 2024") — may need a refresh pass for dead accounts/links.
- **No link-checking.** None of the external resource links (certifications, trainings, communities, companies) have been verified as live during this audit.

## Related notes

- [[Project]]
- [[Architecture]]
- [[Features]]
