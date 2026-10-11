# Portfolio references: what senior frontend / product / design engineers put on their sites

Surveyed 2026-10-11. 25 live sites fetched directly (text + raw HTML; motion and type judged from served CSS/font files and textual hints, not rendered screenshots). Replaced: `sarahdrasnerdesign.com` (301 → thefivefortyfive.com, no longer a personal dev site) and `sdras.dev` (DNS fail); `shuding.org` → `shud.in`. Could not read: `chester.how` (429), `tobiasfried.com` (client-rendered, empty HTML).

## 1. Recommendation for the Front page candidates

- **Photo: no hero photo.** 7/25 sites have one; 5 of those 7 are in the "template" cluster (stats bands, skill grids, availability badges). Of the 14 sites that read as crafted, only the two educator/brand sites (Comeau, Williams) show a face, and Delba's job-seeking site puts it below the fold under "About me". LinkedIn already supplies the face; on Front it signals "personal brand", not "product engineer". If wanted at all: small, on Story, not Front.
- **Skills/stack list: no.** 3/25 have one (Varde, mxis.ch, Wieruch); all three read as template. Every crafted site names tools *inside* prose or project blurbs (Paco, Emil, Hayden, Jakub, Lovin, Robinson). The CV already carries the keyword list. Put tools inside the 2–3 decision stories and on Process; never a grouped grid on Front.
- **Now line: yes, one sentence, in the intro prose, not a labeled block.** 20/25 state the current role in the first sentence. The three sites with a labeled "Now"/"Today" section (Paco, Emil, Appleton) are the most-cited craft references in this space, and Appleton dates hers. Recommended shape: "Now: building this site with an agentic workflow — see Process." It doubles as the hook to the Worked Example and is the only Front element that proves "currently working this way" rather than "once did". Date it or keep it evergreen.
- **Keep (confirmed by evidence):** explicit "what I'm looking for" + one CTA (Delba: one sentence, "Let's talk" → LinkedIn; only 5/25 do this and it is exactly what a recruiter needs), a "Previously …" clause in the career summary (Kowalski, Tompkins), click-to-copy email (Freiberg), a "View source" footer link (Lovin, Williams, Pate) — the cheapest possible proof for a site whose build process is the product.
- **Target density:** crafted fronts run 50–250 words (median of the 25 ≈ 190). Front should fit that budget; everything else is a link.

## 2. Survey table

Label = exact self-description in headline/first sentence. Now = labeled "Now" section (**Y**), current role stated in bio prose (p), or none (–). Proc = documents own build: full write-up (**Y**), source link / "built with" only (s), none (–). Words = visible words on front page from served HTML.

