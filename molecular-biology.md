---
course: biochemistry
section: molecular-biology
section_title: Molecular Biology
version: 0.2
last_updated: 2026-06-02
resources_used: [LIR, KATZUNG, ROBBINS, THOMPSON]
---

# Molecular Biology

Section A of the biochem coverage checklist: the flow of genetic information — DNA
structure, replication, repair, mutation, transcription, RNA processing, translation,
gene silencing, and the lab techniques that interrogate each step.

---

### DNA structure & chromatin organization

```yaml
title: DNA structure & chromatin organization
category: DNA metabolism
system: molecular biology
high_yield: true
tags: [base-pairing, gc-content, nucleosome, histones, euchromatin, methylation, epigenetics]
cases: []
flashcards:
  - q: "How many hydrogen bonds in A–T vs G–C pairs, and how does that affect melting temperature?"
    a: "A–T = 2 bonds, G–C = 3; higher GC content raises the melting temperature."
  - q: "What makes up a nucleosome?"
    a: "DNA wound around a histone octamer (2 each of H2A, H2B, H3, H4); histone H1 binds the linker DNA."
  - q: "Why are histones positively charged, and what does that let them do?"
    a: "They are rich in lysine and arginine (positive), so they grip the negatively charged phosphate backbone."
  - q: "Euchromatin vs heterochromatin — which is transcriptionally active?"
    a: "Euchromatin (loose, active); heterochromatin is condensed and silent."
  - q: "What effect does histone acetylation have on transcription?"
    a: "It loosens chromatin and activates transcription."
  - q: "What effect does DNA methylation (cytosine at CpG islands) have?"
    a: "It condenses chromatin and silences transcription."
  - q: "Which two heritable epigenetic phenomena depend on DNA methylation?"
    a: "Genomic imprinting and X-inactivation."
  - q: "Trap: which is the stronger base pair, A–T or G–C?"
    a: "G–C (three hydrogen bonds)."
references:
  - "LIR §DNA structure and organization"        # primary (biochemistry)
  - "ROBBINS §Epigenetic changes in cancer"       # cross-reference (pathology)
```

**Concept.** DNA is a double helix of antiparallel strands held by complementary base
pairing — A–T with two hydrogen bonds, G–C with three — so the higher the GC content, the
more thermostable the duplex (it takes more energy to melt three bonds than two). In
eukaryotes, roughly two meters of DNA is compacted into the nucleus by wrapping around
histone octamers (two each of H2A, H2B, H3, H4) to form nucleosomes, the "beads on a
string," with histone H1 binding the linker DNA to pack them further. Histones are rich in
the positively charged residues lysine and arginine, which lets them grip the negatively
charged phosphate backbone. Chromatin exists in two states: loosely packed, transcriptionally
active euchromatin and densely packed, silent heterochromatin. Expression is tuned by
reversible chemical marks — histone acetylation (by histone acetyltransferases) loosens
chromatin and activates transcription, whereas histone deacetylation and DNA methylation
(on cytosine at CpG islands) condense and silence it. Because methylation patterns are
copied after replication, they are heritable, which is the molecular basis of genomic
imprinting and X-inactivation.

**Key facts.**
- A–T = 2 H-bonds; G–C = 3 H-bonds → higher GC content raises melting temperature.
- Nucleosome = DNA wound on a histone octamer (2× H2A, H2B, H3, H4); H1 = linker.
- Histones are lysine/arginine-rich (positive) → bind the negative phosphate backbone.
- Euchromatin = active/loose; heterochromatin = silent/condensed.
- Acetylation → activates; deacetylation + DNA (cytosine) methylation → silences.
- Methylation underlies imprinting and X-inactivation; mitotically heritable (epigenetic).

**Clinical correlation.** Epigenetic marks change expression without altering sequence.
Aberrant promoter methylation silences tumor suppressor genes in cancer, and hypomethylating
agents (azacitidine) and HDAC inhibitors are used in some hematologic malignancies. Imprinting
disorders (Prader-Willi/Angelman) arise from parent-of-origin methylation (see Chromosomal
Syndromes).

**Differentiating traps.**
- G–C is the *stronger* pair (3 bonds), not A–T.
- Acetylation *activates*; DNA methylation *silences* — opposite marks, easy to conflate.
- Histones are basic/positive; DNA is acidic/negative.

**Vignette signature.** "GC-rich region → higher melting temperature." "Heavily methylated
promoter → gene silenced." "Lysine-rich proteins that package DNA → histones."

**Mnemonic.** "GC = Greater grip (3 bonds)." "Acetylation → Active."

**Check.**
1. Two DNA segments differ only in base composition; which has the higher melting
   temperature, the GC-rich or the AT-rich one? *(→ key)*
2. A tumor suppressor gene's promoter is found heavily methylated. What happens to its
   expression? *(→ key)*

---

### DNA replication

