---
course: biochemistry
section: lipid-metabolism
section_title: Metabolism — Lipid
version: 0.1
last_updated: 2026-06-02
resources_used: [LIR, ROBBINS, KATZUNG]
---

# Metabolism — Lipid

Section H of the biochem coverage checklist: fatty acid synthesis and oxidation and their
disorders, ketone bodies, cholesterol synthesis, lipoprotein transport, and the familial
dyslipidemias.

---

### Fatty acid synthesis

```yaml
title: Fatty acid synthesis
category: lipid metabolism
system: metabolism
high_yield: true
tags: [fatty-acid-synthesis, acetyl-coa-carboxylase, malonyl-coa, citrate-shuttle, NADPH, fatty-acid-synthase]
cases: []
flashcards:
  - q: "Where does fatty acid synthesis occur, and in what state?"
    a: "Cytosol (liver, lactating mammary gland), in the fed state under insulin."
  - q: "How is acetyl-CoA exported to the cytosol for synthesis?"
    a: "As citrate (the citrate shuttle)."
  - q: "Rate-limiting enzyme of fatty acid synthesis, plus its product and cofactor?"
    a: "Acetyl-CoA carboxylase (ACC) → malonyl-CoA; requires biotin (activated by insulin/citrate)."
  - q: "What reductant does fatty acid synthase use?"
    a: "NADPH (from the pentose phosphate pathway and malic enzyme)."
  - q: "How does malonyl-CoA prevent a futile cycle?"
    a: "It inhibits CPT-1, shutting down β-oxidation during synthesis."
  - q: "Trap: synthesis vs oxidation — location and reductant?"
    a: "Synthesis = cytosolic, uses NADPH; oxidation = mitochondrial, makes NADH/FADH₂."
references:
  - "LIR §Fatty acid synthesis"   # primary (biochemistry)
```

**Concept.** Fatty acid synthesis runs in the **cytosol**, chiefly in liver and lactating
mammary gland, during the fed state under insulin. Mitochondrial acetyl-CoA is exported to the
cytosol as **citrate** (the citrate shuttle) and there regenerated. The committed, rate-limiting
step is **acetyl-CoA carboxylase (ACC)**, which carboxylates acetyl-CoA to **malonyl-CoA**
(requires biotin; activated by insulin and citrate, inhibited by glucagon and palmitoyl-CoA).
**Fatty acid synthase** then builds palmitate (C16) by sequentially adding malonyl-CoA units,
using **NADPH** (from the pentose phosphate pathway and malic enzyme) as the reductant.
Critically, malonyl-CoA also inhibits CPT-1 (carnitine palmitoyltransferase I), shutting down fatty acid oxidation — so synthesis and
oxidation can't run at the same time.

**Key facts.**
- Cytosolic; liver/lactating mammary; fed state (insulin).
- Acetyl-CoA exported via the citrate shuttle.
- Rate-limiting: acetyl-CoA carboxylase (ACC) → malonyl-CoA (biotin; + insulin/citrate, − glucagon).
- Fatty acid synthase builds palmitate (C16); reductant is NADPH.
- Malonyl-CoA inhibits CPT-1 (blocking β-oxidation simultaneously).

**Clinical correlation.** Reciprocal control via malonyl-CoA prevents a futile cycle of
simultaneous synthesis and oxidation.

**Differentiating traps.**
- ACC (synthesis, makes malonyl-CoA) vs CPT-1 (oxidation, inhibited by malonyl-CoA).
- NADPH (not NADH) is the reductant for synthesis.
- Synthesis is cytosolic; oxidation is mitochondrial.

**Vignette signature.** "Rate-limiting enzyme of fatty acid synthesis" → acetyl-CoA carboxylase.
"Molecule that blocks fatty acid oxidation during synthesis" → malonyl-CoA.

**Mnemonic.** "ACC makes malonyl-CoA; malonyl-CoA closes CPT-1."

**Check.**
1. What is the rate-limiting enzyme of fatty acid synthesis? *(→ key)*
2. Which molecule simultaneously inhibits fatty acid oxidation (via CPT-1) during synthesis? *(→ key)*

---

### Fatty acid β-oxidation & the carnitine shuttle

