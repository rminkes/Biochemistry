---
course: biochemistry
section: carbohydrate-metabolism
section_title: Metabolism — Carbohydrate
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, ROBBINS]
---

# Metabolism — Carbohydrate

Section F of the biochem coverage checklist: the glucose/glycogen core (glycolysis and its
regulation, the PDH complex, gluconeogenesis, glycogen metabolism, and the glycogen storage
diseases), then the alternative dietary sugars and their disorders (fructose, galactose, the
pentose phosphate pathway with G6PD, the sorbitol pathway, and lactase).

---

### Glycolysis

```yaml
title: Glycolysis
category: carbohydrate metabolism
system: metabolism
high_yield: true
tags: [glycolysis, PFK-1, hexokinase, glucokinase, pyruvate-kinase, lactate]
cases: []
flashcards:
  - q: "Net ATP and NADH yield of glycolysis per glucose?"
    a: "Net 2 ATP and 2 NADH (4 ATP made, 2 invested)."
  - q: "Rate-limiting enzyme of glycolysis and its regulators?"
    a: "PFK-1; activated by AMP and fructose-2,6-bisphosphate, inhibited by ATP and citrate."
  - q: "Hexokinase vs glucokinase?"
    a: "Hexokinase = ubiquitous, low Km/high affinity, product-inhibited; glucokinase = liver/β-cells, high Km/low affinity, insulin-induced, a glucose sensor."
  - q: "Which three glycolytic steps are irreversible?"
    a: "Hexokinase/glucokinase, PFK-1, and pyruvate kinase."
  - q: "How is NAD⁺ regenerated under anaerobic conditions?"
    a: "Pyruvate is reduced to lactate by lactate dehydrogenase."
  - q: "Why do red blood cells depend entirely on glycolysis?"
    a: "They lack mitochondria."
  - q: "Vignette: hemolytic anemia from an RBC glycolytic enzyme defect — which enzyme?"
    a: "Pyruvate kinase deficiency."
references:
  - "LIR §Glycolysis"                       # primary (biochemistry)
  - "ROBBINS §Hereditary hemolytic anemias"  # cross-reference (pathology)
```

**Concept.** Glycolysis is the cytosolic pathway that converts one glucose into two pyruvate,
yielding a **net 2 ATP and 2 NADH**, and it runs in essentially every cell — it is the *only*
ATP source for red blood cells, which lack mitochondria. An investment phase spends 2 ATP
(including the hexokinase/glucokinase step that traps glucose as glucose-6-phosphate); a payoff
phase generates 4 ATP and 2 NADH. The committed, rate-limiting step is **phosphofructokinase-1
(PFK-1)**, converting fructose-6-phosphate to fructose-1,6-bisphosphate; it is activated by AMP
and fructose-2,6-bisphosphate (the fed-state signal) and inhibited by ATP and citrate. Glucose
entry differs by tissue: **hexokinase** (most tissues, low Km/high affinity, inhibited by its
product G6P) versus **glucokinase** (liver and pancreatic β-cells, high Km/low affinity, not
product-inhibited, induced by insulin — it acts as a glucose sensor). Anaerobically, pyruvate is
reduced to lactate by lactate dehydrogenase, regenerating NAD⁺ so glycolysis can continue.

**Key facts.**
- Cytosolic; glucose → 2 pyruvate; net 2 ATP, 2 NADH.
- Rate-limiting: PFK-1 (+ AMP/F-2,6-BP; − ATP/citrate).
- Hexokinase (low Km, ubiquitous, product-inhibited) vs glucokinase (high Km, liver/β-cell,
  insulin-induced, glucose sensor).
- Anaerobic: pyruvate → lactate (LDH) regenerates NAD⁺.
- Irreversible steps: hexo-/glucokinase, PFK-1, pyruvate kinase.

**Clinical correlation.** Pyruvate kinase deficiency → hereditary hemolytic anemia (RBCs can't
make ATP). Arsenic inhibits glycolysis (and PDH). RBCs depend entirely on glycolysis.

**Differentiating traps.**
- Glucokinase (liver/β-cells, high Km, glucose sensor) vs hexokinase (everywhere, low Km).
- PFK-1 = rate-limiting; pyruvate kinase and hexokinase are also irreversible.
- Net 2 ATP (4 made, 2 invested) — not 4.

**Vignette signature.** "Hemolytic anemia from an RBC glycolytic enzyme defect" → pyruvate
kinase deficiency. "Liver/β-cell glucose-sensing enzyme" → glucokinase.

**Mnemonic.** "PFK-1 = the **P**ace-setter **F**or glycolysis."

**Check.**
1. What is the rate-limiting enzyme of glycolysis? *(→ key)*
2. A hereditary hemolytic anemia results from deficiency of which glycolytic enzyme (RBCs can't
   generate ATP)? *(→ key)*

---

### PFK-2 / FBPase-2 & fed–fasting regulation

```yaml
title: PFK-2 / FBPase-2 & fed–fasting regulation
category: carbohydrate metabolism
system: metabolism
high_yield: true
tags: [PFK-2, FBPase-2, fructose-2,6-bisphosphate, insulin, glucagon, PKA]
cases: []
flashcards:
  - q: "What is the most potent allosteric activator of PFK-1?"
    a: "Fructose-2,6-bisphosphate (F-2,6-BP)."
  - q: "Which enzyme sets the F-2,6-BP level?"
    a: "The bifunctional PFK-2/FBPase-2."
  - q: "Fed/insulin state — what happens to PFK-2/FBPase-2, and which pathway results?"
    a: "Dephosphorylated → PFK-2 (kinase) active → ↑F-2,6-BP → glycolysis."
  - q: "Fasting/glucagon state — what happens, and which pathway results?"
    a: "PKA phosphorylates it → FBPase-2 (phosphatase) active → ↓F-2,6-BP → gluconeogenesis."
  - q: "Trap: F-2,6-BP vs F-1,6-BP?"
    a: "F-2,6-BP activates glycolysis (via PFK-1); F-1,6-BP is a glycolytic intermediate."
  - q: "Vignette: glucagon, PKA phosphorylation, low F-2,6-BP — which pathway is favored?"
    a: "Gluconeogenesis."
references:
  - "LIR §Regulation of glycolysis and gluconeogenesis"   # primary (biochemistry)
```

**Concept.** In the liver, the choice between glycolysis and gluconeogenesis turns largely on a
single bifunctional enzyme, **PFK-2/FBPase-2**, which sets the level of **fructose-2,6-
bisphosphate (F-2,6-BP)** — the most potent activator of PFK-1. In the fed state, insulin leads
to *dephosphorylation* of the enzyme, activating its PFK-2 (kinase) domain, which makes F-2,6-BP;
F-2,6-BP activates PFK-1, so glycolysis proceeds. In fasting, glucagon raises cAMP and activates
protein kinase A, which *phosphorylates* the enzyme, activating its FBPase-2 (phosphatase)
domain, which degrades F-2,6-BP; with F-2,6-BP gone, PFK-1 shuts off and gluconeogenesis is
favored. One phosphorylation switch thus reciprocally controls the two opposing pathways and
prevents a futile cycle.

**Key facts.**
- PFK-2/FBPase-2 is bifunctional; it sets fructose-2,6-bisphosphate (F-2,6-BP).
- F-2,6-BP is the most potent activator of PFK-1 (drives glycolysis).
- Fed/insulin → dephosphorylated → PFK-2 active → ↑F-2,6-BP → glycolysis.
- Fasting/glucagon → PKA phosphorylates → FBPase-2 active → ↓F-2,6-BP → gluconeogenesis.

**Clinical correlation.** This switch explains the hormonal handoff between fed-state glycolysis
and fasting gluconeogenesis in the liver — central to glucose homeostasis and dysregulated in
diabetes.

**Differentiating traps.**
- F-2,6-BP *activates* glycolysis (via PFK-1) — don't confuse with F-1,6-BP, a glycolytic
  intermediate.
