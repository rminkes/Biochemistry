---
course: biochemistry
section: nucleotide-metabolism
section_title: Metabolism — Nucleotides
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, ROBBINS, KATZUNG]
---

# Metabolism — Nucleotides

Section J of the biochem coverage checklist: purine and pyrimidine synthesis and salvage, the
disorders that arise when they fail (Lesch-Nyhan, ADA-deficient SCID, orotic aciduria), and gout.

---

### Purine synthesis & salvage

```yaml
title: Purine synthesis & salvage
category: nucleotide metabolism
system: metabolism
high_yield: true
tags: [purine, PRPP, glutamine-PRPP-amidotransferase, HGPRT, APRT, xanthine-oxidase]
cases: []
flashcards:
  - q: "What molecule do purines start from, and on what scaffold?"
    a: "PRPP (phosphoribosyl pyrophosphate), built on a ribose-5-phosphate scaffold."
  - q: "Rate-limiting enzyme of purine synthesis, and its inhibitors?"
    a: "Glutamine-PRPP amidotransferase; feedback-inhibited by AMP, GMP, and IMP."
  - q: "What does de novo purine synthesis require?"
    a: "Glycine, glutamine, aspartate, CO₂, and tetrahydrofolate-derived carbons (so antifolates inhibit it)."
  - q: "Which salvage enzymes recycle which bases?"
    a: "HGPRT salvages hypoxanthine and guanine; APRT salvages adenine."
  - q: "Which enzyme makes uric acid, and what drugs target it?"
    a: "Xanthine oxidase; targeted by allopurinol and febuxostat."
  - q: "Why does allopurinol potentiate 6-mercaptopurine/azathioprine?"
    a: "Those drugs are normally degraded by xanthine oxidase, which allopurinol inhibits."
  - q: "Trap: de novo vs salvage?"
    a: "De novo builds the ring (on PRPP); salvage recycles free bases."
references:
  - "LIR §Purine synthesis and degradation"   # primary (biochemistry)
```

**Concept.** Purines (adenine, guanine) are built on a ribose-5-phosphate scaffold, starting from
**PRPP (phosphoribosyl pyrophosphate)**. The committed, rate-limiting step is **glutamine-PRPP
amidotransferase**, feedback-inhibited by the end products (AMP, GMP, IMP). De novo synthesis
builds the purine ring directly onto PRPP and needs glycine, glutamine, aspartate, CO₂, and
tetrahydrofolate-derived carbons (so antifolates inhibit it). The **salvage** pathway recycles free
bases: **HGPRT (hypoxanthine-guanine phosphoribosyltransferase)** salvages hypoxanthine and
guanine, while APRT salvages adenine. Purine degradation funnels through xanthine to **uric acid
via xanthine oxidase** — the target of allopurinol and febuxostat. Relevant drugs:
6-mercaptopurine/azathioprine inhibit de novo purine synthesis (and are degraded by xanthine
oxidase, so allopurinol potentiates them); mycophenolate inhibits IMP dehydrogenase.

**Key facts.**
- Purines are built on ribose-5-phosphate, starting from PRPP.
- Rate-limiting: glutamine-PRPP amidotransferase (feedback-inhibited by AMP/GMP/IMP).
- De novo synthesis needs glycine, glutamine, aspartate, CO₂, and tetrahydrofolate.
- Salvage: HGPRT (hypoxanthine/guanine), APRT (adenine).
- Degradation → uric acid via xanthine oxidase (the allopurinol/febuxostat target).

**Clinical correlation.** HGPRT deficiency causes Lesch-Nyhan (next module); xanthine oxidase
inhibitors treat gout; allopurinol potentiates 6-mercaptopurine.

**Differentiating traps.**
- De novo (builds the ring) vs salvage (recycles free bases).
- HGPRT salvages hypoxanthine/guanine; APRT salvages adenine.
- Xanthine oxidase makes uric acid (the drug target).

