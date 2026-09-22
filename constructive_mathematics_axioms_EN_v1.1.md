# Constructive Mathematics · Axiom Set v1.0 (Five-Layer Constructive Mathematics + Representational Mathematics as a Single Ledger)

**Qin Chao** (ORCID 0009-0006-2000-5644 | JueXiao Information Consulting Center, Xingyi, Guizhou 562400, China)

> **v1.0** (2026-09-21): Full public release of the five layers' 14 axioms + 1 definition + observational axiom G0 (the dimensional construction layer added on top of the v0.1 four-layer draft; first release after every layer's formalization files reached zero `sorry`).
> **v1.1** (2026-09-22): Geometry-layer additions — a G-Ⅱ corollary entry, the "irreversibility of abstract projection" principle (energy form → geometry is a one-way projection: the shape structure survives, the history structure is dropped; evidence chain PR6–PR10, five pre-registered batches, closed by PR11's negative result on axis-family extension, 2026-09-21) + a G-Ⅰ reverse-reading note (note form, not entered into the axiom text); the three axioms G0/G-Ⅰ/G-Ⅱ are kept verbatim, preserving axiom minimalism (fixed by the maintainer 2026-09-18; same precedent as the boundary-four-force G-Ⅲ corollary entry of 2026-09-17).
> **Three-layer granularity**: ① mathematical form layer (formal statements — the working objects of the deductive side) / ② observational-origin layer (plain-language observational semantics + evidence pointers) / ③ system-semantics layer (this system's internal reading of its own notation) **is not in this document**.
> **How to use**: Mathematicians and AIs can start deriving directly from each entry's "Formal statement" without any background in the system; to understand "where this axiom comes from," read the "Observational semantics" and the "Evidence pointers"; inter-layer dependencies are declared as they are; formalization status is labeled truthfully from the perspective of machine-checkability hard criteria (all Lean files at zero `sorry`; anyone may download and re-check).
>
> **Author and AI participation statement**: The observational origins and the axiom seeds are due to Qin Chao; formal verification, literature-tracing searches, and document preparation were carried out by the AI system of this framework (Wo) — the human–AI division of labor is auditable.

---

## §0. What Constructive Mathematics Is

**Constructive mathematics (a program we call constructive mathematics; its relation to Bishop's constructivism is discussed in our certification standard) = mathematical construction whose axioms are induced from observation, whose universe of objects grows by self-construction, and from which standard mathematics can be derived as a special case.** Its distinction from standard mathematics (whose axioms are postulates) sits at the observational-origin layer: each axiom carries an "Observational semantics" (which face of reality it was induced from). The four construction modes split two ways: first-order construction (making objects within a universe: the number layer / the motion layer) and second-order construction (constructing the possible universe of objects itself: the relation layer / the geometry layer — de-constraint axioms delimit the universe, and structure emerges spontaneously). The membership criteria (observational origin / independence pre-check / self-construction of objects / special-case crown / self-sufficiency layering / machine-checkability / provenance cross-check) and the certification services are given in the *General Standard of Constructive Mathematics*.

## §1. Number layer · Density mathematics (first-order construction; self-sufficient in statics)

**A1 Existence**
- Formal statement: A mathematical object is a pair (m, p) — m∈ℝ⁺ (mass, a positive scalar), p a normalized nonnegative distribution (shape), ∫p dx=1. Objects are not given by prior symbols; they are defined by distributions in space.
- Observational semantics: A number is a thing gathered together — first comes the accretion in space (a clump with a total amount and a distribution), then the sign humans give it. A number is not an abstract label; it has two faces, "how big" and "how distributed."
- Evidence pointers: The Pythagorean pebble-array tradition (number = spatial arrangement of pebbles); Husserl's *Philosophy of Arithmetic* (1891), collective union (Inbegriff ≈ total amount / figural moment ≈ distribution); number sense in cognitive science (quantity representation in infants and animals precedes symbols).

**A2 Non-reducibility to Zero**
- Formal statement: m>0 holds unconditionally; the mass zero point is unreachable. Algebraic consequence: the object algebra has no nilpotent elements (a reduced ring).
- Observational semantics: Things do not vanish to zero on their own — a gathered amount can shrink, but it cannot get to zero.
- Evidence pointers: The 1/a divergence wall in the dynamics (the zero point is a mathematically necessary forbidden zone); the ubiquitous observation that clusters do not vanish spontaneously.

**A3 Merging (addition)**
- Formal statement: ⊕: (m₁,p₁)⊕(m₂,p₂)=(m₁+m₂, (m₁p₁+m₂p₂)/(m₁+m₂)) — superposition of distributions, mass conservation (a commutative semigroup).
- Observational semantics: Two clumps become one — totals add, distributions blend together.
- Evidence pointers: Superposition and composition of physical quantities (density mixing / probability mixing).

**A4 Resonance (multiplication)**
- Formal statement: ⊗: (m₁,p₁)⊗(m₂,p₂)=(m₁m₂⟨p₁,p₂⟩, p₁p₂/⟨p₁,p₂⟩) — new mass = product of the masses × overlap of the distributions (the L² inner product); the distributions are multiplied and normalized.
- Observational semantics: Only overlap resonates — two clumps resonate only where their distributions overlap, and the resonance strength = the degree of overlap.
- Evidence pointers: The Bhattacharyya coefficient (probability theory) / quantum wavefunction overlap ⟨ψ|φ⟩ (an isomorphism) / resonance phenomena.

**A7 Dynamics**
- Formal statement: The object parameters are themselves dynamical variables, and evolution is governed by the constrained equation m̈−μ(1−m²)ṁ+k(m−1/m)=D_m∇²m (nonlinear restoring force + parameter-dependent damping + spatial diffusion; m=1 is a globally asymptotically stable equilibrium, m→0 is a divergence wall).
- Observational semantics: Numbers breathe — a gathered amount is not dead; it has its own rhythm of rise and fall, decaying toward equilibrium but never vanishing.
- Evidence pointers: The ubiquity of damped oscillations; dual verification by numerics + analysis (RK4 / energy balance).

## §2. Motion layer · Statics-as-manifestation theory (first-order construction; self-sufficient + one cross-system citation)

**D0 Spontaneous dynamics**
- Formal statement: The system's dynamical equations are autonomous — no explicit time term, no external input term, no observer term; the chain of explanation terminates inside the system's structure.
- Observational semantics: The system's motion grows out of itself — the cause of the motion lies in the structure and is not sought outside. What needs explaining is "why this form," not "why it moves."
- Evidence pointers: The no-driver theorem (machine verification of the autonomy of all 13 basic equations passed); vacuum zero-point fluctuations in quantum field theory (the ground state never stops); an equilibrium point is a living steady state, not dead stillness.

**D1 Simultaneity**
- Formal statement: All dynamics is two-way coupling — the two components (aggregating type × diverging type) never appear singly; the isolated existence of one-sided dynamics is not allowed (the decomposition of a force always contains both a restoring and a dissipative component).
- Observational semantics: Two opposite tendencies are always on stage together — there is no change with only "dispersal" and no "gathering," nor one with only "gathering" and no "dispersal"; the two appear as a pair.
- Evidence pointers: The two-component structure of the restoring–dissipative force decomposition; measured two-way coupling terms (~5%); the repeated manifestation of strong–weak combinations of two opposite tendencies (2×2) across six domains.

**D2 Observability of Ratios**
- Formal statement: Observable functionals take values in scale-equivalence classes (ratios) — absolute quantities are unobservable; any single real-valued projection is necessarily lossy (a continuous injection ℝ²→ℝ does not exist), and the minimal complete observation basis of a two-way system is two ratio readings.
- Observational semantics: Only "proportions" can be observed — without a reference object you cannot state absolute size; to read a two-way varying system completely you need at least two readings.
- Evidence pointers: The four-fundamental-force formulas contain zero occurrences of absolute quantities (their structure is consistent with this axiom); the joint reconstruction error of the two ratios is 4.97e-16 (machine verification); Brouwer's invariance-of-domain theorem (a continuous injection ℝ²→ℝ does not exist, 1912 — theorem-grade external compulsion).

**[Citation statement]** E Unique Real Existence (ontological monism) — a cross-system citation, not an independent axiom of this layer; the source is given in the system's General Outline (not released with this document).

## §3. Relation layer · Spontaneous ratio structures (second-order construction; self-sufficient in statics / dynamics borrows the base layers)

**1a Objects**
- Formal statement: The object space is Λⁿ=(0,∞)ⁿ (n-dimensional positive real vectors, with a multiplicative group structure); component values carry no preset restrictions.
- Observational semantics: No preset values — any positive value at any position is allowed to exist; the world of ratios has no forbidden zone.
- Evidence pointers: The multiplicative-group algebraic structure (taking logarithms yields an additive group); the very origin of the construction is "no value is preset and any value may exist."

**1b Dimension**
- Formal statement: The dimension n is arbitrary (defined for all n≥1); no particular dimensionality is preset.
- Observational semantics: No preset dimension — the ratio of two things, of three things, of n things: one and the same construction.
- Evidence pointers: Machine verification of the five criteria passed in full for the n=4,5 dimensional extensions.

**2a Operations (level generation)**
- Formal statement: Coordinate quotients generate levels — a first-order ratio = a component; a k-th order ratio = successive coordinate quotients of the components; the independent second-order ratios have n−1 degrees of freedom (chain constraint: any cross-dimensional second-order ratio = the product of the other two).
- Observational semantics: Ratios of ratios — taking ratios of the original ratios again and again grows levels, but the levels are not arbitrary: they have an intrinsic chain rule.
- Evidence pointers: Machine verification of the sign identities for the chain constraint / scale separation / empty ratio.

**2b Symmetry (a definition, not an axiom)**
- Definition: The shape space is Λⁿ/(ℝ⁺×Sₙ) — global rescaling and permutation of components count as the same shape (the Weyl chamber Aₙ₋₁ as fundamental domain).
- Observational semantics: Shape is separated from size — scale the whole up or down, permute the order of the components, and the "shape" counts as the same one.
- Evidence pointers: The structure-map theorem (spherical = a measure-zero center / symmetric = a measure-zero line / generic position = complete breaking; mutually-exclusive-and-complete verification over 5000 points); Kendall shape space (an academically isomorphic method, 1984).

**2c Dynamics**
- Formal statement: On the shape space, a spontaneous dynamics is configured (citing the motion layer's D0) together with a constrained-dynamics template (citing the equation form of the number layer's A7); there is no external drive.
- Observational semantics: The world of ratios moves by itself — ratio structures have their own fluctuations, solidification, and latching, with no need for an external push.
- Evidence pointers: The behavioral spectrum of the slider equation / solidification bifurcation / periodic boundaries (numerical verification).

## §4. Geometry layer · Pure abstract geometry (second-order construction; self-sufficient in morphology / environment by default cites motion-layer D0)

**Observational axiom G0**: "the mode of existence of geometric form is boundless motion" (the mode-of-existence reading of the conjunction of the two axioms).

**Axiom 1 G-Ⅰ (The existence and freedom of energy)**
- Formal statement: The system is by default in a spontaneous environment (motion is given as background, not the object of study); there is necessarily an energy input (the existence condition of motion); the energy value is not preset — any energy form and any energy value lie within the axiom's scope, and energy is not a screening condition on form.
- Observational semantics: Shapes live in a world of motion; that world always needs to be fed energy, but any energy will do, any amount will do — form is not hand-picked by energy.
- Evidence pointers: Cross-medium conservation (the same shape law appears in 82+ systems — atmospheric circulation / rocket exhaust plumes / aquatic animals / walking machines — with energy form and scale spanning 9 orders of magnitude while the shape law stays unchanged; conservation rate 62%).

**Axiom 2 G-Ⅱ (The disappearance of boundaries and concreteness)**
- Formal statement: Disappearance of real boundaries — form is characterized not by real boundary conditions (medium interfaces / walls / the concreteness of the energy form) but by intrinsic geometric invariants (the drift-rotation ratio α of the path, the curvature κ, the rate of change of curvature τ, the amplitude ratio axial — differential-geometric invariants that need no external reference). Abstraction = maximization of constraints on concreteness on the basis of motion.
- Observational semantics: Take the concrete boundaries and the energy form away and the shape is still there — what remains is the shape itself, fully stateable in the shape's own quantities (bending, twisting, plumpness or slenderness).
- Evidence pointers: Zero-physics realization generation (purely kinematic paths generate the vortex form — 5/6 reproduced on the rotation side, zero energy form, zero boundaries); the universal measurability of the four intrinsic coordinates across the entire realization domain.


### G-Ⅱ corollary entry (the irreversibility of abstract projection)

- Formal statement: The mapping from energy form to geometric form is a one-way projection; the recoverable domain is the instantaneous shape structure (sign structure / support domain / amplitude distribution), while time-derivative structure (growth rate / frequency / timing) lies outside the domain; the inversion is a many-to-one mapping, and exact recovery is impossible. The collapse rate worsens monotonically as the injection space grows (the projection dimension is fixed).
- Observational semantics: Geometry is an abstract form, not a complete record of energy — geometry keeps "what shape it is now," not "how it came to be that way." So from the shape one can recognize the kind of energy form behind it (partial inversion), but one cannot recover it exactly (many energy forms can grow the same shape). If geometry carried all the information of energy, geometry would not be an abstract form but a faithful copy of the real — irreversibility is the counter-side statement of abstractness itself.
- Evidence pointers: The full chain of five pre-registered experiment batches in the single-organ domain is traceable: PR6 inversion matrix (21 injectors → 11 forms, collapse rate 1.91, three cross-class shared forms) + PR7 strictly monotone collapse curve (nested family 1.00 / 2.615 / 4.933; 18-member multi-solution hypercoiled disk) + PR8 axis-selective survival (os axis 0.833 / lo axis 0.762) + PR9 zero contribution of derivative axes (fc margin exactly zero) + PR10 shape axes (os+kurt = 0.7619, survival list = the three shape axes); the axis-family extension (the second batch of three axes) was tested negative by PR11 — the survival list is closed (2026-09-21). Pointers: `papers/涡几何_PR6~PR11_*`.

### G-Ⅰ reverse-reading note

G-Ⅰ stipulates that the energy value is not preset; its reverse reading (reading the energy-form end from the geometric-form end) is constrained by the G-Ⅱ corollary entry (the irreversibility of abstract projection) — only the shape-structure survival set is partially recoverable, and exact recovery is impossible. This note is not entered into the axiom text (fixed 2026-09-18).

## §5. Dimensional construction (second-order construction; convention / meta-object level)

The object of observation = **dimensionality / the description convention itself** (the convention of dimensionality, its source, its selection criteria, its premises, and its collapse mechanism) — none of the four-member object universe (number / motion-stillness / relational structure / geometric form) covers this object. Paper: *Dimensional Construction: A Mapping Construction for a Target Readout Dimensionality*, DOI 10.5281/zenodo.22844311.

**A'_1 Presupposition-free filling axiom**
- Formal statement: There exists a filling operation σ: for any already-constructed description D, σ(D) is the description obtained by adjoining one new degree of freedom to D; σ does not presuppose the direction, the values, or the dimension count of the new degree of freedom — direction decomposition and dimension counting are a convention layer on top of σ, not part of σ's content.
- Observational semantics: Filling itself has no direction — "a point raised to a line, a line raised to a plane" is three fillings; "three directions" is a decomposition fixed by human convention. Filling precedes direction; direction precedes dimension.
- Evidence pointers: That n-dimensional geometry in mathematics exists self-consistently at the formal layer (an accomplished fact for any dimensionality); the formalization file DimensionAxioms.lean (axiom definitions + model pairs M1-M4).

**A'_2 Simultaneity-premise axiom**
- Formal statement: The filling base acquires the form of an isotropic spatial body (spherical state, with the π characteristic) if and only if two groups of opposite generative tendencies (aggregating type × diverging type) exist simultaneously and sit at a balanced cross-section; remove this premise and the description falls back to the A'_1 base (no preset values, no dimension, no form).
- Observational semantics: The spherical spatial body is not built into filling — it appears only when two opposite tendencies are present together and happen to be exactly even; withdraw the constraint and it slides back to no preset values and no dimension.
- Evidence pointers: A symmetry-breaking example in the layered-media numerical domain (non-equilibrium → anisotropic deformation, PR-L28-L31 record); a cross-layer, same-pattern note on the simultaneity grammar (the same origin grammar as motion-layer D1, a different object universe).

**A'_3 Squeeze-criterion axiom**
- Formal statement: The value of a given perception/readout framework's dimensionality convention = the squeeze equality point between the completeness lower bound of readout dimensionality and the simplicity upper bound of encoding dimensionality of the density-manifestation structure.
- Observational semantics: Perception must be complete (too few and you lose structure), encoding must be minimal (too many and you carry redundancy) — three dimensions are squeezed out between the two bounds; they are not preset by the universe.
- Evidence pointers: The empirical face of the incompleteness of the retina's two-dimensional image (the completeness lower bound); the formalization file DimensionMapping.lean (T_维1: well-definedness of the minimal complete family as a pair of results + the threshold-domain theorem, an eight-line mapping hookup).

**A'_4 Dimensional-collapse criterion axiom**
- Formal statement: The maintenance of dimensional distinctions takes numerical commitment as its necessary-and-sufficient resource: where a maintenance mechanism (commitment) is present the distinction is present; when the mechanism exits, the distinction exits (dimensional collapse), collapsing toward the base description within the conventional framework.
- Observational semantics: Maintaining a high-dimensional distinction requires a continuous investment of "numerical commitment"; when the commitment exits, the distinction exits — the dimensionality that demands no commitment is the default state.
- Evidence pointers: The "commitment–distinction" empirical chain in the 3D numerical domain (192³/256³ resolution records: strengthen the commitment and the maintained distinction strengthens); the formalization file CompletenessMeasure.lean (the ε-completeness dimension dimLE + the interface equation τ=dimLE).

## §6. Representational mathematics · Three-dimensional ratio structures (single ledger — not a member of constructive mathematics)

The axiomatic inputs are given externally (the two-force decomposition of field strength + the three-dimensional decomposition convention), and the objects are not constructed by the axioms — by membership criterion C3 (self-construction of objects, the watershed criterion) this is classified as **representational mathematics**: a representational structure over externally given objects. Its axiomatic inputs and structural theorems (ReprBound, seven formalization pieces at zero `sorry`) are released together with this public version; its genealogical status is listed separately.

## §7. Inter-layer dependency master table (C5 disclosure)

| Layer | Mode | Dependency declaration |
|---|---|---|
| Number layer | first-order | self-sufficient |
| Motion layer | first-order | self-sufficient + [citation] E Unique Real Existence (cross-system statement) |
| Relation layer | second-order | statics (1a/1b/2a/2b) self-sufficient; dynamics (2c) cites motion-layer D0 + number-layer A7 |
| Geometry layer | second-order | self-sufficient in morphology; environment by default cites motion-layer D0 (motion given as background) |
| Dimensional construction | second-order | axioms self-sufficient; A'_2's simultaneity grammar is a cross-layer note (same origin grammar as motion-layer D1, not a theorem dependency); A'_4's empirical chain borrows the 3D numerical realization domain (external realization, not an axiom dependency) |

## §8. Formalization status (C6 hard-criterion perspective, truthful)

| Layer | Formalization files | Status |
|---|---|---|
| Motion layer | Retract.lean (family of manifestation operators, 24 definitions and theorems) | ✅ zero `sorry` |
| Relation layer | SpontRatio.lean (structure map / retrogression-boundary theorems) | ✅ zero `sorry` |
| Geometry layer | VortexGeom.lean (complementary-angle identity / symmetry center / logarithmic reading / special case — four theorems) | ✅ zero `sorry` |
| Number layer | StaticCore.lean (axiom set A1-A4 + core theorem family) | ✅ zero `sorry` (make-up completed 2026-09-16; full-chain symbolic-computation verification with sympy run in parallel) |
| Dimensional construction | DimensionAxioms/DimensionConstruct/DimensionMapping/CompletenessMeasure.lean (axiom definitions + model pairs + decision tree / region covering / mapping mechanism / rate-distortion measure) | ✅ zero `sorry` (8717 jobs) |
| The axiom statements themselves | text extraction from this document | ✅ Lean definition files for the five layers' axiom statements all complete (2026-09-20/21: landed for StaticCore / DynamicLayer / RelationLayer / VortexGeom / DimensionAxioms respectively) |

---

**Related documents**: Certification standard *Constructive Mathematics Certification Standard* v1.2 (DOI 10.5281/zenodo.22867678, criteria and procedures) · Genealogy registration and application (github.com/vortex-QC/constructive-mathematics-standard) · Five member papers (22773691 / 22783549 / 22785052 / 22785851 / 22844311) · Completion precedent *Anchor Number* (DOI 10.5281/zenodo.22866459).

---
*Constructive Mathematics Axiom Set v1.1 | 2026-09-22 | Five layers: 14 axioms + 1 definition + observational axiom G0 (the v1.0 axiom text kept verbatim) + one geometry-layer corollary entry + one reverse-reading note; three-line format for each entry (Formal statement / Observational semantics / Evidence pointers); inter-layer dependencies stated as they are; formalization status all zero `sorry` (Lean 8717 jobs; anyone may re-check); the system-semantics layer is not included in this record (the one-way discipline of the translation layer). DOI 10.5281/zenodo. (this record)*
