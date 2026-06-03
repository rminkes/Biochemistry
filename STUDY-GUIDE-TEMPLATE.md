---
template_version: 1.0
purpose: Authoring spec + schema for high-yield, comprehensive basic-science study guides
target_exam: COMLEX-USA Level 1 (320 items effective May 2026; pass/fail; ≥11% OPP/OMT)
dual_audience: [first-year foundations course, second-year COMLEX Level 1]
---

# Basic Science Study Guide — Authoring Template

This file is the **style guide and schema** for every basic-science guide in this
project. Upload it into the project instructions so every course thread produces
consistent, app-ready content. It is *not* itself study content — it defines how the
study content is written.

One course = one project thread. The content files are generated in those threads
using the conventions below.

---

## 1. Design philosophy

**Two layers in every module.** Each topic carries a *Foundation layer* (mechanism, for
the first-year course) and a *Board layer* (associations, buzzwords, traps, for COMLEX).
We do not write two guides; we write one guide that serves both readers.

**Comprehensive is verifiable, not a vibe.** Every guide opens with a coverage checklist
(Section 6). Nothing ships until the checklist is complete, so we never accidentally
publish something that is secretly 40% done.

**The markdown is the database.** Every module is structured data from the start (Section
3), so a future reference site or quiz app renders the files directly instead of
requiring a re-authoring pass.

**Original synthesis, cited for navigation.** We write explanations in our own words and
point students to the authoritative textbooks. We never reproduce copyrighted passages
from any cited text.

**Textbook-only reference spine.** References are the standard discipline textbooks
(Section 7) — primary, citable, library-accessible authorities. No QBanks or video
platforms in the citation system; the board-application flavor lives in our own
*Vignette signature* layer, not in a citation.

---

## 2. File organization

- **One file per major section** (e.g., `carbohydrate-metabolism.md`,
  `molecular-biology.md`). Human-readable for the course; small enough to edit and assign.
- **File-level YAML front-matter** describes the section (schema in 3a).
- **Each module** begins with a `### Topic` heading, immediately followed by a fenced
  ```yaml``` metadata block (the module's machine-readable record, schema in 3b), then the
  human-readable layers.
- A parser builds the app by splitting on `### ` headings and reading the yaml fence that
  follows each.

---

## 3. Schema (YAML)

### 3a. File-level front-matter (top of each section file)

```yaml
course: biochemistry          # which basic science
section: carbohydrate-metabolism
section_title: Carbohydrate Metabolism
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, MARKS, THOMPSON]   # keys defined in project instructions
```

### 3b. Per-module metadata block (under each `### Topic` heading)

```yaml
title: Pompe disease (GSD Type II)
category: glycogen storage disease
enzyme: acid alpha-glucosidase (acid maltase)
inheritance: autosomal recessive
chromosome: 17q25
system: carbohydrate metabolism
high_yield: true
tags: [lysosomal, cardiomegaly, hypotonia, normal-glucose]
cases: []                                  # case IDs this module supports (filled later)
flashcards:                                # drill deck for this module (schema + rule in 8)
  - q: "Which enzyme is deficient in Pompe disease?"
    a: "Lysosomal acid α-glucosidase (acid maltase)."
  - q: "Concept → diagnosis: floppy infant + cardiomegaly + normal fasting glucose."
    a: "Pompe disease (GSD Type II)."
references:
  - "LIR §Glycogen metabolism"             # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"   # cross-reference (pathology)
```

Field notes:
- Omit fields that don't apply (a molecular-biology topic has no `enzyme`); don't pad.
- `tags` drive future search/filter — use the buzzwords a student would search.
- `cases` links a module to the foundations-course cases it supports (case-based
  curriculum). Leave `[]` until the case list firms up, then fill in a tagging pass —
  no rewrite needed.
- `flashcards` is the module's drill deck (5–10 self-contained Q/A pairs). Authoring rule
  in Section 8. An app reads this field directly; the module's `tags`/`high_yield`/`system`
  become the deck's filters for free.
- `references` cite by **section name, not page number** (editions repaginate).
- Use the **discipline's primary anchor text** + an optional **cross-discipline text**
  where the topic bridges (e.g., a metabolic disease covered pathologically in Robbins).
  More than two is noise.

**Cross-reference stubs (single source of truth across subjects).** When a topic belongs
to two subjects, write the full module in ONE canonical home and place a one-line *stub*
in the other subject's checklist/guide pointing to it (e.g.,
`See "Cytoskeleton & motor proteins" — Cell & Molecular Biology`). The topic then shows in
both courses' coverage without duplicating the record, so there's nothing to keep in sync.
**Reference cross-references by section *name*, not letter** ("see Chromosomal Syndromes,"
not "see §D") — names survive reorganization and map directly to a file/app link later.
(The `§` in textbook citations like `ROBBINS §DNA repair` is the standard book-section mark
and stays.)