**Vignette signature.** "Rate-limiting enzyme of purine synthesis" → glutamine-PRPP
amidotransferase. "Enzyme converting xanthine to uric acid" → xanthine oxidase.

**Mnemonic.** "PRPP starts purines; **H**GPRT salvages **H**ypoxanthine & guanine."

**Check.**
1. Which enzyme converts xanthine/hypoxanthine to uric acid (and is the target of allopurinol)?
   *(→ key)*
2. Which salvage enzyme recycles hypoxanthine and guanine? *(→ key)*

---

### Pyrimidine synthesis

```yaml
title: Pyrimidine synthesis
category: nucleotide metabolism
system: metabolism
high_yield: true
tags: [pyrimidine, CPS-II, UMP-synthase, thymidylate-synthase, ribonucleotide-reductase, 5-FU, methotrexate]
cases: []
flashcards:
  - q: "How does pyrimidine assembly differ from purine assembly?"
    a: "The pyrimidine ring is built first, then attached to ribose-5-phosphate (purines build directly on ribose)."
  - q: "Committed step of pyrimidine synthesis?"
    a: "Carbamoyl phosphate synthetase II (CPS-II), cytosolic, using glutamine."
  - q: "Trap: CPS-II vs CPS-I?"
    a: "CPS-II = pyrimidines (cytosol, glutamine); CPS-I = urea cycle (mitochondrial, ammonia)."
  - q: "What converts orotic acid to UMP?"
    a: "UMP synthase."
  - q: "What do thymidylate synthase and ribonucleotide reductase do?"
    a: "Thymidylate synthase makes dTMP from dUMP (regenerating dihydrofolate); ribonucleotide reductase makes deoxyribonucleotides."
  - q: "Match the drug to its target: methotrexate/trimethoprim, 5-fluorouracil, hydroxyurea."
    a: "Methotrexate/trimethoprim → dihydrofolate reductase; 5-FU → thymidylate synthase; hydroxyurea → ribonucleotide reductase."
references:
  - "LIR §Pyrimidine synthesis"   # primary (biochemistry)
```

**Concept.** Pyrimidines (cytosine, thymine, uracil) are made differently from purines: the ring is
built first and then attached to ribose-5-phosphate. The committed step is **carbamoyl phosphate
synthetase II (CPS-II)** in the cytosol, which uses glutamine — contrast **CPS-I** of the urea
cycle (mitochondrial, uses ammonia). **Orotic acid** is an intermediate, converted by **UMP
synthase** to UMP, from which the other pyrimidines form. Thymidylate (dTMP) synthesis requires
**thymidylate synthase** (dUMP → dTMP, regenerating dihydrofolate) and **ribonucleotide reductase**
(makes deoxyribonucleotides). Drug targets: methotrexate and trimethoprim inhibit dihydrofolate
reductase (blocking the folate needed); 5-fluorouracil inhibits thymidylate synthase; hydroxyurea
inhibits ribonucleotide reductase.

**Key facts.**
- Pyrimidine ring is made first, then attached to ribose-5-phosphate.
- Committed step: CPS-II (cytosolic; uses glutamine) — contrast CPS-I (urea, mitochondrial, ammonia).
- Orotic acid → UMP via UMP synthase.
- dUMP → dTMP by thymidylate synthase (regenerates dihydrofolate); ribonucleotide reductase makes
  deoxyribonucleotides.
- Drugs: methotrexate/trimethoprim (dihydrofolate reductase), 5-fluorouracil (thymidylate synthase),
  hydroxyurea (ribonucleotide reductase).

**Clinical correlation.** UMP synthase deficiency causes hereditary orotic aciduria (later module);
the enzymes here are major chemotherapy and antibiotic targets.

**Differentiating traps.**
- CPS-II (pyrimidine, cytosol, glutamine) vs CPS-I (urea, mitochondria, ammonia).
- Ring-first (pyrimidine) vs built-on-ribose (purine).
- 5-fluorouracil → thymidylate synthase; methotrexate → dihydrofolate reductase; hydroxyurea →
  ribonucleotide reductase.

