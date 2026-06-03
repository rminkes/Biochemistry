# Handoff note — Cell & Molecular Biology study guide

Paste this into the new subject thread, and attach `STUDY-GUIDE-TEMPLATE.md` plus one
finished biochem section file (e.g. `molecular-biology.md`) as a worked example.

---

I'm building comprehensive, high-yield study guides for the basic sciences a medical
student must master by COMLEX Level 1 (end of second year), one subject at a time.
Biochemistry is finished (16 sections, ~134 modules) and served as the pilot.
**Cell & Molecular Biology is the next subject** in the build order.

The authoring spec is in the attached `STUDY-GUIDE-TEMPLATE.md` — follow it exactly. It
defines the philosophy, the per-module YAML schema (including the `flashcards:` field), the
prose layers (Concept / Key facts / Clinical correlation / Differentiating traps / Vignette
signature / Mnemonic / Check), the textbook citation spine, the standing style rules and
errata, the app architecture rules (Section 10), and a running open-decisions tracker
(Section 11). Key conventions to honor from the start: one markdown file per section with
modules grouped inside; single-point Check questions with answers in a per-section answer
key; **5–10 flashcards per module** in the `flashcards:` field, with every answer drawn
from that module's own prose (no outside facts); abbreviations defined at first use within
each module; cross-references between guide sections use section names, not letters; "§"
appears only in textbook citations.

**Carryover from biochemistry:** the biochem molecular-biology section left two
cross-references stubbed out, to be written canonically in *this* subject — (1) cytoskeleton
& motor proteins, and (2) vesicular trafficking. Include full modules for both here.

**App architecture is a settled requirement (Section 10 of the template), don't re-decide
it:** study apps are generated from the `.md` (never hand-authored), and **must persist
per-card progress using a shared, namespaced scheme across all subjects** so a future home
page can aggregate. One sub-decision is still open (localStorage vs. exportable progress
file) — see Section 11; don't default into it.

**Workflow:** First build a coverage checklist for Cell & Molecular Biology (the checklist
is the source of truth for completeness, independent of any single textbook). Then author
section by section — I'll review each batch and say "proceed" before you continue. Verify
large files assembled cleanly and mark the checklist as you go.

**To start:** propose the section structure and draft the coverage checklist for my review
before writing any module content.
