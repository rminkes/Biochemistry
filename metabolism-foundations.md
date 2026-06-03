---
course: biochemistry
section: metabolism-foundations
section_title: Metabolism — Foundations
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, GUYTON, KATZUNG]
---

# Metabolism — Foundations

Section E of the biochem coverage checklist: the regulatory and energetic framework the
pathway sections build on — fed/fasting control, bioenergetics, enzyme kinetics, and the
master map of rate-limiting enzymes.

---

### Metabolism overview — fed, fasting & the insulin/glucagon axis

```yaml
title: Metabolism overview — fed, fasting & the insulin/glucagon axis
category: integration
system: metabolism
high_yield: true
tags: [insulin, glucagon, fed-state, fasting, starvation, ketones, organ-fuel-use]
cases: []
flashcards:
  - q: "What signal chiefly governs fed vs fasting metabolism?"
    a: "The insulin-to-glucagon ratio."
  - q: "In the fed (high-insulin) state, what does the body do?"
    a: "Anabolism — glucose uptake, glycogen synthesis, fatty acid/triglyceride synthesis, and protein synthesis."
  - q: "What is the order of fuel mobilization during fasting?"
    a: "Glycogenolysis (hepatic glycogen lasts ~12–24 h) → gluconeogenesis (lactate, glycerol, glucogenic amino acids) → lipolysis/β-oxidation."
  - q: "What fuels the brain in prolonged starvation, and what does that spare?"
    a: "Ketone bodies; this spares protein (and glucose)."
  - q: "Why can't muscle release free glucose to the blood?"
    a: "It lacks glucose-6-phosphatase, so its glycogen is stored only for itself."
  - q: "Which cells depend solely on glycolysis, and why?"
    a: "Red blood cells — they have no mitochondria."
  - q: "Trap: is it absolute insulin or the ratio that matters?"
    a: "The insulin/glucagon ratio, not absolute insulin."
references:
  - "LIR §Feed/fast cycle (insulin & glucagon)"   # primary (biochemistry)
  - "GUYTON §Insulin, glucagon, and diabetes"      # cross-reference (physiology)
```

**Concept.** Metabolism is governed by fuel status, signaled chiefly by the **insulin-to-
glucagon ratio**. In the **fed (absorptive) state**, high insulin drives anabolism — glucose
uptake, glycogen synthesis, fatty acid/triglyceride synthesis, and protein synthesis — and the
liver stores glucose as glycogen and converts the excess to fat. In the **fasting state**,
falling insulin with rising glucagon (plus epinephrine and cortisol) drives catabolism to keep
blood glucose up: first glycogenolysis (hepatic glycogen lasts ~12–24 h), then gluconeogenesis
(from lactate, glycerol, and glucogenic amino acids), with lipolysis supplying fatty acids for
β-oxidation. In **prolonged starvation**, the body spares protein by shifting to fat-derived
**ketone bodies**, which the brain adopts as its major fuel. Organ specialization matters: the
brain normally runs on glucose (and ketones in starvation), red blood cells depend solely on
glycolysis (no mitochondria), the liver is the metabolic hub (glycogen, gluconeogenesis,
ketogenesis, urea), and muscle stores glycogen only for itself — it lacks glucose-6-phosphatase
and so cannot release free glucose to the blood.

**Key facts.**
- The insulin/glucagon ratio sets fed (anabolic) vs fasting (catabolic) metabolism.
- Fed (high insulin): glycogen, fat, and protein synthesis; glucose uptake.
- Fasting (low insulin, high glucagon): glycogenolysis → gluconeogenesis → lipolysis/β-oxidation.
- Prolonged starvation: ketone bodies fuel the brain, sparing protein and glucose.
- RBCs: glycolysis only; brain: glucose then ketones; muscle: stores glycogen for itself
  (no glucose-6-phosphatase); liver: the hub.

**Clinical correlation.** Diabetic ketoacidosis is essentially an exaggerated fasting/starvation
signal (insulin lack) despite high blood glucose. The muscle glucose-6-phosphatase point
explains why muscle glycogen can't raise blood glucose — relevant to the glycogen storage
diseases.

**Differentiating traps.**
- It's the insulin/glucagon *ratio*, not absolute insulin, that matters.
- Glycogen is the short-term store (hours); fat is the long-term store.
- Muscle lacks glucose-6-phosphatase, so it can't export glucose.

**Vignette signature.** "After an overnight fast, what maintains blood glucose?" →
glycogenolysis (then gluconeogenesis). "Major brain fuel in prolonged starvation" → ketone bodies.

**Mnemonic.** "**I**nsulin = **I**ntake/store; **G**lucagon = **G**o mobilize."

