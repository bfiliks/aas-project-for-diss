# AAS Project for Diss — Working Plan

**Felix Oke** · PhD candidate, UIUC · felixo2@illinois.edu
Collaboration: **American Antiquarian Society (AAS)**, Worcester, MA
Introduced by advisor **Ryan Cordell** (School of Information Sciences, UIUC) to **John J. Garcia, Director of Scholarly Programs, AAS** (jgarcia@mwa.org, 508-471-2134)
Topic: archival material in AAS collections on **early African American printing and publishing**

---

## 0. Where things stand

- Ryan (advisor) introduced Felix to John by email, having discussed "the projects you're seeking help on" in Charlottesville over the summer.
- John proposed a Zoom the **week of August 24–28, 2026** (2026-08-24 to 2026-08-28) — he's swamped at AAS and has an LA trip coming up.
- **Action needed:** Felix (or Ryan) proposes a specific day/time in that window.
- No agenda has been set yet — the sections below are prep material for that call, not a substitute for it.

---

## 1. Relevant AAS programs and collections (verified July 2026)

| Item | Detail |
|---|---|
| **Scholars' Workshop in Early African American Print** | 4-day in-person workshop at AAS, most recently held Jan 12–15, 2026. Led by Tara Bynum (Univ. of Iowa) with AAS staff. Open to 8 participants, "emerging scholars at the dissertation stage and beyond," pre-1900 African American studies. Free housing + $1,000 honorarium. **Last cycle's deadline was Oct 15, 2025** — a Jan 2027 cycle, if it recurs, would plausibly have an **~Oct 2026 deadline, i.e. within ~3 months**. Confirm timing with John directly. |
| **Black Self-Publishing project** | Ongoing, crowdsourced AAS research initiative cataloguing books self-published by people of African descent in North America, born before 1851 or first published before 1877. Public portal: collections.americanantiquarian.org/blackpublishing. Explicitly invites outside scholarly contributions. |
| **Just Teach One: Early African American Print** | AAS digital collection of rare early Black-authored texts prepared for classroom use. |
| **AAS General Catalog genre terms** | Catalog uses specific searchable terms: "Works by Black authors," "Works by Black people in the printing and publishing trades," "Works by Black illustrators/photographers/composers," "Works by Black newspaper/periodical editors" — each appended with individual names. |
| **Brown Family Collections + Fellowship** | Digital collection and a dedicated AAS fellowship supporting research in African American materials. |
| **Subscription databases (on-site access)** | African American Newspapers (Series 1 & 2), Black Authors 1556–1922, Slavery and Anti-Slavery: A Transnational Archive (Readex/Gale). |
| **Affiliated external projects** | Black Bibliography Project, Colored Conventions Project, Freedom on the Move — not AAS-run but cross-referenced from AAS's African American studies resource guide. |

Source guide: AAS "Finding Materials for African American Studies" (americanantiquarian.org/african-american-resources).

---

## 2. Pre-meeting prep (before the Aug 24–28 call)

- [ ] Skim the Black Self-Publishing portal and note 2–3 entries/authors that intersect with Felix's period/geography of interest.
- [ ] Browse "Just Teach One: Early African American Print" texts for anything directly relevant.
- [ ] Draft a 1-paragraph statement of Felix's current dissertation interests, specific enough that John can map it to AAS holdings.
- [ ] Ask Ryan what specifically he and John discussed in Charlottesville ("the projects you're seeking help on") — the notes reference this but don't specify it.
- [ ] Check whether the Scholars' Workshop is running its next cycle and what the actual 2026 deadline is (ask John directly — fastest way to get an accurate date).

## 3. Questions to bring to the call

1. What specific archival material/project did Ryan and John discuss in Charlottesville?
2. Is there an existing AAS project Felix could join, or is this scoped as a new collaboration built around his dissertation?
3. Would the Scholars' Workshop (if recurring) or a short-term fellowship (e.g. Brown Family Collection Fellowship) be the right entry point, versus an informal research visit?
4. What's the realistic timeline for archive access — remote finding aids first, or does this require an in-person visit to Worcester?
5. Are there restrictions/embargoes on any of the relevant collections?

## 4. Existing related work (this GitHub account)

Felix's prior repos already build the computational groundwork this collaboration could extend to AAS-held material:

