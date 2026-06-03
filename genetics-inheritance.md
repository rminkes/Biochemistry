---
course: biochemistry
section: genetics-inheritance
section_title: Genetics — Principles & Inheritance
version: 0.1
last_updated: 2026-06-02
resources_used: [THOMPSON, ROBBINS]
---

# Genetics — Principles & Inheritance

Section B of the biochem coverage checklist: how single-gene and non-Mendelian traits are
transmitted, the concepts that blur the genotype–phenotype link, population genetics, and
reading pedigrees.

---

### Mendelian inheritance patterns

```yaml
title: Mendelian inheritance patterns
category: inheritance
system: genetics
high_yield: true
tags: [autosomal-dominant, autosomal-recessive, x-linked-recessive, x-linked-dominant, codominance]
cases: []
flashcards:
  - q: "Autosomal dominant — who is affected and what is the offspring risk?"
    a: "Both sexes, trait in every generation (vertical), ~50% of an affected parent's children; often structural/receptor proteins."
  - q: "Autosomal recessive — transmission pattern and sibling recurrence risk?"
    a: "Two mutant alleles needed; often skips generations with carrier parents; ~25% sibling recurrence; usually enzyme deficiencies."
  - q: "What is the hallmark of X-linked recessive transmission?"
    a: "Mostly affected males through carrier mothers, with no male-to-male transmission."
  - q: "X-linked dominant — how does an affected father transmit it?"
    a: "To all of his daughters and none of his sons."
  - q: "What does codominance mean (with examples)?"
    a: "Both alleles are fully expressed (ABO blood groups, α1-antitrypsin)."
  - q: "Are most enzyme-deficiency disorders dominant or recessive?"
    a: "Recessive (AR); most structural/receptor defects are autosomal dominant."
  - q: "Trap: what does male-to-male transmission tell you?"
    a: "Autosomal inheritance — a father can't pass an X to a son, so it excludes X-linkage."
  - q: "Vignette: unaffected (consanguineous) parents with an affected child — pattern?"
    a: "Autosomal recessive."
  - q: "Vignette: affected father, all daughters affected, no sons — pattern?"
    a: "X-linked dominant."
references:
  - "THOMPSON §Patterns of single-gene inheritance"   # primary (genetics)
```

**Concept.** Classic single-gene disorders transmit predictably based on where the gene sits
and whether one or two defective copies cause disease. **Autosomal dominant (AD):** one mutant
allele suffices; both sexes affected, the trait appears in every generation (vertical
transmission), and ~50% of an affected parent's children inherit it; often structural proteins
or receptors, frequently with delayed onset and variable expression (Huntington, Marfan,
neurofibromatosis, familial hypercholesterolemia). **Autosomal recessive (AR):** two mutant
alleles needed; often skips generations (affected siblings with unaffected carrier parents),
~25% recurrence among siblings; typically enzyme deficiencies (most inborn errors of
metabolism); increased by consanguinity. **X-linked recessive (XLR):** males affected
(hemizygous), females usually carriers; crucially **no male-to-male transmission** (a father
gives sons only his Y); affected males linked through carrier mothers (hemophilia A/B,
Duchenne, G6PD). **X-linked dominant (XLD):** affects both sexes, but an affected father
passes it to *all* daughters and *no* sons; some are male-lethal (hypophosphatemic rickets).
**Codominant:** both alleles fully expressed (ABO blood groups, α1-antitrypsin).

**Key facts.**
- AD: every generation, both sexes, ~50% offspring; often structural/receptor; variable expression.
- AR: skips generations, ~25% sibling recurrence; usually enzymes; consanguinity raises risk.
- XLR: mostly males, carrier mothers; **no male-to-male transmission**.
- XLD: affected father → all daughters, no sons; can be male-lethal.
- Codominance: both alleles expressed (ABO, α1-antitrypsin).