**Check.**
1. After 24+ hours of fasting, hepatic glycogen is largely depleted. Which process now
   maintains blood glucose? *(→ key)*
2. What becomes the brain's major fuel during prolonged starvation? *(→ key)*

---

### Bioenergetics — ATP & electron carriers

```yaml
title: Bioenergetics — ATP & electron carriers
category: integration
system: metabolism
high_yield: true
tags: [ATP, free-energy, NADH, FADH2, NADPH, substrate-level-phosphorylation]
cases: []
flashcards:
  - q: "What is the universal energy currency, and what powers anabolism?"
    a: "ATP; hydrolysis of its terminal phosphoanhydride bonds releases free energy."
  - q: "What does the sign of ΔG indicate?"
    a: "Negative ΔG = spontaneous (exergonic); positive = nonspontaneous (endergonic, must be coupled to ATP)."
  - q: "What do NADH and FADH₂ do?"
    a: "Capture energy from fuel oxidation and deliver electrons to the electron transport chain (oxidative phosphorylation — most ATP)."
  - q: "What is NADPH used for?"
    a: "Reductive biosynthesis (fatty acid, cholesterol, steroid synthesis) and antioxidant defense — not ATP."
  - q: "What are the two ways ATP is generated?"
    a: "Substrate-level phosphorylation (direct phosphate transfer) and oxidative phosphorylation (via the ETC)."
  - q: "Trap: does the ΔG sign tell you reaction speed?"
    a: "No — it indicates spontaneity, not speed (kinetics is separate)."
references:
  - "LIR §Bioenergetics and oxidative phosphorylation"   # primary (biochemistry)
```

**Concept.** Metabolic reactions are coupled so that energy-releasing (catabolic) steps drive
energy-requiring (anabolic) ones, with **ATP** as the universal energy currency: hydrolysis of
its terminal phosphoanhydride bonds releases free energy that powers otherwise unfavorable
reactions. Whether a reaction proceeds is set by the change in free energy (ΔG) — negative ΔG is
spontaneous (exergonic), positive is nonspontaneous (endergonic, and must be coupled to ATP).
The reduced electron carriers **NADH and FADH₂** capture energy from fuel oxidation and deliver
electrons to the electron transport chain, where most ATP is made (oxidative phosphorylation).
**NADPH** is a related but distinct carrier used for *reductive biosynthesis* (fatty acid,
cholesterol, and steroid synthesis) and antioxidant defense — it is not used to make ATP. ATP
itself is generated two ways: **substrate-level phosphorylation** (direct phosphate transfer,
as in glycolysis and the TCA cycle) and **oxidative phosphorylation** (the bulk, via the ETC).

**Key facts.**
- ATP = energy currency; phosphoanhydride-bond hydrolysis powers anabolism.
- ΔG: negative = spontaneous (exergonic); positive = needs coupling (endergonic).
- NADH and FADH₂ feed the ETC → oxidative phosphorylation (most ATP).
- NADPH = reductive biosynthesis + antioxidant defense (not ATP).
- ATP made by substrate-level phosphorylation and oxidative phosphorylation.

**Clinical correlation.** Cyanide, CO, and uncouplers cripple oxidative phosphorylation (see
the ETC module). NADPH from the pentose phosphate pathway protects RBCs from oxidative damage —
its lack in G6PD deficiency causes hemolysis.

**Differentiating traps.**
- NADH/FADH₂ (catabolism, ATP) vs NADPH (anabolism/antioxidant) — distinct roles.
- Substrate-level phosphorylation (direct) vs oxidative phosphorylation (ETC-driven).
- ΔG sign indicates spontaneity, not reaction speed (kinetics is separate).

**Vignette signature.** "Carrier used for fatty acid synthesis and glutathione regeneration" →
NADPH. "ATP made directly during a metabolic step, without the ETC" → substrate-level
phosphorylation.

**Mnemonic.** "NADPH for **P**roduction (biosynthesis) and **P**rotection (antioxidant)."

**Check.**
1. Which carrier supplies reducing power for fatty acid synthesis and antioxidant defense
   rather than for ATP production? *(→ key)*
2. ATP formed by direct phosphate transfer during a reaction (e.g., in the TCA cycle) is made
   by what mechanism? *(→ key)*

---

### Enzyme kinetics