```yaml
title: Fatty acid β-oxidation & the carnitine shuttle
category: lipid metabolism
system: metabolism
high_yield: true
tags: [beta-oxidation, carnitine-shuttle, CPT-1, CPT-2, malonyl-coa, long-chain-fatty-acid]
cases: []
flashcards:
  - q: "Where does β-oxidation occur, and what does it yield?"
    a: "Mitochondrial matrix (during fasting); yields acetyl-CoA, NADH, and FADH₂."
  - q: "What does the carnitine shuttle do, and via which enzymes?"
    a: "Moves long-chain fatty acids into the matrix: CPT-1 (outer membrane, rate-limiting), a translocase, then CPT-2 (inner membrane)."
  - q: "What inhibits CPT-1, and why does that make sense?"
    a: "Malonyl-CoA (the synthesis signal) — preventing simultaneous synthesis and oxidation."
  - q: "What does each β-oxidation cycle produce?"
    a: "It shortens the chain by 2 carbons, releasing 1 acetyl-CoA, 1 NADH, and 1 FADH₂."
  - q: "Which fatty acids bypass the carnitine shuttle?"
    a: "Medium- and short-chain fatty acids."
  - q: "Trap: which chain length requires carnitine?"
    a: "Long-chain (medium/short-chain don't — key to MCAD vs carnitine deficiency)."
references:
  - "LIR §Fatty acid oxidation"   # primary (biochemistry)
```

**Concept.** β-oxidation degrades fatty acids to acetyl-CoA in the **mitochondrial matrix** during
fasting, generating NADH and FADH₂ for ATP and acetyl-CoA for the TCA cycle or ketogenesis.
Long-chain fatty acids can't cross the inner mitochondrial membrane on their own; they need the
**carnitine shuttle**: **CPT-1 (carnitine palmitoyltransferase I)** on the outer membrane attaches carnitine (forming acylcarnitine —
this is the rate-limiting step, inhibited by malonyl-CoA), a translocase moves it across, and
**CPT-2 (carnitine palmitoyltransferase II)** on the inner membrane regenerates acyl-CoA inside. Each β-oxidation cycle shortens the
chain by two carbons, releasing one acetyl-CoA, one NADH, and one FADH₂. Medium- and short-chain
fatty acids enter the mitochondrion independently of carnitine.

**Key facts.**
- Mitochondrial matrix; fasting; yields acetyl-CoA + NADH + FADH₂.
- Carnitine shuttle (long-chain FAs): CPT-1 (rate-limiting, outer membrane, − malonyl-CoA),
  translocase, CPT-2 (inner membrane).
- Each cycle removes 2 carbons → 1 acetyl-CoA, 1 NADH, 1 FADH₂.
- Medium/short-chain fatty acids bypass the carnitine shuttle.

**Clinical correlation.** Defects in the shuttle (carnitine or CPT deficiency) or in β-oxidation
enzymes (MCAD) impair fasting energy production → hypoketotic hypoglycemia (next modules).

**Differentiating traps.**
- CPT-1 = rate-limiting, inhibited by malonyl-CoA (the synthesis signal).
- Long-chain FAs need carnitine; medium/short-chain do not (key to MCAD vs carnitine deficiency).
- Oxidation is mitochondrial; synthesis is cytosolic.

**Vignette signature.** "Long-chain fatty acids can't enter the mitochondrion" → carnitine shuttle
defect. "Rate-limiting step of fatty acid oxidation" → CPT-1.

**Mnemonic.** "**Carnitine Carries** fat in; CPT-1 is the gate (closed by malonyl-CoA)."

**Check.**
1. Which transport system moves long-chain fatty acids into the mitochondrial matrix? *(→ key)*
2. What is the rate-limiting enzyme of fatty acid β-oxidation? *(→ key)*

---

### Carnitine deficiency

```yaml
title: Carnitine deficiency
category: lipid metabolism
system: metabolism
high_yield: true
tags: [carnitine-deficiency, CPT-deficiency, hypoketotic-hypoglycemia, cardiomyopathy, lipid-myopathy]
cases: []
flashcards:
  - q: "What does carnitine (or CPT) deficiency block?"
    a: "Long-chain fatty acid entry into mitochondria → no β-oxidation."
  - q: "Characteristic fasting finding in carnitine deficiency?"
    a: "Hypoketotic hypoglycemia."
  - q: "Clinical features of carnitine deficiency?"
    a: "Weakness, hypotonia, lipid myopathy, cardiomyopathy, elevated muscle triglyceride."
  - q: "Treatment of primary carnitine deficiency?"
    a: "Carnitine supplementation and avoiding fasting."
  - q: "Vignette: muscle weakness, cardiomyopathy, and hypoketotic hypoglycemia with fasting — diagnosis?"
    a: "Carnitine/CPT deficiency."
references:
  - "LIR §Fatty acid oxidation"   # primary (biochemistry)
```