**Clinical correlation.** AD disorders often show incomplete penetrance and variable
expressivity (see Core genetic terms). On a pedigree, "no male-to-male transmission"
separates XLR from AD.

**Differentiating traps.**
- Male-to-male transmission → autosomal (a father can't pass an X to a son), excluding X-linkage.
- AR for most enzyme deficiencies; AD for most structural/receptor defects.
- XLD: affected father → ALL daughters (he gives each his only X), zero sons.

**Vignette signature.** "Trait in every generation, father-to-son transmission" → AD.
"Unaffected parents, affected child, consanguinity" → AR. "Only males affected, through
unaffected mothers" → XLR. "Affected father, all daughters affected, no sons" → XLD.

**Mnemonic.** "**D**ominant → **D**efects in structural proteins; **R**ecessive → **R**educed
enzymes."

**Check.**
1. A pedigree shows a trait passing from an affected father to all of his daughters and none
   of his sons. What inheritance pattern? *(→ key)*
2. Two unaffected first-cousin parents have an affected child. Most likely inheritance
   pattern? *(→ key)*

**Inheritance pattern summary**

| Pattern | Who's affected | Pedigree clue | Examples |
|---|---|---|---|
| Autosomal dominant | Both sexes, every generation | Vertical; male-to-male possible | Huntington, Marfan, NF1, FH |
| Autosomal recessive | Both sexes, skips generations | Horizontal; carrier parents | Most enzyme/metabolic disorders, CF |
| X-linked recessive | Mostly males | No male-to-male; carrier mothers | Hemophilia A/B, Duchenne, G6PD |
| X-linked dominant | Both sexes | Affected father → all daughters, no sons | Hypophosphatemic rickets |
| Mitochondrial | Both sexes | Maternal only (see next module) | Leber, MELAS, MERRF |

---

### Mitochondrial inheritance & heteroplasmy

```yaml
title: Mitochondrial inheritance & heteroplasmy
category: inheritance
system: genetics
high_yield: true
tags: [maternal-inheritance, heteroplasmy, leber, MELAS, MERRF, ragged-red-fibers]
cases: []
flashcards:
  - q: "How are mitochondria inherited, and what is the transmission hallmark?"
    a: "Maternally — an affected mother can pass it to all her children; an affected father passes it to none."
  - q: "What is heteroplasmy?"
    a: "Variable mutant mitochondrial load across cells (mutant and wild-type partition randomly at division), so severity varies between tissues and people."
  - q: "Which tissues are hit hardest in mitochondrial disorders?"
    a: "High-energy tissues — CNS/neurons, muscle, retina, heart."
  - q: "Name classic mitochondrial disorders."
    a: "Leber hereditary optic neuropathy, MELAS, and MERRF (ragged red fibers on biopsy)."
  - q: "What is the risk to the biological children of a father with a mitochondrial disorder?"
    a: "Essentially zero — fathers do not transmit mitochondrial DNA."
  - q: "Vignette: maternal-only transmission, variable severity, sudden bilateral vision loss — diagnosis?"
    a: "Leber hereditary optic neuropathy (mitochondrial)."
references:
  - "THOMPSON §Mitochondrial inheritance"     # primary (genetics)
```

**Concept.** Mitochondria carry their own DNA and are inherited almost entirely from the
mother — the egg supplies the cytoplasm and sperm mitochondria are eliminated — so a mother
with a mitochondrial mutation can pass it to *all* her children, while an affected father
passes it to *none*. That maternal-only pattern is the hallmark. Because each cell has many
mitochondria, a mutation may be present in only some of them (**heteroplasmy**); when cells
divide, mutant and wild-type mitochondria partition randomly, so the mutant load — and thus
disease severity — varies between tissues and family members. High-energy tissues (CNS,
muscle, retina, heart) are hit hardest. Classic disorders: Leber hereditary optic neuropathy
(acute bilateral vision loss), MELAS, and myoclonic epilepsy with ragged red fibers (MERRF).

**Key facts.**
- Maternal inheritance: affected mother → potentially all children; affected father → none.
- Heteroplasmy: variable mutant load → variable severity across cells and people.
- High-energy tissues affected: neurons, muscle, retina.
- Examples: Leber optic neuropathy, MELAS, MERRF (ragged red fibers on biopsy).

**Clinical correlation.** A pedigree in which only mothers transmit, all offspring may be
affected, and severity varies points to mitochondrial inheritance. Muscle biopsy may show
ragged red fibers.

**Differentiating traps.**
- Maternal-only transmission distinguishes mitochondrial from AR and X-linked.
- Heteroplasmy explains intrafamilial variability in severity.
- Fathers never transmit mitochondrial disease.

**Vignette signature.** "Passed only through mothers to all children, variable severity,
sudden bilateral vision loss" → Leber / mitochondrial. "Ragged red fibers" → mitochondrial
myopathy.

**Mnemonic.** "Mitochondria come from **M**om."

**Check.**
1. A father has a mitochondrial disorder. What is the risk to his biological children? *(→ key)*
2. Relatives with the same mitochondrial mutation show widely different severity. What
   concept explains this? *(→ key)*

---

### Genomic imprinting

```yaml
title: Genomic imprinting
category: inheritance
system: genetics
high_yield: true
tags: [imprinting, prader-willi, angelman, uniparental-disomy, methylation]
cases: []
flashcards:
  - q: "What is an imprinted gene?"
    a: "A gene expressed from only one parent's allele; the other is silenced by methylation set during gametogenesis."
  - q: "Which chromosome region underlies Prader-Willi and Angelman syndromes?"
    a: "Chromosome 15q."
  - q: "Prader-Willi results from loss of which parent's contribution?"
    a: "The paternal 15q contribution (paternal deletion or maternal uniparental disomy)."
  - q: "Angelman results from loss of which parent's contribution?"
    a: "The maternal 15q contribution (maternal deletion or paternal uniparental disomy)."
  - q: "What two mechanisms can cause an imprinting disorder?"
    a: "Deletion of the active-parent allele, or uniparental disomy of the silent parent."
  - q: "Trap: Prader-Willi vs Angelman — which parent's loss causes each?"
    a: "Prader-Willi = paternal lost; Angelman = maternal lost (same 15q region)."
references:
  - "THOMPSON §Genomic imprinting"        # primary (genetics)
  - "ROBBINS §Genomic imprinting"          # cross-reference (pathology)
```

**Concept.** For most genes both parental copies are expressed, but **imprinted** genes are
expressed from only one parent's allele, the other silenced by methylation set during
gametogenesis. Disease appears when the single active copy is lost or defective. The classic
locus is chromosome **15q**: lose the paternal contribution (paternal deletion, or maternal
uniparental disomy) and you get **Prader-Willi** (hyperphagia and obesity, hypotonia,
intellectual disability, hypogonadism); lose the maternal contribution (maternal deletion, or
paternal uniparental disomy) and you get **Angelman** ("happy puppet": inappropriate laughter,
ataxic gait, seizures, severe intellectual disability). Same region, opposite parent-of-origin
— a favorite board contrast. (The disease modules themselves live in Chromosomal Syndromes;
this module is the mechanism.)

**Key facts.**
- Imprinted gene = expressed from one parental allele only (other methylated/silenced).
- Chromosome 15q: Prader-Willi (paternal lost) vs Angelman (maternal lost).
- Mechanisms: deletion of the active-parent allele OR uniparental disomy of the silent parent.

**Clinical correlation.** Prader-Willi vs Angelman is the canonical imprinting pair.
Beckwith-Wiedemann (11p15 imprinting; macroglossia, organomegaly, Wilms tumor risk) is another.

**Differentiating traps.**
- Prader-Willi = loss of **paternal**; Angelman = loss of **maternal** — same 15q region.
- Uniparental disomy can cause either, depending on which parent's pair is duplicated.

**Vignette signature.** "Hyperphagia, obesity, hypotonia, paternal 15q deletion" →
Prader-Willi. "Inappropriate laughter, ataxia, seizures, maternal 15q deletion" → Angelman.

**Mnemonic.** "**P**rader = **P**aternal lost; **A**ngelman = m**A**ternal lost."

**Check.**
1. A child with severe obesity, hyperphagia, and hypotonia has a paternal chromosome 15q
   deletion. Diagnosis? *(→ key)*
2. Loss of the maternal 15q contribution produces which syndrome? *(→ key)*

---

### Core genetic terms

```yaml
title: Core genetic terms
category: principles
system: genetics
high_yield: true
tags: [penetrance, expressivity, pleiotropy, anticipation, mosaicism, heterogeneity, dominant-negative]
cases: []
flashcards:
  - q: "What is penetrance?"
    a: "The fraction of people with a genotype who show any phenotype (incomplete penetrance: some carriers look normal, e.g., BRCA)."
  - q: "What is expressivity?"
    a: "How strongly the phenotype shows among those affected (variable expressivity: same genotype, different severity)."
  - q: "What is pleiotropy (with example)?"
    a: "One gene producing multiple unrelated effects (PKU: intellectual disability, eczema, musty odor)."
  - q: "What is anticipation?"
    a: "Earlier onset and greater severity each generation (trinucleotide repeat expansions)."
  - q: "What is mosaicism?"
    a: "Two genetically distinct cell lines in one person from a postzygotic mutation (somatic, e.g., McCune-Albright; or germline)."
  - q: "Locus heterogeneity vs allelic heterogeneity?"
    a: "Locus = different genes causing the same phenotype; allelic = different mutations in the same gene."
  - q: "What is a dominant-negative mutation?"
    a: "A mutant product that interferes with the normal allele's product (some collagen and transcription-factor defects)."
  - q: "Trap: penetrance vs expressivity?"
    a: "Penetrance = whether it shows at all (yes/no); expressivity = how much."
  - q: "Vignette: unaffected parents with several affected children — concept?"
    a: "Germline mosaicism."
references:
  - "THOMPSON §Patterns of single-gene inheritance"   # primary (genetics)
```

**Concept.** Several recurring concepts explain why genotype doesn't map cleanly onto
phenotype. **Penetrance** is the fraction of people with a genotype who show *any* phenotype
(incomplete penetrance: some carriers look normal — e.g., BRCA). **Expressivity** is how
strongly the phenotype shows among those affected (variable expressivity: same genotype,
different severity — e.g., neurofibromatosis). **Pleiotropy** is one gene producing multiple
unrelated effects (PKU: intellectual disability, eczema, musty odor). **Anticipation** is
earlier onset/greater severity each generation (trinucleotide repeats; see Trinucleotide
Repeat & Cancer). **Mosaicism** is two genetically distinct cell lines in one person from a
postzygotic mutation (somatic: McCune-Albright; germline mosaicism explains apparently
unaffected parents with multiple affected children). **Locus heterogeneity** = different genes
causing the same phenotype (albinism, retinitis pigmentosa); **allelic heterogeneity** =
different mutations in the same gene (β-thalassemia). **Dominant negative** = a mutant product
that interferes with the normal allele's product (some collagen and transcription-factor
defects).