- Glucagon → phosphorylation → FBPase-2 → gluconeogenesis; insulin → dephosphorylation →
  PFK-2 → glycolysis.

**Vignette signature.** "Fed, insulin, high F-2,6-BP" → glycolysis on. "Glucagon, PKA
phosphorylation, low F-2,6-BP" → gluconeogenesis on.

**Mnemonic.** "Fasting → PKA **P**hosphorylates → gluconeogenesis; Fed → dephosphorylated →
glycolysis."

**Check.**
1. Which molecule is the most potent allosteric activator of PFK-1? *(→ key)*
2. In the fasting state, glucagon-driven phosphorylation of PFK-2/FBPase-2 favors which pathway?
   *(→ key)*

---

### Pyruvate dehydrogenase complex

```yaml
title: Pyruvate dehydrogenase complex
category: carbohydrate metabolism
system: metabolism
high_yield: true
tags: [PDH, acetyl-CoA, thiamine, lipoic-acid, arsenic, lactic-acidosis]
cases: []
flashcards:
  - q: "What reaction does the PDH complex catalyze, and where?"
    a: "Pyruvate + CoA + NAD⁺ → acetyl-CoA + CO₂ + NADH (irreversible, mitochondrial)."
  - q: "What are the five cofactors of the PDH complex?"
    a: "TPP (B1), lipoic acid, CoA (B5), FAD (B2), NAD⁺ (B3)."
  - q: "What does PDH deficiency cause, and how is it treated?"
    a: "Lactic acidosis and neurologic deficits from infancy; treat with a ketogenic (high-fat) diet plus lysine and leucine."
  - q: "Which amino acids are the only purely ketogenic ones?"
    a: "Lysine and leucine."
  - q: "What does arsenic inhibit, and what is the presentation?"
    a: "Lipoic acid (so it blocks PDH and α-ketoglutarate dehydrogenase) → lactic acidosis with garlic breath, rice-water stools, neuropathy."
  - q: "Vignette: infant with lactic acidosis and neuro signs who improves on a high-fat diet — deficiency?"
    a: "PDH deficiency."
references:
  - "LIR §Pyruvate dehydrogenase"   # primary (biochemistry)
```

**Concept.** The pyruvate dehydrogenase (PDH) complex links glycolysis to the TCA cycle by
*irreversibly* converting pyruvate to acetyl-CoA in the mitochondrion, releasing CO₂ and making
NADH. It is a large multienzyme complex requiring **five cofactors**, four of them B-vitamin–
derived: thiamine (B1, as TPP), lipoic acid, CoA (B5), FAD (B2), and NAD⁺ (B3). It's activated
by fed/high-demand signals (insulin; and by ADP, Ca²⁺, and pyruvate) and inhibited by its
products (acetyl-CoA, NADH) and by fasting. **PDH deficiency** causes pyruvate to back up into
lactate and alanine, producing lactic acidosis and neurologic impairment from infancy; treatment
favors a ketogenic (high-fat) diet plus lysine and leucine — the only purely ketogenic amino
acids — to supply acetyl-CoA without PDH. **Arsenic** inhibits lipoic acid (so it blocks PDH and
α-ketoglutarate dehydrogenase) → lactic acidosis with garlic breath, rice-water stools, and
neuropathy.

**Key facts.**
- PDH: pyruvate + CoA + NAD⁺ → acetyl-CoA + CO₂ + NADH (irreversible, mitochondrial).
- Cofactors: TPP (B1), lipoic acid, CoA (B5), FAD (B2), NAD⁺ (B3).
- PDH deficiency → lactic acidosis + neuro deficits; treat with ketogenic diet, lysine/leucine.
- Arsenic inhibits lipoic acid (PDH and α-KG dehydrogenase) → lactic acidosis, garlic breath.

**Clinical correlation.** Thiamine deficiency also impairs PDH (and α-KG dehydrogenase,
transketolase), contributing to lactic acidosis and Wernicke encephalopathy (see Nutrition).

**Differentiating traps.**
- PDH shares all five cofactors with α-ketoglutarate dehydrogenase (same mechanism).
- Lysine and leucine are the only *purely* ketogenic amino acids.
- PDH deficiency raises lactate *and* alanine.

**Vignette signature.** "Infant with lactic acidosis and neuro signs who improves on a high-fat
diet" → PDH deficiency. "Lactic acidosis + garlic breath + rice-water stools" → arsenic.

**Mnemonic.** PDH cofactors — "**T**ender **L**oving **C**are **F**or **N**ancy": TPP, Lipoic
acid, CoA, FAD, NAD⁺.

**Check.**
1. Which five cofactors does the pyruvate dehydrogenase complex require? *(→ key)*
2. An infant has lactic acidosis and neurologic deficits and improves on a high-fat ketogenic
   diet. Which enzyme complex is deficient? *(→ key)*

---

### Gluconeogenesis

```yaml
title: Gluconeogenesis
category: carbohydrate metabolism
system: metabolism
high_yield: true
tags: [gluconeogenesis, pyruvate-carboxylase, PEPCK, fructose-1,6-bisphosphatase, glucose-6-phosphatase, cori-cycle]
cases: []
flashcards:
  - q: "What are the gluconeogenic precursors?"
    a: "Lactate, glycerol, and glucogenic amino acids (mainly alanine)."
  - q: "Name the four bypass enzymes of gluconeogenesis."
    a: "Pyruvate carboxylase, PEP carboxykinase (PEPCK), fructose-1,6-bisphosphatase, and glucose-6-phosphatase."
  - q: "Which bypass enzyme is rate-limiting?"
    a: "Fructose-1,6-bisphosphatase."
  - q: "Pyruvate carboxylase — cofactor and activator?"
    a: "Requires biotin; activated by acetyl-CoA (the fasting signal)."
  - q: "Why can only liver and kidney export glucose?"
    a: "Only they express glucose-6-phosphatase; muscle lacks it."
  - q: "What is the Cori cycle?"
    a: "Muscle/RBC lactate returns to the liver to be remade into glucose."
  - q: "Trap: can acetyl-CoA (from fat) become net glucose in humans?"
    a: "No — it activates gluconeogenesis but isn't a substrate; fats don't make net glucose."
references:
  - "LIR §Gluconeogenesis"   # primary (biochemistry)
```

**Concept.** Gluconeogenesis synthesizes glucose from non-carbohydrate precursors — lactate,
glycerol, and glucogenic amino acids (chiefly alanine) — during fasting, mainly in the liver
(and to a lesser extent kidney/intestine). It largely reverses glycolysis but bypasses
glycolysis's three irreversible steps using four enzymes: **pyruvate carboxylase** (pyruvate →
oxaloacetate, mitochondrial, requires biotin, activated by acetyl-CoA), **PEP carboxykinase**
(oxaloacetate → phosphoenolpyruvate), **fructose-1,6-bisphosphatase** (the rate-limiting step),
and **glucose-6-phosphatase** (final step, in the ER of liver/kidney, releasing free glucose).
Because muscle lacks glucose-6-phosphatase, only liver and kidney can export glucose. Lactate
from anaerobic tissues and RBCs returns to the liver to be remade into glucose — the **Cori
cycle**. Fatty acid oxidation supplies the ATP and acetyl-CoA that drive and activate the
pathway, coupling it to fasting and lipolysis.

**Key facts.**
- Precursors: lactate, glycerol, glucogenic amino acids (mainly alanine).
- Four bypass enzymes: pyruvate carboxylase (biotin; + acetyl-CoA), PEPCK,
  fructose-1,6-bisphosphatase (rate-limiting), glucose-6-phosphatase (ER).
- Only liver/kidney export glucose (have glucose-6-phosphatase); muscle cannot.
- Cori cycle: muscle/RBC lactate → liver → glucose.
- Driven and activated by fatty acid oxidation (ATP, acetyl-CoA).

**Clinical correlation.** Glucose-6-phosphatase deficiency = Von Gierke disease (severe fasting
hypoglycemia). Alcohol (high NADH) inhibits gluconeogenesis → fasting hypoglycemia. Biotin
deficiency impairs pyruvate carboxylase.

