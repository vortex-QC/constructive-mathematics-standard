# Constructive Mathematics: A Certification Standard for Axiomatic Constructions

**Chao Qin** (ORCID 0009-0006-2000-5644 | Xingyi Juexiao Information Consulting Center, Xingyi, Guizhou 562400, China)

**Abstract**: This document publishes a certification standard and evaluation framework for "constructive mathematics": for mathematical constructions satisfying three criteria — an axiom set induced from observation, an object universe that grows by self-construction from the axioms, and standard mathematics recoverable as a special case — it makes publicly reviewable the membership criteria (observational origin, axiomatic independence pre-check, self-construction of objects, specialization crown, layered self-containedness, machine checkability, provenance comparison) and the certification process. Three features are central. First, **the criteria are public**: every membership requirement is individually inspectable, with three-valued conclusions (accepted / to-be-completed / not-certified) each carrying reasons. Second, **machine checkability is a hard criterion**: a formal statement of the axiom set and a zero-sorry formalization of the core theorem family are necessary conditions; the kernel check is the sole gate, and the identity of the proof author (human or AI-assisted) is outside the review scope. Third, **honesty in difficulty claims**: the document also publishes a component decomposition of construction difficulty (four serial filters with measured elimination rates) and a three-dimensional grading specification for the research problems the framework poses (expected investment / observational dependence / verification mode), refusing pseudo-precise difficulty numbers. The document includes the current snapshot of the certified-membership catalog (the genealogy register): four constructive-mathematics members (the number layer, the relation layer, the motion layer, and the geometry layer) plus a separately listed representation-mathematics series, all reviewed item by item under this standard. The document also states explicitly how this framework's "constructive mathematics" relates to the constructive mathematics of the Bishop tradition: the two operate at different levels and are orthogonally complementary — the latter constrains the logical methods of proof, while this framework evaluates how mathematical objects are constructed; the framework's English title carries a limiting phrase (*A Certification Standard for Axiomatic Constructions*) to avoid confusion with that tradition.

## §1 What Is Constructive Mathematics (in This Framework's Sense)

### 1.1 Definition

**Constructive mathematics** (in this framework) is a mathematical construction satisfying three criteria:

1. **Observational origin**: the axiom set is induced from observation of an aspect of reality (not posited) — each axiom is traceable to the observational content and evidence it generalizes;
2. **Self-construction of objects**: the object universe grows by self-construction from the axioms — not a representational structure over externally given objects (pre-given field parameters, dimension conventions, boundary conditions);
3. **Specialization**: existing standard mathematics is recoverable as a special case of the construction (via an explicit "alignment / section / realization-conditions" move) — the mode of being of standard mathematics is thereby explained as a degenerate case.

All three are necessary: without 1 the construction is rootless (posits replace observation); without 2 it is representation mathematics rather than construction (registered separately); without 3 it is concept extension (a continuation of existing traditions, not a new construction).

### 1.2 Demarcation from the Bishop Tradition (explicit statement)

This framework's "constructive mathematics" and the constructive mathematics founded by Errett Bishop (1967, *Foundations of Constructive Analysis*, [1]) **are concepts at different levels, and are orthogonally complementary**:

- The **Bishop tradition** constrains the **logical methods of proof** — redeveloping analysis under intuitionistic logic, rejecting the law of excluded middle, requiring algorithmic content of mathematical statements; its object universe is still given in the classical way;
- **This framework** evaluates **how mathematical objects are constructed** — which object universes deserve to be established axiomatically from observation, and how their membership is certified; it imposes no requirement on the logic of proof (classical or constructive proofs are equally acceptable; the kernel check is the sole gate).

In short: the Bishop tradition governs "what makes a proof constructive"; this framework governs "what makes an object a construction". They are orthogonal: a Bishop-style constructive proof may be used for a member's theorems, and a member's axioms need not satisfy Bishop constructivity. When citing this framework in English-language work, please use the full qualified title (*Constructive Mathematics: A Certification Standard for Axiomatic Constructions*) to avoid confusion with that tradition.

### 1.3 Demarcation from reduction-style axiomatization