**Key facts.**
- Penetrance: % with the genotype who show the phenotype.
- Expressivity: severity among the affected.
- Pleiotropy: one gene, many effects.
- Anticipation: earlier/worse each generation (repeat expansions).
- Mosaicism: two cell lines (somatic vs germline).
- Locus heterogeneity = different genes; allelic heterogeneity = different mutations in one gene.
- Dominant negative: mutant product sabotages the normal product.

**Clinical correlation.** Incomplete penetrance complicates counseling — an "unaffected"
carrier can still transmit. Germline mosaicism explains recurrence in seemingly unaffected
families (osteogenesis imperfecta, Duchenne).

**Differentiating traps.**
- Penetrance (does it show at all?) vs expressivity (how much?).
- Locus heterogeneity (different genes) vs allelic heterogeneity (same gene, different mutations).
- Dominant negative ≠ simple loss of function — the mutant actively interferes.

**Vignette signature.** "Obligate carriers with no phenotype" → incomplete penetrance. "Same
mutation, different severity between relatives" → variable expressivity. "Unaffected parents,
several affected children" → germline mosaicism.

**Mnemonic.** "**Pen**etrance = **Pre**sence (yes/no); **Ex**pressivity = **Ex**tent (how much)."

**Check.**
1. Among people carrying a disease genotype, only 60% ever show any sign of disease. What is
   this called? *(→ key)*