```yaml
title: DNA replication
category: DNA metabolism
system: molecular biology
high_yield: true
tags: [semiconservative, okazaki-fragments, rna-primer, topoisomerase, telomerase, proofreading]
cases: []
flashcards:
  - q: "What does semiconservative replication mean?"
    a: "Each daughter molecule keeps one parental strand and one newly synthesized strand."
  - q: "In which direction does DNA polymerase synthesize, and what does it need to begin?"
    a: "5′→3′; it requires a free 3′-OH and a primer."
  - q: "What type of primer does primase lay down?"
    a: "A short RNA primer."
  - q: "Leading vs lagging strand — which is synthesized continuously?"
    a: "The leading strand; the lagging strand is made in Okazaki fragments."
  - q: "Which enzyme relieves supercoiling ahead of the replication fork?"
    a: "Topoisomerase."
  - q: "What is bacterial topoisomerase II called, and which drug class inhibits it?"
    a: "DNA gyrase; fluoroquinolones."
  - q: "Which human topoisomerase do etoposide and teniposide inhibit?"
    a: "Topoisomerase II."
  - q: "What is telomerase and what does it do?"
    a: "A reverse transcriptase (RNA-dependent DNA polymerase) that extends chromosome 3′ ends with repeats using its own RNA template."
  - q: "Vignette: tumor cells divide indefinitely with no telomere shortening — why?"
    a: "Reactivated telomerase."
  - q: "Trap: is the replication primer made of DNA or RNA?"
    a: "RNA (made by primase)."
references:
  - "LIR §DNA structure, replication, and repair"   # primary (biochemistry)
  - "KATZUNG §Fluoroquinolones"                      # cross-reference (pharmacology)
```

**Concept.** DNA replication is *semiconservative*: each daughter molecule keeps one
parental strand and one newly made strand. It starts at origins of replication and runs in
both directions, opening replication forks. Helicase unwinds the double helix, single-strand
binding proteins hold the separated strands apart, and topoisomerases relieve the torsional
strain (supercoiling) ahead of the fork by nicking and resealing the backbone. The central
constraint is that DNA polymerase can only add nucleotides to a free 3′-OH and only builds
5′→3′ — so it can neither start from scratch nor copy both template strands in the same
direction. Primase solves the first problem by laying down a short *RNA* primer to give
polymerase a 3′ end to extend. The second is solved by copying the strand pointed toward the
fork continuously (the **leading strand**) while copying the other in short pieces pointed
away from the fork (the **lagging strand**, made of Okazaki fragments, each needing its own
primer). The RNA primers are later excised and replaced with DNA, and DNA ligase seals the
nicks. Throughout, polymerase proofreads with a 3′→5′ exonuclease. One leftover problem is
unique to linear eukaryotic chromosomes: they can't fully replicate their 3′ ends and so
shorten each division — unless **telomerase**, a reverse transcriptase carrying its own RNA
template, extends the ends with repeats.

**Key facts.**
- Semiconservative (Meselson–Stahl).
- Synthesis 5′→3′; template read 3′→5′; requires a free 3′-OH and a primer.
- Helicase unwinds; SSBs stabilize; topoisomerase relieves supercoiling.
- Primase makes the **RNA** primer.
- Prokaryotes: DNA pol III elongates; DNA pol I removes/replaces the RNA primer; both proofread.
- Eukaryotes: pol α primes, pol δ lagging, pol ε leading, pol γ mitochondrial.
- DNA ligase joins Okazaki fragments. Telomerase = RNA-dependent DNA polymerase.

**Clinical correlation.** Bacterial topoisomerase II is **DNA gyrase**; fluoroquinolones
inhibit it (and topo IV). Human topoisomerases are chemo targets: etoposide/teniposide (topo
II), irinotecan/topotecan (topo I). Telomerase is silent in most somatic cells (telomere
shortening → senescence) but reactivated in ~90% of cancers. Helicase defects cause Bloom and
Werner syndromes (genomic instability; premature aging in Werner).

**Differentiating traps.**
- The primer is **RNA** (primase), not DNA.
- Topo I (single-strand nick, no ATP) vs II (double-strand break, ATP, = gyrase); fluoroquinolones
  hit *bacterial* gyrase, etoposide hits *human* topo II.
- Prokaryotic pol III *elongates*; pol I *removes the primer* — don't swap.
- Telomerase adds to the **3′** end and is a reverse transcriptase.

**Vignette signature.** "Antibiotic inhibiting bacterial DNA gyrase" → fluoroquinolone.
"Enzyme adding repeats to chromosome ends, high in tumors" → telomerase. "Short RNA needed
to begin synthesis" → primer. "Premature aging + genomic instability" → helicase defect.

**Mnemonic.** Telomerase = **TERT** (Telomerase Reverse Transcriptase) — the name is the
mechanism.

**Check.**
1. A broad-spectrum antibiotic inhibits bacterial DNA gyrase (topoisomerase II). What drug
   class is it? *(→ key)*
2. The chemotherapeutic etoposide blocks the human enzyme that relieves DNA supercoiling
   during replication. Which enzyme? *(→ key)*
3. A tumor's cells divide indefinitely with no telomere shortening. What enzyme activity
   explains this? *(→ key)*

---

### DNA repair pathways

