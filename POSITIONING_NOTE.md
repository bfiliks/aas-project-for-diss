# Between Two Manifestos: A Positioning Note

*Drafted 2026-07-20 ahead of the August meeting with John Garcia (AAS) and in conversation with Ryan Cordell's work.*

## Two manifestos

Ryan Cordell's "Speculative Bibliography" (*Anglia*, 2020) and John Garcia's "Critique! Critique! Critique! Black Labor in the Early American Book Trade" (*Criticism*, 2022) are both, in their own registers, manifestos for what bibliography should become next.

Cordell's move is computational. Comprehensive manual editing of mass-digitized archives is no longer possible at the scale digitization has produced — Chronicling America holds millions of pages but still represents a small, uneven fraction of what was actually published. His answer: treat a probabilistic computational model — a text-reuse cluster, a classifier, a language model — as a bibliographic argument in its own right, no different in kind from a human bibliographer's judgment that two books belong together. The model is "speculative" in the sense of being propositional, testable, and revisable, not a claim to settled truth.

Garcia's move is critical. Recovering Black labor in the early American and Caribbean book trade — the enslaved compositors, papermakers, couriers, and domestic workers who made white book culture possible — requires more than widening bibliography's subject list. It requires bibliography to critique its own presuppositions, using the resources of Kantian critique, Foucault, and Adorno's negative dialectics, because those presuppositions are what occluded this labor in the first place. His method works close to the archive's grain: financial paperwork, indenture forms, runaway advertisements — evidence that survives in single, non-redundant documents and demands to be read one at a time.

Both have a common, mostly unstated ancestor: D.F. McKenzie's *Bibliography and the Sociology of Texts* (1999), which argued that bibliography must account for the social, technical, and economic circumstances of a text's production and transmission — not just its textual authority — because a book, or a newspaper, is "a product of human agency in complex and highly volatile contexts." Cordell's computational models and Garcia's critique read as two different answers to a McKenzie-shaped question: what does it actually take to recover those conditions of production?

## Why they don't simply combine

These methods are built for differently shaped evidence, not for the same evidence at different resolutions. Cordell's method needs redundancy — many reprints across many papers — before a statistical pattern means anything. Garcia's method needs the opposite: singular, irreplaceable documents read with total care. You cannot run reprint-detection on one indenture form, and you cannot close-read your way through 111,351 newspaper articles. "Combining" them is not actually available as a move; the real question is what happens when a single corpus needs both at once.

## Where the early Black press actually sits

The Black press is unusual because it needs both. It is large enough to be genuinely computational — the *Christian Recorder* alone runs to over 111,000 digitized articles — and it is shaped, at the level of the archival record itself, by the exclusions Garcia's critique is about: worse OCR quality on pre-1860 titles, pseudonymity used as a structural safety practice rather than incidental noise, metadata gaps that are patterned rather than random. Cordell's own corpus (the mainstream nineteenth-century press) doesn't carry this problem to the same degree — it is comparatively well-preserved and well-catalogued. Garcia's corpus (book-trade labor records) doesn't carry Cordell's problem — it was never going to be large enough to need computation. The early Black press carries both.

## The question this raises

Cordell's framework treats the "noise" a computational model encounters — OCR error, scribal variation, gaps in the record — as basically innocent: the ordinary mess of history, to be modeled around or smoothed over. Garcia's argument is that in an archive built under conditions of systematic exclusion, some of what looks like noise is not innocent. It is the residue of who was permitted to be recorded, catalogued, and preserved in the first place.

If that is right, a probabilistic model applied without modification does not just have a data-quality problem. It risks re-encoding that exclusion at computational speed and scale — mistaking historically produced silence for statistical noise, and smoothing over exactly the evidence that most needs to be seen. This is the stake behind Jessica Marie Johnson's "Markup Bodies" (2018): that computational methods applied to Black archives can re-enact the archive's own violence rather than repair it.

**The working question, stated plainly:** does Cordell's claim — that a computational model is a testable, contestable bibliographic proposition — survive contact with an archive for which Garcia's critique is historically true? And if it needs modification to survive, what does that modification look like in practice, not just in theory?

## Where this is already underway, not just proposed

- **Pseudonymity as evidence, not noise.** `black-press-attribution`'s treatment of pseudonymous publishing (following Derrick Spires, 2022) reads it as a deliberate protective practice under conditions of danger, not as a resolution problem to be classified away. This already departs from speculative bibliography's default assumption that ambiguity is something to be modeled through.
- **Confidence as epistemic humility, built in.** The `black-press-knowledge-graph` ontology tags every inferred relationship with a confidence level (HIGH/MEDIUM/WEAK), and specifically defaults title-string entity extraction (R6) to WEAK confidence — because that inference risks the same kind of overclaiming Garcia is careful never to commit in his own paperwork-based recovery. This is Garcia's caution, implemented as a technical constraint on Cordell's method.
- **A critique of bibliography's own presuppositions, executed systematically.** The nine-mode metadata-failure taxonomy is, in substance, a Garcia-style argument — that the field's own descriptive categories produced the gaps — but arrived at through a method closer to Cordell's: applied across multiple case studies, generating enrichment operations that scale, rather than through single-object close reading alone.
- **A McKenzie-style production study, already run.** The March 2026 AFAM Print Culture Project proposal ("Reconstructing the Print Shop: Material Production Conditions of African-American Newspapers, 1827–1920") opens by quoting McKenzie directly and applies computational bibliography — typographic fingerprinting, imprint-metadata extraction — to exactly the question Garcia's critique raises: who actually produced the early Black press, and were they dependent on white-owned printing infrastructure or operating autonomously. Its case work traces the *Weekly Anglo-African*'s successor, *Pine and Palm*, to the same probable Boston print shop as Garrison's *Liberator* (221 Washington Street, likely George T. Garrison) — Cordell-style computational method, aimed at a Garcia-style labor-and-autonomy question. This predates the current Cordell/Garcia reading entirely. It isn't a synthesis built to answer this question; it's a synthesis that was already running before the question got posed this way.

## What I'm not claiming

This is not a claim that the synthesis is finished, or that either Cordell or Garcia would endorse this framing of their own work. It's a working hypothesis about where the dissertation's actual contribution sits — worth testing against both of their reactions directly, not asserting as settled.