2. Two siblings carry the identical mutation, but one is severely affected and the other
   mildly. What concept explains the difference? *(→ key)*

---

### Loss of heterozygosity & the two-hit hypothesis

```yaml
title: Loss of heterozygosity & the two-hit hypothesis
category: cancer genetics
system: genetics
high_yield: true
tags: [tumor-suppressor, two-hit, knudson, retinoblastoma, loss-of-heterozygosity]
cases: []
flashcards:
  - q: "Why do tumor suppressor genes follow a two-hit model?"
    a: "Both copies must usually be inactivated to release the brake on cell division (Knudson's two-hit hypothesis)."
  - q: "In hereditary cancer, where is the first hit and what is the second?"
    a: "First hit is germline (present in every cell); the second is a somatic loss of heterozygosity at the remaining normal allele."
  - q: "How do hereditary vs sporadic tumor-suppressor cancers present?"
    a: "Hereditary = earlier, often bilateral/multifocal; sporadic = later, usually unilateral (both hits somatic)."
  - q: "What is the prototype two-hit tumor suppressor disorder?"
    a: "Retinoblastoma (RB1)."
  - q: "Tumor suppressors vs oncogenes — how many hits, and what kind of change?"
    a: "Tumor suppressors need two hits (loss of function); oncogenes need one (gain of function)."
  - q: "What is loss of heterozygosity?"
    a: "The second hit that removes the remaining normal allele of a tumor suppressor gene."
  - q: "Vignette: bilateral retinoblastoma in infancy with family history — hereditary or sporadic?"
    a: "Hereditary (germline RB1)."
references:
  - "THOMPSON §Cancer genetics"        # primary (genetics)
  - "ROBBINS §Neoplasia"                # cross-reference (pathology)
```