| Repo | Focus | Possible AAS extension |
|---|---|---|
| [`tcr-genre`](https://github.com/bfiliks/tcr-genre) | Genre classification of *The Christian Recorder*, 1861–1870 (Claude Haiku 4.5) | Apply the same classification pipeline to AAS-held Black periodicals beyond the Recorder |
| [`black-press-bible`](https://github.com/bfiliks/black-press-bible) | Biblical quotation detection in *The Christian Recorder*, 1861–1870 (extended Mullen pipeline, AME paraphrase dictionary) | Test against other AAS periodical holdings for cross-title comparison |
| [`black-press-attribution`](https://github.com/bfiliks/black-press-attribution) | Resolving pseudonymous/anonymous authorship in 19th-c. Black press, 1827–1902 | Directly relevant to Black Self-Publishing project entries with uncertain/attributed authorship |
| [`black-press-serials`](https://github.com/bfiliks/black-press-serials) | Serialized fiction across the 19th-c. Black press network, 1837–1902 | Cross-reference against AAS's Just Teach One texts and periodical holdings |
| [`tcr-harper`](https://github.com/bfiliks/tcr-harper) | Frances E.W. Harper in *The Christian Recorder*, 1854–1902 | Check for Harper material or related figures in AAS collections |
| [`tcr-soldiers`](https://github.com/bfiliks/tcr-soldiers) | USCT soldier letters and Civil War-era correspondence in *The Christian Recorder* | Possible parallel in AAS manuscript/correspondence holdings |
| [`tcr-acs`](https://github.com/bfiliks/tcr-acs) | ACS colonization and African emigration discourse in *The Christian Recorder*, 1861–1902 | Check AAS periodical/pamphlet holdings for parallel emigration-debate material |

**Talking point for the August call with John:** Felix isn't starting from zero — the existing computational pipelines (genre classification, biblical-quotation detection, authorship attribution, serial-fiction tracking) were built on *The Christian Recorder* and could plausibly extend to AAS's periodical/pamphlet/self-publishing holdings. Worth asking John directly whether AAS has machine-readable/OCR'd text for candidate collections, since that determines whether these pipelines are portable as-is.

**Advisor alignment:** Ryan Cordell (Associate Professor, School of Information Sciences and Dept. of English, UIUC) leads the NEH/ACLS-funded **Viral Texts** project, which mines large-scale 19th-century periodical archives for borrowed/reprinted text to trace circulation and influence among antebellum writers and editors. This is a direct methodological precedent for `black-press-serials` (serialized fiction tracking) and `black-press-attribution` (pseudonymous authorship) — worth explicitly framing the AAS collaboration as an extension of Viral Texts-style text-reuse methods into the Black press / early Black self-publishing corpus specifically.

## 5. Draft phased plan (to revise after the August call)

| Phase | Target window | Activity |
|---|---|---|
| 0 — Alignment | Aug 2026 | Zoom with Ryan + John; scope the collaboration; confirm any near-term fellowship/workshop deadlines. |
| 1 — Archival scoping | Sep–Oct 2026 | Remote review of AAS catalog (genre-term searches), Black Self-Publishing data, subscription databases where accessible via UIUC. Build a working bibliography. |
| 2 — Funding/access | Oct 2026 (if a fellowship/workshop deadline applies) | Apply to relevant AAS fellowship or workshop; otherwise arrange a self-funded research visit. |
| 3 — On-site research | Winter/Spring 2027 (TBD with John) | Primary-source research at AAS, Worcester. |
| 4 — Analysis & writing | Spring–Summer 2027 | Draft dissertation chapter(s) grounded in AAS material. |
| 5 — Feedback loop | Ongoing | Circulate drafts to Ryan and, where appropriate, John/AAS staff for archival accuracy checks. |

This timeline is a placeholder — dates should be firmed up once the August meeting sets real scope and any actual fellowship deadlines are confirmed with John.

---

## Sources

- [Scholars' Workshop in Early African American Print](https://www.americanantiquarian.org/early-african-american-print-workshop)
- [Black Self-Publishing](https://www.americanantiquarian.org/black-self-publishing)
- [Finding Materials for African American Studies](https://www.americanantiquarian.org/african-american-resources)
- [African American Cultures of Print](https://www.americanantiquarian.org/african-american-cultures-of-print)