```yaml
title: DNA repair pathways
category: DNA metabolism
system: molecular biology
high_yield: true
tags: [NER, BER, mismatch-repair, homologous-recombination, NHEJ, xeroderma, lynch, BRCA]
cases: []
flashcards:
  - q: "Which pathway repairs UV-induced pyrimidine dimers, and what disease results from its defect?"
    a: "Nucleotide excision repair (NER); defect → xeroderma pigmentosum."
  - q: "Which pathway corrects replication base mismatches, and what disease results from its defect?"
    a: "Mismatch repair (MMR); defect → Lynch syndrome (microsatellite instability)."
  - q: "What lesion does base excision repair handle (classic example)?"
    a: "Single damaged/deaminated bases — e.g., cytosine deaminated to uracil."
  - q: "Homologous recombination repairs what, using what template, and in which phases?"
    a: "Double-strand breaks, using the sister chromatid, in S/G2."
  - q: "Defects in homologous recombination appear in which conditions?"
    a: "BRCA1/2, Fanconi anemia, and ataxia-telangiectasia (ATM)."
  - q: "How does nonhomologous end joining repair double-strand breaks, and why is it error-prone?"
    a: "It directly religates the broken ends without a template (any phase)."
  - q: "Vignette: right-sided colon cancer, family history, microsatellite instability — defective pathway?"
    a: "Mismatch repair (Lynch syndrome)."
  - q: "Trap: NER vs MMR — which fixes UV dimers and which fixes replication errors?"
    a: "NER fixes UV dimers (xeroderma); MMR fixes replication errors (Lynch)."
references:
  - "LIR §DNA repair"                       # primary (biochemistry)
  - "ROBBINS §DNA repair defects and cancer" # cross-reference (pathology)
```

**Concept.** Cells repair DNA continuously, and each system handles a characteristic lesion
— the high-yield move is matching the broken pathway to its disease. Nucleotide excision
repair (NER) removes bulky, helix-distorting lesions such as UV-induced pyrimidine dimers:
endonucleases cut out an oligonucleotide containing the damage, then polymerase and ligase
fill the gap (works in G1). Base excision repair (BER) fixes single damaged bases — including
the spontaneous deamination of cytosine to uracil — using a glycosylase that removes the base,
an AP endonuclease that cleaves the abasic site, then fill-in and ligation. Mismatch repair
(MMR) corrects base–base mismatches and small insertion/deletion loops that slip past
proofreading during replication (works in G2/S). Double-strand breaks are repaired either by
nonhomologous end joining (NHEJ), which directly religates the ends (error-prone, any phase),
or homologous recombination (HR), which copies from the sister chromatid (high-fidelity,
requires S/G2). Each pathway carries a signature disease when it fails.

**Key facts.**
- NER → UV/bulky dimers; defect = xeroderma pigmentosum.
- BER → single damaged/deaminated bases (C→U); glycosylase + AP endonuclease.
- MMR → replication mismatches; defect = Lynch syndrome (microsatellite instability).
- HR → double-strand breaks via sister chromatid; defect = BRCA1/2, Fanconi anemia, ataxia-telangiectasia (ATM).
- NHEJ → direct end-joining; error-prone; defects → some immunodeficiencies.

**Clinical correlation.** Xeroderma pigmentosum: severe photosensitivity, many early skin
cancers — patients must avoid sunlight. Lynch syndrome: early right-sided colon and
endometrial cancer; microsatellite-unstable tumors respond to checkpoint inhibitors. BRCA1/2:
hereditary breast/ovarian cancer; PARP inhibitors exploit the HR defect (synthetic lethality).
Ataxia-telangiectasia: cerebellar ataxia, telangiectasias, radiation sensitivity, IgA deficiency.

**Differentiating traps.**
- NER = UV dimers (xeroderma); MMR = replication errors (Lynch) — the classic swap.
- BER specifically handles cytosine → uracil deamination.
- HR needs a sister chromatid (S/G2); NHEJ doesn't (any phase, error-prone).

**Vignette signature.** "Child, extreme UV sensitivity, multiple skin cancers" → NER/xeroderma.
"Right-sided colon cancer, family history, microsatellite instability" → MMR/Lynch.
"Breast + ovarian cancer family treated with a PARP inhibitor" → HR/BRCA.

**Mnemonic.** "MMR fixes Mismatches Made in replication." "Xeroderma = no NER under the sun."

**Check.**
1. A child with extreme UV sensitivity develops multiple skin cancers in childhood. Which
   repair pathway is defective? *(→ key)*
2. A colon tumor shows microsatellite instability in a Lynch syndrome family. Which repair
   pathway is defective? *(→ key)*

**DNA repair summary**

| Pathway | Lesion repaired | Disease when defective |
|---|---|---|
| Nucleotide excision repair (NER) | Bulky/UV pyrimidine dimers | Xeroderma pigmentosum |
| Base excision repair (BER) | Single damaged/deaminated bases (C→U) | (rare; oxidative damage accumulation) |
| Mismatch repair (MMR) | Replication base mismatches, indel loops | Lynch syndrome (HNPCC) |
| Homologous recombination (HR) | Double-strand breaks (uses sister chromatid) | BRCA1/2, Fanconi anemia, ataxia-telangiectasia |
| Nonhomologous end joining (NHEJ) | Double-strand breaks (direct, error-prone) | Some immunodeficiencies |

---

### Mutation types

```yaml
title: Mutation types
category: DNA metabolism
system: molecular biology
high_yield: true
tags: [silent, missense, nonsense, frameshift, splice-site, reading-frame]
cases: []
flashcards:
  - q: "What is a silent mutation?"
    a: "A base change that still specifies the same amino acid (code degeneracy/wobble at the 3rd base); usually no effect."
  - q: "What is a missense mutation (with the classic example)?"
    a: "One amino acid is swapped for another — e.g., sickle cell (Glu→Val at β-globin position 6)."
  - q: "What does a nonsense mutation create?"
    a: "A premature stop codon, truncating the protein."
  - q: "What causes a frameshift mutation?"
    a: "An insertion or deletion of bases not divisible by three, shifting the reading frame."
  - q: "What do splice-site mutations cause?"
    a: "Disrupted intron removal → intron retention or exon skipping."
  - q: "Duchenne vs Becker — which results from an in-frame mutation?"
    a: "Becker (in-frame → partial dystrophin); Duchenne is out-of-frame (no dystrophin)."
  - q: "Trap: is a 3-base deletion a frameshift?"
    a: "No — it is in-frame; a frameshift requires an indel not divisible by three."
references:
  - "LIR §Mutations"          # primary (biochemistry)
  - "THOMPSON §Mutation"      # cross-reference (genetics)
```