**Concept.** Tumor suppressor genes restrain cell division, and because *both* copies must
usually be lost to release the brake, they follow Knudson's "two-hit" model. In **sporadic**
cancer, both hits are acquired somatically in a single cell — a rare coincidence, so the
tumor appears late and is usually unifocal. In **hereditary** cancer, the person inherits one
defective allele in every cell (the first hit is germline), so only a single somatic "second
hit" — **loss of heterozygosity** at the remaining normal allele — is needed; tumors appear
earlier and are often bilateral or multifocal. Retinoblastoma (RB1) is the prototype:
hereditary cases are bilateral and early, sporadic cases unilateral and later. The same logic
governs other tumor suppressors (APC, BRCA, NF1, VHL, TP53/Li-Fraumeni).

**Key facts.**
- Tumor suppressors usually require BOTH alleles inactivated (two hits).
- Hereditary: first hit germline → one somatic hit (LOH) → early, bilateral.
- Sporadic: both hits somatic → late, unilateral.
- Retinoblastoma (RB1) is the prototype.

**Clinical correlation.** Bilateral retinoblastoma in an infant signals the hereditary
(germline RB1) form, which also carries later osteosarcoma risk. Contrast with oncogenes,
which need only ONE activated allele (gain of function).

**Differentiating traps.**
- Tumor suppressors: two hits, loss of function (recessive at the cell level).
- Oncogenes: one hit, gain of function (dominant at the cell level).
- Loss of heterozygosity = the second hit removing the remaining normal allele.

