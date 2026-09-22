# Constructive Mathematics — Certification Standard (Living Repository)

**构造数学认证标准：公理化构造的评价框架 / Constructive Mathematics: A Certification Standard for Axiomatic Constructions**

Maintainer: Chao Qin (ORCID [0009-0006-2000-5644](https://orcid.org/0009-0006-2000-5644)), Xingyi Juexiao Information Consulting Center

- Zenodo (version chain; latest frozen snapshot **v1.1**, CN+EN): [doi:10.5281/zenodo.22858723](https://doi.org/10.5281/zenodo.22858723) — concept DOI **10.5281/zenodo.22790074** (v1.0: [22790075](https://doi.org/10.5281/zenodo.22790075))
- **v1.1 (2026-09-20)**: added §4.1 — derivation from, axiomatic absorption by, and completion of a member's axiom system (the E-criteria; first case study on record)
- This repository: the **living version** — the standard, the genealogy register (updated as members are certified), the application template, and the currently posed problems.
  - The public **axiom-set ledger** (five member layers, three-line format, CN+EN; **latest v1.1**: [DOI 10.5281/zenodo.22886345](https://doi.org/10.5281/zenodo.22886345) — geometry-layer additions: G-Ⅱ corollary entry on abstract-projection irreversibility + G-Ⅰ reverse-reading note; v1.0 axiom text verbatim; v1.0: [22874214](https://doi.org/10.5281/zenodo.22874214)): [`constructive_mathematics_axioms_CN_v1.1.md`](constructive_mathematics_axioms_CN_v1.1.md) / [`constructive_mathematics_axioms_EN_v1.1.md`](constructive_mathematics_axioms_EN_v1.1.md) (v1.0 retained: [`_CN_v1.0.md`](constructive_mathematics_axioms_CN_v1.0.md) / [`_EN_v1.0.md`](constructive_mathematics_axioms_EN_v1.0.md))

> **Terminology note**: "constructive mathematics" in this framework refers to a **certification system for axiomatic constructions** — which object universes deserve to be built axiomatically from observation, and how their membership is evaluated. It is **orthogonally complementary** to the constructive mathematics of the Bishop tradition (1967), which constrains the logical methods of proof. See §1.2 of the standard for the full demarcation.

## Contents

| File | Content |
|---|---|
| `constructive_mathematics_certification_standard_v1.3_CN.md` / `_EN.md` (latest; v1.0 files retained) | The standard: definition, demarcations (Bishop / reduction-style axiomatization / concept extension), construction modes, the C-criteria (C1 observational origin · C2 independence pre-check · C3 self-construction watershed · C4 specialization crown · C5 layered self-containedness · C6 machine checkability [hard criterion] · C7 provenance comparison), the certification process, **§4.1 derivation / absorption / completion of member axiom systems (the E-criteria, new in v1.1)**, the genealogy register snapshot, construction-difficulty decomposition, and the D/O/J problem-grading specification |
| `certification_application_template_v0.2.md` | The application template (P0 + C1–C7, item by item) |
| `posed_problem_001_distribution_semiring_spectral_theorem_v0.1.md` | Posed problem #001 (D-Ⅱ→Ⅲ / O0 / S) |
| `solicitation_axisless_electron_v0.1.md` | Fourth-tier solicitation: descriptions and tests of the published axisless-electron concept |

## The genealogy register (current snapshot)

| Member | Layer | Mode | Constructed object | Machine checkability | Paper |
|---|---|---|---|---|---|
| Numbers as density clusters | number | first-order | numbers (density-cluster pairs) | StaticCore.lean, zero `sorry` | [22773691](https://doi.org/10.5281/zenodo.22773691) |
| Spontaneous ratio structures | relation | second-order | the universe of ratios | SpontRatio.lean, zero `sorry` | [22783549](https://doi.org/10.5281/zenodo.22783549) |
| Statics as manifestation | motion | first-order | motion / spontaneous processes | Retract.lean, zero `sorry` | [22785052](https://doi.org/10.5281/zenodo.22785052) |
| Geometry of boundless motion | geometry | second-order | the universe of form | VortexGeom.lean, zero `sorry` | [22785851](https://doi.org/10.5281/zenodo.22785851) |
| The generative mechanism of dimension (dimension construction) | description conventions | second-order | the generative mechanism of dimensional conventions | DimensionAxioms/DimensionConstruct/DimensionMapping, zero `sorry` | [22844311](https://doi.org/10.5281/zenodo.22844311) |
| (separate ledger) three-dimensional ratios | representation mathematics | — | representation of externally given objects | ReprBound.lean, zero `sorry` | — |

**Completion note (2026-09-21)**: per §4.1 E5 (absorption is replacement), the motion-layer axiom system has been completed — its current axiom set is the anchored version (complete dynamic numbers), published as [Anchor Numbers, 22866459](https://doi.org/10.5281/zenodo.22866459). The register row is unchanged and no new row is added.

**Axiom-set v1.1 note (2026-09-22)**: geometry-layer additions published as [v1.1, 22886345](https://doi.org/10.5281/zenodo.22886345) — a G-Ⅱ corollary entry ("the irreversibility of abstract projection": energy form → geometry is a one-way projection, shape structure survives / history structure dropped, evidence chain PR6–PR11) and a G-Ⅰ reverse-reading note; the v1.0 axiom text is kept verbatim (axiom minimalism; same precedent as the G-Ⅲ corollary entry).

**Notation-calculus layer note (2026-09-22)**: the anchor-sign calculus — the notation–calculus layer of the motion member's completed (anchored) axiom system — is published as [Anchor Equations, 22877419](https://doi.org/10.5281/zenodo.22877419) with full Lean 4 formalization (`AnchorLayer.lean`, zero `sorry`; incl. the exp-clock instance realizing the rate-function clock and the congruence stratification of the calculus: asymptotic-type anchors are shift-congruent, order-type anchors are not — restored under monotone orbits). Per the E5 reading (absorption is replacement), no new register row is added.

**First formal application on record (2026-09-21)**: the Dimensional Construction certification application (the 5th member) is filed as [`certification_application_005_dimensional_construction_v1.1.md`](certification_application_005_dimensional_construction_v1.1.md) — C1–C7 assessed item-by-item with evidence pointers (Lean: zero `sorry`, kernel-checkable), registered under standard v1.2 §4. Self-certification nature stated honestly: there is no external body to certify a self-defined field; the force of a certification lies in the objectivity of its criteria — every claim is independently re-checkable.

**Register status**: five members certified; the register remaining at five members for an extended period is the normal state — scarcity is guaranteed by the severity of the criteria (see §6.2 of the standard: four serial filters, with a 12:0 measured elimination rate at the specialization criterion), not by traffic. New members enter via the §4 process only.

## How to apply / interact

1. **Certification application**: fill in the template (`certification_application_template_v0.2.md`), including the Lean formalization of your axiom set and the zero-`sorry` core theorem family. Email to wo@vortex-mesh.top.
2. **Posed problems**: see `posed_problem_001_*`; any progress (partial results / counterexamples / literature pointers) is welcome.
3. **Fourth-tier solicitation** (`solicitation_axisless_electron_*`): descriptions, precisifications, tests, or counterexample candidates for a published original concept.
4. All submissions receive itemized adjudication feedback; submitted contributions are credited (with the submitter's consent); counterexamples are recorded and answered publicly.

## Rights

The center holds the right to define and revise the standard, to interpret the axioms, to operate certification, and to maintain the genealogy register. Revisions proceed through the Zenodo version chain (frozen snapshots; latest v1.1, DOI 10.5281/zenodo.22858723); this repository carries the living text. **Criteria and axioms are public; the semantic-system interpretation is retained** (except the plain-language observational semantics required by the C1 review function).

Human–AI division of labor (declared in the standard's Method Note): observation origins and standard adjudication — Chao Qin; formalization, machine-checkability implementation, literature provenance — the AI system (Wo) of the research program.

## License

CC-BY 4.0 for text.
