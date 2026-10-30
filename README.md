# dbtm
Boundary-First framework in which information processing begins with contextualized differences rather than symbols. Detectable differences generate salience, salience induces boundary formation, boundaries produce topological structures, and meaning emerges from the resulting topology.





DBTM
Difference–Boundary–Topology–Meaning Theory

A Boundary-First framework for information processing.

Traditional language models assume that meaning emerges from symbolic units such as characters, words, or tokens.

DBTM proposes an alternative hypothesis:

Plain Text
Difference
↓
Salience
↓
Boundary
↓
Topology
↓
Meaning
 

Instead of treating symbols as the primitive objects of cognition, DBTM treats contextualized differences as the primary source of information.

Vision

Current AI systems are largely built upon tokenized representations.

Plain Text
Character
↓
Token
↓
Sentence
↓
Meaning

However, spoken language, biological perception, and neural processing appear to operate differently.

Neural systems are highly sensitive to:

changes
discontinuities
boundaries
salient events

DBTM explores the hypothesis that information processing begins from detectable differences rather than predefined symbols.

Core Principle

DBTM is based on the following emergence chain:

Plain Text
Difference
↓
Salience
↓
Boundary
↓
Topology
↓
Meaning

Where:

Stage	DescriptionDifference	Observable change
Salience	Context-normalized importance
Boundary	Structural discontinuity
Topology	Organization induced by boundaries
Meaning	Semantic interpretation emerging from topology
Mathematical Formulation
Difference

Given observations

x1,x2,…,xTx_1,x_2,\dots,x_Tx1​,x2​,…,xT​

define:

dt=δ(xt,xt−1)d_t = \delta(x_t,x_{t-1})dt​=δ(xt​,xt−1​)

where δ\deltaδ is a distance metric.

Context
ct=Φ(x<t)c_t=\Phi(x_{<t})ct​=Φ(x<t​)

where ctc_tct​ denotes contextual state.

Salience
st=dtθ(ct)s_t = \frac{d_t} {\theta(c_t)}st​=θ(ct​)dt​​

where

θ(ct)\theta(c_t)θ(ct​)

is a context-dependent expectation threshold.

Interpretation:

Plain Text
Salience
=
Observed Difference
/
Expected Difference
Event
et=1(st>τe)e_t = \mathbf{1}(s_t>\tau_e)et​=1(st​>τe​)
Boundary
bt=1(st>τb)b_t = \mathbf{1}(s_t>\tau_b)bt​=1(st​>τb​)

or

bt=1(st=max⁡k∈N(t)sk)b_t = \mathbf{1} \left( s_t = \max_{k\in N(t)} s_k \right)bt​=1(st​=k∈N(t)max​sk​)
Topology
T=g(B)\mathcal T=g(B)T=g(B)

Topology is induced by boundary organization.

Meaning
M=h(T)M=h(\mathcal T)M=h(T)

Meaning emerges from topology.

Axioms
Axiom 1: Difference Primacy

Observable information begins as differences.

Axiom 2: Contextual Salience

The significance of a difference depends on context.

Axiom 3: Event Emergence

Salient differences generate events.

Axiom 4: Boundary Emergence

Boundaries emerge from organized events.

Axiom 5: Topological Emergence

Topology emerges from boundaries.

Axiom 6: Meaning Emergence

Meaning emerges from topology.

DBTM and Information Flow Processing

DBTM is currently being explored through Information Flow Processing (IFP).

Conventional routing:

rij=softmax(Aij)r_{ij} = softmax(A_{ij})rij​=softmax(Aij​)

DBTM routing:

rij=softmax(Aij+λPij)r_{ij} = softmax ( A_{ij} + \lambda P_{ij} )rij​=softmax(Aij​+λPij​)

where

Pij=−BoundaryCost(i,j)P_{ij} = -\mathrm{BoundaryCost}(i,j)Pij​=−BoundaryCost(i,j)

Boundary structure dynamically modulates information flow.

Salience-Driven Routing

Traditional prosody-aware systems treat prosody as an additional feature.

Plain Text
Token + Prosody

DBTM proposes a different view:

Plain Text
Prosody
↓
Difference
↓
Salience
↓
Boundary
↓
Routing Control
 

Prosody is not a feature.

Prosody is a boundary-generation process.

Research Directions
Phase 1

DBTM Theory

Phase 2

DBTM-IFP

Phase 3

DBTM-MRPA

Phase 4

DBTM-GNST

Phase 5

DBTM-LLINGTOPOL

Fundamental Statement

Meaning does not fundamentally emerge from symbols.

Meaning emerges from topology induced by contextualized differences.

これは GitHub README としてかなり読みやすく、同時に arXiv 論文の Introduction と Theory セクションにそのまま発展できる構成です。さらに私は Repo のトップに次の図を置くことを強く勧めます。

Plain Text
Difference
↓
Salience
↓
Boundary
↓
Topology
↓
Meaning
↘
Routing (IFP)