| Site | Label | Front sections, in order | Photo | Stack list | Now | Nav | Proc | Words | Crafted vs. template |
|---|---|---|---|---|---|---|---|---|---|
| [rauno.me](https://rauno.me) | "Estonian interaction designer" | name+label · link list (Craft, History of Software Design, Projects, Field Notes) · socials + yearly archives · email copy · manifesto list ("Make it fast … Make it.") | – | – | p | hub | – | 54 | Near-empty page; one interaction (email → "Copied"); stacked imperative lines as the only ornament |
| [paco.me](https://paco.me) | "Crafting interfaces." | bio · Building · Projects · Writing · **Now** · Connect | – | – | **Y** | single scroll | – | 201 | Söhne + Newsreader + Inter subsets; cmdk menu; Now section mixes focus areas with music |
| [brianlovin.com](https://brianlovin.com) | "software designer … currently making AI products at Notion" | Writing · Projects · Elsewhere · Sections index · footer (source, llms.txt, sitemap) | – | – | p | hub | s | 138 | Sparse list hub; footer ships llms.txt and source repo (briOS) |
| [joshwcomeau.com](https://www.joshwcomeau.com) | none (name only) | top nav · article feed · categories · popular · photo + newsletter · courses · footer (sound + dark toggles) | Y | – (category tags) | – | top nav | **Y** | 1007 | Educator brand; sound toggle, rainbow widget; documents build in "How I built my blog v2" |
| [leerob.com](https://leerob.com) | "I'm an engineer and writer." | name/handle · bio with Default/Long length toggle · Notes topics · dated Blog list | – | – | p | hub | – | 172 | Bio-length toggle is the signature interaction; career woven into 3 prose paragraphs, no work-history block |
| [maggieappleton.com](https://maggieappleton.com) | "Designer, anthropologist, and mediocre developer." | nav · card hub (Essays, Notes, Patterns, …) · Garden intro · Essays · Notes · Patterns · Library · RSS | – | – | **Y** (+ /now log) | top nav | **Y** (/colophon) | 643 | Canela + Lato, Utopia fluid scale, growth-stage labels (seedling/evergreen), view-transitions; dense but systematised |
| [emilkowal.ski](https://emilkowal.ski) | "Design Engineer" | **Today** blurb (Linear; previously Vercel) · Projects · Writing · Newsletter · More | – | – | **Y** | single scroll | – | 228 | Plain copy, lists only; "Today … previously …" as the whole bio |
| [delba.dev](https://delba.dev) | "I build DX and education systems." | intro w/ "I'm looking for my next role … Let's talk" · Work · Personal · About me (photo) · socials | Y (below fold) | – | – | single scroll + anchors | – | 227 | Only site with an explicit ask + CTA; Work entries = name + what was done + (sometimes) outcome |
| [shud.in](https://shud.in) | "designer and developer at Vercel" | nav · name · one bio block · inline links | – | – | p | top nav | – | 125 | One paragraph, four nav items; everything else is a link |
| [jhey.dev](https://jhey.dev) | "A design engineer" / "Brand Design Studio @ Shopify" | tagline · title · bio · Previously · speaking · AMA · link list with live widgets (globe, weather, Spotify) | – | – | p | single scroll | – | 166 | Inter + Doto; live widgets instead of sections; "Previously" credentials line |
| [linusrogge.com](https://linusrogge.com) | "Design Engineer at SPACING" | name+label · Email, Are.na, Cosmos, Letterboxd | – | – | p | hub | – | 13 | 13 words. Business card as a site; confidence by omission |
| [nexxel.dev](https://nexxel.dev) | "software engineer at opencode · chennai, india" | intro · blog · work · projects · elsewhere | – | – (interests only) | p | top nav w/ [h][b][w][p] keys | – | 186 | Lowercase, terminal idiom, keyboard shortcuts; dated work entries |
| [cassidoo.co](https://cassidoo.co) | "Software Engineer in Chicago" | header · nav · bio · newsletter · 5 recent posts · subscribe · tags · footer (open source) | Y | – | p | top nav | s | 251 | Content-creator pattern: newsletter first, posts second |
| [ped.ro](https://ped.ro) | "Yo! I'm Pedro Duarte." | nav · one bio paragraph (Raycast; Radix, Stitches) | – | – | p | top nav | – | 225 | Single paragraph + nav (Writing, Speaking, Shooting); a video element, no images |
| [rsms.me](https://rsms.me) | "Software is the medium through which I express myself." | nav · Projects (15 of 75) · Thoughts (4 of 512) · bio · Inter / shop promos | – | – | – | top nav | – | 455 | Dense archive; typographic authority from Inter itself |
| [jakub.kr](https://jakub.kr) | "Founding Design Engineer at Interfere" | bio · Projects · Writing (incl. dated Notes) · Links/RSS | – | – | p | single scroll | – | 218 | Writing about gestures, shared-layout animation, OKLCH; bio is about craft and feel |
| [steventey.com](https://steventey.com) | "Programmer. Writer. Pianist." | nav · photo + headline · bio (Dub; ex-Vercel) · icon socials | Y | – | p | top nav | – | 61 | Three-word headline, one paragraph, nothing else |
| [haydenbleasel.com](https://www.haydenbleasel.com) | "software engineer and product designer" | skip link · name · nav · bio (OpenAI) · past work · open source · mailing list · socials | – | – | p | top nav | – | 150 | Söhne; three prose paragraphs (now / past / OSS); frames "agentic development" explicitly |
| [shadcn.com](https://shadcn.com) | "design engineer on the AI team at Vercel" | bio · stats · newsletter · product cards · sponsors | – | – | p | hub | – | 151 | Stats band works only because the numbers are extraordinary; consistent `shadcn/x` naming |
| [alexpate.com](https://alexpate.com) | "A product engineer from the UK based in Milan." | bio · Personal Projects (image cards, "Acquired 2025" tag) · Recent Writing · footer (View Source) | – | – | – ("most recently worked with") | top nav | s | n/a | Cleanest of the self-labeled product engineers: minimal, status tags, source link |
| [mxis.ch](https://mxis.ch) | "Product engineer exploring … local-first apps" | hero ("Hello, I'm Maxi 👋") · About · Journey timeline · Toolbox (.ts .svelte .go …) · Projects · Connect | – | Y (Toolbox) | – | single scroll | – | n/a | Timeline + file-extension skills: template bones with a styling idea on top |
| [kamranqadri.com](https://kamranqadri.com) | "Product Engineer — AI-native software" | hero w/ photo · stats band · Selected work · What I work on · Notes · career timeline ("Scope, not titles") · community · Let's talk | Y | – | p ("right now …") | anchors | – | n/a | Closest brief to this project; headline is a positioning sentence; "Best for" audience note; but stats band + hero photo read agency |
| [abhivarde.in](https://abhivarde.in) | "Full stack product engineer" / "An Engineer Who Ships" | hero · Proof of Work stats · D×P×E statement · sponsor · featured project · Work · Skills (7 groups) · availability + copy email · footer "built with" | Y | Y (grouped) | – ("Open to … roles") | top nav (9 items) + guestbook | s | n/a | Every template signal at once: counters, skill grid, 👋, guestbook, "built with Next.js" footer |
| [robinwieruch.de](https://www.robinwieruch.de) | "Freelance Full-Stack Software Engineer for AI and Product" | promo bar · hero (stack line, Work with Me) · stats · Services · clients · CTA · courses · testimonials · newsletter | – | Y (hero line) | – ("Available Remotely") | top nav | – | n/a | Consulting landing page: service cards, testimonials, logos |
| [coderdiaz.com](https://coderdiaz.com) | "Fundador & Senior Lead" | nav · hero (availability badge, CTA, stats) · project cards · services · bio · socials · blog · footer | Y | – (services) | – | top nav | – | n/a | Agency pattern: repeated quote CTAs, delivery promises |

## 3. Frequency table (N = 25)

| Element | Count | Notes |
|---|---|---|
| Photo on front | 7 | 2 educators, 1 job-seeker below fold, 4 freelancer/template cluster |
| Skills/stack list | 3 | all in template cluster |
| Labeled "Now"/"Today" section | 3 | Paco, Kowalski, Appleton (Appleton also keeps a dated /now log) |
| Current role in first sentence (unlabeled) | 17 | the default pattern |
| Explicit "looking for / open to" + CTA | 5 | Delba, Varde, Wieruch, Diaz, Qadri |
| Writing list on front | 13 | +6 more link to Writing from nav only |
| Documents own build (write-up) | 2 | Comeau (blog post), Appleton (/colophon + /garden-history) |
| Source link or "built with" only | 4 | Lovin, Williams, Pate, Varde |
| Top nav | 14 | vs. 11 single-scroll hubs with no nav |
| Newsletter box | 6 | all creators/consultants |
| Stats/counter band | 4 | shadcn, Varde, Qadri, Wieruch |
| Front page ≤ 250 words | 16 of 19 measured | crafted tier clusters at 50–230 |

## 4. Crafted vs. template patterns

Crafted (recurs across Freiberg, Coursey, Lovin, Robinson, Kowalski, Ding, Rogge, Krehel, Bleasel, Duarte, Tey):
- One self-describing sentence in the first person, current employer linked inline, "previously …" as the second clause. No "About" heading, no work-history block; the career is prose.
- Lists of links instead of sections. The front page is an index; depth lives one click away.
- Exactly one signature interaction: email → "Copied" (Freiberg), bio Default/Long toggle (Robinson), cmdk (Coursey), keyboard keys (Dash), live widgets (Tompkins), growth-stage labels (Appleton). Never more than one.
- Restrained type: one licensed/custom family (Söhne, Canela, Newsreader, Inter subset), no display sizes beyond the name, fluid scale (Appleton uses Utopia).
- No hero image, no counters, no badges, no CTA buttons; contact is a text link.
- Word budget 50–250. Rogge proves the floor (13 words) still reads as a senior.
- Tools appear only as nouns inside stories ("built Sonner", "worked on Next.js docs"), never as a grid.
- Status tags carry information, not decoration: "Acquired 2025" (Pate), "wip" (mxis), "In active development" (Qadri), seedling/evergreen (Appleton).

Template (recurs across Varde, Qadri, Wieruch, Diaz, mxis.ch, and every Framer/Webflow template surfaced by search):
- "Hey, I'm X 👋" hero with portrait and primary button.
- Stats band ("Proof of Work", "10+ years", "150+ countries"). Exception: shadcn, where the numbers are genuinely rare.
- Skills grouped by category (Languages / Frontend / Backend / …) or as logo rows.
- Services cards, testimonials, client logos, availability badge, repeated CTAs.
- Vertical timeline with year pills (mxis, Qadri) as the main career artifact.
- Footer "Built with Next.js, Tailwind, Vercel" (the crafted tier links the repo instead of naming the stack).
- Nine-item top nav incl. Guestbook / Hackathons / Network.
- Observation: among sites found by searching for the literal "product engineer" self-label, 5 of 6 fall in this cluster; the crafted tier labels itself "design engineer", "designer and developer", or just a sentence about what they make. The label needs to be carried by the page, not the page by the label (cf. Qadri's positioning headline, which works).

## 5. Ideas not yet planned, with verdict for a recruiter-facing proof site

| Idea | Seen at | Verdict |
|---|---|---|
| Dated `/now` log | Appleton | No separate page; one dated sentence on Front covers it |
| `/stack` or `/uses` page | Lovin | No; Process already carries tooling, and a tools list is the CV's job |
| Colophon | Appleton | Yes, but as the last section of the Worked Example on Process, not a destination |
| "View source" footer link / open-source repo | Lovin, Williams, Pate | **Yes.** Cheapest proof that the Process page is real; also lets a hiring manager read commits |
| `llms.txt` | Lovin | Yes, small; on-brand for the agentic-workflow story and costs one file |
| Click-to-copy email | Freiberg, Varde | Yes; the one permitted signature interaction if nothing better emerges |
| Bio length toggle (Default / Long) | Robinson | Maybe; neat fit for recruiter (short) vs. hiring manager (long), but it competes with Story for the long version |
| "Assumed audience" / "Best for" line | Appleton (components), Qadri | **Yes.** One line under the headline saying who the page is for sharpens the "looking for" statement |
| "Previously …" clause | Kowalski, Tompkins | Yes; it is the compact career summary in six words |
| Status tags on stories ("shipped", "reversed", "in progress") | Pate, Qadri, Appleton | Maybe; only if a decision story has a real status to report |
| Yearly archived site versions | Freiberg | Later; the Worked Example changelog is the v1 equivalent |
| Keyboard shortcuts, cmdk, live widgets | Dash, Coursey, Tompkins | No; recruiters won't find them and they read as developer-for-developers |
| Guestbook, AMA, newsletter, reading list, library | Lovin, Varde, Tompkins, Appleton | No; audience is not a readership |
| Speaking / press | Bleasel, Duarte | Only if real items exist |
| Skip-to-content link, dark mode via `prefers-color-scheme` | Bleasel, Appleton | Yes as baseline accessibility; not a feature |

## 6. Sources

Fetched 2026-10-11: https://rauno.me · https://paco.me · https://brianlovin.com · https://brianlovin.com/stack · https://www.joshwcomeau.com · https://www.joshwcomeau.com/blog/how-i-built-my-blog-v2/ · https://leerob.com · https://maggieappleton.com · https://maggieappleton.com/colophon · https://maggieappleton.com/now · https://emilkowal.ski · https://delba.dev · https://shud.in · https://jhey.dev · https://linusrogge.com · https://nexxel.dev · https://cassidoo.co · https://ped.ro · https://rsms.me · https://jakub.kr · https://steventey.com · https://www.haydenbleasel.com · https://shadcn.com · https://alexpate.com · https://mxis.ch · https://kamranqadri.com · https://abhivarde.in · https://www.robinwieruch.de · https://coderdiaz.com

Product-engineer candidates were found via the GitHub users API (`"product engineer" in:bio followers:>300`), then their `blog` URL fetched. Dead/unreadable: https://sarahdrasnerdesign.com (301 to thefivefortyfive.com), https://sdras.dev (NXDOMAIN), https://chester.how (429 ×2), https://tobiasfried.com (JS-only shell).
