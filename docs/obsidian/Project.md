---
project: cybersecurity
type: overview
status: active
last_updated: 2026-08-22
tags: [project/cybersecurity]
---

# Project

**Cybersecurity** is a small static, link-based resource hub — a personally curated collection of cybersecurity learning resources, not a software application. There is no build system, no source code, and no tests; the repository is a set of standalone dark-themed HTML pages (styled with Tailwind via CDN) plus a couple of Markdown/reference files, meant to be opened directly in a browser or hosted as simple static pages.

## Purpose

Aggregate and organize links useful to someone learning or working in cybersecurity/IT: certifications, training providers, conferences, communities, companies, acronyms, and social accounts to follow. Each topic gets its own self-contained HTML page with a consistent look (GitHub-dark palette, card-based sections) and a "Back to Main" link to [[Features|Resourcehub.html]].

## Scope

- Curated **link lists** grouped by topic (see [[Features]] for the full inventory).
- No application logic, no database, no backend, no auth — every page is static HTML with inline CSS/JS (Tailwind CDN, Google Fonts).
- One supplementary Word doc (`FULL Cybersecurity Resources.docx`) and one draw.io diagram (`Untitled Diagram.drawio`) exist alongside the HTML pages as source/reference material.
- A boilerplate `SECURITY.md` (GitHub's default template, unfilled) is present but not customized — see [[Tasks]].

## Organization

See [[Architecture]] for how the pages relate to one another (navigation, "Back to Main" links) and file layout.

## Related notes

- [[Architecture]] — page/file layout and navigation
- [[Features]] — inventory of resource categories covered
- [[Tasks]] — gaps and unfinished items
- [[Changelog]] — history reconstructed from git log
