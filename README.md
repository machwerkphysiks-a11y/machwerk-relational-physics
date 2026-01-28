# MACHWERK  
## Formal Conditions of Physical Admissibility

**MACHWERK** is a formally closed framework for defining the conditions under which
physical statements, equations, and models are **admissible, comparable, and
meaningfully interpretable**.

This repository contains the **formal mathematical core** of MACHWERK.

The framework is fully developed and published as a printed monograph:

> **MACHWERK — Formale Bedingungen physikalischer Beschreibbarkeit**  
> Author: Stefan Schwarz 
> ISBN: 979-8-24410-846-0
> Platform: Amazon.com (Print-on-Demand)  
> Release date: February 1, 2026
> 
This GitHub repository does **not** replace the book.  
It provides the **machine-readable, axiomatic kernel** underlying it.

---

## What MACHWERK Is

MACHWERK is a **formal meta-framework** for physics.

It defines:
- relational state spaces
- projection operators
- domains of validity
- loss of injectivity (boundary conditions)
- admissibility criteria for physical statements

MACHWERK does **not** introduce new particles, forces, fields, or dynamics.

Instead, it answers a prior question:

> **Under which formal conditions is a physical statement well-defined at all?**

Only after these conditions are fixed does conventional physics become meaningful.

---

## What MACHWERK Is Not

- not a competing physical theory  
- not an interpretation of quantum mechanics  
- not a numerical simulation or solver  
- not speculative or narrative philosophy  

No experimental claims are asserted here.

No ontological commitments are imposed.

All established physical theories remain **fully valid within their
respective domains of applicability**.

---

## Why This Repository Exists

The printed book contains:
- conceptual motivation
- formal development
- derivations
- applications (Parts A–E)
- physical examples and boundary analyses

This repository contains **only the formal kernel**, stripped of:
- prose
- interpretation
- examples
- didactic explanation

The purpose of this repository is to make the framework:

- **machine-readable**
- **algorithmically inspectable**
- **formally auditable**
- **usable for derivation and consistency checks**

This separation is intentional.

---

## Rechenbarkeit / Calculability

MACHWERK is **not descriptive**.  
It is **operational**.

The formal core defines:
- operators
- mappings
- domains
- fixpoints
- admissibility constraints

These structures **can be used for calculation**, derivation, and validation of
physical models.

What is restricted is **not computation**, but **uncontrolled interpretation**.

If a statement cannot be uniquely related back through the defined projections,
it is **formally inadmissible as a physical statement**, even if mathematically valid.

---

## Core Concepts (Formal)

The formal kernel is organized bottom-up:

1. **Relational Full Space (U-space)**  
   A non-geometric, non-temporal relational reference domain.

2. **Projection (Π)**  
   Mapping from relational configurations into observable calculation spaces.

3. **Injectivity & Invertibility**  
   Conditions under which projections preserve distinguishability.

4. **Validity Domains (m₂)**  
   Domains in which physical statements remain uniquely interpretable.

5. **Boundary Conditions (Σ, Δ₀)**  
   Formal markers for loss of injectivity and non-recoverable residues.

6. **Fixpoint Criteria**  
   Recursive stability conditions for admissible statements.

7. **CRA Axiom (Consistency of Relational Applicability)**  
   A global consistency constraint governing admissibility.

Each concept is defined in a **single, self-contained formal file**.

---

## Structure of This Repository

This repository is intentionally non-linear.

Each file defines exactly one formal concept.
No file assumes definitions that appear later.

Recommended reading order:

- `u_space.tex`
- `projection_definition.tex`
- `projection_operator.tex`
- `injectivity_and_invertibility.tex`
- `m2_definition.tex`
- `black_boundary_sigma.tex`
- `delta_zero.tex`
- `fixpoint_m2.tex`
- `cra_axiom.tex`

---

## Relation to the Book

The book applies this formal kernel to:

- dimensional emergence
- limits of spacetime descriptions
- quantum correlations
- gravitational boundaries
- cosmological edge cases
- relational process dynamics (TRD)

These **applications are deliberately not duplicated here**.

This repository provides the **ground truth** against which those applications
can be reconstructed, verified, or rederived.

---

## Intended Audience

- theoretical physicists
- mathematicians
- logicians
- computer scientists
- AI researchers working with formal reasoning systems

This repository assumes familiarity with:
- formal logic
- abstract mathematical structures
- non-narrative specification styles

It is **not** a tutorial.

---

## License

© Author

Creative Commons BY-NC-ND 4.0  
Redistribution of unchanged copies permitted for non-commercial purposes.  
No derivatives.

---

## Keywords (for indexing)

theoretical physics  
foundations of physics  
formal physics  
meta-framework physics  
relational physics  
projection operators  
limits of observability  
injectivity loss  
non-invertible mappings  
formal boundary conditions  
physical admissibility  
consistency axioms  
process-based physics  
non-geometric models  
post-spacetime physics  
formal reasoning systems  
machine-readable physics  
AI physics kernels
