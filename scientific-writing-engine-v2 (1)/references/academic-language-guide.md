# Academic Language & Syntactic Style Guide

This guide establishes the vocabulary, syntactic architecture, epistemic hedging, and transition matrices required for writing polished, journal-ready scientific prose.

---

## 1. High-Precision Academic Verb Matrix

Avoid generic verbs such as `do`, `get`, `make`, `show`, `change`, `look at`. Use precise academic verbs tailored to specific biological actions:

| Informal / Weak Verb | Precision Replacement Verb | Contextual Example |
|---|---|---|
| *look at / check* | `evaluate`, `assess`, `examine`, `probe`, `investigate`, `interrogate` | *"To interrogate the integrity of the mitochondrial membrane..."* |
| *show / see* | `reveal`, `demonstrate`, `manifest`, `exhibit`, `display`, `unveil` | *"Immunostaining revealed discrete synaptic puncta..."* |
| *cause / lead to* | `elicit`, `trigger`, `precipitate`, `drive`, `instigate`, `induce` | *"Alpha-synuclein oligomers elicited severe neuroinflammatory responses..."* |
| *change / alter* | `modulate`, `alter`, `reprogram`, `shift`, `skew`, `perturb` | *"Perfusion significantly modulated metabolic gene signatures..."* |
| *fix / make better* | `ameliorate`, `mitigate`, `attenuate`, `counteract`, `rescue`, `alleviate` | *"Small-molecule inhibition attenuated barrier breakdown..."* |
| *stop / block* | `abrogate`, `suppress`, `impair`, `blunt`, `hinder`, `abolish` | *"Pre-treatment completely abrogated caspase activation..."* |
| *prove mechanism* | `substantiate`, `corroborate`, `delineate`, `decipher`, `elucidate` | *"Our findings delineate a deterministic role for STING..."* |

---

## 2. Epistemic Calibrations (Claim Bounding)

Scientific credibility depends on modulating the strength of verbs to match the weight of experimental evidence:

```
[Definite Proof: Knockout + Rescue + Clinical]
   → "demonstrates", "establishes", "proves", "is required for"

[Robust Corroboration: Multi-assay Concordance]
   → "indicates", "supports", "substantiates", "points to", "corroborates"

[Plausible Hypothesis: Correlative / Indirect Data]
   → "suggests", "implies", "raises the possibility that", "is consistent with"

[Preliminary Speculation: Early Observation]
   → "may contribute to", "warrants further exploration", "could potentially reflect"
```

### Contrast Examples

- **Overclaimed**: "RNA-seq data proves that Parkin deficiency causes cell death through the cGAS pathway."
- **Calibrated (Correct)**: "Transcriptomic profiling, coupled with targeted pharmacological inhibition, indicates that cGAS activation substantially contributes to Parkin deficiency-mediated neuronal demise."

---

## 3. Cohesion & Narrative Transition Matrix

To eliminate choppy, isolated sentences, use structural transitions to link consecutive thoughts:

| Narrative Purpose | Recommended Logical Connectors & Clauses |
|---|---|
| **Forward Hypothesis** | `To test whether...`, `Prompted by this observation, we asked whether...`, `To dissect the mechanism underlying...` |
| **Corroborating Evidence** | `Consistently, ...`, `In agreement with this finding, ...`, `Corroborating these observations, ...`, `In parallel, ...` |
| **Unexpected / Contrast Finding** | `Strikingly, ...`, `Intriguingly, ...`, `In contrast to static cultures, ...`, `Unexpectedly, however, ...` |
| **Synthesizing Intermediate Conclusion** | `Together, these findings indicate that...`, `Collectively, these data establish that...`, `These observations underscore...` |
| **Addressing Methodological Cavity** | `To rule out potential non-specific effects, ...`, `To ensure that this phenotype was not an artifact of..., we performed...` |

---

## 4. Syntactic Architecture: Information Packing & Rhythm

Journal-level biomedical writing achieves high information density through specific grammatical constructions:

### Pattern A: Participial Lead-in for Methodological Economy
Instead of two separate sentences:
> *Weak*: We cultured organoids under perfusion for 30 days. Then we performed single-cell RNA sequencing.
> *High-Density*: "Having maintained the organoids under continuous dynamic perfusion for 30 days, we conducted single-cell transcriptomic profiling to delineate emerging cellular subpopulations."

### Pattern B: Absolute Construction for Multi-variable Reporting
Instead of repetitive "was":
> *Weak*: The expression of TH was significantly decreased. Also, the level of cleaved Caspase-3 was markedly increased.
> *High-Density*: "Mutant organoids exhibited a pronounced neurodegenerative phenotype, characterized by a 60% reduction in TH+ neuronal density accompanied by a 3.5-fold elevation in cleaved Caspase-3."

### Pattern C: Active Predication over Nominalization
Avoid burying verbs inside heavy abstract nouns:
> *Weak*: The realization of the differentiation of stem cells was achieved by the application of neural induction medium.
> *High-Density*: "Neural induction medium drove efficient differentiation of stem cells into polarized neuroepithelial tissues."