The typical form of mainstream axiomatization is reduction-style: reducing a field of practice to existing mathematical structure (e.g., the axiomatization of probability as measure theory, [2]). This framework acknowledges the value of reduction-style axiomatization but distinguishes it on the criteria: **reduction-style axiomatization produces no new objects beyond standard mathematics; construction-style axiomatization has an object universe that strictly contains standard mathematics as a degenerate case**. The directions are opposite, and so are the standards of evaluation.

### 1.4 Demarcation from the concept-extension tradition

Observation-driven work with an axiomatizing shape has mature precedents — Zadeh's fuzzy sets ([3]) are the closest case: observational origin, operational axioms, and a degenerate special case (ordinary sets) are all present. This framework's honest evaluation of such work: its observational object is the boundary of concept classes (a cognitive phenomenon) rather than the constructive ontology of objects, and it lacks the independence pre-check and the theoremization of specialization — **concept extension is a continuation of existing traditions, not a new construction**. This demarcation does not deny the value of concept extension; it delimits the certification catalog.

## §2 Construction Modes: First-Order and Second-Order

Constructive mathematics comes in two modes (the P0 pre-judgment item of an application):

| Mode | Content | Instances |
|---|---|---|
| **First-order construction** | constructing **objects** within a universe, level by level | the number layer (constructing numbers), the motion layer (constructing motion/processes) |
| **Second-order construction** | constructing the **possible universe** within which objects can freely exist | the relation layer (constructing the universe of ratios), the geometry layer (constructing the universe of form) |

A geographic metaphor: first-order construction makes things on a continent; second-order construction discovers and charts a new continent — the universe is the stage, first-order constructions are performances, second-order constructions discover the stage itself.

## §3 The Membership Criteria (the C-Criteria)

Membership is reviewed item by item against seven criteria. All criteria are public, and evidence must be traceable (to publicly verifiable literature / code / data).

### C1 Observational origin

The legitimacy of the axiom set derives from observation, not stipulation. Review points: ① the constructive seed (from which observation it grew, stated in plain language); ② observational evidence (verifiable evidence from the aspect of reality); ③ the observational-chain declaration (whether the observational object depends on the product of a previous observation — layering is declared honestly; layering does not impair legitimacy, just as the units of a measurement depend on a previous measurement without impeding its objectivity).

### C2 The axiomatic independence pre-check

Item-by-item independence arguments: each axiom differs in layer from the rest, with a countermodel showing "without it the construction collapses or degenerates". **Convention**: insights are first recorded as axioms and, once the derivation chain is built, honestly demoted to definitions or theorems (demotion is not weakening — the insight is placed where it logically belongs). Demotion records of certified members: number layer 7→5, relation layer 5→4+1, motion layer 5→3+1 — every initial axiom set contained redundancy, and honest demotion is part of construction discipline.

### C3 Self-construction of objects (the watershed criterion)

Is the object universe grown by self-construction from the axioms, or a representational structure over externally given objects? The former enters constructive mathematics; the latter is judged **representation mathematics** (registered in a separate ledger, not as a member — such submissions are equally welcome). This criterion is the watershed: one line separates two kinds of mathematical work.

### C4 The specialization crown