**Vignette signature.** "Committed pyrimidine enzyme using glutamine in the cytosol" → CPS-II.
"Drug inhibiting thymidylate synthase" → 5-fluorouracil.

**Mnemonic.** "Pyrimidines: ring first, CPS-**II** (**C**ytosol, glutamine); purines: ribose first."

**Check.**
1. Which enzyme catalyzes the committed step of pyrimidine synthesis? *(→ key)*
2. Which chemotherapeutic inhibits thymidylate synthase? *(→ key)*

---

### Lesch-Nyhan syndrome

```yaml
title: Lesch-Nyhan syndrome
category: nucleotide metabolism
system: metabolism
enzyme: HGPRT (hypoxanthine-guanine phosphoribosyltransferase)
inheritance: X-linked recessive
high_yield: true
tags: [lesch-nyhan, HGPRT, purine-salvage, hyperuricemia, self-mutilation, gout]
cases: []
flashcards:
  - q: "Which enzyme is deficient in Lesch-Nyhan syndrome, and what is the inheritance?"
    a: "HGPRT (hypoxanthine-guanine phosphoribosyltransferase); X-linked recessive."
  - q: "What metabolic consequence results from HGPRT loss?"
    a: "Failed purine salvage → excess uric acid (hyperuricemia), with de novo synthesis running unchecked."
  - q: "Pathognomonic behavioral feature of Lesch-Nyhan?"
    a: "Self-mutilation (compulsive biting of the lips and fingers)."
  - q: "Other clinical features of Lesch-Nyhan?"
    a: "Intellectual disability, aggression, dystonia/choreoathetosis, gout and uric acid stones."
  - q: "Does allopurinol correct the neurologic features?"
    a: "No — it lowers uric acid but not the CNS disease."
references:
  - "LIR §Purine salvage disorders"   # primary (biochemistry)
```

**Concept.** Lesch-Nyhan syndrome is X-linked recessive *complete* deficiency of **HGPRT
(hypoxanthine-guanine phosphoribosyltransferase)**, the purine salvage enzyme. Without salvage,
purines are degraded to excess **uric acid** (hyperuricemia) and de novo synthesis runs unchecked
(PRPP accumulates). The classic picture: intellectual disability, **self-mutilation** (compulsive
biting of lips and fingers), aggression, and dystonia/choreoathetosis, plus hyperuricemia causing
gout and uric acid stones. Allopurinol lowers the uric acid but does not correct the neurologic
features.

**Key facts.**
- HGPRT deficiency; X-linked recessive; purine salvage fails.
- ↑uric acid (hyperuricemia), gout, uric acid stones; de novo synthesis increases.
- Intellectual disability, self-mutilation, aggression, dystonia/choreoathetosis.
- Treat hyperuricemia with allopurinol (neurologic features persist).

**Clinical correlation.** A boy with self-mutilation, neurologic signs, and hyperuricemia.

**Differentiating traps.**
- HGPRT (salvage enzyme) deficiency; X-linked.
- Self-mutilation is the pathognomonic clue.
- Allopurinol helps the uric acid, not the CNS disease.

**Vignette signature.** "Boy with intellectual disability, self-mutilation (lip/finger biting), and
hyperuricemia/gout" → Lesch-Nyhan.

**Mnemonic.** "Lesch-Nyhan: **H**GPRT gone → **H**e's **G**ot **P**urine **R**ecovery **T**rouble;
self-mutilation, hyperuricemia."

**Check.**
1. Which enzyme is deficient in Lesch-Nyhan syndrome? *(→ key)*
2. What behavioral feature is characteristic of Lesch-Nyhan syndrome? *(→ key)*

---

### ADA deficiency / SCID