**Concept.** Carnitine deficiency (primary, from a transporter defect, or secondary) prevents
long-chain fatty acids from entering the mitochondrion, so they can't be oxidized. Without fatty
acid oxidation, fasting energy production and ketogenesis fail while fats accumulate.
Presentation: weakness, hypotonia, and a lipid myopathy, with **hypoketotic hypoglycemia** during
fasting, cardiomyopathy, and elevated muscle triglyceride. CPT (carnitine palmitoyltransferase) deficiencies — CPT-1 or CPT-2 — present
similarly (muscle weakness, myoglobinuria after exercise or fasting).

**Key facts.**
- Carnitine (or CPT) deficiency → long-chain FAs can't enter mitochondria → no β-oxidation.
- Hypoketotic hypoglycemia with fasting; weakness, hypotonia, cardiomyopathy, lipid myopathy.
- Elevated muscle triglyceride; low carnitine or abnormal acylcarnitines on labs.

**Clinical correlation.** Weakness and cardiomyopathy with fasting hypoketotic hypoglycemia; treat
with carnitine supplementation (primary form) and by avoiding fasting.

**Differentiating traps.**
- Hypoketotic hypoglycemia (no ketones because FA oxidation is blocked) — shared with MCAD.
- Affects long-chain fatty acid handling specifically.

**Vignette signature.** "Muscle weakness, cardiomyopathy, and hypoketotic hypoglycemia with
fasting" → carnitine/CPT deficiency.

**Mnemonic.** "No carnitine → can't carry fat in → no ketones (hypoketotic hypoglycemia)."

**Check.**
1. Carnitine deficiency produces what characteristic combination of glucose and ketone findings
   during fasting? *(→ key)*
2. Which chain length of fatty acid specifically requires carnitine to enter the mitochondrion?
   *(→ key)*

---

### MCAD deficiency

```yaml
title: MCAD deficiency
category: lipid metabolism
system: metabolism
enzyme: medium-chain acyl-CoA dehydrogenase
inheritance: autosomal recessive
high_yield: true
tags: [MCAD, fatty-acid-oxidation, hypoketotic-hypoglycemia, dicarboxylic-aciduria, newborn-screen, SIDS]
cases: []
flashcards:
  - q: "What is MCAD deficiency — frequency, inheritance, and detection?"
    a: "The most common inherited fatty acid oxidation disorder; autosomal recessive; detected on newborn screening."
  - q: "What does MCAD catalyze, and what accumulates when it's deficient?"
    a: "The first dehydrogenation of medium-chain β-oxidation; medium-chain acyl-CoAs accumulate."
  - q: "Hallmark metabolic finding in MCAD during fasting?"
    a: "Hypoketotic hypoglycemia."
  - q: "Classic MCAD presentation?"
    a: "A previously well infant/toddler who, during fasting or illness, has vomiting, lethargy, and hypoglycemia without ketones (can progress to coma/sudden death)."
  - q: "Lab findings in MCAD?"
    a: "Dicarboxylic aciduria and elevated medium-chain acylcarnitines."
  - q: "Trap: is carnitine low in MCAD?"
    a: "No — MCAD affects medium-chain fats, which don't need carnitine, so carnitine is normal/high (unlike carnitine deficiency)."
references:
  - "LIR §Fatty acid oxidation disorders"   # primary (biochemistry)
```

**Concept.** Medium-chain acyl-CoA dehydrogenase (MCAD) deficiency is the **most common inherited
fatty acid oxidation disorder**, autosomal recessive, and is detected on newborn screening. MCAD
catalyzes the first dehydrogenation step of β-oxidation for medium-chain fatty acids; without it,
medium-chain acyl-CoAs accumulate, and the inability to oxidize fatty acids during fasting produces
**hypoketotic hypoglycemia**. Classic presentation: a previously well infant or toddler who, during
fasting or an intercurrent illness, develops vomiting, lethargy, and hypoglycemia *without ketones*,
which can progress to coma or sudden death (an overlap cause of some sudden infant deaths).
Dicarboxylic aciduria and elevated medium-chain acylcarnitines are found. Management is avoiding
fasting.