**Concept.** A mutation is a change in DNA sequence, and its consequence depends on what it
does to the encoded protein. A **silent** (synonymous) mutation changes a base but, because
the code is degenerate (usually at the third "wobble" position), still specifies the same
amino acid — typically no effect. A **missense** mutation swaps one amino acid for another:
conservative if chemically similar, nonconservative if not (sickle cell is the classic
nonconservative missense). A **nonsense** mutation creates a premature stop codon, truncating
the protein. A **frameshift** comes from inserting or deleting a number of bases *not* divisible
by three, which shifts the reading frame and usually scrambles everything downstream plus an
early stop — generally the most damaging. **Splice-site** mutations disrupt intron removal,
causing intron retention or exon skipping (seen in some β-thalassemias). Severity roughly
tracks how much protein is altered: silent < missense < nonsense ≈ frameshift.

**Key facts.**
- Silent: same amino acid (degeneracy/wobble at 3rd base).
- Missense: one amino acid changed (sickle cell = Glu→Val).
- Nonsense: premature stop codon → truncated protein.
- Frameshift: indel *not* a multiple of 3 → shifted frame, usually severe.
- Splice-site: disrupts splicing → intron retention/exon skipping.

**Clinical correlation.** Sickle cell = missense (Glu→Val at β-globin position 6).
β-thalassemia = often splice-site or nonsense → reduced/absent β-globin. Duchenne muscular
dystrophy = frameshift/nonsense → no dystrophin (severe); Becker = in-frame deletion → partly
functional dystrophin (milder).

**Differentiating traps.**
- A frameshift requires an indel *not* divisible by 3; a 3-base deletion is in-frame
  (Becker; CF ΔF508 removes a single amino acid).
- Nonsense = premature stop; missense = changed amino acid — distinct.
- Severity ladder: silent (least) → frameshift/nonsense (most).

**Vignette signature.** "Single base change creating a stop codon" → nonsense. "One-nucleotide
insertion scrambling the downstream sequence" → frameshift. "In-frame 3-base deletion, milder
phenotype" → Becker / CF ΔF508.

**Mnemonic.** "Frameshift unless the indel comes in 3s."

**Check.**
1. A two-nucleotide insertion occurs in a coding region. What type of mutation is it? *(→ key)*
2. Duchenne (no dystrophin) versus Becker (partial dystrophin) — which results from an
   in-frame mutation? *(→ key)*

---

### Transcription

```yaml
title: Transcription
category: gene expression
system: molecular biology
high_yield: true
tags: [RNA-polymerase, template-strand, TATA-box, enhancer, alpha-amanitin]
cases: []
flashcards:
  - q: "Which eukaryotic RNA polymerase synthesizes mRNA?"
    a: "RNA polymerase II."
  - q: "What do RNA pol I, II, and III make (in order)?"
    a: "rRNA, mRNA, and tRNA."
  - q: "Does RNA polymerase need a primer?"
    a: "No — unlike DNA polymerase, it needs no primer."
  - q: "Which strand is read during transcription, and which one matches the mRNA?"
    a: "The template (antisense) strand is read; the coding (sense) strand matches the mRNA (U for T)."
  - q: "What does α-amanitin inhibit, and where is it from?"
    a: "RNA polymerase II; from death cap mushrooms (Amanita phalloides)."
  - q: "What does rifampin inhibit?"
    a: "Bacterial RNA polymerase."
  - q: "Vignette: liver failure after foraged mushrooms, RNA pol II inhibited — toxin?"
    a: "α-amanitin."
references:
  - "LIR §Transcription"      # primary (biochemistry)
  - "KATZUNG §Rifamycins"     # cross-reference (pharmacology)
```

**Concept.** Transcription copies a gene's template strand into RNA, built 5′→3′ by RNA
polymerase, which — unlike DNA polymerase — needs no primer. Eukaryotes use three nuclear
polymerases: **RNA pol I** makes rRNA (in the nucleolus), **pol II** makes mRNA, and **pol
III** makes tRNA. The template ("antisense") strand is the one actually read; the coding
("sense") strand matches the mRNA sequence (with U replacing T). RNA pol II binds the
promoter — often a TATA box about 25 bases upstream — with help from general transcription
factors, while enhancers are distant sequences that boost transcription by looping to the
promoter. The toxin **α-amanitin** from death cap mushrooms specifically inhibits RNA pol II,
the high-yield clinical hook. The mRNA is first made as a precursor (pre-mRNA/hnRNA) that must
be processed before export.

**Key facts.**
- RNA pol I → rRNA; pol II → mRNA; pol III → tRNA (order r-m-t).
- RNA synthesis 5′→3′, no primer needed.
- Template/antisense strand is read; coding/sense strand = mRNA (U for T).
- Promoter often has a TATA box (~–25); enhancers act at a distance via DNA looping.
- α-amanitin inhibits RNA pol II (death cap, *Amanita phalloides*).