**Vignette signature.** "Bilateral retinoblastoma in infancy, family history" → hereditary
RB1, two-hit. "Unilateral retinoblastoma, older child, no family history" → sporadic.

**Mnemonic.** "Tumor suppressors need **Two**; oncogenes need **One**."

**Check.**
1. An infant has bilateral retinoblastoma with a family history. Is this the hereditary or
   sporadic form? *(→ key)*
2. In hereditary retinoblastoma, what is the term for the somatic event that inactivates the
   remaining normal RB1 allele? *(→ key)*

---

### Hardy-Weinberg equilibrium

```yaml
title: Hardy-Weinberg equilibrium
category: population genetics
system: genetics
high_yield: true
tags: [hardy-weinberg, allele-frequency, carrier-frequency, equilibrium]
cases: []
flashcards:
  - q: "What are the two Hardy-Weinberg equations?"
    a: "p + q = 1 and p² + 2pq + q² = 1."
  - q: "In Hardy-Weinberg, what do q² and 2pq represent?"
    a: "q² = homozygous affected (the AR disease frequency); 2pq = heterozygous carriers."
  - q: "How do you get the disease-allele frequency q from an AR disease frequency?"
    a: "q = √(disease frequency), since q² equals the disease frequency."
  - q: "What are the Hardy-Weinberg assumptions?"
    a: "No mutation, no selection, no migration, random mating, and a large population (no drift)."
  - q: "For an X-linked recessive trait, the affected-male frequency equals what?"
    a: "q (males are hemizygous) — which is why X-linked diseases are commoner in males."
  - q: "An AR disease affects 1/10,000 in equilibrium — approximate carrier frequency?"
    a: "~1/50 (q² = 1/10,000 → q = 1/100 → 2pq ≈ 1/50)."
  - q: "Trap: which term is the carrier frequency, q² or 2pq?"
    a: "2pq is carriers; q² is affected."
references:
  - "THOMPSON §Genetics of populations"   # primary (genetics)
```

**Concept.** Hardy-Weinberg estimates allele and genotype frequencies in a population that
isn't evolving. For a two-allele locus with frequencies p (wild-type) and q (disease),
**p + q = 1** and **p² + 2pq + q² = 1**, where p² = homozygous wild-type, 2pq = heterozygous
carriers, and q² = homozygous affected. So for an autosomal recessive disease, q² is the
disease frequency, q is the disease-allele frequency (√q²), and 2pq estimates carrier
frequency. The equilibrium assumes no mutation, no selection, no migration, random mating,
and a large population (no drift) — the board move is to confirm the stem *says* the
population is in equilibrium before applying the formulas. For X-linked recessive traits,
the affected-male frequency equals q (males are hemizygous), which is why X-linked diseases
are commoner in males.

**Key facts.**
- p + q = 1; p² + 2pq + q² = 1.
- q² = affected (AR) frequency; q = √(disease frequency); 2pq = carrier frequency.
- Assumptions: no mutation/selection/migration, random mating, large population.
- X-linked recessive: affected-male frequency = q.

**Clinical correlation.** Used in counseling to estimate carrier risk. If an AR disease
affects 1/10,000, then q² = 1/10,000, q = 1/100, and carrier frequency 2pq ≈ 2(1)(1/100) ≈ 1/50.

**Differentiating traps.**
- 2pq = carriers; q² = affected — don't report q² as the carrier rate.
- Confirm equilibrium is stated before using the formulas.
- For X-linked recessive, affected-male frequency = q (not q²).

**Vignette signature.** "AR disease incidence given; asked for carrier frequency" → q =
√incidence, carriers ≈ 2pq. "Population in equilibrium" is the green light to apply it.

**Mnemonic.** "q² = affected; 2pq = carriers."