**Differentiating traps.**
- Pyruvate carboxylase needs biotin and is switched on by acetyl-CoA (the fasting signal).
- Fructose-1,6-bisphosphatase = rate-limiting (the mirror of PFK-1).
- Acetyl-CoA cannot become net glucose in humans — it *activates* gluconeogenesis but isn't a
  substrate (fats don't make glucose).

**Vignette signature.** "Fasting hypoglycemia; the four bypass enzymes" → gluconeogenesis.
"Lactate recycled to glucose in the liver" → Cori cycle.

**Mnemonic.** Bypass enzymes — "**P**athway **P**umps **F**resh **G**lucose": Pyruvate
carboxylase, PEPCK, Fructose-1,6-bisphosphatase, Glucose-6-phosphatase.

**Check.**
1. Which enzyme catalyzes the rate-limiting step of gluconeogenesis? *(→ key)*
2. Why can liver and kidney, but not skeletal muscle, release free glucose into the blood?
   *(→ key)*

---

### Glycogen synthesis & breakdown

```yaml
title: Glycogen synthesis & breakdown
category: carbohydrate metabolism
system: metabolism
high_yield: true
tags: [glycogen, glycogen-synthase, glycogen-phosphorylase, branching-enzyme, debranching-enzyme, cAMP]
cases: []
flashcards:
  - q: "Rate-limiting enzymes of glycogen synthesis vs breakdown?"
    a: "Synthesis = glycogen synthase; breakdown = glycogen phosphorylase."
  - q: "Which linkages do the branching and debranching enzymes act on?"
    a: "The α-1,6 branch points (branching in synthesis, debranching in breakdown); main chains are α-1,4."
  - q: "How do insulin vs glucagon/epinephrine regulate glycogen?"
    a: "Insulin activates synthase/inhibits phosphorylase; glucagon (liver) and epinephrine (muscle) raise cAMP→PKA, activating phosphorylase and inhibiting synthase."
  - q: "What also activates muscle glycogen phosphorylase during exercise?"
    a: "Ca²⁺ and AMP."
  - q: "What product does glycogen phosphorylase release?"
    a: "Glucose-1-phosphate (then converted to glucose-6-phosphate)."
  - q: "Vignette: cAMP/PKA activates glycogen breakdown — which hormones?"
    a: "Glucagon (liver) and epinephrine (muscle)."
references:
  - "LIR §Glycogen metabolism"   # primary (biochemistry)
```

**Concept.** Glycogen is the branched storage polymer of glucose, abundant in liver (to buffer
blood glucose) and muscle (for local energy). **Synthesis:** glucose-6-phosphate → glucose-1-
phosphate → UDP-glucose, with **glycogen synthase** (rate-limiting) adding glucose via α-1,4
linkages and a **branching enzyme** creating α-1,6 branch points. **Breakdown (glycogenolysis):**
**glycogen phosphorylase** (rate-limiting) cleaves α-1,4 bonds to release glucose-1-phosphate,
while a **debranching enzyme** handles the α-1,6 branch points. Regulation is reciprocal and
hormonal: insulin (fed) activates synthase and inhibits phosphorylase; glucagon (liver) and
epinephrine (muscle) raise cAMP → protein kinase A → activate phosphorylase and inhibit synthase.
In muscle, Ca²⁺ and AMP also activate phosphorylase during exercise. Defects in these enzymes
produce the glycogen storage diseases below.

**Key facts.**
- Stored in liver (blood glucose) and muscle (local energy); α-1,4 chains, α-1,6 branches.
- Synthesis: glycogen synthase (rate-limiting, α-1,4) + branching enzyme (α-1,6).
- Breakdown: glycogen phosphorylase (rate-limiting, α-1,4) + debranching enzyme (α-1,6).
- Insulin → synthesis; glucagon/epinephrine (cAMP/PKA) → breakdown.
- Muscle phosphorylase also activated by Ca²⁺/AMP during exercise.

**Clinical correlation.** Enzyme defects cause the glycogen storage diseases (next modules).
Liver vs muscle isoforms explain why some diseases are hepatic and others muscular.

**Differentiating traps.**
- Glycogen synthase (build) vs phosphorylase (break) — reciprocally regulated.
- Branching enzyme (α-1,6 in synthesis) vs debranching enzyme (α-1,6 in breakdown).
- Phosphorylase yields glucose-1-phosphate (then → G6P).

**Vignette signature.** "cAMP/PKA activates glycogen breakdown" → glucagon/epinephrine. "Enzyme
making α-1,6 branch points" → branching enzyme.

**Mnemonic.** "**S**ynthase **S**tores; **P**hosphorylase **P**roduces (frees) glucose."

**Check.**
1. Which enzyme is rate-limiting for glycogen breakdown? *(→ key)*
2. Which second-messenger system does glucagon use to stimulate hepatic glycogenolysis? *(→ key)*

---

### Glycogen storage disease I — Von Gierke

```yaml
title: Glycogen storage disease I — Von Gierke
category: glycogen storage disease
system: metabolism
enzyme: glucose-6-phosphatase
inheritance: autosomal recessive
high_yield: true
tags: [von-gierke, glucose-6-phosphatase, fasting-hypoglycemia, lactic-acidosis, hyperuricemia]
cases: []
flashcards:
  - q: "Deficient enzyme and inheritance in Von Gierke (GSD I)?"
    a: "Glucose-6-phosphatase; autosomal recessive."
  - q: "Why is fasting hypoglycemia severe in Von Gierke?"
    a: "It's the exit step shared by glycogenolysis and gluconeogenesis, so the liver can't release free glucose from either."
  - q: "Classic lab triad of Von Gierke?"
    a: "Lactic acidosis, hyperuricemia (gout), and hyperlipidemia."
  - q: "Physical findings in Von Gierke?"
    a: "Massive hepatomegaly and renomegaly, doll-like face, protuberant abdomen."
  - q: "Which blood finding distinguishes Von Gierke from Cori and McArdle?"
    a: "Elevated lactate (lactic acidosis)."
  - q: "Vignette: infant with severe fasting hypoglycemia, hepatomegaly, lactic acidosis, high uric acid and lipids — diagnosis?"
    a: "Von Gierke disease (GSD I)."
references:
  - "LIR §Glycogen storage diseases"        # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"     # cross-reference (pathology)
```

**Concept.** Von Gierke disease (GSD I) is deficiency of **glucose-6-phosphatase**, the final
shared enzyme of both glycogenolysis and gluconeogenesis. Because the liver can't release free
glucose from either source, patients have **severe fasting hypoglycemia** from infancy. The
blocked glucose-6-phosphate is shunted elsewhere, producing the classic lab triad: lactic
acidosis (G6P → pyruvate → lactate), hyperuricemia (→ gout), and hyperlipidemia. Exam shows
massive hepatomegaly and renomegaly with a doll-like face and protuberant abdomen; glycogen is
normal in structure but excessive. Treatment is frequent feeding and cornstarch to maintain
glucose. Autosomal recessive.

**Key facts.**
- Deficient: glucose-6-phosphatase; AR.
- Severe fasting hypoglycemia (both glycogenolysis and gluconeogenesis blocked at the exit).
- Lactic acidosis, hyperuricemia (gout), hyperlipidemia.
- Hepatomegaly/renomegaly, doll-like face; treat with frequent feeds/cornstarch.

**Clinical correlation.** Distinguished from other GSDs by *elevated lactate* plus high uric
acid and lipids alongside severe hypoglycemia.

**Differentiating traps.**
- Von Gierke = elevated lactate (vs Cori and McArdle, which are normal).
- The defect is at the exit step shared by glycogenolysis and gluconeogenesis.
- Hyperuricemia/gout and hyperlipidemia accompany.

**Vignette signature.** "Infant with severe fasting hypoglycemia, hepatomegaly, lactic acidosis,
high uric acid and lipids" → Von Gierke.

**Mnemonic.** "Von **G**ierke = **G**lucose-6-phosphatase: **G**reat big liver, **G**lucose low."

**Check.**
1. Which enzyme is deficient in Von Gierke disease (GSD I)? *(→ key)*
2. Which blood finding distinguishes Von Gierke from Cori and McArdle? *(→ key)*

---

### Glycogen storage disease II — Pompe

```yaml
title: Glycogen storage disease II — Pompe
category: glycogen storage disease
system: metabolism
enzyme: acid alpha-glucosidase (acid maltase)
inheritance: autosomal recessive
high_yield: true
tags: [pompe, acid-alpha-glucosidase, lysosomal, cardiomegaly, hypotonia, normal-glucose]
cases: []
flashcards:
  - q: "Deficient enzyme in Pompe disease (GSD II)?"
    a: "Lysosomal acid α-glucosidase (acid maltase)."
  - q: "How does Pompe differ from other GSDs with respect to blood glucose?"
    a: "Blood glucose and lactate are normal — the defect is lysosomal, not in cytosolic glucose handling."
  - q: "Hallmark features of infantile Pompe?"
    a: "Massive cardiomegaly, hypotonia (floppy baby), macroglossia; death from heart failure if untreated."
  - q: "Why is Pompe also considered a lysosomal storage disease?"
    a: "It is a lysosomal enzyme defect — glycogen accumulates inside lysosomes."
  - q: "Vignette: floppy infant with cardiomegaly and normal glucose — diagnosis?"
    a: "Pompe disease (GSD II)."
references:
  - "LIR §Glycogen metabolism"             # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"    # cross-reference (pathology)
```

**Concept.** Pompe disease (GSD II) is deficiency of **lysosomal acid α-glucosidase (acid
maltase)**. Unlike the other GSDs, the defect is *lysosomal*, so glycogen accumulates inside
lysosomes rather than disrupting cytosolic glucose handling — **blood glucose and lactate are
normal**. The engorged lysosomes wreck the tissues holding the most glycogen, especially cardiac
and skeletal muscle. The infantile form presents with massive cardiomegaly, hypotonia ("floppy
baby"), macroglossia, and feeding/breathing difficulty, with death from heart failure in the
first year if untreated. Enzyme replacement therapy is available. Autosomal recessive.

**Key facts.**
- Deficient: lysosomal acid α-glucosidase (acid maltase); AR.
- Lysosomal glycogen accumulation; blood glucose and lactate NORMAL.
- Cardiomegaly, hypotonia, macroglossia; infantile death from heart failure.
- Enzyme replacement therapy available.

**Clinical correlation.** Floppy infant + big heart + normal glucose = Pompe. Conceptually it
overlaps the lysosomal storage diseases (it's a lysosomal enzyme defect).

**Differentiating traps.**
- Pompe spares blood glucose (lysosomal, not cytosolic) — unlike Von Gierke and Cori.
- Cardiomegaly is the hallmark.
- It is both a glycogen storage disease and a lysosomal enzyme defect.

**Vignette signature.** "Floppy infant with cardiomegaly and normal glucose" → Pompe.

**Mnemonic.** "**Pompe** trashes the **Pump** (heart)."

**Check.**
1. Which enzyme is deficient in Pompe disease (GSD II)? *(→ key)*
2. How does Pompe differ from the other glycogen storage diseases with respect to blood glucose?
   *(→ key)*

---

### Glycogen storage disease III — Cori

```yaml
title: Glycogen storage disease III — Cori
category: glycogen storage disease
system: metabolism
enzyme: debranching enzyme (alpha-1,6-glucosidase)
inheritance: autosomal recessive
high_yield: true
tags: [cori, debranching-enzyme, limit-dextrin, normal-lactate, mild-hypoglycemia]
cases: []
flashcards:
  - q: "Deficient enzyme in Cori disease (GSD III)?"
    a: "Debranching enzyme (α-1,6-glucosidase)."
  - q: "What abnormal glycogen forms in Cori disease?"
    a: "Glycogen with short outer branches (limit dextrin)."
  - q: "What blood finding distinguishes Cori from Von Gierke?"
    a: "Normal lactate (gluconeogenesis is intact); Von Gierke has elevated lactate."
  - q: "Why is Cori milder than Von Gierke?"
    a: "Gluconeogenesis is intact, so it's recruited normally during fasting."
  - q: "Trap: debranching vs branching enzyme disease?"
    a: "Cori = debranching enzyme (breakdown); Andersen = branching enzyme (synthesis) — both act at α-1,6."
references:
  - "LIR §Glycogen storage diseases"        # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"     # cross-reference (pathology)
```

**Concept.** Cori disease (GSD III) is deficiency of the **debranching enzyme**. Glycogen can be
broken down only as far as the branch points, leaving abnormal glycogen with short outer branches
(**limit dextrin**). Because the straight α-1,4 chains can still be partly mobilized *and
gluconeogenesis is intact*, hypoglycemia is milder than Von Gierke and — the key discriminator —
**blood lactate is normal**. Features: mild fasting hypoglycemia, hepatomegaly, and often muscle
weakness/cardiomyopathy. Autosomal recessive.

**Key facts.**
- Deficient: debranching enzyme (α-1,6-glucosidase); AR.
- Abnormal glycogen with short outer branches (limit dextrin).
- Milder hypoglycemia than Von Gierke; NORMAL lactate (gluconeogenesis intact).
- Hepatomegaly, possible muscle involvement.

**Clinical correlation.** The "normal lactate, milder course" GSD — gluconeogenesis works, so
it's recruited normally during fasting.

**Differentiating traps.**
- Cori = normal lactate (vs Von Gierke's elevated lactate) — the classic discriminator.
- Debranching enzyme (breakdown, α-1,6) vs branching enzyme (Andersen, synthesis, α-1,6).
- Milder than Von Gierke because gluconeogenesis is intact.

**Vignette signature.** "Fasting hypoglycemia + hepatomegaly but NORMAL lactate" → Cori.

**Mnemonic.** "**C**ori = **C**an't debranch; lactate **C**onstant (normal)."

**Check.**
1. Which enzyme is deficient in Cori disease (GSD III)? *(→ key)*
2. What blood finding distinguishes Cori disease from Von Gierke disease? *(→ key)*

---

### Glycogen storage disease IV — Andersen

```yaml
title: Glycogen storage disease IV — Andersen
category: glycogen storage disease
system: metabolism
enzyme: branching enzyme
inheritance: autosomal recessive
high_yield: true
tags: [andersen, branching-enzyme, cirrhosis, liver-failure, amylopectin-like]
cases: []
flashcards:
  - q: "Deficient enzyme in Andersen disease (GSD IV)?"
    a: "Branching enzyme."
  - q: "What abnormal glycogen forms in Andersen disease?"
    a: "Long, unbranched, poorly soluble amylopectin-like glycogen."
  - q: "Characteristic clinical outcome of Andersen disease?"
    a: "Progressive cirrhosis and liver failure in early childhood (often fatal)."
  - q: "Vignette: infant with cirrhosis and liver failure and abnormal unbranched glycogen — diagnosis?"
    a: "Andersen disease (GSD IV)."
references:
  - "LIR §Glycogen storage diseases"        # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"     # cross-reference (pathology)
```

**Concept.** Andersen disease (GSD IV) is deficiency of the **branching enzyme**, so glycogen is
made with very few branches — long, unbranched, poorly soluble chains resembling amylopectin.
This abnormal glycogen is hepatotoxic, causing progressive hepatosplenomegaly, **cirrhosis, and
liver failure** in early childhood, often fatal. Autosomal recessive.

**Key facts.**
- Deficient: branching enzyme; AR.
- Few branches → long, insoluble, amylopectin-like glycogen.
- Progressive cirrhosis and liver failure in early childhood (often fatal).

**Clinical correlation.** Infant with failure to thrive, hepatosplenomegaly, and cirrhosis
progressing to liver failure.

**Differentiating traps.**
- Andersen = branching enzyme (synthesis); Cori = debranching enzyme (breakdown) — opposite
  enzymes, both acting at α-1,6.
- Cirrhosis/liver failure is the hallmark, not primarily hypoglycemia.

**Vignette signature.** "Infant with cirrhosis and liver failure; abnormal unbranched glycogen"
→ Andersen.

**Mnemonic.** "**A**ndersen = **A**bnormal **A**rchitecture (can't branch) → cirrhosis."

**Check.**
1. Which enzyme is deficient in Andersen disease (GSD IV)? *(→ key)*
2. What is the characteristic clinical outcome of Andersen disease? *(→ key)*

---

### Glycogen storage disease V — McArdle

```yaml
title: Glycogen storage disease V — McArdle
category: glycogen storage disease
system: metabolism
enzyme: muscle glycogen phosphorylase (myophosphorylase)
inheritance: autosomal recessive
high_yield: true
tags: [mcardle, myophosphorylase, exercise-intolerance, myoglobinuria, second-wind, normal-glucose]
cases: []
flashcards:
  - q: "Deficient enzyme in McArdle disease (GSD V)?"
    a: "Muscle glycogen phosphorylase (myophosphorylase)."
  - q: "Clinical features of McArdle disease?"
    a: "Exercise intolerance with painful cramps, early fatigue, and myoglobinuria after exertion (rhabdomyolysis risk)."
  - q: "What is the second-wind phenomenon?"
    a: "Symptoms ease after brief rest as the body mobilizes alternative fuels (blood glucose, fatty acids)."
  - q: "What happens to blood glucose and exercise lactate in McArdle?"
    a: "Blood glucose is normal (liver unaffected); venous lactate stays flat with exercise."
  - q: "Trap: McArdle vs Hers disease?"
    a: "McArdle = muscle phosphorylase (GSD V); Hers = liver phosphorylase (GSD VI)."
  - q: "Vignette: exercise cramps, myoglobinuria, second wind, normal glucose, no lactate rise — diagnosis?"
    a: "McArdle disease (GSD V)."
references:
  - "LIR §Glycogen storage diseases"        # primary (biochemistry)
  - "ROBBINS §Glycogen storage diseases"     # cross-reference (pathology)
```

**Concept.** McArdle disease (GSD V) is deficiency of **muscle glycogen phosphorylase
(myophosphorylase)**, so skeletal muscle can't break down its own glycogen for energy during
exercise. Patients have exercise intolerance with painful cramps, early fatigue, and
**myoglobinuria** (red-brown urine) after exertion, risking rhabdomyolysis. A hallmark is the
**"second wind" phenomenon** — symptoms ease after brief rest as the body mobilizes alternative
fuels (blood glucose, fatty acids). Because the liver isoform is unaffected, **blood glucose is
normal** (no hypoglycemia), and because muscle can't make lactate from glycogen, venous lactate
stays flat with exercise. Autosomal recessive.

**Key facts.**
- Deficient: muscle glycogen phosphorylase (myophosphorylase); AR.
- Exercise intolerance, cramps, myoglobinuria (rhabdomyolysis risk).
- "Second wind" phenomenon.
- NORMAL blood glucose (liver unaffected); flat lactate rise with exercise.

**Clinical correlation.** Young adult with exercise-induced cramps and dark urine, normal
glucose, and a "second wind."

**Differentiating traps.**
- McArdle = Muscle phosphorylase (vs Hers, the liver phosphorylase, GSD VI).
- Normal glucose (only muscle affected) — separates it from Von Gierke/Cori.
- Flat lactate with exercise (muscle can't make lactate from its glycogen).

**Vignette signature.** "Exercise-induced cramps, myoglobinuria, second wind, normal glucose, no
lactate rise" → McArdle.

**Mnemonic.** "**McA**rdle = **M**uscle; look for the 'second wind'."

**Check.**
1. Which enzyme is deficient in McArdle disease (GSD V)? *(→ key)*
2. What characteristic exercise phenomenon is seen in McArdle disease? *(→ key)*

**Glycogen storage disease summary**

| GSD | Name | Deficient enzyme | Hypoglycemia | Lactate | Hallmark |
|---|---|---|---|---|---|
| I | Von Gierke | Glucose-6-phosphatase | Severe | ↑ | Hepatomegaly, gout, hyperlipidemia |
| II | Pompe | Acid α-glucosidase (lysosomal) | None (normal) | Normal | Cardiomegaly, hypotonia |
| III | Cori | Debranching enzyme | Mild | Normal | Hepatomegaly, limit dextrin |
| IV | Andersen | Branching enzyme | — | — | Cirrhosis, liver failure |
| V | McArdle | Muscle phosphorylase | None | Flat with exercise | Exercise intolerance, second wind, myoglobinuria |

---

### Fructose metabolism — essential fructosuria

```yaml
title: Fructose metabolism — essential fructosuria
category: carbohydrate metabolism
system: metabolism
enzyme: fructokinase
inheritance: autosomal recessive
high_yield: true
tags: [fructokinase, essential-fructosuria, benign, reducing-sugar]
cases: []
flashcards:
  - q: "Deficient enzyme in essential fructosuria, and is it benign?"
    a: "Fructokinase; benign and asymptomatic."
  - q: "What is found in blood and urine in essential fructosuria?"
    a: "Fructose accumulates and spills into urine (a positive non-glucose reducing sugar)."
  - q: "Why is essential fructosuria harmless?"
    a: "Fructose isn't trapped, so there's no phosphate sequestration or toxicity."
  - q: "Trap: fructokinase vs aldolase B deficiency?"
    a: "Fructokinase = essential fructosuria (benign); aldolase B = hereditary fructose intolerance (dangerous)."
  - q: "Vignette: asymptomatic child with a non-glucose reducing substance in urine — diagnosis?"
    a: "Essential fructosuria."
references:
  - "LIR §Fructose metabolism"   # primary (biochemistry)
```

**Concept.** Dietary fructose is normally handled in the liver by **fructokinase** (fructose →
fructose-1-phosphate), after which **aldolase B** splits fructose-1-phosphate into DHAP and
glyceraldehyde for glycolysis/gluconeogenesis. Essential fructosuria is a **benign** autosomal
recessive deficiency of fructokinase: fructose can't be trapped, so it accumulates in blood and
spills into urine (a positive reducing sugar that isn't glucose) but causes no symptoms — an
asymptomatic, incidental finding. The all-important contrast is with the dangerous deficiency of
the *next* enzyme, aldolase B.

**Key facts.**
- Fructokinase deficiency; AR; benign and asymptomatic.
- Fructose in blood and urine (reducing sugar positive, non-glucose).
- No toxicity — fructose isn't trapped, so no phosphate sequestration.

**Clinical correlation.** Incidental non-glucose reducing sugar in the urine of an otherwise
well child → reassurance only.

**Differentiating traps.**
- Fructokinase (essential fructosuria, benign) vs aldolase B (hereditary fructose intolerance,
  dangerous).
- A urine reducing sugar that isn't glucose → think fructose or galactose.

**Vignette signature.** "Asymptomatic child, non-glucose reducing substance in urine, otherwise
well" → essential fructosuria.

**Mnemonic.** "Fructo**kinase** out → fructose out (in urine), and **F**ine."

**Check.**
1. Which enzyme is deficient in essential fructosuria? *(→ key)*
2. Is essential fructosuria symptomatic or benign? *(→ key)*

---

### Hereditary fructose intolerance

```yaml
title: Hereditary fructose intolerance
category: carbohydrate metabolism
system: metabolism
enzyme: aldolase B
inheritance: autosomal recessive
high_yield: true
tags: [aldolase-B, fructose-1-phosphate, phosphate-depletion, hypoglycemia, weaning]
cases: []
flashcards:
  - q: "Deficient enzyme in hereditary fructose intolerance?"
    a: "Aldolase B (autosomal recessive)."
  - q: "Which metabolite accumulates, and what does it do?"
    a: "Fructose-1-phosphate; it traps inorganic phosphate, depleting phosphate/ATP and inhibiting glycogenolysis and gluconeogenesis → hypoglycemia."
  - q: "When do symptoms begin in hereditary fructose intolerance?"
    a: "When fructose or sucrose is introduced (fruit, juice, sweets — often at weaning)."
  - q: "Clinical features of hereditary fructose intolerance?"
    a: "Hypoglycemia, vomiting, jaundice, hepatomegaly, liver dysfunction (cirrhosis with chronic exposure)."
  - q: "Treatment of hereditary fructose intolerance?"
    a: "Eliminate fructose and sucrose from the diet."
  - q: "Vignette: infant vomits and becomes hypoglycemic and jaundiced after starting fruit/juice — diagnosis?"
    a: "Hereditary fructose intolerance."
references:
  - "LIR §Fructose metabolism"   # primary (biochemistry)
```

**Concept.** Hereditary fructose intolerance is autosomal recessive deficiency of **aldolase B**.
Fructose-1-phosphate accumulates because fructokinase makes it but aldolase B can't cleave it;
this **traps inorganic phosphate**, depleting free phosphate and ATP and inhibiting both
glycogenolysis and gluconeogenesis → **hypoglycemia**. Symptoms begin when fructose or sucrose is
introduced (fruit, juice, sweetened foods — often at weaning): hypoglycemia, vomiting, jaundice,
hepatomegaly, and liver dysfunction, with cirrhosis on chronic exposure. Treatment is dietary
elimination of fructose and sucrose.

**Key facts.**
- Aldolase B deficiency; AR.
- Fructose-1-phosphate accumulates → phosphate/ATP depletion → ↓glycogenolysis & gluconeogenesis
  → hypoglycemia.
- Symptoms appear with fructose/sucrose intake (weaning): vomiting, hypoglycemia, jaundice,
  hepatomegaly.
- Treat by eliminating fructose and sucrose.

**Clinical correlation.** Infant who becomes ill — hypoglycemia, vomiting, jaundice — after the
introduction of fruit or juice.

**Differentiating traps.**
- Aldolase B (dangerous: hypoglycemia, liver) vs fructokinase (benign).
- Phosphate trapping by fructose-1-phosphate is the toxicity mechanism — analogous to
  galactose-1-phosphate in classic galactosemia.
- Symptoms coincide with dietary fructose introduction.

**Vignette signature.** "Infant vomits and becomes hypoglycemic and jaundiced after starting
fruit/juice" → hereditary fructose intolerance.

**Mnemonic.** "Aldolase **B** → **B**ad (hypoglycemia, liver); banish fructose."

**Check.**
1. Which enzyme is deficient in hereditary fructose intolerance? *(→ key)*
2. Which accumulated metabolite causes the phosphate depletion and hypoglycemia? *(→ key)*

---

### Galactose metabolism — classic galactosemia

```yaml
title: Galactose metabolism — classic galactosemia
category: carbohydrate metabolism
system: metabolism
enzyme: galactose-1-phosphate uridyltransferase (GALT)
inheritance: autosomal recessive
high_yield: true
tags: [galactosemia, GALT, galactose-1-phosphate, galactitol, cataracts, e-coli-sepsis]
cases: []
flashcards:
  - q: "Deficient enzyme in classic galactosemia?"
    a: "Galactose-1-phosphate uridyltransferase (GALT); autosomal recessive."
  - q: "What accumulates in classic galactosemia, and what causes the cataracts?"
    a: "Galactose-1-phosphate (toxic, traps phosphate); galactitol (made by aldose reductase) damages the lens → cataracts."
  - q: "Clinical features of classic galactosemia?"
    a: "After milk: failure to thrive, vomiting, jaundice, hepatomegaly, cataracts, intellectual disability."
  - q: "Which infection are infants with classic galactosemia prone to?"
    a: "E. coli neonatal sepsis."
  - q: "Treatment of classic galactosemia?"
    a: "Exclude galactose and lactose from the diet."
  - q: "Vignette: neonate after milk with vomiting, jaundice, hepatomegaly, cataracts, and E. coli sepsis — diagnosis?"
    a: "Classic galactosemia."
references:
  - "LIR §Galactose metabolism"             # primary (biochemistry)
  - "ROBBINS §Inborn errors of metabolism"   # cross-reference (pathology)
```

**Concept.** Dietary galactose (from lactose) is converted to glucose via **galactokinase**
(galactose → galactose-1-phosphate) and then **galactose-1-phosphate uridyltransferase (GALT)**.
Classic galactosemia is autosomal recessive deficiency of GALT: galactose-1-phosphate accumulates
(toxic, traps phosphate) and excess galactose is shunted by aldose reductase to **galactitol**,
damaging the lens. Infants present days after starting breast milk or lactose formula with
failure to thrive, vomiting, jaundice, hepatomegaly, cataracts, and intellectual disability, plus
a characteristic susceptibility to **E. coli neonatal sepsis**. Treatment is exclusion of
galactose and lactose.

**Key facts.**
- GALT deficiency; AR; the severe ("classic") galactosemia.
- Galactose-1-phosphate accumulates (toxic); galactitol → cataracts.
- Infant after milk: failure to thrive, vomiting, jaundice, hepatomegaly, cataracts, intellectual
  disability.
- Predisposes to E. coli neonatal sepsis. Treat by excluding galactose/lactose.

**Clinical correlation.** Neonate with jaundice, hepatomegaly, cataracts, and E. coli sepsis after
milk feeds.

**Differentiating traps.**
- GALT (classic, severe, toxic galactose-1-phosphate) vs galactokinase (mild, mainly cataracts).
- E. coli sepsis is the classic association of classic galactosemia.
- Cataracts (from galactitol) are common to both galactose disorders.

**Vignette signature.** "Neonate after milk: vomiting, jaundice, hepatomegaly, cataracts, E. coli
sepsis" → classic galactosemia.

**Mnemonic.** "Classic galactosemia = **GALT**; gets **E. coli** sepsis."

**Check.**
1. Which enzyme is deficient in classic galactosemia? *(→ key)*
2. Which infection are infants with classic galactosemia particularly prone to? *(→ key)*

---

### Galactokinase deficiency

```yaml
title: Galactokinase deficiency
category: carbohydrate metabolism
system: metabolism
enzyme: galactokinase
inheritance: autosomal recessive
high_yield: true
tags: [galactokinase, galactitol, cataracts, mild]
cases: []
flashcards:
  - q: "Deficient enzyme in galactokinase deficiency, and its severity?"
    a: "Galactokinase; relatively mild."
  - q: "What is essentially the only finding in galactokinase deficiency?"
    a: "Infantile cataracts (from galactitol) — e.g., failure to track or an absent red reflex."
  - q: "Why is there no systemic toxicity in galactokinase deficiency?"
    a: "The toxic galactose-1-phosphate of classic galactosemia is not formed."
  - q: "Trap: galactokinase vs GALT deficiency?"
    a: "Galactokinase = mild, cataracts only; GALT = classic, severe + E. coli sepsis."
references:
  - "LIR §Galactose metabolism"   # primary (biochemistry)
```

**Concept.** Galactokinase deficiency is a milder autosomal recessive galactose disorder:
galactose can't be phosphorylated, so it accumulates and is converted by aldose reductase to
**galactitol**, which osmotically damages the lens → **infantile cataracts** (sometimes noticed
as failure to track or an absent red reflex). Because the toxic galactose-1-phosphate of classic
galactosemia is *not* formed, there is no liver/kidney/brain damage and no E. coli sepsis —
cataracts are essentially the whole picture.

**Key facts.**
- Galactokinase deficiency; AR; relatively mild.
- Galactitol accumulation → cataracts (often the only finding).
- No galactose-1-phosphate buildup → no severe systemic toxicity.

**Clinical correlation.** Infant with cataracts or failure to track but otherwise well after milk.

**Differentiating traps.**
- Galactokinase (mild, cataracts) vs GALT (classic, severe + sepsis).
- Cataracts via galactitol are shared; systemic toxicity is not.

**Vignette signature.** "Infant with cataracts but otherwise healthy" → galactokinase deficiency.

**Mnemonic.** "Galacto**kinase** → **K**ataracts (mainly); kid otherwise okay."

**Check.**
1. Which enzyme deficiency causes a mild galactose disorder with cataracts as essentially the only
   finding? *(→ key)*
2. Which metabolite causes the cataracts in galactose disorders? *(→ key)*

---

### Pentose phosphate pathway (HMP shunt)

```yaml
title: Pentose phosphate pathway (HMP shunt)
category: carbohydrate metabolism
system: metabolism
enzyme: glucose-6-phosphate dehydrogenase (rate-limiting)
high_yield: true
tags: [pentose-phosphate, NADPH, ribose-5-phosphate, G6PD, glutathione]
cases: []
flashcards:
  - q: "What are the two main products of the pentose phosphate pathway, and from which phases?"
    a: "NADPH (oxidative phase, rate-limiting G6PD) and ribose-5-phosphate (nonoxidative phase)."
  - q: "Rate-limiting enzyme of the pentose phosphate pathway?"
    a: "Glucose-6-phosphate dehydrogenase (G6PD)."
  - q: "What are NADPH's main uses?"
    a: "Reductive biosynthesis (fatty acids, cholesterol, steroids), the respiratory burst (NADPH oxidase), cytochrome P450, and regenerating reduced glutathione."
  - q: "Does the pentose phosphate pathway make ATP?"
    a: "No — no ATP is made or consumed."
  - q: "Why is NADPH critical in red blood cells?"
    a: "It regenerates reduced glutathione, the cell's defense against oxidative stress."
  - q: "Trap: oxidative vs nonoxidative phase products?"
    a: "Oxidative (irreversible, G6PD) → NADPH; nonoxidative (reversible) → ribose-5-phosphate."
references:
  - "LIR §Pentose phosphate pathway"   # primary (biochemistry)
```

**Concept.** The pentose phosphate pathway (HMP shunt) runs in the cytosol parallel to glycolysis
but serves *biosynthesis*, not ATP. Its irreversible **oxidative phase** (rate-limiting enzyme
**glucose-6-phosphate dehydrogenase, G6PD**) generates **NADPH**, and its reversible
**nonoxidative phase** generates **ribose-5-phosphate** for nucleotide synthesis. NADPH is needed
for reductive biosynthesis (fatty acids, cholesterol, steroids), the phagocyte respiratory burst
(NADPH oxidase), cytochrome P450, and — critically in red blood cells — regenerating reduced
glutathione, the cell's defense against oxidative stress. No ATP is made or consumed.

**Key facts.**
- Cytosolic; products = NADPH (oxidative phase, rate-limiting G6PD) and ribose-5-phosphate
  (nonoxidative phase).
- NADPH uses: fatty acid/cholesterol/steroid synthesis, respiratory burst, P450, glutathione
  regeneration.
- No ATP produced or consumed.
- Active where reductive synthesis or antioxidant defense is high (liver, adrenal, RBC).

**Clinical correlation.** G6PD deficiency (next module) cripples RBC antioxidant defense. NADPH
oxidase deficiency causes chronic granulomatous disease.

**Differentiating traps.**
- The PPP makes NADPH, not ATP.
- Oxidative phase = NADPH (irreversible, G6PD); nonoxidative phase = ribose-5-phosphate
  (reversible).
- Glutathione regeneration depends on NADPH.

**Vignette signature.** "Pathway supplying NADPH for biosynthesis and antioxidant defense" →
pentose phosphate pathway.

**Mnemonic.** "PPP = **NADPH** + **P**entose (ribose); no ATP."

**Check.**
1. What are the two main products of the pentose phosphate pathway? *(→ key)*
2. Which enzyme is rate-limiting for the pentose phosphate pathway? *(→ key)*

---

### G6PD deficiency

```yaml
title: G6PD deficiency
category: carbohydrate metabolism
system: metabolism
enzyme: glucose-6-phosphate dehydrogenase
inheritance: X-linked recessive
high_yield: true
tags: [G6PD, hemolysis, oxidative-stress, bite-cells, heinz-bodies, primaquine, fava-beans]
cases: []
flashcards:
  - q: "Inheritance of G6PD deficiency, and how common is it?"
    a: "X-linked recessive; the most common human enzyme deficiency."
  - q: "Mechanism of hemolysis in G6PD deficiency?"
    a: "↓NADPH → can't regenerate reduced glutathione → RBCs can't neutralize oxidative stress → episodic hemolysis."
  - q: "Triggers of hemolysis in G6PD deficiency?"
    a: "Oxidant drugs (primaquine, dapsone, sulfonamides, nitrofurantoin), fava beans, and infection (most common)."
  - q: "Smear findings during a G6PD hemolytic episode?"
    a: "Bite cells and Heinz bodies."
  - q: "What is the most common precipitant of hemolysis in G6PD deficiency?"
    a: "Infection."
  - q: "Vignette: episodic hemolysis after sulfa/antimalarial/fava beans with bite cells and Heinz bodies — diagnosis?"
    a: "G6PD deficiency."
references:
  - "LIR §Pentose phosphate pathway"        # primary (biochemistry)
  - "ROBBINS §Hemolytic anemias"             # cross-reference (pathology)
```

**Concept.** Glucose-6-phosphate dehydrogenase deficiency is the **most common human enzyme
deficiency**, **X-linked recessive**, and reduces NADPH production in red blood cells. Without
enough NADPH to regenerate reduced glutathione, RBCs can't neutralize oxidative stress, so oxidant
exposure precipitates **episodic hemolytic anemia**. Triggers: oxidant drugs (primaquine, dapsone,
sulfonamides, nitrofurantoin), fava beans, and infection (the most common trigger). The smear
shows **bite cells** (splenic removal of denatured hemoglobin) and **Heinz bodies** (precipitated
hemoglobin). Hemolysis is usually self-limited as the oldest, most-deficient cells are cleared.
The variant in African populations is milder; the Mediterranean variant is more severe.

**Key facts.**
- G6PD deficiency; X-linked recessive; most common enzymopathy.
- ↓NADPH → ↓reduced glutathione → oxidative hemolysis on trigger.
- Triggers: oxidant drugs (primaquine, dapsone, sulfa, nitrofurantoin), fava beans, infection
  (most common).
- Smear: bite cells and Heinz bodies; episodic, often self-limited.

**Clinical correlation.** Acute hemolysis after an antimalarial, sulfa drug, infection, or fava
beans, classically in a male of Mediterranean, African, or Asian descent. (Confers some malaria
resistance.)

**Differentiating traps.**
- X-linked recessive (mostly affected males).
- Heinz bodies (precipitated Hb) lead to bite cells after the spleen "bites" them out.
- Infection is the most common precipitant.

**Vignette signature.** "Episodic hemolysis after sulfa/antimalarial/fava beans, with bite cells
and Heinz bodies" → G6PD deficiency.

**Mnemonic.** "G6PD: bite a fava bean → **Heinz**-body, **bite-cell** hemolysis."

**Check.**
1. What is the inheritance pattern of G6PD deficiency? *(→ key)*
2. Which two red-cell findings appear on the smear during a hemolytic episode? *(→ key)*

---

### Sorbitol (polyol) pathway

```yaml
title: Sorbitol (polyol) pathway
category: carbohydrate metabolism
system: metabolism
enzyme: aldose reductase
high_yield: true
tags: [sorbitol, aldose-reductase, sorbitol-dehydrogenase, diabetic-complications, galactitol]
cases: []
flashcards:
  - q: "What are the two enzymes of the polyol pathway?"
    a: "Aldose reductase (glucose → sorbitol) and sorbitol dehydrogenase (sorbitol → fructose)."
  - q: "Which tissues trap sorbitol, and why?"
    a: "Lens, retina, kidney, and Schwann cells — they have aldose reductase but little or no sorbitol dehydrogenase."
  - q: "What complications does sorbitol trapping cause in chronic hyperglycemia?"
    a: "Cataracts, peripheral neuropathy, and retinopathy (osmotic damage)."
  - q: "What does aldose reductase make from galactose?"
    a: "Galactitol (the basis of cataracts in the galactose disorders)."
  - q: "Vignette: chronic hyperglycemia causing cataracts/neuropathy via an osmotic sugar alcohol — pathway?"
    a: "The sorbitol/polyol pathway."
references:
  - "LIR §Sorbitol/polyol pathway"   # primary (biochemistry)
```

**Concept.** The polyol pathway converts glucose to **sorbitol** via **aldose reductase**, then
sorbitol to fructose via **sorbitol dehydrogenase**. Tissues that have aldose reductase but little
or no sorbitol dehydrogenase — the lens, retina, kidney, and Schwann cells (nerves) — trap
sorbitol, which is osmotically active and draws in water. In chronic hyperglycemia (diabetes),
this osmotic injury contributes to **cataracts, peripheral neuropathy, and retinopathy**. The same
aldose reductase makes **galactitol** from galactose, the basis of cataracts in the galactose
disorders.

**Key facts.**
- Glucose → sorbitol (aldose reductase) → fructose (sorbitol dehydrogenase).
- Tissues lacking sorbitol dehydrogenase (lens, retina, kidney, Schwann cells) trap sorbitol.
- Osmotic damage in hyperglycemia → cataracts, neuropathy, retinopathy.
- Aldose reductase also makes galactitol (the galactose disorders' cataracts).

**Clinical correlation.** Explains the osmotic complications of chronic diabetes; aldose reductase
inhibitors have been studied for them.

**Differentiating traps.**
- Aldose reductase makes both sorbitol (from glucose) and galactitol (from galactose).
- Tissues *without* sorbitol dehydrogenase accumulate sorbitol and are damaged.

**Vignette signature.** "Chronic hyperglycemia causing cataracts/neuropathy via an osmotic sugar
alcohol" → sorbitol/polyol pathway.

**Mnemonic.** "Aldose reductase traps **S**orbitol in **S**chwann cells (plus lens, retina,
kidney)."

**Check.**
1. Which enzyme converts glucose to sorbitol? *(→ key)*
2. Why do the lens and nerves accumulate sorbitol in hyperglycemia? *(→ key)*

---

### Lactase deficiency

```yaml
title: Lactase deficiency
category: carbohydrate metabolism
system: metabolism
enzyme: lactase (brush-border disaccharidase)
high_yield: true
tags: [lactase, lactose-intolerance, osmotic-diarrhea, disaccharidase, stool-osmotic-gap]
cases: []
flashcards:
  - q: "What does lactase do, and where is it located?"
    a: "A small-intestinal brush-border disaccharidase that splits lactose into glucose and galactose."
  - q: "What type of diarrhea does lactase deficiency cause?"
    a: "Osmotic (low-pH), fermentative diarrhea with bloating and flatulence after dairy."
  - q: "What are the three categories of lactase deficiency?"
    a: "Primary (age-related/hereditary decline), secondary (after intestinal injury — usually reversible), and rare congenital."
  - q: "Stool findings in lactase deficiency?"
    a: "Increased osmotic gap and low pH."
  - q: "Trap: osmotic vs secretory diarrhea with fasting?"
    a: "Osmotic improves with fasting; secretory persists."
references:
  - "LIR §Carbohydrate digestion"   # primary (biochemistry)
```

**Concept.** **Lactase**, a brush-border disaccharidase of the small intestine, splits lactose
into glucose and galactose. Deficiency leaves undigested lactose in the gut lumen, which
osmotically draws in water and is fermented by colonic bacteria → bloating, cramps, flatulence,
and **osmotic (low-pH) diarrhea** after dairy. Causes: a common age-related/hereditary decline in
lactase (primary, especially in non-European populations), secondary loss after intestinal injury
(viral gastroenteritis, celiac disease — usually temporary), or rare congenital deficiency. Stool
shows an increased osmotic gap and low pH. Treatment is reducing lactose or using lactase
supplements.

**Key facts.**
- Lactase (brush-border) splits lactose → glucose + galactose.
- Deficiency → osmotic, fermentative diarrhea, bloating, flatulence after dairy.
- Primary (age-related), secondary (post-gastroenteritis/celiac, reversible), or congenital.
- ↑ stool osmotic gap, low stool pH; lactose reduction/lactase helps.

**Clinical correlation.** Bloating and diarrhea after milk that resolves on a lactose-free diet;
commonly transient after viral gastroenteritis.

**Differentiating traps.**
- Osmotic diarrhea (improves with fasting) vs secretory (persists with fasting).
- Secondary lactase deficiency follows mucosal injury and is reversible.

**Vignette signature.** "Bloating, flatulence, and watery diarrhea after dairy that resolves off
lactose" → lactase deficiency.

**Check.**
1. Which two monosaccharides does lactase produce from lactose? *(→ key)*
2. After viral gastroenteritis a child has transient diarrhea with dairy. Which reversible enzyme
   deficiency explains this? *(→ key)*

---

## Section answer key

**Glycolysis**
1. Phosphofructokinase-1 (PFK-1).
2. Pyruvate kinase.

**PFK-2 / FBPase-2 & fed–fasting regulation**
1. Fructose-2,6-bisphosphate (F-2,6-BP).
2. Gluconeogenesis.

**Pyruvate dehydrogenase complex**
1. TPP (B1), lipoic acid, CoA (B5), FAD (B2), and NAD⁺ (B3).
2. The pyruvate dehydrogenase (PDH) complex.

**Gluconeogenesis**
1. Fructose-1,6-bisphosphatase.
2. Only liver and kidney express glucose-6-phosphatase, the enzyme that frees glucose from
   glucose-6-phosphate; muscle lacks it.

**Glycogen synthesis & breakdown**
1. Glycogen phosphorylase.
2. cAMP → protein kinase A (PKA).

**Glycogen storage disease I — Von Gierke**
1. Glucose-6-phosphatase.
2. Elevated lactate (lactic acidosis).

**Glycogen storage disease II — Pompe**
1. Lysosomal acid α-glucosidase (acid maltase).
2. Blood glucose is normal in Pompe (the defect is lysosomal, not in cytosolic glucose handling).

**Glycogen storage disease III — Cori**
1. Debranching enzyme (α-1,6-glucosidase).
2. Normal lactate (gluconeogenesis is intact), versus elevated lactate in Von Gierke.

**Glycogen storage disease IV — Andersen**
1. Branching enzyme.
2. Progressive cirrhosis and liver failure in early childhood.

**Glycogen storage disease V — McArdle**
1. Muscle glycogen phosphorylase (myophosphorylase).
2. The "second wind" phenomenon.

**Fructose metabolism — essential fructosuria**
1. Fructokinase.
2. Benign (asymptomatic).

**Hereditary fructose intolerance**
1. Aldolase B.
2. Fructose-1-phosphate.

**Galactose metabolism — classic galactosemia**
1. Galactose-1-phosphate uridyltransferase (GALT).
2. E. coli neonatal sepsis.

**Galactokinase deficiency**
1. Galactokinase.
2. Galactitol.

**Pentose phosphate pathway (HMP shunt)**
1. NADPH and ribose-5-phosphate.
2. Glucose-6-phosphate dehydrogenase (G6PD).

**G6PD deficiency**
1. X-linked recessive.
2. Bite cells and Heinz bodies.

**Sorbitol (polyol) pathway**
1. Aldose reductase.
2. They have aldose reductase (making sorbitol) but little/no sorbitol dehydrogenase to clear it,
   so osmotically active sorbitol is trapped.

**Lactase deficiency**
1. Glucose and galactose.
2. Lactase deficiency (secondary, post-infectious — reversible).