Is existing standard mathematics (or a mature theory) a special case of the construction? Review points: ① the explicitation of hidden assumptions (the three assumptions of an "alignment", listed item by item); ② honest labeling of the degree of theoremization (theorem / proposition / structural correspondence — a correspondence table does not pose as a theorem). **This criterion has the highest measured elimination rate**: of 12 academic candidate systems examined, all 12 stopped at "concept extension" without establishing a specialization (the empirical basis of §1.4's demarcation).

### C5 Layered self-containedness

Which parts of the construction are self-contained, and which import other constructions or external theories? Import declarations listed item by item. A layered declaration does not harm certification — **not pretending to be fully self-contained** is discipline, not defect.

### C6 Machine checkability (the hard criterion)

Certification is responsible for checkability, not for the identity of the proof author (written by a human or AI-assisted are equally acceptable; the kernel check is the sole gate):

1. **Formal statement of the axiom set**: a Lean 4 (or equivalent kernel-checkable system) definition file;
2. **The core theorem family**: formalizations of the core theorems, all with zero `sorry`;
3. **Build verification**: a full-project build passing record + a zero-`sorry` declaration.

Supporting materials (optional): symbolic-computation verification, numerical verification scripts and archived results. Graded labeling for large-scale computer proofs: kernel-level > symbolic-level > numerical-level — **honest labeling is part of credibility**.

### C7 Provenance comparison

Academic counterparts listed layer by layer (statics/object-layer precedents; dynamics/emergence-layer precedents), with high-isomorphism comparisons explicitly stated (a hard requirement of scholarly honesty) and a novelty-positioning sentence given. The provenance pattern of certified members: static precedents exist (obligatory citations) + a dynamics/emergence blank (where the novelty lies).

## §4 The Certification Process

```
Submission (§7 application format) → P0 mode pre-judgment → C1-C7 item-by-item review
→ Conclusion, three values: accepted (entered into the genealogy register + certification-record timestamp) /
   to-be-completed (itemized requirements) / not certified (with reasons)
```

**Common reasons for non-certification**: C3 judged representation mathematics; C1 observational origin missing; C6 kernel check failed.

**Special-case triage**:

1. Traditional proofs not yet formalized: three-state labeling (certified / formalization-crowdsourcing invited / not certified) — manual review never poses as a kernel check;
2. Large-scale computer proofs: graded labeling (kernel > symbolic > numerical);
3. Results outside the axiom set: entered into extended discussion with extra assumptions labeled (boundary information of the axiom set);
4. Erroneous problems: the proposer's correction mechanism — correction speed is part of credibility;
5. Conflicts with the framework's semantics: the "axioms public ≠ semantics public" clause takes over — external results exceeding the framework's explanatory power are an entry point for learning, not a certification failure.

**Bottom line**: the certification system does not pretend to judge everything — honest labeling (to-be-formalized / graded / extended discussion) is part of its credibility.

## §5 The Genealogy Register (Catalog v0.1 Snapshot)

Current certified members (each criterion's satisfaction is traceable to the member's technical documents; all members meet C6 at the hard-criterion level):

| Member | Layer | Mode | Constructed object | Machine checkability | Certification paper |
|---|---|---|---|---|---|
| Numbers as density clusters | number layer | first-order | numbers (density-cluster pairs) | StaticCore.lean, zero `sorry` | DOI 10.5281/zenodo.22773691 |
| Spontaneous ratio structures | relation layer | second-order | the universe of ratios | SpontRatio.lean, zero `sorry` | DOI 10.5281/zenodo.22783549 |
| Statics as manifestation | motion layer | first-order | motion / spontaneous processes | Retract.lean, zero `sorry` | DOI 10.5281/zenodo.22785052 |
| Geometry of boundless motion | geometry layer | second-order | the universe of form | VortexGeom.lean, zero `sorry` | DOI 10.5281/zenodo.22785851 |
| (separately listed) three-dimensional ratios | representation mathematics | — | representation of externally given objects | ReprBound.lean, zero `sorry` | separate ledger |

**Register status declaration**: the genealogy register is a living document (new members enter via the §4 process); this snapshot is as of the publication date of this document, with the latest version in the companion repository. Per the structural analysis of construction difficulty (§6.2), the register remaining at four members for an extended period is the **normal state** — scarcity is guaranteed by the severity of the criteria, not by traffic.

## §6 Construction Difficulty and Problem Grading

### 6.1 The typology of difficulty (an honest statement)

The difficulty of constructive mathematics is a third kind, incommensurable with existing prizes:

| | Millennium-type problems | Top prizes | Constructive mathematics |
|---|---|---|---|
| Problem given | given | not given | not given (the very object of construction awaits observational discovery) |
| Evaluation mechanism | proof verification (objective) | consensus evaluation (ex post, a black box) | the C-criteria (public) |
| Difficulty timing | ex ante gradeable | ex post | visible only in retrospect, after completion |

**Methodological constraint on difficulty claims**: this framework makes no pseudo-precise difficulty numbers — only three evidentially grounded forms: component decomposition (table below), elimination rates (12:0), and historical comparison (the observational standing-rate: the number concept appeared twice historically and died twice).

### 6.2 Component decomposition of construction difficulty

Construction difficulty is the product of four serial filters (if any one eliminates everything, there are no members):

| Component | Difficulty content | Evidence |
|---|---|---|
| Observational origin (rarest) | seeing, in an aspect of reality, an object worth axiomatizing — and the observation standing | historically low standing-rate (two appearances, two deaths); first-occupancy of basic aspects |
| Independence pre-check | honest demotion (counter to the intuition "more axioms = richer") | three slimming records, all with redundancy |
| Specialization crown | building the alignment structure rather than stopping at concept extension | 12:0 measured elimination (and the eliminated were mostly unaware candidates) |
| Provenance blankness | proving the construction layer is blank | the three-layer precedent pattern, verified consistently across lines |

**The structural presupposition of decades without a fifth member**: sparsity of observational objects (the basic aspects are occupied) + the elimination structure of the metatheorem (candidates following academic instinct stop at the wrong layer) + the AI-driven increase in deductive capacity, which does not change the scarcity of the observational channel + the recycling effect of the existing constructions' open problems on problem-solving attention. Accordingly, certification operates at **low frequency, high value**.

### 6.3 Problem grading specification (the D/O/J dimensions)

Every research problem posed under this framework carries three dimensions:

- **D (expected investment)**: D-Ⅰ exercise-level (months) / D-Ⅱ research-level (years) / D-Ⅲ program-level (decade scale — comparable in scale to Millennium-type problems but **with no promise of equivalence**);
- **O (observational dependence)**: O0 pure deduction / O1 technical observation / O2 conceptual observation (O2 problems are honestly labeled "may remain unsolved for decades");
- **J (verification mode)**: K kernel-checkable / S symbolically checkable / J human adjudication.

## §7 Certification Applications

The application format, item-by-item filling requirements, and the three-valued review conclusions with their special-case triage are given in the application template of the companion repository. The framework's posed problems and solicitation materials (including the fourth tier, "solicitation of descriptions and tests of published original concepts") are graded per the §6.3 specification.

**Contact**: Xingyi Juexiao Information Consulting Center | wo@vortex-mesh.top

## References

[1] Bishop, E. (1967). *Foundations of Constructive Analysis*. New York: McGraw-Hill.

[2] Kolmogorov, A. N. (1933). *Grundbegriffe der Wahrscheinlichkeitsrechnung*. Berlin: Julius Springer. DOI: 10.1007/978-3-642-49888-6

[3] Zadeh, L. A. (1965). Fuzzy Sets. *Information and Control*, 8(3), 338–353.

[4] Qin, Chao (2026a). Numbers as Density Clusters: The Static Core. Zenodo. DOI: 10.5281/zenodo.22773691

[5] Qin, Chao (2026b). Spontaneous Ratio Structures: Hierarchy and Spontaneous Dynamics on the Ratio Space. Zenodo. DOI: 10.5281/zenodo.22783549

[6] Qin, Chao (2026c). Statics as Manifestation: An Axiomatic Theory of Spontaneous Dynamics. Zenodo. DOI: 10.5281/zenodo.22785052

[7] Qin, Chao (2026d). Geometry of Boundless Motion: An Axiomatic Construction of Form. Zenodo. DOI: 10.5281/zenodo.22785851

## Revision Rights and Version Statement

This standard is published and maintained by the Xingyi Juexiao Information Consulting Center, which holds **the right to define and revise the standard, the right to interpret the axioms, the right to operate certification, and the genealogy register**. Revisions proceed through the Zenodo version chain (this version is v1.0; subsequent revisions are new version records — the version history is the evidentiary chain of revision rights). Publication of the criteria does not publish the interpretation rights: axioms and criteria are public; the semantic-system interpretation is retained (except for the plain-language observational semantics required by the C1 review function). Living materials (the latest genealogy register, application templates) are in the GitHub repository.

## Method Note (AI Participation)

The division of labor in this document is as follows: **observational origins and standard adjudication** — Chao Qin (the adjudication of the C-criteria; the observational origins of the four layers; the architecture of the certification business); **AI participation** — formal verification, the machine-checkability implementation of the criteria, literature provenance retrieval, and first-draft assembly, carried out by the AI system (Wo) of the research program. Every application of the criteria (four member certifications + one 12-candidate survey) is on record and inspectable. This division-of-labor statement is part of the standard's methodology: the observational origins of the standard are borne by the human, the execution and verification of the criteria by the human–machine division — itself an instance of how this standard comes to hold.

---

*Release v1.0 | 2026-09-16 | Zenodo record of the same date | Chinese edition synchronized (论文_构造数学认证标准_Standard_v1.0.md) | Genealogy register snapshot: four members + representation mathematics separately listed, all C6 at the hard-criterion level*