```yaml
title: ADA deficiency / SCID
category: nucleotide metabolism
system: metabolism
enzyme: adenosine deaminase
inheritance: autosomal recessive
high_yield: true
tags: [ADA, SCID, deoxyadenosine, dATP, ribonucleotide-reductase, immunodeficiency]
cases: []
flashcards:
  - q: "Which enzyme deficiency causes a major form of SCID, and what is the inheritance?"
    a: "Adenosine deaminase (ADA); autosomal recessive."
  - q: "Mechanism of ADA-deficient SCID?"
    a: "Deoxyadenosine and dATP accumulate; excess dATP inhibits ribonucleotide reductase, blocking DNA synthesis."
  - q: "Why are lymphocytes especially affected in ADA deficiency?"
    a: "They proliferate rapidly, so both B and T cells fail to develop → combined immunodeficiency."
  - q: "Presentation and treatment of ADA-deficient SCID?"
    a: "Recurrent severe infections, failure to thrive, absent thymic shadow; bone marrow transplant is curative (it was the first gene-therapy target)."
  - q: "Vignette: infant with recurrent viral/fungal/bacterial infections, absent thymus, and elevated deoxyadenosine — diagnosis?"
    a: "ADA-deficient SCID."
references:
  - "LIR §Purine metabolism"           # primary (biochemistry)
  - "ROBBINS §Severe combined immunodeficiency"   # cross-reference (immunology/pathology)
```

**Concept.** **Adenosine deaminase (ADA)** deficiency is an autosomal recessive cause of **severe
combined immunodeficiency (SCID)**. ADA normally degrades adenosine and deoxyadenosine; without it,
deoxyadenosine and **dATP** accumulate, and excess dATP **inhibits ribonucleotide reductase**,
blocking DNA synthesis. Rapidly proliferating lymphocytes are especially sensitive, so both B and
T cells fail to develop → SCID. Infants present in the first months with recurrent severe
infections (viral, fungal, bacterial), failure to thrive, and absent lymphoid tissue/thymic shadow.
ADA deficiency is a classic SCID cause (and was the first disease treated with gene therapy); bone
marrow transplant is curative.

**Key facts.**
- ADA (adenosine deaminase) deficiency; AR; a cause of SCID.
- ↑deoxyadenosine/dATP → inhibits ribonucleotide reductase → blocks DNA synthesis.
- Toxic to lymphocytes → failure of B and T cells → SCID.
- Recurrent severe infections, failure to thrive, absent thymic shadow; treat with bone marrow
  transplant (or gene therapy).

**Clinical correlation.** An infant with recurrent infections of all types and absent lymphoid
tissue.

**Differentiating traps.**
- dATP inhibits ribonucleotide reductase (the mechanism).
- Affects both B and T cells (combined immunodeficiency).
- ADA deficiency accounts for roughly half of autosomal recessive SCID.

**Vignette signature.** "Infant with recurrent viral/fungal/bacterial infections, absent thymus,
failure to thrive; elevated deoxyadenosine" → ADA-deficient SCID.

**Mnemonic.** "No ADA → dATP builds → blocks DNA synthesis → no lymphocytes (SCID)."

**Check.**
1. Deficiency of which enzyme causes a major form of severe combined immunodeficiency via purine
   accumulation? *(→ key)*
2. Accumulated dATP in ADA deficiency inhibits which enzyme, blocking DNA synthesis? *(→ key)*

---

### Orotic aciduria (vs OTC deficiency)

```yaml
title: Orotic aciduria (vs OTC deficiency)
category: nucleotide metabolism
system: metabolism
enzyme: UMP synthase
inheritance: autosomal recessive
high_yield: true
tags: [orotic-aciduria, UMP-synthase, megaloblastic-anemia, orotic-acid, uridine, OTC-contrast]
cases: []
flashcards:
  - q: "Which enzyme is deficient in hereditary orotic aciduria, and what is the inheritance?"
    a: "UMP synthase; autosomal recessive."
  - q: "Key findings in hereditary orotic aciduria?"
    a: "Elevated orotic acid, megaloblastic anemia unresponsive to B12/folate, failure to thrive, and no hyperammonemia."
  - q: "Treatment of hereditary orotic aciduria?"
    a: "Oral uridine (it bypasses the block)."
  - q: "Trap: orotic aciduria vs OTC deficiency?"
    a: "Orotic aciduria = megaloblastic anemia, no hyperammonemia (UMP synthase, AR); OTC = hyperammonemia, no anemia (urea cycle, X-linked). Both elevate orotic acid."
  - q: "Vignette: child with megaloblastic anemia unresponsive to B12/folate, elevated orotic acid, and normal ammonia — diagnosis?"
    a: "Hereditary orotic aciduria."
references:
  - "LIR §Pyrimidine synthesis disorders"   # primary (biochemistry)
```