**Clinical correlation.** α-amanitin poisoning → hepatotoxicity from RNA pol II inhibition.
Rifampin inhibits *bacterial* RNA polymerase (antitubercular; turns secretions orange).
Actinomycin D also blocks transcription.

**Differentiating traps.**
- RNA pol I/II/III → rRNA/mRNA/tRNA (r-m-t order).
- α-amanitin → eukaryotic pol II; rifampin → bacterial RNA polymerase. Don't swap.
- The template strand is read, but the mRNA sequence equals the coding strand (U for T).

**Vignette signature.** "Wild mushroom, liver failure, RNA pol II inhibited" → α-amanitin.
"Antibiotic inhibiting bacterial RNA polymerase, orange body fluids" → rifampin.

**Mnemonic.** "I, II, III → rRNA, mRNA, tRNA." "α-amAnitin → pol II."

**Check.**
1. A patient develops fulminant hepatic failure after eating foraged mushrooms; the toxin
   inhibits RNA polymerase II. Name the toxin. *(→ key)*
2. Which eukaryotic RNA polymerase synthesizes mRNA? *(→ key)*

---

### Post-transcriptional modification

```yaml
title: Post-transcriptional modification
category: gene expression
system: molecular biology
high_yield: true
tags: [5-cap, poly-A-tail, splicing, spliceosome, snRNP, anti-smith]
cases: []
flashcards:
  - q: "What is added to the 5′ end of pre-mRNA, and why?"
    a: "A 7-methylguanosine cap — for protection, stability, and ribosome binding."
  - q: "What is added to the 3′ end of pre-mRNA, and after what signal?"
    a: "A poly-A tail (~200 adenines), after cleavage at the AAUAAA signal; template-independent."
  - q: "What machinery removes introns, and what intermediate forms?"
    a: "The spliceosome (snRNPs); a lariat intermediate (GU…AG intron boundaries)."
  - q: "Where do capping, polyadenylation, and splicing occur?"
    a: "In the nucleus, before the mRNA is exported."
  - q: "Anti-Smith (anti-snRNP) antibodies are highly specific for which disease?"
    a: "Systemic lupus erythematosus (SLE)."
  - q: "Trap: which end gets the cap and which gets the poly-A tail?"
    a: "Cap at the 5′ end; poly-A tail at the 3′ end."
references:
  - "LIR §RNA processing"                       # primary (biochemistry)
  - "ROBBINS §Systemic lupus erythematosus"     # cross-reference (pathology)
```

**Concept.** Eukaryotic pre-mRNA (hnRNA) is processed in the nucleus before it can be exported
and translated, through three modifications. A **7-methylguanosine 5′ cap** is added to the
5′ end, protecting it and helping ribosomes bind. A **poly-A tail** of ~200 adenines is added
to the 3′ end after cleavage at a polyadenylation signal (AAUAAA); it is template-independent
and promotes stability and export. **Introns are spliced out and exons joined** by the
spliceosome, a complex of small nuclear ribonucleoproteins (snRNPs) that recognizes GU at the
5′ splice site and AG at the 3′ site, forming a lariat intermediate. Only after capping,
polyadenylation, and splicing does the mature mRNA leave the nucleus.

**Key facts.**
- 5′ cap = 7-methylguanosine (export, stability, ribosome binding).
- 3′ poly-A tail ~200 A's; added after cleavage at AAUAAA; template-independent.
- Splicing by the spliceosome (snRNPs); GU…AG intron boundaries; lariat intermediate.
- All three occur in the nucleus before export.

**Clinical correlation.** Anti-Smith (anti-snRNP) antibodies are highly *specific* for SLE.
Splice-site mutations cause disease (β-thalassemia). Poly-A tail length influences mRNA half-life.

**Differentiating traps.**
- Cap = 5′ end; poly-A tail = 3′ end — don't swap ends.
- Polyadenylation is template-independent; splicing removes introns and keeps exons.
- These are nuclear, pre-export events.

**Vignette signature.** "Malar rash + antibodies to snRNPs" → anti-Smith → SLE. "~200 adenines
added to the 3′ end" → polyadenylation. "7-methylguanosine at the 5′ end" → capping.

**Mnemonic.** "snRNPs (snurps) splice; anti-Smith = SLE-specific." "Cap the 5′, tail the 3′."

**Check.**
1. Antibodies against snRNPs (spliceosome components) are highly specific for which disease?
   *(→ key)*
2. Which processing step adds roughly 200 nucleotides to the 3′ end of pre-mRNA? *(→ key)*

---

### Alternative splicing & tissue-specific isoforms

```yaml
title: Alternative splicing & tissue-specific isoforms
category: gene expression
system: molecular biology
high_yield: true
tags: [alternative-splicing, isoforms, proteome-diversity, spliceopathy]
cases: []
flashcards:
  - q: "How does alternative splicing increase protein diversity?"
    a: "One gene's pre-mRNA includes or excludes different exons, yielding multiple protein isoforms."
  - q: "Give an example of tissue-specific isoforms from alternative splicing."
    a: "Distinct troponin/tropomyosin isoforms in skeletal vs cardiac muscle (or membrane-bound vs secreted IgM)."
  - q: "Is alternative splicing a mutation?"
    a: "No — it is a regulated choice of which exons to include."
  - q: "Which disease is a spliceopathy from sequestered MBNL?"
    a: "Myotonic dystrophy (expanded CTG repeats)."
  - q: "Vignette: the same gene yields a different protein in cardiac vs skeletal muscle — mechanism?"
    a: "Alternative splicing."
references:
  - "LIR §Regulation of gene expression"   # primary (biochemistry)
```

