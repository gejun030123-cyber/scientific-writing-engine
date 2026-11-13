# Scientific Writing Engine (`scientific-writing-engine`)

A reusable, high-impact scientific writing, paragraph rewriting, and peer-review editing engine for biomedical researchers. It translates raw experimental observations into publication-grade academic prose by enforcing rigorous problem-driven logic, figure-driven results storytelling, mechanism-bounded discussion, and high-precision academic English.

---

## 🌟 Core Architecture & Principles

This repository enforces a strict **separation between Scientific Content and Writing Style**:
1. **Scientific Content Layer**: Biological entities, experimental results, numerical measurements, statistical significance, and literature citations originate exclusively from user input and verified domain facts.
2. **Writing Style Layer**: Narrative structure, topic-sentence placement, figure-driven progression, epistemically calibrated verb choices, and logical transitions are guided by this engine.

### The 8 Foundational Rules

1. **Problem-Driven Funnel (Introduction)**: Narrow strictly from clinical/biological burden $\rightarrow$ existing model breakthroughs & limitations $\rightarrow$ critical cellular/microenvironmental gap $\rightarrow$ strategic intervention $\rightarrow$ core mechanistic takeaways.
2. **Figure-Driven Incremental Storytelling (Results)**: Structure results by biological milestones using claim-driven headings and the 6-element sentence cycle (*Rationale $\rightarrow$ Setup & Panel $\rightarrow$ Qualitative Observation $\rightarrow$ Quantitative Metric $\rightarrow$ Bounded Inference $\rightarrow$ Forward Bridge*).
3. **Mechanism-Bounded Evidence Hierarchy**: Strictly demarcate observational claims (`revealed`), correlative trends (`correlated with`), and causal mechanism (`demonstrated that X mediates Y`). Causal claims require targeted rescue or genetic knockdown.
4. **Claim-Driven Topic Sentences**: Open every paragraph with a direct declarative claim summarizing the core finding, followed by 3–5 dense evidential sentences.
5. **Quantitative & Statistical Precision**: Always report absolute metrics/fold-changes, variance ($\pm \text{SD}$ or $\text{SEM}$), and exact $P$-values. Eliminate unsupported subjective intensifiers.
6. **Discussion Conceptual Synthesis & Epistemic Humility**: Avoid regurgitating raw numbers from Results. Focus on human pathology concordance, molecular model synthesis, explicit limitations (maturity, vascularization, throughput), and translational horizons.
7. **Dense Syntactic Packing & Active Voice**: Maximize information density using participial lead-ins, absolute constructions, and high-precision academic verbs.
8. **Strict Content Fidelity Guardrail**: Never fabricate measurements or speculate unverified biological pathways.

---

## 📂 Repository Structure

```text
scientific-writing-engine/
├── SKILL.md                                 # Main Skill definition and workflow triggers
├── README.md                                # Project documentation and usage guide
├── references/
│   ├── paper-corpus.md                      # 12 representative research papers metadata & DOI
│   ├── writing-style-analysis.md            # Empirical deconstruction of top-tier biomedical papers
│   ├── introduction-patterns.md             # 5-paragraph introduction funnel & fillable templates
│   ├── results-patterns.md                  # 6-step results unit & claim-driven subsection titles
│   ├── discussion-patterns.md               # 5-part discussion blueprint & evidence bounding
│   └── academic-language-guide.md           # High-precision verb matrix & epistemic calibration
└── examples/
    ├── introduction-rewrite.md              # Parkinson's disease (PD) brain organoid introduction rewrite
    ├── results-rewrite.md                   # Pathological phenotyping & NLRP3 rescue results rewrite
    └── discussion-rewrite.md                # Mechanistic synthesis & limitation assessment rewrite
```

---

## 🚀 How to Use

### 1. In AI Assistants (Claude, ChatGPT, Gemini, Cursor)
Copy the contents of `SKILL.md` into your custom system instructions, Agent prompt, or `.cursorrules` / `.github/copilot-instructions.md`.

### 2. Five Operational Scenarios
- **Scenario 1: Draft from Scratch**: Provide background notes, experimental assays, and raw data; the engine generates structured sections.
- **Scenario 2: Manuscript Rewrite**: Supply an existing draft; the engine reorganizes paragraph flow and elevates language while freezing scientific facts.
- **Scenario 3: Storyline Construction**: Input figure panels and captions; the engine maps out the optimal multi-act Results narrative.
- **Scenario 4: Peer-Review Audit**: Run draft text through the engine to catch causal over-extrapolations, loose topic sentences, or ungrounded claims.
- **Scenario 5: Grant Proposals**: Apply the funnel structure to Specific Aims and Research Strategy sections.

---

## 📄 License

MIT License. Free for academic and research use.
