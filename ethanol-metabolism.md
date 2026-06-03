---
course: biochemistry
section: ethanol-metabolism
section_title: Metabolism — Ethanol
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, KATZUNG]
---

# Metabolism — Ethanol

Section K of the biochem coverage checklist: how ethanol is metabolized, the redox shift that
drives its consequences, and the toxic alcohols methanol and ethylene glycol.

---

### Ethanol metabolism

```yaml
title: Ethanol metabolism
category: ethanol metabolism
system: metabolism
high_yield: true
tags: [alcohol-dehydrogenase, acetaldehyde-dehydrogenase, NADH-NAD-ratio, fatty-liver, hypoglycemia, disulfiram, MEOS]
cases: []
flashcards:
  - q: "What are the two enzymes of ethanol metabolism, where are they, and what do they produce?"
    a: "Alcohol dehydrogenase (ADH, cytosol): ethanol → acetaldehyde; acetaldehyde dehydrogenase (ALDH, mitochondria): acetaldehyde → acetate."
  - q: "What is the central metabolic effect of ethanol metabolism?"
    a: "A markedly raised hepatic NADH:NAD⁺ ratio."
  - q: "What consequences follow from the high NADH:NAD⁺ ratio?"
    a: "Pyruvate → lactate (lactic acidosis, and fasting hypoglycemia from impaired gluconeogenesis), increased ketogenesis, and increased triglyceride synthesis (fatty liver)."
  - q: "What is the MEOS, and when does it matter?"
    a: "The microsomal ethanol-oxidizing system (CYP2E1) — significant at high intake and inducible."
  - q: "What enzyme does disulfiram inhibit, and why is it used?"
    a: "Acetaldehyde dehydrogenase (ALDH) — acetaldehyde accumulates, causing an aversive reaction (used in alcohol use disorder)."
  - q: "Trap: which ketone predominates with the high NADH state?"
    a: "β-hydroxybutyrate (over acetoacetate)."
references:
  - "LIR §Ethanol metabolism"            # primary (biochemistry)
  - "KATZUNG §Alcohols and disulfiram"    # cross-reference (pharmacology)
```

**Concept.** Ethanol is metabolized in the liver in two main oxidative steps: **alcohol
dehydrogenase (ADH)** in the cytosol converts ethanol to acetaldehyde, and **acetaldehyde
dehydrogenase (ALDH)** in mitochondria converts acetaldehyde to acetate. Both steps reduce NAD⁺ to
NADH, so ethanol metabolism markedly raises the hepatic **NADH:NAD⁺ ratio** — the key to its
metabolic consequences. (A secondary **microsomal ethanol-oxidizing system, MEOS** (CYP2E1) becomes
significant at high intake and is inducible.) The elevated NADH:NAD⁺ ratio drives pyruvate → lactate
(lactic acidosis, and impaired gluconeogenesis → **fasting hypoglycemia**), depletes oxaloacetate
(further impairing gluconeogenesis and favoring **ketogenesis**), and pushes dihydroxyacetone
phosphate toward glycerol-3-phosphate, promoting triglyceride synthesis → **hepatic steatosis
(fatty liver)**. Acetaldehyde is toxic and contributes to hangover and hepatocyte injury.
Disulfiram inhibits ALDH (acetaldehyde accumulates, an aversive reaction), and genetic ALDH
deficiency (common in East Asian populations) causes flushing.

**Key facts.**
- Liver: ADH (cytosol) ethanol → acetaldehyde; ALDH (mitochondria) acetaldehyde → acetate; both make NADH.
- ↑NADH:NAD⁺ ratio is the central effect.
- Consequences: pyruvate → lactate (lactic acidosis, hypoglycemia), ↓gluconeogenesis, ↑ketogenesis,
  ↑triglyceride (fatty liver).
- MEOS (CYP2E1) is inducible at high intake.
- Disulfiram inhibits ALDH (acetaldehyde accumulation); genetic ALDH deficiency → flushing.

**Clinical correlation.** Alcoholic fasting hypoglycemia, alcoholic ketoacidosis (high
β-hydroxybutyrate), and fatty liver all trace to the NADH:NAD⁺ shift. Disulfiram is used in alcohol
use disorder.

**Differentiating traps.**
- ADH (cytosol; ethanol → acetaldehyde) vs ALDH (mitochondria; acetaldehyde → acetate).
- The NADH:NAD⁺ rise explains hypoglycemia, lactic acidosis, ketoacidosis, and fatty liver together.
- High NADH favors β-hydroxybutyrate over acetoacetate (links to the ketone body module).

