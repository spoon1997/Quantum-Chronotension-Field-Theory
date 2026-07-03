# QCFT v2 — Core Assumptions, Definitions, and Open Questions

**Repository role:** Foundational reference document  
**Status:** Working draft  
**Purpose:** Establish the conceptual baseline for Quantum Chronotension Field Theory v2 before detailed mathematics, simulations, or paper rewrites begin.

---

## 0. Purpose of This Document

This file defines what QCFT v2 currently assumes, what it means by its key terms, what remains unresolved, and what must not be overstated.

QCFT v1/CFT developed rapidly and accumulated multiple generations of ideas, some of which remain useful and some of which are likely outdated. QCFT v2 is intended to be a clean restart: not a rejection of the original work, but a disciplined reconstruction.

This document is deliberately written **before** the full mathematical rebuild. Its goal is to prevent conceptual drift.

The guiding rule is:

> QCFT v2 should not preserve ideas because they are elegant, familiar, or emotionally important.
>
> Ideas survive only if they remain internally consistent, mathematically expressible, and compatible with observation.

---

## 1. Working Identity of QCFT v2

Quantum Chronotension Field Theory v2 is an exploratory framework investigating whether gravity, particles, cosmology, quantum behaviour, and black-hole physics can emerge from an underlying temporal field rather than from fundamental spacetime geometry.

The central hypothesis is:

> Time is not merely a coordinate.
>
> Time is the physically real substrate from which spacetime, fields, particles, and gravitational behaviour emerge.

In QCFT v2, the universe is not primarily made of objects moving through spacetime. Instead, apparent objects and spacetime structure are emergent behaviours of an underlying temporal medium.

---

## 2. Current Core Postulates

These are provisional. They are allowed to change, but every major change must be documented.

### Postulate 1 — Temporal Field Primacy

There exists a fundamental temporal field, originally denoted:

\[
\eta(x,t)
\]

which describes the local temporal density, resistance, viscosity, or tension of the underlying physical substrate.

In QCFT v2, the raw \(\eta\) field may not be the best physical variable. A transformed field, denoted:

\[
\sigma
\]

may be more fundamental for dynamics.

---

### Postulate 2 — Bounded Temporal Density

The temporal field has an upper saturation boundary:

\[
0 \leq \eta < \eta_*
\]

where \(\eta_*\) is the Cann boundary.

This means temporal density cannot become infinite.

Physical singularities are therefore not fundamental objects in QCFT v2. They are interpreted as failures of an older effective description.

---

### Postulate 3 — The Physical Field-Space Distance May Be \(\sigma\)

A candidate transformation is:

\[
\rho = \frac{\eta}{\eta_*}
\]

\[
\sigma = \operatorname{artanh}(\rho)
\]

so that:

\[
0 \leq \rho < 1
\]

but:

\[
\sigma \rightarrow \infty
\quad\text{as}\quad
\rho \rightarrow 1
\]

This makes the Cann boundary unreachable in finite field-space distance.

This is conceptually similar to the way massive objects may approach but never reach the speed of light.

---

### Postulate 4 — Gravity Emerges from Temporal Gradients

Gravitational behaviour is not fundamental curvature.

Instead, gravity emerges from gradients in the temporal field.

Older QCFT used:

\[
\text{Gradia} = |\nabla \eta|
\]

QCFT v2 may require:

\[
\text{Gradia} = |\nabla \sigma|
\]

This is a major point requiring careful investigation.

If \(\sigma\)-Gradia is correct, ordinary weak-field gravity should remain approximately unchanged when:

\[
\eta \ll \eta_*
\]

because then:

\[
\sigma \approx \eta/\eta_*
\]

But near the Cann boundary, gravity-like behaviour may become much stronger without producing true singularities.

---

### Postulate 5 — Spacetime Is Emergent

Spacetime geometry is not fundamental.

Metric behaviour arises as an effective description of temporal-field structure.

A previous QCFT metric ansatz was:

\[
ds^2 = -\frac{dt^2}{\eta^2(x,t)} + \eta^2(x,t)\,dx^i dx^i
\]

QCFT v2 must re-evaluate this metric in terms of \(\sigma\), not simply reuse the old form uncritically.

Required question:

> Is the effective metric controlled by raw \(\eta\), by \(\sigma\), or by another derived quantity?

---

### Postulate 6 — Particles Are Topological Chronode Structures

Particles are not fundamental point-like objects.

