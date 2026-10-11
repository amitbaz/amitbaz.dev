---
status: accepted
---

# The repo's documents are the single source of the site's Process content

The Process page needs both a readable narrative and the real brief, PRD, and decisions behind this site. Keeping a hand-written site version alongside the repo docs would mean two places to maintain and a story that drifts from the record. We decided the documents in this repo (`GLOSSARY.md`, `docs/adr/`, the brief, the PRD, and whatever follows) are the only place Process content is authored; the site derives its narrative view from them at build time. How the narrative is curated from the raw docs (frontmatter, ordering, summaries) is a system-design question to be settled later — but the constraint stands: nothing about the Process is written twice.

## Considered options

- **Hand-curated snapshot on the site.** Better story control, but two sources that drift; rejected.
- **Link out to GitHub.** Zero build cost, but the Reader gets GitHub's rendering instead of the site's Craft, and the Process page stops being a demonstration; rejected.