**Concept.** Hereditary orotic aciduria is autosomal recessive deficiency of **UMP synthase**, the
enzyme that converts orotic acid to UMP in pyrimidine synthesis. Orotic acid accumulates and
pyrimidine production fails, so DNA/RNA synthesis is impaired — producing a **megaloblastic anemia
that does NOT respond to vitamin B12 or folate**, along with failure to thrive. The high-yield
contrast is with OTC deficiency (urea cycle): both elevate orotic acid, but **orotic aciduria has
megaloblastic anemia and no hyperammonemia**, whereas **OTC deficiency has hyperammonemia and no
megaloblastic anemia**. Treatment of orotic aciduria is **oral uridine**, which bypasses the block.

**Key facts.**
- UMP synthase deficiency; AR; pyrimidine synthesis fails.
- ↑orotic acid; megaloblastic anemia unresponsive to B12/folate; failure to thrive; no hyperammonemia.
- Treat with oral uridine (bypasses the block).
- Contrast OTC deficiency: ↑orotic acid + hyperammonemia, no megaloblastic anemia.

**Clinical correlation.** A child with megaloblastic anemia not corrected by B12/folate and elevated
orotic acid, *without* hyperammonemia.

**Differentiating traps.**
- Orotic aciduria: megaloblastic anemia, no hyperammonemia (UMP synthase).
- OTC deficiency: hyperammonemia, no megaloblastic anemia (urea cycle).
- The anemia doesn't respond to B12/folate (it's a pyrimidine problem); treat with uridine.

**Vignette signature.** "Child with megaloblastic anemia unresponsive to B12/folate, elevated orotic
acid, and normal ammonia" → hereditary orotic aciduria.

**Mnemonic.** "Orotic aciduria: **O**nly a pyrimidine problem (megaloblastic anemia, no ammonia);
treat with **U**ridine."

**Check.**
1. Which enzyme is deficient in hereditary orotic aciduria? *(→ key)*
2. What distinguishes hereditary orotic aciduria from OTC deficiency? *(→ key)*

**Orotic aciduria vs OTC deficiency**

| Feature | Hereditary orotic aciduria | OTC deficiency |
|---|---|---|
| Defect | UMP synthase (pyrimidine synthesis) | Ornithine transcarbamylase (urea cycle) |
| Orotic acid | Elevated | Elevated |
| Ammonia | Normal | **Elevated (hyperammonemia)** |
| Anemia | **Megaloblastic (B12/folate-unresponsive)** | None |
| Inheritance | Autosomal recessive | X-linked recessive |
| Treatment | Oral uridine | Lower ammonia (low protein, scavengers) |

---

### Gout

```yaml
title: Gout
category: nucleotide metabolism
system: metabolism
high_yield: true
tags: [gout, monosodium-urate, hyperuricemia, podagra, negatively-birefringent, allopurinol, colchicine]
cases: []
flashcards:
  - q: "What causes gout?"
    a: "Hyperuricemia leading to monosodium urate crystal deposition in joints → acute inflammatory arthritis."
  - q: "Crystal morphology and birefringence in gout?"
    a: "Needle-shaped and negatively birefringent (monosodium urate)."
  - q: "Pseudogout crystals vs gout?"
    a: "Pseudogout = rhomboid, positively birefringent calcium pyrophosphate."
  - q: "Most common mechanism of hyperuricemia in gout?"
    a: "Underexcretion (diuretics, alcohol, renal disease); overproduction is the other mechanism."
  - q: "Acute vs chronic gout treatment?"
    a: "Acute — NSAIDs, colchicine, glucocorticoids; chronic urate-lowering — allopurinol/febuxostat (xanthine oxidase), probenecid (uricosuric), rasburicase (uricase)."
  - q: "Vignette: acute painful first-MTP arthritis (podagra) with needle-shaped, negatively birefringent crystals — diagnosis?"
    a: "Gout."
references:
  - "LIR §Purine degradation"        # primary (biochemistry)
  - "KATZUNG §Drugs used in gout"     # cross-reference (pharmacology)
```

