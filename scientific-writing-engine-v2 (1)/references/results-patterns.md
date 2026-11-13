# Results Patterns & Scientific Storytelling Guide

This guide establishes the grammar, progressive structure, and evidence-linking logic for drafting and organizing the Results section of high-impact biomedical manuscripts.

---

## The Macro Results Storyline Progression

High-impact biomedical studies never present assays haphazardly. They follow a predictable 6-act narrative arc:

```
[Act 1: System Construction & Baseline Structural Validation] (Fig. 1)
                               ↓
[Act 2: Multi-lineage Differentiation, Cytoarchitecture & Maturation] (Fig. 2)
                               ↓
[Act 3: Baseline Functional Hallmarks & Stimulus-Response] (Fig. 3)
                               ↓
[Act 4: Disease Induction & Multi-Scale Pathological Phenotyping] (Fig. 4)
                               ↓
[Act 5: Unbiased Molecular & Mechanistic Dissection (e.g., RNA-seq / Proteomics)] (Fig. 5)
                               ↓
[Act 6: Targeted Rescue, Genetic Validation & Pharmacological Proof-of-Concept] (Fig. 6)
```

---

## The Micro Results Unit: The 6-Element Sentence Sequence

Within each individual subsection of Results, every paragraph must function as a self-contained scientific syllogism. Use this 6-element sentence sequence:

### Element 1: Scientific Question / Biological Rationale
- *Role*: State why the experiment was performed before describing what was done.
- *Examples*:
  - "To investigate whether interstitial fluid shear stress modulates the differentiation of neural progenitor cells (NPCs), we first..."
  - "Having verified the cellular identity of our organoids, we next asked whether exposure to [Perturbation] induces selective neurotoxicity..."

### Element 2: Experimental Strategy & Methodological Setup
- *Role*: Briefly name the assay, biological material, and timeline, citing the primary figure panel.
- *Examples*:
  - "Human iPSCs carrying the [Mutation] were differentiated in our microfluidic culture chambers for 45 days and monitored via live-cell confocal microscopy (Figure 2A)."
  - "To assess barrier integrity, we measured trans-epithelial electrical resistance (TEER) and perfused 4-kDa FITC-dextran across the luminal channel over 72 hours (Figure 3C)."

### Element 3: Primary Qualitative Observation / Phenotypic Finding
- *Role*: Report what was visually or biochemically observed in clear, active terms.
- *Examples*:
  - "Immunofluorescence staining revealed robust formation of organized neural rosette-like structures positive for SOX2 and Nestin throughout the outer ventricular zone (Figure 2B)."
  - "Transmission electron microscopy (TEM) demonstrated extensive mitochondrial fragmentation and loss of cristae integrity in diseased organoids compared with isogenic controls (Figure 4D)."

### Element 4: Rigorous Quantitative Verification & Statistical Annotation
- *Role*: Present exact numerical values, fold-changes, and p-values. Avoid vague terms like "drastically increased" without metrics.
- *Examples*:
  - "Quantification confirmed a 3.4-fold decrease in the density of TH+ dopaminergic neurons in mutant organoids relative to wild-type controls (12.4 ± 1.8% vs. 42.1 ± 3.5%, p < 0.001, Figure 4E)."
  - "Consistently, levels of secreted inflammatory cytokines, including IL-6 and TNF-α, increased by 4.2-fold and 5.1-fold, respectively (p < 0.01, Figure 4F)."

### Element 5: Intermediate Biological Inference (Bounded Interpretation)
- *Role*: Conclude what this specific data point means biologically, without claiming whole-pathway proof prematurely.
- *Examples*:
  - "These data demonstrate that [Condition] impairs the survival and morphological integrity of midbrain dopaminergic lineages in a stage-dependent manner."
  - "Together, these findings indicate that fluid perfusion significantly accelerates organoid functional maturation rather than merely supporting bulk survival."

### Element 6: Forward Transition / Narrative Bridge
- *Role*: Create suspense and smoothly segue into the next experiment.
- *Examples*:
  - "Prompted by this marked loss of neuronal viability, we sought to elucidate the underlying transcriptional cascades governing this neurodegenerative process."
  - "To decipher whether this mitochondrial defect was cell-autonomous or mediated by non-neuronal interactions, we subsequently examined the role of resident microglia."

---

## Results Subsection Heading Formulas

Never use raw assay names as subsection titles (e.g., avoid "RT-PCR and Western Blot Results"). Instead, craft **claim-driven titles** that declare the scientific finding:

| Weak / Descriptive Title | High-Impact Claim-Driven Title |
|---|---|
| *Brain organoid culture on chip* | *Engineering biomimetic human brain organoids with accelerated corticogenesis under dynamic perfusion* |
| *Effect of alpha-synuclein on neurons* | *Pathological alpha-synuclein accumulation drives selective dopaminergic loss and mitochondrial oxidative collapse* |
| *RNA-seq analysis of mutant organoids* | *Transcriptomic profiling identifies aberrant activation of the cGAS-STING inflammatory axis* |
| *Drug treatment results* | *Targeted STING inhibition rescues neuronal loss and alleviates functional electrophysiological deficits* |

---

## Guardrails: Distinguishing Observation from Mechanism

Always enforce strict boundaries in verb choice across the Results section:

1. **Observational Data (Unbiased reporting of assay output)**:
   - Use: `revealed`, `exhibited`, `displayed`, `showed`, `was observed`, `characterized by`.
   - *Example*: "Immunostaining revealed a reduction in TH+ cell density."
2. **Correlative Relationships (Co-occurrence without perturbation proof)**:
   - Use: `correlated with`, `coincided with`, `was accompanied by`, `was associated with`.
   - *Example*: "The loss of dopaminergic neurons was accompanied by an elevation in cleaved caspase-3."
3. **Causal & Mechanistic Conclusions (Requires rescue, knockout, or specific pharmacological inhibition)**:
   - Use: `demonstrated that X mediates Y`, `confirmed that X is required for Y`, `established a causal link between X and Y`.
   - *Constraint*: Only use "mediates" or "causes" if an intervention experiment (e.g., siRNA knockdown, pharmacological antagonist, genetic rescue) successfully reversed the phenotype!
