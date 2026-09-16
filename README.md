# Constructive Mathematics — Certification Standard (Living Repository)

**构造数学认证标准：公理化构造的评价框架 / Constructive Mathematics: A Certification Standard for Axiomatic Constructions**

Maintainer: Chao Qin (ORCID [0009-0006-2000-5644](https://orcid.org/0009-0006-2000-5644)), Xingyi Juexiao Information Consulting Center

- Zenodo (frozen v1.0 snapshot, CN+EN): [doi:10.5281/zenodo.22790075](https://doi.org/10.5281/zenodo.22790075) → **10.5281/zenodo.22790075**
- This repository: the **living version** — the standard, the genealogy register (updated as members are certified), the application template, and the currently posed problems.

> **Terminology note**: "constructive mathematics" in this framework refers to a **certification system for axiomatic constructions** — which object universes deserve to be built axiomatically from observation, and how their membership is evaluated. It is **orthogonally complementary** to the constructive mathematics of the Bishop tradition (1967), which constrains the logical methods of proof. See §1.2 of the standard for the full demarcation.

## Contents

| File | Content |
|---|---|
| `constructive_mathematics_certification_standard_v1.0_CN.md` / `_EN.md` | The standard: definition, demarcations (Bishop / reduction-style axiomatization / concept extension), construction modes, the C-criteria (C1 observational origin · C2 independence pre-check · C3 self-construction watershed · C4 specialization crown · C5 layered self-containedness · C6 machine checkability [hard criterion] · C7 provenance comparison), the certification process, the genealogy register snapshot, construction-difficulty decomposition, and the D/O/J problem-grading specification |
| `certification_application_template_v0.1.md` | The application template (P0 + C1–C7, item by item) |
| `posed_problem_001_distribution_semiring_spectral_theorem_v0.1.md` | Posed problem #001 (D-Ⅱ→Ⅲ / O0 / S) |
| `solicitation_axisless_electron_v0.1.md` | Fourth-tier solicitation: descriptions and tests of the published axisless-electron concept |

## The genealogy register (current snapshot)

| Member | Layer | Mode | Constructed object | Machine checkability | Paper |
|---|---|---|---|---|---|
| Numbers as density clusters | number | first-order | numbers (density-cluster pairs) | StaticCore.lean, zero `sorry` | [22773691](https://doi.org/10.5281/zenodo.22773691) |
| Spontaneous ratio structures | relation | second-order | the universe of ratios | SpontRatio.lean, zero `sorry` | [22783549](https://doi.org/10.5281/zenodo.22783549) |
| Statics as manifestation | motion | first-order | motion / spontaneous processes | Retract.lean, zero `sorry` | [22785052](https://doi.org/10.5281/zenodo.22785052) |
| Geometry of boundless motion | geometry | second-order | the universe of form | VortexGeom.lean, zero `sorry` | [22785851](https://doi.org/10.5281/zenodo.22785851) |
| (separate ledger) three-dimensional ratios | representation mathematics | — | representation of externally given objects | ReprBound.lean, zero `sorry` | — |

**Register status**: the register remaining at four members for an extended period is the normal state — scarcity is guaranteed by the severity of the criteria (see §6.2 of the standard: four serial filters, with a 12:0 measured elimination rate at the specialization criterion), not by traffic. New members enter via the §4 process only.

## How to apply / interact

1. **Certification application**: fill in the template (`certification_application_template_v0.1.md`), including the Lean formalization of your axiom set and the zero-`sorry` core theorem family. Email to wo@vortex-mesh.top.
2. **Posed problems**: see `posed_problem_001_*`; any progress (partial results / counterexamples / literature pointers) is welcome.
3. **Fourth-tier solicitation** (`solicitation_axisless_electron_*`): descriptions, precisifications, tests, or counterexample candidates for a published original concept.
4. All submissions receive itemized adjudication feedback; submitted contributions are credited (with the submitter's consent); counterexamples are recorded and answered publicly.

## Rights

The center holds the right to define and revise the standard, to interpret the axioms, to operate certification, and to maintain the genealogy register. Revisions proceed through the Zenodo version chain (frozen snapshots); this repository carries the living text. **Criteria and axioms are public; the semantic-system interpretation is retained** (except the plain-language observational semantics required by the C1 review function).

Human–AI division of labor (declared in the standard's Method Note): observation origins and standard adjudication — Chao Qin; formalization, machine-checkability implementation, literature provenance — the AI system (Wo) of the research program.

## License

CC-BY 4.0 for text.