**Key facts.**
- MCAD deficiency; AR; most common FA oxidation disorder; on newborn screen.
- Impaired medium-chain β-oxidation → hypoketotic hypoglycemia with fasting/illness.
- Vomiting, lethargy, possible coma/sudden death; dicarboxylic aciduria; ↑ medium-chain acylcarnitines.
- Treat by avoiding fasting (frequent feeds).

**Clinical correlation.** A previously well child decompensates during a fast or viral illness with
hypoketotic hypoglycemia — a recognized cause overlapping with sudden infant death.

**Differentiating traps.**
- Hypoketotic hypoglycemia is the unifying clue for FA oxidation defects (MCAD, carnitine/CPT).
- MCAD affects medium-chain fatty acids, which don't need carnitine — so carnitine is normal/high.
- Precipitated by fasting/illness in a previously well child.

**Vignette signature.** "Previously well toddler who, with fasting/illness, has vomiting and
hypoglycemia *without* ketones, plus dicarboxylic aciduria" → MCAD.

**Mnemonic.** "MCAD → can't burn **M**edium fats → hypoketotic hypoglycemia with fasting."

**Check.**
1. What is the most common inherited disorder of fatty acid oxidation? *(→ key)*
2. What is the hallmark metabolic finding during fasting in MCAD deficiency? *(→ key)*

---

### Ketone body metabolism

```yaml
title: Ketone body metabolism
category: lipid metabolism
system: metabolism
high_yield: true
tags: [ketone-bodies, acetoacetate, beta-hydroxybutyrate, HMG-CoA-synthase, thiophorase, DKA]
cases: []
flashcards:
  - q: "What are the ketone bodies, and when are they made?"
    a: "Acetoacetate and β-hydroxybutyrate (plus acetone); made by the liver in fasting/starvation/DKA from excess acetyl-CoA."
  - q: "Rate-limiting enzyme of ketogenesis?"
    a: "HMG-CoA synthase (mitochondrial)."
  - q: "Why can the liver make but not use ketones?"
    a: "It lacks thiophorase; peripheral tissues use thiophorase to reconvert ketones to acetyl-CoA."
  - q: "Which ketone predominates in high-NADH states, and what is the test caveat?"
    a: "β-hydroxybutyrate; nitroprusside tests detect acetoacetate and so may underestimate severity."
  - q: "What do ketones spare in prolonged starvation?"
    a: "Glucose (and protein) — the brain adapts to use ketones."
  - q: "Trap: which organ makes but can't use ketones?"
    a: "The liver (no thiophorase)."
references:
  - "LIR §Ketone body metabolism"   # primary (biochemistry)
```

**Concept.** During prolonged fasting/starvation, low-carbohydrate states, or uncontrolled
diabetes, the liver converts excess acetyl-CoA (from heavy β-oxidation) into **ketone bodies** —
acetoacetate and β-hydroxybutyrate (plus acetone) — via **HMG-CoA synthase** (rate-limiting,
mitochondrial). These water-soluble fuels are exported to peripheral tissues and especially the
brain, which adapts to use them, sparing glucose and protein. Peripheral tissues reconvert them to
acetyl-CoA for the TCA cycle using **thiophorase**; the **liver lacks thiophorase**, so it makes
but cannot use ketones. In high-NADH states (alcoholism, DKA) the equilibrium shifts toward
**β-hydroxybutyrate**, which standard nitroprusside ketone tests (which detect acetoacetate) may
underestimate.

**Key facts.**
- Liver makes ketones (acetoacetate, β-hydroxybutyrate, acetone) from acetyl-CoA in
  fasting/starvation/DKA.