**Check.**
1. An autosomal recessive disease affects 1 in 10,000 in an equilibrium population. What is
   the approximate carrier frequency? *(→ key)*
2. In Hardy-Weinberg, which term represents heterozygous carriers? *(→ key)*

---

### Founder effect, consanguinity & genetic drift

```yaml
title: Founder effect, consanguinity & genetic drift
category: population genetics
system: genetics
high_yield: true
tags: [founder-effect, genetic-drift, bottleneck, consanguinity]
cases: []
flashcards:
  - q: "What is the founder effect?"
    a: "A small founding group carries a non-representative slice of alleles, so a rare allele can become relatively common downstream (e.g., Tay-Sachs in Ashkenazi populations)."
  - q: "What is genetic drift, and where is it strongest?"
    a: "Random fluctuation of allele frequencies, strongest in small populations; it includes the bottleneck effect after a population crash."
  - q: "How does consanguinity affect disease risk?"
    a: "It raises the chance two copies of a rare recessive allele meet in one person, increasing autosomal recessive disease risk in offspring."
  - q: "What is the bottleneck effect?"
    a: "A form of genetic drift following a sharp population reduction."
  - q: "Trap: does consanguinity raise recessive or dominant disease risk?"
    a: "Recessive."
  - q: "Vignette: rare recessive disease unusually common in an isolated founder community — concept?"
    a: "Founder effect."
references:
  - "THOMPSON §Genetics of populations"   # primary (genetics)
```

**Concept.** Several forces push real populations away from Hardy-Weinberg expectations. The
**founder effect** occurs when a small group establishes a population while carrying a
non-representative slice of alleles, so a rare allele can become relatively common downstream
(e.g., Tay-Sachs and related disorders in Ashkenazi Jewish populations; specific disorders in
genetically isolated communities). **Genetic drift** is random fluctuation of allele
frequencies, strongest in small populations, and includes the **bottleneck effect** after a
sharp population reduction. **Consanguinity** (mating between relatives) raises the chance
that two copies of a rare recessive allele meet in one person, increasing autosomal recessive
disease risk in offspring. Together these explain why certain recessive diseases cluster in
particular or inbred populations.

**Key facts.**
- Founder effect: small founding group → skewed allele frequencies (Ashkenazi Tay-Sachs).
- Genetic drift: random frequency change, strongest in small populations; bottleneck after a crash.
- Consanguinity: raises autosomal recessive disease risk in offspring.

**Clinical correlation.** Targeted carrier screening in founder populations (Tay-Sachs,
Canavan, Gaucher in Ashkenazi Jewish individuals; sickle cell and β-thalassemia regionally).
Consanguineous unions warrant expanded recessive-disease counseling.

**Differentiating traps.**
- Founder effect (a specific allele enriched in a derived population) vs drift (random) vs
  bottleneck (after a population crash).
- Consanguinity raises *recessive*, not dominant, disease risk.

**Vignette signature.** "Rare recessive disease unusually common in an isolated/founder
population" → founder effect. "First-cousin marriage, child with a rare recessive disease" →
consanguinity.

**Check.**
1. A rare autosomal recessive disease is far more common in a genetically isolated community
   descended from a few settlers. What concept explains this? *(→ key)*
2. Does consanguinity raise the risk of recessive or dominant disease in offspring? *(→ key)*

---

### Pedigree analysis

```yaml
title: Pedigree analysis
category: principles
system: genetics
high_yield: true
tags: [pedigree, inheritance-pattern, male-to-male, recurrence-risk]
cases: []
flashcards:
  - q: "In a pedigree, what do squares, circles, and filled symbols mean?"
    a: "Squares = males, circles = females, filled symbols = affected."
  - q: "What is the single most useful pedigree discriminator?"
    a: "Male-to-male transmission — possible only with autosomal (or Y-linked) inheritance, so it rules out X-linkage."
  - q: "Pedigree: trait in every generation with male-to-male transmission — pattern?"
    a: "Autosomal dominant."
  - q: "Pedigree: affected males only, transmitted through unaffected mothers, no male-to-male — pattern?"
    a: "X-linked recessive."
  - q: "Pedigree: transmission only through mothers to potentially all children — pattern?"
    a: "Mitochondrial."
  - q: "Trap: how can incomplete penetrance mislead pedigree reading?"
    a: "It can make an autosomal dominant pedigree appear to skip a generation."
references:
  - "THOMPSON §Patterns of single-gene inheritance"   # primary (genetics)
```

