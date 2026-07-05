QCFT Core Equation Set (Foundation Draft)
Version: QCFT vNext Foundation
Author: Luke Cann
Purpose

This document defines the minimum mathematical core currently believed necessary to reproduce the entire QCFT framework.

The intention is that these equations eventually occupy the same role as:

Einstein's field equations in General Relativity.
The Standard Model Lagrangian in particle physics.

Everything else in QCFT should ultimately emerge from these equations rather than being added separately.

1. Fundamental Ontology

QCFT assumes only one truly fundamental physical entity:

η
a
(x
μ
)

The η-field.

Everything else emerges from it:

Phenomenon	QCFT Interpretation
Time	Local η density
Gravity	Gradia (η gradients)
Matter	Stable η topology
Charge	Topological winding
Black holes	Cann density shells
Cosmological expansion	Evolution of background η
Dark matter	Persistent η tension
Dark energy	Background η evolution
2. η Field Decomposition

The η field is decomposed into:

η
a
(x
μ
)=ρ(x
μ
)n
a
(x
μ
)
	​


where:

Density component
ρ(x
μ
)

represents:

local η density,
local clock rate,
gravitational potential.
Orientation component
n
a
(x
μ
)

represents:

internal topology,
charge,
spin,
particle structure.

Subject to:

n
a
n
a
	​

=1
	​


ensuring only orientation changes, not magnitude.

3. Cann Density

QCFT assumes a maximum physically attainable η density:

ρ
C
	​

	​


Interpretation:

not a hard cutoff,
not a discontinuity,
not a singularity,

but an infinite stiffness limit.

Physical systems may approach:

ρ
C
	​


arbitrarily closely but never reach or exceed it.

This replaces:

GR singularities,
infinite curvature,
divergent densities.
4. η Stiffness Function

η resists compression increasingly strongly near Cann density.

Current candidate:

K(ρ)=
(1−ρ/ρ
C
	​

)
2
K
0
	​

	​

	​


Properties:

Weak field:
ρ≪ρ
C
	​


gives:

K(ρ)≈K
0
	​


recovering linear physics.

Strong field:
ρ→ρ
C
	​


gives:

K(ρ)→∞

producing Cann shells naturally.

5. Cann Potential

Current candidate potential:

V
C
	​

(ρ)=
2
1
	​

m
η
2
	​

(ρ−ρ
0
	​

)
2
+Λ[
1−ρ/ρ
C
	​

1
	​

−
1−ρ
0
	​

/ρ
C
	​

1
	​

−
ρ
C
	​

(1−ρ
0
	​

/ρ
C
	​

)
2
ρ−ρ
0
	​

	​

]
	​


This construction guarantees:

Vacuum stability
V
C
	​

(ρ
0
	​

)=0

and

V
C
′
	​

(ρ
0
	​

)=0

meaning the cosmological background density is stable.

Cann protection
V
C
	​

(ρ)→∞

as

ρ→ρ
C
	​


preventing singular collapse.

6. Internal Curvature Tensor

Internal topology generates additional energy through curvature.

Define:

H
μν
ab
	​

=∂
μ
	​

n
a
∂
ν
	​

n
b
−∂
ν
	​

n
a
∂
μ
	​

n
b
	​


Interpretation:

winding density,
internal curvature,
topological tension.

This term stabilises chronodes against collapse.

7. QCFT Master Lagrangian

Current candidate master Lagrangian:

L
QCFT
	​

=
2
1
	​

K(ρ)(∂
μ
	​

ρ)(∂
μ
ρ)+
2
1
	​

ρ
2
(∂
μ
	​

n
a
)(∂
μ
n
a
	​

)−V
C
	​

(ρ)−
4
κ
	​

ρ
4
H
μν
ab
	​

H
ab
μν
	​

+L
source
	​

	​


Interpretation of terms:

Term	Meaning
K(ρ)(∂ρ)
2
	Gradia energy
ρ
2
(∂n)
2
	Orientation energy
V
C
	​

(ρ)	Cann resistance
ρ
4
H
2
	Topological curvature
L
source
	​

	Matter sourcing
8. η Density Field Equation

Variation with respect to:

ρ

gives:

∂
μ
	​

(K(ρ)∂
μ
ρ)−
2
1
	​

K
′
(ρ)(∂
μ
	​

ρ)(∂
μ
ρ)−ρ(∂
μ
	​

n
a
)(∂
μ
n
a
	​

)+V
C
′
	​

(ρ)+κρ
3
H
μν
ab
	​

H
ab
μν
	​

=J
ρ
	​

	​


This is the QCFT equivalent of Einstein's field equations.

9. Orientation Equation

Variation with respect to:

n
a

subject to:

n
a
n
a
	​

=1

gives schematically:

∂
μ
	​

(ρ
2
∂
μ
n
a
	​

+κρ
4
H
a
μ
	​

)=λ
n
	​

n
a
	​

	​


This governs:

chronodes,
charge,
spin,
topology.
10. Time Rate Relation

Local clock rates emerge from η density:

dt
dτ
	​

=T(ρ)=
1−
ρ
C
	​

−ρ
0
	​

ρ−ρ
0
	​

	​

	​

	​


Properties:

Background universe
ρ=ρ
0
	​


gives:

dτ=dt
Cann shell
ρ→ρ
C
	​


gives:

dτ→0

meaning time effectively freezes.

11. Weak Field Matching

For weak gravity:

ρ(r)−ρ
0
	​

=2(ρ
C
	​

−ρ
0
	​

)
rc
2
GM
	​

	​


This recovers:

dt
dτ
	​

≈1−
rc
2
GM
	​


which matches GR gravitational time dilation.

12. Effective Weak Field Metric

QCFT reproduces the GR weak field metric:

ds
2
=−c
2
(1−2ϵ)dt
2
+(1+2ϵ)d
x
2
	​


where:

ϵ=
rc
2
GM
	​


This reproduces:

Newtonian gravity,
gravitational redshift,
lensing,
weak-field Schwarzschild behaviour.
13. Current Development Status
Locked

✅ η decomposition

✅ Cann density interpretation

✅ Stiffness divergence

✅ Candidate master Lagrangian

✅ Candidate field equations

In Development

🟡 Derivation of Newtonian gravity directly from field equations.

🟡 Derivation of lensing from η optics.

🟡 Derivation of cosmological evolution equation.

Untouched

🔴 Stable chronode solutions.

🔴 Charge derivation.

🔴 Spin derivation.

🔴 Lepton generations.

🔴 Gauge structure.

Summary

QCFT currently proposes:

The universe consists only of η.

Matter is trapped topology.

Gravity is η tension.

Time is η density.

Black holes are Cann shells.

Cosmology is η evolution.

The entire remaining task of QCFT is therefore:

Determine whether these equations reproduce reality.
	​


If they do, the rest of physics becomes a problem of solving the equations rather than inventing new entities.