---

## 4. Module template (the repeating unit)

Copy this structure for every topic. Drop any field that genuinely doesn't apply.

```
### [Topic name]

​```yaml
[per-module metadata block per 3b]
​```

**Concept.** 2–5 sentences of prose. The mechanism, *taught* — the Foundation layer.
What a first-year must understand, not just memorize.

**Key facts.** The classic associations: enzyme, cofactor, location, inheritance,
chromosome. One scannable line each.

**Clinical correlation.** The disease the concept produces and the "so what."

**Differentiating traps.** The look-alikes and how to split them. Where COMLEX points are
won or lost.

**Vignette signature.** The buzzwords and how the stem is actually written.
The Board layer.

**Mnemonic.** Only if a strong one exists (see policy, Section 8). Skip otherwise.

**Check.** 1–2 application questions. Answers go in the section answer key, not here.
```

The `flashcards:` block lives in the module's YAML metadata (3b), not in the prose layers —
it's the drill deck an app renders, written per the rule in Section 8.

### Filled example

### Pompe disease (GSD Type II)

```yaml
title: Pompe disease (GSD Type II)
category: glycogen storage disease
enzyme: acid alpha-glucosidase (acid maltase)
inheritance: autosomal recessive
chromosome: 17q25
system: carbohydrate metabolism
high_yield: true
tags: [lysosomal, cardiomegaly, hypotonia, normal-glucose]
flashcards:
  - q: "Which enzyme is deficient in Pompe disease?"
    a: "Lysosomal acid α-glucosidase (acid maltase)."
  - q: "Pompe disease — blood glucose and lactate are characteristically ___."
    a: "Normal (it is a lysosomal problem, not a cytosolic glucose-handling defect)."
  - q: "Which two tissues bear the brunt of damage in infantile Pompe disease?"
    a: "Cardiac and skeletal muscle (massive cardiomegaly, hypotonia)."
  - q: "Concept → diagnosis: floppy infant + enlarged heart + normal fasting glucose."
    a: "Pompe disease (GSD Type II)."
  - q: "Trap: which glycogen storage diseases cause fasting hypoglycemia, unlike Pompe?"
    a: "Von Gierke (G6Pase) and Cori (debrancher); Pompe spares blood glucose."
references:
  - "LIR §Glycogen metabolism"
  - "ROBBINS §Glycogen storage diseases"
```

**Concept.** Lysosomal acid α-glucosidase normally degrades the glycogen that ends up
inside lysosomes. Without it, glycogen accumulates in lysosomes — note this is a
*lysosomal* problem, so unlike Von Gierke and Cori it does **not** disturb blood glucose
or cytoplasmic glycogen handling. The damage is mechanical: engorged lysosomes wreck the
tissues holding the most glycogen — cardiac and skeletal muscle.

**Key facts.** Enzyme: acid α-glucosidase (lysosomal). Inheritance: AR.
Blood glucose & lactate: **normal**.