```yaml
title: Enzyme kinetics
category: enzymes
system: metabolism
high_yield: true
tags: [michaelis-menten, Km, Vmax, lineweaver-burk, competitive, noncompetitive]
cases: []
flashcards:
  - q: "What is Km?"
    a: "The substrate concentration at half Vmax (the Michaelis constant)."
  - q: "Does a low Km mean high or low affinity?"
    a: "High affinity — little substrate is needed to reach half-maximal speed."
  - q: "On a Lineweaver-Burk plot, what are the intercepts?"
    a: "y-intercept = 1/Vmax; x-intercept = –1/Km."
  - q: "How does a competitive inhibitor affect Km and Vmax?"
    a: "Raises apparent Km (lower affinity), Vmax unchanged; overcome by adding substrate."
  - q: "How does a noncompetitive inhibitor affect Km and Vmax?"
    a: "Lowers Vmax, Km unchanged; not overcome by adding substrate."
  - q: "Which inhibition type is overcome by adding more substrate?"
    a: "Competitive."
  - q: "Vignette: an antidote competes for the same enzyme as the toxin (fomepizole/ethanol for alcohol dehydrogenase) — inhibition type?"
    a: "Competitive."
references:
  - "LIR §Enzyme kinetics"                         # primary (biochemistry)
  - "KATZUNG §Pharmacodynamics (enzyme inhibition)" # cross-reference (pharmacology)
```

**Concept.** Enzymes accelerate reactions by lowering activation energy without being consumed.
The **Michaelis-Menten** model describes how velocity (V) rises with substrate concentration
[S] toward a maximum (**Vmax**) as the enzyme saturates. **Km** (the Michaelis constant) is the
[S] at half Vmax and is an *inverse* index of affinity — a **low Km means high affinity**
(little substrate needed to reach half-maximal speed). On a **Lineweaver-Burk** (double-
reciprocal) plot, the y-intercept = 1/Vmax and the x-intercept = –1/Km, which makes inhibitor
effects easy to read. **Competitive** inhibitors bind the active site and are overcome by adding
substrate: they raise the apparent Km (lower affinity) but leave Vmax unchanged. **Noncompetitive**
inhibitors bind elsewhere (allosteric) and can't be outcompeted: they lower Vmax but leave Km
unchanged.

**Key facts.**
- Km = [S] at ½Vmax; **low Km = high affinity**.
- Vmax = maximal velocity at saturation.
- Lineweaver-Burk: y-intercept = 1/Vmax; x-intercept = –1/Km.
- Competitive inhibitor: ↑ apparent Km, Vmax unchanged (overcome by more substrate).
- Noncompetitive inhibitor: ↓ Vmax, Km unchanged (not overcome by more substrate).

**Clinical correlation.** Methanol/ethylene glycol poisoning is treated with fomepizole or
ethanol, which *competitively* inhibit alcohol dehydrogenase. Statins competitively inhibit
HMG-CoA reductase.

**Differentiating traps.**
- Low Km = high affinity (smaller number, tighter binding).
- Competitive → ↑Km, same Vmax; noncompetitive → ↓Vmax, same Km.
- "Overcome by adding substrate" = competitive.

**Vignette signature.** "Inhibitor raises Km, Vmax unchanged" → competitive. "Inhibitor lowers
Vmax, Km unchanged" → noncompetitive. "Antidote competes for the same enzyme as the toxin" →
competitive (fomepizole/ethanol for alcohol dehydrogenase).

**Mnemonic.** "**C**ompetitive: Km **C**limbs, Vmax **C**onstant."

**Check.**
1. An inhibitor increases an enzyme's apparent Km but does not change Vmax. What type of
   inhibition is it? *(→ key)*
2. Does a low Km indicate high or low substrate affinity? *(→ key)*

---

### Rate-limiting enzyme map

```yaml
title: Rate-limiting enzyme map
category: regulation
system: metabolism
high_yield: true
tags: [rate-limiting-enzyme, committed-step, regulation, master-table]
cases: []
flashcards:
  - q: "Rate-limiting enzyme of glycolysis?"
    a: "Phosphofructokinase-1 (PFK-1)."
  - q: "Rate-limiting enzyme of gluconeogenesis?"
    a: "Fructose-1,6-bisphosphatase."
  - q: "Rate-limiting enzyme of the TCA cycle?"
    a: "Isocitrate dehydrogenase."
  - q: "Rate-limiting enzyme of fatty acid synthesis vs β-oxidation?"
    a: "Synthesis = acetyl-CoA carboxylase; β-oxidation = carnitine acyltransferase I (CPT-1)."
  - q: "Rate-limiting enzyme of cholesterol synthesis (and the statin target)?"
    a: "HMG-CoA reductase."
  - q: "Trap: cholesterol synthesis vs ketogenesis rate-limiter?"
    a: "Cholesterol = HMG-CoA reductase (cytosol); ketogenesis = HMG-CoA synthase (mitochondria)."
  - q: "Rate-limiting enzyme of heme synthesis, and the vitamin it needs?"
    a: "ALA synthase; it needs vitamin B6."
  - q: "Trap: urea cycle vs pyrimidine synthesis — CPS-I or CPS-II?"
    a: "Urea cycle = CPS-I (mitochondria, uses ammonia); pyrimidine = CPS-II (cytosol, uses glutamine)."
  - q: "Rate-limiting enzyme of the pentose phosphate pathway?"
    a: "Glucose-6-phosphate dehydrogenase (G6PD)."
references:
  - "LIR §Regulation of metabolism"   # primary (biochemistry)
```