They are stable or metastable topological excitations of the temporal field.

These excitations are called:

> **Chronodes**

Chronodes may correspond to localized knots, windings, shells, twists, or defects in the temporal field.

Particle identity is expected to arise from topology, winding, internal symmetry, and environmental stability.

---

### Postulate 7 — Local Vacuum Conditions Determine the Accessible Particle Spectrum

Particle properties may depend on the local background state of the temporal field.

In calm local vacuum:

\[
\eta \approx \eta_0
\]

or:

\[
\sigma \approx \sigma_0
\]

This yields the familiar low-energy particle spectrum observed in our region.

In extreme environments, such as near Field Collapse Events or very high Gradia regions, different chronode resonances may become accessible.

This is not yet proven. It is a guiding hypothesis.

---

### Postulate 8 — Black Holes Are Field Collapse Events, Not Singularities

QCFT v2 rejects physical singularities.

A black-hole-like object is interpreted as a:

> **Field Collapse Event (FCE)**

where matter/field structure compresses toward the Cann boundary:

\[
\eta \rightarrow \eta_*
\]

but never crosses it.

The resulting finite-density high-\(\eta\) structure is called a:

> **Cann Shell**

This shell may store information topologically and may replace the classical singularity.

---

### Postulate 9 — Vacuum Energy May Represent Temporal Field Stiffness

The large vacuum energy predicted by conventional QFT may be reinterpreted as energy stored in the local temporal medium.

In this view, QFT is not detecting literal particles constantly appearing and disappearing. Instead, it may be probing the stiffness, viscosity, or stored potential of the local \(\eta\)-field vacuum.

This must be handled carefully because of the cosmological constant problem.

QCFT v2 likely requires:

> Absolute temporal-field energy does not gravitate directly.
>
> Gradients, curvature of field-space, or changes in the field do.

---

### Postulate 10 — QCFT Must Recover Known Physics Before Replacing It

QCFT v2 is not allowed to merely explain anomalies.

It must recover the successful limits of:

- Newtonian gravity
- General Relativity
- Quantum Field Theory
- The Standard Model
- Black-hole thermodynamics
- Observational cosmology

Only then can it claim to supersede or reinterpret them.

---

## 3. Key Definitions

### 3.1 \(\eta\)

The original temporal viscosity/tension field.

Possible meanings include:

- temporal density
- resistance to temporal change
- local time-flow impedance
- substrate compression
- vacuum temporal viscosity

In QCFT v2, \(\eta\) should be treated as a bounded raw field.

---

### 3.2 \(\eta_*\)

The maximum temporal-density boundary.

\[
\eta < \eta_*
\]

This boundary is called the Cann boundary.

It replaces the old idea of arbitrarily high \(\eta\) or infinite compression.

---

### 3.3 \(\rho\)

A dimensionless normalized temporal-density field:

\[
\rho = \frac{\eta}{\eta_*}
\]

with:

\[
0 \leq \rho < 1
\]

---

### 3.4 \(\sigma\)

The proposed physical field-space coordinate:

\[
\sigma = \operatorname{artanh}(\rho)
\]

This turns the finite interval:

\[
0 \leq \rho < 1
\]

into the infinite interval:

\[
0 \leq \sigma < \infty
\]

The key reason to introduce \(\sigma\) is that the Cann boundary becomes unreachable by finite field displacement.

---

### 3.5 Gradia

The effective gravitational driver.

Old definition:

\[
\text{Gradia} = |\nabla \eta|
\]

Candidate QCFT v2 definition:

\[
\text{Gradia} = |\nabla \sigma|
\]

This is one of the most important conceptual upgrades to test.

---

### 3.6 Chronode

A localized topological excitation of the temporal field.

Candidate physical interpretations:

- particle
- antiparticle
- resonance
- field knot
- topological defect
- stabilized winding mode

Chronodes are expected to replace fundamental particles in QCFT v2.

---

### 3.7 Cann Boundary

The upper temporal-density limit:

\[
\eta \rightarrow \eta_*
\]

This is not a material wall. It is a field-space boundary.

The boundary should make infinite density, infinite curvature, and singular collapse physically inaccessible.

---

### 3.8 Cann Shell

A finite-density high-\(\eta\) shell formed when collapse approaches the Cann boundary.

Cann Shells are candidate replacements for black-hole singularities.

They may encode information in shell microstates or chronode topology.