**Concept.** Alternative splicing lets one gene encode multiple protein isoforms by including
or excluding particular exons during splicing, expanding proteome diversity far beyond the
gene count. Different tissues splice the same pre-mRNA differently to make tissue-specific
variants — for example, distinct troponin/tropomyosin isoforms in skeletal versus cardiac
muscle, or the membrane-bound versus secreted forms of an antibody from one immunoglobulin
transcript. This is a major reason ~20,000 human genes yield a far larger number of proteins.

**Key facts.**
- One pre-mRNA → multiple mRNAs/proteins by selective exon inclusion.
- Generates tissue-specific isoforms (muscle protein variants; membrane vs secreted IgM).
- Expands the proteome well beyond gene number.

**Clinical correlation.** Myotonic dystrophy is a *spliceopathy*: expanded CTG repeats sequester
the splicing regulator MBNL, mis-splicing many transcripts (see Trinucleotide Repeat &
Cancer). Aberrant splicing also
arises in cancer.

**Differentiating traps.**
- Alternative splicing is a *regulated choice* of exons, not a mutation.
- Distinct from alternative promoters/polyadenylation, though all increase diversity.

**Vignette signature.** "Same gene, different protein in cardiac vs skeletal muscle" →
alternative splicing. "Membrane-bound vs secreted antibody from one transcript" → alternative
splicing.

**Check.**
1. How can a single gene produce different protein isoforms in skeletal versus cardiac
   muscle? *(→ key)*

---

### RNA types & translation

```yaml
title: RNA types & translation
category: gene expression
system: molecular biology
high_yield: true
tags: [mRNA, tRNA, rRNA, ribozyme, ribosome, start-codon, stop-codon, EF-2]
cases: []
flashcards:
  - q: "What are the roles of mRNA, tRNA, and rRNA?"
    a: "mRNA carries the code; tRNA brings amino acids (anticodon pairs the codon); rRNA forms the catalytic ribosome."
  - q: "Why is the ribosome called a ribozyme?"
    a: "rRNA itself catalyzes peptide-bond formation (peptidyl transferase activity)."
  - q: "Ribosome subunit composition in eukaryotes vs prokaryotes?"
    a: "Eukaryotic 40S + 60S = 80S; prokaryotic 30S + 50S = 70S."
  - q: "What is the start codon, and which amino acid does it specify?"
    a: "AUG (methionine)."
  - q: "Name the three stop codons."
    a: "UAA, UAG, UGA."
  - q: "In which directions is mRNA read and the protein built?"
    a: "mRNA is read 5′→3′; protein is built N-terminus → C-terminus."
  - q: "Which antibiotics target the 30S ribosomal subunit?"
    a: "Aminoglycosides and tetracyclines."
  - q: "Which antibiotics target the 50S ribosomal subunit?"
    a: "Macrolides, clindamycin, chloramphenicol, and linezolid."
  - q: "Diphtheria toxin halts translation by modifying what?"
    a: "Elongation factor 2 (EF-2), by ADP-ribosylation."
references:
  - "LIR §Translation"                          # primary (biochemistry)
  - "KATZUNG §Protein synthesis inhibitors"     # cross-reference (pharmacology)
```

**Concept.** Translation reads mRNA codons to build a polypeptide using three RNA types:
**mRNA** carries the code, **tRNA** brings amino acids (its anticodon pairing the codon), and
**rRNA** forms the catalytic core of the ribosome — meaning the ribosome is a *ribozyme*, with
rRNA itself catalyzing peptide-bond formation. The ribosome (eukaryotic 40S + 60S = 80S;
prokaryotic 30S + 50S = 70S) reads mRNA 5′→3′ and builds protein from N-terminus to
C-terminus. **Initiation** starts at the AUG start codon (methionine). **Elongation** brings
aminoacyl-tRNA into the A site (elongation factors + GTP), peptidyl transferase (rRNA) forms
the bond, and translocation advances the ribosome one codon. **Termination** occurs at a stop
codon (UAA, UAG, UGA) when release factors free the chain. The genetic code is degenerate,
unambiguous, and nearly universal, with wobble at the third base. The prokaryote/eukaryote
ribosome difference is the target of many antibiotics.

**Key facts.**
- mRNA = code; tRNA = adaptor; rRNA = ribosome (ribozyme).
- Ribosome: euk 40S+60S=80S; prok 30S+50S=70S. Reads 5′→3′, builds N→C.
- Start = AUG (Met); stops = UAA, UAG, UGA.
- Peptidyl transferase activity = rRNA.
- Code: degenerate, unambiguous, near-universal; wobble at 3rd base.

**Clinical correlation.** Antibiotics by target: aminoglycosides and tetracyclines hit the
**30S**; macrolides, clindamycin, chloramphenicol, and linezolid hit the **50S**. Diphtheria
toxin and *Pseudomonas* exotoxin A ADP-ribosylate eukaryotic EF-2, halting elongation. Shiga
and Shiga-like toxins inactivate the 60S subunit (depurinate rRNA).