**Concept.** A pedigree diagrams a family so an inheritance pattern can be read off directly:
squares = males, circles = females, filled symbols = affected, a horizontal line = mating,
verticals = offspring. The reasoning is elimination. A trait in every generation *with*
male-to-male transmission → autosomal dominant. A trait skipping generations with unaffected
carrier parents → autosomal recessive. Mostly affected males transmitted through unaffected
mothers with **no** male-to-male transmission → X-linked recessive. Affected fathers passing
to all daughters and no sons → X-linked dominant. Transmission only through mothers to
potentially all children → mitochondrial. The single most useful discriminator is
**male-to-male transmission**, which is possible only with autosomal (or Y-linked) inheritance
and rules out X-linkage.

**Key facts.**
- Square = male, circle = female; filled = affected.
- Male-to-male transmission → autosomal (rules OUT X-linked).
- AD: vertical, every generation, both sexes.
- AR: horizontal, skips generations, carrier parents.
- XLR: affected males via carrier mothers, no male-to-male.
- XLD: affected father → all daughters, no sons.
- Mitochondrial: maternal only, all offspring at risk.

**Clinical correlation.** Reading pedigrees underlies recurrence-risk counseling. Incomplete
penetrance can make an AD pedigree appear to skip a generation — a classic trap.

**Differentiating traps.**
- Male-to-male transmission is the killer clue for autosomal (excludes X-linked).
- Incomplete penetrance can mimic skipped generations in AD.
- Maternal-only transmission → mitochondrial, not X-linked.

**Vignette signature.** "Affected father and affected son" → autosomal (not X-linked). "Only
males affected, through unaffected mothers" → XLR. "All daughters of an affected man affected,
no sons" → XLD.

**Mnemonic.** "Father-to-son = not on the X."

**Check.**
1. A pedigree shows an affected father and his affected son. Which inheritance patterns does
   this exclude? *(→ key)*
2. A trait appears only in males and is always transmitted through unaffected females. Most
   likely pattern? *(→ key)*

---

## Section answer key

**Mendelian inheritance patterns**
1. X-linked dominant (an affected father transmits his single X to every daughter and no sons).
2. Autosomal recessive (unaffected carrier parents, raised likelihood with consanguinity).

**Mitochondrial inheritance & heteroplasmy**
1. Essentially zero — fathers do not transmit mitochondrial DNA.
2. Heteroplasmy (variable mutant-to-wild-type mitochondrial load across cells/tissues).

**Genomic imprinting**
1. Prader-Willi syndrome (loss of the paternal 15q contribution).
2. Angelman syndrome (loss of the maternal 15q contribution).

**Core genetic terms**
1. Incomplete (reduced) penetrance.
2. Variable expressivity.

**Loss of heterozygosity & the two-hit hypothesis**
1. Hereditary (germline first hit, so bilateral/early disease).
2. Loss of heterozygosity (the second hit).

**Hardy-Weinberg equilibrium**
1. About 1/50 (q² = 1/10,000 → q = 1/100 → 2pq ≈ 2 × 1 × 1/100 ≈ 1/50).
2. 2pq.

**Founder effect, consanguinity & genetic drift**
1. The founder effect.
2. Recessive disease.

**Pedigree analysis**
1. Both X-linked recessive and X-linked dominant (a father transmits his Y, not his X, to a son).
2. X-linked recessive.