---

### 3.9 Field Collapse Event

A black-hole-like collapse process in QCFT.

Instead of producing a singularity, collapse produces a saturated temporal-field structure.

Abbreviation:

> FCE

---

### 3.10 Local Temporal Vacuum

The approximately homogeneous background temporal-field state in our region of the universe.

Most known particle physics should be derived in this calm local vacuum limit.

---

## 4. What QCFT v2 Currently Claims Only Provisionally

These are not established results. They are working hypotheses.

### 4.1 Charged Lepton Hierarchy

A repaired candidate model is:

\[
m_n = m_e n^2 \exp\left[\chi(n-1)^{3/5}\right]
\]

with:

\[
n=1,2,3
\]

corresponding to:

\[
e,\mu,\tau
\]

Interpretation:

- \(n^2\) arises from winding/torsion energy.
- \(3/5\) arises from balancing inverse-square winding compression against three-dimensional Cann resistance.
- \(\chi\) is the local Cann stiffness/action parameter.

This gives the tau mass within roughly a few percent when \(\chi\) is fixed by the muon.

Status:

> Promising but not yet a first-principles derivation.

---

### 4.2 Three Generations

QCFT v2 should not assume an arbitrary cutoff at three generations.

A better hypothesis is:

> The local temporal vacuum supports only the first few observable chronode resonances.

Higher winding states may be too unstable, too broad, or inaccessible under calm local \(\eta\) conditions.

This requires lifetime and stability analysis.

---

### 4.3 Dark Matter Replacement

QCFT proposes that some dark-matter-like effects arise from Gradia structure rather than unseen matter.

Status:

> Conceptually promising, but must pass galaxy, cluster, lensing, Bullet Cluster, CMB, and structure-formation tests.

---

### 4.4 Dark Energy Replacement

QCFT may replace dark energy with global temporal-field evolution or field-tension behaviour.

Status:

> Highly speculative. Must be rebuilt carefully in QCFT v2.

---

### 4.5 Cosmological Redshift

Older QCFT proposed redshift from temporal-field evolution rather than metric expansion.

A possible form was:

\[
1+z \sim \exp\left(\int \frac{d\eta}{\eta}\right)
\]

QCFT v2 must revisit this.

If \(\sigma\) is the true field-space variable, redshift may depend on:

\[
d\sigma = \frac{d\rho}{1-\rho^2}
\]

Status:

> Important but unresolved.

---

### 4.6 Eternal Finite Universe

Later QCFT discussions favoured an eternal but finite universe rather than a classical origin event.

This may fit better with a bounded temporal field.

Status:

> Conceptually attractive but not yet mathematically established.

---

## 5. Known Weaknesses and Required Repairs

### 5.1 The Old Quartic Cann Potential Is Inadequate

Old form:

\[
V(\eta)=\lambda(\eta^2-\eta_*^2)^2
\]

Problem:

This does not create a true Cann ceiling.

It creates a preferred value, not an unreachable boundary.

QCFT v2 should replace it with either:

1. A field-space boundary, or
2. A divergent stiffness, or
3. A strong nonlinear soliton-stabilizing sector.

Recommended direction:

\[
\sigma=\operatorname{artanh}(\eta/\eta_*)
\]

with divergent field-space distance at \(\eta_*\).

---

### 5.2 Topological Sector Needs Rebuilding

Some old QCFT expressions for field strength cancel algebraically or are not sufficient.

A better direction is the emergent connection:

\[
A_\mu^{ab}
=
\eta^a\partial_\mu\eta^b
-
\eta^b\partial_\mu\eta^a
\]

or the corresponding \(\sigma\)-based version.

QCFT v2 must define:

- the internal field space
- the connection
- the curvature
- conserved topological charges
- the relation to gauge groups

---

### 5.3 Standard Model Recovery Is Not Yet Derived

QCFT v1 contains useful mappings to:

\[
SU(3)\times SU(2)\times U(1)
\]

but QCFT v2 must distinguish:

- resemblance
- mapping
- derivation

A true derivation must recover the actual group structure, charges, couplings, and particle multiplets.

---

### 5.4 Cosmology Is Underdeveloped

QCFT v2 must not claim cosmological success until it can address:

- Hubble law
- supernova time dilation
- CMB blackbody spectrum
- CMB acoustic peaks
- BAO scale
- primordial nucleosynthesis
- structure formation
- lensing maps
- large-scale isotropy and anisotropy