**Clinical correlation.** Infantile form → massive cardiomegaly, hypotonia ("floppy
baby"), early death from heart failure.

**Differentiating traps.** Von Gierke (G6Pase) and Cori (debrancher) → *fasting
hypoglycemia*; Pompe → *normal glucose* + heart. McArdle → muscle only,
exercise-triggered. The discriminator is **glucose + heart involvement.**

**Vignette signature.** Floppy infant + enlarged heart + normal glucose.

**Mnemonic.** "**Pompe** trashes the **Pump**" (heart).

**Check.** A hypotonic 5-month-old has cardiomegaly but normal fasting glucose and
lactate. Deficient enzyme? *(→ key)*

---

## 5. Section-level structures

Each section file should also include, where useful:

- **Buzzword / differential table** — the strongest at-a-glance asset. (e.g., the
  sphingolipidoses table: enzyme | accumulated substrate | histology buzzword |
  hepatosplenomegaly y/n.)
- **Cumulative quiz** — application questions at the end of the section.
- **Answer key** — separated from the quiz so students can self-test.

---

## 6. Coverage checklist (front matter of each guide)

Each course gets its own checklist. The biochemistry/genetics one below is the working
list (merging the existing draft material with the identified gaps). Check off as written.

**Molecular biology & genetics**
- [ ] DNA replication, repair pathways (NER/MMR/HR), mutations
- [ ] Transcription, post-transcriptional modification, alternative splicing
- [ ] Translation; RNA types; gene silencing (miRNA/siRNA)
- [ ] Lab techniques (blots, PCR/RT-PCR, FISH, microarray)
- [ ] Inheritance patterns (AD/AR/XLR/XLD/mitochondrial)
- [ ] Non-Mendelian: imprinting, anticipation, heteroplasmy, loss of heterozygosity
- [ ] Trinucleotide repeat disorders
- [ ] Population genetics: Hardy-Weinberg, penetrance, expressivity, founder effect
- [ ] Chromosomal syndromes (trisomies, microdeletions, sex aneuploidies)
- [ ] Oncogenes & tumor suppressors (p53, Rb, APC, BRCA, RAS, HER2, BCR-ABL)
- [ ] Pharmacogenetics (G6PD, pseudocholinesterase, NAT acetylation, HLA associations)

**Metabolism**
- [ ] Glycolysis / gluconeogenesis & regulation (PFK-1, PFK-2/FBPase-2)
- [ ] Fructose, galactose, pentose phosphate pathway, sorbitol pathway
- [ ] TCA cycle, ETC / oxidative phosphorylation, inhibitors & uncouplers
- [ ] Glycogen storage diseases
- [ ] Fatty acid synthesis, β-oxidation, ketone metabolism, carnitine deficiency, MCAD
- [ ] Lipid transport & dyslipidemias
- [ ] Amino acid disorders (PKU, alkaptonuria, homocystinuria, MSUD, urea cycle)
- [ ] Purine/pyrimidine metabolism (gout, Lesch-Nyhan, orotic aciduria, ADA/SCID)
- [ ] Ethanol metabolism & its consequences
- [ ] Fed / fasting / starvation integration (insulin–glucagon axis)

**Structural & nutritional**
- [ ] Collagen synthesis & disorders; vitamin C
- [ ] Heme synthesis, porphyrias, lead poisoning
- [ ] Hemoglobinopathies (sickle cell, HbC)
- [ ] Lysosomal storage diseases
- [ ] Vitamins (B-complex, fat-soluble), deficiency/toxicity patterns
- [ ] Protein-calorie malnutrition (marasmus, kwashiorkor)

---

## 7. Reference system (textbooks only)

Define the resource keys **once** here in the project instructions. Modules cite the
**edition-agnostic key + a section-name locator** (e.g., `ROBBINS §Glycogen storage
diseases`) — never an edition number and never a page number. When a new edition ships,
update the one cell in this table; every module locator stays valid.

Each module cites its **discipline's primary anchor** plus, optionally, **one
cross-discipline text** where the topic bridges sciences.

| Key | Resource | Discipline | Current edition |
|---|---|---|---|
| LIR | Lippincott Illustrated Reviews: Biochemistry | Biochemistry | 9th (2024) |
| MARKS | Marks' Basic Medical Biochemistry: A Clinical Approach | Biochemistry | current |
| HARPER | Harper's Illustrated Biochemistry | Biochemistry | current |
| THOMPSON | Thompson & Thompson Genetics in Medicine | Genetics | current |
| GUYTON | Guyton and Hall Textbook of Medical Physiology | Physiology | 15th (2025) |
| MOORE | Moore's Clinically Oriented Anatomy | Anatomy | 9th (2023) |
| LANGMAN | Langman's Medical Embryology | Embryology | 15th (2024) |
| KATZUNG | Katzung's Basic & Clinical Pharmacology | Pharmacology | 16th (2023) |
| PAWLINA | Ross & Pawlina, Histology: A Text and Atlas | Histology | 9th (2024) |
| ROBBINS | Robbins, Cotran & Kumar Pathologic Basis of Disease | Pathology | 11th (2025) |

Notes:
- `MARKS`, `HARPER`, and `THOMPSON` editions are marked "current" pending verification at
  first use in their course thread — confirm and fill the edition then.
- Add a discipline's standard atlas (e.g., Netter for anatomy) as a separate key only if a
  course actually cites images from it.
- Keys are intentionally edition-free so locators never rot. Edition tracking happens only
  in this table.

---

## 8. Style conventions

- **Concept layer** is taught prose, not a fact list — it should read like a good lecture
  paragraph a first-year could learn from.
- **Mnemonic policy:** include established mnemonics freely; new ones may be coined only
  when none exists and the mnemonic is genuinely memorable. Never force one.
- **Mathematical/chemical notation** in readable inline form (e.g., "α-1,4," "Glu→Val at
  position 6").
- **Check questions** test one point each — no compound stems that bundle unrelated facts.
  Keep them vignette-style where natural; answers live in the section answer key.
- **Define non-obvious abbreviations at first use within each module** (modules are
  self-contained records, so each viewable alone — e.g., "CPT-1 (carnitine
  palmitoyltransferase I)"). Universally familiar ones (DNA, ATP, NADH) are exempt.
- **Flashcards (`flashcards:` field).** Each module carries **5–10** drill cards in its
  YAML, as `q:`/`a:` pairs, weighted by the module's density (a thin topic ~5, a rich one
  ~10). Authoring rules: (1) **every answer must already be stated in that module's prose**
  (Concept, Key facts, Differentiating traps, or Vignette signature) — cards reformat the
  module's own content and never introduce outside facts; if an answer isn't findable in
  the module, the card is wrong and is cut; (2) one fact per card, with a **self-contained
  answer** (no "see the answer key"); (3) **weight toward the differentiating traps and
  vignette signatures** — the highest-yield discriminators; (4) card types may vary —
  direct recall, fill-in-the-blank, and *concept → diagnosis* (mirroring the Vignette
  signature). This keeps the deck faithful (no generation drift) and canonical (cards
  travel with the content).
- **Accuracy standard:** the guide is a synthesis; the cited text is the authority. On any
  conflict, defer to the current edition and correct the guide.

### Standing errata (verified corrections to carry forward)
- Sickle cell: Glu→Val at **position 6** of β-globin (mature-protein numbering).
- Hemoglobin C: Glu→Lys at **position 6**.
- Alport: **anterior lenticonus** (lens *dislocation* = Marfan / homocystinuria).
- Oxidative phosphorylation uncoupling: phrase as **high-dose salicylates**.
- Vitamin D deficiency: **low/normal** Ca, low PO₄, high PTH, high ALP.
- Homocystinuria enzyme: **cystathionine β-synthase (CBS)**.

---

## 9. Workflow & roadmap

**Settled rules (decided once, never re-litigated per subject):**
- The template, schema, citation convention, and style rules in this file are fixed.
- **The coverage checklist is the source of truth for completeness — not any single
  textbook.** No textbook is a superset of the others; the anchor + cross-reference fill
  each other's gaps, and the checklist catches anything no book happened to cover.
- "It's in the anchor text" never substitutes for "it's in the guide." Coverage is
  verified against the checklist; sources are cited per claim.

**Per-subject loop (this repeats, but it's light):**
1. Load this template into the subject's project thread (one thread per subject).
2. Draft the subject's **module-level coverage checklist** from the COMLEX blueprint + the
   anchor text's table of contents → review/adjust.
3. Confirm anchor text(s) + current editions → add to the Section 7 table.
4. Write modules against the checklist (the real work).
5. Add section-level buzzword tables, cumulative quiz, and answer key.
6. Review pass.

**Build order (later subjects cross-reference earlier ones):**
Biochemistry (pilot) → cell & molecular biology → histology → anatomy & embryology →
physiology → microbiology & immunology → pharmacology → neuroscience → pathology.
Pathology is last on purpose — Robbins integrates nearly everything before it, so its
modules can cross-link to finished work. Slot OMM/OPP, biostatistics, ethics, and public
health where they fit the curriculum.

**Phases:**
- **Phase 0 — Scaffolding:** this file. Done.
- **Phase 1 — Biochemistry pilot:** build the system end-to-end on one subject to expose
  any template/workflow flaw cheaply before scaling. Finish completely and sign off.
- **Phase 2 — Roll out remaining subjects** in build order, each running the per-subject
  loop. Should go faster than the pilot since the schema is fixed.
- **Phase 3 — Integration (deferred):** static reference site / Anki export / app, decided
  once a real body of structured content exists. The YAML schema already keeps it
  app-ready, so nothing here blocks content work.

---

## 10. App architecture (cross-cutting — applies to every subject)

The structured `.md` files feed study apps (one self-contained HTML per section, content
baked in at build time; the `.md` stays canonical and the HTML is regenerated by a build
script). These rules apply to **every** subject's apps so the system stays coherent across
all nine — decide them once here, never per-subject.

**Settled requirements:**
- **Apps are generated from the `.md`, never hand-authored.** A build script parses the
  modules (prose layers + `flashcards:`) and emits HTML. Content fixes happen in the `.md`;
  the app is regenerated. No forking.
- **Progress must persist** (this is a requirement, not a nice-to-have). A study tool used
  across two years must remember per-card state (seen / got / missed, and any scheduling)
  between sessions. A tool that forgets what you keep missing defeats the point of drilling.
- **Persistence uses a shared, namespaced scheme across all subjects** — keyed so that
  every section app writes to a predictable, common structure (e.g.,
  `subject / section / card-id → state`). This is what lets a future home page aggregate
  ("what am I weak on across *everything*"). Per-app siloed storage is explicitly **not**
  acceptable; it fragments progress across nine subjects.
- **Self-contained + offline + double-click** is the durable shape: no server, no database,
  no install. (A database is overkill for single-user static study content; the YAML *is*
  the data layer.)

**Open sub-decision (resolve before the real multi-section build — do NOT default into it):**
- *Where persistence lives:* browser **localStorage** (zero setup, but per-device — phone
  and laptop don't share — and wiped if browser data is cleared) **vs.** an **exportable
  progress file** the apps read/write (portable across devices, survives browser clears,
  but adds load/save friction). Undecided. Pick deliberately before apps multiply, because
  retrofitting the choice across many section files is painful.

---

## 11. Open decisions & deferred items (running tracker)

This list is the *external memory* for the project — what's settled vs. still open vs.
deliberately deferred. It lives here (not in any one chat) so nothing is lost at a
chat/subject boundary. Update it as decisions are made.

**Open (decide before the real multi-section app build):**
- Persistence storage mechanism: localStorage vs. exportable file (see Section 10).
- Home page / index that links the per-section apps and (eventually) aggregates progress.
  Not built; trivial once several sections exist.
- Tag-filtering for flashcard decks: current `tags` were written for *search*; using them
  for *deck-building* is a slight mismatch (too many hyper-specific tags). Consider a small
  set of curated "theme" tags for drilling, separate from search tags. Flagged from the
  biochem lysosomal pilot.

**Deferred deliberately (revisit later, not now):**
- **Student-facing polish pass (do once, near release — currently author-facing language).**
  A single batched find-and-replace across all section files so the voice is student-ready.
  Bundle these so it's one scoped task, not scattered edits:
  - Replace the "Section X of the [subject] coverage checklist: ..." section intros with
    student-facing framing (e.g., "This section covers ..."). The coverage checklist is an
    internal authoring artifact and won't ship; these references are scaffolding for the build.
  - Convert plain-text "see [Section name]" cross-reference pointers into real links.
  - Harmonize any residual section-letter references to section *names* (per the standing
    "names not letters" rule).
  - The "Cross-reference stubs" heading currently renders as an empty module in the app
    (only affects molecular biology) — drop it or suppress no-YAML headings in the build.
- Multiple-choice / vignette-style quiz mode (flashcards first; MCQ later).
- "Star / bookmark this card" and user-built custom decks (comes with persistence).
- Anki export path (the `flashcards:` field already makes this straightforward when wanted).

**Settled (captured elsewhere, listed here for visibility):**
- Module schema incl. `flashcards:` field and its authoring rule (Sections 3b, 8).
- App architecture + persistence-required rule (Section 10).
- Apps generated from `.md`, never hand-authored (Section 10).
