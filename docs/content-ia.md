---
title: Content & information architecture
status: accepted
date: 2026-10-11
---

# Content & information architecture

What exists on each destination, and what each piece of content is for. **Ordering, emphasis, and above-the-fold on the Front are decided with the design exploration, not here** — the content may change once it's seen. The exception is the Process page, whose order is an argument (claims → how → proof) and is settled.

Fact source: [`source/cv.md`](source/cv.md). Evidence for the Front decisions: [`research/portfolio-references.md`](research/portfolio-references.md).

## Navigation

Persistent top nav with three links — **Front · Process · Story** — identical on phone and desktop. A Reader arriving from LinkedIn can go straight to Process without scrolling the Front. Navigation is conventional on purpose; Craft shows elsewhere.

Footer, every page: **View source** → the public repo. The cheapest proof that the build is real.

## Front

Budget: **≤ ~200 words**. Everything that isn't on this list is a link.

| Content | Purpose | Notes |
|---|---|---|
| Name · **Product Engineer** · subline | The claim | Subline wording: content phase. Must contain "frontend" for recruiter search and the agentic differentiator. |
| **Now** line | Proves "works this way today", not "once did" | One sentence in the intro prose: *building this site with an agentic workflow → Process.* Dated or evergreen. |
| **Previously …** clause | Career in one line | *"Previously 6 years at Made2Flow, first employee → senior frontend."* Links to Story. |
| **What's next** | Lets a recruiter match to an opening | Role shape first (owns decisions, planning, system design; still hands-on), then titles it goes by: Product Engineer, Technical PM, Founding Engineer, Forward Deployed Engineer. |
| **Logistics** line | The recruiter's first filter | Berlin · EU citizen · remote Europe/UK · relocation to UK with sponsorship or to Asia. |
| **Decision Stories**, short form | The evidence hook | 2–3 stories, 2–3 lines each, linking to the full versions (Release 2 page; at launch, the full versions live on Story or inline). |
| **CTA** | The action | Email (click-to-copy, "Copied" confirmation) + LinkedIn. Email is `hello@amitbaz.dev`. |

**Not on Front:** photo (if anywhere, small, on Story) · skills/stack grid (tools are named inside the stories and on Process) · anything that needs a scroll to find the CTA.

## Process

Order is fixed: **Principles → Agentic Workflow → Worked Example.** How I think → how I work → proof.

### Principles
3–5. Each: one line Amit would defend in an interview, then 3–4 sentences on what it looks like in practice. To be grilled out in their own session.

### Agentic Workflow
Four parts:
1. **Division of labour** — what Amit directs, what he delegates, what he never delegates (what to build, decisions, taste).
2. **The method** — how a piece of work moves: grilling → glossary & ADRs → brief → spec → tickets → TDD → review → retro. This site is the running example.
3. **Tooling** — Claude Code (plugins, skills, subagents), parallel agents (Superset, worktrees), pen.dev. Concrete and searchable; expect it to date.
4. **Precedent at work** — the Made2Flow plugin (PRD in, questionnaire out). A pointer to that Decision Story, not a repeat.

### Worked Example
**Curated spine + full documents.** A narrative path — brief → decisions → research → content & IA → design → system design → PRD → build — with a paragraph per step, each opening into the full rendered document from this repo. Mechanism (how the spine is derived from `docs/` at build) is a system-design question under ADR-0001.

## Story

**Three acts**, 400–600 words, with the **timeline** running alongside as evidence.

1. **Where I came from** — frontend; first employee at Made2Flow before an engineering team existed; prototypes that became production.
2. **What changed** — the questionnaire platform: shaping PRDs with the PM, building the plugin, owning the problem rather than the ticket.
3. **Where I'm going** — the role shape from What's next, and why agentic workflows are the way he wants to work.

**Timeline:** roles with one line of ownership each, six entries — Made2Flow Senior FE 2023–26 · Made2Flow FE 2020–23 · PAL 2017–18 · IDF 2015–19 · BGU 2012–15 · (gili.careers 2026 as a side-project entry). A compact version appears on Front as the Previously clause.

Photo: optional, small, here — not on Front.

## Decision Stories

Format for each: **situation → the call Amit made → what happened.** May name the company and use any fact already on the public CV; internal specifics (people, customers, data, code, unreleased plans) stay out.

The three:

| Story | The call | What it proves |
|---|---|---|
| **Questionnaire platform + plugin** (Made2Flow 2025–26) | Replace SurveyJS with an own platform, and build a Claude Code plugin that generates questionnaires from a PRD | Delivery went from 1 week–2 months to hours–days; Product became self-serve. PRD shaping, architecture, and agentic work in one. |
| **Monorepo + design system** (Made2Flow 2023–25) | Set up Turborepo and shared packages used by 2–3 apps *and* the backend | Architecture judgement; building leverage, not features. |
| **Killing gili.careers** (2026) | After writing the PRD and building a prototype, discovery surfaced jackandjill.ai already doing it — stopped | Discovery discipline and the willingness to kill an idea. Rarer than shipping. |

At launch the full versions live where design puts them (Story or inline on Front); Release 2 gives them their own destination.

## Content still to be written

Principles · Agentic Workflow · Story prose · the three Decision Stories in full · subline · What's next · logistics line · Now line. Tracked in [`backlog.md`](backlog.md). Voice & tone is decided before any of it.

## Vocabulary

Reader, Process, Worked Example, Craft, Principles, Decision Story, Agentic Workflow, Story, Release — see [GLOSSARY.md](../GLOSSARY.md).