Cosmology is probably QCFT’s hardest sector.

---

### 5.5 Quantization Is Incomplete

QCFT v2 needs a clear quantization procedure.

Possible routes:

- canonical quantization of \(\sigma\)
- path integral over temporal-field configurations
- quantization of chronode collective coordinates
- topological quantization

Unresolved requirements:

- spin
- statistics
- exclusion principle
- antimatter
- uncertainty
- wavefunction behaviour
- scattering amplitudes

---

### 5.6 Black-Hole Thermodynamics Must Be Quantitative

Cann Shells are conceptually strong, but QCFT v2 must eventually derive:

\[
S = \frac{kA}{4l_P^2}
\]

\[
T_H = \frac{\hbar c^3}{8\pi GMk}
\]

or show precisely why the classical formulas are modified.

---

### 5.7 Claims Must Be Graded

Every QCFT v2 statement should be labelled as one of:

- **Postulate**
- **Definition**
- **Derived**
- **Fitted**
- **Numerically supported**
- **Speculative**
- **Rejected / superseded**

This is essential to prevent QCFT v2 from inheriting overclaims from QCFT v1.

---

## 6. Immediate Development Priorities

### Priority 1 — Conceptual Gap Discussion

Before mathematics, discuss the following:

1. What is \(\eta\) physically?
2. Is \(\sigma\) the true dynamical field?
3. What does it mean for time to be viscous?
4. Does absolute \(\eta\) matter, or only gradients?
5. Why do gradients produce gravity?
6. How can particles be topological structures?
7. What determines whether a chronode is stable?
8. How does environment affect particle spectra?
9. What is the relationship between vacuum energy and temporal stiffness?
10. How does QCFT avoid contradicting precision particle physics?

---

### Priority 2 — QCFT v2 Lagrangian

Develop one canonical action.

Candidate structure:

\[
\mathcal L_{\rm QCFT2}
=
\mathcal L_{\rm grad}
+
\mathcal L_{\rm boundary}
+
\mathcal L_{\rm top}
+
\mathcal L_{\rm interaction}
\]

Required properties:

- bounded temporal density
- stable solitons
- topological charges
- emergent gauge behaviour
- weak-field gravity limit
- quantization path

---

### Priority 3 — Lepton Sector

Use the charged-lepton hierarchy as the first serious worked example.

Tasks:

1. Formalize chronode winding number \(n\).
2. Derive \(n^2\) winding energy.
3. Derive \(3/5\) compression exponent.
4. Define \(\chi\) from QCFT parameters.
5. Test electron/muon/tau.
6. Study \(n\ge4\) resonance stability.
7. Compare predicted lifetimes with known muon/tau behaviour.

---

### Priority 4 — Gravity Recovery

Tasks:

1. Define Gradia using \(\sigma\).
2. Recover Newtonian inverse-square behaviour.
3. Recover gravitational time dilation.
4. Recover lensing.
5. Compare with weak-field GR.
6. Identify where QCFT deviates.

---

### Priority 5 — Black Holes / FCEs

Tasks:

1. Define Cann Shell equilibrium.
2. Show collapse halts before singularity.
3. Derive horizon-like behaviour.
4. Derive entropy scaling.
5. Address Hawking radiation and information preservation.

---

### Priority 6 — Cosmology Rebuild

Do not begin with the full CMB.

Start with:

1. redshift law
2. distance-redshift relation
3. supernova time dilation
4. BAO interpretation
5. CMB spectrum
6. CMB peaks

Cosmology should be rebuilt only after the field and gravity sectors are stable.

---

## 7. Research Discipline Rules

### Rule 1 — No Claim Without Status

Do not write:

> QCFT derives X.

unless X is actually derived.

Use:

- suggests
- models
- may explain
- reproduces under assumptions
- derives in limit
- fitted to
- predicts

accurately.

---

### Rule 2 — Existing Physics Must Be Respected

QCFT v2 may reinterpret existing physics, but it cannot casually discard successful results.

If QCFT replaces expansion, it must still explain what expansion explained.

If QCFT replaces dark matter, it must still explain what dark matter explained.

If QCFT replaces point particles, it must still explain scattering.

---

### Rule 3 — Prefer Narrow Wins

Do not try to solve the whole universe at once.

Work on constrained targets:

- lepton hierarchy
- weak-field lensing
- Cann Shell equilibrium
- redshift law
- one gauge group at a time

