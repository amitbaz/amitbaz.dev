---
title: Brief
status: accepted
date: 2026-10-10
---

# amitbaz.dev — Brief

## The problem

Amit's CV says "senior frontend engineer". The roles he wants next carry ownership of decisions, planning, and system design — the shape companies like PostHog and Ashby call *product engineer* — and the way he wants to work in them is with agentic AI workflows. A CV can state that; it cannot prove it. A recruiter deciding whether to forward him, or a hiring manager deciding whether to take the call, has no evidence for the part of the claim that matters most.

## The product

A personal site at `amitbaz.dev`, linked from the CV and LinkedIn, whose one job is **proof**. The Reader arrives already holding the facts; the site shows what the facts can't:

- **How he thinks** — stated as Principles and backed by the Worked Example: this site's own brief, PRD, decisions, and trade-offs, published as they were made.
- **How he works** — the Agentic Workflow, with Claude Code's role explicit and central: what he directed, what the agent produced, what he never delegates.
- **What he's done** — anonymised Decision Stories from past work, and the career history as a timeline inside the Story of the pivot.
- **Craft** — the site itself is frontend evidence. It is not a template; its design, interaction, and polish are part of the proof, on a phone as much as on a laptop.

The site is built *as a product*: brief, PRD, system design, design system, then implementation, each documented in the repository and rendered on the site. The process is the demonstration.

## The Reader

Anyone who clicks through from the CV or LinkedIn — agency recruiter, in-house sourcer, hiring manager. The site must survive a sixty-second skim and reward a five-minute read. The Reader's question is: *do we think this person knows what he's doing, and do we want him here?*

## Positioning

Headline: **Product Engineer**. Subline in the spirit of *"Frontend-rooted. Owns brief → PRD → system design → build, with agentic AI workflows."* The pivot is stated plainly, not hidden. "Senior frontend" stays near the top for recruiter search. Rationale and rejected alternatives: [ADR-0002](adr/0002-position-as-product-engineer.md), evidence in [research/role-label.md](research/role-label.md).

The front page also states, in a few lines, **what's next**: the shape of the role (owns decisions, planning, system design; still hands-on), then the titles it goes by — Product Engineer, Technical Product Manager, Founding Engineer, Forward Deployed Engineer. And one logistics line: Berlin-based, EU work authorisation, open to remote Europe/UK, relocation to the UK with sponsorship or to Asia.

## Destinations

| Destination | Contents |
|---|---|
| **Front** | Headline and subline; what's next; logistics; 2–3 short Decision Stories; compact career summary; email + LinkedIn. |
| **Process** | Principles (how he thinks) · Agentic Workflow (how he works) · Worked Example (this site's documents, rendered). |
| **Story** | The pivot narrative — where he came from, what changed, where he's going — with the career history as a timeline inside it. |
| **Decision Stories** | The anonymised stories with room to breathe: situation → the call → what happened. |

### Releases

- **Launch (~4 weeks from 2026-10-10):** Front, Process, Story.
- **Release 2:** Decision Stories page (Front carries short versions from launch).
- The site ships in Releases; each one extends the Worked Example.

## Constraints

- **Single source.** Process content is authored once, in this repository's documents; the site derives its narrative view at build. Nothing is written twice. ([ADR-0001](adr/0001-docs-are-the-single-source-of-site-content.md))
- **Craft bar.** No template. Phone and desktop designed as equals — the first skim probably happens on a phone from LinkedIn.
- **Honesty.** Past employer work appears only as role summaries and anonymised Decision Stories; the only fully documented Project is this site, and the site says so.
- **English at launch, i18n-ready.** Other languages (German, Mandarin, Spanish are candidates) must be addable without restructuring.
- **Public repository at launch.** Private while building, public when live. Working notes stay out of the history. The commit history is part of the evidence.
- **German-market ambiguity.** "Product Engineer / Produktingenieur" often means a mechanical role on German job boards; the frontend subline is the mitigation.

## Out of scope for v1

Blog or writing section · CV PDF download · analytics of any kind · per-viewer tailoring (`?for=acme`) · Process documentation for past Projects.

## Success

No metric. The bar: Amit would send this link instead of attaching a PDF, and would be glad a hiring manager clicked into Process.

## Deferred, deliberately

| Decision | Settled in |
|---|---|
| Front-page content structure and visual direction | Design phase |
| Exact subline wording; voice and tone | Content phase |
| How the narrative is curated from the raw documents at build | System design |
| Stack, hosting, domain setup | System design |

## Vocabulary

Terms used here — Reader, Project, Process, Worked Example, Craft, Principles, Decision Story, Agentic Workflow, Story, Release — are defined in [GLOSSARY.md](../GLOSSARY.md).