**Vignette signature.** "Chronic alcohol use with fasting hypoglycemia, lactic acidosis, and fatty
liver" → the high NADH:NAD⁺ ratio from ethanol metabolism. "Drug inhibiting acetaldehyde
dehydrogenase to cause an aversive reaction" → disulfiram.

**Mnemonic.** "Ethanol → lots of NADH → **L**actate up, **K**etones up, **L**ipid (fatty liver) up,
**G**lucose down."

**Check.**
1. Ethanol metabolism markedly raises which intracellular ratio? *(→ key)*
2. Which enzyme does disulfiram inhibit? *(→ key)*

---

### Toxic alcohols (methanol & ethylene glycol)

```yaml
title: Toxic alcohols (methanol & ethylene glycol)
category: ethanol metabolism
system: metabolism
high_yield: true
tags: [methanol, ethylene-glycol, formic-acid, oxalate, anion-gap-acidosis, fomepizole]
cases: []
flashcards:
  - q: "Which enzyme produces the toxic metabolites of methanol and ethylene glycol?"
    a: "Alcohol dehydrogenase (ADH)."
  - q: "Methanol → which toxic product, and what damage?"
    a: "Formic acid → retinal/optic nerve damage (visual disturbance, blindness)."
  - q: "Ethylene glycol → which toxic product, and what damage?"
    a: "Oxalic acid → calcium oxalate crystals, acute kidney injury, hypocalcemia."
  - q: "What acid-base disturbance do both toxic alcohols cause?"
    a: "A high-anion-gap metabolic acidosis."
  - q: "Treatment for toxic alcohol poisoning, and its mechanism?"
    a: "Fomepizole (preferred), a competitive ADH inhibitor that blocks toxic metabolite formation; ethanol is an alternative; plus dialysis."
references:
  - "LIR §Ethanol metabolism"                    # primary (biochemistry)
  - "KATZUNG §Toxic alcohol poisoning (fomepizole)" # cross-reference (pharmacology/tox)
```

**Concept.** Methanol and ethylene glycol are themselves relatively non-toxic but are metabolized by
**alcohol dehydrogenase (ADH)** (and acetaldehyde dehydrogenase) into toxic products, producing a
**high-anion-gap metabolic acidosis**. Methanol → formaldehyde → **formic acid**, which damages the
retina and optic nerve (visual disturbance, "snowfield" blindness) and causes the acidosis.
Ethylene glycol (antifreeze) → glycolaldehyde → glycolic acid → **oxalic acid**; oxalate
precipitates as **calcium oxalate crystals** in the urine and kidneys, causing acute kidney injury
(and hypocalcemia), with CNS depression and acidosis. Treatment for both: **fomepizole** (preferred),
a competitive inhibitor of alcohol dehydrogenase that blocks formation of the toxic metabolites
(ethanol is an alternative competitor), plus dialysis and supportive care — the clinical payoff of
competitive enzyme inhibition.

**Key facts.**
- Methanol and ethylene glycol → toxic metabolites via alcohol dehydrogenase; high-anion-gap
  metabolic acidosis.
- Methanol → formic acid → optic nerve/retinal damage (blindness).
- Ethylene glycol → oxalic acid → calcium oxalate crystals, acute kidney injury, hypocalcemia.
- Treat: fomepizole (competitive ADH inhibitor; preferred), ethanol as alternative, dialysis.

**Clinical correlation.** Anion-gap acidosis after antifreeze (ethylene glycol → oxalate crystals,
acute kidney injury) or methanol ("moonshine," vision loss); treated with fomepizole.

**Differentiating traps.**
- Methanol → visual symptoms (formic acid, optic nerve); ethylene glycol → renal failure with
  oxalate crystals.
- Fomepizole competitively inhibits alcohol dehydrogenase (links to the enzyme-kinetics module).
- Both cause a high-anion-gap metabolic acidosis.

**Vignette signature.** "Anion-gap acidosis + vision loss after methanol" → formic acid. "Anion-gap
acidosis + calcium oxalate crystals and acute kidney injury after antifreeze" → ethylene glycol.
"Treated with fomepizole" → competitive ADH inhibition.

**Mnemonic.** "Methanol → eyes (blindness); Ethylene glycol → kidneys (oxalate); fomepizole blocks ADH."

**Check.**
1. The toxicity of methanol and ethylene glycol is produced by their metabolism via which enzyme?
   *(→ key)*
2. Which toxic alcohol classically causes calcium oxalate crystals and acute kidney injury? *(→ key)*

---

## Section answer key

**Ethanol metabolism**
1. The NADH:NAD⁺ ratio (markedly increased).
2. Acetaldehyde dehydrogenase (ALDH).

**Toxic alcohols (methanol & ethylene glycol)**
1. Alcohol dehydrogenase (ADH).
2. Ethylene glycol.