---

### Rule 4 — Preserve Failure Modes

Failed derivations should be documented, not hidden.

A failed derivation is useful because it tells QCFT v2 what not to assume.

---

### Rule 5 — Separate Theory from Psychology

QCFT is not a personal verdict on its author.

The theory can fail, evolve, or partially survive without that reflecting on Luke’s worth or ability.

The goal is not to defend the theory.

The goal is to find out what survives.

---

## 8. Suggested Repository Structure

```text
QCFT-v2/
│
├── README.md
├── LICENSE
├── QCFT_Legal_Notice.md
│
├── 00_Foundation/
│   ├── QCFT_v2_Assumptions.md
│   ├── Terminology.md
│   ├── Status_Legend.md
│   └── Open_Questions.md
│
├── 01_Lagrangian/
│   ├── Candidate_Action.md
│   ├── Field_Equations.md
│   └── Conserved_Quantities.md
│
├── 02_Gravity/
│   ├── Gradia.md
│   ├── Newtonian_Limit.md
│   ├── GR_Weak_Field.md
│   └── Lensing.md
│
├── 03_Particles/
│   ├── Chronodes.md
│   ├── Lepton_Hierarchy.md
│   ├── Spin_and_Statistics.md
│   └── Generations.md
│
├── 04_Gauge_Structure/
│   ├── Emergent_Connection.md
│   ├── U1.md
│   ├── SU2.md
│   └── SU3.md
│
├── 05_Black_Holes/
│   ├── Field_Collapse_Events.md
│   ├── Cann_Shells.md
│   └── Thermodynamics.md
│
├── 06_Cosmology/
│   ├── Redshift.md
│   ├── BAO.md
│   ├── CMB.md
│   └── Structure_Formation.md
│
├── 07_Predictions/
│   ├── Falsifiable_Tests.md
│   └── Observational_Comparisons.md
│
└── Archive/
    └── QCFT_v1_Notes/
```

---

## 9. First Conceptual Questions to Discuss

These should be talked through before doing heavy mathematics.

1. Is \(\eta\) a substance, a field, a resistance, or a field-space coordinate?
2. Is \(\sigma\) merely mathematical convenience, or the true physical variable?
3. Does time flow through \(\eta\), or is time identical with \(\eta\)?
4. Does absolute temporal viscosity matter?
5. Why does spatial variation in temporal viscosity produce attraction?
6. What prevents chronodes from dispersing?
7. What prevents chronodes from collapsing?
8. Is particle mass stored temporal tension?
9. Is vacuum energy the background temporal stiffness?
10. Why is our local vacuum calm and homogeneous?
11. Why are particle constants so stable locally?
12. Do extreme \(\eta\) environments allow exotic particles?
13. What is the physical meaning of a Cann Shell surface?
14. Does information live on the shell, in the shell, or in topology?
15. Is cosmological redshift path-dependent?
16. Can a finite eternal universe avoid entropy problems?
17. Does QCFT need an arrow of time, or does it derive one?
18. What would falsify QCFT quickly?

---

## 10. Current Strategic Focus

QCFT v2 should begin with:

1. Ontology cleanup.
2. \(\sigma\)-field decision.
3. Canonical Lagrangian.
4. Lepton hierarchy as first worked particle test.
5. Gradia/gravity recovery.
6. Cann Shell black-hole model.
7. Cosmology only after the above stabilizes.

The purpose of QCFT v2 is not to declare a completed Theory of Everything.

The purpose is to build a framework strong enough that its successes and failures can be clearly identified.

---

## 11. Plain-English Summary

QCFT v2 currently stands as a promising but incomplete attempt to rebuild physics from a temporal substrate.

Its strongest ideas are:

- bounded temporal density
- no true singularities
- particles as topological chronodes
- gravity as temporal-field gradients
- black holes as Cann Shells
- vacuum energy as temporal stiffness

Its weakest areas are:

- complete mathematical action
- full Standard Model recovery
- quantization
- cosmology
- CMB/BAO/nucleosynthesis

The immediate goal is not to prove QCFT right.

The immediate goal is to make QCFT precise enough that it can be tested, repaired, or falsified.

---

## 12. Status

This document is not final.

It should be updated whenever QCFT v2 changes its foundational assumptions.

Every major revision should record:

- what changed
- why it changed
- what old idea it replaced
- what new problems it creates
- what new predictions it enables