**Concept.** Each major pathway has a committed, regulated **rate-limiting enzyme** — the
control point where hormones and allosteric signals act. These are high yield because board
items hinge on "the rate-limiting step of pathway X is…". This module is primarily the master
table below; the individual pathways are detailed in their own modules. As a frame: catabolic
pathways are generally activated in the fasting state (glucagon/epinephrine, often via
phosphorylation) and anabolic pathways in the fed state (insulin).

**Key facts.**
- Glycolysis → PFK-1; gluconeogenesis → fructose-1,6-bisphosphatase.
- Glycogen synthesis → glycogen synthase; glycogenolysis → glycogen phosphorylase.
- TCA cycle → isocitrate dehydrogenase.
- Fatty acid synthesis → acetyl-CoA carboxylase; β-oxidation → carnitine acyltransferase I (CPT-1).
- Cholesterol synthesis → HMG-CoA reductase (statin target); ketogenesis → HMG-CoA synthase.
- Heme synthesis → ALA synthase; urea cycle → carbamoyl phosphate synthetase I.
- Pentose phosphate pathway → glucose-6-phosphate dehydrogenase (G6PD).

**Clinical correlation.** Many rate-limiting enzymes are drug targets (HMG-CoA reductase →
statins) or disease loci (G6PD deficiency; ALA synthase/porphyrias). Each appears again in its
own module.

**Differentiating traps.**
- Cholesterol synthesis = HMG-CoA *reductase* (cytosol); ketogenesis = HMG-CoA *synthase*
  (mitochondria) — don't confuse.
- Urea cycle CPS-I (mitochondria, uses ammonia) vs pyrimidine CPS-II (cytosol, uses glutamine).
- Gluconeogenesis rate-limiter is fructose-1,6-bisphosphatase (not PFK-1, which is glycolysis).

**Vignette signature.** "Rate-limiting enzyme of [pathway]" → recall from the table.

**Check.**
1. What is the rate-limiting enzyme of glycolysis? *(→ key)*
2. Which enzyme is rate-limiting for cholesterol synthesis (and the statin target)? *(→ key)*

**Rate-limiting enzyme master table**

| Pathway | Rate-limiting enzyme | Key regulation |
|---|---|---|
| Glycolysis | Phosphofructokinase-1 (PFK-1) | + AMP, F-2,6-BP; − ATP, citrate |
| Gluconeogenesis | Fructose-1,6-bisphosphatase | + ATP, citrate; − AMP, F-2,6-BP |
| Glycogen synthesis | Glycogen synthase | + insulin; − glucagon/epi |
| Glycogenolysis | Glycogen phosphorylase | + glucagon/epi; − insulin |
| TCA cycle | Isocitrate dehydrogenase | + ADP; − ATP, NADH |
| Fatty acid synthesis | Acetyl-CoA carboxylase | + insulin, citrate; − glucagon |
| Fatty acid β-oxidation | Carnitine acyltransferase I (CPT-1) | − malonyl-CoA |
| Ketogenesis | HMG-CoA synthase | ↑ in fasting/starvation |
| Cholesterol synthesis | HMG-CoA reductase | − statins, cholesterol |
| Heme synthesis | ALA synthase | − heme; needs B6 |
| Urea cycle | Carbamoyl phosphate synthetase I | + N-acetylglutamate |
| Pentose phosphate pathway | Glucose-6-phosphate dehydrogenase | + NADP⁺/insulin |

---

## Section answer key

**Metabolism overview — fed, fasting & the insulin/glucagon axis**
1. Gluconeogenesis (after glycogen stores are depleted; lipolysis supplies the energy).
2. Ketone bodies (β-hydroxybutyrate and acetoacetate).

**Bioenergetics — ATP & electron carriers**
1. NADPH.
2. Substrate-level phosphorylation.

**Enzyme kinetics**
1. Competitive inhibition.
2. High affinity (low Km = high affinity).

**Rate-limiting enzyme map**
1. Phosphofructokinase-1 (PFK-1).
2. HMG-CoA reductase.