**Differentiating traps.**
- rRNA (not protein) catalyzes the peptide bond — a ribozyme.
- 30S inhibitors (aminoglycosides, tetracyclines) vs 50S inhibitors (the rest).
- Protein grows N→C while mRNA is read 5′→3′.

**Vignette signature.** "Toxin ADP-ribosylates EF-2" → diphtheria / *Pseudomonas*. "Antibiotic
binds 30S and causes mRNA misreading" → aminoglycoside. "Peptide bond formed by RNA" →
peptidyl transferase (ribozyme).

**Mnemonic.** "Buy AT 30, CCEL at 50" — **A**minoglycosides/**T**etracyclines = 30S;
**C**hloramphenicol, **C**lindamycin, **E**rythromycin (macrolides), **L**inezolid = 50S.

**Check.**
1. Which ribosomal component catalyzes peptide-bond formation? *(→ key)*
2. Diphtheria toxin halts protein synthesis by modifying which elongation factor? *(→ key)*

---

### Post-transcriptional gene silencing (miRNA & siRNA)

```yaml
title: Post-transcriptional gene silencing (miRNA & siRNA)
category: gene expression
system: molecular biology
high_yield: true
tags: [miRNA, siRNA, RISC, gene-silencing, oncomir]
cases: []
flashcards:
  - q: "What is a miRNA, and roughly how large?"
    a: "An endogenous ~22-nucleotide RNA that base-pairs with a target mRNA (usually the 3′ UTR)."
  - q: "miRNA imperfect vs strong pairing — what is the result of each?"
    a: "Imperfect pairing → translational repression; strong complementarity → mRNA degradation."
  - q: "How does siRNA act on its target?"
    a: "Perfect pairing → mRNA cleavage (via RISC); often introduced exogenously/therapeutically."
  - q: "Which complex do both miRNA and siRNA act through?"
    a: "RISC."
  - q: "Trap: do these silence before or after transcription?"
    a: "After transcription (they target mRNA), unlike DNA methylation which silences the gene itself."
references:
  - "LIR §Regulation of gene expression"   # primary (biochemistry)
```

**Concept.** Small non-coding RNAs regulate gene expression after transcription.
**microRNAs (miRNAs)** are endogenous ~22-nucleotide RNAs that base-pair with complementary
sequences in target mRNAs (usually the 3′ UTR); imperfect pairing represses translation, while
strong complementarity triggers mRNA degradation — both via the RISC complex. **Small
interfering RNAs (siRNAs)** use the same RISC machinery but pair perfectly and cleave the
target; they can be introduced experimentally or therapeutically to knock down a chosen gene.

**Key facts.**
- miRNA: endogenous, ~22 nt, imperfect pairing → translational repression (or degradation).
- siRNA: perfect pairing → mRNA cleavage; often exogenous/therapeutic.
- Both act via RISC and target mRNA (post-transcriptional).
- Dysregulated miRNAs can be oncogenic ("oncomiRs") or tumor-suppressive.

**Clinical correlation.** miRNA expression profiles serve as cancer biomarkers. siRNA-based
drugs silence disease genes (e.g., in hereditary amyloidosis and hypercholesterolemia).

**Differentiating traps.**
- miRNA = usually imperfect pairing/repression; siRNA = perfect pairing/cleavage.
- These silence *after* transcription (target mRNA), unlike DNA methylation (silences the gene).

**Vignette signature.** "Short endogenous RNA pairs with an mRNA 3′ UTR to block translation"
→ miRNA. "Engineered RNA used to knock down a specific gene" → siRNA.

**Check.**
1. A short endogenous RNA base-pairs imperfectly with a target mRNA's 3′ UTR and blocks its
   translation. What is it? *(→ key)*

---

### Molecular lab techniques

```yaml
title: Molecular lab techniques
category: laboratory methods
system: molecular biology
high_yield: true
tags: [southern, northern, western, PCR, RT-PCR, FISH, ELISA, microarray, flow-cytometry, karyotype]
cases: []
flashcards:
  - q: "Southern, Northern, and Western blots detect what, respectively?"
    a: "DNA, RNA, and protein (mnemonic: SNoW DRoP)."
  - q: "What does a Southwestern blot detect?"
    a: "DNA-binding proteins (e.g., transcription factors)."
  - q: "What does RT-PCR detect that ordinary PCR cannot, and how?"
    a: "RNA — by first converting it to cDNA (e.g., RNA viruses, HIV viral load)."
  - q: "Which technique confirms a microdeletion too small to see on a karyotype?"
    a: "FISH (fluorescence in situ hybridization)."
  - q: "What does ELISA detect?"
    a: "A specific antigen or antibody (e.g., HIV screening)."
  - q: "What does flow cytometry quantify?"
    a: "Cell-surface markers (e.g., CD4 counts, leukemia immunophenotyping)."
  - q: "What is karyotyping used to detect?"
    a: "Whole-chromosome aneuploidy and large translocations."
  - q: "Vignette: detecting an RNA virus — which technique?"
    a: "RT-PCR."
references:
  - "LIR §Recombinant DNA and biotechnology"   # primary (biochemistry)
  - "THOMPSON §Laboratory methods"             # cross-reference (genetics)
```

**Concept.** Diagnostic techniques are distinguished mainly by the molecule they detect — a
frequent board point. **Blots:** Southern detects DNA, Northern detects RNA, Western detects
protein, and Southwestern detects DNA-binding proteins (e.g., transcription factors). **PCR**
amplifies DNA exponentially with primers, dNTPs, and a heat-stable polymerase through cycles
of denaturation, annealing, and extension; **RT-PCR** first converts RNA to cDNA, enabling
detection of RNA viruses. **ELISA** uses antibodies to detect a specific antigen or antibody
(e.g., HIV screening). **FISH** uses fluorescent probes to localize specific DNA sequences on
chromosomes — ideal for microdeletions (Williams, DiGeorge) too small to see on a karyotype.
**Microarrays** measure expression of thousands of genes at once. **Flow cytometry** quantifies
cell-surface markers (e.g., CD4 counts). **Karyotyping** visualizes whole chromosomes for
aneuploidy and translocations. **CRISPR-Cas9** edits genes at targeted sequences.

**Key facts.**
- Southern = DNA, Northern = RNA, Western = protein, Southwestern = DNA-binding proteins.
- PCR amplifies DNA; RT-PCR detects RNA via cDNA → RNA viruses.
- ELISA = antigen/antibody detection (HIV screen).
- FISH = fluorescent probe for specific loci → microdeletions.
- Microarray = many-gene expression; flow cytometry = surface markers (CD4).
- Karyotype = whole-chromosome aneuploidy/translocations.

**Clinical correlation.** HIV: ELISA screen, RT-PCR for viral load. DiGeorge/Williams
microdeletions confirmed by FISH. CML t(9;22) detected by FISH/karyotype. Flow cytometry for
CD4 counts and leukemia immunophenotyping.

**Differentiating traps.**
- "SNoW DRoP" fixes Southern/Northern/Western → DNA/RNA/Protein.
- FISH for microdeletions (too small for karyotype); karyotype for whole-chromosome changes.
- RNA targets require RT-PCR (RNA → cDNA first).

**Vignette signature.** "Detecting an RNA virus" → RT-PCR. "Confirming a 22q11 microdeletion"
→ FISH. "Measuring mRNA level of one gene" → Northern blot. "Identifying a transcription factor"
→ Southwestern blot.

**Mnemonic.** "SNoW DRoP" — **S**outhern→**D**NA, **N**orthern→**R**NA, **W**estern→**P**rotein.

**Check.**
1. Which blot detects RNA? *(→ key)*
2. A clinician must confirm a 22q11 microdeletion too small to see on a standard karyotype.
   Which technique? *(→ key)*

**Lab technique summary**

| Technique | Target | Classic clinical use |
|---|---|---|
| Southern blot | DNA | Detecting a specific DNA sequence/mutation |
| Northern blot | RNA | mRNA expression level of a gene |
| Western blot | Protein | Protein detection (historically HIV confirmation) |
| Southwestern blot | DNA-binding proteins | Identifying transcription factors |
| PCR / RT-PCR | DNA / RNA (via cDNA) | Amplification; RT-PCR for RNA viruses (HIV viral load) |
| ELISA | Antigen/antibody | HIV screening |
| FISH | Specific chromosomal loci | Microdeletions (Williams, DiGeorge), translocations |
| Microarray | DNA/RNA expression | Genome-wide expression comparison |
| Flow cytometry | Cell-surface markers | CD4 counts, leukemia immunophenotyping |
| Karyotype | Whole chromosomes | Aneuploidy, large translocations |

---

### Cross-reference stubs

- **Cytoskeleton & motor proteins** (kinesin, dynein, microtubules) — full module in
  *Cell & Molecular Biology*.
- **Vesicular trafficking** (mannose-6-phosphate targeting) — full module in *Cell &
  Molecular Biology*. The associated disease, **I-cell disease**, is a full module in
  *Biochemistry — Lysosomal Storage Diseases*.

---

## Section answer key

**DNA structure & chromatin organization**
1. The GC-rich segment (three hydrogen bonds per G–C pair → higher melting temperature).
2. Silenced — promoter methylation represses transcription (a common route to tumor
   suppressor inactivation).

**DNA replication**
1. Fluoroquinolones (inhibit bacterial DNA gyrase = topoisomerase II, plus topo IV).
2. Human topoisomerase II (etoposide/teniposide; irinotecan/topotecan inhibit topo I).
3. Telomerase — a reverse transcriptase that extends chromosome 3′ ends using its own RNA
   template.

**DNA repair pathways**
1. Nucleotide excision repair (NER) — xeroderma pigmentosum.
2. Mismatch repair (MMR) — Lynch syndrome.

**Mutation types**
1. A frameshift (insertion not divisible by three shifts the reading frame).
2. Becker (an in-frame mutation preserves partial dystrophin; Duchenne is out-of-frame).

**Transcription**
1. α-amanitin (from *Amanita phalloides*).
2. RNA polymerase II.

**Post-transcriptional modification**
1. Systemic lupus erythematosus (anti-Smith / anti-snRNP antibodies are highly specific).
2. Polyadenylation (the poly-A tail).

**Alternative splicing & tissue-specific isoforms**
1. Alternative splicing — selectively including/excluding exons yields tissue-specific isoforms.

**RNA types & translation**
1. rRNA (the ribosome is a ribozyme; peptidyl transferase activity is rRNA).
2. Elongation factor 2 (EF-2), ADP-ribosylated by diphtheria toxin.

**Post-transcriptional gene silencing**
1. A microRNA (miRNA).

**Molecular lab techniques**
1. Northern blot.
2. FISH (fluorescence in situ hybridization).