**Concept.** Gout results from **hyperuricemia** leading to deposition of **monosodium urate**
crystals in joints, triggering acute inflammatory arthritis. Uric acid is the end product of purine
degradation (via xanthine oxidase). Hyperuricemia arises from **underexcretion** (most common —
renal disease, thiazide/loop diuretics, alcohol) or **overproduction** (high purine turnover —
Lesch-Nyhan, PRPP excess, tumor lysis, high-purine diet). Acute gout is a sudden, exquisitely
painful monoarthritis, classically the first metatarsophalangeal joint (**podagra**). Diagnosis:
**needle-shaped, negatively birefringent** crystals in synovial fluid. (Contrast pseudogout:
rhomboid, *positively* birefringent calcium pyrophosphate crystals.) Treatment: acute — NSAIDs,
colchicine, glucocorticoids; chronic urate-lowering — xanthine oxidase inhibitors
(allopurinol, febuxostat), uricosurics (probenecid), or uricase (rasburicase).

**Key facts.**
- Monosodium urate crystal deposition → acute inflammatory arthritis; uric acid = purine
  degradation end product.
- Causes: underexcretion (diuretics, alcohol, renal disease) or overproduction (Lesch-Nyhan, tumor
  lysis, high purine).
- Acute: podagra (first MTP joint); needle-shaped, negatively birefringent crystals.
- Pseudogout: rhomboid, positively birefringent calcium pyrophosphate.
- Treat: acute (NSAIDs, colchicine, steroids); chronic (allopurinol/febuxostat, probenecid,
  rasburicase).

**Clinical correlation.** A middle-aged patient with acute painful great-toe arthritis, or
hyperuricemia from tumor lysis.

**Differentiating traps.**
- Gout: needle-shaped, **negatively** birefringent (monosodium urate). Pseudogout: rhomboid,
  **positively** birefringent (calcium pyrophosphate).
- Underexcretion is the most common mechanism.
- Colchicine for acute flares; allopurinol for chronic lowering (not started alone mid-flare).

**Vignette signature.** "Acute painful first-MTP arthritis with needle-shaped, negatively
birefringent crystals" → gout.

**Mnemonic.** "Gout: **N**eedle-shaped, **N**egatively birefringent (both N)."

**Check.**
1. What is the crystal morphology and birefringence of gout (monosodium urate)? *(→ key)*
2. What is the most common mechanism of hyperuricemia in gout — overproduction or underexcretion?
   *(→ key)*

---

## Section answer key

**Purine synthesis & salvage**
1. Xanthine oxidase.
2. HGPRT (hypoxanthine-guanine phosphoribosyltransferase).

**Pyrimidine synthesis**
1. Carbamoyl phosphate synthetase II (CPS-II).
2. 5-fluorouracil.

**Lesch-Nyhan syndrome**
1. HGPRT (hypoxanthine-guanine phosphoribosyltransferase).
2. Self-mutilation (compulsive biting of lips and fingers).

**ADA deficiency / SCID**
1. Adenosine deaminase (ADA).
2. Ribonucleotide reductase.

**Orotic aciduria (vs OTC deficiency)**
1. UMP synthase.
2. Orotic aciduria has megaloblastic anemia and *no* hyperammonemia; OTC deficiency has
   hyperammonemia and *no* megaloblastic anemia (both have elevated orotic acid).

**Gout**
1. Needle-shaped and negatively birefringent.
2. Underexcretion.