- Rate-limiting: HMG-CoA synthase (mitochondrial).
- Brain/peripheral tissues use ketones (thiophorase); liver lacks thiophorase (can't use them).
- High NADH (alcohol, DKA) favors β-hydroxybutyrate over acetoacetate.

**Clinical correlation.** DKA (insulin deficiency) and alcoholic ketoacidosis are the clinical
extremes; because the β-hydroxybutyrate:acetoacetate ratio rises with high NADH, nitroprusside
tests can underestimate severity.

**Differentiating traps.**
- The liver makes ketones but can't use them (no thiophorase).
- High-NADH states favor β-hydroxybutyrate (the test caveat).
- Ketones spare glucose for the brain in prolonged starvation.

**Vignette signature.** "Fasting/DKA producing acetoacetate and β-hydroxybutyrate" → ketogenesis.
"Organ that makes but can't use ketones" → liver.

**Mnemonic.** "Liver makes ketones for everyone else — no thiophorase to use its own."

**Check.**
1. Which organ synthesizes ketone bodies but cannot use them, and why? *(→ key)*
2. In high-NADH states (alcoholism, DKA), which ketone body predominates? *(→ key)*

---

### Cholesterol synthesis

```yaml
title: Cholesterol synthesis
category: lipid metabolism
system: metabolism
high_yield: true
tags: [cholesterol, HMG-CoA-reductase, mevalonate, statins, NADPH]
cases: []
flashcards:
  - q: "Rate-limiting enzyme of cholesterol synthesis, and its product?"
    a: "HMG-CoA reductase (HMG-CoA → mevalonate; uses NADPH)."
  - q: "Which drug class competitively inhibits HMG-CoA reductase?"
    a: "Statins."
  - q: "How is HMG-CoA reductase regulated?"
    a: "Sterol feedback inhibition; activated by insulin, inhibited by glucagon."
  - q: "What is cholesterol a precursor of?"
    a: "Bile acids, steroid hormones, and vitamin D."
  - q: "Trap: HMG-CoA reductase vs synthase?"
    a: "Reductase = cholesterol (cytosol, statin target); synthase = ketones (mitochondria)."
references:
  - "LIR §Cholesterol synthesis"   # primary (biochemistry)
  - "KATZUNG §HMG-CoA reductase inhibitors (statins)"   # cross-reference (pharmacology)
```

**Concept.** Cholesterol is synthesized in the cytosol/ER of all cells, most in the liver, from
acetyl-CoA. The committed, rate-limiting step is **HMG-CoA reductase**, which converts HMG-CoA to
**mevalonate** using NADPH; this enzyme is the target of **statins** (competitive inhibitors) and
is regulated by sterol feedback inhibition, insulin (activating), and glucagon (inhibiting).
Cholesterol is the precursor of bile acids, steroid hormones, and vitamin D, and a key membrane
component. Note the contrast: cytosolic HMG-CoA **reductase** for cholesterol versus mitochondrial
HMG-CoA **synthase** for ketones.

**Key facts.**
- From acetyl-CoA; rate-limiting HMG-CoA reductase (HMG-CoA → mevalonate; uses NADPH).
- Statins competitively inhibit HMG-CoA reductase.
- Regulated by sterol feedback, insulin (+), glucagon (−).
- Precursor of bile acids, steroid hormones, vitamin D.

**Clinical correlation.** Statins lower LDL by inhibiting HMG-CoA reductase (and upregulating LDL
receptors). Familial hypercholesterolemia involves the LDL receptor, not this enzyme.

**Differentiating traps.**
- HMG-CoA reductase (cholesterol, cytosol, statin target) vs HMG-CoA synthase (ketones,
  mitochondria).
- Statins are competitive inhibitors.

**Vignette signature.** "Rate-limiting enzyme of cholesterol synthesis / the statin target" →
HMG-CoA reductase.

**Mnemonic.** "Statins stop HMG-CoA **R**eductase."

**Check.**
1. What is the rate-limiting enzyme of cholesterol synthesis? *(→ key)*
2. Which drug class competitively inhibits this enzyme? *(→ key)*

---

### Lipoprotein metabolism & apolipoproteins

```yaml
title: Lipoprotein metabolism & apolipoproteins
category: lipid metabolism
system: metabolism
high_yield: true
tags: [chylomicron, VLDL, LDL, HDL, lipoprotein-lipase, apo-B100, apo-CII, apo-E]
cases: []
flashcards:
  - q: "What do chylomicrons, VLDL, LDL, and HDL each do?"
    a: "Chylomicrons carry dietary TG; VLDL carries hepatic TG; LDL delivers cholesterol to tissues; HDL does reverse cholesterol transport."
  - q: "What does lipoprotein lipase do, where, and what activates it?"
    a: "Hydrolyzes TG in chylomicrons/VLDL to free fatty acids; on capillary endothelium; activated by apo C-II."
  - q: "What does apo B-100 do?"
    a: "Binds the LDL receptor (on VLDL/LDL)."
  - q: "What does apo C-II do?"
    a: "Activates lipoprotein lipase."
  - q: "What does apo E do?"
    a: "Mediates remnant uptake by the liver."
  - q: "What does apo B-48 do?"
    a: "Chylomicron assembly and secretion."
  - q: "Which lipoprotein performs reverse cholesterol transport?"
    a: "HDL."
references:
  - "LIR §Lipoprotein metabolism"   # primary (biochemistry)
```

**Concept.** Lipids travel in blood as **lipoproteins**, classified by density and function.
**Chylomicrons** (largest, least dense) carry dietary triglyceride from the gut. **VLDL** carries
hepatic triglyceride to tissues. **LDL** ("bad") delivers cholesterol to peripheral tissues and is
taken up via the LDL receptor. **HDL** ("good") performs reverse cholesterol transport from
tissues to liver. **Lipoprotein lipase (LPL)**, on capillary endothelium and activated by **apo
C-II**, hydrolyzes triglyceride in chylomicrons and VLDL, releasing free fatty acids. Key
apolipoproteins: **apo B-48** (chylomicron assembly/secretion), **apo B-100** (VLDL/LDL; binds the
LDL receptor), **apo C-II** (activates LPL), **apo E** (remnant uptake by the liver), and **apo
A-I** (activates LCAT for HDL). Defects in these proteins/receptors cause the dyslipidemias.

**Key facts.**
- Chylomicron (dietary TG), VLDL (hepatic TG), LDL (cholesterol to tissues), HDL (reverse transport).
- LPL (capillary endothelium; activated by apo C-II) hydrolyzes TG → free fatty acids.
- Apo B-48 (chylomicron), apo B-100 (VLDL/LDL; LDL-receptor ligand), apo C-II (LPL activator),
  apo E (remnant uptake), apo A-I (LCAT/HDL).

**Clinical correlation.** Dyslipidemias arise from defects in LPL/apo C-II (chylomicronemia), the
LDL receptor/apo B-100 (familial hypercholesterolemia), and apo E (dysbetalipoproteinemia) — next
module.

**Differentiating traps.**
- Apo C-II activates LPL; apo B-100 binds the LDL receptor; apo E mediates remnant uptake.
- LDL delivers cholesterol; HDL does reverse transport.

**Vignette signature.** "Apolipoprotein that activates lipoprotein lipase" → apo C-II. "Ligand for
the LDL receptor" → apo B-100.

**Mnemonic.** "C-II = **C**lears (activates LPL); B-100 = **B**inds the LDL receptor; E = r**E**mnant uptake."

**Check.**
1. Which apolipoprotein activates lipoprotein lipase? *(→ key)*
2. Which lipoprotein performs reverse cholesterol transport? *(→ key)*

---

### Familial dyslipidemias

```yaml
title: Familial dyslipidemias
category: lipid metabolism
system: metabolism
high_yield: true
tags: [hyperchylomicronemia, familial-hypercholesterolemia, dysbetalipoproteinemia, hypertriglyceridemia, xanthoma]
cases: []
flashcards:
  - q: "Type I (familial hyperchylomicronemia) — defect and presentation?"
    a: "LPL or apo C-II deficiency → ↑chylomicrons/TG; pancreatitis, eruptive xanthomas, lipemia retinalis; no premature atherosclerosis."
  - q: "Type IIa (familial hypercholesterolemia) — defect and presentation?"
    a: "LDL receptor (or apo B-100) defect → ↑LDL; tendon xanthomas, xanthelasma, corneal arcus, early MI."
  - q: "Type III (dysbetalipoproteinemia) — defect and hallmark?"
    a: "Apo E defect → ↑remnants/IDL; palmar xanthomas and premature atherosclerosis."
  - q: "Type IV (hypertriglyceridemia) — defect and risk?"
    a: "Hepatic VLDL overproduction → ↑VLDL/TG; pancreatitis risk."
  - q: "Which xanthoma goes with which type — tendon vs palmar?"
    a: "Tendon xanthomas = IIa; palmar xanthomas = III (apo E)."
  - q: "Trap: why no premature atherosclerosis in type I?"
    a: "Chylomicrons are too large to be atherogenic; the risk is pancreatitis instead."
  - q: "Vignette: child with very high LDL, tendon xanthomas, early MI, AD family history — diagnosis?"
    a: "Familial hypercholesterolemia (type IIa)."
references:
  - "LIR §Hyperlipidemias"         # primary (biochemistry)
  - "ROBBINS §Atherosclerosis"      # cross-reference (pathology)
```

**Concept.** Inherited dyslipidemias are classified by which lipoprotein is elevated and which
protein is defective. **Type I (familial hyperchylomicronemia):** lipoprotein lipase or apo C-II
deficiency → massive chylomicrons and triglycerides, presenting with eruptive xanthomas, lipemia
retinalis, hepatosplenomegaly, and **acute pancreatitis** — but *not* premature atherosclerosis.
**Type IIa (familial hypercholesterolemia):** an LDL receptor (or apo B-100) defect → very high
LDL/total cholesterol, with **tendon xanthomas** (Achilles), xanthelasma, corneal arcus, and early
atherosclerosis/MI; homozygotes can have an MI in childhood. **Type III (dysbetalipoproteinemia):**
an apo E defect → elevated chylomicron remnants and IDL, with **palmar xanthomas** and premature
atherosclerosis. **Type IV (hypertriglyceridemia):** hepatic VLDL overproduction → elevated
VLDL/triglycerides, with pancreatitis risk.

**Key facts.**
- Type I: LPL or apo C-II deficiency → ↑chylomicrons/TG; pancreatitis, eruptive xanthomas (no early atherosclerosis).
- Type IIa (familial hypercholesterolemia): LDL receptor/apo B-100 defect → ↑LDL; tendon xanthomas, early MI.
- Type III (dysbetalipoproteinemia): apo E defect → ↑remnants/IDL; palmar xanthomas, atherosclerosis.
- Type IV: VLDL overproduction → ↑VLDL/TG; pancreatitis risk.

**Clinical correlation.** Familial hypercholesterolemia (IIa) is the classic autosomal dominant
high-LDL/tendon-xanthoma/early-MI disorder; the homozygous form is severe. The high-triglyceride
types (I, IV) risk pancreatitis.

**Differentiating traps.**
- High-TG types (I, IV → pancreatitis) vs IIa (high LDL → atherosclerosis/tendon xanthomas).
- Palmar xanthomas → type III (apo E); tendon xanthomas → IIa.
- Type I has *no* premature atherosclerosis (chylomicrons are too large to be atherogenic) —
  pancreatitis instead.

**Vignette signature.** "Child with very high LDL, tendon xanthomas, early MI, AD family history"
→ familial hypercholesterolemia (IIa). "High triglycerides, eruptive xanthomas, pancreatitis" →
type I. "Palmar xanthomas" → type III (apo E).

**Mnemonic.** "I = chylomicrons (LPL/C-II); IIa = LDL (receptor); III = remnants (apo E); IV = VLDL."

**Check.**
1. Familial hypercholesterolemia (type IIa) results from a defect in which receptor? *(→ key)*
2. Which dyslipidemia is caused by lipoprotein lipase or apo C-II deficiency and presents with
   pancreatitis? *(→ key)*

**Familial dyslipidemia summary**

| Type | Name | Defect | Elevated | Hallmark |
|---|---|---|---|---|
| I | Familial hyperchylomicronemia | LPL or apo C-II deficiency | Chylomicrons, TG | Pancreatitis, eruptive xanthomas (no early atherosclerosis) |
| IIa | Familial hypercholesterolemia | LDL receptor / apo B-100 | LDL | Tendon xanthomas, early MI |
| III | Dysbetalipoproteinemia | Apo E | Remnants, IDL | Palmar xanthomas, atherosclerosis |
| IV | Hypertriglyceridemia | VLDL overproduction | VLDL, TG | Pancreatitis risk |

---

### Abetalipoproteinemia

```yaml
title: Abetalipoproteinemia
category: lipid metabolism
system: metabolism
enzyme: microsomal triglyceride transfer protein (MTP)
inheritance: autosomal recessive
high_yield: true
tags: [abetalipoproteinemia, MTP, apo-B, acanthocytes, vitamin-E, steatorrhea, retinitis-pigmentosa]
cases: []
flashcards:
  - q: "Which protein is deficient in abetalipoproteinemia, and what is the inheritance?"
    a: "Microsomal triglyceride transfer protein (MTP); autosomal recessive."
  - q: "What can't be assembled, and what is the consequence?"
    a: "Apo B lipoproteins (chylomicrons, VLDL) → fat and fat-soluble vitamin malabsorption."
  - q: "Which vitamin deficiency drives the neurologic findings, and what are they?"
    a: "Vitamin E → ataxia, neuropathy, and retinitis pigmentosa."
  - q: "Smear and lipid findings in abetalipoproteinemia?"
    a: "Acanthocytes (spur cells); absent apo B; very low triglyceride/cholesterol."
  - q: "Vignette: infant with steatorrhea, failure to thrive, ataxia, acanthocytes, and absent apo B — diagnosis?"
    a: "Abetalipoproteinemia."
references:
  - "LIR §Lipoprotein metabolism"   # primary (biochemistry)
  - "ROBBINS §Malabsorption"         # cross-reference (pathology)
```

**Concept.** Abetalipoproteinemia is an autosomal recessive deficiency of **microsomal triglyceride
transfer protein (MTP)**, needed to assemble apo B–containing lipoproteins (chylomicrons and VLDL).
Without it, the intestine can't export dietary fat or fat-soluble vitamins, and enterocytes
accumulate lipid. Presentation in infancy: failure to thrive, steatorrhea/fat malabsorption, and —
from fat-soluble vitamin deficiency, especially **vitamin E** — progressive ataxia, neuropathy, and
retinitis pigmentosa. The smear shows **acanthocytes** (spur cells); apo B is absent and serum
triglyceride/cholesterol are very low. Treatment is a low-long-chain-fat diet with high doses of
fat-soluble vitamins (especially E).

**Key facts.**
- AR deficiency of microsomal triglyceride transfer protein (MTP).
- Can't assemble apo B lipoproteins (chylomicrons, VLDL) → fat and fat-soluble vitamin malabsorption.
- Infancy: failure to thrive, steatorrhea; vitamin E deficiency → ataxia, neuropathy, retinitis pigmentosa.
- Acanthocytes on smear; absent apo B; very low TG/cholesterol.
- Treat with vitamin E (and other fat-soluble vitamins); restrict long-chain fat.

**Clinical correlation.** Infant with steatorrhea, failure to thrive, neurologic decline, and
acanthocytes on smear.

**Differentiating traps.**
- The MTP defect blocks both chylomicron and VLDL secretion (both require apo B).
- Vitamin E deficiency drives the neurologic and retinal findings.
- Acanthocytes (spur cells) on the peripheral smear.

**Vignette signature.** "Infant with steatorrhea, failure to thrive, ataxia, acanthocytes, and
absent apo B" → abetalipoproteinemia.

**Mnemonic.** "No apo **B** → no chylomicrons/VLDL → fat-soluble vitamin (E) deficiency and
acanthocytes."

**Check.**
1. Which protein is deficient in abetalipoproteinemia? *(→ key)*
2. Deficiency of which fat-soluble vitamin drives the neurologic findings? *(→ key)*

---

## Section answer key

**Fatty acid synthesis**
1. Acetyl-CoA carboxylase (ACC).
2. Malonyl-CoA.

**Fatty acid β-oxidation & the carnitine shuttle**
1. The carnitine shuttle (CPT-1 → translocase → CPT-2).
2. Carnitine palmitoyltransferase I (CPT-1).

**Carnitine deficiency**
1. Hypoketotic hypoglycemia (low glucose with inappropriately low/absent ketones).
2. Long-chain fatty acids.

**MCAD deficiency**
1. Medium-chain acyl-CoA dehydrogenase (MCAD) deficiency.
2. Hypoketotic hypoglycemia.

**Ketone body metabolism**
1. The liver — it synthesizes ketones but lacks thiophorase, so it cannot use them.
2. β-hydroxybutyrate.

**Cholesterol synthesis**
1. HMG-CoA reductase.
2. Statins (HMG-CoA reductase inhibitors).

**Lipoprotein metabolism & apolipoproteins**
1. Apo C-II.
2. HDL.

**Familial dyslipidemias**
1. The LDL receptor (or apo B-100).
2. Type I (familial hyperchylomicronemia).

**Abetalipoproteinemia**
1. Microsomal triglyceride transfer protein (MTP).
2. Vitamin E.
